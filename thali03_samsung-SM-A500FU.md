#### Test 83070177a758936_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-12 13:50:06.797  6119  6119 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:50:06.797  6119  6119 D ActivityThread: Added TimaKeyStore provider
09-12 13:50:06.847  6119  6140 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
--------- beginning of system
09-12 13:50:06.847  1019  1555 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-12 13:50:06.847  1019  1555 I ActivityManager: Killing 4978:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
09-12 13:50:06.847  6119  6140 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-12 13:50:06.857  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:06.857  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:06.857  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:50:06.857  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:06.857  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:06.857  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-12 13:50:06.857  1019  1480 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-12 13:50:06.857  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-12 13:50:06.867  6119  6119 D AcmsService: Enter Oncreate
09-12 13:50:06.867  6119  6119 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:50:06.867  6119  6119 D AcmsService: creating AcmsCore
09-12 13:50:06.867  6119  6119 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-12 13:50:06.867  6119  6119 D AcmsCore: AcmsCore
09-12 13:50:06.867  6119  6119 D AcmsCore: init
09-12 13:50:06.867  6119  6119 D AcmsCore: Looper handler is not null
09-12 13:50:06.867  6119  6119 D AcmsCore: Post to AcmsCoreHandler
09-12 13:50:06.867  6119  6119 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:50:06.877  6119  6119 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-12 13:50:06.877  6119  6119 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-12 13:50:06.877  6119  6119 D AcmsService: onStartCommand
09-12 13:50:06.877  6119  6119 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-12 13:50:06.877  6119  6119 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-12 13:50:06.877  6119  6119 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-12 13:50:06.877  6119  6119 D AcmsService: Incremented Counter Value : onStartCommand
09-12 13:50:06.877  1019  1032 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-12 13:50:06.877  6119  6119 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-12 13:50:06.877  6119  6141 D AcmsCertificateMngr: AcmsCertificateMngr
09-12 13:50:06.897  6119  6141 D AcmsRevocationMngr: AcmsRevocationMngr
09-12 13:50:06.907  6119  6119 D AcmsService: Inside handle Intent
09-12 13:50:06.907  6119  6119 D AcmsService: App added - package name: com.test.thalitest
09-12 13:50:06.907  6119  6119 D AcmsCore: Post to AcmsCoreHandler
09-12 13:50:06.907  6119  6119 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:50:06.907  6119  6119 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-12 13:50:06.907  6119  6119 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-12 13:50:06.907  6119  6119 D AcmsService: Decremented Counter Value : handleStartIntent
09-12 13:50:06.907  6119  6119 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-12 13:50:06.917  3788  4255 I Icing   : Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
09-12 13:50:06.947  5880  5880 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
09-12 13:50:07.117  1019  1545 I art     : Explicit concurrent mark sweep GC freed 147851(8MB) AllocSpace objects, 4(1863KB) LOS objects, 33% free, 27MB/41MB, paused 2.500ms total 170.593ms
09-12 13:50:07.167  3788  4255 I Icing   : Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
09-12 13:50:07.347  3788  4255 I Icing   : Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
09-12 13:50:07.397  3788  4255 I Icing   : Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
09-12 13:50:07.417  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-12 13:50:07.417  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:07.417  1019  3141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:07.417  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:50:07.427  5782  5782 I Mms/MmsApp:  start initViewCache mms
09-12 13:50:07.427  5782  5782 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1933.604947
09-12 13:50:07.427  5782  5782 D Mms/ComposeMessageFragment: fillCache, easy = false
09-12 13:50:07.487  5782  5782 D AbsListView: Get MotionRecognitionManager
09-12 13:50:07.487  1019  1253 D MotionRecognitionService:  ssp status : false
09-12 13:50:07.497  5782  5782 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 68.083698
09-12 13:50:07.577  5782  5782 D Mms/BubbleViewCache: fillCache bubble = 1
,09-12 13:50:07.687  6119  6141 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
09-12 13:50:07.707  6119  6141 I AcmsKeyStoreHelper: Key Store exist
09-12 13:50:07.707  6119  6141 I AcmsKeyStoreHelper: Hence loading the keystore file
09-12 13:50:07.767  6119  6141 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-12 13:50:07.767  6119  6141 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-12 13:50:07.767  6119  6141 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-12 13:50:07.767  6119  6141 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:50:07.767  6119  6141 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-12 13:50:07.767  6119  6141 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
09-12 13:50:07.767  6119  6141 D AcmsCore: This is NOT a valid MirrorLink app
09-12 13:50:07.767  6119  6141 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-12 13:50:07.767  6119  6141 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-12 13:50:07.767  6119  6141 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-12 13:50:07.767  6119  6141 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
09-12 13:50:07.777  6119  6119 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-12 13:50:07.777  6119  6119 D AcmsService: Enter onDestroy
09-12 13:50:07.777  6119  6119 I AcmsService: cleanUp(): inside service clean up
09-12 13:50:07.777  6119  6119 D AcmsCore: AcmsCore: inside DeInit
09-12 13:50:07.777  6119  6119 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-12 13:50:07.777  6119  6119 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-12 13:50:07.777  6119  6119 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-12 13:50:07.777  6119  6119 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-12 13:50:07.777  6119  6119 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
09-12 13:50:07.777  6119  6119 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-12 13:50:07.777  6119  6119 D AcmsService: killing acms process
09-12 13:50:07.777  6119  6119 I Process : Sending signal. PID: 6119 SIG: 9
09-12 13:50:07.847  1019  5323 I ActivityManager: Process ACMS.Process (pid 6119)(adj 0) has died(50,1164)
09-12 13:50:07.857  6144  6144 D AndroidRuntime: 
09-12 13:50:07.857  6144  6144 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 13:50:07.857  6144  6144 D AndroidRuntime: CheckJNI is OFF
09-12 13:50:07.857  6144  6144 D AndroidRuntime: readGMSProperty: start
09-12 13:50:07.857  6144  6144 D AndroidRuntime: readGMSProperty: already setted!!
09-12 13:50:07.857  6144  6144 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 13:50:07.857  6144  6144 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 13:50:07.857  6144  6144 D AndroidRuntime: readGMSProperty: end
09-12 13:50:07.857  6144  6144 D AndroidRuntime: addProductProperty: start
09-12 13:50:07.997  6144  6144 E AffinityControl: AffinityControl: registerfunction enter
09-12 13:50:08.027  6144  6144 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 13:50:08.037  1019  3141 E PersonaManagerService: inState():  stateMachine is null !!
09-12 13:50:08.037  1019  3141 I PersonaManagerService: PersonaId don't exist
09-12 13:50:08.037  1019  3141 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-12 13:50:08.037  1019  3141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 13:50:08.047  1019  3141 W ActivityManager: mDVFSHelper.acquire()
09-12 13:50:08.057  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 13:50:08.057  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-12 13:50:08.057  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:08.057  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:08.057  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:08.057  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:08.067  6155  6155 E Zygote  : MountEmulatedStorage()
09-12 13:50:08.077  6155  6155 E Zygote  : v2
09-12 13:50:08.077  6155  6155 I libpersona: KNOX_SDCARD checking this for 10155
09-12 13:50:08.077  6155  6155 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:08.077  6155  6155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:50:08.077  1019  3141 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6155 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 13:50:08.077  1019  3141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-12 13:50:08.077  1019  3141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 13:50:08.077  1019  3141 D InputDispatcher: Focused application set to: xxxx
09-12 13:50:08.077  1019  3141 D InputDispatcher: Focus left window: 3142
09-12 13:50:08.077  6144  6144 D AndroidRuntime: Shutting down VM
09-12 13:50:08.077  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 13:50:08.077  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-12 13:50:08.077   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-12 13:50:08.077  6155  6155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:08.077  6155  6155 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-12 13:50:08.097  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:50:08.097  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
09-12 13:50:08.097  6155  6155 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:50:08.097  6155  6155 D ActivityThread: Added TimaKeyStore provider
09-12 13:50:08.107  1019  1019 V ActivityManager: Display changed displayId=0
09-12 13:50:08.117  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-12 13:50:08.127  1019  3139 D PersonaManager: isKioskContainerExistOnDevice
09-12 13:50:08.167   257   435 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
09-12 13:50:08.167   257  1836 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
09-12 13:50:08.177  3142  3142 V ActivityThread: updateVisibility : ActivityRecord{2d4efdb0 token=android.os.BinderProxy@d65b7c7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-12 13:50:08.237  6155  6155 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-12 13:50:08.247  6155  6155 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2975-2976)
09-12 13:50:08.247  6155  6155 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:50:08.267  6155  6155 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31a92e6c}
09-12 13:50:08.267  6155  6155 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:50:08.277  6155  6155 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:50:08.287  6144  6144 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-12 13:50:08.307  6155  6155 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,09-12 13:50:08.307  6155  6155 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:50:08.307  6155  6155 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-12 13:50:08.327  6155  6155 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-12 13:50:08.327  6155  6155 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-12 13:50:08.327  6155  6155 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-12 13:50:08.337  6155  6155 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-12 13:50:08.337  6155  6155 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:50:08.337  6155  6155 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:50:08.337  6155  6155 I Adreno-EGL: Local Branch: 
09-12 13:50:08.337  6155  6155 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:50:08.337  6155  6155 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:50:08.337  6155  6155 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 13:50:08.467  6155  6181 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-12 13:50:08.507  6155  6155 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:50:08.527  6155  6155 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 13:50:08.537  6155  6155 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-12 13:50:08.537  6155  6155 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-12 13:50:08.537  6155  6155 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-12 13:50:08.547  6155  6155 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:50:08.547  6155  6155 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:50:08.587  6155  6194 D OpenGLRenderer: Render dirty regions requested: true
,09-12 13:50:08.597  1019  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-12 13:50:08.597  1019  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 13:50:08.597  1019  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-12 13:50:08.597  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 13:50:08.597  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 13:50:08.607  6155  6155 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 13:50:08.607  6155  6155 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-12 13:50:08.617   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-12 13:50:08.627  1019  1547 D InputDispatcher: Focus entered window: 6155
,09-12 13:50:08.627  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-12 13:50:08.627  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
09-12 13:50:08.627  6155  6155 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-12 13:50:08.627  6155  6194 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 13:50:08.637  6155  6194 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-12 13:50:08.637  6155  6194 D OpenGLRenderer: Enabling debug mode 0
,09-12 13:50:08.667  6155  6155 V ActivityThread: updateVisibility : ActivityRecord{1f212c07 token=android.os.BinderProxy@14e3fe21 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-12 13:50:08.707  1019  3139 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 13:50:08.707  1019  6197 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 13:50:08.707  1182  1182 D PanelView: There is/are notification(s) 
,09-12 13:50:08.717  1802  1802 I SamsungIME: getCurrentCandidateView
,09-12 13:50:08.717  6155  6155 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-12 13:50:08.717  6155  6155 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@14e3fe21 time:103449
09-12 13:50:08.727  1019  1050 I ActivityManager: Displayed Component not be shown by security: +591ms (total +667ms)
09-12 13:50:08.727  1019  1050 W ActivityManager: mDVFSHelper.release()
09-12 13:50:08.727  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3146347f u0 com.test.thalitest/.MainActivity t128} time:103456
09-12 13:50:08.727   257  1836 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-12 13:50:08.727   257   444 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-12 13:50:08.777  6155  6155 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6155
,09-12 13:50:08.817  1802  1802 D SamsungIME: Dismiss ExpandCandiate
,09-12 13:50:08.897  6155  6155 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 13:50:08.947  1802  1802 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 13:50:08.987  1802  1802 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 13:50:08.997  1802  1802 I SamsungIME: KeybaordView init() : load resources
,09-12 13:50:09.017  6155  6198 D jxcore_app_log: JniHelper::setJavaVM(0xb8d9b328), pthread_self() = -1188040368
,09-12 13:50:09.027  1802  1802 I SamsungIME: getCurrentKeyboard
09-12 13:50:09.027  1802  1802 I SamsungIME: getTextKeyboard
,09-12 13:50:09.027  6155  6198 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 13:50:09.027  6155  6198 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 13:50:09.027  6155  6198 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 13:50:09.027  6155  6198 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 13:50:09.027  6155  6198 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-12 13:50:09.027  6155  6198 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@310724f7 added. We now have 1 listener(s)
,09-12 13:50:09.037  6155  6198 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-12 13:50:09.037  6155  6198 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 13:50:09.037  6155  6198 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:09.037  6155  6198 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:09.037  1802  1802 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 13:50:09.047  6155  6198 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cd1ae82 added. We now have 1 listener(s)
09-12 13:50:09.047  6155  6198 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:50:09.047  6155  6198 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:50:09.047  6155  6198 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 13:50:09.047  6155  6198 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 13:50:09.047  6155  6198 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 13:50:09.047  6155  6198 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 13:50:09.057  6155  6198 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:09.057  6155  6198 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-12 13:50:09.067  6155  6198 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 13:50:09.067  6155  6198 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:09.067  6155  6198 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:09.067  6155  6198 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:09.067  6155  6198 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:09.067  6155  6198 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:09.067  6155  6198 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:09.067  6155  6198 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:50:09.067  6155  6198 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:50:09.067  6155  6198 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 13:50:09.067  6155  6198 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:50:09.067  6155  6198 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:50:09.067  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:09.077  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:09.087   287   287 E SMD     : DCD OFF
,09-12 13:50:09.117  6155  6155 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 13:50:09.557  1802  6203 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-12 13:50:09.647  6155  6207 W jxcore-log: Initializing JXcore engine
09-12 13:50:09.647  6155  6207 W jxcore-log: JXcore engine is ready
,09-12 13:50:09.707  1907  1907 E audit   : type=1400 msg=audit(1473681009.707:205): avc:  denied  { ioctl } for  pid=6207 comm="Thread-1068" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-12 13:50:09.707  1907  1907 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:09.707  1907  1907 E audit   : type=1300 msg=audit(1473681009.707:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e7048f8 items=0 ppid=317 ppcomm=main pid=6207 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1068" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-12 13:50:09.707  1907  1907 E audit   : type=1320 msg=audit(1473681009.707:205): 
,09-12 13:50:09.727  6155  6207 W jxcore-log: Starting JXcore engine
,09-12 13:50:09.837  6155  6207 W jxcore-log: Platform android,
09-12 13:50:09.837  6155  6207 W jxcore-log: 
09-12 13:50:09.837  6155  6207 W jxcore-log: Process ARCH arm
09-12 13:50:09.837  6155  6207 W jxcore-log: 
,09-12 13:50:10.047  6155  6207 I jxcore-log: JXcore Cordova bridge is ready!
09-12 13:50:10.047  6155  6207 I jxcore-log: 
,09-12 13:50:10.047  6155  6207 W jxcore-log: JXcore engine is started
,09-12 13:50:10.047  6155  6198 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 13:50:10.057  6155  6155 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 13:50:11.257  1019  3132 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:50:11.257  1019  3132 D BatteryService: level:87, scale:100, status:2, health:2, present:true, voltage: 4125, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-12 13:50:11.257  1019  3132 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 13:50:11.257  1019  3132 D BatteryService: stay LED for charging
09-12 13:50:11.257  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:50:11.267  1019  1019 I MotionRecognitionService: Plugged
,09-12 13:50:11.267  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:50:11.267  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:50:11.267  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:50:11.267  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:50:11.267  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 87
,09-12 13:50:11.287  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:50:11.287  2641  2711 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:50:11.297  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:11.297  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:11.297  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:11.417  1019  5323 D ActivityManager: bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-12 13:50:11.417  1019  5323 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-12 13:50:11.417  1019  5323 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:11.417  1019  5323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:11.417  1019  5323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,09-12 13:50:12.097   287   287 E SMD     : DCD OFF
,09-12 13:50:12.747  1019  1052 I PowerManagerService: [PWL] Off : 30s ago
,09-12 13:50:12.767  1019  1098 V AlarmManager: waitForAlarm result :4
,09-12 13:50:12.817  1019  2712 D SSRM:n  : SIOP:: AP = 400
,09-12 13:50:13.397  1019  1342 E Watchdog: !@Sync 3,
,09-12 13:50:14.077   331   331 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-12 13:50:14.077   331   331 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-12 13:50:15.097   287   287 E SMD     : DCD OFF
,09-12 13:50:16.057  1019  1060 D PackageManager: [MSG] MCS_UNBIND
,09-12 13:50:16.067  1019  1126 I ActivityManager: Killing 4416:com.google.android.music:main/u0a111 (adj 15): empty #31
,09-12 13:50:18.067  1019  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-12 13:50:18.097   287   287 E SMD     : DCD OFF
,09-12 13:50:18.217  5370  5370 D FactoryTest: Not factory mode
,09-12 13:50:18.217  5370  5370 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-12 13:50:18.227  5370  5370 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-12 13:50:18.227  5370  5370 D MTPRx   : still no open session command from host, so toast
09-12 13:50:18.227  5370  5370 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-12 13:50:18.227  5370  5370 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-12 13:50:18.227  5370  5370 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:112952
09-12 13:50:18.227  1019  1545 E PersonaManagerService: inState():  stateMachine is null !!
,09-12 13:50:18.227  1019  1545 I PersonaManagerService: PersonaId don't exist
09-12 13:50:18.227  1019  1545 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-12 13:50:18.227  1019  1545 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-12 13:50:18.227  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:18.227  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:18.227  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-12 13:50:18.237  1019  1545 W ActivityManager: mDVFSHelper.acquire()
,09-12 13:50:18.247  1019  1545 I ActivityManager: Killing 5326:com.dropbox.android/u0a92 (adj 15): empty #31
,09-12 13:50:18.257  1019  1545 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:50:18.267  1019  1545 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 13:50:18.267  1019  1545 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 13:50:18.267  1019  1545 D InputDispatcher: Focused application set to: xxxx
09-12 13:50:18.267  1019  1545 D InputDispatcher: Focus left window: 6155
,09-12 13:50:18.267  5370  5370 E MTPRx   : started activity for popup
,09-12 13:50:18.267  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:50:18.267  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:50:18.297  5370  5370 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-12 13:50:18.297  5370  5370 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 13:50:18.297  5370  5370 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:50:18.297  5370  5370 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:50:18.297  5370  5370 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:18.297  5370  5370 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:50:18.317  5370  5370 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-12 13:50:18.317  1019  1126 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-12 13:50:18.317  1019  1126 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 13:50:18.317  1019  1126 D InputDispatcher: Focused application set to: xxxx
09-12 13:50:18.317  1019  1126 D InputDispatcher: Focus entered window: 6155
,09-12 13:50:18.317  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:50:18.317  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:50:18.317  1019  3141 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 13:50:18.327  1019  3141 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@31f63f6b attribute=null, token = android.os.BinderProxy@318a96fe
,09-12 13:50:18.357  5370  5370 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-12 13:50:18.367  5370  5370 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-12 13:50:18.367  5370  5370 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-12 13:50:18.387  6155  6155 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:50:18.387  6155  6155 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-12 13:50:18.387  6155  6155 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
09-12 13:50:18.387  6155  6155 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
09-12 13:50:18.387  1019  1547 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-12 13:50:18.387  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
09-12 13:50:18.387  1019  1547 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 13:50:18.387  1019  1547 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-12 13:50:18.387  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-12 13:50:18.407  6155  6155 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:50:18.407  6155  6155 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 13:50:18.407  6155  6155 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@78b0a9c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@25823304, 16908290=android.view.AbsSavedState$1@25823304}, android:focusedViewId=100}]}]
09-12 13:50:18.407  6155  6155 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 13:50:18.417  6155  6155 V ActivityThread: updateVisibility : ActivityRecord{1f212c07 token=android.os.BinderProxy@14e3fe21 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-12 13:50:18.417  6155  6155 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 13:50:18.417  6155  6155 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 13:50:18.417  6155  6155 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@14e3fe21 time:113140
,09-12 13:50:18.417  1019  1032 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:50:19.077   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:50:20.077   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:50:20.137  1019  1045 I ActivityManager: Waited long enough for: ServiceRecord{2f6d7392 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,09-12 13:50:21.077   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:50:21.097   287   287 E SMD     : DCD OFF
,09-12 13:50:21.237  1019  1045 W ActivityManager: mDVFSHelper.release()
,09-12 13:50:21.317  1019  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:50:21.317  1019  1547 D BatteryService: level:87, scale:100, status:2, health:2, present:true, voltage: 4130, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-12 13:50:21.317  1019  1547 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 13:50:21.317  1019  1547 D BatteryService: stay LED for charging
,09-12 13:50:21.317  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:50:21.317  1019  1019 I MotionRecognitionService: Plugged
,09-12 13:50:21.317  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:50:21.327  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:50:21.327  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:50:21.327  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:50:21.327  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 87
,09-12 13:50:21.337  2641  2641 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:50:21.337  2641  2711 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:50:21.347  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:21.347  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:21.347  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:21.787  1019  2761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-12 13:50:22.077   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:50:22.227  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-12 13:50:22.227  6155  6207 I jxcore-log: 
,09-12 13:50:22.227  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-12 13:50:22.227  6155  6207 I jxcore-log: 
,09-12 13:50:22.237  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,09-12 13:50:22.237  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:22.237  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:22.237  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:22.237  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:22.237  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:22.237  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:50:22.237  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:50:22.237  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:50:22.237  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 13:50:22.237  6155  6207 I jxcore-log: 
09-12 13:50:22.237  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 13:50:22.237  6155  6207 I jxcore-log: 
,09-12 13:50:22.837  1019  2712 D SSRM:n  : SIOP:: AP = 400
,09-12 13:50:22.887  6155  6207 D executeNativeTests: Running unit tests
,09-12 13:50:22.967  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:22.967  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d added. We now have 2 listener(s)
,09-12 13:50:22.967  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:50:22.967  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:22.967  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:22.967  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:22.967  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 added. We now have 2 listener(s)
09-12 13:50:22.967  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:50:22.967  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:50:22.977  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:22.977  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:22.977  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:22.977  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:22.977  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:22.977  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:22.977  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:22.977  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:50:22.977  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:50:22.977  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:50:22.977  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:50:22.977  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:22.977  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:50:22.977  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:50:22.977  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:50:22.987  6155  6207 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-12 13:50:22.987  6155  6207 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:50:22.987  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:50:22.987  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:50:22.987  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:22.987  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:22.987  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:22.987  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:22.987  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:22.987  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d removed from the list
09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:22.987  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 removed from the list
,09-12 13:50:22.987  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:22.987  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:22.987  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:22.987  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:22.987  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:22.987  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
,09-12 13:50:22.987  6155  6207 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 13:50:22.987  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:22.987  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:22.987  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:22.987  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:22.987  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:22.987  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:22.987  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:22.987  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:22.987  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:22.987  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:22.987  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:22.987  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:22.987  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:22.997  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:22.997  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:22.997  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:22.997  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
,09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:50:22.997  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:22.997  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:50:22.997  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:22.997  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:22.997  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:22.997  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:22.997  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list,
09-12 13:50:22.997  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:22.997  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:22.997  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:22.997  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:22.997  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:22.997  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 13:50:22.997  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.007  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:50:23.007  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.007  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.007  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.007  6155  6207 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:50:23.007  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:23.007  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:23.007  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:23.007  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:23.007  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:23.007  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:23.007  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:23.007  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:50:23.007  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:50:23.007  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:50:23.007  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:50:23.007  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:50:23.007  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:50:23.007  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:50:23.007  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:50:23.007  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:50:23.017  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.017  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:50:23.017  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.017  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:50:23.027  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:50:23.027  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 13:50:23.027  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-12 13:50:23.027  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:50:23.027  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:50:23.027  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:50:23.047  2641  2651 D BtGatt.GattService: registerClient() - UUID=f2d65013-fc92-4d22-9989-bb76cf1a4c31
,09-12 13:50:23.077   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:50:23.087  2641  2706 D BtGatt.GattService: onClientRegistered() - UUID=f2d65013-fc92-4d22-9989-bb76cf1a4c31, clientIf=6
,09-12 13:50:23.087  6155  6164 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:50:23.087  2641  2650 D BtGatt.GattService: start scan with filters
,09-12 13:50:23.097  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:50:23.097  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:50:23.097  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:50:23.097  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:50:23.097  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:23.097  2641  2709 D BtGatt.ScanManager: handling starting scan
,09-12 13:50:23.097  2641  2709 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
,09-12 13:50:23.107  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:23.107  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:50:23.117  2641  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 13:50:23.117  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:50:23.117  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.117  2641  2709 D BtGatt.ScanManager: allow scan with filters
09-12 13:50:23.117  2641  2709 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 13:50:23.117  2641  2709 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-12 13:50:23.117  6155  6207 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:50:23.127  2641  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:50:23.127  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.127  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:23.127  6155  6207 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:50:23.127  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.127  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:50:23.127  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:50:23.127  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:50:23.127  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:50:23.127  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:50:23.127  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:50:23.127  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:50:23.127  2641  2709 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:50:23.127  2641  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 13:50:23.127  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:50:23.127  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:50:23.127  2641  2650 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:50:23.127  2641  2651 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:50:23.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:50:23.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:50:23.137  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:50:23.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:50:23.137  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:50:23.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:23.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:50:23.137  2641  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 13:50:23.137  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:23.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:50:23.137  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:50:23.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:23.147  2641  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:50:23.147  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.147  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.147  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.147  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:50:23.147  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.147  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.147  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.147  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.147  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.147  6155  6207 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:50:23.147  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:23.147  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:23.147  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:23.147  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:23.157  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:23.157  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:23.157  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:23.157  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:23.157  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:23.157  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:23.157  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:50:23.157  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:50:23.157  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:50:23.157  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:50:23.167  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:50:23.167  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:50:23.167  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:50:23.167  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:50:23.167  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:50:23.167  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.167  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.167  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:50:23.177  2641  2709 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 39
,09-12 13:50:23.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:50:23.177  2641  2709 D BtGatt.ScanManager: filter size is 1
09-12 13:50:23.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:50:23.177  2641  2709 D BtGatt.ScanManager: delete FilterIndex - 3,
09-12 13:50:23.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-12 13:50:23.177  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:50:23.177  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:50:23.187  2641  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 13:50:23.187  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.187  2641  2709 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:50:23.187  2641  2651 D BtGatt.GattService: registerClient() - UUID=01c77a54-5c38-4bbd-a485-452fe0256441
,09-12 13:50:23.197  2641  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 13:50:23.197  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.197  2641  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:50:23.207  2641  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:50:23.207  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.227  2641  2706 D BtGatt.GattService: onClientRegistered() - UUID=01c77a54-5c38-4bbd-a485-452fe0256441, clientIf=6
,09-12 13:50:23.227  6155  6163 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:50:23.227  2641  2872 D BtGatt.GattService: start scan with filters
,09-12 13:50:23.237  2641  2709 D BtGatt.ScanManager: handling starting scan
,09-12 13:50:23.237  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:50:23.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:50:23.237  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:50:23.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:50:23.237  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:23.237  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:23.237  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:50:23.247  2641  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-12 13:50:23.247  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:23.247  2641  2709 D BtGatt.ScanManager: allow scan with filters
09-12 13:50:23.247  2641  2709 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 13:50:23.247  2641  2709 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-12 13:50:23.247  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:50:23.247  2641  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:50:23.247  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.247  2641  2709 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:50:23.247  2641  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 13:50:23.247  6155  6207 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:50:23.257  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:50:23.257  2641  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 13:50:23.257  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.257  6155  6207 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:50:23.257  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:50:23.257  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:50:23.257  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.257  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:50:23.257  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:50:23.257  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:50:23.257  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:50:23.267  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:50:23.267  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:50:23.267  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:50:23.267  2641  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 13:50:23.267  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.267  2641  2650 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:50:23.267  2641  2651 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:50:23.277  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:50:23.277  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:50:23.277  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:50:23.277  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:50:23.277  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:50:23.277  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:23.277  2641  2709 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 40
,09-12 13:50:23.277  2641  2709 D BtGatt.ScanManager: filter size is 1
,09-12 13:50:23.277  2641  2709 D BtGatt.ScanManager: delete FilterIndex - 4
,09-12 13:50:23.287  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:50:23.287  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:50:23.287  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:50:23.287  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:23.287  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:50:23.287  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:50:23.287  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:23.287  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:50:23.287  2641  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 13:50:23.287  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.287  2641  2709 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:50:23.287  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:50:23.287  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:23.287  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.287  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.287  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
,09-12 13:50:23.297  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.297  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:23.297  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:50:23.297  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:23.297  2641  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 13:50:23.297  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.297  2641  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:50:23.297  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:50:23.297  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:50:23.297  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.297  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
,09-12 13:50:23.297  2641  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:50:23.307  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:23.307  6155  6207 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:50:23.307  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:23.307  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:23.307  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:23.307  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:23.307  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:23.307  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:23.307  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:23.307  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:50:23.307  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:50:23.307  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:50:23.307  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:50:23.317  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:50:23.317  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:50:23.317  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:50:23.317  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:50:23.317  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:50:23.317  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.317  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.317  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:50:23.327  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:50:23.327  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:50:23.327  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:50:23.327  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:50:23.327  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:50:23.337  2641  2872 D BtGatt.GattService: registerClient() - UUID=1369020f-b1ab-44ce-b242-d3d51b41bae6
,09-12 13:50:23.377  2641  2706 D BtGatt.GattService: onClientRegistered() - UUID=1369020f-b1ab-44ce-b242-d3d51b41bae6, clientIf=6
,09-12 13:50:23.377  6155  6164 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:50:23.377  2641  2873 D BtGatt.GattService: start scan with filters
,09-12 13:50:23.377  2641  2709 D BtGatt.ScanManager: handling starting scan
09-12 13:50:23.377  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 13:50:23.377  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:50:23.377  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:50:23.377  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:50:23.387  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:23.387  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:50:23.387  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:50:23.387  2641  2706 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 13:50:23.387  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.387  2641  2709 D BtGatt.ScanManager: allow scan with filters
09-12 13:50:23.387  2641  2709 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 13:50:23.387  2641  2709 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-12 13:50:23.387  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:50:23.387  2641  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:50:23.387  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.387  2641  2709 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:50:23.387  2641  2709 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 13:50:23.397  6155  6207 I io.jxcore.node.ConnectionHelper: start: OK
09-12 13:50:23.397  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.397  6155  6207 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:50:23.397  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.397  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:50:23.397  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.397  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:50:23.397  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:50:23.397  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:50:23.397  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:50:23.397  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:50:23.397  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:50:23.397  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:50:23.397  2641  2872 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:50:23.397  2641  2873 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:50:23.397  2641  2706 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 13:50:23.397  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.407  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:50:23.407  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:50:23.407  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:50:23.407  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 13:50:23.407  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:50:23.407  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:23.407  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:50:23.407  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:50:23.407  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:50:23.407  2641  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:50:23.407  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:23.417  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:23.417  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:50:23.417  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:23.417  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:23.417  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.417  6155  6207 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:50:23.417  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.417  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.417  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.417  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.417  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:50:23.417  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.417  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.417  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.417  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.417  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.417  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.417  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:23.417  2641  2709 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 41
,09-12 13:50:23.427  2641  2709 D BtGatt.ScanManager: filter size is 1
09-12 13:50:23.427  2641  2709 D BtGatt.ScanManager: delete FilterIndex - 5
,09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
,09-12 13:50:23.427  6155  6207 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 13:50:23.427  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:50:23.427  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.427  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.427  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.427  2641  2706 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 13:50:23.427  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:23.427  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:50:23.427  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.427  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.427  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.427  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:23.427  2641  2709 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.427  6155  6207 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 13:50:23.427  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.427  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.427  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.427  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.427  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.427  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.427  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.427  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.437  6155  6207 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 13:50:23.437  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.437  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.437  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.437  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.437  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.437  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.437  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.437  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.437  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.437  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.437  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.437  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.437  2641  2706 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 13:50:23.437  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:23.437  2641  2709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.437  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:50:23.437  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:50:23.437  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:50:23.437  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:50:23.437  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.437  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.437  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.437  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.437  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.437  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.437  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.437  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.437  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.437  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.437  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.437  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.437  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.447  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.447  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.447  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.447  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.447  2641  2706 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 13:50:23.447  6155  6207 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:50:23.447  6155  6207 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:50:23.447  2641  2706 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:23.447  6155  6207 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:50:23.447  6155  6207 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:50:23.447  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:50:23.447  6155  6207 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 13:50:23.447  6155  6207 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:50:23.447  6155  6207 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 13:50:23.447  6155  6207 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:50:23.447  6155  6207 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:50:23.447  6155  6207 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 13:50:23.447  6155  6207 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:50:23.447  6155  6207 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:50:23.447  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 13:50:23.457  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 13:50:23.457  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 13:50:23.457  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 13:50:23.457  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 13:50:23.457  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 13:50:23.457  6155  6207 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 13:50:23.457  6155  6207 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:50:23.457  6155  6207 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 13:50:23.457  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.457  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.457  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.457  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.457  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.457  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.457  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 13:50:23.457  6155  6224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1132)
09-12 13:50:23.457  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.457  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.457  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.457  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.457  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.457  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.457  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.457  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.457  6155  6225 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1132
,09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.467  6155  6207 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 13:50:23.467  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.467  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.467  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.467  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.467  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.467  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.467  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.467  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.467  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.467  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.467  6155  6207 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 13:50:23.467  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.467  6155  6224 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-12 13:50:23.467  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.467  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.467  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.467  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.467  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.467  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.467  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.467  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.467  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.467  6155  6207 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 13:50:23.467  6155  6207 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 13:50:23.467  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:50:23.467  6155  6207 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 13:50:23.467  6155  6207 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:50:23.467  6155  6207 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 13:50:23.467  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:50:23.467  6155  6207 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 13:50:23.467  6155  6207 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:50:23.467  6155  6207 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:50:23.467  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:50:23.467  6155  6207 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 13:50:23.467  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.467  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.467  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.467  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.467  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.467  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.467  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.477  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.477  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.477  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.477  6155  6224 D BluetoothSocket: connect(): myUserId = 0
09-12 13:50:23.477  6155  6224 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.477  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.477  2641  2650 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.477  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.477  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.477  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.477  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.477  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.477  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.477  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.477  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.477  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.477  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.477  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.477  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.477  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.477  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.477  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.477  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.477  6155  6224 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-12 13:50:23.477  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.477  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.477  6155  6207 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:50:23.477  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:50:23.487  6155  6155 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:50:23.487  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:50:23.487  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.487  6155  6155 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:50:23.487  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.487  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.487  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.487  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.487  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.487  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.487  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.487  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.487  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.487  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.487  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:50:23.487  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.487  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.487  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.487  6155  6226 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:50:23.487  6155  6226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:50:23.487  6155  6207 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 13:50:23.487  6155  6207 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:50:23.487  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:50:23.487  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.487  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.487  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.487  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.487  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.487  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.487  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.487  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.487  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.487  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.487  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.487  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.487  6155  6226 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
09-12 13:50:23.487  6155  6226 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:50:23.487  6155  6226 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:50:23.487  6155  6226 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d7b8364
09-12 13:50:23.487  6155  6226 D BluetoothSocket: channel: 6
09-12 13:50:23.487  6155  6226 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@22f799cd, channel: 6, state: LISTENING
09-12 13:50:23.487  6155  6226 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@22f799cd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d7b8364, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15d72282mSocket: android.net.LocalSocket@ba97d93 impl:android.net.LocalSocketImpl@e1f71d0 fd:FileDescriptor[108]
09-12 13:50:23.487  6155  6226 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ba97d93 impl:android.net.LocalSocketImpl@e1f71d0 fd:FileDescriptor[108]
09-12 13:50:23.487  6155  6226 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:50:23.487  6155  6226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:50:23.487  6155  6226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:50:23.487  6155  6155 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:50:23.497  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.497  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.497  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.497  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does, not exist in the list - probably already removed
09-12 13:50:23.497  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.497  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.497  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.497  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.497  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.497  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.497  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.497  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.497  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:23.497  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:23.497  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:23.497  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.497  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.497  6155  6207 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c0b1f5d not in the list
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.497  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:23.497  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.497  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.497  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:23.497  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:23.497  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:23.497  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3338e0d2 not in the list
09-12 13:50:23.497  6155  6207 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:50:23.497  6155  6207 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:50:23.497  6155  6207 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 13:50:23.497  6155  6207 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:50:23.497  6155  6207 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:50:23.497  6155  6207 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 13:50:23.497  6155  6207 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 13:50:23.497  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:23.497  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ef105c9 added. We now have 2 listener(s),
09-12 13:50:23.497  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:23.507  6155  6207 D BluetoothAdapter: enable()
09-12 13:50:23.507  6155  6207 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 13:50:23.507  1019  1555 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:50:23.507  1019  1555 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:50:23.507  1019  1555 D SecContentProvider2: mCursor = null
09-12 13:50:23.507  1019  1555 D WifiService: setWifiEnabled: true pid=6155, uid=10155
09-12 13:50:23.507  1019  1555 W ActivityManager: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:50:23.507  1019  1555 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:50:23.507  1019  1555 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:50:23.507  1019  1555 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:50:23.507  1019  1555 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:50:23.507  1019  1555 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:50:23.507  1019  1555 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:50:23.507  1019  1555 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:50:23.507  1019  1555 D SettingsProvider: name = wifi_on
09-12 13:50:23.507  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:23.507  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ed8e4ce added. We now have 3 listener(s)
09-12 13:50:23.507  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:23.517  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:23.517  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d645fef added. We now have 4 listener(s)
09-12 13:50:23.517  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:23.517  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:23.517  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ad1dafc added. We now have 5 listener(s)
09-12 13:50:23.517  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:23.517  1019  1321 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:50:23.517  1019  1321 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:50:23.517  1019  1321 D SecContentProvider2: mCursor = null
09-12 13:50:23.517  1019  1321 D WifiService: setWifiEnabled: false pid=6155, uid=10155
09-12 13:50:23.517  1019  1321 D SettingsProvider: name = wifi_on
09-12 13:50:23.527  6155  6207 D BluetoothAdapter: disable()
09-12 13:50:23.527  1019  1547 D SettingsProvider: name = bluetooth_on
09-12 13:50:23.527  1019  1131 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 13:50:23.527  2107  2107 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 13:50:23.527  2107  2107 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-12 13:50:23,.527  2107  2107 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:50:23.527  2107  2107 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-12 13:50:23.527  1019  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:50:23.537  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:50:23.537  2641  2703 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-12 13:50:23.537  2641  2703 D BluetoothAdapterProperties: Setting state to 13
09-12 13:50:23.537  2641  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:50:23.537  2641  2703 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:50:23.537  2641  2703 D BluetoothAdapterService: updateAdapterState state is 13
09-12 13:50:23.537  1019  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:23.537  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-12 13:50:23.537  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:23.537  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:23.537  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:23.547  2641  2641 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
09-12 13:50:23.547  2641  2703 D BluetoothAdapterService: Autoconnection is available 
09-12 13:50:23.547  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-12 13:50:23.547  2641  2703 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 13:50:23.547  2641  2703 D BluetoothAdapterService: terminating service from this receiver
09-12 13:50:23.547  2641  2641 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2230697e, channel: 19, state: LISTENING
09-12 13:50:23.547  2641  2641 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2230697e, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f5c96e8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24357edfmSocket: android.net.LocalSocket@36e9272c impl:android.net.LocalSocketImpl@233d45f5 fd:FileDescriptor[74]
,09-12 13:50:23.547  2641  2641 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36e9272c impl:android.net.LocalSocketImpl@233d45f5 fd:FileDescriptor[74]
09-12 13:50:23.547  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:23.547  1019  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:23.547  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:50:23.547  1295  1295 D BluetoothPbap: Proxy object disconnected
09-12 13:50:23.547  1295  1295 D PbapServerProfile: Bluetooth service disconnected
,09-12 13:50:23.547  2641  2703 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:50:23.547  2641  2703 D BluetoothAdapterProperties: mDiscovering is false
09-12 13:50:23.547  1019  1131 E WifiNative-wlan0: do suspend true
,09-12 13:50:23.547  1019  3141 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 13:50:23.547  2641  2703 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 13:50:23.547  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:23.557  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-12 13:50:23.557  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:50:23.557  2641  2706 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:50:23.557  2641  2706 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:50:23.557  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:23.557  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:23.557  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:23.557  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:23.557  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:23.557  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:23.557  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:50:23.557  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:50:23.567  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:23.567  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:50:23.567  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:50:23.567  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:50:23.567  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:50:23.567  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:23.567  1182  1182 D BluetoothTile:  getBluetoothState : 13
,09-12 13:50:23.567  1802  1802 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:50:23.567  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:23.567  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.567  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.567  1295  1295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:23.577  1019  1126 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:23.577  1019  1479 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:50:23.577  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:23.577  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:23.577  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:50:23.577  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:50:23.577  2641  2703 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 13:50:23.577  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:50:23.577  2641  2703 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-12 13:50:23.577  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-12 13:50:23.587  2641  2703 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-12 13:50:23.587  2641  2703 E bt-btif : cmd socket is not created
09-12 13:50:23.587  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:50:23.587  2641  2766 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-12 13:50:23.587  2641  2766 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 13:50:23.587  2641  2703 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 13:50:23.587  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:23.587  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:23.587  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:50:23.587  6155  6224 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d227fda, channel: -1, state: INIT
09-12 13:50:23.587  6155  6224 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d227fda, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37410c0b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33dfaae8mSocket: android.net.LocalSocket@13bea501 impl:android.net.LocalSocketImpl@1e38bfa6 fd:FileDescriptor[106]
09-12 13:50:23.587  6155  6224 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@13bea501 impl:android.net.LocalSocketImpl@1e38bfa6 fd:FileDescriptor[106]
09-12 13:50:23.587  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:23.587  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:50:23.587  6155  6224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1132)
,09-12 13:50:23.587  2641  4955 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 13:50:23.587  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.597  2641  2766 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:50:23.597  2641  2766 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:50:23.597  2641  2766 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 13:50:23.597  2641  2641 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@131d29fb, channel: 5, state: LISTENING
09-12 13:50:23.597  2641  2641 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@131d29fb, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@219539e7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39578a18mSocket: android.net.LocalSocket@3ce94c71 impl:android.net.LocalSocketImpl@15062a56 fd:FileDescriptor[76]
09-12 13:50:23.597  2641  2641 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ce94c71 impl:android.net.LocalSocketImpl@15062a56 fd:FileDescriptor[76]
09-12 13:50:23.597  1295  1295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:50:23.597  2641  2641 I BtOppRfcommListener: stopping Accept Thread
09-12 13:50:23.597  2641  2641 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@290a6ad7, channel: 12, state: LISTENING
09-12 13:50:23.597  2641  2641 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@290a6ad7, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a75ef39, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f472fc4mSocket: android.net.LocalSocket@37753ead impl:android.net.LocalSocketImpl@3cd295e2 fd:FileDescriptor[79]
09-12 13:50:23.597  2641  2641 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37753ead impl:android.net.LocalSocketImpl@3cd295e2 fd:FileDescriptor[79]
09-12 13:50:23.597  1019  3141 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 13:50:23.597  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:50:23.597  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:50:23.597  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:23.597  1019  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:23.597  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-12 13:50:23.597  2641  4955 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:50:23.607  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:23.607  2641  2641 V BluetoothOppManager: cleanUp...
,09-12 13:50:23.607  1295  1295 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:50:23.617  1295  1295 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:50:23.617  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:23.617  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 13:50:23.627  1019  1555 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-12 13:50:23.627  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:23.627  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:23.627  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:23.627  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:23.647  6232  6232 E Zygote  : MountEmulatedStorage()
09-12 13:50:23.647  6232  6232 E Zygote  : v2
09-12 13:50:23.647  6232  6232 I libpersona: KNOX_SDCARD checking this for 10003
09-12 13:50:23.647  6232  6232 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:23.647  1019  1555 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6232 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-12 13:50:23.647  6232  6232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:50:23.647  6232  6232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:23.657  6232  6232 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:50:23.667   317   317 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 22.864ms
,09-12 13:50:23.677  6232  6232 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:23.677  6232  6232 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:23.687   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.198ms
,09-12 13:50:23.697   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.961ms,
,09-12 13:50:23.707  6232  6232 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-12 13:50:23.747  6232  6232 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-12 13:50:23.747  6232  6232 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-12 13:50:23.747  6232  6232 D UserAnalysis: Create SecureDbHelper
,09-12 13:50:23.747  6232  6232 D IntelligenceServiceApplication: onCreate()
,09-12 13:50:23.757  1019  3139 I ActivityManager: Killing 5272:com.google.android.talk/u0a104 (adj 15): empty #31
,09-12 13:50:23.757  1019  1555 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-12 13:50:23.757  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:23.757  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:23.757  6232  6232 D IntelligenceServiceApplication: no applications having user consent for prediction
09-12 13:50:23.757  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:23.767  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:23.777  6250  6250 E Zygote  : MountEmulatedStorage(),
09-12 13:50:23.777  6250  6250 E Zygote  : v2
,09-12 13:50:23.777  6250  6250 I libpersona: KNOX_SDCARD checking this for 10107
09-12 13:50:23.777  6250  6250 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:23.777  6250  6250 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:23.777  6250  6250 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-12 13:50:23.777  1019  1555 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6250 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-12 13:50:23.777  1019  1126 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
09-12 13:50:23.777  6250  6250 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 13:50:23.777  6232  6232 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-12 13:50:23.787  2641  2766 W bt-l2cap: btif_mce_execute_service enable:0
09-12 13:50:23.787  2641  2766 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:50:23.787  2641  2766 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:50:23.787  2641  2766 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:50:23.787  2641  2766 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:50:23.787  2641  2766 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:50:23.787  2641  2766 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:50:23.787  2641  2766 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:50:23.787  2641  2766 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:50:23.787  2641  2766 W bt-btif : ag scb idx 1 not allocated
09-12 13:50:23.787  2641  2766 W bt-btif : ag scb idx 2 not allocated
09-12 13:50:23.787  2641  2766 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 13:50:23.787  2641  2821 I bt_userial_mct: exiting userial_read_thread
09-12 13:50:23.787  2641  2821 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 13:50:23.787  2641  2706 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 13:50:23.787  2641  2768 I bt_vendor: hw_epilog_process
09-12 13:50:23.787  2641  2706 D bt_userial_mct: userial_close
09-12 13:50:23.787  2641  2706 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 13:50:23.787  6232  6232 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 13:50:23.797  6250  6250 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:23.797  6250  6250 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:23.867  2107  2107 I wpa_supplicant: nl80211: Received scan results (16 BSSes),
,09-12 13:50:23.877  1019  1130 D WifiP2pService: InactiveState{ what=147461 }
,09-12 13:50:23.877  1019  1130 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-12 13:50:23.877  1019  1130 D WifiP2pService: DefaultState{ what=147461 }
,09-12 13:50:23.877   277   996 D CommandListener: Clearing all IP addresses on wlan0,
09-12 13:50:23.877  1019  1130 D WifiP2pService: InactiveState{ what=143375 }
09-12 13:50:23.877  1019  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
09-12 13:50:23.887  1914  4332 V NativeCrypto: Read error: ssl=0xb92a3d38: I/O error during system call, Connection timed out
,09-12 13:50:23.887  1019  1133 E ConnectivityService: updateNetworkInfo()
09-12 13:50:23.887  1019  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:50:23.887  1019  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-12 13:50:23.887  1914  4332 V NativeCrypto: SSL shutdown failed: ssl=0xb92a3d38: I/O error during system call, Broken pipe
,09-12 13:50:23.887  1914  4332 E GCM     : Wifi connection closed with errorCode 20
,09-12 13:50:23.887  1019  1545 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,09-12 13:50:23.887  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:23.887  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:50:23.887  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.887  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.887  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:23.887  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.897  1019  2220 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:23.897  1019  2220 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:23.897  1019  2220 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:50:23.897  1019  2220 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:23.897  1019  2220 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-12 13:50:23.897  1019  2220 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:50:23.897  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 13:50:23.897  1019  2220 I qtaguid : Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1019, getuid(): 1000
,09-12 13:50:23.897  1019  2220 I qtaguid : Untagging socket 360
,09-12 13:50:23.907  1019  2220 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:50:23.907  1019  1130 D WifiP2pService: InactiveState{ what=131204 }
09-12 13:50:23.907  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:23.907  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:23.907  1019  1130 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 13:50:23.907  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:23.907  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
,09-12 13:50:23.907  1019  1019 D RttService: SCAN_AVAILABLE : 1
09-12 13:50:23.907  1019  1154 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:23.907  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.907  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.907  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.907  1019  1153 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:50:23.917  1019  1130 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-12 13:50:23.917  1019  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 13:50:23.917  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 13:50:23.927  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
,09-12 13:50:23.927  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-12 13:50:23.927  1019  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 13:50:23.927  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:50:23.927  1019  1130 D WifiP2pService: P2pDisablingState
09-12 13:50:23.927  1019  1130 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 13:50:23.927  1019  1130 D WifiP2pService: p2p socket connection lost
,09-12 13:50:23.927  1019  1130 D WifiP2pService: P2pDisabledState
,09-12 13:50:23.927  1019  1131 E WifiNative-wlan0: do suspend true
,09-12 13:50:23.927  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 13:50:23.927  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 13:50:23.927  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:50:23.927  1019  1050 D WifiDisplayController: disconnect
09-12 13:50:23.927  1019  1050 D WifiDisplayController: updateConnection
09-12 13:50:23.927  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:50:23.927  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:50:23.927   277   992 D EnterpriseController: uids 1000
09-12 13:50:23.927   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 13:50:23.927   277   992 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-12 13:50:23.937  1019  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-12 13:50:23.937  1019  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-12 13:50:23.937  1019  2220 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-12 13:50:23.937  1019  2220 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-12 13:50:23.937  1019  2220 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:23.937  1019  1133 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:50:23.937  1182  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 13:50:23.937  1019  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-12 13:50:23.937  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 13:50:23.937  1019  1133 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-12 13:50:23.937  1459  1459 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:50:23.937  1019  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 13:50:23.937  1019  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:50:23.937  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-12 13:50:23.937  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 13:50:23.937  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:50:23.937  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-12 13:50:23.937  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:50:23.937  1019  1133 D ConnectivityService: nai.networkMonitor.doQuit()
09-12 13:50:23.937  1019  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,09-12 13:50:23.937  1019  1133 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 13:50:23.947  1019  1133 E ConnectivityService: updateNetworkInfo()
,09-12 13:50:23.947  1019  1133 E ConnectivityService: updateNetworkInfo()
09-12 13:50:23.947  1019  1133 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:50:23.947  1019  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-12 13:50:23.947  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 13:50:23.947  1019  3139 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:50:23.947  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 13:50:23.947  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-12 13:50:23.947  1019  1134 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:50:23.947  1019  1128 V NetworkStats: updateIfacesLocked()
09-12 13:50:23.947  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:23.947  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-12 13:50:23.947  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:23.947  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: updateDataNetType()
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-12 13:50:23.957  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 13:50:23.957  1019  1128 V NetworkStats: performPollLocked() took 4ms
09-12 13:50:23.957  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:23.957  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:23.957  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:23.957  1019  1129 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 13:50:23.957  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-12 13:50:23.957  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:23.957  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:23.957  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:23.957  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:23.957  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:23.987  6155  6155 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:50:24.007  1019  1130 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-12 13:50:24.007  1019  1130 D WifiP2pService: DefaultState{ what=143375 }
,09-12 13:50:24.007   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:50:24.007  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:24.007  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:24.007  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.007  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.007  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.007  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:24.007  2107  2107 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 13:50:24.017  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:50:24.027  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:24.027  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:24.027  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.027  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.027  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.027  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:24.027  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.027  1019  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:50:24.037  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.037  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.037  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:50:24.037  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:24.037  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.037  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.047  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:24.047  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:50:24.047  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.047  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.047  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.047  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:24.047  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:50:24.047  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.047  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:24.047  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-12 13:50:24.047  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.047  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:50:24.047  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:24.047  1182  1182 D HotspotTile: onReceive : 0, 0
,09-12 13:50:24.047  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.057  1295  1295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:24.057  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.057  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.057  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:50:24.057  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:24.057  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:24.057  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:24.057  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:24.057  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:24.057  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:24.057  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:24.057  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:24.057  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:24.057  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:24.057  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.057  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.067  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.067  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.067  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:50:24.067  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:50:24.067  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:24.067  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:24.067  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:24.067  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:24.067  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:24.067  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:24.067  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:24.067  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:50:24.067  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.067  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:24.067  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.067  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:24.067  2641  2706 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-12 13:50:24.067  2641  2706 I bt_vendor: bluetooth satus is on
09-12 13:50:24.067  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 13:50:24.067  2641  2706 I bt_vendor: bt-vendor : resetting BT status
09-12 13:50:24.067  2641  2706 I bt_vendor: Starting hciattach daemon
09-12 13:50:24.067  2641  2706 I bt_vendor: try to set false
,09-12 13:50:24.067  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:50:24.067  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.077  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:50:24.077  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.077  2641  2706 I bt_vendor: Starting hciattach daemon
,09-12 13:50:24.077  2641  2706 I bt_vendor: try to set false
09-12 13:50:24.077  2641  2706 I bt_vendor: cleanup
,09-12 13:50:24.077  2641  2766 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-12 13:50:24.077  2641  2706 I GKI_LINUX: GKI_exit_task 0 done
09-12 13:50:24.077  2641  2706 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-12 13:50:24.077  2641  2703 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-12 13:50:24.077  2641  2703 D BtConfig.SecureMode: isSecureModeOn:false
09-12 13:50:24.077  2641  2703 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 13:50:24.077  1019  1126 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-12 13:50:24.077  1019  1126 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-12 13:50:24.077  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-12 13:50:24.077  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 13:50:24.077   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-12 13:50:24.077  2641  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 13:50:24.087  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:50:24.087  1019  1126 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.087  1019  1126 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:24.087  1019  1126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 13:50:24.087  1914  1914 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-12 13:50:24.087  1019  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:24.087  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-12 13:50:24.087  1914  1914 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-12 13:50:24.087  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 13:50:24.087  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.087  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.087  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:24.097  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:50:24.097  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:50:24.097  2641  2641 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:50:24.097  2641  2641 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:50:24.097  2641  2641 D BtGatt.GattService: stop()
09-12 13:50:24.097  2641  2641 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 13:50:24.097  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.097  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:50:24.097  2641  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 13:50:24.097  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 13:50:24.097   287   287 E SMD     : DCD OFF
,09-12 13:50:24.097  1019  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:24.097  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-12 13:50:24.097  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
09-12 13:50:24.097  1459  1459 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 13:50:24.097  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.097  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.097  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:24.097  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 13:50:24.097  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:24.107  2641  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-12 13:50:24.107  1019  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:24.107  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:24.107  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.107  1019  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.107  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:50:24.107  1459  1459 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:50:24.107  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-12 13:50:24.107  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:50:24.107  2641  2641 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:50:24.107  2107  2107 I wpa_supplicant: Blacklist: Clear (all) 
09-12 13:50:24.107  2641  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:50:24.107  1019  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:24.107  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-12 13:50:24.107  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
,09-12 13:50:24.107  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.107  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.107  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:24.107  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-12 13:50:24.107  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 13:50:24.117  2641  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:50:24.117  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-12 13:50:24.117  1295  1295 D HeadsetProfile: Bluetooth service disconnected
09-12 13:50:24.117  1019  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:24.117  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:50:24.117  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.117  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.117  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:24.117  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-12 13:50:24.117  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:50:24.117  2641  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-12 13:50:24.117  1019  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:24.117  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:50:24.117  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.117  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.117  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:24.117  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:24.117  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:24.117  2641  2703 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:24.127  1019  3139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:24.127  1019  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:50:24.127  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.127  1019  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.127  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:24.127  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-12 13:50:24.127  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:50:24.127  2641  2703 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 13:50:24.127  1019  5323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:24.127  6250  6250 D StrictMode: StrictMode policy violation; ~duration=285 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 13:50:24.127  1019  5323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-12 13:50:24.127  6250  6250 D StrictMode: StrictMode policy violation; ~duration=278 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-12 13:50:24.127  6250  6250 D StrictMode: ,	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-12 13:50:24.127  6250  6250 D StrictMode: 	,at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020),
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:50:24.127  6250  6250 D StrictMode: StrictMode policy violation; ~duration=192 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164),
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 13:50:24.127  6250  6250 D StrictMode: StrictMode policy violation; ~duration=182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at an,droid.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:50:24.127  6250  6250 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:24.127  6250  6250 D StrictMode: 	,at android.os.Looper.loop(Looper.java:145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:50:24.127  6250  6250 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290),
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:50:24.147  1019  1253 I ActivityManager: Killing 5704:com.google.android.gms:car/u0a12 (adj 15): empty #31
09-12 13:50:24.127  6250  6250 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.k.c(PG:583)
09-12 13:50:24.127  6250  6250 D StrictMode: ,	at com.google.v.a.a.eq.<init>(PG:40)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:50:24.127  6250  6250 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195),
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:24.127  6250  6250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:50:24.137  1019  5323 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.137  1019  5323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.137  1019  5323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:50:24.147  1914  1914 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-12 13:50:24.147  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:24.147  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:24.157  2641  2703 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:24.157  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:24.157  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:24.157  2641  2703 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:24.157  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:50:24.157  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:50:24.157  2641  2703 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 13:50:24.157  2641  2703 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:50:24.157  2641  2703 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:50:24.157  2641  2703 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 13:50:24.157  2641  2703 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 13:50:24.157  2641  2641 E BluetoothAdapterService(833171052): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-12 13:50:24.157  2641  2641 D A2dpService: Received stop request...Stopping profile...
09-12 13:50:24.157  2641  2716 D A2dpStateMachine: Exit Disconnected: -1
,09-12 13:50:24.157  1914  1914 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:50:24.157  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
,09-12 13:50:24.167  2107  2107 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 13:50:24.167  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:50:24.167  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:50:24.167  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:50:24.167  1019  3132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:50:24.167  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:24.167  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.167  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.167  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:24.167  1019  5323 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:24.167  3557  3557 I Hs20UtilService: Starting #8
09-12 13:50:24.167  1019  5323 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.167  1019  5323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:24.167  1019  5323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:50:24.177  3557  3601 I Hs20UtilService: Message received 5007
,09-12 13:50:24.177  2641  2641 E BluetoothAdapterService(833171052): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-12 13:50:24.177  2641  2641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:50:24.177  2641  2641 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 13:50:24.177  2641  2641 D HidService: Received stop request...Stopping profile...
09-12 13:50:24.177  2641  2641 D HidService: Stopping Bluetooth HidService
09-12 13:50:24.177  2641  2641 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:50:24.177  2641  2641 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 13:50:24.177  2641  2641 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:50:24.177  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
,09-12 13:50:24.177  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-12 13:50:24.177  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 13:50:24.177  1295  1295 D BluetoothA2dp: Proxy object disconnected
09-12 13:50:24.177  2852  2852 D BluetoothA2dp: Proxy object disconnected
09-12 13:50:24.177  1295  1295 D A2dpProfile: Bluetooth service disconnected
,09-12 13:50:24.177  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:50:24.177  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 13:50:24.177  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:50:24.187  2641  2641 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 13:50:24.187  2641  2641 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 13:50:24.187  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:50:24.187  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:24.187  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:50:24.187  1295  1295 D BluetoothInputDevice: Proxy object disconnected
09-12 13:50:24.187  1295  1295 D HidProfile: Bluetooth service disconnected
,09-12 13:50:24.187  2641  2641 D HealthService: Received stop request...Stopping profile...
09-12 13:50:24.187  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
,09-12 13:50:24.187  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:24.187  2641  2641 D PanService: Received stop request...Stopping profile...
09-12 13:50:24.187  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
,09-12 13:50:24.197  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 13:50:24.197  1295  1295 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:50:24.197  1295  1295 D PanProfile: Bluetooth service disconnected
09-12 13:50:24.197  2641  2641 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 13:50:24.197  1019  5323 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.197  1019  5323 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:24.197  1019  5323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-12 13:50:24.197  1019  5323 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-12 13:50:24.197  1019  5323 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:24.197  2107  2107 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-12 13:50:24.197  2107  2107 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 13:50:24.197  6250  6270 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-12 13:50:24.197  2107  2107 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-12 13:50:24.197  2107  2107 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 13:50:24.197  2107  2107 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-12 13:50:24.207  1019  5323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.207  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:24.207  1019  5323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.207  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:50:24.207  1019  5323 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.207  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:50:24.207  1019  1134 D Tethering: InitialState.processMessage what=4
09-12 13:50:24.207  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:24.207  1019  1131 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-12 13:50:24.207  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:24.207  1019  1134 E Tethering: No numeric data
,09-12 13:50:24.207  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:50:24.207  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:24.207  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:50:24.207  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:24.217  6297  6297 E Zygote  : MountEmulatedStorage()
09-12 13:50:24.217  6297  6297 I libpersona: KNOX_SDCARD checking this for 10104
09-12 13:50:24.217  6297  6297 E Zygote  : v2
09-12 13:50:24.217  6297  6297 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:24.217  6297  6297 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:50:24.217  1019  5323 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6297 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-12 13:50:24.217  6297  6297 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:24.217  6297  6297 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:50:24.227  1019  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:50:24.227  1019  1134 D Tethering: clearTetheredNotification()
,09-12 13:50:24.227  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:24.227  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:50:24.227  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:24.227  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:50:24.227  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:50:24.227  1182  1182 D HotspotTile: updateTetherState():false, false
09-12 13:50:24.227  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
,09-12 13:50:24.227  1019  3138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-12 13:50:24.227  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.227  1019  1128 V NetworkStats: performPollLocked() took 5ms
09-12 13:50:24.227  1019  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:24.227  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-12 13:50:24.227  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:24.237  2641  2641 D SapService: Received stop request...Stopping profile...
,09-12 13:50:24.237  2641  2641 D SapService: Stopping Bluetooth SapService
09-12 13:50:24.237  2641  2641 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31a92e6c
09-12 13:50:24.237  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:24.237  1295  1295 D BluetoothMap: Proxy object disconnected
09-12 13:50:24.237  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:24.237  1295  1295 D MapProfile: Bluetooth service disconnected
,09-12 13:50:24.237  2641  2641 E BluetoothAdapterService(833171052): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 13:50:24.237  2641  2641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:50:24.237  2641  2641 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 13:50:24.237  2641  2641 D BluetoothA2dp: Proxy object disconnected
09-12 13:50:24.237  2641  2641 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-12 13:50:24.237  1295  1295 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 13:50:24.237  1295  1295 D SapProfile: Bluetooth service disconnected
,09-12 13:50:24.237  2641  2717 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 13:50:24.237  2641  2641 I GKI_LINUX: GKI_exit_task 2 done
09-12 13:50:24.237  2641  2641 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 13:50:24.237  2641  2641 E BluetoothAdapterService(833171052): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 13:50:24.237  2641  2641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:24.237  2641  2641 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:24.237  2641  2641 E BluetoothAdapterService(833171052): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 13:50:24.237  2641  2641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:24.237  2641  2641 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:24.237  2641  2641 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:50:24.237  2641  2641 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-12 13:50:24.237  2641  2641 E BluetoothAdapterService(833171052): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 13:50:24.237  2641  2641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:24.237  2641  2641 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:24.237  2641  2641 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:50:24.237  2641  2641 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:50:24.247  2641  2641 E BluetoothAdapterService(833171052): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 13:50:24.247  2641  2641 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:50:24.247  2641  2641 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-12 13:50:24.247  2641  2641 E BluetoothAdapterService(833171052): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-12 13:50:24.247  2641  2641 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 13:50:24.247  2641  2641 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 13:50:24.247  2641  2703 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-12 13:50:24.247  2641  2703 D BluetoothAdapterProperties: Setting state to 10
09-12 13:50:24.247  2641  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 13:50:24.247  2641  2703 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:50:24.247  2641  2703 D BluetoothAdapterService: updateAdapterState state is 10
,09-12 13:50:24.247  2641  2703 D BluetoothAdapterService: Autoconnection is available 
09-12 13:50:24.247  2641  2703 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 13:50:24.247  2641  2703 I BluetoothAdapterState: Entering OffState
09-12 13:50:24.247  1295  1303 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:50:24.247  2641  2873 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:50:24.247  1459  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:24.247  1459  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:50:24.247  6297  6297 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:24.247  6297  6297 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:24.257  1295  1306 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:50:24.257  1443  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:24.257  1443  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:24.257   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb725e7c8
09-12 13:50:24.257   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,09-12 13:50:24.257   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-12 13:50:24.257   272   321 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1222252408)
09-12 13:50:24.257  1295  1303 D BluetoothA2dp: onBluetoothStateChange: up=false,
,09-12 13:50:24.267  1429  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:24.267  1429  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:24.267  1295  1306 D Bluetoothsap: onBluetoothStateChange: up=false
09-12 13:50:24.267  1295  1306 D Bluetoothsap: Unbinding service...
09-12 13:50:24.267  6297  6297 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 13:50:24.277  1295  1303 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 13:50:24.277  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:50:24.287  2852  2864 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:50:24.287  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:24.287  1019  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:50:24.287  1182  1201 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:24.287  1182  1201 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:50:24.287  6250  6261 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:24.287  6250  6261 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:50:24.287  2852  2860 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:24.287  2852  2860 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:50:24.287  2641  2651 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:24.287  2641  2651 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:24.287  1295  1303 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:24.287  1295  1303 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:50:24.287  1914  1925 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:24.287  1914  1925 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:24.297  6155  6163 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:24.297  6155  6163 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:50:24.297  6155  6163 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-12 13:50:24.297  6155  6163 D BluetoothLeAdvertiser: Exit stop advertising
09-12 13:50:24.297  6155  6163 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 13:50:24.297  6155  6163 D BluetoothLeScanner: Exiting stopAllScan
,09-12 13:50:24.297  1019  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-12 13:50:24.297  1019  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-12 13:50:24.307   272   321 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-12 13:50:24.307  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:24.307   272   321 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-12 13:50:24.307  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-12 13:50:24.307   272   321 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1222252408) wakelock released: 1, error no: 0
09-12 13:50:24.307   272   321 I rmt_storage: 
09-12 13:50:24.307  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:50:24.307   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb725e7c8
,09-12 13:50:24.307  1182  1182 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:24.307  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 13:50:24.307  1182  1729 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:24.307  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:24.317  1182  1182 D BluetoothTile:  getBluetoothState : 10
09-12 13:50:24.317  1182  1729 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
,09-12 13:50:24.317  1182  1182 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:24.317  1019  1555 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:50:24.317  1182  1182 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:24.317  1019  1321 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:50:24.317  1802  1802 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:50:24.317  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:50:24.317  1914  2128 D BluetoothAdapter: 332330329: getState() :  mService = null. Returning STATE_OFF
,09-12 13:50:24.317  1914  2128 D BluetoothAdapter: 332330329: getState() :  mService = null. Returning STATE_OFF
,09-12 13:50:24.317  1019  1126 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:50:24.327  1295  1295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:24.327  1019  1126 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:50:24.327  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:24.327  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:24.327  1019  1126 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.327  1019  1126 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:24.327  1019  1126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:24.327  2641  2706 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-12 13:50:24.327  2641  2641 I GKI_LINUX: GKI_exit_task 1 done
09-12 13:50:24.327  2641  2641 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-12 13:50:24.337  2641  2641 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 13:50:24.337  2107  2107 I wpa_supplicant: Blacklist: Clear (all) ,
,09-12 13:50:24.337  2641  2641 I art     : System.exit called, status: 0
09-12 13:50:24.337  2641  2641 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:50:24.397  2107  2107 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-12 13:50:24.397  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:24.397  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:24.397  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:24.397  1019  1555 I ActivityManager: Process com.android.bluetooth (pid 2641)(adj 0) has died(42,1103)
,09-12 13:50:24.437  1019  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:50:24.447  1019  1019 I ApplicationPolicy: updateDataUsageMap
,09-12 13:50:24.457  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:24.467  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:24.467  3142  3142 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-12 13:50:24.467  3142  3142 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-12 13:50:24.477  1019  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:50:24.487  6297  6325 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-12 13:50:24.487  6297  6325 I Babel   : MmsConfig.loadMmsSettings
,09-12 13:50:24.487  6297  6325 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-12 13:50:24.487  6297  6325 I Babel   : MmsConfig.loadFromDatabase
,09-12 13:50:24.497  6297  6325 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-12 13:50:24.497  6297  6325 I Babel   : MmsConfig.loadFromResources
,09-12 13:50:24.497  1019  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-12 13:50:24.497  1019  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-12 13:50:24.497  1019  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:50:24.507  6297  6325 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-12 13:50:24.507  6297  6325 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-12 13:50:24.507  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:50:24.507  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-12 13:50:24.507  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.507  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.507  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.507  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:24.507  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:24.507  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-12 13:50:24.507  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:24.507  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:50:24.507  1182  1182 D HotspotTile: onReceive : 1, 0
,09-12 13:50:24.507  1914  2128 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:50:24.517  1295  1295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:24.517  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:24.517  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:24.517  1019  3132 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-12 13:50:24.517  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-12 13:50:24.517  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.517  1019  3132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:24.517  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 13:50:24.527  6297  6297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:50:24.557  6297  6297 I Babel_StickerModule: App launched.
,09-12 13:50:24.577  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 13:50:24.577  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 13:50:24.577  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:50:24.577  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:50:24.577  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:24.577  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:50:24.577  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:24.577  1019  1321 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-12 13:50:24.577  1019  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:24.577  1019  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.577  1019  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.577  1019  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:24.587   282   677 W QCamera2Factory: getCameraInfo: E, camera_id = 0,
09-12 13:50:24.587   282   677 W QCamera2Factory: getCameraInfo: X
,09-12 13:50:24.597   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 1,
09-12 13:50:24.597   282   282 W QCamera2Factory: getCameraInfo: X
,09-12 13:50:24.597  6327  6327 E Zygote  : MountEmulatedStorage()
,09-12 13:50:24.597  6327  6327 E Zygote  : v2
09-12 13:50:24.597  6327  6327 I libpersona: KNOX_SDCARD checking this for 10068
,09-12 13:50:24.597  6327  6327 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:24.597  6327  6327 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:24.597  6327  6327 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:24.597  6327  6327 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:24.607  1019  1321 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6327 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:50:24.627  6297  6297 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 13:50:24.627  6327  6327 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:24.627  6327  6327 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:24.637  6297  6297 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 13:50:24.637  6297  6297 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 13:50:24.637  6327  6327 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 13:50:24.637  6297  6297 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-12 13:50:24.637  6297  6297 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-12 13:50:24.647  6297  6297 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-12 13:50:24.647  6297  6297 W AudioCapabilities: Unsupported mime audio/x-ima
,09-12 13:50:24.647  6297  6297 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 13:50:24.647  6297  6297 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 13:50:24.657  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:50:24.657  6297  6297 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 13:50:24.657  6297  6297 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 13:50:24.667  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 13:50:24.667  6297  6297 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-12 13:50:24.667  6297  6297 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 13:50:24.677  6297  6297 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 13:50:24.677  6297  6297 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-12 13:50:24.677  6297  6297 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-12 13:50:24.677  6297  6297 W VideoCapabilities: Unsupported mime video/mp43
,09-12 13:50:24.687  6297  6297 W VideoCapabilities: Unsupported mime video/sorenson
,09-12 13:50:24.687  6297  6297 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-12 13:50:24.697  6327  6327 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:50:24.697  1019  1555 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-12 13:50:24.697  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.697  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.697  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.697  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:24.707  6342  6342 E Zygote  : MountEmulatedStorage(),
09-12 13:50:24.707  1019  1555 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6342 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:50:24.707  1019  1555 I ActivityManager: Killing 4993:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
09-12 13:50:24.717  6342  6342 E Zygote  : v2
,09-12 13:50:24.717  6342  6342 I libpersona: KNOX_SDCARD checking this for 10069
09-12 13:50:24.717  6342  6342 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:24.717  6342  6342 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:50:24.717  6342  6342 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:50:24.717  6342  6342 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:24.727  6297  6297 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 13:50:24.737  6342  6342 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:24.737  6342  6342 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:24.767  6342  6342 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:50:24.767  1019  3139 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
09-12 13:50:24.767  1019  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-12 13:50:24.767  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.767  1019  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:24.767  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 13:50:24.767  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.767  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.767  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.767  1019  3132 I ActivityManager: Killing 5679:com.samsung.android.sm/1000 (adj 15): empty #31
,09-12 13:50:24.777  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.777  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.777  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.777  1019  1253 I ActivityManager: Killing 5518:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-12 13:50:24.777  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.777  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.777  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.787  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.787  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.787  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.787  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.787  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.787  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.797  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.797  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.797  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.797  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.797  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.797  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.797  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.797  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.797  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.807  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:24.807  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.807  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.807  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.807  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.807  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.807  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.807  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.807  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.807  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.807  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.807  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.817  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.817  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.817  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.817  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.817  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.817  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.817  1019  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:24.817  1019  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:24.817  1019  1321 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.817  1019  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.817  1019  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:50:24.827  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:50:24.827  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:50:24.827  3557  3557 I Hs20UtilService: Starting #9
,09-12 13:50:24.827  3557  3601 I Hs20UtilService: Message received 5007
,09-12 13:50:24.827  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:50:24.827  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:50:24.827  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:24.827  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:50:24.837  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,09-12 13:50:24.837  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.837  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.837  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:50:24.837  1019  1555 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:50:24.847  1019  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:24.847  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.847  1019  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.847  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:50:24.847  1019  1547 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-12 13:50:24.847  3557  3557 I Hs20UtilService: Starting #10
,09-12 13:50:24.847  3557  3601 I Hs20UtilService: Message received 5011
,09-12 13:50:24.847  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:50:24.847  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.847  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.847  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:24.857  6358  6358 E Zygote  : MountEmulatedStorage(),
09-12 13:50:24.857  6358  6358 E Zygote  : v2
09-12 13:50:24.857  6358  6358 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:50:24.857  6358  6358 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:24.857  6358  6358 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:24.857  1019  1547 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6358 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 13:50:24.867  6358  6358 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:50:24.867  6358  6358 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:24.887  6358  6358 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:24.887  6358  6358 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:24.917  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:50:24.917  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 13:50:24.917  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:50:24.917  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:50:24.927  1019  1126 I ActivityManager: Killing 5428:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-12 13:50:24.937  1295  1295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:50:24.937  1019  1479 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings,
09-12 13:50:24.937  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-12 13:50:24.937  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:24.937  1019  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:24.937  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:50:24.947  1295  1295 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:50:24.947  1295  1295 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:50:24.947  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:24.947  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 13:50:24.957  1019  1547 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-12 13:50:24.957  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.957  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.957  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:24.957  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:24.967  1019  1547 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6375 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-12 13:50:24.967  6375  6375 E Zygote  : MountEmulatedStorage()
09-12 13:50:24.967  6375  6375 E Zygote  : v2
09-12 13:50:24.967  6375  6375 I libpersona: KNOX_SDCARD checking this for 1002
09-12 13:50:24.967  6375  6375 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:24.977  6375  6375 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:24.977  6375  6375 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:50:24.977  6375  6375 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:24.997  6375  6375 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:24.997  6375  6375 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:25.007  6375  6375 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-12 13:50:25.007  6375  6375 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:50:25.037  6375  6375 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding GattService
,09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding HeadsetService
,09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding A2dpService
09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding HidService
09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding HealthService
09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding PanService
09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding SapService
09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding SapClientService
,09-12 13:50:25.067  6375  6375 D BtSettings.ProfileConfig: Adding HidDevService
09-12 13:50:25.067  6375  6375 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-12 13:50:25.067  1019  1253 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-12 13:50:25.067  1019  1253 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.067  1019  1253 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:50:25.067  1019  1253 D SettingsProvider: selectionArgs: false
09-12 13:50:25.067  1019  1253 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.067  1019  1253 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.067  1019  1253 D SettingsProvider: ret = -1
,09-12 13:50:25.067  1019  1547 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-12 13:50:25.067  1019  1547 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.067  1019  1547 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.067  1019  1547 D SettingsProvider: selectionArgs: false
09-12 13:50:25.067  1019  1547 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.067  1019  1547 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.067  1019  1547 D SettingsProvider: ret = -1
09-12 13:50:25.067  1019  1555 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-12 13:50:25.067  1019  1555 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-12 13:50:25.067  1019  1555 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.067  1019  1555 D SettingsProvider: selectionArgs: false
09-12 13:50:25.067  1019  1555 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.067  1019  1555 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:50:25.067  1019  1555 D SettingsProvider: ret = -1
09-12 13:50:25.067  1019  3139 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-12 13:50:25.067  1019  3139 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.067  1019  3139 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-12 13:50:25.067  1019  3139 D SettingsProvider: selectionArgs: false
09-12 13:50:25.067  1019  3139 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.067  1019  3139 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.067  1019  3139 D SettingsProvider: ret = -1
09-12 13:50:25.067  1019  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-12 13:50:25.067  1019  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.067  1019  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.067  1019  1480 D SettingsProvider: selectionArgs: false
09-12 13:50:25.067  1019  1480 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:25.067  1019  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.067  1019  1480 D SettingsProvider: ret = -1
09-12 13:50:25.077  1019  3132 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-12 13:50:25.077  1019  3132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.077  1019  3132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.077  1019  3132 D SettingsProvider: selectionArgs: false
09-12 13:50:25.077  1019  3132 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.077  1019  3132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.077  1019  3132 D SettingsProvider: ret = -1
09-12 13:50:25.077  1019  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-12 13:50:25.077  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.077  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.077  1019  1031 D SettingsProvider: selectionArgs: false
09-12 13:50:25.077  1019  1031 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.077  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.077  1019  1031 D SettingsProvider: ret = -1
,09-12 13:50:25.077  1019  1479 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-12 13:50:25.077  1019  1479 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.077  1019  1479 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.077  1019  1479 D SettingsProvider: selectionArgs: false
09-12 13:50:25.077  1019  1479 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.077  1019  1479 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.077  1019  1479 D SettingsProvider: ret = -1
09-12 13:50:25.077  1019  1032 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:50:25.077  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.077  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.077  1019  1032 D SettingsProvider: selectionArgs: false
09-12 13:50:25.077  1019  1032 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.077  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.077  1019  1032 D SettingsProvider: ret = -1
,09-12 13:50:25.077  1019  3138 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:25.077  1019  3138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.077  1019  3138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.077  1019  3138 D SettingsProvider: selectionArgs: false
09-12 13:50:25.077  1019  3138 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.077  1019  3138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.077  1019  3138 D SettingsProvider: ret = -1
,09-12 13:50:25.077  1019  1047 D Tethering: interfaceRemoved wlan0
09-12 13:50:25.077  1019  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
09-12 13:50:25.077  1019  3141 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-12 13:50:25.077  1019  3141 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.077  1019  3141 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.077  1019  3141 D SettingsProvider: selectionArgs: false
09-12 13:50:25.077  1019  3141 D SettingsProvider: selectionArgs: 1002
09-12 13:50:25.077  1019  3141 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-12 13:50:25.077  1019  3141 D SettingsProvider: ret = -1
,09-12 13:50:25.077  1019  5323 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-12 13:50:25.077  1019  5323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:25.077  1019  5323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:25.077  1019  5323 D SettingsProvider: selectionArgs: false
,09-12 13:50:25.077  1019  5323 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:25.077  1019  5323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:25.077  1019  5323 D SettingsProvider: ret = -1
,09-12 13:50:25.087  1019  1321 I ActivityManager: Killing 5803:com.sec.pcw.device/1000 (adj 15): empty #31
,09-12 13:50:25.087  1914  1914 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:50:25.097  1019  1555 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:50:25.097  1019  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 13:50:25.097  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:25.097  1019  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:25.097  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:25.107  1914  6391 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 13:50:25.107  1914  1914 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:50:25.107  1019  1321 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 13:50:25.107  1019  1321 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.pcw.device/com.sec.pcw.device.receiver.SYSTEMReceiver}
09-12 13:50:25.107  1019  1321 W BroadcastQueue: android.os.TransactionTooLargeException
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-12 13:50:25.107  1019  1321 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:50:25.107  1019  1321 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-12 13:50:25.117  1019  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.117  1019  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.117  1019  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.117  1019  1321 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.127  6392  6392 E Zygote  : MountEmulatedStorage(),
09-12 13:50:25.127  1019  1321 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6392 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-12 13:50:25.127  6392  6392 E Zygote  : v2
,09-12 13:50:25.127  6392  6392 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:50:25.127  6392  6392 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:50:25.127  6392  6392 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:25.137  1019  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:25.137  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:25.137  1019  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:25.137  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:50:25.137  6392  6392 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:25.137  6392  6392 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:25.147  1019  3139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:25.147  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:25.147  1019  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:50:25.147  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:25.157  1914  6391 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-12 13:50:25.167  6392  6392 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:25.167  6392  6392 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:25.177  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_5803/cgroup.procs: No such file or directory
,09-12 13:50:25.187  6392  6392 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-12 13:50:25.187  6392  6392 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-12 13:50:25.187  6392  6392 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-12 13:50:25.197  6392  6392 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-12 13:50:25.197  6392  6392 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 13:50:25.197  6392  6392 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-12 13:50:25.197  6392  6392 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:50:25.207  1019  1126 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-12 13:50:25.207  1019  1126 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-12 13:50:25.207  6392  6407 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-12 13:50:25.207  1019  1047 D Tethering: interfaceRemoved p2p0
09-12 13:50:25.207  1019  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 13:50:25.207  1019  1126 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-12 13:50:25.207  1019  1126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.207  1019  1126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.207  1019  1126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.207  1019  1126 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.227  6409  6409 E Zygote  : MountEmulatedStorage()
,09-12 13:50:25.227  6409  6409 I libpersona: KNOX_SDCARD checking this for 10111
09-12 13:50:25.227  6409  6409 E Zygote  : v2
09-12 13:50:25.227  6409  6409 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:25.227  6409  6409 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:25.227  6409  6409 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:25.227  1019  1126 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6409 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:50:25.227  6409  6409 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 13:50:25.227  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-12 13:50:25.237  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.237  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.237  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.237  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.247  6421  6421 E Zygote  : MountEmulatedStorage(),
09-12 13:50:25.247  6421  6421 E Zygote  : v2
09-12 13:50:25.247  6421  6421 I libpersona: KNOX_SDCARD checking this for 10009
09-12 13:50:25.247  6421  6421 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:25.247  6421  6421 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:25.257  1019  1045 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6421 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:50:25.257  6409  6409 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:25.257  6409  6409 D ActivityThread: Added TimaKeyStore provider
09-12 13:50:25.257  6421  6421 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:25.257  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-12 13:50:25.257  6421  6421 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-12 13:50:25.257  1730  1730 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 13:50:25.257  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.257  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.257  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.257  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.277  1019  1098 V AlarmManager: waitForAlarm result :4
,09-12 13:50:25.277  6437  6437 E Zygote  : MountEmulatedStorage()
09-12 13:50:25.277  6437  6437 E Zygote  : v2
09-12 13:50:25.277  6437  6437 I libpersona: KNOX_SDCARD checking this for 10145
09-12 13:50:25.277  6437  6437 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:25.277  6437  6437 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:50:25.277  1019  1045 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6437 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-12 13:50:25.287  6437  6437 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:25.287  6437  6437 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:25.287  1019  1098 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-12 13:50:25.297  1019  1098 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-12 13:50:25.297  1730  1730 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-12 13:50:25.307  1730  1730 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,09-12 13:50:25.307  1730  1730 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-12 13:50:25.307  1730  1730 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-12 13:50:25.307  5540  5576 I Finsky  : [950] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,09-12 13:50:25.317  6421  6421 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:25.317  6421  6421 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:25.327  1318  1333 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,09-12 13:50:25.327  6437  6437 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:25.327  6437  6437 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:25.337  1730  1730 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 13:50:25.347  1730  1730 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-12 13:50:25.357  1019  1480 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-12 13:50:25.357  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.357  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.357  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.357  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.367  6455  6455 E Zygote  : MountEmulatedStorage()
,09-12 13:50:25.367  6455  6455 I libpersona: KNOX_SDCARD checking this for 10081
09-12 13:50:25.367  6455  6455 E Zygote  : v2
09-12 13:50:25.367  6455  6455 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:25.367  6455  6455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:25.377  1019  1480 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6455 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:50:25.367  6455  6455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:25.377  6455  6455 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-12 13:50:25.387  6437  6437 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-12 13:50:25.387  6437  6437 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:50:25.387  6437  6437 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-12 13:50:25.387  6437  6437 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:25.387  6437  6437 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:50:25.387  1730  1730 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-12 13:50:25.397   317   317 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 25.870ms
,09-12 13:50:25.417  6455  6455 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:25.417  6455  6455 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:25.417   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 18.017ms
,09-12 13:50:25.437   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.709ms
,09-12 13:50:25.447  6409  6409 I MusicStore: Database version: 108
,09-12 13:50:25.477  1019  1321 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:50:25.477  1019  1321 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
09-12 13:50:25.477  1019  1555 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:50:25.487  1019  1321 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:25.487  1019  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:25.487  1019  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:25.497  3603  3603 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 13:50:25 GMT+02:00 2016
,09-12 13:50:25.497  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 13:50:25.497  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 13:50:25.497  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:25.497  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:25.497  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 13:50:25.507  3603  3603 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-12 13:50:25.507  1019  3138 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:50:25.517  3788  3788 D ConnectivityManager: CallingUid : 10012, CallingPid : 3788
,09-12 13:50:25.517  1019  1321 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 13:50:25.517  1019  1133 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-12 13:50:25.517  1019  1126 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-12 13:50:25.527  1019  1126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.527  1019  1126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.527  1019  1126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.527  1019  1126 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.527  3603  3603 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-12 13:50:25.527  3603  3603 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 13:50:25.537  6482  6482 E Zygote  : MountEmulatedStorage()
09-12 13:50:25.537  6482  6482 E Zygote  : v2
09-12 13:50:25.537  6482  6482 I libpersona: KNOX_SDCARD checking this for 10034
09-12 13:50:25.537  6482  6482 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:25.537  6482  6482 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:25.537  3603  3603 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 13:50:25.537  1019  1126 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6482 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-12 13:50:25.537  6482  6482 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:25.537  3603  6479 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 13:50:25.537  6482  6482 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:25.547  3603  6479 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-12 13:50:25.557  3603  6479 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-12 13:50:25.557  3603  6479 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-12 13:50:25.557  3603  3603 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-12 13:50:25.567  6482  6482 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:25.567  6482  6482 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:25.577  1019  3141 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:50:25.577  1019  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-12 13:50:25.587  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.587  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.587  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.587  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.587  1019  3139 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:50:25.597  6501  6501 E Zygote  : MountEmulatedStorage()
09-12 13:50:25.597  6501  6501 I libpersona: KNOX_SDCARD checking this for 10113
09-12 13:50:25.597  6501  6501 E Zygote  : v2
09-12 13:50:25.597  6501  6501 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:25.597  6501  6501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:50:25.607  1019  1031 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6501 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-12 13:50:25.607  6501  6501 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:25.607  6501  6501 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:50:25.627  6482  6482 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-12 13:50:25.637  6501  6501 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:25.637  6501  6501 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:25.647  1019  1031 I ActivityManager: Killing 5060:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-12 13:50:25.647  6409  6409 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-12 13:50:25.647  6409  6409 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 13:50:25.677  3160  6518 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-12 13:50:25.677  3160  6518 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-12 13:50:25.677  3160  6518 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-12 13:50:25.687  3160  6518 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-12 13:50:25.687  3160  6518 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-12 13:50:25.697  5849  5849 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-12 13:50:25.697  5956  5965 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-12 13:50:25.707  6409  6409 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-12 13:50:25.707  1019  1126 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-12 13:50:25.707  1019  1126 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-12 13:50:25.717  1019  1126 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:25.717  1019  1126 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 13:50:25.717  1019  1126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-12 13:50:25.717  3788  6519 W DriveInitializer: Background init thread started
,09-12 13:50:25.717  6050  6050 I SA      : [DM] init START
,09-12 13:50:25.727  1019  1321 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:50:25.727  6050  6050 I SA      : [DM] This device is not a Vodafone
,09-12 13:50:25.737  5956  5965 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-12 13:50:25.737  5956  5965 D BadgeProvider: sendNotify, [notify] : null
09-12 13:50:25.737  5956  5965 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-12 13:50:25.737  5956  5965 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 13:50:25.737  5956  5965 D BadgeProvider: update, [UpdateCount] : 1
09-12 13:50:25.737  1481  1481 D Launcher.Model: reloadBadges entered.
,09-12 13:50:25.737  5849  6520 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-12 13:50:25.747   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-12 13:50:25.747   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:25.747  1019  3141 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:50:25.747  3788  6519 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-12 13:50:25.747  6050  6050 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-12 13:50:25.747  6050  6050 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-12 13:50:25.747  6050  6050 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-12 13:50:25.747  6050  6050 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-12 13:50:25.747  6050  6050 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,09-12 13:50:25.747  6050  6050 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,09-12 13:50:25.747  6050  6050 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-12 13:50:25.767  6050  6050 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 13:50:25.767  6050  6050 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-12 13:50:25.767  6050  6050 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-12 13:50:25.767  6050  6050 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-12 13:50:25.767  6050  6050 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-12 13:50:25.777  6050  6050 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-12 13:50:25.777  6050  6050 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-12 13:50:25.777  6050  6050 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-12 13:50:25.777  6050  6050 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-12 13:50:25.787  6050  6050 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-12 13:50:25.787  1019  1321 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:50:25.787  6050  6050 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-12 13:50:25.787  6050  6050 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-12 13:50:25.787  6050  6050 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75),
,09-12 13:50:25.787  6050  6050 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-12 13:50:25.787  6050  6050 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-12 13:50:25.787  6050  6050 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-12 13:50:25.797  6050  6050 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-12 13:50:25.797  6050  6050 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,09-12 13:50:25.797  6050  6050 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-12 13:50:25.797  1019  3132 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:50:25.797  6050  6050 I SA      : [SCU] isHaveSA() - false
,09-12 13:50:25.807  6050  6050 I SA      : support phone number id : false
,09-12 13:50:25.807  6050  6050 I SA      : [DM] Supports Ref Jpn : true
09-12 13:50:25.807  6050  6050 I SA      : [DM] init END
,09-12 13:50:25.807  6050  6050 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-12 13:50:25.807  6050  6050 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-12 13:50:25.807  6050  6050 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-12 13:50:25.807  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:50:25.807  6050  6050 I SA      : [SLFUCHKMGR] constructor called
,09-12 13:50:25.807  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 13:50:25.817  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:50:25.817  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:50:25.817  6409  6409 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 13:50:25.817  6409  6409 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3dc95b00: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-12 13:50:25.817  6409  6409 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-12 13:50:25.817  6409  6409 D AndroidMusic: GMSCore installation verified
,09-12 13:50:25.817  1019  1253 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-12 13:50:25.817  6437  6490 W art     : Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 163.653ms
,09-12 13:50:25.817  1019  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.817  1019  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.827  1019  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:25.827  1019  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:25.837  6526  6526 E Zygote  : MountEmulatedStorage(),
09-12 13:50:25.837  6526  6526 I libpersona: KNOX_SDCARD checking this for 10159
09-12 13:50:25.837  6526  6526 E Zygote  : v2
09-12 13:50:25.837  6526  6526 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:25.837  6526  6526 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:50:25.847  1019  1253 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6526 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:50:25.847  6526  6526 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:50:25.847  6526  6526 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-12 13:50:25.867  6050  6050 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-12 13:50:25.867  6050  6050 I SA      : [OR] == isSIMCardReady false ==
,09-12 13:50:25.867  6050  6050 I SA      : [SCU] == networkStateCheck == false
,09-12 13:50:25.867  6050  6050 I SA      : [OR] onReceive END
,09-12 13:50:25.877  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:50:25.877  1019  1479 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:50:25.877  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-12 13:50:25.887  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:25.887  1019  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:25.887  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-12 13:50:25.887  1019  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 13:50:25.897  3788  6519 W DriveInitializer: Background init thread ended
,09-12 13:50:25.907  6526  6526 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:25.907  6526  6526 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:25.907  1019  1480 I art     : Explicit concurrent mark sweep GC freed 58260(3MB) AllocSpace objects, 13(256KB) LOS objects, 33% free, 27MB/41MB, paused 3.113ms total 172.820ms
,09-12 13:50:25.917  6409  6409 I ConfigStore: Config Database version: 1
,09-12 13:50:25.937  1019  3141 I ActivityManager: Killing 5819:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-12 13:50:25.977  1019  3138 I ActivityManager: Killing 5452:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-12 13:50:25.977  1019  3141 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:50:25.977  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 13:50:25.977  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:25.977  1019  3141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:25.977  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:25.987  3788  3788 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:50:25.997  3788  4554 I iu.UploadsManager: num queued entries: 0
,09-12 13:50:25.997  3788  4554 I iu.UploadsManager: num updated entries: 0
,09-12 13:50:25.997  3788  4554 I iu.SyncManager: NEXT; no task
,09-12 13:50:26.027   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 13:50:26.027   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:26.027  6409  6409 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-12 13:50:26.037   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 13:50:26.037   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:26.037  6409  6409 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-12 13:50:26.037   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 13:50:26.037   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:26.047  6409  6409 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-12 13:50:26.057  1019  1480 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-12 13:50:26.057  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-12 13:50:26.057  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:26.057  1019  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:26.057  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:26.077  1019  1321 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:50:26.077  1019  1321 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-12 13:50:26.087  1019  1321 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:26.087  1019  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:26.087  1019  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:26.087   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 13:50:26.087   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:26.087  6501  6552 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 13:50:26.107   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 13:50:26.107   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:26.107  6501  6552 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 13:50:26.117  1019  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:50:26.117  1019  3141 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:50:26.117  1019  1126 I AudioService: getStreamVolume 3 index 0
,09-12 13:50:26.127  6409  6409 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-12 13:50:26.127  6409  6409 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-12 13:50:26.137   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 13:50:26.137   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:26.147  6501  6557 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 13:50:26.157   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 13:50:26.157   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:26.157  6501  6557 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 13:50:26.167  1019  3132 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:50:26.167  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:50:26.167  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:26.167  1019  3132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:26.167  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:26.167  1019  1479 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:50:26.167  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-12 13:50:26.167  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:26.167  1019  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:26.167  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:26.177  1019  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-12 13:50:26.177  1019  3138 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-12 13:50:26.177  1019  3138 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:50:26.177  1019  3138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-12 13:50:26.177  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:26.177  1019  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:26.177  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:26.177  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-12 13:50:26.187  1019  1032 I ActivityManager: Killing 5833:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-12 13:50:26.187  1019  1253 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:50:26.187  1019  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-12 13:50:26.197  1019  1019 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-12 13:50:26.197  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.197  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.197  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.197  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:26.207  6561  6561 E Zygote  : MountEmulatedStorage()
09-12 13:50:26.207  6561  6561 E Zygote  : v2
09-12 13:50:26.207  6561  6561 I libpersona: KNOX_SDCARD checking this for 10002
09-12 13:50:26.207  6561  6561 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:26.217  6561  6561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:26.217  6561  6561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-12 13:50:26.217  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6561 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:50:26.217  6561  6561 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:26.237  1019  3141 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
09-12 13:50:26.237  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-12 13:50:26.247  6561  6561 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:50:26.247  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:26.247  1019  3141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:26.247  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
09-12 13:50:26.247  6561  6561 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:26.247  6409  6409 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-12 13:50:26.257  1019  3132 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:50:26.257  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:50:26.257  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:26.257  1019  3132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:26.257  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:26.277  1019  1547 I ActivityManager: Killing 5486:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-12 13:50:26.297  1019  1547 I ActivityManager: Killing 5865:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-12 13:50:26.307  1019  1547 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-12 13:50:26.307  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:26.307  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.307  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.307  1019  1547 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:26.317  6593  6593 E Zygote  : MountEmulatedStorage()
,09-12 13:50:26.317  6593  6593 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:50:26.317  6593  6593 E Zygote  : v2
09-12 13:50:26.317  6593  6593 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:26.317  1019  1547 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6593 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 13:50:26.317  6593  6593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:26.327  6593  6593 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:26.327  6593  6593 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:50:26.327  1019  1253 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:26.327  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:26.327  1019  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:26.327  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-12 13:50:26.347  6593  6593 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:26.347  6593  6593 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:26.357  6501  6501 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-12 13:50:26.377  6501  6501 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1101-1103)
09-12 13:50:26.377  6501  6501 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:50:26.377  6501  6501 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ce94c71}
,09-12 13:50:26.377  6501  6501 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:50:26.377  6501  6501 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 13:50:26.397  6593  6593 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-12 13:50:26.407  6501  6501 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 13:50:26.407  6501  6501 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-12 13:50:26.407  6501  6501 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 13:50:26.407  5540  5576 I Finsky  : [950] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,09-12 13:50:26.407  5540  5540 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.,
,09-12 13:50:26.427  6501  6501 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-12 13:50:26.427  6501  6501 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,09-12 13:50:26.427  6501  6501 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-12 13:50:26.437  6501  6501 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 13:50:26.437  6501  6501 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:50:26.437  6501  6501 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:50:26.437  6501  6501 I Adreno-EGL: Local Branch: 
09-12 13:50:26.437  6501  6501 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:50:26.437  6501  6501 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:50:26.437  6501  6501 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 13:50:26.487  6501  6622 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 13:50:26.497  6501  6501 I NSApplication: Starting up...
,09-12 13:50:26.507  1019  3141 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-12 13:50:26.507  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.507  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.507  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.507  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:26.517  6593  6593 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-12 13:50:26.517  1019  3141 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6627 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-12 13:50:26.527  6627  6627 E Zygote  : MountEmulatedStorage()
09-12 13:50:26.527  6627  6627 E Zygote  : v2
09-12 13:50:26.527  6627  6627 I libpersona: KNOX_SDCARD checking this for 10120
09-12 13:50:26.527  6593  6593 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
09-12 13:50:26.527  6627  6627 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:26.527  6627  6627 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:50:26.527  1019  3141 I ActivityManager: Killing 5983:com.wsomacp/u0a25 (adj 15): empty #31
09-12 13:50:26.527  1019  3141 I ActivityManager: Killing 5782:com.android.mms/u0a46 (adj 15): empty #32
09-12 13:50:26.527  6593  6593 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,09-12 13:50:26.527  6627  6627 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:26.527  6593  6593 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-12 13:50:26.527  6593  6593 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-12 13:50:26.527  6593  6593 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-12 13:50:26.527  6627  6627 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:50:26.527  1019  1126 I ActivityManager: Killing 5973:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-12 13:50:26.547  6627  6627 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:26.557  6627  6627 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:26.567  1019  1321 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:50:26.567  1019  1321 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:50:26.567  1019  1321 D SecContentProvider2: mCursor = null
,09-12 13:50:26.567  1019  1321 D WifiService: setWifiEnabled: true pid=6155, uid=10155
09-12 13:50:26.567  1019  1321 W ActivityManager: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:50:26.567  1019  1321 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:50:26.567  1019  1321 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:50:26.567  1019  1321 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:50:26.567  1019  1321 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:50:26.567  1019  1321 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:50:26.567  1019  1321 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:50:26.567  1019  1321 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:50:26.567  1019  1321 D SettingsProvider: name = wifi_on
,09-12 13:50:26.567  1019  1131 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 13:50:26.577  6627  6627 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:50:26.597  1019  1480 D CountryDetector: No listener is left
,09-12 13:50:26.857  1019  1555 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-12 13:50:26.867  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:26.867  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.867  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:26.867  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:26.877  6655  6655 E Zygote  : MountEmulatedStorage(),
,09-12 13:50:26.877  6655  6655 E Zygote  : v2
,09-12 13:50:26.877  6655  6655 I libpersona: KNOX_SDCARD checking this for 10125,
09-12 13:50:26.877  1019  1555 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6655 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-12 13:50:26.877  6655  6655 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:26.887  1019  1555 I ActivityManager: Killing 6019:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-12 13:50:26.887  6655  6655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:50:26.887  6655  6655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:26.887  6655  6655 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:26.917  6655  6655 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:26.917  6655  6655 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:26.927  1019  1047 D Tethering: interfaceAdded wlan0
,09-12 13:50:26.927  6655  6655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:50:26.927  6655  6655 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:50:26.927  6655  6655 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:50:26.937  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 13:50:26.937  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:26.937  1019  1134 E Tethering: No numeric data
09-12 13:50:26.937  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:26.937  1019  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:50:26.937  1019  1134 D Tethering: clearTetheredNotification()
09-12 13:50:26.947  1019  1134 D Tethering: InitialState.processMessage what=4
09-12 13:50:26.947  6655  6655 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:50:26.947  1019  1047 D Tethering: interfaceAdded p2p0
09-12 13:50:26.947  1019  1134 E Tethering: No numeric data
,09-12 13:50:26.947  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:50:26.947  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:26.947  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:26.947  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:50:26.947  1182  1182 D HotspotTile: updateTetherState():false, false
,09-12 13:50:26.957  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:50:26.957  6655  6655 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-12 13:50:26.957  1019  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-12 13:50:26.957   277   996 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 13:50:26.957  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:50:26.957  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:50:26.957   277   996 D SoftapController: Softap fwReload - Ok
,09-12 13:50:26.967  1019  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:50:26.967  1019  1134 D Tethering: clearTetheredNotification()
,09-12 13:50:26.967  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:26.967  1019  1128 V NetworkStats: performPollLocked() took 16ms
,09-12 13:50:26.967  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:50:26.967  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:50:26.967  1182  1182 D HotspotTile: updateTetherState():false, false
,09-12 13:50:26.967   277   996 D CommandListener: Setting iface cfg
09-12 13:50:26.967   277   996 D CommandListener: Trying to bring down wlan0
,09-12 13:50:26.967   277   996 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:50:26.967  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:50:26.967  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:26.967  6655  6655 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-12 13:50:26.967  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:26.967  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:50:26.967  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:26.967  1019  1128 V NetworkStats: performPollLocked() took 3ms
09-12 13:50:26.967  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:26.967  1019  1031 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-12 13:50:26.967  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:26.977  1019  1131 E WifiHW  : supplicant_name : p2p_supplicant
09-12 13:50:26.977  1019  1031 I ActivityManager: Killing 5899:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-12 13:50:26.977  1019  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-12 13:50:26.977  1019  1547 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:26.977  1019  1547 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:26.987  1019  1547 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:50:26.987  1019  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:26.987  1019  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:50:26.987  3557  3557 I Hs20UtilService: Starting #11
,09-12 13:50:26.987  3557  3601 I Hs20UtilService: Message received 5011
09-12 13:50:26.987  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:26.987  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:26.997  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:50:26.997  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:50:26.997  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:26.997  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:26.997  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:26.997  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:26.997  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:26.997  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-12 13:50:26.997  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:50:26.997  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:26.997  1295  1295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:26.997  1182  1182 D HotspotTile: onReceive : 2, 0
09-12 13:50:26.997  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:50:26.997  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:27.007  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:50:27.007  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:50:27.007  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:50:27.007  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:50:27.017  1019  3141 I ActivityManager: Killing 5880:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-12 13:50:27.027  6671  6671 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 13:50:27.027  6671  6671 I wpa_supplicant: Successfully initialized wpa_supplicant
09-12 13:50:27.027  1019  3138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:27.027  6671  6671 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
09-12 13:50:27.027  1019  3138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:27.027  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:27.027  1019  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:27.027  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:50:27.027  3557  3557 I Hs20UtilService: Starting #12
,09-12 13:50:27.037  3557  3601 I Hs20UtilService: Message received 5011
,09-12 13:50:27.037  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:50:27.037  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:50:27.037  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:50:27.037  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:50:27.037  6671  6671 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-12 13:50:27.037   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6671
09-12 13:50:27.037   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 13:50:27.037  6671  6671 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 13:50:27.037  6671  6671 I wpa_supplicant: ssSupport state is = 1
,09-12 13:50:27.037  6671  6671 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 13:50:27.037  6671  6671 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-12 13:50:27.037   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6671
09-12 13:50:27.037   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-12 13:50:27.097   287   287 E SMD     : DCD OFF
,09-12 13:50:27.187   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-12 13:50:27.187  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-12 13:50:27.257  6671  6671 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-12 13:50:27.257  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 13:50:27.267  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-12 13:50:27.267   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6671
09-12 13:50:27.267   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 13:50:27.267  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 13:50:27.267  6671  6671 I wpa_supplicant: ssSupport state is = 1
,09-12 13:50:27.267  6671  6671 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 13:50:27.267  6671  6671 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:50:27.267  6671  6671 E wpa_supplicant: SIM READ ERROR
09-12 13:50:27.267  6671  6671 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:50:27.267  6671  6671 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:50:27.267  6671  6671 E wpa_supplicant: SIM READ ERROR
09-12 13:50:27.267  6671  6671 I wpa_supplicant: Blacklist: Clear (all) 
09-12 13:50:27.267  6671  6671 I wpa_supplicant: wpa_default_ap_write_once,
09-12 13:50:27.267  6671  6671 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:50:27.267  6671  6671 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:50:27.267  6671  6671 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-12 13:50:27.267  6671  6671 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:50:27.267  6671  6671 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:50:27.277  6671  6671 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 13:50:27.277  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 13:50:27.277  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:50:27.277  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:27.457  6671  6671 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-12 13:50:27.637  6671  6671 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
09-12 13:50:27.637  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 13:50:27.647  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 13:50:27.647   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6671
09-12 13:50:27.647   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-12 13:50:27.647  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-12 13:50:27.647  6671  6671 I wpa_supplicant: ssSupport state is = 1
09-12 13:50:27.657  6671  6671 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 13:50:27.657  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 13:50:27.667  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-12 13:50:27.667   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6671
09-12 13:50:27.667   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 13:50:27.667  6671  6671 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-12 13:50:27.667  6671  6671 I wpa_supplicant: ssSupport state is = 1
09-12 13:50:27.667  6671  6671 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:50:27.667  6671  6671 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 13:50:27.667  6671  6671 E wpa_supplicant: SIM READ ERROR
,09-12 13:50:27.667  6671  6671 I wpa_supplicant: wpa_default_ap_write_once
09-12 13:50:27.667  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:50:27.667  6671  6671 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:50:27.667  6671  6671 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 13:50:27.667  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:50:27.667  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:50:27.677  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,09-12 13:50:27.677  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:50:27.677  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:50:27.787  6671  6671 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-12 13:50:27.787  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 13:50:27.867  6671  6671 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-12 13:50:27.867  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-12 13:50:27.867  6671  6671 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 13:50:27.877  1019  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-12 13:50:27.877  1019  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 13:50:27.877  6671  6671 I wpa_supplicant: HOTSPOT20_ENABLE called
09-12 13:50:27.877  6671  6671 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:50:27.877  6671  6671 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 13:50:27.877  6671  6671 E wpa_supplicant: SIM READ ERROR
09-12 13:50:27.877  6671  6671 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:50:27.907  6671  6671 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-12 13:50:27.927  1019  1131 D WifiNative-wlan0: callSECApiInt - ID [210],
09-12 13:50:27.927  6671  6671 I wpa_supplicant: Skip scan - bUseNetwork false
09-12 13:50:27.927  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:27.927  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:27.927  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 13:50:27.927  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:27.927  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:27.927  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:27.927  1019  1131 D WifiConfigStore: Loading config and enabling all networks 
09-12 13:50:27.937  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:27.937  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-12 13:50:27.937  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:50:27.937  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:50:27.937  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:27.937  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:50:27.937  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:50:27.937  1182  1182 D HotspotTile: onReceive : 3, 0
,09-12 13:50:27.937  1295  1295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:27.947  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:50:27.947  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:27.947  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:27.947  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:27.947  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:50:27.947  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:27.947  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:27.957  1019  1555 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:50:27.957  1019  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:27.957  1019  1131 E WifiConfigStore: Not a HS20
,09-12 13:50:27.957  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:27.957  1019  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:27.957  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:27.957  1019  1131 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-12 13:50:27.957  3557  3557 I Hs20UtilService: Starting #13
09-12 13:50:27.957  3557  3601 I Hs20UtilService: Message received 5011
,09-12 13:50:27.967  1019  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-12 13:50:27.967  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:50:27.967  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:50:27.967  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:50:27.967  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:50:27.967  1019  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 13:50:27.967  6671  6671 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 13:50:27.967  6671  6671 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 13:50:27.967  6671  6671 I wpa_supplicant: reset timer : RESET_TIMER 0
,09-12 13:50:27.967  6671  6671 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:50:27.967  6671  6671 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 13:50:27.967  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 13:50:27.967  6671  6671 I wpa_supplicant: First Scan Start
09-12 13:50:27.967  6671  6671 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 13:50:27.977  1019  1131 D WifiNative-wlan0: Setting external_sim to 1
,09-12 13:50:27.977  1019  1131 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:50:27.977  1019  1131 I WifiNative-HAL: startHal
09-12 13:50:27.977  1019  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9e11488c
09-12 13:50:27.977  1019  1131 I WifiNative-HAL: Could not start hal
,09-12 13:50:27.977  6297  6297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:50:27.977  1019  1131 E WifiNative-wlan0: do suspend true
,09-12 13:50:27.977  1019  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-12 13:50:27.987  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 13:50:27.987  1019  1130 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-12 13:50:27.987  1019  1019 D RttService: SCAN_AVAILABLE : 3
09-12 13:50:27.987   277   996 D CommandListener: Setting iface cfg
09-12 13:50:27.987   277   996 D CommandListener: Trying to bring up p2p0
,09-12 13:50:27.987  1019  1130 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 13:50:27.987  1019  1154 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:27.987  1019  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:50:27.987  1019  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:50:27.987  1019  1131 E WifiNative-wlan0: invaild command id : 215
09-12 13:50:27.987  1019  1153 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:27.987  1019  1153 I WifiNative-HAL: startHal
09-12 13:50:27.987  1019  1130 D WifiP2pService: P2pEnablingState
09-12 13:50:27.987  1019  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9ce9e9bc
09-12 13:50:27.987  1019  1153 I WifiNative-HAL: Could not start hal
09-12 13:50:27.987  1019  1153 E WifiScanningService: could not start HAL
,09-12 13:50:27.987  1019  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:50:27.987  1019  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:50:27.987  1019  1131 E WifiNative-wlan0: invaild command id : 215
09-12 13:50:27.987  1019  1130 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-12 13:50:27.987  1019  1130 D WifiP2pService: P2p socket connection successful
,09-12 13:50:27.987  1019  1130 D WifiP2pService: P2pEnabledState
,09-12 13:50:27.987  6671  6671 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 13:50:27.987  1019  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 13:50:27.987  1019  1133 E ConnectivityService: updateNetworkInfo()
,09-12 13:50:27.987  6671  6671 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:50:27.987  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 13:50:27.987  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
09-12 13:50:27.987  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:50:27.987  1019  1050 D WifiDisplayController: disconnect
,09-12 13:50:27.987  1019  1050 D WifiDisplayController: updateConnection
09-12 13:50:27.987  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:50:27.997  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:50:27.997  6671  6671 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-12 13:50:27.997  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-12 13:50:27.997  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,09-12 13:50:27.997  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
,09-12 13:50:27.997  1019  1131 D SecContentProvider2: mCursor = null
09-12 13:50:27.997  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:50:27.997  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 13:50:28.007  1019  1130 D WifiNative-p2p0: p2pGetDeviceAddress
09-12 13:50:27.997  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 13:50:28.007  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 13:50:27.997  1019  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:50:28.007  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:50:27.997  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-12 13:50:28.007  1019  1130 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-12 13:50:28.007  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 13:50:28.007  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:28.007  1019  1131 D SecContentProvider2: mCursor = null
09-12 13:50:28.007  1019  1130 D WifiP2pService: DeviceAddress: 7e:96:ac
09-12 13:50:28.007  1019  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  secondary type: null
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  wps: 0
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  grpcapab: 0
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  devcapab: 0
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  status: 3
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  wfdInfo: null
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  groupownerAddress: null
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  GOdeviceName: null
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  interfaceAddress: 
09-12 13:50:28.007  1019  1050 D WifiDisplayController:  SConnectInfo : null
09-12 13:50:28.007  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:50:28.007  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:28.007  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:50:28.007  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:28.007  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
09-12 13:50:28.007  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 13:50:28.007  6327  6327 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:50:28.017  6342  6342 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:50:28.027  1019  1130 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 13:50:28.027  1019  1130 D WifiP2pService: InactiveState
,09-12 13:50:28.027  1019  1130 D WifiP2pService: InactiveState{ what=143376 }
,09-12 13:50:28.027  1019  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:50:28.027  6671  6671 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:50:28.027  1019  1130 D WifiP2pService: InactiveState{ what=143376 },
09-12 13:50:28.027  1019  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:50:29.087   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:50:29.247  6671  6671 I wpa_supplicant: nl80211: Received scan results (15 BSSes),
,09-12 13:50:29.247  6671  6671 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-12 13:50:29.247  1019  6676 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
09-12 13:50:29.247  6671  6671 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-12 13:50:29.247  6671  6671 I wpa_supplicant: Trying to associate with  'G700',
09-12 13:50:29.257  6671  6671 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-12 13:50:29.257  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-12 13:50:29.277  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:29.277  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:29.387  6671  6671 E wpa_supplicant: Cmd 35605 not handled
,09-12 13:50:29.387  6671  6671 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:50:29.387  6671  6671 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-12 13:50:29.387  6671  6671 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-12 13:50:29.387  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 13:50:29.387  6671  6671 I wpa_supplicant: Associated with F4.99.3E
09-12 13:50:29.387  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:29.387  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:50:29.387  6671  6671 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:50:29.387  6671  6671 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 13:50:29.387  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-12 13:50:29.387  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:29.397  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:29.397  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:29.397  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:29.397  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:29.397  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:50:29.397  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:29.397  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 13:50:29.397  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 13:50:29.397  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
,09-12 13:50:29.397  1019  1134 E Tethering: No numeric data
,09-12 13:50:29.397  1019  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:50:29.397  1019  1134 D Tethering: clearTetheredNotification()
,09-12 13:50:29.397  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:50:29.397  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:29.397  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-12 13:50:29.397  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:50:29.397  6671  6671 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:50:29.397  1182  1182 D HotspotTile: updateTetherState():false, false
09-12 13:50:29.397  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:29.397  6671  6671 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-12 13:50:29.397  6671  6671 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-12 13:50:29.397  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-12 13:50:29.397  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:29.397  1019  1131 D SecContentProvider2: mCursor = null
09-12 13:50:29.397  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 13:50:29.397  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:50:29.397  6671  6671 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:50:29.397  6671  6671 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 13:50:29.397  6671  6671 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-12 13:50:29.407  6671  6671 I wpa_supplicant: Blacklist: Clear (temp) 
,09-12 13:50:29.407  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-12 13:50:29.407  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 13:50:29.407  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
09-12 13:50:29.407  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 13:50:29.407  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:29.407  1019  1128 V NetworkStats: performPollLocked() took 4ms
,09-12 13:50:29.407  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:29.407  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:29.407  1019  1131 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 13:50:29.407  1019  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:50:29.407  1019  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 13:50:29.407  1019  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 13:50:29.407  1019  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:50:29.407  1019  1133 E ConnectivityService: updateNetworkInfo()
,09-12 13:50:29.417  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:50:29.417  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:29.417  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.417  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.417  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.417  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.417  1019  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:50:29.417  1019  5323 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:29.417  1019  5323 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:29.417  1019  5323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:29.417  1019  5323 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:50:29.417  1019  5323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:29.417  3557  3557 I Hs20UtilService: Starting #14
,09-12 13:50:29.427  3557  3601 I Hs20UtilService: Message received 5007
09-12 13:50:29.427  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:50:29.427  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:50:29.427  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,09-12 13:50:29.427  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:50:29.427  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-12 13:50:29.427  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:50:29.427  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:29.437  1019  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-12 13:50:29.447   277   996 D CommandListener: Setting iface cfg,
09-12 13:50:29.447  1019  1131 E WifiStateMachine: Start Dhcp Watchdog 2
,09-12 13:50:29.447  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-12 13:50:29.447  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:29.457  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 13:50:29.457  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:29.457  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.457  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.457  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.457  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.467  1019  1131 E WifiNative-wlan0: do suspend false
,09-12 13:50:29.467  1019  1130 D WifiP2pService: InactiveState{ what=143375 }
09-12 13:50:29.467  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:29.467  1019  1131 D SecContentProvider2: mCursor = null
09-12 13:50:29.467  1019  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 13:50:29.577  1019  3141 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:50:29.577  1019  3141 D WifiService: setWifiEnabled: false pid=6155, uid=10155
09-12 13:50:29.577  1019  3141 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:50:29.577  1019  3141 D SecContentProvider2: mCursor = null
09-12 13:50:29.577  1019  3141 D SettingsProvider: name = wifi_on
,09-12 13:50:29.587  1019  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-12 13:50:29.597  1019  1131 E WifiNative-wlan0: do suspend true,
,09-12 13:50:29.617  1019  1130 D WifiP2pService: InactiveState{ what=143375 },
09-12 13:50:29.617  1019  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 13:50:29.617  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:29.627  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:29.627  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.627  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.627  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.627  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.627   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:50:29.627  1019  1133 E ConnectivityService: updateNetworkInfo(),
09-12 13:50:29.627  1019  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:50:29.627  1019  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-12 13:50:29.637   277   996 E Netd    : no such netId 503
09-12 13:50:29.637  1019  1133 D ConnectivityService: nai.networkMonitor.doQuit(),
,09-12 13:50:29.637  1019  1133 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
09-12 13:50:29.637  1019  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-12 13:50:29.637  1019  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-12 13:50:29.637  1019  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:50:29.637  1019  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-12 13:50:29.637  1019  1133 E ConnectivityService: updateNetworkInfo()
,09-12 13:50:29.637  1019  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 13:50:29.637  1019  1133 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-12 13:50:29.637  1019  1130 D WifiP2pService: InactiveState{ what=131204 }
,09-12 13:50:29.637  1019  1130 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 13:50:29.637  1019  1130 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-12 13:50:29.637  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:50:29.647  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:29.647  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:29.647  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.647  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.647  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.647  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.657  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 13:50:29.657  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:50:29.657  1019  1019 D RttService: SCAN_AVAILABLE : 1
,09-12 13:50:29.657  1019  1154 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:50:29.667  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 13:50:29.667  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:50:29.667  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-12 13:50:29.667  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 13:50:29.667  1019  1133 E ConnectivityService: updateNetworkInfo()
09-12 13:50:29.667  1019  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 13:50:29.667  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:29.667  1019  1545 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:29.667  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:29.667  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:29.667  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:29.667  3557  3557 I Hs20UtilService: Starting #15
09-12 13:50:29.667  1019  1130 D WifiP2pService: P2pDisablingState
09-12 13:50:29.667  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 13:50:29.667  1019  1130 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 13:50:29.667  3557  3601 I Hs20UtilService: Message received 5007
09-12 13:50:29.667  1019  1130 D WifiP2pService: p2p socket connection lost
09-12 13:50:29.667  1019  1131 E WifiNative-wlan0: do suspend true
09-12 13:50:29.667  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 13:50:29.667  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:50:29.667  1019  1050 D WifiDisplayController: disconnect
09-12 13:50:29.667  1019  1050 D WifiDisplayController: updateConnection
09-12 13:50:29.667  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:50:29.667  1019  1130 D WifiP2pService: P2pDisabledState
09-12 13:50:29.667  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:50:29.677  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:50:29.677  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 13:50:29.677  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 13:50:29.677  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:50:29.677  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:50:29.677  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:50:29.677  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:50:29.677  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 13:50:29.677  1019  3132 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:50:29.677  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 13:50:29.687  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:50:29.687  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:29.687  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:50:29.687  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:29.687  6683  6683 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 13:50:29.687  6683  6683 I dhcpcd  : version 5.5.6 starting
,09-12 13:50:29.697  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 13:50:29.697  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:50:29.697  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:50:29.697  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:50:29.697  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:29.697  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:50:29.697  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:29.697  6683  6683 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-12 13:50:29.697  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:50:29.707  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
09-12 13:50:29.707  6327  6327 D FileShare-Client: Outbound.stopDelayTimer - 
09-12 13:50:29.707  1019  1130 D WifiP2pService: P2pDisabledState{ what=143375 }
09-12 13:50:29.707  1019  1130 D WifiP2pService: DefaultState{ what=143375 }
,09-12 13:50:29.707   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:50:29.707  6342  6342 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:50:29.717  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:29.717  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:29.717  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.717  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.717  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.717  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.727  6671  6671 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-12 13:50:29.727  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:50:29.737  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:29.737  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 13:50:29.737  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.737  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.737  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.737  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:29.737  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:29.737  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:50:29.737  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.747  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.747  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:50:29.747  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.747  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:29.747  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:29.747  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-12 13:50:29.747  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:29.747  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:29.747  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:29.747  1295  1295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:29.747  1182  1182 D HotspotTile: onReceive : 0, 0
09-12 13:50:29.747  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:29.747  1019  3132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:29.747  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:29.747  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:29.747  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:29.747  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:29.747  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:29.747  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:29.747  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:29.747  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:50:29.747  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:50:29.747  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:29.747  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:50:29.747  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:29.747  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:29.747  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:29.757  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:29.757  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:29.757  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:29.757  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:29.757  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:29.757  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:29.757  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:29.757  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:29.757  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:50:29.757  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:29.757  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:50:29.757  3557  3557 I Hs20UtilService: Starting #16
,09-12 13:50:29.757  3557  3601 I Hs20UtilService: Message received 5007
,09-12 13:50:29.767  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:50:29.767  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:50:29.767  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:50:29.767  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:50:29.767  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:29.767  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:50:29.767  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:29.777  1019  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:50:29.777  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:50:29.777  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:29.777  1019  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:29.777  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:50:29.777  3557  3557 I Hs20UtilService: Starting #17
,09-12 13:50:29.777  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:50:29.777  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:50:29.777  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:50:29.777  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:50:29.787  3557  3601 I Hs20UtilService: Message received 5011
09-12 13:50:29.787  6683  6683 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-12 13:50:29.787  6683  6683 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-12 13:50:29.787  6683  6683 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-12 13:50:29.787  6683  6683 I dhcpcd  : bssid match
09-12 13:50:29.787  6683  6683 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-12 13:50:29.857  6683  6683 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-12 13:50:29.947  6671  6671 I wpa_supplicant: Blacklist: Clear (all) ,
09-12 13:50:29.947  6683  6683 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,09-12 13:50:30.077  6671  6671 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-12 13:50:30.077  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:50:30.077  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:50:30.077  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 13:50:30.087   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:50:30.097  6671  6671 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
09-12 13:50:30.097  6671  6671 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 13:50:30.097  6671  6671 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-12 13:50:30.097  6671  6671 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 13:50:30.097  6671  6671 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-12 13:50:30.097  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 13:50:30.097  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:50:30.097  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:30.097  1019  1134 D Tethering: InitialState.processMessage what=4
,09-12 13:50:30.097  1019  1131 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-12 13:50:30.097   287   287 E SMD     : DCD OFF
09-12 13:50:30.107  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:30.107  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:30.107  1019  1134 E Tethering: No numeric data
,09-12 13:50:30.107  1019  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
09-12 13:50:30.107  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-12 13:50:30.107  1019  1134 D Tethering: clearTetheredNotification()
09-12 13:50:30.107  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:50:30.107  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:30.107  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-12 13:50:30.107  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:30.107  1182  1182 D HotspotTile: updateTetherState():false, false
09-12 13:50:30.107  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:50:30.117  1019  1128 V NetworkStats: performPollLocked() took 4ms
09-12 13:50:30.117  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:30.117  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:30.117  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:30.117  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:50:30.117  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:30.117  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:30.387  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 13:50:30.387  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:30.387  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:30.427  6671  6671 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:50:30.487  6671  6671 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-12 13:50:30.487  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 13:50:30.487  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:30.487  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:30.587  1019  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-12 13:50:30.597  1019  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-12 13:50:30.597  6297  6297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:50:30.597  1019  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:50:30.597  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:50:30.597  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:50:30.597  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:30.597  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:30.597  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:30.597  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:30.607  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:30.607  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-12 13:50:30.607  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:30.607  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:50:30.607  1182  1182 D HotspotTile: onReceive : 1, 0
,09-12 13:50:30.607  1914  2128 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:50:30.607  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:30.607  1295  1295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:30.617  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:30.617  1019  5323 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:50:30.617  1019  5323 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:30.617  1019  5323 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:30.617  1019  5323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:30.617  1019  5323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:50:30.627  3557  3557 I Hs20UtilService: Starting #18
,09-12 13:50:30.627  3557  3601 I Hs20UtilService: Message received 5011
,09-12 13:50:30.627  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:50:30.627  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 13:50:30.627  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:50:30.627  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:50:31.087   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:50:31.107  1019  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:31.107  1019  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:50:31.107  1019  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:31.107  1019  3141 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
09-12 13:50:31.107  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-12 13:50:31.107  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:31.107  1019  3141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:31.107  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
09-12 13:50:31.117  1019  1480 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-12 13:50:31.117  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-12 13:50:31.117  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:31.117  1019  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:31.117  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:31.127  6501  6554 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-12 13:50:31.137  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:31.137  1019  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:31.137  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:31.147  1019  1547 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:50:31.147  1019  1547 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-12 13:50:31.147  1019  1547 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:31.147  1019  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:31.147  1019  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:31.147  1019  1031 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:50:31.147  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-12 13:50:31.147  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:31.147  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:31.147  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,09-12 13:50:31.157  1019  3132 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:50:31.157  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:50:31.157  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:31.157  1019  3132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:50:31.157  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:31.167  1019  1479 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-12 13:50:31.177  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-12 13:50:31.177  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:31.177  1019  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:31.177  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:31.197  1019  1547 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:31.197  1019  1547 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:31.197  1019  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:50:31.197  1019  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-12 13:50:31.207  1914  1914 D WearableService: callingUid 10012, callindPid: 1914
,09-12 13:50:31.227  1019  1032 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:50:31.227  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:50:31.227  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:31.227  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:50:31.227  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:50:31.247  6409  6713 I MusicLeanback: Conditions not met for autocaching.
,09-12 13:50:31.247  6409  6713 I MusicLeanback: Stop autocaching.
,09-12 13:50:31.267   277   990 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-12 13:50:31.267  1019  1047 D Tethering: interfaceRemoved wlan0
,09-12 13:50:31.267  1019  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 13:50:31.267  6409  6409 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-12 13:50:31.277  6409  6718 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-12 13:50:31.387  1019  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:50:31.387  1019  1031 D BatteryService: level:87, scale:100, status:2, health:2, present:true, voltage: 4143, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-12 13:50:31.387  1019  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-12 13:50:31.387  1019  1031 D BatteryService: stay LED for charging
,09-12 13:50:31.387  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:50:31.397  1019  1019 I MotionRecognitionService: Plugged
,09-12 13:50:31.397  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:50:31.397  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:50:31.397  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:50:31.397  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:50:31.407  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 87
,09-12 13:50:31.427  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:31.427  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
09-12 13:50:31.427  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:31.587  1019  1047 D Tethering: interfaceRemoved p2p0
09-12 13:50:31.587  1019  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 13:50:32.087   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:50:32.367  1019  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 13:50:32.577  6155  6207 D BluetoothAdapter: enable()
,09-12 13:50:32.587  1019  1032 W ActivityManager: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:50:32.587  1019  1032 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-12 13:50:32.587  1019  1032 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:50:32.587  1019  1032 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:50:32.587  1019  1032 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
,09-12 13:50:32.587  1019  1032 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-12 13:50:32.587  1019  1032 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-12 13:50:32.587  1019  1032 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:50:32.587  1019  1032 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:32.587  1019  1032 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:32.597  1019  1032 D SettingsProvider: name = bluetooth_on,
,09-12 13:50:32.597  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 13:50:32.597  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:32.597  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
,09-12 13:50:32.597  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-12 13:50:32.637  6375  6375 D BluetoothAdapterState: make
,09-12 13:50:32.637  6375  6375 I bluedroid: init
,09-12 13:50:32.647  6375  6722 I BluetoothAdapterState: Entering OffState,
,09-12 13:50:32.647  6375  6375 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 13:50:32.647  6375  6375 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 13:50:32.647  6375  6375 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 13:50:32.647  6375  6375 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 13:50:32.657  6375  6375 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-12 13:50:32.657  6375  6375 I bluedroid: get_profile_interface socket
09-12 13:50:32.657  6375  6375 I bluedroid: get_profile_interface map_client
,09-12 13:50:32.657  6375  6375 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-12 13:50:32.657  6375  6725 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting,
09-12 13:50:32.657  6375  6725 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-12 13:50:32.657  6375  6725 E BluetoothServiceJni: populateRssiValuesNative
09-12 13:50:32.657  6375  6725 I bluedroid: getModelRssiValues
09-12 13:50:32.657  6375  6725 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-12 13:50:32.657  6375  6725 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:50:32.667  1019  1019 D SettingsProvider: name = bluetooth_name
,09-12 13:50:32.667  6375  6725 D BluetoothAdapterProperties: Name is: A5-1
,09-12 13:50:32.667  6375  6375 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:32.667  1019  3139 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-12 13:50:32.667  1019  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.677  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:32.677  1019  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.677  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.677  6375  6383 I bluedroid: config_hci_snoop_log
,09-12 13:50:32.677  1019  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-12 13:50:32.677  1019  1049 D BluetoothManagerService: Ble is always on enable gatt
,09-12 13:50:32.677  1019  1049 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-12 13:50:32.687  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-12 13:50:32.687  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:50:32.687  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:32.687  6375  6375 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-12 13:50:32.687  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:32.687  1019  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 13:50:32.697  6375  6722 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-12 13:50:32.697  6375  6722 D BluetoothAdapterProperties: Setting state to 11
09-12 13:50:32.697  6375  6722 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 13:50:32.697  6375  6722 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:50:32.697  6375  6722 D BluetoothAdapterService: updateAdapterState state is 11
,09-12 13:50:32.697  6375  6722 D BluetoothAdapterService: Autoconnection is available 
,09-12 13:50:32.697  6375  6722 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-12 13:50:32.697  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:32.697  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,09-12 13:50:32.707  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:,
09-12 13:50:32.707  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:32.707  1182  1182 D BluetoothTile:  getBluetoothState : 11
,09-12 13:50:32.707  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:32.707  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:50:32.707  1019  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:32.707  1019  3132 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:50:32.717  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:32.717  1802  1802 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:50:32.717  6375  6722 D BluetoothSecureManager: getInstant: null
09-12 13:50:32.717  6375  6722 D BluetoothSecureManager: calling getMethod for getService
09-12 13:50:32.717  6375  6722 D BluetoothSecureManager: calling getService
,09-12 13:50:32.717  6375  6722 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@346e770
,09-12 13:50:32.717  1019  3139 D BluetoothSecureManagerService: isSecureModeEnabled
09-12 13:50:32.717  1019  3139 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-12 13:50:32.717  6375  6722 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 13:50:32.717  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 13:50:32.717  6375  6722 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-12 13:50:32.717  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 13:50:32.717  6375  6722 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-12 13:50:32.717  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:32.717  6375  6722 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-12 13:50:32.717  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 13:50:32.717  6375  6722 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,09-12 13:50:32.717  1295  1295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:32.717  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 13:50:32.727  6375  6722 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-12 13:50:32.727  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:50:32.727  1019  1321 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:50:32.727  1019  1321 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.727  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:50:32.727  1019  1321 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.727  1019  1321 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:32.727  1019  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:32.727  1019  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.,
09-12 13:50:32.727  6375  6722 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-12 13:50:32.727  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:32.727  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:32.727  6375  6722 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-12 13:50:32.727  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:50:32.737  6375  6722 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-12 13:50:32.737  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:32.737  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:50:32.737  6375  6722 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:32.737  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 13:50:32.737  1295  1295 D BluetoothNotiBroadcastReceiver: onReceive
09-12 13:50:32.737  6375  6722 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:32.737  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-12 13:50:32.737  6375  6722 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 13:50:32.737  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:50:32.737  6375  6722 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-12 13:50:32.737  6375  6722 D BluetoothBondStateMachine: make
,09-12 13:50:32.737  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 13:50:32.737  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 13:50:32.737  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 13:50:32.737  6375  6727 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 13:50:32.737  1019  1479 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:32.737  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.737  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.737  1019  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.737  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.747  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:50:32.747  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:50:32.747  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 13:50:32.747  1019  3139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:32.747  6375  6375 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:50:32.747  1019  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-12 13:50:32.747  6375  6375 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:50:32.747  6375  6375 D BtGatt.GattService: start()
09-12 13:50:32.747  6375  6375 D BtGatt.GattService: start()
09-12 13:50:32.747  6375  6375 I bluedroid: get_profile_interface gatt
,09-12 13:50:32.747  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:32.747  6375  6375 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:50:32.747  1019  1052 I PowerManagerService: [PWL] Off : 50s ago
09-12 13:50:32.747  1019  1052 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-12 13:50:32.747  1019  1052 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-12 13:50:32.747  1019  1052 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1019, ws=null) (elapsedTime=8805)
09-12 13:50:32.747  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.747  1019  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.747  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.747  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:32.747  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 13:50:32.747  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:32.747  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:32.757  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:32.757  1019  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:32.757  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.757  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.757  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.757  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.767  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-12 13:50:32.767  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:50:32.767  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:50:32.767  1019  3141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:32.767  6375  6375 D BtGatt.GattService: mStartError = false
09-12 13:50:32.767  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:32.767  6375  6375 D HeadsetService: Received start request. Starting profile...
,09-12 13:50:32.767  6375  6375 D HeadsetService: start()
,09-12 13:50:32.767  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.767  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.767  6375  6375 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 13:50:32.767  1019  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:32.767  6375  6375 D HeadsetStateMachine: make
09-12 13:50:32.767  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.777  6375  6375 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 13:50:32.787  1019  1126 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-12 13:50:32.787  1019  1126 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.787  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-12 13:50:32.787  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:50:32.787  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-12 13:50:32.787  1019  1126 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.787  1019  1126 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.787  1019  1126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 13:50:32.787  1019  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:32.787  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.787  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.787  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:32.787  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.797  1019  1555 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 13:50:32.797  1019  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.797  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.797  1019  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.797  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 13:50:32.797  6375  6375 I bluedroid: get_profile_interface handsfree
09-12 13:50:32.797  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-12 13:50:32.797  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:50:32.797  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 13:50:32.797  1019  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:32.797  1019  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.797  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.797  1019  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.797  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.797  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 13:50:32.797  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:32.797  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:32.807  1019  1547 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:32.807  1019  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:50:32.807  1019  1547 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.807  1019  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.807  1019  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.817  6375  6375 I DualScoManager: Instantiating Dual Sco Manager
09-12 13:50:32.817  6375  6375 I DualScoManager: Set HeadsetServiceHelper
,09-12 13:50:32.817  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-12 13:50:32.817  1019  3139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:32.817  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:50:32.817  1019  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-12 13:50:32.817  6375  6722 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-12 13:50:32.817  6375  6375 D BluetoothAtMessage: createCMTIContentObservers
,09-12 13:50:32.817  1019  1032 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-12 13:50:32.817  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:32.817  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:32.817  1019  1032 D SettingsProvider: selectionArgs: false
09-12 13:50:32.817  1019  1032 D SettingsProvider: selectionArgs: 1002
09-12 13:50:32.817  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:32.817  1019  1032 D SettingsProvider: ret = -1
09-12 13:50:32.817  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:32.817  1019  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:32.817  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:32.817  6375  6730 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 13:50:32.827  6375  6375 D HeadsetService: mStartError = false
09-12 13:50:32.827  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:32.827  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:50:32.827  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService,
09-12 13:50:32.827  6375  6722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:32.827  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:32.827  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:32.827  6375  6722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-12 13:50:32.827  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:50:32.827  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:50:32.827  6375  6722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 13:50:32.827  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:50:32.827  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:50:32.827  6375  6722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 13:50:32.827  6375  6722 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-12 13:50:32.827  6375  6375 D A2dpService: Received start request. Starting profile...
09-12 13:50:32.827  6375  6375 D A2dpService: start()
09-12 13:50:32.827  6375  6730 D HeadsetStateMachine: Clear mHeadsetBrsf
09-12 13:50:32.827  6375  6730 D HeadsetStateMachine: map size, before remove : 0
09-12 13:50:32.827  6375  6730 D HeadsetStateMachine: map size, after remove: 0
,09-12 13:50:32.827  6375  6375 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 13:50:32.827  6375  6375 I bluedroid: get_profile_interface avrcp
,09-12 13:50:32.837  6375  6375 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:50:32.847  6375  6375 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 13:50:32.857  6375  6735 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 13:50:32.857  6375  6375 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 13:50:32.857  6375  6375 D A2dpStateMachine: make
,09-12 13:50:32.857  6375  6375 I bluedroid: get_profile_interface a2dp
,09-12 13:50:32.857  6375  6737 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-12 13:50:32.857  6375  6375 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 13:50:32.867  6375  6375 D A2dpService: mStartError = false
09-12 13:50:32.867  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:32.867  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-12 13:50:32.867  6375  6375 I BluetoothHidServiceJni: classInitNative: succeeds
09-12 13:50:32.867  1019  2712 D SSRM:n  : SIOP:: AP = 390
,09-12 13:50:32.867  6375  6736 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:50:32.867  6375  6375 D HidService: Received start request. Starting profile...
09-12 13:50:32.867  6375  6375 D HidService: start()
09-12 13:50:32.867  6375  6375 I bluedroid: get_profile_interface hidhost
09-12 13:50:32.867  6375  6375 D HidService: setHidService(): set to: null
09-12 13:50:32.867  6375  6375 D HidService: mStartError = false
09-12 13:50:32.867  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:32.867  6375  6375 D HeadsetStateMachine: Try to query the phonestate on bind
,09-12 13:50:32.867  1429  1453 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:50:32.867  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-12 13:50:32.867  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-12 13:50:32.877  1429  1453 I Telecom : BluetoothPhoneService: Result of Message : true
09-12 13:50:32.877  6375  6375 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 13:50:32.877  6375  6375 D HealthService: Received start request. Starting profile...
09-12 13:50:32.877  6375  6375 D HealthService: start()
,09-12 13:50:32.877  6375  6375 I bluedroid: get_profile_interface health
09-12 13:50:32.877  6375  6375 D HealthService: mStartError = false
09-12 13:50:32.877  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:32.877  6375  6375 D HeadsetStateMachine: Proxy object connected
09-12 13:50:32.877  6375  6375 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:50:32.887  6375  6375 D PanService: Received start request. Starting profile...
09-12 13:50:32.887  6375  6375 D PanService: start()
09-12 13:50:32.887  6375  6375 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:50:32.887  6375  6375 I bluedroid: get_profile_interface pan
09-12 13:50:32.887  6375  6735 D BluetoothMediaBrowser: no now playing list
09-12 13:50:32.887  6375  6735 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-12 13:50:32.887  6375  6375 D PanService: mStartError = false
09-12 13:50:32.887  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:32.887  6375  6375 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-12 13:50:32.887  1914  1914 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:50:32.887  6375  6730 D HeadsetStateMachine: Disconnected process message: 11
,09-12 13:50:32.887  6375  6375 D BluetoothMapService: Received start request. Starting profile...
09-12 13:50:32.887  6375  6375 D BluetoothMapService: start()
09-12 13:50:32.887  1914  1914 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:50:32.887  6375  6375 D BluetoothMapService: mStartError = false
09-12 13:50:32.887  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:32.887  6375  6375 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 13:50:32.887  6375  6375 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-12 13:50:32.887  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 13:50:32.897  6375  6730 D HeadsetStateMachine: Disconnected process message: 18
09-12 13:50:32.897  6375  6375 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
09-12 13:50:32.897  6375  6375 D SapService: Received start request. Starting profile...
09-12 13:50:32.897  6375  6375 D SapService: start()
09-12 13:50:32.897  6375  6375 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 13:50:32.897  6375  6375 I bluedroid: get_profile_interface sap
09-12 13:50:32.897  6375  6375 D SapService: mStartError = false
09-12 13:50:32.897  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:32.897  6375  6375 D BluetoothA2dp: Proxy object connected
09-12 13:50:32.897  6375  6375 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-12 13:50:32.897  6375  6375 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 13:50:32.897  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 13:50:32.897  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-12 13:50:32.897  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-12 13:50:32.897  6375  6730 D HeadsetStateMachine: Disconnected process message: 10
09-12 13:50:32.897  6375  6730 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-12 13:50:32.897  6375  6730 D HeadsetStateMachine: Disconnected process message: 11
09-12 13:50:32.897  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-12 13:50:32.917  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 13:50:32.917  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 13:50:32.927  6375  6722 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-12 13:50:32.927  6375  6722 I bluedroid: enable
,09-12 13:50:32.927  6375  6722 I bt_hci_bdroid: init
09-12 13:50:32.927  6375  6741 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-12 13:50:32.927  6375  6722 I bt_vendor: bt-vendor : init
09-12 13:50:32.927  6375  6722 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 13:50:32.927  6375  6722 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 13:50:32.927  6375  6722 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-12 13:50:32.927  6375  6722 D bt_userial_mct: userial_init
,09-12 13:50:32.927  6375  6722 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-12 13:50:32.927  6375  6722 I bt_vendor: Starting hciattach daemon
09-12 13:50:32.927  6375  6722 I bt_vendor: try to set false
,09-12 13:50:32.927  6375  6722 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 13:50:32.927  6375  6722 I bt_vendor: Starting hciattach daemon
09-12 13:50:32.927  6375  6722 I bt_vendor: try to set true
,09-12 13:50:32.947  6745  6745 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-12 13:50:32.997  6751  6751 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-12 13:50:33.007  6752  6752 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 13:50:33.017  6754  6754 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 13:50:33.027  6755  6755 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-12 13:50:33.037  6756  6756 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 13:50:33.047  6757  6757 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-12 13:50:33.087   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:50:33.107   287   287 E SMD     : DCD OFF
,09-12 13:50:33.337  6760  6760 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-12 13:50:33.347  6761  6761 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 13:50:33.387  6375  6722 I bt_vendor: bluetooth satus is on,
09-12 13:50:33.387  6375  6743 D bt_userial_mct: userial_open(port:0)
09-12 13:50:33.387  6375  6743 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-12 13:50:33.387  6375  6743 I bt_vendor: Done intiailizing UART,
,09-12 13:50:33.397  6375  6743 I bt_vendor: Done intiailizing UART,
09-12 13:50:33.397  6375  6743 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
09-12 13:50:33.397  6375  6743 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
09-12 13:50:33.397  6375  6763 D bt_userial_mct: Entering userial_read_thread(),
,09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_SAP
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_BTIF
09-12 13:50:33.397  6375  6741 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-12 13:50:33.497  6375  6741 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-12 13:50:33.507  6375  6741 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3e8b6e9 
,09-12 13:50:33.507  6375  6741 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3e8b6e9 
,09-12 13:50:33.517  6375  6725 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-12 13:50:33.527  6375  6725 E bt-btif : Calling BTA_HhEnable
,09-12 13:50:33.527  6375  6725 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 13:50:33.527  6375  6725 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 13:50:33.527  6375  6725 E BluetoothServiceJni: populateRssiValuesNative
,09-12 13:50:33.527  6375  6725 I bluedroid: getModelRssiValues
09-12 13:50:33.527  6375  6725 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 13:50:33.527  6375  6725 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:50:33.527  1019  1019 D SettingsProvider: name = bluetooth_name
,09-12 13:50:33.527  6375  6725 D BluetoothAdapterProperties: Name is: A5-1
,09-12 13:50:33.537  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:33.537  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:33.537  6375  6725 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 13:50:33.547  6375  6725 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:50:33.547  6375  6725 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:50:33.547  6375  6725 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-12 13:50:33.547  6375  6725 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-12 13:50:33.547  6375  6725 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-12 13:50:33.547  6375  6725 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 13:50:33.547  6375  6725 E bt-btif : btif_sock_init: !vhci_init
,09-12 13:50:33.547  6375  6725 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-12 13:50:33.547  6375  6725 D IOP_DB_BT: db_open: db_open : handle 3027689488l, read 13894 bytes onto local cache
09-12 13:50:33.547  6375  6725 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-12 13:50:33.547  6375  6725 D IOP_DB_BT: db_query: result 1
09-12 13:50:33.547  6375  6725 I         : iop_db_open: iop_db_open status 0
09-12 13:50:33.547  6375  6725 D bte_conf: Device ID record 1 : primary
09-12 13:50:33.547  6375  6725 D bte_conf:   vendorId            = 0075
09-12 13:50:33.547  6375  6725 D bte_conf:   vendorIdSource      = 0001
09-12 13:50:33.547  6375  6725 D bte_conf:   product             = 0100
09-12 13:50:33.547  6375  6725 D bte_conf:   version             = 0200
09-12 13:50:33.547  6375  6725 D bte_conf:   clientExecutableURL = 
09-12 13:50:33.547  6375  6725 D bte_conf:   serviceDescription  = 
09-12 13:50:33.547  6375  6725 D bte_conf:   documentationURL    = 
09-12 13:50:33.547  6375  6725 D bte_conf: bte_load_did_conf no section named DID2.
,09-12 13:50:33.547  6375  6722 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 13:50:33.547  6375  6722 D BluetoothAdapterProperties: ScanMode =  20
,09-12 13:50:33.547  6375  6722 D BluetoothAdapterProperties: State =  11,
09-12 13:50:33.547  6375  6725 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
09-12 13:50:33.547  1019  5323 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 13:50:33.547  6375  6722 D BluetoothAdapterProperties: Setting state to 12
,09-12 13:50:33.547  6375  6722 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12,
09-12 13:50:33.547  6375  6763 E bt_mct  : hci lib postload completed
,09-12 13:50:33.557  6375  6725 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:50:33.557  6375  6725 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:50:33.557  6375  6725 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:50:33.557  1019  1480 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-12 13:50:33.557  1019  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:33.557  1019  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:33.557  1019  1480 D SettingsProvider: selectionArgs: false
09-12 13:50:33.557  1019  1480 D SettingsProvider: selectionArgs: 1002
09-12 13:50:33.557  1019  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:33.557  1019  1480 D SettingsProvider: ret = -1
,09-12 13:50:33.557  6375  6722 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:50:33.557  6375  6722 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 13:50:33.557  1019  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:33.557  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.557  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:33.557  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,09-12 13:50:33.557  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.567  6375  6722 D BluetoothAdapterService: Autoconnection is available 
09-12 13:50:33.567  6375  6722 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 13:50:33.567  6375  6722 D BluetoothAdapterService: starting service from this receiver
,09-12 13:50:33.567  1019  1126 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:33.567  1019  1126 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.567  1019  1126 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:33.567  6375  6731 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:33.567  6375  6731 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:50:33.567  1019  1126 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.567  1019  1126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:50:33.567  1295  1306 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:50:33.567  6375  6722 I BluetoothAdapterState: Entering On State from state = 11
,09-12 13:50:33.577  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-12 13:50:33.577  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.577  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:33.577  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:33.577  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:33.577  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:33.577  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:33.577  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:33.577  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:33.577  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:33.577  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.577  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.577  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-12 13:50:33.577  1459  1473 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:33.577  1459  1473 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:50:33.577  1295  1303 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:50:33.577  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-12 13:50:33.577  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.587  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:33.587  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:33.587  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.587  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:50:33.587  6375  6375 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 13:50:33.587  1429  1469 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:33.587  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:33.587  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:33.597  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.597  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.597  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.597  1429  1469 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:33.597  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:33.597  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:33.597  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:33.597  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:33.597  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:33.597  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:33.597  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:33.597  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:33.597  1443  1458 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:50:33.597  1443  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:33.597  1295  1306 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:50:33.597  1295  1306 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:33.607  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:50:33.607  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.607  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.607  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.607  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.607  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:50:33.607  1295  1295 D BluetoothPbap: Proxy object connected
09-12 13:50:33.607  1295  1295 D PbapServerProfile: Bluetooth service connected
,09-12 13:50:33.607  6375  6375 I BluetoothPbapService: Handler(): got msg=1
09-12 13:50:33.607  1429  2710 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:33.607  1429  2710 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:33.607  1295  1303 D Bluetoothsap: onBluetoothStateChange: up=true
09-12 13:50:33.607  1295  1303 D Bluetoothsap: Binding service...
09-12 13:50:33.607  1295  1295 D BluetoothA2dp: Proxy object connected
09-12 13:50:33.607  1295  1295 D A2dpProfile: Bluetooth service connected
,09-12 13:50:33.607  1019  1480 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 13:50:33.617  1295  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 13:50:33.617  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 13:50:33.617  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.617  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.617  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.617  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.617  1295  1303 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 13:50:33.617  1295  1306 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 13:50:33.617  1295  1295 D BluetoothMap: Proxy object connected
09-12 13:50:33.617  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-12 13:50:33.617  1295  1295 D MapProfile: Bluetooth service connected
09-12 13:50:33.617  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-12 13:50:33.617  1295  1295 D BluetoothMap: getConnectedDevices()
,09-12 13:50:33.627  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.627  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.627  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-12 13:50:33.627  6375  6768 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-12 13:50:33.627  1295  1295 D Bluetoothsap: BluetoothSAP Proxy object connected
09-12 13:50:33.627  1295  1295 D SapProfile: Bluetooth service connected
09-12 13:50:33.627  1295  1295 D Bluetoothsap: getConnectedDevices()
09-12 13:50:33.627  1019  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:33.627  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:33.627  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:33.627  6375  6768 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:50:33.627  6375  6768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:50:33.627  1019  1049 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:33.627  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:50:33.627  6375  6768 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-12 13:50:33.627  6375  6768 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:50:33.627  6375  6768 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:50:33.627  6375  6768 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@219539e7
09-12 13:50:33.627  1019  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 13:50:33.627  6375  6768 D BluetoothSocket: channel: 19
09-12 13:50:33.627  6375  6768 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-12 13:50:33.627  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-12 13:50:33.627  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 13:50:33.627  1295  1295 D BluetoothInputDevice: Proxy object connected
09-12 13:50:33.627  1295  1295 D HidProfile: Bluetooth service connected
09-12 13:50:33.627  1295  6766 D BluetoothPan: Binding service...
,09-12 13:50:33.637  1019  1019 D BluetoothA2dp: Proxy object connected
,09-12 13:50:33.637  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 13:50:33.637  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.637  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.637  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.637  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.637  2852  2860 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:50:33.637  1295  1295 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:50:33.637  2852  2860 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:33.637  1295  1295 D PanProfile: Bluetooth service connected
,09-12 13:50:33.637  1019  1049 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:50:33.637  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.637  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.637  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.637  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.647  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:50:33.647  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 13:50:33.647  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:50:33.647  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 13:50:33.647  1019  1049 D BluetoothPan: Binding service...
09-12 13:50:33.647  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
09-12 13:50:33.647  1429  1469 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 13:50:33.647  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:33.647  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:33.647  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:50:33.647  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.647  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-12 13:50:33.647  2852  2852 D BluetoothA2dp: Proxy object connected
09-12 13:50:33.647  1429  1469 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 13:50:33.647  6375  6384 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:50:33.647  1182  1193 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:33.647  1182  1193 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:50:33.647  6250  6261 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:33.647  6250  6261 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:33.647  2852  6769 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:33.647  2852  6769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:50:33.647  1295  1306 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:33.647  1295  1306 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:50:33.647  1914  1925 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:33.647  1914  1925 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:33.647  1295  6766 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:33.647  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:33.647  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:33.657  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.657  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.657  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.657  1295  6766 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:33.657  1295  1295 D HeadsetProfile: Bluetooth service connected
,09-12 13:50:33.657  1429  1469 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:33.657  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 13:50:33.657  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:33.657  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.657  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.657  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.657  1429  1469 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:33.657  2852  2864 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:33.817  1019  1049 I art     : Explicit concurrent mark sweep GC freed 68152(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.484ms total 152.071ms
09-12 13:50:33.817  1019  1049 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:33.817  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:33.817  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.817  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.817  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.817  2852  2864 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 13:50:33.817  6155  6164 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:50:33.817  6155  6164 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:33.817  1459  1473 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:33.817  1019  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:33.817  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:33.817  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.817  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.817  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.817  1459  1473 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:33.817  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 13:50:33.817  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:50:33.827  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:33.827  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
09-12 13:50:33.827  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:50:33.827  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1cd1ae82, true
,09-12 13:50:33.827  1429  1429 D BluetoothHeadset: registerMessageListener
,09-12 13:50:33.837  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:50:33.837  1802  1802 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:50:33.837  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 13:50:33.837  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:33.837  1182  1182 D BluetoothTile:  getBluetoothState : 12
,09-12 13:50:33.837  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:33.837  1295  1295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:33.847  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:33.847  1019  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:33.847  1019  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:50:33.847  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.847  1019  1547 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-12 13:50:33.847  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:33.847  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.847  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:33.847  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:33.847  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:33.847  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:33.847  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:33.857  1295  1295 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-12 13:50:33.857  6375  6383 D HeadsetService: registerMessageListener
09-12 13:50:33.857  1295  1295 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,09-12 13:50:33.857  1295  1295 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 13:50:33.857  1295  1295 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-12 13:50:33.857  6375  6383 D HeadsetService: registerMessageListener
,09-12 13:50:33.857  6375  6730 D HeadsetStateMachine: Disconnected process message: 70,
09-12 13:50:33.857  6375  6730 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@33d83994
09-12 13:50:33.857  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-12 13:50:33.857  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 13:50:33.857  6375  6771 D BluetoothMapMasInstance: set MAP SDP message type : 1,
,09-12 13:50:33.867  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-12 13:50:33.867  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-12 13:50:33.867  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 13:50:33.867  6375  6771 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:50:33.867  6375  6771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:50:33.867  1295  1295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:50:33.867  6375  6771 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-12 13:50:33.867  1019  3132 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 13:50:33.867  6375  6771 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:50:33.867  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-12 13:50:33.867  6375  6771 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:50:33.867  6375  6771 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1113cc3d
09-12 13:50:33.867  6375  6771 D BluetoothSocket: channel: 5
09-12 13:50:33.867  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.867  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.867  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:50:33.877  6375  6730 D HeadsetStateMachine: Disconnected process message: 9
09-12 13:50:33.877  6375  6730 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 13:50:33.887   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-12 13:50:33.887   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 13:50:33.887   282   282 V voice   : voice_set_parameters: exit with code(-2)
09-12 13:50:33.887   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 13:50:33.887   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 13:50:33.887   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 13:50:33.887   282   282 V audio_hw_primary: adev_set_parameters: exit
,09-12 13:50:33.887  6375  6730 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 13:50:33.887  1295  1295 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:50:33.887  1295  1295 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:50:33.897  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:33.897  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 13:50:33.907  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:33.907  6375  6375 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 13:50:33.907  1019  1547 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:33.907  1019  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.907  1019  1547 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.907  1019  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:33.907  1019  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:33.927  1914  1914 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:50:33.927  1019  3138 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:50:33.927  1019  3138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 13:50:33.927  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:33.927  1019  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:33.927  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:33.937  1914  6778 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 13:50:33.937  1019  3132 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 13:50:33.947  1914  1914 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:50:33.947  1019  3141 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:33.947  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:33.947  1019  3141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:33.947  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:33.957  6375  6782 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:50:33.957  6375  6782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:50:33.967  6375  6782 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,09-12 13:50:33.967  6375  6782 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:50:33.967  6375  6782 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:50:33.967  6375  6782 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a75ef39
09-12 13:50:33.967  6375  6782 D BluetoothSocket: channel: 12
09-12 13:50:33.967  6375  6782 I BtOppRfcommListener: Accept thread started.
,09-12 13:50:33.977  1019  3138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:33.977  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:33.977  1019  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:50:33.977  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:33.987  1914  6778 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-12 13:50:34.087   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-12 13:50:35.597  6155  6207 D BluetoothAdapter: disable()
,09-12 13:50:35.607  1019  1555 D SettingsProvider: name = bluetooth_on
,09-12 13:50:35.617  6375  6722 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-12 13:50:35.617  6375  6722 D BluetoothAdapterProperties: Setting state to 13
09-12 13:50:35.617  6375  6722 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:50:35.617  6375  6722 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:50:35.617  6375  6722 D BluetoothAdapterService: updateAdapterState state is 13
,09-12 13:50:35.617  1019  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:35.617  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:50:35.617  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:35.617  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:35.617  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:35.617  6375  6722 D BluetoothAdapterService: Autoconnection is available 
,09-12 13:50:35.617  6375  6722 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,09-12 13:50:35.617  6375  6722 D BluetoothAdapterService: terminating service from this receiver
,09-12 13:50:35.627  6375  6375 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-12 13:50:35.627  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-12 13:50:35.627  6375  6375 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2230697e, channel: 19, state: LISTENING
09-12 13:50:35.627  1019  1019 I InputMethodManagerService: [BT Setting State] State =13
,09-12 13:50:35.627  6375  6375 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2230697e, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@219539e7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24357edfmSocket: android.net.LocalSocket@36e9272c impl:android.net.LocalSocketImpl@233d45f5 fd:FileDescriptor[75]
09-12 13:50:35.627  6375  6375 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36e9272c impl:android.net.LocalSocketImpl@233d45f5 fd:FileDescriptor[75]
,09-12 13:50:35.627  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:50:35.637  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:50:35.637  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:35.637  1182  1182 D BluetoothTile:  getBluetoothState : 13
,09-12 13:50:35.637  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:35.637  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:35.637  1019  1555 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:35.637  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:50:35.647  1802  1802 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 13:50:35.647  1019  1126 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:50:35.647  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:50:35.647  1295  1295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:35.657  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:35.657  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:50:35.657  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:35.657  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:50:35.657  1019  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:35.657  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:35.657  1019  1547 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:35.657  1019  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:35.657  1019  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:35.667  6155  6155 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:50:35.667  6375  6722 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:50:35.667  6375  6722 D BluetoothAdapterProperties: mDiscovering is false
09-12 13:50:35.667  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:35.667  1019  3138 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 13:50:35.667  1295  1295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:50:35.667  6375  6722 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 13:50:35.667  1019  3141 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 13:50:35.667  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:50:35.667  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:35.667  1019  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:35.667  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:50:35.677  1019  3139 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:50:35.677  1019  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:50:35.677  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:35.677  1019  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:35.677  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:35.677  1295  1295 D BluetoothPbap: Proxy object disconnected
09-12 13:50:35.677  1295  1295 D PbapServerProfile: Bluetooth service disconnected
,09-12 13:50:35.687  6375  6725 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:50:35.687  6375  6725 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:50:35.687  1295  1295 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:50:35.687  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:35.687  6375  6722 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 13:50:35.687  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:35.687  6375  6722 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-12 13:50:35.697  6375  6722 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-12 13:50:35.697  6375  6722 E bt-btif : BTM_SEC_CLR[17]: id 57
,09-12 13:50:35.697  6375  6722 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 13:50:35.697  6375  6741 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,09-12 13:50:35.697  6375  6741 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-12 13:50:35.697  6375  6741 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 13:50:35.697  6375  6741 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:50:35.697  6375  6741 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 13:50:35.697  1295  1295 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:50:35.697  6375  6782 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 13:50:35.707  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:35.707  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 13:50:35.707  6375  6375 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ce59f8a, channel: 5, state: LISTENING
,09-12 13:50:35.707  6375  6375 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ce59f8a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1113cc3d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@131d29fbmSocket: android.net.LocalSocket@39578a18 impl:android.net.LocalSocketImpl@3ce94c71 fd:FileDescriptor[77]
,09-12 13:50:35.707  6375  6375 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@39578a18 impl:android.net.LocalSocketImpl@3ce94c71 fd:FileDescriptor[77]
,09-12 13:50:35.707  6375  6375 I BtOppRfcommListener: stopping Accept Thread
09-12 13:50:35.707  6375  6375 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15062a56, channel: 12, state: LISTENING
09-12 13:50:35.707  6375  6375 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15062a56, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a75ef39, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@290a6ad7mSocket: android.net.LocalSocket@1f472fc4 impl:android.net.LocalSocketImpl@37753ead fd:FileDescriptor[81]
09-12 13:50:35.707  6375  6375 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1f472fc4 impl:android.net.LocalSocketImpl@37753ead fd:FileDescriptor[81]
,09-12 13:50:35.707  6375  6782 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:50:35.727  6375  6375 V BluetoothOppManager: cleanUp...
,09-12 13:50:35.737  1914  1914 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:50:35.737  1914  1914 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:50:35.897  6375  6741 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:50:35.897  6375  6741 W bt-btif : ag scb idx 1 not allocated
09-12 13:50:35.897  6375  6741 W bt-btif : ag scb idx 2 not allocated
09-12 13:50:35.897  6375  6741 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 13:50:35.897  6375  6763 I bt_userial_mct: exiting userial_read_thread
09-12 13:50:35.897  6375  6763 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 13:50:35.897  6375  6725 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 13:50:35.897  6375  6743 I bt_vendor: hw_epilog_process
09-12 13:50:35.897  6375  6725 D bt_userial_mct: userial_close
09-12 13:50:35.897  6375  6725 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 13:50:36.107   287   287 E SMD     : DCD OFF,
,09-12 13:50:36.497  6375  6725 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-12 13:50:36.497  6375  6725 I bt_vendor: bluetooth satus is on
,09-12 13:50:36.497  6375  6725 I bt_vendor: bt-vendor : resetting BT status
09-12 13:50:36.497  6375  6725 I bt_vendor: Starting hciattach daemon
,09-12 13:50:36.497  6375  6725 I bt_vendor: try to set false
,09-12 13:50:36.507  6375  6725 I bt_vendor: Starting hciattach daemon
,09-12 13:50:36.507  6375  6725 I bt_vendor: try to set false
,09-12 13:50:36.507  6375  6725 I bt_vendor: cleanup
,09-12 13:50:36.507  6375  6741 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-12 13:50:36.507  6375  6725 I GKI_LINUX: GKI_exit_task 0 done,
09-12 13:50:36.507  6375  6725 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-12 13:50:36.517  6375  6722 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-12 13:50:36.517  6375  6722 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 13:50:36.517  6375  6722 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 13:50:36.517  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 13:50:36.517  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 13:50:36.517  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 13:50:36.517  1019  1547 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:36.517  1019  1547 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.517  1019  1547 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:50:36.517  1019  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.517  1019  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:50:36.517  6375  6375 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:50:36.517  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:50:36.517  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:50:36.517  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 13:50:36.517  1019  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:36.517  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-12 13:50:36.517  6375  6375 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:50:36.517  6375  6375 D BtGatt.GattService: stop()
09-12 13:50:36.517  6375  6375 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 13:50:36.517  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:36.517  1019  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.517  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:36.517  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 13:50:36.517  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:36.517  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:36.517  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:36.527  1019  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:36.527  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.527  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:36.527  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.527  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:36.527  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-12 13:50:36.527  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:50:36.527  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:50:36.527  1019  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:36.527  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.527  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:36.527  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.527  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:36.527  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-12 13:50:36.527  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:50:36.527  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:50:36.527  1019  3141 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:36.527  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.537  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:36.537  1019  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.537  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:36.537  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-12 13:50:36.537  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:50:36.537  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 13:50:36.537  1019  5323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:36.537  1019  5323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.537  1019  5323 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:36.537  1019  5323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.537  1019  5323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:36.537  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:36.537  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:36.537  6375  6722 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:36.537  1019  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:36.537  1019  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.547  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:36.547  1019  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.547  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-12 13:50:36.547  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 13:50:36.547  1019  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:36.547  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.547  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:36.547  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.547  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:50:36.547  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:36.547  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:50:36.547  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:50:36.547  6375  6722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:50:36.547  6375  6722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 13:50:36.547  6375  6722 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 13:50:36.547  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-12 13:50:36.547  6375  6375 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:50:36.547  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:36.557  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-12 13:50:36.557  1295  1295 D HeadsetProfile: Bluetooth service disconnected,
,09-12 13:50:36.557  6375  6375 D A2dpService: Received stop request...Stopping profile...
,09-12 13:50:36.557  6375  6736 D A2dpStateMachine: Exit Disconnected: -1
,09-12 13:50:36.557  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:36.557  1019  1019 D BluetoothA2dp: Proxy object disconnected
09-12 13:50:36.557  1019  1019 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 13:50:36.557  1295  1295 D BluetoothA2dp: Proxy object disconnected
09-12 13:50:36.557  1295  1295 D A2dpProfile: Bluetooth service disconnected
,09-12 13:50:36.567  2852  2852 D BluetoothA2dp: Proxy object disconnected
09-12 13:50:36.567  6375  6375 D HidService: Received stop request...Stopping profile...
,09-12 13:50:36.567  6375  6375 D HidService: Stopping Bluetooth HidService
09-12 13:50:36.567  6375  6375 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 13:50:36.567  6375  6375 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 13:50:36.567  6375  6375 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 13:50:36.567  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:36.567  6375  6375 D HealthService: Received stop request...Stopping profile...
,09-12 13:50:36.567  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:36.567  1295  1295 D BluetoothInputDevice: Proxy object disconnected
09-12 13:50:36.567  1295  1295 D HidProfile: Bluetooth service disconnected
,09-12 13:50:36.567  6375  6375 D PanService: Received stop request...Stopping profile...
09-12 13:50:36.567  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:36.567  1019  1019 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 13:50:36.567  1295  1295 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 13:50:36.567  1295  1295 D PanProfile: Bluetooth service disconnected
09-12 13:50:36.567  6375  6375 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 13:50:36.577  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:36.577  6375  6375 D SapService: Received stop request...Stopping profile...
,09-12 13:50:36.577  6375  6375 D SapService: Stopping Bluetooth SapService
,09-12 13:50:36.577  6375  6375 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:36.577  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-12 13:50:36.577  6375  6375 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:50:36.577  6375  6375 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 13:50:36.577  1295  1295 D BluetoothMap: Proxy object disconnected
09-12 13:50:36.577  1295  1295 D MapProfile: Bluetooth service disconnected
,09-12 13:50:36.577  1295  1295 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 13:50:36.577  1295  1295 D SapProfile: Bluetooth service disconnected
,09-12 13:50:36.577  6375  6375 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:50:36.577  6375  6375 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:50:36.577  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 13:50:36.577  6375  6375 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:50:36.577  6375  6375 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 13:50:36.577  6375  6375 D BluetoothA2dp: Proxy object disconnected
09-12 13:50:36.577  6375  6375 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-12 13:50:36.587  6375  6737 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-12 13:50:36.587  6375  6375 I GKI_LINUX: GKI_exit_task 2 done
09-12 13:50:36.587  6375  6375 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 13:50:36.587  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 13:50:36.587  6375  6375 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:36.587  6375  6375 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:36.587  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 13:50:36.587  6375  6375 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:36.587  6375  6375 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:36.587  6375  6375 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:50:36.587  6375  6375 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:50:36.587  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 13:50:36.587  6375  6375 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:36.587  6375  6375 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:36.587  6375  6375 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-12 13:50:36.587  6375  6375 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:50:36.587  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 13:50:36.587  6375  6375 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:50:36.587  6375  6375 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-12 13:50:36.587  6375  6375 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-12 13:50:36.587  6375  6375 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 13:50:36.587  6375  6375 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 13:50:36.587  6375  6722 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-12 13:50:36.587  6375  6722 D BluetoothAdapterProperties: Setting state to 10
09-12 13:50:36.587  6375  6722 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 13:50:36.587  6375  6722 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 13:50:36.587  6375  6722 D BluetoothAdapterService: updateAdapterState state is 10
09-12 13:50:36.587  6375  6722 D BluetoothAdapterService: Autoconnection is available 
,09-12 13:50:36.587  6375  6722 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 13:50:36.587  6375  6722 I BluetoothAdapterState: Entering OffState
09-12 13:50:36.587  6375  6731 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:36.587  6375  6731 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.587  1295  1306 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:50:36.587  1459  1746 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:36.587  1459  1746 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.587  1295  1303 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:50:36.597  1443  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:36.597  1443  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.597  1295  6766 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:50:36.597  1429  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:36.597  1429  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.597  1295  1306 D Bluetoothsap: onBluetoothStateChange: up=false
09-12 13:50:36.597  1295  1306 D Bluetoothsap: Unbinding service...
,09-12 13:50:36.597  1295  1303 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 13:50:36.597  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:50:36.597  2852  2860 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:50:36.597  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:36.597  1019  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.607  6375  6384 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:50:36.607  1182  1201 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:36.607  1182  1201 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.607  6250  6261 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:36.607  6250  6261 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.607  2852  6769 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:36.607  2852  6769 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.607  1295  1306 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:36.607  1295  1306 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.607  1914  1929 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:50:36.607  1914  1929 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:50:36.607  6155  6164 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:50:36.607  6155  6164 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:50:36.607  6155  6164 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-12 13:50:36.607  6155  6164 D BluetoothLeAdvertiser: Exit stop advertising
09-12 13:50:36.607  6155  6164 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 13:50:36.607  6155  6164 D BluetoothLeScanner: Exiting stopAllScan
,09-12 13:50:36.617  1019  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-12 13:50:36.617  1019  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-12 13:50:36.617  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:36.617  1019  1019 I InputMethodManagerService: [BT Setting State] State =10
09-12 13:50:36.617  1019  1019 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:50:36.627  6375  6725 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-12 13:50:36.627  6375  6375 I GKI_LINUX: GKI_exit_task 1 done
09-12 13:50:36.627  6375  6375 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-12 13:50:36.627  6375  6375 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 13:50:36.627  6375  6375 I art     : System.exit called, status: 0
09-12 13:50:36.627  6375  6375 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:50:36.627  1182  1182 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:36.627  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:50:36.627  1182  1729 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
,09-12 13:50:36.627  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:36.627  1182  1182 D BluetoothTile:  getBluetoothState : 10
09-12 13:50:36.627  1182  1729 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:36.627  1182  1182 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:36.627  1182  1182 D BluetoothAdapter: 436165973: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:36.627  1019  1126 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:36.627  1802  1802 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:50:36.627  1019  3138 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:50:36.627  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:50:36.627  1914  2128 D BluetoothAdapter: 332330329: getState() :  mService = null. Returning STATE_OFF
09-12 13:50:36.627  1914  2128 D BluetoothAdapter: 332330329: getState() :  mService = null. Returning STATE_OFF
,09-12 13:50:36.637  1295  1295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:36.637  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:36.637  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:36.637  1019  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:50:36.637  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.637  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:36.637  1019  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:36.637  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:36.647  1295  1295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:50:36.647  1019  3132 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 13:50:36.647  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.647  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:36.647  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:36.647  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:50:36.667  1295  1295 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:50:36.667  1295  1295 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:50:36.667  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:36.667  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 13:50:36.667  1019  1480 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 13:50:36.677  1019  1480 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 13:50:36.677  1019  1480 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-12 13:50:36.677  1019  1480 W BroadcastQueue: android.os.TransactionTooLargeException
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-12 13:50:36.677  1019  1480 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:50:36.677  1019  1480 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-12 13:50:36.677  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:36.677  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:36.677  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:36.677  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:36.697  6799  6799 E Zygote  : MountEmulatedStorage()
09-12 13:50:36.697  6799  6799 E Zygote  : v2
,09-12 13:50:36.697  6799  6799 I libpersona: KNOX_SDCARD checking this for 1002
09-12 13:50:36.697  6799  6799 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:36.697  1019  1480 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6799 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-12 13:50:36.697  6799  6799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:36.707  6799  6799 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:50:36.707  6799  6799 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:36.717  6799  6799 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:36.727  6799  6799 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:36.737  6799  6799 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-12 13:50:36.737  6799  6799 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:50:36.757  6799  6799 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding GattService
,09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding HeadsetService
09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding A2dpService
09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding HidService
09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding HealthService
09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding PanService
,09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding SapService
09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding SapClientService
09-12 13:50:36.797  6799  6799 D BtSettings.ProfileConfig: Adding HidDevService
09-12 13:50:36.797  6799  6799 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-12 13:50:36.807  1019  1032 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-12 13:50:36.807  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:50:36.807  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:36.807  1019  1032 D SettingsProvider: selectionArgs: false
09-12 13:50:36.807  1019  1032 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:36.807  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:50:36.807  1019  1032 D SettingsProvider: ret = -1
,09-12 13:50:36.807  1019  1547 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-12 13:50:36.807  1019  1547 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.807  1019  1547 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:36.807  1019  1547 D SettingsProvider: selectionArgs: false
,09-12 13:50:36.807  1019  1547 D SettingsProvider: selectionArgs: 1002
09-12 13:50:36.807  1019  1547 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:50:36.807  1019  1547 D SettingsProvider: ret = -1
,09-12 13:50:36.807  1019  1253 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:36.807  1019  1253 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.807  1019  1253 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:36.807  1019  1253 D SettingsProvider: selectionArgs: false
,09-12 13:50:36.807  1019  1253 D SettingsProvider: selectionArgs: 1002
09-12 13:50:36.807  1019  1253 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:36.807  1019  1253 D SettingsProvider: ret = -1
,09-12 13:50:36.807  1019  1545 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-12 13:50:36.807  1019  1545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.807  1019  1545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:50:36.807  1019  1545 D SettingsProvider: selectionArgs: false
09-12 13:50:36.807  1019  1545 D SettingsProvider: selectionArgs: 1002
09-12 13:50:36.807  1019  1545 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:50:36.807  1019  1545 D SettingsProvider: ret = -1
09-12 13:50:36.817  1019  1555 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-12 13:50:36.817  1019  1555 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:50:36.817  1019  1555 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:36.817  1019  1555 D SettingsProvider: selectionArgs: false
09-12 13:50:36.817  1019  1555 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:36.817  1019  1555 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:36.817  1019  1555 D SettingsProvider: ret = -1
,09-12 13:50:36.817  1019  1321 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-12 13:50:36.817  1019  1321 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.817  1019  1321 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:50:36.817  1019  1321 D SettingsProvider: selectionArgs: false
09-12 13:50:36.817  1019  1321 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:36.817  1019  1321 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:36.817  1019  1321 D SettingsProvider: ret = -1
,09-12 13:50:36.817  1019  1031 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-12 13:50:36.817  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.817  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:50:36.817  1019  1031 D SettingsProvider: selectionArgs: false
09-12 13:50:36.817  1019  1031 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:36.817  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:36.817  1019  1031 D SettingsProvider: ret = -1
,09-12 13:50:36.817  1019  5323 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-12 13:50:36.817  1019  5323 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.817  1019  5323 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:36.817  1019  5323 D SettingsProvider: selectionArgs: false
,09-12 13:50:36.817  1019  5323 D SettingsProvider: selectionArgs: 1002
09-12 13:50:36.817  1019  5323 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:50:36.817  1019  5323 D SettingsProvider: ret = -1
,09-12 13:50:36.827  1019  3132 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:50:36.827  1019  3132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.827  1019  3132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:36.827  1019  3132 D SettingsProvider: selectionArgs: false
,09-12 13:50:36.827  1019  3132 D SettingsProvider: selectionArgs: 1002
09-12 13:50:36.827  1019  3132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:50:36.827  1019  3132 D SettingsProvider: ret = -1
,09-12 13:50:36.827  1019  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-12 13:50:36.827  1019  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.827  1019  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:36.827  1019  1480 D SettingsProvider: selectionArgs: false
09-12 13:50:36.827  1019  1480 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:36.827  1019  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:36.827  1019  1480 D SettingsProvider: ret = -1
,09-12 13:50:36.827  1019  1126 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-12 13:50:36.827  1019  1126 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.827  1019  1126 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:36.827  1019  1126 D SettingsProvider: selectionArgs: false
09-12 13:50:36.827  1019  1126 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:36.827  1019  1126 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:36.827  1019  1126 D SettingsProvider: ret = -1
,09-12 13:50:36.827  1019  3138 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-12 13:50:36.827  1019  3138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:36.827  1019  3138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:50:36.827  1019  3138 D SettingsProvider: selectionArgs: false
09-12 13:50:36.827  1019  3138 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:36.837  1019  3138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:50:36.837  1019  3138 D SettingsProvider: ret = -1
,09-12 13:50:36.847  1914  1914 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:50:36.847  1019  1253 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:50:36.847  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 13:50:36.847  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:36.847  1019  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:36.847  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:36.857  1914  6815 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 13:50:36.857  1914  1914 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:50:36.867  1019  3138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:36.867  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:36.867  1019  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:36.867  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:36.877  1914  6815 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-12 13:50:38.617  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:50:38.617  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:39.107   287   287 E SMD     : DCD OFF
,09-12 13:50:41.447  1019  1479 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:50:41.447  1019  1479 D BatteryService: level:87, scale:100, status:2, health:2, present:true, voltage: 4153, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-12 13:50:41.447  1019  1479 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
09-12 13:50:41.447  1019  1479 D BatteryService: stay LED for charging
,09-12 13:50:41.447  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-12 13:50:41.457  1019  1019 I MotionRecognitionService: Plugged,
,09-12 13:50:41.457  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
09-12 13:50:41.457  1182  1182 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:50:41.457  1182  1182 D KeyguardUpdateMonitor: handleBatteryUpdate
09-12 13:50:41.457  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:50:41.457  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 87
,09-12 13:50:41.477  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:41.477  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
09-12 13:50:41.477  1182  1182 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:87 status:2 health:2
,09-12 13:50:41.617  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-12 13:50:41.617  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8f25de7 added. We now have 6 listener(s)
09-12 13:50:41.617  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:41.617  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:41.617  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f788d94 added. We now have 7 listener(s)
09-12 13:50:41.617  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:50:41.617  6155  6207 I System.out: IsBluetoothEnabled
09-12 13:50:41.617  6155  6207 D BluetoothAdapter: disable()
09-12 13:50:41.617  1019  1031 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-12 13:50:41.627  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 13:50:41.627  1019  3132 W ActivityManager: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
09-12 13:50:41.627  6155  6207 D BluetoothAdapter: enable(),
09-12 13:50:41.627  1019  3132 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:41.627  1019  3132 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 13:50:41.627  1019  3132 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:50:41.627  1019  3132 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:50:41.627  1019  3132 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-12 13:50:41.627  1019  3132 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-12 13:50:41.627  1019  3132 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-12 13:50:41.627  1019  3132 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:50:41.627  1019  3132 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 13:50:41.627  1019  3132 D SettingsProvider: name = bluetooth_on
,09-12 13:50:41.637  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 13:50:41.637  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:41.637  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-12 13:50:41.637  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-12 13:50:41.677  6799  6799 D BluetoothAdapterState: make
,09-12 13:50:41.677  6799  6799 I bluedroid: init
09-12 13:50:41.677  6799  6821 I BluetoothAdapterState: Entering OffState
,09-12 13:50:41.687  6799  6799 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 13:50:41.687  6799  6799 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 13:50:41.687  6799  6799 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 13:50:41.687  6799  6799 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 13:50:41.687  6799  6799 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-12 13:50:41.687  6799  6799 I bluedroid: get_profile_interface socket
09-12 13:50:41.687  6799  6799 I bluedroid: get_profile_interface map_client
,09-12 13:50:41.687  6799  6799 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-12 13:50:41.697  6799  6824 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-12 13:50:41.707  6799  6824 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 13:50:41.707  6799  6824 E BluetoothServiceJni: populateRssiValuesNative
09-12 13:50:41.707  6799  6824 I bluedroid: getModelRssiValues
,09-12 13:50:41.707  6799  6824 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-12 13:50:41.707  6799  6824 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:50:41.707  6799  6824 D BluetoothAdapterProperties: Name is: A5-1
,09-12 13:50:41.707  1019  1019 D SettingsProvider: name = bluetooth_name
,09-12 13:50:41.707  6799  6799 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:41.707  1019  1321 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-12 13:50:41.707  1019  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.717  1019  1321 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:41.717  1019  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.717  1019  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.717  6799  6813 I bluedroid: config_hci_snoop_log
,09-12 13:50:41.717  1019  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-12 13:50:41.717  1019  1049 D BluetoothManagerService: Ble is always on enable gatt
,09-12 13:50:41.717  1019  1049 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-12 13:50:41.717  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-12 13:50:41.727  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:50:41.727  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:41.727  1019  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:50:41.727  6799  6799 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-12 13:50:41.737  1019  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 13:50:41.737  6799  6821 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-12 13:50:41.737  6799  6821 D BluetoothAdapterProperties: Setting state to 11
,09-12 13:50:41.737  6799  6821 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 13:50:41.737  6799  6821 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 13:50:41.737  6799  6821 D BluetoothAdapterService: updateAdapterState state is 11
,09-12 13:50:41.747  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:41.747  1019  1019 I InputMethodManagerService: [BT Setting State] State =11
,09-12 13:50:41.747  6799  6821 D BluetoothAdapterService: Autoconnection is available 
09-12 13:50:41.747  6799  6821 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-12 13:50:41.747  6799  6821 D BluetoothSecureManager: getInstant: null
09-12 13:50:41.747  6799  6821 D BluetoothSecureManager: calling getMethod for getService
09-12 13:50:41.747  6799  6821 D BluetoothSecureManager: calling getService
,09-12 13:50:41.757  6799  6821 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3dd4c5b3
09-12 13:50:41.757  1019  3138 D BluetoothSecureManagerService: isSecureModeEnabled
,09-12 13:50:41.757  1019  3138 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-12 13:50:41.757  6799  6821 D BtConfig.SecureMode: isSecureModeOn:false
09-12 13:50:41.757  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 13:50:41.757  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:41.757  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:50:41.757  1182  1182 D BluetoothTile:  getBluetoothState : 11
,09-12 13:50:41.757  6799  6821 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-12 13:50:41.757  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 13:50:41.757  6799  6821 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-12 13:50:41.757  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:41.757  6799  6821 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-12 13:50:41.757  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 13:50:41.757  6799  6821 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-12 13:50:41.757  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 13:50:41.757  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
09-12 13:50:41.757  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:50:41.757  6799  6821 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-12 13:50:41.757  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:50:41.757  1802  1802 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:50:41.757  6799  6821 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-12 13:50:41.757  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:41.767  6799  6821 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-12 13:50:41.767  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:50:41.767  6799  6821 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-12 13:50:41.767  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:50:41.767  1019  5323 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:50:41.767  6799  6821 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:41.767  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 13:50:41.767  1295  1295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:41.767  1019  3141 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:50:41.767  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:50:41.767  6799  6821 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:41.767  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-12 13:50:41.767  6799  6821 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 13:50:41.767  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:50:41.767  6799  6821 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-12 13:50:41.767  6799  6821 D BluetoothBondStateMachine: make
,09-12 13:50:41.777  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:41.777  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 13:50:41.777  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 13:50:41.777  6799  6821 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 13:50:41.777  6799  6826 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 13:50:41.777  1019  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:50:41.777  1019  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-12 13:50:41.777  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.777  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:41.777  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:41.777  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:41.777  1019  3139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:41.777  1019  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.777  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:41.777  1019  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.777  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.777  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:50:41.777  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:50:41.777  6799  6821 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 13:50:41.787  6799  6799 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:50:41.787  6799  6799 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:50:41.787  6799  6799 D BtGatt.GattService: start()
09-12 13:50:41.787  6799  6799 D BtGatt.GattService: start()
09-12 13:50:41.787  6799  6799 I bluedroid: get_profile_interface gatt
,09-12 13:50:41.787  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:41.787  6799  6799 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:50:41.787  1019  2761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 13:50:41.787  1019  5323 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:41.787  1019  5323 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.787  1295  1295 D BluetoothNotiBroadcastReceiver: onReceive
09-12 13:50:41.787  1019  5323 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:41.787  1019  5323 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.787  1019  5323 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.787  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 13:50:41.787  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 13:50:41.787  6799  6821 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 13:50:41.797  1019  3138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:41.797  1019  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.797  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:41.797  1019  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:41.797  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.797  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-12 13:50:41.797  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:50:41.797  6799  6821 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:50:41.807  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:41.807  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 13:50:41.807  1019  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:41.807  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.807  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:41.807  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.807  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.807  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-12 13:50:41.807  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:50:41.807  6799  6821 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:50:41.817  1019  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:41.817  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.817  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:41.817  6799  6799 D BtGatt.GattService: mStartError = false
09-12 13:50:41.817  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:41.817  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.817  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.817  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-12 13:50:41.817  6799  6799 D HeadsetService: Received start request. Starting profile...
09-12 13:50:41.817  6799  6799 D HeadsetService: start()
,09-12 13:50:41.817  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:50:41.817  6799  6799 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 13:50:41.817  6799  6799 D HeadsetStateMachine: make
,09-12 13:50:41.827  6799  6821 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 13:50:41.827  1019  3138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:41.827  1019  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.827  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:41.827  1019  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.827  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.827  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 13:50:41.827  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:50:41.827  6799  6821 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:50:41.827  1019  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:41.827  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.827  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:41.827  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.827  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.837  6799  6799 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 13:50:41.847  1019  1253 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-12 13:50:41.847  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.847  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-12 13:50:41.847  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:41.847  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:41.847  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-12 13:50:41.847  1019  1321 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:41.847  1019  1321 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.847  1019  1321 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:41.847  1019  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.847  1019  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:41.847  1019  1032 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 13:50:41.847  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 13:50:41.847  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:41.847  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:41.847  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:41.847  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:41.847  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:50:41.847  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:50:41.847  6799  6821 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:50:41.847  6799  6821 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 13:50:41.847  6799  6821 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 13:50:41.847  6799  6799 I bluedroid: get_profile_interface handsfree
,09-12 13:50:41.867  6799  6799 I DualScoManager: Instantiating Dual Sco Manager
,09-12 13:50:41.867  6799  6799 I DualScoManager: Set HeadsetServiceHelper
,09-12 13:50:41.867  6799  6799 D BluetoothAtMessage: createCMTIContentObservers
,09-12 13:50:41.867  1019  1555 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-12 13:50:41.867  1019  1555 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:41.867  1019  1555 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:41.867  1019  1555 D SettingsProvider: selectionArgs: false
,09-12 13:50:41.867  1019  1555 D SettingsProvider: selectionArgs: 1002
,09-12 13:50:41.867  1019  1555 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:41.867  1019  1555 D SettingsProvider: ret = -1
,09-12 13:50:41.867  6799  6830 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 13:50:41.867  6799  6799 D HeadsetService: mStartError = false
09-12 13:50:41.867  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:41.877  6799  6799 D A2dpService: Received start request. Starting profile...
,09-12 13:50:41.877  6799  6799 D A2dpService: start()
09-12 13:50:41.877  6799  6830 D HeadsetStateMachine: Clear mHeadsetBrsf
09-12 13:50:41.877  6799  6830 D HeadsetStateMachine: map size, before remove : 0
,09-12 13:50:41.877  6799  6830 D HeadsetStateMachine: map size, after remove: 0
,09-12 13:50:41.877  6799  6799 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 13:50:41.877  6799  6799 I bluedroid: get_profile_interface avrcp
,09-12 13:50:41.887  6799  6799 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:50:41.897  6799  6799 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 13:50:41.907  6799  6834 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 13:50:41.907  6799  6799 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 13:50:41.907  6799  6799 D A2dpStateMachine: make
,09-12 13:50:41.907  6799  6799 I bluedroid: get_profile_interface a2dp
09-12 13:50:41.907  6799  6836 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 13:50:41.907  6799  6799 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 13:50:41.907  6799  6799 D A2dpService: mStartError = false
09-12 13:50:41.907  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:41.907  6799  6835 D A2dpStateMachine: Enter Disconnected: -2
09-12 13:50:41.907  6799  6799 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:50:41.917  6799  6799 D HidService: Received start request. Starting profile...
09-12 13:50:41.917  6799  6799 D HidService: start()
09-12 13:50:41.917  6799  6799 I bluedroid: get_profile_interface hidhost
09-12 13:50:41.917  6799  6799 D HidService: setHidService(): set to: null
09-12 13:50:41.917  6799  6799 D HidService: mStartError = false
09-12 13:50:41.917  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:41.917  6799  6799 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-12 13:50:41.917  6799  6799 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 13:50:41.917  6799  6799 D HealthService: Received start request. Starting profile...
09-12 13:50:41.917  6799  6799 D HealthService: start()
,09-12 13:50:41.917  6799  6834 D BluetoothMediaBrowser: no now playing list
09-12 13:50:41.917  6799  6834 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-12 13:50:41.917  6799  6799 I bluedroid: get_profile_interface health
09-12 13:50:41.927  6799  6799 D HealthService: mStartError = false
09-12 13:50:41.927  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:41.927  6799  6799 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:50:41.927  6799  6799 D PanService: Received start request. Starting profile...
09-12 13:50:41.927  6799  6799 D PanService: start()
09-12 13:50:41.927  6799  6799 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:50:41.927  6799  6799 I bluedroid: get_profile_interface pan
,09-12 13:50:41.927  6799  6799 D PanService: mStartError = false
09-12 13:50:41.927  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:41.937  6799  6799 D BluetoothMapService: Received start request. Starting profile...
09-12 13:50:41.937  6799  6799 D BluetoothMapService: start()
,09-12 13:50:41.937  1914  1914 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:50:41.947  6799  6799 D BluetoothMapService: mStartError = false
09-12 13:50:41.947  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:41.947  6799  6799 D HeadsetStateMachine: Try to query the phonestate on bind
,09-12 13:50:41.947  1429  2710 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:50:41.947  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-12 13:50:41.947  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 13:50:41.947  1429  2710 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 13:50:41.947  6799  6799 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-12 13:50:41.957  6799  6799 D SapService: Received start request. Starting profile...
09-12 13:50:41.957  6799  6799 D SapService: start()
09-12 13:50:41.957  6799  6799 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 13:50:41.957  6799  6799 I bluedroid: get_profile_interface sap
09-12 13:50:41.957  6799  6799 D SapService: mStartError = false
09-12 13:50:41.957  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
09-12 13:50:41.957  6799  6799 D HeadsetStateMachine: Proxy object connected
,09-12 13:50:41.957  6799  6799 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-12 13:50:41.957  6799  6799 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 13:50:41.957  6799  6830 D HeadsetStateMachine: Disconnected process message: 11
09-12 13:50:41.957  6799  6830 D HeadsetStateMachine: Disconnected process message: 18
09-12 13:50:41.957  6799  6799 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-12 13:50:41.957  6799  6799 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 13:50:41.957  6799  6799 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 13:50:41.957  6799  6799 D BluetoothA2dp: Proxy object connected
09-12 13:50:41.957  6799  6830 D HeadsetStateMachine: Disconnected process message: 10
09-12 13:50:41.957  6799  6799 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-12 13:50:41.957  6799  6799 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 13:50:41.957  6799  6830 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-12 13:50:41.957  6799  6799 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-12 13:50:41.957  6799  6830 D HeadsetStateMachine: Disconnected process message: 11
09-12 13:50:41.957  1914  1914 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:50:41.957  6799  6799 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-12 13:50:41.957  6799  6799 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-12 13:50:41.987  6799  6799 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 13:50:41.987  6799  6799 E BluetoothAdapterService(814029002): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 13:50:41.997  6799  6821 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-12 13:50:41.997  6799  6821 I bluedroid: enable
09-12 13:50:41.997  6799  6821 I bt_hci_bdroid: init
,09-12 13:50:41.997  6799  6821 I bt_vendor: bt-vendor : init
09-12 13:50:41.997  6799  6821 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 13:50:41.997  6799  6821 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 13:50:41.997  6799  6821 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-12 13:50:41.997  6799  6821 D bt_userial_mct: userial_init
,09-12 13:50:41.997  6799  6821 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 13:50:41.997  6799  6821 I bt_vendor: Starting hciattach daemon
09-12 13:50:41.997  6799  6821 I bt_vendor: try to set false
,09-12 13:50:41.997  6799  6840 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-12 13:50:41.997  6799  6821 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 13:50:41.997  6799  6821 I bt_vendor: Starting hciattach daemon
09-12 13:50:41.997  6799  6821 I bt_vendor: try to set true
,09-12 13:50:42.017  6844  6844 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-12 13:50:42.067  6850  6850 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-12 13:50:42.077  6851  6851 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-12 13:50:42.097  6853  6853 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 13:50:42.107  6854  6854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-12 13:50:42.107   287   287 E SMD     : DCD OFF,
,09-12 13:50:42.117  6855  6855 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 13:50:42.127  6856  6856 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-12 13:50:42.557  6859  6859 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-12 13:50:42.567  6860  6860 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 13:50:42.607  6799  6821 I bt_vendor: bluetooth satus is on,
09-12 13:50:42.607  6799  6842 D bt_userial_mct: userial_open(port:0)
09-12 13:50:42.607  6799  6842 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-12 13:50:42.607  6799  6842 I bt_vendor: Done intiailizing UART
,09-12 13:50:42.607  6799  6842 I bt_vendor: Done intiailizing UART
09-12 13:50:42.607  6799  6842 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-12 13:50:42.607  6799  6842 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-12 13:50:42.617  6799  6862 D bt_userial_mct: Entering userial_read_thread()
,09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:50:42.617  6799  6840 I         : BTE_InitTraceLevels -- TRC_SAP
,09-12 13:50:42.627  6799  6840 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:50:42.627  6799  6840 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:50:42.627  6799  6840 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:50:42.627  6799  6840 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:50:42.627  6799  6840 I         : BTE_InitTraceLevels -- TRC_BTIF
09-12 13:50:42.627  6799  6840 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-12 13:50:42.727  6799  6840 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-12 13:50:42.727  6799  6840 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fed6e9 
,09-12 13:50:42.727  6799  6840 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fed6e9 
,09-12 13:50:42.747  6799  6824 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-12 13:50:42.757  6799  6824 E bt-btif : Calling BTA_HhEnable
,09-12 13:50:42.757  6799  6824 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 13:50:42.757  6799  6824 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 13:50:42.757  6799  6824 E BluetoothServiceJni: populateRssiValuesNative
09-12 13:50:42.757  6799  6824 I bluedroid: getModelRssiValues
,09-12 13:50:42.757  6799  6824 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 13:50:42.757  6799  6824 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:50:42.757  1019  1019 D SettingsProvider: name = bluetooth_name
,09-12 13:50:42.757  6799  6824 D BluetoothAdapterProperties: Name is: A5-1
,09-12 13:50:42.767  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:42.767  6799  6824 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 13:50:42.767  6799  6824 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:50:42.767  6799  6824 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:50:42.767  6799  6824 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-12 13:50:42.767  6799  6824 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-12 13:50:42.767  6799  6824 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-12 13:50:42.767  6799  6824 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 13:50:42.767  6799  6824 E bt-btif : btif_sock_init: !vhci_init
09-12 13:50:42.767  6799  6824 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-12 13:50:42.767  6799  6824 D IOP_DB_BT: db_open: db_open : handle 3023220752l, read 13894 bytes onto local cache
09-12 13:50:42.767  6799  6824 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-12 13:50:42.767  6799  6824 D IOP_DB_BT: db_query: result 1
,09-12 13:50:42.767  6799  6824 I         : iop_db_open: iop_db_open status 0
09-12 13:50:42.767  6799  6824 D bte_conf: Device ID record 1 : primary
,09-12 13:50:42.767  6799  6824 D bte_conf:   vendorId            = 0075
09-12 13:50:42.767  6799  6824 D bte_conf:   vendorIdSource      = 0001
09-12 13:50:42.767  6799  6824 D bte_conf:   product             = 0100
09-12 13:50:42.767  6799  6824 D bte_conf:   version             = 0200
09-12 13:50:42.767  6799  6824 D bte_conf:   clientExecutableURL = 
09-12 13:50:42.767  6799  6824 D bte_conf:   serviceDescription  = 
09-12 13:50:42.767  6799  6824 D bte_conf:   documentationURL    = 
09-12 13:50:42.767  6799  6824 D bte_conf: bte_load_did_conf no section named DID2.
09-12 13:50:42.777  6799  6862 E bt_mct  : hci lib postload completed
,09-12 13:50:42.777  6799  6821 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 13:50:42.777  6799  6821 D BluetoothAdapterProperties: ScanMode =  20
,09-12 13:50:42.777  6799  6821 D BluetoothAdapterProperties: State =  11
,09-12 13:50:42.777  1019  1480 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 13:50:42.777  6799  6821 D BluetoothAdapterProperties: Setting state to 12,
09-12 13:50:42.777  6799  6821 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:50:42.777  6799  6824 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 13:50:42.777  6799  6824 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:50:42.777  6799  6824 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:50:42.777  6799  6824 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:50:42.787  1019  1545 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-12 13:50:42.787  1019  1545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:50:42.787  1019  1545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:50:42.787  1019  1545 D SettingsProvider: selectionArgs: false
09-12 13:50:42.787  1019  1545 D SettingsProvider: selectionArgs: 1002
09-12 13:50:42.787  1019  1545 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:50:42.787  1019  1545 D SettingsProvider: ret = -1
09-12 13:50:42.787  6799  6821 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:50:42.787  6799  6821 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 13:50:42.787  1019  3132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:42.787  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.787  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.787  1019  3132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.787  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.787  6799  6821 D BluetoothAdapterService: Autoconnection is available 
09-12 13:50:42.787  6799  6821 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 13:50:42.787  6799  6821 D BluetoothAdapterService: starting service from this receiver
,09-12 13:50:42.787  1019  1253 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:50:42.787  1295  1303 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:50:42.787  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.797  1019  1253 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:50:42.797  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.797  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:50:42.797  6799  6821 I BluetoothAdapterState: Entering On State from state = 11
09-12 13:50:42.797  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-12 13:50:42.807  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:42.807  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:42.807  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:42.807  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:42.807  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:42.807  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:42.807  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:42.807  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:50:42.807  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.807  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:42.807  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.807  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.807  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:42.807  1459  1472 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:50:42.807  1459  1472 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.807  1295  1306 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:50:42.817  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-12 13:50:42.817  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.817  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:42.817  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.817  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-12 13:50:42.817  6799  6799 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 13:50:42.817  1429  1469 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:42.817  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 13:50:42.817  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:42.817  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.817  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.817  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.827  1429  1469 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:42.827  1443  1458 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:42.827  1443  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.827  1295  6766 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:50:42.827  1295  6766 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:42.827  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-12 13:50:42.827  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.827  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.827  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.827  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.827  1429  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:42.827  1429  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.827  1295  1306 D Bluetoothsap: onBluetoothStateChange: up=true
,09-12 13:50:42.827  1295  1306 D Bluetoothsap: Binding service...
,09-12 13:50:42.837  1295  1295 D BluetoothA2dp: Proxy object connected
09-12 13:50:42.837  1295  1295 D A2dpProfile: Bluetooth service connected
,09-12 13:50:42.837  1295  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 13:50:42.837  6799  6799 I BluetoothPbapService: Handler(): got msg=1
,09-12 13:50:42.837  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 13:50:42.837  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.837  1019  1555 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 13:50:42.837  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.837  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.837  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.837  1295  1306 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 13:50:42.837  1295  1303 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:50:42.837  1295  1295 D BluetoothPbap: Proxy object connected
09-12 13:50:42.837  1295  1295 D PbapServerProfile: Bluetooth service connected
,09-12 13:50:42.847  1295  1295 D BluetoothMap: Proxy object connected
09-12 13:50:42.847  1295  1295 D MapProfile: Bluetooth service connected
09-12 13:50:42.847  1295  1295 D BluetoothMap: getConnectedDevices()
,09-12 13:50:42.847  6799  6865 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-12 13:50:42.847  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-12 13:50:42.847  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.847  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.847  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.847  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.847  1019  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 13:50:42.847  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:42.847  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:42.847  1019  1049 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 13:50:42.847  1019  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:50:42.847  1019  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 13:50:42.847  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:50:42.847  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.857  6799  6825 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:42.857  6799  6825 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.857  1295  6766 D BluetoothPan: Binding service...
09-12 13:50:42.857  1295  1295 D Bluetoothsap: BluetoothSAP Proxy object connected
09-12 13:50:42.857  1295  1295 D SapProfile: Bluetooth service connected
09-12 13:50:42.857  1295  1295 D Bluetoothsap: getConnectedDevices()
,09-12 13:50:42.857  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 13:50:42.857  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.857  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.857  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.857  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.857  1295  1295 D BluetoothInputDevice: Proxy object connected
09-12 13:50:42.857  6799  6865 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:50:42.857  1295  1295 D HidProfile: Bluetooth service connected
09-12 13:50:42.857  6799  6865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:50:42.857  2852  2864 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:50:42.857  6799  6865 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-12 13:50:42.857  6799  6865 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:50:42.857  6799  6865 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:50:42.857  6799  6865 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@219539e7
09-12 13:50:42.857  2852  2864 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:42.857  6799  6865 D BluetoothSocket: channel: 19
09-12 13:50:42.857  6799  6865 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-12 13:50:42.857  1295  1295 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:50:42.857  1019  1049 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:50:42.857  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 13:50:42.857  1295  1295 D PanProfile: Bluetooth service connected
09-12 13:50:42.857  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.857  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.857  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.867  1019  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:42.867  1019  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:50:42.867  1019  1049 D BluetoothPan: Binding service...
09-12 13:50:42.867  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 13:50:42.867  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 13:50:42.867  1019  1019 D BluetoothA2dp: Proxy object connected
,09-12 13:50:42.867  1429  1469 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:42.867  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:42.867  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:42.867  2852  2852 D BluetoothA2dp: Proxy object connected
09-12 13:50:42.867  1019  1019 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:50:42.867  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.867  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.867  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.867  1429  1469 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:42.867  1182  1201 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:50:42.867  1182  1201 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:50:42.867  6250  6260 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:42.867  6250  6260 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.867  2852  6769 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:42.867  2852  6769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.867  1295  1303 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:42.867  1295  1303 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.867  1914  1925 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:50:42.867  1914  1925 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.877  1295  6766 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:42.877  1019  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 13:50:42.877  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 13:50:42.877  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.877  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.877  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.877  1295  6766 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 13:50:42.877  1295  1295 D HeadsetProfile: Bluetooth service connected
,09-12 13:50:42.877  1429  2710 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:42.877  1019  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:42.877  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:42.877  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:42.877  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.877  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-12 13:50:42.877  1429  2710 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:42.877  6799  6807 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:50:42.887  2852  2860 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:42.887  1019  2712 D SSRM:n  : SIOP:: AP = 360
,09-12 13:50:42.887  1019  1049 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:50:42.887  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:42.887  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.887  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.887  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.887  2852  2860 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:42.887  6155  6163 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:50:42.887  6155  6163 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:50:42.897  1459  1472 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:50:42.897  1019  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 13:50:42.897  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:50:42.897  1019  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:42.897  1019  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:42.897  1019  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:42.897  1459  1472 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:50:42.897  1019  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 13:50:42.897  1019  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:50:42.907  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:42.907  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
,09-12 13:50:42.907  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:50:42.907  1182  1182 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:50:42.917  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@22ff1993, true
,09-12 13:50:42.917  1429  1429 D BluetoothHeadset: registerMessageListener
,09-12 13:50:42.917  1182  1182 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 13:50:42.917  1182  1182 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:42.917  1182  1182 D BluetoothTile:  getBluetoothState : 12
,09-12 13:50:42.917  1802  1802 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:50:42.917  1295  1295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:50:42.917  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:42.927  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:42.927  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:42.927  1019  1545 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:50:42.927  1019  1545 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.927  6799  6867 D HeadsetService: registerMessageListener
09-12 13:50:42.927  1019  1545 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.927  1019  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:42.927  1019  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:42.927  6799  6867 D HeadsetService: registerMessageListener
,09-12 13:50:42.927  6799  6830 D HeadsetStateMachine: Disconnected process message: 70
09-12 13:50:42.927  6799  6830 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@33d83994
,09-12 13:50:42.927  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-12 13:50:42.927  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 13:50:42.927  1182  1729 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:50:42.927  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-12 13:50:42.927  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-12 13:50:42.927  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 13:50:42.937  1295  1295 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-12 13:50:42.937  1295  1295 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 13:50:42.937  1295  1295 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 13:50:42.937  1295  1295 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-12 13:50:42.937  6799  6868 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 13:50:42.937  1019  1480 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:50:42.937  1019  5323 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 13:50:42.937  6799  6830 D HeadsetStateMachine: Disconnected process message: 9
09-12 13:50:42.937  1182  1182 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:50:42.937  6799  6830 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 13:50:42.947   282   677 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-12 13:50:42.947   282   677 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 13:50:42.947   282   677 V voice   : voice_set_parameters: exit with code(-2)
09-12 13:50:42.947   282   677 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 13:50:42.947   282   677 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 13:50:42.947  1295  1295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:50:42.947   282   677 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 13:50:42.947   282   677 V audio_hw_primary: adev_set_parameters: exit
,09-12 13:50:42.947  6799  6830 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-12 13:50:42.947  1019  1480 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 13:50:42.947  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.947  6799  6868 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:50:42.947  6799  6868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:50:42.947  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.947  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:50:42.947  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:50:42.957  6799  6868 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-12 13:50:42.957  6799  6868 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:50:42.957  6799  6868 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:50:42.957  6799  6868 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1113cc3d
,09-12 13:50:42.957  6799  6868 D BluetoothSocket: channel: 5
,09-12 13:50:42.967  1295  1295 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:50:42.967  1295  1295 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:50:42.967  1182  1182 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:50:42.967  1182  1182 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 13:50:42.977  6799  6799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:42.977  6799  6799 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 13:50:42.987  1019  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:50:42.987  1019  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 13:50:42.987  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:42.987  1019  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:42.987  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:50:43.007  1914  1914 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:50:43.007  1019  3141 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
09-12 13:50:43.007  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 13:50:43.007  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:43.007  1019  3141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:50:43.007  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:43.017  1019  1547 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 13:50:43.027  1914  6877 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 13:50:43.027  1914  1914 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:50:43.057  6799  6878 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:50:43.057  6799  6878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:50:43.057  6799  6878 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-12 13:50:43.057  6799  6878 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:50:43.057  6799  6878 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:50:43.057  6799  6878 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a75ef39
09-12 13:50:43.057  6799  6878 D BluetoothSocket: channel: 12
09-12 13:50:43.057  6799  6878 I BtOppRfcommListener: Accept thread started.
,09-12 13:50:43.187  1019  1555 I art     : Explicit concurrent mark sweep GC freed 20085(1175KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.365ms total 150.332ms
,09-12 13:50:43.187  1019  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:43.187  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:43.187  1019  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:43.187  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:43.197  1019  3139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:50:43.207  1019  3139 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:43.207  1019  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:43.207  1019  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:43.217  1914  6877 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-12 13:50:43.397  1019  1342 E Watchdog: !@Sync 4
,09-12 13:50:43.647  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:43.647  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:43.647  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:43.647  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:50:43.647  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:43.647  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:43.647  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:43.647  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:43.647  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:43.647  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:50:43.647  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ef903d added. We now have 8 listener(s)
,09-12 13:50:43.647  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:50:43.657  1019  1126 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:50:43.657  1019  1126 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 13:50:43.657  1019  1126 D SecContentProvider2: mCursor = null
,09-12 13:50:43.657  1019  1126 D WifiService: setWifiEnabled: false pid=6155, uid=10155
,09-12 13:50:43.657  1019  1126 D SettingsProvider: name = wifi_on
,09-12 13:50:43.667  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:43.667  1019  3139 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:50:43.667  1019  3139 D WifiService: setWifiEnabled: true pid=6155, uid=10155
,09-12 13:50:43.667  1019  3139 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:50:43.667  1019  3139 W ActivityManager: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:50:43.667  1019  3139 D SecContentProvider2: mCursor = null
09-12 13:50:43.667  1019  3139 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:50:43.667  1019  3139 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6155, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:50:43.667  1019  3139 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:50:43.667  1019  3139 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:50:43.667  1019  3139 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:50:43.667  1019  3139 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:50:43.667  1019  3139 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:50:43.667  1019  3139 D SettingsProvider: name = wifi_on
,09-12 13:50:43.677  1019  1131 E WifiHW  : ##################### set firmware type 0 #####################,
,09-12 13:50:44.037  1019  1047 D Tethering: interfaceAdded wlan0
,09-12 13:50:44.037  1019  1134 E Tethering: No numeric data
,09-12 13:50:44.037  1019  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:50:44.037  1019  1134 D Tethering: clearTetheredNotification()
,09-12 13:50:44.047  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:50:44.047  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:44.047  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:44.047  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:50:44.047  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:44.047  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:50:44.047  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:50:44.047  1019  1134 D Tethering: InitialState.processMessage what=4
,09-12 13:50:44.057  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:50:44.057  1182  1182 D HotspotTile: updateTetherState():false, false
,09-12 13:50:44.067  1019  1047 D Tethering: interfaceAdded p2p0
,09-12 13:50:44.067   277   996 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 13:50:44.067   277   996 D SoftapController: Softap fwReload - Ok
09-12 13:50:44.067  1019  1134 E Tethering: No numeric data
,09-12 13:50:44.067  1019  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
09-12 13:50:44.067  1019  1128 V NetworkStats: performPollLocked() took 22ms
,09-12 13:50:44.067  1019  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-12 13:50:44.067  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:44.067  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:50:44.067  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:50:44.077  1019  1134 D Tethering: clearTetheredNotification()
,09-12 13:50:44.077   277   996 D CommandListener: Setting iface cfg
09-12 13:50:44.077   277   996 D CommandListener: Trying to bring down wlan0
,09-12 13:50:44.077   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:50:44.077  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:50:44.077  1182  1182 D HotspotTile: updateTetherState():false, false
,09-12 13:50:44.077  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:44.077  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:44.077  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:44.077  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:50:44.077  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 13:50:44.087  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:44.087  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:50:44.087  1019  1131 E WifiHW  : supplicant_name : p2p_supplicant
,09-12 13:50:44.087  1019  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-12 13:50:44.087  1019  1131 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-12 13:50:44.097   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:50:44.097  1019  1128 V NetworkStats: performPollLocked() took 15ms
09-12 13:50:44.097  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:44.097  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:44.097  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:50:44.097  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:44.097  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:44.097  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:44.097  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:44.107  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:50:44.107  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-12 13:50:44.107  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:44.107  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:50:44.107  1182  1182 D HotspotTile: onReceive : 2, 0
,09-12 13:50:44.107  1295  1295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:44.107  1019  1321 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:44.107  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:44.107  1019  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:50:44.107  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:44.107  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:50:44.107  1019  1321 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:50:44.107  1019  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:44.107  1019  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:44.107  3557  3557 I Hs20UtilService: Starting #19,
,09-12 13:50:44.117  3557  3601 I Hs20UtilService: Message received 5011
,09-12 13:50:44.117  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:50:44.117  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:50:44.117  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:50:44.117  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:50:44.147  6891  6891 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 13:50:44.147  6891  6891 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 13:50:44.147  6891  6891 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 13:50:44.157  6891  6891 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-12 13:50:44.157   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6891
09-12 13:50:44.157   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-12 13:50:44.157  6891  6891 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 13:50:44.167  6891  6891 I wpa_supplicant: ssSupport state is = 1
09-12 13:50:44.167  6891  6891 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 13:50:44.167  6891  6891 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-12 13:50:44.167   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6891
09-12 13:50:44.167   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-12 13:50:44.297   394   394 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,09-12 13:50:44.307  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,09-12 13:50:44.377  6891  6891 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-12 13:50:44.377  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-12 13:50:44.387  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
09-12 13:50:44.387   394   394 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6891,
09-12 13:50:44.387   394   394 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-12 13:50:44.387  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 13:50:44.387  6891  6891 I wpa_supplicant: ssSupport state is = 1
09-12 13:50:44.387  6891  6891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 13:50:44.387  6891  6891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:50:44.387  6891  6891 E wpa_supplicant: SIM READ ERROR
09-12 13:50:44.387  6891  6891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:50:44.387  6891  6891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:50:44.387  6891  6891 E wpa_supplicant: SIM READ ERROR
09-12 13:50:44.387  6891  6891 I wpa_supplicant: Blacklist: Clear (all) ,
09-12 13:50:44.387  6891  6891 I wpa_supplicant: wpa_default_ap_write_once
09-12 13:50:44.387  6891  6891 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:50:44.387  6891  6891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:50:44.387  6891  6891 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-12 13:50:44.387  6891  6891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:50:44.387  6891  6891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-12 13:50:44.387  6891  6891 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 13:50:44.387  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 13:50:44.387  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:50:44.387  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:44.447  6891  6891 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-12 13:50:45.097   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:50:45.107   287   287 E SMD     : DCD OFF
,09-12 13:50:45.157  6891  6891 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 13:50:45.157  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-12 13:50:45.167  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
09-12 13:50:45.167   394   394 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6891
09-12 13:50:45.167   394   394 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-12 13:50:45.167  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 13:50:45.167  6891  6891 I wpa_supplicant: ssSupport state is = 1
09-12 13:50:45.167  6891  6891 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 13:50:45.167  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-12 13:50:45.187  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-12 13:50:45.187   394   394 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6891
09-12 13:50:45.187   394   394 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,09-12 13:50:45.187  6891  6891 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 13:50:45.187  6891  6891 I wpa_supplicant: ssSupport state is = 1
09-12 13:50:45.187  6891  6891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 13:50:45.187  6891  6891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:50:45.187  6891  6891 E wpa_supplicant: SIM READ ERROR
09-12 13:50:45.187  6891  6891 I wpa_supplicant: wpa_default_ap_write_once
,09-12 13:50:45.187  6891  6891 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-12 13:50:45.187  6891  6891 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 13:50:45.197  1019  1047 D Tethering: interfaceLinkStateChanged p2p0, false
,09-12 13:50:45.197  1019  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:50:45.197  1019  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:50:45.267  6891  6891 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-12 13:50:45.267  6891  6891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 13:50:45.337  6891  6891 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-12 13:50:45.337  6891  6891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-12 13:50:45.337  6891  6891 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-12 13:50:45.347  1019  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-12 13:50:45.347  1019  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 13:50:45.347  6891  6891 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-12 13:50:45.347  6891  6891 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 13:50:45.357  6891  6891 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:50:45.357  6891  6891 E wpa_supplicant: SIM READ ERROR
09-12 13:50:45.357  6891  6891 I wpa_supplicant: Blacklist: Clear (all) ,
,09-12 13:50:45.377  6891  6891 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-12 13:50:45.387  1019  1131 D WifiNative-wlan0: callSECApiInt - ID [210],
09-12 13:50:45.387  6891  6891 I wpa_supplicant: Skip scan - bUseNetwork false
09-12 13:50:45.387  1019  1131 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:50:45.397  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:45.397  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:45.397  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:45.397  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:45.397  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:45.397  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:45.397  1182  1182 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:45.397  1182  1182 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-12 13:50:45.397  1182  1182 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:45.397  1182  1729 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:50:45.397  1182  1182 D HotspotTile: onReceive : 3, 0
,09-12 13:50:45.397  1295  1295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:50:45.407  1019  1131 E WifiConfigStore: Not a HS20
,09-12 13:50:45.407  1019  1131 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 13:50:45.407  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:45.407  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:45.407  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:45.407  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:45.407  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:45.407  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:45.407  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:45.407  6155  6155 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:45.407  1019  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-12 13:50:45.407  1019  1479 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:50:45.407  6155  6155 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:50:45.407  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:45.417  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:45.417  1019  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:45.417  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:50:45.417  3557  3557 I Hs20UtilService: Starting #20
,09-12 13:50:45.417  3557  3601 I Hs20UtilService: Message received 5011
,09-12 13:50:45.417  1019  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-12 13:50:45.417  6891  6891 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 13:50:45.417  6891  6891 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-12 13:50:45.417  6891  6891 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 13:50:45.417  6891  6891 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:50:45.417  6891  6891 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 13:50:45.417  6891  6891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 13:50:45.417  6891  6891 I wpa_supplicant: First Scan Start
,09-12 13:50:45.417  6891  6891 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 13:50:45.417  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:50:45.427  6358  6358 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:50:45.427  6358  6358 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:50:45.427  6358  6358 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-12 13:50:45.427  1019  1131 D WifiNative-wlan0: Setting external_sim to 1
,09-12 13:50:45.427  1019  1131 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:50:45.427  1019  1131 I WifiNative-HAL: startHal
09-12 13:50:45.427  1019  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9e11488c
09-12 13:50:45.427  1019  1131 I WifiNative-HAL: Could not start hal
,09-12 13:50:45.427  1019  1131 E WifiNative-wlan0: do suspend true
,09-12 13:50:45.427  1019  1130 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-12 13:50:45.427  6297  6297 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:50:45.437   277   996 D CommandListener: Setting iface cfg
09-12 13:50:45.437   277   996 D CommandListener: Trying to bring up p2p0
,09-12 13:50:45.437  1019  1130 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:50:45.437  1019  1130 D WifiP2pService: P2pEnablingState
09-12 13:50:45.437  1019  1130 D WifiP2pService: P2pEnablingState{ what=147457 }
09-12 13:50:45.437  1019  1130 D WifiP2pService: P2p socket connection successful
,09-12 13:50:45.437  1019  1130 D WifiP2pService: P2pEnabledState
09-12 13:50:45.437  1019  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-12 13:50:45.437  1019  1019 D WifiScanningService: SCAN_AVAILABLE : 3
,09-12 13:50:45.437  1019  1153 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:50:45.437  1019  1153 I WifiNative-HAL: startHal
09-12 13:50:45.437  1019  1153 E wifi    : getStaticLongField sWifiHalHandle 0x9ce9e9bc
09-12 13:50:45.437  1019  1153 I WifiNative-HAL: Could not start hal
09-12 13:50:45.437  1019  1153 E WifiScanningService: could not start HAL
,09-12 13:50:45.437  1019  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 13:50:45.437  1019  1019 D RttService: SCAN_AVAILABLE : 3
09-12 13:50:45.437  1019  1133 E ConnectivityService: updateNetworkInfo()
,09-12 13:50:45.437  1019  1154 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:50:45.437  1019  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:50:45.437  1019  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:50:45.437  1019  1131 E WifiNative-wlan0: invaild command id : 215
,09-12 13:50:45.437  1019  1019 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 13:50:45.437  1019  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-12 13:50:45.437  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:50:45.437  1019  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:50:45.437  1019  1050 D WifiDisplayController: disconnect
09-12 13:50:45.437  1019  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:50:45.437  1019  1050 D WifiDisplayController: updateConnection
09-12 13:50:45.437  1019  1131 E WifiNative-wlan0: invaild command id : 215
09-12 13:50:45.437  1019  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:50:45.437  1019  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:50:45.447  6891  6891 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:50:45.447  6891  6891 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:50:45.447  1019  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-12 13:50:45.447  1019  1050 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:50:45.447  1019  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:50:45.447  1019  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:50:45.457  6891  6891 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-12 13:50:45.457  1182  1182 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 13:50:45.457  1019  3141 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:50:45.457  1182  1182 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 13:50:45.457  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:45.457  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:45.457  1019  1130 D WifiNative-p2p0: p2pGetDeviceAddress
,09-12 13:50:45.457  1019  1130 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-12 13:50:45.457  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 13:50:45.457  1019  1130 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-12 13:50:45.457  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:45.457  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:45.467  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:50:45.467  1019  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  secondary type: null
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  wps: 0
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  grpcapab: 0
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  devcapab: 0
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  status: 3
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  wfdInfo: null
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  groupownerAddress: null
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  GOdeviceName: null
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  interfaceAddress: 
09-12 13:50:45.467  1019  1050 D WifiDisplayController:  SConnectInfo : null
,09-12 13:50:45.467  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:50:45.467  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:50:45.467  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:45.467  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:50:45.467  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:45.467  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:50:45.477  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 13:50:45.477  6327  6327 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:50:45.477  6342  6342 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:50:45.487  1019  1130 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 13:50:45.487  1019  1130 D WifiP2pService: InactiveState
,09-12 13:50:45.487  1019  1130 D WifiP2pService: InactiveState{ what=143376 }
,09-12 13:50:45.487  1019  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:50:45.487  6891  6891 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:50:45.487  1019  1130 D WifiP2pService: InactiveState{ what=143376 }
,09-12 13:50:45.487  1019  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:50:45.687  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:50:45.687  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:45.687  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:45.687  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:45.687  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:45.687  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:45.687  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:45.687  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:45.697  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,09-12 13:50:45.697  6155  6207 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 13:50:45.697  6155  6207 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 13:50:45.697  6155  6207 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@78b0a9c Bundle[{}]
,09-12 13:50:45.707  6155  6207 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:50:45.707  6155  6207 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 13:50:45.707  6155  6207 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:50:45.707  6155  6207 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 13:50:45.707  6155  6207 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 13:50:45.707  6155  6207 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:50:45.717  6155  6207 I System.out: Running OutgoingSocketThread
,09-12 13:50:45.717  6155  6898 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1162)
,09-12 13:50:45.727  6155  6898 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39111
09-12 13:50:45.727  6155  6898 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:50:46.097   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:50:46.517  6891  6891 I wpa_supplicant: nl80211: Received scan results (22 BSSes),
09-12 13:50:46.527  6891  6891 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-12 13:50:46.527  6891  6891 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-12 13:50:46.527  1019  6896 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-12 13:50:46.527  6891  6891 I wpa_supplicant: Trying to associate with  'G700'
09-12 13:50:46.527  6891  6891 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-12 13:50:46.527  6891  6891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-12 13:50:46.547  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:46.547  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:46.637  6891  6891 E wpa_supplicant: Cmd 35605 not handled
,09-12 13:50:46.637  6891  6891 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:50:46.637  6891  6891 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-12 13:50:46.637  6891  6891 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-12 13:50:46.637  6891  6891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 13:50:46.637  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:46.637  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:50:46.637  6891  6891 I wpa_supplicant: Associated with F4.99.3E
09-12 13:50:46.637  6891  6891 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:50:46.637  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:50:46.637  6891  6891 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 13:50:46.637  6891  6891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-12 13:50:46.647  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:50:46.647  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:46.647  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:50:46.647  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 13:50:46.647  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:50:46.647  1019  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:50:46.647  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 13:50:46.647  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 13:50:46.647  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
09-12 13:50:46.647  1019  1134 E Tethering: No numeric data
09-12 13:50:46.647  1019  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:50:46.647  1019  1134 D Tethering: clearTetheredNotification()
,09-12 13:50:46.647  6891  6891 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:50:46.647  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:50:46.647  1019  1131 D SecContentProvider2: mCursor = null
09-12 13:50:46.647  6891  6891 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-12 13:50:46.647  6891  6891 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-12 13:50:46.647  6891  6891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-12 13:50:46.657  6891  6891 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:50:46.657  6891  6891 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 13:50:46.657  6891  6891 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-12 13:50:46.657  6891  6891 I wpa_supplicant: Blacklist: Clear (temp) 
09-12 13:50:46.657  6891  6891 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-12 13:50:46.657  1019  1047 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 13:50:46.657  1019  1047 D Tethering: interfaceStatusChanged wlan0, true
,09-12 13:50:46.657  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:46.657  1019  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
,09-12 13:50:46.657  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:46.657  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:50:46.657  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:50:46.657  1182  1182 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:50:46.657  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-12 13:50:46.657  1182  1182 D HotspotTile: updateTetherState():false, false
09-12 13:50:46.657  1019  1131 D SecContentProvider2: mCursor = null
09-12 13:50:46.657  1019  1128 V NetworkStats: performPollLocked() took 5ms
,09-12 13:50:46.657  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:46.667  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:46.667  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:46.667  1019  1131 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 13:50:46.667  1019  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:50:46.677  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:46.677  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:46.677  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:46.677  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:46.677  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:46.677  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:46.677  1019  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-12 13:50:46.677  1019  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 13:50:46.677  1019  1133 E ConnectivityService: updateNetworkInfo()
09-12 13:50:46.677  1019  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 13:50:46.677  1019  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:50:46.677  1019  3141 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:50:46.677  1019  3141 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:50:46.687  1019  3141 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:46.687  1019  3141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:46.687  1019  3141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:50:46.687  1019  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:50:46.687  3557  3557 I Hs20UtilService: Starting #21
,09-12 13:50:46.687  3557  3601 I Hs20UtilService: Message received 5007
,09-12 13:50:46.687  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:50:46.687  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:50:46.697  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:50:46.697  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:50:46.697   277   996 D CommandListener: Setting iface cfg
,09-12 13:50:46.697  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:50:46.697  1295  1295 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:50:46.697  1295  3009 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:50:46.707  1019  1131 E WifiStateMachine: Start Dhcp Watchdog 3
,09-12 13:50:46.707  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:50:46.707  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:46.717  6155  6207 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1163)
09-12 13:50:46.717  6155  6207 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1163)
,09-12 13:50:46.717  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 13:50:46.717  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:46.717  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:46.717  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:46.717  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:46.717  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:46.717  6155  6207 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1168)
,09-12 13:50:46.717  6155  6207 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 13:50:46.717  6155  6207 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1169)
,09-12 13:50:46.727  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:46.727  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11213032 added. We now have 2 listener(s)
,09-12 13:50:46.727  1019  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:50:46.727  1019  1131 D SecContentProvider2: mCursor = null
,09-12 13:50:46.727  1019  1131 E WifiNative-wlan0: do suspend false
,09-12 13:50:46.727  1019  1130 D WifiP2pService: InactiveState{ what=143375 }
,09-12 13:50:46.737  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:50:46.737  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:46.737  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:46.737  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:46.737  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207cf183 added. We now have 9 listener(s)
09-12 13:50:46.737  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:50:46.737  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:50:46.737  1019  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 13:50:46.747  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:46.747  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:46.747  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:46.747  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:46.747  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:46.747  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:46.747  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:46.747  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:46.747  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:46.757  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-12 13:50:46.757  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:50:46.757  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:50:46.757  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b49f339 added. We now have 3 listener(s)
,09-12 13:50:46.757  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:50:46.757  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:50:46.757  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:46.757  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dae1d7e added. We now have 10 listener(s)
09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:46.757  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:46.757  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:50:46.757  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:46.757  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:46.757  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11213032 removed from the list
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:50:46.757  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207cf183 removed from the list
09-12 13:50:46.757  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:46.757  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:46.757  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@207cf183 not in the list
09-12 13:50:46.757  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:46.757  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dae1d7e removed from the list
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:46.757  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:46.757  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:46.757  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:46.757  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b49f339 removed from the list
09-12 13:50:46.767  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:46.767  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d9322df added. We now have 2 listener(s)
09-12 13:50:46.767  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:50:46.767  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-12 13:50:46.767  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:46.767  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:46.767  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bffb2c added. We now have 9 listener(s)
09-12 13:50:46.767  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:46.767  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:50:46.767  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:46.787  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:46.787  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:46.787  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:46.787  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:46.787  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:46.787  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:46.787  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:46.787  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:46.787  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:50:46.787  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:50:46.787  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:46.787  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@348a938a added. We now have 3 listener(s)
,09-12 13:50:46.787  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:50:46.787  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:46.787  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:46.787  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:46.787  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb10dfb added. We now have 10 listener(s)
09-12 13:50:46.787  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:46.787  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:50:46.787  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:50:46.787  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:50:46.787  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:50:46.787  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:50:46.787  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:50:46.797  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:50:46.797  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:50:46.797  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:50:46.797  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:50:46.797  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:50:46.807  6799  6807 D BtGatt.GattService: registerClient() - UUID=e29107f3-3c92-4d7a-abef-6dda6175c34d
,09-12 13:50:46.827  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:46.827  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:46.847  6799  6824 D BtGatt.GattService: onClientRegistered() - UUID=e29107f3-3c92-4d7a-abef-6dda6175c34d, clientIf=6
,09-12 13:50:46.847  6155  6163 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:50:46.847  6799  6825 D BtGatt.GattService: start scan with filters
,09-12 13:50:46.857  6799  6829 D BtGatt.ScanManager: handling starting scan
,09-12 13:50:46.857  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:50:46.857  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:50:46.857  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:50:46.857  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:50:46.857  6799  6829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@308518ca
,09-12 13:50:46.857  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:46.867  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:50:46.867  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:46.867  6799  6824 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 13:50:46.867  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:46.867  6799  6829 D BtGatt.ScanManager: allow scan with filters
09-12 13:50:46.867  6799  6829 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 13:50:46.867  6799  6829 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-12 13:50:46.867  6799  6824 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:50:46.867  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 13:50:46.867  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:46.867  6799  6829 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:50:46.867  6799  6829 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 13:50:46.867  6799  6824 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 13:50:46.867  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:46.877  6155  6207 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:50:46.877  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:50:46.877  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 13:50:46.877  6799  6824 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:50:46.877  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:46.887  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:50:46.887  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:50:46.887  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:50:46.887  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:50:46.887  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:50:46.887  6799  6807 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:50:46.887  6799  6825 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:50:46.887  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:50:46.887  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,09-12 13:50:46.887  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:50:46.887  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:46.897  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:50:46.897  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:46.897  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:46.897  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:50:46.897  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:46.897  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:50:46.897  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,09-12 13:50:46.897  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 13:50:46.897  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:46.897  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:46.897  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d9322df removed from the list
09-12 13:50:46.897  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:50:46.897  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bffb2c removed from the list
09-12 13:50:46.897  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop,
09-12 13:50:46.897  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:46.907  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:50:46.907  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:46.907  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:50:46.907  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:46.907  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:46.907  6799  6829 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 42
09-12 13:50:46.907  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bffb2c not in the list
,09-12 13:50:46.907  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:46.907  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:46.907  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:46.907  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:46.907  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:46.907  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb10dfb removed from the list
09-12 13:50:46.907  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:46.907  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:46.907  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:46.907  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:46.907  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@348a938a removed from the list
,09-12 13:50:46.907  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:46.907  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f88ed7 added. We now have 2 listener(s)
,09-12 13:50:46.907  6799  6829 D BtGatt.ScanManager: filter size is 1
09-12 13:50:46.907  6799  6829 D BtGatt.ScanManager: delete FilterIndex - 3
,09-12 13:50:46.917  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 13:50:46.917  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:46.917  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:46.917  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:46.917  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da483c4 added. We now have 9 listener(s)
09-12 13:50:46.917  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:50:46.917  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:50:46.917  6799  6824 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 13:50:46.917  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:46.917  6799  6829 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:50:46.917  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:46.917  6799  6824 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 13:50:46.917  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:46.917  6799  6829 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:50:46.927  6799  6824 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:50:46.927  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:46.927  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:46.927  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:46.927  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:46.927  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:46.927  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:46.927  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:46.927  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:46.927  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:46.927  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:46.927  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:50:46.927  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:46.937  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:46.937  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3da209e2 added. We now have 3 listener(s)
,09-12 13:50:46.937  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:46.937  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
,09-12 13:50:46.937  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:46.937  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:50:46.937  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:46.937  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23cd4173 added. We now have 10 listener(s)
09-12 13:50:46.937  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:46.937  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-12 13:50:46.937  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:50:46.937  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:50:46.937  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:50:46.937  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:46.937  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:50:46.947  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:50:46.947  6906  6906 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 13:50:46.947  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:50:46.947  6906  6906 I dhcpcd  : version 5.5.6 starting
,09-12 13:50:46.957  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-12 13:50:46.957  6906  6906 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-12 13:50:46.957  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:50:46.957  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:50:46.957  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:50:46.977  6799  6813 D BtGatt.GattService: registerClient() - UUID=c341fe67-6a43-4372-b2f9-61b55760e533
,09-12 13:50:47.007  6906  6906 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-12 13:50:47.007  6906  6906 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-12 13:50:47.007  6906  6906 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-12 13:50:47.007  6906  6906 I dhcpcd  : bssid match
,09-12 13:50:47.007  6906  6906 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-12 13:50:47.017  6799  6824 D BtGatt.GattService: onClientRegistered() - UUID=c341fe67-6a43-4372-b2f9-61b55760e533, clientIf=6
,09-12 13:50:47.027  6155  6164 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 13:50:47.027  6799  6825 D BtGatt.GattService: start scan with filters
09-12 13:50:47.027  6799  6829 D BtGatt.ScanManager: handling starting scan
,09-12 13:50:47.027  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 13:50:47.027  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:50:47.027  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:50:47.027  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:50:47.027  6799  6824 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 13:50:47.027  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:47.027  6799  6829 D BtGatt.ScanManager: allow scan with filters
,09-12 13:50:47.027  6799  6829 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 13:50:47.027  6799  6829 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-12 13:50:47.027  6799  6824 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:50:47.027  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:47.027  6799  6829 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:50:47.027  6799  6829 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 13:50:47.037  6799  6824 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 13:50:47.037  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:47.037  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:47.037  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:47.037  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:50:47.037  6799  6824 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:50:47.037  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:50:47.047  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:50:47.047  6155  6207 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 13:50:47.047  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:47.047  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:47.047  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:47.047  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.047  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:47.047  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f88ed7 removed from the list
09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:47.047  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da483c4 removed from the list
09-12 13:50:47.047  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:47.047  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:47.047  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.047  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 13:50:47.047  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.047  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:47.047  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3da483c4 not in the list
09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:50:47.047  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:50:47.047  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:50:47.047  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:50:47.047  6799  6825 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:50:47.047  6799  6807 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:47.057  6799  6829 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 43
,09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:50:47.057  6799  6829 D BtGatt.ScanManager: filter size is 1
09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:50:47.057  6799  6829 D BtGatt.ScanManager: delete FilterIndex - 4
09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:47.057  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23cd4173 removed from the list
09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:47.057  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:47.057  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3da209e2 removed from the list
,09-12 13:50:47.057  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:47.057  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:47.057  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d3081cf added. We now have 2 listener(s)
09-12 13:50:47.057  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:50:47.057  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:47.057  6799  6824 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 13:50:47.057  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:47.057  6799  6829 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:47.057  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:50:47.057  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4e875c added. We now have 9 listener(s)
09-12 13:50:47.057  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:47.057  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:50:47.067  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-12 13:50:47.067  6799  6824 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 13:50:47.067  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:47.067  6799  6829 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 13:50:47.067  6799  6824 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:50:47.067  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:47.067  6906  6906 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-12 13:50:47.067  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:47.067  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:47.067  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:47.067  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:47.067  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:47.067  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:50:47.067  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:47.067  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:50:47.067  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:50:47.067  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:50:47.067  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:47.067  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb6f33a added. We now have 3 listener(s)
,09-12 13:50:47.077  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:47.077  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:47.077  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:50:47.077  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:47.077  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:47.077  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:47.077  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33dd6beb added. We now have 10 listener(s)
09-12 13:50:47.077  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:47.077  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:50:47.077  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:50:47.077  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:50:47.077  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:50:47.077  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:50:47.077  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:50:47.087  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:50:47.087  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:50:47.087  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:50:47.087  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:50:47.087  6155  6207 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:50:47.087  6799  6813 D BtGatt.GattService: registerClient() - UUID=7aa6b45e-6490-4f91-bd1b-e548e37065b8
,09-12 13:50:47.097   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:50:47.127  6799  6824 D BtGatt.GattService: onClientRegistered() - UUID=7aa6b45e-6490-4f91-bd1b-e548e37065b8, clientIf=6,
09-12 13:50:47.127  6155  6163 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 13:50:47.127  6799  6807 D BtGatt.GattService: start scan with filters
09-12 13:50:47.127  6799  6829 D BtGatt.ScanManager: handling starting scan
09-12 13:50:47.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:50:47.137  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:50:47.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:50:47.137  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:50:47.137  6799  6824 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 13:50:47.137  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:47.137  6799  6829 D BtGatt.ScanManager: allow scan with filters
09-12 13:50:47.137  6799  6829 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 13:50:47.137  6799  6829 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-12 13:50:47.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:50:47.137  6799  6824 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 13:50:47.137  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:47.137  6799  6829 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:50:47.137  6799  6829 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 13:50:47.137  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:50:47.137  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:50:47.147  6799  6824 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 13:50:47.147  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:47.147  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:50:47.147  6799  6824 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:50:47.147  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:47.167  6799  6829 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 44
,09-12 13:50:47.167  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:50:47.167  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:50:47.167  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:50:47.167  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:50:47.167  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:50:47.167  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:50:47.167  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:50:47.167  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d3081cf removed from the list
,09-12 13:50:47.167  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:47.167  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4e875c removed from the list
,09-12 13:50:47.167  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:50:47.167  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:47.167  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:50:47.177  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
09-12 13:50:47.177  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.177  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:50:47.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:50:47.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:47.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:50:47.177  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4e875c not in the list
,09-12 13:50:47.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:50:47.177  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:50:47.177  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:50:47.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:50:47.177  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
09-12 13:50:47.177  6799  6813 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:50:47.177  6799  6829 D BtGatt.ScanManager: filter size is 1
,09-12 13:50:47.177  6799  6829 D BtGatt.ScanManager: delete FilterIndex - 5
09-12 13:50:47.177  6799  6807 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:50:47.177  6799  6824 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 13:50:47.187  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:50:47.187  6906  6906 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,09-12 13:50:47.187  6799  6829 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:50:47.187  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:50:47.187  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:50:47.187  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:50:47.187  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:50:47.187  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:50:47.187  6799  6824 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 13:50:47.187  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:47.187  6799  6829 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:50:47.197  6799  6824 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:50:47.197  6799  6824 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:50:47.197  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:50:47.197  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:50:47.197  6155  6207 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:50:47.197  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:50:47.197  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:47.197  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:50:47.197  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:47.197  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:47.197  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33dd6beb removed from the list
09-12 13:50:47.197  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:47.197  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.197  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:50:47.197  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:47.197  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb6f33a removed from the list
09-12 13:50:47.197  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:47.197  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2224dbc7 added. We now have 2 listener(s)
09-12 13:50:47.207  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:47.207  6155  6155 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:50:47.207  6155  6155 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:50:47.207  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:50:47.207  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:47.207  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:47.207  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:47.207  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79265f4 added. We now have 9 listener(s)
09-12 13:50:47.207  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:50:47.207  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:50:47.217  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:50:47.217  6155  6207 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:50:47.217  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:50:47.217  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:50:47.217  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:50:47.217  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:50:47.217  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
09-12 13:50:47.217  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:50:47.217  6155  6207 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:50:47.217  6155  6207 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:50:47.227  6155  6207 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:50:47.227  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:50:47.227  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ca4af92 added. We now have 3 listener(s)
,09-12 13:50:47.227  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:47.227  6155  6155 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:50:47.227  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:50:47.227  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:50:47.227  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:50:47.227  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:50:47.227  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c896d63 added. We now have 10 listener(s)
09-12 13:50:47.227  6155  6207 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:50:47.227  6155  6207 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:50:47.227  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:50:47.227  6155  6207 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:50:47.227  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:47.227  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.227  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:50:47.227  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:47.227  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2224dbc7 removed from the list
09-12 13:50:47.227  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:47.227  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79265f4 removed from the list
09-12 13:50:47.227  6155  6207 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:50:47.227  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:47.227  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.227  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-12 13:50:47.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:47.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:47.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:47.237  6155  6207 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79265f4 not in the list
09-12 13:50:47.237  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.237  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:47.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:50:47.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:50:47.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:50:47.237  6155  6207 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c896d63 removed from the list
09-12 13:50:47.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:50:47.237  6155  6207 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:50:47.237  6155  6207 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:50:47.237  6155  6207 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:50:47.237  6155  6207 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ca4af92 removed from the list
09-12 13:50:47.237  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 13:50:47.237  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 13:50:47.237  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 13:50:47.237  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:50:47.237  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-12 13:50:47.237  6155  6207 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:50:47.247  6155  6921 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1176, name: My test thread name)
09-12 13:50:47.247  6155  6921 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1176, thread name: My test thread name)
09-12 13:50:47.247  6155  6921 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1176, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 13:50:47.247  6155  6922 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1178, name: My test thread name)
,09-12 13:50:47.247  6155  6922 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1178, thread name: My test thread name)
,09-12 13:50:47.247  6155  6922 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1178, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 13:50:47.257  6155  6207 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-12 13:50:47.257  6155  6207 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 13:50:47.257  6155  6207 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 13:50:47.257  6155  6207 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 13:50:47.257  6155  6207 D com.test.thalitest.ThaliTestRunner: Total duration: 24288 ms
,09-12 13:50:47.257  6155  6207 I jxcore-log: *Native tests were executed*
09-12 13:50:47.257  6155  6207 I jxcore-log: 
,09-12 13:50:47.257  6155  6207 I jxcore-log: Total number of executed tests:  80
09-12 13:50:47.257  6155  6207 I jxcore-log: 
09-12 13:50:47.257  6155  6207 I jxcore-log: Number of passed tests:  80
09-12 13:50:47.257  6155  6207 I jxcore-log: 
,09-12 13:50:47.257  6155  6207 I jxcore-log: Number of failed tests:  0
09-12 13:50:47.257  6155  6207 I jxcore-log: 
09-12 13:50:47.257  6155  6207 I jxcore-log: Number of ignored tests:  0
09-12 13:50:47.257  6155  6207 I jxcore-log: 
,09-12 13:50:47.257  6155  6207 I jxcore-log: Total duration:  24288
09-12 13:50:47.257  6155  6207 I jxcore-log: 
09-12 13:50:47.257  6155  6207 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 13:50:47.257  6155  6207 I jxcore-log: 
,09-12 13:50:47.257  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:50:47.257  6155  6207 I jxcore-log: 
09-12 13:50:47.267  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:50:47.267  6155  6207 I jxcore-log: 
09-12 13:50:47.267  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:50:47.267  6155  6207 I jxcore-log: 
09-12 13:50:47.267  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:50:47.267  6155  6207 I jxcore-log: 
09-12 13:50:47.267  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:50:47.267  6155  6207 I jxcore-log: 
09-12 13:50:47.267  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:50:47.267  6155  6207 I jxcore-log: 
09-12 13:50:47.277  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:50:47.277  6155  6207 I jxcore-log: 
09-12 13:50:47.277  6155  6155 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 13:50:47.277  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:50:47.277  6155  6207 I jxcore-log: 
09-12 13:50:47.277  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.277  6155  6207 I jxcore-log: 
09-12 13:50:47.277  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.277  6155  6207 I jxcore-log: 
09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:50:47.287  6155  6207 I jxcore-log: 
,09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
09-12 13:50:47.287  6155  6207 I jxcore-log: 
,09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.287  6155  6207 I jxcore-log: 
,09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.287  6155  6207 I jxcore-log: 
,09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.287  6155  6207 I jxcore-log: 
,09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.287  6155  6207 I jxcore-log: ,
09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-12 13:50:47.287  6155  6207 I jxcore-log: 
,09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.287  6155  6207 I jxcore-log: 
,09-12 13:50:47.287  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.287  6155  6207 I jxcore-log: 
,09-12 13:50:47.297  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:50:47.297  6155  6207 I jxcore-log: 
09-12 13:50:47.297  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,09-12 13:50:47.297  6155  6207 I jxcore-log: 
09-12 13:50:47.297  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,09-12 13:50:47.297  6155  6207 I jxcore-log: 
09-12 13:50:47.297  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 13:50:47.297  6155  6207 I jxcore-log: 
09-12 13:50:47.297  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 13:50:47.297  6155  6207 I jxcore-log: 
09-12 13:50:47.297  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-12 13:50:47.297  6155  6207 I jxcore-log: 
,09-12 13:50:47.297  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:50:47.297  6155  6207 I jxcore-log: 
,09-12 13:50:47.297  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:50:47.297  6155  6207 I jxcore-log: 
,09-12 13:50:47.397  6155  6155 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-12 13:50:47.397  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:50:47.397  6155  6207 I jxcore-log: 
,09-12 13:50:47.437  1019  1961 V SAMP_SPCM_test: CSC File load.. ,
,09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
,09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-12 13:50:47.447  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-12 13:50:47.477  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars,
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-12 13:50:47.487  1019  1961 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-12 13:50:47.487  1019  1961 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,09-12 13:50:47.487  1019  1961 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:50:47.487  1019  1961 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:47.487  1019  1961 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:47.487  1019  1961 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:47.507  6940  6940 E Zygote  : MountEmulatedStorage()
,09-12 13:50:47.507  6940  6940 E Zygote  : v2,
09-12 13:50:47.507  1019  1961 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6940 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-12 13:50:47.507  6940  6940 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:50:47.507  6940  6940 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:47.507  6940  6940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:50:47.507  6940  6940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:47.517  6940  6940 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:50:47.537  6940  6940 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:47.537  6940  6940 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:47.537  6931  6931 D AndroidRuntime: 
09-12 13:50:47.537  6931  6931 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-12 13:50:47.537  6931  6931 D AndroidRuntime: CheckJNI is OFF,
09-12 13:50:47.537  1019  1131 E WifiNative-wlan0: do suspend true,
09-12 13:50:47.537  6931  6931 D AndroidRuntime: readGMSProperty: start,
09-12 13:50:47.537  6931  6931 D AndroidRuntime: readGMSProperty: already setted!!
09-12 13:50:47.537  6931  6931 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 13:50:47.537  6931  6931 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 13:50:47.537  6931  6931 D AndroidRuntime: readGMSProperty: end
09-12 13:50:47.537  6931  6931 D AndroidRuntime: addProductProperty: start
,09-12 13:50:47.557  6940  6940 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:50:47.557  6155  6155 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:50:47.557  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:50:47.557  6155  6207 I jxcore-log: 
,09-12 13:50:47.567  1019  1130 D WifiP2pService: InactiveState{ what=143375 }
,09-12 13:50:47.567  1019  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
09-12 13:50:47.577  1019  1131 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 13:50:47.577  1019  1131 E WifiStateMachine: VerifyingLinkState enter
09-12 13:50:47.577  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:47.577  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:47.577  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.577  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.577  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.577  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.577  1019  1131 D WifiNative-wlan0: callSECApiInt - ID [210]
09-12 13:50:47.577  1019  1133 E ConnectivityService: updateNetworkInfo()
09-12 13:50:47.577  1019  1133 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-12 13:50:47.577  1019  1133 D ConnectivityService: Adding iface wlan0 to network 504
,09-12 13:50:47.597  1019  1147 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-12 13:50:47.597  1019  1147 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 13:50:47.597  1019  1147 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 13:50:47.597  1019  1147 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 13:50:47.597  1019  1147 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 13:50:47.597  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 13:50:47.597  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:50:47.597  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.597  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:47.597  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:47.597  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:47.607  1019  1253 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-12 13:50:47.607  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:50:47.617  1019  1133 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-12 13:50:47.617  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:47.617  1019  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:47.617  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:47.617  3557  3557 I Hs20UtilService: Starting #22
09-12 13:50:47.617  1019  1133 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-12 13:50:47.617  1019  1961 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-12 13:50:47.617  1019  1131 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-12 13:50:47.617  1019  1133 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504,
,09-12 13:50:47.617  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:50:47.617  1019  1133 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 13:50:47.617  3557  3601 I Hs20UtilService: Message received 5007
09-12 13:50:47.617  1019  1133 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-12 13:50:47.617  1295  1295 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 13:50:47.617  1019  1133 D ConnectivityService: LTETest block dns file not exists
,09-12 13:50:47.627  1019  1133 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-12 13:50:47.627  1019  1133 E ConnectivityService: updateNetworkInfo(),
,09-12 13:50:47.637  1019  1133 E ConnectivityService: updateNetworkInfo()
09-12 13:50:47.637  1019  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:50:47.637  1019  6899 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:47.637  1019  1133 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-12 13:50:47.637  1019  6899 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-12 13:50:47.637  1019  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-12 13:50:47.637  1019  6899 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:50:47.637  1019  6899 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-12 13:50:47.637  1019  6899 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:50:47.637   277   992 D EnterpriseController: uids 1000
09-12 13:50:47.637   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 13:50:47.637   277   992 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-12 13:50:47.637  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:50:47.647  1019  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:50:47.647  1019  1133 D ConnectivityService:    accepting network in place of null
09-12 13:50:47.647  1459  1459 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-12 13:50:47.647  1019  1133 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-12 13:50:47.647  1459  1459 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:50:47.647  1019  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-12 13:50:47.647  1019  1133 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,09-12 13:50:47.647  1182  1182 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:47.657  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 13:50:47.657  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.657  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.657  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.657  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:47.657  1019  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-12 13:50:47.657  1019  1019 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 13:50:47.657  1019  1019 I WifiTrafficPoller: mBoosterFLAG : 0
09-12 13:50:47.657  1019  1019 I WifiTrafficPoller: current booster mode : FullMode
,09-12 13:50:47.657  1019  1019 D WifiNative-wlan0: callSECApiVoid - ID [212],
,09-12 13:50:47.667  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:47.667  1019  1133 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-12 13:50:47.667  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:50:47.667  1019  1133 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-12 13:50:47.667  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:47.667  1019  1019 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-12 13:50:47.667  1019  1134 D Tethering: MasterInitialState.processMessage what=3
09-12 13:50:47.667  1019  1128 V NetworkStats: updateIfacesLocked()
09-12 13:50:47.667  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:47.667  1019  1128 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:50:47.667  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:47.667  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:50:47.677  1182  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:50:47.677  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:47.677  1019  1128 V NetworkStats: performPollLocked() took 6ms
09-12 13:50:47.677  1019  1032 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:47.677  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:50:47.677  3788  6478 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:50:47.677  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:47.677  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:47.677  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:47.677  1019  1129 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 13:50:47.677  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:47.677  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.677  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.677  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:47.677  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:47.677  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:47.677  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:47.677  3557  3557 I Hs20UtilService: Starting #23
09-12 13:50:47.677  3557  3601 I Hs20UtilService: Message received 5007
,09-12 13:50:47.687  6931  6931 E AffinityControl: AffinityControl: registerfunction enter
09-12 13:50:47.687  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:47.687  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:47.687  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:50:47.687  1295  1295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:50:47.687  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-12 13:50:47.687  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:50:47.687  1295  1295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-12 13:50:47.687  1295  1295 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 13:50:47.697  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
09-12 13:50:47.697  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:50:47.697  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 13:50:47.697  1182  1182 D StatusBar.NetworkController: updateDataNetType()
09-12 13:50:47.697  1182  1182 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-12 13:50:47.697  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 13:50:47.707  6155  6155 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:50:47.707  6155  6207 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:50:47.707  6155  6207 I jxcore-log: 
,09-12 13:50:47.707  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 13:50:47.707  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-12 13:50:47.707  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 13:50:47.707  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:47.707  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:50:47.707  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.707  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.707  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:50:47.707  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.707  6931  6931 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-12 13:50:47.717  1019  3138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:50:47.717  1019  3138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:50:47.717  1019  3138 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:47.717  1019  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:47.717  1019  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:50:47.717  3557  3557 I Hs20UtilService: Starting #24
,09-12 13:50:47.717  1295  1295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:50:47.717  3557  3601 I Hs20UtilService: Message received 5007
09-12 13:50:47.717  1295  1295 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 13:50:47.727  1019  6899 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 13:50:47.727  1019  3139 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-12 13:50:47.727  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-12 13:50:47.727  1019  1032 D PackageManager: START PACKAGE DELETE: observer{43544549}
09-12 13:50:47.727  1019  1032 D PackageManager: pkg{<packageName>}
09-12 13:50:47.727  1019  1032 D PackageManager: user{0}
09-12 13:50:47.727  1019  1032 D PackageManager: caller{2000}
09-12 13:50:47.727  1019  1032 D PackageManager: flags{2}
09-12 13:50:47.727  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-12 13:50:47.727  1019  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-12 13:50:47.727  1019  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-12 13:50:47.727  1019  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-12 13:50:47.727  1019  1555 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-12 13:50:47.727  1019  1555 D SecContentProvider2: mCursor = null
09-12 13:50:47.727  1019  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-12 13:50:47.727  1019  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-12 13:50:47.727  1019  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-12 13:50:47.727  1019  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
09-12 13:50:47.727  1019  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-12 13:50:47.727  1019  1480 D SecContentProvider2: uri = 15 selection = getToastGravity
09-12 13:50:47.727  1019  1060 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
09-12 13:50:47.727  1019  1480 D SecContentProvider2: mCursor = null
,09-12 13:50:47.737  1019  3138 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-12 13:50:47.737  1019  3138 D SecContentProvider2: mCursor = null
09-12 13:50:47.737  1019  1045 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
09-12 13:50:47.737  1019  1031 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-12 13:50:47.737  1019  1045 I ActivityManager: Killing 6155:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
09-12 13:50:47.737  1019  1031 D SecContentProvider2: mCursor = null
,09-12 13:50:47.737  1019  1045 I ActivityManager:   Force finishing activity ActivityRecord{3146347f u0 com.test.thalitest/.MainActivity t128},
09-12 13:50:47.737  1019  1545 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-12 13:50:47.737  1019  1545 D SecContentProvider2: mCursor = null
,09-12 13:50:47.737  1019  1045 W ActivityManager: mDVFSHelper.acquire()
,09-12 13:50:47.747  1019  1479 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-12 13:50:47.747  1019  1479 D SecContentProvider2: mCursor = null
,09-12 13:50:47.767  1019  6899 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:50:47 GMT], X-Android-Received-Millis=[1473681047780], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473681047754]}
09-12 13:50:47.777  1019  6899 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 13:50:47.777  1019  6899 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-12 13:50:47.777  1019  1133 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-12 13:50:47.777  1019  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-12 13:50:47.777  1019  1133 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-12 13:50:47.777  1019  1133 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-12 13:50:47.777  3788  6478 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:50:47.777  1019  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:50:47.777  1182  1707 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:50:47.807  1019  1031 I WindowState: WIN DEATH: Window{1877de5f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 13:50:47.807   257  1836 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,09-12 13:50:47.807   257   435 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,09-12 13:50:47.807  1019  1031 D InputDispatcher: Focus left window: 6155
,09-12 13:50:47.817   257   435 I SurfaceFlinger: id=14 Removed NainActivit (-2/8),
,09-12 13:50:47.817  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 13:50:47.817  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:50:47.877  1182  1182 D StatusBar.NetworkController: EthernetConnected: false
,09-12 13:50:47.877  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:50:47.877  1182  1182 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 13:50:47.877  1182  1182 D StatusBar.NetworkController: updateDataNetType()
09-12 13:50:47.877  1182  1182 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-12 13:50:47.877  1182  1182 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-12 13:50:47.877  1182  1182 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 13:50:47.877  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-12 13:50:47.877  1182  1182 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 13:50:47.887  1182  1182 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:50:47.887  1182  1182 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:50:47.887  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.887  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.887  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.887  1182  1182 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:50:47.887  1019  1060 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
09-12 13:50:47.887  1019  1060 I ActivityManager:   Force finishing activity ActivityRecord{3146347f u0 com.test.thalitest/.MainActivity t128 f}
09-12 13:50:47.887  1019  1060 W ActivityManager: Duplicate finish request for ActivityRecord{3146347f u0 com.test.thalitest/.MainActivity t128 f}
,09-12 13:50:47.897   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-12 13:50:47.907  1019  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-12 13:50:47.907  1019  1031 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,09-12 13:50:47.917  1182  1182 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 13:50:47.917  1019  1045 D InputDispatcher: Focused application released
,09-12 13:50:47.927  5618  5618 I art     : Explicit concurrent mark sweep GC freed 2070(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 990us total 25.549ms
,09-12 13:50:47.937  5410  5410 I art     : Explicit concurrent mark sweep GC freed 386(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 739us total 30.308ms
,09-12 13:50:47.947  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 13:50:47.947  1802  1802 E SamsungIME: mOCRHelper is null
,09-12 13:50:47.957  1914  2119 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 13:50:47.967  3788  3788 I art     : Explicit concurrent mark sweep GC freed 29943(1967KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 15MB/26MB, paused 1.355ms total 78.949ms
,09-12 13:50:47.977  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-12 13:50:47.987  3788  3797 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-12 13:50:47.987  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-12 13:50:47.997  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-12 13:50:48.007  3603  3603 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 13:50:47 GMT+02:00 2016
,09-12 13:50:48.007  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:50:48.007  1019  1555 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-12 13:50:48.007  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-12 13:50:48.007  1019  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 13:50:48.007  1019  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:48.007  1019  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:48.007  1019  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
09-12 13:50:48.007  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-12 13:50:48.017  1443  1443 D RegisteredServicesCache: empty dynamic service
,09-12 13:50:48.017  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-12 13:50:48.027  3142  3142 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-12 13:50:48.037  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-12 13:50:48.037  1019  1128 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-12 13:50:48.037  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:48.037  1019  1128 V NetworkStats: performPollLocked(flags=0x3)
,09-12 13:50:48.047  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:50:48.047  1019  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:50:48.047  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
09-12 13:50:48.047  3603  3603 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-12 13:50:48.047  1019  1128 V NetworkStats: performPollLocked() took 13ms
09-12 13:50:48.047  1019  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:48.047  1019  1479 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
09-12 13:50:48.047  1019  1479 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-12 13:50:48.047  1019  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-12 13:50:48.057  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.057  3603  3603 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
09-12 13:50:48.057  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.057  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.057  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.067  1019  3141 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-12 13:50:48.067  1019  3141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-12 13:50:48.067  6972  6972 E Zygote  : MountEmulatedStorage()
09-12 13:50:48.067  6972  6972 E Zygote  : v2
09-12 13:50:48.067  6972  6972 I libpersona: KNOX_SDCARD checking this for 10094
09-12 13:50:48.067  6972  6972 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:48.077  3603  3603 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 13:50:48.077  6972  6972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:50:48.077  6972  6972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:48.077  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-12 13:50:48.077  6972  6972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:50:48.077  1019  1479 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6972 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,09-12 13:50:48.087  1443  1443 D RegisteredComponentCache: Collect Tech packages for Knox
,09-12 13:50:48.087  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:50:48.087  1019  1253 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-12 13:50:48.087  1019  1253 D SecContentProvider2: mCursor = null
,09-12 13:50:48.097  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-12 13:50:48.097   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:50:48.107  3142  3142 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-12 13:50:48.107  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-12 13:50:48.107  3142  3142 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-12 13:50:48.107  3142  3142 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-12 13:50:48.107  3603  3603 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 13:50:48.107  1019  3132 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
09-12 13:50:48.107   287   287 E SMD     : DCD OFF
09-12 13:50:48.117  1019  3132 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 13:50:48.117  1019  3132 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-12 13:50:48.117  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,09-12 13:50:48.117  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-12 13:50:48.117  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-12 13:50:48.117  1019  1019 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-12 13:50:48.117  1019  1019 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-12 13:50:48.117  1019  1019 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-12 13:50:48.117  3142  3142 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-12 13:50:48.127  6972  6972 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.127  1019  1019 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
09-12 13:50:48.127  6972  6972 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.127  1019  1019 I OTPFW   : ProvisionData::getAllEntries Enter
,09-12 13:50:48.127  1019  1019 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-12 13:50:48.127  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-12 13:50:48.127  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicy: uID is 10155
09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 13:50:48.127  3603  6971 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-12 13:50:48.127  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 13:50:48.137  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 13:50:48.137  1019  1019 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicy: uID is 10155
09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 13:50:48.137  1019  2712 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-12 13:50:48.137  1019  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
09-12 13:50:48.137  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-12 13:50:48.137  3603  6971 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,09-12 13:50:48.137   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-12 13:50:48.147  3603  6971 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-12 13:50:48.147  1019  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-12 13:50:48.147  1019  1044 W TextServicesManagerService: no available spell checker services found
,09-12 13:50:48.147  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-12 13:50:48.157  1019  3141 D InputDispatcher: Focus entered window: 3142
,09-12 13:50:48.157  3142  3142 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 13:50:48.157  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:50:48.157  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
09-12 13:50:48.157  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:50:48.157  3603  6971 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-12 13:50:48.157  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.157  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.157  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.157  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.167  1019  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:50:48.177  6988  6988 E Zygote  : MountEmulatedStorage()
09-12 13:50:48.177  6988  6988 I libpersona: KNOX_SDCARD checking this for 10044
09-12 13:50:48.177  6988  6988 E Zygote  : v2
09-12 13:50:48.177  6988  6988 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:48.177  6988  6988 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:48.177  6988  6988 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:48.177  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:50:48.177  6988  6988 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:48.177  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.187  1019  1045 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6988 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-12 13:50:48.197  1019  1479 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 13:50:48.197  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-12 13:50:48.197  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 13:50:48.197  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 13:50:48.207   317   317 I art     : Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 23.596ms
,09-12 13:50:48.217  6988  6988 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.217  6988  6988 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.217  1019  7003 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 13:50:48.227  1019  1164 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-12 13:50:48.227   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.260ms
,09-12 13:50:48.227  1019  1164 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-12 13:50:48.227  1019  1479 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6155 uid 10155
,09-12 13:50:48.227  3142  3142 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@d65b7c7 time:142959
,09-12 13:50:48.247   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 17.259ms
,09-12 13:50:48.247  1182  1182 D PanelView: There is/are notification(s) 
,09-12 13:50:48.257  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.257  1802  1802 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-12 13:50:48.257  1182  1182 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
09-12 13:50:48.257  6972  6972 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-12 13:50:48.257  6972  6972 D elm:15183: ELMEngine.ELMEngine( context ).
,09-12 13:50:48.257  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
09-12 13:50:48.257  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
09-12 13:50:48.257  1182  1182 D PanelView: There is/are notification(s) 
09-12 13:50:48.257  1182  1182 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-12 13:50:48.257  6972  6972 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-12 13:50:48.257  1182  1182 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:50:48.267  1019  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-12 13:50:48.267  1182  1182 D PanelView: There is/are notification(s) 
,09-12 13:50:48.267  1182  1182 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-12 13:50:48.267  3603  6971 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-12 13:50:48.267  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.267  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.267  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.267  1019  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.277  6988  6988 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 13:50:48.277  6988  6988 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:50:48.277  6988  6988 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:50:48.277  6988  6988 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:48.277  6988  6988 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-12 13:50:48.277  6988  6988 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 13:50:48.277  6988  6988 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:50:48.277  6988  6988 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:50:48.277  1019  1045 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7006 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:50:48.287  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:50:48.287  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:50:48.287  7006  7006 E Zygote  : MountEmulatedStorage()
09-12 13:50:48.287  7006  7006 I libpersona: KNOX_SDCARD checking this for 10149
09-12 13:50:48.287  7006  7006 E Zygote  : v2
09-12 13:50:48.287  7006  7006 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:48.287  7006  7006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:48.287  7006  7006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:48.297  7006  7006 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:48.297  3603  6971 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-12 13:50:48.297  3603  6971 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-12 13:50:48.307  3142  3142 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-12 13:50:48.317  6409  6409 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-12 13:50:48.327  1182  1182 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
09-12 13:50:48.327  1019  1031 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-12 13:50:48.327  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:48.327  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-12 13:50:48.327  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:48.327  3142  3142 V ActivityThread: updateVisibility : ActivityRecord{2d4efdb0 token=android.os.BinderProxy@d65b7c7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
09-12 13:50:48.327  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-12 13:50:48.337  6972  6972 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-12 13:50:48.337  7006  7006 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.337  7006  7006 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.347  1019  1050 W ActivityManager: mDVFSHelper.release()
,09-12 13:50:48.347  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b60332f u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:143072
,09-12 13:50:48.347  6972  6972 D elm:15183: ElmAgentService : onCreate()
,09-12 13:50:48.357  6972  7021 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-12 13:50:48.357  6972  7021 D elm:15183: MainReceiver.listeningToPackageRemoved()
,09-12 13:50:48.357  6972  7021 D elm:15183: MDMBridge.getInstance()
09-12 13:50:48.357  6972  7021 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 13:50:48.377  1019  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-12 13:50:48.377  6972  7021 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 13:50:48.387  1914  1914 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-12 13:50:48.387  3603  3603 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-12 13:50:48.397  6940  7005 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-12 13:50:48.397  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.397  3292  3292 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-12 13:50:48.397  3292  3292 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-12 13:50:48.397  3292  3292 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-12 13:50:48.397  3292  3292 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
,09-12 13:50:48.397  3292  3292 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-12 13:50:48.397  3292  3292 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-12 13:50:48.397  3292  3292 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-12 13:50:48.397  3292  3292 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:48.397  3292  3292 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:48.397  3292  3292 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:48.397  3292  3292 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,09-12 13:50:48.397  3292  3292 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:48.397  3292  3292 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:48.397  3292  3292 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:50:48.407  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.417  6392  6392 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-12 13:50:48.417  6392  6392 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 13:50:48.417  6392  6392 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 13:50:48.417  6392  6392 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-12 13:50:48.417  1019  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-12 13:50:48.427  6972  6972 D elm:15183: ElmAgentService : onDestroy().
,09-12 13:50:48.427  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.427  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.427  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.427  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.447  7024  7024 E Zygote  : MountEmulatedStorage()
09-12 13:50:48.447  7024  7024 E Zygote  : v2
09-12 13:50:48.447  7024  7024 I libpersona: KNOX_SDCARD checking this for 10032
09-12 13:50:48.447  6940  6940 I art     : Explicit concurrent mark sweep GC freed 9030(429KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 828us total 56.756ms
09-12 13:50:48.447  7024  7024 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:48.457  1019  1032 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7024 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
,09-12 13:50:48.457  7024  7024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:50:48.457  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:50:48.457  7024  7024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:48.457  7024  7024 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:48.477  1019  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:50:48.477  1019  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:50:48.477  1019  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:50:48.477  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.487  7024  7024 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.487  7024  7024 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.497  7006  7006 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-12 13:50:48.497  7006  7006 D ThemeInfoUtil: isCurrentFestival = false
,09-12 13:50:48.507  1019  3132 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:50:48.507  1019  3132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-12 13:50:48.507  1019  3132 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:48.507  1019  3132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:48.507  1019  3132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:48.517  1019  1060 I art     : Explicit concurrent mark sweep GC freed 80552(5MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 28MB/42MB, paused 5.368ms total 499.079ms
,09-12 13:50:48.517  1019  1029 I art     : WaitForGcToComplete blocked for 324.317ms for cause HeapTrim
09-12 13:50:48.517  1019  1253 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-12 13:50:48.517  1019  1253 D SecContentProvider2: mCursor = null
,09-12 13:50:48.517  5956  5964 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-12 13:50:48.517  5956  5964 D BadgeProvider: sendNotify, [notify] : null
09-12 13:50:48.517  5956  5964 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-12 13:50:48.517  5956  5964 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 13:50:48.517  5956  5964 D BadgeProvider: update, [UpdateCount] : 1
,09-12 13:50:48.517  1019  3141 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-12 13:50:48.527  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.527  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.527  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.527  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.537  1019  1060 D PackageManager: delete codoeFile: 
,09-12 13:50:48.547  7043  7043 E Zygote  : MountEmulatedStorage()
,09-12 13:50:48.547  7043  7043 E Zygote  : v2
09-12 13:50:48.547  7043  7043 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:50:48.547  7043  7043 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:48.547  7043  7043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:48.547  7043  7043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-12 13:50:48.547  1019  3141 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7043 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 13:50:48.547  7043  7043 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:48.557  1019  1060 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,09-12 13:50:48.557  1019  1060 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-12 13:50:48.557  1019  3141 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-12 13:50:48.567  1019  1060 D PackageManager: result of delete: 1{43544549}
,09-12 13:50:48.567  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.567  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.567  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.567  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.577  6931  6931 D AndroidRuntime: Shutting down VM
,09-12 13:50:48.577  7058  7058 E Zygote  : MountEmulatedStorage(),
09-12 13:50:48.577  7058  7058 E Zygote  : v2
09-12 13:50:48.577  7058  7058 I libpersona: KNOX_SDCARD checking this for 10152
09-12 13:50:48.577  7058  7058 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:48.577  7058  7058 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:50:48.587  7058  7058 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:48.587  1019  3141 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7058 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,09-12 13:50:48.587  7058  7058 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:48.597  7043  7043 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.597  1019  3141 I ActivityManager: Killing 6080:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-12 13:50:48.597  7043  7043 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.607  1019  1321 I ActivityManager: Killing 6103:com.samsung.helphub/1000 (adj 15): empty #31
,09-12 13:50:48.617  7058  7058 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.617  7058  7058 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.637  6988  6988 D NearbySource: Nearby Source Create!
,09-12 13:50:48.637  6988  6988 D NearbyContext: Nearby Context Create!
,09-12 13:50:48.647  7024  7073 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-12 13:50:48.657  1019  3141 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 13:50:48.657  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.657  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.657  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.657  1019  3141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.667  1019  1133 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-12 13:50:48.667  7076  7076 E Zygote  : MountEmulatedStorage(),
09-12 13:50:48.667  7076  7076 E Zygote  : v2
09-12 13:50:48.667  7076  7076 I libpersona: KNOX_SDCARD checking this for 10035
09-12 13:50:48.667  7076  7076 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:48.667  7076  7076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:48.677  1019  3141 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7076 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:50:48.677  7076  7076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:48.677  1019  3141 I ActivityManager: Killing 5410:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-12 13:50:48.677  7076  7076 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 13:50:48.697   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-12 13:50:48.697   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:50:48.697  6988  6988 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-12 13:50:48.697  7043  7043 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-12 13:50:48.697  6988  6988 D SLinkSource: Samsung link source created
,09-12 13:50:48.707  1019  1555 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:50:48.717  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.717  7058  7058 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-12 13:50:48.717  1019  1321 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-12 13:50:48.717  1019  1321 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-12 13:50:48.717  1019  1321 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:48.717  1019  1321 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:48.717  1019  1321 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-12 13:50:48.727  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.737  7076  7076 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.737  7076  7076 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.737  1019  1555 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-12 13:50:48.737  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:50:48.737  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:50:48.737  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.737  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.737  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.737  1019  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.737  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.737  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:50:48.737  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:50:48.747  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:50:48.747  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:50:48.747  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:50:48.747  7092  7092 E Zygote  : MountEmulatedStorage()
09-12 13:50:48.747  7092  7092 E Zygote  : v2
09-12 13:50:48.747  7092  7092 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:50:48.747  7092  7092 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:48.747  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:48.757  1019  1555 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7092 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-12 13:50:48.757  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:48.757  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:50:48.777  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.777  7092  7092 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.777  1019  1480 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,09-12 13:50:48.777  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-12 13:50:48.787  1019  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-12 13:50:48.787  1019  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest,
09-12 13:50:48.787  6799  6822 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 13:50:48.787  1019  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:50:48.787  7024  7073 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-12 13:50:48.787  7024  7073 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:50:48.787  7024  7073 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:50:48.787  7024  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:48.787  7024  7073 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
09-12 13:50:48.787  7024  7073 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.,
,09-12 13:50:48.797  6931  6931 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-12 13:50:48.797  1019  1480 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:50:48.797  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:50:48.797  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
09-12 13:50:48.797  1914  1914 I art     : Explicit concurrent mark sweep GC freed 38841(2MB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 13MB/22MB, paused 1.637ms total 73.727ms
,09-12 13:50:48.807  1019  1253 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-12 13:50:48.817  7024  7073 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-12 13:50:48.817  7024  7073 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 13:50:48.817  7024  7073 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:50:48.817  7024  7073 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:50:48.817  7024  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:48.817  7024  7073 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:50:48.817  1019  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.817  1019  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.817  1019  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.817  1019  1253 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.827  7092  7092 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:50:48.837  7110  7110 E Zygote  : MountEmulatedStorage()
09-12 13:50:48.837  7110  7110 E Zygote  : v2
09-12 13:50:48.837  7110  7110 I libpersona: KNOX_SDCARD checking this for 10156
09-12 13:50:48.837  7110  7110 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:48.837  7110  7110 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:48.837  1019  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-12 13:50:48.837  1019  1060 D PackageManager: userId{-1}
09-12 13:50:48.837  1019  1060 D PackageManager: andCode{true}
,09-12 13:50:48.837  7110  7110 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:50:48.837  7110  7110 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:50:48.847  1019  1253 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7110 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,09-12 13:50:48.867  1019  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:50:48.867  1019  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
09-12 13:50:48.867  1019  3141 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:50:48.867  7024  7073 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:50:48.867  7024  7073 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:50:48.867  7024  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:50:48.867  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:48.867  1019  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:48.867  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:48.867  7110  7110 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.877  7110  7110 D ActivityThread: Added TimaKeyStore provider
,09-12 13:50:48.877  1019  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-12 13:50:48.897  1019  1547 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:50:48.897  6988  6988 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-12 13:50:48.897  6940  7040 E SQLiteLog: (10) unixWrite() File Descriptor : 26 gets errno : 9
09-12 13:50:48.897  6940  7040 E SQLiteLog: (10) unixWrite() File Descriptor : 26 gets errno : 9
,09-12 13:50:48.907  6940  7040 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:211)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:50:48.907  6940  7040 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-12 13:50:48.907  6940  7040 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,09-12 13:50:48.907  6940  7040 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:212)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:48.907  6940  7040 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:50:48.907  7024  7073 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 13:50:48.907  7024  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:48.907  7024  7073 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-12 13:50:48.917  7092  7092 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-12 13:50:48.917  6940  7040 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-12 13:50:48.917  1019  1480 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-12 13:50:48.917  6940  7040 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
09-12 13:50:48.917  1019  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-12 13:50:48.917  1019  1547 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-12 13:50:48.917  1019  1547 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-12 13:50:48.917  6940  7040 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.0.2
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:213)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:50:48.917  6988  7109 D ContactProvider: getAllContactInfoList Start
,09-12 13:50:48.917  1019  1253 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:50:48.917  1019  1253 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-12 13:50:48.917  6940  7040 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-12 13:50:48.917  1019  1253 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:50:48.917  6940  7040 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
09-12 13:50:48.917  1019  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:50:48.917  1019  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:50:48.917  6940  7040 E SQLiteDatabase: Error inserting name=status value=successfully initialized
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487),
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:214)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:48.917  6940  7040 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:50:48.927  6988  6988 E SharedPreferencesImpl: Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,09-12 13:50:48.927  1019  3139 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
09-12 13:50:48.927  7024  7073 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:50:48.927  7024  7073 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:50:48.927  7024  7073 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:50:48.927  7024  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:48.927  7024  7073 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-12 13:50:48.927  7024  7073 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 13:50:48.927  7024  7073 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:50:48.927  7024  7073 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:50:48.927  1019  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.927  1019  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.927  1019  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.927  1019  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.937  7110  7110 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-12 13:50:48.937  7076  7130 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 13:50:48.937  7076  7130 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 13:50:48.937  7110  7110 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-12 13:50:48.947  7132  7132 E Zygote  : MountEmulatedStorage()
09-12 13:50:48.947  1019  3139 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7132 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:50:48.947  7132  7132 E Zygote  : v2
09-12 13:50:48.947  7132  7132 I libpersona: KNOX_SDCARD checking this for 10091
09-12 13:50:48.947  7132  7132 I libpersona: KNOX_SDCARD not a persona
09-12 13:50:48.947  7024  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:48.947  7024  7073 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:50:48.947  7024  7073 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:50:48.947  1019  3139 I ActivityManager: Killing 5540:com.android.vending/u0a28 (adj 15): empty #31,
09-12 13:50:48.947  7132  7132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:48.957  7132  7132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:50:48.957  7132  7132 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 13:50:48.957  1019  3139 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
09-12 13:50:48.957  7024  7073 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-12 13:50:48.957  7024  7073 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:50:48.957  7024  7073 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:50:48.957  7024  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:48.957  7024  7073 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 13:50:48.967  1019  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.967  1019  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.967  1019  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:50:48.967  1019  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:50:48.967  7110  7110 I TapandpayWidget:Utils: Clear T&P info.
,09-12 13:50:48.967  7076  7130 D SPPClientService: PushLog.txt file is not deleted.
,09-12 13:50:48.967  7076  7130 D SPPClientService: PushLog.txt file is not deleted.
09-12 13:50:48.967  7076  7130 D SPPClientService: ============PushLog. stop!
,09-12 13:50:48.977  7024  7073 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-12 13:50:48.977  7024  7073 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:50:48.977  7024  7073 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:50:48.977  7024  7073 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:50:48.977  7076  7076 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,09-12 13:50:48.977  7076  7076 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.b(Unknown Source)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.a(Unknown Source)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.i.handleMessage(Unknown Source)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:50:48.977  7076  7076 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:50:48.977  7076  7076 E LNoti   : [b] open fail. SQLException occured
,09-12 13:50:48.977  7149  7149 E Zygote  : MountEmulatedStorage()
09-12 13:50:48.977  7149  7149 E Zygote  : v2
09-12 13:50:48.977  7149  7149 I libpersona: KNOX_SDCARD checking this for 10046
09-12 13:50:48.977  7149  7149 I libpersona: KNOX_SDCARD not a persona
,09-12 13:50:48.977  7149  7149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:50:48.987  7149  7149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:50:48.987  1019  3139 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7149 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-12 13:50:48.987  7149  7149 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 13:50:48.987  1019  3139 I ActivityManager: Killing 6455:com.android.chrome/u0a81 (adj 15): empty #31
,09-12 13:50:48.997  7132  7132 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:50:48.997  7132  7132 D ActivityThread: Added TimaKeyStore provider

```
