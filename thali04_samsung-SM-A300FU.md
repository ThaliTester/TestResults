#### Test 808075736be4f0c_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-17 13:10:58.170   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
08-17 13:10:58.200   287   287 E SMD     : DCD OFF
,--------- beginning of system
08-17 13:10:59.050  1017  1095 V AlarmManager: waitForAlarm result :4
08-17 13:10:59.050  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
08-17 13:10:59.050  6743  6743 D AndroidRuntime: 
08-17 13:10:59.050  6743  6743 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 13:10:59.060  6743  6743 D AndroidRuntime: CheckJNI is OFF
08-17 13:10:59.060  6743  6743 D AndroidRuntime: readGMSProperty: start
08-17 13:10:59.060  6743  6743 D AndroidRuntime: readGMSProperty: already setted!!
08-17 13:10:59.060  6743  6743 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 13:10:59.060  6743  6743 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 13:10:59.060  6743  6743 D AndroidRuntime: readGMSProperty: end
08-17 13:10:59.060  6743  6743 D AndroidRuntime: addProductProperty: start
08-17 13:10:59.070  2046  2046 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
08-17 13:10:59.130  1017  1539 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 13:10:59.130  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
08-17 13:10:59.130  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:10:59.130  1017  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:10:59.130  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 13:10:59.190  6743  6743 E AffinityControl: AffinityControl: registerfunction enter
08-17 13:10:59.200  4802  4802 D ConnectivityManager: CallingUid : 10011, CallingPid : 4802
08-17 13:10:59.210  1017  1257 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 13:10:59.210  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-17 13:10:59.210  1017  1129 D ConnectivityService: apparently satisfied.  currentScore=60
08-17 13:10:59.210  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-17 13:10:59.210  4802  6752 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 13:10:59.210  6743  6743 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 13:10:59.220  1017  1030 E PersonaManagerService: inState():  stateMachine is null !!
08-17 13:10:59.220  1017  1030 I PersonaManagerService: PersonaId don't exist
08-17 13:10:59.220  1017  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-17 13:10:59.230  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 13:10:59.240  1017  1030 W ActivityManager: mDVFSHelper.acquire()
08-17 13:10:59.250  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 13:10:59.250  1017  1030 D FocusedStackFrame: Set to : 0
08-17 13:10:59.250  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-17 13:10:59.250  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:10:59.250  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:10:59.250  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:10:59.250  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:10:59.270  6756  6756 E Zygote  : MountEmulatedStorage()
08-17 13:10:59.270  6756  6756 E Zygote  : v2
08-17 13:10:59.270  6756  6756 I libpersona: KNOX_SDCARD checking this for 10171
08-17 13:10:59.270  6756  6756 I libpersona: KNOX_SDCARD not a persona
08-17 13:10:59.270  6756  6756 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:10:59.270  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 13:10:59.270  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 13:10:59.270   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-17 13:10:59.280  1017  1030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6756 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 13:10:59.280  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-17 13:10:59.280  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 13:10:59.280  6756  6756 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:10:59.280  6756  6756 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 13:10:59.290  1017  1030 D InputDispatcher: Focused application set to: xxxx
08-17 13:10:59.290  1017  1030 D InputDispatcher: Focus left window: 1484
08-17 13:10:59.290  6743  6743 D AndroidRuntime: Shutting down VM
08-17 13:10:59.290  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 13:10:59.290  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 13:10:59.320  6756  6756 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 13:10:59.320  6756  6756 D ActivityThread: Added TimaKeyStore provider
08-17 13:10:59.330  1017  1257 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-17 13:10:59.330  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 13:10:59.340  1017  1257 D PersonaManager: isKioskContainerExistOnDevice
08-17 13:10:59.370  4802  6771 W DriveInitializer: Background init thread started
08-17 13:10:59.390   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-17 13:10:59.390   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 13:10:59.390  4802  6771 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
08-17 13:10:59.400   257   440 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-17 13:10:59.400   257  5998 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-17 13:10:59.420  1484  1484 V ActivityThread: updateVisibility : ActivityRecord{3d7972a7 token=android.os.BinderProxy@12f581ff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-17 13:10:59.420  1484  1484 D Launcher: onTrimMemory. Level: 20
08-17 13:10:59.470  2046  2046 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
08-17 13:10:59.480  6756  6756 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-17 13:10:59.500  6743  6743 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-17 13:10:59.510  4802  6771 W DriveInitializer: Background init thread ended
,08-17 13:10:59.510  6756  6756 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 463-465)
,08-17 13:10:59.510  6756  6756 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 13:10:59.550  2046  2046 I art     : Explicit concurrent mark sweep GC freed 55752(3MB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 10MB/17MB, paused 1.266ms total 72.140ms
,08-17 13:10:59.560  6756  6756 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13a3f53a}
,08-17 13:10:59.560  6756  6756 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 13:10:59.560  6756  6756 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 13:10:59.590  1017  1257 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:10:59.590  1017  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-17 13:10:59.590  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:10:59.590  1017  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:10:59.600  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:10:59.610  1017  1476 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-17 13:10:59.610  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-17 13:10:59.620  6756  6756 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-17 13:10:59.620  6756  6756 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 13:10:59.630  6756  6756 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 13:10:59.640  1017  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:10:59.640  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-17 13:10:59.640  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:10:59.640  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:10:59.640  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:10:59.670  4802  6783 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-17 13:10:59.670  4802  6783 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-17 13:10:59.670  6756  6756 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 13:10:59.670  6756  6756 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 13:10:59.670  6756  6756 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 13:10:59.670  6756  6756 I Adreno-EGL: Local Branch: 
08-17 13:10:59.670  6756  6756 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 13:10:59.670  6756  6756 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 13:10:59.670  6756  6756 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 13:10:59.710  2046  2046 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 13:10:59.750  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:10:59.750  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:10:59.750  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:10:59.790  6756  6756 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 13:10:59.810  6756  6756 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-17 13:10:59.810  6756  6756 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-17 13:10:59.820  6756  6756 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-17 13:10:59.820  6756  6756 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-17 13:10:59.850  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{3bb96b7 u0 com.test.thalitest/.MainActivity t3}
,08-17 13:10:59.910  1017  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:10:59.910  1017  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-17 13:10:59.910  1017  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:10:59.910  1017  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:10:59.910  1017  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:10:59.960  1017  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:10:59.960  1017  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-17 13:10:59.960  1017  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:10:59.960  1017  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:10:59.960  1017  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:10:59.970  6756  6756 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 13:10:59.990  6756  6756 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 13:10:59.990  1017  1095 V AlarmManager: waitForAlarm result :8
,08-17 13:11:00.000  6756  6756 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 13:11:00.000  6756  6756 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-17 13:11:00.010  6756  6756 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-17 13:11:00.020  6756  6756 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 13:11:00.020  6756  6756 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 13:11:00.030  1017  2092 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:00.030  1017  2092 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:00.030  1017  2092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:00.030  1017  2092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:00.040  1017  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:00.040  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:00.040  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:00.040  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:00.100  6756  6808 D OpenGLRenderer: Render dirty regions requested: true
,08-17 13:11:00.100  1017  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-17 13:11:00.100  1017  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 13:11:00.100  1017  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-17 13:11:00.100  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-17 13:11:00.110  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-17 13:11:00.110  6756  6792 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-17 13:11:00.120  6756  6756 V ActivityThread: updateVisibility : ActivityRecord{e293945 token=android.os.BinderProxy@944daf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-17 13:11:00.120  6756  6756 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 13:11:00.120  6756  6756 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-17 13:11:00.120  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:00.130  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:00.130  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:00.130  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:00.130  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:00.130  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:00.130  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:00.130  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:00.140   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-17 13:11:00.140  6812  6812 E Zygote  : MountEmulatedStorage(),
08-17 13:11:00.140  6812  6812 E Zygote  : v2
08-17 13:11:00.140  6812  6812 I libpersona: KNOX_SDCARD checking this for 10011
08-17 13:11:00.140  6812  6812 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:00.140  1017  1030 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6812 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-17 13:11:00.140  6812  6812 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:00.150  6812  6812 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:00.150  1017  2092 D InputDispatcher: Focus entered window: 6756,
08-17 13:11:00.150  6812  6812 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-17 13:11:00.150  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 13:11:00.150  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 13:11:00.150  6756  6756 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 13:11:00.150  6756  6808 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 13:11:00.160  6756  6808 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-17 13:11:00.160  6756  6808 D OpenGLRenderer: Enabling debug mode 0
,08-17 13:11:00.170  6812  6812 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:00.180  6812  6812 D ActivityThread: Added TimaKeyStore provider
08-17 13:11:00.180  1017  1490 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-17 13:11:00.180  1017  6827 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-17 13:11:00.180  1174  1174 I StatusBar: Icon Only
08-17 13:11:00.180  1174  1174 D PanelView: There is/are notification(s) 
,08-17 13:11:00.200  1017  1047 I ActivityManager: Displayed Component not be shown by security: +850ms (total +6s229ms)
08-17 13:11:00.200  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3bb96b7 u0 com.test.thalitest/.MainActivity t3} time:121152
08-17 13:11:00.200  1017  1047 W ActivityManager: mDVFSHelper.release()
08-17 13:11:00.200  6756  6756 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-17 13:11:00.200  6756  6756 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@944daf time:121158
08-17 13:11:00.210   257  1097 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-17 13:11:00.210   257   440 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-17 13:11:00.210  1888  1888 I SamsungIME: getCurrentCandidateView
08-17 13:11:00.210  6812  6812 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-17 13:11:00.210  6812  6812 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-17 13:11:00.260  6812  6812 I MultiDex: VM with version 2.1.0 has multidex support
08-17 13:11:00.260  6812  6812 I MultiDex: install
08-17 13:11:00.260  6812  6812 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 13:11:00.290  6812  6812 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-17 13:11:00.360  6812  6812 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-17 13:11:00.360  6812  6812 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b2df316: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-17 13:11:00.360  6812  6812 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-17 13:11:00.380  1888  1888 D SamsungIME: Dismiss ExpandCandiate
,08-17 13:11:00.380  6812  6812 D ChimeraCfgMgr: Reading stored module config
,08-17 13:11:00.390  6756  6756 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6756
,08-17 13:11:00.490  6812  6836 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-17 13:11:00.520  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-17 13:11:00.520  6812  6812 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-17 13:11:00.570  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-17 13:11:00.580  1017  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:00.580  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:00.580  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:00.580  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:00.590  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:00.590  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:00.590  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:00.590  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:00.610   282  1006 D WVCdm   : Instantiating CDM.
,08-17 13:11:00.620   282   684 I WVCdm   : CdmEngine::OpenSession
,08-17 13:11:00.620   282   684 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-17 13:11:00.630   282   684 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-17 13:11:00.660   282   684 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-17 13:11:00.660  1888  1888 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 13:11:00.710  1888  1888 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 13:11:00.710   282   684 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-17 13:11:00.710   282   715 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-17 13:11:00.710   282   715 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-17 13:11:00.710   282   715 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-17 13:11:00.730  1888  1888 I SamsungIME: KeybaordView init() : load resources
,08-17 13:11:00.730   282   715 D WVCdm   : PrepareKeyRequest: nonce=1385985981
08-17 13:11:00.740  2046  2046 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=ae859ddc-a1fe-41fe-98c6-799aa294ffba
,08-17 13:11:00.750  1017  1483 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-17 13:11:00.750  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-17 13:11:00.750  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:00.750  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:00.750  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:00.760  1888  1888 I SamsungIME: getCurrentKeyboard
,08-17 13:11:00.760  1888  1888 I SamsungIME: getTextKeyboard
,08-17 13:11:00.770  2046  2046 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 13:11:00.770  2046  2046 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-17 13:11:00.800  4294  4381 I art     : Explicit concurrent mark sweep GC freed 2120(80KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 716us total 30.858ms
,08-17 13:11:00.810  1888  1888 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-17 13:11:00.810  6756  6756 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 13:11:00.820  1017  1257 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:00.820  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:00.820  1017  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:00.820  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:00.910  6756  6833 D jxcore_app_log: JniHelper::setJavaVM(0xb7ddc2b0), pthread_self() = -1204381568
,08-17 13:11:00.920  6756  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 13:11:00.920  6756  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 13:11:00.920  6756  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 13:11:00.920  6756  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 13:11:00.920  6756  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 13:11:00.920  6756  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@255aadc0 added. We now have 1 listener(s)
,08-17 13:11:00.930  6756  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-17 13:11:00.930  6756  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 13:11:00.940  6756  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:00.940  6756  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:00.940  6812  6824 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-17 13:11:00.940  6812  6824 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 13:11:00.940  6812  6824 I System.out: (HTTPLog)-Static: isShipBuild true
08-17 13:11:00.940  6812  6824 I System.out: (HTTPLog)-Thread-1223-424039851: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-17 13:11:00.940  6812  6824 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 13:11:00.940  6756  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e7a009f added. We now have 1 listener(s)
08-17 13:11:00.940  6756  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:00.940   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 13:11:00.940   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 13:11:00.950  6756  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:00.950  6756  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 13:11:00.950  6756  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 13:11:00.950  6756  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 13:11:00.950  6756  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 13:11:00.950  6756  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:00.960  6756  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-17 13:11:00.960  6756  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 13:11:00.960  6756  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:00.960  6756  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:00.960  6756  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:00.960  6756  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:00.960  6756  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:00.960  6756  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:00.960  6756  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:00.960  6756  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:00.960  6756  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 13:11:00.960  6756  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:00.960  6756  6833 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 13:11:00.960  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:00.970  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:00.990  6756  6756 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 13:11:01.000  6812  6824 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 13:11:01.000  6812  6824 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6812, getuid(): 10011
,08-17 13:11:01.130  2046  2216 W GCoreFlp: No location to return for getLastLocation()
,08-17 13:11:01.200   287   287 E SMD     : DCD OFF
,08-17 13:11:01.280  6812  6824 I qtaguid : Untagging socket 33
,08-17 13:11:01.300  1017  3361 D SSRM:n  : SIOP:: AP = 320
,08-17 13:11:01.300  1017  1476 I art     : Explicit concurrent mark sweep GC freed 32364(1679KB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 2.452ms total 156.657ms
,08-17 13:11:01.330  2046  2220 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 13:11:01.340  4802  6801 D UdcContextInitService: registered all accounts: true
,08-17 13:11:01.350  1017  1462 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:01.350  1017  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:01.350  1017  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:01.350  1017  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:01.360  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-17 13:11:01.360  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:01.360  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:01.360  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-17 13:11:01.370  1017  2116 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:01.370  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:01.370  1017  2116 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:01.370  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:01.430  1017  3391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-17 13:11:01.430  2046  2232 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-17 13:11:01.700  1017  1257 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 13:11:01.710  1017  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-17 13:11:01.710  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:01.710  1017  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:01.710  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:01.880  1017  1257 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-17 13:11:01.880  1017  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-17 13:11:01.890  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:01.890  1017  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:01.890  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:01.940  6756  6850 W jxcore-log: Initializing JXcore engine
08-17 13:11:01.940  6756  6850 W jxcore-log: JXcore engine is ready
,08-17 13:11:01.960  6854  6854 I dex2oat : ----------------------------------------------------
,08-17 13:11:01.960  6854  6854 I dex2oat : <SS>: S T A R T I N G . . .
,08-17 13:11:01.960  6854  6854 I dex2oat : <SS>: Zip is absent. Canceled.
,08-17 13:11:01.960  6854  6854 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-17 13:11:02.020  6854  6854 I dex2oat : dex2oat took 62.369ms (threads: 4)
,08-17 13:11:02.030  2033  2033 E audit   : type=1400 msg=audit(1471432262.030:205): avc:  denied  { ioctl } for  pid=6850 comm="Thread-1245" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-17 13:11:02.030  2033  2033 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:02.030  2033  2033 E audit   : type=1300 msg=audit(1471432262.030:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f5c58f8 items=0 ppid=313 ppcomm=main pid=6850 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1245" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-17 13:11:02.030  2033  2033 E audit   : type=1320 msg=audit(1471432262.030:205): 
,08-17 13:11:02.040  6812  6824 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 13:11:02.040  6812  6824 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 13:11:02.040  6812  6824 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 13:11:02.040  6812  6824 I Adreno-EGL: Local Branch: 
08-17 13:11:02.040  6812  6824 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 13:11:02.040  6812  6824 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 13:11:02.040  6812  6824 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 13:11:02.050  6756  6850 W jxcore-log: Starting JXcore engine
,08-17 13:11:02.060  2046  2232 I art     : Explicit concurrent mark sweep GC freed 45789(2MB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 11MB/18MB, paused 1.665ms total 160.533ms
,08-17 13:11:02.100  2046  2232 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-17 13:11:02.100  2046  2232 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:02.100  2046  2232 I System.out: (HTTPLog)-Static: isShipBuild true
08-17 13:11:02.100  2046  2232 I System.out: (HTTPLog)-Thread-201-667137534: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-17 13:11:02.100  2046  2232 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:02.100   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 13:11:02.100   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 13:11:02.110  2046  2232 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 13:11:02.110  2046  2232 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2046, getuid(): 10011
,08-17 13:11:02.150  6812  6824 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 13:11:02.150  6812  6824 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 13:11:02.150  6812  6824 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 13:11:02.150  6812  6824 I Adreno-EGL: Local Branch: 
08-17 13:11:02.150  6812  6824 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 13:11:02.150  6812  6824 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 13:11:02.150  6812  6824 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 13:11:02.160  2046  2232 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2046, getuid(): 10011
,08-17 13:11:02.180  6756  6850 W jxcore-log: Platform android
08-17 13:11:02.180  6756  6850 W jxcore-log: 
08-17 13:11:02.180  6756  6850 W jxcore-log: Process ARCH arm
08-17 13:11:02.180  6756  6850 W jxcore-log: 
,08-17 13:11:02.190  6812  6824 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 13:11:02.190  6812  6824 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 13:11:02.190  6812  6824 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 13:11:02.190  6812  6824 I Adreno-EGL: Local Branch: 
08-17 13:11:02.190  6812  6824 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 13:11:02.190  6812  6824 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 13:11:02.190  6812  6824 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 13:11:02.400   282   282 I WVCdm   : CdmEngine::CloseSession
,08-17 13:11:02.410   282   282 I WVCdm   : L3 Terminate.
,08-17 13:11:02.450  6756  6850 I jxcore-log: JXcore Cordova bridge is ready!
08-17 13:11:02.450  6756  6850 I jxcore-log: 
,08-17 13:11:02.450  6756  6850 W jxcore-log: JXcore engine is started
,08-17 13:11:02.470  2046  6803 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:02.470  6756  6833 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 13:11:02.470  2046  6803 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-17 13:11:02.470  6756  6756 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-17 13:11:02.470  2046  6803 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2046, getuid(): 10011
,08-17 13:11:02.510  2046  6803 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2046, getuid(): 10011
,08-17 13:11:02.660  2046  2232 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 13:11:02.660  2046  2232 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-17 13:11:02.660  2046  2232 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-17 13:11:01.562+0200, stopTime=2016-08-17 13:11:02.673+0200, duration=1111ms
,08-17 13:11:02.670  2046  6865 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:02.680   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 13:11:02.680   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 13:11:02.680  2046  6865 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 13:11:02.680  2046  6865 I qtaguid : Tagging socket 69 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2046, getuid(): 10011
,08-17 13:11:02.720  2046  6865 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2046, getuid(): 10011
,08-17 13:11:02.730  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 13:11:02.970  2046  6865 I qtaguid : Untagging socket 69
,08-17 13:11:03.000  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:11:03.000  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-17 13:11:03.000  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:03.000  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:03.000  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:03.030  2046  2232 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-17 13:11:03.090  1017  1257 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:03.100  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:03.100  1017  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:03.100  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:03.130  1017  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:03.130  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:03.130  1017  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:03.130  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:03.160   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 13:11:03.190  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:03.190  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:03.190  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:03.190  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:03.190  2046  6873 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 13:11:03.190  2046  6871 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 13:11:03.190  1017  2116 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:03.190  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:03.190  1017  2116 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:03.190  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:03.220  1017  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:03.220  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:03.220  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:03.220  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:03.220  2046  6873 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-17 13:11:03.220  2046  6871 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 13:11:03.220  1017  1462 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:03.220  1017  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:03.220  1017  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:03.220  1017  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:03.250  1017  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:03.250  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:03.250  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:03.250  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:03.250  2046  6873 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-17 13:11:03.250  2046  6871 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-17 13:11:03.250  2046  6871 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-17 13:11:03.270  2046  6871 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 13:11:03.320  1017  1483 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 13:11:03.370  2046  6871 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:03.380   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 13:11:03.380   277  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-17 13:11:03.380  2046  6871 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-17 13:11:03.380  2046  6871 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2046, getuid(): 10011
,08-17 13:11:03.420  2046  6871 I qtaguid : Tagging socket 84 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2046, getuid(): 10011
,08-17 13:11:03.690  1017  1257 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 13:11:03.700  2046  6871 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
08-17 13:11:03.700  2046  6871 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 2046, getuid(): 10011
,08-17 13:11:03.840  1017  2092 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 13:11:03.860  2046  6871 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:03.860  2046  6871 I qtaguid : Tagging socket 81 with tag fffffca200000000{4294966434,0} for uid -1, pid: 2046, getuid(): 10011
,08-17 13:11:04.040  1017  2100 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 13:11:04.040  2046  6871 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:04.040  2046  6871 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 2046, getuid(): 10011
,08-17 13:11:04.160   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 13:11:04.170  1017  1445 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 13:11:04.180  2046  6871 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:04.180  2046  6871 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 2046, getuid(): 10011
,08-17 13:11:04.200   287   287 E SMD     : DCD OFF
,08-17 13:11:04.340  1017  1257 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-17 13:11:04.360  2046  6871 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:04.360  2046  6871 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 2046, getuid(): 10011
,08-17 13:11:04.800  2046  6866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:04.800  2046  6866 I qtaguid : Tagging socket 69 with tag 1000310200000000{268448002,0} for uid 10011, pid: 2046, getuid(): 10011
,08-17 13:11:05.010  2046  6866 I qtaguid : Untagging socket 69
,08-17 13:11:05.010  2046  2232 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-17 13:11:05.040  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-17 13:11:05.170   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 13:11:05.300  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-17 13:11:05.300  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 13:11:05.300  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-17 13:11:05.300  1017  1030 D BatteryService: stay LED for fully charged
08-17 13:11:05.300  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 13:11:05.310  1017  1017 I MotionRecognitionService: Plugged
08-17 13:11:05.320  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-17 13:11:05.310  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-17 13:11:05.320  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 13:11:05.320  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 13:11:05.320  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 13:11:05.330  3184  3184 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 13:11:05.330  3184  3287 D HeadsetStateMachine: Disconnected process message: 10
,08-17 13:11:05.340  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-17 13:11:05.340  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-17 13:11:05.340  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:05.340  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:05.350  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:06.170   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 13:11:07.170   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 13:11:07.200   287   287 E SMD     : DCD OFF,
,08-17 13:11:07.460  1017  1483 I ActivityManager: Killing 6488:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-17 13:11:08.170   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-17 13:11:09.300  1017  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-17 13:11:10.210   287   287 E SMD     : DCD OFF
,08-17 13:11:11.350  1017  3361 D SSRM:n  : SIOP:: AP = 340,
,08-17 13:11:13.210   287   287 E SMD     : DCD OFF,
,08-17 13:11:15.350  1017  2092 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 13:11:15.350  1017  2092 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 13:11:15.350  1017  2092 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 13:11:15.350  1017  2092 D BatteryService: stay LED for fully charged
,08-17 13:11:15.350  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 13:11:15.360  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 13:11:15.360  1017  1017 I MotionRecognitionService: Plugged
08-17 13:11:15.360  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-17 13:11:15.360  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
,08-17 13:11:15.360  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 13:11:15.360  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 13:11:15.370  3184  3184 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 13:11:15.370  3184  3287 D HeadsetStateMachine: Disconnected process message: 10
,08-17 13:11:15.380  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-17 13:11:15.380  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-17 13:11:15.390  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:15.390  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:15.390  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:15.630  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 13:11:15.630  6756  6850 I jxcore-log: 
,08-17 13:11:15.630  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 13:11:15.630  6756  6850 I jxcore-log: 
,08-17 13:11:15.640  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:15.640  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:15.640  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:15.640  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:15.640  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:15.640  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:15.640  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:15.640  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:15.640  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:15.640  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 13:11:15.640  6756  6850 I jxcore-log: 
,08-17 13:11:15.650  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 13:11:15.650  6756  6850 I jxcore-log: 
,08-17 13:11:16.080  6756  6850 D ExecuteNativeTests: Running unit tests
,08-17 13:11:16.160  1017  1049 I PowerManagerService: [PWL] Off : 75s ago
,08-17 13:11:16.190  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 13:11:16.190  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe added. We now have 2 listener(s)
,08-17 13:11:16.190  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 13:11:16.190  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:16.190  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:16.190  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:16.190  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f added. We now have 2 listener(s)
08-17 13:11:16.190  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:16.190  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:16.200  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:16.200  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:16.200  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.200  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.200  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.200  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:16.200  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.200  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:16.200  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:16.200  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:16.200  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:16.210  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.210  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 13:11:16.210  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 13:11:16.210  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 13:11:16.210  6756  6850 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 13:11:16.210   287   287 E SMD     : DCD OFF
08-17 13:11:16.210  6756  6850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 13:11:16.210  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 13:11:16.210  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 13:11:16.210  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 13:11:16.210  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.210  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.210  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.210  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.210  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.210  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:16.210  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:16.210  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe removed from the list
08-17 13:11:16.210  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.210  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f removed from the list
,08-17 13:11:16.210  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:16.210  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.210  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.210  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.210  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.220  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.220  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.220  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.220  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.220  6756  6850 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 13:11:16.220  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.220  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.220  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.220  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.220  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.220  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.220  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.220  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.220  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.220  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.220  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.220  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.220  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.220  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.220  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.220  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.220  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.220  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.220  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 13:11:16.220  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 13:11:16.220  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 13:11:16.220  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 13:11:16.230  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.230  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.230  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.230  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.230  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.230  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.230  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.230  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.230  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.230  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.230  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.230  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.230  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.230  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.230  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.230  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.230  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.230  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.230  6756  6850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 13:11:16.230  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:16.230  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:16.230  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.230  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.230  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.230  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:16.230  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.230  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:16.230  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:16.240  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.240  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:16.240  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:16.240  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:16.240  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 13:11:16.240  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:16.240  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 13:11:16.240  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:16.240  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 13:11:16.240  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:16.250  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:16.250  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 13:11:16.250  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-17 13:11:16.260  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 13:11:16.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 13:11:16.260  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 13:11:16.260  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 13:11:16.270  3184  3372 D BtGatt.GattService: registerClient() - UUID=0ec87604-0bc9-45ad-9765-031c1e05ad3d
,08-17 13:11:16.310  3184  3280 D BtGatt.GattService: onClientRegistered() - UUID=0ec87604-0bc9-45ad-9765-031c1e05ad3d, clientIf=6
,08-17 13:11:16.320  6756  6764 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 13:11:16.320  3184  3371 D BtGatt.GattService: start scan with filters
,08-17 13:11:16.320  3184  3286 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:16.320  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 13:11:16.320  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 13:11:16.320  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 13:11:16.320  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:16.320  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:16.330  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:16.330  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 13:11:16.330  3184  3286 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:16.330  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:16.340  3184  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 13:11:16.340  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.340  3184  3286 D BtGatt.ScanManager: allow scan with filters
,08-17 13:11:16.340  3184  3286 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 13:11:16.340  3184  3286 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 13:11:16.340  6756  6850 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 13:11:16.350  3184  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 13:11:16.350  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.350  3184  3286 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 13:11:16.350  3184  3286 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 13:11:16.350  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.350  6756  6850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 13:11:16.350  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.350  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 13:11:16.350  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.350  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 13:11:16.350  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:16.350  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:16.350  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:16.350  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 13:11:16.350  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 13:11:16.350  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 13:11:16.360  3184  3192 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:16.360  3184  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 13:11:16.360  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.360  3184  3372 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 13:11:16.360  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:16.360  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:16.360  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:16.360  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:16.360  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 13:11:16.360  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:16.370  3184  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 13:11:16.370  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.370  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:16.370  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:16.370  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:16.370  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:16.370  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:16.370  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.370  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.370  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:16.370  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.370  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.370  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.370  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.370  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.370  6756  6850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 13:11:16.380  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:16.380  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:16.380  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:16.380  3184  3286 D BtGatt.ScanManager: filter size is 1
08-17 13:11:16.380  3184  3286 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 13:11:16.390  3184  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 13:11:16.390  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:16.390  3184  3286 D BtGatt.ScanManager: stopping BLe Batch
,08-17 13:11:16.390  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:16.390  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.390  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.390  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.390  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:16.390  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.390  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:16.390  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:16.390  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:16.390  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:16.390  3184  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 13:11:16.390  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.390  3184  3286 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 13:11:16.390  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:16.390  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:16.390  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 13:11:16.390  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:16.390  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:16.400  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
08-17 13:11:16.400  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.400  3184  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 13:11:16.400  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.400  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.410  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:16.410  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:16.410  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 13:11:16.410  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 13:11:16.410  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 13:11:16.410  3184  3192 D BtGatt.GattService: registerClient() - UUID=51c148d0-7b4b-4b31-8e29-ce1a2c54f6b3
,08-17 13:11:16.450  3184  3280 D BtGatt.GattService: onClientRegistered() - UUID=51c148d0-7b4b-4b31-8e29-ce1a2c54f6b3, clientIf=6
,08-17 13:11:16.460  6756  6766 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 13:11:16.460  3184  3371 D BtGatt.GattService: start scan with filters
,08-17 13:11:16.460  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 13:11:16.460  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 13:11:16.460  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 13:11:16.460  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:16.460  3184  3286 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:16.460  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:16.460  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:16.460  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 13:11:16.470  3184  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 13:11:16.470  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.470  3184  3286 D BtGatt.ScanManager: allow scan with filters
08-17 13:11:16.470  3184  3286 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 13:11:16.470  3184  3286 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6,
,08-17 13:11:16.470  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:16.470  6756  6850 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 13:11:16.470  3184  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 13:11:16.470  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.470  3184  3286 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 13:11:16.480  3184  3286 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 13:11:16.480  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:16.480  6756  6850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 13:11:16.480  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:16.480  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 13:11:16.480  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:16.480  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 13:11:16.480  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:16.480  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 13:11:16.480  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:16.480  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 13:11:16.480  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 13:11:16.490  3184  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 13:11:16.490  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.490  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 13:11:16.490  3184  3196 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:16.490  3184  3192 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 13:11:16.490  3184  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 13:11:16.490  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.490  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:16.490  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:16.490  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:16.490  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:16.490  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 13:11:16.500  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:16.500  3184  3286 D BtGatt.ScanManager: filter size is 1
,08-17 13:11:16.500  3184  3286 D BtGatt.ScanManager: delete FilterIndex - 4
08-17 13:11:16.500  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:16.500  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:16.500  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:16.500  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:16.500  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:16.500  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:16.500  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:16.510  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.510  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.510  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:16.510  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.510  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.510  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.510  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.510  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.510  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.510  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.510  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-17 13:11:16.510  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.510  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:16.510  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.510  6756  6850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 13:11:16.510  3184  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 13:11:16.510  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:16.510  3184  3286 D BtGatt.ScanManager: stopping BLe Batch
,08-17 13:11:16.510  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:16.520  3184  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 13:11:16.520  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.520  3184  3286 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 13:11:16.520  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:16.520  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.520  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.520  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.520  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:16.520  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.520  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:16.520  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:16.520  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:16.520  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:16.520  3184  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 13:11:16.530  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-17 13:11:16.530  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:16.530  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 13:11:16.530  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:16.530  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 13:11:16.530  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.530  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.530  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.530  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-17 13:11:16.540  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:16.540  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:16.540  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 13:11:16.540  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 13:11:16.540  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 13:11:16.550  3184  3371 D BtGatt.GattService: registerClient() - UUID=fcfd35c0-09fe-495a-a979-0ae6e13a7fa8
,08-17 13:11:16.590  3184  3280 D BtGatt.GattService: onClientRegistered() - UUID=fcfd35c0-09fe-495a-a979-0ae6e13a7fa8, clientIf=6
,08-17 13:11:16.590  6756  6766 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 13:11:16.590  3184  3372 D BtGatt.GattService: start scan with filters
,08-17 13:11:16.590  3184  3286 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:16.590  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 13:11:16.600  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 13:11:16.600  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 13:11:16.600  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:16.600  3184  3280 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 13:11:16.600  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.600  3184  3286 D BtGatt.ScanManager: allow scan with filters
,08-17 13:11:16.600  3184  3286 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 13:11:16.600  3184  3286 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 13:11:16.600  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:16.600  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:16.600  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 13:11:16.610  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:16.610  3184  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 13:11:16.610  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:16.610  3184  3286 D BtGatt.ScanManager: Starting BLE batch scan
08-17 13:11:16.610  3184  3286 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 13:11:16.610  6756  6850 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 13:11:16.610  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:16.610  6756  6850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 13:11:16.610  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:16.620  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 13:11:16.620  3184  3280 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 13:11:16.620  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.620  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:16.620  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 13:11:16.620  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:16.620  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 13:11:16.620  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:16.620  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
,08-17 13:11:16.620  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 13:11:16.620  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 13:11:16.620  3184  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-17 13:11:16.630  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:16.630  3184  3371 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:16.630  3184  3286 D BtGatt.ScanManager: filter size is 1
,08-17 13:11:16.630  3184  3286 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 13:11:16.630  3184  3372 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 13:11:16.640  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:16.640  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:16.640  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:16.640  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:16.640  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 13:11:16.640  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:16.640  3184  3280 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-17 13:11:16.640  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:16.640  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:16.640  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:16.640  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:16.640  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:16.640  3184  3286 D BtGatt.ScanManager: stopping BLe Batch
,08-17 13:11:16.640  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:16.640  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:16.640  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:16.640  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:16.640  6756  6850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 13:11:16.640  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.640  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:16.640  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.640  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:16.650  3184  3280 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-17 13:11:16.650  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:16.650  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:16.650  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.650  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.650  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.650  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.650  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.650  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.650  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.650  3184  3286 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 13:11:16.650  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:16.650  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.650  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:16.650  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.650  6756  6850 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 13:11:16.650  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:16.650  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.650  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:16.650  3184  3280 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-17 13:11:16.650  3184  3280 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:16.650  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.650  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.650  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.650  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.650  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.650  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.650  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.650  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.650  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.650  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.650  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.660  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-17 13:11:16.660  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.660  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:16.660  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.660  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.660  6756  6850 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-17 13:11:16.660  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.660  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.660  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.660  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.660  6756  6850 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 13:11:16.660  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:16.660  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.660  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.660  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.660  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:16.660  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.660  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.660  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list,
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 13:11:16.670  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 13:11:16.670  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 13:11:16.670  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 13:11:16.670  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:16.670  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.670  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.670  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.670  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.670  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.670  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.670  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.670  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.670  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.670  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.670  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.670  6756  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 13:11:16.670  6756  6850 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 13:11:16.670  6756  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 13:11:16.670  6756  6850 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAnd,RemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-17 13:11:16.670  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 13:11:16.670  6756  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 13:11:16.670  6756  6850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 13:11:16.670  6756  6850 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 13:11:16.670  6756  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 13:11:16.670  6756  6850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 13:11:16.670  6756  6850 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 13:11:16.670  6756  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 13:11:16.670  6756  6850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 13:11:16.670  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 13:11:16.680  6756  6850 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 13:11:16.680  6756  6850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 13:11:16.680  6756  6850 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 13:11:16.680  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.680  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.680  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 13:11:16.680  6756  6886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1309)
08-17 13:11:16.680  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.680  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.680  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.680  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.680  6756  6850 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-17 13:11:16.680  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.680  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.680  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.680  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:16.680  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.680  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.680  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.680  6756  6850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 13:11:16.680  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.680  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.680  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.680  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.680  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.680  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.680  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.680  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.680  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.680  6756  6887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1309
,08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 13:11:16.690  6756  6850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 13:11:16.690  6756  6850 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 13:11:16.690  6756  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 13:11:16.690  6756  6850 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 13:11:16.690  6756  6850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 13:11:16.690  6756  6850 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 13:11:16.690  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.690  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.690  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
,08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.690  6756  6886 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.690  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.690  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.690  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.690  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.690  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.690  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 13:11:16.690  6756  6850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 13:11:16.690  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:16.690  6756  6756 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 13:11:16.700  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:16.700  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.700  6756  6756 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:16.700  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.700  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.700  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.700  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.700  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.700  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:16.700  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.700  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.700  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:16.700  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.700  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.700  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:16.700  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.700  6756  6886 D BluetoothSocket: connect(): myUserId = 0
08-17 13:11:16.700  6756  6886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 13:11:16.700  6756  6888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-17 13:11:16.700  6756  6888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 13:11:16.700  3184  3192 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:16.700  6756  6756 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.700  6756  6886 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.700  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.700  6756  6850 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 13:11:16.700  6756  6850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 13:11:16.700  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 13:11:16.700  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:16.700  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.700  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.700  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.700  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.700  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.700  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:16.700  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.700  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.700  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.700  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.700  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.710  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:16.710  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.710  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.710  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.710  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.710  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.710  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.710  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.710  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.710  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.710  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.710  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.710  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:16.710  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:16.710  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:16.710  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.710  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.710  6756  6850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b0cebfe not in the list
08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.710  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:16.710  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.710  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:16.710  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:16.710  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:16.710  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:16.710  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18dc0f5f not in the list
,08-17 13:11:16.710  6756  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-17 13:11:16.710  6756  6850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 13:11:16.710  6756  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 13:11:16.710  6756  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 13:11:16.710  6756  6850 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 13:11:16.710  6756  6850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 13:11:16.710  6756  6850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-17 13:11:16.720  6756  6850 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 13:11:16.720  6756  6850 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 13:11:16.720  6756  6850 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 13:11:16.720  6756  6850 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-17 13:11:16.720  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:16.720  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17973529 added. We now have 2 listener(s)
08-17 13:11:16.720  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:16.720  6756  6850 D BluetoothAdapter: enable()
,08-17 13:11:16.720  6756  6850 D BluetoothAdapter: enable(): BT is already enabled..!,
,08-17 13:11:16.720  1017  1490 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 13:11:16.720  1017  1490 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 13:11:16.720  1017  1490 D SecContentProvider2: mCursor = null
,08-17 13:11:16.720  1017  1490 D WifiService: setWifiEnabled: true pid=6756, uid=10171,
08-17 13:11:16.720  1017  1490 W ActivityManager: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 13:11:16.730  1017  1490 W WifiService: Failed getting userId using ActivityManagerNative
08-17 13:11:16.730  1017  1490 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 13:11:16.730  1017  1490 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 13:11:16.730  1017  1490 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 13:11:16.730  1017  1490 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 13:11:16.730  1017  1490 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 13:11:16.730  1017  1490 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 13:11:16.730  1017  1490 D SettingsProvider: name = wifi_on
,08-17 13:11:16.730  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:16.730  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@244a50ae added. We now have 3 listener(s)
08-17 13:11:16.730  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:16.740  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:16.740  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ccd8e4f added. We now have 4 listener(s)
,08-17 13:11:16.740  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:16.740  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:16.740  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14fbd9dc added. We now have 5 listener(s)
08-17 13:11:16.740  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:16.740  1017  2100 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 13:11:16.750  1017  2100 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-17 13:11:16.750  1017  2100 D SecContentProvider2: mCursor = null
,08-17 13:11:16.750  1017  2100 D WifiService: setWifiEnabled: false pid=6756, uid=10171
,08-17 13:11:16.750  1017  2100 D SettingsProvider: name = wifi_on
,08-17 13:11:16.750  1017  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 13:11:16.760  1357  1357 I wpa_supplicant: reset timer : RESET_TIMER 0,
08-17 13:11:16.760  1357  1357 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-17 13:11:16.760  1357  1357 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 13:11:16.760  6756  6850 D BluetoothAdapter: disable()
08-17 13:11:16.760  1357  1357 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 13:11:16.760  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:16.770  1017  1483 D SettingsProvider: name = bluetooth_on,
,08-17 13:11:16.770  3184  3275 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-17 13:11:16.770  3184  3275 D BluetoothAdapterProperties: Setting state to 13
08-17 13:11:16.770  3184  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 13:11:16.770  3184  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 13:11:16.770  3184  3275 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 13:11:16.770  1017  2116 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:16.780  1017  2116 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 13:11:16.780  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:16.780  1017  2116 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:16.780  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:16.780  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:16.780  3184  3184 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-17 13:11:16.780  3184  3275 D BluetoothAdapterService: Autoconnection is available 
08-17 13:11:16.780  3184  3275 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 13:11:16.780  3184  3275 D BluetoothAdapterService: terminating service from this receiver
,08-17 13:11:16.780  3184  3184 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c1ba21c, channel: 19, state: LISTENING
08-17 13:11:16.780  3184  3184 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c1ba21c, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ddc0684, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d0be25mSocket: android.net.LocalSocket@286e6bfa impl:android.net.LocalSocketImpl@194655ab fd:FileDescriptor[74]
08-17 13:11:16.780  3184  3184 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@286e6bfa impl:android.net.LocalSocketImpl@194655ab fd:FileDescriptor[74]
,08-17 13:11:16.780  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 13:11:16.780  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:16.780  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:16.780  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:16.780  3184  3275 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 13:11:16.780  3184  3275 D BluetoothAdapterProperties: mDiscovering is false
,08-17 13:11:16.790  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.790  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:16.790  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.790  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.790  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.790  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:16.790  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.790  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:16.790  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 13:11:16.790  1017  1476 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 13:11:16.790  3184  3275 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 13:11:16.790  3071  3071 D BluetoothPbap: Proxy object disconnected
08-17 13:11:16.790  3071  3071 D PbapServerProfile: Bluetooth service disconnected
,08-17 13:11:16.790  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:16.790  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-17 13:11:16.790  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.790  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:16.790  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:16.790  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.800  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-17 13:11:16.800  1357  1357 I wpa_supplicant: nl80211: Received scan results (9 BSSes)
,08-17 13:11:16.800  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:16.800  1017  1127 E WifiNative-wlan0: do suspend true
08-17 13:11:16.800  1017  1126 D WifiP2pService: InactiveState{ what=147461 }
08-17 13:11:16.800  1017  1126 D WifiP2pService: P2pEnabledState{ what=147461 }
08-17 13:11:16.800  1017  1126 D WifiP2pService: DefaultState{ what=147461 }
08-17 13:11:16.800  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 13:11:16.800  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:16.800  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-17 13:11:16.800  1888  1888 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 13:11:16.800  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null,
,08-17 13:11:16.810  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 13:11:16.810  1017  1462 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 13:11:16.810  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 13:11:16.810  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 13:11:16.810  3071  3071 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:16.810  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 13:11:16.810  3184  3280 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 13:11:16.820  1017  2092 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:11:16.820  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 13:11:16.820  1017  2092 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:16.820  1017  2092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:16.820  1017  2092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:16.820  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:16.820  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:16.820  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:16.820  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:16.820  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:16.820  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:16.820  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 13:11:16.820  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 13:11:16.820  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:16.820  3184  3280 D BluetoothAdapterProperties: Scan Mode:20
,08-17 13:11:16.820  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:16.820  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 13:11:16.820  3184  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 13:11:16.820  3184  3275 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 13:11:16.820  3184  3275 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-17 13:11:16.820  3184  3275 E bt-btif : cmd socket is not created
,08-17 13:11:16.820  3184  5208 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 13:11:16.830  3184  3306 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 13:11:16.830  3184  3306 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 13:11:16.830  3184  3275 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 13:11:16.830  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.840  3184  3184 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d7417a1, channel: 5, state: LISTENING
08-17 13:11:16.840  3184  3184 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d7417a1, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ec32e6d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1274dc6mSocket: android.net.LocalSocket@2492a187 impl:android.net.LocalSocketImpl@351018b4 fd:FileDescriptor[76]
08-17 13:11:16.840  3184  3184 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2492a187 impl:android.net.LocalSocketImpl@351018b4 fd:FileDescriptor[76]
,08-17 13:11:16.840  3071  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:16.840  3184  3184 I BtOppRfcommListener: stopping Accept Thread
08-17 13:11:16.840  1017  1539 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 13:11:16.840  3184  3184 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e998cdd, channel: 12, state: LISTENING
08-17 13:11:16.840  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-17 13:11:16.840  3184  3184 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e998cdd, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f6a4f8f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@103a8052mSocket: android.net.LocalSocket@d6dcf23 impl:android.net.LocalSocketImpl@4f00c20 fd:FileDescriptor[79]
08-17 13:11:16.840  3184  3184 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d6dcf23 impl:android.net.LocalSocketImpl@4f00c20 fd:FileDescriptor[79]
08-17 13:11:16.840  3184  5208 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 13:11:16.840  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:16.840  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:16.840  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 13:11:16.850  3184  3184 V BluetoothOppManager: cleanUp...
,08-17 13:11:16.850  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.850  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:16.850  3071  3071 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:16.850  3071  3071 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 13:11:16.860  3184  3306 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 13:11:16.860  3184  3306 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:16.860  3184  3306 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 13:11:16.860  6756  6886 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@56ec9ba, channel: -1, state: INIT
08-17 13:11:16.860  6756  6886 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@56ec9ba, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@117ec06b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f5ab7c8mSocket: android.net.LocalSocket@1a4f6061 impl:android.net.LocalSocketImpl@f2fc786 fd:FileDescriptor[106]
08-17 13:11:16.860  6756  6886 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a4f6061 impl:android.net.LocalSocketImpl@f2fc786 fd:FileDescriptor[106]
,08-17 13:11:16.860  6756  6886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1309)
,08-17 13:11:16.860  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-17 13:11:16.860  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 13:11:16.870  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 13:11:16.870  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:16.880  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:16.880  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:16.880  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:16.890  6895  6895 E Zygote  : MountEmulatedStorage(),
08-17 13:11:16.890  6895  6895 E Zygote  : v2
08-17 13:11:16.890  6895  6895 I libpersona: KNOX_SDCARD checking this for 10055
,08-17 13:11:16.890  1017  1030 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6895 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-17 13:11:16.890  6895  6895 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:16.900  6895  6895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:16.900  6895  6895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:16.900  6895  6895 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:16.930  6895  6895 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:16.930  6895  6895 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:16.940  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-17 13:11:16.940  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 13:11:16.940  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 13:11:16.950  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-17 13:11:16.950   277  1016 D CommandListener: Clearing all IP addresses on wlan0
08-17 13:11:16.950  2046  3025 V NativeCrypto: Read error: ssl=0xb82d8388: I/O error during system call, Connection timed out
,08-17 13:11:16.950  2046  3025 V NativeCrypto: SSL shutdown failed: ssl=0xb82d8388: I/O error during system call, Broken pipe
08-17 13:11:16.950  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:16.950  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 13:11:16.950  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:16.950  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-17 13:11:16.960  2046  3025 E GCM     : Wifi connection closed with errorCode 20
,08-17 13:11:16.960  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 13:11:16.960  1017  2116 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-17 13:11:16.960  1017  1722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:16.960  1017  1722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:16.960  1017  1722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 13:11:16.960  1017  1722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:16.960  1017  1722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-17 13:11:16.960  1017  1722 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:16.960  1017  1722 I qtaguid : Tagging socket 328 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,08-17 13:11:16.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 13:11:16.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:16.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:16.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:16.980  1017  1722 I qtaguid : Untagging socket 328,
08-17 13:11:16.980  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
08-17 13:11:16.980  1017  1722 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-17 13:11:16.980  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-17 13:11:16.980  6895  6895 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-17 13:11:16.980  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:16.980  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:16.980  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:16.980  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:16.980  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:16.980  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:16.990  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-17 13:11:16.990  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
,08-17 13:11:16.990  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 13:11:16.990  1017  1017 D RttService: SCAN_AVAILABLE : 1
,08-17 13:11:16.990  1017  1151 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:16.990  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 13:11:16.990  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 13:11:17.000  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-17 13:11:17.000  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 13:11:17.000  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 13:11:17.000  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 13:11:17.000  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 13:11:17.000  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 13:11:17.000  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 13:11:17.000  1017  1047 D WifiDisplayController: disconnect
08-17 13:11:17.000  1017  1047 D WifiDisplayController: updateConnection
08-17 13:11:17.000  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 13:11:17.000  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 13:11:17.000  1017  1126 D WifiP2pService: P2pDisablingState
08-17 13:11:17.000  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 13:11:17.000  1017  1126 D WifiP2pService: p2p socket connection lost
08-17 13:11:17.000  1017  1126 D WifiP2pService: P2pDisabledState
08-17 13:11:17.000  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 13:11:17.000  1017  1127 E WifiNative-wlan0: do suspend true
08-17 13:11:17.000  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-17 13:11:17.000  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 13:11:17.000  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 13:11:17.010  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-17 13:11:17.010  6895  6895 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-17 13:11:17.010  6895  6895 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 13:11:17.010  6895  6895 D UserAnalysis: Create SecureDbHelper
,08-17 13:11:17.020  1017  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 13:11:17.020  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 13:11:17.020  6895  6895 D IntelligenceServiceApplication: onCreate()
,08-17 13:11:17.030  3184  3306 W bt-l2cap: HC lib lpm enable=0 return 0
08-17 13:11:17.030  3184  3352 I bt_userial_mct: exiting userial_read_thread
08-17 13:11:17.030  3184  3352 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 13:11:17.030  3184  3280 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 13:11:17.030  3184  3308 I bt_vendor: hw_epilog_process
,08-17 13:11:17.030  3184  3306 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:17.030  3184  3280 D bt_userial_mct: userial_close
08-17 13:11:17.030  3184  3280 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 13:11:17.030  3184  3306 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 13:11:17.030  3184  3306 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:17.030  3184  3306 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:17.030  3184  3306 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 13:11:17.030  3184  3306 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:17.030  3184  3306 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:17.030  3184  3306 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 13:11:17.030  3184  3306 W bt-btif : ag scb idx 1 not allocated
08-17 13:11:17.030  3184  3306 W bt-btif : ag scb idx 2 not allocated
08-17 13:11:17.030  3184  3306 E bt-btif : BTA AG is already disabled, ignoring ...
,08-17 13:11:17.030  1017  2116 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 13:11:17.030  1017  2116 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:17.030  6895  6895 D IntelligenceServiceApplication: no applications having user consent for prediction
08-17 13:11:17.030  1017  2116 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:17.030  1017  2116 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:17.030  1017  2116 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:17.050  6918  6918 E Zygote  : MountEmulatedStorage(),
,08-17 13:11:17.050  6918  6918 E Zygote  : v2,
08-17 13:11:17.050  6918  6918 I libpersona: KNOX_SDCARD checking this for 10105
08-17 13:11:17.050  6918  6918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:11:17.050  6918  6918 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:17.050  1017  2116 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6918 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-17 13:11:17.050  1017  1029 I ActivityManager: Killing 6511:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-17 13:11:17.050  6918  6918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:17.050  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-17 13:11:17.060  6895  6895 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-17 13:11:17.060  6918  6918 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 13:11:17.070  6895  6895 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 13:11:17.070  6918  6918 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:17.070  6918  6918 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:17.120  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 },
08-17 13:11:17.120  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
,08-17 13:11:17.120   277  1016 D CommandListener: Clearing all IP addresses on wlan0,
08-17 13:11:17.120  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-17 13:11:17.120  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 13:11:17.120  1017  1129 V NetworkStats: updateIfacesLocked()
08-17 13:11:17.120  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,08-17 13:11:17.120  1017  1129 V NetworkStats: performPollLocked(flags=0x1),
08-17 13:11:17.120  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.120  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 13:11:17.120  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.120  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.120  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 13:11:17.120   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 13:11:17.120   277  1012 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-17 13:11:17.120  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:17.120  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:17.130  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 13:11:17.130  1017  1722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-17 13:11:17.130  1017  1722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-17 13:11:17.130  1357  1357 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-17 13:11:17.130  1017  1129 V NetworkStats: performPollLocked() took 7ms
,08-17 13:11:17.130  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-17 13:11:17.130  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 13:11:17.130  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:17.130  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.130  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.130  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:17.130  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.140  1174  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 13:11:17.140  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-17 13:11:17.140  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 13:11:17.140  1017  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 13:11:17.140  1017  1127 D SecContentProvider2: mCursor = null
08-17 13:11:17.140  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-17 13:11:17.140  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-17 13:11:17.140  1017  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-17 13:11:17.140  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:17.140  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 13:11:17.140  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.140  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.140  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 13:11:17.140  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.140  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.140  1017  1722 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:17.140  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 13:11:17.140  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 13:11:17.140  1460  1460 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 13:11:17.150  4802  6752 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-17 13:11:17.150  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:17.150  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 13:11:17.150  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:17.150  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 13:11:17.150  1174  1174 D HotspotTile: onReceive : 0, 0
,08-17 13:11:17.150  3071  3071 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:17.150  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:17.150  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:17.160  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-17 13:11:17.160  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 13:11:17.160  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 13:11:17.160  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 13:11:17.160  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:17.160  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-17 13:11:17.160  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-17 13:11:17.160  1017  1124 V NetworkStats: updateIfacesLocked()
08-17 13:11:17.160  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:17.160  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-17 13:11:17.160  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:17.160  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 13:11:17.160  1017  1130 D Tethering: MasterInitialState.processMessage what=3
,08-17 13:11:17.160  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:17.160  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:17.160  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:17.160  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:17.160  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:17.160  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:17.160  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:17.160  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:17.160  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 13:11:17.160  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:17.160  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:17.170  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 13:11:17.170  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:17.170  1017  1124 V NetworkStats: performPollLocked() took 6ms
08-17 13:11:17.170  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:17.170  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:17.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:17.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:17.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:17.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:17.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:17.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:17.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:17.170  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:17.170  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:17.180  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-17 13:11:17.180  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 13:11:17.180  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 13:11:17.180  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-17 13:11:17.180  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 13:11:17.180  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 13:11:17.180  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:17.180  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:17.180  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 13:11:17.180  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:17.180  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:17.180  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 13:11:17.180  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-17 13:11:17.190  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 13:11:17.190  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:17.190  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-17 13:11:17.190  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.190  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.190  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.190  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.190  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:17.190  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:17.200  6756  6756 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 13:11:17.200  1017  1323 E Watchdog: !@Sync 4
,08-17 13:11:17.210  1357  1357 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 13:11:17.210   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 13:11:17.210   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 13:11:17.210  6918  6938 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 13:11:17.220   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 13:11:17.220   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 13:11:17.220  6918  6938 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 13:11:17.250  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.260  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 13:11:17.260  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-17 13:11:17.260  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 13:11:17.260  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.270  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 13:11:17.270  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.270  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 13:11:17.270  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.270  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 13:11:17.270  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.270  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 13:11:17.280  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 13:11:17.280  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 13:11:17.280  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 13:11:17.280  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 13:11:17.280  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.280  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-17 13:11:17.280  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.290  3184  3280 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 13:11:17.290  3184  3280 I bt_vendor: bluetooth satus is on
08-17 13:11:17.290  3184  3280 I bt_vendor: bt-vendor : resetting BT status
08-17 13:11:17.290  3184  3280 I bt_vendor: Starting hciattach daemon
08-17 13:11:17.290  3184  3280 I bt_vendor: try to set false
,08-17 13:11:17.290  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 13:11:17.290  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 13:11:17.290  3184  3280 I bt_vendor: Starting hciattach daemon
,08-17 13:11:17.290  3184  3280 I bt_vendor: try to set false
08-17 13:11:17.290  3184  3280 I bt_vendor: cleanup
,08-17 13:11:17.290  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-17 13:11:17.290  3184  3306 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-17 13:11:17.290  3184  3280 I GKI_LINUX: GKI_exit_task 0 done
08-17 13:11:17.290  3184  3280 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 13:11:17.290  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.300  3184  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 13:11:17.300  3184  3275 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 13:11:17.300  3184  3275 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-17 13:11:17.300  1357  1357 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 13:11:17.300  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 13:11:17.300  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 13:11:17.300  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-17 13:11:17.300  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 13:11:17.300  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 13:11:17.300  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 13:11:17.300  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.300  3184  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 13:11:17.300  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:17.310  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.300  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-17 13:11:17.310  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.310  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:17.310  1017  2116 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:17.310  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 13:11:17.310  1017  2116 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 13:11:17.310  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 13:11:17.310  3184  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 13:11:17.310  3184  3184 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 13:11:17.310  3184  3184 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 13:11:17.310  3184  3184 D BtGatt.GattService: stop()
08-17 13:11:17.310  3184  3184 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 13:11:17.310  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.310  1017  2116 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.310  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:17.310  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 13:11:17.310  1017  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:17.310  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 13:11:17.310  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-17 13:11:17.310  3184  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 13:11:17.310  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 13:11:17.310  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-17 13:11:17.310  3184  3184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:17.310  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.310  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.310  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:17.310  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 13:11:17.310  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 13:11:17.310  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 13:11:17.320  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-17 13:11:17.320  3184  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-17 13:11:17.320  1017  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:17.320  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 13:11:17.320  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.320  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.320  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:17.320  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-17 13:11:17.320  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 13:11:17.320  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 13:11:17.320  3184  3184 D HeadsetService: Received stop request...Stopping profile...
08-17 13:11:17.320  3184  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 13:11:17.320  1017  1445 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:17.320  1017  1445 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-17 13:11:17.320  3184  3184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:17.320  1017  1445 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.320  1017  1445 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.320  1017  1445 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:17.320  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 13:11:17.320  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 13:11:17.320  3184  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 13:11:17.320  3071  3071 D HeadsetProfile: Bluetooth service disconnected
,08-17 13:11:17.320  1357  1357 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-17 13:11:17.320  1017  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:17.330  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 13:11:17.330  1357  1357 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 13:11:17.330  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:17.330  1357  1357 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 13:11:17.330  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:17.330  1357  1357 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 13:11:17.330  1357  1357 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 13:11:17.330  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:17.330  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 13:11:17.330  1017  1130 D Tethering: InitialState.processMessage what=4
08-17 13:11:17.330  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:17.330  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.330  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:17.330  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.330  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.330  3184  3275 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.330  1017  1130 E Tethering: No numeric data
,08-17 13:11:17.330  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:17.330  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:17.330  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:17.330  1017  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:17.330  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 13:11:17.330  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-17 13:11:17.330  1017  1130 D Tethering: clearTetheredNotification()
,08-17 13:11:17.330  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.330  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.330  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:17.330  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:17.330  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:17.330  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:17.340  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 13:11:17.340  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 13:11:17.340  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-17 13:11:17.340  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:17.340  3184  3275 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-17 13:11:17.340  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:17.340  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 13:11:17.340  1017  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:17.340  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 13:11:17.340  1174  1174 D HotspotTile: updateTetherState():false, false
,08-17 13:11:17.340  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-17 13:11:17.340  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.340  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.340  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:17.340  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 13:11:17.340  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:17.340  1017  1124 V NetworkStats: performPollLocked() took 5ms,
08-17 13:11:17.340  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:17.340  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:17.340  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:17.340  3184  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:17.340  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:17.340  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 13:11:17.340  3184  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:17.340  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 13:11:17.340  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 13:11:17.350  3184  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 13:11:17.350  3184  3275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 13:11:17.350  3184  3275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 13:11:17.350  3184  3275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 13:11:17.350  3184  3275 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-17 13:11:17.350  3184  3184 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-17 13:11:17.350  3184  3184 D A2dpService: Received stop request...Stopping profile...
08-17 13:11:17.350  3184  3295 D A2dpStateMachine: Exit Disconnected: -1
,08-17 13:11:17.350  3184  3184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:17.350  3071  3071 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:17.350  3071  3071 D A2dpProfile: Bluetooth service disconnected
08-17 13:11:17.350  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:17.350  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 13:11:17.350  3184  3184 D HidService: Received stop request...Stopping profile...
08-17 13:11:17.350  3184  3184 D HidService: Stopping Bluetooth HidService
08-17 13:11:17.350  3184  3184 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 13:11:17.350  3184  3184 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 13:11:17.350  3184  3184 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 13:11:17.350  3184  3184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:17.360  3184  3184 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 13:11:17.360  3184  3184 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 13:11:17.360  3184  3184 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 13:11:17.360  3071  3071 D BluetoothInputDevice: Proxy object disconnected
08-17 13:11:17.360  3071  3071 D HidProfile: Bluetooth service disconnected
,08-17 13:11:17.360  3184  3184 D HealthService: Received stop request...Stopping profile...
08-17 13:11:17.360  3184  3184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:17.360  3184  3184 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 13:11:17.360  3184  3184 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 13:11:17.360  3184  3184 D PanService: Received stop request...Stopping profile...
08-17 13:11:17.360  3184  3184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:17.360  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 13:11:17.360  3184  3184 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 13:11:17.360  3071  3071 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 13:11:17.360  3071  3071 D PanProfile: Bluetooth service disconnected
,08-17 13:11:17.370  3184  3184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465,
,08-17 13:11:17.370  3071  3071 D BluetoothMap: Proxy object disconnected
08-17 13:11:17.370  3071  3071 D MapProfile: Bluetooth service disconnected
,08-17 13:11:17.370  3184  3184 D SapService: Received stop request...Stopping profile...
08-17 13:11:17.370  3184  3184 D SapService: Stopping Bluetooth SapService
08-17 13:11:17.370  3184  3184 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:17.370  3184  3184 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-17 13:11:17.370  3184  3184 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 13:11:17.370  3184  3184 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-17 13:11:17.370  3184  3184 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:17.370  3184  3184 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 13:11:17.370  3071  3071 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 13:11:17.370  3071  3071 D SapProfile: Bluetooth service disconnected
,08-17 13:11:17.370  3184  3296 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-17 13:11:17.370  3184  3184 I GKI_LINUX: GKI_exit_task 2 done
08-17 13:11:17.370  3184  3184 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 13:11:17.370  3184  3184 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 13:11:17.370  3184  3184 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.370  3184  3184 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.370  3184  3184 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 13:11:17.370  3184  3184 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.370  3184  3184 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.370  3184  3184 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 13:11:17.370  3184  3184 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 13:11:17.370  3184  3184 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 13:11:17.370  3184  3184 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.370  3184  3184 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:17.370  3184  3184 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 13:11:17.370  3184  3184 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-17 13:11:17.380  3184  3184 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-17 13:11:17.380  3184  3184 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 13:11:17.380  3184  3184 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 13:11:17.380  3184  3184 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-17 13:11:17.380  3184  3184 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 13:11:17.380  3184  3184 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 13:11:17.380  3184  3275 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-17 13:11:17.380  3184  3275 D BluetoothAdapterProperties: Setting state to 10
08-17 13:11:17.380  3184  3275 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 13:11:17.380  3184  3275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 13:11:17.380  3184  3275 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 13:11:17.380  2046  6846 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:17.380  2046  6846 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:17.380   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb827d7c8
08-17 13:11:17.380   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-17 13:11:17.380   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-17 13:11:17.380   272   334 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1205348216)
,08-17 13:11:17.390  3184  3275 D BluetoothAdapterService: Autoconnection is available 
,08-17 13:11:17.390  3184  3275 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 13:11:17.390  3184  3275 I BluetoothAdapterState: Entering OffState
,08-17 13:11:17.390  3071  6891 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 13:11:17.390  1444  1459 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 13:11:17.390  1444  1459 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:17.390  3184  3192 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:17.390  3184  3192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:17.390  3071  3082 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 13:11:17.390  6756  6764 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 13:11:17.390  6756  6764 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 13:11:17.390  6756  6764 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 13:11:17.390  6756  6764 D BluetoothLeAdvertiser: Exit stop advertising
,08-17 13:11:17.390  6756  6764 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 13:11:17.390  6756  6764 D BluetoothLeScanner: Exiting stopAllScan
,08-17 13:11:17.400  3071  3079 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 13:11:17.400  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 13:11:17.400  3071  3082 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 13:11:17.400  3071  3079 D Bluetoothsap: onBluetoothStateChange: up=false
,08-17 13:11:17.400  3071  3079 D Bluetoothsap: Unbinding service...
,08-17 13:11:17.400  1174  3349 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 13:11:17.400  1174  3349 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:17.400  1433  1448 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:17.400  1433  1448 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:17.400  3184  3371 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 13:11:17.400  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 13:11:17.400  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:17.400  1460  1777 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:17.400  1460  1777 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:17.400  3071  6891 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:17.400  3071  6891 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:17.410  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 13:11:17.410  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 13:11:17.420  3184  3280 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 13:11:17.420  3184  3184 I GKI_LINUX: GKI_exit_task 1 done
08-17 13:11:17.420  3184  3184 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-17 13:11:17.420  3184  3184 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 13:11:17.430  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:17.430  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-17 13:11:17.430  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 13:11:17.430  3184  3184 I art     : System.exit called, status: 0
,08-17 13:11:17.430  3184  3184 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 13:11:17.430  1174  1174 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
08-17 13:11:17.430  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 13:11:17.430  1174  1756 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
,08-17 13:11:17.430  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:17.430  1174  1174 D BluetoothTile:  getBluetoothState : 10
,08-17 13:11:17.430  1174  1756 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
,08-17 13:11:17.440  1174  1174 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
08-17 13:11:17.440  1174  1174 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
08-17 13:11:17.440  1888  1888 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 13:11:17.440  1017  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 13:11:17.440  1017  2116 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 13:11:17.440  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 13:11:17.440  2046  2229 D BluetoothAdapter: 1052742631: getState() :  mService = null. Returning STATE_OFF
08-17 13:11:17.440  2046  2229 D BluetoothAdapter: 1052742631: getState() :  mService = null. Returning STATE_OFF
08-17 13:11:17.440  1017  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 13:11:17.440  1017  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 13:11:17.440  3071  3071 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:17.440  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:17.440  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:17.440  1017  1462 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.440  1017  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:17.440  1017  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:17.450   272   334 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-17 13:11:17.450   272   334 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-17 13:11:17.450   272   334 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1205348216) wakelock released: 1, error no: 0
08-17 13:11:17.450   272   334 I rmt_storage: 
,08-17 13:11:17.450   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb827d7c8
,08-17 13:11:17.470  6918  6918 D StrictMode: StrictMode policy violation; ~duration=247 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:17.470  6918  6918 D StrictMode: StrictMode policy violation; ~duration=243 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:17.470  6918  6918 D StrictMode: StrictMode policy violation; ~duration=241 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:17.470  6918  6918 D StrictMode: StrictMode policy violation; ~duration=240 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:17.470  6918  6918 D StrictMode: StrictMode policy violation; ~duration=236 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:17.480  1017  1257 I ActivityManager: Killing 6557:com.samsung.android.sm/1000 (adj 15): empty #21
08-17 13:11:17.470  6918  6918 D StrictMode: StrictMode policy violation; ~duration=210 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:17.470  6918  6918 D StrictMode: StrictMode policy violation; ~duration=209 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:17.470  6918  6918 D StrictMode: StrictMode policy violation; ~duration=208 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:17.470  6918  6918 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:17.490  2046  2046 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 13:11:17.490  2046  2046 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-17 13:11:17.490  1357  1357 I wpa_supplicant: Blacklist: Clear (all) 
08-17 13:11:17.500  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:17.500  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 13:11:17.500  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.500  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:17.500  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 13:11:17.500  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 13:11:17.510  1626  1626 I Hs20UtilService: Starting #8
08-17 13:11:17.510  1626  1693 I Hs20UtilService: Message received 5007
08-17 13:11:17.510  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 13:11:17.510  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 13:11:17.520  1017  2116 I ActivityManager: Process com.android.bluetooth (pid 3184)(adj 0) has died(31,717)
,08-17 13:11:17.520  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 13:11:17.520  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:17.520  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:17.520  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-17 13:11:17.530  1017  2100 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.530  1017  2100 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-17 13:11:17.530  1017  2100 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:17.530  1017  2100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-17 13:11:17.530  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:17.530  1357  1357 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 13:11:17.530  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:17.530  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:17.530  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:17.530  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:17.530  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:17.530  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:17.540  6918  6956 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-17 13:11:17.550  6971  6971 E Zygote  : MountEmulatedStorage()
08-17 13:11:17.550  6971  6971 E Zygote  : v2
08-17 13:11:17.550  6971  6971 I libpersona: KNOX_SDCARD checking this for 10102
08-17 13:11:17.550  6971  6971 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:17.550  6971  6971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:11:17.550  6971  6971 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:17.550  1017  2100 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6971 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-17 13:11:17.560  6971  6971 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 13:11:17.560  1017  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 13:11:17.560  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:17.560  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:17.560  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 13:11:17.580  6971  6971 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:17.580  6971  6971 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:17.600  6971  6971 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 13:11:17.640  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-17 13:11:17.640  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 13:11:17.640  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 13:11:17.640  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 13:11:17.640  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:17.640  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.640  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:17.640  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:17.640  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:17.640  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 13:11:17.640  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:17.650  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 13:11:17.650  2046  2229 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 13:11:17.650  1174  1174 D HotspotTile: onReceive : 1, 0
,08-17 13:11:17.650  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:17.650  3071  3071 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:17.660  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:17.660  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:17.660  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-17 13:11:17.670  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:17.680  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:17.680  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:17.810  6971  6993 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-17 13:11:17.820  6971  6993 I Babel_SMS: MmsConfig.loadMmsSettings
,08-17 13:11:17.820  6971  6993 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-17 13:11:17.820  6971  6993 I Babel_SMS: MmsConfig.loadFromDatabase
,08-17 13:11:17.840  6971  6993 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-17 13:11:17.840  6971  6993 I Babel_SMS: MmsConfig.loadFromResources
,08-17 13:11:17.840  6971  6993 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-17 13:11:17.840  6971  6993 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-17 13:11:17.860  1017  1539 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-17 13:11:17.860  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-17 13:11:17.860  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:17.860  1017  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:17.870  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 13:11:17.880  6971  6971 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 13:11:17.890  6971  6971 I Babel_Crash: startup - clean
,08-17 13:11:17.920  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 13:11:17.920  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 13:11:17.920  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 13:11:17.920  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 13:11:17.920  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:17.920  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:17.920  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:17.920  1017  1443 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 13:11:17.920  1017  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:17.920  1017  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:17.920  1017  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:17.920  1017  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:17.940  6996  6996 E Zygote  : MountEmulatedStorage()
08-17 13:11:17.940  6996  6996 E Zygote  : v2
08-17 13:11:17.940  6996  6996 I libpersona: KNOX_SDCARD checking this for 10064
08-17 13:11:17.940  6996  6996 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:17.940  6996  6996 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:17.940  6996  6996 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:17.940  1017  1443 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6996 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 13:11:17.940  6996  6996 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:17.960  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 13:11:17.960  6971  6971 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 13:11:17.960  6971  6971 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 13:11:17.960  6996  6996 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:17.960  6996  6996 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:17.970  6971  6971 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-17 13:11:17.970  6971  6971 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-17 13:11:17.980  6996  6996 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 13:11:17.990  6971  6971 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-17 13:11:17.990  6971  6971 W AudioCapabilities: Unsupported mime audio/x-ima
,08-17 13:11:17.990  6971  6971 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 13:11:17.990  6971  6971 W AudioCapabilities: Unsupported mime audio/evrc
,08-17 13:11:18.000  6996  6996 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 13:11:18.000  6996  6996 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 13:11:18.020  6971  6971 W VideoCapabilities: Unsupported mime video/wvc1
,08-17 13:11:18.030  6971  6971 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 13:11:18.030  6996  6996 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 13:11:18.030  1017  2100 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 13:11:18.040  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.040  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.040  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.040  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.040  6971  6971 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-17 13:11:18.040  6971  6971 W VideoCapabilities: Unsupported mime video/wvc1
08-17 13:11:18.040  6971  6971 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-17 13:11:18.050  6971  6971 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-17 13:11:18.050  7011  7011 E Zygote  : MountEmulatedStorage()
,08-17 13:11:18.050  7011  7011 E Zygote  : v2
08-17 13:11:18.050  7011  7011 I libpersona: KNOX_SDCARD checking this for 10065
08-17 13:11:18.050  7011  7011 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:18.050  7011  7011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 13:11:18.050  7011  7011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:18.060  7011  7011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-17 13:11:18.060  6971  6971 W VideoCapabilities: Unsupported mime video/x-ms-wmv8,
08-17 13:11:18.060  6971  6971 W VideoCapabilities: Unsupported mime video/mp43
08-17 13:11:18.060  1017  2100 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7011 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 13:11:18.060  1017  2100 I ActivityManager: Killing 6526:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-17 13:11:18.070  7011  7011 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 13:11:18.070  6971  6971 W VideoCapabilities: Unsupported mime video/sorenson
08-17 13:11:18.070  7011  7011 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.080  6971  6971 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 13:11:18.100  7011  7011 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 13:11:18.100  6971  6971 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 13:11:18.110  1017  1030 I ActivityManager: Killing 6578:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-17 13:11:18.110  1017  1539 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 13:11:18.110  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:18.120  1017  1539 W ActivityManager: userId = 0, bbcId = -10000,
08-17 13:11:18.120  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.120  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 13:11:18.120  1626  1626 I Hs20UtilService: Starting #9
08-17 13:11:18.120  1626  1693 I Hs20UtilService: Message received 5007
,08-17 13:11:18.120  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 13:11:18.120  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 13:11:18.120  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 13:11:18.120  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 13:11:18.120  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:18.120  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:18.120  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:18.130  1017  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 13:11:18.130  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:18.130  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:18.130  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.130  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 13:11:18.130  1017  1476 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 13:11:18.140  1626  1626 I Hs20UtilService: Starting #10
,08-17 13:11:18.140  1017  1476 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.receivers.NetworkReceiver}
08-17 13:11:18.140  1017  1476 W BroadcastQueue: android.os.TransactionTooLargeException
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-17 13:11:18.140  1017  1476 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 13:11:18.140  1017  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-17 13:11:18.140  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 13:11:18.140  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.140  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.140  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.140  1017  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.140  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 13:11:18.150  1626  1693 I Hs20UtilService: Message received 5011
,08-17 13:11:18.150  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc,
,08-17 13:11:18.150  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_6578/cgroup.procs: No such file or directory
,08-17 13:11:18.150  6971  6971 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 13:11:18.170   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 13:11:18.170  1017  1476 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 13:11:18.170  6971  6971 I vclib   : onServiceConnected
08-17 13:11:18.170  1017  1476 I ActivityManager: Killing 6609:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-17 13:11:18.170  7027  7027 E Zygote  : MountEmulatedStorage()
08-17 13:11:18.170  7027  7027 E Zygote  : v2
08-17 13:11:18.170  7027  7027 I libpersona: KNOX_SDCARD checking this for 1000
08-17 13:11:18.170  7027  7027 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:18.170  7027  7027 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:18.180  7027  7027 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:18.180  7027  7027 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:18.190  1017  1044 D Tethering: interfaceRemoved wlan0
,08-17 13:11:18.190  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 13:11:18.200  7027  7027 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:18.200  7027  7027 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.230  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 13:11:18.230  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-17 13:11:18.230  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 13:11:18.230  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 13:11:18.230  1017  1490 I ActivityManager: Killing 6627:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-17 13:11:18.240  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.240  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.240  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.240  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:18.240  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.240  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.240  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:18.240  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.240  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.250  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
08-17 13:11:18.250  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.250  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.250  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.250  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.250  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.260  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.260  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.260  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.260  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
08-17 13:11:18.260  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.260  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.260  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:18.260  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.260  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.260  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.260  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.260  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.270  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
08-17 13:11:18.270  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.270  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.270  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.270  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.270  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.270  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.270  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.270  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.280  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.280  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.280  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.280  1017  1017 W ActivityManager: userId = 0, bbcId = -10000,
08-17 13:11:18.280  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.280  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.280  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.280  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.280  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-17 13:11:18.290  3071  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:18.290  1017  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 13:11:18.290  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 13:11:18.290  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.290  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:18.290  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 13:11:18.300  3071  3071 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:18.300  3071  3071 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 13:11:18.300  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:18.300  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 13:11:18.310  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 13:11:18.310  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 13:11:18.310  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.310  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.310  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.320  7044  7044 E Zygote  : MountEmulatedStorage()
08-17 13:11:18.320  7044  7044 E Zygote  : v2
08-17 13:11:18.320  7044  7044 I libpersona: KNOX_SDCARD checking this for 1002
08-17 13:11:18.320  7044  7044 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:18.320  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 13:11:18.320  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 13:11:18.320  1017  1135 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7044 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-17 13:11:18.320  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:18.340  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:18.340  7044  7044 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.360  7044  7044 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.,
08-17 13:11:18.360  7044  7044 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 13:11:18.370  1017  1044 D Tethering: interfaceRemoved p2p0
,08-17 13:11:18.370  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 13:11:18.380  7044  7044 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding GattService
,08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding HeadsetService
08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding HidService
08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding HealthService
08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding PanService
08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding SapService
08-17 13:11:18.410  7044  7044 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 13:11:18.420  7044  7044 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 13:11:18.420  7044  7044 D BtSettings.ProfileConfig: Adding SapClientService
08-17 13:11:18.420  7044  7044 D BtSettings.ProfileConfig: Adding HidDevService
,08-17 13:11:18.420  7044  7044 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 13:11:18.420  1017  1539 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 13:11:18.420  1017  1539 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.420  1017  1539 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.420  1017  1539 D SettingsProvider: selectionArgs: false
,08-17 13:11:18.420  1017  1539 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.420  1017  1539 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 13:11:18.420  1017  1539 D SettingsProvider: ret = -1
,08-17 13:11:18.420  1017  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 13:11:18.420  1017  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.420  1017  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.420  1017  1490 D SettingsProvider: selectionArgs: false
08-17 13:11:18.420  1017  1490 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.420  1017  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.420  1017  1490 D SettingsProvider: ret = -1
,08-17 13:11:18.420  1017  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 13:11:18.420  1017  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.420  1017  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.420  1017  1483 D SettingsProvider: selectionArgs: false
08-17 13:11:18.420  1017  1483 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.420  1017  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.420  1017  1483 D SettingsProvider: ret = -1
,08-17 13:11:18.420  1017  1135 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 13:11:18.420  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.420  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.420  1017  1135 D SettingsProvider: selectionArgs: false
08-17 13:11:18.420  1017  1135 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.420  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.420  1017  1135 D SettingsProvider: ret = -1
,08-17 13:11:18.420  1017  2116 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 13:11:18.420  1017  2116 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.420  1017  2116 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.420  1017  2116 D SettingsProvider: selectionArgs: false
08-17 13:11:18.420  1017  2116 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.420  1017  2116 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.420  1017  2116 D SettingsProvider: ret = -1
,08-17 13:11:18.420  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 13:11:18.420  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.420  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 13:11:18.420  1017  1029 D SettingsProvider: selectionArgs: false
08-17 13:11:18.420  1017  1029 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.420  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.420  1017  1029 D SettingsProvider: ret = -1
,08-17 13:11:18.430  1017  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
08-17 13:11:18.430  1017  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:18.430  1017  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 13:11:18.430  1017  1476 D SettingsProvider: selectionArgs: false
,08-17 13:11:18.430  1017  1476 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:18.430  1017  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.430  1017  1476 D SettingsProvider: ret = -1
,08-17 13:11:18.430  1017  2092 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 13:11:18.430  1017  2092 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.430  1017  2092 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.430  1017  2092 D SettingsProvider: selectionArgs: false
08-17 13:11:18.430  1017  2092 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.430  1017  2092 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.430  1017  2092 D SettingsProvider: ret = -1
,08-17 13:11:18.430  1017  2100 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 13:11:18.430  1017  2100 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.430  1017  2100 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.430  1017  2100 D SettingsProvider: selectionArgs: false
08-17 13:11:18.430  1017  2100 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.430  1017  2100 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.430  1017  2100 D SettingsProvider: ret = -1
,08-17 13:11:18.430  1017  1445 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:18.430  1017  1445 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:18.430  1017  1445 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.430  1017  1445 D SettingsProvider: selectionArgs: false
08-17 13:11:18.430  1017  1445 D SettingsProvider: selectionArgs: 1002
08-17 13:11:18.430  1017  1445 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 13:11:18.430  1017  1445 D SettingsProvider: ret = -1
,08-17 13:11:18.440  1017  1443 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService,
,08-17 13:11:18.440  1017  1443 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.440  1017  1443 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-17 13:11:18.440  1017  1443 D SettingsProvider: selectionArgs: false
08-17 13:11:18.440  1017  1443 D SettingsProvider: selectionArgs: 1002,
08-17 13:11:18.440  1017  1443 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.440  1017  1443 D SettingsProvider: ret = -1,
,08-17 13:11:18.440  1017  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-17 13:11:18.440  1017  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:18.440  1017  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:18.440  1017  1462 D SettingsProvider: selectionArgs: false
08-17 13:11:18.440  1017  1462 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:18.440  1017  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:18.440  1017  1462 D SettingsProvider: ret = -1
,08-17 13:11:18.450  1017  1257 I ActivityManager: Killing 6644:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-17 13:11:18.460  2046  2046 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:18.460  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:11:18.460  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 13:11:18.470  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:18.470  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:18.470  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:18.480  2046  7060 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 13:11:18.480  1017  2116 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:18.490  2046  2046 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 13:11:18.490  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:18.490  1017  2116 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:18.490  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:18.510  1017  2116 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-17 13:11:18.510  1017  2116 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:18.510  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:18.510  1017  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-17 13:11:18.510  1017  2116 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:18.510  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 13:11:18.510  1626  1626 I Hs20UtilService: Starting #11
08-17 13:11:18.510  1626  1693 I Hs20UtilService: Message received 5011
,08-17 13:11:18.510  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:18.510  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:18.510  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:18.520  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 13:11:18.520  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 13:11:18.520  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-17 13:11:18.520  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 13:11:18.530  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-17 13:11:18.530  2046  7060 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 13:11:18.530  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.530  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.530  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.530  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.540  7061  7061 E Zygote  : MountEmulatedStorage(),
08-17 13:11:18.540  7061  7061 I libpersona: KNOX_SDCARD checking this for 1000
08-17 13:11:18.540  7061  7061 E Zygote  : v2
,08-17 13:11:18.540  7061  7061 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:18.540  7061  7061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:18.540  7061  7061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:18.540  1017  1030 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7061 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 13:11:18.550  7061  7061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:18.560  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:18.560  7061  7061 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.580  7061  7061 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true,
08-17 13:11:18.580  7061  7061 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-17 13:11:18.580  7061  7061 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-17 13:11:18.600  7061  7061 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-17 13:11:18.600  7061  7061 I PCWCLIENTTRACE_PushUtil: sales region : global
08-17 13:11:18.600  7061  7061 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-17 13:11:18.600  7061  7061 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:18.600  1017  1445 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-17 13:11:18.600  1017  1445 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-17 13:11:18.600  7061  7076 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-17 13:11:18.620  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-17 13:11:18.620  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.620  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.620  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.620  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.620  1803  1803 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
,08-17 13:11:18.630  7078  7078 E Zygote  : MountEmulatedStorage()
,08-17 13:11:18.630  7078  7078 E Zygote  : v2
08-17 13:11:18.630  7078  7078 I libpersona: KNOX_SDCARD checking this for 10121
08-17 13:11:18.630  7078  7078 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:18.630  7078  7078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:18.630  7078  7078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 13:11:18.640  1017  1042 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7078 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-17 13:11:18.640  7078  7078 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-17 13:11:18.640  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-17 13:11:18.640  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.640  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.640  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.640  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.660   313   313 I art     : Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 22.067ms
,08-17 13:11:18.670  7078  7078 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 13:11:18.670  7078  7078 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.680   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 649us total 16.354ms,
,08-17 13:11:18.700   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 18.587ms,
,08-17 13:11:18.710  7093  7093 E Zygote  : MountEmulatedStorage()
,08-17 13:11:18.710  7093  7093 E Zygote  : v2
08-17 13:11:18.710  7093  7093 I libpersona: KNOX_SDCARD checking this for 10001
08-17 13:11:18.710  7093  7093 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:18.710  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7093 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-17 13:11:18.710  7093  7093 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:18.710  7093  7093 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:18.720  7093  7093 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:18.720  1017  1445 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-17 13:11:18.730  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.730  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.730  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.730  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.740  2492  3288 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
,08-17 13:11:18.740  7078  7078 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 13:11:18.740  7078  7078 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-17 13:11:18.740  7078  7078 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 13:11:18.750  7107  7107 E Zygote  : MountEmulatedStorage()
,08-17 13:11:18.750  7107  7107 E Zygote  : v2
08-17 13:11:18.750  7107  7107 I libpersona: KNOX_SDCARD checking this for 10031
08-17 13:11:18.750  7107  7107 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:18.750  1017  1445 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7107 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-17 13:11:18.750  7107  7107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:18.760  7093  7093 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-17 13:11:18.760  1803  1803 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-17 13:11:18.760  1803  1803 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-17 13:11:18.760  1803  1803 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-17 13:11:18.760  1803  1803 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-17 13:11:18.760  7107  7107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:18.760  7107  7107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:18.760  7093  7093 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.770  1803  1803 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-17 13:11:18.770  7078  7078 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
08-17 13:11:18.770  1803  1803 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-17 13:11:18.780  1017  1445 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-17 13:11:18.780  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.780  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.780  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.780  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.780  7107  7107 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:18.790  7107  7107 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.790  7123  7123 E Zygote  : MountEmulatedStorage()
08-17 13:11:18.790  7123  7123 E Zygote  : v2
08-17 13:11:18.790  7123  7123 I libpersona: KNOX_SDCARD checking this for 10077
08-17 13:11:18.790  7123  7123 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:18.790  7123  7123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:18.800  1017  1445 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7123 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 13:11:18.800  7123  7123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 13:11:18.800  7123  7123 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-17 13:11:18.800  7078  7078 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-17 13:11:18.810  7078  7078 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-17 13:11:18.810  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-17 13:11:18.810  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.810  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.810  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.810  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.820  7123  7123 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 13:11:18.820  7123  7123 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.830  7138  7138 E Zygote  : MountEmulatedStorage()
08-17 13:11:18.830  7138  7138 E Zygote  : v2
08-17 13:11:18.830  7138  7138 I libpersona: KNOX_SDCARD checking this for 10141
08-17 13:11:18.830  7138  7138 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:18.830  1017  1030 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7138 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-17 13:11:18.830  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:11:18.830  1017  1030 I ActivityManager: Killing 6589:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-17 13:11:18.830  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 13:11:18.830  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:18.840  7107  7107 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-17 13:11:18.840  1017  1257 I ActivityManager: Killing 6662:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-17 13:11:18.850  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:18.850  7138  7138 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.860  1017  1462 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-17 13:11:18.860  2763  7153 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-17 13:11:18.860  1017  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.860  1017  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.860  1017  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.860  1017  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.870  2763  7153 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-17 13:11:18.870  2763  7153 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-17 13:11:18.870  2763  7153 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-17 13:11:18.870  7138  7138 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-17 13:11:18.870  7138  7138 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 13:11:18.870  7138  7138 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-17 13:11:18.870  7138  7138 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-17 13:11:18.870  2763  7153 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-17 13:11:18.880  7154  7154 E Zygote  : MountEmulatedStorage()
,08-17 13:11:18.880  7154  7154 E Zygote  : v2
08-17 13:11:18.880  7154  7154 I libpersona: KNOX_SDCARD checking this for 10032
08-17 13:11:18.880  7154  7154 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:18.880  1017  1462 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7154 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 13:11:18.880  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:18.890  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:18.890  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-17 13:11:18.920  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:18.920  7154  7154 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:18.930  1017  2092 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 13:11:18.960  1017  1476 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 13:11:18.970  7154  7171 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-17 13:11:18.970  7154  7171 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-17 13:11:18.970  7154  7171 D SPPClientService: PushLog.txt file is not deleted.
,08-17 13:11:18.970  7154  7171 D SPPClientService: PushLog.txt file is not deleted.
08-17 13:11:18.970  7154  7171 D SPPClientService: ============PushLog. stop!
08-17 13:11:18.980  7154  7154 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
08-17 13:11:18.980  1017  1445 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
08-17 13:11:18.980  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.980  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.980  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:18.980  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:18.990  7175  7175 E Zygote  : MountEmulatedStorage()
08-17 13:11:18.990  7175  7175 I libpersona: KNOX_SDCARD checking this for 10036
08-17 13:11:18.990  7175  7175 E Zygote  : v2
08-17 13:11:18.990  7175  7175 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:19.000  7175  7175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 13:11:19.000  1017  1443 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 13:11:19.000  7175  7175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:19.000  7175  7175 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-17 13:11:19.000  1017  1445 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7175 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 13:11:19.000  1017  1445 I ActivityManager: Killing 6382:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-17 13:11:19.010  1017  1135 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-17 13:11:19.010  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-17 13:11:19.010  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:19.010  1017  1135 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-17 13:11:19.010  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-17 13:11:19.020  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:19.020  7175  7175 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:19.020  1017  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 13:11:19.050  7154  7190 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-17 13:11:19.070  7175  7175 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@15b8cbe2
,08-17 13:11:19.080  7175  7175 I SA      : [SSP] onCreated
,08-17 13:11:19.090  1017  1483 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 13:11:19.090  1017  1490 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-17 13:11:19.090  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:19.090  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.090  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.090  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:19.090  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 13:11:19.100  7175  7175 I SA      : [TPM] There is no property file
,08-17 13:11:19.110  7201  7201 E Zygote  : MountEmulatedStorage()
,08-17 13:11:19.110  7201  7201 E Zygote  : v2
08-17 13:11:19.110  7201  7201 I libpersona: KNOX_SDCARD checking this for 10068
08-17 13:11:19.110  7201  7201 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:19.110  7201  7201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:19.110  7175  7175 I SA      : [SCU] isHaveSA() - false
08-17 13:11:19.110  1017  1490 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7201 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-17 13:11:19.110  1017  1135 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
08-17 13:11:19.110  7201  7201 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:19.110  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.110  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.110  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.110  1017  1135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.110  7175  7175 I SA      : [TPM] getModelProperty : null
08-17 13:11:19.110  7175  7175 I SA      : [TPM] getCSCProperty : null
,08-17 13:11:19.110  7201  7201 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 13:11:19.110  7175  7175 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-17 13:11:19.110  7175  7175 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-17 13:11:19.110  7175  7175 I SA      : [DM] TFT FEATURE: false
,08-17 13:11:19.120  7175  7175 I SA      : [DM] init START
,08-17 13:11:19.120  7175  7175 I SA      : [DM] This device is not a Vodafone
,08-17 13:11:19.130  7211  7211 E Zygote  : MountEmulatedStorage(),
08-17 13:11:19.130  1017  1135 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7211 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 13:11:19.130  7211  7211 E Zygote  : v2
08-17 13:11:19.130  7211  7211 I libpersona: KNOX_SDCARD checking this for 1000
08-17 13:11:19.130  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:11:19.130  7211  7211 I libpersona: KNOX_SDCARD not a persona,
08-17 13:11:19.130  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
08-17 13:11:19.130  1017  1135 I ActivityManager: Killing 6087:com.android.mms/u0a41 (adj 15): empty #21
,08-17 13:11:19.140  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:19.140  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:19.150  7175  7175 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-17 13:11:19.150  7175  7175 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-17 13:11:19.160  7175  7175 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-17 13:11:19.170  7201  7201 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 13:11:19.170  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:19.170  7201  7201 D ActivityThread: Added TimaKeyStore provider
08-17 13:11:19.170  7211  7211 D ActivityThread: Added TimaKeyStore provider
08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
08-17 13:11:19.170   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-17 13:11:19.170  7175  7175 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-17 13:11:19.180  7175  7175 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-17 13:11:19.180  7175  7175 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-17 13:11:19.180  7175  7175 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-17 13:11:19.190  1017  1135 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 13:11:19.190  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-17 13:11:19.190  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-17 13:11:19.190  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:19.190  7175  7175 I SA      : [SCU] isHaveSA() - false
08-17 13:11:19.190  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:19.190  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-17 13:11:19.190  7175  7175 I SA      : support phone number id : false
08-17 13:11:19.190  7175  7175 I SA      : [DM] Supports Ref Jpn : true
08-17 13:11:19.190  7175  7175 I SA      : [DM] init END
08-17 13:11:19.190  7175  7175 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-17 13:11:19.190  1017  1445 D RCPManagerService: exchangeData() failure , invalid userId
,08-17 13:11:19.190  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-17 13:11:19.200  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:19.200  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.200  7175  7175 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-17 13:11:19.200  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.200  7175  7175 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-17 13:11:19.200  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:19.200  7201  7201 D BadgeProvider: onCreate,
08-17 13:11:19.200  7201  7201 D BadgeProvider: DatabaseHelper
,08-17 13:11:19.210   287   287 E SMD     : DCD OFF
,08-17 13:11:19.210  7235  7235 E Zygote  : MountEmulatedStorage()
,08-17 13:11:19.210  7235  7235 E Zygote  : v2
08-17 13:11:19.210  7235  7235 I libpersona: KNOX_SDCARD checking this for 10009
08-17 13:11:19.210  7235  7235 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:19.210  7235  7235 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-17 13:11:19.210  1017  1029 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7235 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-17 13:11:19.220  1017  1029 I ActivityManager: Killing 6702:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21,
08-17 13:11:19.220  1017  1029 I ActivityManager: Killing 6684:com.sec.esdk.elm/u0a90 (adj 15): empty #22
,08-17 13:11:19.220  7235  7235 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:19.220  7235  7235 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-17 13:11:19.220  1017  1483 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-17 13:11:19.220  7175  7175 I SA      : [SLFUCHKMGR] constructor called
08-17 13:11:19.220  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-17 13:11:19.220  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:19.220  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:19.220  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-17 13:11:19.230  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-17 13:11:19.230  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.230  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.230  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.230  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:19.240  7211  7211 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-17 13:11:19.240  6971  7234 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 13:11:19.250  1017  1135 D CountryDetector: No listener is left
,08-17 13:11:19.250  7235  7235 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:19.260  7235  7235 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:19.260  7251  7251 E Zygote  : MountEmulatedStorage(),
08-17 13:11:19.260  7251  7251 E Zygote  : v2
08-17 13:11:19.260  7251  7251 I libpersona: KNOX_SDCARD checking this for 10110
,08-17 13:11:19.260  7251  7251 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:11:19.260  7251  7251 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:19.260  7251  7251 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:19.260  1017  1029 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7251 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 13:11:19.260  7251  7251 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 13:11:19.270  7175  7175 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-17 13:11:19.270  1017  1030 I ActivityManager: Killing 6339:com.google.android.gms:car/u0a11 (adj 15): empty #21
08-17 13:11:19.270  7175  7175 I SA      : [OR] == isSIMCardReady false ==
,08-17 13:11:19.290  7175  7175 I SA      : [SCU] == networkStateCheck == false
,08-17 13:11:19.290  7251  7251 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 13:11:19.290  7251  7251 D ActivityThread: Added TimaKeyStore provider
08-17 13:11:19.300  7175  7175 I SA      : [OR] onReceive END
,08-17 13:11:19.300  1017  1029 I ActivityManager: Killing 6537:com.android.calendar/u0a131 (adj 15): empty #21
,08-17 13:11:19.310  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:19.410  7211  7211 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-17 13:11:19.410  1017  1490 I art     : Explicit concurrent mark sweep GC freed 60540(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 24MB/36MB, paused 2.541ms total 192.059ms
,08-17 13:11:19.420  7211  7211 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-17 13:11:19.430  7211  7211 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:19.430  7211  7211 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-17 13:11:19.430  7211  7211 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-17 13:11:19.430  7211  7211 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-17 13:11:19.430  1017  2116 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-17 13:11:19.430  1017  2116 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.430  1017  2116 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.430  1017  2116 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:19.430  1017  2116 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:19.430  7201  7217 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-17 13:11:19.440  7272  7272 E Zygote  : MountEmulatedStorage(),
08-17 13:11:19.440  7272  7272 I libpersona: KNOX_SDCARD checking this for 10008
08-17 13:11:19.440  7272  7272 E Zygote  : v2
08-17 13:11:19.440  7272  7272 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:19.440  7272  7272 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:19.450  7272  7272 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:19.450  1017  2116 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7272 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 13:11:19.450  1017  2116 I ActivityManager: Killing 6048:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-17 13:11:19.450  7272  7272 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-17 13:11:19.450  1017  2116 I ActivityManager: Killing 5836:com.android.vending/u0a26 (adj 15): empty #21
,08-17 13:11:19.460  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 13:11:19.460  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-17 13:11:19.460  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:19.460  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:19.460  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:19.470   313   313 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 24.988ms
,08-17 13:11:19.470  7272  7272 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:19.470  7272  7272 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:19.490  4802  7285 I iu.SyncManager: SYNC; picasa accounts
,08-17 13:11:19.490   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.915ms,
08-17 13:11:19.490  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-17 13:11:19.490  1017  2092 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-17 13:11:19.490  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-17 13:11:19.490  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-17 13:11:19.500  7201  7217 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-17 13:11:19.500  7201  7217 D BadgeProvider: sendNotify, [notify] : null
08-17 13:11:19.500  1484  1484 D Launcher.Model: reloadBadges entered.
08-17 13:11:19.500  7201  7217 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-17 13:11:19.500  7201  7217 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-17 13:11:19.500  7201  7217 D BadgeProvider: update, [UpdateCount] : 1
,08-17 13:11:19.510   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 17.218ms
,08-17 13:11:19.520  4802  4802 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-17 13:11:19.550  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 13:11:19.560  1017  1443 I ActivityManager: Killing 6812:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-17 13:11:19.560  2876  2876 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 13:11:19 GMT+02:00 2016
,08-17 13:11:19.570  1017  1483 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 13:11:19.570  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-17 13:11:19.570  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:19.570  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:19.570  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 13:11:19.580  2876  2876 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 13:11:19.580  2876  2876 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 13:11:19.580  2876  2876 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 13:11:19.580  2876  2876 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-17 13:11:19.590  2876  7288 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-17 13:11:19.590  2876  7288 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-17 13:11:19.590  2876  7288 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-17 13:11:19.590  2876  7288 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-17 13:11:19.590  2876  2876 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-17 13:11:19.690  7251  7251 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 13:11:19.690  7251  7251 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 13:11:19.690  7251  7251 I GAv4    :   adb logcat -s GAv4
,08-17 13:11:19.700   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 13:11:19.700   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 13:11:19.700  7251  7292 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 13:11:19.710   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 13:11:19.710   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 13:11:19.710  7251  7251 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 13:11:19.710  1017  1029 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 13:11:19.710  7251  7292 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 13:11:19.720   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-17 13:11:19.720   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 13:11:19.720  7251  7294 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-17 13:11:19.720  7251  7251 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 13:11:19.720   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-17 13:11:19.720   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 13:11:19.720  7251  7294 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-17 13:11:19.730  7251  7295 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 13:11:19.790  1017  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 13:11:19.790  1017  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 13:11:19.790  1017  1029 D SecContentProvider2: mCursor = null
,08-17 13:11:19.790  1017  1029 D WifiService: setWifiEnabled: true pid=6756, uid=10171
08-17 13:11:19.800  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 13:11:19.800  1017  1029 W WifiService: Failed getting userId using ActivityManagerNative
08-17 13:11:19.800  1017  1029 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 13:11:19.800  1017  1029 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 13:11:19.800  1017  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 13:11:19.800  1017  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 13:11:19.800  1017  1029 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 13:11:19.800  1017  1029 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 13:11:19.800  1017  1029 D SettingsProvider: name = wifi_on
,08-17 13:11:19.800  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 13:11:19.970  1017  1539 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:19.970  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:19.970  1017  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:19.970  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-17 13:11:20.010  7251  7251 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-17 13:11:20.030  7251  7251 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 984-986)
,08-17 13:11:20.030  7251  7251 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 13:11:20.040  7251  7251 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d0be25}
,08-17 13:11:20.040  7251  7251 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-17 13:11:20.040  7251  7251 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 13:11:20.060  7251  7251 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-17 13:11:20.060  7251  7251 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 13:11:20.060  7251  7251 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 13:11:20.080  7251  7251 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 13:11:20.080  7251  7251 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 13:11:20.080  7251  7251 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 13:11:20.080  7251  7251 I Adreno-EGL: Local Branch: 
08-17 13:11:20.080  7251  7251 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 13:11:20.080  7251  7251 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 13:11:20.080  7251  7251 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 13:11:20.130  7251  7330 W cr.media: Requires BLUETOOTH permission
,08-17 13:11:20.140  7251  7251 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 13:11:20.150  7251  7251 I NSApplication: Starting up...
,08-17 13:11:20.150  1017  1476 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 13:11:20.160  1017  1443 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-17 13:11:20.160  1017  1483 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-17 13:11:20.170  1017  1044 D Tethering: interfaceAdded wlan0
,08-17 13:11:20.170  1017  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:20.170  1017  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:20.170  1017  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:20.170  1017  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:20.170   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 13:11:20.170  1017  1130 E Tethering: No numeric data
,08-17 13:11:20.180  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:20.180  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-17 13:11:20.180  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 13:11:20.190  1017  1044 D Tethering: interfaceAdded p2p0,
08-17 13:11:20.190   277  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-17 13:11:20.190  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-17 13:11:20.190   277  1016 D SoftapController: Softap fwReload - Ok
08-17 13:11:20.190  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 13:11:20.190  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 13:11:20.190  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-17 13:11:20.190   277  1016 D CommandListener: Setting iface cfg,
08-17 13:11:20.190  7336  7336 I libpersona: KNOX_SDCARD checking this for 10117
08-17 13:11:20.190  7336  7336 E Zygote  : MountEmulatedStorage()
08-17 13:11:20.190  7336  7336 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:20.190  7336  7336 E Zygote  : v2,
08-17 13:11:20.190   277  1016 D CommandListener: Trying to bring down wlan0
08-17 13:11:20.200   277  1016 D CommandListener: Clearing all IP addresses on wlan0
08-17 13:11:20.200  7336  7336 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:20.200  1017  1483 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7336 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 13:11:20.200  7336  7336 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:20.200  7336  7336 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-17 13:11:20.200  1017  1483 I ActivityManager: Killing 6996:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-17 13:11:20.200  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
08-17 13:11:20.200  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 13:11:20.200  1017  1130 D Tethering: clearTetheredNotification()
08-17 13:11:20.200  1017  1130 D Tethering: InitialState.processMessage what=4
,08-17 13:11:20.220  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:20.220  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-17 13:11:20.220  1017  1130 E Tethering: No numeric data
,08-17 13:11:20.220  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:20.220  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 13:11:20.230  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 13:11:20.230  1017  1130 D Tethering: clearTetheredNotification()
,08-17 13:11:20.230  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 13:11:20.230  1174  1174 D HotspotTile: updateTetherState():false, false
08-17 13:11:20.230  1017  1124 V NetworkStats: performPollLocked() took 8ms
08-17 13:11:20.230  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:20.230  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 13:11:20.230  1174  1174 D HotspotTile: updateTetherState():false, false
,08-17 13:11:20.230  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:20.230  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-17 13:11:20.230  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:20.230  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:20.230  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 13:11:20.230  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:20.240  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:20.240  1017  1124 V NetworkStats: performPollLocked() took 4ms
,08-17 13:11:20.240  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:20.240  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:20.240  7336  7336 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:20.240  7336  7336 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:20.260  7344  7344 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-17 13:11:20.260  7344  7344 I wpa_supplicant: Successfully initialized wpa_supplicant
08-17 13:11:20.260  7344  7344 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 13:11:20.260  7336  7336 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 13:11:20.280  7344  7344 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-17 13:11:20.280   395   395 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7344
08-17 13:11:20.280   395   395 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-17 13:11:20.280  7344  7344 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 13:11:20.280  7344  7344 I wpa_supplicant: ssSupport state is = 1
08-17 13:11:20.280  7344  7344 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 13:11:20.280  7344  7344 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-17 13:11:20.280   395   395 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7344
08-17 13:11:20.280   395   395 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-17 13:11:20.300  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-17 13:11:20.310  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 13:11:20.310  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 13:11:20.310  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:20.310  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:20.310  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 13:11:20.310  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:20.310  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-17 13:11:20.310  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 13:11:20.310  1174  1174 D HotspotTile: onReceive : 2, 0,
08-17 13:11:20.310  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:20.310  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-17 13:11:20.320  3071  3071 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:20.320  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:20.320  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 13:11:20.470   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,08-17 13:11:20.470  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-17 13:11:20.510  7344  7344 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-17 13:11:20.510  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 13:11:20.530  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 13:11:20.530   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7344
08-17 13:11:20.530   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 13:11:20.530  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-17 13:11:20.530  7344  7344 I wpa_supplicant: ssSupport state is = 1
08-17 13:11:20.530  7344  7344 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:20.530  7344  7344 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-17 13:11:20.530  7344  7344 E wpa_supplicant: SIM READ ERROR
08-17 13:11:20.530  7344  7344 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:20.530  7344  7344 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 13:11:20.530  7344  7344 E wpa_supplicant: SIM READ ERROR
08-17 13:11:20.530  7344  7344 I wpa_supplicant: Blacklist: Clear (all) ,
08-17 13:11:20.530  7344  7344 I wpa_supplicant: wpa_default_ap_write_once
08-17 13:11:20.530  7344  7344 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 13:11:20.530  7344  7344 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:20.530  7344  7344 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 13:11:20.530  7344  7344 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-17 13:11:20.530  7344  7344 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 13:11:20.530  7344  7344 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 13:11:20.530  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 13:11:20.530  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:20.530  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 13:11:20.610  7344  7344 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-17 13:11:20.630  1017  1443 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-17 13:11:20.630  1017  1443 I ActivityManager: Killing 7011:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-17 13:11:20.640  1017  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:20.640  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:20.640  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:20.640  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:20.640  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 13:11:20.640  1626  1626 I Hs20UtilService: Starting #12
,08-17 13:11:20.640  1626  1693 I Hs20UtilService: Message received 5011
,08-17 13:11:20.650  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-17 13:11:20.650  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 13:11:20.650  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-17 13:11:20.650  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 13:11:20.850  7344  7344 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 13:11:20.850  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 13:11:20.860  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 13:11:20.860   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7344
08-17 13:11:20.860   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 13:11:20.860  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 13:11:20.860  7344  7344 I wpa_supplicant: ssSupport state is = 1,
,08-17 13:11:20.870  7344  7344 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-17 13:11:20.870  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-17 13:11:20.880  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-17 13:11:20.880   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7344,
,08-17 13:11:20.880   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 13:11:20.880  7344  7344 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-17 13:11:20.880  7344  7344 I wpa_supplicant: ssSupport state is = 1
08-17 13:11:20.880  7344  7344 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:20.880  7344  7344 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 13:11:20.880  7344  7344 E wpa_supplicant: SIM READ ERROR
08-17 13:11:20.880  7344  7344 I wpa_supplicant: wpa_default_ap_write_once
08-17 13:11:20.880  7344  7344 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 13:11:20.880  7344  7344 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 13:11:20.890  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 13:11:20.890  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 13:11:20.890  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-17 13:11:20.890  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 13:11:20.890  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-17 13:11:20.890  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-17 13:11:21.040  7344  7344 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 13:11:21.040  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 13:11:21.100  7344  7344 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 13:11:21.100  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-17 13:11:21.100  7344  7344 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 13:11:21.110  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-17 13:11:21.110  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 13:11:21.120  7344  7344 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-17 13:11:21.120  7344  7344 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:21.120  7344  7344 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-17 13:11:21.120  7344  7344 E wpa_supplicant: SIM READ ERROR
08-17 13:11:21.120  7344  7344 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 13:11:21.140  7344  7344 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 13:11:21.160  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 13:11:21.160  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:21.160  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:21.160  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:21.160  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 13:11:21.160  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:21.160  7344  7344 I wpa_supplicant: Skip scan - bUseNetwork false
08-17 13:11:21.160  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:21.160  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 13:11:21.160  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-17 13:11:21.160  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:21.170  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 13:11:21.170  1174  1174 D HotspotTile: onReceive : 3, 0
,08-17 13:11:21.170  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-17 13:11:21.170  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 13:11:21.170  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-17 13:11:21.170  3071  3071 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:21.170   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 13:11:21.170  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:21.170  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:21.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:21.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:21.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:21.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:21.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:21.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:21.170  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:21.170  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:21.170  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:21.180  1017  1257 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:21.180  1017  1257 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:21.180  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:21.180  1017  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:21.180  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 13:11:21.180  1017  1127 E WifiConfigStore: Not a HS20
08-17 13:11:21.180  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:21.180  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:21.180  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:21.180  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:21.180  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:21.180  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:21.180  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:21.180  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:21.180  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:21.180  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:21.180  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:21.180  1017  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 13:11:21.180  1626  1626 I Hs20UtilService: Starting #13
08-17 13:11:21.180  1626  1693 I Hs20UtilService: Message received 5011
,08-17 13:11:21.180  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 13:11:21.180  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 13:11:21.180  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
08-17 13:11:21.180  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 13:11:21.180  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 13:11:21.190  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 13:11:21.190  7344  7344 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 13:11:21.190  7344  7344 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 13:11:21.190  7344  7344 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 13:11:21.190  7344  7344 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 13:11:21.190  7344  7344 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 13:11:21.190  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 13:11:21.190  7344  7344 I wpa_supplicant: First Scan Start
,08-17 13:11:21.190  7344  7344 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 13:11:21.190  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-17 13:11:21.190  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 13:11:21.190  1017  1127 I WifiNative-HAL: startHal
08-17 13:11:21.190  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d68b88c
08-17 13:11:21.190  1017  1127 I WifiNative-HAL: Could not start hal
,08-17 13:11:21.190  6971  6971 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 13:11:21.200  1017  1127 E WifiNative-wlan0: do suspend true,
,08-17 13:11:21.200  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-17 13:11:21.200  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-17 13:11:21.200  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler },
,08-17 13:11:21.200  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
08-17 13:11:21.200  1017  1150 I WifiNative-HAL: startHal
08-17 13:11:21.200  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9e7399bc
,08-17 13:11:21.200  1017  1150 I WifiNative-HAL: Could not start hal
08-17 13:11:21.200  1017  1150 E WifiScanningService: could not start HAL
08-17 13:11:21.200  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 13:11:21.200  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 13:11:21.200  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-17 13:11:21.200  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 13:11:21.200  1017  1126 D WifiP2pService: P2pEnablingState
08-17 13:11:21.200  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215],
08-17 13:11:21.200  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-17 13:11:21.200   277  1016 D CommandListener: Setting iface cfg
08-17 13:11:21.200   277  1016 D CommandListener: Trying to bring up p2p0
08-17 13:11:21.210  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
08-17 13:11:21.200  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-17 13:11:21.200  1017  1151 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:21.210  1017  1126 D WifiP2pService: P2p socket connection successful
08-17 13:11:21.200  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 13:11:21.200  7344  7344 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-17 13:11:21.210  7344  7344 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 13:11:21.210  1017  1126 D WifiP2pService: P2pEnabledState
,08-17 13:11:21.210  7344  7344 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-17 13:11:21.210  1017  1127 E WifiStateMachine: Failed to set frequency band 0
08-17 13:11:21.210  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 13:11:21.210  1017  1127 D SecContentProvider2: mCursor = null
08-17 13:11:21.210  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-17 13:11:21.210  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-17 13:11:21.210  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-17 13:11:21.210  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 13:11:21.210  1017  1047 D WifiDisplayController: disconnect
08-17 13:11:21.210  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:21.210  1017  1047 D WifiDisplayController: updateConnection
08-17 13:11:21.210  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 13:11:21.210  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 13:11:21.210  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-17 13:11:21.210  1017  2100 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-17 13:11:21.210  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 13:11:21.210  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-17 13:11:21.210  1017  1127 D SecContentProvider2: mCursor = null
08-17 13:11:21.220  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-17 13:11:21.220  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-17 13:11:21.220  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 13:11:21.220  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
,08-17 13:11:21.220  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 13:11:21.220  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 13:11:21.220  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-17 13:11:21.220  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 13:11:21.220  1017  1126 D WifiP2pService: DeviceAddress: 0a:76:28
,08-17 13:11:21.230  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  secondary type: null
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  wps: 0
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  grpcapab: 0
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  devcapab: 0
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  status: 3
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  wfdInfo: null
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-17 13:11:21.230  1017  1047 D WifiDisplayController:  SConnectInfo : null
08-17 13:11:21.230  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 13:11:21.230  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 13:11:21.230  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:21.230  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:21.230  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:21.230  1017  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-17 13:11:21.230  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-17 13:11:21.230  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:21.230  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:21.230  1017  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:21.240  7370  7370 E Zygote  : MountEmulatedStorage()
08-17 13:11:21.240  7370  7370 I libpersona: KNOX_SDCARD checking this for 10064
,08-17 13:11:21.240  7370  7370 E Zygote  : v2
08-17 13:11:21.240  7370  7370 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:21.240  1017  1490 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7370 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 13:11:21.250  7370  7370 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:21.250  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast,
08-17 13:11:21.250  1017  1126 D WifiP2pService: InactiveState
,08-17 13:11:21.250  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
08-17 13:11:21.250  7344  7344 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-17 13:11:21.250  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 13:11:21.250  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
08-17 13:11:21.250  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
08-17 13:11:21.250  7370  7370 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 13:11:21.250  7370  7370 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:21.270  7370  7370 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:21.270  7370  7370 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:21.280  7370  7370 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-17 13:11:21.300  7370  7370 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 13:11:21.300  7370  7370 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 13:11:21.320  7370  7370 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 13:11:21.330  1017  1443 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-17 13:11:21.330  1017  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:21.330  1017  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:21.330  1017  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:21.330  1017  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:21.340  7386  7386 E Zygote  : MountEmulatedStorage(),
08-17 13:11:21.340  7386  7386 I libpersona: KNOX_SDCARD checking this for 10065
08-17 13:11:21.340  7386  7386 E Zygote  : v2
08-17 13:11:21.340  7386  7386 I libpersona: KNOX_SDCARD not a persona
08-17 13:11:21.340  7386  7386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:11:21.340  1017  1443 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7386 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-17 13:11:21.340  1017  1443 I ActivityManager: Killing 6895:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-17 13:11:21.350  7386  7386 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:21.350  7386  7386 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:21.360  1017  3361 D SSRM:n  : SIOP:: AP = 360
,08-17 13:11:21.370  7386  7386 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:21.370  7386  7386 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:21.390  7386  7386 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 13:11:21.390  1017  1029 I ActivityManager: Killing 7044:com.android.bluetooth/1002 (adj 15): empty #21
,08-17 13:11:21.430  1017  3391 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 13:11:21.870  1017  2090 V SAMP_SPCM_test: CSC File load.. 
,08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time,
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,08-17 13:11:21.890  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
,08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,08-17 13:11:21.930  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-17 13:11:21.940  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-17 13:11:21.950  1017  2090 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time,
08-17 13:11:21.950  1017  2090 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-17 13:11:21.950  1017  2090 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:21.950  1017  2090 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:21.950  1017  2090 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:21.950  1017  2090 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:21.970  7401  7401 E Zygote  : MountEmulatedStorage()
,08-17 13:11:21.970  7401  7401 E Zygote  : v2
08-17 13:11:21.970  7401  7401 I libpersona: KNOX_SDCARD checking this for 1000
08-17 13:11:21.970  7401  7401 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:21.970  7401  7401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:21.970  1017  2090 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7401 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-17 13:11:21.970  7401  7401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:21.970  7401  7401 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:21.990  7401  7401 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-17 13:11:21.990  7401  7401 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:22.010  7401  7401 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 13:11:22.050  1017  2090 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-17 13:11:22.050  1017  1017 I ActivityManager: Killing 6918:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-17 13:11:22.170   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 13:11:22.210   287   287 E SMD     : DCD OFF
,08-17 13:11:22.410  7344  7344 I wpa_supplicant: nl80211: Received scan results (21 BSSes),
08-17 13:11:22.410  7344  7344 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 13:11:22.410  7344  7344 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-17 13:11:22.410  7344  7344 I wpa_supplicant: Trying to associate with  'G700'
08-17 13:11:22.410  7344  7344 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-17 13:11:22.410  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-17 13:11:22.410  1017  7365 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-17 13:11:22.430  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 13:11:22.430  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:22.560  7344  7344 E wpa_supplicant: Cmd 35605 not handled
08-17 13:11:22.560  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:22.560  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:22.560  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:22.560  7344  7344 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 13:11:22.560  7344  7344 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-17 13:11:22.560  7344  7344 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-17 13:11:22.560  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 13:11:22.560  7344  7344 I wpa_supplicant: Associated with F4.99.3E
08-17 13:11:22.560  7344  7344 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 13:11:22.560  7344  7344 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 13:11:22.560  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-17 13:11:22.560  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:22.560  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-17 13:11:22.560  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:22.560  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 13:11:22.560  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:22.560  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 13:11:22.560  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 13:11:22.560  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-17 13:11:22.570  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 13:11:22.570  7344  7344 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 13:11:22.570  7344  7344 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-17 13:11:22.570  7344  7344 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
08-17 13:11:22.570  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-17 13:11:22.570  7344  7344 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-17 13:11:22.570  7344  7344 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 13:11:22.570  1017  1130 E Tethering: No numeric data
08-17 13:11:22.570  7344  7344 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-17 13:11:22.570  7344  7344 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 13:11:22.570  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 13:11:22.570  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 13:11:22.570  1017  1130 D Tethering: clearTetheredNotification()
08-17 13:11:22.570  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-17 13:11:22.570  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 13:11:22.570  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-17 13:11:22.570  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 13:11:22.570  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:22.580  1017  1124 V NetworkStats: performPollLocked(flags=0x1),
08-17 13:11:22.580  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:22.580  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 13:11:22.580  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:22.580  1174  1174 D HotspotTile: updateTetherState():false, false
08-17 13:11:22.580  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 13:11:22.580  1017  1124 V NetworkStats: performPollLocked() took 5ms
,08-17 13:11:22.580  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:22.580  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-17 13:11:22.580  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:22.580  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:22.580  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-17 13:11:22.590  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 13:11:22.590  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 13:11:22.590  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:22.590  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 13:11:22.590  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 13:11:22.590  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:22.590  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.590  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.590  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.590  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.590  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:22.590  1017  1443 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:22.590  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:22.600  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:22.600  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:22.600  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 13:11:22.600  1626  1626 I Hs20UtilService: Starting #14
,08-17 13:11:22.600  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 13:11:22.600  1626  1693 I Hs20UtilService: Message received 5007
08-17 13:11:22.600  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 13:11:22.610  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 13:11:22.610  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:22.610  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 13:11:22.610  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:22.610  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:22.610  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:22.620   277  1016 D CommandListener: Setting iface cfg,
08-17 13:11:22.620  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-17 13:11:22.630  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 13:11:22.630  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:22.630  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 13:11:22.630  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:22.640  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 13:11:22.640  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:22.640  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.640  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.640  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.640  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.650  1017  1127 E WifiNative-wlan0: do suspend false
,08-17 13:11:22.650  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-17 13:11:22.650  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-17 13:11:22.650  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 13:11:22.650  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:22.800  1017  2092 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 13:11:22.800  1017  2092 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 13:11:22.800  1017  2092 D SecContentProvider2: mCursor = null
,08-17 13:11:22.800  1017  2092 D WifiService: setWifiEnabled: false pid=6756, uid=10171
,08-17 13:11:22.800  1017  2092 D SettingsProvider: name = wifi_on
,08-17 13:11:22.820  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:22.830  1017  1127 E WifiNative-wlan0: do suspend true,
,08-17 13:11:22.850  1017  1126 D WifiP2pService: InactiveState{ what=143375 },
,08-17 13:11:22.850  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 13:11:22.860   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-17 13:11:22.860  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 13:11:22.860  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:22.860  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.860  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.860  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.860  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.860  1017  1129 E ConnectivityService: updateNetworkInfo(),
08-17 13:11:22.860  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-17 13:11:22.860  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:22.860  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-17 13:11:22.860  1017  1126 D WifiP2pService: InactiveState{ what=131204 }
08-17 13:11:22.870  1017  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 13:11:22.870   277  1016 E Netd    : no such netId 503
08-17 13:11:22.870  1017  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-17 13:11:22.870  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 13:11:22.870  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-17 13:11:22.880  1017  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-17 13:11:22.880  1017  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-17 13:11:22.880  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:22.880  1017  1129 V NetworkStats: updateIfacesLocked()
08-17 13:11:22.880  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-17 13:11:22.880  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:22.880  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:22.880  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 13:11:22.880  1017  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:22.880  1017  1017 D RttService: SCAN_AVAILABLE : 1
,08-17 13:11:22.880  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:22.890  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:22.890  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 13:11:22.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.890  7420  7420 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-17 13:11:22.890  1017  1129 V NetworkStats: performPollLocked() took 17ms
08-17 13:11:22.900  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:22.900  7420  7420 I dhcpcd  : version 5.5.6 starting
,08-17 13:11:22.900  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 13:11:22.900  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-17 13:11:22.900  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 13:11:22.900  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 13:11:22.900  7420  7420 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-17 13:11:22.900  1017  1443 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:22.900  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:22.900  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 13:11:22.900  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:22.900  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 13:11:22.900  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 13:11:22.900  1017  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-17 13:11:22.900  1017  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-17 13:11:22.900  1017  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-17 13:11:22.900  1017  7417 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:22.910  1017  1126 D WifiP2pService: P2pDisablingState
08-17 13:11:22.900  1017  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-17 13:11:22.910  1017  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-17 13:11:22.900  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:22.910  1017  1126 D WifiP2pService: p2p socket connection lost
08-17 13:11:22.900  1017  7417 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 13:11:22.900  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:22.910  1017  1126 D WifiP2pService: P2pDisabledState
,08-17 13:11:22.910  1626  1626 I Hs20UtilService: Starting #15
08-17 13:11:22.910  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-17 13:11:22.910  1017  1127 E WifiNative-wlan0: do suspend true
08-17 13:11:22.910  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-17 13:11:22.910  1626  1693 I Hs20UtilService: Message received 5007
08-17 13:11:22.910  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 13:11:22.910  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:22.910  1017  1047 D WifiDisplayController: disconnect
08-17 13:11:22.910  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:22.910  1017  1047 D WifiDisplayController: updateConnection
08-17 13:11:22.910  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 13:11:22.910  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 13:11:22.920  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 13:11:22.920  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 13:11:22.920  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 13:11:22.920  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-17 13:11:22.920  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-17 13:11:22.920  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-17 13:11:22.930  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 13:11:22.930  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 13:11:22.930  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:22.930  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:22.930  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:22.930  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 13:11:22.930  1017  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 13:11:22.930  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-17 13:11:22.940  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 13:11:22.940  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 13:11:22.940  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 13:11:22.940  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 13:11:22.940  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:22.940  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:22.940  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:22.950  1017  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-17 13:11:22.950  1017  1126 D WifiP2pService: DefaultState{ what=143375 }
08-17 13:11:22.950  7370  7370 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 13:11:22.950  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:22.950  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:22.950  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.950  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.950  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.950  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.950  7370  7370 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-17 13:11:22.950  7370  7370 D FileShare-Client: Outbound.stopDelayTimer - 
08-17 13:11:22.950   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-17 13:11:22.960  7386  7386 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 13:11:22.960  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 13:11:22.960  7344  7344 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:22.970  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:22.970  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 13:11:22.970  1017  1127 D SecContentProvider2: mCursor = null
08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:22.970  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.970  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:22.970  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,08-17 13:11:22.970  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-17 13:11:22.970  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 13:11:22.990  3071  3071 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:22.990  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:22.990  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:22.990  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.990  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:22.990  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:22.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:22.990  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:22.990  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:22.990  1174  1174 D HotspotTile: onReceive : 0, 0
,08-17 13:11:23.000  7420  7420 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-17 13:11:23.000  7420  7420 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 13:11:23.000  1017  1135 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:23.000  7420  7420 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-17 13:11:23.000  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:23.000  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:23.000  7420  7420 I dhcpcd  : bssid match
,08-17 13:11:23.000  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:23.000  7420  7420 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-17 13:11:23.000  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 13:11:23.010  1626  1626 I Hs20UtilService: Starting #16
,08-17 13:11:23.010  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 13:11:23.010  1626  1693 I Hs20UtilService: Message received 5007
08-17 13:11:23.010  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 13:11:23.010  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 13:11:23.010  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 13:11:23.010  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:23.010  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 13:11:23.010  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:23.020  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 13:11:23.020  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 13:11:23.020  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:23.020  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:23.020  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 13:11:23.020  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 13:11:23.020  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 13:11:23.020  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-17 13:11:23.020  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 13:11:23.030  1626  1626 I Hs20UtilService: Starting #17
,08-17 13:11:23.030  1626  1693 I Hs20UtilService: Message received 5011
,08-17 13:11:23.060  7344  7344 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 13:11:23.080  7420  7420 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-17 13:11:23.130  7344  7344 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,08-17 13:11:23.130  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 13:11:23.130  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 13:11:23.130  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-17 13:11:23.160  7344  7344 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-17 13:11:23.160  7344  7344 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-17 13:11:23.160  7344  7344 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-17 13:11:23.160  7344  7344 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-17 13:11:23.160  7344  7344 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-17 13:11:23.160  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 13:11:23.160  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:23.160  1017  1130 D Tethering: InitialState.processMessage what=4
08-17 13:11:23.160  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 13:11:23.160  1017  1130 E Tethering: No numeric data
,08-17 13:11:23.160  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:23.160  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:23.160  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:23.160  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 13:11:23.160  1017  1130 D Tethering: clearTetheredNotification()
08-17 13:11:23.170  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-17 13:11:23.170  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:23.170  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 13:11:23.170  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:23.170  1174  1174 D HotspotTile: updateTetherState():false, false
08-17 13:11:23.170  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:23.170  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:23.170  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:23.170  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:23.170  7420  7420 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
08-17 13:11:23.170  1017  1124 V NetworkStats: performPollLocked() took 6ms
08-17 13:11:23.170  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:23.170   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-17 13:11:23.180  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:23.180  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:23.470  7344  7344 I wpa_supplicant: Blacklist: Clear (all) ,
,08-17 13:11:23.540  1017  1490 I ActivityManager: Killing 7061:com.sec.pcw.device/1000 (adj 15): empty #21
,08-17 13:11:23.550  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 13:11:23.550  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-17 13:11:23.550  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 13:11:23.560  7344  7344 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-17 13:11:23.560  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-17 13:11:23.560  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:23.560  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-17 13:11:23.670  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-17 13:11:23.670  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-17 13:11:23.670  6971  6971 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 13:11:23.680  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 13:11:23.680  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 13:11:23.680  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:23.680  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:23.680  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:23.680  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:23.680  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:23.680  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-17 13:11:23.680  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 13:11:23.680  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:23.680  1174  1174 D HotspotTile: onReceive : 1, 0
,08-17 13:11:23.680  2046  2229 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 13:11:23.680  3071  3071 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:23.690  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:23.690  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:23.690  1017  2092 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 13:11:23.690  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:23.690  1017  2092 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:23.690  1017  2092 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:23.690  1017  2092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 13:11:23.690  1626  1626 I Hs20UtilService: Starting #18,
,08-17 13:11:23.690  1626  1693 I Hs20UtilService: Message received 5011
,08-17 13:11:23.700  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-17 13:11:23.700  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 13:11:23.700  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
,08-17 13:11:23.700  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 13:11:24.520   277  1010 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-17 13:11:24.520  1017  1044 D Tethering: interfaceRemoved wlan0
,08-17 13:11:24.520  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-17 13:11:24.640  1017  1044 D Tethering: interfaceRemoved p2p0
,08-17 13:11:24.640  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-17 13:11:25.210   287   287 E SMD     : DCD OFF,
,08-17 13:11:25.410  1017  1257 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 13:11:25.420  1017  1257 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 13:11:25.420  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
08-17 13:11:25.420  1017  1257 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 13:11:25.420  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 13:11:25.420  1017  1257 D BatteryService: stay LED for fully charged,
08-17 13:11:25.420  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
08-17 13:11:25.420  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 13:11:25.420  1017  1017 I MotionRecognitionService: Plugged,
08-17 13:11:25.420  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 13:11:25.430  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-17 13:11:25.430  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 13:11:25.450  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-17 13:11:25.450  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-17 13:11:25.450  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:25.460  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:25.460  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:25.810  6756  6850 D BluetoothAdapter: enable()
,08-17 13:11:25.820  1017  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 13:11:25.820  1017  1029 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 13:11:25.820  1017  1029 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 13:11:25.820  1017  1029 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 13:11:25.820  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-17 13:11:25.820  1017  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-17 13:11:25.820  1017  1029 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 13:11:25.820  1017  1029 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 13:11:25.820  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:25.820  1017  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:25.830  1017  1029 D SettingsProvider: name = bluetooth_on
,08-17 13:11:25.830  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 13:11:25.830  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:25.830  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-17 13:11:25.830  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 13:11:25.830  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:25.830  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:25.830  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:25.830  1017  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:25.850  7450  7450 E Zygote  : MountEmulatedStorage()
08-17 13:11:25.850  7450  7450 E Zygote  : v2
08-17 13:11:25.850  7450  7450 I libpersona: KNOX_SDCARD checking this for 1002
,08-17 13:11:25.850  7450  7450 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:25.850  7450  7450 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:25.850  7450  7450 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 13:11:25.860  1017  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7450 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
08-17 13:11:25.860  7450  7450 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-17 13:11:25.880  7450  7450 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:25.880  7450  7450 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:25.900  7450  7450 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 13:11:25.900  7450  7450 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 13:11:25.930  7450  7450 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 13:11:25.960  7450  7450 D BtSettings.ProfileConfig: Adding GattService
,08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding HeadsetService
,08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding HidService
08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding HealthService
08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding PanService
08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding BluetoothMapService,
08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding SapService
08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding SapClientService
08-17 13:11:25.970  7450  7450 D BtSettings.ProfileConfig: Adding HidDevService
08-17 13:11:25.970  7450  7450 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 13:11:25.970  1017  1539 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-17 13:11:25.970  1017  1539 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:25.970  1017  1539 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.970  1017  1539 D SettingsProvider: selectionArgs: false
08-17 13:11:25.970  1017  1539 D SettingsProvider: selectionArgs: 1002
08-17 13:11:25.970  1017  1539 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.970  1017  1539 D SettingsProvider: ret = -1
,08-17 13:11:25.970  1017  2092 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-17 13:11:25.970  1017  2092 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:25.970  1017  2092 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.970  1017  2092 D SettingsProvider: selectionArgs: false
08-17 13:11:25.970  1017  2092 D SettingsProvider: selectionArgs: 1002
08-17 13:11:25.970  1017  2092 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-17 13:11:25.970  1017  2092 D SettingsProvider: ret = -1
08-17 13:11:25.970  1017  1257 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-17 13:11:25.970  1017  1257 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-17 13:11:25.970  1017  1257 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.970  1017  1257 D SettingsProvider: selectionArgs: false
08-17 13:11:25.970  1017  1257 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:25.970  1017  1257 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.970  1017  1257 D SettingsProvider: ret = -1
,08-17 13:11:25.970  1017  1445 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService,
08-17 13:11:25.970  1017  1445 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:25.970  1017  1445 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.970  1017  1445 D SettingsProvider: selectionArgs: false
08-17 13:11:25.970  1017  1445 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:25.970  1017  1445 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.970  1017  1445 D SettingsProvider: ret = -1
08-17 13:11:25.970  1017  1135 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-17 13:11:25.970  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:25.970  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.970  1017  1135 D SettingsProvider: selectionArgs: false
,08-17 13:11:25.970  1017  1135 D SettingsProvider: selectionArgs: 1002
08-17 13:11:25.970  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.970  1017  1135 D SettingsProvider: ret = -1
08-17 13:11:25.970  1017  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 13:11:25.970  1017  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:25.970  1017  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.970  1017  1462 D SettingsProvider: selectionArgs: false
08-17 13:11:25.970  1017  1462 D SettingsProvider: selectionArgs: 1002
08-17 13:11:25.980  1017  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.980  1017  1462 D SettingsProvider: ret = -1
,08-17 13:11:25.980  1017  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 13:11:25.980  1017  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:25.980  1017  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-17 13:11:25.980  1017  1476 D SettingsProvider: selectionArgs: false
08-17 13:11:25.980  1017  1476 D SettingsProvider: selectionArgs: 1002
08-17 13:11:25.980  1017  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.980  1017  1476 D SettingsProvider: ret = -1
08-17 13:11:25.980  1017  1030 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 13:11:25.980  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:25.980  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.980  1017  1030 D SettingsProvider: selectionArgs: false
,08-17 13:11:25.980  1017  1030 D SettingsProvider: selectionArgs: 1002
08-17 13:11:25.980  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.980  1017  1030 D SettingsProvider: ret = -1
08-17 13:11:25.980  1017  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 13:11:25.980  1017  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:25.980  1017  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.980  1017  1490 D SettingsProvider: selectionArgs: false
08-17 13:11:25.980  1017  1490 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:25.980  1017  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.980  1017  1490 D SettingsProvider: ret = -1
08-17 13:11:25.980  1017  2100 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:25.980  1017  2100 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:25.980  1017  2100 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.980  1017  2100 D SettingsProvider: selectionArgs: false
,08-17 13:11:25.980  1017  2100 D SettingsProvider: selectionArgs: 1002
08-17 13:11:25.980  1017  2100 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.980  1017  2100 D SettingsProvider: ret = -1,
08-17 13:11:25.980  1017  1443 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 13:11:25.980  1017  1443 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-17 13:11:25.980  1017  1443 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.980  1017  1443 D SettingsProvider: selectionArgs: false
08-17 13:11:25.980  1017  1443 D SettingsProvider: selectionArgs: 1002,
08-17 13:11:25.980  1017  1443 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.980  1017  1443 D SettingsProvider: ret = -1
08-17 13:11:25.980  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-17 13:11:25.980  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:25.980  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:25.980  1017  1029 D SettingsProvider: selectionArgs: false
,08-17 13:11:25.980  1017  1029 D SettingsProvider: selectionArgs: 1002
08-17 13:11:25.980  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:25.980  1017  1029 D SettingsProvider: ret = -1
,08-17 13:11:26.000  7450  7450 D BluetoothAdapterState: make
,08-17 13:11:26.000  7450  7450 I bluedroid: init
,08-17 13:11:26.000  7450  7465 I BluetoothAdapterState: Entering OffState
,08-17 13:11:26.000  7450  7450 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 13:11:26.000  7450  7450 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 13:11:26.000  7450  7450 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 13:11:26.000  7450  7450 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 13:11:26.000  7450  7450 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-17 13:11:26.000  7450  7450 I bluedroid: get_profile_interface socket
08-17 13:11:26.000  7450  7468 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 13:11:26.000  7450  7450 I bluedroid: get_profile_interface map_client
,08-17 13:11:26.010  7450  7450 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
08-17 13:11:26.010  7450  7468 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-17 13:11:26.010  7450  7468 E BluetoothServiceJni: populateRssiValuesNative
08-17 13:11:26.010  7450  7468 I bluedroid: getModelRssiValues
08-17 13:11:26.010  7450  7468 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 13:11:26.010  7450  7468 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 13:11:26.010  1017  1017 D SettingsProvider: name = bluetooth_name
,08-17 13:11:26.010  7450  7468 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 13:11:26.010  7450  7450 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:26.010  1017  2100 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 13:11:26.020  1017  2100 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.020  1017  2100 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:26.020  1017  2100 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.020  1017  2100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.020  7450  7460 I bluedroid: config_hci_snoop_log
,08-17 13:11:26.020  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-17 13:11:26.020  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-17 13:11:26.020  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 13:11:26.020  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 13:11:26.030  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 13:11:26.030  7450  7450 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 13:11:26.030  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:26.030  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:26.040  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 13:11:26.040  7450  7465 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 13:11:26.040  7450  7465 D BluetoothAdapterProperties: Setting state to 11
,08-17 13:11:26.040  7450  7465 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-17 13:11:26.040  7450  7465 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 13:11:26.040  7450  7465 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 13:11:26.040  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-17 13:11:26.040  7450  7465 D BluetoothAdapterService: Autoconnection is available 
08-17 13:11:26.040  7450  7465 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 13:11:26.040  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:26.040  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-17 13:11:26.050  7450  7465 D BluetoothSecureManager: getInstant: null
08-17 13:11:26.050  7450  7465 D BluetoothSecureManager: calling getMethod for getService
08-17 13:11:26.050  7450  7465 D BluetoothSecureManager: calling getService
08-17 13:11:26.050  7450  7465 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@eff192
,08-17 13:11:26.050  1017  2092 D BluetoothSecureManagerService: isSecureModeEnabled
,08-17 13:11:26.050  1017  2092 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-17 13:11:26.050  7450  7465 D BtConfig.SecureMode: isSecureModeOn:false
08-17 13:11:26.050  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 13:11:26.050  7450  7465 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 13:11:26.050  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-17 13:11:26.060  1888  1888 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0,
,08-17 13:11:26.060  7450  7465 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 13:11:26.060  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 13:11:26.060  7450  7465 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 13:11:26.060  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 13:11:26.060  7450  7465 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-17 13:11:26.060  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 13:11:26.060  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 13:11:26.060  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:26.060  1174  1174 D BluetoothTile:  getBluetoothState : 11
,08-17 13:11:26.060  7450  7465 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 13:11:26.060  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 13:11:26.060  7450  7465 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,08-17 13:11:26.060  3071  3071 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:26.060  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 13:11:26.070  1017  2100 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 13:11:26.070  7450  7465 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 13:11:26.070  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 13:11:26.070  7450  7465 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 13:11:26.070  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:26.070  7450  7465 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:26.070  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 13:11:26.070  7450  7465 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:26.070  1017  2116 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 13:11:26.070  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 13:11:26.070  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-17 13:11:26.070  7450  7465 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 13:11:26.070  1017  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:11:26.070  1017  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 13:11:26.070  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 13:11:26.070  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 13:11:26.070  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:26.070  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Bluetooth,
08-17 13:11:26.070  7450  7465 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-17 13:11:26.070  1017  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:26.070  1017  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:26.070  1017  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:26.080  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:26.080  3071  3071 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 13:11:26.080  7450  7465 D BluetoothBondStateMachine: make
,08-17 13:11:26.090  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 13:11:26.090  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 13:11:26.090  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 13:11:26.090  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:26.090  7450  7471 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 13:11:26.090  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 13:11:26.090  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:26.090  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.090  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.090  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.090  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.090  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 13:11:26.090  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 13:11:26.090  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 13:11:26.090  7450  7450 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 13:11:26.090  7450  7450 D BtGatt.GattService: Received start request. Starting profile...
08-17 13:11:26.090  7450  7450 D BtGatt.GattService: start()
08-17 13:11:26.090  7450  7450 D BtGatt.GattService: start()
08-17 13:11:26.090  7450  7450 I bluedroid: get_profile_interface gatt
,08-17 13:11:26.090  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:26.090  7450  7450 D BtGatt.AdvertiseManager: advertise manager created
,08-17 13:11:26.090  1017  1257 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-17 13:11:26.100  1017  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:26.100  1017  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:26.100  1017  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:26.100  1017  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:26.110  7473  7473 E Zygote  : MountEmulatedStorage(),
08-17 13:11:26.110  7473  7473 E Zygote  : v2
,08-17 13:11:26.110  7473  7473 I libpersona: KNOX_SDCARD checking this for 10055
08-17 13:11:26.110  7473  7473 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:26.110  7473  7473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:26.110  1017  1257 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7473 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-17 13:11:26.120  1017  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:26.120  7473  7473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:26.120  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.120  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.120  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.120  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:26.120  7473  7473 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:26.120  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 13:11:26.120  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 13:11:26.120  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 13:11:26.120  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:26.120  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.130  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.130  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.130  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:26.130  7450  7450 D BtGatt.GattService: mStartError = false
08-17 13:11:26.130  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:26.130  7450  7450 D HeadsetService: Received start request. Starting profile...
08-17 13:11:26.130  7450  7450 D HeadsetService: start()
,08-17 13:11:26.130  7450  7450 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 13:11:26.130  7450  7450 D HeadsetStateMachine: make
08-17 13:11:26.130  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 13:11:26.130  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 13:11:26.130  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 13:11:26.130  1017  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:26.130  1017  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.140  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.140  1017  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.140  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:26.140  7450  7450 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 13:11:26.140  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 13:11:26.140  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 13:11:26.140  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 13:11:26.140  1017  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:26.140  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.140  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:26.140  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.140  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.140  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 13:11:26.140  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 13:11:26.140  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-17 13:11:26.140  1017  1135 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-17 13:11:26.140  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.140  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.140  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.140  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 13:11:26.140  1017  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:26.140  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.150  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.150  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.150  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.150  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 13:11:26.150  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:26.150  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 13:11:26.150  7473  7473 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:26.150  7473  7473 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:26.150  1017  1476 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-17 13:11:26.150  1017  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.160  1017  1476 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.160  1017  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.160  1017  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 13:11:26.160  7450  7450 I bluedroid: get_profile_interface handsfree
,08-17 13:11:26.160  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:26.160  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.160  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.160  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.160  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.160  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 13:11:26.160  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 13:11:26.160  7450  7465 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 13:11:26.160  1017  2100 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:26.160  1017  2100 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.170  1017  2100 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.170  1017  2100 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.170  1017  2100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.170  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:26.170  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:26.170  7450  7465 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:26.170  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:26.170  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:26.170  7450  7465 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:26.170  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 13:11:26.170  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 13:11:26.170  7450  7465 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-17 13:11:26.170  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 13:11:26.170  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 13:11:26.170  7450  7465 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 13:11:26.170  7450  7465 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 13:11:26.180  7450  7450 I DualScoManager: Instantiating Dual Sco Manager
,08-17 13:11:26.180  7450  7450 I DualScoManager: Set HeadsetServiceHelper
,08-17 13:11:26.180  7450  7450 D BluetoothAtMessage: createCMTIContentObservers
,08-17 13:11:26.180  1017  1445 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-17 13:11:26.180  1017  1445 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:26.180  1017  1445 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:26.180  1017  1445 D SettingsProvider: selectionArgs: false
08-17 13:11:26.180  1017  1445 D SettingsProvider: selectionArgs: 1002
08-17 13:11:26.180  1017  1445 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:26.180  1017  1445 D SettingsProvider: ret = -1
,08-17 13:11:26.180  7450  7487 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 13:11:26.190  7450  7450 D HeadsetService: mStartError = false
08-17 13:11:26.190  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:26.190  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 13:11:26.190  7450  7450 D A2dpService: Received start request. Starting profile...
08-17 13:11:26.190  7450  7450 D A2dpService: start()
,08-17 13:11:26.190  7473  7473 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
08-17 13:11:26.190  7450  7487 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-17 13:11:26.190  7450  7487 D HeadsetStateMachine: map size, before remove : 0
08-17 13:11:26.190  7450  7487 D HeadsetStateMachine: map size, after remove: 0
,08-17 13:11:26.190  7450  7450 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 13:11:26.190  7450  7450 I bluedroid: get_profile_interface avrcp
,08-17 13:11:26.200  7450  7450 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 13:11:26.200  7450  7450 D Avrcp   : Initialize Media Controller
,08-17 13:11:26.200  7450  7450 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 13:11:26.200  7450  7450 E Avrcp   : getActiveSessions
08-17 13:11:26.200  7450  7450 D Avrcp   : pick active media Controller
08-17 13:11:26.200  7450  7450 D Avrcp   : Get the active Media Controller 
,08-17 13:11:26.220  7450  7450 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 13:11:26.220  7450  7493 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 13:11:26.220  7450  7450 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-17 13:11:26.220  7450  7450 D A2dpStateMachine: make
08-17 13:11:26.220  7473  7473 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-17 13:11:26.220  7473  7473 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-17 13:11:26.220  7473  7473 D UserAnalysis: Create SecureDbHelper
,08-17 13:11:26.230  7450  7450 I bluedroid: get_profile_interface a2dp
,08-17 13:11:26.230  7450  7495 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-17 13:11:26.230  7450  7450 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 13:11:26.230  7450  7450 D A2dpService: mStartError = false
08-17 13:11:26.230  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:26.230  7450  7494 D A2dpStateMachine: Enter Disconnected: -2
08-17 13:11:26.230  7473  7473 D IntelligenceServiceApplication: onCreate()
08-17 13:11:26.230  7450  7450 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 13:11:26.230  7450  7450 D HidService: Received start request. Starting profile...
08-17 13:11:26.230  1017  1462 I ActivityManager: Killing 7078:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-17 13:11:26.230  7450  7450 D HidService: start()
08-17 13:11:26.230  7450  7450 I bluedroid: get_profile_interface hidhost
08-17 13:11:26.230  7450  7450 D HidService: setHidService(): set to: null
08-17 13:11:26.230  7450  7450 D HidService: mStartError = false
08-17 13:11:26.230  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:26.230  7450  7450 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 13:11:26.240  7450  7450 D HealthService: Received start request. Starting profile...
08-17 13:11:26.240  7450  7450 D HealthService: start()
,08-17 13:11:26.240  7450  7493 D BluetoothMediaBrowser: no now playing list
08-17 13:11:26.240  7450  7493 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 13:11:26.240  7450  7450 I bluedroid: get_profile_interface health
08-17 13:11:26.240  7450  7450 D HealthService: mStartError = false
08-17 13:11:26.240  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:26.240  7450  7450 D HeadsetStateMachine: Try to query the phonestate on bind
,08-17 13:11:26.240  7473  7473 D IntelligenceServiceApplication: no applications having user consent for prediction
08-17 13:11:26.240  1433  1448 I Telecom : BluetoothPhoneService: queryPhoneState
08-17 13:11:26.240  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-17 13:11:26.240  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 13:11:26.240  1433  1448 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 13:11:26.240  7450  7450 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 13:11:26.250  7450  7450 D PanService: Received start request. Starting profile...
08-17 13:11:26.250  7450  7450 D PanService: start()
08-17 13:11:26.250  7450  7450 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 13:11:26.250  7450  7450 I bluedroid: get_profile_interface pan
,08-17 13:11:26.250  7450  7450 D PanService: mStartError = false
08-17 13:11:26.250  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:26.250  7450  7450 D HeadsetStateMachine: Proxy object connected
,08-17 13:11:26.250  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-17 13:11:26.250  7473  7473 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-17 13:11:26.250  7450  7450 D BluetoothMapService: Received start request. Starting profile...,
08-17 13:11:26.250  7450  7450 D BluetoothMapService: start()
,08-17 13:11:26.250  7450  7450 D BluetoothMapService: mStartError = false
08-17 13:11:26.250  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:26.250  7450  7450 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-17 13:11:26.250  7450  7487 D HeadsetStateMachine: Disconnected process message: 11
08-17 13:11:26.250  7450  7450 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 13:11:26.250  7450  7450 D SapService: Received start request. Starting profile...
08-17 13:11:26.250  7450  7450 D SapService: start()
08-17 13:11:26.250  7450  7450 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 13:11:26.250  7450  7450 I bluedroid: get_profile_interface sap
08-17 13:11:26.250  7450  7450 D SapService: mStartError = false
08-17 13:11:26.250  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:26.250  7450  7450 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 13:11:26.250  7450  7450 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-17 13:11:26.250  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-17 13:11:26.250  7450  7450 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 13:11:26.260  7450  7450 D BluetoothA2dp: Proxy object connected
08-17 13:11:26.260  7450  7450 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 13:11:26.260  7450  7487 D HeadsetStateMachine: Disconnected process message: 18
08-17 13:11:26.260  7450  7487 D HeadsetStateMachine: Disconnected process message: 10
08-17 13:11:26.260  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 13:11:26.260  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-17 13:11:26.260  7450  7487 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 13:11:26.260  7450  7487 D HeadsetStateMachine: Disconnected process message: 11
,08-17 13:11:26.260  1017  2100 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-17 13:11:26.260  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:26.260  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:26.260  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:26.260  1017  2100 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:26.260  7473  7473 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-17 13:11:26.270  7500  7500 E Zygote  : MountEmulatedStorage()
,08-17 13:11:26.270  7500  7500 E Zygote  : v2
08-17 13:11:26.270  7500  7500 I libpersona: KNOX_SDCARD checking this for 10105
,08-17 13:11:26.270  7500  7500 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:26.270  7500  7500 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:26.280  7500  7500 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-17 13:11:26.280  1017  2100 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7500 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-17 13:11:26.280  7500  7500 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-17 13:11:26.280  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 13:11:26.280  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 13:11:26.300  7500  7500 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:26.300  7500  7500 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:26.310  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-17 13:11:26.310  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 13:11:26.310  7450  7465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-17 13:11:26.310  7450  7465 I bluedroid: enable
,08-17 13:11:26.310  7450  7465 I bt_hci_bdroid: init
08-17 13:11:26.320  7450  7516 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-17 13:11:26.320  7450  7465 I bt_vendor: bt-vendor : init
,08-17 13:11:26.320  7450  7465 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 13:11:26.320  7450  7465 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-17 13:11:26.320  7450  7465 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-17 13:11:26.320  7450  7465 D bt_userial_mct: userial_init
,08-17 13:11:26.320  7450  7465 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 13:11:26.320  7450  7465 I bt_vendor: Starting hciattach daemon
08-17 13:11:26.320  7450  7465 I bt_vendor: try to set false
,08-17 13:11:26.330  7450  7465 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-17 13:11:26.330  7450  7465 I bt_vendor: Starting hciattach daemon
08-17 13:11:26.330  7450  7465 I bt_vendor: try to set true
,08-17 13:11:26.350  7521  7521 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 13:11:26.400  7529  7529 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-17 13:11:26.400  7530  7530 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 13:11:26.420  7532  7532 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 13:11:26.420  7533  7533 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 13:11:26.430  7534  7534 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 13:11:26.440  7535  7535 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 13:11:26.470   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 13:11:26.470   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 13:11:26.470  7500  7538 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 13:11:26.480   256   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-17 13:11:26.480   256   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-17 13:11:26.480  7500  7538 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-17 13:11:26.640  7500  7500 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-17 13:11:26.640  7500  7500 D StrictMode: StrictMode policy violation; ~duration=144 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:26.640  7500  7500 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:26.640  7500  7500 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:26.640  7500  7500 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.k.d(PG:583)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.e.b(PG:170)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:26.640  7500  7500 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:26.640  7500  7500 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.File.exists(File.java:363)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:26.640  7500  7500 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-17 13:11:26.640  7500  7500 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-17 13:11:26.650  1017  1483 I ActivityManager: Killing 7093:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
08-17 13:11:26.650  2046  2046 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 13:11:26.660  2046  2046 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 13:11:26.700  7500  7549 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 13:11:26.720  7550  7550 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-17 13:11:26.730  1017  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:26.730  7552  7552 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 13:11:26.730  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:26.730  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:26.730  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-17 13:11:26.780  7450  7465 I bt_vendor: bluetooth satus is on
,08-17 13:11:26.780  7450  7518 D bt_userial_mct: userial_open(port:0)
08-17 13:11:26.780  7450  7518 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 13:11:26.780  7450  7518 I bt_vendor: Done intiailizing UART
,08-17 13:11:26.790  7450  7518 I bt_vendor: Done intiailizing UART
,08-17 13:11:26.790  7450  7518 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
,08-17 13:11:26.790  7450  7518 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_GAP
,08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_GATT,
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 13:11:26.790  7450  7516 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
08-17 13:11:26.800  7450  7555 D bt_userial_mct: Entering userial_read_thread()
,08-17 13:11:26.890  7450  7516 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 13:11:26.890  7450  7516 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4282ed1 
,08-17 13:11:26.890  7450  7516 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4282ed1 
,08-17 13:11:26.910  7450  7468 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 13:11:26.910  7450  7468 E bt-btif : Calling BTA_HhEnable
,08-17 13:11:26.910  7450  7468 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-17 13:11:26.910  7450  7468 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-17 13:11:26.910  7450  7468 E BluetoothServiceJni: populateRssiValuesNative
08-17 13:11:26.910  7450  7468 I bluedroid: getModelRssiValues
,08-17 13:11:26.920  7450  7468 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 13:11:26.920  7450  7468 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 13:11:26.920  1017  1017 D SettingsProvider: name = bluetooth_name
08-17 13:11:26.920  7450  7468 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 13:11:26.920  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-17 13:11:26.920  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:26.930  7450  7468 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-17 13:11:26.930  7450  7468 D BluetoothAdapterProperties: Scan Mode:20
,08-17 13:11:26.930  7450  7468 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 13:11:26.930  7450  7468 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-17 13:11:26.930  7450  7468 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-17 13:11:26.930  7450  7468 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-17 13:11:26.930  7450  7468 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 13:11:26.930  7450  7468 E bt-btif : btif_sock_init: !vhci_init
,08-17 13:11:26.930  7450  7468 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-17 13:11:26.930  7450  7555 E bt_mct  : hci lib postload completed,
,08-17 13:11:26.940  7450  7468 D IOP_DB_BT: db_open: db_open : handle 3025866768l, read 13894 bytes onto local cache,
08-17 13:11:26.940  7450  7468 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-17 13:11:26.940  7450  7468 D IOP_DB_BT: db_query: result 1
,08-17 13:11:26.940  7450  7468 I         : iop_db_open: iop_db_open status 0
,08-17 13:11:26.940  7450  7468 D bte_conf: Device ID record 1 : primary,
08-17 13:11:26.940  7450  7468 D bte_conf:   vendorId            = 0075
08-17 13:11:26.940  7450  7468 D bte_conf:   vendorIdSource      = 0001
08-17 13:11:26.940  7450  7468 D bte_conf:   product             = 0100
,08-17 13:11:26.940  7450  7468 D bte_conf:   version             = 0200
08-17 13:11:26.940  7450  7468 D bte_conf:   clientExecutableURL = 
08-17 13:11:26.940  7450  7468 D bte_conf:   serviceDescription  = 
08-17 13:11:26.940  7450  7468 D bte_conf:   documentationURL    = ,
08-17 13:11:26.940  7450  7468 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 13:11:26.940  7450  7465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-17 13:11:26.950  7450  7465 D BluetoothAdapterProperties: ScanMode =  20
,08-17 13:11:26.950  7450  7468 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 13:11:26.950  7450  7465 D BluetoothAdapterProperties: State =  11
,08-17 13:11:26.950  1017  2116 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 13:11:26.950  7450  7465 D BluetoothAdapterProperties: Setting state to 12,
08-17 13:11:26.950  7450  7465 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12,
,08-17 13:11:26.950  1017  1135 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-17 13:11:26.950  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:26.950  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 13:11:26.950  1017  1135 D SettingsProvider: selectionArgs: false,
,08-17 13:11:26.960  1017  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-17 13:11:26.950  1017  1135 D SettingsProvider: selectionArgs: 1002
08-17 13:11:26.960  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 13:11:26.950  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:26.950  1017  1135 D SettingsProvider: ret = -1
08-17 13:11:26.950  7450  7465 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 13:11:26.950  7450  7465 D BluetoothAdapterService: updateAdapterState state is 12
08-17 13:11:26.960  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.960  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.960  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.970  7450  7465 D BluetoothAdapterService: Autoconnection is available 
08-17 13:11:26.970  7450  7465 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 13:11:26.970  7450  7465 D BluetoothAdapterService: starting service from this receiver
,08-17 13:11:26.970  1017  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:26.970  2046  6846 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:26.970  2046  6846 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:26.970  1017  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 13:11:26.970  7450  7468 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 13:11:26.970  7450  7468 D BluetoothAdapterProperties: Scan Mode:21
,08-17 13:11:26.970  7450  7468 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 13:11:26.970  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.970  1017  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.970  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.970  7450  7465 I BluetoothAdapterState: Entering On State from state = 11
,08-17 13:11:26.980  3071  3082 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:26.980  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 13:11:26.980  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:26.980  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:26.980  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:26.980  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:26.980  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:26.980  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:26.980  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:26.980  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:26.980  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:26.980  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:26.990  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:26.990  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:26.990  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:26.990  3071  3082 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 13:11:26.990  3071  6891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:26.990  3071  6891 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:26.990  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:26.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:26.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:26.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:26.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:26.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:26.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:26.990  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:26.990  7450  7450 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 13:11:26.990  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:27.000  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 13:11:27.000  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.000  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:27.000  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.000  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.000  1444  1465 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.000  1444  1465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.000  3071  3071 D BluetoothA2dp: Proxy object connected
08-17 13:11:27.000  7450  7458 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:27.000  3071  3071 D A2dpProfile: Bluetooth service connected
,08-17 13:11:27.000  1460  1473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:27.000  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 13:11:27.010  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:27.010  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:27.010  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:27.010  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.010  1460  1473 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 13:11:27.010  7450  7450 I BluetoothPbapService: Handler(): got msg=1
,08-17 13:11:27.010  3071  3082 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 13:11:27.010  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 13:11:27.010  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.010  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.010  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.010  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.010  1017  2092 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-17 13:11:27.010  3071  3071 D HeadsetProfile: Bluetooth service connected
08-17 13:11:27.010  6756  6766 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.010  6756  6766 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.020  1433  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:27.020  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 13:11:27.020  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:27.020  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.020  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.020  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.020  1433  1457 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 13:11:27.020  3071  3071 D BluetoothMap: Proxy object connected
08-17 13:11:27.020  3071  3071 D MapProfile: Bluetooth service connected
08-17 13:11:27.020  3071  3071 D BluetoothMap: getConnectedDevices()
,08-17 13:11:27.020  7450  7559 V BluetoothPbapService: PBAP Service initSocket try: 0
08-17 13:11:27.020  7450  7460 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.020  7450  7460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.020  3071  7271 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 13:11:27.030  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 13:11:27.030  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.030  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.030  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.030  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.030  7450  7559 D BluetoothSocket: bindListen(): myUserId = 0
08-17 13:11:27.030  3071  3079 D BluetoothPan: Binding service...
,08-17 13:11:27.030  7450  7559 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:27.030  3071  3071 D BluetoothInputDevice: Proxy object connected
08-17 13:11:27.030  3071  3071 D HidProfile: Bluetooth service connected
,08-17 13:11:27.030  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 13:11:27.030  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.030  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:27.030  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.030  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.030  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:27.040  3071  3071 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 13:11:27.040  3071  3071 D PanProfile: Bluetooth service connected
08-17 13:11:27.040  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:27.040  7450  7559 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-17 13:11:27.040  7450  7559 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 13:11:27.040  7450  7559 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-17 13:11:27.040  7450  7559 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ba56497
08-17 13:11:27.040  7450  7559 D BluetoothSocket: channel: 19
08-17 13:11:27.040  7450  7559 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 13:11:27.040  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-17 13:11:27.040  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.040  3071  7271 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 13:11:27.040  1017  1017 D BluetoothA2dp: Proxy object connected
,08-17 13:11:27.040  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-17 13:11:27.040  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.040  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.040  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:27.040  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.050  3071  7271 D Bluetoothsap: onBluetoothStateChange: up=true
08-17 13:11:27.050  3071  3071 D BluetoothPbap: Proxy object connected
08-17 13:11:27.050  3071  3071 D PbapServerProfile: Bluetooth service connected
,08-17 13:11:27.050  3071  7271 D Bluetoothsap: Binding service...
,08-17 13:11:27.050  3071  7271 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 13:11:27.050  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-17 13:11:27.050  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.050  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.050  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.050  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-17 13:11:27.050  3071  7271 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 13:11:27.050  1433  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:27.050  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 13:11:27.050  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:27.050  3071  3071 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 13:11:27.050  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.050  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.050  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.050  1433  1457 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 13:11:27.050  3071  3071 D SapProfile: Bluetooth service connected
08-17 13:11:27.050  3071  3071 D Bluetoothsap: getConnectedDevices()
,08-17 13:11:27.060  1174  3349 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.060  1174  3349 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.060  1433  7560 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.060  1433  7560 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.060  7500  7512 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.060  7500  7512 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.060  1433  1457 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:27.060  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 13:11:27.060  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:27.060  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:27.060  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.060  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.060  1433  1457 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 13:11:27.060  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.060  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.060  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-17 13:11:27.060  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 13:11:27.060  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:27.060  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 13:11:27.060  1460  1757 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.060  1460  1757 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.060  3071  6891 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:27.060  3071  6891 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:27.060  1017  1046 D BluetoothPan: Binding service...
,08-17 13:11:27.060  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 13:11:27.060  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.060  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 13:11:27.060  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 13:11:27.070  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 13:11:27.070  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:27.070  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-17 13:11:27.070  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 13:11:27.070  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@67d7343, true
,08-17 13:11:27.070  1433  1433 D BluetoothHeadset: registerMessageListener
,08-17 13:11:27.070  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-17 13:11:27.070  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 13:11:27.070  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:27.070  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-17 13:11:27.080  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 13:11:27.080  1888  1888 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 13:11:27.080  1017  1539 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 13:11:27.080  1017  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 13:11:27.090  3071  3071 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:27.090  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 13:11:27.090  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 13:11:27.090  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:27.100  1017  2116 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 13:11:27.100  1017  2116 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.100  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 13:11:27.100  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 13:11:27.100  7450  7458 D HeadsetService: registerMessageListener
08-17 13:11:27.100  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.100  1017  2116 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:27.100  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 13:11:27.100  7450  7458 D HeadsetService: registerMessageListener
08-17 13:11:27.100  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-17 13:11:27.100  7450  7487 D HeadsetStateMachine: Disconnected process message: 70
08-17 13:11:27.100  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 13:11:27.100  7450  7487 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2ddc0684,
,08-17 13:11:27.100  3071  3071 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 13:11:27.100  3071  3071 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 13:11:27.100  3071  3071 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 13:11:27.100  3071  3071 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 13:11:27.100  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-17 13:11:27.110  7450  7562 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-17 13:11:27.110  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-17 13:11:27.110  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 13:11:27.110  7450  7562 D BluetoothSocket: bindListen(): myUserId = 0
08-17 13:11:27.110  7450  7562 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:27.110  7450  7562 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-17 13:11:27.110  7450  7562 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 13:11:27.110  7450  7562 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 13:11:27.110  7450  7562 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ec32e6d
,08-17 13:11:27.110  7450  7562 D BluetoothSocket: channel: 5
,08-17 13:11:27.110  7450  7487 D HeadsetStateMachine: Disconnected process message: 9
,08-17 13:11:27.110  7450  7487 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 13:11:27.120   282   715 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-17 13:11:27.120  3071  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:27.120   282   715 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-17 13:11:27.120   282   715 V voice   : voice_set_parameters: exit with code(-2)
08-17 13:11:27.120  1017  1135 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-17 13:11:27.120   282   715 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 13:11:27.120  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-17 13:11:27.120   282   715 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 13:11:27.120   282   715 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 13:11:27.120   282   715 V audio_hw_primary: adev_set_parameters: exit,
08-17 13:11:27.120  7450  7487 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-17 13:11:27.130  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.130  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:27.130  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 13:11:27.140  3071  3071 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:27.140  3071  3071 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 13:11:27.140  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:27.140  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 13:11:27.150  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:27.150  7450  7450 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 13:11:27.150  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:27.150  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.150  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:27.160  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:27.160  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:27.180  2046  2046 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:27.180  1017  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:11:27.180  1017  1462 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 13:11:27.180  1017  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:27.180  1017  1462 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:27.180  1017  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:27.190  1017  2092 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 13:11:27.190  2046  7569 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 13:11:27.190  2046  2046 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 13:11:27.200  7450  7572 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 13:11:27.200  7450  7572 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:27.200  7450  7572 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,08-17 13:11:27.200  7450  7572 D BluetoothSocket: bindListen(), new LocalSocket 
,08-17 13:11:27.200  7450  7572 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 13:11:27.200  7450  7572 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f6a4f8f
,08-17 13:11:27.210  7450  7572 D BluetoothSocket: channel: 12
,08-17 13:11:27.210  7450  7572 I BtOppRfcommListener: Accept thread started.
,08-17 13:11:27.350  1017  1030 I art     : Explicit concurrent mark sweep GC freed 73407(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 2.360ms total 155.586ms
08-17 13:11:27.350  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:27.350  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:27.350  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:27.350  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:27.370  1017  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:27.370  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:27.370  1017  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:27.370  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:27.380  2046  7569 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 13:11:28.210   287   287 E SMD     : DCD OFF
,08-17 13:11:28.830  6756  6850 D BluetoothAdapter: disable()
,08-17 13:11:28.840  1017  1443 D SettingsProvider: name = bluetooth_on
,08-17 13:11:28.850  7450  7465 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-17 13:11:28.850  7450  7465 D BluetoothAdapterProperties: Setting state to 13
08-17 13:11:28.850  7450  7465 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 13:11:28.850  7450  7465 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 13:11:28.850  7450  7465 D BluetoothAdapterService: updateAdapterState state is 13
,08-17 13:11:28.850  1017  1445 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:28.850  1017  1445 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 13:11:28.850  1017  1445 W ActivityManager: userId = 0, bbcId = -10000,
08-17 13:11:28.850  1017  1445 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-17 13:11:28.850  1017  1445 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:28.860  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-17 13:11:28.850  7450  7450 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-17 13:11:28.850  7450  7465 D BluetoothAdapterService: Autoconnection is available 
08-17 13:11:28.850  7450  7465 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-17 13:11:28.850  7450  7465 D BluetoothAdapterService: terminating service from this receiver
08-17 13:11:28.860  7450  7450 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c1ba21c, channel: 19, state: LISTENING
08-17 13:11:28.860  7450  7450 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c1ba21c, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3ba56497, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d0be25mSocket: android.net.LocalSocket@286e6bfa impl:android.net.LocalSocketImpl@194655ab fd:FileDescriptor[74]
08-17 13:11:28.860  7450  7450 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@286e6bfa impl:android.net.LocalSocketImpl@194655ab fd:FileDescriptor[74]
,08-17 13:11:28.860  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:28.860  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:28.860  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:28.860  7450  7465 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 13:11:28.860  7450  7465 D BluetoothAdapterProperties: mDiscovering is false
,08-17 13:11:28.860  1017  1490 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-17 13:11:28.860  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:28.860  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-17 13:11:28.860  7450  7465 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-17 13:11:28.870  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-17 13:11:28.870  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 13:11:28.870  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:28.870  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-17 13:11:28.880  1888  1888 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 13:11:28.880  3071  3071 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:28.880  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 13:11:28.880  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:28.880  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:28.880  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:28.880  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:28.880  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:28.880  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:28.880  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:28.880  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:28.880  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 13:11:28.890  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:28.890  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:28.890  1017  1490 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 13:11:28.890  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 13:11:28.890  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 13:11:28.890  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 13:11:28.890  1017  2092 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 13:11:28.890  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 13:11:28.890  1017  2092 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:28.890  1017  2092 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:28.890  1017  2092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:28.890  7450  7468 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 13:11:28.890  7450  7468 D BluetoothAdapterProperties: Scan Mode:20
,08-17 13:11:28.900  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:28.900  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:28.900  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:28.900  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:28.900  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:28.900  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 13:11:28.900  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:28.900  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:28.900  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:28.900  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-17 13:11:28.900  3071  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:28.900  6756  6756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 13:11:28.900  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:28.900  7450  7465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 13:11:28.900  7450  7465 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-17 13:11:28.900  7450  7465 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-17 13:11:28.900  7450  7465 E bt-btif : cmd socket is not created
,08-17 13:11:28.900  7450  7572 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 13:11:28.910  7450  7465 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 13:11:28.910  7450  7516 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-17 13:11:28.910  7450  7516 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-17 13:11:28.910  1017  1445 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 13:11:28.910  1017  1445 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 13:11:28.910  1017  1445 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:28.910  1017  1445 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:28.910  1017  1445 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 13:11:28.910  7450  7516 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:28.910  7450  7516 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:28.910  7450  7516 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-17 13:11:28.910  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:28.910  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:28.920  3071  3071 D BluetoothPbap: Proxy object disconnected
,08-17 13:11:28.920  3071  3071 D PbapServerProfile: Bluetooth service disconnected
,08-17 13:11:28.930  7450  7450 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1e4ec408, channel: 5, state: LISTENING
08-17 13:11:28.930  7450  7450 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1e4ec408, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ec32e6d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d7417a1mSocket: android.net.LocalSocket@1274dc6 impl:android.net.LocalSocketImpl@2492a187 fd:FileDescriptor[76]
08-17 13:11:28.930  7450  7450 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1274dc6 impl:android.net.LocalSocketImpl@2492a187 fd:FileDescriptor[76]
,08-17 13:11:28.930  7450  7450 I BtOppRfcommListener: stopping Accept Thread
08-17 13:11:28.930  7450  7450 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@351018b4, channel: 12, state: LISTENING
08-17 13:11:28.930  7450  7450 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@351018b4, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f6a4f8f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e998cddmSocket: android.net.LocalSocket@103a8052 impl:android.net.LocalSocketImpl@d6dcf23 fd:FileDescriptor[80]
08-17 13:11:28.930  7450  7450 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@103a8052 impl:android.net.LocalSocketImpl@d6dcf23 fd:FileDescriptor[80]
08-17 13:11:28.930  7450  7572 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-17 13:11:28.940  3071  3071 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:28.940  3071  3071 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 13:11:28.940  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:28.940  7450  7450 V BluetoothOppManager: cleanUp...,
08-17 13:11:28.940  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-17 13:11:28.960  2046  2046 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:28.960  2046  2046 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 13:11:29.110  7450  7555 I bt_userial_mct: exiting userial_read_thread
08-17 13:11:29.110  7450  7555 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 13:11:29.110  7450  7516 W bt-btif : ag scb idx 1 not allocated
08-17 13:11:29.110  7450  7516 W bt-btif : ag scb idx 2 not allocated
08-17 13:11:29.110  7450  7516 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 13:11:29.110  7450  7468 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 13:11:29.110  7450  7518 I bt_vendor: hw_epilog_process
08-17 13:11:29.110  7450  7468 D bt_userial_mct: userial_close
08-17 13:11:29.110  7450  7468 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-17 13:11:29.520  7450  7468 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 13:11:29.520  7450  7468 I bt_vendor: bluetooth satus is on
08-17 13:11:29.520  7450  7468 I bt_vendor: bt-vendor : resetting BT status
08-17 13:11:29.520  7450  7468 I bt_vendor: Starting hciattach daemon
08-17 13:11:29.520  7450  7468 I bt_vendor: try to set false
,08-17 13:11:29.520  7450  7468 I bt_vendor: Starting hciattach daemon
08-17 13:11:29.520  7450  7468 I bt_vendor: try to set false
,08-17 13:11:29.520  7450  7468 I bt_vendor: cleanup
,08-17 13:11:29.520  7450  7516 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-17 13:11:29.520  7450  7468 I GKI_LINUX: GKI_exit_task 0 done
,08-17 13:11:29.520  7450  7468 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-17 13:11:29.520  7450  7465 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 13:11:29.520  7450  7465 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 13:11:29.520  7450  7465 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-17 13:11:29.520  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-17 13:11:29.520  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-17 13:11:29.520  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 13:11:29.530  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:29.530  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-17 13:11:29.530  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:29.530  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-17 13:11:29.530  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:29.530  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 13:11:29.530  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 13:11:29.530  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-17 13:11:29.530  7450  7450 D BtGatt.DebugUtils: handleDebugAction() action=null,
08-17 13:11:29.530  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:29.530  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
,08-17 13:11:29.530  7450  7450 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 13:11:29.530  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:29.530  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:29.530  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:29.530  7450  7450 D BtGatt.GattService: stop()
08-17 13:11:29.530  7450  7450 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 13:11:29.530  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 13:11:29.530  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 13:11:29.530  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-17 13:11:29.530  1017  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:29.530  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:29.530  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:29.530  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:29.530  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:29.540  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:29.540  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-17 13:11:29.540  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 13:11:29.540  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-17 13:11:29.540  1017  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:29.540  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 13:11:29.540  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:29.540  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:29.540  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:29.540  7450  7450 D HeadsetService: Received stop request...Stopping profile...
,08-17 13:11:29.540  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 13:11:29.540  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 13:11:29.540  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-17 13:11:29.540  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:29.540  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 13:11:29.540  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:29.540  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:29.540  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:29.540  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:29.550  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 13:11:29.550  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 13:11:29.550  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 13:11:29.550  1017  2116 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:29.550  1017  2116 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 13:11:29.550  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-17 13:11:29.550  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:29.550  1017  2116 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:29.550  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:29.550  3071  3071 D HeadsetProfile: Bluetooth service disconnected
,08-17 13:11:29.550  7450  7450 D A2dpService: Received stop request...Stopping profile...
,08-17 13:11:29.550  7450  7494 D A2dpStateMachine: Exit Disconnected: -1
,08-17 13:11:29.550  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-17 13:11:29.550  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:29.550  7450  7465 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 13:11:29.560  1017  2092 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:29.560  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 13:11:29.560  1017  2092 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:29.560  1017  2092 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:29.560  1017  2092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-17 13:11:29.560  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 13:11:29.560  1017  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:29.560  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0,
08-17 13:11:29.560  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:29.560  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:29.560  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:29.560  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:29.560  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:29.560  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-17 13:11:29.560  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 13:11:29.560  7450  7465 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-17 13:11:29.560  7450  7465 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 13:11:29.560  7450  7465 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-17 13:11:29.570  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-17 13:11:29.570  7450  7450 D HidService: Received stop request...Stopping profile...
08-17 13:11:29.570  7450  7450 D HidService: Stopping Bluetooth HidService
08-17 13:11:29.570  7450  7450 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 13:11:29.570  7450  7450 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-17 13:11:29.570  7450  7450 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 13:11:29.570  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:29.570  1017  1017 D BluetoothA2dp: Proxy object disconnected
,08-17 13:11:29.570  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 13:11:29.570  3071  3071 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:29.570  3071  3071 D A2dpProfile: Bluetooth service disconnected
,08-17 13:11:29.570  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-17 13:11:29.570  7450  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 13:11:29.570  7450  7450 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 13:11:29.570  3071  3071 D BluetoothInputDevice: Proxy object disconnected
08-17 13:11:29.570  3071  3071 D HidProfile: Bluetooth service disconnected
,08-17 13:11:29.570  7450  7450 D HealthService: Received stop request...Stopping profile...
08-17 13:11:29.570  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:29.580  7450  7450 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 13:11:29.580  7450  7450 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-17 13:11:29.580  7450  7450 D PanService: Received stop request...Stopping profile...
08-17 13:11:29.580  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:29.580  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-17 13:11:29.580  7450  7450 D BluetoothMapService: Received stop request...Stopping profile...
08-17 13:11:29.580  3071  3071 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 13:11:29.580  3071  3071 D PanProfile: Bluetooth service disconnected
,08-17 13:11:29.580  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
,08-17 13:11:29.580  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-17 13:11:29.580  7450  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 13:11:29.580  7450  7450 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-17 13:11:29.590  7450  7450 D SapService: Received stop request...Stopping profile...
08-17 13:11:29.590  7450  7450 D SapService: Stopping Bluetooth SapService
08-17 13:11:29.590  7450  7450 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@212da465
08-17 13:11:29.590  3071  3071 D BluetoothMap: Proxy object disconnected
08-17 13:11:29.590  3071  3071 D MapProfile: Bluetooth service disconnected
,08-17 13:11:29.590  7450  7450 D BluetoothA2dp: Proxy object disconnected
08-17 13:11:29.590  7450  7450 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-17 13:11:29.590  7450  7495 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 13:11:29.590  7450  7450 I GKI_LINUX: GKI_exit_task 2 done
08-17 13:11:29.590  7450  7450 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-17 13:11:29.590  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-17 13:11:29.590  7450  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:29.590  7450  7450 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-17 13:11:29.590  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-17 13:11:29.590  7450  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:29.590  7450  7450 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:29.590  7450  7450 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 13:11:29.590  7450  7450 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 13:11:29.590  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-17 13:11:29.590  7450  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:29.590  7450  7450 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:29.590  7450  7450 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 13:11:29.590  7450  7450 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 13:11:29.590  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-17 13:11:29.590  7450  7450 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 13:11:29.590  7450  7450 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-17 13:11:29.590  3071  3071 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-17 13:11:29.590  3071  3071 D SapProfile: Bluetooth service disconnected
08-17 13:11:29.590  7450  7450 E BluetoothAdapterService(556639333): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-17 13:11:29.590  7450  7450 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-17 13:11:29.590  7450  7450 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-17 13:11:29.590  7450  7465 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-17 13:11:29.590  7450  7465 D BluetoothAdapterProperties: Setting state to 10
08-17 13:11:29.590  7450  7465 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 13:11:29.590  7450  7465 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-17 13:11:29.590  7450  7465 D BluetoothAdapterService: updateAdapterState state is 10
,08-17 13:11:29.600  7450  7465 D BluetoothAdapterService: Autoconnection is available 
08-17 13:11:29.600  7450  7465 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-17 13:11:29.600  7450  7465 I BluetoothAdapterState: Entering OffState
08-17 13:11:29.600  2046  7270 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:29.600  2046  7270 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:29.600  3071  3082 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 13:11:29.600  1444  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 13:11:29.600  1444  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:29.600  7450  7460 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 13:11:29.600  3071  6891 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 13:11:29.600  6756  6766 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:29.600  6756  6766 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 13:11:29.600  6756  6766 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-17 13:11:29.600  6756  6766 D BluetoothLeAdvertiser: Exit stop advertising
08-17 13:11:29.600  6756  6766 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-17 13:11:29.600  6756  6766 D BluetoothLeScanner: Exiting stopAllScan
,08-17 13:11:29.600  7450  7561 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:29.600  7450  7561 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:29.600  3071  3079 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 13:11:29.610  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-17 13:11:29.610  3071  3082 D BluetoothPbap: onBluetoothStateChange: up=false
,08-17 13:11:29.610  3071  6891 D Bluetoothsap: onBluetoothStateChange: up=false
08-17 13:11:29.610  3071  6891 D Bluetoothsap: Unbinding service...
,08-17 13:11:29.610  1174  1185 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 13:11:29.610  1174  1185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:29.610  1433  1448 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:29.610  1433  1448 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 13:11:29.610  7500  7509 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:29.610  7500  7509 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:29.610  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-17 13:11:29.610  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 13:11:29.610  1460  4064 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:29.610  1460  4064 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-17 13:11:29.610  3071  3079 D BluetoothAdapter: onBluetoothStateChange: up=false
08-17 13:11:29.610  3071  3079 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-17 13:11:29.610  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 13:11:29.620  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 13:11:29.620  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:29.620  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
,08-17 13:11:29.630  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 13:11:29.630  1174  1174 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
08-17 13:11:29.630  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 13:11:29.630  1174  1756 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
,08-17 13:11:29.630  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:29.630  1174  1174 D BluetoothTile:  getBluetoothState : 10
08-17 13:11:29.630  1174  1756 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
,08-17 13:11:29.630  1174  1174 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
08-17 13:11:29.630  1017  1257 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-17 13:11:29.630  1174  1174 D BluetoothAdapter: 434557692: getState() :  mService = null. Returning STATE_OFF
,08-17 13:11:29.630  1017  1445 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-17 13:11:29.630  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 13:11:29.640  1888  1888 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 13:11:29.640  2046  2229 D BluetoothAdapter: 1052742631: getState() :  mService = null. Returning STATE_OFF
08-17 13:11:29.640  2046  2229 D BluetoothAdapter: 1052742631: getState() :  mService = null. Returning STATE_OFF
,08-17 13:11:29.640  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:29.640  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:29.650  3071  3071 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:29.650  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 13:11:29.650  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 13:11:29.650  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:29.650  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:29.650  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:29.650  7450  7468 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 13:11:29.650  7450  7450 I GKI_LINUX: GKI_exit_task 1 done
,08-17 13:11:29.650  7450  7450 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-17 13:11:29.650  7450  7450 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 13:11:29.650  3071  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:29.650  1017  1257 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 13:11:29.650  1017  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 13:11:29.650  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:29.660  1017  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:29.660  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 13:11:29.660  7450  7450 I art     : System.exit called, status: 0
08-17 13:11:29.660  7450  7450 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 13:11:29.670  3071  3071 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:29.670  3071  3071 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 13:11:29.670  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:29.670  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-17 13:11:29.680  1017  1483 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-17 13:11:29.680  1017  1483 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-17 13:11:29.680  1017  1483 W BroadcastQueue: android.os.TransactionTooLargeException
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-17 13:11:29.680  1017  1483 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-17 13:11:29.680  1017  1483 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-17 13:11:29.680  1017  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:29.680  1017  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:29.680  1017  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:29.680  1017  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:29.700  7588  7588 E Zygote  : MountEmulatedStorage(),
08-17 13:11:29.700  7588  7588 I libpersona: KNOX_SDCARD checking this for 1002
08-17 13:11:29.700  7588  7588 E Zygote  : v2
08-17 13:11:29.700  7588  7588 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:29.700  7588  7588 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:11:29.700  1017  1483 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7588 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-17 13:11:29.700  7588  7588 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:29.700  7588  7588 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:29.720  7588  7588 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:29.720  7588  7588 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:29.730  7588  7588 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-17 13:11:29.730  7588  7588 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 13:11:29.760  7588  7588 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding GattService
,08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding HeadsetService
08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding A2dpService
,08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding HidService
08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding HealthService
08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding PanService
08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding SapService
08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding SapClientService
08-17 13:11:29.790  7588  7588 D BtSettings.ProfileConfig: Adding HidDevService,
08-17 13:11:29.790  7588  7588 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-17 13:11:29.790  1017  1135 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-17 13:11:29.790  1017  1135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.790  1017  1135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.790  1017  1135 D SettingsProvider: selectionArgs: false
,08-17 13:11:29.790  1017  1135 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.790  1017  1135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 13:11:29.790  1017  1135 D SettingsProvider: ret = -1
,08-17 13:11:29.800  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-17 13:11:29.800  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.800  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 13:11:29.800  1017  1030 D SettingsProvider: selectionArgs: false
08-17 13:11:29.800  1017  1030 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.800  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 13:11:29.800  1017  1030 D SettingsProvider: ret = -1
,08-17 13:11:29.800  1017  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-17 13:11:29.800  1017  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.800  1017  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.800  1017  1462 D SettingsProvider: selectionArgs: false
08-17 13:11:29.800  1017  1462 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.800  1017  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.800  1017  1462 D SettingsProvider: ret = -1
,08-17 13:11:29.800  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-17 13:11:29.800  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.800  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 13:11:29.800  1017  1029 D SettingsProvider: selectionArgs: false
08-17 13:11:29.800  1017  1029 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.800  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.800  1017  1029 D SettingsProvider: ret = -1
,08-17 13:11:29.800  1017  1445 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-17 13:11:29.800  1017  1445 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.800  1017  1445 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.800  1017  1445 D SettingsProvider: selectionArgs: false
,08-17 13:11:29.800  1017  1445 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.800  1017  1445 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 13:11:29.800  1017  1445 D SettingsProvider: ret = -1
,08-17 13:11:29.800  1017  1483 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-17 13:11:29.800  1017  1483 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.800  1017  1483 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.800  1017  1483 D SettingsProvider: selectionArgs: false
08-17 13:11:29.800  1017  1483 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.800  1017  1483 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.800  1017  1483 D SettingsProvider: ret = -1
,08-17 13:11:29.800  1017  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-17 13:11:29.800  1017  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.800  1017  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.800  1017  1490 D SettingsProvider: selectionArgs: false
08-17 13:11:29.800  1017  1490 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.800  1017  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.800  1017  1490 D SettingsProvider: ret = -1
,08-17 13:11:29.810  1017  1257 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-17 13:11:29.810  1017  1257 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.810  1017  1257 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.810  1017  1257 D SettingsProvider: selectionArgs: false
08-17 13:11:29.810  1017  1257 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:29.810  1017  1257 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.810  1017  1257 D SettingsProvider: ret = -1
,08-17 13:11:29.810  1017  2092 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:29.810  1017  2092 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:29.810  1017  2092 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.810  1017  2092 D SettingsProvider: selectionArgs: false
08-17 13:11:29.810  1017  2092 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:29.810  1017  2092 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.810  1017  2092 D SettingsProvider: ret = -1
,08-17 13:11:29.810  1017  2116 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:29.810  1017  2116 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.810  1017  2116 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.810  1017  2116 D SettingsProvider: selectionArgs: false
08-17 13:11:29.810  1017  2116 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.810  1017  2116 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.810  1017  2116 D SettingsProvider: ret = -1
,08-17 13:11:29.810  1017  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-17 13:11:29.810  1017  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:29.810  1017  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 13:11:29.810  1017  1476 D SettingsProvider: selectionArgs: false
08-17 13:11:29.810  1017  1476 D SettingsProvider: selectionArgs: 1002
08-17 13:11:29.810  1017  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.810  1017  1476 D SettingsProvider: ret = -1
,08-17 13:11:29.810  1017  2100 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-17 13:11:29.810  1017  2100 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:29.810  1017  2100 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:29.810  1017  2100 D SettingsProvider: selectionArgs: false
08-17 13:11:29.810  1017  2100 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:29.810  1017  2100 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:29.810  1017  2100 D SettingsProvider: ret = -1
,08-17 13:11:29.820  2046  2046 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:29.820  1017  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:11:29.820  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 13:11:29.830  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:29.830  1017  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:29.830  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:29.840  2046  7604 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 13:11:29.840  2046  2046 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 13:11:29.840  1017  2100 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:29.840  1017  2100 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:29.840  1017  2100 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:29.840  1017  2100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:29.850  2046  7604 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-17 13:11:31.220   287   287 E SMD     : DCD OFF
,08-17 13:11:31.400  1017  3361 D SSRM:n  : SIOP:: AP = 330
,08-17 13:11:31.850  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:31.850  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:34.220   287   287 E SMD     : DCD OFF,
,08-17 13:11:34.850  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:34.850  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1dc6f847 added. We now have 6 listener(s)
,08-17 13:11:34.850  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:34.850  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:34.850  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b478874 added. We now have 7 listener(s)
,08-17 13:11:34.850  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:34.860  6756  6850 I System.out: IsBluetoothEnabled
,08-17 13:11:34.860  6756  6850 D BluetoothAdapter: disable()
,08-17 13:11:34.860  1017  1029 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-17 13:11:34.870  1017  1445 I ActivityManager: Killing 7107:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-17 13:11:34.870  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 13:11:34.870  6756  6850 D BluetoothAdapter: enable()
,08-17 13:11:34.870  1017  1135 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-17 13:11:34.870  1017  1135 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-17 13:11:34.870  1017  1135 W BluetoothManagerService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 13:11:34.870  1017  1135 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-17 13:11:34.870  1017  1135 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-17 13:11:34.870  1017  1135 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-17 13:11:34.870  1017  1135 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 13:11:34.870  1017  1135 W ActivityManager: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 13:11:34.870  1017  1135 D SettingsProvider: name = bluetooth_on
08-17 13:11:34.870  1017  1135 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 13:11:34.870  1017  1135 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:34.890  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-17 13:11:34.890  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:34.890  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-17 13:11:34.890  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-17 13:11:34.910  7588  7588 D BluetoothAdapterState: make
,08-17 13:11:34.910  7588  7588 I bluedroid: init
,08-17 13:11:34.910  7588  7610 I BluetoothAdapterState: Entering OffState
,08-17 13:11:34.920  7588  7588 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 13:11:34.920  7588  7588 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 13:11:34.920  7588  7588 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 13:11:34.920  7588  7588 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 13:11:34.920  7588  7588 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-17 13:11:34.920  7588  7588 I bluedroid: get_profile_interface socket
,08-17 13:11:34.920  7588  7588 I bluedroid: get_profile_interface map_client
08-17 13:11:34.920  7588  7613 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-17 13:11:34.920  7588  7613 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-17 13:11:34.920  7588  7613 E BluetoothServiceJni: populateRssiValuesNative
08-17 13:11:34.920  7588  7613 I bluedroid: getModelRssiValues
08-17 13:11:34.920  7588  7613 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 13:11:34.920  7588  7613 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 13:11:34.930  7588  7588 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-17 13:11:34.930  7588  7613 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-17 13:11:34.930  1017  1017 D SettingsProvider: name = bluetooth_name
,08-17 13:11:34.930  7588  7588 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:34.940  1017  1462 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 13:11:34.940  1017  1462 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:34.940  1017  1462 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:34.940  1017  1462 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:34.940  1017  1462 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:34.940  7588  7601 I bluedroid: config_hci_snoop_log
,08-17 13:11:34.940  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 13:11:34.950  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-17 13:11:34.950  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-17 13:11:34.950  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-17 13:11:34.950  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 13:11:34.950  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:34.950  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-17 13:11:34.950  7588  7588 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-17 13:11:34.960  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-17 13:11:34.960  7588  7610 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-17 13:11:34.960  7588  7610 D BluetoothAdapterProperties: Setting state to 11
,08-17 13:11:34.960  7588  7610 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 13:11:34.960  7588  7610 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 13:11:34.960  7588  7610 D BluetoothAdapterService: updateAdapterState state is 11
,08-17 13:11:34.960  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:34.960  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-17 13:11:34.970  7588  7610 D BluetoothAdapterService: Autoconnection is available 
08-17 13:11:34.970  7588  7610 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-17 13:11:34.970  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-17 13:11:34.970  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:34.970  1174  1174 D BluetoothTile:  getBluetoothState : 11
,08-17 13:11:34.980  7588  7610 D BluetoothSecureManager: getInstant: null
08-17 13:11:34.980  7588  7610 D BluetoothSecureManager: calling getMethod for getService
08-17 13:11:34.980  7588  7610 D BluetoothSecureManager: calling getService
,08-17 13:11:34.980  7588  7610 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3a5b2c19
,08-17 13:11:34.980  1017  1257 D BluetoothSecureManagerService: isSecureModeEnabled
08-17 13:11:34.980  1017  1257 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-17 13:11:34.980  7588  7610 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 13:11:34.980  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 13:11:34.980  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 13:11:34.980  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-17 13:11:34.980  7588  7610 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-17 13:11:34.980  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
,08-17 13:11:34.980  1888  1888 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-17 13:11:34.980  7588  7610 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-17 13:11:34.980  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-17 13:11:34.980  1017  1462 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 13:11:34.980  7588  7610 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-17 13:11:34.980  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-17 13:11:34.980  7588  7610 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-17 13:11:34.980  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-17 13:11:34.980  1017  1445 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-17 13:11:34.980  7588  7610 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-17 13:11:34.980  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-17 13:11:34.980  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-17 13:11:34.990  7588  7610 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-17 13:11:34.990  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-17 13:11:34.990  3071  3071 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:34.990  7588  7610 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-17 13:11:34.990  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-17 13:11:34.990  7588  7610 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-17 13:11:34.990  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-17 13:11:34.990  7588  7610 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:34.990  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-17 13:11:34.990  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-17 13:11:34.990  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:34.990  1017  1539 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:11:34.990  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.000  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.000  1017  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:35.000  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-17 13:11:35.000  7588  7610 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:35.000  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-17 13:11:35.000  7588  7610 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-17 13:11:35.000  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 13:11:35.000  7588  7610 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-17 13:11:35.000  7588  7610 D BluetoothBondStateMachine: make
,08-17 13:11:35.000  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-17 13:11:35.000  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-17 13:11:35.000  7588  7610 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-17 13:11:35.000  1017  2092 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:35.000  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-17 13:11:35.000  3071  3071 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 13:11:35.000  7588  7615 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 13:11:35.010  1017  2092 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.010  1017  2092 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.010  1017  2092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-17 13:11:35.010  7588  7588 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 13:11:35.010  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-17 13:11:35.010  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-17 13:11:35.010  7588  7610 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-17 13:11:35.010  7588  7588 D BtGatt.GattService: Received start request. Starting profile...
,08-17 13:11:35.010  7588  7588 D BtGatt.GattService: start()
08-17 13:11:35.010  7588  7588 D BtGatt.GattService: start()
08-17 13:11:35.010  7588  7588 I bluedroid: get_profile_interface gatt
,08-17 13:11:35.010  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.010  7588  7588 D BtGatt.AdvertiseManager: advertise manager created
,08-17 13:11:35.010  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-17 13:11:35.010  1017  1135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:35.010  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-17 13:11:35.010  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-17 13:11:35.020  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.020  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.020  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.020  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-17 13:11:35.020  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-17 13:11:35.020  7588  7610 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-17 13:11:35.020  1017  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:35.020  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.020  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.020  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:35.020  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.030  7588  7588 D BtGatt.GattService: mStartError = false
,08-17 13:11:35.030  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.030  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-17 13:11:35.030  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-17 13:11:35.030  7588  7610 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-17 13:11:35.030  7588  7588 D HeadsetService: Received start request. Starting profile...
08-17 13:11:35.030  7588  7588 D HeadsetService: start()
,08-17 13:11:35.030  1017  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:35.030  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.040  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.040  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.040  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.040  7588  7588 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 13:11:35.040  7588  7588 D HeadsetStateMachine: make
,08-17 13:11:35.040  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-17 13:11:35.040  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-17 13:11:35.040  7588  7610 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-17 13:11:35.040  1017  1445 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:35.040  1017  1445 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.040  1017  1445 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.040  1017  1445 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.040  1017  1445 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.040  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-17 13:11:35.040  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-17 13:11:35.040  7588  7610 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-17 13:11:35.040  1017  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:35.040  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.040  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.040  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.040  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.050  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-17 13:11:35.050  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-17 13:11:35.050  7588  7610 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-17 13:11:35.050  7588  7588 E HeadsetStateMachine: # of Max HF connection is 2
,08-17 13:11:35.050  1017  1445 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:35.050  1017  1445 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.050  1017  1445 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.050  1017  1445 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.050  1017  1445 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.050  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-17 13:11:35.050  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-17 13:11:35.050  7588  7610 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-17 13:11:35.050  1017  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:35.050  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.050  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.060  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.060  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.060  1017  2092 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-17 13:11:35.060  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.060  1017  2092 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.060  1017  2092 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.060  1017  2092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-17 13:11:35.060  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:35.060  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:35.060  7588  7610 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-17 13:11:35.060  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:35.060  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:35.060  7588  7610 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-17 13:11:35.060  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-17 13:11:35.060  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-17 13:11:35.060  7588  7610 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-17 13:11:35.060  7588  7610 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-17 13:11:35.060  7588  7610 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-17 13:11:35.060  7588  7610 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-17 13:11:35.060  7588  7610 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 13:11:35.060  1017  2116 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-17 13:11:35.060  1017  2116 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.060  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.060  1017  2116 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.060  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-17 13:11:35.060  7588  7588 I bluedroid: get_profile_interface handsfree
,08-17 13:11:35.070  7588  7588 I DualScoManager: Instantiating Dual Sco Manager
,08-17 13:11:35.080  7588  7588 I DualScoManager: Set HeadsetServiceHelper
,08-17 13:11:35.080  7588  7588 D BluetoothAtMessage: createCMTIContentObservers
,08-17 13:11:35.080  1017  2100 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-17 13:11:35.080  1017  2100 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:35.080  1017  2100 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 13:11:35.080  1017  2100 D SettingsProvider: selectionArgs: false
08-17 13:11:35.080  1017  2100 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:35.080  1017  2100 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:35.080  1017  2100 D SettingsProvider: ret = -1
,08-17 13:11:35.080  7588  7588 D HeadsetService: mStartError = false
08-17 13:11:35.080  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.090  7588  7619 D HeadsetStateMachine: Enter Disconnected: -2
,08-17 13:11:35.090  7588  7588 D A2dpService: Received start request. Starting profile...
08-17 13:11:35.090  7588  7588 D A2dpService: start()
,08-17 13:11:35.090  7588  7619 D HeadsetStateMachine: Clear mHeadsetBrsf
08-17 13:11:35.090  7588  7588 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 13:11:35.090  7588  7619 D HeadsetStateMachine: map size, before remove : 0
,08-17 13:11:35.090  7588  7588 I bluedroid: get_profile_interface avrcp
08-17 13:11:35.090  7588  7619 D HeadsetStateMachine: map size, after remove: 0
,08-17 13:11:35.100  7588  7588 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 13:11:35.100  7588  7588 D Avrcp   : Initialize Media Controller
08-17 13:11:35.100  7588  7588 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-17 13:11:35.100  7588  7588 E Avrcp   : getActiveSessions
,08-17 13:11:35.100  7588  7588 D Avrcp   : pick active media Controller
,08-17 13:11:35.100  7588  7588 D Avrcp   : Get the active Media Controller 
,08-17 13:11:35.120  7588  7588 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-17 13:11:35.120  7588  7623 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-17 13:11:35.120  7588  7588 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 13:11:35.120  7588  7588 D A2dpStateMachine: make
,08-17 13:11:35.120  7588  7588 I bluedroid: get_profile_interface a2dp,
,08-17 13:11:35.120  7588  7625 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 13:11:35.120  7588  7588 E bt-btif : warning : media task started media_task_refcnt 1 
,08-17 13:11:35.130  7588  7588 D A2dpService: mStartError = false
08-17 13:11:35.130  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.130  7588  7624 D A2dpStateMachine: Enter Disconnected: -2
08-17 13:11:35.130  7588  7588 E BluetoothAdapterService(912475627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-17 13:11:35.130  7588  7588 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 13:11:35.130  7588  7588 D HidService: Received start request. Starting profile...
08-17 13:11:35.130  7588  7588 D HidService: start()
08-17 13:11:35.130  7588  7588 I bluedroid: get_profile_interface hidhost
08-17 13:11:35.130  7588  7588 D HidService: setHidService(): set to: null
08-17 13:11:35.130  7588  7588 D HidService: mStartError = false
08-17 13:11:35.130  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.130  7588  7588 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 13:11:35.130  7588  7588 D HealthService: Received start request. Starting profile...
08-17 13:11:35.130  7588  7588 D HealthService: start()
,08-17 13:11:35.130  7588  7623 D BluetoothMediaBrowser: no now playing list
08-17 13:11:35.130  7588  7623 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-17 13:11:35.140  7588  7588 I bluedroid: get_profile_interface health
,08-17 13:11:35.140  7588  7588 D HealthService: mStartError = false
08-17 13:11:35.140  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.140  7588  7588 I BluetoothPanServiceJni: classInitNative(L105): succeeds,
,08-17 13:11:35.140  7588  7588 D PanService: Received start request. Starting profile...
08-17 13:11:35.140  7588  7588 D PanService: start()
08-17 13:11:35.140  2046  2046 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-17 13:11:35.140  7588  7588 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 13:11:35.140  7588  7588 I bluedroid: get_profile_interface pan
,08-17 13:11:35.140  7588  7588 D PanService: mStartError = false
08-17 13:11:35.140  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.150  7588  7588 D BluetoothMapService: Received start request. Starting profile...
08-17 13:11:35.150  7588  7588 D BluetoothMapService: start()
,08-17 13:11:35.150  2046  2046 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 13:11:35.150  7588  7588 D BluetoothMapService: mStartError = false
08-17 13:11:35.150  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.150  7588  7588 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-17 13:11:35.150  7588  7588 D SapService: Received start request. Starting profile...
08-17 13:11:35.150  7588  7588 D SapService: start()
08-17 13:11:35.150  7588  7588 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-17 13:11:35.150  7588  7588 I bluedroid: get_profile_interface sap
08-17 13:11:35.150  7588  7588 D SapService: mStartError = false
08-17 13:11:35.150  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:35.150  7588  7588 D HeadsetStateMachine: Try to query the phonestate on bind
08-17 13:11:35.150  1433  1448 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 13:11:35.150  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-17 13:11:35.150  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-17 13:11:35.150  1433  1448 I Telecom : BluetoothPhoneService: Result of Message : true
,08-17 13:11:35.150  7588  7588 D HeadsetStateMachine: Proxy object connected
08-17 13:11:35.150  7588  7588 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-17 13:11:35.150  7588  7588 D HeadsetPhoneState: sendDeviceDataStateChanged
08-17 13:11:35.150  7588  7619 D HeadsetStateMachine: Disconnected process message: 11
,08-17 13:11:35.150  7588  7588 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-17 13:11:35.150  7588  7619 D HeadsetStateMachine: Disconnected process message: 18
08-17 13:11:35.150  7588  7588 E BluetoothAdapterService(912475627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-17 13:11:35.150  7588  7588 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-17 13:11:35.150  7588  7588 D BluetoothA2dp: Proxy object connected
08-17 13:11:35.150  7588  7588 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-17 13:11:35.150  7588  7619 D HeadsetStateMachine: Disconnected process message: 10
08-17 13:11:35.150  7588  7588 E BluetoothAdapterService(912475627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-17 13:11:35.150  7588  7588 E BluetoothAdapterService(912475627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-17 13:11:35.150  7588  7619 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 13:11:35.150  7588  7619 D HeadsetStateMachine: Disconnected process message: 11
,08-17 13:11:35.160  7588  7588 E BluetoothAdapterService(912475627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-17 13:11:35.160  7588  7588 E BluetoothAdapterService(912475627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-17 13:11:35.180  7588  7588 E BluetoothAdapterService(912475627): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-17 13:11:35.180  7588  7588 E BluetoothAdapterService(912475627): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-17 13:11:35.180  7588  7610 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-17 13:11:35.180  7588  7610 I bluedroid: enable
,08-17 13:11:35.180  7588  7610 I bt_hci_bdroid: init
,08-17 13:11:35.180  7588  7610 I bt_vendor: bt-vendor : init
,08-17 13:11:35.180  7588  7610 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 13:11:35.180  7588  7610 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 13:11:35.180  7588  7610 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
,08-17 13:11:35.180  7588  7610 D bt_userial_mct: userial_init
,08-17 13:11:35.180  7588  7610 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 13:11:35.180  7588  7610 I bt_vendor: Starting hciattach daemon
08-17 13:11:35.190  7588  7610 I bt_vendor: try to set false
08-17 13:11:35.190  7588  7629 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-17 13:11:35.190  7588  7610 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-17 13:11:35.190  7588  7610 I bt_vendor: Starting hciattach daemon
08-17 13:11:35.190  7588  7610 I bt_vendor: try to set true
,08-17 13:11:35.210  7634  7634 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-17 13:11:35.250  7640  7640 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 13:11:35.260  7641  7641 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-17 13:11:35.270  7643  7643 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 13:11:35.280  7644  7644 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-17 13:11:35.290  7645  7645 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-17 13:11:35.300  7646  7646 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-17 13:11:35.480  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-17 13:11:35.480  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-17 13:11:35.480  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 13:11:35.480  1017  1030 D BatteryService: stay LED for fully charged
,08-17 13:11:35.480  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 13:11:35.480  1017  1017 I MotionRecognitionService: Plugged
,08-17 13:11:35.480  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 13:11:35.480  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 13:11:35.480  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 13:11:35.490  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 13:11:35.490  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 13:11:35.500  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-17 13:11:35.500  1174  1174 D SViewCoverView: level :100 plugged : 2
,08-17 13:11:35.510  7588  7588 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-17 13:11:35.510  7588  7619 D HeadsetStateMachine: Disconnected process message: 10
,08-17 13:11:35.520  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-17 13:11:35.520  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:35.520  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-17 13:11:35.530  7649  7649 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-17 13:11:35.540  7650  7650 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 13:11:35.590  7588  7610 I bt_vendor: bluetooth satus is on
08-17 13:11:35.590  7588  7631 D bt_userial_mct: userial_open(port:0)
08-17 13:11:35.590  7588  7631 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 13:11:35.600  7588  7631 I bt_vendor: Done intiailizing UART
,08-17 13:11:35.600  7588  7631 I bt_vendor: Done intiailizing UART
08-17 13:11:35.600  7588  7631 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 13:11:35.600  7588  7631 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 13:11:35.600  7588  7652 D bt_userial_mct: Entering userial_read_thread()
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_SAP
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_BTIF
08-17 13:11:35.600  7588  7629 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-17 13:11:35.700  7588  7629 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-17 13:11:35.700  7588  7629 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa42c2ed1 
,08-17 13:11:35.710  7588  7629 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa42c2ed1 
,08-17 13:11:35.720  7588  7613 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-17 13:11:35.720  7588  7613 E bt-btif : Calling BTA_HhEnable
,08-17 13:11:35.730  7588  7613 E bt-btif : AG evt (hdl 0x0002): State 0perty service_mask:0x2120048
08-17 13:11:35.730  7588  7613 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-17 13:11:35.730  7588  7613 E BluetoothServiceJni: populateRssiValuesNative
08-17 13:11:35.730  7588  7613 I bluedroid: getModelRssiValues
08-17 13:11:35.730  7588  7613 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-17 13:11:35.730  7588  7613 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-17 13:11:35.730  7588  7613 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3),
,08-17 13:11:35.730  1017  1017 D SettingsProvider: name = bluetooth_name
,08-17 13:11:35.730  7588  7613 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-17 13:11:35.730  7588  7613 D BluetoothAdapterProperties: Scan Mode:20
08-17 13:11:35.730  7588  7613 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 13:11:35.730  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:35.730  7588  7613 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-17 13:11:35.730  7588  7613 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-17 13:11:35.730  7588  7613 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-17 13:11:35.740  7588  7613 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-17 13:11:35.740  7588  7613 E bt-btif : btif_sock_init: !vhci_init,
,08-17 13:11:35.740  7588  7613 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-17 13:11:35.740  7588  7613 D IOP_DB_BT: db_open: db_open : handle 2965557264l, read 13894 bytes onto local cache
08-17 13:11:35.740  7588  7613 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-17 13:11:35.740  7588  7613 D IOP_DB_BT: db_query: result 1
08-17 13:11:35.740  7588  7613 I         : iop_db_open: iop_db_open status 0
08-17 13:11:35.740  7588  7613 D bte_conf: Device ID record 1 : primary
08-17 13:11:35.740  7588  7613 D bte_conf:   vendorId            = 0075
08-17 13:11:35.740  7588  7613 D bte_conf:   vendorIdSource      = 0001
08-17 13:11:35.740  7588  7613 D bte_conf:   product             = 0100
08-17 13:11:35.740  7588  7613 D bte_conf:   version             = 0200
08-17 13:11:35.740  7588  7613 D bte_conf:   clientExecutableURL = 
08-17 13:11:35.740  7588  7613 D bte_conf:   serviceDescription  = 
08-17 13:11:35.740  7588  7613 D bte_conf:   documentationURL    = 
08-17 13:11:35.740  7588  7613 D bte_conf: bte_load_did_conf no section named DID2.
,08-17 13:11:35.740  7588  7610 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 13:11:35.740  7588  7610 D BluetoothAdapterProperties: ScanMode =  20
08-17 13:11:35.740  7588  7610 D BluetoothAdapterProperties: State =  11
,08-17 13:11:35.740  7588  7613 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 13:11:35.740  1017  1476 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-17 13:11:35.740  7588  7652 E bt_mct  : hci lib postload completed
,08-17 13:11:35.740  7588  7610 D BluetoothAdapterProperties: Setting state to 12
08-17 13:11:35.740  7588  7610 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 13:11:35.750  7588  7613 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-17 13:11:35.750  7588  7613 D BluetoothAdapterProperties: Scan Mode:21
08-17 13:11:35.750  7588  7613 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 13:11:35.750  1017  2100 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-17 13:11:35.750  1017  2100 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-17 13:11:35.750  1017  2100 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-17 13:11:35.750  1017  2100 D SettingsProvider: selectionArgs: false
08-17 13:11:35.750  1017  2100 D SettingsProvider: selectionArgs: 1002
,08-17 13:11:35.750  1017  2100 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-17 13:11:35.750  1017  2100 D SettingsProvider: ret = -1
,08-17 13:11:35.760  7588  7610 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-17 13:11:35.760  7588  7610 D BluetoothAdapterService: updateAdapterState state is 12
,08-17 13:11:35.760  1017  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:35.760  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.760  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.760  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:35.760  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.770  2046  7270 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:35.770  2046  7270 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 13:11:35.770  7588  7610 D BluetoothAdapterService: Autoconnection is available 
08-17 13:11:35.770  7588  7610 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-17 13:11:35.770  7588  7610 D BluetoothAdapterService: starting service from this receiver
08-17 13:11:35.770  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:35.770  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:35.770  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:35.770  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:35.770  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:35.770  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:35.770  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:35.770  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:35.770  1017  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-17 13:11:35.770  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.770  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.770  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.770  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.780  7588  7610 I BluetoothAdapterState: Entering On State from state = 11
,08-17 13:11:35.780  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:35.780  3071  7271 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:35.780  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 13:11:35.780  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:35.790  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.790  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:35.790  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.790  3071  7271 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 13:11:35.790  3071  3082 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:35.790  3071  3082 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:35.790  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 13:11:35.790  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.790  7588  7588 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-17 13:11:35.800  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.800  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.800  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.800  1444  1465 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 13:11:35.800  1444  1465 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-17 13:11:35.800  3071  3071 D BluetoothA2dp: Proxy object connected
08-17 13:11:35.800  3071  3071 D A2dpProfile: Bluetooth service connected
,08-17 13:11:35.800  1460  1757 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:35.800  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 13:11:35.800  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:35.800  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.800  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.800  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.810  1460  1757 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 13:11:35.810  3071  6891 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 13:11:35.810  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-17 13:11:35.810  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.810  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.810  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:35.810  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.810  7588  7588 I BluetoothPbapService: Handler(): got msg=1
,08-17 13:11:35.820  3071  3071 D HeadsetProfile: Bluetooth service connected
08-17 13:11:35.820  1017  1476 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 13:11:35.820  6756  6764 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:35.820  6756  6764 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:35.820  1433  7560 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:35.820  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-17 13:11:35.820  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:35.820  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.820  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.820  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-17 13:11:35.820  1433  7560 E BluetoothHeadset: BluetoothHeadset service is binded
08-17 13:11:35.820  3071  3082 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 13:11:35.820  3071  3071 D BluetoothMap: Proxy object connected
08-17 13:11:35.820  3071  3071 D MapProfile: Bluetooth service connected
08-17 13:11:35.820  3071  3071 D BluetoothMap: getConnectedDevices()
,08-17 13:11:35.820  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-17 13:11:35.820  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-17 13:11:35.820  7588  7656 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-17 13:11:35.820  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.820  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.820  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.830  3071  7271 D BluetoothPan: Binding service...
,08-17 13:11:35.830  3071  3071 D BluetoothInputDevice: Proxy object connected
,08-17 13:11:35.830  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-17 13:11:35.830  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-17 13:11:35.830  3071  3071 D HidProfile: Bluetooth service connected
,08-17 13:11:35.830  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.830  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.830  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.830  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:35.830  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-17 13:11:35.830  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-17 13:11:35.830  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.830  7588  7656 D BluetoothSocket: bindListen(): myUserId = 0
08-17 13:11:35.830  7588  7656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:35.840  1017  1017 D BluetoothA2dp: Proxy object connected
,08-17 13:11:35.840  3071  7271 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 13:11:35.840  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-17 13:11:35.840  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-17 13:11:35.840  3071  3071 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 13:11:35.840  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.840  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.840  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.840  3071  3071 D PanProfile: Bluetooth service connected
,08-17 13:11:35.840  3071  3079 D Bluetoothsap: onBluetoothStateChange: up=true
,08-17 13:11:35.840  3071  3079 D Bluetoothsap: Binding service...
08-17 13:11:35.840  7588  7656 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-17 13:11:35.840  7588  7656 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 13:11:35.840  7588  7656 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 13:11:35.840  7588  7656 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ec32e6d
08-17 13:11:35.840  7588  7656 D BluetoothSocket: channel: 19
08-17 13:11:35.840  7588  7656 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-17 13:11:35.840  3071  3079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-17 13:11:35.840  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-17 13:11:35.840  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.850  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.850  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.850  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.850  3071  3079 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-17 13:11:35.850  7588  7601 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:35.850  7588  7601 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:35.850  3071  3071 D BluetoothPbap: Proxy object connected
,08-17 13:11:35.850  3071  3071 D PbapServerProfile: Bluetooth service connected
08-17 13:11:35.850  3071  3071 D Bluetoothsap: BluetoothSAP Proxy object connected
08-17 13:11:35.850  3071  3071 D SapProfile: Bluetooth service connected
08-17 13:11:35.850  3071  3071 D Bluetoothsap: getConnectedDevices()
,08-17 13:11:35.850  1433  7560 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:35.850  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 13:11:35.850  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:35.850  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.850  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.850  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.850  1433  7560 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 13:11:35.850  1174  1200 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 13:11:35.850  1174  1200 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:35.860  1433  1448 D BluetoothAdapter: onBluetoothStateChange: up=true
08-17 13:11:35.860  1433  1448 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:35.860  7500  7512 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 13:11:35.860  7500  7512 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:35.860  1433  7560 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:35.860  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 13:11:35.860  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:35.860  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.860  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.860  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.860  1433  7560 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 13:11:35.860  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 13:11:35.860  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:35.860  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-17 13:11:35.870  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-17 13:11:35.870  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-17 13:11:35.870  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-17 13:11:35.870  1460  4064 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 13:11:35.870  1460  4064 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:35.870  7588  7657 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 13:11:35.870  3071  6891 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-17 13:11:35.870  3071  6891 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-17 13:11:35.870  1017  1046 D BluetoothPan: Binding service...
,08-17 13:11:35.870  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-17 13:11:35.870  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.880  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-17 13:11:35.880  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-17 13:11:35.880  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 13:11:35.880  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:35.880  1017  1017 I InputMethodManagerService: [BT Setting State] State =12,
08-17 13:11:35.880  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-17 13:11:35.880  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-17 13:11:35.890  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-17 13:11:35.890  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:35.890  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-17 13:11:35.890  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@255aadc0, true
,08-17 13:11:35.890  1433  1433 D BluetoothHeadset: registerMessageListener
,08-17 13:11:35.890  1888  1888 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-17 13:11:35.890  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
,08-17 13:11:35.890  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:35.890  3071  3071 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED,
,08-17 13:11:35.890  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null,
08-17 13:11:35.900  7588  7602 D HeadsetService: registerMessageListener
,08-17 13:11:35.900  7588  7602 D HeadsetService: registerMessageListener
08-17 13:11:35.900  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-17 13:11:35.900  7588  7619 D HeadsetStateMachine: Disconnected process message: 70
08-17 13:11:35.900  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-17 13:11:35.900  7588  7619 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@268e2aa2
08-17 13:11:35.900  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-17 13:11:35.900  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.900  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-17 13:11:35.900  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:35.900  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:35.900  1174  1756 D BluetoothTile:  handleUpdatestate:false name:null
08-17 13:11:35.900  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-17 13:11:35.900  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-17 13:11:35.900  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-17 13:11:35.900  3071  3071 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-17 13:11:35.900  3071  3071 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-17 13:11:35.900  3071  3071 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-17 13:11:35.900  3071  3071 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-17 13:11:35.900  7588  7619 D HeadsetStateMachine: Disconnected process message: 9
,08-17 13:11:35.900  7588  7619 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-17 13:11:35.910  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:35.910  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:35.910  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:35.910  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 13:11:35.910  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:35.910  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:35.910  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:35.910  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:35.910  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 13:11:35.910  1017  2092 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-17 13:11:35.910  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-17 13:11:35.910  7588  7658 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-17 13:11:35.910   282   684 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-17 13:11:35.910   282   684 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-17 13:11:35.910   282   684 V voice   : voice_set_parameters: exit with code(-2)
08-17 13:11:35.910   282   684 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-17 13:11:35.910   282   684 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-17 13:11:35.910   282   684 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-17 13:11:35.910   282   684 V audio_hw_primary: adev_set_parameters: exit
,08-17 13:11:35.910  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 13:11:35.910  7588  7619 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-17 13:11:35.910  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:35.910  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26c0a19d added. We now have 8 listener(s)
,08-17 13:11:35.920  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:35.920  3071  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 13:11:35.920  1017  1443 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-17 13:11:35.920  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.920  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.920  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.920  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-17 13:11:35.920  7588  7658 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 13:11:35.920  7588  7658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:35.920  1017  1539 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-17 13:11:35.920  1017  1539 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 13:11:35.920  1017  1539 D SecContentProvider2: mCursor = null
08-17 13:11:35.920  7588  7658 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-17 13:11:35.920  7588  7658 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 13:11:35.920  7588  7658 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 13:11:35.920  7588  7658 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16d1b333
08-17 13:11:35.920  7588  7658 D BluetoothSocket: channel: 5
,08-17 13:11:35.920  1017  1539 D WifiService: setWifiEnabled: false pid=6756, uid=10171
,08-17 13:11:35.920  1017  1539 D SettingsProvider: name = wifi_on
,08-17 13:11:35.930  3071  3071 D DockEventReceiver: finishStartingService: stopping service
,08-17 13:11:35.930  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:35.930  3071  3071 D BluetoothNotiBroadcastReceiver: onReceive
,08-17 13:11:35.930  1017  1476 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-17 13:11:35.930  1017  1476 D WifiService: setWifiEnabled: true pid=6756, uid=10171
08-17 13:11:35.930  1017  1476 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-17 13:11:35.930  1017  1476 W ActivityManager: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 13:11:35.930  1017  1476 D SecContentProvider2: mCursor = null
08-17 13:11:35.930  1017  1476 W WifiService: Failed getting userId using ActivityManagerNative
08-17 13:11:35.930  1017  1476 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6756, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-17 13:11:35.930  1017  1476 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-17 13:11:35.930  1017  1476 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-17 13:11:35.930  1017  1476 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-17 13:11:35.930  1017  1476 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-17 13:11:35.930  1017  1476 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-17 13:11:35.930  1017  1476 D SettingsProvider: name = wifi_on
08-17 13:11:35.930  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-17 13:11:35.930  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-17 13:11:35.940  7588  7588 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
08-17 13:11:35.940  7588  7588 D BtConfig.SecureMode: isSecureModeOn:false
,08-17 13:11:35.950  1017  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-17 13:11:35.950  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.950  1017  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-17 13:11:35.950  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:35.950  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:35.950  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-17 13:11:35.970  2046  2046 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-17 13:11:35.970  1017  1135 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-17 13:11:35.970  1017  1135 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-17 13:11:35.970  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.970  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:35.970  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:35.980  1017  1476 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-17 13:11:35.980  2046  7671 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-17 13:11:35.990  2046  2046 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-17 13:11:35.990  1017  2100 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:35.990  1017  2100 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:35.990  1017  2100 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-17 13:11:35.990  1017  2100 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:36.000  1017  1257 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-17 13:11:36.010  7588  7672 D BluetoothSocket: bindListen(): myUserId = 0
,08-17 13:11:36.010  7588  7672 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 13:11:36.010  1017  1257 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:36.010  1017  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-17 13:11:36.010  1017  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-17 13:11:36.010  7588  7672 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-17 13:11:36.010  7588  7672 D BluetoothSocket: bindListen(), new LocalSocket 
08-17 13:11:36.010  7588  7672 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-17 13:11:36.010  7588  7672 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f6a4f8f
,08-17 13:11:36.010  7588  7672 D BluetoothSocket: channel: 12
08-17 13:11:36.010  7588  7672 I BtOppRfcommListener: Accept thread started.
,08-17 13:11:36.020  2046  7671 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-17 13:11:36.270  1017  1044 D Tethering: interfaceAdded wlan0
,08-17 13:11:36.280  1017  1130 E Tethering: No numeric data
,08-17 13:11:36.280  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 13:11:36.280  1017  1130 D Tethering: clearTetheredNotification()
,08-17 13:11:36.280  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:36.280  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-17 13:11:36.290  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-17 13:11:36.290  1174  1174 D HotspotTile: updateTetherState():false, false
,08-17 13:11:36.290  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:36.290  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:36.290  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 13:11:36.290  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:36.290  1017  1124 V NetworkStats: performPollLocked() took 9ms
08-17 13:11:36.290  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:36.290  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-17 13:11:36.300  1017  1130 D Tethering: InitialState.processMessage what=4
,08-17 13:11:36.300  1017  1044 D Tethering: interfaceAdded p2p0
08-17 13:11:36.300  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:36.300  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:36.300  1017  1130 E Tethering: No numeric data
08-17 13:11:36.300  1017  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 13:11:36.300  1017  1130 D Tethering: clearTetheredNotification()
08-17 13:11:36.300  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-17 13:11:36.300  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-17 13:11:36.300  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:36.310  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:36.310  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:36.310  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 13:11:36.310  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-17 13:11:36.320  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-17 13:11:36.320  1174  1174 D HotspotTile: updateTetherState():false, false
,08-17 13:11:36.320  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 13:11:36.320   277  1016 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-17 13:11:36.320  1017  1124 V NetworkStats: performPollLocked() took 16ms
08-17 13:11:36.320   277  1016 D SoftapController: Softap fwReload - Ok
08-17 13:11:36.320  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:36.320  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:36.320  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:36.330   277  1016 D CommandListener: Setting iface cfg
08-17 13:11:36.330   277  1016 D CommandListener: Trying to bring down wlan0
,08-17 13:11:36.330   277  1016 D CommandListener: Clearing all IP addresses on wlan0
,08-17 13:11:36.330  1017  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-17 13:11:36.340  1017  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
08-17 13:11:36.340  1017  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-17 13:11:36.350  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:36.350  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-17 13:11:36.350  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-17 13:11:36.350  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-17 13:11:36.350  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:36.350  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:36.350  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:36.350  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 13:11:36.350  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:36.350  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-17 13:11:36.350  1174  1174 D HotspotTile: onReceive : 2, 0
,08-17 13:11:36.350  3071  3071 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:36.360  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:36.360  1017  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:36.360  1017  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:36.360  1017  1490 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:36.360  1017  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:36.360  1017  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 13:11:36.360  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 13:11:36.360  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 13:11:36.360  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-17 13:11:36.360  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 13:11:36.370  1626  1626 I Hs20UtilService: Starting #19
,08-17 13:11:36.370  1626  1693 I Hs20UtilService: Message received 5011
,08-17 13:11:36.380  7682  7682 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-17 13:11:36.380  7682  7682 I wpa_supplicant: Successfully initialized wpa_supplicant
08-17 13:11:36.380  7682  7682 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-17 13:11:36.390  7682  7682 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-17 13:11:36.400   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7682,
08-17 13:11:36.400   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-17 13:11:36.400  7682  7682 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-17 13:11:36.400  7682  7682 I wpa_supplicant: ssSupport state is = 1,
08-17 13:11:36.400  7682  7682 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-17 13:11:36.400  7682  7682 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-17 13:11:36.400   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7682,
08-17 13:11:36.400   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-17 13:11:36.580   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-17 13:11:36.580  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-17 13:11:36.630  7682  7682 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-17 13:11:36.630  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 13:11:36.640  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 13:11:36.640   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7682
08-17 13:11:36.640   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-17 13:11:36.640  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 13:11:36.640  7682  7682 I wpa_supplicant: ssSupport state is = 1
08-17 13:11:36.640  7682  7682 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:36.640  7682  7682 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 13:11:36.640  7682  7682 E wpa_supplicant: SIM READ ERROR
08-17 13:11:36.640  7682  7682 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-17 13:11:36.640  7682  7682 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 13:11:36.640  7682  7682 E wpa_supplicant: SIM READ ERROR
08-17 13:11:36.640  7682  7682 I wpa_supplicant: Blacklist: Clear (all) 
08-17 13:11:36.640  7682  7682 I wpa_supplicant: wpa_default_ap_write_once
08-17 13:11:36.640  7682  7682 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-17 13:11:36.640  7682  7682 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:36.640  7682  7682 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-17 13:11:36.640  7682  7682 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:36.640  7682  7682 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 13:11:36.640  7682  7682 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-17 13:11:36.640  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 13:11:36.640  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:36.640  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-17 13:11:36.700  7682  7682 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-17 13:11:36.850  7682  7682 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-17 13:11:36.850  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-17 13:11:36.860  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-17 13:11:36.870   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7682,
08-17 13:11:36.870   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-17 13:11:36.870  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 13:11:36.870  7682  7682 I wpa_supplicant: ssSupport state is = 1
08-17 13:11:36.870  7682  7682 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-17 13:11:36.870  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-17 13:11:36.880  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-17 13:11:36.880   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7682
08-17 13:11:36.880   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-17 13:11:36.880  7682  7682 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-17 13:11:36.880  7682  7682 I wpa_supplicant: ssSupport state is = 1,
08-17 13:11:36.880  7682  7682 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:36.880  7682  7682 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-17 13:11:36.880  7682  7682 E wpa_supplicant: SIM READ ERROR
08-17 13:11:36.880  7682  7682 I wpa_supplicant: wpa_default_ap_write_once
08-17 13:11:36.880  7682  7682 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-17 13:11:36.880  7682  7682 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 13:11:36.890  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 13:11:36.890  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-17 13:11:36.890  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-17 13:11:36.890  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-17 13:11:36.890  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-17 13:11:36.890  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-17 13:11:36.960  7682  7682 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-17 13:11:36.960  7682  7682 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-17 13:11:37.030  7682  7682 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-17 13:11:37.030  7682  7682 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-17 13:11:37.030  7682  7682 I wpa_supplicant: Skip scan - bUseNetwork false
,08-17 13:11:37.220   287   287 E SMD     : DCD OFF,
,08-17 13:11:37.290  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
08-17 13:11:37.290  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-17 13:11:37.290  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-17 13:11:37.340  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-17 13:11:37.340  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-17 13:11:37.350  7682  7682 I wpa_supplicant: HOTSPOT20_ENABLE called
08-17 13:11:37.350  7682  7682 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-17 13:11:37.350  7682  7682 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-17 13:11:37.350  7682  7682 E wpa_supplicant: SIM READ ERROR
08-17 13:11:37.350  7682  7682 I wpa_supplicant: Blacklist: Clear (all) 
,08-17 13:11:37.360  7682  7682 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-17 13:11:37.370  7682  7682 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-17 13:11:37.370  1017  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-17 13:11:37.370  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:37.370  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:37.370  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:37.370  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:37.370  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:37.370  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:37.370  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-17 13:11:37.380  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-17 13:11:37.380  1174  1756 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-17 13:11:37.380  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:37.390  1174  1174 D HotspotTile: onReceive : 3, 0
,08-17 13:11:37.390  3071  3071 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-17 13:11:37.400  1017  1127 E WifiConfigStore: Not a HS20
,08-17 13:11:37.400  1017  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 13:11:37.400  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 13:11:37.400  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:37.400  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:37.400  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-17 13:11:37.400  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 13:11:37.400  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:37.400  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:37.400  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:37.400  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:37.400  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:37.400  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:37.400  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:37.400  6756  6756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:37.400  1017  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-17 13:11:37.410  1626  1626 I Hs20UtilService: Starting #20
,08-17 13:11:37.410  1626  1693 I Hs20UtilService: Message received 5011
,08-17 13:11:37.410  6756  6756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:37.410  1017  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-17 13:11:37.410  7682  7682 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-17 13:11:37.410  7682  7682 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-17 13:11:37.410  7682  7682 I wpa_supplicant: reset timer : RESET_TIMER 0
08-17 13:11:37.410  7682  7682 I wpa_supplicant: P2P: Current p2p state = IDLE
08-17 13:11:37.410  7682  7682 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-17 13:11:37.410  7682  7682 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-17 13:11:37.410  7682  7682 I wpa_supplicant: First Scan Start
,08-17 13:11:37.410  7682  7682 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-17 13:11:37.420  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-17 13:11:37.420  7027  7027 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-17 13:11:37.420  7027  7027 D SecurityLogAgent: StateMachine : Current State = 1
08-17 13:11:37.420  7027  7027 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-17 13:11:37.420  1017  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-17 13:11:37.420  1017  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 13:11:37.420  1017  1127 I WifiNative-HAL: startHal
08-17 13:11:37.420  1017  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9d68b88c
08-17 13:11:37.420  1017  1127 I WifiNative-HAL: Could not start hal
,08-17 13:11:37.420  6971  6971 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 13:11:37.430  1017  1127 E WifiNative-wlan0: do suspend true
,08-17 13:11:37.430  1017  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-17 13:11:37.430   277  1016 D CommandListener: Setting iface cfg
08-17 13:11:37.430   277  1016 D CommandListener: Trying to bring up p2p0
,08-17 13:11:37.430  1017  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 13:11:37.430  1017  1126 D WifiP2pService: P2pEnablingState
,08-17 13:11:37.430  1017  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-17 13:11:37.430  1017  1126 D WifiP2pService: P2p socket connection successful
08-17 13:11:37.430  1017  1126 D WifiP2pService: P2pEnabledState
,08-17 13:11:37.430  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-17 13:11:37.430  1017  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-17 13:11:37.440  1017  1129 E ConnectivityService: updateNetworkInfo()
,08-17 13:11:37.440  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-17 13:11:37.440  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 13:11:37.440  1017  1047 D WifiDisplayController: disconnect
08-17 13:11:37.440  1017  1047 D WifiDisplayController: updateConnection
08-17 13:11:37.440  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-17 13:11:37.440  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-17 13:11:37.440  1017  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3,
08-17 13:11:37.440  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 13:11:37.440  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-17 13:11:37.440  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer,
08-17 13:11:37.440  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-17 13:11:37.450  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 13:11:37.450  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-17 13:11:37.450  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 13:11:37.450  1017  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-17 13:11:37.450  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-17 13:11:37.450  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-17 13:11:37.450  1017  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-17 13:11:37.450  1017  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-17 13:11:37.450  1017  1127 E WifiNative-wlan0: invaild command id : 215
08-17 13:11:37.450  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-17 13:11:37.450  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 13:11:37.450  1017  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-17 13:11:37.450  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:37.450  1017  1150 I WifiNative-HAL: startHal
08-17 13:11:37.450  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9e7399bc
08-17 13:11:37.450  1017  1150 I WifiNative-HAL: Could not start hal
08-17 13:11:37.450  1017  1150 E WifiScanningService: could not start HAL
08-17 13:11:37.450  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-17 13:11:37.450  1017  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 13:11:37.450  7682  7682 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 13:11:37.450  7682  7682 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-17 13:11:37.450  7682  7682 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-17 13:11:37.450  1017  1127 E WifiStateMachine: Failed to set frequency band 0
,08-17 13:11:37.460  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-17 13:11:37.460  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 13:11:37.460  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
,08-17 13:11:37.460  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  secondary type: null
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  wps: 0
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  grpcapab: 0
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  devcapab: 0
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  status: 3
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  wfdInfo: null
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-17 13:11:37.460  1017  1047 D WifiDisplayController:  SConnectInfo : null
08-17 13:11:37.460  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 13:11:37.460  1017  1126 D WifiP2pService: DeviceAddress: 0a:76:28
08-17 13:11:37.460  1017  1127 D SecContentProvider2: mCursor = null
08-17 13:11:37.460  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 13:11:37.460  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-17 13:11:37.460  1017  1127 D SecContentProvider2: mCursor = null
08-17 13:11:37.460  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 13:11:37.460  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:37.460  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:37.460  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:37.470  7370  7370 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 13:11:37.470  7370  7370 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-17 13:11:37.470  7370  7370 D FileShare-Client: Outbound.stopDelayTimer - 
,08-17 13:11:37.470  7386  7386 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-17 13:11:37.480  1017  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-17 13:11:37.480  1017  1126 D WifiP2pService: InactiveState
,08-17 13:11:37.480  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-17 13:11:37.480  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 13:11:37.480  7682  7682 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-17 13:11:37.490  1017  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-17 13:11:37.490  1017  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-17 13:11:37.960  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 13:11:37.960  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:37.960  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:37.960  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:37.960  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:37.960  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:37.960  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:37.960  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:37.970  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:37.970  6756  6850 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 13:11:37.970  6756  6850 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,08-17 13:11:37.970  6756  6850 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1457fdb Bundle[{}]
,08-17 13:11:37.980  6756  6850 I io.jxcore.node.LifeCycleMonitor: start: OK,
08-17 13:11:37.980  6756  6850 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 13:11:37.980  6756  6850 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 13:11:37.980  6756  6850 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 13:11:37.980  6756  6850 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 13:11:37.980  6756  6850 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
,08-17 13:11:37.980  6756  6850 I System.out: Running OutgoingSocketThread
,08-17 13:11:37.980  6756  7690 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1339)
,08-17 13:11:37.990  6756  7690 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57814,
08-17 13:11:37.990  6756  7690 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 13:11:38.180   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-17 13:11:38.760  7682  7682 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
,08-17 13:11:38.760  7682  7682 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-17 13:11:38.770  1017  7688 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-17 13:11:38.770  7682  7682 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-17 13:11:38.770  7682  7682 I wpa_supplicant: Trying to associate with  'G700'
,08-17 13:11:38.770  7682  7682 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-17 13:11:38.770  7682  7682 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-17 13:11:38.790  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 13:11:38.790  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:38.880  7682  7682 E wpa_supplicant: Cmd 35605 not handled
,08-17 13:11:38.880  7682  7682 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 13:11:38.880  7682  7682 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-17 13:11:38.880  7682  7682 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-17 13:11:38.880  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-17 13:11:38.880  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-17 13:11:38.880  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-17 13:11:38.880  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-17 13:11:38.880  7682  7682 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-17 13:11:38.890  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-17 13:11:38.880  7682  7682 I wpa_supplicant: Associated with F4.99.3E
08-17 13:11:38.880  7682  7682 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-17 13:11:38.880  7682  7682 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-17 13:11:38.880  7682  7682 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-17 13:11:38.880  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-17 13:11:38.880  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-17 13:11:38.880  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 13:11:38.880  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-17 13:11:38.890  1017  1130 E Tethering: No numeric data
,08-17 13:11:38.890  1017  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 13:11:38.890  1017  1130 D Tethering: clearTetheredNotification()
,08-17 13:11:38.890  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:38.890  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
08-17 13:11:38.890  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:38.890  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-17 13:11:38.890  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-17 13:11:38.890  1174  1174 D HotspotTile: updateTetherState():false, false
,08-17 13:11:38.900  7682  7682 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-17 13:11:38.900  7682  7682 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-17 13:11:38.900  1017  1124 V NetworkStats: performPollLocked() took 8ms
08-17 13:11:38.900  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:38.900  7682  7682 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-17 13:11:38.900  7682  7682 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-17 13:11:38.900  7682  7682 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 13:11:38.900  7682  7682 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-17 13:11:38.900  7682  7682 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-17 13:11:38.900  7682  7682 I wpa_supplicant: Blacklist: Clear (temp) 
08-17 13:11:38.900  7682  7682 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-17 13:11:38.900  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-17 13:11:38.900  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:38.900  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-17 13:11:38.900  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-17 13:11:38.900  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:38.910  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-17 13:11:38.910  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:38.910  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 13:11:38.910  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:38.910  1017  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-17 13:11:38.930  1017  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-17 13:11:38.930  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:38.930  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:38.930  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:38.930  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:38.930  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:38.930  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:38.930  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-17 13:11:38.930  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 13:11:38.930  1017  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-17 13:11:38.930  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:38.930  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 13:11:38.930  1017  2092 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-17 13:11:38.930  1017  2092 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-17 13:11:38.930  1017  2092 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:38.940  1017  2092 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:38.940  1017  2092 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-17 13:11:38.940  1626  1626 I Hs20UtilService: Starting #21
,08-17 13:11:38.940  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 13:11:38.940  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-17 13:11:38.940  1626  1693 I Hs20UtilService: Message received 5007
,08-17 13:11:38.950  1017  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 13:11:38.950  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-17 13:11:38.950  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-17 13:11:38.950  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:38.950  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-17 13:11:38.950  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:38.960   277  1016 D CommandListener: Setting iface cfg
,08-17 13:11:38.970  1017  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-17 13:11:38.970  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 13:11:38.970  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:38.980  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-17 13:11:38.980  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-17 13:11:38.980  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:38.980  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:38.980  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:38.980  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:38.980  1017  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-17 13:11:38.980  1017  1127 D SecContentProvider2: mCursor = null
,08-17 13:11:38.980  6756  6850 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1340)
08-17 13:11:38.980  6756  6850 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1340)
,08-17 13:11:38.990  1017  1127 E WifiNative-wlan0: do suspend false,
,08-17 13:11:38.990  1017  1126 D WifiP2pService: InactiveState{ what=143375 }
08-17 13:11:38.990  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 13:11:38.990  6756  6850 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1345)
,08-17 13:11:38.990  6756  6850 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 13:11:38.990  6756  6850 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1346)
,08-17 13:11:38.990  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 13:11:38.990  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db0d612 added. We now have 2 listener(s)
,08-17 13:11:39.000  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 13:11:39.000  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:39.000  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:39.000  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:39.000  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1970d1e3 added. We now have 9 listener(s)
08-17 13:11:39.000  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:39.000  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:39.000  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:39.010  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 13:11:39.010  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:39.010  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:39.010  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:39.010  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:39.010  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:39.010  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:39.010  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 13:11:39.010  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:39.010  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:39.010  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:39.010  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@390aba99 added. We now have 3 listener(s)
,08-17 13:11:39.010  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:39.010  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 13:11:39.010  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:39.010  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:39.010  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:39.010  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c2415e added. We now have 10 listener(s)
08-17 13:11:39.010  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:39.010  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:39.010  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:39.010  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:39.010  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:39.010  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.010  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:39.010  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:39.010  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@db0d612 removed from the list
08-17 13:11:39.010  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.010  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1970d1e3 removed from the list
,08-17 13:11:39.010  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 13:11:39.010  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:39.010  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.010  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.010  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.020  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1970d1e3 not in the list
,08-17 13:11:39.020  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.020  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.020  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39c2415e removed from the list,
08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:39.020  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.020  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-17 13:11:39.020  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@390aba99 removed from the list
08-17 13:11:39.020  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 13:11:39.020  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3454a93f added. We now have 2 listener(s)
,08-17 13:11:39.020  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 13:11:39.020  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:39.020  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:39.020  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:39.020  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3957720c added. We now have 9 listener(s)
08-17 13:11:39.020  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 13:11:39.020  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:39.030  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:39.030  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:39.030  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-17 13:11:39.030  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:39.030  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:39.030  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:39.030  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:39.030  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:39.030  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:39.030  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:39.030  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:39.030  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ed156a added. We now have 3 listener(s)
,08-17 13:11:39.030  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 13:11:39.030  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:39.030  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 13:11:39.030  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:39.030  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:39.030  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:39.030  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19749a5b added. We now have 10 listener(s)
08-17 13:11:39.030  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:39.030  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:39.030  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 13:11:39.030  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 13:11:39.030  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:39.030  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:39.040  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 13:11:39.040  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:39.040  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:39.050  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 13:11:39.050  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 13:11:39.050  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 13:11:39.050  7588  7657 D BtGatt.GattService: registerClient() - UUID=9faf4f11-7479-4bde-a9f3-32e6f86a0b73
,08-17 13:11:39.090  7588  7613 D BtGatt.GattService: onClientRegistered() - UUID=9faf4f11-7479-4bde-a9f3-32e6f86a0b73, clientIf=6
,08-17 13:11:39.090  6756  6764 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 13:11:39.100  7588  7659 D BtGatt.GattService: start scan with filters
,08-17 13:11:39.100  7588  7618 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:39.100  7588  7618 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@366345eb
,08-17 13:11:39.110  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 13:11:39.110  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 13:11:39.110  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 13:11:39.110  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:39.110  7588  7613 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 13:11:39.110  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.110  7588  7618 D BtGatt.ScanManager: allow scan with filters
08-17 13:11:39.110  7588  7618 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-17 13:11:39.110  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:39.110  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:39.110  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 13:11:39.120  7588  7618 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-17 13:11:39.120  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:39.120  7588  7613 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 13:11:39.120  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.120  7588  7618 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 13:11:39.120  7588  7618 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 13:11:39.120  7588  7613 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 13:11:39.130  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.130  6756  6850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 13:11:39.130  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:39.130  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 13:11:39.130  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.130  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 13:11:39.130  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 13:11:39.130  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:39.130  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:39.130  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:39.130  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 13:11:39.130  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 13:11:39.130  7588  7613 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-17 13:11:39.130  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.130  7588  7601 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:39.130  7588  7614 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 13:11:39.130  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 13:11:39.130  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:39.130  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:39.130  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:39.130  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 13:11:39.140  7588  7618 D BtGatt.ScanManager: filter size is 1
,08-17 13:11:39.140  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:39.140  7588  7618 D BtGatt.ScanManager: delete FilterIndex - 3
,08-17 13:11:39.140  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:39.140  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:39.140  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:39.140  7588  7613 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 13:11:39.140  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.140  7588  7618 D BtGatt.ScanManager: stopping BLe Batch
,08-17 13:11:39.140  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:39.140  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:39.140  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:39.140  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-17 13:11:39.140  7588  7613 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 13:11:39.140  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.140  7588  7618 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 13:11:39.150  7588  7613 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 13:11:39.150  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.150  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:39.150  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:39.150  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:39.150  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.150  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:39.150  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3454a93f removed from the list
08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.150  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3957720c removed from the list
08-17 13:11:39.150  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:39.150  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.150  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:39.150  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:39.150  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3957720c not in the list
08-17 13:11:39.150  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:39.150  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.150  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19749a5b removed from the list
08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:39.150  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.150  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:39.150  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:39.150  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ed156a removed from the list
,08-17 13:11:39.150  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:39.150  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d88137 added. We now have 2 listener(s)
,08-17 13:11:39.160  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 13:11:39.160  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:39.160  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:39.160  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:39.160  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@617f6a4 added. We now have 9 listener(s)
08-17 13:11:39.160  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:39.160  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:39.160  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:39.170  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:39.170  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:39.170  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:39.170  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:39.170  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:39.170  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:39.170  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:39.170  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:39.170  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:39.170  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:39.170  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:39.170  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19d6e7c2 added. We now have 3 listener(s)
,08-17 13:11:39.170  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:39.170  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:39.180  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 13:11:39.180  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:39.180  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:39.180  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 13:11:39.180  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d29f9d3 added. We now have 10 listener(s)
08-17 13:11:39.180  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:39.180  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:39.180   326   326 I ServiceManager: Waiting for service AtCmdFwd...
08-17 13:11:39.180  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:39.180  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:39.180  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 13:11:39.180  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:39.180  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:39.180  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 13:11:39.190  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:39.190  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:39.190  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 13:11:39.190  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 13:11:39.190  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 13:11:39.190  7588  7614 D BtGatt.GattService: registerClient() - UUID=8b3837df-1143-450a-94d6-9ca04e344637
,08-17 13:11:39.200  7695  7695 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-17 13:11:39.210  7695  7695 I dhcpcd  : version 5.5.6 starting,
,08-17 13:11:39.210  7695  7695 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-17 13:11:39.240  7588  7613 D BtGatt.GattService: onClientRegistered() - UUID=8b3837df-1143-450a-94d6-9ca04e344637, clientIf=6
,08-17 13:11:39.240  6756  6766 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 13:11:39.250  7588  7602 D BtGatt.GattService: start scan with filters
,08-17 13:11:39.250  7588  7618 D BtGatt.ScanManager: handling starting scan
08-17 13:11:39.250  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 13:11:39.250  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 13:11:39.250  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 13:11:39.250  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:39.250  7588  7613 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-17 13:11:39.250  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.250  7588  7618 D BtGatt.ScanManager: allow scan with filters,
,08-17 13:11:39.250  7588  7618 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 13:11:39.250  7588  7618 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-17 13:11:39.250  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 13:11:39.250  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-17 13:11:39.260  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:39.260  7588  7613 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-17 13:11:39.260  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.260  7695  7695 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-17 13:11:39.260  7695  7695 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-17 13:11:39.260  7695  7695 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-17 13:11:39.260  7695  7695 I dhcpcd  : bssid match
08-17 13:11:39.260  7695  7695 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-17 13:11:39.260  7588  7618 D BtGatt.ScanManager: Starting BLE batch scan
08-17 13:11:39.260  7588  7618 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,08-17 13:11:39.260  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 13:11:39.260  6756  6850 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 13:11:39.260  7588  7613 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 13:11:39.260  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.260  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 13:11:39.260  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:39.260  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:39.260  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.260  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:39.260  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17d88137 removed from the list
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:39.260  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@617f6a4 removed from the list
08-17 13:11:39.260  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:39.260  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:39.260  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.260  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 13:11:39.260  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:39.260  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 13:11:39.260  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@617f6a4 not in the list
,08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:39.260  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 13:11:39.260  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:39.260  7588  7613 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 13:11:39.260  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 13:11:39.260  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 13:11:39.270  7588  7659 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:39.270  7588  7614 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 13:11:39.270  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:39.270  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:39.270  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:39.270  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:39.270  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 13:11:39.270  7588  7618 D BtGatt.ScanManager: filter size is 1
08-17 13:11:39.270  7588  7618 D BtGatt.ScanManager: delete FilterIndex - 4
,08-17 13:11:39.270  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:39.270  7588  7613 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 13:11:39.270  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.270  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 13:11:39.270  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 13:11:39.270  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:39.270  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:39.270  7588  7618 D BtGatt.ScanManager: stopping BLe Batch
,08-17 13:11:39.270  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:39.270  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:39.270  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:39.270  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:39.270  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:39.270  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.270  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d29f9d3 removed from the list
08-17 13:11:39.270  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:39.270  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.270  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:39.270  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:39.270  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19d6e7c2 removed from the list
,08-17 13:11:39.280  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:39.280  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e10602f added. We now have 2 listener(s)
,08-17 13:11:39.280  7588  7613 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-17 13:11:39.280  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.280  7588  7618 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 13:11:39.280  7588  7613 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 13:11:39.280  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.280  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 13:11:39.280  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:39.280  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:39.280  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:39.280  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da1763c added. We now have 9 listener(s)
08-17 13:11:39.280  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:39.280  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:39.280  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:39.290  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:39.290  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:39.290  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:39.290  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:39.290  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:39.290  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:39.290  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:39.290  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:39.290  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:39.290  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 13:11:39.290  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:39.290  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62dad1a added. We now have 3 listener(s)
,08-17 13:11:39.290  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:39.290  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:39.290  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-17 13:11:39.290  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:39.290  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 13:11:39.290  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:39.290  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84cd04b added. We now have 10 listener(s)
08-17 13:11:39.290  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:39.290  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:39.290  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 13:11:39.290  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 13:11:39.290  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 13:11:39.290  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 13:11:39.300  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 13:11:39.300  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 13:11:39.300  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 13:11:39.310  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 13:11:39.310  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 13:11:39.310  6756  6850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 13:11:39.310  7588  7602 D BtGatt.GattService: registerClient() - UUID=d690274f-8de7-4b72-aa81-844b8000190f
,08-17 13:11:39.350  7588  7613 D BtGatt.GattService: onClientRegistered() - UUID=d690274f-8de7-4b72-aa81-844b8000190f, clientIf=6
,08-17 13:11:39.350  6756  6764 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-17 13:11:39.350  7588  7601 D BtGatt.GattService: start scan with filters
,08-17 13:11:39.350  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 13:11:39.350  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 13:11:39.350  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 13:11:39.350  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 13:11:39.360  7588  7618 D BtGatt.ScanManager: handling starting scan
,08-17 13:11:39.360  7588  7613 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-17 13:11:39.360  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.360  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:39.360  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 13:11:39.360  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 13:11:39.370  7588  7618 D BtGatt.ScanManager: allow scan with filters
08-17 13:11:39.370  7588  7618 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-17 13:11:39.370  7588  7618 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-17 13:11:39.370  7588  7613 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-17 13:11:39.370  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.370  7588  7618 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 13:11:39.370  7588  7618 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-17 13:11:39.370  7588  7613 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-17 13:11:39.370  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.370  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 13:11:39.380  7695  7695 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-17 13:11:39.380  7588  7613 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-17 13:11:39.380  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.380  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:39.390  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:39.390  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:39.390  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:39.390  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:39.390  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 13:11:39.390  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 13:11:39.390  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e10602f removed from the list
08-17 13:11:39.390  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:39.390  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da1763c removed from the list
,08-17 13:11:39.390  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
08-17 13:11:39.390  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:39.390  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:39.390  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 13:11:39.390  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.390  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:39.390  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 13:11:39.400  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:39.400  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:39.400  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da1763c not in the list
08-17 13:11:39.400  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 13:11:39.400  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 13:11:39.400  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 13:11:39.400  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 13:11:39.400  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 13:11:39.400  7588  7614 D BtGatt.GattService: stopScan() - queue size =1
,08-17 13:11:39.400  7588  7618 D BtGatt.ScanManager: filter size is 1
,08-17 13:11:39.400  7588  7618 D BtGatt.ScanManager: delete FilterIndex - 5
,08-17 13:11:39.400  7588  7657 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-17 13:11:39.400  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 13:11:39.400  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 13:11:39.400  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 13:11:39.400  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 13:11:39.400  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 13:11:39.400  7588  7613 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-17 13:11:39.400  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-17 13:11:39.400  7588  7618 D BtGatt.ScanManager: stopping BLe Batch
,08-17 13:11:39.410  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 13:11:39.410  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 13:11:39.410  6756  6850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 13:11:39.410  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 13:11:39.410  7588  7613 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-17 13:11:39.410  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.410  7588  7618 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-17 13:11:39.410  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.410  7588  7613 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-17 13:11:39.410  7588  7613 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-17 13:11:39.410  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 13:11:39.410  6756  6756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 13:11:39.420  6756  6756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 13:11:39.420  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:39.420  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:39.420  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.420  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84cd04b removed from the list
08-17 13:11:39.420  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:39.420  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.420  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:39.420  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:39.420  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62dad1a removed from the list
,08-17 13:11:39.420  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:39.420  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a962627 added. We now have 2 listener(s)
,08-17 13:11:39.420  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 13:11:39.420  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 13:11:39.420  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:39.420  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:39.420  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab850d4 added. We now have 9 listener(s)
08-17 13:11:39.420  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 13:11:39.420  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 13:11:39.430  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 13:11:39.430  6756  6850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 13:11:39.430  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 13:11:39.430  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 13:11:39.430  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 13:11:39.430  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 13:11:39.430  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 13:11:39.430  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 13:11:39.430  6756  6850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 13:11:39.430  6756  6850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 13:11:39.430  6756  6850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 13:11:39.430  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:39.440  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 13:11:39.440  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@183cc572 added. We now have 3 listener(s)
,08-17 13:11:39.440  6756  6756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 13:11:39.440  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-17 13:11:39.440  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 13:11:39.440  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 13:11:39.440  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 13:11:39.440  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e34fdc3 added. We now have 10 listener(s)
,08-17 13:11:39.440  6756  6850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 13:11:39.440  6756  6850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 13:11:39.440  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 13:11:39.440  6756  6850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 13:11:39.440  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 13:11:39.440  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.440  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 13:11:39.440  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:39.440  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a962627 removed from the list
,08-17 13:11:39.440  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.450  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab850d4 removed from the list
,08-17 13:11:39.450  6756  6850 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 13:11:39.450  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.450  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 13:11:39.450  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.450  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:39.450  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 13:11:39.450  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 13:11:39.450  6756  6850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ab850d4 not in the list
08-17 13:11:39.450  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 13:11:39.450  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 13:11:39.450  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 13:11:39.450  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 13:11:39.450  6756  6850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 13:11:39.450  6756  6850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e34fdc3 removed from the list
08-17 13:11:39.450  6756  6850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 13:11:39.450  6756  6850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 13:11:39.450  6756  6850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 13:11:39.450  6756  6850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 13:11:39.450  6756  6850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@183cc572 removed from the list
08-17 13:11:39.450  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 13:11:39.450  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-17 13:11:39.450  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 13:11:39.450  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 13:11:39.450  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 13:11:39.450  6756  6850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 13:11:39.460  6756  7703 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1353, name: My test thread name)
08-17 13:11:39.460  6756  7703 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1353, thread name: My test thread name)
08-17 13:11:39.460  6756  7703 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1353, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 13:11:39.460  6756  7704 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1355, name: My test thread name)
,08-17 13:11:39.460  6756  7704 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1355, thread name: My test thread name)
08-17 13:11:39.460  6756  7704 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1355, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 13:11:39.460  6756  6850 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 13:11:39.460  6756  6850 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 13:11:39.460  6756  6850 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 13:11:39.460  6756  6850 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 13:11:39.460  6756  6850 D com.test.thalitest.ThaliTestRunner: Total duration: 23281 ms
,08-17 13:11:39.470  7695  7695 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
08-17 13:11:39.470  6756  6850 I jxcore-log: Total number of executed tests:  80
08-17 13:11:39.470  6756  6850 I jxcore-log: 
08-17 13:11:39.470  6756  6850 I jxcore-log: Number of passed tests:  80
08-17 13:11:39.470  6756  6850 I jxcore-log: 
08-17 13:11:39.470  6756  6850 I jxcore-log: Number of failed tests:  0
08-17 13:11:39.470  6756  6850 I jxcore-log: 
08-17 13:11:39.470  6756  6850 I jxcore-log: Number of ignored tests:  0
08-17 13:11:39.470  6756  6850 I jxcore-log: 
08-17 13:11:39.470  6756  6850 I jxcore-log: Total duration:  23281
08-17 13:11:39.470  6756  6850 I jxcore-log: 
08-17 13:11:39.470  6756  6850 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 13:11:39.470  6756  6850 I jxcore-log: 
,08-17 13:11:39.470  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:39.470  6756  6850 I jxcore-log: 
08-17 13:11:39.480  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:39.480  6756  6850 I jxcore-log: 
08-17 13:11:39.480  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:39.480  6756  6850 I jxcore-log: 
,08-17 13:11:39.480  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-17 13:11:39.480  6756  6850 I jxcore-log: 
08-17 13:11:39.480  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:39.480  6756  6850 I jxcore-log: 
08-17 13:11:39.480  6756  6756 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 13:11:39.490  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:39.490  6756  6850 I jxcore-log: 
,08-17 13:11:39.490  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 13:11:39.490  6756  6850 I jxcore-log: 
,08-17 13:11:39.490  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:39.490  6756  6850 I jxcore-log: 
,08-17 13:11:39.490  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:39.490  6756  6850 I jxcore-log: 
,08-17 13:11:39.490  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
08-17 13:11:39.490  6756  6850 I jxcore-log: 
,08-17 13:11:39.490  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 13:11:39.490  6756  6850 I jxcore-log: 
,08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 13:11:39.500  6756  6850 I jxcore-log: 
,08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-17 13:11:39.500  6756  6850 I jxcore-log: 
,08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:39.500  6756  6850 I jxcore-log: 
,08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 13:11:39.500  6756  6850 I jxcore-log: 
,08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 13:11:39.500  6756  6850 I jxcore-log: 
,08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:39.500  6756  6850 I jxcore-log: 
,08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 13:11:39.500  6756  6850 I jxcore-log: 
,08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-17 13:11:39.500  6756  6850 I jxcore-log: 
08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-17 13:11:39.500  6756  6850 I jxcore-log: 
08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-17 13:11:39.500  6756  6850 I jxcore-log: 
08-17 13:11:39.500  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-17 13:11:39.500  6756  6850 I jxcore-log: 
,08-17 13:11:39.510  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 13:11:39.510  6756  6850 I jxcore-log: 
,08-17 13:11:39.510  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 13:11:39.510  6756  6850 I jxcore-log: 
,08-17 13:11:39.510  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 13:11:39.510  6756  6850 I jxcore-log: 
,08-17 13:11:39.510  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 13:11:39.510  6756  6850 I jxcore-log: 
,08-17 13:11:39.510  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-17 13:11:39.510  6756  6850 I jxcore-log: 
,08-17 13:11:39.640  6756  6756 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 13:11:39.640  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 13:11:39.640  6756  6850 I jxcore-log: 
,08-17 13:11:39.740  7710  7710 D AndroidRuntime: ,
08-17 13:11:39.740  7710  7710 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-17 13:11:39.740  7710  7710 D AndroidRuntime: CheckJNI is OFF,
08-17 13:11:39.740  7710  7710 D AndroidRuntime: readGMSProperty: start
08-17 13:11:39.740  7710  7710 D AndroidRuntime: readGMSProperty: already setted!!,
08-17 13:11:39.740  7710  7710 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 13:11:39.740  7710  7710 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 13:11:39.740  7710  7710 D AndroidRuntime: readGMSProperty: end
08-17 13:11:39.740  7710  7710 D AndroidRuntime: addProductProperty: start
,08-17 13:11:39.780  6756  6756 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-17 13:11:39.780  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 13:11:39.780  6756  6850 I jxcore-log: 
,08-17 13:11:39.800  1017  1127 E WifiNative-wlan0: do suspend true,
,08-17 13:11:39.820  1017  1126 D WifiP2pService: InactiveState{ what=143375 },
08-17 13:11:39.820  1017  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-17 13:11:39.830  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 13:11:39.830  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:39.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 13:11:39.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.830  1017  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 13:11:39.830  1017  1127 E WifiStateMachine: VerifyingLinkState enter
,08-17 13:11:39.830  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:39.840  1017  1129 D ConnectivityService: Adding iface wlan0 to network 504
08-17 13:11:39.840  1017  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-17 13:11:39.840  1017  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-17 13:11:39.840  1017  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 13:11:39.840  1017  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-17 13:11:39.840  1017  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 13:11:39.840  1017  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-17 13:11:39.840  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:39.840  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:39.840  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.840  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.840  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.840  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.850  1017  1539 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:39.850  1017  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 13:11:39.850  1017  1539 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:39.850  1017  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:39.850  1017  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-17 13:11:39.850  1626  1626 I Hs20UtilService: Starting #22
08-17 13:11:39.850  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 13:11:39.850  1626  1693 I Hs20UtilService: Message received 5007
,08-17 13:11:39.860  3071  3071 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-17 13:11:39.860  1017  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-17 13:11:39.870  7710  7710 E AffinityControl: AffinityControl: registerfunction enter
,08-17 13:11:39.880  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-17 13:11:39.880  1017  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-17 13:11:39.880  1017  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-17 13:11:39.890  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-17 13:11:39.890  1017  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-17 13:11:39.890  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-17 13:11:39.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-17 13:11:39.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.890  1017  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 13:11:39.890  1017  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 13:11:39.890  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-17 13:11:39.890  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-17 13:11:39.890  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-17 13:11:39.890  1017  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 13:11:39.890  1017  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-17 13:11:39.890  1017  1129 D ConnectivityService: LTETest block dns file not exists
,08-17 13:11:39.900  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:39.900  1017  1443 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-17 13:11:39.900  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 13:11:39.900  1017  1443 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 13:11:39.900  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.900  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.900  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.900  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:39.900  1017  1443 W ActivityManager: userId = 0, bbcId = -10000
,08-17 13:11:39.900  1017  1443 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:39.900  1017  1443 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 13:11:39.900  1626  1626 I Hs20UtilService: Starting #23
08-17 13:11:39.900  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.900  1017  1129 V NetworkStats: updateIfacesLocked()
08-17 13:11:39.900  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
,08-17 13:11:39.910  7710  7710 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-17 13:11:39.910  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:39.910  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:39.910  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-17 13:11:39.910  3071  3071 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-17 13:11:39.910  1626  1693 I Hs20UtilService: Message received 5007
08-17 13:11:39.910  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.910  1017  1129 V NetworkStats: performPollLocked() took 11ms
08-17 13:11:39.920  6756  6756 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 13:11:39.920  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-17 13:11:39.920  1017  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-17 13:11:39.920  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.920  1017  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 13:11:39.920  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.920  1017  1129 V NetworkStats: updateIfacesLocked()
08-17 13:11:39.920  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:39.920  1017  1129 V NetworkStats: performPollLocked(flags=0x1)
08-17 13:11:39.920  1017  1129 E ConnectivityService: updateNetworkInfo()
08-17 13:11:39.920  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.920  6756  6850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 13:11:39.920  6756  6850 I jxcore-log: 
08-17 13:11:39.920  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-17 13:11:39.920  3071  3071 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-17 13:11:39.920  3071  3071 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-17 13:11:39.920  3071  3862 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-17 13:11:39.920  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:39.920  1017  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:39.920  1017  1129 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.920  1017  1129 V NetworkStats: performPollLocked() took 6ms
,08-17 13:11:39.930  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 13:11:39.930  1017  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-17 13:11:39.930  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.930  1017  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-17 13:11:39.930  1017  7691 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:39.930  1017  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-17 13:11:39.930  1017  7691 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-17 13:11:39.930  1017  7691 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 13:11:39.930  1017  7691 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-17 13:11:39.930  1017  7691 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-17 13:11:39.930  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-17 13:11:39.930  1017  1483 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:39.930  1017  1135 D PackageManager: START PACKAGE DELETE: observer{794202840}
08-17 13:11:39.930  1017  1135 D PackageManager: pkg{<packageName>}
08-17 13:11:39.930  1017  1135 D PackageManager: user{0}
08-17 13:11:39.930  1017  1135 D PackageManager: caller{2000}
08-17 13:11:39.930  1017  1135 D PackageManager: flags{2}
08-17 13:11:39.930  1017  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:39.930  1017  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-17 13:11:39.930  1626  1626 I Hs20UtilService: Starting #24
08-17 13:11:39.930   277  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-17 13:11:39.930   277  1012 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-17 13:11:39.930  1626  1693 I Hs20UtilService: Message received 5007
08-17 13:11:39.930  1017  1135 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-17 13:11:39.930  1017  1135 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-17 13:11:39.930  1017  1135 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-17 13:11:39.930  1017  1135 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 13:11:39.930  1017  1135 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-17 13:11:39.930  3071  3071 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-17 13:11:39.930  1017  1129 D ConnectivityService:    accepting network in place of null
,08-17 13:11:39.940  1017  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 13:11:39.940  1017  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-17 13:11:39.940  3071  3071 I NearbySettings: MountReceiver.onReceive - Keep current state
08-17 13:11:39.940  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-17 13:11:39.940  1460  1460 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 13:11:39.940  1017  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 13:11:39.940  1017  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-17 13:11:39.940  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-17 13:11:39.940  1017  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
08-17 13:11:39.940  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-17 13:11:39.940  1017  1130 D Tethering: MasterInitialState.processMessage what=3
08-17 13:11:39.940  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-17 13:11:39.940  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-17 13:11:39.940  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-17 13:11:39.940  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-17 13:11:39.940  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-17 13:11:39.940  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-17 13:11:39.940  1017  1124 V NetworkStats: updateIfacesLocked()
08-17 13:11:39.940  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.940  1017  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-17 13:11:39.940  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:39.940  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:39.940  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-17 13:11:39.950  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-17 13:11:39.950  1017  1124 V NetworkStats: performPollLocked() took 4ms
08-17 13:11:39.950  1174  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 13:11:39.950  4802  6752 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 13:11:39.950  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.950  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.950  1017  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-17 13:11:39.950  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.950  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.950  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.950  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:39.950  1017  1443 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-17 13:11:39.950  1017  1135 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-17 13:11:39.950  1017  1135 D SecContentProvider2: mCursor = null
,08-17 13:11:39.950  1017  1490 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-17 13:11:39.950  1017  1490 D SecContentProvider2: mCursor = null
08-17 13:11:39.950  1017  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-17 13:11:39.960  1017  1257 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-17 13:11:39.960  1017  1257 D SecContentProvider2: mCursor = null
,08-17 13:11:39.960  1017  2116 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-17 13:11:39.960  1017  2116 D SecContentProvider2: mCursor = null
,08-17 13:11:39.960  1017  1476 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-17 13:11:39.960  1017  1476 D SecContentProvider2: mCursor = null
,08-17 13:11:39.960  1017  1029 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-17 13:11:39.960  1017  1029 D SecContentProvider2: mCursor = null
,08-17 13:11:39.970  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-17 13:11:39.970  1017  1042 I ActivityManager: Killing 6756:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-17 13:11:40.040  1017  7691 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-17 13:11:40.040  1017  1056 W PackageSettings: Skipping PackageSetting{32e250fe com.example.hello/10168} due to missing metadata
,08-17 13:11:40.070  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{3bb96b7 u0 com.test.thalitest/.MainActivity t3}
,08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 13:11:40.080  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:40.080  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:40.080  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:40.090  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-17 13:11:40.090  1017  1056 I ActivityManager:   Force finishing activity ActivityRecord{3bb96b7 u0 com.test.thalitest/.MainActivity t3 f}
08-17 13:11:40.090  1017  1056 W ActivityManager: Duplicate finish request for ActivityRecord{3bb96b7 u0 com.test.thalitest/.MainActivity t3 f}
,08-17 13:11:40.090  1017  7691 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 11:11:40 GMT], X-Android-Received-Millis=[1471432300103], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471432300075]}
08-17 13:11:40.090  1017  7691 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 13:11:40.090  1017  7691 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-17 13:11:40.090  1017  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-17 13:11:40.090  1017  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-17 13:11:40.090  1017  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-17 13:11:40.090  1017  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-17 13:11:40.090  1174  1739 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 13:11:40.090  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 13:11:40.090  4802  6752 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 13:11:40.110  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-17 13:11:40.110  1017  2092 I WindowState: WIN DEATH: Window{579afa1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 13:11:40.110   257  5998 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-17 13:11:40.120   257  5997 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-17 13:11:40.140  1017  2092 D InputDispatcher: Focus left window: 6756
,08-17 13:11:40.150  2645  2645 I art     : Explicit concurrent mark sweep GC freed 19564(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 791us total 44.705ms
,08-17 13:11:40.170   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-17 13:11:40.180   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-17 13:11:40.180  4802  4802 I art     : Explicit concurrent mark sweep GC freed 22678(1387KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 12MB/21MB, paused 1.334ms total 91.282ms
,08-17 13:11:40.190  1017  1462 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-17 13:11:40.190  1017  1042 D InputDispatcher: Focused application released
,08-17 13:11:40.190  1017  1042 D FocusedStackFrame: Set to : 0
,08-17 13:11:40.190  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 13:11:40.190  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 13:11:40.200  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 13:11:40.200  1017  1042 W ActivityManager: mDVFSHelper.acquire()
,08-17 13:11:40.210  1017  1042 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-17 13:11:40.220   287   287 E SMD     : DCD OFF
,08-17 13:11:40.240  1484  1484 D Launcher: onRestart, Launcher: 794370529
,08-17 13:11:40.240  1888  1888 E SamsungIME: mOCRHelper is null
,08-17 13:11:40.260  1460  1460 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 13:11:40.260  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 13:11:40.270  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-17 13:11:40.270  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:40.270  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-17 13:11:40.280  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-17 13:11:40.280  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-17 13:11:40.280  1017  1124 V NetworkStats: performPollLocked() took 8ms
08-17 13:11:40.280  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-17 13:11:40.290  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-17 13:11:40.290  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:40.290  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-17 13:11:40.300  1484  1484 D Launcher: onStart, Launcher: 794370529
08-17 13:11:40.300  1484  1484 D Launcher.HomeView: onStart
08-17 13:11:40.300  1484  1484 D Launcher: onResume, Launcher: 794370529
08-17 13:11:40.300  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:40.300  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-17 13:11:40.300  1017  1476 D SettingsProvider: name = kids_home_mode
08-17 13:11:40.300  1017  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-17 13:11:40.300  1017  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-17 13:11:40.300  1017  1476 D SettingsProvider: selectionArgs: false
08-17 13:11:40.300  1017  1476 D SettingsProvider: selectionArgs: 10006
08-17 13:11:40.300  1017  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-17 13:11:40.300  1017  1476 D SettingsProvider: ret = -1
08-17 13:11:40.300  1484  1484 D Launcher.HomeView: onResume
,08-17 13:11:40.350  2876  2876 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 17 13:11:40 GMT+02:00 2016,
,08-17 13:11:40.350  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,08-17 13:11:40.360  1444  1444 D RegisteredServicesCache: empty dynamic service
,08-17 13:11:40.380  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-17 13:11:40.380  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-17 13:11:40.380  1017  1056 I art     : Explicit concurrent mark sweep GC freed 78988(5MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 24MB/37MB, paused 5.730ms total 271.696ms
08-17 13:11:40.380  1017  1017 I art     : WaitForGcToComplete blocked for 269.089ms for cause Explicit
,08-17 13:11:40.400  1444  1444 D RegisteredComponentCache: Collect Tech packages for Knox
,08-17 13:11:40.400  1444  1444 D PersonaManager: isKioskContainerExistOnDevice
,08-17 13:11:40.410  1017  1056 D PackageManager: delete codoeFile: 
,08-17 13:11:40.420  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-17 13:11:40.420  1017  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-17 13:11:40.420  1017  1056 D PackageManager: result of delete: 1{794202840}
,08-17 13:11:40.440  7710  7710 D AndroidRuntime: Shutting down VM
,08-17 13:11:40.440  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-17 13:11:40.440  1017  1056 D PackageManager: userId{-1}
08-17 13:11:40.440  1017  1056 D PackageManager: andCode{true}
,08-17 13:11:40.440  1017  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 13:11:40.450  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-17 13:11:40.470  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.470  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.470  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.470  1017  1056 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:40.490  7745  7745 E Zygote  : MountEmulatedStorage(),
08-17 13:11:40.490  7745  7745 E Zygote  : v2
08-17 13:11:40.490  7745  7745 I libpersona: KNOX_SDCARD checking this for 10003
,08-17 13:11:40.490  7745  7745 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:40.490  7745  7745 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-17 13:11:40.500  7745  7745 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-17 13:11:40.500  1017  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7745 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
,08-17 13:11:40.500  7745  7745 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:40.530  7745  7745 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:40.530  7745  7745 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:40.530  1017  1017 I art     : Explicit concurrent mark sweep GC freed 8816(666KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.780ms total 149.831ms
,08-17 13:11:40.530  1017  2100 I art     : WaitForGcToComplete blocked for 288.476ms for cause Explicit
,08-17 13:11:40.560  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-17 13:11:40.560  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-17 13:11:40.570  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-17 13:11:40.570  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-17 13:11:40.570  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-17 13:11:40.570  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-17 13:11:40.570  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-17 13:11:40.630  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-17 13:11:40.630  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 13:11:40.630  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-17 13:11:40.630  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-17 13:11:40.640  1017  3361 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-17 13:11:40.640  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-17 13:11:40.640  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=3_task.xml
08-17 13:11:40.640  7710  7710 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-17 13:11:40.640  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-17 13:11:40.640  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-17 13:11:40.680  1017  2100 I art     : Explicit concurrent mark sweep GC freed 5166(291KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.910ms total 142.575ms,
08-17 13:11:40.680  2046  2220 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-17 13:11:40.680  1017  2116 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-17 13:11:40.680  1017  1029 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-17 13:11:40.680  1017  2116 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-17 13:11:40.680  1017  1029 D SecContentProvider2: mCursor = null
,08-17 13:11:40.680  1017  2116 W ActivityManager: userId = 0, bbcId = -10000
08-17 13:11:40.680  1017  2116 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-17 13:11:40.680  1017  2116 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-17 13:11:40.680  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-17 13:11:40.680  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0,
08-17 13:11:40.680  1017  1041 W TextServicesManagerService: no available spell checker services found
08-17 13:11:40.680  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-17 13:11:40.700  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-17 13:11:40.700  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.700  1484  1484 D MenuAppsGridFragment: onResume
,08-17 13:11:40.700  2876  2876 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-17 13:11:40.710  1017  1445 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-17 13:11:40.710  1017  1445 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-17 13:11:40.710  1484  1484 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-17 13:11:40.710  1017  1445 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
08-17 13:11:40.710  1484  1484 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-17 13:11:40.710  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.710  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.710  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.710  1017  1445 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:40.710  2876  2876 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-17 13:11:40.710  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.720  2876  2876 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-17 13:11:40.720  7762  7762 E Zygote  : MountEmulatedStorage()
08-17 13:11:40.720  7762  7762 E Zygote  : v2
08-17 13:11:40.720  7762  7762 I libpersona: KNOX_SDCARD checking this for 10090
08-17 13:11:40.720  7762  7762 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:40.730  2876  2876 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-17 13:11:40.730  7762  7762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:40.730  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.730  1017  1445 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7762 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-17 13:11:40.730  2876  7761 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-17 13:11:40.730  2876  7761 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-17 13:11:40.730  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.740  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-17 13:11:40.740  7762  7762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-17 13:11:40.740  7762  7762 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-17 13:11:40.740  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.740  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.740  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.740  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-17 13:11:40.740  1017  1443 I TactileAssist: enable value -1
08-17 13:11:40.740  1017  1443 I TactileAssist: internal enable value -1
08-17 13:11:40.740  1017  1443 I TactileAssist: intensity value -1
08-17 13:11:40.740  1017  1443 I TactileAssist: saveAppList value true
,08-17 13:11:40.750  1017  1443 I TactileAssist: List of disabled apps :
,08-17 13:11:40.760  7772  7772 E Zygote  : MountEmulatedStorage(),
,08-17 13:11:40.760  7772  7772 E Zygote  : v2,
08-17 13:11:40.760  7772  7772 I libpersona: KNOX_SDCARD checking this for 1000
08-17 13:11:40.760  7772  7772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 13:11:40.760  7772  7772 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:40.760  7762  7762 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-17 13:11:40.760  7772  7772 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:40.760  1017  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7772 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 13:11:40.760  2876  7761 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-17 13:11:40.760  7772  7772 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 13:11:40.770  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-17 13:11:40.770  2876  7761 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-17 13:11:40.780  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.780  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.780  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.780  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 13:11:40.780  7762  7762 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:40.780   313   313 I art     : Explicit concurrent mark sweep GC freed 8706(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 627us total 22.907ms
,08-17 13:11:40.800   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.580ms
,08-17 13:11:40.810  7772  7772 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-17 13:11:40.820  7772  7772 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:40.820   313   313 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 16.661ms
,08-17 13:11:40.830  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-17 13:11:40.830  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.830  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.830  7794  7794 E Zygote  : MountEmulatedStorage()
,08-17 13:11:40.830  7794  7794 E Zygote  : v2
08-17 13:11:40.830  7794  7794 I libpersona: KNOX_SDCARD checking this for 1000
08-17 13:11:40.830  7794  7794 I libpersona: KNOX_SDCARD not a persona
,08-17 13:11:40.840  7794  7794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-17 13:11:40.840  7794  7794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 13:11:40.840  7794  7794 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-17 13:11:40.840  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.850  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-17 13:11:40.850  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 13:11:40.850  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-17 13:11:40.850  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.850  1017  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7794 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-17 13:11:40.850  1017  1483 D ActivityManager: handle home activity for 0
08-17 13:11:40.850  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{2a045e3c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1}
08-17 13:11:40.850  1017  1483 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-17 13:11:40.850  2876  7761 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-17 13:11:40.850  1017  1483 D KnoxTimeoutHandler: post home show event for user 0
08-17 13:11:40.850  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-17 13:11:40.850  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-17 13:11:40.850  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-17 13:11:40.850  1017  1483 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-17 13:11:40.850  1017  1483 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-17 13:11:40.850  1017  1483 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 13:11:40.850  1484  1484 D Launcher.HomeView: onPause
08-17 13:11:40.850  1484  1484 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-17 13:11:40.850  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-17 13:11:40.860  7794  7794 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 13:11:40.860  7794  7794 D ActivityThread: Added TimaKeyStore provider
,08-17 13:11:40.860  2876  7761 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-17 13:11:40.870  2876  7761 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:40.870  2876  7761 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-17 13:11:40.870  2876  7761 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 13:11:40.870  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 13:11:40.870  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 13:11:40.870  2876  7761 W SQLiteOpenHelper: Opened klms.db in read-only mode
08-17 13:11:40.870  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 13:11:40.870  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 13:11:40.870  2876  7761 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-17 13:11:40.880  2876  7761 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-17 13:11:40.880  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.880  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 13:11:40.880  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 13:11:40.880  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-17 13:11:40.880  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-17 13:11:40.890  1484  1484 I Choreographer: Skipped 37 frames!  The application may be doing too much work on its main thread.
,08-17 13:11:40.890  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-17 13:11:40.890  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-17 13:11:40.900  2876  2876 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-17 13:11:40.900  1484  1574 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-17 13:11:40.900  1484  1574 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-17 13:11:40.900  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-17 13:11:40.910   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher

```
