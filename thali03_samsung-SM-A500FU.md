#### Test 84648740f6d448c_thali03_samsung-SM-A500FU Logs


```
--------- beginning of system
09-09 17:17:29.034  1016  3272 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
09-09 17:17:29.034  1016  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:29.034  1016  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:29.034  1016  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:29.034  1016  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
09-09 17:17:29.054  6151  6151 E Zygote  : MountEmulatedStorage()
09-09 17:17:29.054  6151  6151 E Zygote  : v2
09-09 17:17:29.054  6151  6151 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 17:17:29.054  6151  6151 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:29.054  6151  6151 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 17:17:29.054  6151  6151 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:17:29.054  6151  6151 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:29.084  1016  3272 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6151 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-09 17:17:29.084  1016  3272 I ActivityManager: Killing 5656:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
09-09 17:17:29.094  6151  6151 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:29.094  6151  6151 D ActivityThread: Added TimaKeyStore provider
09-09 17:17:29.094   302   302 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 785us total 24.808ms
,09-09 17:17:29.114   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 779us total 20.587ms
09-09 17:17:29.134   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 19.608ms
09-09 17:17:29.144  1016  1724 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-09 17:17:29.154  1016  1724 I ActivityManager: Killing 4383:com.google.android.music:main/u0a111 (adj 15): empty #31
09-09 17:17:29.154  6151  6168 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
09-09 17:17:29.154  6151  6168 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-09 17:17:29.154  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:29.154  1016  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:29.154  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 17:17:29.164  1016  3272 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-09 17:17:29.164  1016  3272 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-09 17:17:29.164  1016  3272 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:29.164  1016  3272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:29.164  1016  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-09 17:17:29.174  6151  6151 D AcmsService: Enter Oncreate
09-09 17:17:29.174  6151  6151 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 17:17:29.174  6151  6151 D AcmsService: creating AcmsCore
09-09 17:17:29.174  6151  6151 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-09 17:17:29.174  6151  6151 D AcmsCore: AcmsCore
09-09 17:17:29.174  6151  6151 D AcmsCore: init
09-09 17:17:29.174  6151  6151 D AcmsCore: Looper handler is not null
09-09 17:17:29.174  6151  6151 D AcmsCore: Post to AcmsCoreHandler
09-09 17:17:29.174  6151  6151 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 17:17:29.174  6151  6151 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-09 17:17:29.174  6151  6151 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-09 17:17:29.174  6151  6151 D AcmsService: onStartCommand
09-09 17:17:29.174  6151  6151 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-09 17:17:29.184  6151  6151 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-09 17:17:29.184  6151  6151 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-09 17:17:29.184  6151  6151 D AcmsService: Incremented Counter Value : onStartCommand
09-09 17:17:29.184  6151  6171 D AcmsCertificateMngr: AcmsCertificateMngr
09-09 17:17:29.184  1016  1252 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-09 17:17:29.184  6151  6151 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-09 17:17:29.184  6151  6171 D AcmsRevocationMngr: AcmsRevocationMngr
09-09 17:17:29.214  6151  6151 D AcmsService: Inside handle Intent
09-09 17:17:29.214  6151  6151 D AcmsService: App added - package name: com.test.thalitest
09-09 17:17:29.214  6151  6151 D AcmsCore: Post to AcmsCoreHandler
09-09 17:17:29.214  6151  6151 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 17:17:29.214  6151  6151 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-09 17:17:29.214  6151  6151 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-09 17:17:29.214  6151  6151 D AcmsService: Decremented Counter Value : handleStartIntent
09-09 17:17:29.214  6151  6151 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-09 17:17:29.224  5880  5880 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
09-09 17:17:29.344  6169  6169 D AndroidRuntime: 
09-09 17:17:29.344  6169  6169 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 17:17:29.344  6169  6169 D AndroidRuntime: CheckJNI is OFF
09-09 17:17:29.344  6169  6169 D AndroidRuntime: readGMSProperty: start
09-09 17:17:29.344  6169  6169 D AndroidRuntime: readGMSProperty: already setted!!
09-09 17:17:29.344  6169  6169 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 17:17:29.344  6169  6169 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 17:17:29.344  6169  6169 D AndroidRuntime: readGMSProperty: end
09-09 17:17:29.344  6169  6169 D AndroidRuntime: addProductProperty: start
09-09 17:17:29.474  6169  6169 E AffinityControl: AffinityControl: registerfunction enter
09-09 17:17:29.494  6169  6169 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 17:17:29.504  1016  1028 E PersonaManagerService: inState():  stateMachine is null !!
09-09 17:17:29.504  1016  1028 I PersonaManagerService: PersonaId don't exist
09-09 17:17:29.504  1016  1028 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 17:17:29.504  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 17:17:29.514  1016  1028 W ActivityManager: mDVFSHelper.acquire()
09-09 17:17:29.524  1016  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 17:17:29.524  1016  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 17:17:29.534  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:29.534  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:29.534  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:29.534  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:29.544  6182  6182 E Zygote  : MountEmulatedStorage()
09-09 17:17:29.544  6182  6182 E Zygote  : v2
09-09 17:17:29.544  6182  6182 I libpersona: KNOX_SDCARD checking this for 10155
09-09 17:17:29.544  6182  6182 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:29.544  6182  6182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 17:17:29.544  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-09 17:17:29.544  1016  1028 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6182 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 17:17:29.544  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 17:17:29.544  1016  1028 D InputDispatcher: Focused application set to: xxxx
09-09 17:17:29.544  3810  4306 I Icing   : Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
09-09 17:17:29.544  1016  1028 D InputDispatcher: Focus left window: 3143
09-09 17:17:29.544  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 17:17:29.544  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 17:17:29.544  6182  6182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:29.544  6182  6182 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 17:17:29.554   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-09 17:17:29.554  6169  6169 D AndroidRuntime: Shutting down VM
09-09 17:17:29.564  6182  6182 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:29.564  6182  6182 D ActivityThread: Added TimaKeyStore provider
09-09 17:17:29.574  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 17:17:29.574  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 17:17:29.584  1016  1016 V ActivityManager: Display changed displayId=0
09-09 17:17:29.594  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 17:17:29.604  1016  3273 D PersonaManager: isKioskContainerExistOnDevice
09-09 17:17:29.664  5814  5814 I Mms/MmsApp:  start initViewCache mms
09-09 17:17:29.664  5814  5814 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1846.527812
09-09 17:17:29.664  5814  5814 D Mms/ComposeMessageFragment: fillCache, easy = false
09-09 17:17:29.664   257  1038 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
09-09 17:17:29.674   257   438 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
09-09 17:17:29.684  3143  3143 V ActivityThread: updateVisibility : ActivityRecord{3e86cb5a token=android.os.BinderProxy@29202939 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-09 17:17:29.744  6182  6182 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-09 17:17:29.744  5814  5814 D AbsListView: Get MotionRecognitionManager
09-09 17:17:29.744  1016  1724 I art     : Explicit concurrent mark sweep GC freed 147699(8MB) AllocSpace objects, 3(1841KB) LOS objects, 33% free, 28MB/42MB, paused 2.843ms total 196.342ms
09-09 17:17:29.754  1016  1029 D MotionRecognitionService:  ssp status : false
09-09 17:17:29.754  6169  6169 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 17:17:29.764  6182  6182 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1818-1822)
09-09 17:17:29.764  6182  6182 I LibraryLoader: Expected native library version number "",actual native library version number "",
09-09 17:17:29.774  5814  5814 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 111.687708
09-09 17:17:29.784  6182  6182 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3bd1836}
09-09 17:17:29.794  6182  6182 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 17:17:29.794  6182  6182 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 17:17:29.824  6182  6182 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 17:17:29.824  6182  6182 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 17:17:29.824  6182  6182 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 17:17:29.854  6182  6182 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
09-09 17:17:29.854  3810  4306 I Icing   : Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
09-09 17:17:29.854  6182  6182 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
09-09 17:17:29.854  6182  6182 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
09-09 17:17:29.854  6182  6182 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 17:17:29.854  6182  6182 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 17:17:29.854  6182  6182 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 17:17:29.854  6182  6182 I Adreno-EGL: Local Branch: 
09-09 17:17:29.854  6182  6182 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 17:17:29.854  6182  6182 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 17:17:29.854  6182  6182 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-09 17:17:29.874  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-09 17:17:29.874  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:29.874  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:29.874  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 17:17:29.904  5814  5814 D Mms/BubbleViewCache: fillCache bubble = 1
09-09 17:17:29.974  6182  6212 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
09-09 17:17:30.034  6182  6182 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 17:17:30.054  6182  6182 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-09 17:17:30.054  6182  6182 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 17:17:30.054  6182  6182 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-09 17:17:30.064  6182  6182 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-09 17:17:30.074  6182  6182 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 17:17:30.074  6182  6182 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 17:17:30.114  1016  1042 W ActivityManager: Activity pause timeout for ActivityRecord{3e962225 u0 com.test.thalitest/.MainActivity t128}
09-09 17:17:30.124  6182  6225 D OpenGLRenderer: Render dirty regions requested: true
09-09 17:17:30.124  1016  1389 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 17:17:30.124  1016  1389 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 17:17:30.124  1016  1389 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 17:17:30.124  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 17:17:30.124  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 17:17:30.134  6182  6182 V ActivityThread: updateVisibility : ActivityRecord{2e5db79 token=android.os.BinderProxy@1cd20fc3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 17:17:30.134  6182  6182 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 17:17:30.134  6182  6182 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 17:17:30.144   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
09-09 17:17:30.154  1016  3138 D InputDispatcher: Focus entered window: 6182
09-09 17:17:30.164  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 17:17:30.164  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 17:17:30.164  6182  6182 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-09 17:17:30.164  6182  6225 I OpenGLRenderer: Initialized EGL, version 1.4
09-09 17:17:30.164  6182  6225 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-09 17:17:30.164  6182  6225 D OpenGLRenderer: Enabling debug mode 0
09-09 17:17:30.204  1016  1028 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-09 17:17:30.214  1016  6228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-09 17:17:30.214  1173  1173 D PanelView: There is/are notification(s) 
09-09 17:17:30.224  1016  1047 I ActivityManager: Displayed Component not be shown by security: +609ms (total +691ms)
09-09 17:17:30.224  6182  6182 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-09 17:17:30.224  6182  6182 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1cd20fc3 time:102283
09-09 17:17:30.224  1016  1047 W ActivityManager: mDVFSHelper.release()
09-09 17:17:30.224  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3e962225 u0 com.test.thalitest/.MainActivity t128} time:102287
09-09 17:17:30.234   257   438 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
09-09 17:17:30.234   257  1038 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
09-09 17:17:30.234  1795  1795 I SamsungIME: getCurrentCandidateView
09-09 17:17:30.304  6182  6182 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6182
09-09 17:17:30.354  1795  1795 D SamsungIME: Dismiss ExpandCandiate
09-09 17:17:30.424  6182  6182 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 17:17:30.494  1795  1795 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 17:17:30.524  6182  6230 D jxcore_app_log: JniHelper::setJavaVM(0xb700a328), pthread_self() = -1219069856
,09-09 17:17:30.524  1795  1795 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 17:17:30.534  6182  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 17:17:30.534  6182  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 17:17:30.534  6182  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 17:17:30.534  6182  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 17:17:30.534  6182  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 17:17:30.534  6182  6230 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34b794e9 added. We now have 1 listener(s)
,09-09 17:17:30.544  1795  1795 I SamsungIME: KeybaordView init() : load resources
,09-09 17:17:30.544  6182  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-09 17:17:30.544  6182  6230 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 17:17:30.544  6182  6230 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 17:17:30.544  6182  6230 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 17:17:30.554  6182  6230 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33f08c9c added. We now have 1 listener(s)
,09-09 17:17:30.554  6182  6230 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:30.554  6182  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:17:30.564  6182  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 17:17:30.564  6182  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 17:17:30.564  6182  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 17:17:30.564  6182  6230 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 17:17:30.564  6182  6230 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:30.564  6182  6230 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-09 17:17:30.574  6182  6230 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 17:17:30.574  6182  6230 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:30.574  6182  6230 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:30.574  6182  6230 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:30.574  6182  6230 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:30.574  6182  6230 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:30.574  6182  6230 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:30.574  6182  6230 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:30.574  6182  6230 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:30.574  6182  6230 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 17:17:30.574  6182  6230 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:30.574  6182  6230 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 17:17:30.574  1795  1795 I SamsungIME: getCurrentKeyboard
09-09 17:17:30.574  1795  1795 I SamsungIME: getTextKeyboard
,09-09 17:17:30.584  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-09 17:17:30.584  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:30.604  1795  1795 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 17:17:30.614  6182  6182 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 17:17:31.154  1795  6236 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 17:17:31.164  6182  6235 W jxcore-log: Initializing JXcore engine
09-09 17:17:31.164  6182  6235 W jxcore-log: JXcore engine is ready
,09-09 17:17:31.214  1889  1889 E audit   : type=1400 msg=audit(1473434251.214:205): avc:  denied  { ioctl } for  pid=6235 comm="Thread-1079" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 17:17:31.214  1889  1889 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:31.214  1889  1889 E audit   : type=1300 msg=audit(1473434251.214:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e9008f8 items=0 ppid=302 ppcomm=main pid=6235 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1079" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 17:17:31.214  1889  1889 E audit   : type=1320 msg=audit(1473434251.214:205): 
,09-09 17:17:31.234  6182  6235 W jxcore-log: Starting JXcore engine
,09-09 17:17:31.334  6182  6235 W jxcore-log: Platform android
09-09 17:17:31.334  6182  6235 W jxcore-log: 
09-09 17:17:31.334  6182  6235 W jxcore-log: Process ARCH arm
09-09 17:17:31.334  6182  6235 W jxcore-log: 
,09-09 17:17:31.534  6182  6235 I jxcore-log: JXcore Cordova bridge is ready!
09-09 17:17:31.534  6182  6235 I jxcore-log: 
,09-09 17:17:31.534  6182  6235 W jxcore-log: JXcore engine is started
,09-09 17:17:31.544  6182  6230 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 17:17:31.544  6182  6182 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 17:17:31.764   287   287 E SMD     : DCD OFF,
,09-09 17:17:32.954  6151  6171 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-09 17:17:32.974  6151  6171 I AcmsKeyStoreHelper: Key Store exist
,09-09 17:17:32.974  6151  6171 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-09 17:17:33.044  6151  6171 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-09 17:17:33.044  6151  6171 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-09 17:17:33.044  6151  6171 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-09 17:17:33.044  6151  6171 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 17:17:33.044  6151  6171 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-09 17:17:33.044  6151  6171 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-09 17:17:33.044  6151  6171 D AcmsCore: This is NOT a valid MirrorLink app
09-09 17:17:33.044  6151  6171 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-09 17:17:33.044  6151  6171 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 17:17:33.044  6151  6171 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-09 17:17:33.044  6151  6171 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-09 17:17:33.044  6151  6151 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-09 17:17:33.044  6151  6151 D AcmsService: Enter onDestroy
09-09 17:17:33.044  6151  6151 I AcmsService: cleanUp(): inside service clean up
,09-09 17:17:33.044  6151  6151 D AcmsCore: AcmsCore: inside DeInit
09-09 17:17:33.044  6151  6151 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,09-09 17:17:33.044  6151  6151 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,09-09 17:17:33.044  6151  6151 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-09 17:17:33.044  6151  6151 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-09 17:17:33.044  6151  6151 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,09-09 17:17:33.044  6151  6151 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-09 17:17:33.044  6151  6151 D AcmsService: killing acms process
,09-09 17:17:33.044  6151  6151 I Process : Sending signal. PID: 6151 SIG: 9
,09-09 17:17:33.174  1016  1029 I ActivityManager: Process ACMS.Process (pid 6151)(adj 0) has died(37,1127)
,09-09 17:17:33.744  1016  3139 D ActivityManager: bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-09 17:17:33.744  1016  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-09 17:17:33.744  1016  3139 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:33.744  1016  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:33.744  1016  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,09-09 17:17:33.964  1016  3058 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 17:17:33.964  1016  3058 D BatteryService: level:75, scale:100, status:2, health:2, present:true, voltage: 3995, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 17:17:33.964  1016  3058 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 17:17:33.964  1016  3058 D BatteryService: stay LED for charging
,09-09 17:17:33.964  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 17:17:33.964  1016  1016 I MotionRecognitionService: Plugged
,09-09 17:17:33.964  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 17:17:33.974  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 17:17:33.974  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 75
,09-09 17:17:33.974  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 17:17:33.984  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 17:17:33.984  2655  2655 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 17:17:33.984  2655  2736 D HeadsetStateMachine: Disconnected process message: 10
,09-09 17:17:33.984  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:17:33.984  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-09 17:17:33.984  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-09 17:17:34.764   287   287 E SMD     : DCD OFF,
,09-09 17:17:35.844  1016  1095 V AlarmManager: waitForAlarm result :4
,09-09 17:17:35.864  1016  1049 I PowerManagerService: [PWL] Off : 30s ago
,09-09 17:17:35.884  1016  2734 D SSRM:n  : SIOP:: AP = 410
,09-09 17:17:36.124  1016  1299 E Watchdog: !@Sync 3
,09-09 17:17:36.824   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-09 17:17:36.824   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-09 17:17:37.764   287   287 E SMD     : DCD OFF
,09-09 17:17:38.284  1016  1057 D PackageManager: [MSG] MCS_UNBIND
,09-09 17:17:38.294  1016  1724 I ActivityManager: Killing 5144:com.google.android.gm/u0a101 (adj 15): empty #31
,09-09 17:17:39.534  1016  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 17:17:40.764   287   287 E SMD     : DCD OFF
,09-09 17:17:41.604  5385  5385 D FactoryTest: Not factory mode
,09-09 17:17:41.604  5385  5385 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-09 17:17:41.604  5385  5385 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-09 17:17:41.614  5385  5385 D MTPRx   : still no open session command from host, so toast
,09-09 17:17:41.614  5385  5385 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-09 17:17:41.614  5385  5385 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-09 17:17:41.614  5385  5385 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113671
,09-09 17:17:41.614  1016  3269 E PersonaManagerService: inState():  stateMachine is null !!
09-09 17:17:41.614  1016  3269 I PersonaManagerService: PersonaId don't exist
09-09 17:17:41.614  1016  3269 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-09 17:17:41.614  1016  3269 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-09 17:17:41.614  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:41.614  1016  3269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:41.614  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-09 17:17:41.624  1016  3269 W ActivityManager: mDVFSHelper.acquire(),
,09-09 17:17:41.634  1016  3269 D PersonaManager: isKioskContainerExistOnDevice
,09-09 17:17:41.634  1016  3269 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 17:17:41.634  1016  3269 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 17:17:41.634  1016  3269 D InputDispatcher: Focused application set to: xxxx
,09-09 17:17:41.644  1016  3269 D InputDispatcher: Focus left window: 6182
,09-09 17:17:41.644  5385  5385 E MTPRx   : started activity for popup
,09-09 17:17:41.644  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 17:17:41.644  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 17:17:41.674  5385  5385 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-09 17:17:41.674  5385  5385 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-09 17:17:41.674  5385  5385 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 17:17:41.674  5385  5385 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:17:41.674  5385  5385 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 17:17:41.684  5385  5385 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:17:41.694  5385  5385 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-09 17:17:41.694  1016  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 17:17:41.694  1016  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 17:17:41.694  1016  1489 D InputDispatcher: Focused application set to: xxxx
,09-09 17:17:41.704  1016  1489 D InputDispatcher: Focus entered window: 6182
,09-09 17:17:41.704  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 17:17:41.704  1016  3138 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 17:17:41.704  1016  3138 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@22b829f1 attribute=null, token = android.os.BinderProxy@22239705
,09-09 17:17:41.704  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 17:17:41.744  5385  5385 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-09 17:17:41.754  5385  5385 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-09 17:17:41.754  5385  5385 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-09 17:17:41.774  6182  6182 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 17:17:41.774  6182  6182 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-09 17:17:41.774  6182  6182 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 17:17:41.774  6182  6182 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-09 17:17:41.784  1016  1252 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 17:17:41.784  1016  1252 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 17:17:41.784  1016  1252 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 17:17:41.784  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 17:17:41.784  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 17:17:41.794  6182  6182 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 17:17:41.794  6182  6182 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 17:17:41.804  6182  6182 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@20d9fae6 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@224115c5, 16908290=android.view.AbsSavedState$1@224115c5}, android:focusedViewId=100}]}]
,09-09 17:17:41.804  6182  6182 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-09 17:17:41.804  6182  6182 V ActivityThread: updateVisibility : ActivityRecord{2e5db79 token=android.os.BinderProxy@1cd20fc3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 17:17:41.804  6182  6182 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 17:17:41.804  6182  6182 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 17:17:41.804  6182  6182 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1cd20fc3 time:113866
,09-09 17:17:41.804  1016  1389 D PersonaManager: isKioskContainerExistOnDevice
,09-09 17:17:41.824   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:42.524  1016  1042 I ActivityManager: Waited long enough for: ServiceRecord{cef0865 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,09-09 17:17:42.824   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:42.944  1016  3138 I ActivityManager: Killing 5340:com.dropbox.android/u0a92 (adj 15): empty #31
,09-09 17:17:43.664  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 17:17:43.664  6182  6235 I jxcore-log: 
,09-09 17:17:43.664  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 17:17:43.664  6182  6235 I jxcore-log: 
,09-09 17:17:43.664  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:43.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:43.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:43.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:43.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:43.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:43.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:43.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:43.674  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:43.674  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 17:17:43.674  6182  6235 I jxcore-log: 
,09-09 17:17:43.674  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 17:17:43.674  6182  6235 I jxcore-log: 
,09-09 17:17:43.764   287   287 E SMD     : DCD OFF,
,09-09 17:17:43.824   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 17:17:44.014  1016  3272 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 17:17:44.014  1016  3272 D BatteryService: level:75, scale:100, status:2, health:2, present:true, voltage: 4011, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 17:17:44.014  1016  3272 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 17:17:44.014  1016  3272 D BatteryService: stay LED for charging
09-09 17:17:44.014  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 17:17:44.024  1016  1016 I MotionRecognitionService: Plugged
,09-09 17:17:44.024  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 17:17:44.024  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 17:17:44.024  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 17:17:44.024  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 17:17:44.024  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 75
09-09 17:17:44.034  2655  2655 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 17:17:44.034  2655  2736 D HeadsetStateMachine: Disconnected process message: 10
09-09 17:17:44.044  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:17:44.044  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:17:44.044  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-09 17:17:44.324  6182  6235 D executeNativeTests: Running unit tests
,09-09 17:17:44.404  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:17:44.404  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca added. We now have 2 listener(s)
,09-09 17:17:44.404  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:17:44.404  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:17:44.404  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:17:44.404  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:44.404  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b added. We now have 2 listener(s)
09-09 17:17:44.404  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:44.404  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:17:44.404  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:44.414  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:44.414  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:44.414  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:44.414  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:44.414  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:44.414  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:44.414  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:44.414  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:44.414  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:44.414  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:44.414  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:44.424  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:44.424  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 17:17:44.424  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:44.424  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 17:17:44.434  6182  6235 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,09-09 17:17:44.434  6182  6235 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 17:17:44.434  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 17:17:44.434  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 17:17:44.434  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
,09-09 17:17:44.434  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,09-09 17:17:44.444  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:44.444  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:44.444  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:44.444  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:44.444  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:44.444  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 17:17:44.444  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca removed from the list
,09-09 17:17:44.444  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:44.444  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b removed from the list
09-09 17:17:44.444  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:44.444  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.454  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.454  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:44.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:17:44.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:44.454  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
,09-09 17:17:44.454  6182  6235 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-09 17:17:44.464  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:44.464  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:44.464  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:44.464  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:44.464  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:44.464  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.464  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
,09-09 17:17:44.464  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.464  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
,09-09 17:17:44.464  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:44.464  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:44.464  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.464  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:44.464  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.464  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:44.464  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.464  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:44.464  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAll,OutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:17:44.474  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.474  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.474  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.474  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.474  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.474  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.474  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.474  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.474  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.474  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.474  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.474  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.474  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.474  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.474  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.474  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.474  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.474  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.474  6182  6235 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 17:17:44.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:44.484  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:44.484  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:44.484  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:44.484  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:44.484  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:44.484  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:44.484  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:44.484  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 17:17:44.484  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:44.484  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:44.484  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:44.484  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:44.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:44.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:44.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:17:44.494  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:44.494  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:17:44.494  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:44.504  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:17:44.504  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:17:44.514  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 17:17:44.514  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 17:17:44.514  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:17:44.514  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:17:44.524  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:17:44.544  2655  2665 D BtGatt.GattService: registerClient() - UUID=aac045e6-eaa3-4ff3-8c64-c277ad18853f
,09-09 17:17:44.594  2655  2731 D BtGatt.GattService: onClientRegistered() - UUID=aac045e6-eaa3-4ff3-8c64-c277ad18853f, clientIf=6
,09-09 17:17:44.594  6182  6192 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:17:44.594  2655  2737 D BtGatt.GattService: start scan with filters
,09-09 17:17:44.594  2655  2735 D BtGatt.ScanManager: handling starting scan
,09-09 17:17:44.594  2655  2735 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:17:44.604  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:17:44.604  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 17:17:44.604  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 17:17:44.604  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:17:44.604  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:44.614  2655  2731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 17:17:44.614  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.614  2655  2735 D BtGatt.ScanManager: allow scan with filters
,09-09 17:17:44.614  2655  2735 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 17:17:44.614  2655  2735 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-09 17:17:44.614  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:44.614  1016  1042 W ActivityManager: mDVFSHelper.release()
,09-09 17:17:44.624  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:17:44.624  2655  2731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:17:44.624  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:44.624  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 17:17:44.624  2655  2735 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:17:44.624  2655  2735 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:17:44.624  6182  6235 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:17:44.634  2655  2731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 17:17:44.634  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.634  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.634  6182  6235 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:44.634  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:44.634  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:17:44.634  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.634  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:17:44.634  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:44.634  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:44.634  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:44.634  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 17:17:44.634  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 17:17:44.634  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:17:44.644  2655  2731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 17:17:44.644  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:44.644  2655  2670 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:17:44.644  2655  2665 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:17:44.644  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:44.644  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:44.644  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:17:44.644  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:17:44.644  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:17:44.644  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:17:44.654  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:17:44.654  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:44.654  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:17:44.654  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:44.654  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:44.654  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:44.654  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:44.654  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.654  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.654  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:44.654  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.654  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.654  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.654  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.654  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.654  6182  6235 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 17:17:44.654  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:44.664  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:44.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:44.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:44.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:44.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:44.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:44.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:44.664  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:44.664  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:44.664  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:44.664  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:44.664  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:44.664  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:44.664  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:44.664  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:17:44.674  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:44.674  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:17:44.674  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:44.674  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:17:44.684  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
09-09 17:17:44.684  2655  2735 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 63,
,09-09 17:17:44.684  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:17:44.684  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:17:44.684  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:17:44.684  2655  2735 D BtGatt.ScanManager: filter size is 1
,09-09 17:17:44.684  2655  2735 D BtGatt.ScanManager: delete FilterIndex - 3
,09-09 17:17:44.684  2655  2670 D BtGatt.GattService: registerClient() - UUID=315125f1-c3f9-4c63-980c-f5a838c738a1
,09-09 17:17:44.694  2655  2731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 17:17:44.694  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:44.694  2655  2735 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:17:44.694  2655  2731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 17:17:44.694  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:44.694  2655  2735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:17:44.704  2655  2731 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 17:17:44.704  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.734  2655  2731 D BtGatt.GattService: onClientRegistered() - UUID=315125f1-c3f9-4c63-980c-f5a838c738a1, clientIf=6
,09-09 17:17:44.734  6182  6192 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:17:44.734  2655  2665 D BtGatt.GattService: start scan with filters
,09-09 17:17:44.734  2655  2735 D BtGatt.ScanManager: handling starting scan
,09-09 17:17:44.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 17:17:44.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 17:17:44.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:17:44.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:17:44.734  2655  2731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 17:17:44.734  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.734  2655  2735 D BtGatt.ScanManager: allow scan with filters
09-09 17:17:44.734  2655  2735 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 17:17:44.744  2655  2735 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-09 17:17:44.744  2655  2731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:17:44.744  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.744  2655  2735 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:17:44.744  2655  2735 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:17:44.744  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:44.744  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:44.744  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:17:44.754  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:17:44.754  2655  2731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 17:17:44.754  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.764  6182  6235 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:17:44.764  2655  2731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 17:17:44.764  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.774  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:44.774  6182  6235 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:44.774  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.774  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:17:44.774  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.774  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:17:44.774  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:44.774  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:44.774  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:44.774  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:17:44.774  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:17:44.774  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:17:44.774  2655  2737 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:17:44.774  2655  2670 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:17:44.774  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:44.774  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:44.774  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:17:44.774  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:17:44.774  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:17:44.784  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:17:44.784  2655  2735 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 64
,09-09 17:17:44.784  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:17:44.784  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:44.784  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:17:44.784  2655  2735 D BtGatt.ScanManager: filter size is 1
09-09 17:17:44.784  2655  2735 D BtGatt.ScanManager: delete FilterIndex - 4
,09-09 17:17:44.784  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:44.784  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:17:44.784  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:44.784  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:17:44.784  2655  2731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 17:17:44.784  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:44.784  2655  2735 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:17:44.784  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 17:17:44.784  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:44.784  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:44.784  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.784  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.784  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.784  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.784  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.784  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.784  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.794  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-09 17:17:44.794  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.794  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.794  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.794  6182  6235 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 17:17:44.794  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:44.794  2655  2731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 17:17:44.794  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.794  2655  2735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:17:44.804  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:44.804  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:44.804  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:44.804  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:44.804  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:44.804  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:44.804  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:44.804  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:44.804  2655  2731 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 17:17:44.804  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.804  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:44.804  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:17:44.804  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:17:44.804  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:17:44.804  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:17:44.804  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:44.804  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:17:44.804  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:44.814  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:44.814  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:17:44.814  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:17:44.814  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:17:44.824  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:17:44.824  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:17:44.824  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:17:44.824   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:44.824  2655  2737 D BtGatt.GattService: registerClient() - UUID=1956de60-42d5-4a10-bd02-cd5a7e3e2f98
,09-09 17:17:44.864  2655  2731 D BtGatt.GattService: onClientRegistered() - UUID=1956de60-42d5-4a10-bd02-cd5a7e3e2f98, clientIf=6
,09-09 17:17:44.864  6182  6197 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:17:44.864  2655  2670 D BtGatt.GattService: start scan with filters
,09-09 17:17:44.864  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:17:44.864  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:17:44.874  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:17:44.874  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:17:44.874  2655  2735 D BtGatt.ScanManager: handling starting scan
,09-09 17:17:44.874  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:44.874  2655  2731 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 17:17:44.874  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.874  2655  2735 D BtGatt.ScanManager: allow scan with filters
09-09 17:17:44.874  2655  2735 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 17:17:44.874  2655  2735 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-09 17:17:44.884  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:17:44.884  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:17:44.884  2655  2731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:17:44.884  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.884  2655  2735 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:17:44.884  2655  2735 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:17:44.884  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:17:44.894  2655  2731 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 17:17:44.894  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.894  6182  6235 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 17:17:44.894  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.894  6182  6235 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 17:17:44.894  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.894  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 17:17:44.894  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.894  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 17:17:44.894  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:44.894  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 17:17:44.894  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:44.894  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 17:17:44.904  2655  2731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-09 17:17:44.904  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:44.904  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:17:44.904  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:17:44.904  2655  2665 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:17:44.904  2655  2737 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:17:44.914  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:17:44.914  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:17:44.914  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:17:44.914  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:17:44.914  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:17:44.914  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:17:44.914  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:17:44.914  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:17:44.914  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:17:44.914  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:17:44.914  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:17:44.914  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:17:44.914  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:17:44.924  2655  2735 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 65
,09-09 17:17:44.924  2655  2735 D BtGatt.ScanManager: filter size is 1
09-09 17:17:44.924  2655  2735 D BtGatt.ScanManager: delete FilterIndex - 5
,09-09 17:17:44.924  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.924  6182  6235 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 17:17:44.924  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.924  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.924  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.924  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.924  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:17:44.924  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.924  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.924  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.924  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.924  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.924  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.924  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.924  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:17:44.924  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.924  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:44.924  2655  2731 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 17:17:44.924  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:44.924  2655  2735 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:17:44.924  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
,09-09 17:17:44.934  6182  6235 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 17:17:44.934  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:17:44.934  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.934  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:44.934  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:44.934  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.934  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.934  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
,09-09 17:17:44.934  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:44.934  2655  2731 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 17:17:44.934  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:17:44.934  2655  2735 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:17:44.934  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
,09-09 17:17:44.934  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.934  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.934  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.934  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.934  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.944  2655  2731 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 17:17:44.944  2655  2731 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.944  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:17:44.944  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.944  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.944  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.944  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.944  6182  6235 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 17:17:44.944  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.944  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.944  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.944  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.944  6182  6235 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-09 17:17:44.944  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.944  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.944  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.944  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.944  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.944  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.944  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:17:44.944  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 17:17:44.954  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
09-09 17:17:44.954  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 17:17:44.954  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 17:17:44.954  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 17:17:44.954  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.954  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:44.954  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.954  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.954  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.954  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:44.954  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:44.954  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.954  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.954  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.954  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:17:44.954  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.954  6182  6235 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 17:17:44.954  6182  6235 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 17:17:44.954  6182  6235 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:44.954  6182  6235 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 17:17:44.954  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 17:17:44.954  6182  6235 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 17:17:44.954  6182  6235 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-09 17:17:44.954  6182  6235 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 17:17:44.954  6182  6235 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:44.954  6182  6235 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:44.954  6182  6235 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 17:17:44.954  6182  6235 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 17:17:44.954  6182  6235 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 17:17:44.954  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 17:17:44.964  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 17:17:44.964  6182  6235 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 17:17:44.964  6182  6235 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 17:17:44.964  6182  6235 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 17:17:44.964  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.964  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.964  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.964  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.964  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.964  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-09 17:17:44.964  6182  6254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1143)
09-09 17:17:44.964  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.964  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.964  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.964  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.964  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.964  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.964  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.964  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.964  6182  6235 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-09 17:17:44.964  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.964  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.964  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.964  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.964  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.964  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.964  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.964  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.964  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.964  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.964  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.964  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.964  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
,09-09 17:17:44.974  6182  6235 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 17:17:44.974  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.974  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.974  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6255 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1143
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 17:17:44.974  6182  6235 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:44.974  6182  6235 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:17:44.974  6182  6235 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:44.974  6182  6235 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 17:17:44.974  6182  6235 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 17:17:44.974  6182  6235 W io.jxcore.node.ConnectionHelper: disconnectOutgoi,ngConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 17:17:44.974  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.974  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.974  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
,09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.974  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.974  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.974  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.974  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.974  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.974  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.974  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.974  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.984  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.984  6182  6254 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 17:17:44.984  6182  6254 D BluetoothSocket: connect(): myUserId = 0
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 17:17:44.984  6182  6254 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:17:44.984  6182  6182 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 17:17:44.984  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 17:17:44.984  6182  6182 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 17:17:44.984  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.984  2655  2665 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:17:44.984  6182  6256 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 17:17:44.984  6182  6256 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 17:17:44.984  6182  6254 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:44.984  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.984  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:44.984  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.984  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:17:44.984  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:17:44.984  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.984  6182  6182 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.984  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:17:44.984  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.984  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.984  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.984  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.984  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.984  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.984  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.984  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.994  6182  6235 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 17:17:44.994  6182  6235 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 17:17:44.994  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 17:17:44.994  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.994  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.994  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.994  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
,09-09 17:17:44.994  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.994  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.994  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.994  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.994  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:17:44.994  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:17:44.994  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30b3deca not in the list
09-09 17:17:44.994  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:44.994  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
09-09 17:17:44.994  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:44.994  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:17:44.994  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:17:45.004  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:17:45.004  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:17:45.004  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:17:45.004  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b3983b not in the list
,09-09 17:17:45.004  6182  6235 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:45.004  6182  6235 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 17:17:45.004  6182  6235 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 17:17:45.004  6182  6235 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:17:45.004  6182  6235 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 17:17:45.004  6182  6235 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 17:17:45.004  6182  6235 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 17:17:45.004  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.004  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d10daa5 added. We now have 2 listener(s)
09-09 17:17:45.004  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.004  6182  6235 D BluetoothAdapter: enable()
,09-09 17:17:45.004  6182  6235 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 17:17:45.014  1016  1724 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 17:17:45.014  1016  1724 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:17:45.014  1016  1724 D SecContentProvider2: mCursor = null
,09-09 17:17:45.014  1016  1724 D WifiService: setWifiEnabled: true pid=6182, uid=10155
,09-09 17:17:45.014  1016  1724 W ActivityManager: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:17:45.014  1016  1724 W WifiService: Failed getting userId using ActivityManagerNative
09-09 17:17:45.014  1016  1724 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:17:45.014  1016  1724 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 17:17:45.014  1016  1724 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 17:17:45.014  1016  1724 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 17:17:45.014  1016  1724 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 17:17:45.014  1016  1724 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 17:17:45.014  1016  1724 D SettingsProvider: name = wifi_on
,09-09 17:17:45.014  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:17:45.014  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3698e7a added. We now have 3 listener(s)
09-09 17:17:45.014  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.014  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.014  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b7062b added. We now have 4 listener(s)
09-09 17:17:45.014  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.024  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:17:45.024  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1710ea88 added. We now have 5 listener(s)
09-09 17:17:45.024  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:17:45.024  1016  1389 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 17:17:45.024  1016  1389 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:17:45.024  1016  1389 D SecContentProvider2: mCursor = null
,09-09 17:17:45.024  1016  1389 D WifiService: setWifiEnabled: false pid=6182, uid=10155,
09-09 17:17:45.024  1016  1389 D SettingsProvider: name = wifi_on
,09-09 17:17:45.024  1016  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 17:17:45.034  6182  6235 D BluetoothAdapter: disable()
,09-09 17:17:45.034  2106  2106 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 17:17:45.034  2106  2106 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 17:17:45.034  2106  2106 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 17:17:45.034  2106  2106 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 17:17:45.034  1016  3139 D SettingsProvider: name = bluetooth_on
,09-09 17:17:45.034  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:17:45.044  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:17:45.044  2655  2728 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-09 17:17:45.044  2655  2728 D BluetoothAdapterProperties: Setting state to 13
09-09 17:17:45.044  2655  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 17:17:45.044  2655  2728 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:45.044  2655  2728 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 17:17:45.044  1016  1724 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:45.044  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.044  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.044  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.044  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:45.044  2655  2728 D BluetoothAdapterService: Autoconnection is available 
09-09 17:17:45.044  2655  2728 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 17:17:45.044  2655  2728 D BluetoothAdapterService: terminating service from this receiver
09-09 17:17:45.044  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.044  2655  2655 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-09 17:17:45.044  2655  2655 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3261f1b8, channel: 19, state: LISTENING
09-09 17:17:45.044  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.044  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.044  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:45.044  2655  2655 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3261f1b8, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1828eea0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37aa2b91mSocket: android.net.LocalSocket@fe0eaf6 impl:android.net.LocalSocketImpl@3a9f2ef7 fd:FileDescriptor[74]
09-09 17:17:45.044  2655  2655 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fe0eaf6 impl:android.net.LocalSocketImpl@3a9f2ef7 fd:FileDescriptor[74]
09-09 17:17:45.044  2655  2728 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 17:17:45.044  2655  2728 D BluetoothAdapterProperties: mDiscovering is false
,09-09 17:17:45.054  1016  1489 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 17:17:45.054  2655  2728 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-09 17:17:45.054  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.054  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:17:45.054  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.054  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:45.054  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.054  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:45.054  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.054  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.054  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:45.054  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:45.054  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,09-09 17:17:45.054  2106  2106 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-09 17:17:45.054  2106  2106 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
09-09 17:17:45.054  2106  2106 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,09-09 17:17:45.054  1016  1127 E WifiNative-wlan0: do suspend true
09-09 17:17:45.054  1306  1306 D BluetoothPbap: Proxy object disconnected
,09-09 17:17:45.054  1306  1306 D PbapServerProfile: Bluetooth service disconnected
,09-09 17:17:45.064  1016  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 17:17:45.064  2655  2731 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:17:45.064  2655  2731 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:17:45.064  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.064  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.064  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 17:17:45.064  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.064  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.064  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-09 17:17:45.074  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:17:45.074  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:45.074  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-09 17:17:45.074  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:45.074  1795  1795 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:45.074  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:45.074  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 17:17:45.074  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:45.084  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.084  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:45.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:45.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:45.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:45.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 17:17:45.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 17:17:45.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 17:17:45.084  1016  1389 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 17:17:45.084  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.084  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 17:17:45.084  1016  3272 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:17:45.084  2655  2728 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-09 17:17:45.084  2655  2728 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-09 17:17:45.084  2655  2728 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-09 17:17:45.084  2655  2728 E bt-btif : cmd socket is not created
09-09 17:17:45.084  2655  4954 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 17:17:45.094  2655  2728 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
09-09 17:17:45.094  2655  2814 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-09 17:17:45.094  1016  1724 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:45.094  2655  2814 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 17:17:45.094  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.094  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-09 17:17:45.094  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 17:17:45.094  6182  6254 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30f21846, channel: -1, state: INIT
09-09 17:17:45.094  6182  6254 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30f21846, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@269dda07, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@320e2734mSocket: android.net.LocalSocket@2630b95d impl:android.net.LocalSocketImpl@162772d2 fd:FileDescriptor[107]
09-09 17:17:45.094  6182  6254 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2630b95d impl:android.net.LocalSocketImpl@162772d2 fd:FileDescriptor[107]
09-09 17:17:45.094  6182  6254 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1143)
,09-09 17:17:45.094  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.094  1016  1724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:45.094  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:45.094  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.094  2655  2814 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:45.094  2655  2814 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:45.094  2655  2814 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 17:17:45.104  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.104  2655  2655 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@7b4efcd, channel: 5, state: LISTENING
09-09 17:17:45.104  2655  2655 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@7b4efcd, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31e28a59, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ea8c082mSocket: android.net.LocalSocket@2f0dc393 impl:android.net.LocalSocketImpl@11253fd0 fd:FileDescriptor[76]
09-09 17:17:45.104  2655  2655 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f0dc393 impl:android.net.LocalSocketImpl@11253fd0 fd:FileDescriptor[76]
09-09 17:17:45.104  2655  2655 I BtOppRfcommListener: stopping Accept Thread
09-09 17:17:45.104  2655  2655 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@112dbbc9, channel: 12, state: LISTENING
09-09 17:17:45.104  2655  2655 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@112dbbc9, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f7ec1b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@62662cemSocket: android.net.LocalSocket@9c705ef impl:android.net.LocalSocketImpl@136688fc fd:FileDescriptor[79]
09-09 17:17:45.104  2655  2655 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9c705ef impl:android.net.LocalSocketImpl@136688fc fd:FileDescriptor[79]
,09-09 17:17:45.104  2655  4954 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 17:17:45.104  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 17:17:45.104  2655  2655 V BluetoothOppManager: cleanUp...
,09-09 17:17:45.104  1016  1389 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 17:17:45.104  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-09 17:17:45.104  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.114  1016  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.114  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:45.114  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:45.114  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:45.124  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:45.124  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 17:17:45.124  1016  1305 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 17:17:45.124  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:45.124  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.124  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.124  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:45.144  6262  6262 E Zygote  : MountEmulatedStorage()
09-09 17:17:45.144  6262  6262 E Zygote  : v2
09-09 17:17:45.144  6262  6262 I libpersona: KNOX_SDCARD checking this for 10003
09-09 17:17:45.144  6262  6262 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:45.144  1016  1305 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6262 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-09 17:17:45.144  6262  6262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:45.144  6262  6262 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:17:45.144  6262  6262 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:45.174  6262  6262 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:45.174  6262  6262 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:45.204  6262  6262 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 17:17:45.214  1016  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-09 17:17:45.214   277   973 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:17:45.214  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 17:17:45.214  1925  4497 V NativeCrypto: Read error: ssl=0xb751c038: I/O error during system call, Connection timed out
,09-09 17:17:45.224  1016  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:17:45.224  1016  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:45.224  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:45.224  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,09-09 17:17:45.224  1925  4497 V NativeCrypto: SSL shutdown failed: ssl=0xb751c038: I/O error during system call, Broken pipe
,09-09 17:17:45.234  1925  4497 E GCM     : Wifi connection closed with errorCode 20,
,09-09 17:17:45.234  1016  3058 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012,
,09-09 17:17:45.234  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:45.234  1016  1126 D WifiP2pService: InactiveState{ what=131204 }
09-09 17:17:45.234  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 17:17:45.234  1016  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 17:17:45.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.234  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-09 17:17:45.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.234  1016  2236 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.234  1016  2236 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.234  1016  2236 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-09 17:17:45.234  1016  2236 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.234  1016  2236 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-09 17:17:45.234  1016  2236 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 17:17:45.234  1016  2236 I qtaguid : Tagging socket 358 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1016, getuid(): 1000
09-09 17:17:45.234  1016  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:17:45.234  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 17:17:45.234  1016  2236 I qtaguid : Untagging socket 358
,09-09 17:17:45.244  1016  2236 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 17:17:45.244  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:45.244  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:45.244  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.244  6262  6262 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-09 17:17:45.244  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 17:17:45.244  1016  1016 D RttService: SCAN_AVAILABLE : 1
,09-09 17:17:45.244  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.244  1016  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.244  6262  6262 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 17:17:45.244  6262  6262 D UserAnalysis: Create SecureDbHelper
,09-09 17:17:45.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.254  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 17:17:45.254  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:45.254  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:45.254  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:17:45.254  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 17:17:45.254  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 17:17:45.254  1016  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 17:17:45.254  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:45.254  1016  1047 D WifiDisplayController: disconnect
09-09 17:17:45.254  1016  1047 D WifiDisplayController: updateConnection
09-09 17:17:45.254  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-09 17:17:45.264  1016  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 17:17:45.264  1016  1126 D WifiP2pService: P2pDisablingState
09-09 17:17:45.264  1016  1126 D WifiP2pService: P2pDisablingState{ what=147458 },
09-09 17:17:45.264  1016  1127 E WifiNative-wlan0: do suspend true
09-09 17:17:45.264  1016  1126 D WifiP2pService: p2p socket connection lost
09-09 17:17:45.264  6262  6262 D IntelligenceServiceApplication: onCreate()
09-09 17:17:45.264  1016  1126 D WifiP2pService: P2pDisabledState
,09-09 17:17:45.264  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
09-09 17:17:45.264  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:45.264  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:17:45.264  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 17:17:45.274  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 17:17:45.274  1016  3139 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:45.274  1016  1029 I ActivityManager: Killing 5315:com.google.android.talk/u0a104 (adj 15): empty #31
,09-09 17:17:45.274  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 17:17:45.274  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 17:17:45.274  6262  6262 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-09 17:17:45.274  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.274  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.274  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.274  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:45.284  6284  6284 E Zygote  : MountEmulatedStorage()
,09-09 17:17:45.284  6284  6284 E Zygote  : v2
09-09 17:17:45.284  6284  6284 I libpersona: KNOX_SDCARD checking this for 10107
09-09 17:17:45.284  6284  6284 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:45.294  6284  6284 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:45.294  2655  2814 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:45.294  2655  2908 I bt_userial_mct: exiting userial_read_thread
09-09 17:17:45.294  2655  2908 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 17:17:45.294  2655  2814 W bt-btif : ag scb idx 1 not allocated
09-09 17:17:45.294  2655  2814 W bt-btif : ag scb idx 2 not allocated
09-09 17:17:45.294  2655  2814 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 17:17:45.294  2655  2731 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 17:17:45.294  2655  2816 I bt_vendor: hw_epilog_process
09-09 17:17:45.294  2655  2731 D bt_userial_mct: userial_close
09-09 17:17:45.294  2655  2731 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 17:17:45.294  6284  6284 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:17:45.294  6284  6284 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:45.304  1016  1029 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6284 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-09 17:17:45.304  1016  3068 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 17:17:45.304  6262  6262 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-09 17:17:45.314  6284  6284 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:45.314  6284  6284 D ActivityThread: Added TimaKeyStore provider
09-09 17:17:45.314  6262  6262 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-09 17:17:45.384  1016  1126 D WifiP2pService: P2pDisabledState{ what=143375 },
09-09 17:17:45.384  1016  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-09 17:17:45.384  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:45.384  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:45.384  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.384  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.384  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.384  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.394   277   969 D EnterpriseController: uids 1000,
09-09 17:17:45.394   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 17:17:45.394   277   969 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-09 17:17:45.394  1173  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 17:17:45.394  1016  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 17:17:45.394  1016  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 17:17:45.394  1016  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-09 17:17:45.394  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 17:17:45.394  1016  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:45.394  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 17:17:45.394  1016  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 17:17:45.394  1016  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-09 17:17:45.394  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 17:17:45.394   277   973 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:17:45.394  1016  2236 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 17:17:45.394  1016  2236 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated,
09-09 17:17:45.394  1016  2236 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:45.394  1016  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 17:17:45.404  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 17:17:45.404  2106  2106 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-09 17:17:45.404  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:45.404  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:45.404  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.404  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.404  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.404  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.414  1016  1129 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 17:17:45.414  1016  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-09 17:17:45.414  1016  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 17:17:45.414  1016  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:45.414  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:45.414  1016  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:17:45.414  1016  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 17:17:45.414  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:45.414  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:45.414  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 17:17:45.414  1016  1130 D Tethering: MasterInitialState.processMessage what=3
,09-09 17:17:45.414  1016  1124 V NetworkStats: updateIfacesLocked()
09-09 17:17:45.414  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:45.414  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-09 17:17:45.414  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:45.414  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:17:45.414  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-09 17:17:45.414  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-09 17:17:45.424  1016  1124 V NetworkStats: performPollLocked() took 4ms
09-09 17:17:45.424  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:45.424  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 17:17:45.424  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 17:17:45.424  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 17:17:45.424  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 17:17:45.424  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:45.424  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:45.424  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:45.424  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 17:17:45.424  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 17:17:45.424  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-09 17:17:45.424  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:45.424  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:45.424  1016  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 17:17:45.424  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 17:17:45.424  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.434  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.434  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.434  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.434  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:45.434  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:45.434  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:45.434  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.434  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.434  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.434  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.434  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:45.434  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:45.434  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 17:17:45.434  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 17:17:45.434  1173  1173 D HotspotTile: onReceive : 0, 0
,09-09 17:17:45.434  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.434  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:45.434  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.434  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:45.434  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:45.434  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:45.434  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:45.434  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:45.434  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:45.444  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.444  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:45.444  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.444  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:45.444  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:45.444  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:45.444  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:45.444  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:45.444  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:45.444  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:45.444  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:45.444  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:45.444  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:45.454  2106  2106 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:45.454  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:45.454  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:45.494  6182  6182 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:17:45.494  2106  2106 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 17:17:45.494  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:17:45.494  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:45.494  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:45.514  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:45.514  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:45.514  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 17:17:45.514  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:45.514  2106  2106 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-09 17:17:45.514  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:45.514  2106  2106 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 17:17:45.514  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:45.514  2106  2106 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 17:17:45.514  2106  2106 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 17:17:45.514  2106  2106 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 17:17:45.524  1016  1130 D Tethering: InitialState.processMessage what=4
,09-09 17:17:45.524  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 17:17:45.524  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:45.524  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:45.524  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 17:17:45.524  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:45.524  1016  1127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 ,
,09-09 17:17:45.524  1016  1130 E Tethering: No numeric data
,09-09 17:17:45.524  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:45.524  1016  1130 D Tethering: clearTetheredNotification()
09-09 17:17:45.524  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:45.524  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:45.534  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 17:17:45.534  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 17:17:45.534  2655  2731 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 17:17:45.534  2655  2731 I bt_vendor: bluetooth satus is on
09-09 17:17:45.534  2655  2731 I bt_vendor: bt-vendor : resetting BT status
09-09 17:17:45.534  2655  2731 I bt_vendor: Starting hciattach daemon
09-09 17:17:45.534  2655  2731 I bt_vendor: try to set false
,09-09 17:17:45.534  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:45.534  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:45.534  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:45.534  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:45.534  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:45.534  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:45.534  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:45.534  2655  2731 I bt_vendor: Starting hciattach daemon
,09-09 17:17:45.534  2655  2731 I bt_vendor: try to set false
09-09 17:17:45.534  2655  2731 I bt_vendor: cleanup
,09-09 17:17:45.534  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:45.534  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:17:45.534  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:45.534  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 17:17:45.534  2655  2814 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-09 17:17:45.534  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:45.534  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:45.544  2655  2731 I GKI_LINUX: GKI_exit_task 0 done
,09-09 17:17:45.544  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 17:17:45.544  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:17:45.544  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 17:17:45.544  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 17:17:45.544  2655  2731 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-09 17:17:45.544  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 17:17:45.544  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:45.544  2655  2728 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 17:17:45.544  2655  2728 D BtConfig.SecureMode: isSecureModeOn:false
09-09 17:17:45.544  2655  2728 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 17:17:45.544  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 17:17:45.544  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 17:17:45.544  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:45.544  2655  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-09 17:17:45.544  1016  1124 V NetworkStats: performPollLocked() took 13ms
09-09 17:17:45.544  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:45.544  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:45.544  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-09 17:17:45.544  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
09-09 17:17:45.544  1016  1489 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:45.544  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.544  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:45.554  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 17:17:45.554  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 17:17:45.554  2655  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 17:17:45.554  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 17:17:45.554  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:45.554  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:45.554  1016  3272 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:45.554  1016  3272 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 17:17:45.554  2655  2655 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:17:45.554  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:45.554  1016  3272 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.554  1016  3272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.554  1016  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:45.554  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:45.554  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 17:17:45.554  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 17:17:45.554  2655  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 17:17:45.554  2655  2655 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 17:17:45.554  2655  2655 D BtGatt.GattService: stop()
09-09 17:17:45.554  2655  2655 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 17:17:45.554  1016  1724 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:45.564  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.564  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 17:17:45.564  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:45.564  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.564  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:45.564  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 17:17:45.564  2655  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:17:45.564  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 17:17:45.564  2655  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 17:17:45.564  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 17:17:45.564  1016  3271 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:45.564  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 17:17:45.564  1016  3271 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.564  2655  2655 D HeadsetService: Received stop request...Stopping profile...
09-09 17:17:45.564  1016  3271 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:45.564  1016  3271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:45.564  1016  3271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:45.574  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 17:17:45.574  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 17:17:45.574  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 17:17:45.574  2655  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 17:17:45.574  2655  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:17:45.574  1016  1389 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:45.574  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.574  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 17:17:45.574   270   270 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb82447c8
09-09 17:17:45.574   270   270 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,09-09 17:17:45.574   270   270 I rmt_storage: wakelock acquired: 1, error no: 42
09-09 17:17:45.574   270   372 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1205582536)
09-09 17:17:45.574  1306  1306 D HeadsetProfile: Bluetooth service disconnected
09-09 17:17:45.584  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 17:17:45.584  2655  2655 D A2dpService: Received stop request...Stopping profile...
,09-09 17:17:45.584  2655  2743 D A2dpStateMachine: Exit Disconnected: -1
09-09 17:17:45.584  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.594  1016  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.594  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:45.594  1016  1489 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-09 17:17:45.594  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 17:17:45.594  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 17:17:45.594  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 17:17:45.594  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 17:17:45.594  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:45.594  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:45.594  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-09 17:17:45.594  2655  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 17:17:45.604  2655  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:17:45.604  1016  3272 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:45.604  1016  3272 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.604  1016  3272 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.604  1016  3272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.604  1016  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:45.604  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 17:17:45.604  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:45.604  2655  2728 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 17:17:45.604  2864  2864 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:45.604  1016  1252 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:45.604  1016  1252 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.604  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.604  1016  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.604  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:45.604  1925  1925 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 17:17:45.614  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 17:17:45.614  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 17:17:45.614  1016  1016 D BluetoothA2dp: Proxy object disconnected
,09-09 17:17:45.614  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-09 17:17:45.614  1925  1925 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 17:17:45.614  2655  2728 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-09 17:17:45.614  1306  1306 D BluetoothA2dp: Proxy object disconnected
,09-09 17:17:45.614  1306  1306 D A2dpProfile: Bluetooth service disconnected
,09-09 17:17:45.614  1016  3271 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:45.614  1016  3271 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.614  1016  3271 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.614  1016  3271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.614  1016  3271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:45.624  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 17:17:45.624  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:45.624  2655  2728 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 17:17:45.624  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:45.624  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:45.624  2655  2728 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:45.624  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 17:17:45.624  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-09 17:17:45.624  2655  2728 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 17:17:45.624  2655  2728 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 17:17:45.624  2655  2728 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 17:17:45.624  2655  2728 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-09 17:17:45.624  2655  2728 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 17:17:45.624  2655  2655 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-09 17:17:45.624  2655  2655 D HidService: Received stop request...Stopping profile...
,09-09 17:17:45.624  2655  2655 D HidService: Stopping Bluetooth HidService
09-09 17:17:45.624  2655  2655 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 17:17:45.624  2655  2655 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 17:17:45.624  2655  2655 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 17:17:45.624  2655  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:17:45.634  2655  2655 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-09 17:17:45.634  1306  1306 D BluetoothInputDevice: Proxy object disconnected
09-09 17:17:45.634  1306  1306 D HidProfile: Bluetooth service disconnected
09-09 17:17:45.634  2655  2655 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:45.634  2655  2655 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 17:17:45.634  6284  6284 D StrictMode: StrictMode policy violation; ~duration=272 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:45.634  6284  6284 D StrictMode: StrictMode policy violation; ~duration=265 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:45.634  6284  6284 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:45.634  6284  6284 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:45.634  6284  6284 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:45.634  6284  6284 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:45.634  6284  6284 D StrictMode: StrictMode policy violation; ~duration=198 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.k.c(PG:583)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:45.634  6284  6284 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:17:45.634  6284  6284 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:17:45.644  1016  1489 I ActivityManager: Killing 5737:com.google.android.gms:car/u0a12 (adj 15): empty #31
09-09 17:17:45.644  1925  1925 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-09 17:17:45.654   270   372 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-09 17:17:45.654   270   372 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-09 17:17:45.654   270   372 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1205582536) wakelock released: 1, error no: 0
09-09 17:17:45.654   270   372 I rmt_storage: 
09-09 17:17:45.654   270   270 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb82447c8
09-09 17:17:45.654  1925  1925 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 17:17:45.654  2655  2655 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 17:17:45.654  2655  2655 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 17:17:45.654  2655  2655 D HealthService: Received stop request...Stopping profile...
09-09 17:17:45.654  2655  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:17:45.654  2655  2655 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 17:17:45.654  2655  2655 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:45.654  2655  2655 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 17:17:45.664  2655  2655 D PanService: Received stop request...Stopping profile...
09-09 17:17:45.664  2655  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:17:45.664  1306  1306 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 17:17:45.664  1306  1306 D PanProfile: Bluetooth service disconnected
09-09 17:17:45.664  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:45.664  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:17:45.664  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 17:17:45.664  2655  2655 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:45.664  2655  2655 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-09 17:17:45.664  2655  2744 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 17:17:45.664  2655  2655 I GKI_LINUX: GKI_exit_task 2 done
09-09 17:17:45.664  2655  2655 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 17:17:45.664  2655  2655 D BluetoothMapService: Received stop request...Stopping profile...
09-09 17:17:45.664  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.664  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:45.664  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:17:45.664  3618  3618 I Hs20UtilService: Starting #8
09-09 17:17:45.664  3618  3653 I Hs20UtilService: Message received 5007
09-09 17:17:45.674  2655  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:17:45.674  2655  2655 D SapService: Received stop request...Stopping profile...
,09-09 17:17:45.674  1306  1306 D BluetoothMap: Proxy object disconnected
09-09 17:17:45.674  1306  1306 D MapProfile: Bluetooth service disconnected
09-09 17:17:45.674  2655  2655 D SapService: Stopping Bluetooth SapService
09-09 17:17:45.674  2655  2655 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:17:45.674  2655  2655 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 17:17:45.674  2655  2655 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:45.674  2655  2655 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:45.674  2655  2655 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 17:17:45.674  2655  2655 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:45.674  2655  2655 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:45.674  2655  2655 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:17:45.674  2655  2655 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:17:45.674  2655  2655 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 17:17:45.674  2655  2655 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:45.674  2655  2655 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:45.674  2655  2655 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:17:45.674  2655  2655 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:17:45.684  2655  2655 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 17:17:45.684  2655  2655 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:17:45.684  2655  2655 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-09 17:17:45.684  2655  2655 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 17:17:45.684  2655  2655 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 17:17:45.684  2655  2655 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-09 17:17:45.684  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:17:45.684  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:45.684  2655  2728 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-09 17:17:45.684  2655  2728 D BluetoothAdapterProperties: Setting state to 10
09-09 17:17:45.684  2655  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 17:17:45.684  2655  2728 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:45.684  2655  2728 D BluetoothAdapterService: updateAdapterState state is 10
09-09 17:17:45.684  2655  2728 D BluetoothAdapterService: Autoconnection is available 
09-09 17:17:45.684  2655  2728 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 17:17:45.684  2655  2728 I BluetoothAdapterState: Entering OffState
09-09 17:17:45.684  1925  2118 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.684  1925  2118 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.684  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 17:17:45.684  2864  2873 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.684  2864  2873 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.684  1455  2439 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.684  1455  2439 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.684  2655  2665 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:17:45.684  1306  1337 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.684  1306  1337 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.684  2864  2880 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:17:45.694  1306  1319 D BluetoothPbap: onBluetoothStateChange: up=false
09-09 17:17:45.694  1440  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.694  1440  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.694  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:45.694  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:45.694  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 17:17:45.694  1306  1306 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 17:17:45.694  1306  1306 D SapProfile: Bluetooth service disconnected
09-09 17:17:45.694  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 17:17:45.694  1306  1319 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 17:17:45.694  1306  1319 D Bluetoothsap: Unbinding service...
09-09 17:17:45.704  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 17:17:45.704  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:45.704  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 17:17:45.704  2106  2106 I wpa_supplicant: Blacklist: Clear (all) 
09-09 17:17:45.704  1016  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:17:45.704  1173  1716 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.704  1173  1716 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.704  1431  1446 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.704  1431  1446 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.704  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:45.704  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:45.704  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 17:17:45.704  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 17:17:45.704  2655  2737 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.704  2655  2737 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.704  1306  1337 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 17:17:45.704  1016  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-09 17:17:45.704  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.704  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.704  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.704  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.714  6284  6305 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 17:17:45.714  6327  6327 E Zygote  : MountEmulatedStorage()
09-09 17:17:45.714  6327  6327 E Zygote  : v2
09-09 17:17:45.714  6327  6327 I libpersona: KNOX_SDCARD checking this for 10068
09-09 17:17:45.714  6327  6327 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:45.714  6327  6327 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:45.724  6327  6327 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:17:45.724  1016  1489 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6327 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:17:45.724  1306  1319 D BluetoothMap: onBluetoothStateChange: up=false
09-09 17:17:45.724  6182  6192 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:45.724  6182  6192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:45.724  6182  6192 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 17:17:45.724  6182  6192 D BluetoothLeAdvertiser: Exit stop advertising
09-09 17:17:45.724  6182  6192 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 17:17:45.724  6182  6192 D BluetoothLeScanner: Exiting stopAllScan
09-09 17:17:45.724  1306  6326 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:17:45.724  1016  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:45.724  1016  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
09-09 17:17:45.724  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-09 17:17:45.724  1016  1724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 17:17:45.724  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.724  1016  1724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:45.724  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-09 17:17:45.724  6327  6327 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 17:17:45.734  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 17:17:45.744  1925  1940 I art     : Explicit concurrent mark sweep GC freed 47171(2MB) AllocSpace objects, 10(400KB) LOS objects, 39% free, 13MB/22MB, paused 1.407ms total 80.187ms
,09-09 17:17:45.744  2106  2106 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 17:17:45.744  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:45.744  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:45.744  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:45.754  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:45.754  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
09-09 17:17:45.754  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 17:17:45.754  1173  1173 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:45.754  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 17:17:45.754  1173  1705 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
,09-09 17:17:45.754  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:45.754  1173  1173 D BluetoothTile:  getBluetoothState : 10
09-09 17:17:45.754  1173  1705 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
,09-09 17:17:45.754  1173  1173 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:45.754  1173  1173 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:45.754  1016  1252 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:45.764  1925  2125 D BluetoothAdapter: 500543803: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:45.764  1016  1219 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 17:17:45.764  1925  2125 D BluetoothAdapter: 500543803: getState() :  mService = null. Returning STATE_OFF
,09-09 17:17:45.764  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 17:17:45.764  1016  3273 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 17:17:45.764  1795  1795 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-09 17:17:45.764  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:45.764  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.764  1016  3273 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:45.764  1016  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:45.764  1016  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 17:17:45.764  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.764  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:45.764  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 17:17:45.774  6327  6327 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:45.774  6327  6327 D ActivityThread: Added TimaKeyStore provider
09-09 17:17:45.774  2655  2731 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 17:17:45.774  2655  2655 I GKI_LINUX: GKI_exit_task 1 done
09-09 17:17:45.774  2655  2655 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-09 17:17:45.774  2655  2655 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 17:17:45.774  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:45.774  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:45.774  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:45.774  2655  2655 I art     : System.exit called, status: 0
09-09 17:17:45.774  2655  2655 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 17:17:45.794  6327  6327 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 17:17:45.814  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:45.814  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 17:17:45.824   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 17:17:45.834  6327  6327 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 17:17:45.844  1016  3138 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 17:17:45.844  1016  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:45.844  1016  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.844  1016  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.844  1016  3138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: android.os.DeadObjectException
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at android.bluetooth.IBluetooth$Stub$Proxy.isEnabled(IBluetooth.java:1218)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at android.bluetooth.BluetoothAdapter.isEnabled(BluetoothAdapter.java:702)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.m.b(PG:7267)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.x.run(PG:38)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at com.google.android.apps.gmm.shared.f.a.k.run(PG:29)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-09 17:17:45.844  6284  6305 E BluetoothAdapter: 	at java.lang.Thread.run(Thread.java:818)
,09-09 17:17:45.854  6348  6348 E Zygote  : MountEmulatedStorage()
,09-09 17:17:45.854  6348  6348 E Zygote  : v2
09-09 17:17:45.854  1016  3138 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6348 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:45.854  6348  6348 I libpersona: KNOX_SDCARD checking this for 10069
09-09 17:17:45.854  1016  3138 I ActivityManager: Killing 4992:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
09-09 17:17:45.854  6348  6348 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:45.864  6348  6348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:45.864  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 17:17:45.864  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-09 17:17:45.864  1016  1127 E WifiConfigStore: setLastSelectedConfiguration -1
09-09 17:17:45.864  6348  6348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:17:45.864  6348  6348 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:45.864  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:45.864  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:45.864  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.864  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.864  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:45.864  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:45.864  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:45.864  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 17:17:45.874  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 17:17:45.874  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:45.874  1173  1173 D HotspotTile: onReceive : 1, 0
,09-09 17:17:45.874  1925  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:45.874  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:45.874  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.874  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:17:45.874  1016  1219 I ActivityManager: Process com.android.bluetooth (pid 2655)(adj 0) has died(45,1105)
,09-09 17:17:45.894  6348  6348 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:45.894  6348  6348 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:45.904  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:45.914  1016  2734 D SSRM:n  : SIOP:: AP = 410
,09-09 17:17:45.914  1016  1016 I ApplicationPolicy: updateDataUsageMap
,09-09 17:17:45.924  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.934  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:45.934  6348  6348 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-09 17:17:45.934  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-09 17:17:45.934  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-09 17:17:45.944  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:45.944  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:45.944  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 17:17:45.944  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-09 17:17:45.944  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:45.944  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.944  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:45.944  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:45.964  1016  1029 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6363 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 17:17:45.964  6363  6363 E Zygote  : MountEmulatedStorage()
09-09 17:17:45.964  6363  6363 E Zygote  : v2
09-09 17:17:45.964  6363  6363 I libpersona: KNOX_SDCARD checking this for 10104
09-09 17:17:45.964  6363  6363 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:45.964  6363  6363 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 17:17:45.964  1016  1029 I ActivityManager: Killing 5446:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-09 17:17:45.964  6363  6363 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:45.964  6363  6363 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:45.984  1016  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:45.984  6363  6363 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:45.984  6363  6363 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.004  6363  6363 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 17:17:46.164  6363  6386 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-09 17:17:46.164  6363  6386 I Babel   : MmsConfig.loadMmsSettings
09-09 17:17:46.164  6363  6386 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-09 17:17:46.164  6363  6386 I Babel   : MmsConfig.loadFromDatabase
,09-09 17:17:46.184  6363  6386 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-09 17:17:46.184  6363  6386 I Babel   : MmsConfig.loadFromResources
,09-09 17:17:46.184  6363  6386 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 17:17:46.184  6363  6386 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-09 17:17:46.184  1016  1028 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-09 17:17:46.184  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.194  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.194  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:46.194  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 17:17:46.194  6363  6363 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:46.234  6363  6363 I Babel_StickerModule: App launched.
,09-09 17:17:46.244  1016  3272 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:17:46.244  1016  3272 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:46.244  1016  3272 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.244  1016  3272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.244  1016  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:46.244  3618  3618 I Hs20UtilService: Starting #9
,09-09 17:17:46.244  3618  3653 I Hs20UtilService: Message received 5007
,09-09 17:17:46.254  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 17:17:46.254  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:17:46.254  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:46.254  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:17:46.254  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:46.254  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:46.254  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:46.264  1016  3269 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:46.264  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:46.264  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.264  1016  3269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.264  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:46.264  3618  3618 I Hs20UtilService: Starting #10
,09-09 17:17:46.264  1016  1219 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
09-09 17:17:46.264  3618  3653 I Hs20UtilService: Message received 5011
,09-09 17:17:46.264  1016  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.264  1016  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.264  1016  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.264  1016  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.264   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 0
09-09 17:17:46.264   282   282 W QCamera2Factory: getCameraInfo: X
,09-09 17:17:46.274   282  1014 W QCamera2Factory: getCameraInfo: E, camera_id = 1
09-09 17:17:46.274   282  1014 W QCamera2Factory: getCameraInfo: X
,09-09 17:17:46.284  6388  6388 E Zygote  : MountEmulatedStorage(),
09-09 17:17:46.284  6388  6388 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:17:46.284  6388  6388 E Zygote  : v2
09-09 17:17:46.284  6388  6388 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:46.284  6388  6388 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 17:17:46.284  6388  6388 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 17:17:46.284  6388  6388 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 17:17:46.284  1016  1219 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 17:17:46.294  6363  6363 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 17:17:46.294  6363  6363 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 17:17:46.294  6363  6363 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 17:17:46.304  6388  6388 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.304  6363  6363 W AudioCapabilities: Unsupported mime audio/mpeg-L1
09-09 17:17:46.304  6388  6388 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.304  6363  6363 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-09 17:17:46.304  6363  6363 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 17:17:46.314  6363  6363 W AudioCapabilities: Unsupported mime audio/x-ima
,09-09 17:17:46.314  6363  6363 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 17:17:46.314  6363  6363 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 17:17:46.324  6363  6363 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 17:17:46.324  6363  6363 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 17:17:46.334  6363  6363 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-09 17:17:46.334  6363  6363 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 17:17:46.344  6363  6363 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 17:17:46.344  6363  6363 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-09 17:17:46.344  6363  6363 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-09 17:17:46.344  6363  6363 W VideoCapabilities: Unsupported mime video/mp43
09-09 17:17:46.344  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:46.354  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 17:17:46.354  6363  6363 W VideoCapabilities: Unsupported mime video/sorenson
09-09 17:17:46.354  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 17:17:46.354  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:46.354  6363  6363 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 17:17:46.354  1016  1028 I ActivityManager: Killing 5713:com.samsung.android.sm/1000 (adj 15): empty #31
,09-09 17:17:46.364  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.364  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.364  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.364  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.364  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.364  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.374  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.374  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.374  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.374  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.374  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.374  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.374  1016  1044 D Tethering: interfaceRemoved wlan0
09-09 17:17:46.374  1016  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 17:17:46.374  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.374  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.374  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.384  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.384  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.384  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.384  6363  6363 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 17:17:46.384  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.384  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.384  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.384  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.384  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.384  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.394  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.394  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.394  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.394  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.394  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.394  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.394  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.394  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.394  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.404  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.404  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.404  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.404  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.404  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.404  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.404  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.404  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.404  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.414  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.414  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.414  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 17:17:46.424  1016  1489 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-09 17:17:46.424  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 17:17:46.424  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.424  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.424  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:46.424  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 17:17:46.424  1016  1305 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 17:17:46.424  1016  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.424  1016  1305 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.424  1016  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.424  1016  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:46.434  1016  1724 I ActivityManager: Killing 5536:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-09 17:17:46.434  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:46.434  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:46.444  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:46.444  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 17:17:46.444  1016  3272 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-09 17:17:46.444  1016  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.444  1016  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.444  1016  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.444  1016  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.454  6407  6407 E Zygote  : MountEmulatedStorage()
,09-09 17:17:46.454  6407  6407 E Zygote  : v2
09-09 17:17:46.454  6407  6407 I libpersona: KNOX_SDCARD checking this for 1002
,09-09 17:17:46.454  6407  6407 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:46.464  6407  6407 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-09 17:17:46.464  1016  3272 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6407 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-09 17:17:46.464  6407  6407 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 17:17:46.464  6407  6407 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.484  6407  6407 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.484  6407  6407 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.504  6407  6407 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-09 17:17:46.504  6407  6407 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:17:46.514  1016  1044 D Tethering: interfaceRemoved p2p0
,09-09 17:17:46.514  1016  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 17:17:46.524  6407  6407 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-09 17:17:46.554  6407  6407 D BtSettings.ProfileConfig: Adding GattService
,09-09 17:17:46.554  6407  6407 D BtSettings.ProfileConfig: Adding HeadsetService
09-09 17:17:46.554  6407  6407 D BtSettings.ProfileConfig: Adding A2dpService
,09-09 17:17:46.554  6407  6407 D BtSettings.ProfileConfig: Adding HidService
09-09 17:17:46.554  6407  6407 D BtSettings.ProfileConfig: Adding HealthService
09-09 17:17:46.554  6407  6407 D BtSettings.ProfileConfig: Adding PanService
,09-09 17:17:46.564  6407  6407 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-09 17:17:46.564  6407  6407 D BtSettings.ProfileConfig: Adding SapService
09-09 17:17:46.564  6407  6407 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-09 17:17:46.564  6407  6407 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-09 17:17:46.564  6407  6407 D BtSettings.ProfileConfig: Adding SapClientService
09-09 17:17:46.564  6407  6407 D BtSettings.ProfileConfig: Adding HidDevService
,09-09 17:17:46.564  6407  6407 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-09 17:17:46.564  1016  1305 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-09 17:17:46.564  1016  1305 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.564  1016  1305 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.564  1016  1305 D SettingsProvider: selectionArgs: false
,09-09 17:17:46.564  1016  1305 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.564  1016  1305 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 17:17:46.564  1016  1305 D SettingsProvider: ret = -1
,09-09 17:17:46.564  1016  3272 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-09 17:17:46.564  1016  3272 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.564  1016  3272 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.564  1016  3272 D SettingsProvider: selectionArgs: false
09-09 17:17:46.564  1016  3272 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.564  1016  3272 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.564  1016  3272 D SettingsProvider: ret = -1
,09-09 17:17:46.564  1016  1389 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-09 17:17:46.564  1016  1389 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.564  1016  1389 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.564  1016  1389 D SettingsProvider: selectionArgs: false
09-09 17:17:46.564  1016  1389 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.564  1016  1389 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.564  1016  1389 D SettingsProvider: ret = -1
,09-09 17:17:46.564  1016  1252 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-09 17:17:46.564  1016  1252 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.564  1016  1252 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 17:17:46.564  1016  1252 D SettingsProvider: selectionArgs: false
09-09 17:17:46.564  1016  1252 D SettingsProvider: selectionArgs: 1002
,09-09 17:17:46.564  1016  1252 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.564  1016  1252 D SettingsProvider: ret = -1
,09-09 17:17:46.564  1016  3139 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-09 17:17:46.564  1016  3139 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.564  1016  3139 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.564  1016  3139 D SettingsProvider: selectionArgs: false
09-09 17:17:46.564  1016  3139 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.564  1016  3139 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.574  1016  3139 D SettingsProvider: ret = -1
,09-09 17:17:46.574  1016  3068 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-09 17:17:46.574  1016  3068 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.574  1016  3068 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.574  1016  3068 D SettingsProvider: selectionArgs: false
09-09 17:17:46.574  1016  3068 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.574  1016  3068 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.574  1016  3068 D SettingsProvider: ret = -1
,09-09 17:17:46.574  1016  3271 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-09 17:17:46.574  1016  3271 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.574  1016  3271 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.574  1016  3271 D SettingsProvider: selectionArgs: false
,09-09 17:17:46.574  1016  3271 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.574  1016  3271 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.574  1016  3271 D SettingsProvider: ret = -1
,09-09 17:17:46.574  1016  1724 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-09 17:17:46.574  1016  1724 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.574  1016  1724 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.574  1016  1724 D SettingsProvider: selectionArgs: false
,09-09 17:17:46.574  1016  1724 D SettingsProvider: selectionArgs: 1002
,09-09 17:17:46.574  1016  1724 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.574  1016  1724 D SettingsProvider: ret = -1
09-09 17:17:46.574  1016  3273 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:46.574  1016  3273 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.574  1016  3273 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 17:17:46.574  1016  3273 D SettingsProvider: selectionArgs: false
09-09 17:17:46.574  1016  3273 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.574  1016  3273 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.574  1016  3273 D SettingsProvider: ret = -1
,09-09 17:17:46.574  1016  3058 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-09 17:17:46.574  1016  3058 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.574  1016  3058 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.574  1016  3058 D SettingsProvider: selectionArgs: false
,09-09 17:17:46.574  1016  3058 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.574  1016  3058 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.574  1016  3058 D SettingsProvider: ret = -1
,09-09 17:17:46.574  1016  3138 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-09 17:17:46.574  1016  3138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.574  1016  3138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.574  1016  3138 D SettingsProvider: selectionArgs: false
,09-09 17:17:46.574  1016  3138 D SettingsProvider: selectionArgs: 1002
09-09 17:17:46.584  1016  3138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 17:17:46.584  1016  3138 D SettingsProvider: ret = -1
,09-09 17:17:46.584  1016  3269 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-09 17:17:46.584  1016  3269 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:46.584  1016  3269 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:46.584  1016  3269 D SettingsProvider: selectionArgs: false
09-09 17:17:46.584  1016  3269 D SettingsProvider: selectionArgs: 1002
,09-09 17:17:46.584  1016  3269 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:46.584  1016  3269 D SettingsProvider: ret = -1
,09-09 17:17:46.594  1016  1028 I ActivityManager: Killing 5062:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: android.os.DeadObjectException
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at android.bluetooth.IBluetooth$Stub$Proxy.isEnabled(IBluetooth.java:1218)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at android.bluetooth.BluetoothAdapter.isEnabled(BluetoothAdapter.java:702)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.m.b(PG:7267)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.x.run(PG:38)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at com.google.android.apps.gmm.shared.f.a.k.run(PG:29)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-09 17:17:46.594  6284  6304 E BluetoothAdapter: 	at java.lang.Thread.run(Thread.java:818)
,09-09 17:17:46.594  1925  1925 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:46.594  1016  3272 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:46.594  1016  3272 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.594  1016  3272 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.594  1016  3272 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:46.594  1016  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:46.604  1925  6423 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 17:17:46.604  1016  1305 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:46.614  1925  1925 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 17:17:46.614  1016  1305 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.614  1016  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:46.614  1016  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:46.624  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:46.624  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:46.624  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.624  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.624  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:46.624  3618  3618 I Hs20UtilService: Starting #11
,09-09 17:17:46.634  3618  3653 I Hs20UtilService: Message received 5011
,09-09 17:17:46.634  1016  1389 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:46.634  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.634  1016  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:46.634  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:46.634  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 17:17:46.634  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:46.634  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1
09-09 17:17:46.634  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:46.654  1925  6423 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-09 17:17:46.654  5833  5833 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 17:17:46.654  5833  5833 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 17:17:46.654  5833  5833 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 17:17:46.654  5833  5833 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:46.654  1016  1305 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-09 17:17:46.654  1016  1305 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 17:17:46.654  1016  1305 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-09 17:17:46.654  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.654  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.654  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.654  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.664  5833  6424 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 17:17:46.684  6427  6427 E Zygote  : MountEmulatedStorage()
09-09 17:17:46.684  6427  6427 I libpersona: KNOX_SDCARD checking this for 10111
09-09 17:17:46.684  6427  6427 E Zygote  : v2
09-09 17:17:46.684  6427  6427 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:46.684  6427  6427 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 17:17:46.684  6427  6427 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:46.684  6427  6427 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.694  1016  1305 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6427 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:46.694  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-09 17:17:46.694  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.694  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.694  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.694  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.704  6427  6427 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.704  6427  6427 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.714  6442  6442 E Zygote  : MountEmulatedStorage(),
09-09 17:17:46.714  6442  6442 E Zygote  : v2
09-09 17:17:46.714  6442  6442 I libpersona: KNOX_SDCARD checking this for 10009
09-09 17:17:46.714  6442  6442 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:46.714  6442  6442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:46.714  1016  1042 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6442 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:46.714  6442  6442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:46.714  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-09 17:17:46.714  1725  1725 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 17:17:46.714  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.714  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.714  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.714  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.724  6442  6442 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.734  6453  6453 E Zygote  : MountEmulatedStorage()
09-09 17:17:46.734  6453  6453 E Zygote  : v2
09-09 17:17:46.734  6453  6453 I libpersona: KNOX_SDCARD checking this for 10145
09-09 17:17:46.734  6453  6453 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:46.734  6453  6453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:46.734  1016  1042 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6453 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-09 17:17:46.744  6442  6442 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:17:46.744  6442  6442 D ActivityThread: Added TimaKeyStore provider
09-09 17:17:46.744  6453  6453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:17:46.744  1725  1725 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-09 17:17:46.744  6453  6453 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 17:17:46.744  1725  1725 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-09 17:17:46.744  1725  1725 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-09 17:17:46.744  1725  1725 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 17:17:46.754  1725  1725 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 17:17:46.764  1322  1707 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,09-09 17:17:46.764   302   302 I art     : Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 662us total 25.343ms
,09-09 17:17:46.764  1725  1725 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-09 17:17:46.764  1016  1305 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-09 17:17:46.774   287   287 E SMD     : DCD OFF
09-09 17:17:46.774  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.774  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.774  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.774  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.774  6453  6453 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.774  6453  6453 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.784   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 17.513ms
,09-09 17:17:46.804   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.914ms
,09-09 17:17:46.814  6472  6472 E Zygote  : MountEmulatedStorage()
09-09 17:17:46.814  6472  6472 I libpersona: KNOX_SDCARD checking this for 10081
09-09 17:17:46.814  6472  6472 E Zygote  : v2
09-09 17:17:46.814  6472  6472 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:46.814  6472  6472 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 17:17:46.814  6472  6472 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:46.814  6472  6472 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.824  1016  1305 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6472 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:46.824   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-09 17:17:46.834  1725  1725 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-09 17:17:46.844  6472  6472 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.844  6472  6472 D ActivityThread: Added TimaKeyStore provider
09-09 17:17:46.844  6453  6453 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-09 17:17:46.844  6453  6453 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:17:46.844  6453  6453 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 17:17:46.844  6453  6453 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 17:17:46.844  6453  6453 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 17:17:46.854  3655  3655 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 17:17:46 GMT+02:00 2016
,09-09 17:17:46.854  1016  1219 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 17:17:46.854  1016  1219 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.854  6427  6427 I MusicStore: Database version: 108
,09-09 17:17:46.854  1016  1219 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.854  1016  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:46.854  1016  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 17:17:46.854  3655  3655 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 17:17:46.864  3655  3655 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 17:17:46.864  1016  1724 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-09 17:17:46.864  3655  3655 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 17:17:46.864  1016  1724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.864  1016  1724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.864  1016  1724 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:46.864  1016  1724 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:46.874  3655  3655 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 17:17:46.874  3655  6492 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 17:17:46.874  3655  6492 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 17:17:46.884  6493  6493 E Zygote  : MountEmulatedStorage()
,09-09 17:17:46.884  6493  6493 E Zygote  : v2
09-09 17:17:46.884  6493  6493 I libpersona: KNOX_SDCARD checking this for 10034
09-09 17:17:46.884  6493  6493 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:46.884  1016  1724 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6493 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-09 17:17:46.884  6493  6493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 17:17:46.884  6493  6493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 17:17:46.884  6493  6493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:46.894  1016  1252 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null,
09-09 17:17:46.894  1016  1252 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 17:17:46.894  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:46.894  1016  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:46.894  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-09 17:17:46.894  3655  6492 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 17:17:46.894  3655  6492 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END,
,09-09 17:17:46.904  3655  3655 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-09 17:17:46.904  6493  6493 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:46.904  1016  1252 D RCPManagerService: exchangeData() failure , invalid userId
09-09 17:17:46.914  6493  6493 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:46.924  1016  1219 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:46.944  6493  6493 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-09 17:17:46.974  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId
09-09 17:17:46.974  6427  6427 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 17:17:46.974  6427  6427 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 17:17:46.974  3194  6514 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 17:17:46.974  3194  6514 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-09 17:17:46.974  3194  6514 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-09 17:17:46.984  5895  5895 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 17:17:46.984  3194  6514 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-09 17:17:46.994  3194  6514 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 17:17:46.994  6076  6076 I SA      : [DM] init START
,09-09 17:17:46.994  1016  3273 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 17:17:46.994  1016  3273 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 17:17:46.994  1016  3273 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:46.994  1016  3273 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 17:17:46.994  1016  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 17:17:47.004  1016  3068 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 17:17:47.004  1016  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.004  1016  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.004  1016  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.004  1016  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.004  6076  6076 I SA      : [DM] This device is not a Vodafone
,09-09 17:17:47.014  5895  6517 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 17:17:47.014  1016  1219 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:47.014  6518  6518 E Zygote  : MountEmulatedStorage()
09-09 17:17:47.014  6518  6518 I libpersona: KNOX_SDCARD checking this for 10113
09-09 17:17:47.014  6518  6518 E Zygote  : v2
09-09 17:17:47.014  6518  6518 I libpersona: KNOX_SDCARD not a persona
09-09 17:17:47.014  6518  6518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 17:17:47.024  1016  3068 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6518 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:17:47.024  6518  6518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:47.024  6518  6518 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:47.024  6076  6076 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-09 17:17:47.024  6076  6076 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-09 17:17:47.024  6076  6076 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-09 17:17:47.024  6076  6076 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
09-09 17:17:47.024  6076  6076 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
09-09 17:17:47.024  6076  6076 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
09-09 17:17:47.024  6076  6076 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-09 17:17:47.044  6076  6076 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 17:17:47.044  6518  6518 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-09 17:17:47.044  6518  6518 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-09 17:17:47.044  6076  6076 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-09 17:17:47.054  6076  6076 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-09 17:17:47.054  6076  6076 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
09-09 17:17:47.054  6427  6427 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 17:17:47.054  6076  6076 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-09 17:17:47.054  6076  6076 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-09 17:17:47.054  6076  6076 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-09 17:17:47.054  6076  6076 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
09-09 17:17:47.054  6076  6076 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
09-09 17:17:47.054  6076  6076 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-09 17:17:47.064  6076  6076 I SA      : [SCU] isHaveSA() - false,
09-09 17:17:47.064  6076  6076 I SA      : support phone number id : false
09-09 17:17:47.064  6076  6076 I SA      : [DM] Supports Ref Jpn : true
09-09 17:17:47.064  6076  6076 I SA      : [DM] init END
09-09 17:17:47.064  6076  6076 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-09 17:17:47.064  6076  6076 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 17:17:47.064  6076  6076 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 17:17:47.074  6076  6076 I SA      : [SLFUCHKMGR] constructor called
,09-09 17:17:47.084  6076  6076 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 17:17:47.084  6076  6076 I SA      : [OR] == isSIMCardReady false ==
,09-09 17:17:47.084  6076  6076 I SA      : [SCU] == networkStateCheck == false
09-09 17:17:47.084  6076  6076 I SA      : [OR] onReceive END
,09-09 17:17:47.084  1016  1305 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:47.094  1016  3139 I ActivityManager: Killing 5850:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-09 17:17:47.094  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:47.094  1016  3058 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:47.124  5988  6003 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-09 17:17:47.124  1016  1724 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:47.124  6427  6427 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 17:17:47.124  6427  6427 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c87962a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 17:17:47.134  6427  6427 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 17:17:47.134  6427  6427 D AndroidMusic: GMSCore installation verified
,09-09 17:17:47.144  5988  6003 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-09 17:17:47.144  5988  6003 D BadgeProvider: sendNotify, [notify] : null
09-09 17:17:47.144  5988  6003 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-09 17:17:47.144  5988  6003 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 17:17:47.144  5988  6003 D BadgeProvider: update, [UpdateCount] : 1
,09-09 17:17:47.144  1477  1477 D Launcher.Model: reloadBadges entered.
,09-09 17:17:47.144  1016  3139 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 17:17:47.154  1016  1252 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 17:17:47.154  1016  1252 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-09 17:17:47.154  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.154  1016  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.154  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:47.174  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:47.174  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:47.174  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1
09-09 17:17:47.174  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:47.174  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-09 17:17:47.174  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.174  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.174  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.174  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.194  6540  6540 E Zygote  : MountEmulatedStorage(),
09-09 17:17:47.194  6540  6540 E Zygote  : v2
09-09 17:17:47.194  6540  6540 I libpersona: KNOX_SDCARD checking this for 10159
09-09 17:17:47.194  6540  6540 I libpersona: KNOX_SDCARD not a persona,
,09-09 17:17:47.194  6540  6540 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:47.194  1016  1029 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6540 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:17:47.204  6540  6540 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:17:47.204  6427  6427 I ConfigStore: Config Database version: 1
,09-09 17:17:47.204  6540  6540 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-09 17:17:47.224  6540  6540 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:47.224  6540  6540 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.264  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 17:17:47.264  1016  1389 I ActivityManager: Killing 5503:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-09 17:17:47.274  1016  3068 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:47.274  1016  3068 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.274  1016  3068 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.274  1016  3068 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.274  1016  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:47.284  3810  3810 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 17:17:47.294  3810  4549 I iu.UploadsManager: num queued entries: 0
,09-09 17:17:47.294  3810  4549 I iu.UploadsManager: num updated entries: 0
,09-09 17:17:47.294  3810  4549 I iu.SyncManager: NEXT; no task
,09-09 17:17:47.304   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 17:17:47.304   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:47.314  6427  6427 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 17:17:47.314   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 17:17:47.314   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:47.314  6427  6427 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 17:17:47.324   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 17:17:47.324   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:47.324  6427  6427 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 17:17:47.324  1016  1489 I art     : Explicit concurrent mark sweep GC freed 55443(3MB) AllocSpace objects, 13(256KB) LOS objects, 33% free, 28MB/42MB, paused 3.018ms total 184.145ms
,09-09 17:17:47.334  1016  3273 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-09 17:17:47.334  1016  3273 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.334  1016  3273 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.334  1016  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.334  1016  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:47.354  1016  1252 I ActivityManager: Killing 5469:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-09 17:17:47.364  1016  1489 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 17:17:47.364  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-09 17:17:47.364  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.364  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.364  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:47.384  1016  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:47.394  1016  3058 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:47.394   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 17:17:47.394   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:47.394  6518  6560 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 17:17:47.394  1016  1028 I AudioService: getStreamVolume 3 index 0
,09-09 17:17:47.394  6427  6427 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 17:17:47.404   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 17:17:47.404   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:47.404  6427  6427 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 17:17:47.404  6518  6560 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 17:17:47.434  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.434  1016  1029 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-09 17:17:47.434  1016  1389 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 17:17:47.434  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 17:17:47.434  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.434  1016  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.434  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:47.444   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 17:17:47.444   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:47.444  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.444  1016  1219 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 17:17:47.444  1016  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.444  1016  1219 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.444  1016  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.444  1016  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-09 17:17:47.444  6518  6564 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 17:17:47.444  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.444  1016  3269 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 17:17:47.444  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
09-09 17:17:47.444   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 17:17:47.444   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:47.454  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.454  1016  3269 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.454  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:47.454  6518  6564 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 17:17:47.454  1016  3068 I ActivityManager: Killing 5865:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-09 17:17:47.454  1016  1389 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:47.474  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 17:17:47.474  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.474  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.474  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.474  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.484  6568  6568 E Zygote  : MountEmulatedStorage()
09-09 17:17:47.484  6568  6568 I libpersona: KNOX_SDCARD checking this for 10002
09-09 17:17:47.484  6568  6568 E Zygote  : v2
09-09 17:17:47.484  6568  6568 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:47.494  6568  6568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:47.494  6568  6568 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 17:17:47.494  6568  6568 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:47.504  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6568 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:47.524  6568  6568 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:47.524  6568  6568 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.534  1016  1029 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
09-09 17:17:47.534  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.534  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:47.534  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.534  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-09 17:17:47.544  6427  6427 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-09 17:17:47.554  1016  3068 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 17:17:47.554  1016  3068 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 17:17:47.554  1016  3068 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.554  1016  3068 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.554  1016  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:47.584  1016  1489 I ActivityManager: Killing 5910:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-09 17:17:47.594  1016  1028 I ActivityManager: Killing 5558:com.android.vending/u0a28 (adj 15): empty #31
,09-09 17:17:47.594  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-09 17:17:47.604  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.604  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.604  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.604  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.614  6599  6599 E Zygote  : MountEmulatedStorage()
,09-09 17:17:47.614  6599  6599 E Zygote  : v2
09-09 17:17:47.614  6599  6599 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:17:47.614  6599  6599 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:47.614  6599  6599 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:47.614  1016  1029 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6599 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 17:17:47.614  6599  6599 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:17:47.614  6599  6599 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 17:17:47.644  6599  6599 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:47.644  6599  6599 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.654  1016  3273 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:47.654  1016  3273 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:47.654  1016  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:47.654  1016  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 17:17:47.664  6518  6518 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-09 17:17:47.674  6518  6518 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9737-9738)
09-09 17:17:47.674  6518  6518 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 17:17:47.684  6518  6518 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f0dc393}
,09-09 17:17:47.684  6518  6518 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 17:17:47.684  6518  6518 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 17:17:47.684  6599  6599 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 17:17:47.704  6518  6518 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 17:17:47.704  6518  6518 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 17:17:47.704  6518  6518 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 17:17:47.734  6518  6518 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-09 17:17:47.734  6518  6518 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,09-09 17:17:47.734  6518  6518 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-09 17:17:47.734  6518  6518 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 17:17:47.734  6518  6518 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 17:17:47.734  6518  6518 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 17:17:47.734  6518  6518 I Adreno-EGL: Local Branch: 
09-09 17:17:47.734  6518  6518 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 17:17:47.734  6518  6518 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 17:17:47.734  6518  6518 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 17:17:47.784  6518  6627 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 17:17:47.794  6518  6518 I NSApplication: Starting up...
,09-09 17:17:47.804  6599  6599 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-09 17:17:47.814  1016  3269 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-09 17:17:47.814  6599  6599 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-09 17:17:47.814  6599  6599 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:47.814  1016  3269 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.814  1016  3269 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.814  1016  3269 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.814  6599  6599 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 17:17:47.814  6599  6599 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 17:17:47.814  6599  6599 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-09 17:17:47.814  1016  3269 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.824  1016  3269 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6632 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 17:17:47.834  6632  6632 E Zygote  : MountEmulatedStorage()
09-09 17:17:47.834  6632  6632 E Zygote  : v2
09-09 17:17:47.834  6632  6632 I libpersona: KNOX_SDCARD checking this for 10120
09-09 17:17:47.834  6632  6632 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:47.834  1016  3269 I ActivityManager: Killing 6005:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
09-09 17:17:47.834  1016  3269 I ActivityManager: Killing 5814:com.android.mms/u0a46 (adj 15): empty #32
,09-09 17:17:47.834  6632  6632 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:47.834  1016  3269 I ActivityManager: Killing 6030:com.wsomacp/u0a25 (adj 15): empty #31
09-09 17:17:47.834  6632  6632 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:47.834  6632  6632 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:47.864  6632  6632 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:47.864  6632  6632 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:47.874  6632  6632 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:17:47.944  1016  1095 V AlarmManager: waitForAlarm result :4
,09-09 17:17:47.944  1016  1095 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.944  1016  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.944  1016  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:47.944  1016  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.944  1016  1095 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:47.954  1016  1029 D CountryDetector: No listener is left
,09-09 17:17:47.974  6651  6651 E Zygote  : MountEmulatedStorage(),
09-09 17:17:47.974  6651  6651 E Zygote  : v2
,09-09 17:17:47.974  6651  6651 I libpersona: KNOX_SDCARD checking this for 10028
,09-09 17:17:47.974  6651  6651 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:47.984  1016  1095 I ActivityManager: Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6651 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-09 17:17:47.984  1016  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-09 17:17:47.984  6651  6651 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:47.984  6651  6651 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:17:47.994  6651  6651 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 17:17:48.024  6651  6651 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:48.034  6651  6651 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:48.064  1016  3068 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 17:17:48.064  1016  3068 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:17:48.064  1016  3068 D SecContentProvider2: mCursor = null
,09-09 17:17:48.064  1016  3068 D WifiService: setWifiEnabled: true pid=6182, uid=10155
,09-09 17:17:48.064  1016  3068 W ActivityManager: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:17:48.064  1016  3068 W WifiService: Failed getting userId using ActivityManagerNative
09-09 17:17:48.064  1016  3068 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:17:48.064  1016  3068 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 17:17:48.064  1016  3068 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 17:17:48.064  1016  3068 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 17:17:48.064  1016  3068 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 17:17:48.064  1016  3068 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 17:17:48.064  1016  3068 D SettingsProvider: name = wifi_on
,09-09 17:17:48.074  1016  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 17:17:48.134  3810  3810 D ConnectivityManager: CallingUid : 10012, CallingPid : 3810
,09-09 17:17:48.134  1016  3271 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 17:17:48.134  1016  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-09 17:17:48.214  3810  6677 W DriveInitializer: Background init thread started
,09-09 17:17:48.234  1016  1305 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 17:17:48.234  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.234  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.234  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:17:48.234  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:17:48.244  6678  6678 E Zygote  : MountEmulatedStorage()
,09-09 17:17:48.244  6678  6678 E Zygote  : v2
09-09 17:17:48.244  6678  6678 I libpersona: KNOX_SDCARD checking this for 10125,
09-09 17:17:48.244  6678  6678 I libpersona: KNOX_SDCARD not a persona
,09-09 17:17:48.244  6678  6678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:17:48.254  1016  1305 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6678 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
09-09 17:17:48.254  6678  6678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 17:17:48.254  6678  6678 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:17:48.274   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-09 17:17:48.274   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 17:17:48.274  3810  6677 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-09 17:17:48.294  6678  6678 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:17:48.294  6678  6678 D ActivityThread: Added TimaKeyStore provider
,09-09 17:17:48.314  3810  6677 W DriveInitializer: Background init thread ended
,09-09 17:17:48.324  6678  6678 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 17:17:48.324  6678  6678 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 17:17:48.324  6678  6678 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:17:48.334  6678  6678 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:17:48.334  6678  6678 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 17:17:48.344  6678  6678 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 17:17:48.344  1016  1305 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 17:17:48.354  1016  1389 I ActivityManager: Killing 5930:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-09 17:17:48.404  6651  6651 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(225): No need to run daily hygiene.
,09-09 17:17:48.424  6651  6651 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 17:17:48.424  6651  6651 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-09 17:17:48.434  1016  1028 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-09 17:17:48.434  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-09 17:17:48.444  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:48.444  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:48.444  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-09 17:17:48.454  6651  6651 I Finsky  : [1] com.google.android.finsky.utils.bp.a(177): Enabling bucket experiment: factor=2.000, zeroDelta=0ms, forceNetwork=false
,09-09 17:17:48.464  1016  1044 D Tethering: interfaceAdded wlan0
,09-09 17:17:48.474  1016  1130 E Tethering: No numeric data
,09-09 17:17:48.474  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:17:48.474  1016  1130 D Tethering: clearTetheredNotification()
,09-09 17:17:48.474  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 17:17:48.474  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:48.474  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:48.474  1016  1130 D Tethering: InitialState.processMessage what=4
,09-09 17:17:48.474  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:48.474  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:48.474  1016  1130 E Tethering: No numeric data
09-09 17:17:48.474  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 17:17:48.474  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:17:48.474  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:17:48.474  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 17:17:48.484  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:48.484  1016  1130 D Tethering: clearTetheredNotification()
09-09 17:17:48.484  1016  1124 V NetworkStats: performPollLocked() took 3ms
09-09 17:17:48.484  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:48.484  1016  1044 D Tethering: interfaceAdded p2p0
,09-09 17:17:48.484  1016  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 17:17:48.484  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 17:17:48.484  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 17:17:48.484  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:48.484  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:48.484  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:48.484  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:17:48.484  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:48.494  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:48.494  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:48.494  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:48.494  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:17:48.494  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:48.494  1016  1124 V NetworkStats: performPollLocked() took 5ms
09-09 17:17:48.494   277   973 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 17:17:48.494   277   973 D SoftapController: Softap fwReload - Ok
,09-09 17:17:48.494   277   973 D CommandListener: Setting iface cfg
09-09 17:17:48.494   277   973 D CommandListener: Trying to bring down wlan0
,09-09 17:17:48.494   277   973 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:17:48.494  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:48.494  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:48.504  1016  1127 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 17:17:48.504  1016  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 17:17:48.504  1016  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-09 17:17:48.514  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:48.514  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:48.514  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:48.514  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:48.514  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:48.514  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:48.514  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:48.514  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-09 17:17:48.514  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
09-09 17:17:48.514  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:48.514  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 17:17:48.534  1173  1173 D HotspotTile: onReceive : 2, 0
,09-09 17:17:48.534  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: com.google.android.gms signature not valid.  Found: 
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: MIIEQzCCAyugAwIBAgIJAMLgh0ZkSjCNMA0GCSqGSIb3DQEBBAUAMHQxCzAJBgNVBAYTAlVTMRMw
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: EQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29n
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: bGUgSW5jLjEQMA4GA1UECxMHQW5kcm9pZDEQMA4GA1UEAxMHQW5kcm9pZDAeFw0wODA4MjEyMzEz
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: MzRaFw0zNjAxMDcyMzEzMzRaMHQxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYw
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: FAYDVQQHEw1Nb3VudGFpbiBWaWV3MRQwEgYDVQQKEwtHb29nbGUgSW5jLjEQMA4GA1UECxMHQW5k
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: cm9pZDEQMA4GA1UEAxMHQW5kcm9pZDCCASAwDQYJKoZIhvcNAQEBBQADggENADCCAQgCggEBAKtW
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: LgDYO6IIrgqWbxJOKdoR8qtW0I9Y4sypEwPpt1TTcvZApxsdyxMJZ2JORland2qSGT2y5b+3JKke
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: dxiLDmpHpDsz2WCbdxgxRczfey5YZnTJ4VZbH0xqWVW/8lGmPav5xVwnIiJS6HXk+BVKZF+JcWjA
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: sb/GEuq/eFdpuzSqeYTcfi6idkyugwfYwXFU1+5fZKUaRKYCwkkFQVfcAs1fXA5V+++FGfvjJ/Cx
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: URaSxaBvGdGDhfXE28LWuT9ozCl5xw4Yq5OGazvV24mZVSoOO0yZ31j7kYvtwYK6NeADwbSxDdJE
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: qO4k//0zOHKrUiGYXtqw/A0LFFtqoZKFjnkCAQOjgdkwgdYwHQYDVR0OBBYEFMd9jMIhF1Ylmn/T
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: gt9r45jk14alMIGmBgNVHSMEgZ4wgZuAFMd9jMIhF1Ylmn/Tgt9r45jk14aloXikdjB0MQswCQYD
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: VQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNTW91bnRhaW4gVmlldzEUMBIG
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: A1UEChMLR29vZ2xlIEluYy4xEDAOBgNVBAsTB0FuZHJvaWQxEDAOBgNVBAMTB0FuZHJvaWSCCQDC
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: 4IdGZEowjTAMBgNVHRMEBTADAQH/MA0GCSqGSIb3DQEBBAUAA4IBAQBt0lLO74UwLDYKqs6Tm8/y
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: zKkEu116FmH4rkaymUIE0P9KaMftGlMexFlaYjzmB2OxZyl6euNXEsQH8gjwyxCUKRJNexBiGcCE
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: yj6z+a1fuHHvkiaai+KL8W1EyNmgjmyy8AW7P+LLlkR+ho5zEHatRbM/YAnqGcFh5iZBqpknHf1S
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: KMXFh4dd239FJ1jWYfbMDMy3NS5CTMQ2XFI1MvcyUTdZPErjQfTbQe3aDQsQcafEQPD+nqActifK
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: Z0Np0IS9L9kR/wbNvyz6ENwPiTrjV2KRkEjH78ZMcUQXg0L3BYHJ3lc69Vs5Ddf9uUGGMYldX3Wf
09-09 17:17:48.534  6651  6724 V GoogleSignatureVerifier: MBEmh/9iFBDAaTCK
,09-09 17:17:48.534  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:48.534  1016  1389 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:48.534  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:48.544  1016  1389 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:48.544  1016  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:48.544  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:17:48.544  6651  6651 I Finsky  : [1] com.google.android.finsky.l.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
09-09 17:17:48.544  6651  6651 I Finsky  : [1] com.google.android.finsky.l.j.run(214): Finished loading 1 libraries.
,09-09 17:17:48.544  3618  3618 I Hs20UtilService: Starting #12
,09-09 17:17:48.544  3618  3653 I Hs20UtilService: Message received 5011
,09-09 17:17:48.544  1016  3271 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 17:17:48.544  6723  6723 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 17:17:48.544  6723  6723 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 17:17:48.554  6723  6723 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
09-09 17:17:48.554  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 17:17:48.554  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:48.554  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1
09-09 17:17:48.554  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:48.554  1016  3271 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:48.554  1016  3271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:48.554  1016  3271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-09 17:17:48.564  6723  6723 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-09 17:17:48.574   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6723,
09-09 17:17:48.574   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 17:17:48.574  6723  6723 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 17:17:48.574  6723  6723 I wpa_supplicant: ssSupport state is = 1
09-09 17:17:48.574  6723  6723 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 17:17:48.574  6723  6723 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-09 17:17:48.574   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6723
09-09 17:17:48.574   351   351 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-09 17:17:48.574  1016  1252 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:48.584  6651  6651 I Finsky  : [1] com.google.android.finsky.c.l.a(253): result=false type=4
,09-09 17:17:48.584  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:48.584  1016  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:48.584  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
09-09 17:17:48.584  1016  3139 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-09 17:17:48.584  1016  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,09-09 17:17:48.584  1016  3139 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:48.584  1016  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:48.584  1016  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-09 17:17:48.594  1925  1925 D WearableService: callingUid 10012, callindPid: 1925
,09-09 17:17:48.614  6651  6719 I Finsky  : [1165] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,09-09 17:17:48.614  6651  6651 I Finsky  : [1] com.google.android.finsky.services.bd.a(1075): Restore complete with 0 success and 0 failed.
,09-09 17:17:48.634  6651  6651 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-09 17:17:48.634  6651  6651 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-09 17:17:48.744   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-09 17:17:48.754  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-09 17:17:48.814  6723  6723 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 17:17:48.814  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 17:17:48.824  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 17:17:48.834   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6723
09-09 17:17:48.834   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 17:17:48.834  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 17:17:48.834  6723  6723 I wpa_supplicant: ssSupport state is = 1
09-09 17:17:48.834  6723  6723 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 17:17:48.834  6723  6723 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:17:48.834  6723  6723 E wpa_supplicant: SIM READ ERROR
09-09 17:17:48.834  6723  6723 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:48.834  6723  6723 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:17:48.834  6723  6723 E wpa_supplicant: SIM READ ERROR
09-09 17:17:48.834  6723  6723 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:48.834  6723  6723 I wpa_supplicant: wpa_default_ap_write_once
09-09 17:17:48.834  6723  6723 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 17:17:48.834  6723  6723 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:48.834  6723  6723 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 17:17:48.834  6723  6723 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:48.834  6723  6723 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 17:17:48.834  6723  6723 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:17:48.834  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:48.834  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:48.834  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:48.854  6651  6719 I Finsky  : [1165] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,09-09 17:17:48.854  6651  6651 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,09-09 17:17:48.854  1016  3272 I ActivityManager: Killing 6054:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-09 17:17:48.934  6723  6723 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-09 17:17:49.074  1016  1041 E libprocessgroup: failed to kill 1 processes for processgroup 6054
,09-09 17:17:49.224  6723  6723 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 17:17:49.224  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-09 17:17:49.234  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 17:17:49.244   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6723
09-09 17:17:49.244   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-09 17:17:49.244  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 17:17:49.244  6723  6723 I wpa_supplicant: ssSupport state is = 1
09-09 17:17:49.244  6723  6723 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 17:17:49.244  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 17:17:49.254  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 17:17:49.254   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6723
09-09 17:17:49.254   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-09 17:17:49.264  6723  6723 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 17:17:49.264  6723  6723 I wpa_supplicant: ssSupport state is = 1
,09-09 17:17:49.264  6723  6723 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:49.264  6723  6723 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:17:49.264  6723  6723 E wpa_supplicant: SIM READ ERROR
,09-09 17:17:49.264  6723  6723 I wpa_supplicant: wpa_default_ap_write_once
09-09 17:17:49.264  6723  6723 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
,09-09 17:17:49.264  6723  6723 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 17:17:49.264  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-09 17:17:49.264  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:49.264  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 17:17:49.264  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
09-09 17:17:49.264  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:49.264  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:49.304  6723  6723 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 17:17:49.304  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 17:17:49.414  6723  6723 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-09 17:17:49.414  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 17:17:49.414  6723  6723 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 17:17:49.474  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 17:17:49.474  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:49.474  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:49.514  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 17:17:49.514  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 17:17:49.514  6723  6723 I wpa_supplicant: HOTSPOT20_ENABLE called
09-09 17:17:49.514  6723  6723 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:17:49.514  6723  6723 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:17:49.514  6723  6723 E wpa_supplicant: SIM READ ERROR
09-09 17:17:49.514  6723  6723 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:49.534  6723  6723 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 17:17:49.544  1016  1127 D WifiNative-wlan0: callSECApiInt - ID [210],
09-09 17:17:49.544  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 17:17:49.544  6723  6723 I wpa_supplicant: Skip scan - bUseNetwork false
09-09 17:17:49.544  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:49.544  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:49.544  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:49.544  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:49.544  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:49.544  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:49.554  1173  1173 D HotspotTile: onReceive : 3, 0
09-09 17:17:49.544  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:49.544  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:49.544  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-09 17:17:49.554  1016  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-09 17:17:49.554  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:49.554  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:49.554  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:49.554  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
09-09 17:17:49.554  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:49.554  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:49.554  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:49.554  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:49.554  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:49.554  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:49.554  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:17:49.554  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:49.554  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:49.564  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:49.564  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:49.564  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:49.564  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:17:49.564  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:49.564  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:49.564  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:49.564  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:49.564  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:49.564  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:49.564  1016  3269 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:17:49.564  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:17:49.564  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:49.564  1016  3269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-09 17:17:49.564  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:17:49.564  3618  3618 I Hs20UtilService: Starting #13
,09-09 17:17:49.564  3618  3653 I Hs20UtilService: Message received 5011
,09-09 17:17:49.574  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 17:17:49.574  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:49.574  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1
09-09 17:17:49.574  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:49.584  1016  1127 E WifiConfigStore: Not a HS20
,09-09 17:17:49.584  1016  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 17:17:49.584  1016  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 17:17:49.594  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13],
09-09 17:17:49.594  6723  6723 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON,
,09-09 17:17:49.594  6723  6723 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 17:17:49.594  6723  6723 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 17:17:49.594  6723  6723 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 17:17:49.594  6723  6723 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 17:17:49.594  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 17:17:49.594  6723  6723 I wpa_supplicant: First Scan Start
,09-09 17:17:49.594  6723  6723 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-09 17:17:49.594  1016  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-09 17:17:49.594  1016  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:17:49.594  1016  1127 I WifiNative-HAL: startHal
09-09 17:17:49.594  1016  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9c66388c
09-09 17:17:49.594  1016  1127 I WifiNative-HAL: Could not start hal
,09-09 17:17:49.594  6363  6363 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:49.604  1016  1127 E WifiNative-wlan0: do suspend true,
,09-09 17:17:49.604  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 17:17:49.604  1016  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 17:17:49.614  1016  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 17:17:49.614  1016  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 17:17:49.614  1016  1127 E WifiNative-wlan0: invaild command id : 215
,09-09 17:17:49.614  1016  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 17:17:49.614  1016  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 17:17:49.614  1016  1127 E WifiNative-wlan0: invaild command id : 215
,09-09 17:17:49.614   277   973 D CommandListener: Setting iface cfg
09-09 17:17:49.614   277   973 D CommandListener: Trying to bring up p2p0
,09-09 17:17:49.614  1016  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 17:17:49.624  6723  6723 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 17:17:49.624  1016  1126 D WifiP2pService: P2pEnablingState
09-09 17:17:49.624  1016  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:49.624  1016  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 17:17:49.624  6723  6723 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 17:17:49.624  1016  1126 D WifiP2pService: P2p socket connection successful
09-09 17:17:49.624  1016  1126 D WifiP2pService: P2pEnabledState
,09-09 17:17:49.624  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 17:17:49.624  6723  6723 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
09-09 17:17:49.624  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:49.624  1016  1127 D SecContentProvider2: mCursor = null
09-09 17:17:49.634  1016  1126 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 17:17:49.634  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:49.634  1016  1127 D SecContentProvider2: mCursor = null
09-09 17:17:49.634  1016  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-09 17:17:49.634  1016  1126 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-09 17:17:49.654  1016  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 17:17:49.654  1016  1126 D WifiP2pService: InactiveState
,09-09 17:17:49.654  1016  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-09 17:17:49.654  1016  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 17:17:49.654  6723  6723 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-09 17:17:49.654  1016  1126 D WifiP2pService: InactiveState{ what=143376 }
09-09 17:17:49.654  1016  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 17:17:49.694  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 17:17:49.694  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:49.694  1016  1149 I WifiNative-HAL: startHal
09-09 17:17:49.694  1016  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9d70b9bc
09-09 17:17:49.694  1016  1149 I WifiNative-HAL: Could not start hal
09-09 17:17:49.694  1016  1149 E WifiScanningService: could not start HAL
,09-09 17:17:49.694  1016  1016 D RttService: SCAN_AVAILABLE : 3
09-09 17:17:49.694  1016  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:49.694  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 17:17:49.694  1016  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 17:17:49.694  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:49.694  1016  1047 D WifiDisplayController: disconnect
09-09 17:17:49.694  1016  1047 D WifiDisplayController: updateConnection
09-09 17:17:49.694  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:49.694  1016  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:49.704  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 17:17:49.704  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:49.704  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:17:49.704  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 17:17:49.704  1016  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  secondary type: null
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  wps: 0
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  grpcapab: 0
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  devcapab: 0
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  status: 3
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  wfdInfo: null
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  groupownerAddress: null
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  GOdeviceName: null
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  interfaceAddress: 
09-09 17:17:49.704  1016  1047 D WifiDisplayController:  SConnectInfo : null
,09-09 17:17:49.704  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 17:17:49.704  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 17:17:49.704  1016  3138 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:49.704  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-09 17:17:49.704  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:17:49.704  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:49.704  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:17:49.704  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:49.704  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:49.704  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:49.714  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:49.714  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 17:17:49.714  6327  6327 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 17:17:49.714  6348  6348 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:49.774   287   287 E SMD     : DCD OFF,
,09-09 17:17:50.754  6723  6723 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
09-09 17:17:50.754  6723  6723 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-09 17:17:50.754  6723  6723 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 17:17:50.754  6723  6723 I wpa_supplicant: Trying to associate with  'G700'
09-09 17:17:50.754  6723  6723 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-09 17:17:50.754  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-09 17:17:50.754  1016  6736 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 17:17:50.774  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:50.774  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:50.914  6723  6723 E wpa_supplicant: Cmd 35605 not handled
09-09 17:17:50.914  6723  6723 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:17:50.914  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:50.914  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:50.914  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:50.914  6723  6723 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-09 17:17:50.914  6723  6723 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 17:17:50.914  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 17:17:50.914  6723  6723 I wpa_supplicant: Associated with F4.99.3E
09-09 17:17:50.914  6723  6723 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:17:50.914  6723  6723 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 17:17:50.914  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:17:50.924  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:50.924  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:50.924  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
09-09 17:17:50.924  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-09 17:17:50.924  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 17:17:50.924  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
09-09 17:17:50.924  1016  1130 E Tethering: No numeric data
09-09 17:17:50.924  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 17:17:50.924  1016  1130 D Tethering: clearTetheredNotification()
,09-09 17:17:50.924  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:50.924  1016  1127 D SecContentProvider2: mCursor = null,
,09-09 17:17:50.924  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:50.924  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:50.934  6723  6723 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:17:50.934  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:50.934  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:17:50.934  6723  6723 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 17:17:50.934  6723  6723 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-09 17:17:50.934  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:17:50.934  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-09 17:17:50.934  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 17:17:50.934  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:50.934  1016  1127 D SecContentProvider2: mCursor = null
09-09 17:17:50.934  6723  6723 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:17:50.934  6723  6723 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-09 17:17:50.934  6723  6723 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 17:17:50.934  6723  6723 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 17:17:50.934  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:17:50.934  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 17:17:50.934  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 17:17:50.934  1016  1124 V NetworkStats: performPollLocked() took 8ms
09-09 17:17:50.934  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:50.934  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 17:17:50.934  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 17:17:50.934  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:50.944  1016  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 17:17:50.944  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:50.954  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:50.954  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:50.954  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:50.954  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:50.954  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:50.954  1016  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 17:17:50.954  1016  1042 I ActivityManager: Killing 5428:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-09 17:17:50.954  1016  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 17:17:50.954  1016  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 17:17:50.954  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:50.954  1016  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:17:50.954  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-09 17:17:50.954  1016  3058 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:17:50.954  1016  3058 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:17:50.954  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:50.954  1016  3058 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:50.954  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:50.954  3618  3618 I Hs20UtilService: Starting #14
,09-09 17:17:50.964  3618  3653 I Hs20UtilService: Message received 5007
,09-09 17:17:50.964  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 17:17:50.964  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:50.964  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:50.964  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:17:50.964  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:50.964  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:50.964  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:50.974  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:17:50.984   277   973 D CommandListener: Setting iface cfg,
,09-09 17:17:50.984  1016  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,09-09 17:17:50.984  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 17:17:50.984  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:51.004  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:51.004  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:51.004  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.004  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.004  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.004  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:51.004  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:51.004  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:51.004  1016  1127 E WifiNative-wlan0: do suspend false
,09-09 17:17:51.014  1016  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-09 17:17:51.014  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 17:17:51.074  1016  3068 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 17:17:51.074  1016  3068 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-09 17:17:51.074  1016  3068 D SecContentProvider2: mCursor = null
,09-09 17:17:51.074  1016  3068 D WifiService: setWifiEnabled: false pid=6182, uid=10155
,09-09 17:17:51.074  1016  3068 D SettingsProvider: name = wifi_on
,09-09 17:17:51.084  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:17:51.104  1016  1127 E WifiNative-wlan0: do suspend true
,09-09 17:17:51.124  1016  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-09 17:17:51.124  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 17:17:51.124  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:51.124  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 17:17:51.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:51.134  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.134  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.134   277   973 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:17:51.134  1016  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:51.134  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:17:51.134  1016  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:17:51.134  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-09 17:17:51.134   277   973 E Netd    : no such netId 503
09-09 17:17:51.134  1016  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
09-09 17:17:51.134  1016  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 17:17:51.134  1016  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-09 17:17:51.144  1016  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 17:17:51.144  1016  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:17:51.144  1016  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 17:17:51.144  1016  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-09 17:17:51.144  1016  1129 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 17:17:51.144  1016  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,09-09 17:17:51.144  1016  1126 D WifiP2pService: InactiveState{ what=131204 }
,09-09 17:17:51.144  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 17:17:51.144  1016  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 17:17:51.144  1016  1129 E ConnectivityService: updateNetworkInfo(),
09-09 17:17:51.144  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED,
09-09 17:17:51.154  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:51.154  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:51.154  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.154  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.154  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.154  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.154  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 17:17:51.154  1016  1016 D RttService: SCAN_AVAILABLE : 1
09-09 17:17:51.154  1016  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:51.154  1016  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:17:51.154  1016  1724 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:51.154  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:17:51.164  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.164  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:51.164  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:51.164  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
09-09 17:17:51.164  1016  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:17:51.164  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,09-09 17:17:51.164  1016  1127 E WifiNative-wlan0: do suspend true
09-09 17:17:51.164  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:51.164  3618  3618 I Hs20UtilService: Starting #15
09-09 17:17:51.164  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-09 17:17:51.164  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 17:17:51.164  1016  1126 D WifiP2pService: P2pDisablingState
09-09 17:17:51.164  1016  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 17:17:51.164  1016  1126 D WifiP2pService: p2p socket connection lost
09-09 17:17:51.164  1016  1126 D WifiP2pService: P2pDisabledState
,09-09 17:17:51.174  1016  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 17:17:51.174  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 17:17:51.174  3618  3653 I Hs20UtilService: Message received 5007
,09-09 17:17:51.174  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:51.174  1016  1047 D WifiDisplayController: disconnect
,09-09 17:17:51.174  1016  1047 D WifiDisplayController: updateConnection
,09-09 17:17:51.174  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:17:51.174  1016  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:17:51.174  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 17:17:51.174  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
09-09 17:17:51.174  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:17:51.174  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 17:17:51.174  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:17:51.174  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:17:51.174  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:51.184  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 17:17:51.184  1016  3271 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 17:17:51.184  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 17:17:51.184  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:17:51.184  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:51.184  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 17:17:51.184  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:51.194  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 17:17:51.194  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:17:51.194  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,09-09 17:17:51.194  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:17:51.194  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:51.194  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:17:51.194  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:51.204  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:51.204  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 17:17:51.204  6327  6327 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 17:17:51.204  1016  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-09 17:17:51.204  1016  1126 D WifiP2pService: DefaultState{ what=143375 }
,09-09 17:17:51.204  6348  6348 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:17:51.204   277   973 D CommandListener: Clearing all IP addresses on wlan0
,09-09 17:17:51.214  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:51.214  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:51.214  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.214  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.214  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.214  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:51.224  6723  6723 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
,09-09 17:17:51.224  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,09-09 17:17:51.224  6743  6743 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 17:17:51.234  6743  6743 I dhcpcd  : version 5.5.6 starting
,09-09 17:17:51.234  6743  6743 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 17:17:51.234  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:17:51.234  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:17:51.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:17:51.244  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:17:51.244  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:17:51.244  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:51.244  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 17:17:51.244  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:17:51.244  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:51.244  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.244  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 17:17:51.244  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.244  1173  1173 D HotspotTile: onReceive : 0, 0
,09-09 17:17:51.244  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:51.244  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-09 17:17:51.244  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 17:17:51.254  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
09-09 17:17:51.254  1016  3271 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:51.254  1016  3271 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-09 17:17:51.254  1016  3271 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.254  1016  3271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:51.254  1016  3271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:17:51.254  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:51.254  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:51.254  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:51.254  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:51.254  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:17:51.254  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-09 17:17:51.254  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:17:51.254  3618  3618 I Hs20UtilService: Starting #16
09-09 17:17:51.254  3618  3653 I Hs20UtilService: Message received 5007
,09-09 17:17:51.264  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-09 17:17:51.264  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:17:51.264  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:17:51.264  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:17:51.264  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:17:51.264  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 17:17:51.264  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:17:51.294  1016  3269 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:17:51.294  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:17:51.294  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:51.294  1016  3269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-09 17:17:51.294  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:17:51.294  3618  3618 I Hs20UtilService: Starting #17
,09-09 17:17:51.294  6743  6743 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 17:17:51.294  6743  6743 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,09-09 17:17:51.294  6743  6743 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 17:17:51.294  6743  6743 I dhcpcd  : bssid match
09-09 17:17:51.294  6743  6743 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-09 17:17:51.294  3618  3653 I Hs20UtilService: Message received 5011
,09-09 17:17:51.294  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:51.294  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:51.294  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1,
09-09 17:17:51.294  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:51.364  6723  6723 I wpa_supplicant: Blacklist: Clear (all) ,
,09-09 17:17:51.424  6723  6723 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-09 17:17:51.424  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:17:51.424  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:17:51.424  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:17:51.444  6723  6723 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 17:17:51.444  6723  6723 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 17:17:51.444  6723  6723 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 17:17:51.454  6723  6723 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 17:17:51.454  6723  6723 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 17:17:51.454  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 17:17:51.454  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 17:17:51.454  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:51.454  1016  1127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-09 17:17:51.454  1016  1130 D Tethering: InitialState.processMessage what=4
,09-09 17:17:51.454  1016  1130 E Tethering: No numeric data
,09-09 17:17:51.464  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 17:17:51.464  1016  1130 D Tethering: clearTetheredNotification()
,09-09 17:17:51.464  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 17:17:51.464  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 17:17:51.464  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:51.464  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:17:51.464  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:17:51.464  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.464  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:17:51.464  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 17:17:51.464  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:17:51.464  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 17:17:51.464  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.464  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:51.474  1016  1124 V NetworkStats: performPollLocked() took 11ms
,09-09 17:17:51.474  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:51.474  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 17:17:51.474  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:17:51.824   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:51.854  6723  6723 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:17:51.914  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.914  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.914  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:51.914  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.914  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:17:51.914  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:17:51.914  6723  6723 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 17:17:52.024  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
09-09 17:17:52.024  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 17:17:52.024  6363  6363 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 17:17:52.024  1016  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 17:17:52.024  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:17:52.024  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
09-09 17:17:52.024  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.024  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.024  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.024  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:17:52.024  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:17:52.024  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 17:17:52.024  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 17:17:52.024  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:52.034  1925  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:17:52.034  1173  1173 D HotspotTile: onReceive : 1, 0
,09-09 17:17:52.034  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:52.034  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:52.034  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:17:52.034  1016  1389 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:17:52.034  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-09 17:17:52.034  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.034  1016  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:52.034  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:17:52.034  3618  3618 I Hs20UtilService: Starting #18
09-09 17:17:52.044  3618  3653 I Hs20UtilService: Message received 5011
,09-09 17:17:52.044  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:17:52.044  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:17:52.044  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 17:17:52.044  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:17:52.394  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:52.394  1016  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:52.394  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:52.404  1016  1305 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-09 17:17:52.404  1016  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-09 17:17:52.404  1016  1305 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.404  1016  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:52.404  1016  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:52.404  1016  3068 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
09-09 17:17:52.404  1016  3068 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-09 17:17:52.414  1016  3068 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:52.414  1016  3068 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:52.414  1016  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 17:17:52.414  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.414  1016  3058 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:52.414  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:52.414  6518  6562 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-09 17:17:52.424  1016  1724 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 17:17:52.424  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-09 17:17:52.424  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.424  1016  1724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:52.424  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:52.424  1016  1389 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 17:17:52.424  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-09 17:17:52.424  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.424  1016  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:52.424  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:52.424  1016  1029 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 17:17:52.424  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 17:17:52.434  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.434  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:52.434  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:52.434  1016  1305 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-09 17:17:52.444  1016  1305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-09 17:17:52.444  1016  1305 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.444  1016  1305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:52.444  1016  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:52.454  1016  1252 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:52.464  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:52.464  1016  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:52.464  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-09 17:17:52.474  1016  1219 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 17:17:52.474  1016  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0,
,09-09 17:17:52.474  1016  1219 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:52.474  1016  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:17:52.474  1016  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 17:17:52.494  6427  6752 I MusicLeanback: Conditions not met for autocaching.
,09-09 17:17:52.494  6427  6752 I MusicLeanback: Stop autocaching.
,09-09 17:17:52.514  6427  6427 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-09 17:17:52.514  6427  6757 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-09 17:17:52.624  1016  1044 D Tethering: interfaceRemoved wlan0
09-09 17:17:52.624  1016  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 17:17:52.774   287   287 E SMD     : DCD OFF,
,09-09 17:17:52.824   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 17:17:52.854  1016  1044 D Tethering: interfaceRemoved p2p0
,09-09 17:17:52.854  1016  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 17:17:52.894  6743  6743 E dhcpcd  : wlan0: send_raw_packet: No such file or directory
,09-09 17:17:53.024  1016  6741 D NetUtils: dhcp_do_request failed : wlan0 (new)
09-09 17:17:53.024  1016  6741 E DhcpStateMachine: DHCP failed on wlan0: DHCP result was failed
,09-09 17:17:53.644  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 17:17:53.834   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:17:54.084  1016  1489 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 17:17:54.084  1016  1489 D BatteryService: level:75, scale:100, status:2, health:2, present:true, voltage: 4033, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 17:17:54.084  1016  1489 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 17:17:54.084  1016  1489 D BatteryService: stay LED for charging
,09-09 17:17:54.084  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 17:17:54.084  6182  6235 D BluetoothAdapter: enable()
,09-09 17:17:54.084  1016  1016 I MotionRecognitionService: Plugged
,09-09 17:17:54.084  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 17:17:54.094  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-09 17:17:54.094  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 17:17:54.094  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-09 17:17:54.094  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 75
,09-09 17:17:54.104  1016  3139 W ActivityManager: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:17:54.114  1016  3139 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 17:17:54.114  1016  3139 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:17:54.114  1016  3139 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 17:17:54.114  1016  3139 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-09 17:17:54.114  1016  3139 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-09 17:17:54.114  1016  3139 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-09 17:17:54.114  1016  3139 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 17:17:54.114  1016  3139 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:17:54.114  1016  3139 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:17:54.124  1016  3139 D SettingsProvider: name = bluetooth_on,
,09-09 17:17:54.124  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-09 17:17:54.124  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:17:54.124  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:17:54.124  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:17:54.124  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:17:54.124  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-09 17:17:54.124  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-09 17:17:54.154  6407  6407 D BluetoothAdapterState: make
,09-09 17:17:54.164  6407  6407 I bluedroid: init
,09-09 17:17:54.164  6407  6779 I BluetoothAdapterState: Entering OffState,
09-09 17:17:54.164  6407  6407 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 17:17:54.164  6407  6407 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 17:17:54.174  6407  6407 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 17:17:54.174  6407  6407 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 17:17:54.174  6407  6407 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-09 17:17:54.174  6407  6407 I bluedroid: get_profile_interface socket
09-09 17:17:54.174  6407  6407 I bluedroid: get_profile_interface map_client,
,09-09 17:17:54.174  6407  6782 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-09 17:17:54.174  6407  6407 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-09 17:17:54.174  6407  6782 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-09 17:17:54.174  6407  6782 E BluetoothServiceJni: populateRssiValuesNative
09-09 17:17:54.174  6407  6782 I bluedroid: getModelRssiValues
09-09 17:17:54.174  6407  6782 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 17:17:54.174  6407  6782 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 17:17:54.184  6407  6782 D BluetoothAdapterProperties: Name is: A5-1
,09-09 17:17:54.184  1016  1016 D SettingsProvider: name = bluetooth_name,
,09-09 17:17:54.184  6407  6407 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:54.184  1016  3269 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:17:54.184  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:54.184  1016  3269 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:54.184  1016  3269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.184  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:54.184  6407  6419 I bluedroid: config_hci_snoop_log
,09-09 17:17:54.184  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-09 17:17:54.194  1016  1046 D BluetoothManagerService: Ble is always on enable gatt
,09-09 17:17:54.194  1016  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
09-09 17:17:54.194  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-09 17:17:54.194  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 17:17:54.194  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:17:54.194  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:17:54.194  6407  6407 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-09 17:17:54.204  1016  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 17:17:54.214  6407  6779 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 17:17:54.214  6407  6779 D BluetoothAdapterProperties: Setting state to 11
,09-09 17:17:54.214  6407  6779 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-09 17:17:54.214  6407  6779 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 17:17:54.214  6407  6779 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 17:17:54.214  6407  6779 D BluetoothAdapterService: Autoconnection is available 
09-09 17:17:54.214  6407  6779 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-09 17:17:54.214  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:54.214  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,09-09 17:17:54.214  6407  6779 D BluetoothSecureManager: getInstant: null
09-09 17:17:54.214  6407  6779 D BluetoothSecureManager: calling getMethod for getService
09-09 17:17:54.214  6407  6779 D BluetoothSecureManager: calling getService
,09-09 17:17:54.214  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 17:17:54.224  6407  6779 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1d0dd1c5
09-09 17:17:54.224  1016  3273 D BluetoothSecureManagerService: isSecureModeEnabled
09-09 17:17:54.224  1016  3273 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-09 17:17:54.224  6407  6779 D BtConfig.SecureMode: isSecureModeOn:false
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService,
09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 17:17:54.224  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 17:17:54.224  6407  6779 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-09 17:17:54.234  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:17:54.234  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:54.234  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-09 17:17:54.234  6407  6779 D BluetoothBondStateMachine: make
,09-09 17:17:54.234  1795  1795 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:54.234  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:54.244  1016  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:54.244  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 17:17:54.244  1016  3269 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:54.244  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 17:17:54.244  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-09 17:17:54.244  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-09 17:17:54.244  6407  6783 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 17:17:54.244  1016  1389 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:17:54.244  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 17:17:54.244  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 17:17:54.244  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.244  1016  3269 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:54.244  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:54.244  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:54.244  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:54.244  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 17:17:54.244  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:54.254  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:54.254  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-09 17:17:54.254  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.254  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.254  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:54.254  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 17:17:54.254  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 17:17:54.254  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 17:17:54.254  6407  6407 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:17:54.254  6407  6407 D BtGatt.GattService: Received start request. Starting profile...
09-09 17:17:54.254  6407  6407 D BtGatt.GattService: start()
09-09 17:17:54.254  6407  6407 D BtGatt.GattService: start()
09-09 17:17:54.254  6407  6407 I bluedroid: get_profile_interface gatt
,09-09 17:17:54.254  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
09-09 17:17:54.254  6407  6407 D BtGatt.AdvertiseManager: advertise manager created
,09-09 17:17:54.254  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:54.254  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:54.264  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 17:17:54.264  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.264  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.264  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:54.264  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-09 17:17:54.264  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:17:54.264  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 17:17:54.274  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:54.274  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 17:17:54.274  1016  3139 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:54.274  1016  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:54.274  1016  3139 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:54.274  1016  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.274  1016  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:54.284  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-09 17:17:54.284  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 17:17:54.284  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 17:17:54.284  1016  3058 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:54.284  1016  3058 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:17:54.284  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:54.284  1016  3058 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.284  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:54.284  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-09 17:17:54.284  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 17:17:54.284  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 17:17:54.294  6407  6407 D BtGatt.GattService: mStartError = false
09-09 17:17:54.294  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:54.294  1016  3058 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:54.294  1016  3058 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 17:17:54.294  6407  6407 D HeadsetService: Received start request. Starting profile...
,09-09 17:17:54.294  6407  6407 D HeadsetService: start()
09-09 17:17:54.294  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.294  1016  3058 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:54.294  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:54.304  6407  6407 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 17:17:54.304  6407  6407 D HeadsetStateMachine: make
,09-09 17:17:54.304  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 17:17:54.304  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 17:17:54.304  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 17:17:54.304  1016  3269 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:54.304  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:54.304  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.304  1016  3269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.304  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:54.304  6407  6407 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 17:17:54.304  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 17:17:54.304  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:54.304  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:54.304  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:54.304  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-09 17:17:54.304  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.304  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.304  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 17:17:54.314  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 17:17:54.314  1016  1389 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:54.314  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 17:17:54.314  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.314  1016  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.314  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:54.314  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:54.314  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 17:17:54.314  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 17:17:54.314  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 17:17:54.314  6407  6779 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 17:17:54.314  6407  6779 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 17:17:54.314  1016  3139 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-09 17:17:54.314  1016  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 17:17:54.314  1016  3139 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.314  1016  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.314  1016  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 17:17:54.314  1016  3138 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 17:17:54.314  1016  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
09-09 17:17:54.314  1016  3138 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:54.314  1016  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:54.314  1016  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 17:17:54.314  6407  6407 I bluedroid: get_profile_interface handsfree
,09-09 17:17:54.334  6407  6407 I DualScoManager: Instantiating Dual Sco Manager
09-09 17:17:54.334  6407  6407 I DualScoManager: Set HeadsetServiceHelper
09-09 17:17:54.334  6407  6407 D BluetoothAtMessage: createCMTIContentObservers
,09-09 17:17:54.334  1016  3058 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-09 17:17:54.334  1016  3058 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:54.334  1016  3058 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 17:17:54.334  1016  3058 D SettingsProvider: selectionArgs: false
09-09 17:17:54.334  1016  3058 D SettingsProvider: selectionArgs: 1002
09-09 17:17:54.334  1016  3058 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:54.334  1016  3058 D SettingsProvider: ret = -1
,09-09 17:17:54.334  6407  6790 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 17:17:54.344  6407  6407 D HeadsetService: mStartError = false
09-09 17:17:54.344  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:54.344  6407  6407 D A2dpService: Received start request. Starting profile...
,09-09 17:17:54.344  6407  6407 D A2dpService: start()
,09-09 17:17:54.344  6407  6407 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 17:17:54.344  6407  6790 D HeadsetStateMachine: Clear mHeadsetBrsf
09-09 17:17:54.344  6407  6790 D HeadsetStateMachine: map size, before remove : 0
09-09 17:17:54.344  6407  6790 D HeadsetStateMachine: map size, after remove: 0
,09-09 17:17:54.344  6407  6407 I bluedroid: get_profile_interface avrcp
,09-09 17:17:54.354  6407  6407 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:17:54.364  6407  6407 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 17:17:54.364  6407  6792 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 17:17:54.364  6407  6407 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 17:17:54.364  6407  6407 D A2dpStateMachine: make
,09-09 17:17:54.364  6407  6407 I bluedroid: get_profile_interface a2dp
09-09 17:17:54.364  6407  6794 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-09 17:17:54.364  6407  6407 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 17:17:54.374  6407  6407 D A2dpService: mStartError = false
09-09 17:17:54.374  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:54.374  6407  6407 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 17:17:54.374  6407  6793 D A2dpStateMachine: Enter Disconnected: -2
,09-09 17:17:54.374  6407  6407 D HidService: Received start request. Starting profile...
09-09 17:17:54.374  6407  6407 D HidService: start()
09-09 17:17:54.374  6407  6407 I bluedroid: get_profile_interface hidhost
09-09 17:17:54.374  6407  6407 D HidService: setHidService(): set to: null
09-09 17:17:54.374  6407  6407 D HidService: mStartError = false
09-09 17:17:54.374  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:54.374  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-09 17:17:54.374  6407  6407 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 17:17:54.384  6407  6407 D HealthService: Received start request. Starting profile...
09-09 17:17:54.384  6407  6407 D HealthService: start()
,09-09 17:17:54.384  6407  6407 I bluedroid: get_profile_interface health,
09-09 17:17:54.384  6407  6407 D HealthService: mStartError = false
09-09 17:17:54.384  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
09-09 17:17:54.384  6407  6407 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 17:17:54.384  6407  6407 D PanService: Received start request. Starting profile...
09-09 17:17:54.384  6407  6407 D PanService: start()
09-09 17:17:54.384  6407  6407 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 17:17:54.384  6407  6407 I bluedroid: get_profile_interface pan
,09-09 17:17:54.384  6407  6407 D PanService: mStartError = false
09-09 17:17:54.384  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:54.394  6407  6407 D BluetoothMapService: Received start request. Starting profile...
09-09 17:17:54.394  6407  6407 D BluetoothMapService: start()
,09-09 17:17:54.394  1925  1925 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:54.394  6407  6407 D BluetoothMapService: mStartError = false
09-09 17:17:54.394  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:54.404  6407  6407 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-09 17:17:54.404  6407  6792 D BluetoothMediaBrowser: no now playing list
09-09 17:17:54.404  6407  6792 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-09 17:17:54.404  6407  6407 D SapService: Received start request. Starting profile...
09-09 17:17:54.404  6407  6407 D SapService: start()
09-09 17:17:54.404  6407  6407 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 17:17:54.404  6407  6407 I bluedroid: get_profile_interface sap
09-09 17:17:54.404  6407  6407 D SapService: mStartError = false
09-09 17:17:54.404  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
09-09 17:17:54.404  6407  6407 D HeadsetStateMachine: Try to query the phonestate on bind
,09-09 17:17:54.404  1431  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 17:17:54.414  1925  1925 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 17:17:54.414  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-09 17:17:54.414  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-09 17:17:54.414  1431  1446 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 17:17:54.414  6407  6407 D HeadsetStateMachine: Proxy object connected
,09-09 17:17:54.414  6407  6407 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-09 17:17:54.414  6407  6407 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-09 17:17:54.414  6407  6407 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-09 17:17:54.414  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-09 17:17:54.414  6407  6407 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 17:17:54.414  6407  6790 D HeadsetStateMachine: Disconnected process message: 11
09-09 17:17:54.414  6407  6407 D BluetoothA2dp: Proxy object connected
09-09 17:17:54.414  6407  6407 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-09 17:17:54.414  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 17:17:54.414  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 17:17:54.414  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 17:17:54.414  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-09 17:17:54.414  6407  6790 D HeadsetStateMachine: Disconnected process message: 18
,09-09 17:17:54.414  6407  6790 D HeadsetStateMachine: Disconnected process message: 10
09-09 17:17:54.414  6407  6790 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-09 17:17:54.414  6407  6790 D HeadsetStateMachine: Disconnected process message: 11
,09-09 17:17:54.444  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 17:17:54.454  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true,
,09-09 17:17:54.454  6407  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-09 17:17:54.454  6407  6779 I bluedroid: enable
,09-09 17:17:54.454  6407  6779 I bt_hci_bdroid: init
,09-09 17:17:54.454  6407  6799 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-09 17:17:54.454  6407  6779 I bt_vendor: bt-vendor : init
09-09 17:17:54.454  6407  6779 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 17:17:54.454  6407  6779 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 17:17:54.454  6407  6779 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-09 17:17:54.454  6407  6779 D bt_userial_mct: userial_init
,09-09 17:17:54.454  6407  6779 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 17:17:54.454  6407  6779 I bt_vendor: Starting hciattach daemon
,09-09 17:17:54.454  6407  6779 I bt_vendor: try to set false
,09-09 17:17:54.464  6407  6779 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
09-09 17:17:54.464  6407  6779 I bt_vendor: Starting hciattach daemon
09-09 17:17:54.464  6407  6779 I bt_vendor: try to set true
,09-09 17:17:54.484  6803  6803 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-09 17:17:54.534  6809  6809 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-09 17:17:54.544  6810  6810 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 17:17:54.554  6812  6812 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 17:17:54.564  6813  6813 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-09 17:17:54.574  6814  6814 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 17:17:54.584  6815  6815 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-09 17:17:54.824   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 17:17:54.864  6818  6818 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-09 17:17:54.874  6819  6819 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 17:17:54.924  6407  6779 I bt_vendor: bluetooth satus is on,
09-09 17:17:54.924  6407  6801 D bt_userial_mct: userial_open(port:0)
09-09 17:17:54.924  6407  6801 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-09 17:17:54.924  6407  6801 I bt_vendor: Done intiailizing UART,
,09-09 17:17:54.924  6407  6801 I bt_vendor: Done intiailizing UART
,09-09 17:17:54.924  6407  6801 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 17:17:54.924  6407  6801 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 17:17:54.934  6407  6821 D bt_userial_mct: Entering userial_read_thread()
,09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_BNEP,
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_SAP
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_SDP
,09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 17:17:54.934  6407  6799 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-09 17:17:55.034  6407  6799 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-09 17:17:55.044  6407  6799 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa406d6e9 
,09-09 17:17:55.044  6407  6799 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa406d6e9 
,09-09 17:17:55.054  6407  6782 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-09 17:17:55.064  6407  6782 E bt-btif : Calling BTA_HhEnable
,09-09 17:17:55.064  6407  6782 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 17:17:55.064  6407  6782 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-09 17:17:55.064  6407  6782 E BluetoothServiceJni: populateRssiValuesNative
09-09 17:17:55.064  6407  6782 I bluedroid: getModelRssiValues
,09-09 17:17:55.064  6407  6782 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-09 17:17:55.064  6407  6782 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 17:17:55.064  1016  1016 D SettingsProvider: name = bluetooth_name
,09-09 17:17:55.074  6407  6782 D BluetoothAdapterProperties: Name is: A5-1
,09-09 17:17:55.074  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:55.074  6407  6782 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:17:55.074  6407  6782 D BluetoothAdapterProperties: Scan Mode:20
09-09 17:17:55.074  6407  6782 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:17:55.074  6407  6782 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-09 17:17:55.074  6407  6782 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-09 17:17:55.074  6407  6782 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-09 17:17:55.074  6407  6782 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-09 17:17:55.074  6407  6782 E bt-btif : btif_sock_init: !vhci_init
09-09 17:17:55.074  6407  6782 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-09 17:17:55.084  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 17:17:55.084  6407  6782 D IOP_DB_BT: db_open: db_open : handle 3028197392l, read 13894 bytes onto local cache,
09-09 17:17:55.084  6407  6782 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-09 17:17:55.084  6407  6782 D IOP_DB_BT: db_query: result 1
09-09 17:17:55.084  6407  6782 I         : iop_db_open: iop_db_open status 0
,09-09 17:17:55.084  6407  6782 D bte_conf: Device ID record 1 : primary
09-09 17:17:55.084  6407  6782 D bte_conf:   vendorId            = 0075
09-09 17:17:55.084  6407  6782 D bte_conf:   vendorIdSource      = 0001
09-09 17:17:55.084  6407  6782 D bte_conf:   product             = 0100
,09-09 17:17:55.084  6407  6782 D bte_conf:   version             = 0200
09-09 17:17:55.084  6407  6782 D bte_conf:   clientExecutableURL = 
09-09 17:17:55.084  6407  6782 D bte_conf:   serviceDescription  = 
09-09 17:17:55.084  6407  6782 D bte_conf:   documentationURL    = 
,09-09 17:17:55.084  6407  6782 D bte_conf: bte_load_did_conf no section named DID2.
09-09 17:17:55.084  6407  6782 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 17:17:55.084  6407  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 17:17:55.084  6407  6779 D BluetoothAdapterProperties: ScanMode =  20
,09-09 17:17:55.084  6407  6779 D BluetoothAdapterProperties: State =  11
,09-09 17:17:55.084  6407  6821 E bt_mct  : hci lib postload completed,
,09-09 17:17:55.094  1016  3138 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 17:17:55.094  6407  6779 D BluetoothAdapterProperties: Setting state to 12
09-09 17:17:55.094  6407  6779 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 17:17:55.104  6407  6782 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:17:55.104  6407  6782 D BluetoothAdapterProperties: Scan Mode:21
,09-09 17:17:55.104  6407  6782 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 17:17:55.104  1016  1028 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-09 17:17:55.104  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:17:55.104  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:17:55.104  1016  1028 D SettingsProvider: selectionArgs: false
09-09 17:17:55.104  1016  1028 D SettingsProvider: selectionArgs: 1002
,09-09 17:17:55.104  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:17:55.104  1016  1028 D SettingsProvider: ret = -1
,09-09 17:17:55.104  6407  6779 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
09-09 17:17:55.104  6407  6779 D BluetoothAdapterService: updateAdapterState state is 12
09-09 17:17:55.104  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:55.104  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:55.104  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:55.104  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:55.104  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:55.104  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:55.104  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:55.104  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:55.104  1016  3138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.104  1016  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.104  1016  3138 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.104  1016  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.104  1016  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.114  6407  6779 D BluetoothAdapterService: Autoconnection is available 
09-09 17:17:55.114  6407  6779 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 17:17:55.114  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:17:55.114  1016  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 17:17:55.114  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 17:17:55.114  6407  6779 D BluetoothAdapterService: starting service from this receiver
,09-09 17:17:55.114  1016  3269 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.114  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.114  1016  1046 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:17:55.114  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.114  1016  3269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.114  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.114  6284  6292 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.114  6284  6292 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:17:55.114  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:55.114  6407  6779 I BluetoothAdapterState: Entering On State from state = 11
,09-09 17:17:55.114  6407  6419 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.114  6407  6419 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.124  1925  2117 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:17:55.124  1925  2117 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.124  2864  2873 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.124  1016  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 17:17:55.124  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.124  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.124  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.124  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.124  2864  2873 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.134  1306  1337 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
09-09 17:17:55.134  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 17:17:55.134  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.134  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.134  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.134  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.134  1306  1337 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.134  1016  1046 D BluetoothPan: Binding service...
,09-09 17:17:55.134  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-09 17:17:55.134  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.134  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:55.134  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:55.134  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:55.134  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:55.134  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:17:55.134  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
09-09 17:17:55.134  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:55.134  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
09-09 17:17:55.134  1306  6326 D BluetoothPan: Binding service...
,09-09 17:17:55.144  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:55.144  6407  6407 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-09 17:17:55.294  1016  1046 I art     : Explicit concurrent mark sweep GC freed 67741(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.516ms total 159.557ms
09-09 17:17:55.304  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 17:17:55.304  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.304  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.304  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.304  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.304  1306  1306 D HeadsetProfile: Bluetooth service connected
,09-09 17:17:55.304  2864  2873 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:17:55.304  2864  2873 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.304  1455  2439 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.304  1455  2439 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.314  1431  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.314  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:17:55.314  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.314  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.314  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.314  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.314  1431  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.314  1306  1337 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.314  1306  1337 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.314  6407  6415 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:17:55.314  1455  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.314  1016  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:17:55.314  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.314  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.314  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.314  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.314  1455  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.314  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:17:55.314  6407  6407 I BluetoothPbapService: Handler(): got msg=1
09-09 17:17:55.314  1306  1306 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:17:55.314  1306  1306 D PanProfile: Bluetooth service connected
,09-09 17:17:55.324  2864  2880 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:17:55.324  1016  3068 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-09 17:17:55.324  2864  2880 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 17:17:55.324  1016  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:17:55.324  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.324  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.324  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.324  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.324  1306  6326 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 17:17:55.324  2864  2864 D BluetoothA2dp: Proxy object connected
,09-09 17:17:55.324  6407  6829 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 17:17:55.324  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-09 17:17:55.324  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.334  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.334  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.334  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.334  6407  6829 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 17:17:55.334  6407  6829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 17:17:55.334  1440  1475 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.334  1440  1475 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.334  1306  1319 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 17:17:55.334  1306  1319 D Bluetoothsap: Binding service...
,09-09 17:17:55.334  1306  1306 D BluetoothPbap: Proxy object connected
09-09 17:17:55.334  1306  1319 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
09-09 17:17:55.334  6407  6829 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-09 17:17:55.334  6407  6829 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:17:55.334  6407  6829 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:17:55.334  6407  6829 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31e28a59
09-09 17:17:55.334  6407  6829 D BluetoothSocket: channel: 19
09-09 17:17:55.334  6407  6829 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-09 17:17:55.334  1306  1306 D PbapServerProfile: Bluetooth service connected
,09-09 17:17:55.334  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 17:17:55.334  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.334  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.334  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.334  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.334  1306  1319 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 17:17:55.344  1431  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.344  1306  1306 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 17:17:55.344  1306  1306 D SapProfile: Bluetooth service connected
09-09 17:17:55.344  1306  1306 D Bluetoothsap: getConnectedDevices()
,09-09 17:17:55.344  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 17:17:55.344  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.344  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.344  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.344  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 17:17:55.344  1431  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.344  1016  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:17:55.344  1016  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.344  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:17:55.344  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 17:17:55.344  1016  1016 D BluetoothA2dp: Proxy object connected
09-09 17:17:55.344  1173  1888 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:17:55.344  1173  1888 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.354  1431  6828 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:17:55.354  1431  6828 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.354  1306  1337 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:17:55.354  1306  1337 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.354  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:17:55.354  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.354  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.354  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.354  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.354  1306  1306 D BluetoothA2dp: Proxy object connected
,09-09 17:17:55.354  1431  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:17:55.354  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 17:17:55.354  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:17:55.364  1306  1306 D A2dpProfile: Bluetooth service connected
09-09 17:17:55.364  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.364  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.364  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.364  1431  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:17:55.364  1306  6326 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 17:17:55.364  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-09 17:17:55.364  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.364  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.364  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.364  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.364  1306  1306 D BluetoothMap: Proxy object connected
,09-09 17:17:55.364  6182  6192 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.364  6182  6192 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:17:55.364  1306  1337 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 17:17:55.364  1306  1306 D MapProfile: Bluetooth service connected
,09-09 17:17:55.364  1306  1306 D BluetoothMap: getConnectedDevices()
,09-09 17:17:55.374  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-09 17:17:55.374  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.374  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.374  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:55.374  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.374  1016  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:17:55.374  1306  1306 D BluetoothInputDevice: Proxy object connected
09-09 17:17:55.374  1016  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:17:55.374  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 17:17:55.374  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 17:17:55.374  1306  1306 D HidProfile: Bluetooth service connected
,09-09 17:17:55.374  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.374  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
09-09 17:17:55.374  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 17:17:55.384  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-09 17:17:55.384  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:17:55.384  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:55.384  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:55.384  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:55.384  1173  1173 D BluetoothTile:  getBluetoothState : 12
,09-09 17:17:55.394  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:55.394  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@33f08c9c, true
09-09 17:17:55.394  1795  1795 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:55.394  1431  1431 D BluetoothHeadset: registerMessageListener,
,09-09 17:17:55.394  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:55.394  1016  1724 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:55.404  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:55.404  1016  1389 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-09 17:17:55.404  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:55.404  1016  3273 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:17:55.404  1016  3273 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.404  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:55.404  1016  3273 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.404  1016  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:55.404  1016  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:55.404  6407  6827 D HeadsetService: registerMessageListener
,09-09 17:17:55.404  6407  6827 D HeadsetService: registerMessageListener
,09-09 17:17:55.414  6407  6790 D HeadsetStateMachine: Disconnected process message: 70
,09-09 17:17:55.414  6407  6790 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1d72361e
09-09 17:17:55.414  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 17:17:55.414  1306  1306 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 17:17:55.414  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-09 17:17:55.414  1306  1306 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 17:17:55.414  1306  1306 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 17:17:55.414  1306  1306 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-09 17:17:55.414  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 17:17:55.414  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-09 17:17:55.414  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 17:17:55.414  6407  6830 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 17:17:55.424  6407  6790 D HeadsetStateMachine: Disconnected process message: 9
,09-09 17:17:55.424  6407  6790 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-09 17:17:55.424  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:17:55.424  1016  1389 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 17:17:55.424  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.434  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.434  1016  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.434  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:55.434  6407  6830 D BluetoothSocket: bindListen(): myUserId = 0
09-09 17:17:55.434  6407  6830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:17:55.434   282  1014 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-09 17:17:55.434   282  1014 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 17:17:55.434   282  1014 V voice   : voice_set_parameters: exit with code(-2)
09-09 17:17:55.434   282  1014 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 17:17:55.434   282  1014 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 17:17:55.434   282  1014 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 17:17:55.434   282  1014 V audio_hw_primary: adev_set_parameters: exit
09-09 17:17:55.434  6407  6790 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 17:17:55.434  6407  6830 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-09 17:17:55.434  6407  6830 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:17:55.434  6407  6830 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:17:55.434  6407  6830 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f525eff
,09-09 17:17:55.434  6407  6830 D BluetoothSocket: channel: 5
,09-09 17:17:55.444  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:55.444  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:55.454  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:55.454  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 17:17:55.464  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:55.464  6407  6407 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 17:17:55.464  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:55.464  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 17:17:55.464  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.464  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:55.464  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:55.484  1925  1925 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:55.484  1016  1724 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:17:55.484  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-09 17:17:55.484  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.484  1016  1724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:55.484  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:55.494  1016  3271 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 17:17:55.494  1925  6839 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 17:17:55.494  1925  1925 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 17:17:55.504  1016  1724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:55.504  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:55.504  1016  1724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:55.504  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:55.514  6407  6840 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 17:17:55.514  6407  6840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:17:55.514  6407  6840 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-09 17:17:55.514  6407  6840 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:17:55.514  6407  6840 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:17:55.514  6407  6840 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f7ec1b
09-09 17:17:55.514  6407  6840 D BluetoothSocket: channel: 12
09-09 17:17:55.514  6407  6840 I BtOppRfcommListener: Accept thread started.
,09-09 17:17:55.514  1016  3058 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:55.524  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:55.524  1016  3058 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:55.524  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:55.524  1925  6839 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-09 17:17:55.784   287   287 E SMD     : DCD OFF,
,09-09 17:17:55.834   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 17:17:55.864  1016  1049 I PowerManagerService: [PWL] Off : 50s ago,
09-09 17:17:55.864  1016  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-09 17:17:55.864  1016  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-09 17:17:55.864  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=10454)
09-09 17:17:55.864  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=6407, ws=null) (elapsedTime=928)
09-09 17:17:55.864  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=434),
09-09 17:17:55.864  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=431)
,09-09 17:17:55.934  1016  2734 D SSRM:n  : SIOP:: AP = 400
,09-09 17:17:56.834   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-09 17:17:57.134  6182  6235 D BluetoothAdapter: disable()
,09-09 17:17:57.134  1016  1029 D SettingsProvider: name = bluetooth_on
,09-09 17:17:57.134  6407  6779 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-09 17:17:57.134  6407  6779 D BluetoothAdapterProperties: Setting state to 13
,09-09 17:17:57.134  6407  6779 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 17:17:57.134  6407  6779 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:57.134  6407  6779 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 17:17:57.134  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:57.134  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.144  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:57.144  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:57.144  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:57.144  6407  6779 D BluetoothAdapterService: Autoconnection is available 
,09-09 17:17:57.144  6407  6779 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 17:17:57.144  6407  6779 D BluetoothAdapterService: terminating service from this receiver
,09-09 17:17:57.144  6407  6407 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-09 17:17:57.144  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 17:17:57.144  6407  6407 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3261f1b8, channel: 19, state: LISTENING
09-09 17:17:57.144  6407  6407 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3261f1b8, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31e28a59, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37aa2b91mSocket: android.net.LocalSocket@fe0eaf6 impl:android.net.LocalSocketImpl@3a9f2ef7 fd:FileDescriptor[75]
09-09 17:17:57.144  6407  6407 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fe0eaf6 impl:android.net.LocalSocketImpl@3a9f2ef7 fd:FileDescriptor[75]
09-09 17:17:57.144  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:57.144  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:57.144  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:57.154  6407  6779 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 17:17:57.154  6407  6779 D BluetoothAdapterProperties: mDiscovering is false
,09-09 17:17:57.154  1016  1305 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 17:17:57.154  6407  6779 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 17:17:57.154  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:57.154  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,09-09 17:17:57.164  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-09 17:17:57.164  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:17:57.164  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:57.164  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:17:57.164  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:57.164  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-09 17:17:57.174  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 17:17:57.174  1795  1795 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:57.174  1016  3138 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:57.174  1016  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:17:57.174  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 17:17:57.184  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:57.184  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:17:57.184  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:57.184  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:57.184  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:57.184  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:57.184  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:57.184  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:57.184  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:57.184  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:57.184  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 17:17:57.184  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:57.194  1016  3269 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:17:57.194  1016  3269 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.194  1016  3269 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:57.194  1016  3269 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:57.194  1016  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:57.194  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:57.194  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:17:57.194  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:17:57.194  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:17:57.194  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:17:57.194  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 17:17:57.194  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:17:57.194  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:17:57.194  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:17:57.194  6182  6182 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 17:17:57.194  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:17:57.204  6407  6782 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:17:57.204  6407  6782 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:17:57.204  6407  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 17:17:57.204  6407  6779 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-09 17:17:57.204  6407  6779 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-09 17:17:57.204  6407  6779 E bt-btif : cmd socket is not created
,09-09 17:17:57.204  6407  6799 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-09 17:17:57.204  6407  6799 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-09 17:17:57.204  6407  6799 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:57.204  6407  6799 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:57.204  6407  6799 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:57.204  6407  6779 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 17:17:57.204  6407  6840 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 17:17:57.214  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:57.214  6407  6407 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@207164, channel: 5, state: LISTENING
,09-09 17:17:57.224  6407  6407 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@207164, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f525eff, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7b4efcdmSocket: android.net.LocalSocket@2ea8c082 impl:android.net.LocalSocketImpl@2f0dc393 fd:FileDescriptor[77]
,09-09 17:17:57.224  6407  6407 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ea8c082 impl:android.net.LocalSocketImpl@2f0dc393 fd:FileDescriptor[77]
,09-09 17:17:57.224  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:17:57.224  1016  3138 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 17:17:57.224  6407  6407 I BtOppRfcommListener: stopping Accept Thread
09-09 17:17:57.224  6407  6407 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@11253fd0, channel: 12, state: LISTENING
,09-09 17:17:57.224  6407  6407 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@11253fd0, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f7ec1b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@112dbbc9mSocket: android.net.LocalSocket@62662ce impl:android.net.LocalSocketImpl@9c705ef fd:FileDescriptor[80]
,09-09 17:17:57.224  1016  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-09 17:17:57.224  6407  6407 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@62662ce impl:android.net.LocalSocketImpl@9c705ef fd:FileDescriptor[80]
,09-09 17:17:57.224  6407  6840 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 17:17:57.224  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:57.234  1016  3138 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:57.234  1016  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:57.234  1016  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:57.244  6407  6407 V BluetoothOppManager: cleanUp...
,09-09 17:17:57.244  1306  1306 D BluetoothPbap: Proxy object disconnected
,09-09 17:17:57.244  1306  1306 D PbapServerProfile: Bluetooth service disconnected
,09-09 17:17:57.254  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:57.254  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:57.254  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:17:57.254  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 17:17:57.274  1925  1925 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:57.284  1925  1925 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 17:17:57.404  6407  6799 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 17:17:57.404  6407  6799 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 17:17:57.404  6407  6799 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 17:17:57.414  6407  6799 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:57.414  6407  6821 I bt_userial_mct: exiting userial_read_thread
09-09 17:17:57.414  6407  6821 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 17:17:57.414  6407  6782 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 17:17:57.414  6407  6801 I bt_vendor: hw_epilog_process
,09-09 17:17:57.414  6407  6782 D bt_userial_mct: userial_close,
09-09 17:17:57.414  6407  6799 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 17:17:57.414  6407  6799 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:57.414  6407  6799 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 17:17:57.414  6407  6799 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 17:17:57.414  6407  6799 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 17:17:57.414  6407  6799 W bt-btif : ag scb idx 1 not allocated
09-09 17:17:57.414  6407  6799 W bt-btif : ag scb idx 2 not allocated
09-09 17:17:57.414  6407  6799 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 17:17:57.414  6407  6782 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-09 17:17:57.774  6407  6782 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-09 17:17:57.774  6407  6782 I bt_vendor: bluetooth satus is on
,09-09 17:17:57.774  6407  6782 I bt_vendor: bt-vendor : resetting BT status
09-09 17:17:57.774  6407  6782 I bt_vendor: Starting hciattach daemon
,09-09 17:17:57.774  6407  6782 I bt_vendor: try to set false
,09-09 17:17:57.774  6407  6782 I bt_vendor: Starting hciattach daemon,
09-09 17:17:57.774  6407  6782 I bt_vendor: try to set false
,09-09 17:17:57.774  6407  6782 I bt_vendor: cleanup
,09-09 17:17:57.774  6407  6799 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
,09-09 17:17:57.774  6407  6782 I GKI_LINUX: GKI_exit_task 0 done
,09-09 17:17:57.774  6407  6782 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-09 17:17:57.784  6407  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-09 17:17:57.784  6407  6779 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 17:17:57.784  6407  6779 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-09 17:17:57.784  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-09 17:17:57.784  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 17:17:57.784  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-09 17:17:57.784  1016  1389 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-09 17:17:57.784  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.784  1016  1389 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:57.784  1016  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:57.784  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:57.784  6407  6407 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:17:57.784  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 17:17:57.784  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 17:17:57.784  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 17:17:57.794  6407  6407 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 17:17:57.794  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:57.794  6407  6407 D BtGatt.GattService: stop()
09-09 17:17:57.794  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.794  6407  6407 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 17:17:57.794  1016  1029 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:57.794  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:57.794  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:57.794  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
09-09 17:17:57.794  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 17:17:57.794  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:17:57.794  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 17:17:57.794  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:57.794  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.794  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:57.794  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:57.794  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:57.804  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 17:17:57.804  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:57.804  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 17:17:57.804  6407  6407 D HeadsetService: Received stop request...Stopping profile...
,09-09 17:17:57.804  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:57.804  1016  3058 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:57.804  1016  3058 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.804  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:57.804  1016  3058 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:57.804  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:57.814  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 17:17:57.814  1306  1306 D HeadsetProfile: Bluetooth service disconnected
09-09 17:17:57.814  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 17:17:57.814  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:17:57.814  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 17:17:57.814  1016  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:57.814  1016  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.814  1016  1219 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:57.814  1016  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:17:57.814  1016  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:57.814  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 17:17:57.814  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 17:17:57.814  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 17:17:57.814  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:17:57.814  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.814  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:57.814  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:57.814  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:57.824  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 17:17:57.824  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:57.824  6407  6779 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:57.824  1016  3138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:57.824  1016  3138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.824  1016  3138 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:57.824  1016  3138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-09 17:17:57.824  1016  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:17:57.824  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-09 17:17:57.824  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:17:57.824  6407  6779 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 17:17:57.824  1016  1724 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:17:57.824  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.824  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:57.824  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:57.824  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:17:57.824  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 17:17:57.834  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:57.834  6407  6779 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:17:57.834  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:57.834  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 17:17:57.834  6407  6779 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:17:57.834  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-09 17:17:57.834  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:17:57.834  6407  6779 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-09 17:17:57.834  6407  6779 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-09 17:17:57.834  6407  6779 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 17:17:57.834  6407  6779 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-09 17:17:57.834  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-09 17:17:57.834  6407  6779 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-09 17:17:57.834  6407  6407 D A2dpService: Received stop request...Stopping profile...
,09-09 17:17:57.834  6407  6793 D A2dpStateMachine: Exit Disconnected: -1
,09-09 17:17:57.834  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:57.834  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-09 17:17:57.834  1016  1016 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:57.834  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-09 17:17:57.844  1306  1306 D BluetoothA2dp: Proxy object disconnected
09-09 17:17:57.844  6407  6407 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:17:57.844  1306  1306 D A2dpProfile: Bluetooth service disconnected
,09-09 17:17:57.844  6407  6407 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 17:17:57.844  2864  2864 D BluetoothA2dp: Proxy object disconnected
,09-09 17:17:57.844  6407  6407 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 17:17:57.844  6407  6407 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 17:17:57.844  6407  6407 D HidService: Received stop request...Stopping profile...
,09-09 17:17:57.844  6407  6407 D HidService: Stopping Bluetooth HidService
09-09 17:17:57.844  6407  6407 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 17:17:57.844  6407  6407 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-09 17:17:57.844  6407  6407 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 17:17:57.844  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:57.844  6407  6407 D HealthService: Received stop request...Stopping profile...
,09-09 17:17:57.844  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:57.844  1306  1306 D BluetoothInputDevice: Proxy object disconnected
09-09 17:17:57.844  1306  1306 D HidProfile: Bluetooth service disconnected
,09-09 17:17:57.854  6407  6407 D PanService: Received stop request...Stopping profile...
,09-09 17:17:57.854  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:57.854  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 17:17:57.854  6407  6407 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 17:17:57.854  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
,09-09 17:17:57.854  6407  6407 D SapService: Received stop request...Stopping profile...
,09-09 17:17:57.854  6407  6407 D SapService: Stopping Bluetooth SapService
,09-09 17:17:57.854  6407  6407 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1b2780a4
09-09 17:17:57.854  1306  1306 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 17:17:57.864  1306  1306 D PanProfile: Bluetooth service disconnected
09-09 17:17:57.864  1306  1306 D BluetoothMap: Proxy object disconnected
09-09 17:17:57.864  1306  1306 D MapProfile: Bluetooth service disconnected
,09-09 17:17:57.864  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-09 17:17:57.864  6407  6407 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 17:17:57.864  6407  6407 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 17:17:57.864  6407  6407 D BluetoothA2dp: Proxy object disconnected
,09-09 17:17:57.864  6407  6407 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-09 17:17:57.864  6407  6794 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 17:17:57.864  6407  6407 I GKI_LINUX: GKI_exit_task 2 done
,09-09 17:17:57.864  6407  6407 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 17:17:57.864  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 17:17:57.864  6407  6407 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:57.864  6407  6407 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:57.864  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 17:17:57.864  6407  6407 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:57.864  6407  6407 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
09-09 17:17:57.864  6407  6407 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 17:17:57.864  6407  6407 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 17:17:57.864  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 17:17:57.864  6407  6407 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 17:17:57.864  6407  6407 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-09 17:17:57.864  6407  6407 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 17:17:57.864  6407  6407 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 17:17:57.864  1306  1306 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 17:17:57.864  1306  1306 D SapProfile: Bluetooth service disconnected
09-09 17:17:57.864  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 17:17:57.864  6407  6407 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:17:57.864  6407  6407 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-09 17:17:57.864  6407  6407 E BluetoothAdapterService(455573668): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 17:17:57.864  6407  6407 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 17:17:57.864  6407  6407 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-09 17:17:57.864  6407  6779 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-09 17:17:57.864  6407  6779 D BluetoothAdapterProperties: Setting state to 10
09-09 17:17:57.864  6407  6779 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 17:17:57.864  6407  6779 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 17:17:57.864  6407  6779 D BluetoothAdapterService: updateAdapterState state is 10
,09-09 17:17:57.874  6284  6292 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:57.874  6284  6292 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:57.874  6407  6779 D BluetoothAdapterService: Autoconnection is available 
09-09 17:17:57.874  6407  6779 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 17:17:57.874  6407  6779 I BluetoothAdapterState: Entering OffState
,09-09 17:17:57.874  6407  6825 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:57.874  6407  6825 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:57.874  1925  2117 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:57.874  1925  2117 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:57.874  2864  2873 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:57.874  2864  2873 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:57.874  1455  1476 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:57.874  1455  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:57.874  1306  1337 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:57.874  1306  1337 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:57.874  6407  6827 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:57.874  2864  2880 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:57.874  1306  1319 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 17:17:57.884  1440  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:57.884  1440  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:57.884  1306  6326 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 17:17:57.884  1306  6326 D Bluetoothsap: Unbinding service...
,09-09 17:17:57.884  1016  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:57.884  1173  3552 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:57.884  1173  3552 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:57.884  1431  1446 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:57.884  1431  1446 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:57.884  1306  1337 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 17:17:57.884  1306  1319 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 17:17:57.884  6182  6197 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 17:17:57.884  6182  6197 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 17:17:57.884  6182  6197 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-09 17:17:57.884  6182  6197 D BluetoothLeAdvertiser: Exit stop advertising
09-09 17:17:57.884  6182  6197 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 17:17:57.884  6182  6197 D BluetoothLeScanner: Exiting stopAllScan
,09-09 17:17:57.884  1306  6326 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 17:17:57.884  1016  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 17:17:57.884  1016  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 17:17:57.894  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-09 17:17:57.894  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 17:17:57.904  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:57.904  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
09-09 17:17:57.904  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 17:17:57.904  1173  1173 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
,09-09 17:17:57.904  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:17:57.904  1173  1705 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
,09-09 17:17:57.904  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:57.904  1173  1173 D BluetoothTile:  getBluetoothState : 10
,09-09 17:17:57.904  1173  1705 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
,09-09 17:17:57.904  1173  1173 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:57.904  1173  1173 D BluetoothAdapter: 305453911: getState() :  mService = null. Returning STATE_OFF
,09-09 17:17:57.914  6407  6782 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-09 17:17:57.914  1016  3272 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:17:57.914  6407  6407 I GKI_LINUX: GKI_exit_task 1 done
09-09 17:17:57.914  6407  6407 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 17:17:57.914  1795  1795 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:17:57.914  1016  3269 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 17:17:57.914  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 17:17:57.914  6407  6407 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 17:17:57.914  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:57.914  1925  2125 D BluetoothAdapter: 500543803: getState() :  mService = null. Returning STATE_OFF
09-09 17:17:57.914  1925  2125 D BluetoothAdapter: 500543803: getState() :  mService = null. Returning STATE_OFF
,09-09 17:17:57.914  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:57.914  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:17:57.914  1016  3138 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:17:57.914  1016  3138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.914  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:17:57.924  6407  6407 I art     : System.exit called, status: 0
09-09 17:17:57.924  6407  6407 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 17:17:57.924  1016  3138 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:17:57.924  1016  3138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:57.924  1016  3138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:57.924  1016  3068 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 17:17:57.924  1016  3068 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:17:57.924  1016  3068 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:57.924  1016  3068 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:17:57.924  1016  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:17:57.934  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:17:57.934  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:17:57.944  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:17:57.944  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 17:17:58.014  1016  3068 I ActivityManager: Process com.android.bluetooth (pid 6407)(adj 0) has died(58,1099)
,09-09 17:17:58.024  1925  1925 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 17:17:58.024  1016  3271 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:17:58.024  1016  3271 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:17:58.024  1016  3271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:58.024  1016  3271 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-09 17:17:58.024  1016  3271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:58.034  1925  6855 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 17:17:58.044  1925  1925 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 17:17:58.044  1016  1724 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:17:58.054  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:17:58.054  1016  1724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:17:58.054  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:17:58.054  1925  6855 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-09 17:17:58.774   287   287 E SMD     : DCD OFF
,09-09 17:17:59.994  1016  1095 V AlarmManager: waitForAlarm result :8,
,09-09 17:18:00.134  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 17:18:00.134  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:01.774   287   287 E SMD     : DCD OFF,
,09-09 17:18:03.134  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:03.134  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14340fa3 added. We now have 6 listener(s)
09-09 17:18:03.134  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:03.134  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-09 17:18:03.134  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@320082a0 added. We now have 7 listener(s)
,09-09 17:18:03.134  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:03.134  6182  6235 I System.out: IsBluetoothEnabled,
,09-09 17:18:03.144  6182  6235 D BluetoothAdapter: disable()
,09-09 17:18:03.144  1016  3058 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-09 17:18:03.144  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:03.144  6182  6235 D BluetoothAdapter: enable()
,09-09 17:18:03.144  1016  1219 W ActivityManager: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:18:03.154  1016  1219 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 17:18:03.154  1016  1219 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:18:03.154  1016  1219 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 17:18:03.154  1016  1219 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-09 17:18:03.154  1016  1219 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-09 17:18:03.154  1016  1219 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-09 17:18:03.154  1016  1219 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 17:18:03.154  1016  1219 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:18:03.154  1016  1219 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:18:03.154  1016  1219 D SettingsProvider: name = bluetooth_on
,09-09 17:18:03.154  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 17:18:03.154  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:18:03.154  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-09 17:18:03.154  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-09 17:18:03.164  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:03.164  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:03.164  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:03.164  1016  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:03.174  6861  6861 E Zygote  : MountEmulatedStorage(),
09-09 17:18:03.174  6861  6861 I libpersona: KNOX_SDCARD checking this for 1002
09-09 17:18:03.174  6861  6861 E Zygote  : v2
09-09 17:18:03.174  6861  6861 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:03.174  1016  1046 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6861 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-09 17:18:03.174  6861  6861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:18:03.184  6861  6861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:18:03.184  6861  6861 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:03.204  6861  6861 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:03.204  6861  6861 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:03.214  6861  6861 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-09 17:18:03.214  6861  6861 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 17:18:03.244  6861  6861 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding GattService
,09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding HeadsetService
09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding A2dpService
09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding HidService
,09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding HealthService
09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding PanService
09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding SapService
09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding SapClientService
09-09 17:18:03.274  6861  6861 D BtSettings.ProfileConfig: Adding HidDevService
09-09 17:18:03.274  6861  6861 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-09 17:18:03.274  1016  3068 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-09 17:18:03.274  1016  3068 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.274  1016  3068 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 17:18:03.274  1016  3068 D SettingsProvider: selectionArgs: false
09-09 17:18:03.274  1016  3068 D SettingsProvider: selectionArgs: 1002
,09-09 17:18:03.274  1016  3068 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.274  1016  3068 D SettingsProvider: ret = -1
,09-09 17:18:03.284  1016  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-09 17:18:03.284  1016  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.284  1016  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.284  1016  1029 D SettingsProvider: selectionArgs: false
09-09 17:18:03.284  1016  1029 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.284  1016  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.284  1016  1029 D SettingsProvider: ret = -1
,09-09 17:18:03.284  1016  3138 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-09 17:18:03.284  1016  3138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.284  1016  3138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.284  1016  3138 D SettingsProvider: selectionArgs: false
09-09 17:18:03.284  1016  3138 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.284  1016  3138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.284  1016  3138 D SettingsProvider: ret = -1
,09-09 17:18:03.284  1016  1389 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-09 17:18:03.284  1016  1389 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.284  1016  1389 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.284  1016  1389 D SettingsProvider: selectionArgs: false
09-09 17:18:03.284  1016  1389 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.284  1016  1389 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.284  1016  1389 D SettingsProvider: ret = -1
,09-09 17:18:03.284  1016  3271 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-09 17:18:03.284  1016  3271 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.284  1016  3271 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.284  1016  3271 D SettingsProvider: selectionArgs: false
,09-09 17:18:03.284  1016  3271 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.284  1016  3271 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 17:18:03.284  1016  3271 D SettingsProvider: ret = -1
,09-09 17:18:03.284  1016  3272 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-09 17:18:03.284  1016  3272 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.284  1016  3272 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.284  1016  3272 D SettingsProvider: selectionArgs: false
09-09 17:18:03.284  1016  3272 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.284  1016  3272 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.284  1016  3272 D SettingsProvider: ret = -1
,09-09 17:18:03.284  1016  1724 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,09-09 17:18:03.284  1016  1724 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.284  1016  1724 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.284  1016  1724 D SettingsProvider: selectionArgs: false
09-09 17:18:03.284  1016  1724 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.284  1016  1724 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.284  1016  1724 D SettingsProvider: ret = -1
,09-09 17:18:03.284  1016  3273 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-09 17:18:03.284  1016  3273 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.284  1016  3273 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 17:18:03.284  1016  3273 D SettingsProvider: selectionArgs: false
09-09 17:18:03.284  1016  3273 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.284  1016  3273 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.284  1016  3273 D SettingsProvider: ret = -1
,09-09 17:18:03.294  1016  1489 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 17:18:03.294  1016  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.294  1016  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 17:18:03.294  1016  1489 D SettingsProvider: selectionArgs: false
09-09 17:18:03.294  1016  1489 D SettingsProvider: selectionArgs: 1002
,09-09 17:18:03.294  1016  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.294  1016  1489 D SettingsProvider: ret = -1
,09-09 17:18:03.294  1016  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-09 17:18:03.294  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.294  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.294  1016  1028 D SettingsProvider: selectionArgs: false
,09-09 17:18:03.294  1016  1028 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.294  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 17:18:03.294  1016  1028 D SettingsProvider: ret = -1
,09-09 17:18:03.294  1016  3269 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-09 17:18:03.294  1016  3269 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.294  1016  3269 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 17:18:03.294  1016  3269 D SettingsProvider: selectionArgs: false
09-09 17:18:03.294  1016  3269 D SettingsProvider: selectionArgs: 1002
,09-09 17:18:03.294  1016  3269 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.294  1016  3269 D SettingsProvider: ret = -1
,09-09 17:18:03.294  1016  3058 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-09 17:18:03.294  1016  3058 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.294  1016  3058 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.294  1016  3058 D SettingsProvider: selectionArgs: false
09-09 17:18:03.294  1016  3058 D SettingsProvider: selectionArgs: 1002
09-09 17:18:03.294  1016  3058 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-09 17:18:03.294  1016  3058 D SettingsProvider: ret = -1
,09-09 17:18:03.314  6861  6861 D BluetoothAdapterState: make
,09-09 17:18:03.314  6861  6861 I bluedroid: init,
,09-09 17:18:03.314  6861  6876 I BluetoothAdapterState: Entering OffState
,09-09 17:18:03.324  6861  6861 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 17:18:03.324  6861  6861 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 17:18:03.324  6861  6861 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 17:18:03.324  6861  6861 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 17:18:03.324  6861  6861 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-09 17:18:03.324  6861  6861 I bluedroid: get_profile_interface socket
09-09 17:18:03.324  6861  6861 I bluedroid: get_profile_interface map_client
,09-09 17:18:03.324  6861  6879 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-09 17:18:03.324  6861  6861 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-09 17:18:03.324  6861  6879 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-09 17:18:03.324  6861  6879 E BluetoothServiceJni: populateRssiValuesNative
09-09 17:18:03.324  6861  6879 I bluedroid: getModelRssiValues
,09-09 17:18:03.324  6861  6879 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-09 17:18:03.324  6861  6879 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 17:18:03.334  6861  6861 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:03.334  6861  6879 D BluetoothAdapterProperties: Name is: A5-1
,09-09 17:18:03.334  1016  1016 D SettingsProvider: name = bluetooth_name
,09-09 17:18:03.334  1016  1724 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 17:18:03.334  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.334  1016  1724 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:18:03.334  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.334  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.334  6861  6869 I bluedroid: config_hci_snoop_log
,09-09 17:18:03.334  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-09 17:18:03.344  1016  1046 D BluetoothManagerService: Ble is always on enable gatt
,09-09 17:18:03.344  1016  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-09 17:18:03.344  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-09 17:18:03.344  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 17:18:03.344  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:18:03.344  6861  6861 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-09 17:18:03.344  1016  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 17:18:03.354  1016  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 17:18:03.354  6861  6876 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 17:18:03.354  6861  6876 D BluetoothAdapterProperties: Setting state to 11
,09-09 17:18:03.354  6861  6876 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 17:18:03.354  6861  6876 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 17:18:03.354  6861  6876 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 17:18:03.354  6861  6876 D BluetoothAdapterService: Autoconnection is available 
09-09 17:18:03.354  6861  6876 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-09 17:18:03.364  1016  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 17:18:03.364  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:03.364  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
09-09 17:18:03.364  6861  6876 D BluetoothSecureManager: getInstant: null
,09-09 17:18:03.364  6861  6876 D BluetoothSecureManager: calling getMethod for getService
09-09 17:18:03.364  6861  6876 D BluetoothSecureManager: calling getService
,09-09 17:18:03.374  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 17:18:03.374  6861  6876 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1fd8403c
,09-09 17:18:03.374  1016  1219 D BluetoothSecureManagerService: isSecureModeEnabled
09-09 17:18:03.374  1016  1219 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-09 17:18:03.374  6861  6876 D BtConfig.SecureMode: isSecureModeOn:false
09-09 17:18:03.374  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 17:18:03.374  6861  6876 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-09 17:18:03.374  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:03.374  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-09 17:18:03.374  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 17:18:03.374  6861  6876 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,09-09 17:18:03.374  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
09-09 17:18:03.374  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-09 17:18:03.374  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 17:18:03.374  6861  6876 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-09 17:18:03.374  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 17:18:03.374  6861  6876 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-09 17:18:03.374  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 17:18:03.374  6861  6876 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-09 17:18:03.374  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 17:18:03.374  1795  1795 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:18:03.374  1016  3139 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 17:18:03.374  6861  6876 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-09 17:18:03.374  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 17:18:03.374  6861  6876 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-09 17:18:03.374  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 17:18:03.374  1016  1724 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 17:18:03.384  6861  6876 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-09 17:18:03.384  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 17:18:03.384  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 17:18:03.384  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:03.384  6861  6876 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:03.384  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 17:18:03.384  6861  6876 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:03.384  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-09 17:18:03.384  6861  6876 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 17:18:03.384  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 17:18:03.384  6861  6876 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-09 17:18:03.384  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:03.394  1016  1252 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:18:03.394  1016  1252 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.394  1016  1252 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:03.394  1016  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:18:03.394  1016  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:03.394  6861  6876 D BluetoothBondStateMachine: make
,09-09 17:18:03.394  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 17:18:03.394  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 17:18:03.394  6861  6876 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-09 17:18:03.394  6861  6880 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 17:18:03.394  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:18:03.394  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:03.404  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-09 17:18:03.404  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:03.404  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.404  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.404  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 17:18:03.404  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 17:18:03.404  6861  6876 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 17:18:03.404  6861  6861 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 17:18:03.404  6861  6861 D BtGatt.GattService: Received start request. Starting profile...
,09-09 17:18:03.404  6861  6861 D BtGatt.GattService: start()
09-09 17:18:03.404  6861  6861 D BtGatt.GattService: start()
09-09 17:18:03.404  6861  6861 I bluedroid: get_profile_interface gatt
,09-09 17:18:03.404  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:18:03.404  6861  6861 D BtGatt.AdvertiseManager: advertise manager created
,09-09 17:18:03.414  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:03.414  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 17:18:03.414  1016  1305 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:03.414  1016  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.414  1016  1305 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:03.414  1016  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.414  1016  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.424  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 17:18:03.424  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 17:18:03.424  6861  6876 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 17:18:03.424  6861  6861 D BtGatt.GattService: mStartError = false
09-09 17:18:03.424  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:18:03.424  1016  3058 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:03.424  1016  3058 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 17:18:03.424  6861  6861 D HeadsetService: Received start request. Starting profile...
09-09 17:18:03.424  6861  6861 D HeadsetService: start()
09-09 17:18:03.424  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:03.434  1016  3058 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.434  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.434  6861  6861 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 17:18:03.434  6861  6861 D HeadsetStateMachine: make
,09-09 17:18:03.434  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 17:18:03.434  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 17:18:03.434  6861  6876 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 17:18:03.434  1016  3068 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:03.434  1016  3068 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.434  1016  3068 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:03.434  1016  3068 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.434  1016  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.434  6861  6861 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 17:18:03.434  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 17:18:03.434  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 17:18:03.434  6861  6876 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 17:18:03.444  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 17:18:03.444  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.444  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:03.444  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.444  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.444  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 17:18:03.444  1016  3058 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-09 17:18:03.444  1016  3058 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.444  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 17:18:03.444  6861  6876 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 17:18:03.444  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:03.444  1016  3058 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.444  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 17:18:03.444  1016  3058 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:03.444  1016  3058 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.444  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:03.444  1016  3058 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.444  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.454  1016  1389 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 17:18:03.454  1016  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.454  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 17:18:03.454  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 17:18:03.454  6861  6876 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 17:18:03.454  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:03.454  1016  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.454  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 17:18:03.454  1016  1305 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:03.454  1016  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.454  6861  6861 I bluedroid: get_profile_interface handsfree
,09-09 17:18:03.454  1016  1305 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:03.454  1016  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.454  1016  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.454  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 17:18:03.454  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 17:18:03.454  6861  6876 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 17:18:03.454  1016  1305 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:03.464  1016  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 17:18:03.464  1016  1305 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:03.464  1016  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:03.464  1016  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:03.464  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:03.464  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:03.464  6861  6876 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 17:18:03.464  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:03.464  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:03.464  6861  6876 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 17:18:03.464  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 17:18:03.464  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 17:18:03.464  6861  6876 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 17:18:03.464  6861  6876 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 17:18:03.464  6861  6876 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 17:18:03.464  6861  6876 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 17:18:03.464  6861  6876 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 17:18:03.474  6861  6861 I DualScoManager: Instantiating Dual Sco Manager
,09-09 17:18:03.474  6861  6861 I DualScoManager: Set HeadsetServiceHelper
,09-09 17:18:03.474  6861  6861 D BluetoothAtMessage: createCMTIContentObservers
,09-09 17:18:03.474  1016  1489 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-09 17:18:03.474  1016  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:03.474  1016  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 17:18:03.474  1016  1489 D SettingsProvider: selectionArgs: false
,09-09 17:18:03.474  1016  1489 D SettingsProvider: selectionArgs: 1002
,09-09 17:18:03.474  1016  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:03.474  1016  1489 D SettingsProvider: ret = -1
,09-09 17:18:03.474  6861  6884 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 17:18:03.484  6861  6861 D HeadsetService: mStartError = false,
09-09 17:18:03.484  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:18:03.484  6861  6861 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-09 17:18:03.484  6861  6884 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-09 17:18:03.484  6861  6884 D HeadsetStateMachine: map size, before remove : 0
09-09 17:18:03.484  6861  6884 D HeadsetStateMachine: map size, after remove: 0
,09-09 17:18:03.494  6861  6861 D A2dpService: Received start request. Starting profile...
09-09 17:18:03.494  6861  6861 D A2dpService: start()
,09-09 17:18:03.494  6861  6861 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 17:18:03.494  6861  6861 I bluedroid: get_profile_interface avrcp
,09-09 17:18:03.494  6861  6861 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 17:18:03.504  1925  1925 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:03.504  1925  1925 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 17:18:03.514  6861  6861 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 17:18:03.514  6861  6889 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 17:18:03.514  6861  6861 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-09 17:18:03.514  6861  6861 D A2dpStateMachine: make
,09-09 17:18:03.524  6861  6861 I bluedroid: get_profile_interface a2dp
,09-09 17:18:03.524  6861  6891 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 17:18:03.524  6861  6861 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 17:18:03.524  6861  6861 D A2dpService: mStartError = false
09-09 17:18:03.524  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:18:03.524  6861  6889 D BluetoothMediaBrowser: no now playing list
09-09 17:18:03.524  6861  6889 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 17:18:03.524  6861  6861 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 17:18:03.524  6861  6890 D A2dpStateMachine: Enter Disconnected: -2
,09-09 17:18:03.534  6861  6861 D HidService: Received start request. Starting profile...
,09-09 17:18:03.534  6861  6861 D HidService: start()
,09-09 17:18:03.534  6861  6861 I bluedroid: get_profile_interface hidhost
09-09 17:18:03.534  6861  6861 D HidService: setHidService(): set to: null
,09-09 17:18:03.534  6861  6861 D HidService: mStartError = false
09-09 17:18:03.534  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:18:03.534  6861  6861 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 17:18:03.534  6861  6861 D HealthService: Received start request. Starting profile...
09-09 17:18:03.534  6861  6861 D HealthService: start()
,09-09 17:18:03.534  6861  6861 I bluedroid: get_profile_interface health
,09-09 17:18:03.534  6861  6861 D HealthService: mStartError = false
09-09 17:18:03.534  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:18:03.534  6861  6861 D HeadsetStateMachine: Try to query the phonestate on bind
09-09 17:18:03.534  1431  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 17:18:03.534  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-09 17:18:03.534  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 17:18:03.534  1431  1446 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 17:18:03.544  6861  6861 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 17:18:03.544  6861  6861 D PanService: Received start request. Starting profile...
,09-09 17:18:03.544  6861  6861 D PanService: start()
09-09 17:18:03.544  6861  6861 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 17:18:03.544  6861  6861 I bluedroid: get_profile_interface pan
,09-09 17:18:03.544  6861  6861 D PanService: mStartError = false
,09-09 17:18:03.544  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:18:03.544  6861  6861 D HeadsetStateMachine: Proxy object connected
,09-09 17:18:03.544  6861  6861 D BluetoothMapService: Received start request. Starting profile...
09-09 17:18:03.544  6861  6861 D BluetoothMapService: start()
,09-09 17:18:03.554  6861  6861 D BluetoothMapService: mStartError = false
09-09 17:18:03.554  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:18:03.554  6861  6861 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-09 17:18:03.554  6861  6884 D HeadsetStateMachine: Disconnected process message: 11
09-09 17:18:03.554  6861  6861 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-09 17:18:03.554  6861  6861 D SapService: Received start request. Starting profile...
09-09 17:18:03.554  6861  6861 D SapService: start()
09-09 17:18:03.554  6861  6861 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 17:18:03.554  6861  6861 I bluedroid: get_profile_interface sap
09-09 17:18:03.554  6861  6861 D SapService: mStartError = false
09-09 17:18:03.554  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:18:03.554  6861  6861 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 17:18:03.554  6861  6884 D HeadsetStateMachine: Disconnected process message: 18
09-09 17:18:03.554  6861  6861 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-09 17:18:03.554  6861  6861 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 17:18:03.554  6861  6861 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 17:18:03.554  6861  6861 D BluetoothA2dp: Proxy object connected
09-09 17:18:03.554  6861  6861 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-09 17:18:03.554  6861  6861 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,09-09 17:18:03.554  6861  6884 D HeadsetStateMachine: Disconnected process message: 10
09-09 17:18:03.554  6861  6884 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-09 17:18:03.554  6861  6884 D HeadsetStateMachine: Disconnected process message: 11
,09-09 17:18:03.554  6861  6861 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 17:18:03.554  6861  6861 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 17:18:03.554  6861  6861 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-09 17:18:03.574  6861  6861 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 17:18:03.574  6861  6861 E BluetoothAdapterService(62724150): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 17:18:03.584  6861  6876 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-09 17:18:03.584  6861  6876 I bluedroid: enable
,09-09 17:18:03.584  6861  6876 I bt_hci_bdroid: init
,09-09 17:18:03.584  6861  6876 I bt_vendor: bt-vendor : init
,09-09 17:18:03.584  6861  6876 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 17:18:03.584  6861  6876 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-09 17:18:03.584  6861  6876 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-09 17:18:03.584  6861  6876 D bt_userial_mct: userial_init
,09-09 17:18:03.584  6861  6895 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-09 17:18:03.584  6861  6876 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 17:18:03.584  6861  6876 I bt_vendor: Starting hciattach daemon
09-09 17:18:03.584  6861  6876 I bt_vendor: try to set false
,09-09 17:18:03.584  6861  6876 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
09-09 17:18:03.584  6861  6876 I bt_vendor: Starting hciattach daemon
09-09 17:18:03.584  6861  6876 I bt_vendor: try to set true
,09-09 17:18:03.604  6899  6899 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-09 17:18:03.644  6905  6905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-09 17:18:03.654  6906  6906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 17:18:03.674  6908  6908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 17:18:03.674  6909  6909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-09 17:18:03.684  6910  6910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 17:18:03.694  6911  6911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-09 17:18:03.864  6914  6914 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-09 17:18:03.874  6915  6915 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 17:18:03.894  6861  6876 I bt_vendor: bluetooth satus is on
,09-09 17:18:03.894  6861  6897 D bt_userial_mct: userial_open(port:0)
09-09 17:18:03.894  6861  6897 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-09 17:18:03.894  6861  6897 I bt_vendor: Done intiailizing UART
,09-09 17:18:03.904  6861  6897 I bt_vendor: Done intiailizing UART,
09-09 17:18:03.904  6861  6897 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-09 17:18:03.904  6861  6897 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
09-09 17:18:03.904  6861  6917 D bt_userial_mct: Entering userial_read_thread()
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_AVDT,
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_A2D
,09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_SAP
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_SDP
,09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 17:18:03.904  6861  6895 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,
,09-09 17:18:04.014  6861  6895 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-09 17:18:04.014  6861  6895 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40736e9 
,09-09 17:18:04.014  6861  6895 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40736e9 
,09-09 17:18:04.034  6861  6879 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-09 17:18:04.034  6861  6879 E bt-btif : Calling BTA_HhEnable
,09-09 17:18:04.034  6861  6879 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 17:18:04.034  6861  6879 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-09 17:18:04.034  6861  6879 E BluetoothServiceJni: populateRssiValuesNative
,09-09 17:18:04.034  6861  6879 I bluedroid: getModelRssiValues
,09-09 17:18:04.034  6861  6879 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-09 17:18:04.034  6861  6879 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 17:18:04.044  1016  1016 D SettingsProvider: name = bluetooth_name
,09-09 17:18:04.044  6861  6879 D BluetoothAdapterProperties: Name is: A5-1
,09-09 17:18:04.044  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:04.054  6861  6879 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 17:18:04.054  6861  6879 D BluetoothAdapterProperties: Scan Mode:20
,09-09 17:18:04.054  6861  6879 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 17:18:04.054  6861  6879 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-09 17:18:04.054  6861  6879 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-09 17:18:04.054  6861  6879 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-09 17:18:04.054  6861  6879 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-09 17:18:04.054  6861  6879 E bt-btif : btif_sock_init: !vhci_init
,09-09 17:18:04.054  6861  6879 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-09 17:18:04.054  6861  6879 D IOP_DB_BT: db_open: db_open : handle 3028172816l, read 13894 bytes onto local cache,
09-09 17:18:04.054  6861  6879 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1,
09-09 17:18:04.054  6861  6879 D IOP_DB_BT: db_query: result 1
09-09 17:18:04.054  6861  6879 I         : iop_db_open: iop_db_open status 0
09-09 17:18:04.054  6861  6879 D bte_conf: Device ID record 1 : primary
09-09 17:18:04.054  6861  6879 D bte_conf:   vendorId            = 0075
09-09 17:18:04.054  6861  6879 D bte_conf:   vendorIdSource      = 0001
09-09 17:18:04.054  6861  6879 D bte_conf:   product             = 0100
09-09 17:18:04.054  6861  6879 D bte_conf:   version             = 0200
09-09 17:18:04.054  6861  6879 D bte_conf:   clientExecutableURL = 
,09-09 17:18:04.054  6861  6879 D bte_conf:   serviceDescription  = 
09-09 17:18:04.054  6861  6879 D bte_conf:   documentationURL    = 
09-09 17:18:04.054  6861  6879 D bte_conf: bte_load_did_conf no section named DID2.
09-09 17:18:04.054  6861  6879 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 17:18:04.064  6861  6876 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-09 17:18:04.064  6861  6876 D BluetoothAdapterProperties: ScanMode =  20
09-09 17:18:04.064  6861  6876 D BluetoothAdapterProperties: State =  11
09-09 17:18:04.064  1016  1305 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-09 17:18:04.064  6861  6876 D BluetoothAdapterProperties: Setting state to 12
09-09 17:18:04.064  6861  6876 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 17:18:04.064  6861  6917 E bt_mct  : hci lib postload completed
,09-09 17:18:04.064  6861  6879 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 17:18:04.064  6861  6879 D BluetoothAdapterProperties: Scan Mode:21
09-09 17:18:04.064  6861  6879 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 17:18:04.064  1016  3272 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-09 17:18:04.064  1016  3272 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 17:18:04.064  1016  3272 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 17:18:04.064  1016  3272 D SettingsProvider: selectionArgs: false
09-09 17:18:04.064  1016  3272 D SettingsProvider: selectionArgs: 1002
09-09 17:18:04.064  1016  3272 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 17:18:04.064  1016  3272 D SettingsProvider: ret = -1
,09-09 17:18:04.074  6861  6876 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 17:18:04.074  6861  6876 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 17:18:04.074  1016  3068 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:04.074  1016  3068 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.074  1016  3068 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.074  1016  3068 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.074  1016  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.084  1016  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.084  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.084  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.084  1016  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:18:04.084  6284  6294 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.084  6284  6294 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.084  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:04.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:04.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:04.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:04.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:04.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:04.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:04.084  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:04.084  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:04.094  6861  6876 D BluetoothAdapterService: Autoconnection is available 
,09-09 17:18:04.094  6861  6876 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 17:18:04.094  6861  6876 D BluetoothAdapterService: starting service from this receiver
,09-09 17:18:04.094  1016  3058 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:04.094  1016  3058 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.094  1016  3058 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.094  1016  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.094  1016  3058 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.094  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 17:18:04.094  1016  3058 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 17:18:04.094  6861  6876 I BluetoothAdapterState: Entering On State from state = 11
09-09 17:18:04.094  1925  1940 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.094  1925  1940 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:18:04.094  2864  2873 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 17:18:04.094  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.094  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:04.094  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-09 17:18:04.094  2864  2873 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:18:04.094  6861  6875 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.094  6861  6875 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:18:04.094  6861  6869 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:18:04.104  1306  6326 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.104  6861  6861 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-09 17:18:04.104  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.104  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.104  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.104  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.104  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.104  1306  1306 D HeadsetProfile: Bluetooth service connected
,09-09 17:18:04.104  1306  6326 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:18:04.114  1016  1046 D BluetoothPan: Binding service...
,09-09 17:18:04.114  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 17:18:04.114  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.114  1306  1337 D BluetoothPan: Binding service...
,09-09 17:18:04.114  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 17:18:04.114  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.114  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.114  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.114  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.114  2864  2873 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:18:04.114  2864  2873 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.124  1455  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:18:04.124  1455  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.124  1431  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.124  6861  6861 I BluetoothPbapService: Handler(): got msg=1
,09-09 17:18:04.124  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.124  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.124  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.124  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.124  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 17:18:04.124  1016  1305 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 17:18:04.124  1431  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:18:04.124  1306  1319 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:18:04.124  1306  1319 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.134  1455  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.134  1016  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.134  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.134  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.134  1016  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:18:04.134  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.134  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 17:18:04.134  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-09 17:18:04.134  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:18:04.134  1455  1476 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 17:18:04.134  2864  2880 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:18:04.134  2864  2880 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 17:18:04.134  6861  6922 V BluetoothPbapService: PBAP Service initSocket try: 0
09-09 17:18:04.134  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.134  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.134  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.134  1016  3269 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-09 17:18:04.134  2864  2864 D BluetoothA2dp: Proxy object connected
,09-09 17:18:04.134  1016  3269 D BatteryService: level:75, scale:100, status:2, health:2, present:true, voltage: 4017, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 17:18:04.134  1016  3269 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 17:18:04.134  1016  3269 D BatteryService: stay LED for charging
09-09 17:18:04.134  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 17:18:04.144  1306  1337 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 17:18:04.144  1306  1306 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 17:18:04.144  1306  1306 D PanProfile: Bluetooth service connected
,09-09 17:18:04.144  1016  1016 I MotionRecognitionService: Plugged
09-09 17:18:04.144  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 17:18:04.144  6861  6922 D BluetoothSocket: bindListen(): myUserId = 0
09-09 17:18:04.144  6861  6922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:04.144  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 17:18:04.144  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 17:18:04.144  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-09 17:18:04.144  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 75
,09-09 17:18:04.154  6861  6861 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 17:18:04.154  6861  6884 D HeadsetStateMachine: Disconnected process message: 10
09-09 17:18:04.154  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-09 17:18:04.154  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.154  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.154  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.154  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.154  1440  1475 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.154  1440  1475 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.154  1306  6326 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 17:18:04.154  1306  6326 D Bluetoothsap: Binding service...
,09-09 17:18:04.164  6861  6922 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-09 17:18:04.164  6861  6922 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:18:04.164  6861  6922 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:18:04.164  6861  6922 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@94aaba3
09-09 17:18:04.164  1306  1306 D BluetoothPbap: Proxy object connected
09-09 17:18:04.164  1306  1306 D PbapServerProfile: Bluetooth service connected
,09-09 17:18:04.164  1306  6326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
09-09 17:18:04.164  6861  6922 D BluetoothSocket: channel: 19
09-09 17:18:04.164  6861  6922 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 17:18:04.164  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 17:18:04.164  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.164  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-09 17:18:04.164  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:04.164  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.164  1306  6326 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 17:18:04.164  1431  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 17:18:04.164  1306  1306 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-09 17:18:04.164  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 17:18:04.164  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 17:18:04.164  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.164  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:18:04.164  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.164  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:18:04.164  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 17:18:04.164  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
09-09 17:18:04.164  1306  1306 D SapProfile: Bluetooth service connected
09-09 17:18:04.164  1306  1306 D Bluetoothsap: getConnectedDevices()
09-09 17:18:04.164  1431  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:18:04.164  1016  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 17:18:04.164  1016  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.174  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 17:18:04.174  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.174  1016  1016 D BluetoothA2dp: Proxy object connected
09-09 17:18:04.174  1173  1888 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.174  1173  1888 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.174  1431  1446 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.174  1431  1446 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.174  1306  1319 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 17:18:04.174  1306  1319 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.174  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:04.174  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:04.174  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:04.174  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 17:18:04.174  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:04.174  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:04.174  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:04.174  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:04.174  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 17:18:04.174  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 17:18:04.174  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.174  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.174  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.174  1306  1306 D BluetoothA2dp: Proxy object connected
09-09 17:18:04.174  1306  1306 D A2dpProfile: Bluetooth service connected
09-09 17:18:04.174  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:04.174  1431  6828 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 17:18:04.184  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:04.184  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19c48e59 added. We now have 8 listener(s)
09-09 17:18:04.184  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-09 17:18:04.184  1016  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 17:18:04.184  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 17:18:04.184  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.184  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:04.184  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.184  1431  6828 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 17:18:04.184  1306  6326 D BluetoothMap: onBluetoothStateChange: up=true
09-09 17:18:04.184  1016  3269 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 17:18:04.184  1016  3269 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:18:04.184  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-09 17:18:04.184  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-09 17:18:04.184  1016  3269 D SecContentProvider2: mCursor = null
,09-09 17:18:04.184  1016  3269 D WifiService: setWifiEnabled: false pid=6182, uid=10155
,09-09 17:18:04.184  1016  3269 D SettingsProvider: name = wifi_on
09-09 17:18:04.184  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.184  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.184  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.184  6182  6190 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 17:18:04.184  6182  6190 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 17:18:04.194  1306  6326 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 17:18:04.194  1306  1306 D BluetoothMap: Proxy object connected
09-09 17:18:04.194  1306  1306 D MapProfile: Bluetooth service connected
09-09 17:18:04.194  1306  1306 D BluetoothMap: getConnectedDevices()
,09-09 17:18:04.194  1016  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice,
,09-09 17:18:04.194  1016  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.194  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 17:18:04.194  1016  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:04.194  1016  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.194  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:04.194  1306  1306 D BluetoothInputDevice: Proxy object connected
,09-09 17:18:04.194  1016  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 17:18:04.194  1016  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 17:18:04.194  1016  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 17:18:04.194  1306  1306 D HidProfile: Bluetooth service connected
,09-09 17:18:04.194  1016  3269 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 17:18:04.194  1016  3269 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 17:18:04.194  1016  3269 D SecContentProvider2: mCursor = null
,09-09 17:18:04.204  1016  3269 D WifiService: setWifiEnabled: true pid=6182, uid=10155
,09-09 17:18:04.204  1016  3269 W ActivityManager: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 17:18:04.204  1016  3269 W WifiService: Failed getting userId using ActivityManagerNative
09-09 17:18:04.204  1016  3269 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6182, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 17:18:04.204  1016  3269 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 17:18:04.204  1016  3269 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 17:18:04.204  1016  3269 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 17:18:04.204  1016  3269 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 17:18:04.204  1016  3269 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 17:18:04.204  1016  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 17:18:04.204  1016  3269 D SettingsProvider: name = wifi_on
,09-09 17:18:04.214  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:04.214  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
09-09 17:18:04.214  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 17:18:04.214  1016  1127 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 17:18:04.214  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@4eb96a5, true,
09-09 17:18:04.224  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-09 17:18:04.224  1431  1431 D BluetoothHeadset: registerMessageListener
09-09 17:18:04.224  1795  1795 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 17:18:04.224  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 17:18:04.224  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 17:18:04.224  1173  1173 D BluetoothTile:  getBluetoothState : 12
,09-09 17:18:04.224  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:18:04.224  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:04.224  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:18:04.234  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:04.234  1173  1705 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 17:18:04.234  1016  1724 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:18:04.234  1016  3068 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:18:04.234  6861  6869 D HeadsetService: registerMessageListener
09-09 17:18:04.234  1016  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-09 17:18:04.234  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 17:18:04.244  6861  6869 D HeadsetService: registerMessageListener
,09-09 17:18:04.244  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null,
09-09 17:18:04.244  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.244  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 17:18:04.244  1016  1724 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:04.244  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0,
09-09 17:18:04.244  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:04.244  6861  6884 D HeadsetStateMachine: Disconnected process message: 70
09-09 17:18:04.244  6861  6884 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1828eea0
09-09 17:18:04.244  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 17:18:04.244  1306  1306 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-09 17:18:04.244  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-09 17:18:04.244  1306  1306 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 17:18:04.244  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-09 17:18:04.244  1306  1306 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,09-09 17:18:04.244  1306  1306 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-09 17:18:04.244  6861  6930 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 17:18:04.254  6861  6884 D HeadsetStateMachine: Disconnected process message: 9
09-09 17:18:04.254  6861  6884 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-09 17:18:04.254  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 17:18:04.254   282   696 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 17:18:04.254   282   696 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 17:18:04.254   282   696 V voice   : voice_set_parameters: exit with code(-2)
09-09 17:18:04.254   282   696 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 17:18:04.254   282   696 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 17:18:04.254   282   696 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 17:18:04.254   282   696 V audio_hw_primary: adev_set_parameters: exit
09-09 17:18:04.254  6861  6884 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 17:18:04.264  1016  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 17:18:04.264  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.264  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.264  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.264  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 17:18:04.274  6861  6930 D BluetoothSocket: bindListen(): myUserId = 0
09-09 17:18:04.274  6861  6930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:04.274  6861  6930 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-09 17:18:04.274  6861  6930 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:18:04.274  6861  6930 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 17:18:04.274  6861  6930 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31e28a59
09-09 17:18:04.274  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,09-09 17:18:04.274  6861  6930 D BluetoothSocket: channel: 5
,09-09 17:18:04.274  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 17:18:04.274  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 17:18:04.274  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 17:18:04.294  6861  6861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
09-09 17:18:04.294  6861  6861 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 17:18:04.294  1016  1305 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 17:18:04.294  1016  1305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.294  1016  1305 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.294  1016  1305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.294  1016  1305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 17:18:04.314  1925  1925 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 17:18:04.314  1016  3139 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 17:18:04.314  1016  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 17:18:04.314  1016  3139 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.314  1016  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:04.314  1016  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:04.324  1925  6937 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 17:18:04.334  1925  1925 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 17:18:04.334  1016  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 17:18:04.344  6861  6940 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 17:18:04.344  6861  6940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 17:18:04.344  6861  6940 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-09 17:18:04.344  6861  6940 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 17:18:04.344  6861  6940 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-09 17:18:04.344  6861  6940 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f7ec1b
09-09 17:18:04.344  6861  6940 D BluetoothSocket: channel: 12
09-09 17:18:04.344  6861  6940 I BtOppRfcommListener: Accept thread started.
,09-09 17:18:04.484  1016  1028 I art     : Explicit concurrent mark sweep GC freed 22074(1314KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.418ms total 146.036ms
09-09 17:18:04.484  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:18:04.484  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.484  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:04.484  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:04.494  1016  1389 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 17:18:04.494  1016  1389 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:04.494  1016  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 17:18:04.494  1016  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:04.504  1925  6937 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-09 17:18:04.574  1016  1044 D Tethering: interfaceAdded wlan0
,09-09 17:18:04.584  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 17:18:04.584  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:18:04.584  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:18:04.584  1016  1130 E Tethering: No numeric data
09-09 17:18:04.594  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:18:04.594  1016  1130 D Tethering: clearTetheredNotification()
,09-09 17:18:04.594  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:04.594  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:18:04.594  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:18:04.594  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:04.594  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 17:18:04.594  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:18:04.594  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 17:18:04.594  1016  1124 V NetworkStats: performPollLocked() took 6ms
09-09 17:18:04.604  1016  1130 D Tethering: InitialState.processMessage what=4
,09-09 17:18:04.604  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:04.604  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:04.604  1016  1044 D Tethering: interfaceAdded p2p0
,09-09 17:18:04.604  1016  1130 E Tethering: No numeric data
,09-09 17:18:04.604  1016  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 17:18:04.604  1016  1130 D Tethering: clearTetheredNotification()
,09-09 17:18:04.614  1016  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 17:18:04.614  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 17:18:04.614  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 17:18:04.614  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 17:18:04.614  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 17:18:04.614  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:18:04.614  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:04.614  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:18:04.614   277   973 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 17:18:04.624   277   973 D SoftapController: Softap fwReload - Ok
09-09 17:18:04.624  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:04.624  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:18:04.624   277   973 D CommandListener: Setting iface cfg
09-09 17:18:04.624  1016  1124 V NetworkStats: performPollLocked() took 4ms
09-09 17:18:04.624  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:04.624   277   973 D CommandListener: Trying to bring down wlan0
,09-09 17:18:04.624   277   973 D CommandListener: Clearing all IP addresses on wlan0
09-09 17:18:04.624  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:04.624  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:04.624  1016  1127 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 17:18:04.634  1016  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 17:18:04.634  1016  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-09 17:18:04.634  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:04.634  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 17:18:04.634  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:04.634  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:18:04.634  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:04.634  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:04.634  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:04.634  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:18:04.634  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-09 17:18:04.634  1173  1173 D HotspotTile: onReceive : 2, 0
09-09 17:18:04.634  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 17:18:04.644  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:18:04.644  1016  3068 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:18:04.644  1016  3068 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:04.654  1016  3068 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:04.654  1016  3068 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:04.654  1016  3068 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:18:04.654  3618  3618 I Hs20UtilService: Starting #19
09-09 17:18:04.654  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:04.654  3618  3653 I Hs20UtilService: Message received 5011
,09-09 17:18:04.654  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
09-09 17:18:04.654  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:18:04.654  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1
09-09 17:18:04.654  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:18:04.674  6948  6948 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 17:18:04.674  6948  6948 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 17:18:04.674  6948  6948 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 17:18:04.694  6948  6948 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-09 17:18:04.694   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6948
09-09 17:18:04.694   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 17:18:04.694  6948  6948 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 17:18:04.694  6948  6948 I wpa_supplicant: ssSupport state is = 1
09-09 17:18:04.694  6948  6948 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 17:18:04.694  6948  6948 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 17:18:04.694   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6948
09-09 17:18:04.694   351   351 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-09 17:18:04.774   287   287 E SMD     : DCD OFF,
,09-09 17:18:04.834   351   351 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-09 17:18:04.834  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,09-09 17:18:04.904  6948  6948 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 17:18:04.904  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 17:18:04.914  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-09 17:18:04.914   351   351 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6948
09-09 17:18:04.914   351   351 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-09 17:18:04.914  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 17:18:04.914  6948  6948 I wpa_supplicant: ssSupport state is = 1
09-09 17:18:04.914  6948  6948 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:04.914  6948  6948 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 17:18:04.914  6948  6948 E wpa_supplicant: SIM READ ERROR
09-09 17:18:04.914  6948  6948 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:04.914  6948  6948 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 17:18:04.914  6948  6948 E wpa_supplicant: SIM READ ERROR
09-09 17:18:04.914  6948  6948 I wpa_supplicant: Blacklist: Clear (all) 
09-09 17:18:04.914  6948  6948 I wpa_supplicant: wpa_default_ap_write_once
09-09 17:18:04.914  6948  6948 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-09 17:18:04.914  6948  6948 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:04.914  6948  6948 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 17:18:04.914  6948  6948 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:04.914  6948  6948 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-09 17:18:04.914  6948  6948 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:18:04.924  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 17:18:04.924  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:18:04.924  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:18:04.974  6948  6948 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 17:18:05.094  1016  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-09 17:18:05.134  6948  6948 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 17:18:05.134  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,09-09 17:18:05.154  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 17:18:05.154   351   351 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6948
,09-09 17:18:05.154   351   351 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-09 17:18:05.154  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 17:18:05.154  6948  6948 I wpa_supplicant: ssSupport state is = 1
09-09 17:18:05.154  6948  6948 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 17:18:05.154  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 17:18:05.174  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 17:18:05.174   351   351 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6948
09-09 17:18:05.174   351   351 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
,09-09 17:18:05.174  6948  6948 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 17:18:05.174  6948  6948 I wpa_supplicant: ssSupport state is = 1
,09-09 17:18:05.174  6948  6948 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 17:18:05.174  6948  6948 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 17:18:05.174  6948  6948 E wpa_supplicant: SIM READ ERROR
09-09 17:18:05.174  6948  6948 I wpa_supplicant: wpa_default_ap_write_once
,09-09 17:18:05.174  6948  6948 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
,09-09 17:18:05.174  6948  6948 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 17:18:05.184  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 17:18:05.184  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-09 17:18:05.184  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:18:05.184  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 17:18:05.184  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 17:18:05.184  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:18:05.234  6948  6948 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 17:18:05.234  6948  6948 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 17:18:05.334  6948  6948 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
09-09 17:18:05.334  6948  6948 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 17:18:05.334  6948  6948 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 17:18:05.584  1016  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 17:18:05.584  1016  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,09-09 17:18:05.584  1016  1044 D Tethering: interfaceStatusChanged p2p0, false
,09-09 17:18:05.634  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 17:18:05.644  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 17:18:05.644  6948  6948 I wpa_supplicant: HOTSPOT20_ENABLE called,
,09-09 17:18:05.644  6948  6948 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 17:18:05.644  6948  6948 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-09 17:18:05.644  6948  6948 E wpa_supplicant: SIM READ ERROR,
,09-09 17:18:05.644  6948  6948 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 17:18:05.644  6948  6948 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 17:18:05.664  1016  1127 D WifiNative-wlan0: callSECApiInt - ID [210],
09-09 17:18:05.664  6948  6948 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 17:18:05.664  1016  1127 D WifiConfigStore: Loading config and enabling all networks 
,09-09 17:18:05.664  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:05.664  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:18:05.664  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:05.664  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:05.664  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:05.664  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:05.674  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 17:18:05.674  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-09 17:18:05.674  1173  1705 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,09-09 17:18:05.674  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:18:05.674  1173  1173 D HotspotTile: onReceive : 3, 0
,09-09 17:18:05.674  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 17:18:05.684  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:05.684  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:05.684  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:05.684  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:05.684  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:05.684  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:05.684  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:05.684  6182  6182 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:05.684  1016  1127 E WifiConfigStore: Not a HS20
,09-09 17:18:05.694  1016  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 17:18:05.694  6182  6182 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:05.694  1016  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 17:18:05.694  1016  3139 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 17:18:05.694  1016  3139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:05.694  1016  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 17:18:05.694  6948  6948 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 17:18:05.694  6948  6948 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 17:18:05.694  6948  6948 I wpa_supplicant: reset timer : RESET_TIMER 0
,09-09 17:18:05.694  6948  6948 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 17:18:05.694  6948  6948 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 17:18:05.694  6948  6948 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,09-09 17:18:05.694  6948  6948 I wpa_supplicant: First Scan Start
09-09 17:18:05.694  6948  6948 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-09 17:18:05.704  1016  3139 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:05.704  1016  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:05.704  1016  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:18:05.704  3618  3618 I Hs20UtilService: Starting #20
,09-09 17:18:05.704  1016  1127 D WifiNative-wlan0: Setting external_sim to 1
,09-09 17:18:05.704  3618  3653 I Hs20UtilService: Message received 5011
,09-09 17:18:05.704  1016  1127 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 17:18:05.704  1016  1127 I WifiNative-HAL: startHal
09-09 17:18:05.704  1016  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9c66388c
09-09 17:18:05.704  1016  1127 I WifiNative-HAL: Could not start hal
,09-09 17:18:05.714  6363  6363 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 17:18:05.714  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 17:18:05.714  6388  6388 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 17:18:05.714  1016  1127 E WifiNative-wlan0: do suspend true
,09-09 17:18:05.714  6388  6388 D SecurityLogAgent: StateMachine : Current State = 1
09-09 17:18:05.714  6388  6388 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 17:18:05.714  1016  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
09-09 17:18:05.714  1016  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 17:18:05.724  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 17:18:05.724  1016  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:05.724  1016  1149 I WifiNative-HAL: startHal
09-09 17:18:05.724  1016  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9d70b9bc
09-09 17:18:05.724  1016  1149 I WifiNative-HAL: Could not start hal
09-09 17:18:05.724  1016  1149 E WifiScanningService: could not start HAL
09-09 17:18:05.724   277   973 D CommandListener: Setting iface cfg
09-09 17:18:05.724   277   973 D CommandListener: Trying to bring up p2p0
09-09 17:18:05.724  1016  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-09 17:18:05.724  1016  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 17:18:05.724  1016  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 17:18:05.724  1016  1127 E WifiNative-wlan0: invaild command id : 215
,09-09 17:18:05.724  1016  1126 D WifiP2pService: P2pEnablingState
09-09 17:18:05.724  1016  1016 D RttService: SCAN_AVAILABLE : 3
,09-09 17:18:05.724  1016  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 17:18:05.724  1016  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 17:18:05.724  1016  1126 D WifiP2pService: P2p socket connection successful
09-09 17:18:05.724  1016  1126 D WifiP2pService: P2pEnabledState
,09-09 17:18:05.724  6948  6948 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 17:18:05.734  6948  6948 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 17:18:05.734  6948  6948 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-09 17:18:05.734  1016  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 17:18:05.734  1016  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:18:05.734  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 17:18:05.734  1016  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-09 17:18:05.734  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:18:05.734  1016  1047 D WifiDisplayController: disconnect
09-09 17:18:05.734  1016  1047 D WifiDisplayController: updateConnection
09-09 17:18:05.734  1016  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 17:18:05.734  1016  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 17:18:05.734  1016  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 17:18:05.734  1016  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 17:18:05.734  1016  1127 E WifiNative-wlan0: invaild command id : 215
,09-09 17:18:05.744  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:05.744  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 17:18:05.744  1016  1127 D SecContentProvider2: mCursor = null
09-09 17:18:05.744  1016  3272 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 17:18:05.744  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 17:18:05.744  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 17:18:05.744  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:05.744  1016  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 17:18:05.744  1016  1047 D WifiDisplayAdapter: onP2pDisconnected
,09-09 17:18:05.744  1016  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 17:18:05.744  1016  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 17:18:05.754  1016  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 17:18:05.754  1016  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-09 17:18:05.754  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 17:18:05.754  1016  1126 D WifiP2pService: DeviceAddress: 7e:96:ac
09-09 17:18:05.754  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:18:05.754  1016  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  secondary type: null
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  wps: 0
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  grpcapab: 0
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  devcapab: 0
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  status: 3
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  wfdInfo: null
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  groupownerAddress: null
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  GOdeviceName: null
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  interfaceAddress: 
09-09 17:18:05.754  1016  1047 D WifiDisplayController:  SConnectInfo : null
,09-09 17:18:05.754  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:18:05.754  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:18:05.754  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 17:18:05.754  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:18:05.764  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:18:05.764  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:18:05.764  6327  6327 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 17:18:05.764  6327  6327 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 17:18:05.774  6348  6348 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 17:18:05.774  1016  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 17:18:05.774  1016  1126 D WifiP2pService: InactiveState
,09-09 17:18:05.774  1016  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-09 17:18:05.774  1016  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 17:18:05.774  6948  6948 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 17:18:05.774  1016  1126 D WifiP2pService: InactiveState{ what=143376 }
,09-09 17:18:05.774  1016  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 17:18:05.954  1016  2734 D SSRM:n  : SIOP:: AP = 380
,09-09 17:18:06.124  1016  1299 E Watchdog: !@Sync 4,
,09-09 17:18:06.214  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 17:18:06.214  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:06.214  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:06.214  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:06.214  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:06.214  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:06.214  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:06.214  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:06.224  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 17:18:06.224  6182  6235 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 17:18:06.224  6182  6235 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 17:18:06.234  6182  6235 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@20d9fae6 Bundle[{}]
,09-09 17:18:06.234  6182  6235 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 17:18:06.234  6182  6235 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 17:18:06.234  6182  6235 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 17:18:06.234  6182  6235 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 17:18:06.234  6182  6235 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 17:18:06.234  6182  6235 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 17:18:06.244  6182  6235 I System.out: Running OutgoingSocketThread
,09-09 17:18:06.244  6182  6956 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1173)
,09-09 17:18:06.254  6182  6956 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 51112
,09-09 17:18:06.254  6182  6956 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 17:18:06.834   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:18:06.834  6948  6948 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
,09-09 17:18:06.834  6948  6948 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-09 17:18:06.834  6948  6948 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 17:18:06.834  6948  6948 I wpa_supplicant: Trying to associate with  'G700',
09-09 17:18:06.834  6948  6948 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-09 17:18:06.834  6948  6948 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-09 17:18:06.844  1016  6954 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 17:18:06.854  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:06.854  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:06.954  6948  6948 E wpa_supplicant: Cmd 35605 not handled
,09-09 17:18:06.954  6948  6948 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:18:06.954  6948  6948 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-09 17:18:06.954  6948  6948 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 17:18:06.954  6948  6948 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 17:18:06.954  6948  6948 I wpa_supplicant: Associated with F4.99.3E
09-09 17:18:06.954  6948  6948 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:18:06.954  6948  6948 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 17:18:06.954  6948  6948 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:18:06.954  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 17:18:06.954  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:18:06.954  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:18:06.954  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-09 17:18:06.954  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:18:06.954  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:18:06.964  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 17:18:06.964  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 17:18:06.964  1016  1044 D Tethering: interfaceStatusChanged wlan0, false
,09-09 17:18:06.964  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-09 17:18:06.964  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 17:18:06.964  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 17:18:06.964  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 17:18:06.964  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:06.964  1016  1130 E Tethering: No numeric data
,09-09 17:18:06.964  1016  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 17:18:06.964  1016  1130 D Tethering: clearTetheredNotification()
,09-09 17:18:06.964  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
,09-09 17:18:06.974  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:06.974  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:06.974  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 17:18:06.974  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 17:18:06.974  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 17:18:06.974  6948  6948 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 17:18:06.974  6948  6948 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 17:18:06.974  6948  6948 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 17:18:06.974  1016  1124 V NetworkStats: performPollLocked() took 3ms
09-09 17:18:06.974  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:06.974  6948  6948 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:18:06.974  6948  6948 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 17:18:06.974  6948  6948 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-09 17:18:06.974  6948  6948 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-09 17:18:06.974  6948  6948 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 17:18:06.974  6948  6948 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-09 17:18:06.974  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 17:18:06.974  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:06.974  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 17:18:06.974  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 17:18:06.974  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
,09-09 17:18:06.974  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:06.974  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:06.984  1016  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 17:18:06.984  1016  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 17:18:06.984  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:18:06.984  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-09 17:18:06.984  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:06.994  1016  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 17:18:06.984  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:06.994  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:18:06.984  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:06.984  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:06.994  1016  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 17:18:06.994  1016  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:18:06.994  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 17:18:06.994  1016  1724 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-09 17:18:06.994  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:06.994  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 17:18:06.994  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 17:18:06.994  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:18:06.994  3618  3618 I Hs20UtilService: Starting #21
,09-09 17:18:06.994  3618  3653 I Hs20UtilService: Message received 5007
,09-09 17:18:07.004  1016  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-09 17:18:07.004  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 17:18:07.004  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 17:18:07.004  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:18:07.004  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 17:18:07.004  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:18:07.004  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 17:18:07.004  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:18:07.014   277   973 D CommandListener: Setting iface cfg
,09-09 17:18:07.014  1016  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,09-09 17:18:07.024  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 17:18:07.024  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:07.024  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:07.024  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:18:07.024  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.024  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.024  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.024  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:07.034  1016  1127 E WifiNative-wlan0: do suspend false
,09-09 17:18:07.034  1016  1126 D WifiP2pService: InactiveState{ what=143375 }
,09-09 17:18:07.034  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 17:18:07.034  1016  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 17:18:07.034  1016  1127 D SecContentProvider2: mCursor = null
,09-09 17:18:07.244  6959  6959 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 17:18:07.254  6182  6235 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1174)
09-09 17:18:07.254  6182  6235 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1174)
,09-09 17:18:07.254  6182  6235 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1179)
,09-09 17:18:07.254  6959  6959 I dhcpcd  : version 5.5.6 starting
,09-09 17:18:07.254  6182  6235 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 17:18:07.254  6182  6235 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1180)
,09-09 17:18:07.264  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:18:07.264  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de5ea1e added. We now have 2 listener(s)
09-09 17:18:07.264  6959  6959 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 17:18:07.274  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:18:07.274  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.274  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.274  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.274  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296e02ff added. We now have 9 listener(s)
09-09 17:18:07.274  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-09 17:18:07.274  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:07.274  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:07.284  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:07.284  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:07.284  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:07.284  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:07.284  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:07.284  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:07.284  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:07.284  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:07.294  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:07.294  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:07.294  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 17:18:07.294  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2326b715 added. We now have 3 listener(s)
,09-09 17:18:07.294  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:07.294  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:07.294  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:18:07.294  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.294  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.304  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 17:18:07.304  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32828a2a added. We now have 10 listener(s)
,09-09 17:18:07.304  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:07.304  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-09 17:18:07.304  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:07.304  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:07.304  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.304  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:07.304  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@de5ea1e removed from the list
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.304  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296e02ff removed from the list
09-09 17:18:07.304  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:07.304  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.304  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.304  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.304  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@296e02ff not in the list
09-09 17:18:07.304  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.304  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.304  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32828a2a removed from the list
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:07.304  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.304  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.304  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:07.304  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2326b715 removed from the list
09-09 17:18:07.304  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:07.304  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e29d01b added. We now have 2 listener(s)
09-09 17:18:07.314  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:18:07.314  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.314  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.314  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.314  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@151805b8 added. We now have 9 listener(s)
09-09 17:18:07.314  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:07.314  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:07.314  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:07.324  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:07.324  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:07.324  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:07.324  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:07.324  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:07.324  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:07.324  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:07.324  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:07.324  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:07.324  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:07.324  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:07.324  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c971ef6 added. We now have 3 listener(s)
,09-09 17:18:07.334  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:07.334  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:07.334  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:18:07.334  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.334  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.334  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.334  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b52f7 added. We now have 10 listener(s)
09-09 17:18:07.334  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:07.334  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:07.334  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:07.334  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:07.334  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:07.334  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 17:18:07.344  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 17:18:07.344  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:18:07.344  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:18:07.354  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-09 17:18:07.354  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:18:07.354  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:18:07.354  6861  6875 D BtGatt.GattService: registerClient() - UUID=24bf8fc0-2774-4a44-8e8c-d62b9135a861
09-09 17:18:07.354  6959  6959 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 17:18:07.354  6959  6959 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 17:18:07.354  6959  6959 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 17:18:07.354  6959  6959 I dhcpcd  : bssid match
09-09 17:18:07.354  6959  6959 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-09 17:18:07.404  6861  6879 D BtGatt.GattService: onClientRegistered() - UUID=24bf8fc0-2774-4a44-8e8c-d62b9135a861, clientIf=6
,09-09 17:18:07.404  6182  6192 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:18:07.404  6861  6869 D BtGatt.GattService: start scan with filters
,09-09 17:18:07.404  6861  6883 D BtGatt.ScanManager: handling starting scan
09-09 17:18:07.404  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:18:07.404  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:07.404  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:18:07.404  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:18:07.404  6861  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3bd1836
,09-09 17:18:07.404  6861  6879 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 17:18:07.404  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:07.404  6861  6883 D BtGatt.ScanManager: allow scan with filters
,09-09 17:18:07.414  6861  6883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 17:18:07.414  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:07.414  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:18:07.414  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:07.414  6861  6883 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-09 17:18:07.414  6861  6879 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:18:07.414  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:07.414  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:18:07.414  6861  6883 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 17:18:07.414  6861  6883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 17:18:07.424  6861  6879 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 17:18:07.424  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:07.424  6182  6235 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 17:18:07.424  6861  6879 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 17:18:07.424  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:07.434  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:07.434  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 17:18:07.434  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.434  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:18:07.434  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 17:18:07.434  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:18:07.434  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:18:07.434  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:18:07.434  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:18:07.434  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:18:07.434  6861  6875 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:18:07.434  6861  6869 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:18:07.434  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 17:18:07.434  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:07.434  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:18:07.434  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:07.434  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 17:18:07.444  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:18:07.444  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:18:07.444  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:18:07.444  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:18:07.444  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:07.444  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:18:07.444  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 17:18:07.444  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 17:18:07.444  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 17:18:07.444  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:18:07.444  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:18:07.444  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:18:07.444  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:07.454  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 17:18:07.454  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e29d01b removed from the list,
09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.454  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@151805b8 removed from the list
09-09 17:18:07.454  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:07.454  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.454  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:07.454  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.454  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@151805b8 not in the list
09-09 17:18:07.454  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.454  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 17:18:07.454  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b52f7 removed from the list
09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 17:18:07.454  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.454  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.454  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 17:18:07.454  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c971ef6 removed from the list
09-09 17:18:07.454  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:07.454  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9182793 added. We now have 2 listener(s)
,09-09 17:18:07.464  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 17:18:07.464  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.464  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.464  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.464  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a09d3d0 added. We now have 9 listener(s)
09-09 17:18:07.464  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:07.464  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:07.464  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:07.464  6861  6883 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 66
,09-09 17:18:07.474  6861  6883 D BtGatt.ScanManager: filter size is 1
,09-09 17:18:07.474  6861  6883 D BtGatt.ScanManager: delete FilterIndex - 3
,09-09 17:18:07.474  6861  6879 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 17:18:07.474  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:07.474  6861  6883 D BtGatt.ScanManager: stopping BLe Batch
,09-09 17:18:07.474  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:07.474  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:07.474  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:07.474  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:07.474  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:07.474  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:07.474  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:07.474  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:07.474  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:07.474  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:07.474  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:07.474  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ef16ce added. We now have 3 listener(s)
,09-09 17:18:07.474  6861  6879 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 17:18:07.474  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.474  6861  6883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:18:07.474  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:07.484  6861  6879 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 17:18:07.484  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:07.484  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 17:18:07.484  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.484  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.484  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.484  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@413a9ef added. We now have 10 listener(s)
,09-09 17:18:07.484  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 17:18:07.484  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:07.484  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:07.484  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:07.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:07.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:07.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:18:07.484  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:07.484  6959  6959 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
09-09 17:18:07.484  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-09 17:18:07.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 17:18:07.484  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 17:18:07.494  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 17:18:07.494  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 17:18:07.494  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 17:18:07.494  6861  6920 D BtGatt.GattService: registerClient() - UUID=65d59bf6-a933-469d-a868-adb702463221,
,09-09 17:18:07.534  6959  6959 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-09 17:18:07.534  6861  6879 D BtGatt.GattService: onClientRegistered() - UUID=65d59bf6-a933-469d-a868-adb702463221, clientIf=6
09-09 17:18:07.534  6182  6192 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 17:18:07.534  6861  6875 D BtGatt.GattService: start scan with filters
,09-09 17:18:07.534  6861  6883 D BtGatt.ScanManager: handling starting scan
,09-09 17:18:07.534  6861  6879 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 17:18:07.534  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 17:18:07.534  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:07.534  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:18:07.534  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:18:07.534  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.534  6861  6883 D BtGatt.ScanManager: allow scan with filters
09-09 17:18:07.534  6861  6883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 17:18:07.534  6861  6883 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-09 17:18:07.544  6861  6879 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-09 17:18:07.544  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:07.544  6861  6883 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:18:07.544  6861  6883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-09 17:18:07.544  6861  6879 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 17:18:07.544  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.544  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:07.544  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 17:18:07.544  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:07.544  6861  6879 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 17:18:07.544  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 17:18:07.544  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 17:18:07.554  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:07.554  6182  6235 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 17:18:07.554  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:07.554  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:07.554  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:07.554  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:07.554  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.554  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 17:18:07.554  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:07.554  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9182793 removed from the list
09-09 17:18:07.554  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.554  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a09d3d0 removed from the list
09-09 17:18:07.554  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:07.554  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:07.554  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:07.554  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 17:18:07.554  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.554  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.564  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a09d3d0 not in the list
09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:18:07.564  6861  6929 D BtGatt.GattService: stopScan() - queue size =1
09-09 17:18:07.564  6861  6920 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:18:07.564  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 17:18:07.564  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.574  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:07.574  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:07.574  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:07.574  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:18:07.574  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:07.574  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.574  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@413a9ef removed from the list
09-09 17:18:07.574  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:07.574  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.574  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.574  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:07.574  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24ef16ce removed from the list
09-09 17:18:07.574  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:07.574  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9af60b added. We now have 2 listener(s)
09-09 17:18:07.574  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:18:07.574  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.574  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.574  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.574  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12744ce8 added. We now have 9 listener(s)
09-09 17:18:07.574  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:07.574  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 17:18:07.574  6861  6883 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 67
09-09 17:18:07.574  6861  6883 D BtGatt.ScanManager: filter size is 1
09-09 17:18:07.574  6861  6883 D BtGatt.ScanManager: delete FilterIndex - 4
09-09 17:18:07.574  6861  6879 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 17:18:07.574  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.574  6861  6883 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:18:07.574  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:07.584  6861  6879 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 17:18:07.584  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.584  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:07.584  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:07.584  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:07.584  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:07.584  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:07.584  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:07.584  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:07.584  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 17:18:07.584  6861  6883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-09 17:18:07.584  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:07.584  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:07.584  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:07.584  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16a331a6 added. We now have 3 listener(s)
09-09 17:18:07.584  6861  6879 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 17:18:07.584  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.584  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:07.594  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:18:07.594  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.594  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.594  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.594  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2900e7e7 added. We now have 10 listener(s)
09-09 17:18:07.594  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:07.594  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:07.594  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 17:18:07.594  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 17:18:07.594  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 17:18:07.594  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 17:18:07.594  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 17:18:07.594  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 17:18:07.604  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 17:18:07.604  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 17:18:07.614  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 17:18:07.614  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 17:18:07.614  6182  6235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 17:18:07.624  6861  6869 D BtGatt.GattService: registerClient() - UUID=15ed9838-3796-4f91-b940-1182c9ef329b
,09-09 17:18:07.664  6861  6879 D BtGatt.GattService: onClientRegistered() - UUID=15ed9838-3796-4f91-b940-1182c9ef329b, clientIf=6
09-09 17:18:07.664  6182  6190 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-09 17:18:07.664  6861  6888 D BtGatt.GattService: start scan with filters
09-09 17:18:07.674  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-09 17:18:07.674  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 17:18:07.674  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 17:18:07.674  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 17:18:07.674  6861  6883 D BtGatt.ScanManager: handling starting scan
09-09 17:18:07.674  6861  6879 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 17:18:07.674  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.674  6861  6883 D BtGatt.ScanManager: allow scan with filters,
09-09 17:18:07.674  6861  6883 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 17:18:07.674  6861  6883 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
09-09 17:18:07.674  6861  6879 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 17:18:07.674  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.674  6861  6883 D BtGatt.ScanManager: Starting BLE batch scan
09-09 17:18:07.674  6861  6883 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,09-09 17:18:07.674  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 17:18:07.674  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 17:18:07.674  6861  6879 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 17:18:07.674  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.674  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 17:18:07.684  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
09-09 17:18:07.684  6861  6879 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 17:18:07.684  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-09 17:18:07.694  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:07.694  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:07.694  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:07.694  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.694  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 17:18:07.694  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a9af60b removed from the list
09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.694  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12744ce8 removed from the list
,09-09 17:18:07.694  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:07.694  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:07.694  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.694  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 17:18:07.694  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.694  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.694  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12744ce8 not in the list
09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 17:18:07.694  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 17:18:07.694  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 17:18:07.694  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 17:18:07.704  6861  6929 D BtGatt.GattService: stopScan() - queue size =1
,09-09 17:18:07.704  6861  6875 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 17:18:07.704  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 17:18:07.704  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 17:18:07.704  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 17:18:07.704  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 17:18:07.704  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 17:18:07.704  6861  6883 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 68
,09-09 17:18:07.704  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:18:07.704  6861  6883 D BtGatt.ScanManager: filter size is 1,
09-09 17:18:07.704  6861  6883 D BtGatt.ScanManager: delete FilterIndex - 5
09-09 17:18:07.704  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 17:18:07.704  6182  6235 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 17:18:07.704  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 17:18:07.704  6861  6879 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 17:18:07.704  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.704  6861  6883 D BtGatt.ScanManager: stopping BLe Batch
09-09 17:18:07.704  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:07.714  6861  6879 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 17:18:07.714  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.714  6861  6883 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 17:18:07.714  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:07.714  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:07.714  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.714  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2900e7e7 removed from the list
,09-09 17:18:07.714  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:07.714  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.714  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 17:18:07.714  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:07.714  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16a331a6 removed from the list
09-09 17:18:07.714  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:07.714  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33ea1b83 added. We now have 2 listener(s)
,09-09 17:18:07.714  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-09 17:18:07.714  6182  6182 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 17:18:07.714  6182  6182 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 17:18:07.714  6861  6879 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 17:18:07.714  6861  6879 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 17:18:07.714  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:18:07.714  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.714  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.714  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.714  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3961d100 added. We now have 9 listener(s)
09-09 17:18:07.714  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:07.714  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 17:18:07.724  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 17:18:07.724  6182  6235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 17:18:07.724  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 17:18:07.724  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 17:18:07.724  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 17:18:07.724  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 17:18:07.724  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 17:18:07.724  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 17:18:07.724  6182  6235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 17:18:07.724  6182  6235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 17:18:07.724  6182  6235 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 17:18:07.724  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 17:18:07.724  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b4cf7e added. We now have 3 listener(s)
,09-09 17:18:07.724  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:07.734  6182  6182 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 17:18:07.734  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 17:18:07.734  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba8ecdf added. We now have 10 listener(s)
09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 17:18:07.734  6182  6235 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 17:18:07.734  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 17:18:07.734  6182  6235 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:07.734  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:07.734  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33ea1b83 removed from the list
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.734  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3961d100 removed from the list
09-09 17:18:07.734  6182  6235 D io.jxcore.node.ConnectivityMonitor: stop
09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.734  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.734  6182  6235 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3961d100 not in the list
,09-09 17:18:07.734  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 17:18:07.734  6182  6235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ba8ecdf removed from the list
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 17:18:07.734  6182  6235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 17:18:07.734  6182  6235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 17:18:07.734  6182  6235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 17:18:07.734  6182  6235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36b4cf7e removed from the list
09-09 17:18:07.734  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 17:18:07.734  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 17:18:07.734  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 17:18:07.734  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 17:18:07.734  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 17:18:07.734  6182  6235 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 17:18:07.744  6182  6992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1187, name: My test thread name)
,09-09 17:18:07.744  6182  6992 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1187, thread name: My test thread name)
09-09 17:18:07.744  6182  6992 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 17:18:07.744  6182  6993 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1189, name: My test thread name)
,09-09 17:18:07.744  6182  6993 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1189, thread name: My test thread name)
09-09 17:18:07.744  6182  6993 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1189, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 17:18:07.744  6182  6235 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-09 17:18:07.744  6182  6235 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-09 17:18:07.744  6182  6235 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 17:18:07.744  6182  6235 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-09 17:18:07.744  6182  6235 D com.test.thalitest.ThaliTestRunner: Total duration: 23346 ms
,09-09 17:18:07.744  6182  6235 I jxcore-log: *Native tests were executed*,
09-09 17:18:07.744  6182  6235 I jxcore-log: 
09-09 17:18:07.744  6182  6235 I jxcore-log: Total number of executed tests:  80
09-09 17:18:07.744  6182  6235 I jxcore-log: 
09-09 17:18:07.744  6182  6235 I jxcore-log: Number of passed tests:  80
09-09 17:18:07.744  6182  6235 I jxcore-log: 
,09-09 17:18:07.754  6182  6235 I jxcore-log: Number of failed tests:  0
09-09 17:18:07.754  6182  6235 I jxcore-log: 
09-09 17:18:07.754  6182  6235 I jxcore-log: Number of ignored tests:  0
09-09 17:18:07.754  6182  6235 I jxcore-log: 
,09-09 17:18:07.754  6182  6235 I jxcore-log: Total duration:  23346,
09-09 17:18:07.754  6182  6235 I jxcore-log: 
09-09 17:18:07.754  6182  6235 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 17:18:07.754  6182  6235 I jxcore-log: 
,09-09 17:18:07.754  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:07.754  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6182 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.764  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:07.764  6182  6235 I jxcore-log: 
09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-09 17:18:07.774  6182  6235 I jxcore-log: 
09-09 17:18:07.774  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:07.774  6182  6235 I jxcore-log: 
,09-09 17:18:07.784  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-09 17:18:07.784  6182  6235 I jxcore-log: 
,09-09 17:18:07.784  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:07.784  6182  6235 I jxcore-log: 
09-09 17:18:07.784   287   287 E SMD     : DCD OFF
,09-09 17:18:07.784  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 17:18:07.784  6182  6235 I jxcore-log: 
,09-09 17:18:07.834   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 17:18:07.844  1016  1127 E WifiNative-wlan0: do suspend true
,09-09 17:18:07.874  1016  1126 D WifiP2pService: InactiveState{ what=143375 },
09-09 17:18:07.874  1016  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 17:18:07.874  1016  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 17:18:07.874  1016  1127 E WifiStateMachine: VerifyingLinkState enter,
,09-09 17:18:07.874  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 17:18:07.874  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:18:07.874  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:07.874  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.874  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.874  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:07.884  1016  1127 D WifiNative-wlan0: callSECApiInt - ID [210],
09-09 17:18:07.884  1016  1129 E ConnectivityService: updateNetworkInfo()
,09-09 17:18:07.884  1016  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-09 17:18:07.884  1016  1129 D ConnectivityService: Adding iface wlan0 to network 504
,09-09 17:18:07.894  1016  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-09 17:18:07.894  1016  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 17:18:07.894  1016  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 17:18:07.894  1016  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 17:18:07.894  1016  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 17:18:07.904  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 17:18:07.904  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:18:07.904  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.904  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 17:18:07.904  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.904  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 17:18:07.904  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:18:07.904  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:07.914  1016  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check,
09-09 17:18:07.914  1016  1028 W ActivityManager: userId = 0, bbcId = -10000,
09-09 17:18:07.914  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:07.914  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 17:18:07.914  3618  3618 I Hs20UtilService: Starting #22
,09-09 17:18:07.914  3618  3653 I Hs20UtilService: Message received 5007,
,09-09 17:18:07.914  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:18:07.914  1306  1306 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 17:18:07.924  1016  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
09-09 17:18:07.924  1016  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 17:18:07.924  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 17:18:07.934  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 17:18:07.934  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 17:18:07.934  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.934  1016  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-09 17:18:07.934  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 17:18:07.934  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.934  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.934  1016  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-09 17:18:07.934  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 17:18:07.934  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 17:18:07.934  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
,09-09 17:18:07.934  1016  1016 D WifiNative-wlan0: callSECApiVoid - ID [212]
09-09 17:18:07.934  1016  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-09 17:18:07.944  1016  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 17:18:07.944  1016  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-09 17:18:07.944  1016  1129 D ConnectivityService: LTETest block dns file not exists
,09-09 17:18:07.944  6182  6182 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 17:18:07.944  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:07.944  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 17:18:07.944  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.944  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:07.944  6182  6235 I jxcore-log: 
09-09 17:18:07.944  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.944  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.944  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:07.954  1016  1724 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:18:07.954  1016  1724 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:07.954  1016  1724 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:07.954  1016  1724 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:07.954  1016  1724 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:18:07.954  1016  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:18:07.954  1016  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 17:18:07.954  1016  1129 E ConnectivityService: updateNetworkInfo()
09-09 17:18:07.954  1016  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 17:18:07.954  1016  6957 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.954  1016  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-09 17:18:07.954  1016  6957 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 17:18:07.954  1016  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 17:18:07.954  1016  6957 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 17:18:07.954  1016  6957 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-09 17:18:07.954  1016  6957 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 17:18:07.964  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:18:07.964  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 17:18:07.964   277   969 D EnterpriseController: uids 1000
09-09 17:18:07.964   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 17:18:07.964   277   969 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-09 17:18:07.964  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 17:18:07.964  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 17:18:07.964  1016  1129 D ConnectivityService:    accepting network in place of null
09-09 17:18:07.964  1016  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 17:18:07.964  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 17:18:07.964  1016  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 17:18:07.964  1016  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-09 17:18:07.964  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 17:18:07.964  1016  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 17:18:07.964  3618  3618 I Hs20UtilService: Starting #23
,09-09 17:18:07.964  1016  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-09 17:18:07.964  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-09 17:18:07.974  1016  1130 D Tethering: MasterInitialState.processMessage what=3
09-09 17:18:07.974  1016  1124 V NetworkStats: updateIfacesLocked()
,09-09 17:18:07.974  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:07.974  1016  1124 V NetworkStats: performPollLocked(flags=0x1)
09-09 17:18:07.974  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 17:18:07.974  1016  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-09 17:18:07.974  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,09-09 17:18:07.974  1173  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:18:07.974  1016  1124 V NetworkStats: performPollLocked() took 3ms
09-09 17:18:07.974  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:07.974  3810  6670 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:18:07.974  3618  3653 I Hs20UtilService: Message received 5007
09-09 17:18:07.974  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-09 17:18:07.974  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 17:18:07.974  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE,
09-09 17:18:07.974  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 17:18:07.974  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 17:18:07.974  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 17:18:07.974  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 17:18:07.974  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 17:18:07.974  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 17:18:07.974  1306  3046 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 17:18:07.984  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:07.984  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:07.984  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:07.984  1016  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 17:18:07.984  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:07.984  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:07.984  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:07.984  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 17:18:07.984  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 17:18:07.984  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 17:18:07.984  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 17:18:07.984  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 17:18:07.984  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.984  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.984  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:07.984  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:07.994  1016  3271 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 17:18:07.994  1016  3271 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 17:18:07.994  1016  3271 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:07.994  1016  3271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:07.994  1016  3271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 17:18:07.994  3618  3618 I Hs20UtilService: Starting #24
,09-09 17:18:07.994  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 17:18:07.994  3618  3653 I Hs20UtilService: Message received 5007
09-09 17:18:07.994  1306  1306 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 17:18:08.004  1016  1028 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 17:18:08.004  1016  1219 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-09 17:18:08.004  1016  1219 D SecContentProvider2: mCursor = null
,09-09 17:18:08.004  1016  1305 D SecContentProvider2: uri = 15 selection = getToastGravity
09-09 17:18:08.004  1016  1305 D SecContentProvider2: mCursor = null
,09-09 17:18:08.004  1016  3272 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-09 17:18:08.004  1016  3272 D SecContentProvider2: mCursor = null
,09-09 17:18:08.004  1016  1724 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-09 17:18:08.004  1016  1724 D SecContentProvider2: mCursor = null
,09-09 17:18:08.004  1016  1029 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-09 17:18:08.004  1016  1029 D SecContentProvider2: mCursor = null
,09-09 17:18:08.004  1016  3271 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-09 17:18:08.004  1016  3271 D SecContentProvider2: mCursor = null
,09-09 17:18:08.034   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-09 17:18:08.044  1016  3138 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,09-09 17:18:08.054  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 17:18:08.064  6994  6994 D AndroidRuntime: 
09-09 17:18:08.064  6994  6994 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 17:18:08.064  6994  6994 D AndroidRuntime: CheckJNI is OFF
,09-09 17:18:08.064  6994  6994 D AndroidRuntime: readGMSProperty: start,
09-09 17:18:08.064  6994  6994 D AndroidRuntime: readGMSProperty: already setted!!
09-09 17:18:08.064  6994  6994 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 17:18:08.064  6994  6994 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,09-09 17:18:08.064  6994  6994 D AndroidRuntime: readGMSProperty: end
09-09 17:18:08.064  6994  6994 D AndroidRuntime: addProductProperty: start
,09-09 17:18:08.074  6182  6182 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-09 17:18:08.074  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:08.074  6182  6235 I jxcore-log: 
,09-09 17:18:08.154  1016  6957 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 17:18:08.194  6994  6994 E AffinityControl: AffinityControl: registerfunction enter
,09-09 17:18:08.214  6182  6182 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 17:18:08.214  6182  6235 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 17:18:08.214  6182  6235 I jxcore-log: 
,09-09 17:18:08.224  6994  6994 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 17:18:08.224  1016  6957 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 15:18:08 GMT], X-Android-Received-Millis=[1473434288235], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473434288196]}
09-09 17:18:08.224  1016  6957 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 17:18:08.224  1016  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-09 17:18:08.224  1016  6957 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-09 17:18:08.224  1016  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 17:18:08.224  1173  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
09-09 17:18:08.224  1016  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-09 17:18:08.224  3810  6670 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 17:18:08.224  1016  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-09 17:18:08.224  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: EthernetConnected: false,
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE,
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0,
09-09 17:18:08.234  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte,
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 17:18:08.234  1016  1252 D PackageManager: START PACKAGE DELETE: observer{932086317}
09-09 17:18:08.234  1016  1252 D PackageManager: pkg{<packageName>}
09-09 17:18:08.234  1016  1252 D PackageManager: user{0}
09-09 17:18:08.234  1016  1252 D PackageManager: caller{2000}
09-09 17:18:08.234  1016  1252 D PackageManager: flags{2}
09-09 17:18:08.234  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 17:18:08.234  1016  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 17:18:08.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 17:18:08.234  1016  1252 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-09 17:18:08.234  1016  1252 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-09 17:18:08.234  1016  1252 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,09-09 17:18:08.234  1016  1252 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 17:18:08.234  1016  1252 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 17:18:08.234  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-09 17:18:08.234  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
09-09 17:18:08.234  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 17:18:08.234  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 17:18:08.244  1016  1057 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,09-09 17:18:08.244  1016  1042 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
09-09 17:18:08.244  1016  1042 I ActivityManager: Killing 6182:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-09 17:18:08.244  1016  1042 I ActivityManager:   Force finishing activity ActivityRecord{3e962225 u0 com.test.thalitest/.MainActivity t128}
,09-09 17:18:08.244  1016  1042 W ActivityManager: mDVFSHelper.acquire(),
,09-09 17:18:08.354  1016  1057 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-09 17:18:08.354  1016  1057 I ActivityManager:   Force finishing activity ActivityRecord{3e962225 u0 com.test.thalitest/.MainActivity t128 f}
,09-09 17:18:08.354  1016  1057 W ActivityManager: Duplicate finish request for ActivityRecord{3e962225 u0 com.test.thalitest/.MainActivity t128 f}
,09-09 17:18:08.384  1016  1097 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
,09-09 17:18:08.384  1016  1097 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,09-09 17:18:08.384  1016  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 17:18:08.384  1016  1219 I WindowState: WIN DEATH: Window{3409035a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 17:18:08.394  1016  1219 W InputDispatcher: Attempted to unregister already unregistered input channel
09-09 17:18:08.394   257   436 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
09-09 17:18:08.394   257   438 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
09-09 17:18:08.394   257   438 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
09-09 17:18:08.394  1016  1219 D InputDispatcher: Focus left window: 6182
,09-09 17:18:08.394  1016  1042 D InputDispatcher: Focused application released
,09-09 17:18:08.404  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 17:18:08.404  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 17:18:08.404  5634  5634 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 687us total 31.007ms
,09-09 17:18:08.414  3143  3143 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-09 17:18:08.424  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-09 17:18:08.434  3810  3810 I art     : Explicit concurrent mark sweep GC freed 29357(1950KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 15MB/26MB, paused 1.332ms total 76.961ms
,09-09 17:18:08.434  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-09 17:18:08.444  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-09 17:18:08.444  3143  3143 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-09 17:18:08.454  3810  3821 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-09 17:18:08.454  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-09 17:18:08.454  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-09 17:18:08.464  3143  3143 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-09 17:18:08.464  1016  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:18:08.474  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-09 17:18:08.494  1016  3068 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,09-09 17:18:08.494  1016  3068 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-09 17:18:08.504  1016  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 17:18:08.514  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-09 17:18:08.514  1795  1795 E SamsungIME: mOCRHelper is null
09-09 17:18:08.514  1925  2115 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 17:18:08.524  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-09 17:18:08.524  1016  1124 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-09 17:18:08.524  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:08.524  1016  1124 V NetworkStats: performPollLocked(flags=0x3)
,09-09 17:18:08.534  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 17:18:08.534  1016  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 17:18:08.534  1016  1124 V NetworkStats: performPollLocked() took 6ms
,09-09 17:18:08.534  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 17:18:08.544  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-09 17:18:08.544  3143  3143 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-09 17:18:08.544  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-09 17:18:08.544  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-09 17:18:08.564  1016  1016 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,09-09 17:18:08.564  1016  3139 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 17:18:08.564  1016  3139 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 17:18:08.564  1016  3139 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 17:18:08.574  3143  3143 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-09 17:18:08.584   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-09 17:18:08.594  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,09-09 17:18:08.594  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 17:18:08.594  6427  6427 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 17:18:08.604  1440  1440 D RegisteredServicesCache: empty dynamic service
,09-09 17:18:08.604  3655  3655 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 17:18:08 GMT+02:00 2016
,09-09 17:18:08.634  1016  1489 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 17:18:08.634  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 17:18:08.634  1016  3068 D InputDispatcher: Focus entered window: 3143
09-09 17:18:08.634  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 17:18:08.634  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 17:18:08.634  3143  3143 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 17:18:08.634  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:08.634  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:08.634  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 17:18:08.644  3143  3143 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-09 17:18:08.654  3655  3655 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 17:18:08.654  1016  1389 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
09-09 17:18:08.654  1016  1389 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 17:18:08.654  1016  1389 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 17:18:08.654  1016  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:08.654  1016  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:08.654  1016  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.654  1016  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:08.664  1016  3272 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 17:18:08.664  1016  3272 D SecContentProvider2: mCursor = null
09-09 17:18:08.664  3655  3655 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
09-09 17:18:08.674  7017  7017 E Zygote  : MountEmulatedStorage()
09-09 17:18:08.674  7017  7017 E Zygote  : v2
09-09 17:18:08.674  7017  7017 I libpersona: KNOX_SDCARD checking this for 10094
09-09 17:18:08.674  7017  7017 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:08.674  7017  7017 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:18:08.674  1016  1389 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7017 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
09-09 17:18:08.674  7017  7017 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:18:08.674  7017  7017 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:08.684  3143  3143 V ActivityThread: updateVisibility : ActivityRecord{3e86cb5a token=android.os.BinderProxy@29202939 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-09 17:18:08.684  3655  3655 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 17:18:08.694  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:08.694  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 17:18:08.694   302   302 I art     : Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 26.007ms
,09-09 17:18:08.704  1016  1057 I art     : Explicit concurrent mark sweep GC freed 58986(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 28MB/43MB, paused 23.359ms total 298.052ms
,09-09 17:18:08.704  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,09-09 17:18:08.714  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-09 17:18:08.714  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.714  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.714  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.714  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.714  3655  3655 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 17:18:08.714  7017  7017 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:08.724  7017  7017 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:08.724  3655  7016 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 17:18:08.724   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 23.142ms
,09-09 17:18:08.734  3655  7016 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
09-09 17:18:08.734  3655  7016 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 17:18:08.734  3655  7016 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-09 17:18:08.734   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 16.905ms
,09-09 17:18:08.754  1016  1057 D PackageManager: delete codoeFile: 
,09-09 17:18:08.764  1016  1057 I AASA_removePackage: UID=10155 Target=com.test.thalitest
09-09 17:18:08.764  1016  1057 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
09-09 17:18:08.764  1016  1057 D PackageManager: result of delete: 1{932086317}
,09-09 17:18:08.764  7032  7032 E Zygote  : MountEmulatedStorage()
09-09 17:18:08.764  7032  7032 I libpersona: KNOX_SDCARD checking this for 10044
09-09 17:18:08.764  7032  7032 E Zygote  : v2
09-09 17:18:08.764  7032  7032 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:08.764  7032  7032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:18:08.764  1016  3068 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 17:18:08.764  7032  7032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:18:08.764  1016  7034 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 17:18:08.764  6994  6994 D AndroidRuntime: Shutting down VM
09-09 17:18:08.764  7032  7032 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:08.774  1016  3068 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6182 uid 10155
09-09 17:18:08.774  1016  1042 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7032 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-09 17:18:08.774  3143  3143 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29202939 time:140837
,09-09 17:18:08.784  1795  1795 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-09 17:18:08.784  1016  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
09-09 17:18:08.784  1016  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-09 17:18:08.784  7032  7032 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:18:08.784  7032  7032 D ActivityThread: Added TimaKeyStore provider
09-09 17:18:08.784  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
09-09 17:18:08.784  1016  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 17:18:08.784  1016  1057 D PackageManager: userId{-1}
09-09 17:18:08.784  1016  1057 D PackageManager: andCode{true}
,09-09 17:18:08.784  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.784  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.784  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.784  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:08.794  1016  1041 W TextServicesManagerService: no available spell checker services found
,09-09 17:18:08.804  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,09-09 17:18:08.804  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-09 17:18:08.804  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 17:18:08.804  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-09 17:18:08.804  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-09 17:18:08.804  1016  1016 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-09 17:18:08.804  3655  7016 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
09-09 17:18:08.804  7049  7049 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:18:08.804  7049  7049 E Zygote  : MountEmulatedStorage()
09-09 17:18:08.804  7049  7049 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:08.804  7049  7049 E Zygote  : v2
09-09 17:18:08.804  1016  1016 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-09 17:18:08.804  7049  7049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 17:18:08.804  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:08.814  7049  7049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:18:08.814  1016  1042 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=7049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 17:18:08.814  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 17:18:08.814  7049  7049 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 17:18:08.814  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-09 17:18:08.814  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
09-09 17:18:08.814  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 17:18:08.814  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-09 17:18:08.814  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.814  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.814  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.814  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:08.814  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 17:18:08.814  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 17:18:08.814  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 17:18:08.814  1016  1016 V EnterpriseBillingPolicy: uID is 10155
09-09 17:18:08.814  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 17:18:08.814  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 17:18:08.814  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 17:18:08.814  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 17:18:08.814  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 17:18:08.814  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 17:18:08.824  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 17:18:08.824  3655  7016 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-09 17:18:08.824  3655  7016 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-09 17:18:08.834  7061  7061 E Zygote  : MountEmulatedStorage()
09-09 17:18:08.834  7061  7061 E Zygote  : v2
09-09 17:18:08.834  7061  7061 I libpersona: KNOX_SDCARD checking this for 10149
09-09 17:18:08.834  7061  7061 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:08.834  7061  7061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:18:08.844   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 17:18:08.844  7061  7061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:18:08.844  7061  7061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:08.844  1016  1042 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7061 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 17:18:08.844  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,09-09 17:18:08.844  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{cb7f5c6 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:140908
09-09 17:18:08.844  1016  1047 W ActivityManager: mDVFSHelper.release()
,09-09 17:18:08.854  7049  7049 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:08.854  7049  7049 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:08.864  1016  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 17:18:08.864  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 17:18:08.874  1016  2734 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicy: uID is 10155
09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 17:18:08.874  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 17:18:08.884  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 17:18:08.884  7061  7061 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:08.884  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 17:18:08.884  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 17:18:08.884  1016  1016 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-09 17:18:08.884  1925  1925 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
09-09 17:18:08.884  1173  1173 D PanelView: There is/are notification(s) 
,09-09 17:18:08.894  7032  7032 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 17:18:08.894  7032  7032 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:18:08.894  7032  7032 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 17:18:08.894  7032  7032 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 17:18:08.894  7032  7032 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-09 17:18:08.894  7032  7032 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 17:18:08.894  7032  7032 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 17:18:08.894  7032  7032 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 17:18:08.914  1173  1173 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-09 17:18:08.914  3655  3655 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
09-09 17:18:08.914  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
09-09 17:18:08.914  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
09-09 17:18:08.914  1173  1173 D PanelView: There is/are notification(s) 
09-09 17:18:08.914  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-09 17:18:08.914  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
,09-09 17:18:08.924  1173  1173 D PanelView: There is/are notification(s) 
,09-09 17:18:08.924  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-09 17:18:08.924  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-09 17:18:08.924  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-09 17:18:08.944  1016  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 17:18:08.954  7049  7049 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 17:18:08.954  1016  1489 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 17:18:08.954  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-09 17:18:08.964  7017  7017 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-09 17:18:08.964  7017  7017 D elm:15183: ELMEngine.ELMEngine( context ).
,09-09 17:18:08.964  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:08.964  7017  7017 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-09 17:18:08.964  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:08.964  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-09 17:18:08.964  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 17:18:08.974  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 17:18:08.974  1016  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-09 17:18:08.974  1016  3273 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-09 17:18:08.974  1016  3273 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-09 17:18:08.974  1016  3273 W ActivityManager: userId = 0, bbcId = -10000
09-09 17:18:08.974  1016  3273 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 17:18:08.974  1016  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
09-09 17:18:08.974  6994  6994 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 17:18:08.984  7017  7017 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 17:18:08.984  3322  3322 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
09-09 17:18:08.984  1173  1173 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-09 17:18:08.984  3322  3322 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-09 17:18:08.984  3322  3322 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-09 17:18:08.994  3322  3322 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-09 17:18:08.994  3322  3322 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-09 17:18:08.994  3322  3322 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-09 17:18:08.994  3322  3322 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-09 17:18:08.994  3322  3322 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:08.994  3322  3322 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:08.994  3322  3322 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:18:08.994  3322  3322 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:08.994  3322  3322 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:08.994  3322  3322 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:18:08.994  3322  3322 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 17:18:08.994  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:08.994  7017  7017 D elm:15183: ElmAgentService : onCreate()
,09-09 17:18:08.994  7017  7080 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-09 17:18:08.994  7017  7080 D elm:15183: MainReceiver.listeningToPackageRemoved()
,09-09 17:18:08.994  7017  7080 D elm:15183: MDMBridge.getInstance()
09-09 17:18:08.994  1016  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 17:18:08.994  1016  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 17:18:08.994  1016  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 17:18:08.994  7017  7080 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 17:18:08.994  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.004  7017  7080 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 17:18:09.014  5833  5833 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 17:18:09.014  5833  5833 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 17:18:09.014  5833  5833 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 17:18:09.014  5833  5833 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-09 17:18:09.014  7061  7061 D ThemeInfoUtil: getCurrentFestivalName is [null]
,09-09 17:18:09.014  1016  3068 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-09 17:18:09.014  7061  7061 D ThemeInfoUtil: isCurrentFestival = false
,09-09 17:18:09.014  1016  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.014  1016  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.014  1016  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.014  1016  3068 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.024  1016  3269 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 17:18:09.024  1016  3269 D SecContentProvider2: mCursor = null
,09-09 17:18:09.024  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.034  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-09 17:18:09.034  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.034  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 17:18:09.034  7083  7083 E Zygote  : MountEmulatedStorage()
09-09 17:18:09.034  7083  7083 I libpersona: KNOX_SDCARD checking this for 10032
,09-09 17:18:09.034  7083  7083 E Zygote  : v2,
09-09 17:18:09.034  7083  7083 I libpersona: KNOX_SDCARD not a persona
09-09 17:18:09.034  7083  7083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 17:18:09.044  7083  7083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-09 17:18:09.044  7083  7083 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 17:18:09.044  1016  3068 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7083 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-09 17:18:09.044  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-09 17:18:09.054  7017  7017 D elm:15183: ElmAgentService : onDestroy().
,09-09 17:18:09.054  1016  1305 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-09 17:18:09.054  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.054  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.054  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.054  1016  1305 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.054  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 17:18:09.054  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 17:18:09.054  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 17:18:09.054  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-09 17:18:09.064  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 17:18:09.074  7101  7101 E Zygote  : MountEmulatedStorage()
09-09 17:18:09.074  7101  7101 E Zygote  : v2
09-09 17:18:09.074  7101  7101 I libpersona: KNOX_SDCARD checking this for 10152
09-09 17:18:09.074  7101  7101 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:09.074  7101  7101 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 17:18:09.074  1016  1305 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7101 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
09-09 17:18:09.074  7101  7101 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 17:18:09.084  7101  7101 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 17:18:09.084  1016  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-09 17:18:09.084  1016  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 17:18:09.084  1016  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 17:18:09.094  7083  7083 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:18:09.094  7083  7083 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:09.104  7101  7101 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 17:18:09.104  7101  7101 D ActivityThread: Added TimaKeyStore provider
,09-09 17:18:09.114  7049  7098 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-09 17:18:09.124  7049  7049 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
,09-09 17:18:09.124  7049  7049 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:18:09.124  7049  7049 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:18:09.124  7049  7098 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
09-09 17:18:09.124  7049  7049 D AndroidRuntime: Shutting down VM
,09-09 17:18:09.124  7049  7049 E AndroidRuntime: FATAL EXCEPTION: main
09-09 17:18:09.124  7049  7049 E AndroidRuntime: Process: com.samsung.android.sm, PID: 7049
09-09 17:18:09.124  7049  7049 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125),
09-09 17:18:09.124  7049  7049 E AndroidRuntime: 	... 9 more
,09-09 17:18:09.134  1016  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,09-09 17:18:09.144  7049  7098 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/seatbelt.db'.
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:40)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:28)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at com.samsung.android.sm.common.r.n(Utils.java:2237)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at com.samsung.android.sm.common.o.run(SmartManagerReceiver.java:125)
09-09 17:18:09.144  7049  7098 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 17:18:09.144  7049  7098 I Process : Sending signal. PID: 7049 SIG: 9
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop202.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	at libcore.io.IoBridg,e.open(IoBridge.java:442)
09-09 17:18:09.144  1016  7117 E DropBoxManagerService: 	... 5 more
,09-09 17:18:09.154  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-09 17:18:09.154  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.154  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.154  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.154  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 17:18:09.164  7118  7118 E Zygote  : MountEmulatedStorage()
09-09 17:18:09.164  7118  7118 E Zygote  : v2
09-09 17:18:09.164  7118  7118 I libpersona: KNOX_SDCARD checking this for 1000
09-09 17:18:09.164  7118  7118 I libpersona: KNOX_SDCARD not a persona
,09-09 17:18:09.174  7101  7101 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
09-09 17:18:09.174  7118  7118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at java.lang.,reflect.Method.invoke(Method.java:372)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:18:09.174  7101  7101 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:18:09.174  7101  7101 D AndroidRuntime: Shutting down VM
09-09 17:18:09.174  1016  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7118 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-09 17:18:09.174  7101  7101 E AndroidRuntime: FATAL EXCEPTION: main
09-09 17:18:09.174  7101  7101 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 7101
09-09 17:18:09.174  7101  7101 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.content.Co,ntextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 17:18:09.174  7101  7101 E AndroidRuntime: 	... 11 more
09-09 17:18:09.174  1016  1219 I ActivityManager: Process com.samsung.android.sm (pid 7049)(adj 0) has died(154,1075)
09-09 17:18:09.174  7118  7118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 17:18:09.174  7118  7118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 17:18:09.184  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-09 17:18:09.174  1016  1219 D PersonaManager: isKioskContainerExistOnDevice
09-09 17:18:09.184  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.184  1016  3273 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
09-09 17:18:09.184  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.184  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.184  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: Can't write: system_app_crash
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop203.tmp: open failed: EROFS (Read-only file system)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 17:18:09.184  1016  7126 E DropBoxManagerService: 	... 5 more

```
