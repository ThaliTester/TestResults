#### Test 807613740d5db28_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-16 14:40:25.881   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
08-16 14:40:25.951   288   288 E SMD     : DCD OFF
--------- beginning of system
08-16 14:40:26.211  1014  2722 D SSRM:n  : SIOP:: AP = 310
,08-16 14:40:26.751  6167  6167 D AndroidRuntime: 
08-16 14:40:26.751  6167  6167 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 14:40:26.751  6167  6167 D AndroidRuntime: CheckJNI is OFF
08-16 14:40:26.751  6167  6167 D AndroidRuntime: readGMSProperty: start
08-16 14:40:26.751  6167  6167 D AndroidRuntime: readGMSProperty: already setted!!
08-16 14:40:26.751  6167  6167 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 14:40:26.751  6167  6167 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 14:40:26.751  6167  6167 D AndroidRuntime: readGMSProperty: end
08-16 14:40:26.751  6167  6167 D AndroidRuntime: addProductProperty: start
08-16 14:40:26.911  6167  6167 E AffinityControl: AffinityControl: registerfunction enter
08-16 14:40:26.931  6167  6167 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 14:40:26.941  1014  3215 E PersonaManagerService: inState():  stateMachine is null !!
08-16 14:40:26.941  1014  3215 I PersonaManagerService: PersonaId don't exist
08-16 14:40:26.941  1014  3215 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 14:40:26.941  1014  3215 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 14:40:26.961  1014  3215 W ActivityManager: mDVFSHelper.acquire()
08-16 14:40:26.961  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 14:40:26.961  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 14:40:26.961  1014  3215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:26.961  1014  3215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:26.961  1014  3215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:26.961  1014  3215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:26.981  6178  6178 E Zygote  : MountEmulatedStorage()
08-16 14:40:26.981  6178  6178 E Zygote  : v2
08-16 14:40:26.981  6178  6178 I libpersona: KNOX_SDCARD checking this for 10155
08-16 14:40:26.981  6178  6178 I libpersona: KNOX_SDCARD not a persona
08-16 14:40:26.981  1014  3215 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6178 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 14:40:26.981  1014  3215 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-16 14:40:26.981  1014  3215 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 14:40:26.981  1014  3215 D InputDispatcher: Focused application set to: xxxx
08-16 14:40:26.981  1014  3215 D InputDispatcher: Focus left window: 3178
08-16 14:40:26.981  6167  6167 D AndroidRuntime: Shutting down VM
08-16 14:40:26.981  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 14:40:26.981  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 14:40:26.981   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-16 14:40:26.991  6178  6178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:40:26.991  6178  6178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:40:26.991  6178  6178 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 14:40:27.011  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 14:40:27.011  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 14:40:27.011  6178  6178 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 14:40:27.011  6178  6178 D ActivityThread: Added TimaKeyStore provider
08-16 14:40:27.021  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 14:40:27.041  1014  1026 D PersonaManager: isKioskContainerExistOnDevice
08-16 14:40:27.061   258   440 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-16 14:40:27.061   258  1093 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-16 14:40:27.071  3178  3178 V ActivityThread: updateVisibility : ActivityRecord{1fb99591 token=android.os.BinderProxy@2aa6e97c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-16 14:40:27.151  6178  6178 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-16 14:40:27.171  6178  6178 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9988-9990)
08-16 14:40:27.171  6178  6178 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:40:27.181  1014  1092 V AlarmManager: waitForAlarm result :4
08-16 14:40:27.191  6178  6178 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8a28a1d}
08-16 14:40:27.191  1014  1092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
08-16 14:40:27.191  6167  6167 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-16 14:40:27.191  6178  6178 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:40:27.191  6178  6178 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 14:40:27.231  6178  6178 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 14:40:27.231  6178  6178 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:40:27.231  6178  6178 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 14:40:27.251  1911  1911 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-16 14:40:27.271  6178  6178 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-16 14:40:27.271  6178  6178 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-16 14:40:27.271  6178  6178 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-16 14:40:27.281  6178  6178 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 14:40:27.281  6178  6178 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:40:27.281  6178  6178 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:40:27.281  6178  6178 I Adreno-EGL: Local Branch: 
08-16 14:40:27.281  6178  6178 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:40:27.281  6178  6178 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:40:27.281  6178  6178 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 14:40:27.421  1014  1208 I art     : Explicit concurrent mark sweep GC freed 43369(2MB) AllocSpace objects, 18(288KB) LOS objects, 33% free, 27MB/41MB, paused 2.398ms total 146.915ms
,08-16 14:40:27.441  3757  3757 D ConnectivityManager: CallingUid : 10012, CallingPid : 3757
,08-16 14:40:27.451  1014  3224 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 14:40:27.451  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-16 14:40:27.451  1014  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-16 14:40:27.451  1014  3204 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:40:27.451  1014  3204 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
08-16 14:40:27.451  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-16 14:40:27.451  3757  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 14:40:27.451  1014  3204 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:27.451  1014  3204 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:27.451  1014  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:27.511  3757  6214 W DriveInitializer: Background init thread started
,08-16 14:40:27.541  1014  1039 W ActivityManager: Activity pause timeout for ActivityRecord{15652d91 u0 com.test.thalitest/.MainActivity t129}
,08-16 14:40:27.561  6178  6206 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-16 14:40:27.591   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-16 14:40:27.591   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:40:27.591  3757  6214 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-16 14:40:27.621  6178  6178 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:40:27.631  6178  6178 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 14:40:27.641  6178  6178 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 14:40:27.641  6178  6178 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-16 14:40:27.651  1014  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:40:27.651  1014  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-16 14:40:27.651  1014  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:27.651  1014  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:27.651  1014  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 14:40:27.651  6178  6178 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-16 14:40:27.661  6178  6178 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:40:27.661  6178  6178 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:40:27.671  1014  1336 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-16 14:40:27.671  1014  1336 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-16 14:40:27.671  3757  6214 W DriveInitializer: Background init thread ended
,08-16 14:40:27.701  1014  3224 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:40:27.701  1014  3224 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-16 14:40:27.701  1014  3224 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:27.701  1014  3224 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:27.701  1014  3224 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:27.721  6178  6229 D OpenGLRenderer: Render dirty regions requested: true
,08-16 14:40:27.721  1014  1207 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 14:40:27.721  1014  1207 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-16 14:40:27.721  1014  1207 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 14:40:27.731  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 14:40:27.731  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 14:40:27.731  6178  6178 V ActivityThread: updateVisibility : ActivityRecord{380420bc token=android.os.BinderProxy@e0ec48e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-16 14:40:27.741  6178  6178 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-16 14:40:27.741  6178  6178 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-16 14:40:27.741  3757  6228 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-16 14:40:27.741  3757  6228 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-16 14:40:27.741   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,08-16 14:40:27.751  1014  1559 D InputDispatcher: Focus entered window: 6178
,08-16 14:40:27.751  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 14:40:27.761  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 14:40:27.761  6178  6178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-16 14:40:27.761  6178  6229 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 14:40:27.761  6178  6229 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-16 14:40:27.761  6178  6229 D OpenGLRenderer: Enabling debug mode 0
,08-16 14:40:27.771  1911  1911 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 14:40:27.811  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:27.811  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:27.811  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:27.831  1014  1336 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 14:40:27.841  6178  6178 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e0ec48e time:120664
,08-16 14:40:27.841  1176  1176 D PanelView: There is/are notification(s) 
,08-16 14:40:27.841  1014  6232 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 14:40:27.851  6178  6178 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-16 14:40:27.861  1014  1044 I ActivityManager: Displayed Component not be shown by security: +813ms (total +6s785ms)
,08-16 14:40:27.861  1816  1816 I SamsungIME: getCurrentCandidateView
,08-16 14:40:27.861  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{15652d91 u0 com.test.thalitest/.MainActivity t129} time:120681
08-16 14:40:27.861  1014  1044 W ActivityManager: mDVFSHelper.release()
,08-16 14:40:27.861   258   440 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,08-16 14:40:27.861   258  4438 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,08-16 14:40:27.881  1014  1208 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:40:27.891  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-16 14:40:27.891  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:27.891  1014  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:40:27.891  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:27.941  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:40:27.941  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-16 14:40:27.941  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:27.941  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:40:27.941  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:27.941  1816  1816 D SamsungIME: Dismiss ExpandCandiate
,08-16 14:40:27.951  6178  6178 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6178
,08-16 14:40:27.961  1014  1092 V AlarmManager: waitForAlarm result :4
,08-16 14:40:28.001  1014  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:28.011  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:28.011  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:40:28.011  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:28.071  1014  1208 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:28.081  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:28.081  1014  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:28.081  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:28.081  6178  6178 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 14:40:28.121  1816  1816 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 14:40:28.151  1014  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:28.161  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:28.161  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:40:28.161  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 14:40:28.161  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 14:40:28.161  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:28.161  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:28.161  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-16 14:40:28.181  6241  6241 E Zygote  : MountEmulatedStorage()
,08-16 14:40:28.181  6241  6241 E Zygote  : v2
08-16 14:40:28.181  6241  6241 I libpersona: KNOX_SDCARD checking this for 10012
08-16 14:40:28.181  6241  6241 I libpersona: KNOX_SDCARD not a persona
08-16 14:40:28.181  6241  6241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:40:28.181  1014  1491 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6241 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-16 14:40:28.181  6241  6241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:40:28.191  6241  6241 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 14:40:28.201  1816  1816 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 14:40:28.211  6241  6241 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:40:28.211  6241  6241 D ActivityThread: Added TimaKeyStore provider
,08-16 14:40:28.211  6178  6233 D jxcore_app_log: JniHelper::setJavaVM(0xb7656328), pthread_self() = -1212469960
,08-16 14:40:28.221  1816  1816 I SamsungIME: KeybaordView init() : load resources
,08-16 14:40:28.231  6178  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 14:40:28.231  6178  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 14:40:28.231  6178  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 14:40:28.231  6178  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 14:40:28.231  6178  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 14:40:28.231  6178  6233 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fef30ec added. We now have 1 listener(s)
,08-16 14:40:28.231  6178  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-16 14:40:28.241  6178  6233 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 14:40:28.241  6178  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:40:28.241  6178  6233 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 14:40:28.241  6178  6233 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364b0ebb added. We now have 1 listener(s)
,08-16 14:40:28.241  6178  6233 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:40:28.241  6241  6241 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 14:40:28.241  6241  6241 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 14:40:28.251  1816  1816 I SamsungIME: getCurrentKeyboard
08-16 14:40:28.251  1816  1816 I SamsungIME: getTextKeyboard
,08-16 14:40:28.251  6178  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:40:28.251  6178  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 14:40:28.261  6178  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-16 14:40:28.261  6178  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-16 14:40:28.261  6178  6233 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 14:40:28.261  6178  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:40:28.271  1816  1816 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 14:40:28.271  6178  6233 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-16 14:40:28.281  6178  6233 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 14:40:28.291  6178  6233 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:40:28.291  6178  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:40:28.291  6178  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:40:28.291  6178  6233 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:40:28.291  6178  6233 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:40:28.291  6178  6233 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:40:28.291  6178  6233 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:40:28.291  6178  6233 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:40:28.291  6178  6233 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 14:40:28.291  6178  6233 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:40:28.291  6178  6233 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 14:40:28.291  6178  6178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:40:28.291  6178  6178 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:40:28.291  6241  6241 I MultiDex: VM with version 2.1.0 has multidex support
08-16 14:40:28.291  6241  6241 I MultiDex: install
08-16 14:40:28.291  6241  6241 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 14:40:28.341  6178  6178 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 14:40:28.341  6241  6241 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 14:40:28.371  1014  1558 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:28.381  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:28.381  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:28.381  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:28.381  1014  1336 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-16 14:40:28.401  1014  1208 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:28.401  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:28.401  1014  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:28.401  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:28.401  6241  6241 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 14:40:28.411  6241  6241 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c7ba1ee: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 14:40:28.411  6241  6241 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 14:40:28.431  6241  6241 D ChimeraCfgMgr: Reading stored module config
,08-16 14:40:28.531  1911  1927 I art     : Explicit concurrent mark sweep GC freed 58545(3MB) AllocSpace objects, 9(384KB) LOS objects, 39% free, 13MB/23MB, paused 1.584ms total 106.962ms
,08-16 14:40:28.541  6241  6255 I art     : Background sticky concurrent mark sweep GC freed 27848(1317KB) AllocSpace objects, 3(133KB) LOS objects, 6% free, 10MB/11MB, paused 6.900ms total 68.075ms
,08-16 14:40:28.561  1911  1911 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=fe5dc3e7-dce3-44f7-bd88-714c6d571c2b
,08-16 14:40:28.561  6241  6267 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-16 14:40:28.571  6241  6241 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 14:40:28.571  6241  6241 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 14:40:28.591  1014  1208 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 14:40:28.591  1014  1208 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 14:40:28.591  1014  1208 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:28.591  1014  1208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:28.591  1014  1208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:28.601  1911  1911 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 14:40:28.601  1911  1911 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 14:40:28.651  1014  3204 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:28.651  1014  3204 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:28.651  1014  3204 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:28.651  1014  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:28.671   282   680 D WVCdm   : Instantiating CDM.
,08-16 14:40:28.671   282   282 I WVCdm   : CdmEngine::OpenSession
,08-16 14:40:28.671   282   282 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-16 14:40:28.691   282   282 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-16 14:40:28.701  1658  2131 I art     : Explicit concurrent mark sweep GC freed 1409(48KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 846us total 23.724ms
,08-16 14:40:28.721   282   282 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-16 14:40:28.721   282   282 D DrmWidevineDash: Service_Initialize: starts!
08-16 14:40:28.721   282   282 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-16 14:40:28.721   282   282 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 14:40:28.721   282   282 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-16 14:40:28.721   282   282 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 14:40:28.721   282   282 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 14:40:28.721   282   282 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 14:40:28.731   282   282 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-16 14:40:28.731   282   282 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 14:40:28.731   282   282 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 14:40:28.731   282   282 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 14:40:28.751   282   282 D QSEECOMAPI: : Loaded image: APP id = 11
,08-16 14:40:28.751   282   282 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-16 14:40:28.761   282   282 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-16 14:40:28.761   282   282 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-16 14:40:28.761   282   282 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb166a000
08-16 14:40:28.761   282   282 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb166a000
08-16 14:40:28.761   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:28.771   418   429 D DrmLibTime: got the req here! ret=0
08-16 14:40:28.771   418   429 D DrmLibTime: command id, time_cmd_id = 770
08-16 14:40:28.771   418   429 D DrmLibTime: time_getutcsec starts!
08-16 14:40:28.771   418   429 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-16 14:40:28.771   418   429 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-16 14:40:28.771   418   429 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-16 14:40:28.771   418   429 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-16 14:40:28.781   418   429 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-16 14:40:28.781   418   429 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-16 14:40:28.781   418   429 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,08-16 14:40:28.781   418   429 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-16 14:40:28.781   317   556 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-16 14:40:28.781   317  6272 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0,
08-16 14:40:28.781   317  6272 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
,08-16 14:40:28.781   317  6272 D QC-time-services: offset is: 0 for base: 0
,08-16 14:40:28.781   418   429 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-16 14:40:28.781   418   429 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,08-16 14:40:28.781   418   429 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1471351228
,08-16 14:40:28.781   418   429 D DrmLibTime: time_getutcsec returns 0, sec = 1471351228; nsec = 0
08-16 14:40:28.781   418   429 D DrmLibTime: time_getutcsec finished! ,
,08-16 14:40:28.781   418   429 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-16 14:40:28.781   418   429 D DrmLibTime: before calling ioctl to read the next time_cmd
08-16 14:40:28.781   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:40:28.781   317   556 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-16 14:40:28.801   282   282 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-16 14:40:28.801   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-16 14:40:28.801   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:28.801   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:40:28.801   282   282 D DrmWidevineDash: hlos api version =  9
08-16 14:40:28.801   282   282 D DrmWidevineDash: tz api version =  9
08-16 14:40:28.801   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
,08-16 14:40:28.801   282   282 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-16 14:40:28.801   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:28.821  6241  6250 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-16 14:40:28.821  6241  6250 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 14:40:28.821  6241  6250 I System.out: (HTTPLog)-Static: isShipBuild true
08-16 14:40:28.821  6241  6250 I System.out: (HTTPLog)-Thread-1043-976385571: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-16 14:40:28.821  6241  6250 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:40:28.821   277  1008 D EnterpriseController: uids 10012
08-16 14:40:28.821   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:40:28.821   277  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 14:40:28.831   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:40:28.831   282   282 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-16 14:40:28.831   282   282 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-16 14:40:28.831   282   282 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbec671b0
08-16 14:40:28.831   282   282 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-16 14:40:28.831   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
08-16 14:40:28.831   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:40:28.831   282   282 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-16 14:40:28.831   282   282 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-16 14:40:28.831   282   282 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8cb0330, dataLength=8
,08-16 14:40:28.831   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:40:28.831   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:40:28.831   282   282 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-16 14:40:28.841   282   282 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb8c6a820, wrapped_rsa_key_length=1280
08-16 14:40:28.841   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:28.841   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:40:28.841   282   282 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-16 14:40:28.841   282   282 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-16 14:40:28.841   282   680 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-16 14:40:28.841   282   680 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-16 14:40:28.841   282   680 I WVCdm   : CdmEngine::GenerateKeyRequest
08-16 14:40:28.841   282   680 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8c651d8, idLength=0xb18be730
08-16 14:40:28.841   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb18be746, maximum = 0xb18be747
08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:40:28.861   282   680 D DrmWidevineDash: hlos api version =  9
08-16 14:40:28.861   282   680 D DrmWidevineDash: tz api version =  9
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18be7b4
08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:40:28.861   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:40:28.861   282   680 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-16 14:40:28.861   282   680 D WVCdm   : PrepareKeyRequest: nonce=4268089649
,08-16 14:40:28.871   282   680 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8c67f78
,08-16 14:40:28.871   282   680 D DrmWidevineDash: message_length=1599, signature=0xb8c83ce0, signature_length=0xb18be714
,08-16 14:40:28.871   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:40:28.881  6241  6250 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 14:40:28.881  6241  6250 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6241, getuid(): 10012
,08-16 14:40:28.951   288   288 E SMD     : DCD OFF
,08-16 14:40:29.031  1911  2105 W GCoreFlp: No location to return for getLastLocation()
,08-16 14:40:29.031   282   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:40:29.031   282   680 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-16 14:40:29.031   282   689 I WVCdm   : CdmEngine::CloseSession
,08-16 14:40:29.031   282   689 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-16 14:40:29.031   282   689 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:29.031   282   689 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:40:29.031   282   689 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-16 14:40:29.031   282   689 I WVCdm   : L3 Terminate.
,08-16 14:40:29.031   282   689 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-16 14:40:29.031   282   689 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:40:29.031   282   689 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:40:29.031   282   689 D DrmWidevineDash: Service_Uninitialize: starts!
,08-16 14:40:29.031   282   689 D QSEECOMAPI: : QSEECom_dealloc_memory 
,08-16 14:40:29.041   282   689 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-16 14:40:29.041   282   689 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-16 14:40:29.041   282   689 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-16 14:40:29.081  1014  1557 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.081  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:29.081  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.081  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.091  1014  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.101  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.101  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:40:29.101  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.101  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.101  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:29.101  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.101  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.141  1816  6258 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 14:40:29.141  1911  2112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 14:40:29.151  3757  6236 D UdcContextInitService: registered all accounts: true
,08-16 14:40:29.161  6241  6250 I qtaguid : Untagging socket 30
,08-16 14:40:29.171  6178  6260 W jxcore-log: Initializing JXcore engine
08-16 14:40:29.171  6178  6260 W jxcore-log: JXcore engine is ready
,08-16 14:40:29.181  1911  2130 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-16 14:40:29.231  1897  1897 E audit   : type=1400 msg=audit(1471351229.231:205): avc:  denied  { ioctl } for  pid=6260 comm="Thread-1063" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 14:40:29.231  1897  1897 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:40:29.231  1897  1897 E audit   : type=1300 msg=audit(1471351229.231:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9ea008f8 items=0 ppid=304 ppcomm=main pid=6260 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1063" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 14:40:29.231  1897  1897 E audit   : type=1320 msg=audit(1471351229.231:205): 
,08-16 14:40:29.251  6178  6260 W jxcore-log: Starting JXcore engine
,08-16 14:40:29.311  1014  3215 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:40:29.311  1014  3215 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-16 14:40:29.311  1014  3215 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.311  1014  3215 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.311  1014  3215 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.361  6178  6260 W jxcore-log: Platform android
08-16 14:40:29.361  6178  6260 W jxcore-log: 
,08-16 14:40:29.361  6178  6260 W jxcore-log: Process ARCH arm
08-16 14:40:29.361  6178  6260 W jxcore-log: 
,08-16 14:40:29.371  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 14:40:29.371  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 14:40:29.381  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.381  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.381  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.431  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.431  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.431  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.431  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.461  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.461  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.461  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.461  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.511  1014  3208 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-16 14:40:29.511  1014  3208 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.511  1014  3208 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.511  1014  3208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.521  1911  6280 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 14:40:29.521  1911  6277 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 14:40:29.521  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.521  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:29.521  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.521  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.531  1014  1207 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 14:40:29.531  1014  1207 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 14:40:29.531  1014  1207 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:29.531  1014  1207 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:40:29.531  1014  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.541  1911  2130 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:40:29.541   277  1008 D EnterpriseController: uids 10012
08-16 14:40:29.541   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:40:29.541   277  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 14:40:29.541  1911  2130 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 14:40:29.541  1911  2130 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1911, getuid(): 10012
,08-16 14:40:29.551  1014  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.551  1014  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.551  1014  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.551  1014  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.551  1911  6280 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 14:40:29.551  1911  6277 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 14:40:29.551  1014  1306 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.561  1014  1306 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.561  1014  1306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:40:29.561  1014  1306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.591  1911  2130 I qtaguid : Tagging socket 75 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1911, getuid(): 10012
,08-16 14:40:29.591  1014  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:40:29.591  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:29.601  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:29.601  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:40:29.601  1911  6280 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 14:40:29.601  1911  6277 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-16 14:40:29.601  1911  6277 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-16 14:40:29.601  1911  6277 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 14:40:29.611  6178  6260 I jxcore-log: JXcore Cordova bridge is ready!
08-16 14:40:29.611  6178  6260 I jxcore-log: 
,08-16 14:40:29.611  6178  6260 W jxcore-log: JXcore engine is started
,08-16 14:40:29.621  6178  6233 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 14:40:29.621  6178  6178 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 14:40:29.631  6178  6260 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
08-16 14:40:29.631  6178  6260 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,08-16 14:40:29.641  6178  6178 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,08-16 14:40:29.641  6178  6178 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-16 14:40:29.641  1014  3215 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 14:40:29.641  1014  3215 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-16 14:40:29.641  1014  3215 D InputDispatcher: Focused application set to: xxxx
08-16 14:40:29.651  6178  6178 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 14:40:29.651  1014  3204 I ActivityManager: Killing 5326:com.google.android.talk/u0a104 (adj 15): empty #31
08-16 14:40:29.651  6178  6178 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-16 14:40:29.651  6178  6178 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:40:29.651  6178  6178 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:40:29.651  6178  6178 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:40:29.651  6178  6178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:40:29.651  6178  6178 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fef30ec removed from the list
08-16 14:40:29.651  6178  6178 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:40:29.651  6178  6178 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@364b0ebb removed from the list
08-16 14:40:29.651  6178  6178 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:40:29.651  6178  6178 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-16 14:40:29.661  6178  6178 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 14:40:29.681   258   440 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,08-16 14:40:29.681  1014  1555 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 14:40:29.681   258   442 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,08-16 14:40:29.681  1014  1306 D InputDispatcher: Focus left window: 6178
,08-16 14:40:29.691  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 14:40:29.691  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 14:40:29.691  1014  1207 W ActivityManager: mDVFSHelper.acquire()
,08-16 14:40:29.701  6178  6178 E ViewRootImpl: sendUserActionEvent() mView == null
,08-16 14:40:29.721  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-16 14:40:29.731  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 14:40:29.741  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 14:40:29.751  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 14:40:29.751  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 3
,08-16 14:40:29.761  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-16 14:40:29.761  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-16 14:40:29.771  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-16 14:40:29.781  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 14:40:29.791  1911  6277 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:40:29.801   277  1008 D EnterpriseController: uids 10012
08-16 14:40:29.801   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:40:29.801   277  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-16 14:40:29.801  6285  6285 I dex2oat : ----------------------------------------------------
08-16 14:40:29.801  6285  6285 I dex2oat : <SS>: S T A R T I N G . . .
08-16 14:40:29.801  6285  6285 I dex2oat : <SS>: Zip is absent. Canceled.
08-16 14:40:29.801  6285  6285 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 14:40:29.801  1911  6277 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 14:40:29.801  1911  6277 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1911, getuid(): 10012
,08-16 14:40:29.821  1014  1555 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-16 14:40:29.821  1014  1555 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-16 14:40:29.821  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,08-16 14:40:29.821  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 14:40:29.831  1176  1176 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-16 14:40:29.831  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
08-16 14:40:29.831  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:40:29.831  1176  1176 D PanelView: There is/are notification(s) 
08-16 14:40:29.831  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-16 14:40:29.831  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:40:29.841  1176  1176 D PanelView: There is/are notification(s) 
,08-16 14:40:29.841  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
08-16 14:40:29.841  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-16 14:40:29.841  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 14:40:29.851  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-16 14:40:29.851  6285  6285 I dex2oat : dex2oat took 47.188ms (threads: 4)
08-16 14:40:29.851  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-16 14:40:29.851  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-16 14:40:29.851  1014  1027 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 14:40:29.851  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-16 14:40:29.851  1014  1027 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 14:40:29.851  1014  1027 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 14:40:29.851  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 14:40:29.851  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-16 14:40:29.861   258   258 I SurfaceFlinger: id=15 createSurf (720x1280),1 flag=404, YUIInstallC
08-16 14:40:29.861  6241  6250 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 14:40:29.861  6241  6250 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:40:29.861  6241  6250 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:40:29.861  6241  6250 I Adreno-EGL: Local Branch: 
08-16 14:40:29.861  6241  6250 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:40:29.861  6241  6250 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:40:29.861  6241  6250 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 14:40:29.871  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-16 14:40:29.871  1014  1306 D InputDispatcher: Focus entered window: 3178
,08-16 14:40:29.881  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 14:40:29.881  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 14:40:29.881  3178  3178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 14:40:29.891  3178  3178 V ActivityThread: updateVisibility : ActivityRecord{1fb99591 token=android.os.BinderProxy@2aa6e97c {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-16 14:40:29.911  1176  1176 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-16 14:40:29.911  1014  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 14:40:29.921  1176  1176 D PanelView: There is/are notification(s) 
,08-16 14:40:29.921  1014  6296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 14:40:29.921  6178  6178 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-16 14:40:29.931  1816  1816 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-16 14:40:29.931  3178  3178 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2aa6e97c time:122754
,08-16 14:40:29.931  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19432bda u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:122757
08-16 14:40:29.931  1014  1044 W ActivityManager: mDVFSHelper.release()
,08-16 14:40:29.931  6283  6283 D AndroidRuntime: 
08-16 14:40:29.931  6283  6283 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 14:40:29.941  6283  6283 D AndroidRuntime: CheckJNI is OFF
,08-16 14:40:29.941  6283  6283 D AndroidRuntime: readGMSProperty: start
08-16 14:40:29.941  6283  6283 D AndroidRuntime: readGMSProperty: already setted!!
08-16 14:40:29.941  6283  6283 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 14:40:29.941  6283  6283 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 14:40:29.941  6283  6283 D AndroidRuntime: readGMSProperty: end
08-16 14:40:29.941  6283  6283 D AndroidRuntime: addProductProperty: start
,08-16 14:40:29.951  6241  6250 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 14:40:29.951  6241  6250 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:40:29.951  6241  6250 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:40:29.951  6241  6250 I Adreno-EGL: Local Branch: 
08-16 14:40:29.951  6241  6250 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:40:29.951  6241  6250 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:40:29.951  6241  6250 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 14:40:30.061  6283  6283 E AffinityControl: AffinityControl: registerfunction enter
,08-16 14:40:30.091  6283  6283 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 14:40:30.101  1014  3224 D PackageManager: START PACKAGE DELETE: observer{760064149}
08-16 14:40:30.101  1014  3224 D PackageManager: pkg{<packageName>}
08-16 14:40:30.101  1014  3224 D PackageManager: user{0}
08-16 14:40:30.101  1014  3224 D PackageManager: caller{2000}
08-16 14:40:30.101  1014  3224 D PackageManager: flags{2}
08-16 14:40:30.101  1014  3224 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-16 14:40:30.101  1014  3224 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-16 14:40:30.101  1014  3224 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-16 14:40:30.101  1014  3224 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 14:40:30.101  1014  3224 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-16 14:40:30.101  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-16 14:40:30.101  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-16 14:40:30.101  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 14:40:30.101  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 14:40:30.101  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 14:40:30.101  1014  1054 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-16 14:40:30.101  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-16 14:40:30.101  1014  1039 I ActivityManager: Killing 6178:com.test.thalitest/u0a155 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-16 14:40:30.111  1014  1039 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:40:30.121  6241  6250 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-16 14:40:30.121  6241  6250 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:40:30.121  6241  6250 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:40:30.121  6241  6250 I Adreno-EGL: Local Branch: 
08-16 14:40:30.121  6241  6250 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:40:30.121  6241  6250 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:40:30.121  6241  6250 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 14:40:30.261  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-16 14:40:30.291  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-16 14:40:30.321  5647  5647 I art     : Explicit concurrent mark sweep GC freed 1964(113KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 812us total 39.064ms
,08-16 14:40:30.331  5435  5435 I art     : Explicit concurrent mark sweep GC freed 403(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 1.034ms total 63.015ms
,08-16 14:40:30.351  1816  1816 E SamsungIME: mOCRHelper is null
,08-16 14:40:30.351  1911  2112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 14:40:30.361  5740  5740 I art     : Explicit concurrent mark sweep GC freed 673(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 630us total 64.966ms
,08-16 14:40:30.371  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 14:40:30.401  3757  3757 I art     : Explicit concurrent mark sweep GC freed 20185(1252KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 15MB/20MB, paused 1.351ms total 139.924ms
,08-16 14:40:30.401  3696  3696 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 14:40:30 GMT+02:00 2016
,08-16 14:40:30.411  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:40:30.411  3757  3771 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-16 14:40:30.441  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-16 14:40:30.441  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-16 14:40:30.441  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:40:30.441  1014  3208 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 14:40:30.441  1014  3208 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 14:40:30.441  1439  1439 D RegisteredServicesCache: empty dynamic service
,08-16 14:40:30.441  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 14:40:30.441  1014  3208 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:30.441  1014  3208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:40:30.441  1014  3208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 14:40:30.441  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 14:40:30.451  1014  1122 V NetworkStats: performPollLocked() took 11ms
08-16 14:40:30.451  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:40:30.461  3696  3696 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 14:40:30.461  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 14:40:30.461  1014  1559 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-16 14:40:30.461  1014  1559 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-16 14:40:30.461  1014  1559 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 14:40:30.461  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:30.461  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:30.461  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:30.461  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:40:30.471  6308  6308 E Zygote  : MountEmulatedStorage()
,08-16 14:40:30.471  6308  6308 I libpersona: KNOX_SDCARD checking this for 10094
08-16 14:40:30.471  6308  6308 E Zygote  : v2
08-16 14:40:30.471  6308  6308 I libpersona: KNOX_SDCARD not a persona
,08-16 14:40:30.481  6308  6308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:40:30.481  6308  6308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:40:30.481  1014  1559 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6308 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
08-16 14:40:30.481  6308  6308 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:40:30.491  3696  3696 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-16 14:40:30.501   304   304 I art     : Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.742ms total 21.784ms
,08-16 14:40:30.501  1439  1439 D PersonaManager: isKioskContainerExistOnDevice,
,08-16 14:40:30.501  3696  3696 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 14:40:30.521   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.828ms
08-16 14:40:30.521  6308  6308 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:40:30.521  6308  6308 D ActivityThread: Added TimaKeyStore provider
,08-16 14:40:30.541   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 16.867ms
,08-16 14:40:30.541  3696  3696 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 14:40:30.541  3696  6307 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 14:40:30.561  3696  6307 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-16 14:40:30.561  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:40:30.561  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:40:30.561  3696  6307 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-16 14:40:30.561  3696  6307 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-16 14:40:30.561  5007  5007 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-16 14:40:30.571  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,08-16 14:40:30.581  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-16 14:40:30.581  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-16 14:40:30.581  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:30.581  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:30.581  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:30.581  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:30.581  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 14:40:30.581  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-16 14:40:30.581  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-16 14:40:30.581  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-16 14:40:30.591  6324  6324 E Zygote  : MountEmulatedStorage()
08-16 14:40:30.591  6324  6324 I libpersona: KNOX_SDCARD checking this for 10149
08-16 14:40:30.591  6324  6324 E Zygote  : v2
08-16 14:40:30.591  6324  6324 I libpersona: KNOX_SDCARD not a persona
,08-16 14:40:30.591  6324  6324 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:40:30.601  6324  6324 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 14:40:30.601  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6324 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:40:30.601  6324  6324 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-16 14:40:30.601  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-16 14:40:30.601  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
08-16 14:40:30.601  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 14:40:30.601  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 14:40:30.601  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 14:40:30.601  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-16 14:40:30.601  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-16 14:40:30.601  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 14:40:30.601  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 14:40:30.601  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 14:40:30.601  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 14:40:30.601  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 14:40:30.601  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 14:40:30.611  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 14:40:30.611  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-16 14:40:30.611  1014  2722 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-16 14:40:30.611  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 14:40:30.621  6324  6324 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:40:30.621  6324  6324 D ActivityThread: Added TimaKeyStore provider
,08-16 14:40:30.631  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=129_task.xml
,08-16 14:40:30.631  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-16 14:40:30.681  3696  6307 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-16 14:40:30.691  3696  6307 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-16 14:40:30.691  3696  6307 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
08-16 14:40:30.691  3696  3696 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 14:40:30.701  1014  1054 I art     : Explicit concurrent mark sweep GC freed 57360(4MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 27MB/41MB, paused 2.913ms total 292.895ms
,08-16 14:40:30.701  1014  1336 I art     : WaitForGcToComplete blocked for 235.057ms for cause Explicit
,08-16 14:40:30.711  1014  1054 D PackageManager: delete codoeFile: 
,08-16 14:40:30.731  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-16 14:40:30.731  1014  1054 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-16 14:40:30.731  1014  1054 D PackageManager: result of delete: 1{760064149}
,08-16 14:40:30.731  6283  6283 D AndroidRuntime: Shutting down VM
,08-16 14:40:30.741  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 14:40:30.741  1014  1054 D PackageManager: userId{-1}
08-16 14:40:30.741  1014  1054 D PackageManager: andCode{true}
,08-16 14:40:30.741  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 14:40:30.851  1014  1336 I art     : Explicit concurrent mark sweep GC freed 9851(470KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.682ms total 155.356ms
,08-16 14:40:30.851  1014  1336 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 14:40:30.851  1014  1336 D SecContentProvider2: mCursor = null
,08-16 14:40:30.861  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
08-16 14:40:30.861  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-16 14:40:30.861  1014  1038 W TextServicesManagerService: no available spell checker services found
,08-16 14:40:30.881   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:40:30.881  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:40:30.921  5760  5760 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,08-16 14:40:30.921  1014  1207 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-16 14:40:30.921  1014  1207 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,08-16 14:40:30.921  1014  1207 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:30.921  1014  1207 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:40:30.921  1014  1207 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,08-16 14:40:30.931  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:40:30.931  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:40:30.941  5740  6323 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-16 14:40:30.951  6283  6283 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 14:40:30.951  1014  1559 I TactileAssist: enable value -1
08-16 14:40:30.951  1014  1559 I TactileAssist: internal enable value -1
08-16 14:40:30.951  1014  1559 I TactileAssist: intensity value -1
08-16 14:40:30.951  1014  1559 I TactileAssist: saveAppList value true
08-16 14:40:30.951  6308  6308 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-16 14:40:30.951  6308  6308 D elm:15183: ELMEngine.ELMEngine( context ).,
08-16 14:40:30.961  5760  6340 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,08-16 14:40:30.961  5760  6340 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
08-16 14:40:30.961  1014  1559 I TactileAssist: List of disabled apps :
,08-16 14:40:30.961  6308  6308 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-16 14:40:30.981  1014  3208 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-16 14:40:30.981  1014  3208 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-16 14:40:30.981  1014  3208 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:30.981  1014  3208 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:40:30.981  1014  3208 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 14:40:30.981  6308  6308 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-16 14:40:30.991  6308  6308 D elm:15183: ElmAgentService : onCreate()
,08-16 14:40:30.991  6308  6341 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-16 14:40:30.991  6308  6341 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-16 14:40:30.991  6308  6341 D elm:15183: MDMBridge.getInstance()
08-16 14:40:30.991  6308  6341 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 14:40:30.991  5740  5740 I art     : Explicit concurrent mark sweep GC freed 613(35KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.518ms total 67.435ms
08-16 14:40:30.991  6324  6324 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-16 14:40:30.991  6324  6324 D ThemeInfoUtil: isCurrentFestival = false
,08-16 14:40:30.991  3390  3390 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-16 14:40:30.991  3390  3390 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-16 14:40:30.991  3390  3390 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-16 14:40:30.991  3390  3390 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-16 14:40:30.991  3390  3390 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-16 14:40:30.991  3390  3390 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-16 14:40:30.991  3390  3390 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-16 14:40:30.991  3390  3390 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:40:30.991  3390  3390 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:40:30.991  3390  3390 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:40:30.991  3390  3390 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:40:30.991  3390  3390 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:40:30.991  3390  3390 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:40:30.991  3390  3390 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 14:40:30.991  6308  6341 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 14:40:31.001  6011  6011 D Compatibility: onReceive() it will make start service
,08-16 14:40:31.021  1014  1475 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,08-16 14:40:31.021  1014  1475 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-16 14:40:31.021  1014  1475 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:31.021  1014  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:40:31.021  1014  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-16 14:40:31.021  1014  3204 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,08-16 14:40:31.021  1014  3204 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-16 14:40:31.031  1014  3204 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:31.031  1014  3204 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:40:31.031  1014  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-16 14:40:31.041  1476  1476 D Launcher.Model: reloadBadges entered.
,08-16 14:40:31.041  5779  5779 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-16 14:40:31.041  5907  5915 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-16 14:40:31.041  5907  5915 D BadgeProvider: sendNotify, [notify] : null
08-16 14:40:31.041  5907  5915 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-16 14:40:31.041  5907  5915 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 14:40:31.041  5907  5915 D BadgeProvider: update, [UpdateCount] : 1
08-16 14:40:31.041  6011  6344 D Compatibility: onHandleIntent()
,08-16 14:40:31.041  6011  6344 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-16 14:40:31.041  1911  6239 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:40:31.041  1911  6239 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 14:40:31.041  1911  6239 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1911, getuid(): 10012
08-16 14:40:31.041  5779  5779 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 14:40:31.041  5779  5779 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-16 14:40:31.041  6011  6344 D Compatibility: found: 2
,08-16 14:40:31.041  6011  6344 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-16 14:40:31.041  5779  5779 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
08-16 14:40:31.041  6011  6344 D Compatibility: skipping ResolveInfo{f861a60 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-16 14:40:31.041  6011  6344 D Compatibility: considering ResolveInfo{3e62ab19 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-16 14:40:31.041  6011  6344 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-16 14:40:31.041  6308  6308 D elm:15183: ElmAgentService : onDestroy().
,08-16 14:40:31.041  6011  6344 D Compatibility: enabling receiver ResolveInfo{e7aa7de com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-16 14:40:31.051  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-16 14:40:31.051  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:40:31.051  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:40:31.051  6011  6344 D Compatibility: enabling receiver ResolveInfo{3d134dbf com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-16 14:40:31.061  5075  5075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-16 14:40:31.061  6011  6344 D Compatibility: enabling receiver ResolveInfo{3a27c8c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-16 14:40:31.061  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:40:31.071  6011  6344 D Compatibility: enabling receiver ResolveInfo{2e69dfd5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-16 14:40:31.081  5859  5859 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-16 14:40:31.081  1014  1557 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-16 14:40:31.081  5859  5859 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
08-16 14:40:31.081  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-16 14:40:31.081  5859  5859 I TapandpayWidget:Utils: Clear T&P info.
,08-16 14:40:31.081  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 14:40:31.081  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:40:31.081  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 14:40:31.081  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:40:31.081  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:40:31.081  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:40:31.081  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-16 14:40:31.081  5859  5859 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-16 14:40:31.081  6011  6344 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-16 14:40:31.091  1014  3204 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-16 14:40:31.091  1014  3204 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-16 14:40:31.091  1014  3204 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:40:31.091  1014  3204 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:40:31.091  1014  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-16 14:40:31.091  5435  6347 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-16 14:40:31.101  5075  6346 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,08-16 14:40:31.101  5075  6346 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:40:31.101  5075  6346 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:40:31.101  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:40:31.101  5075  6346 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:40:31.101  5075  6346 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:40:31.101  5075  6346 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 14:40:31.101  5075  6346 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 14:40:31.101  5075  6346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:40:31.111  5075  6346 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
08-16 14:40:31.111  5075  6346 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:40:31.111  5075  6346 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:40:31.111  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:40:31.121  1014  3215 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
08-16 14:40:31.121  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:40:31.121  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-16 14:40:31.121  1014  3215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:31.121  1014  3215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:31.121  1014  3215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:31.121  1014  3215 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:40:31.121  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:40:31.121  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:40:31.121  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-16 14:40:31.131  5515  5515 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-16 14:40:31.131  1014  1208 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-16 14:40:31.131  1014  1208 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-16 14:40:31.131  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:40:31.131  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-16 14:40:31.131  1014  3215 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6348 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
08-16 14:40:31.131  6348  6348 E Zygote  : MountEmulatedStorage()
08-16 14:40:31.131  6348  6348 E Zygote  : v2
08-16 14:40:31.141  6348  6348 I libpersona: KNOX_SDCARD checking this for 10160
08-16 14:40:31.141  6348  6348 I libpersona: KNOX_SDCARD not a persona
,08-16 14:40:31.141  6348  6348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:40:31.141  6348  6348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:40:31.141  6348  6348 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 14:40:31.151  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:40:31.151  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-16 14:40:31.151  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-16 14:40:31.161  5435  6347 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 14:40:31.161  5435  6347 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
