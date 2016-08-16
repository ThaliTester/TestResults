#### Test 813219427e676a1_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main,
08-16 19:31:38.490   335   335 I ServiceManager: Waiting for service AtCmdFwd...
08-16 19:31:38.760  6900  6900 D AndroidRuntime: 
08-16 19:31:38.760  6900  6900 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 19:31:38.760  6900  6900 D AndroidRuntime: CheckJNI is OFF
08-16 19:31:38.760  6900  6900 D AndroidRuntime: readGMSProperty: start
08-16 19:31:38.760  6900  6900 D AndroidRuntime: readGMSProperty: already setted!!
08-16 19:31:38.760  6900  6900 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 19:31:38.760  6900  6900 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 19:31:38.760  6900  6900 D AndroidRuntime: readGMSProperty: end
08-16 19:31:38.760  6900  6900 D AndroidRuntime: addProductProperty: start
08-16 19:31:38.780  5644  5644 D FactoryTest: Not factory mode
08-16 19:31:38.780  5644  5644 D FactoryTest: Not factory mode. isFactoryMode() returend false
08-16 19:31:38.780  5644  5644 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-16 19:31:38.780  5644  5644 D MTPRx   : still no open session command from host, so toast
--------- beginning of system
08-16 19:31:38.790  5644  5644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-16 19:31:38.790  5644  5644 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114984
08-16 19:31:38.790  5644  5644 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
08-16 19:31:38.800  1017  1533 E PersonaManagerService: inState():  stateMachine is null !!
08-16 19:31:38.800  1017  1533 I PersonaManagerService: PersonaId don't exist
08-16 19:31:38.800  1017  1533 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 19:31:38.800  1017  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-16 19:31:38.800  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:38.800  1017  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:38.800  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
08-16 19:31:38.810  1017  1533 W ActivityManager: mDVFSHelper.acquire()
08-16 19:31:38.810   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-16 19:31:38.820   258   258 I SurfaceFlinger: id=12 createSurf (16x16),-1 flag=20004, EimLayer(An
08-16 19:31:38.820  1017  1533 D FocusedStackFrame: Set to : 0
08-16 19:31:38.840  1017  1533 D PersonaManager: isKioskContainerExistOnDevice
08-16 19:31:38.870  1017  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-16 19:31:38.870  1017  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-16 19:31:38.870  1017  1533 D InputDispatcher: Focused application set to: xxxx
08-16 19:31:38.870  1017  1533 D InputDispatcher: Focus left window: 1499
08-16 19:31:38.870  5644  5644 E MTPRx   : started activity for popup
08-16 19:31:38.870  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 19:31:38.870  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 19:31:38.880  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-16 19:31:38.900  6900  6900 E AffinityControl: AffinityControl: registerfunction enter
08-16 19:31:38.920  5644  5644 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-16 19:31:38.920  5644  5644 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-16 19:31:38.920  5644  5644 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 19:31:38.920  5644  5644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 19:31:38.920  5644  5644 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 19:31:38.920  5644  5644 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 19:31:38.930  6900  6900 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 19:31:38.940  1017  1533 E PersonaManagerService: inState():  stateMachine is null !!
08-16 19:31:38.940  1017  1533 I PersonaManagerService: PersonaId don't exist
08-16 19:31:38.940  1017  1533 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 19:31:38.940  1017  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 19:31:38.960  5644  5644 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
08-16 19:31:38.960  1017  1533 W ActivityManager: mDVFSHelper.acquire()
08-16 19:31:38.960  1017  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-16 19:31:38.960  1017  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 19:31:38.960  1017  1533 D InputDispatcher: Focused application set to: xxxx
08-16 19:31:38.960  6900  6900 D AndroidRuntime: Shutting down VM
08-16 19:31:38.970  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 19:31:38.970  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 19:31:38.990  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 19:31:38.990  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 19:31:38.990   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-16 19:31:39.020  5644  5644 D SettingsReceiverActivity: dev.kiessupport is : TRUE
08-16 19:31:39.030  5644  5644 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-16 19:31:39.030  5644  5644 D PhoneWindow: *FMB* installDecor flags : 8388610
08-16 19:31:39.040  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:39.040  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:39.040  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:39.040  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:39.060  6912  6912 E Zygote  : MountEmulatedStorage()
08-16 19:31:39.060  6912  6912 E Zygote  : v2
08-16 19:31:39.060  6912  6912 I libpersona: KNOX_SDCARD checking this for 10171
08-16 19:31:39.060  6912  6912 I libpersona: KNOX_SDCARD not a persona
08-16 19:31:39.060  6912  6912 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 19:31:39.060  6912  6912 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:39.060  1017  6702 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6912 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 19:31:39.060  6912  6912 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 19:31:39.090  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{17c4c173 token=android.os.BinderProxy@18b793e0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-16 19:31:39.090   258   438 I SurfaceFlinger: id=6 Removed Mauncher (6/9)
08-16 19:31:39.090   258  5983 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-16 19:31:39.090  6912  6912 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 19:31:39.100  6912  6912 D ActivityThread: Added TimaKeyStore provider
08-16 19:31:39.100  1017  1497 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-16 19:31:39.110  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 19:31:39.110  1017  1497 D PersonaManager: isKioskContainerExistOnDevice
08-16 19:31:39.130  1499  1499 D Launcher: onTrimMemory. Level: 20
08-16 19:31:39.170  6900  6900 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 19:31:39.230  6912  6912 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-16 19:31:39.250  6912  6912 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 5443-5445)
08-16 19:31:39.250  6912  6912 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-16 19:31:39.290  6912  6912 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {40ddd2b}
08-16 19:31:39.290  6912  6912 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-16 19:31:39.300  6912  6912 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 19:31:39.340  6912  6912 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-16 19:31:39.350  6912  6912 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 19:31:39.350  6912  6912 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 19:31:39.380  6912  6912 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 19:31:39.380  6912  6912 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 19:31:39.380  6912  6912 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 19:31:39.380  6912  6912 I Adreno-EGL: Local Branch: 
08-16 19:31:39.380  6912  6912 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 19:31:39.380  6912  6912 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 19:31:39.380  6912  6912 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-16 19:31:39.390  1017  1095 V AlarmManager: waitForAlarm result :4
08-16 19:31:39.410  1017  1017 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-16 19:31:39.410  1017  1017 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-16 19:31:39.410  1017  1017 I BackgroundCompactionService: onStart. jobID=801
08-16 19:31:39.410  1987  1987 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
08-16 19:31:39.410  1017  1017 I BackgroundCompactionService: onStart done. jobID=801
08-16 19:31:39.420  1017  6934 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-16 19:31:39.420  1017  6934 I BackgroundCompactionService: compact_memory command done
08-16 19:31:39.490   335   335 I ServiceManager: Waiting for service AtCmdFwd...
08-16 19:31:39.500  6912  6912 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 19:31:39.510  1987  1987 I art     : Explicit concurrent mark sweep GC freed 58215(3MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 10MB/17MB, paused 1.395ms total 76.732ms
08-16 19:31:39.520  6912  6912 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-16 19:31:39.520  6912  6912 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-16 19:31:39.540  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 19:31:39.540  6912  6912 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-16 19:31:39.540  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
08-16 19:31:39.540  6912  6912 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-16 19:31:39.540  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:39.540  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:39.540  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 19:31:39.620  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{2f69902c u0 com.test.thalitest/.MainActivity t3}
08-16 19:31:39.710  6912  6912 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 19:31:39.720  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 19:31:39.720  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.HeartbeatAlarm$ConnectionInfoPersistService; callingUser = 0; userId(target) = 0
08-16 19:31:39.720  6912  6912 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 19:31:39.720  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:39.720  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:39.720  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 19:31:39.730  6912  6912 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 19:31:39.730  6912  6912 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-16 19:31:39.740  6912  6912 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-16 19:31:39.750  6912  6912 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 19:31:39.750  6912  6912 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 19:31:39.760  1017  1497 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 19:31:39.760  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.net.NetworkReportService; callingUser = 0; userId(target) = 0
08-16 19:31:39.760  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:39.760  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:39.760  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 19:31:39.810  4814  5124 D NetworkUsageDbReporter: Started reporting usage
08-16 19:31:39.810  1017  1498 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 19:31:39.810  1017  1498 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
08-16 19:31:39.810  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:39.810  1017  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:39.810  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 19:31:39.830  6912  6958 D OpenGLRenderer: Render dirty regions requested: true
08-16 19:31:39.830  1017  1498 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 19:31:39.830  1017  1498 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 19:31:39.830  1017  1498 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 19:31:39.830  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 19:31:39.830  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-16 19:31:39.840  6912  6940 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-16 19:31:39.840  6912  6912 V ActivityThread: updateVisibility : ActivityRecord{1b294d0b token=android.os.BinderProxy@22d2b7fc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 19:31:39.850  6912  6912 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 19:31:39.850  6912  6912 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 19:31:39.860   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
08-16 19:31:39.880   288   288 E SMD     : DCD OFF
08-16 19:31:39.890  1017  1135 D InputDispatcher: Focus entered window: 6912
08-16 19:31:39.890  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 19:31:39.890  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 19:31:39.890  6912  6912 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-16 19:31:39.890  6912  6958 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 19:31:39.900  6912  6958 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-16 19:31:39.900  6912  6958 D OpenGLRenderer: Enabling debug mode 0
08-16 19:31:39.900  4814  5124 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1245
08-16 19:31:39.900  4814  5124 D NetworkUsageDbReporter: keeping row: 961
08-16 19:31:39.900  4814  5124 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 334118
08-16 19:31:39.900  4814  5124 D NetworkUsageDbReporter: keeping row: 960
08-16 19:31:39.910  4814  5124 D NetworkUsageDbReporter: Finished reporting usage.
08-16 19:31:39.930  1017  1029 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-16 19:31:39.930  1175  1175 I StatusBar: Icon Only
08-16 19:31:39.930  1175  1175 D PanelView: There is/are notification(s) 
08-16 19:31:39.940  1017  6962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-16 19:31:39.950  1017  1047 I ActivityManager: Displayed Component not be shown by security: +833ms (total +1s124ms)
08-16 19:31:39.950  1017  1047 W ActivityManager: mDVFSHelper.release()
08-16 19:31:39.950  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f69902c u0 com.test.thalitest/.MainActivity t3} time:116144
08-16 19:31:39.960   258   444 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
08-16 19:31:39.960   258   438 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
08-16 19:31:39.970  1872  1872 I SamsungIME: getCurrentCandidateView
08-16 19:31:39.970  6912  6912 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-16 19:31:39.970  6912  6912 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@22d2b7fc time:116165
,08-16 19:31:40.010  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-16 19:31:40.010  1017  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-16 19:31:40.010  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-16 19:31:40.010  1017  1135 D BatteryService: stay LED for fully charged
08-16 19:31:40.010  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 19:31:40.020  1017  1017 I MotionRecognitionService: Plugged
08-16 19:31:40.020  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 19:31:40.020  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 19:31:40.020  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 19:31:40.020  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 19:31:40.020  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 19:31:40.030  3163  3163 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 19:31:40.030  3163  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-16 19:31:40.040  1017  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 19:31:40.040  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-16 19:31:40.040  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:40.040  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:40.040  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:40.040  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-16 19:31:40.040  1175  1175 D SViewCoverView: level :100 plugged : 2
,08-16 19:31:40.050  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-16 19:31:40.050  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 19:31:40.050  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-16 19:31:40.050  1017  1533 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-16 19:31:40.050  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-16 19:31:40.080  1017  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 19:31:40.080  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-16 19:31:40.090  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:40.090  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:40.090  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:40.100  1872  1872 D SamsungIME: Dismiss ExpandCandiate
,08-16 19:31:40.120  6912  6912 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6912
,08-16 19:31:40.140  1987  1987 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 19:31:40.160  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:40.160  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:40.160  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:40.260  1017  1439 I art     : Explicit concurrent mark sweep GC freed 55520(3MB) AllocSpace objects, 14(492KB) LOS objects, 33% free, 24MB/36MB, paused 2.607ms total 160.781ms
,08-16 19:31:40.260  1017  1516 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 19:31:40.260  1017  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-16 19:31:40.270  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:40.270  1017  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:40.270  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:40.270  4814  6969 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-16 19:31:40.270  4814  6969 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-16 19:31:40.280  1017  3340 D SSRM:n  : SIOP:: AP = 310
,08-16 19:31:40.320  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c,
,08-16 19:31:40.330  1017  1516 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 19:31:40.340  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:40.340  1017  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:40.340  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:40.390  1872  1872 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 19:31:40.410  1872  1872 I SamsungIME: KeybaordView init() : load resources
,08-16 19:31:40.410  1017  1330 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 19:31:40.410  1017  1330 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:40.410  1017  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:40.410  1017  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:40.410  1017  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:40.410  1017  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:40.410  1017  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:40.410  1017  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:40.430  6980  6980 E Zygote  : MountEmulatedStorage()
08-16 19:31:40.430  6980  6980 E Zygote  : v2
08-16 19:31:40.430  6980  6980 I libpersona: KNOX_SDCARD checking this for 10011
08-16 19:31:40.430  6980  6980 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:40.430  6980  6980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:40.430  6980  6980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 19:31:40.440  1017  1330 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6980 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
08-16 19:31:40.440  6980  6980 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 19:31:40.440  1872  1872 I SamsungIME: getCurrentKeyboard
08-16 19:31:40.440  1872  1872 I SamsungIME: getTextKeyboard
,08-16 19:31:40.460   308   308 I art     : Explicit concurrent mark sweep GC freed 8673(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 23.657ms
,08-16 19:31:40.460  6980  6980 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:40.460  6980  6980 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:40.470  1872  1872 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 19:31:40.480   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 18.086ms
,08-16 19:31:40.480  6980  6980 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 19:31:40.480  6980  6980 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 19:31:40.490   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 19:31:40.490   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 17.585ms
,08-16 19:31:40.520  6912  6912 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 19:31:40.520  6980  6980 I MultiDex: VM with version 2.1.0 has multidex support
08-16 19:31:40.520  6980  6980 I MultiDex: install
08-16 19:31:40.520  6980  6980 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 19:31:40.560  6980  6980 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 19:31:40.610  6912  6965 D jxcore_app_log: JniHelper::setJavaVM(0xb73d22b0), pthread_self() = -1214893480
,08-16 19:31:40.620  6912  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 19:31:40.620  6912  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 19:31:40.620  6912  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 19:31:40.620  6912  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 19:31:40.620  6912  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 19:31:40.620  6980  6980 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 19:31:40.620  6912  6965 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@672bc39 added. We now have 1 listener(s)
08-16 19:31:40.620  6980  6980 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29a1fd7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-16 19:31:40.620  6980  6980 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 19:31:40.630  6912  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-16 19:31:40.630  6912  6965 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-16 19:31:40.630  6912  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 19:31:40.630  6912  6965 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 19:31:40.630  6912  6965 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2032182c added. We now have 1 listener(s)
,08-16 19:31:40.630  6912  6965 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 19:31:40.640  6980  6980 D ChimeraCfgMgr: Reading stored module config
,08-16 19:31:40.640  6912  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 19:31:40.640  6912  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 19:31:40.640  6912  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 19:31:40.640  6912  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 19:31:40.640  6912  6965 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 19:31:40.640  6912  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 19:31:40.650  6912  6965 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-16 19:31:40.660  6912  6965 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 19:31:40.660  6912  6965 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 19:31:40.660  6912  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 19:31:40.660  6912  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 19:31:40.660  6912  6965 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 19:31:40.660  6912  6965 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 19:31:40.660  6912  6965 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 19:31:40.660  6912  6965 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 19:31:40.660  6912  6965 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 19:31:40.660  6912  6965 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 19:31:40.660  6912  6965 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 19:31:40.660  6912  6965 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 19:31:40.660  6912  6912 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:40.660  6912  6912 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 19:31:40.690  6912  6912 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 19:31:40.740  6980  6997 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-16 19:31:40.760  6980  6994 I art     : Background partial concurrent mark sweep GC freed 905(189KB) AllocSpace objects, 1(101KB) LOS objects, 39% free, 7MB/12MB, paused 8.122ms total 35.948ms
,08-16 19:31:40.770  6980  6980 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 19:31:40.770  6980  6980 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 19:31:40.870   283   681 D WVCdm   : Instantiating CDM.
,08-16 19:31:40.870   283   702 I WVCdm   : CdmEngine::OpenSession
,08-16 19:31:40.870   283   702 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-16 19:31:40.900   283   702 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-16 19:31:40.920   283   702 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-16 19:31:40.960  6980  6988 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-16 19:31:40.960  6980  6988 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 19:31:40.970  6980  6988 I System.out: (HTTPLog)-Static: isShipBuild true
08-16 19:31:40.970  6980  6988 I System.out: (HTTPLog)-Thread-1265-318171720: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-16 19:31:40.970  6980  6988 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 19:31:40.980   278   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 19:31:40.980   278   963 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-16 19:31:40.980   283   702 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-16 19:31:40.980   283   804 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-16 19:31:40.980   283   804 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-16 19:31:40.980   283   804 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-16 19:31:40.990   283   804 D WVCdm   : PrepareKeyRequest: nonce=624824663
,08-16 19:31:41.020  6980  6988 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 19:31:41.030  6980  6988 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6980, getuid(): 10011
,08-16 19:31:41.260  6980  6988 I qtaguid : Untagging socket 30
,08-16 19:31:41.400  6912  6999 W jxcore-log: Initializing JXcore engine
08-16 19:31:41.400  6912  6999 W jxcore-log: JXcore engine is ready
,08-16 19:31:41.460  1981  1981 E audit   : type=1400 msg=audit(1471368701.460:205): avc:  denied  { ioctl } for  pid=6999 comm="Thread-1290" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2066 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-16 19:31:41.460  1981  1981 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:41.460  1981  1981 E audit   : type=1300 msg=audit(1471368701.460:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9df838f8 items=0 ppid=308 ppcomm=main pid=6999 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1290" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 19:31:41.460  1981  1981 E audit   : type=1320 msg=audit(1471368701.460:205): 
,08-16 19:31:41.470  6912  6999 W jxcore-log: Starting JXcore engine
,08-16 19:31:41.490   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 19:31:41.580  6912  6999 W jxcore-log: Platform android
08-16 19:31:41.580  6912  6999 W jxcore-log: 
08-16 19:31:41.580  6912  6999 W jxcore-log: Process ARCH arm
08-16 19:31:41.580  6912  6999 W jxcore-log: 
,08-16 19:31:41.740  7006  7006 I dex2oat : ----------------------------------------------------
08-16 19:31:41.740  7006  7006 I dex2oat : <SS>: S T A R T I N G . . .
08-16 19:31:41.740  7006  7006 I dex2oat : <SS>: Zip is absent. Canceled.
08-16 19:31:41.740  7006  7006 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 19:31:41.790  7006  7006 I dex2oat : dex2oat took 45.549ms (threads: 4)
,08-16 19:31:41.800  6980  6988 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 19:31:41.800  6980  6988 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 19:31:41.800  6980  6988 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 19:31:41.800  6980  6988 I Adreno-EGL: Local Branch: 
08-16 19:31:41.800  6980  6988 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 19:31:41.800  6980  6988 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 19:31:41.800  6980  6988 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 19:31:41.830  6912  6999 I jxcore-log: JXcore Cordova bridge is ready!
08-16 19:31:41.830  6912  6999 I jxcore-log: 
,08-16 19:31:41.830  6912  6999 W jxcore-log: JXcore engine is started
,08-16 19:31:41.830  6912  6965 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 19:31:41.830  6912  6912 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 19:31:41.840  6912  6999 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
08-16 19:31:41.840  6912  6999 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,08-16 19:31:41.860  6912  6912 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,08-16 19:31:41.860  6912  6912 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
08-16 19:31:41.860  1017  1516 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 19:31:41.860  1017  1516 D FocusedStackFrame: Set to : 0
,08-16 19:31:41.860  1017  1516 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-16 19:31:41.860  1017  1516 D InputDispatcher: Focused application set to: xxxx
08-16 19:31:41.860  1017  1516 D InputDispatcher: Focus left window: 6912
08-16 19:31:41.860  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 19:31:41.860  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 19:31:41.870  1017  1516 I ActivityManager: Killing 6612:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-16 19:31:41.870  6912  6912 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 19:31:41.870  6912  6912 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-16 19:31:41.870  6912  6912 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 19:31:41.870  6912  6912 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 19:31:41.870  6912  6912 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 19:31:41.870  6912  6912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 19:31:41.870  6912  6912 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@672bc39 removed from the list
08-16 19:31:41.870  6912  6912 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 19:31:41.870  6912  6912 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2032182c removed from the list
08-16 19:31:41.870  6912  6912 D io.jxcore.node.ConnectivityMonitor: stop
08-16 19:31:41.870  6912  6912 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-16 19:31:41.870  6912  6912 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 19:31:41.890   258  1101 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,08-16 19:31:41.890   258  5983 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,08-16 19:31:41.890  1017  1029 W ActivityManager: mDVFSHelper.acquire()
,08-16 19:31:41.900  1017  1029 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-16 19:31:41.920  1499  1499 D Launcher: onRestart, Launcher: 826022726
,08-16 19:31:41.920  1499  1499 D Launcher: onStart, Launcher: 826022726
,08-16 19:31:41.920  1499  1499 D Launcher.HomeView: onStart
,08-16 19:31:41.920  1499  1499 D Launcher: onResume, Launcher: 826022726
,08-16 19:31:41.920  1017  1439 D SettingsProvider: name = kids_home_mode
,08-16 19:31:41.920  1017  1439 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 19:31:41.920  1017  1439 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 19:31:41.920  1017  1439 D SettingsProvider: selectionArgs: false
08-16 19:31:41.920  1017  1439 D SettingsProvider: selectionArgs: 10006
,08-16 19:31:41.920  1017  1439 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 19:31:41.920  1017  1439 D SettingsProvider: ret = -1
,08-16 19:31:41.920  1499  1499 D Launcher.HomeView: onResume
,08-16 19:31:41.950  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,08-16 19:31:41.960  1499  1499 D MenuAppsGridFragment: onResume,
,08-16 19:31:41.960  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:41.960  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:41.960  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-16 19:31:41.970  1017  1325 D ActivityManager: handle home activity for 0
08-16 19:31:41.970  1017  1325 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-16 19:31:41.970  1017  1325 D KnoxTimeoutHandler: post home show event for user 0
08-16 19:31:41.970  1017  1325 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 19:31:41.970  1017  1325 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 19:31:41.970  1017  1325 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 19:31:41.970  1499  1499 D Launcher.HomeView: onPause
,08-16 19:31:41.970  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,08-16 19:31:41.970  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-16 19:31:41.970  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-16 19:31:41.970  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 19:31:41.970  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 19:31:41.970   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-16 19:31:41.980  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-16 19:31:41.980  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-16 19:31:41.990  1017  1498 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
08-16 19:31:41.990  1017  1498 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-16 19:31:41.990  1017  1497 D InputDispatcher: Focus entered window: 1499
,08-16 19:31:41.990  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:41.990  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 19:31:41.990  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-16 19:31:41.990  1017  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-16 19:31:41.990  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 19:31:41.990  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 19:31:41.990  1499  1499 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 19:31:42.000  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.000  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.000  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.000  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:42.000  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{17c4c173 token=android.os.BinderProxy@18b793e0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-16 19:31:42.010  1499  1499 D Launcher.HomeView: onStop
,08-16 19:31:42.010  1017  1515 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 19:31:42.010  7019  7019 E Zygote  : MountEmulatedStorage(),
08-16 19:31:42.010  1017  1498 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7019 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-16 19:31:42.010  7019  7019 E Zygote  : v2
08-16 19:31:42.010  7019  7019 I libpersona: KNOX_SDCARD checking this for 10039
08-16 19:31:42.010  7019  7019 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:42.020  1017  7018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-16 19:31:42.020  1872  1872 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-16 19:31:42.020  7019  7019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 19:31:42.020  7019  7019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:42.020  1175  1175 I StatusBar: Icon Only
08-16 19:31:42.020  1175  1175 D PanelView: There is/are notification(s) 
08-16 19:31:42.020  7019  7019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 19:31:42.030  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.030  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.030  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-16 19:31:42.030  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.030  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-16 19:31:42.030  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.030  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.030  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
08-16 19:31:42.030  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.030  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.030  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:42.050  7030  7030 E Zygote  : MountEmulatedStorage()
08-16 19:31:42.050  7030  7030 I libpersona: KNOX_SDCARD checking this for 10089
08-16 19:31:42.050  7030  7030 E Zygote  : v2
08-16 19:31:42.050  7030  7030 I libpersona: KNOX_SDCARD not a persona
08-16 19:31:42.050  7030  7030 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:42.050  1499  1499 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@18b793e0 time:118246
08-16 19:31:42.050  7030  7030 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:42.050  7030  7030 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-16 19:31:42.070  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7030 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a,
,08-16 19:31:42.070  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.070  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.070  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-16 19:31:42.070  7019  7019 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 19:31:42.070  7019  7019 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:42.080  7030  7030 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 19:31:42.080  7030  7030 D ActivityThread: Added TimaKeyStore provider
08-16 19:31:42.090  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.090  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.090  1017  1498 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1499, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-16 19:31:42.090  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-16 19:31:42.090  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{149efb98 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:118286
08-16 19:31:42.090  1017  1047 W ActivityManager: mDVFSHelper.release()
,08-16 19:31:42.090  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.090  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.090  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
08-16 19:31:42.100  2555  2555 D Recents_RecreateReceiver: onReceive by home
,08-16 19:31:42.100  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.100  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.100  1017  1498 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-16 19:31:42.100  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-16 19:31:42.100  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:42.100  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.100  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.100  1017  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:42.110  7019  7019 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 19:31:42.110  7019  7019 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 19:31:42.110  7019  7019 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 19:31:42.110  7019  7019 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-16 19:31:42.110  7019  7019 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 19:31:42.110  7019  7019 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 19:31:42.110  7019  7019 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 19:31:42.140  7052  7052 E Zygote  : MountEmulatedStorage()
08-16 19:31:42.140  7052  7052 E Zygote  : v2
08-16 19:31:42.140  7052  7052 I libpersona: KNOX_SDCARD checking this for 10084
08-16 19:31:42.140  7052  7052 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:42.140  7052  7052 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:42.140  7052  7052 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 19:31:42.140  7052  7052 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-16 19:31:42.150  1017  1498 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7052 uid=10084 gids={50084, 9997} abi=armeabi-v7a,
,08-16 19:31:42.150  1017  1515 D PersonaManager: isKioskContainerExistOnDevice
,08-16 19:31:42.170  7015  7015 D AndroidRuntime: 
08-16 19:31:42.170  7015  7015 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 19:31:42.170  7052  7052 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:42.170  7052  7052 D ActivityThread: Added TimaKeyStore provider
08-16 19:31:42.170  7015  7015 D AndroidRuntime: CheckJNI is OFF
,08-16 19:31:42.170  7015  7015 D AndroidRuntime: readGMSProperty: start
08-16 19:31:42.170  7015  7015 D AndroidRuntime: readGMSProperty: already setted!!
08-16 19:31:42.170  7015  7015 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 19:31:42.170  7015  7015 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 19:31:42.170  7015  7015 D AndroidRuntime: readGMSProperty: end
08-16 19:31:42.170  7015  7015 D AndroidRuntime: addProductProperty: start
,08-16 19:31:42.180  6980  6988 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 19:31:42.180  6980  6988 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 19:31:42.180  6980  6988 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 19:31:42.180  6980  6988 I Adreno-EGL: Local Branch: 
08-16 19:31:42.180  6980  6988 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 19:31:42.180  6980  6988 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 19:31:42.180  6980  6988 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 19:31:42.190  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-16 19:31:42.190  6868  6868 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-16 19:31:42.190  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:42.190  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 19:31:42.190  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,08-16 19:31:42.200  6912  6912 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-16 19:31:42.210  7052  7052 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 19:31:42.210  7030  7030 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 19:31:42.220  7030  7030 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-16 19:31:42.220  6980  6988 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 19:31:42.220  6980  6988 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 19:31:42.220  6980  6988 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 19:31:42.220  6980  6988 I Adreno-EGL: Local Branch: 
08-16 19:31:42.220  6980  6988 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 19:31:42.220  6980  6988 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 19:31:42.220  6980  6988 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 19:31:42.260  1017  1516 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:42.260  1017  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.260  1017  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
08-16 19:31:42.260  1017  1516 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-16 19:31:42.260  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:42.260  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.260  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.260  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:42.300  1017  1516 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7074 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
08-16 19:31:42.310  7074  7074 E Zygote  : MountEmulatedStorage()
08-16 19:31:42.300  1017  1516 I ActivityManager: Killing 6660:com.osp.app.signin/u0a36 (adj 15): empty #21
08-16 19:31:42.310  7074  7074 E Zygote  : v2
08-16 19:31:42.310  7074  7074 I libpersona: KNOX_SDCARD checking this for 10135
08-16 19:31:42.310  7074  7074 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:42.310  7074  7074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:42.310  1017  1135 I ActivityManager: Killing 6692:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-16 19:31:42.310  7074  7074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:42.310  7074  7074 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 19:31:42.310  7015  7015 E AffinityControl: AffinityControl: registerfunction enter,
,08-16 19:31:42.350  7074  7074 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 19:31:42.350  7015  7015 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-16 19:31:42.350  7074  7074 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:42.360  1017  1497 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 19:31:42.360  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 19:31:42.360  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.360  1017  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:42.360  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:42.370  1017  1515 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-16 19:31:42.370  1017  1515 D PackageManager: START PACKAGE DELETE: observer{941540636}
08-16 19:31:42.370  1017  1515 D PackageManager: pkg{<packageName>}
08-16 19:31:42.370  1017  1515 D PackageManager: user{0}
08-16 19:31:42.370  1017  1515 D PackageManager: caller{2000}
08-16 19:31:42.370  1017  1515 D PackageManager: flags{2}
08-16 19:31:42.370  1017  1515 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-16 19:31:42.370  1017  1515 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-16 19:31:42.370  1017  1515 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 19:31:42.370  1017  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-16 19:31:42.370  1017  1515 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 19:31:42.370  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-16 19:31:42.370  1017  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 19:31:42.370  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 19:31:42.370  1017  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 19:31:42.380  1017  1056 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-16 19:31:42.380  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-16 19:31:42.380  1017  1042 I ActivityManager: Killing 6912:com.test.thalitest/u0a171 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-16 19:31:42.400  1987  6977 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 19:31:42.400   278   963 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-16 19:31:42.400   278   963 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-16 19:31:42.400  7074  7074 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,08-16 19:31:42.400  7074  7074 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 19:31:42.400  7074  7074 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-16 19:31:42.400  7074  7074 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,08-16 19:31:42.400  7074  7074 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-16 19:31:42.400  1987  6977 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 19:31:42.400  1987  6977 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1987, getuid(): 10011
,08-16 19:31:42.440  1987  6977 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1987, getuid(): 10011
,08-16 19:31:42.480  1017  1056 W PackageSettings: Skipping PackageSetting{2b89a797 com.example.hello/10168} due to missing metadata
,08-16 19:31:42.490   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 19:31:42.530  1017  1056 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-16 19:31:42.550  7019  7019 D NearbySource: Nearby Source Create!
,08-16 19:31:42.550  7019  7019 D NearbyContext: Nearby Context Create!
,08-16 19:31:42.550  1017  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-16 19:31:42.580  1017  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 19:31:42.590  2642  2642 I art     : Explicit concurrent mark sweep GC freed 19465(1111KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 785us total 38.961ms
,08-16 19:31:42.600  1872  1872 E SamsungIME: mOCRHelper is null
,08-16 19:31:42.610  1476  1476 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 19:31:42.610   257   525 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-16 19:31:42.610   257   525 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 19:31:42.620  7019  7019 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-16 19:31:42.620  7019  7019 D SLinkSource: Samsung link source created
08-16 19:31:42.620  1987  2213 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 19:31:42.640  4814  4814 I art     : Explicit concurrent mark sweep GC freed 6067(346KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 12MB/16MB, paused 1.161ms total 103.272ms
,08-16 19:31:42.660  1459  1459 D PersonaManager: isKioskContainerExistOnDevice
,08-16 19:31:42.670  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
,08-16 19:31:42.670  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
08-16 19:31:42.670  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 19:31:42.670  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 19:31:42.670  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 19:31:42.680  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-16 19:31:42.680  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 19:31:42.680  1017  1124 V NetworkStats: performPollLocked() took 14ms
,08-16 19:31:42.680  1459  1459 D RegisteredServicesCache: empty dynamic service
08-16 19:31:42.680  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-16 19:31:42.690  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 19:31:42.690  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-16 19:31:42.690  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-16 19:31:42.710  1459  1459 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 19:31:42.720  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-16 19:31:42.720  1459  1459 D PersonaManager: isKioskContainerExistOnDevice
,08-16 19:31:42.720  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 19:31:42.730  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 19:31:42.730  1017  1030 D SecContentProvider2: mCursor = null
,08-16 19:31:42.760  1017  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 19:31:42.760  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-16 19:31:42.760  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.760  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:42.760  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:42.790  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 19:31:42.790  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 19:31:42.790  1017  1533 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 19:31:42.810  7019  7096 D ContactProvider: getAllContactInfoList Start
,08-16 19:31:42.810   283   283 I WVCdm   : CdmEngine::CloseSession
,08-16 19:31:42.810  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-16 19:31:42.820  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-16 19:31:42.820  1017  1041 W TextServicesManagerService: no available spell checker services found
,08-16 19:31:42.820   283   283 I WVCdm   : L3 Terminate.
,08-16 19:31:42.830  1017  1325 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 19:31:42.840  7019  7019 D GalleryCacheReady: Receive : home resume
,08-16 19:31:42.840  1017  1330 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.840  1017  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.840  1017  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-16 19:31:42.840  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 19:31:42.840  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 19:31:42.850  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 19:31:42.850  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:42.860  6767  6767 D Mms/UIEventReceiver: ui event
,08-16 19:31:42.860  1017  1330 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-16 19:31:42.860  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:42.860  1017  1330 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.860  1017  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.860  1017  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-16 19:31:42.860  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:42.870  6868  6868 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-16 19:31:42.870  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-16 19:31:42.870  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=3_task.xml
08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 19:31:42.870  1017  3340 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-16 19:31:42.870  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 19:31:42.870  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.,
,08-16 19:31:42.880  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:42.880  7019  7096 D ContactProvider: getAllContactInfoList End
,08-16 19:31:42.880   288   288 E SMD     : DCD OFF
,08-16 19:31:42.890  7019  7096 I syncContacts: thread: 1278, sync time = 135
,08-16 19:31:42.890  2910  2910 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 19:31:42 GMT+02:00 2016
,08-16 19:31:42.890  1017  1533 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 19:31:42.890  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 19:31:42.890  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.890  1017  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 19:31:42.890  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 19:31:42.900  2910  2910 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-16 19:31:42.910  1017  1516 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-16 19:31:42.910  1017  1516 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-16 19:31:42.920  6783  6783 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-16 19:31:42.930  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-16 19:31:42.930  2910  2910 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-16 19:31:42.930  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.930  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.930  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.930  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:42.940  7100  7100 E Zygote  : MountEmulatedStorage()
08-16 19:31:42.940  7100  7100 E Zygote  : v2
08-16 19:31:42.940  7100  7100 I libpersona: KNOX_SDCARD checking this for 1000
08-16 19:31:42.940  7100  7100 I libpersona: KNOX_SDCARD not a persona
08-16 19:31:42.940  2910  2910 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
08-16 19:31:42.950  1017  6702 I TactileAssist: enable value -1
08-16 19:31:42.950  1017  6702 I TactileAssist: internal enable value -1
,08-16 19:31:42.950  7100  7100 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 19:31:42.950  1017  6702 I TactileAssist: intensity value -1
08-16 19:31:42.950  1017  6702 I TactileAssist: saveAppList value true
,08-16 19:31:42.950  1017  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7100 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-16 19:31:42.950  1017  1325 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-16 19:31:42.950  1017  1056 I art     : Explicit concurrent mark sweep GC freed 47782(3MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 4.986ms total 309.868ms,
08-16 19:31:42.950  1017  1325 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-16 19:31:42.950  7100  7100 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 19:31:42.950  7100  7100 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 19:31:42.960  1017  6702 I TactileAssist: List of disabled apps :
,08-16 19:31:42.960  1017  1325 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:42.960  1017  1325 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:42.960  1017  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 19:31:42.970  6783  6783 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-16 19:31:42.970  2910  2910 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 19:31:42.970  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 19:31:42.970  2910  7099 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 19:31:42.970  2910  7099 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-16 19:31:42.970  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 19:31:42.970  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 19:31:42.970  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 19:31:42.980  2910  7099 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-16 19:31:42.980  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-16 19:31:42.980  6783  6783 D elm:15121: ElmAgentService : onCreate()
,08-16 19:31:42.980  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.980  7100  7100 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:42.980  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.980  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:42.980  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:42.980  7100  7100 D ActivityThread: Added TimaKeyStore provider
08-16 19:31:42.980  6783  7109 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-16 19:31:42.980  6783  7109 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-16 19:31:42.980  6783  7109 D elm:15121: MDMBridge.getInstance()
,08-16 19:31:42.990  6783  7109 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 19:31:42.990  2910  7099 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-16 19:31:42.990  6783  7109 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 19:31:43.000  7116  7116 E Zygote  : MountEmulatedStorage()
08-16 19:31:43.000  7116  7116 E Zygote  : v2
08-16 19:31:43.000  7116  7116 I libpersona: KNOX_SDCARD checking this for 1000
08-16 19:31:43.000  7116  7116 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:43.000  7116  7116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:43.000  7116  7116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 19:31:43.000  7116  7116 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 19:31:43.010  1017  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-16 19:31:43.020  6783  6783 D elm:15121: ElmAgentService : onDestroy().
,08-16 19:31:43.020  7116  7116 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:43.020  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-16 19:31:43.020  7116  7116 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:43.030  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-16 19:31:43.030  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.030  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.030  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.030  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.050  7131  7131 E Zygote  : MountEmulatedStorage()
,08-16 19:31:43.050  7131  7131 E Zygote  : v2
08-16 19:31:43.050  7131  7131 I libpersona: KNOX_SDCARD checking this for 1000
08-16 19:31:43.050  7131  7131 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:43.050  7131  7131 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:43.050  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-16 19:31:43.050  7131  7131 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-16 19:31:43.050  7131  7131 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 19:31:43.060  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:43.070  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:43.070  2910  7099 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-16 19:31:43.070  1017  1056 D PackageManager: delete codoeFile: 
,08-16 19:31:43.080  1017  1056 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-16 19:31:43.080  1017  1056 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-16 19:31:43.080  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 19:31:43.080  1017  1056 D PackageManager: result of delete: 1{941540636}
,08-16 19:31:43.090  1017  1439 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-16 19:31:43.090  1017  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.090  1017  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.090  1017  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.090  1017  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.100  2910  7099 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-16 19:31:43.100  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
08-16 19:31:43.100  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 19:31:43.100  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 19:31:43.100  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:43.110  7015  7015 D AndroidRuntime: Shutting down VM
08-16 19:31:43.110  7131  7131 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 19:31:43.110  7147  7147 I libpersona: KNOX_SDCARD checking this for 10048
08-16 19:31:43.110  7147  7147 E Zygote  : MountEmulatedStorage()
08-16 19:31:43.110  7147  7147 I libpersona: KNOX_SDCARD not a persona
08-16 19:31:43.110  7147  7147 E Zygote  : v2
08-16 19:31:43.110  7147  7147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 19:31:43.110  7131  7131 D ActivityThread: Added TimaKeyStore provider
08-16 19:31:43.110  2910  7099 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-16 19:31:43.110  7147  7147 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:43.110  7147  7147 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-16 19:31:43.110  1017  1439 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7147 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-16 19:31:43.130  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:43.130  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:43.130  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 19:31:43.140  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 19:31:43.140  2910  2910 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-16 19:31:43.140  7116  7116 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-16 19:31:43.140  1017  1439 D SecContentProvider2: uri = -1 selection = getSealedState
08-16 19:31:43.140  1017  1439 D SecContentProvider2: mCursor = null
,08-16 19:31:43.140  7116  7116 I PopupuiReceiver_KNOX: getSealedState : true
,08-16 19:31:43.140  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:43.140  1017  1029 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-16 19:31:43.150  1017  1029 D SecContentProvider2: mCursor = null
,08-16 19:31:43.150  7116  7116 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-16 19:31:43.150  1017  1498 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-16 19:31:43.150  1017  1498 D SecContentProvider2: mCursor = null
,08-16 19:31:43.150  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 19:31:43.150  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 19:31:43.150  7100  7100 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-16 19:31:43.150  1017  1497 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-16 19:31:43.150  1017  1497 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-16 19:31:43.150  7116  7116 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-16 19:31:43.150  7116  7116 D PopupuiReceiver: Action package removed
,08-16 19:31:43.150  1017  1497 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:43.150  1017  1497 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:43.150  1017  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-16 19:31:43.160  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 19:31:43.160  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 19:31:43.160  7147  7147 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:43.160  7147  7147 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:43.160  1017  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 19:31:43.160  1017  1056 D PackageManager: userId{-1}
08-16 19:31:43.160  1017  1056 D PackageManager: andCode{true}
,08-16 19:31:43.170  1017  1439 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-16 19:31:43.170  1017  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.170  1017  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.170  1017  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.170  1017  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.170  7131  7131 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-16 19:31:43.170  7131  7131 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-16 19:31:43.170  7131  7131 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 19:31:43.180  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 19:31:43.180  7163  7163 E Zygote  : MountEmulatedStorage()
08-16 19:31:43.180  7163  7163 E Zygote  : v2
08-16 19:31:43.180  7163  7163 I libpersona: KNOX_SDCARD checking this for 10145
08-16 19:31:43.180  7163  7163 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:43.190  7163  7163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:43.190  7163  7163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:43.190  1017  1439 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7163 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 19:31:43.190  1017  1439 I ActivityManager: Killing 6708:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-16 19:31:43.190  7163  7163 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 19:31:43.190  1017  6702 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-16 19:31:43.190  7147  7147 D Compatibility: onReceive() it will make start service
08-16 19:31:43.190  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.190  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.190  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.190  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.210  7173  7173 E Zygote  : MountEmulatedStorage()
08-16 19:31:43.210  7173  7173 E Zygote  : v2
08-16 19:31:43.210  7173  7173 I libpersona: KNOX_SDCARD checking this for 1000
08-16 19:31:43.210  7173  7173 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:43.210  7173  7173 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-16 19:31:43.210  1017  6702 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7173 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-16 19:31:43.210  7173  7173 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 19:31:43.220  1017  1498 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-16 19:31:43.220  1017  1498 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-16 19:31:43.220  1017  1498 W ActivityManager: userId = 0, bbcId = -10000
,08-16 19:31:43.220  7173  7173 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 19:31:43.220  1017  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 19:31:43.220  1017  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-16 19:31:43.220  7163  7163 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:43.220  7163  7163 D ActivityThread: Added TimaKeyStore provider
08-16 19:31:43.220  1017  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 19:31:43.230  7147  7185 D Compatibility: onHandleIntent()
08-16 19:31:43.230  7147  7185 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-16 19:31:43.230  7131  7131 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-16 19:31:43.230  7131  7131 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 19:31:43.230  7131  7131 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 19:31:43.230  7131  7131 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
08-16 19:31:43.230  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-16 19:31:43.230  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-16 19:31:43.230  7147  7185 D Compatibility: found: 2
,08-16 19:31:43.230  1017  1516 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-16 19:31:43.240  7147  7185 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-16 19:31:43.240  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.240  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.240  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.240  1017  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.240  7147  7185 D Compatibility: skipping ResolveInfo{2d49e7e9 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,08-16 19:31:43.240  7147  7185 D Compatibility: considering ResolveInfo{1456ec6e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,08-16 19:31:43.240  7147  7185 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-16 19:31:43.250  7147  7185 D Compatibility: enabling receiver ResolveInfo{30205f0f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-16 19:31:43.250  7196  7196 E Zygote  : MountEmulatedStorage()
08-16 19:31:43.250  7196  7196 I libpersona: KNOX_SDCARD checking this for 10052
08-16 19:31:43.250  7196  7196 E Zygote  : v2
08-16 19:31:43.250  7196  7196 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:43.250  7196  7196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:43.250  7173  7173 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 19:31:43.250  7173  7173 D ActivityThread: Added TimaKeyStore provider
08-16 19:31:43.250  7147  7185 D Compatibility: enabling receiver ResolveInfo{2f593b9c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-16 19:31:43.250  1017  1516 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7196 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-16 19:31:43.250  7196  7196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 19:31:43.250  7196  7196 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 19:31:43.260  7147  7185 D Compatibility: enabling receiver ResolveInfo{fd019a5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-16 19:31:43.260  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-16 19:31:43.270  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.270  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.270  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.270  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.270  7147  7185 D Compatibility: enabling receiver ResolveInfo{1e09617a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-16 19:31:43.280   308   308 I art     : Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 29.949ms
08-16 19:31:43.280  7173  7173 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 19:31:43.280  7147  7185 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-16 19:31:43.290  7196  7196 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:43.290  7196  7196 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:43.300   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.766ms
08-16 19:31:43.300  7173  7173 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-16 19:31:43.310  7015  7015 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,08-16 19:31:43.320   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 17.449ms,
08-16 19:31:43.320  1017  1330 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-16 19:31:43.320  1017  1330 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-16 19:31:43.330  7211  7211 E Zygote  : MountEmulatedStorage(),
08-16 19:31:43.330  7211  7211 E Zygote  : v2
08-16 19:31:43.330  7211  7211 I libpersona: KNOX_SDCARD checking this for 10029
08-16 19:31:43.330  7211  7211 I libpersona: KNOX_SDCARD not a persona
,08-16 19:31:43.330  1017  1030 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7211 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-16 19:31:43.330  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-16 19:31:43.330  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 19:31:43.340  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 19:31:43.340  1017  1030 I ActivityManager: Killing 6728:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-16 19:31:43.350  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-16 19:31:43.350  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.350  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.350  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.350  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.350  7163  7163 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-16 19:31:43.350  7163  7163 D ThemeInfoUtil: isCurrentFestival = false
,08-16 19:31:43.370  7226  7226 E Zygote  : MountEmulatedStorage(),
08-16 19:31:43.370  7226  7226 I libpersona: KNOX_SDCARD checking this for 10087
08-16 19:31:43.370  7226  7226 E Zygote  : v2
08-16 19:31:43.370  7226  7226 I libpersona: KNOX_SDCARD not a persona
08-16 19:31:43.370  7226  7226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 19:31:43.370  1017  1030 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7226 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,08-16 19:31:43.370  1017  1030 I ActivityManager: Killing 6745:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-16 19:31:43.380  1017  1030 I ActivityManager: Killing 6672:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-16 19:31:43.380  7226  7226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-16 19:31:43.380  7226  7226 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 19:31:43.380  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast,
,08-16 19:31:43.390  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.390  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.390  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.390  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 19:31:43.390  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 19:31:43.390  7211  7211 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:43.400  7238  7238 E Zygote  : MountEmulatedStorage(),
08-16 19:31:43.400  7238  7238 E Zygote  : v2
08-16 19:31:43.400  7238  7238 I libpersona: KNOX_SDCARD checking this for 10148
08-16 19:31:43.400  7238  7238 I libpersona: KNOX_SDCARD not a persona
08-16 19:31:43.400  7238  7238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-16 19:31:43.410  1017  1030 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7238 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-16 19:31:43.410  7238  7238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:43.410  1017  1030 I ActivityManager: Killing 6826:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-16 19:31:43.410  7238  7238 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 19:31:43.420  1987  1996 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 19:31:43.420  1987  1996 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: Getting service failed
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at android.database.sqlite.SQLiteSession.throwIfNoTransaction(SQLiteSession.java:926)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:398)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at ivh.c(:com.google.android.gms:73)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at bzx.b(:com.google.android.gms:415)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at bzx.a(:com.google.android.gms:360)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at bzx.a(:com.google.android.gms:142)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at bre.M(:com.google.android.gms:10077)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at bre.a(:com.google.android.gms:1318)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at bre.l(:com.google.android.gms:160)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at bxr.<init>(:com.google.android.gms:44)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at bxp.a(:com.google.android.gms:154)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at ilk.a(:com.google.android.gms:592)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at ioe.onTransact(:com.google.android.gms:824)
08-16 19:31:43.420  1987  1996 E AbstractServiceBroker: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 19:31:43.420  4814  4814 D AndroidRuntime: Shutting down VM
,08-16 19:31:43.430  7226  7226 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:43.430  7226  7226 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:43.440  7238  7238 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 19:31:43.440  7238  7238 D ActivityThread: Added TimaKeyStore provider
,08-16 19:31:43.450  4814  4814 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQstg5Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
08-16 19:31:43.450  4814  4814 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjQgKDMwNTE3NzQtMDM0KRji-eAR
08-16 19:31:43.450  4814  4814 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQwPngEQ
08-16 19:31:43.450  4814  4814 I GCore-Chimera-Crash: ==
08-16 19:31:43.450  4814  4814 I GCore-Chimera-Crash: GCore-Chimera-Crash
,08-16 19:31:43.450  4814  4814 I DeviceDoctorDatabaseHelper: Cleaning stale data from database!
,08-16 19:31:43.450  4814  4814 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131138) and mode_t (0) due to error (30)
08-16 19:31:43.450  4814  4814 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131072) and mode_t (0) due to error (2)
08-16 19:31:43.450  4814  4814 E SQLiteLog: (14) cannot open file at line 32510 of [b3bb660af9]
08-16 19:31:43.450  4814  4814 E SQLiteLog: (14) os_unix.c:32510: (2) open(/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db) - 
,08-16 19:31:43.460  4814  4814 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db'.
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at iiq.c(:com.google.android.gms:207)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at ifm.uncaughtException(:com.google.android.gms:2111)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at ifs.uncaughtException(:com.google.android.gms:54)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at ifl.uncaughtException(:com.google.android.gms:62)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-16 19:31:43.460  4814  4814 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,08-16 19:31:43.460  4814  4814 E AndroidRuntime: FATAL EXCEPTION: main
08-16 19:31:43.460  4814  4814 E AndroidRuntime: Process: com.google.android.gms, PID: 4814
08-16 19:31:43.460  4814  4814 E AndroidRuntime: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1548)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1493)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at iof.a(:com.google.android.gms:1949)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at ilq.a(:com.google.android.gms:1293)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at idd.a(:com.google.android.gms:824)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at idh.run(:com.google.android.gms:712)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at jch.run(:com.google.android.gms:17)
08-16 19:31:43.460  4814  4814 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-16 19:31:43.460  1017  1330 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
08-16 19:31:43.480  7238  7238 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
08-16 19:31:43.480  1017  1497 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 19:31:43.480  7238  7238 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 19:31:43.480  7238  7238 D AndroidRuntime: Shutting down VM
08-16 19:31:43.480  7238  7238 E AndroidRuntime: FATAL EXCEPTION: main
08-16 19:31:43.480  7238  7238 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 7238
08-16 19:31:43.480  7238  7238 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-16 19:31:43.480  7238  7238 E AndroidRuntime: 	... 11 more
08-16 19:31:43.480  1017  6702 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-16 19:31:43.480  4814  4814 I Process : Sending signal. PID: 4814 SIG: 9
08-16 19:31:43.490  1017  1516 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: Can't write: system_app_crash
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop177.tmp: open failed: EROFS (Read-only file system)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 19:31:43.490  1017  7258 E DropBoxManagerService: 	... 5 more
08-16 19:31:43.490  1017  1439 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-16 19:31:43.490  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-16 19:31:43.490   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: Can't write: system_app_crash
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop178.tmp: open failed: EROFS (Read-only file system)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 19:31:43.490  1017  7260 E DropBoxManagerService: 	... 5 more
08-16 19:31:43.490  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.490  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.490  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.490  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.500  7211  7259 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
08-16 19:31:43.510  7262  7262 E Zygote  : MountEmulatedStorage()
08-16 19:31:43.510  7262  7262 E Zygote  : v2
08-16 19:31:43.510  7262  7262 I libpersona: KNOX_SDCARD checking this for 10152
08-16 19:31:43.510  7262  7262 I libpersona: KNOX_SDCARD not a persona
08-16 19:31:43.510  7262  7262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-16 19:31:43.510  1017  1042 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7262 uid=10152 gids={50152, 9997} abi=armeabi-v7a
08-16 19:31:43.510  7262  7262 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-16 19:31:43.510  7262  7262 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 19:31:43.520  1017  1533 I ActivityManager: Killing 6841:com.wsomacp/u0a23 (adj 15): empty #21
08-16 19:31:43.520  1017  6702 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-16 19:31:43.520  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.520  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.520  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 19:31:43.520  1017  6702 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
