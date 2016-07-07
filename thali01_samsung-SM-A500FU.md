#### Test 7578926821ef376_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
07-07 20:27:28.060  6345  6345 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:28.060  6345  6345 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:28.120  6345  6364 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
07-07 20:27:28.120  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:28.120  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:28.120  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
--------- beginning of system
07-07 20:27:28.120  1017  1338 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
07-07 20:27:28.120  1017  1338 I ActivityManager: Killing 5772:com.google.android.gms:car/u0a12 (adj 15): empty #31
07-07 20:27:28.120  6345  6364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
07-07 20:27:28.130  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
07-07 20:27:28.130  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
07-07 20:27:28.130  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:28.130  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:28.130  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
07-07 20:27:28.140  6345  6345 D AcmsService: Enter Oncreate
07-07 20:27:28.140  6345  6345 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-07 20:27:28.140  6345  6345 D AcmsService: creating AcmsCore
07-07 20:27:28.140  6345  6345 D AcmsCore: AcmsCore.getAcmsCore() - Enter
07-07 20:27:28.140  6345  6345 D AcmsCore: AcmsCore
07-07 20:27:28.150  6345  6345 D AcmsCore: init
07-07 20:27:28.150  6345  6345 D AcmsCore: Looper handler is not null
07-07 20:27:28.150  6345  6345 D AcmsCore: Post to AcmsCoreHandler
07-07 20:27:28.150  6345  6345 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-07 20:27:28.150  6345  6345 D AcmsServiceMonitor: Incrementing - Counter value: 1
07-07 20:27:28.150  6345  6345 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
07-07 20:27:28.150  6345  6345 D AcmsService: onStartCommand
07-07 20:27:28.150  6345  6345 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
07-07 20:27:28.150  6345  6345 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
07-07 20:27:28.150  6345  6345 D AcmsServiceMonitor: Incrementing - Counter value: 2
07-07 20:27:28.150  6345  6345 D AcmsService: Incremented Counter Value : onStartCommand
07-07 20:27:28.150  6345  6365 D AcmsCertificateMngr: AcmsCertificateMngr
07-07 20:27:28.150  1017  1480 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
07-07 20:27:28.150  1017  1480 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
07-07 20:27:28.160  6345  6345 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
07-07 20:27:28.160  6345  6365 D AcmsRevocationMngr: AcmsRevocationMngr
07-07 20:27:28.180  2067  4265 I Icing   : Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
07-07 20:27:28.190  6345  6345 D AcmsService: Inside handle Intent
07-07 20:27:28.190  6345  6345 D AcmsService: App added - package name: com.test.thalitest
07-07 20:27:28.190  6345  6345 D AcmsCore: Post to AcmsCoreHandler
07-07 20:27:28.190  6345  6345 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-07 20:27:28.190  6345  6345 D AcmsServiceMonitor: Incrementing - Counter value: 3
07-07 20:27:28.190  6345  6345 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
07-07 20:27:28.190  6345  6345 D AcmsService: Decremented Counter Value : handleStartIntent
07-07 20:27:28.190  6345  6345 D AcmsServiceMonitor: Decrementing - Counter value: 2
07-07 20:27:28.210  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-07 20:27:28.210  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:28.210  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:28.210  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-07 20:27:28.210  6143  6143 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
07-07 20:27:28.900   316   316 I ServiceManager: Waiting for service AtCmdFwd...
07-07 20:27:28.900   290   290 E SMD     : DCD OFF
,07-07 20:27:29.900   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
07-07 20:27:30.020  1017  1096 V AlarmManager: waitForAlarm result :8
07-07 20:27:30.070  6367  6367 D AndroidRuntime: 
07-07 20:27:30.070  6367  6367 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-07 20:27:30.070  6367  6367 D AndroidRuntime: CheckJNI is OFF
07-07 20:27:30.080  6367  6367 D AndroidRuntime: readGMSProperty: start
07-07 20:27:30.080  6367  6367 D AndroidRuntime: readGMSProperty: already setted!!
07-07 20:27:30.080  6367  6367 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-07 20:27:30.080  6367  6367 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-07 20:27:30.080  6367  6367 D AndroidRuntime: readGMSProperty: end
07-07 20:27:30.080  6367  6367 D AndroidRuntime: addProductProperty: start
07-07 20:27:30.200  6367  6367 E AffinityControl: AffinityControl: registerfunction enter
07-07 20:27:30.220  6367  6367 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-07 20:27:30.230  1017  1095 E PersonaManagerService: inState():  stateMachine is null !!
07-07 20:27:30.230  1017  1095 I PersonaManagerService: PersonaId don't exist
07-07 20:27:30.230  1017  1095 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-07 20:27:30.230  1017  1095 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 20:27:30.250  1017  1095 W ActivityManager: mDVFSHelper.acquire()
07-07 20:27:30.250  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-07 20:27:30.250  1017  1095 D FocusedStackFrame: Set to : 0
07-07 20:27:30.250  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-07 20:27:30.260  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.260  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.260  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.260  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:30.270  6378  6378 E Zygote  : MountEmulatedStorage()
07-07 20:27:30.270  6378  6378 E Zygote  : v2
07-07 20:27:30.270  6378  6378 I libpersona: KNOX_SDCARD checking this for 10155
07-07 20:27:30.270  6378  6378 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:30.270  1017  1095 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6378 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-07 20:27:30.270  1017  1095 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-07 20:27:30.270  1017  1095 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 20:27:30.270  1017  1095 D InputDispatcher: Focused application set to: xxxx
07-07 20:27:30.270  1017  1095 D InputDispatcher: Focus left window: 1477
07-07 20:27:30.270  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-07 20:27:30.270  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-07 20:27:30.270  6378  6378 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-07 20:27:30.270   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
07-07 20:27:30.280  6367  6367 D AndroidRuntime: Shutting down VM
07-07 20:27:30.280  6378  6378 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-07 20:27:30.280  6378  6378 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-07 20:27:30.290  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 20:27:30.290  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 20:27:30.300  6378  6378 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:30.300  6378  6378 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:30.300  1017  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-07 20:27:30.310  1017  1017 V ActivityManager: Display changed displayId=0
07-07 20:27:30.310  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-07 20:27:30.320  1017  1030 D PersonaManager: isKioskContainerExistOnDevice
07-07 20:27:30.340  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-07 20:27:30.360   257   427 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-07 20:27:30.360   257   434 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-07 20:27:30.370  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{1df5ebaa token=android.os.BinderProxy@26ee45a6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-07 20:27:30.370  1477  1477 D Launcher: onTrimMemory. Level: 20
07-07 20:27:30.430  6378  6378 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-07 20:27:30.440  6378  6378 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9478-9479)
07-07 20:27:30.450  6378  6378 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:27:30.460  6378  6378 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1bcd0c42}
07-07 20:27:30.470  6378  6378 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-07 20:27:30.470  6378  6378 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-07 20:27:30.490  6367  6367 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-07 20:27:30.500  6378  6378 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-07 20:27:30.500  6378  6378 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:27:30.500  6378  6378 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-07 20:27:30.520  6378  6378 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-07 20:27:30.520  6378  6378 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-07 20:27:30.520  6378  6378 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-07 20:27:30.530  6378  6378 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-07 20:27:30.530  6378  6378 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-07 20:27:30.530  6378  6378 I Adreno-EGL: Build Date: 04/06/15 Mon
07-07 20:27:30.530  6378  6378 I Adreno-EGL: Local Branch: 
07-07 20:27:30.530  6378  6378 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-07 20:27:30.530  6378  6378 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-07 20:27:30.530  6378  6378 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-07 20:27:30.560  6345  6365 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,07-07 20:27:30.580  6345  6365 I AcmsKeyStoreHelper: Key Store exist
07-07 20:27:30.580  6345  6365 I AcmsKeyStoreHelper: Hence loading the keystore file
,07-07 20:27:30.640  6378  6404 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-07 20:27:30.650  6345  6365 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
07-07 20:27:30.650  6345  6365 I AcmsCertificateMngr: getKeyStoreForApplication success 
07-07 20:27:30.650  6345  6365 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
07-07 20:27:30.650  6345  6365 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-07 20:27:30.650  6345  6365 D AcmsServiceMonitor: Decrementing - Counter value: 1
07-07 20:27:30.650  6345  6365 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,07-07 20:27:30.650  6345  6365 D AcmsCore: This is NOT a valid MirrorLink app
07-07 20:27:30.650  6345  6365 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
07-07 20:27:30.650  6345  6365 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
07-07 20:27:30.650  6345  6365 D AcmsServiceMonitor: Decrementing - Counter value: 0
07-07 20:27:30.650  6345  6365 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,07-07 20:27:30.650  6345  6345 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-07 20:27:30.650  6345  6345 D AcmsService: Enter onDestroy
07-07 20:27:30.650  6345  6345 I AcmsService: cleanUp(): inside service clean up
07-07 20:27:30.650  6345  6345 D AcmsCore: AcmsCore: inside DeInit
07-07 20:27:30.650  6345  6345 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
07-07 20:27:30.650  6345  6345 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
07-07 20:27:30.650  6345  6345 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
07-07 20:27:30.650  6345  6345 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
07-07 20:27:30.650  6345  6345 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,07-07 20:27:30.650  6345  6345 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
07-07 20:27:30.650  6345  6345 D AcmsService: killing acms process
07-07 20:27:30.650  6345  6345 I Process : Sending signal. PID: 6345 SIG: 9
,07-07 20:27:30.690  6378  6378 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:27:30.700  6378  6378 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-07 20:27:30.710  6378  6378 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-07 20:27:30.710  6378  6378 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-07 20:27:30.720  1017  1338 I ActivityManager: Process ACMS.Process (pid 6345)(adj 0) has died(68,1126)
,07-07 20:27:30.720  6378  6378 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-07 20:27:30.730  6378  6378 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:27:30.730  6378  6378 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-07 20:27:30.770  6378  6417 D OpenGLRenderer: Render dirty regions requested: true
,07-07 20:27:30.770  1017  3228 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-07 20:27:30.770  1017  3228 D KnoxTimeoutHandler: postActiveUserChange for user 0
,07-07 20:27:30.770  1017  3228 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-07 20:27:30.780  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,07-07 20:27:30.780  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,07-07 20:27:30.790  6378  6378 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-07 20:27:30.790  6378  6378 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-07 20:27:30.800   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,07-07 20:27:30.810  1017  3227 D InputDispatcher: Focus entered window: 6378
,07-07 20:27:30.810  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 20:27:30.810  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-07 20:27:30.810  6378  6378 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-07 20:27:30.810  6378  6417 I OpenGLRenderer: Initialized EGL, version 1.4
,07-07 20:27:30.820  6378  6417 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,07-07 20:27:30.820  6378  6417 D OpenGLRenderer: Enabling debug mode 0
,07-07 20:27:30.880  1017  1029 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-07 20:27:30.890  6378  6378 V ActivityThread: updateVisibility : ActivityRecord{175a0ab5 token=android.os.BinderProxy@101c059f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-07 20:27:30.890  1017  6420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-07 20:27:30.900  6378  6378 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-07 20:27:30.900  6378  6378 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@101c059f time:129932
,07-07 20:27:30.900  1174  1174 I StatusBar: Icon Only
07-07 20:27:30.900  1174  1174 D PanelView: There is/are notification(s) 
,07-07 20:27:30.900  1017  1047 I ActivityManager: Displayed Component not be shown by security: +578ms (total +15s349ms)
,07-07 20:27:30.910  1017  1047 W ActivityManager: mDVFSHelper.release()
,07-07 20:27:30.910  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{931f49a u0 com.test.thalitest/.MainActivity t24} time:129940
,07-07 20:27:30.910  1812  1812 I SamsungIME: getCurrentCandidateView
,07-07 20:27:30.910   257   427 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,07-07 20:27:30.910   257   636 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,07-07 20:27:30.970  6378  6378 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6378
,07-07 20:27:31.010  1812  1812 D SamsungIME: Dismiss ExpandCandiate
,07-07 20:27:31.100  6378  6378 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-07 20:27:31.150  1812  1812 I SamsungIME: getDebugLevel  : 0x4f4c
,07-07 20:27:31.200  1812  1812 I SamsungIME: getDebugLevel  : 0x4f4c
,07-07 20:27:31.210  1812  1812 I SamsungIME: KeybaordView init() : load resources
,07-07 20:27:31.210  6378  6422 D jxcore_app_log: JniHelper::setJavaVM(0xb8320328), pthread_self() = -1199051192
,07-07 20:27:31.220  6378  6422 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-07 20:27:31.220  6378  6422 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-07 20:27:31.220  6378  6422 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-07 20:27:31.220  6378  6422 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-07 20:27:31.220  6378  6422 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-07 20:27:31.220  6378  6422 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11640b25 added. We now have 1 listener(s)
,07-07 20:27:31.230  6378  6422 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,07-07 20:27:31.230  6378  6422 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,07-07 20:27:31.230  6378  6422 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-07 20:27:31.230  6378  6422 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c003508 added. We now have 1 listener(s)
,07-07 20:27:31.240  6378  6422 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-07 20:27:31.240  1812  1812 I SamsungIME: getCurrentKeyboard
07-07 20:27:31.240  1812  1812 I SamsungIME: getTextKeyboard
,07-07 20:27:31.240  6378  6422 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-07 20:27:31.250  6378  6422 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-07 20:27:31.250  6378  6422 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-07 20:27:31.250  6378  6422 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-07 20:27:31.250  6378  6422 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2,
,07-07 20:27:31.250  6378  6422 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-07 20:27:31.250  6378  6422 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,07-07 20:27:31.260  6378  6422 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-07 20:27:31.260  6378  6422 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-07 20:27:31.260  6378  6422 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-07 20:27:31.260  6378  6422 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-07 20:27:31.260  6378  6422 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-07 20:27:31.260  6378  6422 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-07 20:27:31.260  6378  6422 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-07 20:27:31.260  6378  6422 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-07 20:27:31.260  6378  6422 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-07 20:27:31.260  6378  6422 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-07 20:27:31.260  1812  1812 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-07 20:27:31.260  6378  6422 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-07 20:27:31.260  6378  6378 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:31.270  6378  6378 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-07 20:27:31.290  6378  6378 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-07 20:27:31.780  1812  6427 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-07 20:27:31.790  6378  6428 W jxcore-log: Initializing JXcore engine
07-07 20:27:31.790  6378  6428 W jxcore-log: JXcore engine is ready
,07-07 20:27:31.850  1921  1921 E audit   : type=1400 msg=audit(1467916051.850:205): avc:  denied  { ioctl } for  pid=6428 comm="Thread-1108" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-07 20:27:31.850  1921  1921 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
07-07 20:27:31.850  1921  1921 E audit   : type=1300 msg=audit(1467916051.850:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9d9008f8 items=0 ppid=305 ppcomm=main pid=6428 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1108" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-07 20:27:31.850  1921  1921 E audit   : type=1320 msg=audit(1467916051.850:205): 
,07-07 20:27:31.860  6378  6428 W jxcore-log: Starting JXcore engine
,07-07 20:27:31.910   290   290 E SMD     : DCD OFF
,07-07 20:27:31.960  6378  6428 W jxcore-log: Platform android
07-07 20:27:31.960  6378  6428 W jxcore-log: 
07-07 20:27:31.960  6378  6428 W jxcore-log: Process ARCH arm
07-07 20:27:31.960  6378  6428 W jxcore-log: 
,07-07 20:27:32.160  6378  6428 I jxcore-log: JXcore Cordova bridge is ready!
07-07 20:27:32.160  6378  6428 I jxcore-log: 
,07-07 20:27:32.160  6378  6428 W jxcore-log: JXcore engine is started
,07-07 20:27:32.170  6378  6422 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-07 20:27:32.180  6378  6378 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-07 20:27:32.190  6378  6428 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-07 20:27:32.190  6378  6428 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-07 20:27:32.200  6378  6378 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-07 20:27:32.200  6378  6378 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-07 20:27:32.200  1017  1543 D FocusedStackFrame: Set to : 0
07-07 20:27:32.200  1017  1543 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-07 20:27:32.200  1017  1543 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-07 20:27:32.200  1017  1543 D InputDispatcher: Focused application set to: xxxx
07-07 20:27:32.200  1017  1543 D InputDispatcher: Focus left window: 6378
07-07 20:27:32.210  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-07 20:27:32.210  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-07 20:27:32.210  1017  1543 I ActivityManager: Killing 5874:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,07-07 20:27:32.210  6378  6378 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-07 20:27:32.220  6378  6378 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,07-07 20:27:32.220  6378  6378 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-07 20:27:32.220  6378  6378 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-07 20:27:32.220  6378  6378 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-07 20:27:32.220  6378  6378 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-07 20:27:32.220  6378  6378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11640b25 removed from the list
07-07 20:27:32.220  6378  6378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-07 20:27:32.220  6378  6378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c003508 removed from the list
07-07 20:27:32.220  6378  6378 D io.jxcore.node.ConnectivityMonitor: stop
07-07 20:27:32.220  6378  6378 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-07 20:27:32.220  6378  6378 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-07 20:27:32.250   257   427 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,07-07 20:27:32.250   257   636 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,07-07 20:27:32.250  1017  3229 W ActivityManager: mDVFSHelper.acquire()
,07-07 20:27:32.260  1017  3229 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-07 20:27:32.280  1477  1477 D Launcher: onRestart, Launcher: 228829838
,07-07 20:27:32.280  1477  1477 D Launcher: onStart, Launcher: 228829838,
07-07 20:27:32.280  1477  1477 D Launcher.HomeView: onStart
07-07 20:27:32.280  1477  1477 D Launcher: onResume, Launcher: 228829838,
07-07 20:27:32.280  1017  1095 D SettingsProvider: name = kids_home_mode,
07-07 20:27:32.280  1017  1095 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-07 20:27:32.280  1017  1095 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
,07-07 20:27:32.280  1017  1095 D SettingsProvider: selectionArgs: false
07-07 20:27:32.280  1017  1095 D SettingsProvider: selectionArgs: 10007
07-07 20:27:32.280  1017  1095 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
07-07 20:27:32.280  1017  1095 D SettingsProvider: ret = -1
07-07 20:27:32.280  1477  1477 D Launcher.HomeView: onResume
07-07 20:27:32.290  1477  1477 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-07 20:27:32.290  1477  1477 D MenuAppsGridFragment: onResume
07-07 20:27:32.290  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.290  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.290  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
07-07 20:27:32.290  1477  1477 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-07 20:27:32.290  1477  1477 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-07 20:27:32.290  1477  1477 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
07-07 20:27:32.300  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.300  1017  1480 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
07-07 20:27:32.300  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.300  1017  1480 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
07-07 20:27:32.300  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
07-07 20:27:32.300  5036  5036 D GalleryCacheReady: Receive : home resume
07-07 20:27:32.300  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.300  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.300  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-07 20:27:32.310  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.310  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.310  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-07 20:27:32.310  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.310  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.310  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-07 20:27:32.310  1017  1338 D ActivityManager: handle home activity for 0
07-07 20:27:32.310  1017  1338 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-07 20:27:32.310  1017  1338 D KnoxTimeoutHandler: post home show event for user 0
07-07 20:27:32.310  1017  1338 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-07 20:27:32.310  1017  1338 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-07 20:27:32.310  1017  1338 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-07 20:27:32.310  5726  5726 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
07-07 20:27:32.310  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-07 20:27:32.310  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-07 20:27:32.310  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-07 20:27:32.310  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,07-07 20:27:32.310  1477  1477 D Launcher.HomeView: onPause
,07-07 20:27:32.320  1477  1477 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-07 20:27:32.320  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.320  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.320  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-07 20:27:32.320  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.320  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.320  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
07-07 20:27:32.320  5828  5828 D Mms/UIEventReceiver: ui event
,07-07 20:27:32.330  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:32.330  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.330  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-07 20:27:32.340  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.340  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.340  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-07 20:27:32.340  1017  1480 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1477, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,07-07 20:27:32.340  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.340  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.340  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-07 20:27:32.340  2515  2515 D Recents_RecreateReceiver: onReceive by home
,07-07 20:27:32.350  1017  1480 I splitIntent: Queue : backgroundsplit_0 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,07-07 20:27:32.350   257   257 I SurfaceFlinger: id=15 createSurf (720x1280),1 flag=4, Mauncher
07-07 20:27:32.350  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.350  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:32.350  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-07 20:27:32.360  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-07 20:27:32.360  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-07 20:27:32.360  5726  5726 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-07 20:27:32.360  1017  1545 D InputDispatcher: Focus entered window: 1477
,07-07 20:27:32.370  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-07 20:27:32.370  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-07 20:27:32.370  1477  1477 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-07 20:27:32.370  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{1df5ebaa token=android.os.BinderProxy@26ee45a6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-07 20:27:32.370  1477  1477 D Launcher.HomeView: onStop
,07-07 20:27:32.380  1017  3006 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-07 20:27:32.380  6378  6378 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-07 20:27:32.380  1017  6436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-07 20:27:32.390  1812  1812 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-07 20:27:32.400  1174  1174 I StatusBar: Icon Only
07-07 20:27:32.400  1174  1174 D PanelView: There is/are notification(s) 
,07-07 20:27:32.410  1477  1477 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@26ee45a6 time:131444
,07-07 20:27:32.430  1017  1047 W ActivityManager: mDVFSHelper.release()
,07-07 20:27:32.430  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{29828a60 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t22} time:131467
,07-07 20:27:32.470  6431  6431 D AndroidRuntime: 
07-07 20:27:32.470  6431  6431 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-07 20:27:32.470  1017  1049 I PowerManagerService: [PWL] Off : 15s ago
,07-07 20:27:32.470  6431  6431 D AndroidRuntime: CheckJNI is OFF
,07-07 20:27:32.470  6431  6431 D AndroidRuntime: readGMSProperty: start
07-07 20:27:32.470  6431  6431 D AndroidRuntime: readGMSProperty: already setted!!
07-07 20:27:32.470  6431  6431 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-07 20:27:32.470  6431  6431 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-07 20:27:32.470  6431  6431 D AndroidRuntime: readGMSProperty: end
07-07 20:27:32.470  6431  6431 D AndroidRuntime: addProductProperty: start
,07-07 20:27:32.520  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200,
,07-07 20:27:32.630  6431  6431 E AffinityControl: AffinityControl: registerfunction enter,
,07-07 20:27:32.660  6431  6431 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-07 20:27:32.670  1017  1029 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-07 20:27:32.670  1017  1029 D PackageManager: START PACKAGE DELETE: observer{453962654}
07-07 20:27:32.670  1017  1029 D PackageManager: pkg{<packageName>}
07-07 20:27:32.670  1017  1029 D PackageManager: user{0}
07-07 20:27:32.670  1017  1029 D PackageManager: caller{2000}
07-07 20:27:32.670  1017  1029 D PackageManager: flags{2}
07-07 20:27:32.670  1017  1029 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-07 20:27:32.670  1017  1029 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-07 20:27:32.670  1017  1029 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-07 20:27:32.670  1017  1029 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-07 20:27:32.670  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-07 20:27:32.670  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-07 20:27:32.670  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,07-07 20:27:32.670  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
07-07 20:27:32.670  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-07 20:27:32.670  1017  1057 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,07-07 20:27:32.670  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
07-07 20:27:32.670  1017  1042 I ActivityManager: Killing 6378:com.test.thalitest/u0a155 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-07 20:27:32.680  1017  1042 D PersonaManager: isKioskContainerExistOnDevice,
,07-07 20:27:32.930  1017  1545 I art     : Explicit concurrent mark sweep GC freed 167205(9MB) AllocSpace objects, 9(1949KB) LOS objects, 33% free, 28MB/42MB, paused 2.520ms total 203.331ms
07-07 20:27:32.930  1017  1545 D ActivityManager: bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
07-07 20:27:32.930  1017  1545 D ActivityManager: com.google.android.gms, Starting
07-07 20:27:32.930  1017  1545 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,07-07 20:27:32.930  1017  1545 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:32.930  1017  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:32.930  1017  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,07-07 20:27:32.940  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,07-07 20:27:32.970  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-07 20:27:32.980  5661  5661 I art     : Explicit concurrent mark sweep GC freed 15868(921KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 6MB/11MB, paused 770us total 28.505ms
,07-07 20:27:33.000  5748  5748 I art     : Explicit concurrent mark sweep GC freed 13308(747KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 6MB/9MB, paused 765us total 29.986ms
,07-07 20:27:33.020  1936  2112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-07 20:27:33.020  1812  1812 E SamsungIME: mOCRHelper is null
,07-07 20:27:33.020  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-07 20:27:33.030  1017  1125 V NetworkStats: removeUidsLocked() for UIDs [10155]
07-07 20:27:33.030  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
07-07 20:27:33.030  1017  1125 V NetworkStats: performPollLocked(flags=0x3)
,07-07 20:27:33.040  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
07-07 20:27:33.040  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-07 20:27:33.040  1017  1125 V NetworkStats: performPollLocked() took 8ms
07-07 20:27:33.040  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 20:27:33.060  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,07-07 20:27:33.060  1440  1440 D RegisteredServicesCache: empty dynamic service
,07-07 20:27:33.070  3688  3688 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jul 07 20:27:33 GMT+02:00 2016
,07-07 20:27:33.070  1017  3006 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-07 20:27:33.070  1017  3006 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.070  1017  3006 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.070  1017  3006 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.070  1017  3006 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-07 20:27:33.080  3688  3688 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,07-07 20:27:33.080  1017  3229 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
07-07 20:27:33.080  1017  3229 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
07-07 20:27:33.080  1017  3229 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-07 20:27:33.080  1017  3229 D ActivityManager: com.sec.esdk.elm, Starting
07-07 20:27:33.080  1017  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.080  1017  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.080  1017  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.080  1017  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.090  3688  3688 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,07-07 20:27:33.100  6453  6453 E Zygote  : MountEmulatedStorage()
07-07 20:27:33.100  6453  6453 E Zygote  : v2
07-07 20:27:33.100  6453  6453 I libpersona: KNOX_SDCARD checking this for 10094
07-07 20:27:33.100  6453  6453 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:33.100  3688  3688 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-07 20:27:33.100  6453  6453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,07-07 20:27:33.100  1017  3229 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6453 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,07-07 20:27:33.110  6453  6453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-07 20:27:33.110  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,07-07 20:27:33.110  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-07 20:27:33.110  6453  6453 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 20:27:33.120  3688  3688 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-07 20:27:33.120  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,07-07 20:27:33.120  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,07-07 20:27:33.120  1017  1041 W TextServicesManagerService: no available spell checker services found
,07-07 20:27:33.130  3688  6452 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,07-07 20:27:33.160  6453  6453 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:33.160  6453  6453 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:33.170  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,07-07 20:27:33.180  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 20:27:33.180  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-07 20:27:33.180  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,07-07 20:27:33.190  1017  3229 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-07 20:27:33.190  1017  3229 D SecContentProvider2: mCursor = null
,07-07 20:27:33.190  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-07 20:27:33.190  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,07-07 20:27:33.190  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,07-07 20:27:33.190  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:33.190  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,07-07 20:27:33.190  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.190  5036  5036 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,07-07 20:27:33.200  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,07-07 20:27:33.200  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,07-07 20:27:33.200  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-07 20:27:33.200  3688  6452 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
07-07 20:27:33.200  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
07-07 20:27:33.200  1017  1042 D ActivityManager: com.sec.android.app.themechooser, Starting
,07-07 20:27:33.200  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-07 20:27:33.200  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-07 20:27:33.200  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-07 20:27:33.200  1017  1017 V EnterpriseBillingPolicy: uID is 10155
07-07 20:27:33.200  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-07 20:27:33.200  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-07 20:27:33.210  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,07-07 20:27:33.210  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.210  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.210  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.210  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.210  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-07 20:27:33.210  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-07 20:27:33.210  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-07 20:27:33.210  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-07 20:27:33.220  3688  6452 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,07-07 20:27:33.220  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.220  3688  6452 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-07 20:27:33.230  6469  6469 E Zygote  : MountEmulatedStorage(),
07-07 20:27:33.230  6469  6469 E Zygote  : v2
07-07 20:27:33.230  6469  6469 I libpersona: KNOX_SDCARD checking this for 10149
07-07 20:27:33.230  6469  6469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-07 20:27:33.230  6469  6469 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:33.230  6469  6469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-07 20:27:33.230  1017  1057 I art     : Explicit concurrent mark sweep GC freed 22376(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 6.706ms total 249.247ms
07-07 20:27:33.230  6469  6469 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 20:27:33.240  1017  1042 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6469 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-07 20:27:33.250  6453  6453 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-07 20:27:33.250  6453  6453 D elm:15183: ELMEngine.ELMEngine( context ).
,07-07 20:27:33.260  6453  6453 D elm:15183: MDMBridge.setEnterpriseBridge()
,07-07 20:27:33.260  5828  5828 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-07 20:27:33.270  1017  1338 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-07 20:27:33.270  1017  1338 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.270  1017  1338 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.270  1017  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.270  1017  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-07 20:27:33.270  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-07 20:27:33.270  6453  6453 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-07 20:27:33.280  1017  1480 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-07 20:27:33.280  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicy: uID is 10155
07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-07 20:27:33.280  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-07 20:27:33.280  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.280  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.280  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,07-07 20:27:33.280  5748  6468 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,07-07 20:27:33.280  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,07-07 20:27:33.280  6469  6469 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:33.290  6469  6469 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:33.290  6453  6453 D elm:15183: ElmAgentService : onCreate()
,07-07 20:27:33.290  6453  6484 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-07 20:27:33.290  6453  6484 D elm:15183: MainReceiver.listeningToPackageRemoved()
07-07 20:27:33.290  6453  6484 D elm:15183: MDMBridge.getInstance()
07-07 20:27:33.290  6453  6484 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,07-07 20:27:33.290  6453  6484 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,07-07 20:27:33.290  5748  5748 I art     : Explicit concurrent mark sweep GC freed 1038(49KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 782us total 31.564ms
,07-07 20:27:33.290  1017  2747 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,07-07 20:27:33.300  3380  3380 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-07 20:27:33.300  3380  3380 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-07 20:27:33.300  3380  3380 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
07-07 20:27:33.300  3380  3380 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-07 20:27:33.300  3380  3380 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-07 20:27:33.300  3380  3380 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-07 20:27:33.300  3380  3380 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-07 20:27:33.300  3380  3380 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:33.300  3380  3380 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.300  3380  3380 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:33.300  3380  3380 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:33.300  3380  3380 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:33.300  3380  3380 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:33.300  3380  3380 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-07 20:27:33.300  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=24_task.xml
,07-07 20:27:33.310  3688  6452 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-07 20:27:33.320  1017  3228 I TactileAssist: enable value -1
,07-07 20:27:33.320  1017  3228 I TactileAssist: internal enable value -1
07-07 20:27:33.320  1017  3228 I TactileAssist: intensity value -1
,07-07 20:27:33.320  1017  3228 I TactileAssist: saveAppList value true
,07-07 20:27:33.320  1017  3228 I TactileAssist: List of disabled apps :
,07-07 20:27:33.320  5828  6485 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-07 20:27:33.320  5828  6485 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-07 20:27:33.330  6453  6453 D elm:15183: ElmAgentService : onDestroy().
,07-07 20:27:33.330  1017  1338 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
07-07 20:27:33.330  1017  1338 D ActivityManager: com.sec.android.provider.badge, Starting
,07-07 20:27:33.330  3688  6452 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-07 20:27:33.330  1017  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.330  1017  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.330  6031  6031 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-07 20:27:33.330  1017  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.330  6031  6031 I PCWCLIENTTRACE_PushUtil: sales region : global
07-07 20:27:33.330  1017  1338 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.330  6031  6031 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-07 20:27:33.330  6031  6031 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-07 20:27:33.340  3688  6452 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,07-07 20:27:33.350  6487  6487 E Zygote  : MountEmulatedStorage()
,07-07 20:27:33.350  6487  6487 E Zygote  : v2
07-07 20:27:33.350  6487  6487 I libpersona: KNOX_SDCARD checking this for 10072
07-07 20:27:33.350  6487  6487 I libpersona: KNOX_SDCARD not a persona,
07-07 20:27:33.350  6487  6487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-07 20:27:33.350  6487  6487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-07 20:27:33.350  6487  6487 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-07 20:27:33.350  1017  1338 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6487 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
,07-07 20:27:33.360  6469  6469 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-07 20:27:33.360  6469  6469 D ThemeInfoUtil: isCurrentFestival = false
,07-07 20:27:33.370  3688  3688 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,07-07 20:27:33.380  6487  6487 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:33.380  6487  6487 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:33.380  6042  6042 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,07-07 20:27:33.390  1017  3229 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,07-07 20:27:33.400  1017  3229 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.400  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-07 20:27:33.400  1017  3229 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:33.400  1017  3229 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.400  1017  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,07-07 20:27:33.400  1017  1480 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
07-07 20:27:33.400  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.400  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.400  1017  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.400  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,07-07 20:27:33.410  6487  6487 D BadgeProvider: onCreate
,07-07 20:27:33.410  6487  6487 D BadgeProvider: DatabaseHelper
,07-07 20:27:33.410  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.420  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.430  1017  1057 D PackageManager: delete codoeFile: 
,07-07 20:27:33.440  6123  6123 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
07-07 20:27:33.440  6123  6123 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
07-07 20:27:33.440  6123  6123 I TapandpayWidget:Utils: Clear T&P info.
,07-07 20:27:33.440  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.440  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
07-07 20:27:33.440  1017  1057 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,07-07 20:27:33.440  6487  6500 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-07 20:27:33.440  6487  6500 D BadgeProvider: sendNotify, [notify] : null
07-07 20:27:33.440  6487  6500 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-07 20:27:33.440  6487  6500 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-07 20:27:33.440  6487  6500 D BadgeProvider: update, [UpdateCount] : 1
,07-07 20:27:33.450  6161  6161 D Compatibility: onReceive() it will make start service
,07-07 20:27:33.450  6123  6123 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
07-07 20:27:33.450  1017  1544 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-07 20:27:33.450  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-07 20:27:33.450  1017  1057 D PackageManager: result of delete: 1{453962654}
,07-07 20:27:33.450  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:33.450  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.450  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,07-07 20:27:33.450  5533  5533 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
07-07 20:27:33.450  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-07 20:27:33.450  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-07 20:27:33.450  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-07 20:27:33.450  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.450  1017  3229 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
07-07 20:27:33.450  1017  3229 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-07 20:27:33.460  1017  1095 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-07 20:27:33.460  1017  1095 D ActivityManager: com.sec.spp.push, Starting
,07-07 20:27:33.460  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.460  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.460  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.460  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.460  6161  6504 D Compatibility: onHandleIntent()
07-07 20:27:33.460  6431  6431 D AndroidRuntime: Shutting down VM
07-07 20:27:33.460  6161  6504 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,07-07 20:27:33.470  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-07 20:27:33.470  1017  1057 D PackageManager: userId{-1}
07-07 20:27:33.470  1017  1057 D PackageManager: andCode{true}
,07-07 20:27:33.470  6161  6504 D Compatibility: found: 2
07-07 20:27:33.470  6161  6504 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-07 20:27:33.470  6161  6504 D Compatibility: skipping ResolveInfo{20384a89 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-07 20:27:33.470  6161  6504 D Compatibility: considering ResolveInfo{da3aa8e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-07 20:27:33.470  6161  6504 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,07-07 20:27:33.470  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.480  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:33.480  6505  6505 E Zygote  : MountEmulatedStorage()
07-07 20:27:33.480  6505  6505 E Zygote  : v2
07-07 20:27:33.480  6505  6505 I libpersona: KNOX_SDCARD checking this for 10035
07-07 20:27:33.480  6505  6505 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:33.480  6505  6505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-07 20:27:33.480  6161  6504 D Compatibility: enabling receiver ResolveInfo{247b12af com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-07 20:27:33.480  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:33.480  1017  1095 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6505 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-07 20:27:33.480  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 20:27:33.480  6505  6505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,07-07 20:27:33.490  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.490  6505  6505 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-07 20:27:33.490  6161  6504 D Compatibility: enabling receiver ResolveInfo{2a7276bc com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-07 20:27:33.500  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:33.500  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 20:27:33.500  6161  6504 D Compatibility: enabling receiver ResolveInfo{4520645 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-07 20:27:33.500  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-07 20:27:33.500  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-07 20:27:33.500  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-07 20:27:33.500   305   305 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 675us total 23.105ms
,07-07 20:27:33.500  1017  1095 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
07-07 20:27:33.500  1017  1095 D ActivityManager: com.sec.enterprise.knox.cloudmdm.smdms, Starting
,07-07 20:27:33.500  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.500  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.500  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.500  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.510  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-07 20:27:33.510  6161  6504 D Compatibility: enabling receiver ResolveInfo{3333e19a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-07 20:27:33.520  6161  6504 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-07 20:27:33.520   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 16.949ms
,07-07 20:27:33.530  6505  6505 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:33.530  6505  6505 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:33.540   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 16.976ms
,07-07 20:27:33.560  6520  6520 E Zygote  : MountEmulatedStorage()
,07-07 20:27:33.560  6520  6520 E Zygote  : v2
07-07 20:27:33.560  6520  6520 I libpersona: KNOX_SDCARD checking this for 10160
07-07 20:27:33.560  6520  6520 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:33.560  6520  6520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-07 20:27:33.560  6520  6520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-07 20:27:33.560  1017  1095 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6520 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
07-07 20:27:33.560  6520  6520 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 20:27:33.570  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-07 20:27:33.570  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-07 20:27:33.580  1017  3229 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-07 20:27:33.580  1017  3229 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.580  1017  3229 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.580  1017  3229 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:33.580  1017  3229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-07 20:27:33.590  1017  3229 I ActivityManager: Killing 5889:com.wsomacp/u0a25 (adj 15): empty #31
,07-07 20:27:33.600  6520  6520 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:33.600  6520  6520 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:33.610  6205  6532 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-07 20:27:33.610  1017  1480 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,07-07 20:27:33.610  1017  1480 D ActivityManager: com.android.keychain, Starting
,07-07 20:27:33.620  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.620  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.620  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.620  1017  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.620  6520  6520 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-07 20:27:33.630  6536  6536 E Zygote  : MountEmulatedStorage()
07-07 20:27:33.630  6536  6536 E Zygote  : v2
07-07 20:27:33.630  6536  6536 I libpersona: KNOX_SDCARD checking this for 1000
07-07 20:27:33.630  6536  6536 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:33.630  6536  6536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-07 20:27:33.640  6536  6536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-07 20:27:33.640  6536  6536 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-07 20:27:33.640  1017  1480 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6536 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,07-07 20:27:33.640  6520  6520 D [0]UMC:UMCContentProvider: @onCreate
,07-07 20:27:33.640  1017  1480 I ActivityManager: Killing 5962:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,07-07 20:27:33.650  1017  1095 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
07-07 20:27:33.650  1017  1095 D ActivityManager: com.samsung.android.intelligenceservice, Starting
,07-07 20:27:33.650  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.650  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.650  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.650  1017  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.650  1477  1477 D Launcher.Model: reloadBadges entered.
,07-07 20:27:33.670  6431  6431 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,07-07 20:27:33.680  6552  6552 E Zygote  : MountEmulatedStorage()
07-07 20:27:33.680  6552  6552 E Zygote  : v2
,07-07 20:27:33.680  6552  6552 I libpersona: KNOX_SDCARD checking this for 10003
07-07 20:27:33.680  6552  6552 I libpersona: KNOX_SDCARD not a persona
,07-07 20:27:33.680  6552  6552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,07-07 20:27:33.680  6536  6536 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-07 20:27:33.680  6536  6536 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:33.690  6552  6552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,07-07 20:27:33.690  6552  6552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:33.690  1017  1095 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6552 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,07-07 20:27:33.690  1017  1338 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-07 20:27:33.690  1017  1338 W ActivityManager: userId = 0, bbcId = -10000,
07-07 20:27:33.690  1017  1338 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
07-07 20:27:33.690  1017  1338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.690  1017  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,07-07 20:27:33.710  6520  6520 D [0]UMC:Core: onCreate(): 
07-07 20:27:33.710  6520  6520 D [0]UMC:Core: @isManagedProfileUser
07-07 20:27:33.710  6520  6520 D [0]UMC:Core: userId: 0
,07-07 20:27:33.720  6520  6520 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
07-07 20:27:33.720  6520  6520 D [0]UMC:Core: userInfo.isManagedProfile() : false
,07-07 20:27:33.720  6505  6563 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-07 20:27:33.720  6505  6563 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-07 20:27:33.730  6265  6265 I SA      : [SUR] onReceive called
07-07 20:27:33.730  6265  6265 I SA      : [SUR] Not SA Package.. finish
,07-07 20:27:33.730  1017  1545 I ActivityManager: Killing 5476:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,07-07 20:27:33.730  6552  6552 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-07 20:27:33.740  6552  6552 D ActivityThread: Added TimaKeyStore provider
,07-07 20:27:33.740  1017  1308 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,07-07 20:27:33.740  6505  6563 D SPPClientService: PushLog.txt file is not deleted.
07-07 20:27:33.740  6505  6563 D SPPClientService: PushLog.txt file is not deleted.
07-07 20:27:33.740  6505  6563 D SPPClientService: ============PushLog. stop!
,07-07 20:27:33.740  1017  1308 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.740  1017  1308 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:33.740  1017  1308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.740  1017  1308 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,07-07 20:27:33.750  1017  1338 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-07 20:27:33.750  1017  1338 W ActivityManager: userId = 0, bbcId = -10000
,07-07 20:27:33.750  1017  1338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:33.750  1017  1338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,07-07 20:27:33.750  6520  6520 D [0]UMC:DeviceInfo: USA==US==
,07-07 20:27:33.760  1017  3227 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-07 20:27:33.760  1017  3227 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.760  1017  3227 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.760  1017  3227 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:33.760  1017  3227 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-07 20:27:33.780  1017  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-07 20:27:33.780  1017  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.780  1017  1480 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.780  1017  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:33.780  1017  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-07 20:27:33.780  6552  6552 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-07 20:27:33.780  6536  6536 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,07-07 20:27:33.780  1017  1544 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
07-07 20:27:33.780  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.790  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.790  1017  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-07 20:27:33.790  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,07-07 20:27:33.800  1017  3229 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,07-07 20:27:33.800  1017  3229 D ActivityManager: com.samsung.android.app.mirrorlink, Starting
,07-07 20:27:33.800  1017  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.800  1017  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.800  1017  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-07 20:27:33.800  1017  3229 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-07 20:27:33.810  1520  1530 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-07 20:27:33.810  1520  1530 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-07 20:27:33.810  1520  1530 E DatabaseUtils: Writing exception to parcel
07-07 20:27:33.810  1520  1530 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at com.sec.android.provider.logsprovider.LogsProvider.delete(LogsProvider.java:3550)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
07-07 20:27:33.810  1520  1530 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,07-07 20:27:33.810  6552  6552 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,07-07 20:27:33.820  6552  6552 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-07 20:27:33.820  6552  6552 D UserAnalysis: Create SecureDbHelper
,07-07 20:27:33.820  6536  6572 E SQLiteLog: (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,07-07 20:27:33.820  6573  6573 E Zygote  : MountEmulatedStorage()
,07-07 20:27:33.820  6573  6573 E Zygote  : v2
07-07 20:27:33.820  6573  6573 I libpersona: KNOX_SDCARD checking this for 1000
07-07 20:27:33.820  6573  6573 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
07-07 20:27:33.820  6573  6573 I libpersona: KNOX_SDCARD not a persona
07-07 20:27:33.820  1017  3229 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6573 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
07-07 20:27:33.830  1017  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-07 20:27:33.830  1017  1493 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.830  1017  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:33.830  1017  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-07 20:27:33.830  1017  1544 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
07-07 20:27:33.830  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.830  1017  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
07-07 20:27:33.830  1017  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
07-07 20:27:33.830  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-07 20:27:33.830  6552  6552 D IntelligenceServiceApplication: onCreate()
07-07 20:27:33.830  6573  6573 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
07-07 20:27:33.830  6552  6552 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,07-07 20:27:33.840  6573  6573 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-07 20:27:33.840  6552  6552 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,07-07 20:27:33.840  6552  6552 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:33.840  6552  6552 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:33.840  6552  6552 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-07 20:27:33.840  6552  6552 W SQLiteOpenHelper: Opened privacy in read-only mode
07-07 20:27:33.840  1692  6570 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-07 20:27:33.840  1692  6570 E AndroidRuntime: Process: android.process.acore, PID: 1692
07-07 20:27:33.840  1692  6570 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:543)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:476)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.840  1692  6570 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.840  6536  6572 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:27,:33.840  6536  6572 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
07-07 20:27:33.840  6536  6572 E AndroidRuntime: Process: com.android.keychain, PID: 6536
07-07 20:27:33.840  6536  6572 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.840  6536  6572 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:27:33.850  1017  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname android.process.acore
07-07 20:27:33.850  6552  6552 D IntelligenceServiceApplication: no applications having user consent for prediction
07-07 20:27:33.860  1017  3228 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.keychain
07-07 20:27:33.860  1692  6570 I Process : Sending signal. PID: 1692 SIG: 9
07-07 20:27:33.860  6536  6572 I Process : Sending signal. PID: 6536 SIG: 9
07-07 20:27:33.860  1017  3225 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
07-07 20:27:33.860  6552  6552 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
07-07 20:27:33.860  5748  5748 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop179.tmp: open failed: EROFS (Read-only file system)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:27:33.870  1017  6582 E DropBoxManagerService: 	... 5 more
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop180.tmp: open failed: EROFS (Read-only file system)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:27:33.870  1017  6588 E DropBoxManagerService: 	... 5 more
07-07 20:27:33.870  6573  6573 D TimaKeyStoreProvider: TimaSignature is unavailable
07-07 20:27:33.870  6573  6573 D ActivityThread: Added TimaKeyStore provider
07-07 20:27:33.870  6520  6520 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,07-07 20:27:33.880  6520  6520 D [0]UMC:AdminManager: init - start
07-07 20:27:33.880  6487  6498 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-07 20:27:33.880  6487  6498 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
07-07 20:27:33.890  6487  6498 E DatabaseUtils: Writing exception to parcel
07-07 20:27:33.890  6487  6498 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
07-07 20:27:33.890  6487  6498 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
07-07 20:27:33.890  6552  6552 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
07-07 20:27:33.890  6552  6552 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
07-07 20:27:33.890   254   254 E lowmemorykiller: Error writing /proc/1692/oom_score_adj; errno=22
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:33.890  6552  6552 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-07 20:27:33.890  6552  6552 D AndroidRuntime: Shutting down VM
07-07 20:27:33.890  6552  6552 E AndroidRuntime: FATAL EXCEPTION: main
07-07 20:27:33.890  6552  6552 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 6552
07-07 20:27:33.890  6552  6552 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-07 20:27:33.890  6552  6552 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-07 20:27:33.890  6205  6532 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-07 20:27:33.890  6205  6532 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-07 20:27:33.890  1017  3006 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
07-07 20:27:33.890  6552  6552 I Process : Sending signal. PID: 6552 SIG: 9
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: Can't write: system_app_crash
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-07 20:27:33.900  1017  6591 E DropBoxManagerService: 	... 5 more
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: Exception thrown from onTableChanged
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.j(InternalIcingCorporaProvider.java:661)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.a(InternalIcingCorporaProvider.java:652)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.g(InternalIcingCorporaProvider.java:590)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:290)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.os.Looper.loop(Looper.java:145)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.b.amO(AppDataSearchDbOpenHelperBase.java:246)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.b.call(AppDataSearchDbOpenHelperBase.java:227)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
07-07 20:27:33.900  6205  6532 E AppDataSearchHelper: 	... 16 more
07-07 20:27:33.900  1017  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
07-07 20:27:33.900  6205  6532 W AppDataSearchHelper: Table change notification failed for com.google.android.gms.appdatasearch.a.k@be7fd6a1
07-07 20:27:33.900  1017  1544 W ActivityManager: userId = 0, bbcId = -10000
07-07 20:27:33.900  1017  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-07 20:27:33.900  1017  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-07 20:27:33.900  6520  6520 D [0]UMC:AdminManager: loadAdmins
07-07 20:27:33.900  6205  6532 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 297 ms] updated apps [took 297 ms] 
07-07 20:27:33.910  1017  1493 I ActivityManager: Killing 5565:com.google.android.apps.plus/u0a120 (adj 15): empty #31

```
