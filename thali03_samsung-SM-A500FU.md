#### Test 79763830b1f5deb_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-23 17:04:05.147  6147  6147 E Zygote  : MountEmulatedStorage()
08-23 17:04:05.147  6147  6147 E Zygote  : v2
08-23 17:04:05.147  6147  6147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-23 17:04:05.147  6147  6147 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-23 17:04:05.147  6147  6147 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
--------- beginning of system
08-23 17:04:05.147  6147  6147 I libpersona: KNOX_SDCARD checking this for 1000
08-23 17:04:05.147  6147  6147 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:05.147  1018  3306 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6147 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-23 17:04:05.157  6147  6147 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:05.167  6147  6147 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:05.187  3856  4405 I Icing   : Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
08-23 17:04:05.207  1018  2739 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
08-23 17:04:05.207  1018  2739 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:05.207  1018  2739 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:05.207  1018  2739 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:05.207  1018  2739 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:05.227  6164  6164 E Zygote  : MountEmulatedStorage()
08-23 17:04:05.227  6164  6164 E Zygote  : v2
08-23 17:04:05.227  6164  6164 I libpersona: KNOX_SDCARD checking this for 1000
08-23 17:04:05.227  6164  6164 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:05.227  6164  6164 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-23 17:04:05.227  1018  2739 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6164 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-23 17:04:05.227  1018  2739 I ActivityManager: Killing 5202:com.google.android.gm/u0a101 (adj 15): empty #31
08-23 17:04:05.227  6164  6164 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-23 17:04:05.227  6164  6164 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 17:04:05.257  6164  6164 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:05.257  6164  6164 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:05.267  3856  4405 I Icing   : Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
08-23 17:04:05.307  1018  1481 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-23 17:04:05.307  1018  1481 I ActivityManager: Killing 5558:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
08-23 17:04:05.317  6164  6181 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
08-23 17:04:05.317  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:05.317  6164  6181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
08-23 17:04:05.317  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:05.317  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 17:04:05.327  1018  3317 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-23 17:04:05.327  1018  3317 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
08-23 17:04:05.327  1018  3317 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:05.327  1018  3317 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 17:04:05.327  1018  3317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
08-23 17:04:05.337  6164  6164 D AcmsService: Enter Oncreate
08-23 17:04:05.337  6164  6164 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 17:04:05.337  6164  6164 D AcmsService: creating AcmsCore
08-23 17:04:05.337  6164  6164 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-23 17:04:05.337  6164  6164 D AcmsCore: AcmsCore
08-23 17:04:05.337  6164  6164 D AcmsCore: init
08-23 17:04:05.337  6164  6164 D AcmsCore: Looper handler is not null
08-23 17:04:05.337  6164  6164 D AcmsCore: Post to AcmsCoreHandler
08-23 17:04:05.337  1018  3183 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-23 17:04:05.337  6164  6164 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 17:04:05.337  6164  6164 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-23 17:04:05.337  6164  6164 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
08-23 17:04:05.337  6164  6164 D AcmsService: onStartCommand
08-23 17:04:05.337  6164  6164 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
08-23 17:04:05.337  6164  6164 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-23 17:04:05.337  6164  6164 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-23 17:04:05.337  6164  6164 D AcmsService: Incremented Counter Value : onStartCommand
08-23 17:04:05.347  6164  6164 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
08-23 17:04:05.347  6164  6182 D AcmsCertificateMngr: AcmsCertificateMngr
08-23 17:04:05.347  6164  6182 D AcmsRevocationMngr: AcmsRevocationMngr
08-23 17:04:05.377  5921  5921 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-23 17:04:05.387  6164  6164 D AcmsService: Inside handle Intent
08-23 17:04:05.387  6164  6164 D AcmsService: App added - package name: com.test.thalitest
08-23 17:04:05.387  6164  6164 D AcmsCore: Post to AcmsCoreHandler
08-23 17:04:05.387  6164  6164 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 17:04:05.387  6164  6164 D AcmsServiceMonitor: Incrementing - Counter value: 3
08-23 17:04:05.387  6164  6164 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
08-23 17:04:05.387  6164  6164 D AcmsService: Decremented Counter Value : handleStartIntent
08-23 17:04:05.387  6164  6164 D AcmsServiceMonitor: Decrementing - Counter value: 2
08-23 17:04:05.507  6179  6179 D AndroidRuntime: 
08-23 17:04:05.507  6179  6179 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 17:04:05.517  6179  6179 D AndroidRuntime: CheckJNI is OFF
08-23 17:04:05.517  6179  6179 D AndroidRuntime: readGMSProperty: start
08-23 17:04:05.517  6179  6179 D AndroidRuntime: readGMSProperty: already setted!!
08-23 17:04:05.517  6179  6179 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 17:04:05.517  6179  6179 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 17:04:05.517  6179  6179 D AndroidRuntime: readGMSProperty: end
08-23 17:04:05.517  6179  6179 D AndroidRuntime: addProductProperty: start
08-23 17:04:05.637  6179  6179 E AffinityControl: AffinityControl: registerfunction enter
08-23 17:04:05.667  6179  6179 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 17:04:05.667  3856  4405 I Icing   : Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
08-23 17:04:05.667  1018  1292 E PersonaManagerService: inState():  stateMachine is null !!
08-23 17:04:05.667  1018  1292 I PersonaManagerService: PersonaId don't exist
08-23 17:04:05.667  1018  1292 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 17:04:05.677  1018  1292 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 17:04:05.687  1018  1292 W ActivityManager: mDVFSHelper.acquire()
08-23 17:04:05.697  1018  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 17:04:05.697  1018  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 17:04:05.707  1018  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:05.707  1018  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:05.707  1018  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:05.707  1018  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:05.717  1018  1292 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6193 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 17:04:05.717  1018  1292 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-23 17:04:05.717  1018  1292 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 17:04:05.717  1018  1292 D InputDispatcher: Focused application set to: xxxx
08-23 17:04:05.717  1018  1292 D InputDispatcher: Focus left window: 3232
08-23 17:04:05.717  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 17:04:05.717  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 17:04:05.727   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-23 17:04:05.727  6193  6193 E Zygote  : MountEmulatedStorage()
08-23 17:04:05.727  6193  6193 E Zygote  : v2
08-23 17:04:05.727  6193  6193 I libpersona: KNOX_SDCARD checking this for 10155
08-23 17:04:05.727  6193  6193 I libpersona: KNOX_SDCARD not a persona
08-23 17:04:05.727  6193  6193 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-23 17:04:05.727  6193  6193 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-23 17:04:05.727  6193  6193 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 17:04:05.737  6179  6179 D AndroidRuntime: Shutting down VM
08-23 17:04:05.737  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 17:04:05.737  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 17:04:05.747   306   306 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 678us total 28.438ms
08-23 17:04:05.767   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 18.089ms
08-23 17:04:05.777  6193  6193 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 17:04:05.777  6193  6193 D ActivityThread: Added TimaKeyStore provider
08-23 17:04:05.777  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 17:04:05.787  1018  1018 V ActivityManager: Display changed displayId=0
08-23 17:04:05.787   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 681us total 17.578ms
08-23 17:04:05.787  5824  5824 I Mms/MmsApp:  start initViewCache mms
08-23 17:04:05.787  5824  5824 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1904.645468
08-23 17:04:05.787  5824  5824 D Mms/ComposeMessageFragment: fillCache, easy = false
08-23 17:04:05.807  1018  3325 D PersonaManager: isKioskContainerExistOnDevice
08-23 17:04:05.857   258  1040 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-23 17:04:05.857   258   448 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-23 17:04:05.857  3232  3232 V ActivityThread: updateVisibility : ActivityRecord{4074616 token=android.os.BinderProxy@2a8ed9a5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-23 17:04:05.867  1018  3317 I art     : Explicit concurrent mark sweep GC freed 147584(8MB) AllocSpace objects, 4(1863KB) LOS objects, 33% free, 27MB/41MB, paused 3.126ms total 194.364ms
08-23 17:04:05.917  5824  5824 D AbsListView: Get MotionRecognitionManager
08-23 17:04:05.917  1018  2739 D MotionRecognitionService:  ssp status : false
08-23 17:04:05.917  5824  5824 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 133.054532
08-23 17:04:05.947  6179  6179 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 17:04:05.967  6193  6193 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-23 17:04:05.977  6193  6193 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1726-1728)
08-23 17:04:05.977  6193  6193 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 17:04:06.007  6193  6193 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e0517b2}
08-23 17:04:06.007  3856  4405 I Icing   : Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
08-23 17:04:06.017  6193  6193 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 17:04:06.017  6193  6193 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 17:04:06.027  1018  3311 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-23 17:04:06.027  1018  3311 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:06.027  1018  3311 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:06.037  1018  3311 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 17:04:06.037  5824  5824 D Mms/BubbleViewCache: fillCache bubble = 1
08-23 17:04:06.047  6193  6193 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 17:04:06.047  6193  6193 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 17:04:06.057  6193  6193 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 17:04:06.067  6193  6193 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-23 17:04:06.077  6193  6193 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-23 17:04:06.077  6193  6193 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-23 17:04:06.077  6193  6193 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 17:04:06.077  6193  6193 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 17:04:06.077  6193  6193 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 17:04:06.077  6193  6193 I Adreno-EGL: Local Branch: 
08-23 17:04:06.077  6193  6193 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 17:04:06.077  6193  6193 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 17:04:06.077  6193  6193 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-23 17:04:06.197  6193  6223 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
08-23 17:04:06.237  6193  6193 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 17:04:06.247  6193  6193 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 17:04:06.257  6193  6193 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 17:04:06.257  6193  6193 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-23 17:04:06.267  6193  6193 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-23 17:04:06.277  6193  6193 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 17:04:06.277  6193  6193 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 17:04:06.307  1018  1044 W ActivityManager: Activity pause timeout for ActivityRecord{3102c6bb u0 com.test.thalitest/.MainActivity t128}
08-23 17:04:06.317  6193  6236 D OpenGLRenderer: Render dirty regions requested: true
08-23 17:04:06.327  1018  2739 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 17:04:06.327  1018  2739 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 17:04:06.327  1018  2739 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 17:04:06.327  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 17:04:06.327  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 17:04:06.347  6193  6193 V ActivityThread: updateVisibility : ActivityRecord{25243fe5 token=android.os.BinderProxy@21b80b4f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 17:04:06.347  6193  6193 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 17:04:06.347  6193  6193 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 17:04:06.357   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
08-23 17:04:06.367  1018  2778 D InputDispatcher: Focus entered window: 6193
08-23 17:04:06.367  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 17:04:06.367  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 17:04:06.367  6193  6193 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-23 17:04:06.367  6193  6236 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 17:04:06.377  6193  6236 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-23 17:04:06.377  6193  6236 D OpenGLRenderer: Enabling debug mode 0
08-23 17:04:06.417  1018  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-23 17:04:06.417  1179  1179 D PanelView: There is/are notification(s) 
08-23 17:04:06.427  1018  6239 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-23 17:04:06.427  6193  6193 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 17:04:06.427  6193  6193 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@21b80b4f time:102177
08-23 17:04:06.437  1789  1789 I SamsungIME: getCurrentCandidateView
08-23 17:04:06.447  1018  1049 I ActivityManager: Displayed Component not be shown by security: +641ms (total +749ms)
08-23 17:04:06.457  1018  1049 W ActivityManager: mDVFSHelper.release()
08-23 17:04:06.457  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3102c6bb u0 com.test.thalitest/.MainActivity t128} time:102203
08-23 17:04:06.457   258   448 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
08-23 17:04:06.457   258   442 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
08-23 17:04:06.507  1789  1789 D SamsungIME: Dismiss ExpandCandiate
08-23 17:04:06.527  6193  6193 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6193
08-23 17:04:06.637  6193  6193 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-23 17:04:06.637  1789  1789 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 17:04:06.677  1789  1789 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 17:04:06.687  1789  1789 I SamsungIME: KeybaordView init() : load resources
,08-23 17:04:06.717  1789  1789 I SamsungIME: getCurrentKeyboard
,08-23 17:04:06.717  1789  1789 I SamsungIME: getTextKeyboard
,08-23 17:04:06.727  1789  1789 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 17:04:06.747  6193  6241 D jxcore_app_log: JniHelper::setJavaVM(0xb7748328), pthread_self() = -1211468760
,08-23 17:04:06.757  6193  6241 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 17:04:06.757  6193  6241 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 17:04:06.757  6193  6241 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 17:04:06.757  6193  6241 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 17:04:06.757  6193  6241 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 17:04:06.757  6193  6241 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7dec55 added. We now have 1 listener(s)
,08-23 17:04:06.757  6193  6241 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-23 17:04:06.757  6193  6241 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-23 17:04:06.767  6193  6241 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 17:04:06.767  6193  6241 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 17:04:06.767  6193  6241 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@111babf8 added. We now have 1 listener(s)
08-23 17:04:06.767  6193  6241 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 17:04:06.777  6193  6241 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 17:04:06.777  6193  6241 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 17:04:06.777  6193  6241 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 17:04:06.777  6193  6241 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 17:04:06.777  6193  6241 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 17:04:06.777  6193  6241 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 17:04:06.787  6193  6241 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-23 17:04:06.787  6193  6241 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 17:04:06.787  6193  6241 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 17:04:06.787  6193  6241 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 17:04:06.787  6193  6241 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 17:04:06.787  6193  6241 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 17:04:06.787  6193  6241 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 17:04:06.787  6193  6241 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 17:04:06.787  6193  6241 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 17:04:06.787  6193  6241 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 17:04:06.787  6193  6241 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 17:04:06.787  6193  6241 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 17:04:06.797  6193  6241 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 17:04:06.797  6193  6193 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 17:04:06.797  6193  6193 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 17:04:06.827  6193  6193 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 17:04:07.267  1789  6245 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 17:04:07.397  6193  6250 W jxcore-log: Initializing JXcore engine
08-23 17:04:07.397  6193  6250 W jxcore-log: JXcore engine is ready
,08-23 17:04:07.447  1913  1913 E audit   : type=1400 msg=audit(1471964647.447:205): avc:  denied  { ioctl } for  pid=6250 comm="Thread-1074" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 17:04:07.447  1913  1913 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-23 17:04:07.447  1913  1913 E audit   : type=1300 msg=audit(1471964647.447:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ee808f8 items=0 ppid=306 ppcomm=main pid=6250 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1074" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 17:04:07.447  1913  1913 E audit   : type=1320 msg=audit(1471964647.447:205): 
,08-23 17:04:07.467  6193  6250 W jxcore-log: Starting JXcore engine
,08-23 17:04:07.567  6193  6250 W jxcore-log: Platform android
08-23 17:04:07.567  6193  6250 W jxcore-log: 
08-23 17:04:07.567  6193  6250 W jxcore-log: Process ARCH arm
08-23 17:04:07.567  6193  6250 W jxcore-log: 
,08-23 17:04:07.777  6193  6250 I jxcore-log: JXcore Cordova bridge is ready!
08-23 17:04:07.777  6193  6250 I jxcore-log: 
,08-23 17:04:07.777  6193  6250 W jxcore-log: JXcore engine is started
,08-23 17:04:07.777  6193  6241 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 17:04:07.787  6193  6193 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 17:04:08.037   288   288 E SMD     : DCD OFF
,08-23 17:04:08.047  6164  6182 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,08-23 17:04:08.057  6164  6182 I AcmsKeyStoreHelper: Key Store exist
,08-23 17:04:08.067  6164  6182 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-23 17:04:08.127  6164  6182 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
,08-23 17:04:08.127  6164  6182 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-23 17:04:08.127  6164  6182 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
,08-23 17:04:08.127  6164  6182 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 17:04:08.127  6164  6182 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-23 17:04:08.127  6164  6182 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
08-23 17:04:08.127  6164  6182 D AcmsCore: This is NOT a valid MirrorLink app,
08-23 17:04:08.127  6164  6182 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-23 17:04:08.127  6164  6182 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 17:04:08.127  6164  6182 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-23 17:04:08.127  6164  6182 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service,
,08-23 17:04:08.127  6164  6164 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-23 17:04:08.127  6164  6164 D AcmsService: Enter onDestroy
,08-23 17:04:08.127  6164  6164 I AcmsService: cleanUp(): inside service clean up
08-23 17:04:08.127  6164  6164 D AcmsCore: AcmsCore: inside DeInit
,08-23 17:04:08.127  6164  6164 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,08-23 17:04:08.137  6164  6164 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,08-23 17:04:08.137  6164  6164 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-23 17:04:08.137  6164  6164 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
08-23 17:04:08.137  6164  6164 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-23 17:04:08.137  6164  6164 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-23 17:04:08.137  6164  6164 D AcmsService: killing acms process
,08-23 17:04:08.137  6164  6164 I Process : Sending signal. PID: 6164 SIG: 9
,08-23 17:04:08.267  1018  1031 I ActivityManager: Process ACMS.Process (pid 6164)(adj 0) has died(42,1145)
,08-23 17:04:09.857  1018  3317 D ActivityManager: bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-23 17:04:09.857  1018  3317 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-23 17:04:09.857  1018  3317 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:09.857  1018  3317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 17:04:09.857  1018  3317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,08-23 17:04:10.247  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:10.247  1018  1030 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4115, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:04:10.247  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:04:10.247  1018  1030 D BatteryService: stay LED for charging
08-23 17:04:10.247  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:10.247  1018  1051 D PowerManagerService: [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 85, mLowBatteryTriggerLevel: 0)
,08-23 17:04:10.257  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:04:10.257  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:04:10.257  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:04:10.257  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:04:10.257  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:04:10.257  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:04:10.257  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:04:10.277  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:04:10.277  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:04:10.287  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:10.287  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:10.287  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:11.047   288   288 E SMD     : DCD OFF,
,08-23 17:04:11.757  1018  1051 I PowerManagerService: [PWL] Off : 30s ago
,08-23 17:04:11.797  1018  1097 V AlarmManager: waitForAlarm result :4
,08-23 17:04:11.797  1018  1018 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-23 17:04:11.807  1018  1018 V AlarmManagerEXT: <AppSync3 Whitelist>,
08-23 17:04:11.807  1018  1018 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-23 17:04:11.807  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 17:04:11.807  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:04:11.817  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 17:04:11.827  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1,
,08-23 17:04:11.827  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:04:11.837  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-23 17:04:11.837  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-23 17:04:11.857  1018  2753 D SSRM:n  : SIOP:: AP = 400
,08-23 17:04:11.877  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:04:11.887  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:04:11.887  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:04:11.907  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:04:12.497  1018  1338 E Watchdog: !@Sync 3
,08-23 17:04:13.097   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 17:04:13.097   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 17:04:14.047   288   288 E SMD     : DCD OFF
,08-23 17:04:14.327  1018  1059 D PackageManager: [MSG] MCS_UNBIND
,08-23 17:04:14.327  1018  1480 I ActivityManager: Killing 5589:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,08-23 17:04:15.707  1018  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-23 17:04:17.047   288   288 E SMD     : DCD OFF
,08-23 17:04:17.837  5424  5424 D FactoryTest: Not factory mode
,08-23 17:04:17.837  5424  5424 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-23 17:04:17.847  5424  5424 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-23 17:04:17.847  5424  5424 D MTPRx   : still no open session command from host, so toast
,08-23 17:04:17.847  5424  5424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-23 17:04:17.847  5424  5424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-23 17:04:17.847  5424  5424 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113594
08-23 17:04:17.847  1018  2739 E PersonaManagerService: inState():  stateMachine is null !!
08-23 17:04:17.847  1018  2739 I PersonaManagerService: PersonaId don't exist
08-23 17:04:17.847  1018  2739 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-23 17:04:17.857  1018  2739 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 17:04:17.857  1018  2739 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:17.857  1018  2739 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 17:04:17.857  1018  2739 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-23 17:04:17.857  1018  2739 W ActivityManager: mDVFSHelper.acquire()
,08-23 17:04:17.867  1018  2739 D PersonaManager: isKioskContainerExistOnDevice
,08-23 17:04:17.877  1018  2739 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 17:04:17.877  1018  2739 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
08-23 17:04:17.877  1018  2739 D InputDispatcher: Focused application set to: xxxx
08-23 17:04:17.877  1018  2739 D InputDispatcher: Focus left window: 6193,
,08-23 17:04:17.877  5424  5424 E MTPRx   : started activity for popup
,08-23 17:04:17.887  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 17:04:17.887  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 17:04:17.907  5424  5424 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-23 17:04:17.907  5424  5424 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-23 17:04:17.907  5424  5424 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 17:04:17.907  5424  5424 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 17:04:17.907  5424  5424 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 17:04:17.907  5424  5424 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-23 17:04:17.937  5424  5424 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-23 17:04:17.937  1018  3317 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 17:04:17.937  1018  3317 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 17:04:17.937  1018  3317 D InputDispatcher: Focused application set to: xxxx
,08-23 17:04:17.937  1018  3317 D InputDispatcher: Focus entered window: 6193
,08-23 17:04:17.937  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-23 17:04:17.937  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 17:04:17.937  1018  1125 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 17:04:17.937  1018  1125 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@369ec4bd attribute=null, token = android.os.BinderProxy@cb23e9b,
,08-23 17:04:17.977  5424  5424 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-23 17:04:17.987  5424  5424 D PhoneWindow: *FMB* installDecor mIsFloating : true,
08-23 17:04:17.987  5424  5424 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-23 17:04:18.007  6193  6193 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 17:04:18.007  6193  6193 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-23 17:04:18.007  6193  6193 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 17:04:18.007  6193  6193 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-23 17:04:18.017  1018  3325 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 17:04:18.017  1018  3325 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 17:04:18.017  1018  3325 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 17:04:18.017  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-23 17:04:18.017  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 17:04:18.027  6193  6193 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 17:04:18.027  6193  6193 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 17:04:18.037  6193  6193 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@150ed162 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e00df0a, 16908290=android.view.AbsSavedState$1@e00df0a}, android:focusedViewId=100}]}]
08-23 17:04:18.037  6193  6193 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 17:04:18.037  6193  6193 V ActivityThread: updateVisibility : ActivityRecord{25243fe5 token=android.os.BinderProxy@21b80b4f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-23 17:04:18.037  6193  6193 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 17:04:18.037  6193  6193 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-23 17:04:18.037  6193  6193 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@21b80b4f time:113782
,08-23 17:04:18.037  1018  3311 D PersonaManager: isKioskContainerExistOnDevice
,08-23 17:04:18.097   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:04:18.547  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{ebb502c u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,08-23 17:04:19.097   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:04:19.237  1018  1125 I ActivityManager: Killing 5380:com.dropbox.android/u0a92 (adj 15): empty #31
,08-23 17:04:19.997  6193  6250 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 17:04:19.997  6193  6250 I jxcore-log: 
,08-23 17:04:19.997  6193  6250 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 17:04:19.997  6193  6250 I jxcore-log: 
,08-23 17:04:20.007  6193  6250 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 17:04:20.007  6193  6250 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 17:04:20.007  6193  6250 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 17:04:20.007  6193  6250 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 17:04:20.007  6193  6250 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 17:04:20.007  6193  6250 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 17:04:20.007  6193  6250 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 17:04:20.007  6193  6250 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 17:04:20.007  6193  6250 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 17:04:20.007  6193  6250 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 17:04:20.007  6193  6250 I jxcore-log: 
,08-23 17:04:20.007  6193  6250 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 17:04:20.007  6193  6250 I jxcore-log: 
,08-23 17:04:20.047   288   288 E SMD     : DCD OFF,
,08-23 17:04:20.097   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:04:20.307  1018  2778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:20.307  1018  2778 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4118, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:04:20.307  1018  2778 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:04:20.307  1018  2778 D BatteryService: stay LED for charging
,08-23 17:04:20.307  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:20.307  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:04:20.307  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:04:20.317  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:20.317  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:04:20.317  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:04:20.317  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:04:20.327  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:04:20.327  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:04:20.337  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:20.337  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:20.337  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:20.657  6193  6250 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests,
08-23 17:04:20.657  6193  6250 I jxcore-log: Failed to execute UT.
08-23 17:04:20.657  6193  6250 I jxcore-log: 
,08-23 17:04:20.657  6193  6250 I jxcore-log: Unit Test app is loaded,
08-23 17:04:20.657  6193  6250 I jxcore-log: 
,08-23 17:04:20.667  6193  6250 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-23 17:04:20.667  6193  6250 I jxcore-log: 
,08-23 17:04:20.667  6193  6193 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-23 17:04:20.687  6193  6250 I jxcore-log: My device name is: samsung-SM-A500FU
08-23 17:04:20.687  6193  6250 I jxcore-log: 
,08-23 17:04:20.857  1018  1044 W ActivityManager: mDVFSHelper.release()
,08-23 17:04:21.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:04:21.187  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 17:04:21.877  1018  2753 D SSRM:n  : SIOP:: AP = 390
,08-23 17:04:22.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:04:23.047   288   288 E SMD     : DCD OFF
,08-23 17:04:23.107   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-23 17:04:24.257  1018  1097 V AlarmManager: waitForAlarm result :4
,08-23 17:04:24.257  1018  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0,
,08-23 17:04:24.267  1018  1097 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,08-23 17:04:24.267  5628  5665 I Finsky  : [966] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,08-23 17:04:24.297  1935  1935 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-23 17:04:24.337  1018  3317 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 17:04:24.337  1018  3317 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-23 17:04:24.337  1018  3317 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:24.337  1018  3317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:24.337  1018  3317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:24.467  3856  3856 D ConnectivityManager: CallingUid : 10012, CallingPid : 3856
,08-23 17:04:24.467  1018  3306 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 17:04:24.467  1018  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-23 17:04:24.467  1018  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-23 17:04:24.467  1018  1132 D ConnectivityService: apparently satisfied.  currentScore=60
,08-23 17:04:24.467  3856  6266 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-23 17:04:24.547  3856  6267 W DriveInitializer: Background init thread started
,08-23 17:04:24.577   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-23 17:04:24.577   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 17:04:24.577  3856  6267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-23 17:04:24.627  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 17:04:24.627  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-23 17:04:24.627  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:24.627  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:24.627  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:24.667  1018  3311 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-23 17:04:24.667  1018  3311 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-23 17:04:24.667  3856  6267 W DriveInitializer: Background init thread ended
,08-23 17:04:24.667  1018  1125 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 17:04:24.667  1018  1125 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-23 17:04:24.667  1018  1125 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:24.667  1018  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:24.667  1018  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:24.687  5628  5665 I Finsky  : [966] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,08-23 17:04:24.687  5628  5628 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,08-23 17:04:24.697  3856  6275 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-23 17:04:24.697  3856  6275 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-23 17:04:24.717  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:24.747  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:24.747  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 17:04:24.747  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:24.817  1018  3158 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 17:04:24.817  1018  3158 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-23 17:04:24.817  1018  3158 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:24.817  1018  3158 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 17:04:24.817  1018  3158 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:24.847  1018  1336 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 17:04:24.847  1018  1336 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-23 17:04:24.857  1018  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:24.857  1018  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:24.857  1018  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:24.917  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:24.927  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:24.927  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:24.927  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:24.947  1018  3158 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:24.947  1018  3158 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:24.947  1018  3158 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:24.947  1018  3158 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.007  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:25.007  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:25.007  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:25.007  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.017  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 17:04:25.017  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 17:04:25.017  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 17:04:25.017  1018  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 17:04:25.027  6280  6280 E Zygote  : MountEmulatedStorage()
,08-23 17:04:25.027  6280  6280 E Zygote  : v2
08-23 17:04:25.027  6280  6280 I libpersona: KNOX_SDCARD checking this for 10012
08-23 17:04:25.027  1018  1481 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6280 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-23 17:04:25.027  6280  6280 I libpersona: KNOX_SDCARD not a persona
,08-23 17:04:25.037  6280  6280 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-23 17:04:25.037  6280  6280 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-23 17:04:25.037  6280  6280 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 17:04:25.057  6280  6280 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 17:04:25.057  6280  6280 D ActivityThread: Added TimaKeyStore provider
,08-23 17:04:25.077  6280  6280 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-23 17:04:25.087  6280  6280 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 17:04:25.127  6280  6280 I MultiDex: VM with version 2.1.0 has multidex support
,08-23 17:04:25.127  6280  6280 I MultiDex: install
08-23 17:04:25.127  6280  6280 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 17:04:25.157  6280  6280 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 17:04:25.187  1018  1097 V AlarmManager: waitForAlarm result :4
,08-23 17:04:25.207  1018  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,08-23 17:04:25.207  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,08-23 17:04:25.227  1018  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter,
08-23 17:04:25.227  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,08-23 17:04:25.227  6280  6280 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-23 17:04:25.237  6280  6280 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ffd5d2f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-23 17:04:25.237  6280  6280 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 17:04:25.237  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-23 17:04:25.247  1018  3158 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:25.257  1018  3158 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:25.257  1018  3158 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:25.257  1018  3158 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.267  6280  6280 D ChimeraCfgMgr: Reading stored module config
,08-23 17:04:25.347  1935  1951 I art     : Explicit concurrent mark sweep GC freed 56325(3MB) AllocSpace objects, 15(480KB) LOS objects, 39% free, 13MB/23MB, paused 1.685ms total 93.627ms
,08-23 17:04:25.367  1018  2778 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:25.377  1018  2778 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:25.377  1018  2778 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:25.377  1018  2778 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.387  6280  6294 I art     : Background sticky concurrent mark sweep GC freed 20805(1048KB) AllocSpace objects, 3(133KB) LOS objects, 5% free, 10MB/11MB, paused 7.447ms total 86.666ms
,08-23 17:04:25.387  6280  6302 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-23 17:04:25.417  6280  6280 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-23 17:04:25.417  6280  6280 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-23 17:04:25.447  1935  1935 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=032e6858-3107-4ead-b7e3-27651ae1ac51
,08-23 17:04:25.457  1018  1336 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-23 17:04:25.457  1018  1336 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-23 17:04:25.467  1018  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:25.467  1018  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 17:04:25.467  1018  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.497  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:25.497  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:04:25.507  1641  2122 I art     : Explicit concurrent mark sweep GC freed 1829(68KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 748us total 31.719ms
,08-23 17:04:25.527   283   724 D WVCdm   : Instantiating CDM.
,08-23 17:04:25.537   283   691 I WVCdm   : CdmEngine::OpenSession
,08-23 17:04:25.537   283   691 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-23 17:04:25.537  1018  3306 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:25.547  1018  3306 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:25.547  1018  3306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:25.547  1018  3306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.557   283   691 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-23 17:04:25.577   283   691 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-23 17:04:25.577   283   691 D DrmWidevineDash: Service_Initialize: starts!
08-23 17:04:25.577   283   691 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-23 17:04:25.577   283   691 D QSEECOMAPI: : App is not loaded in QSEE
08-23 17:04:25.577   283   691 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-23 17:04:25.577   283   691 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 17:04:25.577   283   691 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 17:04:25.577   283   691 D QSEECOMAPI: : App is not loaded in QSEE
08-23 17:04:25.577   283   691 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-23 17:04:25.577   283   691 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 17:04:25.577   283   691 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 17:04:25.577   283   691 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 17:04:25.597  1018  1336 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
,08-23 17:04:25.607   283   691 D QSEECOMAPI: : Loaded image: APP id = 11
,08-23 17:04:25.617   283   691 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-23 17:04:25.617   283   691 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-23 17:04:25.617   283   691 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-23 17:04:25.617   283   691 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1594000
08-23 17:04:25.617   283   691 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1594000
08-23 17:04:25.617   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.627   423   434 D DrmLibTime: got the req here! ret=0
08-23 17:04:25.627   423   434 D DrmLibTime: command id, time_cmd_id = 770
08-23 17:04:25.627   423   434 D DrmLibTime: time_getutcsec starts!
08-23 17:04:25.627   423   434 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-23 17:04:25.627   423   434 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-23 17:04:25.627   423   434 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-23 17:04:25.627   423   434 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-23 17:04:25.637  6280  6288 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-23 17:04:25.637  6280  6288 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 17:04:25.637  6280  6288 I System.out: (HTTPLog)-Static: isShipBuild true
08-23 17:04:25.637  6280  6288 I System.out: (HTTPLog)-Thread-1049-737414976: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-23 17:04:25.637  6280  6288 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:25.637   278  1002 D EnterpriseController: uids 10012
08-23 17:04:25.637   278  1002 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 17:04:25.637   278  1002 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-23 17:04:25.647   423   434 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
08-23 17:04:25.647   423   434 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-23 17:04:25.647   423   434 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-23 17:04:25.647   423   434 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!,
08-23 17:04:25.647   317   557 D QC-time-services: Daemon: Connection accepted:time_genoff
08-23 17:04:25.647   317  6314 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-23 17:04:25.647   317  6314 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-23 17:04:25.647   317  6314 D QC-time-services: offset is: 0 for base: 0
08-23 17:04:25.647   317   557 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-23 17:04:25.647   423   434 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-23 17:04:25.647   423   434 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-23 17:04:25.647   423   434 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1471964665
08-23 17:04:25.647   423   434 D DrmLibTime: time_getutcsec returns 0, sec = 1471964665; nsec = 0
08-23 17:04:25.647   423   434 D DrmLibTime: time_getutcsec finished! ,
08-23 17:04:25.647   423   434 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-23 17:04:25.647   423   434 D DrmLibTime: before calling ioctl to read the next time_cmd
08-23 17:04:25.647  6280  6288 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 17:04:25.647   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.647  6280  6288 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6280, getuid(): 10012
,08-23 17:04:25.667   283   691 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-23 17:04:25.667   283   691 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-23 17:04:25.667   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.667   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.667   283   691 D DrmWidevineDash: hlos api version =  9
08-23 17:04:25.667   283   691 D DrmWidevineDash: tz api version =  9
08-23 17:04:25.667   283   691 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-23 17:04:25.667   283   691 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-23 17:04:25.667   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.717   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-23 17:04:25.717   283   691 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb18e8960
08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-23 17:04:25.717   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.717   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb77c4e18, dataLength=8
08-23 17:04:25.717   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.717   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb77c33c8, wrapped_rsa_key_length=1280
08-23 17:04:25.717   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.717   283   691 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.717   283   691 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-23 17:04:25.717   283   691 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-23 17:04:25.727   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-23 17:04:25.727   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-23 17:04:25.727   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
08-23 17:04:25.727   283   283 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7775cd8, idLength=0xbec4af80
,08-23 17:04:25.727   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.737   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-23 17:04:25.737   283   283 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-23 17:04:25.737   283   283 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xbec4af96, maximum = 0xbec4af97
08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.747   283   283 D DrmWidevineDash: hlos api version =  9
08-23 17:04:25.747   283   283 D DrmWidevineDash: tz api version =  9
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xbec4b004
08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-23 17:04:25.747   283   283 D WVCdm   : PrepareKeyRequest: nonce=2640445130
08-23 17:04:25.747   283   283 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb777ac48
08-23 17:04:25.747   283   283 D DrmWidevineDash: message_length=1599, signature=0xb777b8d8, signature_length=0xbec4af64
08-23 17:04:25.747   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.817  1935  2109 W GCoreFlp: No location to return for getLastLocation()
,08-23 17:04:25.837  1018  3311 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:25.847  1018  3311 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:25.847  1018  3311 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:25.847  1018  3311 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.857  1018  1125 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:25.857  1018  1125 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:25.857  1018  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:25.857  1018  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.857  1018  3317 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:25.867  1018  3317 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:25.867  1018  3317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:25.867  1018  3317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:25.887  3856  6276 D UdcContextInitService: registered all accounts: true
,08-23 17:04:25.897   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.897   283   283 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-23 17:04:25.897  1935  2117 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 17:04:25.907   283   724 I WVCdm   : CdmEngine::CloseSession
08-23 17:04:25.907   283   724 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-23 17:04:25.907   283   724 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 17:04:25.907   283   724 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.907   283   724 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-23 17:04:25.907   283   724 I WVCdm   : L3 Terminate.
08-23 17:04:25.907   283   724 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-23 17:04:25.907   283   724 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-23 17:04:25.907   283   724 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 17:04:25.907   283   724 D DrmWidevineDash: Service_Uninitialize: starts!
08-23 17:04:25.907   283   724 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-23 17:04:25.907   283   724 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-23 17:04:25.907   283   724 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-23 17:04:25.907   283   724 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-23 17:04:25.917  1935  2130 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-23 17:04:25.997  6280  6288 I qtaguid : Untagging socket 33
,08-23 17:04:26.047   288   288 E SMD     : DCD OFF
,08-23 17:04:26.057  1018  3317 I art     : Explicit concurrent mark sweep GC freed 36175(1874KB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 27MB/41MB, paused 2.600ms total 160.610ms
,08-23 17:04:26.057  1018  3311 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-23 17:04:26.057  1018  3311 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-23 17:04:26.067  1018  3311 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.067  1018  3311 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.067  1018  3311 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.177  1018  3158 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 17:04:26.177  1018  3158 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-23 17:04:26.187  1018  3158 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.187  1018  3158 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 17:04:26.187  1018  3158 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.277  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 17:04:26.277  6193  6250 I jxcore-log: 
,08-23 17:04:26.277  1018  3311 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:26.277  1018  3311 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.277  1018  3311 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.277  1018  3311 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.307  1018  3311 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:26.317  1018  3311 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.317  1018  3311 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.317  1018  3311 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.357  1018  1125 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:26.357  1018  1125 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.357  1018  1125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.357  1018  1125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.357  1935  6321 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 17:04:26.357  1935  6319 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 17:04:26.357  1018  1292 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:26.357  1018  1292 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.367  1018  1292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.367  1018  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.387  1018  1670 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:26.387  1018  1670 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.387  1018  1670 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.387  1018  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.387  1935  6321 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 17:04:26.387  1935  6319 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 17:04:26.387  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:26.387  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:04:26.387  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.387  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.417  1018  1336 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:04:26.417  1018  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.417  1018  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.417  1018  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.417  1935  6321 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 17:04:26.417  1935  6319 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 17:04:26.417  1935  6319 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-23 17:04:26.427  1935  6319 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 17:04:26.477  1018  1336 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:26.517  1018  1481 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-23 17:04:26.517  1018  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-23 17:04:26.517  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:04:26.517  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:04:26.517  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:04:26.527  1935  6319 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:26.527   278  1002 D EnterpriseController: uids 10012
08-23 17:04:26.527   278  1002 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 17:04:26.527   278  1002 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-23 17:04:26.527  1935  6319 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 17:04:26.527  1935  6319 I qtaguid : Tagging socket 72 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1935, getuid(): 10012
,08-23 17:04:26.547  6322  6322 I dex2oat : ----------------------------------------------------
08-23 17:04:26.547  6322  6322 I dex2oat : <SS>: S T A R T I N G . . .
08-23 17:04:26.547  6322  6322 I dex2oat : <SS>: Zip is absent. Canceled.
,08-23 17:04:26.547  6322  6322 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-23 17:04:26.577  6322  6322 I dex2oat : dex2oat took 25.769ms (threads: 4)
,08-23 17:04:26.577  1935  6319 I qtaguid : Tagging socket 76 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1935, getuid(): 10012
,08-23 17:04:26.587  6280  6288 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 17:04:26.587  6280  6288 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 17:04:26.587  6280  6288 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 17:04:26.587  6280  6288 I Adreno-EGL: Local Branch: 
08-23 17:04:26.587  6280  6288 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 17:04:26.587  6280  6288 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 17:04:26.587  6280  6288 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 17:04:26.677  6280  6288 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 17:04:26.677  6280  6288 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 17:04:26.677  6280  6288 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 17:04:26.677  6280  6288 I Adreno-EGL: Local Branch: 
08-23 17:04:26.677  6280  6288 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 17:04:26.677  6280  6288 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 17:04:26.677  6280  6288 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 17:04:26.807  6280  6288 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 17:04:26.807  6280  6288 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 17:04:26.807  6280  6288 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 17:04:26.807  6280  6288 I Adreno-EGL: Local Branch: 
08-23 17:04:26.807  6280  6288 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 17:04:26.807  6280  6288 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 17:04:26.807  6280  6288 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 17:04:26.827  1018  1336 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-23 17:04:26.837  1935  6319 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 17:04:26.837  1935  6319 I qtaguid : Tagging socket 72 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1935, getuid(): 10012
,08-23 17:04:26.967  1018  3317 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:26.997  1935  6319 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:26.997  1935  6319 I qtaguid : Tagging socket 72 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1935, getuid(): 10012
,08-23 17:04:27.047  1935  6278 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:27.047   278  1002 D EnterpriseController: uids 10012
08-23 17:04:27.047   278  1002 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 17:04:27.047   278  1002 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-23 17:04:27.057  1935  6278 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-23 17:04:27.057  1935  6278 I qtaguid : Tagging socket 69 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1935, getuid(): 10012
,08-23 17:04:27.087  1935  6278 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1935, getuid(): 10012
,08-23 17:04:27.157  1018  2778 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:27.157  1935  6319 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:27.157  1935  6319 I qtaguid : Tagging socket 72 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1935, getuid(): 10012
,08-23 17:04:27.267  1935  2130 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 17:04:27.277  1935  2130 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-23 17:04:27.277  1935  2130 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-23 17:04:25.976+0200, stopTime=2016-08-23 17:04:27.287+0200, duration=1311ms
,08-23 17:04:27.287  1935  6337 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:27.297   278  1002 D EnterpriseController: uids 10012
08-23 17:04:27.297   278  1002 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 17:04:27.297   278  1002 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-23 17:04:27.297  1935  6337 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-23 17:04:27.297  1935  6337 I qtaguid : Tagging socket 80 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1935, getuid(): 10012
,08-23 17:04:27.307  1018  3183 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 17:04:27.307  1935  6319 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:27.307  1935  6319 I qtaguid : Tagging socket 72 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1935, getuid(): 10012
,08-23 17:04:27.327  1935  6337 I qtaguid : Tagging socket 83 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1935, getuid(): 10012
,08-23 17:04:27.367  1935  2130 I art     : Explicit concurrent mark sweep GC freed 45808(2MB) AllocSpace objects, 37(1477KB) LOS objects, 40% free, 14MB/24MB, paused 1.667ms total 80.892ms
,08-23 17:04:27.407  1018  1292 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-23 17:04:27.547  1935  6337 I qtaguid : Untagging socket 80
,08-23 17:04:27.557  1935  2130 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-23 17:04:27.627  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 17:04:27.627  6193  6250 I jxcore-log: 
,08-23 17:04:27.657  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 17:04:27.657  6193  6250 I jxcore-log: 
,08-23 17:04:27.657  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 17:04:27.657  6193  6250 I jxcore-log: 
,08-23 17:04:27.677  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 17:04:27.677  6193  6250 I jxcore-log: 
,08-23 17:04:27.687  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 17:04:27.687  6193  6250 I jxcore-log: 
,08-23 17:04:28.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:04:29.047   288   288 E SMD     : DCD OFF,
,08-23 17:04:29.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:04:29.497  1935  6338 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:04:29.497  1935  6338 I qtaguid : Tagging socket 80 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1935, getuid(): 10012
,08-23 17:04:29.707  1935  6338 I qtaguid : Untagging socket 80
,08-23 17:04:29.717  1935  2130 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-23 17:04:29.727  1018  3306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-23 17:04:30.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:04:30.367  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:30.367  1018  3311 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4110, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:04:30.367  1018  3311 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:04:30.367  1018  3311 D BatteryService: stay LED for charging
,08-23 17:04:30.367  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:30.377  1018  1018 I MotionRecognitionService: Plugged
08-23 17:04:30.377  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:04:30.377  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:04:30.377  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:04:30.377  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:04:30.377  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:04:30.387  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:04:30.387  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:04:30.397  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:30.397  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:30.397  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:31.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:04:31.737  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
08-23 17:04:31.737  6193  6250 I jxcore-log: 
,08-23 17:04:31.747  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
08-23 17:04:31.747  6193  6250 I jxcore-log: 
,08-23 17:04:31.757  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
08-23 17:04:31.757  6193  6250 I jxcore-log: 
,08-23 17:04:31.757  1018  1051 I PowerManagerService: [PWL] Off : 50s ago
,08-23 17:04:31.897  1018  2753 D SSRM:n  : SIOP:: AP = 390
,08-23 17:04:31.957  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-23 17:04:31.957  6193  6250 I jxcore-log: 
,08-23 17:04:32.037  1018  1125 I ActivityManager: Killing 5355:com.google.android.talk/u0a104 (adj 15): empty #31
,08-23 17:04:32.047   288   288 E SMD     : DCD OFF
,08-23 17:04:32.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:04:32.987  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-23 17:04:32.987  6193  6250 I jxcore-log: 
,08-23 17:04:33.107   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-23 17:04:33.287  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-23 17:04:33.287  6193  6250 I jxcore-log: 
,08-23 17:04:33.297  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js,
08-23 17:04:33.297  6193  6250 I jxcore-log: 
,08-23 17:04:33.547  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-23 17:04:33.547  6193  6250 I jxcore-log: 
,08-23 17:04:33.577  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-23 17:04:33.577  6193  6250 I jxcore-log: 
,08-23 17:04:33.587  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-23 17:04:33.587  6193  6250 I jxcore-log: 
,08-23 17:04:33.587  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-23 17:04:33.587  6193  6250 I jxcore-log: 
,08-23 17:04:33.607  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
08-23 17:04:33.607  6193  6250 I jxcore-log: 
,08-23 17:04:33.637  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
08-23 17:04:33.637  6193  6250 I jxcore-log: 
,08-23 17:04:33.737  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
08-23 17:04:33.737  6193  6250 I jxcore-log: 
,08-23 17:04:33.737  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
08-23 17:04:33.737  6193  6250 I jxcore-log: 
,08-23 17:04:33.767  6193  6250 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
08-23 17:04:33.767  6193  6250 I jxcore-log: 
,08-23 17:04:33.787  6193  6250 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-23 17:04:33.787  6193  6250 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-23 17:04:33.787  6193  6250 I jxcore-log: 
,08-23 17:04:35.057   288   288 E SMD     : DCD OFF
,08-23 17:04:38.057   288   288 E SMD     : DCD OFF
,08-23 17:04:40.427  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:40.427  1018  1292 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4142, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:04:40.427  1018  1292 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:04:40.427  1018  1292 D BatteryService: stay LED for charging
,08-23 17:04:40.427  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:40.437  1018  1018 I MotionRecognitionService: Plugged
08-23 17:04:40.437  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:04:40.437  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:04:40.437  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:04:40.437  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:04:40.437  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:04:40.447  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:40.447  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:04:40.447  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:04:40.457  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:40.457  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:41.057   288   288 E SMD     : DCD OFF
,08-23 17:04:41.197  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:04:41.917  1018  2753 D SSRM:n  : SIOP:: AP = 360
,08-23 17:04:42.497  1018  1338 E Watchdog: !@Sync 4
,08-23 17:04:43.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:04:44.057   288   288 E SMD     : DCD OFF,
,08-23 17:04:44.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:04:45.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:04:46.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:04:46.717  1018  1984 V SAMP_SPCM_test: CSC File load.. 
,08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-23 17:04:46.727  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-23 17:04:46.757  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-23 17:04:46.757  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
,08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-23 17:04:46.767  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time,
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
,08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-23 17:04:46.777  1018  1984 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-23 17:04:46.797  1018  1984 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-23 17:04:47.057   288   288 E SMD     : DCD OFF
,08-23 17:04:47.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:04:48.107   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-23 17:04:50.057   288   288 E SMD     : DCD OFF
,08-23 17:04:50.487  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:04:50.487  1018  3183 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4145, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:04:50.487  1018  3183 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:04:50.487  1018  3183 D BatteryService: stay LED for charging
,08-23 17:04:50.487  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:04:50.497  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-23 17:04:50.497  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:04:50.497  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:04:50.497  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
08-23 17:04:50.497  1018  1018 I MotionRecognitionService: Plugged
08-23 17:04:50.497  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:04:50.507  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:04:50.507  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:04:50.517  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:50.517  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:50.517  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:04:51.937  1018  2753 D SSRM:n  : SIOP:: AP = 340
,08-23 17:04:53.057   288   288 E SMD     : DCD OFF
,08-23 17:04:55.227  1018  1097 V AlarmManager: waitForAlarm result :4
,08-23 17:04:56.057   288   288 E SMD     : DCD OFF
,08-23 17:04:56.767  1018  1051 I PowerManagerService: [PWL] Off : 75s ago,
,08-23 17:04:59.067   288   288 E SMD     : DCD OFF
,08-23 17:04:59.987  1018  1097 V AlarmManager: waitForAlarm result :8
,08-23 17:05:00.557  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 17:05:00.557  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:05:00.557  1018  3158 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:05:00.557  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:00.557  1018  3158 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:05:00.557  1018  3158 D BatteryService: stay LED for charging
,08-23 17:05:00.557  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:00.557  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:05:00.557  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
08-23 17:05:00.567  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:05:00.567  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85,
,08-23 17:05:00.577  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:05:00.577  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:05:00.587  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:00.587  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:00.587  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:01.197  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:05:01.947  1018  2753 D SSRM:n  : SIOP:: AP = 330
,08-23 17:05:02.067   288   288 E SMD     : DCD OFF
,08-23 17:05:03.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:05:04.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:05:05.067   288   288 E SMD     : DCD OFF
,08-23 17:05:05.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:05:06.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:05:07.107   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:05:08.067   288   288 E SMD     : DCD OFF
,08-23 17:05:08.117   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-23 17:05:09.367  3856  4584 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 17:05:10.617  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:10.627  1018  1125 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:05:10.627  1018  1125 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:05:10.627  1018  1125 D BatteryService: stay LED for charging
08-23 17:05:10.627  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:10.627  1018  1018 I MotionRecognitionService: Plugged
08-23 17:05:10.627  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:05:10.627  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-23 17:05:10.627  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:10.627  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:05:10.627  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85,
,08-23 17:05:10.637  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:05:10.647  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:05:10.657  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:10.657  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:10.657  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:11.067   288   288 E SMD     : DCD OFF,
,08-23 17:05:11.967  1018  2753 D SSRM:n  : SIOP:: AP = 320
,08-23 17:05:12.357  1935  2580 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,08-23 17:05:12.497  1018  1338 E Watchdog: !@Sync 5,
,08-23 17:05:14.067   288   288 E SMD     : DCD OFF
,08-23 17:05:17.067   288   288 E SMD     : DCD OFF
,08-23 17:05:20.077   288   288 E SMD     : DCD OFF
,08-23 17:05:20.687  1018  3325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:05:20.687  1018  3325 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:05:20.687  1018  3325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:05:20.687  1018  3325 D BatteryService: stay LED for charging
08-23 17:05:20.687  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:20.687  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:05:20.687  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:05:20.687  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:20.687  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:20.687  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:05:20.697  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:05:20.697  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:05:20.697  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:05:20.717  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2,
08-23 17:05:20.717  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:05:20.717  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:21.197  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:05:21.977  1018  2753 D SSRM:n  : SIOP:: AP = 320
,08-23 17:05:23.077   288   288 E SMD     : DCD OFF
,08-23 17:05:26.077   288   288 E SMD     : DCD OFF
,08-23 17:05:26.767  1018  1051 I PowerManagerService: [PWL] Off : 105s ago
,08-23 17:05:28.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:05:29.077   288   288 E SMD     : DCD OFF
,08-23 17:05:29.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:05:30.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:05:30.747  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:30.747  1018  1480 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:05:30.747  1018  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:05:30.747  1018  1480 D BatteryService: stay LED for charging
,08-23 17:05:30.757  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:30.757  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:05:30.757  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:05:30.757  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:30.757  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:30.757  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:05:30.757  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:05:30.767  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:05:30.767  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:05:30.787  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:30.787  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:30.787  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:31.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:05:31.997  1018  2753 D SSRM:n  : SIOP:: AP = 320
,08-23 17:05:32.077   288   288 E SMD     : DCD OFF
,08-23 17:05:32.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:05:33.117   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-23 17:05:35.077   288   288 E SMD     : DCD OFF
,08-23 17:05:38.077   288   288 E SMD     : DCD OFF
,08-23 17:05:40.817  1018  1670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:40.817  1018  1670 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,08-23 17:05:40.817  1018  1670 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:05:40.817  1018  1670 D BatteryService: stay LED for charging
08-23 17:05:40.817  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:05:40.817  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:05:40.817  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:05:40.817  1018  1018 I MotionRecognitionService: Plugged
08-23 17:05:40.817  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
08-23 17:05:40.827  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:05:40.827  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85,
,08-23 17:05:40.837  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:05:40.837  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:05:40.847  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:40.847  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:05:40.847  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:41.077   288   288 E SMD     : DCD OFF
,08-23 17:05:41.197  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 17:05:42.017  1018  2753 D SSRM:n  : SIOP:: AP = 310
,08-23 17:05:42.497  1018  1338 E Watchdog: !@Sync 6
,08-23 17:05:44.087   288   288 E SMD     : DCD OFF
,08-23 17:05:47.087   288   288 E SMD     : DCD OFF
,08-23 17:05:50.087   288   288 E SMD     : DCD OFF
,08-23 17:05:50.877  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:05:50.887  1018  1031 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:05:50.887  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:05:50.887  1018  1031 D BatteryService: stay LED for charging
,08-23 17:05:50.887  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:05:50.887  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:05:50.887  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:05:50.887  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:05:50.887  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:05:50.887  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:05:50.887  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:05:50.897  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:05:50.897  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:05:50.907  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:50.907  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:05:50.907  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:05:52.027  1018  2753 D SSRM:n  : SIOP:: AP = 310
,08-23 17:05:53.087   288   288 E SMD     : DCD OFF
,08-23 17:05:56.087   288   288 E SMD     : DCD OFF,
,08-23 17:05:58.117   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 17:05:58.117   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 17:05:59.087   288   288 E SMD     : DCD OFF
,08-23 17:06:00.947  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:01.197  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 17:06:01.777  1018  1051 I PowerManagerService: [PWL] Off : 140s ago,
,08-23 17:06:02.067  1018  2753 D SSRM:n  : SIOP:: AP = 310,
,08-23 17:06:02.087   288   288 E SMD     : DCD OFF
,08-23 17:06:05.097   288   288 E SMD     : DCD OFF,
,08-23 17:06:08.097   288   288 E SMD     : DCD OFF
,08-23 17:06:08.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:09.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:10.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:11.017  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:11.017  1018  1125 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:06:11.017  1018  1125 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:06:11.017  1018  1125 D BatteryService: stay LED for charging
08-23 17:06:11.017  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:06:11.017  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:06:11.017  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:06:11.017  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:06:11.017  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:06:11.027  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:06:11.027  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:06:11.027  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:06:11.027  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:06:11.047  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:11.047  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:06:11.047  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:11.097   288   288 E SMD     : DCD OFF,
,08-23 17:06:11.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:06:12.077  1018  2753 D SSRM:n  : SIOP:: AP = 310
,08-23 17:06:12.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:12.497  1018  1338 E Watchdog: !@Sync 7
,08-23 17:06:13.117   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-23 17:06:14.097   288   288 E SMD     : DCD OFF
,08-23 17:06:17.097   288   288 E SMD     : DCD OFF
,08-23 17:06:18.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:19.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:20.097   288   288 E SMD     : DCD OFF
,08-23 17:06:20.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:06:21.077  1018  2778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:21.077  1018  2778 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4151, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:06:21.077  1018  2778 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:06:21.077  1018  2778 D BatteryService: stay LED for charging
08-23 17:06:21.077  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:06:21.087  1018  1018 I MotionRecognitionService: Plugged
08-23 17:06:21.087  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:06:21.087  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:21.087  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:06:21.087  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:06:21.087  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:06:21.097  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:06:21.097  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:06:21.117  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:06:21.117  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:21.117  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:21.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:06:21.197  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:06:21.987  1018  1097 V AlarmManager: waitForAlarm result :4
,08-23 17:06:21.997  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-23 17:06:21.997  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate,
,08-23 17:06:22.007  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 17:06:22.017  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 17:06:22.017  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:06:22.017  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-23 17:06:22.017  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-23 17:06:22.057  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:06:22.067  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:06:22.067  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:06:22.087  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:06:22.087  1018  2753 D SSRM:n  : SIOP:: AP = 310
,08-23 17:06:22.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:22.187  1018  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
08-23 17:06:22.187  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,08-23 17:06:23.097   288   288 E SMD     : DCD OFF
,08-23 17:06:23.117   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-23 17:06:23.677  1018  1097 V AlarmManager: waitForAlarm result :4
,08-23 17:06:23.697  1018  3317 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 17:06:23.697  1018  3317 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,08-23 17:06:23.697  1018  3317 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:06:23.697  1018  3317 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:06:23.697  1018  3317 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:06:23.717  1018  2778 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:06:23.727  1018  2778 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:06:23.727  1018  2778 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:06:23.727  1018  2778 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:06:23.747  3856  6395 I EventLogChimeraService: Aggregate from 1471962983626 (log), 1471962983626 (data)
,08-23 17:06:23.847  1018  1670 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:06:23.847  1018  1670 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:06:23.847  1018  1670 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:06:23.847  1018  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:06:23.867  1018  3158 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:06:23.867  1018  3158 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:06:23.867  1018  3158 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:06:23.867  1018  3158 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:06:23.877  1018  1336 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:06:23.877  1018  1336 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:06:23.877  1018  1336 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:06:23.877  1018  1336 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:06:23.887  1018  3183 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:06:23.887  1018  3183 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:06:23.887  1018  3183 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:06:23.887  1018  3183 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:06:23.917  3856  6396 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-23 17:06:23.937  3856  6396 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-23 17:06:26.107   288   288 E SMD     : DCD OFF
,08-23 17:06:26.137  1018  1044 W ProcessCpuTracker: Skipping unknown process pid 6397
,08-23 17:06:26.137  1018  1044 W ProcessCpuTracker: Skipping unknown process pid 6398
,08-23 17:06:29.107   288   288 E SMD     : DCD OFF
,08-23 17:06:31.147  1018  3317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:31.147  1018  3317 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4151, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:06:31.157  1018  3317 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:06:31.157  1018  3317 D BatteryService: stay LED for charging
,08-23 17:06:31.157  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:06:31.157  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:06:31.157  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:06:31.157  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:06:31.157  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:06:31.157  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:06:31.157  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:06:31.177  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:06:31.177  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:06:31.187  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2,
,08-23 17:06:31.187  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:31.187  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:32.107  1018  2753 D SSRM:n  : SIOP:: AP = 310
,08-23 17:06:32.107   288   288 E SMD     : DCD OFF
,08-23 17:06:33.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:06:34.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:35.107   288   288 E SMD     : DCD OFF
,08-23 17:06:35.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:36.117   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:06:37.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:38.107   288   288 E SMD     : DCD OFF,
,08-23 17:06:38.127   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-23 17:06:41.117   288   288 E SMD     : DCD OFF
,08-23 17:06:41.197  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:06:41.217  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:41.777  1018  1051 I PowerManagerService: [PWL] Off : 180s ago
,08-23 17:06:42.117  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:06:42.507  1018  1338 E Watchdog: !@Sync 8
,08-23 17:06:44.117   288   288 E SMD     : DCD OFF
,08-23 17:06:47.117   288   288 E SMD     : DCD OFF
,08-23 17:06:50.117   288   288 E SMD     : DCD OFF
,08-23 17:06:51.277  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:06:51.277  1018  3311 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:06:51.277  1018  3311 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:06:51.277  1018  3311 D BatteryService: stay LED for charging
,08-23 17:06:51.287  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-23 17:06:51.287  1018  1018 I MotionRecognitionService: Plugged
08-23 17:06:51.287  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:06:51.287  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:06:51.287  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:06:51.297  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-23 17:06:51.297  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:06:51.297  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:06:51.307  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:06:51.317  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:51.317  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:51.317  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:06:52.137  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:06:52.197  1018  1097 V AlarmManager: waitForAlarm result :4
,08-23 17:06:53.117   288   288 E SMD     : DCD OFF
,08-23 17:06:53.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:54.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:55.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:56.117   288   288 E SMD     : DCD OFF
,08-23 17:06:56.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:57.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:06:58.127   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-23 17:06:59.117   288   288 E SMD     : DCD OFF
,08-23 17:06:59.987  1018  1097 V AlarmManager: waitForAlarm result :8
,08-23 17:07:01.197  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:07:01.347  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:01.347  1018  3306 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:07:01.347  1018  3306 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:07:01.347  1018  3306 D BatteryService: stay LED for charging
08-23 17:07:01.347  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:07:01.357  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:07:01.357  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:07:01.357  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:07:01.357  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:07:01.357  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:07:01.357  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:07:01.367  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:07:01.367  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:07:01.377  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:07:01.377  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:07:01.377  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:07:02.127   288   288 E SMD     : DCD OFF
,08-23 17:07:02.147  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:07:05.127   288   288 E SMD     : DCD OFF
,08-23 17:07:08.127   288   288 E SMD     : DCD OFF
,08-23 17:07:11.127   288   288 E SMD     : DCD OFF
,08-23 17:07:11.407  1018  3325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:11.407  1018  3325 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:07:11.407  1018  3325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:07:11.407  1018  3325 D BatteryService: stay LED for charging
08-23 17:07:11.417  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:07:11.417  1018  1018 I MotionRecognitionService: Plugged
08-23 17:07:11.417  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:07:11.417  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:07:11.417  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:07:11.417  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:07:11.417  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:07:11.427  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:07:11.427  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:07:11.437  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:07:11.437  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:07:11.437  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:07:12.157  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:07:12.507  1018  1338 E Watchdog: !@Sync 9
,08-23 17:07:14.127   288   288 E SMD     : DCD OFF
,08-23 17:07:17.127   288   288 E SMD     : DCD OFF
,08-23 17:07:18.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:07:19.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:07:20.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:07:20.127   288   288 E SMD     : DCD OFF,
,08-23 17:07:21.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:07:21.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 17:07:21.477  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:22.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:07:22.197  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:07:23.127   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-23 17:07:23.127   288   288 E SMD     : DCD OFF
,08-23 17:07:26.137   288   288 E SMD     : DCD OFF
,08-23 17:07:26.777  1018  1051 I PowerManagerService: [PWL] Off : 225s ago
,08-23 17:07:29.137   288   288 E SMD     : DCD OFF
,08-23 17:07:31.537  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:31.537  1018  2739 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:07:31.537  1018  2739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:07:31.537  1018  2739 D BatteryService: stay LED for charging
,08-23 17:07:31.547  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:07:31.547  1018  1018 I MotionRecognitionService: Plugged
08-23 17:07:31.547  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:07:31.547  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:07:31.547  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:07:31.547  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:07:31.547  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:07:31.557  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:07:31.567  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:07:31.577  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:07:31.577  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:07:31.577  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:07:32.137   288   288 E SMD     : DCD OFF
,08-23 17:07:32.207  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:07:35.137   288   288 E SMD     : DCD OFF
,08-23 17:07:38.137   288   288 E SMD     : DCD OFF
,08-23 17:07:39.437  1018  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:07:39.437  1018  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-23 17:07:39.437  1018  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 17:07:39.447  1018  1088 I TLC_TIMA_PKM_initialize: initializing...
,08-23 17:07:39.447  1018  1088 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
08-23 17:07:39.447  1018  1088 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
08-23 17:07:39.447  1018  1088 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
08-23 17:07:39.447  1018  1088 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
08-23 17:07:39.447  1018  1088 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,08-23 17:07:39.447  1018  1088 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
08-23 17:07:39.447  1018  1088 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
08-23 17:07:39.447  1018  1088 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
08-23 17:07:39.447  1018  1088 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 17:07:39.477  1018  1088 D QSEECOMAPI: : Loaded image: APP id = 12
,08-23 17:07:39.477  1018  1088 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-23 17:07:39.487  1018  1088 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-23 17:07:41.137   288   288 E SMD     : DCD OFF
,08-23 17:07:41.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:07:41.387  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 17:07:41.387  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 17:07:41.387  1018  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:07:41.397  1018  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:07:41.607  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 17:07:41.607  1018  1030 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:07:41.607  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:07:41.607  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:07:41.607  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:07:41.607  1018  1030 D BatteryService: stay LED for charging
08-23 17:07:41.607  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:07:41.607  1018  1018 I MotionRecognitionService: Plugged
08-23 17:07:41.607  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:07:41.607  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:07:41.607  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:07:41.617  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:07:41.617  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:07:41.627  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2,
08-23 17:07:41.637  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:07:41.637  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:07:42.217  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:07:42.507  1018  1338 E Watchdog: !@Sync 10
,08-23 17:07:44.137   288   288 E SMD     : DCD OFF
,08-23 17:07:47.137   288   288 E SMD     : DCD OFF
,08-23 17:07:48.127   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 17:07:48.127   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 17:07:50.147   288   288 E SMD     : DCD OFF
,08-23 17:07:51.667  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:07:51.667  1018  3158 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:07:51.667  1018  3158 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:07:51.667  1018  3158 D BatteryService: stay LED for charging
,08-23 17:07:51.667  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:07:51.677  1018  1018 I MotionRecognitionService: Plugged
08-23 17:07:51.677  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:07:51.677  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:07:51.677  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:07:51.677  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-23 17:07:51.677  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:07:51.687  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:07:51.687  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:07:51.697  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2,
08-23 17:07:51.697  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:07:51.697  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:07:52.227  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:07:53.147   288   288 E SMD     : DCD OFF
,08-23 17:07:56.147   288   288 E SMD     : DCD OFF
,08-23 17:07:59.147   288   288 E SMD     : DCD OFF
,08-23 17:08:01.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:08:01.727  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:08:02.147   288   288 E SMD     : DCD OFF
,08-23 17:08:02.267  1018  2753 D SSRM:n  : SIOP:: AP = 300,
,08-23 17:08:03.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:04.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:05.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:05.147   288   288 E SMD     : DCD OFF
,08-23 17:08:06.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:07.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:08.127   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-23 17:08:08.147   288   288 E SMD     : DCD OFF
,08-23 17:08:11.157   288   288 E SMD     : DCD OFF
,08-23 17:08:11.797  1018  3317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:11.797  1018  3317 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4151, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:08:11.797  1018  3317 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:08:11.797  1018  3317 D BatteryService: stay LED for charging
,08-23 17:08:11.797  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:08:11.807  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:08:11.807  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:08:11.807  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:08:11.807  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:08:11.807  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:08:11.807  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:08:11.817  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:08:11.817  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:08:11.827  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:11.827  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:08:11.827  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:12.277  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:08:12.507  1018  1338 E Watchdog: !@Sync 11
,08-23 17:08:13.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:14.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:14.157   288   288 E SMD     : DCD OFF
,08-23 17:08:15.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:16.127   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:16.777  1018  1051 I PowerManagerService: [PWL] Off : 275s ago
,08-23 17:08:17.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:17.157   288   288 E SMD     : DCD OFF
,08-23 17:08:18.137   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-23 17:08:20.157   288   288 E SMD     : DCD OFF
,08-23 17:08:20.537  5628  5662 I PlayCommon: [963] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-23 17:08:20.537  1018  1336 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-23 17:08:20.537  1018  1336 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-23 17:08:20.537  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
08-23 17:08:20.547  1018  1292 W ActivityManager: userId = 0, bbcId = -10000
08-23 17:08:20.547  1018  1292 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-23 17:08:20.547  1018  1292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:08:20.547  1018  1292 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-23 17:08:20.547  1018  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:08:20.547  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:08:20.557  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 17:08:20.577  1018  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 17:08:20.577  1018  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-23 17:08:20.577  1018  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 17:08:20.577  1018  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 17:08:20.587  5628  5662 I PlayCommon: [963] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-23 17:08:20.587  5628  5662 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 17:08:20.597   278  1002 D EnterpriseController: uids 10028
08-23 17:08:20.597   278  1002 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 17:08:20.597   278  1002 D Netd    : getNetworkForDns: using netid 502 for uid 10028
,08-23 17:08:20.597  5628  5662 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 17:08:20.757  5628  5662 I PlayCommon: [963] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,08-23 17:08:21.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:08:21.867  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:21.867  1018  1336 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:08:21.867  1018  1336 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:08:21.867  1018  1336 D BatteryService: stay LED for charging
08-23 17:08:21.867  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:08:21.867  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:08:21.877  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:08:21.867  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
08-23 17:08:21.877  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:08:21.877  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:08:21.877  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
08-23 17:08:21.877  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:21.887  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:08:21.887  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:08:21.897  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:21.897  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:22.297  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:08:23.157   288   288 E SMD     : DCD OFF
,08-23 17:08:26.157   288   288 E SMD     : DCD OFF
,08-23 17:08:28.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:29.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:29.157   288   288 E SMD     : DCD OFF
,08-23 17:08:30.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:31.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:31.927  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:31.937  1018  1292 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4151, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:08:31.937  1018  1292 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:08:31.937  1018  1292 D BatteryService: stay LED for charging
,08-23 17:08:31.937  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:08:31.937  1018  1018 I MotionRecognitionService: Plugged,
,08-23 17:08:31.937  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:08:31.937  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:08:31.937  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:08:31.937  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:08:31.937  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85,
,08-23 17:08:31.947  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:08:31.947  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:08:31.967  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:31.967  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:31.967  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:32.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:32.157   288   288 E SMD     : DCD OFF,
,08-23 17:08:32.307  1018  2753 D SSRM:n  : SIOP:: AP = 300,
,08-23 17:08:33.137   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-23 17:08:35.167   288   288 E SMD     : DCD OFF
,08-23 17:08:38.167   288   288 E SMD     : DCD OFF
,08-23 17:08:41.167   288   288 E SMD     : DCD OFF
,08-23 17:08:41.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 17:08:41.997  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:08:41.997  1018  3306 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:08:41.997  1018  3306 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:08:41.997  1018  3306 D BatteryService: stay LED for charging
,08-23 17:08:41.997  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:08:42.007  1018  1018 I MotionRecognitionService: Plugged
08-23 17:08:42.007  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:08:42.007  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:08:42.007  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:08:42.007  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:08:42.007  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:08:42.017  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:08:42.017  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:08:42.027  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:42.027  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:08:42.027  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:42.317  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:08:42.507  1018  1338 E Watchdog: !@Sync 12
,08-23 17:08:44.167   288   288 E SMD     : DCD OFF
,08-23 17:08:45.417  5628  5772 I PlayCommon: [981] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-23 17:08:45.417  5628  5772 I PlayCommon: [981] com.google.android.play.a.l.e(789): No file ready to send
,08-23 17:08:47.167   288   288 E SMD     : DCD OFF
,08-23 17:08:48.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:49.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:50.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:08:50.167   288   288 E SMD     : DCD OFF
,08-23 17:08:51.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:08:52.067  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:08:52.067  1018  1125 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4151, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:08:52.067  1018  1125 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:08:52.067  1018  1125 D BatteryService: stay LED for charging
08-23 17:08:52.067  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:08:52.067  1018  1018 I MotionRecognitionService: Plugged
08-23 17:08:52.067  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:08:52.067  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:08:52.067  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:08:52.067  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:08:52.077  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:08:52.087  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:08:52.087  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:08:52.097  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:52.097  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:08:52.097  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:08:52.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:08:52.337  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:08:53.137   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-23 17:08:53.167   288   288 E SMD     : DCD OFF
,08-23 17:08:56.167   288   288 E SMD     : DCD OFF
,08-23 17:08:59.177   288   288 E SMD     : DCD OFF
,08-23 17:09:01.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 17:09:02.127  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:09:02.127  1018  1480 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:09:02.127  1018  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:09:02.127  1018  1480 D BatteryService: stay LED for charging
08-23 17:09:02.127  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:09:02.127  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:09:02.127  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:09:02.137  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:09:02.137  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:09:02.137  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:09:02.137  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85,
,08-23 17:09:02.147  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:09:02.147  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:09:02.157  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:02.157  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:09:02.157  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:02.177   288   288 E SMD     : DCD OFF
,08-23 17:09:02.347  1018  2753 D SSRM:n  : SIOP:: AP = 300,
,08-23 17:09:05.177   288   288 E SMD     : DCD OFF
,08-23 17:09:08.177   288   288 E SMD     : DCD OFF
,08-23 17:09:11.177   288   288 E SMD     : DCD OFF
,08-23 17:09:11.777  1018  1051 I PowerManagerService: [PWL] Off : 330s ago
,08-23 17:09:12.197  1018  3317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:09:12.197  1018  3317 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:09:12.197  1018  3317 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:09:12.197  1018  3317 D BatteryService: stay LED for charging
08-23 17:09:12.197  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:09:12.197  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:09:12.197  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:09:12.197  1018  1018 I MotionRecognitionService: Plugged
08-23 17:09:12.197  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:09:12.197  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
08-23 17:09:12.197  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:09:12.207  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:09:12.207  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:09:12.217  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2,
08-23 17:09:12.217  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:09:12.217  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:12.357  1018  2753 D SSRM:n  : SIOP:: AP = 300,
,08-23 17:09:12.507  1018  1338 E Watchdog: !@Sync 13
,08-23 17:09:13.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:09:14.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:09:14.177   288   288 E SMD     : DCD OFF
,08-23 17:09:15.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:09:16.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:09:17.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:09:17.177   288   288 E SMD     : DCD OFF
,08-23 17:09:18.137   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-23 17:09:20.187   288   288 E SMD     : DCD OFF
,08-23 17:09:21.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:09:22.257  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 17:09:22.257  1018  3158 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4151, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:09:22.257  1018  3158 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:09:22.257  1018  3158 D BatteryService: stay LED for charging
08-23 17:09:22.257  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:09:22.257  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:09:22.257  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:09:22.267  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:09:22.267  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-23 17:09:22.267  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:09:22.267  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:09:22.267  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:22.277  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:09:22.277  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:09:22.287  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:22.287  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:22.367  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:09:23.187   288   288 E SMD     : DCD OFF
,08-23 17:09:26.187   288   288 E SMD     : DCD OFF
,08-23 17:09:29.187   288   288 E SMD     : DCD OFF
,08-23 17:09:32.187   288   288 E SMD     : DCD OFF
,08-23 17:09:32.317  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:09:32.387  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:09:35.187   288   288 E SMD     : DCD OFF
,08-23 17:09:38.187   288   288 E SMD     : DCD OFF
,08-23 17:09:41.187   288   288 E SMD     : DCD OFF
,08-23 17:09:41.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:09:42.387  1018  1670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 17:09:42.387  1018  1670 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:09:42.387  1018  1670 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:09:42.387  1018  1670 D BatteryService: stay LED for charging
08-23 17:09:42.387  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:09:42.387  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:09:42.387  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:09:42.397  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:09:42.397  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:09:42.397  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:09:42.397  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:09:42.407  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:09:42.407  1018  2753 D SSRM:n  : SIOP:: AP = 300
08-23 17:09:42.407  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:09:42.417  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:42.417  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:42.417  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:09:42.507  1018  1338 E Watchdog: !@Sync 14
,08-23 17:09:43.137   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 17:09:43.137   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 17:09:44.197   288   288 E SMD     : DCD OFF
,08-23 17:09:47.197   288   288 E SMD     : DCD OFF
,08-23 17:09:50.197   288   288 E SMD     : DCD OFF
,08-23 17:09:52.447  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:09:52.457  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:09:53.197   288   288 E SMD     : DCD OFF
,08-23 17:09:56.197   288   288 E SMD     : DCD OFF,
,08-23 17:09:59.197   288   288 E SMD     : DCD OFF
,08-23 17:09:59.987  1018  1097 V AlarmManager: waitForAlarm result :8
,08-23 17:09:59.987  1018  1097 V AlarmManager: No more alarm at this time.nowELAPSED=455735 batch.start=801066
,08-23 17:09:59.997  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-23 17:09:59.997  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 17:09:59.997  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-23 17:09:59.997  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-23 17:10:00.007  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:10:00.007  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-23 17:10:00.007  1179  1179 I KeyguardEffectViewController: *** don't update sliding image ***
,08-23 17:10:00.047  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:10:00.047  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:10:00.057  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:10:00.067  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-23 17:10:01.207  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:10:02.197   288   288 E SMD     : DCD OFF
,08-23 17:10:02.467  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:10:02.527  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:10:03.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:10:04.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:05.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:05.207   288   288 E SMD     : DCD OFF
,08-23 17:10:06.137   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:07.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:08.147   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-23 17:10:08.207   288   288 E SMD     : DCD OFF
,08-23 17:10:11.207   288   288 E SMD     : DCD OFF
,08-23 17:10:11.797  1018  1051 I PowerManagerService: [PWL] Off : 390s ago
,08-23 17:10:12.497  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:10:12.507  1018  1338 E Watchdog: !@Sync 15
,08-23 17:10:12.597  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:10:12.597  1018  3311 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:10:12.597  1018  3311 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:10:12.597  1018  3311 D BatteryService: stay LED for charging
08-23 17:10:12.597  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:10:12.597  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:10:12.597  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:10:12.607  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-23 17:10:12.607  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:10:12.607  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:10:12.607  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:10:12.617  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:10:12.617  2652  2751 D HeadsetStateMachine: Disconnected process message: 10,
,08-23 17:10:12.627  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:10:12.627  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:10:12.627  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:10:13.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:14.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:14.207   288   288 E SMD     : DCD OFF
,08-23 17:10:15.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:16.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:10:17.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:10:17.207   288   288 E SMD     : DCD OFF
,08-23 17:10:18.147   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-23 17:10:20.207   288   288 E SMD     : DCD OFF
,08-23 17:10:21.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 17:10:22.537  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:10:22.657  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:10:23.207   288   288 E SMD     : DCD OFF
,08-23 17:10:26.207   288   288 E SMD     : DCD OFF
,08-23 17:10:28.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:10:29.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:10:29.217   288   288 E SMD     : DCD OFF
,08-23 17:10:30.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:31.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 17:10:31.167   311   311 I bootchecker: bootchecker wake up!!
,08-23 17:10:32.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:32.217   288   288 E SMD     : DCD OFF
,08-23 17:10:32.567  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:10:32.727  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:10:33.147   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-23 17:10:35.217   288   288 E SMD     : DCD OFF
,08-23 17:10:38.217   288   288 E SMD     : DCD OFF
,08-23 17:10:41.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:10:41.217   288   288 E SMD     : DCD OFF
,08-23 17:10:42.507  1018  1338 E Watchdog: !@Sync 16
,08-23 17:10:42.577  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:10:42.797  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:10:44.217   288   288 E SMD     : DCD OFF
,08-23 17:10:47.217   288   288 E SMD     : DCD OFF
,08-23 17:10:48.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:49.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:50.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:50.217   288   288 E SMD     : DCD OFF
,08-23 17:10:51.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:52.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:10:52.607  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:10:52.857  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:10:53.147   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-23 17:10:53.227   288   288 E SMD     : DCD OFF,
,08-23 17:10:56.227   288   288 E SMD     : DCD OFF
,08-23 17:10:59.227   288   288 E SMD     : DCD OFF
,08-23 17:10:59.987  1018  1097 V AlarmManager: waitForAlarm result :8
,08-23 17:11:01.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:11:02.227   288   288 E SMD     : DCD OFF
,08-23 17:11:02.647  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:11:02.927  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:11:05.227   288   288 E SMD     : DCD OFF
,08-23 17:11:08.227   288   288 E SMD     : DCD OFF
,08-23 17:11:11.227   288   288 E SMD     : DCD OFF
,08-23 17:11:12.507  1018  1338 E Watchdog: !@Sync 17
,08-23 17:11:12.687  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:11:12.987  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:11:13.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:11:14.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:11:14.237   288   288 E SMD     : DCD OFF
,08-23 17:11:15.147   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:11:16.157   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:11:16.857  1018  1051 I PowerManagerService: [PWL] Off : 455s ago,
,08-23 17:11:17.157   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 17:11:17.237   288   288 E SMD     : DCD OFF
,08-23 17:11:18.157   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-23 17:11:20.237   288   288 E SMD     : DCD OFF
,08-23 17:11:21.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:11:22.717  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:11:23.057  1018  1670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:11:23.057  1018  1670 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:11:23.057  1018  1670 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:11:23.057  1018  1670 D BatteryService: stay LED for charging,
08-23 17:11:23.057  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:11:23.057  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:11:23.057  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:11:23.067  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-23 17:11:23.067  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:11:23.067  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:11:23.067  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85,
,08-23 17:11:23.077  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:11:23.077  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:11:23.087  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:11:23.087  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:11:23.087  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:11:23.237   288   288 E SMD     : DCD OFF
,08-23 17:11:26.237   288   288 E SMD     : DCD OFF
,08-23 17:11:29.237   288   288 E SMD     : DCD OFF
,08-23 17:11:32.237   288   288 E SMD     : DCD OFF,
,08-23 17:11:32.737  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:11:33.117  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:11:35.247   288   288 E SMD     : DCD OFF
,08-23 17:11:38.247   288   288 E SMD     : DCD OFF
,08-23 17:11:41.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:11:41.247   288   288 E SMD     : DCD OFF
,08-23 17:11:42.507  1018  1338 E Watchdog: !@Sync 18,
,08-23 17:11:42.747  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:11:43.157   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-23 17:11:43.157   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-23 17:11:43.187  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:11:44.247   288   288 E SMD     : DCD OFF
,08-23 17:11:47.247   288   288 E SMD     : DCD OFF
,08-23 17:11:50.247   288   288 E SMD     : DCD OFF
,08-23 17:11:52.757  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:11:53.247   288   288 E SMD     : DCD OFF
,08-23 17:11:53.257  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:11:53.257  1018  3306 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:11:53.257  1018  3306 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:11:53.257  1018  3306 D BatteryService: stay LED for charging
08-23 17:11:53.257  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:11:53.257  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:11:53.257  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:11:53.257  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:11:53.257  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:11:53.267  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:11:53.267  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:11:53.277  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:11:53.277  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:11:53.287  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:11:53.287  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:11:53.287  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:11:56.257   288   288 E SMD     : DCD OFF
,08-23 17:11:59.257   288   288 E SMD     : DCD OFF
,08-23 17:12:01.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:12:02.257   288   288 E SMD     : DCD OFF
,08-23 17:12:02.797  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:12:03.317  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:12:03.317  1018  1336 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:12:03.317  1018  1336 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:12:03.317  1018  1336 D BatteryService: stay LED for charging
,08-23 17:12:03.317  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:12:03.327  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:12:03.327  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:12:03.327  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:12:03.327  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:12:03.327  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:12:03.327  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:12:03.337  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:12:03.337  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:12:03.357  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:12:03.357  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:12:03.357  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:12:05.257   288   288 E SMD     : DCD OFF
,08-23 17:12:08.157   315   315 I Atfwd_Daemon: Stop the daemon....,
,08-23 17:12:08.257   288   288 E SMD     : DCD OFF
,08-23 17:12:11.257   288   288 E SMD     : DCD OFF
,08-23 17:12:12.507  1018  1338 E Watchdog: !@Sync 19
,08-23 17:12:12.827  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:12:13.387  1018  2778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:12:14.257   288   288 E SMD     : DCD OFF
,08-23 17:12:17.267   288   288 E SMD     : DCD OFF
,08-23 17:12:20.267   288   288 E SMD     : DCD OFF
,08-23 17:12:21.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:12:22.837  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:12:23.267   288   288 E SMD     : DCD OFF
,08-23 17:12:23.457  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:12:23.457  1018  3158 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:12:23.457  1018  3158 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:12:23.457  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:12:23.457  1018  3158 D BatteryService: stay LED for charging
,08-23 17:12:23.457  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:12:23.457  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:12:23.457  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:12:23.467  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:12:23.467  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:12:23.467  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:12:23.477  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:12:23.477  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:12:23.487  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:12:23.487  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:12:23.487  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:12:26.267   288   288 E SMD     : DCD OFF,
,08-23 17:12:26.867  1018  1051 I PowerManagerService: [PWL] Off : 525s ago
,08-23 17:12:29.267   288   288 E SMD     : DCD OFF
,08-23 17:12:32.267   288   288 E SMD     : DCD OFF,
,08-23 17:12:32.847  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:12:33.517  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:12:35.267   288   288 E SMD     : DCD OFF
,08-23 17:12:38.267   288   288 E SMD     : DCD OFF
,08-23 17:12:39.437  1018  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:12:39.437  1018  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-23 17:12:39.437  1018  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 17:12:40.257  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 17:12:40.257  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 17:12:40.267  1018  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:12:40.267  1018  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:12:41.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:12:41.277   288   288 E SMD     : DCD OFF
,08-23 17:12:42.517  1018  1338 E Watchdog: !@Sync 20
,08-23 17:12:42.887  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:12:43.587  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:12:44.277   288   288 E SMD     : DCD OFF
,08-23 17:12:47.277   288   288 E SMD     : DCD OFF
,08-23 17:12:50.277   288   288 E SMD     : DCD OFF
,08-23 17:12:52.917  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:12:53.277   288   288 E SMD     : DCD OFF
,08-23 17:12:53.647  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:12:53.657  1018  1031 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
08-23 17:12:53.657  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:12:53.657  1018  1031 D BatteryService: stay LED for charging
08-23 17:12:53.657  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:12:53.657  1018  1018 I MotionRecognitionService: Plugged
08-23 17:12:53.657  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:12:53.657  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:12:53.657  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:12:53.657  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:12:53.657  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:12:53.667  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:12:53.667  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:12:53.687  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:12:53.687  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:12:53.687  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:12:56.277   288   288 E SMD     : DCD OFF
,08-23 17:12:59.277   288   288 E SMD     : DCD OFF
,08-23 17:13:01.217  1018  2795 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 17:13:02.277   288   288 E SMD     : DCD OFF
,08-23 17:13:02.927  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:13:03.717  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:13:03.717  1018  1030 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:13:03.717  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:13:03.717  1018  1030 D BatteryService: stay LED for charging
,08-23 17:13:03.717  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:13:03.717  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:13:03.717  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:13:03.727  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:13:03.727  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:13:03.727  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:13:03.727  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:13:03.737  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:13:03.737  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:13:03.747  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:13:03.747  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:13:03.747  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:13:05.287   288   288 E SMD     : DCD OFF
,08-23 17:13:08.287   288   288 E SMD     : DCD OFF,
,08-23 17:13:11.287   288   288 E SMD     : DCD OFF
,08-23 17:13:12.517  1018  1338 E Watchdog: !@Sync 21
,08-23 17:13:12.957  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:13:13.777  1018  1670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 17:13:13.777  1018  1670 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:13:13.777  1018  1670 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:13:13.777  1018  1670 D BatteryService: stay LED for charging
08-23 17:13:13.777  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:13:13.787  1018  1018 I MotionRecognitionService: Plugged
08-23 17:13:13.787  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:13:13.787  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-23 17:13:13.787  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-23 17:13:13.787  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:13:13.787  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:13:13.797  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:13:13.797  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:13:13.807  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:13:13.807  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:13:13.807  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:13:14.287   288   288 E SMD     : DCD OFF
,08-23 17:13:17.287   288   288 E SMD     : DCD OFF
,08-23 17:13:20.287   288   288 E SMD     : DCD OFF
,08-23 17:13:22.997  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:13:23.287   288   288 E SMD     : DCD OFF
,08-23 17:13:23.837  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:13:26.297   288   288 E SMD     : DCD OFF
,08-23 17:13:29.297   288   288 E SMD     : DCD OFF
,08-23 17:13:32.297   288   288 E SMD     : DCD OFF
,08-23 17:13:33.027  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:13:33.907  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:13:35.297   288   288 E SMD     : DCD OFF
,08-23 17:13:38.297   288   288 E SMD     : DCD OFF
,08-23 17:13:41.297   288   288 E SMD     : DCD OFF
,08-23 17:13:41.867  1018  1051 I PowerManagerService: [PWL] Off : 600s ago
,08-23 17:13:42.517  1018  1338 E Watchdog: !@Sync 22
,08-23 17:13:43.057  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:13:43.977  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:13:44.297   288   288 E SMD     : DCD OFF
,08-23 17:13:45.447  5628  5772 I PlayCommon: [981] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-23 17:13:45.447  5628  5772 I PlayCommon: [981] com.google.android.play.a.l.e(789): No file ready to send
,08-23 17:13:47.307   288   288 E SMD     : DCD OFF
,08-23 17:13:50.307   288   288 E SMD     : DCD OFF
,08-23 17:13:53.097  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:13:53.307   288   288 E SMD     : DCD OFF
,08-23 17:13:54.037  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 17:13:54.037  1018  3183 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:13:54.037  1018  3183 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:13:54.037  1018  3183 D BatteryService: stay LED for charging
08-23 17:13:54.037  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:13:54.037  1018  1018 I MotionRecognitionService: Plugged
08-23 17:13:54.037  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:13:54.047  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:13:54.047  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:13:54.047  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:13:54.047  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:13:54.047  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:13:54.047  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:13:54.067  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:13:54.067  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:13:54.067  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:13:56.307   288   288 E SMD     : DCD OFF
,08-23 17:13:59.307   288   288 E SMD     : DCD OFF
,08-23 17:14:02.307   288   288 E SMD     : DCD OFF
,08-23 17:14:03.127  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:14:04.107  1018  3325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:14:04.107  1018  3325 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:14:04.107  1018  3325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:14:04.107  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:14:04.107  1018  3325 D BatteryService: stay LED for charging
,08-23 17:14:04.107  1018  1018 I MotionRecognitionService: Plugged
08-23 17:14:04.107  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:14:04.117  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:14:04.117  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:14:04.117  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:14:04.117  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:14:04.127  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:14:04.127  2652  2751 D HeadsetStateMachine: Disconnected process message: 10,
,08-23 17:14:04.137  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2,
08-23 17:14:04.137  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:14:04.137  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:14:05.307   288   288 E SMD     : DCD OFF
,08-23 17:14:08.307   288   288 E SMD     : DCD OFF
,08-23 17:14:11.317   288   288 E SMD     : DCD OFF,
,08-23 17:14:12.517  1018  1338 E Watchdog: !@Sync 23
,08-23 17:14:13.157  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:14:14.167  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:14:14.317   288   288 E SMD     : DCD OFF
,08-23 17:14:17.317   288   288 E SMD     : DCD OFF
,08-23 17:14:20.317   288   288 E SMD     : DCD OFF
,08-23 17:14:23.167  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:14:23.317   288   288 E SMD     : DCD OFF
,08-23 17:14:24.237  1018  2778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:14:26.317   288   288 E SMD     : DCD OFF,
,08-23 17:14:29.317   288   288 E SMD     : DCD OFF
,08-23 17:14:32.327   288   288 E SMD     : DCD OFF
,08-23 17:14:33.187  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:14:34.297  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:14:35.327   288   288 E SMD     : DCD OFF
,08-23 17:14:38.327   288   288 E SMD     : DCD OFF
,08-23 17:14:41.327   288   288 E SMD     : DCD OFF
,08-23 17:14:42.517  1018  1338 E Watchdog: !@Sync 24
,08-23 17:14:43.217  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:14:44.327   288   288 E SMD     : DCD OFF
,08-23 17:14:44.367  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:14:47.327   288   288 E SMD     : DCD OFF
,08-23 17:14:50.327   288   288 E SMD     : DCD OFF
,08-23 17:14:53.227  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:14:53.337   288   288 E SMD     : DCD OFF
,08-23 17:14:54.427  1018  1670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:14:56.337   288   288 E SMD     : DCD OFF,
,08-23 17:14:59.337   288   288 E SMD     : DCD OFF
,08-23 17:15:01.927  1018  1051 I PowerManagerService: [PWL] Off : 680s ago
,08-23 17:15:02.337   288   288 E SMD     : DCD OFF
,08-23 17:15:03.267  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:15:04.497  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:15:05.337   288   288 E SMD     : DCD OFF
,08-23 17:15:08.337   288   288 E SMD     : DCD OFF
,08-23 17:15:11.337   288   288 E SMD     : DCD OFF
,08-23 17:15:12.517  1018  1338 E Watchdog: !@Sync 25,
,08-23 17:15:13.277  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:15:14.347   288   288 E SMD     : DCD OFF
,08-23 17:15:14.557  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:15:14.557  1018  1125 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4143, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:15:14.557  1018  1125 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:15:14.557  1018  1125 D BatteryService: stay LED for charging
,08-23 17:15:14.557  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:15:14.567  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:15:14.567  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:15:14.567  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:15:14.567  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:15:14.567  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:15:14.567  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:15:14.577  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:15:14.577  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:15:14.587  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:15:14.587  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:15:14.597  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:15:17.347   288   288 E SMD     : DCD OFF
,08-23 17:15:20.347   288   288 E SMD     : DCD OFF
,08-23 17:15:23.287  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:15:23.347   288   288 E SMD     : DCD OFF
,08-23 17:15:24.627  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:15:24.627  1018  3306 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:15:24.627  1018  3306 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:15:24.627  1018  3306 D BatteryService: stay LED for charging
08-23 17:15:24.627  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:15:24.627  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:15:24.627  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:15:24.637  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:15:24.637  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:15:24.637  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:15:24.637  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:15:24.647  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:15:24.647  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:15:24.657  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:15:24.657  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:15:24.657  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:15:26.347   288   288 E SMD     : DCD OFF
,08-23 17:15:29.347   288   288 E SMD     : DCD OFF
,08-23 17:15:32.347   288   288 E SMD     : DCD OFF
,08-23 17:15:33.327  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:15:34.687  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:15:35.357   288   288 E SMD     : DCD OFF,
,08-23 17:15:38.357   288   288 E SMD     : DCD OFF
,08-23 17:15:41.357   288   288 E SMD     : DCD OFF
,08-23 17:15:42.517  1018  1338 E Watchdog: !@Sync 26,
,08-23 17:15:43.337  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:15:44.357   288   288 E SMD     : DCD OFF
,08-23 17:15:44.757  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:15:44.757  1018  1481 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:15:44.757  1018  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:15:44.757  1018  1481 D BatteryService: stay LED for charging
08-23 17:15:44.757  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:15:44.767  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:15:44.767  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:15:44.767  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:15:44.767  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:15:44.767  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:15:44.767  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85,
,08-23 17:15:44.777  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:15:44.777  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:15:44.787  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2,
08-23 17:15:44.787  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:15:44.787  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:15:45.317  1018  1097 V AlarmManager: waitForAlarm result :8
,08-23 17:15:47.357   288   288 E SMD     : DCD OFF
,08-23 17:15:50.357   288   288 E SMD     : DCD OFF
,08-23 17:15:53.357  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:15:53.357   288   288 E SMD     : DCD OFF,
,08-23 17:15:54.827  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:15:54.827  1018  3158 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:15:54.827  1018  3158 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:15:54.827  1018  3158 D BatteryService: stay LED for charging
08-23 17:15:54.827  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:15:54.827  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:15:54.827  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:15:54.827  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:15:54.827  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:15:54.827  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:15:54.837  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:15:54.837  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:15:54.847  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:15:54.857  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:15:54.857  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:15:54.857  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:15:56.367   288   288 E SMD     : DCD OFF
,08-23 17:15:59.367   288   288 E SMD     : DCD OFF
,08-23 17:16:02.367   288   288 E SMD     : DCD OFF
,08-23 17:16:03.377  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:16:04.887  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:16:04.887  1018  3183 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:16:04.887  1018  3183 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:16:04.887  1018  3183 D BatteryService: stay LED for charging
,08-23 17:16:04.887  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:16:04.897  1018  1018 I MotionRecognitionService: Plugged
08-23 17:16:04.897  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:16:04.897  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:16:04.897  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:16:04.897  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:16:04.897  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85,
,08-23 17:16:04.907  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:16:04.907  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:16:04.917  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2,
08-23 17:16:04.917  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:16:04.917  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:16:05.367   288   288 E SMD     : DCD OFF
,08-23 17:16:08.367   288   288 E SMD     : DCD OFF
,08-23 17:16:11.367   288   288 E SMD     : DCD OFF
,08-23 17:16:12.517  1018  1338 E Watchdog: !@Sync 27
,08-23 17:16:13.387  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:16:14.367   288   288 E SMD     : DCD OFF
,08-23 17:16:14.957  1018  3325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 17:16:14.957  1018  3325 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:16:14.957  1018  3325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:16:14.957  1018  3325 D BatteryService: stay LED for charging
08-23 17:16:14.957  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:16:14.957  1018  1018 I MotionRecognitionService: Plugged
08-23 17:16:14.957  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:16:14.957  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:16:14.957  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:16:14.957  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:16:14.957  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:16:14.967  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:16:14.967  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:16:14.977  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:16:14.987  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:16:14.987  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:16:17.377   288   288 E SMD     : DCD OFF
,08-23 17:16:20.377   288   288 E SMD     : DCD OFF
,08-23 17:16:23.377   288   288 E SMD     : DCD OFF
,08-23 17:16:23.417  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:16:25.017  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:16:26.377   288   288 E SMD     : DCD OFF
,08-23 17:16:26.927  1018  1051 I PowerManagerService: [PWL] Off : 765s ago
,08-23 17:16:29.377   288   288 E SMD     : DCD OFF
,08-23 17:16:32.377   288   288 E SMD     : DCD OFF
,08-23 17:16:33.447  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:16:35.087  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:16:35.377   288   288 E SMD     : DCD OFF
,08-23 17:16:38.387   288   288 E SMD     : DCD OFF
,08-23 17:16:41.387   288   288 E SMD     : DCD OFF
,08-23 17:16:42.517  1018  1338 E Watchdog: !@Sync 28
,08-23 17:16:43.477  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:16:44.387   288   288 E SMD     : DCD OFF
,08-23 17:16:45.147  1018  1670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:16:45.147  1018  1670 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:16:45.147  1018  1670 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:16:45.147  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:16:45.147  1018  1670 D BatteryService: stay LED for charging
,08-23 17:16:45.157  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:16:45.157  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:16:45.157  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:16:45.157  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:16:45.157  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:16:45.157  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:16:45.167  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:16:45.167  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:16:45.177  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:16:45.177  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:16:45.177  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:16:47.387   288   288 E SMD     : DCD OFF
,08-23 17:16:50.387   288   288 E SMD     : DCD OFF
,08-23 17:16:53.387   288   288 E SMD     : DCD OFF
,08-23 17:16:53.517  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:16:55.217  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:16:55.217  1018  2739 D BatteryService: level:85, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:16:55.217  1018  2739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:16:55.217  1018  2739 D BatteryService: stay LED for charging
08-23 17:16:55.217  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:16:55.217  1018  1018 I MotionRecognitionService: Plugged
08-23 17:16:55.217  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:16:55.217  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:16:55.217  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:16:55.217  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:16:55.217  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 85
,08-23 17:16:55.227  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:16:55.227  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:16:55.247  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:16:55.247  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
08-23 17:16:55.247  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:85 status:2 health:2
,08-23 17:16:56.387   288   288 E SMD     : DCD OFF
,08-23 17:16:59.387   288   288 E SMD     : DCD OFF
,08-23 17:17:02.397   288   288 E SMD     : DCD OFF
,08-23 17:17:03.557  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:17:05.277  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:17:05.397   288   288 E SMD     : DCD OFF,
,08-23 17:17:08.397   288   288 E SMD     : DCD OFF
,08-23 17:17:11.397   288   288 E SMD     : DCD OFF
,08-23 17:17:12.517  1018  1338 E Watchdog: !@Sync 29
,08-23 17:17:13.587  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:17:14.397   288   288 E SMD     : DCD OFF
,08-23 17:17:15.337  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:17:15.347  1018  1125 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:17:15.347  1018  1125 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:17:15.347  1018  1125 D BatteryService: stay LED for charging
,08-23 17:17:15.347  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:17:15.347  1018  1051 D PowerManagerService: [PSM] lowPowerModeEnabled: false (mLowPowerModeSetting: false, mAutoLowPowerModeConfigured: false, mBatteryLevel: 84, mLowBatteryTriggerLevel: 0)
,08-23 17:17:15.347  1018  1018 I MotionRecognitionService: Plugged
08-23 17:17:15.347  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:17:15.347  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:17:15.347  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:17:15.357  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:17:15.347  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-23 17:17:15.357  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:17:15.357  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:15.357  1018  2753 D U       : limitLiveThumbnail:: limit = true
08-23 17:17:15.357  1018  2753 D U       : broadcastSiopChangedIntent:: FLASH = false, CAMERA = false, RECORDING = false, RECORDING_FPS = false, SMARTBONDING = false, LIVETHUMBNAIL = true
,08-23 17:17:15.357  1018  2753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.U.co:-1 com.android.server.ssrm.ad.i:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,08-23 17:17:15.357  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 17:17:15.367  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:17:15.377  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2,
08-23 17:17:15.377  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:17.397   288   288 E SMD     : DCD OFF
,08-23 17:17:20.397   288   288 E SMD     : DCD OFF,
,08-23 17:17:23.397   288   288 E SMD     : DCD OFF
,08-23 17:17:23.627  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:17:25.407  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:17:25.407  1018  2739 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:17:25.407  1018  2739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:17:25.407  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:17:25.407  1018  2739 D BatteryService: stay LED for charging
,08-23 17:17:25.417  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:17:25.417  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:17:25.417  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:17:25.417  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:17:25.417  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:17:25.417  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:17:25.427  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:17:25.427  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:17:25.437  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:25.437  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:17:25.437  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:26.407   288   288 E SMD     : DCD OFF
,08-23 17:17:29.407   288   288 E SMD     : DCD OFF
,08-23 17:17:32.407   288   288 E SMD     : DCD OFF
,08-23 17:17:33.637  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:17:35.407   288   288 E SMD     : DCD OFF
,08-23 17:17:35.477  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:17:35.477  1018  1030 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 17:17:35.477  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:17:35.477  1018  1030 D BatteryService: stay LED for charging
,08-23 17:17:35.477  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:17:35.477  1018  1018 I MotionRecognitionService: Plugged
08-23 17:17:35.477  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:17:35.487  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:17:35.487  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:17:35.487  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,08-23 17:17:35.487  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:17:35.497  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:17:35.497  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:17:35.507  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:35.507  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:17:35.507  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:38.407   288   288 E SMD     : DCD OFF
,08-23 17:17:39.437  1018  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:17:39.437  1018  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-23 17:17:39.447  1018  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 17:17:41.337  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-23 17:17:41.347  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 17:17:41.347  1018  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:17:41.347  1018  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:17:41.407   288   288 E SMD     : DCD OFF
,08-23 17:17:42.517  1018  1338 E Watchdog: !@Sync 30
,08-23 17:17:43.677  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:17:44.407   288   288 E SMD     : DCD OFF
,08-23 17:17:45.537  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:17:47.417   288   288 E SMD     : DCD OFF
,08-23 17:17:50.417   288   288 E SMD     : DCD OFF
,08-23 17:17:53.417   288   288 E SMD     : DCD OFF
,08-23 17:17:53.707  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:17:55.607  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:17:55.607  1018  3306 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4145, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:17:55.607  1018  3306 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:17:55.607  1018  3306 D BatteryService: stay LED for charging
08-23 17:17:55.607  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:17:55.607  1018  1018 I MotionRecognitionService: Plugged
08-23 17:17:55.607  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:17:55.617  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:17:55.617  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:17:55.617  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:17:55.617  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84,
,08-23 17:17:55.627  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:17:55.627  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:17:55.637  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:55.637  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:55.637  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:17:56.417   288   288 E SMD     : DCD OFF
,08-23 17:17:56.927  1018  1051 I PowerManagerService: [PWL] Off : 855s ago
,08-23 17:17:59.417   288   288 E SMD     : DCD OFF
,08-23 17:18:02.417   288   288 E SMD     : DCD OFF
,08-23 17:18:03.727  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:18:05.417   288   288 E SMD     : DCD OFF
,08-23 17:18:05.677  1018  3325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:18:05.677  1018  3325 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:18:05.677  1018  3325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:18:05.677  1018  3325 D BatteryService: stay LED for charging
08-23 17:18:05.677  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:18:05.677  1018  1018 I MotionRecognitionService: Plugged
08-23 17:18:05.677  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:18:05.677  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:18:05.677  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:18:05.677  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:18:05.677  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:18:05.687  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:18:05.687  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:18:05.697  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:18:05.707  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:18:05.707  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:18:08.417   288   288 E SMD     : DCD OFF
,08-23 17:18:11.427   288   288 E SMD     : DCD OFF
,08-23 17:18:12.517  1018  1338 E Watchdog: !@Sync 31
,08-23 17:18:13.757  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:18:14.427   288   288 E SMD     : DCD OFF
,08-23 17:18:15.737  1018  3317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:18:17.427   288   288 E SMD     : DCD OFF
,08-23 17:18:20.427   288   288 E SMD     : DCD OFF
,08-23 17:18:23.427   288   288 E SMD     : DCD OFF
,08-23 17:18:23.797  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:18:25.807  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:18:26.427   288   288 E SMD     : DCD OFF
,08-23 17:18:29.427   288   288 E SMD     : DCD OFF
,08-23 17:18:32.437   288   288 E SMD     : DCD OFF
,08-23 17:18:33.807  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:18:35.437   288   288 E SMD     : DCD OFF
,08-23 17:18:35.877  1018  2778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:18:38.437   288   288 E SMD     : DCD OFF
,08-23 17:18:41.437   288   288 E SMD     : DCD OFF
,08-23 17:18:42.517  1018  1338 E Watchdog: !@Sync 32
,08-23 17:18:43.847  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:18:44.437   288   288 E SMD     : DCD OFF
,08-23 17:18:45.547  5628  5772 I PlayCommon: [981] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-23 17:18:45.547  5628  5772 I PlayCommon: [981] com.google.android.play.a.l.e(789): No file ready to send
,08-23 17:18:45.937  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:18:47.437   288   288 E SMD     : DCD OFF
,08-23 17:18:50.437   288   288 E SMD     : DCD OFF
,08-23 17:18:53.447   288   288 E SMD     : DCD OFF
,08-23 17:18:53.857  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:18:56.007  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:18:56.007  1018  3306 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
08-23 17:18:56.007  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:18:56.007  1018  3306 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
08-23 17:18:56.007  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:18:56.007  1018  3306 D BatteryService: stay LED for charging
08-23 17:18:56.007  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:18:56.007  1018  1018 I MotionRecognitionService: Plugged
08-23 17:18:56.007  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:18:56.017  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-23 17:18:56.017  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:18:56.027  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:18:56.027  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:18:56.037  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:18:56.037  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:18:56.037  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:18:56.447   288   288 E SMD     : DCD OFF
,08-23 17:18:59.447   288   288 E SMD     : DCD OFF
,08-23 17:19:02.447   288   288 E SMD     : DCD OFF
,08-23 17:19:03.897  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:19:05.447   288   288 E SMD     : DCD OFF
,08-23 17:19:06.077  1018  1670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:19:06.077  1018  1670 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:19:06.077  1018  1670 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:19:06.077  1018  1670 D BatteryService: stay LED for charging
08-23 17:19:06.077  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:19:06.077  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:19:06.077  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
,08-23 17:19:06.077  1018  1018 I MotionRecognitionService: Plugged
08-23 17:19:06.077  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:19:06.077  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:19:06.077  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:19:06.087  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:19:06.087  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:19:06.107  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:19:06.107  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:19:06.107  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:19:08.447   288   288 E SMD     : DCD OFF
,08-23 17:19:11.447   288   288 E SMD     : DCD OFF
,08-23 17:19:12.527  1018  1338 E Watchdog: !@Sync 33
,08-23 17:19:13.907  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:19:14.447   288   288 E SMD     : DCD OFF
,08-23 17:19:16.137  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:19:17.457   288   288 E SMD     : DCD OFF
,08-23 17:19:20.457   288   288 E SMD     : DCD OFF
,08-23 17:19:23.457   288   288 E SMD     : DCD OFF
,08-23 17:19:23.917  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:19:26.207  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:19:26.457   288   288 E SMD     : DCD OFF
,08-23 17:19:29.457   288   288 E SMD     : DCD OFF
,08-23 17:19:31.927  1018  1051 I PowerManagerService: [PWL] Off : 950s ago
,08-23 17:19:32.457   288   288 E SMD     : DCD OFF
,08-23 17:19:33.937  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:19:35.457   288   288 E SMD     : DCD OFF
,08-23 17:19:36.267  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 17:19:36.267  1018  3311 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:19:36.267  1018  3311 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:19:36.267  1018  3311 D BatteryService: stay LED for charging
08-23 17:19:36.267  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-23 17:19:36.277  1018  1018 I MotionRecognitionService: Plugged
08-23 17:19:36.277  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:19:36.277  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:19:36.277  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:19:36.277  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:19:36.277  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:19:36.287  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:19:36.287  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:19:36.297  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2,
08-23 17:19:36.297  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:19:36.297  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:19:38.467   288   288 E SMD     : DCD OFF
,08-23 17:19:41.467   288   288 E SMD     : DCD OFF
,08-23 17:19:42.527  1018  1338 E Watchdog: !@Sync 34
,08-23 17:19:43.947  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:19:44.467   288   288 E SMD     : DCD OFF
,08-23 17:19:46.337  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:19:47.467   288   288 E SMD     : DCD OFF
,08-23 17:19:50.467   288   288 E SMD     : DCD OFF
,08-23 17:19:53.467   288   288 E SMD     : DCD OFF
,08-23 17:19:53.957  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:19:56.397  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:19:56.467   288   288 E SMD     : DCD OFF
,08-23 17:19:59.467   288   288 E SMD     : DCD OFF
,08-23 17:20:02.477   288   288 E SMD     : DCD OFF
,08-23 17:20:03.977  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:20:05.477   288   288 E SMD     : DCD OFF
,08-23 17:20:06.467  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:20:08.477   288   288 E SMD     : DCD OFF
,08-23 17:20:11.477   288   288 E SMD     : DCD OFF
,08-23 17:20:12.527  1018  1338 E Watchdog: !@Sync 35
,08-23 17:20:14.007  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:20:14.477   288   288 E SMD     : DCD OFF
,08-23 17:20:16.537  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:20:16.537  1018  1292 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4147, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:20:16.537  1018  1292 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:20:16.537  1018  1292 D BatteryService: stay LED for charging
08-23 17:20:16.537  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:20:16.537  1018  1018 I MotionRecognitionService: Plugged
08-23 17:20:16.537  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:20:16.537  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:20:16.537  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:20:16.537  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:20:16.537  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:20:16.547  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:20:16.547  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:20:16.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:20:16.567  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:20:16.567  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:20:17.477   288   288 E SMD     : DCD OFF
,08-23 17:20:20.477   288   288 E SMD     : DCD OFF
,08-23 17:20:23.477   288   288 E SMD     : DCD OFF
,08-23 17:20:24.027  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:20:26.487   288   288 E SMD     : DCD OFF
,08-23 17:20:26.597  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:20:26.597  1018  1480 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:20:26.597  1018  1480 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 17:20:26.597  1018  1480 D BatteryService: stay LED for charging
08-23 17:20:26.597  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:20:26.607  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:20:26.607  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
08-23 17:20:26.607  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:20:26.607  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:20:26.607  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:20:26.607  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:20:26.617  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:20:26.617  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:20:26.627  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:20:26.627  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:20:26.627  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:20:29.487   288   288 E SMD     : DCD OFF
,08-23 17:20:32.487   288   288 E SMD     : DCD OFF
,08-23 17:20:34.037  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:20:35.487   288   288 E SMD     : DCD OFF
,08-23 17:20:36.667  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:20:38.487   288   288 E SMD     : DCD OFF
,08-23 17:20:41.487   288   288 E SMD     : DCD OFF
,08-23 17:20:42.527  1018  1338 E Watchdog: !@Sync 36
,08-23 17:20:44.067  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:20:44.487   288   288 E SMD     : DCD OFF
,08-23 17:20:46.737  1018  3325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:20:47.497   288   288 E SMD     : DCD OFF
,08-23 17:20:50.497   288   288 E SMD     : DCD OFF
,08-23 17:20:53.497   288   288 E SMD     : DCD OFF
,08-23 17:20:54.097  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:20:56.497   288   288 E SMD     : DCD OFF
,08-23 17:20:56.797  1018  2778 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:20:59.497   288   288 E SMD     : DCD OFF
,08-23 17:21:02.497   288   288 E SMD     : DCD OFF
,08-23 17:21:04.117  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:21:05.497   288   288 E SMD     : DCD OFF
,08-23 17:21:06.867  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:21:08.497   288   288 E SMD     : DCD OFF
,08-23 17:21:11.507   288   288 E SMD     : DCD OFF
,08-23 17:21:11.977  1018  1051 I PowerManagerService: [PWL] Off : 1050s ago,
,08-23 17:21:12.527  1018  1338 E Watchdog: !@Sync 37,
,08-23 17:21:14.127  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:21:14.507   288   288 E SMD     : DCD OFF
,08-23 17:21:16.927  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:21:17.507   288   288 E SMD     : DCD OFF
,08-23 17:21:20.507   288   288 E SMD     : DCD OFF
,08-23 17:21:23.507   288   288 E SMD     : DCD OFF
,08-23 17:21:24.137  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:21:26.507   288   288 E SMD     : DCD OFF
,08-23 17:21:26.997  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:21:26.997  1018  3183 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:21:26.997  1018  3183 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:21:26.997  1018  3183 D BatteryService: stay LED for charging
08-23 17:21:26.997  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:21:26.997  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:21:26.997  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:21:27.007  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-23 17:21:27.007  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:21:27.007  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:21:27.007  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:21:27.017  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:21:27.017  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:21:27.027  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2,
08-23 17:21:27.027  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:21:27.027  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:21:29.507   288   288 E SMD     : DCD OFF
,08-23 17:21:32.507   288   288 E SMD     : DCD OFF
,08-23 17:21:34.157  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:21:35.517   288   288 E SMD     : DCD OFF
,08-23 17:21:37.057  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:21:38.517   288   288 E SMD     : DCD OFF
,08-23 17:21:41.517   288   288 E SMD     : DCD OFF
,08-23 17:21:42.527  1018  1338 E Watchdog: !@Sync 38
,08-23 17:21:44.167  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:21:44.517   288   288 E SMD     : DCD OFF
,08-23 17:21:47.127  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:21:47.127  1018  1336 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4145, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:21:47.127  1018  1336 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:21:47.127  1018  1336 D BatteryService: stay LED for charging
08-23 17:21:47.127  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:21:47.127  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:21:47.127  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:21:47.137  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:21:47.137  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:21:47.137  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:21:47.137  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:21:47.147  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:21:47.147  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:21:47.157  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2,
08-23 17:21:47.157  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:21:47.157  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:21:47.517   288   288 E SMD     : DCD OFF
,08-23 17:21:50.517   288   288 E SMD     : DCD OFF
,08-23 17:21:53.517   288   288 E SMD     : DCD OFF
,08-23 17:21:54.177  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:21:56.517   288   288 E SMD     : DCD OFF
,08-23 17:21:57.197  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:21:57.197  1018  1292 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4146, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:21:57.197  1018  1292 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:21:57.197  1018  1292 D BatteryService: stay LED for charging
,08-23 17:21:57.197  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:21:57.197  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:21:57.197  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:21:57.197  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:21:57.207  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:21:57.207  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-23 17:21:57.207  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:21:57.217  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:21:57.217  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:21:57.227  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:21:57.227  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:21:57.227  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:21:59.527   288   288 E SMD     : DCD OFF
,08-23 17:22:02.527   288   288 E SMD     : DCD OFF
,08-23 17:22:04.197  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:22:05.527   288   288 E SMD     : DCD OFF
,08-23 17:22:07.257  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:22:08.527   288   288 E SMD     : DCD OFF
,08-23 17:22:11.527   288   288 E SMD     : DCD OFF
,08-23 17:22:12.527  1018  1338 E Watchdog: !@Sync 39
,08-23 17:22:14.207  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:22:14.527   288   288 E SMD     : DCD OFF
,08-23 17:22:17.327  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:22:17.527   288   288 E SMD     : DCD OFF
,08-23 17:22:20.537   288   288 E SMD     : DCD OFF
,08-23 17:22:23.537   288   288 E SMD     : DCD OFF
,08-23 17:22:24.217  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:22:26.537   288   288 E SMD     : DCD OFF
,08-23 17:22:27.387  1018  3317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:22:29.537   288   288 E SMD     : DCD OFF
,08-23 17:22:32.537   288   288 E SMD     : DCD OFF
,08-23 17:22:34.227  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:22:35.537   288   288 E SMD     : DCD OFF
,08-23 17:22:37.457  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:22:38.537   288   288 E SMD     : DCD OFF
,08-23 17:22:39.437  1018  1088 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-23 17:22:39.437  1018  1088 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-23 17:22:39.437  1018  1087 D TimaService: TimaServiceHandler.handleMessage what =1
,08-23 17:22:40.177  1018  1043 I UsageStatsService: User[0] Flushing usage stats to disk
,08-23 17:22:40.207  1018  1103 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,08-23 17:22:40.207  1018  1103 I ApplicationUsage: Updating Usage Statistics in DB @ 1471965760222
,08-23 17:22:40.217  1018  1103 I ApplicationPolicy: updateDataUsageMap
,08-23 17:22:40.267  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3,
08-23 17:22:40.267  1018  1088 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-23 17:22:40.277  1018  1088 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
08-23 17:22:40.277  1018  1088 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-23 17:22:40.697  1018  1103 I NetworkDataUsageDb: ::getAppControlDB: DB is Created ,
08-23 17:22:40.697  1018  1103 I NetworkDataUsageDb: ::isTableExists: Table exists 
,08-23 17:22:40.717  1018  1103 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1471965760725
,08-23 17:22:41.547   288   288 E SMD     : DCD OFF
,08-23 17:22:42.527  1018  1338 E Watchdog: !@Sync 40
,08-23 17:22:44.267  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:22:44.547   288   288 E SMD     : DCD OFF
,08-23 17:22:47.517  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:22:47.517  1018  2739 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4145, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:22:47.517  1018  2739 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:22:47.517  1018  2739 D BatteryService: stay LED for charging
,08-23 17:22:47.517  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:22:47.527  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:22:47.527  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:22:47.527  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:22:47.527  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:22:47.527  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:22:47.537  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:22:47.547  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:22:47.547  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:22:47.547   288   288 E SMD     : DCD OFF
,08-23 17:22:47.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:22:47.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:22:47.557  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:22:50.547   288   288 E SMD     : DCD OFF
,08-23 17:22:53.547   288   288 E SMD     : DCD OFF
,08-23 17:22:54.307  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:22:56.547   288   288 E SMD     : DCD OFF
,08-23 17:22:56.977  1018  1051 I PowerManagerService: [PWL] Off : 1155s ago
,08-23 17:22:57.587  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:22:59.547   288   288 E SMD     : DCD OFF
,08-23 17:23:02.547   288   288 E SMD     : DCD OFF
,08-23 17:23:04.317  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:23:05.557   288   288 E SMD     : DCD OFF
,08-23 17:23:07.657  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:23:08.557   288   288 E SMD     : DCD OFF
,08-23 17:23:11.557   288   288 E SMD     : DCD OFF
,08-23 17:23:12.527  1018  1338 E Watchdog: !@Sync 41
,08-23 17:23:14.327  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:23:14.557   288   288 E SMD     : DCD OFF
,08-23 17:23:17.557   288   288 E SMD     : DCD OFF
,08-23 17:23:17.717  1018  1670 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:23:20.557   288   288 E SMD     : DCD OFF,
,08-23 17:23:20.857  5628  5662 I PlayCommon: [963] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-23 17:23:20.857  5628  5662 I PlayCommon: [963] com.google.android.play.a.l.e(789): No file ready to send
,08-23 17:23:23.557   288   288 E SMD     : DCD OFF
,08-23 17:23:24.367  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:23:26.567   288   288 E SMD     : DCD OFF
,08-23 17:23:27.787  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:23:29.567   288   288 E SMD     : DCD OFF
,08-23 17:23:32.567   288   288 E SMD     : DCD OFF
,08-23 17:23:34.407  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:23:35.567   288   288 E SMD     : DCD OFF,
,08-23 17:23:37.847  1018  1125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:23:38.567   288   288 E SMD     : DCD OFF
,08-23 17:23:41.567   288   288 E SMD     : DCD OFF
,08-23 17:23:42.527  1018  1338 E Watchdog: !@Sync 42
,08-23 17:23:44.427  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:23:44.567   288   288 E SMD     : DCD OFF
,08-23 17:23:45.597  5628  5772 I PlayCommon: [981] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-23 17:23:45.597  5628  5772 I PlayCommon: [981] com.google.android.play.a.l.e(789): No file ready to send
,08-23 17:23:47.577   288   288 E SMD     : DCD OFF
,08-23 17:23:47.917  1018  3325 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-23 17:23:47.917  1018  3325 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4143, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:23:47.917  1018  3325 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:23:47.917  1018  3325 D BatteryService: stay LED for charging
08-23 17:23:47.917  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:23:47.917  1018  1018 I MotionRecognitionService: Plugged,
08-23 17:23:47.917  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:23:47.927  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:23:47.927  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:23:47.927  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 17:23:47.927  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:23:47.937  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-23 17:23:47.937  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:23:47.947  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:23:47.947  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:23:47.947  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:23:50.577   288   288 E SMD     : DCD OFF,
,08-23 17:23:53.577   288   288 E SMD     : DCD OFF
,08-23 17:23:54.447  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:23:56.577   288   288 E SMD     : DCD OFF
,08-23 17:23:57.977  1018  3317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:23:57.977  1018  3317 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4145, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:23:57.977  1018  3317 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:23:57.977  1018  3317 D BatteryService: stay LED for charging
08-23 17:23:57.977  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:23:57.977  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:23:57.987  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
08-23 17:23:57.987  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:23:57.987  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:23:57.987  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:23:57.987  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:23:57.997  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:23:57.997  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:23:58.007  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2,
08-23 17:23:58.007  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:23:58.007  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:23:59.577   288   288 E SMD     : DCD OFF
,08-23 17:24:02.577   288   288 E SMD     : DCD OFF
,08-23 17:24:04.487  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:24:05.577   288   288 E SMD     : DCD OFF
,08-23 17:24:08.047  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:24:08.587   288   288 E SMD     : DCD OFF
,08-23 17:24:11.587   288   288 E SMD     : DCD OFF
,08-23 17:24:12.527  1018  1338 E Watchdog: !@Sync 43
,08-23 17:24:14.527  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:24:14.587   288   288 E SMD     : DCD OFF
,08-23 17:24:17.587   288   288 E SMD     : DCD OFF
,08-23 17:24:18.117  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:24:20.587   288   288 E SMD     : DCD OFF,
,08-23 17:24:23.587   288   288 E SMD     : DCD OFF
,08-23 17:24:24.557  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:24:26.587   288   288 E SMD     : DCD OFF
,08-23 17:24:28.187  1018  3306 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:24:29.597   288   288 E SMD     : DCD OFF
,08-23 17:24:32.597   288   288 E SMD     : DCD OFF
,08-23 17:24:34.567  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:24:35.597   288   288 E SMD     : DCD OFF,
,08-23 17:24:38.247  1018  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:24:38.597   288   288 E SMD     : DCD OFF
,08-23 17:24:41.597   288   288 E SMD     : DCD OFF
,08-23 17:24:42.527  1018  1338 E Watchdog: !@Sync 44
,08-23 17:24:44.597   288   288 E SMD     : DCD OFF
,08-23 17:24:44.607  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:24:47.027  1018  1051 I PowerManagerService: [PWL] Off : 1265s ago
,08-23 17:24:47.597   288   288 E SMD     : DCD OFF
,08-23 17:24:48.317  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:24:50.597   288   288 E SMD     : DCD OFF
,08-23 17:24:53.607   288   288 E SMD     : DCD OFF
,08-23 17:24:54.647  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:24:56.607   288   288 E SMD     : DCD OFF,
,08-23 17:24:58.377  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:24:59.607   288   288 E SMD     : DCD OFF
,08-23 17:25:02.607   288   288 E SMD     : DCD OFF
,08-23 17:25:04.687  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:25:05.607   288   288 E SMD     : DCD OFF
,08-23 17:25:08.447  1018  3317 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:25:08.607   288   288 E SMD     : DCD OFF
,08-23 17:25:11.607   288   288 E SMD     : DCD OFF
,08-23 17:25:12.527  1018  1338 E Watchdog: !@Sync 45
,08-23 17:25:14.617   288   288 E SMD     : DCD OFF
,08-23 17:25:14.727  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:25:17.617   288   288 E SMD     : DCD OFF
,08-23 17:25:18.507  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:25:18.507  1018  1481 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4143, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:25:18.507  1018  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:25:18.507  1018  1481 D BatteryService: stay LED for charging
,08-23 17:25:18.507  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:25:18.517  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:25:18.517  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:25:18.517  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:25:18.517  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-23 17:25:18.517  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:25:18.517  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:25:18.527  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:25:18.527  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:25:18.537  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:25:18.537  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:25:18.537  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:25:20.617   288   288 E SMD     : DCD OFF
,08-23 17:25:23.617   288   288 E SMD     : DCD OFF
,08-23 17:25:24.777  1018  2753 D SSRM:n  : SIOP:: AP = 300
,08-23 17:25:26.617   288   288 E SMD     : DCD OFF
,08-23 17:25:28.577  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:25:28.577  1018  1031 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4145, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:25:28.577  1018  1031 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:25:28.577  1018  1031 D BatteryService: stay LED for charging
08-23 17:25:28.577  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:25:28.577  1018  1018 I MotionRecognitionService: Plugged
,08-23 17:25:28.577  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 17:25:28.577  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 17:25:28.577  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:25:28.577  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:25:28.577  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:25:28.587  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:25:28.587  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:25:28.597  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:25:28.607  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:25:28.607  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:25:29.617   288   288 E SMD     : DCD OFF
,08-23 17:25:32.617   288   288 E SMD     : DCD OFF
,08-23 17:25:34.787  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:25:35.617   288   288 E SMD     : DCD OFF,
,08-23 17:25:38.627   288   288 E SMD     : DCD OFF
,08-23 17:25:38.637  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:25:38.637  1018  3183 D BatteryService: level:84, scale:100, status:2, health:2, present:true, voltage: 4143, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 17:25:38.637  1018  3183 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 17:25:38.647  1018  3183 D BatteryService: stay LED for charging
,08-23 17:25:38.647  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 17:25:38.647  1018  1018 I MotionRecognitionService: Plugged
08-23 17:25:38.647  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 17:25:38.647  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 17:25:38.647  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 17:25:38.647  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 17:25:38.647  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 84
,08-23 17:25:38.657  2652  2652 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 17:25:38.657  2652  2751 D HeadsetStateMachine: Disconnected process message: 10
,08-23 17:25:38.667  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:25:38.667  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
08-23 17:25:38.677  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:84 status:2 health:2
,08-23 17:25:41.627   288   288 E SMD     : DCD OFF,
,08-23 17:25:42.527  1018  1338 E Watchdog: !@Sync 46
,08-23 17:25:44.627   288   288 E SMD     : DCD OFF
,08-23 17:25:44.797  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:25:47.627   288   288 E SMD     : DCD OFF
,08-23 17:25:48.707  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-23 17:25:50.627   288   288 E SMD     : DCD OFF
,08-23 17:25:53.627   288   288 E SMD     : DCD OFF
,08-23 17:25:54.837  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:25:56.627   288   288 E SMD     : DCD OFF
,08-23 17:25:58.777  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:25:59.637   288   288 E SMD     : DCD OFF
,08-23 17:26:02.637   288   288 E SMD     : DCD OFF
,08-23 17:26:04.857  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:26:05.637   288   288 E SMD     : DCD OFF
,08-23 17:26:08.637   288   288 E SMD     : DCD OFF
,08-23 17:26:08.847  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:26:11.637   288   288 E SMD     : DCD OFF
,08-23 17:26:12.527  1018  1338 E Watchdog: !@Sync 47
,08-23 17:26:14.637   288   288 E SMD     : DCD OFF
,08-23 17:26:14.867  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:26:17.637   288   288 E SMD     : DCD OFF
,08-23 17:26:18.907  1018  2739 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:26:20.647   288   288 E SMD     : DCD OFF
,08-23 17:26:23.647   288   288 E SMD     : DCD OFF
,08-23 17:26:24.877  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:26:26.647   288   288 E SMD     : DCD OFF
,08-23 17:26:28.967  1018  1031 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:26:29.647   288   288 E SMD     : DCD OFF
,08-23 17:26:32.647   288   288 E SMD     : DCD OFF
,08-23 17:26:34.897  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:26:35.647   288   288 E SMD     : DCD OFF
,08-23 17:26:38.647   288   288 E SMD     : DCD OFF
,08-23 17:26:39.037  1018  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:26:41.657   288   288 E SMD     : DCD OFF
,08-23 17:26:42.027  1018  1051 I PowerManagerService: [PWL] Off : 1380s ago
,08-23 17:26:42.527  1018  1338 E Watchdog: !@Sync 48
,08-23 17:26:44.657   288   288 E SMD     : DCD OFF
,08-23 17:26:44.907  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:26:47.657   288   288 E SMD     : DCD OFF
,08-23 17:26:49.097  1018  3183 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:26:50.657   288   288 E SMD     : DCD OFF
,08-23 17:26:53.657   288   288 E SMD     : DCD OFF
,08-23 17:26:54.947  1018  2753 D SSRM:n  : SIOP:: AP = 290,
,08-23 17:26:56.657   288   288 E SMD     : DCD OFF
,08-23 17:26:59.167  1018  1480 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:26:59.657   288   288 E SMD     : DCD OFF
,08-23 17:27:02.657   288   288 E SMD     : DCD OFF
,08-23 17:27:04.957  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:27:05.667   288   288 E SMD     : DCD OFF
,08-23 17:27:08.667   288   288 E SMD     : DCD OFF
,08-23 17:27:09.237  1018  3311 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:27:11.667   288   288 E SMD     : DCD OFF
,08-23 17:27:12.537  1018  1338 E Watchdog: !@Sync 49,
,08-23 17:27:14.667   288   288 E SMD     : DCD OFF
,08-23 17:27:14.997  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:27:17.667   288   288 E SMD     : DCD OFF
,08-23 17:27:19.297  1018  3158 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:27:20.667   288   288 E SMD     : DCD OFF
,08-23 17:27:23.667   288   288 E SMD     : DCD OFF
,08-23 17:27:25.007  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:27:26.677   288   288 E SMD     : DCD OFF
,08-23 17:27:29.367  1018  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 17:27:29.677   288   288 E SMD     : DCD OFF,
,08-23 17:27:32.677   288   288 E SMD     : DCD OFF
,08-23 17:27:35.027  1018  2753 D SSRM:n  : SIOP:: AP = 290
,08-23 17:27:35.677   288   288 E SMD     : DCD OFF
,TIME-OUT KILL (timeout was 1400000ms)
```
