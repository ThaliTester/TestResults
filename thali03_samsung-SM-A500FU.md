#### Test 836273375fe617f_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-09 13:40:58.611  6096  6096 E Zygote  : MountEmulatedStorage()
09-09 13:40:58.611  6096  6096 E Zygote  : v2
09-09 13:40:58.611  6096  6096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
--------- beginning of system
09-09 13:40:58.611  6096  6096 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:40:58.611  6096  6096 I libpersona: KNOX_SDCARD not a persona
09-09 13:40:58.611  1014  1214 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6096 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-09 13:40:58.621  6096  6096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:40:58.621  6096  6096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:40:58.621  1014  1539 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-09 13:40:58.621  1014  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-09 13:40:58.631  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 13:40:58.641  5851  6095 W AccountFeatureHelper: Write apps_features disabled false
09-09 13:40:58.641  1014  3124 I art     : Explicit concurrent mark sweep GC freed 146986(8MB) AllocSpace objects, 4(1863KB) LOS objects, 33% free, 28MB/42MB, paused 3.123ms total 184.432ms
09-09 13:40:58.651  6096  6096 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:58.651  6096  6096 D ActivityThread: Added TimaKeyStore provider
09-09 13:40:58.651   290   290 E SMD     : DCD OFF
09-09 13:40:58.701  3798  4469 I Icing   : Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
09-09 13:40:58.711  1014  1500 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
09-09 13:40:58.711  1014  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:58.711  1014  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:58.711  1014  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:58.711  1014  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:58.721  6114  6114 E Zygote  : MountEmulatedStorage()
09-09 13:40:58.721  6114  6114 E Zygote  : v2
09-09 13:40:58.721  6114  6114 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:40:58.721  6114  6114 I libpersona: KNOX_SDCARD not a persona
09-09 13:40:58.721  6114  6114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:40:58.721  1014  1500 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6114 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-09 13:40:58.731  1014  1500 I ActivityManager: Killing 4972:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
09-09 13:40:58.731  6114  6114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:40:58.731  6114  6114 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:40:58.751  6114  6114 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:58.751  6114  6114 D ActivityThread: Added TimaKeyStore provider
09-09 13:40:58.801  1014  3125 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-09 13:40:58.801  1014  3125 I ActivityManager: Killing 4372:com.google.android.music:main/u0a111 (adj 15): empty #31
09-09 13:40:58.811  6114  6129 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
09-09 13:40:58.811  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:40:58.811  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:40:58.811  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:40:58.811  6114  6129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-09 13:40:58.811  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-09 13:40:58.811  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-09 13:40:58.811  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:40:58.811  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:40:58.811  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-09 13:40:58.821  6114  6114 D AcmsService: Enter Oncreate
09-09 13:40:58.821  6114  6114 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 13:40:58.821  6114  6114 D AcmsService: creating AcmsCore
09-09 13:40:58.821  6114  6114 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-09 13:40:58.821  6114  6114 D AcmsCore: AcmsCore
09-09 13:40:58.831  6114  6114 D AcmsCore: init
09-09 13:40:58.831  6114  6114 D AcmsCore: Looper handler is not null
09-09 13:40:58.831  6114  6114 D AcmsCore: Post to AcmsCoreHandler
09-09 13:40:58.831  6114  6114 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 13:40:58.831  6114  6114 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-09 13:40:58.831  6114  6114 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-09 13:40:58.831  6114  6114 D AcmsService: onStartCommand
09-09 13:40:58.831  6114  6114 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-09 13:40:58.831  6114  6114 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-09 13:40:58.831  6114  6114 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-09 13:40:58.831  6114  6114 D AcmsService: Incremented Counter Value : onStartCommand
09-09 13:40:58.831  6114  6130 D AcmsCertificateMngr: AcmsCertificateMngr
09-09 13:40:58.831  1014  1539 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-09 13:40:58.831  6114  6114 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-09 13:40:58.841  6114  6130 D AcmsRevocationMngr: AcmsRevocationMngr
09-09 13:40:58.871  6114  6114 D AcmsService: Inside handle Intent
09-09 13:40:58.871  6114  6114 D AcmsService: App added - package name: com.test.thalitest
09-09 13:40:58.871  6114  6114 D AcmsCore: Post to AcmsCoreHandler
09-09 13:40:58.871  6114  6114 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 13:40:58.871  6114  6114 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-09 13:40:58.871  6114  6114 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-09 13:40:58.871  6114  6114 D AcmsService: Decremented Counter Value : handleStartIntent
09-09 13:40:58.871  6114  6114 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-09 13:40:58.891  5851  5851 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
09-09 13:40:59.261  3798  4469 I Icing   : Indexing 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD from com.google.android.googlequicksearchbox
09-09 13:40:59.321  3798  4469 I Icing   : Indexing done 675A4012BEFF6588AF9C8DE380F736BA72E6F9BD
,09-09 13:40:59.341  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-09 13:40:59.341  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:40:59.341  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:40:59.341  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:40:59.531  5773  5773 I Mms/MmsApp:  start initViewCache mms
09-09 13:40:59.531  5773  5773 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1939.949583
09-09 13:40:59.531  5773  5773 D Mms/ComposeMessageFragment: fillCache, easy = false
09-09 13:40:59.571  6134  6134 D AndroidRuntime: 
09-09 13:40:59.571  6134  6134 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 13:40:59.571  6134  6134 D AndroidRuntime: CheckJNI is OFF
09-09 13:40:59.571  6134  6134 D AndroidRuntime: readGMSProperty: start
09-09 13:40:59.571  6134  6134 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:40:59.571  6134  6134 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 13:40:59.571  6134  6134 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:40:59.571  6134  6134 D AndroidRuntime: readGMSProperty: end
09-09 13:40:59.571  6134  6134 D AndroidRuntime: addProductProperty: start
09-09 13:40:59.611  5773  5773 D AbsListView: Get MotionRecognitionManager
09-09 13:40:59.611  1014  3126 D MotionRecognitionService:  ssp status : false
09-09 13:40:59.611  5773  5773 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 78.42651
09-09 13:40:59.701  6134  6134 E AffinityControl: AffinityControl: registerfunction enter
09-09 13:40:59.711  5773  5773 D Mms/BubbleViewCache: fillCache bubble = 1
09-09 13:40:59.731  6134  6134 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 13:40:59.731  1014  1137 E PersonaManagerService: inState():  stateMachine is null !!
09-09 13:40:59.731  1014  1137 I PersonaManagerService: PersonaId don't exist
09-09 13:40:59.731  1014  1137 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 13:40:59.731  1014  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:40:59.751  1014  1137 W ActivityManager: mDVFSHelper.acquire()
09-09 13:40:59.751  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 13:40:59.751  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 13:40:59.761  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:59.761  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:59.761  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:59.761  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:40:59.771  6146  6146 E Zygote  : MountEmulatedStorage()
09-09 13:40:59.771  6146  6146 E Zygote  : v2
09-09 13:40:59.771  6146  6146 I libpersona: KNOX_SDCARD checking this for 10155
09-09 13:40:59.771  6146  6146 I libpersona: KNOX_SDCARD not a persona
09-09 13:40:59.771  1014  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-09 13:40:59.771  1014  1137 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6146 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 13:40:59.771  1014  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:40:59.771  1014  1137 D InputDispatcher: Focused application set to: xxxx
09-09 13:40:59.771  1014  1137 D InputDispatcher: Focus left window: 3144
09-09 13:40:59.771  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 13:40:59.771  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 13:40:59.781  6134  6134 D AndroidRuntime: Shutting down VM
09-09 13:40:59.781   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-09 13:40:59.781  6146  6146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:40:59.781  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:40:59.781  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 13:40:59.781  6146  6146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:40:59.781  6146  6146 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 13:40:59.801  6146  6146 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:40:59.801  6146  6146 D ActivityThread: Added TimaKeyStore provider
09-09 13:40:59.801  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 13:40:59.801  1014  1014 V ActivityManager: Display changed displayId=0
09-09 13:40:59.831  1014  3126 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:40:59.861   257  1052 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
09-09 13:40:59.861   257   450 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
09-09 13:40:59.861  3144  3144 V ActivityThread: updateVisibility : ActivityRecord{1512de6c token=android.os.BinderProxy@144d4633 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-09 13:40:59.931  6146  6146 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-09 13:40:59.941  6146  6146 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2157-2159)
09-09 13:40:59.951  6146  6146 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:40:59.961  6146  6146 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cc573e8}
09-09 13:40:59.971  6146  6146 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 13:40:59.971  6146  6146 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 13:40:59.981  6134  6134 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 13:40:59.991  1014  1093 V AlarmManager: waitForAlarm result :8
,09-09 13:41:00.001  6146  6146 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,09-09 13:41:00.001  6146  6146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:00.001  6146  6146 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-09 13:41:00.021  6146  6146 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-09 13:41:00.021  6146  6146 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-09 13:41:00.021  6146  6146 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-09 13:41:00.031  6146  6146 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:41:00.031  6146  6146 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:41:00.031  6146  6146 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:41:00.031  6146  6146 I Adreno-EGL: Local Branch: 
09-09 13:41:00.031  6146  6146 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:41:00.031  6146  6146 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:41:00.031  6146  6146 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:41:00.151  6146  6172 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-09 13:41:00.191  6146  6146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:00.201  6146  6146 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 13:41:00.211  6146  6146 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-09 13:41:00.211  6146  6146 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-09 13:41:00.221  6146  6146 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 13:41:00.231  6146  6146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:00.231  6146  6146 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:00.271  6146  6185 D OpenGLRenderer: Render dirty regions requested: true
,09-09 13:41:00.281  1014  3124 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
09-09 13:41:00.281  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 13:41:00.281  1014  3124 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 13:41:00.281  1014  3124 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 13:41:00.281  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 13:41:00.291  6146  6146 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-09 13:41:00.291  6146  6146 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-09 13:41:00.301   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-09 13:41:00.311  1014  1535 D InputDispatcher: Focus entered window: 6146
,09-09 13:41:00.321  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 13:41:00.321  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:41:00.321  6146  6146 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:41:00.321  6146  6185 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 13:41:00.331  6146  6185 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-09 13:41:00.331  6146  6185 D OpenGLRenderer: Enabling debug mode 0
,09-09 13:41:00.361  6146  6146 V ActivityThread: updateVisibility : ActivityRecord{31ca6e73 token=android.os.BinderProxy@3f9627ad {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 13:41:00.411  1014  3124 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:41:00.411  1173  1173 D PanelView: There is/are notification(s) 
,09-09 13:41:00.411  1014  6188 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:41:00.421  1014  1044 I ActivityManager: Displayed Component not be shown by security: +590ms (total +668ms)
09-09 13:41:00.421  1014  1044 W ActivityManager: mDVFSHelper.release()
09-09 13:41:00.421  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1055b9ba u0 com.test.thalitest/.MainActivity t128} time:102638
09-09 13:41:00.421  1774  1774 I SamsungIME: getCurrentCandidateView
,09-09 13:41:00.431  6146  6146 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-09 13:41:00.431  6146  6146 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f9627ad time:102647
,09-09 13:41:00.431   257  1052 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-09 13:41:00.441   257   452 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-09 13:41:00.501  6146  6146 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6146
,09-09 13:41:00.521  1774  1774 D SamsungIME: Dismiss ExpandCandiate
,09-09 13:41:00.621  6146  6146 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 13:41:00.651  1774  1774 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 13:41:00.691  1774  1774 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 13:41:00.711  1774  1774 I SamsungIME: KeybaordView init() : load resources
,09-09 13:41:00.731  6146  6189 D jxcore_app_log: JniHelper::setJavaVM(0xb7f6b328), pthread_self() = -1202914040
,09-09 13:41:00.731  6146  6189 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 13:41:00.731  6146  6189 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 13:41:00.731  6146  6189 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 13:41:00.731  6146  6189 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 13:41:00.731  6146  6189 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 13:41:00.731  6146  6189 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eabda63 added. We now have 1 listener(s)
,09-09 13:41:00.741  1774  1774 I SamsungIME: getCurrentKeyboard
09-09 13:41:00.741  1774  1774 I SamsungIME: getTextKeyboard
,09-09 13:41:00.741  6146  6189 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-09 13:41:00.741  6146  6189 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:00.741  6146  6189 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:00.741  6146  6189 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 13:41:00.751  6146  6189 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d3d43de added. We now have 1 listener(s)
,09-09 13:41:00.751  6146  6189 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:00.761  6146  6189 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:00.761  6146  6189 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 13:41:00.761  6146  6189 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 13:41:00.761  6146  6189 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 13:41:00.761  6146  6189 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 13:41:00.761  1774  1774 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 13:41:00.761  6146  6189 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:00.761  6146  6189 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-09 13:41:00.771  6146  6189 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 13:41:00.771  6146  6189 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:00.771  6146  6189 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:00.771  6146  6189 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:00.771  6146  6189 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:00.771  6146  6189 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:00.771  6146  6189 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:00.771  6146  6189 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:00.771  6146  6189 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:00.771  6146  6189 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-09 13:41:00.771  6146  6189 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:00.771  6146  6189 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 13:41:00.771  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:00.781  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:00.801  6146  6146 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 13:41:01.321  1774  6195 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 13:41:01.351  6146  6196 W jxcore-log: Initializing JXcore engine
09-09 13:41:01.351  6146  6196 W jxcore-log: JXcore engine is ready
,09-09 13:41:01.401  1930  1930 E audit   : type=1400 msg=audit(1473421261.401:205): avc:  denied  { ioctl } for  pid=6196 comm="Thread-1068" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 13:41:01.401  1930  1930 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:41:01.401  1930  1930 E audit   : type=1300 msg=audit(1473421261.401:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ddd48f8 items=0 ppid=306 ppcomm=main pid=6196 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1068" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 13:41:01.401  1930  1930 E audit   : type=1320 msg=audit(1473421261.401:205): 
,09-09 13:41:01.421  6146  6196 W jxcore-log: Starting JXcore engine
,09-09 13:41:01.531  6146  6196 W jxcore-log: Platform android
09-09 13:41:01.531  6146  6196 W jxcore-log: 
09-09 13:41:01.531  6146  6196 W jxcore-log: Process ARCH arm
09-09 13:41:01.531  6146  6196 W jxcore-log: 
,09-09 13:41:01.661   290   290 E SMD     : DCD OFF
,09-09 13:41:01.741  6146  6196 I jxcore-log: JXcore Cordova bridge is ready!
09-09 13:41:01.741  6146  6196 I jxcore-log: 
,09-09 13:41:01.741  6146  6196 W jxcore-log: JXcore engine is started
09-09 13:41:01.741  6146  6189 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-09 13:41:01.741  6146  6146 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 13:41:03.381  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-09 13:41:03.381  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-09 13:41:03.381  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:03.381  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:03.381  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,09-09 13:41:03.791  1014  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:03.791  1014  1500 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4161, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 13:41:03.791  1014  1500 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 13:41:03.791  1014  1500 D BatteryService: stay LED for charging
09-09 13:41:03.791  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:03.801  1014  1014 I MotionRecognitionService: Plugged
,09-09 13:41:03.801  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:03.801  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:03.801  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:03.811  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:03.811  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,09-09 13:41:03.821  2657  2657 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:41:03.821  2657  2729 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:03.831  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:03.831  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:03.831  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:04.661   290   290 E SMD     : DCD OFF,
,09-09 13:41:05.031  1014  1093 V AlarmManager: waitForAlarm result :4,
09-09 13:41:05.031  1014  1046 I PowerManagerService: [PWL] Off : 30s ago
,09-09 13:41:05.041  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-09 13:41:05.051  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-09 13:41:05.051  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-09 13:41:05.051  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-09 13:41:05.051  1173  1173 D KeyguardUpdateMonitor: handleTimeUpdate
,09-09 13:41:05.061  1173  1173 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-09 13:41:05.071  1173  1173 D SecKeyguardClockView: HomeTimezone(): 1
,09-09 13:41:05.071  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:41:05.071  1173  1173 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-09 13:41:05.071  1173  1173 I KeyguardEffectViewController: *** don't update sliding image ***
,09-09 13:41:05.091  1014  2730 D SSRM:n  : SIOP:: AP = 410
,09-09 13:41:05.111  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:41:05.111  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:41:05.111  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:41:05.131  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 13:41:05.901  6114  6130 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-09 13:41:05.911  6114  6130 I AcmsKeyStoreHelper: Key Store exist
09-09 13:41:05.921  6114  6130 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-09 13:41:05.981  6114  6130 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
,09-09 13:41:05.981  6114  6130 I AcmsCertificateMngr: getKeyStoreForApplication success 
,09-09 13:41:05.981  6114  6130 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-09 13:41:05.981  6114  6130 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,09-09 13:41:05.981  6114  6130 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-09 13:41:05.981  6114  6130 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-09 13:41:05.981  6114  6130 D AcmsCore: This is NOT a valid MirrorLink app
09-09 13:41:05.981  6114  6130 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-09 13:41:05.981  6114  6130 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 13:41:05.981  6114  6130 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-09 13:41:05.981  6114  6130 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-09 13:41:05.981  6114  6114 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-09 13:41:05.981  6114  6114 D AcmsService: Enter onDestroy
09-09 13:41:05.981  6114  6114 I AcmsService: cleanUp(): inside service clean up
09-09 13:41:05.981  6114  6114 D AcmsCore: AcmsCore: inside DeInit
09-09 13:41:05.981  6114  6114 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-09 13:41:05.981  6114  6114 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-09 13:41:05.981  6114  6114 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-09 13:41:05.981  6114  6114 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-09 13:41:05.981  6114  6114 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
09-09 13:41:05.981  6114  6114 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-09 13:41:05.981  6114  6114 D AcmsService: killing acms process
09-09 13:41:05.981  6114  6114 I Process : Sending signal. PID: 6114 SIG: 9
,09-09 13:41:06.131  1014  3126 I ActivityManager: Process ACMS.Process (pid 6114)(adj 0) has died(43,1098)
,09-09 13:41:06.221  1014  1328 E Watchdog: !@Sync 3
,09-09 13:41:06.681   319   319 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-09 13:41:06.681   319   319 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-09 13:41:07.661   290   290 E SMD     : DCD OFF
,09-09 13:41:07.961  1014  1055 D PackageManager: [MSG] MCS_UNBIND
,09-09 13:41:07.971  1014  3125 I ActivityManager: Killing 5138:com.google.android.gm/u0a101 (adj 15): empty #31
,09-09 13:41:09.761  1014  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 13:41:10.661   290   290 E SMD     : DCD OFF
,09-09 13:41:11.031  5362  5362 D FactoryTest: Not factory mode
,09-09 13:41:11.031  5362  5362 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-09 13:41:11.031  5362  5362 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-09 13:41:11.031  5362  5362 D MTPRx   : still no open session command from host, so toast
,09-09 13:41:11.031  5362  5362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-09 13:41:11.031  5362  5362 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113248
09-09 13:41:11.031  5362  5362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-09 13:41:11.031  1014  1483 E PersonaManagerService: inState():  stateMachine is null !!
09-09 13:41:11.031  1014  1483 I PersonaManagerService: PersonaId don't exist
,09-09 13:41:11.031  1014  1483 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-09 13:41:11.041  1014  1483 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:41:11.041  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:11.041  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:11.041  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-09 13:41:11.041  1014  1483 W ActivityManager: mDVFSHelper.acquire()
,09-09 13:41:11.051  1014  1483 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:41:11.061  1014  1483 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 13:41:11.061  1014  1483 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:41:11.061  1014  1483 D InputDispatcher: Focused application set to: xxxx
,09-09 13:41:11.061  1014  1483 D InputDispatcher: Focus left window: 6146
,09-09 13:41:11.061  5362  5362 E MTPRx   : started activity for popup
,09-09 13:41:11.071  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 13:41:11.071  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:41:11.101  5362  5362 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-09 13:41:11.101  5362  5362 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 13:41:11.101  5362  5362 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 13:41:11.101  5362  5362 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:11.101  5362  5362 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:41:11.101  5362  5362 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:41:11.121  5362  5362 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-09 13:41:11.121  1014  1539 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 13:41:11.121  1014  1539 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:41:11.121  1014  1539 D InputDispatcher: Focused application set to: xxxx
,09-09 13:41:11.121  1014  1539 D InputDispatcher: Focus entered window: 6146
,09-09 13:41:11.131  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 13:41:11.131  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:41:11.131  1014  3124 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 13:41:11.131  1014  3124 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@783df96 attribute=null, token = android.os.BinderProxy@2db27fc5
,09-09 13:41:11.171  5362  5362 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-09 13:41:11.181  5362  5362 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-09 13:41:11.181  5362  5362 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-09 13:41:11.191  6146  6146 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:41:11.201  6146  6146 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-09 13:41:11.201  6146  6146 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:41:11.201  6146  6146 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-09 13:41:11.201  1014  1541 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 13:41:11.201  1014  1541 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-09 13:41:11.201  1014  1541 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 13:41:11.201  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:41:11.201  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 13:41:11.211  6146  6146 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:41:11.211  6146  6146 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 13:41:11.221  6146  6146 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2531a718 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@13002c39, 16908290=android.view.AbsSavedState$1@13002c39}, android:focusedViewId=100}]}]
09-09 13:41:11.221  6146  6146 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 13:41:11.221  6146  6146 V ActivityThread: updateVisibility : ActivityRecord{31ca6e73 token=android.os.BinderProxy@3f9627ad {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 13:41:11.221  6146  6146 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 13:41:11.221  6146  6146 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 13:41:11.221  6146  6146 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f9627ad time:113431
,09-09 13:41:11.221  1014  1342 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:41:11.681   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:11.931  1014  1039 I ActivityManager: Waited long enough for: ServiceRecord{227e4331 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,09-09 13:41:12.461  1014  1500 I ActivityManager: Killing 5315:com.dropbox.android/u0a92 (adj 15): empty #31
,09-09 13:41:12.681   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:13.661   290   290 E SMD     : DCD OFF,
,09-09 13:41:13.681   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:13.851  1014  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:13.851  1014  1500 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4185, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 13:41:13.851  1014  1500 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 13:41:13.851  1014  1500 D BatteryService: stay LED for charging
09-09 13:41:13.851  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:13.861  1014  1014 I MotionRecognitionService: Plugged
,09-09 13:41:13.861  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
09-09 13:41:13.861  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:41:13.861  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:13.861  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:13.861  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,09-09 13:41:13.871  2657  2657 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:13.871  2657  2729 D HeadsetStateMachine: Disconnected process message: 10
09-09 13:41:13.881  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
09-09 13:41:13.881  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
09-09 13:41:13.881  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:13.921  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 13:41:13.921  6146  6196 I jxcore-log: 
,09-09 13:41:13.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 13:41:13.931  6146  6196 I jxcore-log: 
,09-09 13:41:13.931  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:13.931  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:13.931  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:13.931  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:13.931  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:13.931  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:13.931  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:13.931  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:13.931  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:13.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 13:41:13.931  6146  6196 I jxcore-log: 
09-09 13:41:13.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 13:41:13.941  6146  6196 I jxcore-log: 
,09-09 13:41:14.041  1014  1039 W ActivityManager: mDVFSHelper.release()
,09-09 13:41:14.591  6146  6196 I jxcore-log: Unit Test app is loaded
09-09 13:41:14.591  6146  6196 I jxcore-log: 
,09-09 13:41:14.591  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:14.591  6146  6196 I jxcore-log: 
,09-09 13:41:14.601  6146  6146 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 13:41:14.611  6146  6196 D executeNativeTests: Running unit tests
,09-09 13:41:14.611  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:14.611  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11a2627e added. We now have 2 listener(s)
,09-09 13:41:14.611  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:41:14.611  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:14.611  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:14.611  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 13:41:14.611  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279a83df added. We now have 2 listener(s)
09-09 13:41:14.611  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:14.611  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:14.621  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:14.621  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:14.621  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:14.621  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:14.621  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:14.621  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:14.621  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:14.621  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:14.621  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:14.621  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:14.621  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:14.621  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:14.631  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:14.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:14.691  1014  2772 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-09 13:41:15.111  1014  2730 D SSRM:n  : SIOP:: AP = 400
,09-09 13:41:15.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:16.671   290   290 E SMD     : DCD OFF
,09-09 13:41:16.691   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-09 13:41:17.791  1014  1093 V AlarmManager: waitForAlarm result :4,
,09-09 13:41:17.801  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-09 13:41:17.801  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,09-09 13:41:17.811  5531  5566 I Finsky  : [950] com.google.android.finsky.c.e.run(1154): Replicating app states via AMAS.
,09-09 13:41:17.861  1946  1946 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-09 13:41:17.911  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:17.911  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-09 13:41:17.921  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:17.921  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:17.921  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:17.981  3798  3798 D ConnectivityManager: CallingUid : 10012, CallingPid : 3798
,09-09 13:41:17.981  1014  1214 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:17.981  1014  1131 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-09 13:41:17.981  1014  1131 D ConnectivityService: apparently satisfied.  currentScore=60
,09-09 13:41:17.991  1014  1131 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-09 13:41:17.991  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:18.041  3798  6213 W DriveInitializer: Background init thread started
,09-09 13:41:18.081   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-09 13:41:18.081   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:18.081  3798  6213 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-09 13:41:18.131  1014  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:18.131  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-09 13:41:18.131  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:18.131  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.131  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.151  1014  1027 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-09 13:41:18.151  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-09 13:41:18.161  3798  6213 W DriveInitializer: Background init thread ended
,09-09 13:41:18.181  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:18.181  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-09 13:41:18.181  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:18.181  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.181  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.191  3798  6221 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-09 13:41:18.191  3798  6221 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-09 13:41:18.221  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:18.261  5531  5566 I Finsky  : [950] com.google.android.finsky.c.c.a(316): Completed 0 account content syncs with 0 successful.
,09-09 13:41:18.261  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:18.261  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.261  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.261  5531  5531 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,09-09 13:41:18.341  1014  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:18.341  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-09 13:41:18.341  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:18.341  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.341  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.371  1014  1342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:18.371  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-09 13:41:18.371  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:18.371  1014  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.371  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.421  1014  1326 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:18.421  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:18.421  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.421  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.431  1014  3125 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:18.431  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:18.431  1014  3125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.431  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.461  1014  1326 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:18.461  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:18.461  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:18.461  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.461  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:18.461  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:18.461  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:18.471  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:18.481  6226  6226 E Zygote  : MountEmulatedStorage()
,09-09 13:41:18.481  6226  6226 E Zygote  : v2,
,09-09 13:41:18.481  6226  6226 I libpersona: KNOX_SDCARD checking this for 10012
09-09 13:41:18.481  6226  6226 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:18.481  1014  1326 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6226 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-09 13:41:18.481  6226  6226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:41:18.491  6226  6226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:41:18.491  6226  6226 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:41:18.501   306   306 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 19.897ms
,09-09 13:41:18.521   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 16.983ms
,09-09 13:41:18.531  6226  6226 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:18.531  6226  6226 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:18.541   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.917ms
,09-09 13:41:18.551  6226  6226 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 13:41:18.551  6226  6226 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:41:18.591  6226  6226 I MultiDex: VM with version 2.1.0 has multidex support
09-09 13:41:18.591  6226  6226 I MultiDex: install
09-09 13:41:18.591  6226  6226 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 13:41:18.621  6226  6226 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:18.681  6226  6226 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:41:18.681  6226  6226 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a05008d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:41:18.681  6226  6226 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 13:41:18.701  1014  3125 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-09 13:41:18.701  6226  6226 D ChimeraCfgMgr: Reading stored module config
,09-09 13:41:18.701  1014  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:18.711  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:18.711  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.711  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.771  6226  6240 I art     : Background sticky concurrent mark sweep GC freed 28605(1355KB) AllocSpace objects, 2(32KB) LOS objects, 5% free, 10MB/11MB, paused 6.308ms total 57.306ms
,09-09 13:41:18.791  1946  1959 I art     : Explicit concurrent mark sweep GC freed 60429(3MB) AllocSpace objects, 12(432KB) LOS objects, 39% free, 13MB/23MB, paused 1.495ms total 92.727ms
,09-09 13:41:18.801  6226  6244 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 13:41:18.801  1014  1539 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:18.811  1014  1539 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:18.811  1014  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:18.811  1014  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.811  6226  6226 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:41:18.811  6226  6226 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 13:41:18.841  1014  3124 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-09 13:41:18.841  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 13:41:18.841  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:18.841  1014  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:18.841  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.841  1946  1946 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=9a1d0be4-ccba-49a8-a347-97faaba32e5a
,09-09 13:41:18.851  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:18.851  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:18.881  1014  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:18.891  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:18.891  1014  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:18.891  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:18.921   282   282 D WVCdm   : Instantiating CDM.
,09-09 13:41:18.921   282   673 I WVCdm   : CdmEngine::OpenSession
,09-09 13:41:18.921   282   673 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-09 13:41:18.951   282   673 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-09 13:41:18.971   282   673 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
09-09 13:41:18.971   282   673 D DrmWidevineDash: Service_Initialize: starts!
09-09 13:41:18.971   282   673 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-09 13:41:18.971   282   673 D QSEECOMAPI: : App is not loaded in QSEE
09-09 13:41:18.971   282   673 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-09 13:41:18.971   282   673 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-09 13:41:18.971   282   673 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-09 13:41:18.971   282   673 D QSEECOMAPI: : App is not loaded in QSEE
09-09 13:41:18.971   282   673 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-09 13:41:18.971   282   673 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-09 13:41:18.971   282   673 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-09 13:41:18.971   282   673 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 13:41:18.991   282   673 D QSEECOMAPI: : Loaded image: APP id = 11
,09-09 13:41:18.991   282   673 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-09 13:41:18.991   282   673 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
09-09 13:41:18.991   282   673 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-09 13:41:18.991   282   673 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16d2000
09-09 13:41:18.991   282   673 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16d2000
09-09 13:41:18.991   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.001   433   441 D DrmLibTime: got the req here! ret=0
09-09 13:41:19.001   433   441 D DrmLibTime: command id, time_cmd_id = 770
09-09 13:41:19.001   433   441 D DrmLibTime: time_getutcsec starts!
09-09 13:41:19.001   433   441 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-09 13:41:19.001   433   441 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-09 13:41:19.001   433   441 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-09 13:41:19.001   433   441 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-09 13:41:19.001   433   441 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
09-09 13:41:19.001   433   441 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-09 13:41:19.001   433   441 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
09-09 13:41:19.001   433   441 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,09-09 13:41:19.001   321   427 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-09 13:41:19.001   321  6250 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
09-09 13:41:19.001   321  6250 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
09-09 13:41:19.001   321  6250 D QC-time-services: offset is: 0 for base: 0
09-09 13:41:19.001   433   441 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
09-09 13:41:19.001   433   441 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
09-09 13:41:19.001   433   441 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1473421279
09-09 13:41:19.001   433   441 D DrmLibTime: time_getutcsec returns 0, sec = 1473421279; nsec = 0
09-09 13:41:19.001   433   441 D DrmLibTime: time_getutcsec finished! 
09-09 13:41:19.001   433   441 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-09 13:41:19.001   433   441 D DrmLibTime: before calling ioctl to read the next time_cmd
09-09 13:41:19.001   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 13:41:19.001   321   427 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-09 13:41:19.011   282   673 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-09 13:41:19.011   282   673 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-09 13:41:19.011   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.011   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.011   282   673 D DrmWidevineDash: hlos api version =  9
09-09 13:41:19.011   282   673 D DrmWidevineDash: tz api version =  9
09-09 13:41:19.011   282   673 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-09 13:41:19.011   282   673 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-09 13:41:19.011   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.041   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-09 13:41:19.041   282   673 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1926960
09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-09 13:41:19.041   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-09 13:41:19.041   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8ceec90, dataLength=8
09-09 13:41:19.041   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.041   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb8cf75c0, wrapped_rsa_key_length=1280
09-09 13:41:19.041   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.041   282   673 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.041   282   673 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-09 13:41:19.041   282   673 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 13:41:19.041   282   282 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 13:41:19.041   282   282 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 13:41:19.041   282   282 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 13:41:19.041   282   282 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8d0c340, idLength=0xbe90ef80
09-09 13:41:19.041   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.051   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.051   282   282 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-09 13:41:19.051   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-09 13:41:19.051   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.051   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.051   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-09 13:41:19.051   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-09 13:41:19.051   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-09 13:41:19.051   282   282 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xbe90ef96, maximum = 0xbe90ef97
09-09 13:41:19.051   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-09 13:41:19.051   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 13:41:19.051   282   282 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-09 13:41:19.061   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-09 13:41:19.061   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-09 13:41:19.061   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.061   282   282 D DrmWidevineDash: hlos api version =  9
09-09 13:41:19.061   282   282 D DrmWidevineDash: tz api version =  9
09-09 13:41:19.061   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-09 13:41:19.061   282   282 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xbe90f004
09-09 13:41:19.061   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.061   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.061   282   282 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-09 13:41:19.061   282   282 D WVCdm   : PrepareKeyRequest: nonce=1980322223
09-09 13:41:19.061   282   282 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8cf7438
09-09 13:41:19.061   282   282 D DrmWidevineDash: message_length=1599, signature=0xb8cf7a80, signature_length=0xbe90ef64
09-09 13:41:19.061   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.071  1656  2141 I art     : Explicit concurrent mark sweep GC freed 1677(59KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 686us total 33.627ms
,09-09 13:41:19.081  6226  6237 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-09 13:41:19.081  6226  6237 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:19.081  6226  6237 I System.out: (HTTPLog)-Static: isShipBuild true
09-09 13:41:19.081  6226  6237 I System.out: (HTTPLog)-Thread-1050-76280678: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 13:41:19.081  6226  6237 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:19.091   277   992 D EnterpriseController: uids 10012
09-09 13:41:19.091   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:19.091   277   992 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 13:41:19.131  6226  6237 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:19.131  6226  6237 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6226, getuid(): 10012
,09-09 13:41:19.161  1946  2112 W GCoreFlp: No location to return for getLastLocation()
,09-09 13:41:19.211   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 13:41:19.211   282   282 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-09 13:41:19.211   282   699 I WVCdm   : CdmEngine::CloseSession
,09-09 13:41:19.211   282   699 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-09 13:41:19.211   282   699 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.211   282   699 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 13:41:19.211   282   699 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-09 13:41:19.211   282   699 I WVCdm   : L3 Terminate.
09-09 13:41:19.211   282   699 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-09 13:41:19.211   282   699 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 13:41:19.211   282   699 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 13:41:19.211   282   699 D DrmWidevineDash: Service_Uninitialize: starts!
09-09 13:41:19.211   282   699 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-09 13:41:19.211   282   699 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-09 13:41:19.211   282   699 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-09 13:41:19.211   282   699 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-09 13:41:19.311  1014  1342 I art     : Explicit concurrent mark sweep GC freed 31219(1647KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 28MB/42MB, paused 2.478ms total 144.489ms
,09-09 13:41:19.331  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:19.331  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:19.331  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:19.331  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:19.341  1014  1326 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:19.341  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:19.341  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:19.341  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:19.351  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:19.361  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:19.361  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:19.361  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:19.381  3798  6222 D UdcContextInitService: registered all accounts: true
,09-09 13:41:19.381  1946  2118 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 13:41:19.401  1946  2127 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-09 13:41:19.421  6226  6237 I qtaguid : Untagging socket 30
,09-09 13:41:19.571  1014  3124 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-09 13:41:19.571  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 13:41:19.571  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:19.571  1014  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:19.571  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:19.661   290   290 E SMD     : DCD OFF
,09-09 13:41:19.731  6258  6258 I dex2oat : ----------------------------------------------------,
09-09 13:41:19.731  6258  6258 I dex2oat : <SS>: S T A R T I N G . . .
09-09 13:41:19.731  6258  6258 I dex2oat : <SS>: Zip is absent. Canceled.
,09-09 13:41:19.731  6258  6258 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 13:41:19.761  6258  6258 I dex2oat : dex2oat took 24.650ms (threads: 4)
,09-09 13:41:19.771  6226  6237 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:41:19.771  6226  6237 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:41:19.771  6226  6237 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:41:19.771  6226  6237 I Adreno-EGL: Local Branch: 
09-09 13:41:19.771  6226  6237 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:41:19.771  6226  6237 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:41:19.771  6226  6237 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:41:19.871  6226  6237 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:41:19.871  6226  6237 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:41:19.871  6226  6237 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:41:19.871  6226  6237 I Adreno-EGL: Local Branch: 
09-09 13:41:19.871  6226  6237 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:41:19.871  6226  6237 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:41:19.871  6226  6237 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:41:19.981  6226  6237 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:41:19.981  6226  6237 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:41:19.981  6226  6237 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:41:19.981  6226  6237 I Adreno-EGL: Local Branch: 
09-09 13:41:19.981  6226  6237 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:41:19.981  6226  6237 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:41:19.981  6226  6237 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:41:20.361  1014  1137 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-09 13:41:20.361  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-09 13:41:20.361  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:20.361  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:20.361  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:20.371  1946  6224 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:20.371   277   992 D EnterpriseController: uids 10012
09-09 13:41:20.371   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:20.371   277   992 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 13:41:20.371  1946  6224 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:20.371  1946  6224 I qtaguid : Tagging socket 59 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1946, getuid(): 10012
,09-09 13:41:20.411  1946  6224 I qtaguid : Tagging socket 67 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1946, getuid(): 10012
,09-09 13:41:20.571  1946  2127 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:41:20.581  1946  2127 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-09 13:41:20.581  1946  2127 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-09 13:41:19.501+0200, stopTime=2016-09-09 13:41:20.594+0200, duration=1093ms
,09-09 13:41:20.591  1946  6270 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:20.601   277   992 D EnterpriseController: uids 10012
09-09 13:41:20.601   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:20.601   277   992 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 13:41:20.611  1946  6270 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-09 13:41:20.611  1946  6270 I qtaguid : Tagging socket 70 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1946, getuid(): 10012
,09-09 13:41:20.661  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-09 13:41:20.671  1946  6270 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1946, getuid(): 10012
,09-09 13:41:20.981  1946  6270 I qtaguid : Untagging socket 70
,09-09 13:41:21.021  1014  1541 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:21.021  1014  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,09-09 13:41:21.021  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.021  1014  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.021  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.061  1014  3126 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:21.061  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-09 13:41:21.061  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.061  1014  3126 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.061  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.091  1946  2127 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-09 13:41:21.091  1014  1500 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.101  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.101  1014  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.101  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.101  1014  1535 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.101  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.101  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.101  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.111  1946  1946 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:41:21.191  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.191  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.191  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.191  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.221  1014  3126 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.221  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.221  1014  3126 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.221  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.221  1946  6277 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:41:21.221  1946  6274 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:41:21.221  1014  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.231  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.231  1014  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.231  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.251  1014  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.251  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.251  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.251  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.251  1946  6277 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:41:21.251  1946  6274 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:41:21.251  1014  3125 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.251  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.251  1014  3125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.251  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.281  1014  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.281  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.281  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:21.281  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:21.281  1946  6277 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 13:41:21.281  1946  6274 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 13:41:21.281  1946  6274 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-09 13:41:21.291  1946  6274 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 13:41:21.361  1946  6274 I art     : Explicit concurrent mark sweep GC freed 35154(2MB) AllocSpace objects, 19(590KB) LOS objects, 39% free, 14MB/23MB, paused 1.493ms total 66.987ms
,09-09 13:41:21.371  1946  6273 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:21.371  1946  6273 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:21.371  1946  6273 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1946, getuid(): 10012
,09-09 13:41:21.401  1014  1026 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:21.421  1946  6273 I qtaguid : Tagging socket 84 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1946, getuid(): 10012
,09-09 13:41:21.441  1946  6274 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:21.441   277   992 D EnterpriseController: uids 10012
09-09 13:41:21.441   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:21.441   277   992 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 13:41:21.441  1946  6274 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:21.441  1946  6274 I qtaguid : Tagging socket 85 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:21.481  1946  6274 I qtaguid : Tagging socket 88 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:21.621  1946  6273 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:21.631  1946  6273 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:21.631  1946  6273 I qtaguid : Tagging socket 89 with tag 1000120300000000{268440067,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:21.671  1946  6273 I qtaguid : Tagging socket 92 with tag 1000120300000000{268440067,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:21.681   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:21.771  1014  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:21.781  1946  6274 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:21.781  1946  6274 I qtaguid : Tagging socket 85 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:21.861  1946  6273 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:21.861  1946  6273 I qtaguid : Tagging socket 89 with tag 1000120300000000{268440067,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:21.921  1014  1541 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:21.921  1946  6274 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:21.931  1946  6274 I qtaguid : Tagging socket 85 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:21.961  1014  1214 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:21.961  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:21.961  1014  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:21.961  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:22.001  1014  1539 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:22.001  1014  1539 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:22.001  1014  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:22.001  1014  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:22.021  1946  6273 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,09-09 13:41:22.021  1014  1326 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:22.031  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:22.031  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:22.031  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:22.031  1946  6273 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,09-09 13:41:22.051  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:22.051  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:22.051  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:22.081  1014  1137 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 13:41:22.101  1946  6274 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:22.101  1946  6274 I qtaguid : Tagging socket 85 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:22.661   290   290 E SMD     : DCD OFF
,09-09 13:41:22.681   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:22.751  1946  6268 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:22.751  1946  6268 I qtaguid : Tagging socket 70 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1946, getuid(): 10012
,09-09 13:41:23.011  1946  6268 I qtaguid : Untagging socket 70
,09-09 13:41:23.021  1946  2135 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-09 13:41:23.031  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-09 13:41:23.681   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:23.921  1014  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:23.921  1014  1500 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 13:41:23.921  1014  1500 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-09 13:41:23.921  1014  1500 D BatteryService: stay LED for charging
,09-09 13:41:23.921  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:23.921  1014  1014 I MotionRecognitionService: Plugged
,09-09 13:41:23.921  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:23.931  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:23.931  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,09-09 13:41:23.931  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 13:41:23.931  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:23.941  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:23.941  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:23.951  2657  2657 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:41:23.951  2657  2729 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:23.961  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:24.681   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:24.731  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:24.731  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 added. We now have 3 listener(s)
,09-09 13:41:24.731  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:41:24.731  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 13:41:24.731  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:24.731  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-09 13:41:24.731  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a added. We now have 3 listener(s)
09-09 13:41:24.731  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,09-09 13:41:24.731  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:24.741  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:24.741  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:24.741  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:24.741  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:24.741  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:24.741  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:24.741  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:24.741  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:24.741  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:24.741  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:24.741  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:24.751  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:24.751  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:24.751  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 13:41:24.751  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-09 13:41:24.751  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:41:24.751  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 13:41:24.761  6146  6196 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
09-09 13:41:24.761  6146  6196 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 13:41:24.761  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:24.761  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:24.761  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 13:41:24.761  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:24.761  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:24.761  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.761  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:24.761  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:24.761  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 removed from the list
09-09 13:41:24.761  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:24.761  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a removed from the list
09-09 13:41:24.761  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:24.761  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:24.761  6146  6196 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 13:41:24.761  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:24.761  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.761  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:24.761  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:24.761  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:24.761  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:24.761  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:24.761  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.761  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:24.771  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:24.771  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.771  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:24.771  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:24.771  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:24.771  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:24.771  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:24.771  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:24.771  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:24.771  6146  6196 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:41:24.771  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:24.781  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:24.781  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:24.781  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:24.781  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:24.781  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:24.781  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:24.781  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:24.781  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:24.781  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:24.781  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:24.781  6146  6196 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-09 13:41:24.781  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 13:41:24.781  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:24.781  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:24.781  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:24.781  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:24.781  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:24.781  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:24.781  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:24.781  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:24.781  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:24.791  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:24.791  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:24.791  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:24.791  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:24.791  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:24.791  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:41:24.791  6146  6284 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:24.791  6146  6284 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:24.801  6146  6284 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
09-09 13:41:24.801  6146  6284 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:24.801  6146  6284 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:24.801  6146  6284 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@76c2e06
09-09 13:41:24.801  6146  6284 D BluetoothSocket: channel: 6
,09-09 13:41:24.801  6146  6284 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:24.801  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:24.801  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 13:41:24.811  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:41:24.811  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:24.811  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 7C F9 0E 37 96 AB
09-09 13:41:24.811  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.811  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.811  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:41:24.821  2657  2918 D BtGatt.GattService: registerClient() - UUID=b4778ca5-cfb5-4e56-8caf-d62976b9e6ea
,09-09 13:41:24.861  2657  2725 D BtGatt.GattService: onClientRegistered() - UUID=b4778ca5-cfb5-4e56-8caf-d62976b9e6ea, clientIf=6
09-09 13:41:24.861  6146  6154 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
09-09 13:41:24.861  2657  2727 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:24.881  2657  2727 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 9
,09-09 13:41:24.881  2657  2727 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:41:24.881  2657  2727 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:24.881  2657  2727 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:24.881  2657  2727 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:24.901  2657  2725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:24.901  2657  2727 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:24.911  2657  2725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:24.911  2657  2727 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:24.911  2657  2727 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:24.911  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:24.911  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:24.911  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:24.921  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:24.921  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:24.921  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-09 13:41:24.921  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:41:24.921  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:41:24.921  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:24.921  6146  6146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:24.931  6146  6196 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:24.931  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:24.931  6146  6196 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:41:24.931  6146  6196 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 13:41:24.931  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:41:24.931  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:41:24.931  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:24.931  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:24.931  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:24.931  6146  6196 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1eb692f4, channel: 6, state: LISTENING
09-09 13:41:24.931  6146  6196 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1eb692f4, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@76c2e06, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@113b1a1dmSocket: android.net.LocalSocket@278d2492 impl:android.net.LocalSocketImpl@33293e63 fd:FileDescriptor[108]
09-09 13:41:24.931  6146  6196 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@278d2492 impl:android.net.LocalSocketImpl@33293e63 fd:FileDescriptor[108]
09-09 13:41:24.931  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:24.931  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:41:24.931  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:41:24.931  6146  6284 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1eb692f4, channel: 6, state: CLOSED
09-09 13:41:24.931  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:24.931  6146  6284 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:24.931  6146  6284 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:41:24.931  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:24.931  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:41:24.931  6146  6284 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:41:24.931  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:24.931  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:24.931  6146  6196 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:24.931  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:41:24.931  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:24.941  2657  2727 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:24.941  2657  2727 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:41:24.941  2657  2727 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:41:24.941  2657  2727 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:24.941  2657  2725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:41:24.941  2657  2725 D BtGatt.GattService: Client app is not null!
09-09 13:41:24.941  2657  2917 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 13:41:24.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:24.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:24.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:24.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:24.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:24.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:24.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-09 13:41:24.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:24.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:24.951  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 13:41:24.951  6146  6146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:24.951  6146  6146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:24.951  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:24.951  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:24.951  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:24.951  6146  6196 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:41:24.951  6146  6196 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-09 13:41:24.951  6146  6196 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-09 13:41:24.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-09 13:41:24.961  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:24.961  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:41:24.961  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:24.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:24.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:24.961  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:24.961  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:41:24.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:24.961  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:41:24.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:24.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:24.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:24.961  6146  6290 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:41:24.971  6146  6290 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:24.971  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:24.971  6146  6290 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
09-09 13:41:24.971  6146  6290 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:24.971  6146  6290 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:24.971  6146  6290 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1354f7de
09-09 13:41:24.971  6146  6290 D BluetoothSocket: channel: 6
09-09 13:41:24.971  6146  6290 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:24.971  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:24.971  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:24.981  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:24.981  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:24.981  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 7C F9 0E 37 96 AB
09-09 13:41:24.981  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.981  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:24.981  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:24.981  2657  2918 D BtGatt.GattService: registerClient() - UUID=59e69a34-bd4b-4387-8008-7fa624f3ece2
,09-09 13:41:25.021  2657  2725 D BtGatt.GattService: onClientRegistered() - UUID=59e69a34-bd4b-4387-8008-7fa624f3ece2, clientIf=6
,09-09 13:41:25.021  6146  6155 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:25.021  2657  2727 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:25.031  1014  1046 I PowerManagerService: [PWL] Off : 50s ago
,09-09 13:41:25.031  1014  1046 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-09 13:41:25.031  1014  1046 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-09 13:41:25.031  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2657, ws=null) (elapsedTime=146)
,09-09 13:41:25.041  2657  2727 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 10
,09-09 13:41:25.041  2657  2727 D BtGatt.AdvertiseManager: number of adv instance running0,
,09-09 13:41:25.041  2657  2727 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:25.041  2657  2727 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:25.041  2657  2727 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:25.051  2657  2725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:25.051  2657  2727 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:25.061  2657  2725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:25.061  2657  2727 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:25.061  2657  2727 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:25.061  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:25.061  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:25.061  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:25.061  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:25.071  6146  6196 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:25.071  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 13:41:25.071  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:25.071  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 13:41:25.071  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:25.071  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:25.071  6146  6146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:25.071  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:25.131  1014  2730 D SSRM:n  : SIOP:: AP = 380
,09-09 13:41:25.351  1014  1535 I ActivityManager: Killing 5290:com.google.android.talk/u0a104 (adj 15): empty #31
,09-09 13:41:25.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:25.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:25.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:25.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:25.571  6146  6196 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@354d4c8c, channel: 6, state: LISTENING
09-09 13:41:25.571  6146  6196 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@354d4c8c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1354f7de, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f846fd5mSocket: android.net.LocalSocket@3934b3ea impl:android.net.LocalSocketImpl@3b3e16db fd:FileDescriptor[108]
09-09 13:41:25.571  6146  6196 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3934b3ea impl:android.net.LocalSocketImpl@3b3e16db fd:FileDescriptor[108]
,09-09 13:41:25.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:25.571  6146  6290 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@354d4c8c, channel: 6, state: CLOSED
09-09 13:41:25.571  6146  6290 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:25.571  6146  6290 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:25.571  6146  6290 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:41:25.571  6146  6146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:25.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:25.571  6146  6146 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:41:25.571  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:25.571  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:25.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:25.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:25.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:25.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:25.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:25.571  6146  6196 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:25.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:25.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:25.581  2657  2727 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:25.581  2657  2727 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:41:25.581  2657  2727 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:41:25.581  2657  2727 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:25.591  2657  2725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:41:25.591  2657  2725 D BtGatt.GattService: Client app is not null!
,09-09 13:41:25.591  2657  2666 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:25.591  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:25.591  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:25.591  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:41:25.591  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:41:25.591  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:25.591  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:25.591  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:41:25.601  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 13:41:25.601  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:25.601  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:25.601  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:25.601  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:25.601  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
,09-09 13:41:25.601  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:25.601  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:25.601  6146  6196 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-09 13:41:25.611  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.611  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:25.611  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:25.611  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:25.611  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:25.611  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:25.611  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:25.611  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:25.611  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:25.611  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:25.611  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:25.621  6146  6196 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-09 13:41:25.621  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-09 13:41:25.621  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:25.621  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:25.621  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:25.621  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.621  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:25.621  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:25.631  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:25.631  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:41:25.631  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:41:25.631  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:41:25.631  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:25.631  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-09 13:41:25.631  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:25.631  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:25.631  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:25.641  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:25.641  6146  6293 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:25.641  6146  6293 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:25.641  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:25.641  6146  6293 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
09-09 13:41:25.641  6146  6293 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:25.641  6146  6293 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:25.641  6146  6293 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35fd45b7
09-09 13:41:25.641  6146  6293 D BluetoothSocket: channel: 6
09-09 13:41:25.641  6146  6293 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:25.641  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:25.641  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:25.641  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 7C F9 0E 37 96 AB
,09-09 13:41:25.651  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:25.651  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:25.651  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:25.651  2657  2666 D BtGatt.GattService: registerClient() - UUID=396d7d05-e9bb-4065-a106-721c3d2c998d
,09-09 13:41:25.671   290   290 E SMD     : DCD OFF
,09-09 13:41:25.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:25.691  2657  2725 D BtGatt.GattService: onClientRegistered() - UUID=396d7d05-e9bb-4065-a106-721c3d2c998d, clientIf=6
,09-09 13:41:25.691  6146  6154 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6,
,09-09 13:41:25.691  2657  2727 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:25.711  2657  2727 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 11
,09-09 13:41:25.711  2657  2727 D BtGatt.AdvertiseManager: number of adv instance running0
09-09 13:41:25.711  2657  2727 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:25.711  2657  2727 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:25.711  2657  2727 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:25.721  2657  2725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:25.721  2657  2727 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:25.721  2657  2725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:25.721  2657  2727 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:25.721  2657  2727 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:25.731  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:41:25.731  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:25.731  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:25.731  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:25.731  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:25.731  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:25.731  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:41:25.731  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-09 13:41:25.731  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:25.741  6146  6196 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:25.741  6146  6146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:25.741  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:26.241  6146  6196 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 13:41:26.241  6146  6196 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 13:41:26.241  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-09 13:41:26.241  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 13:41:26.241  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:26.241  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:26.241  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:26.241  6146  6196 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@207bc48d, channel: 6, state: LISTENING
09-09 13:41:26.241  6146  6196 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@207bc48d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35fd45b7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ca3d642mSocket: android.net.LocalSocket@16168653 impl:android.net.LocalSocketImpl@3bb6ab90 fd:FileDescriptor[108]
09-09 13:41:26.241  6146  6196 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@16168653 impl:android.net.LocalSocketImpl@3bb6ab90 fd:FileDescriptor[108]
,09-09 13:41:26.241  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:26.241  6146  6293 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@207bc48d, channel: 6, state: CLOSED
09-09 13:41:26.241  6146  6293 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:26.241  6146  6293 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:26.241  6146  6293 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:41:26.241  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:26.241  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:26.241  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:26.241  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:26.241  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:26.241  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:26.241  6146  6146 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:41:26.241  6146  6196 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:26.241  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:26.241  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:26.241  2657  2727 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:26.241  2657  2727 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:41:26.251  2657  2727 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:41:26.251  2657  2727 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:26.251  2657  2725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:41:26.251  2657  2725 D BtGatt.GattService: Client app is not null!
,09-09 13:41:26.251  2657  2665 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:26.261  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:26.261  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:26.261  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:26.261  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:26.261  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:26.261  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:26.261  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:26.261  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:26.261  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:26.261  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:26.261  6146  6146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:26.261  6146  6146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:26.261  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:26.261  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:26.261  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:26.261  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:26.261  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:26.271  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.271  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:26.271  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.271  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:26.271  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.271  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:26.271  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.271  6146  6196 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-09 13:41:26.271  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:26.271  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.271  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.271  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
,09-09 13:41:26.271  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.271  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
,09-09 13:41:26.271  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.271  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:26.271  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.281  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-09 13:41:26.281  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:26.281  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:26.281  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.281  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
,09-09 13:41:26.281  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.281  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
,09-09 13:41:26.281  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.281  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:26.281  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.281  6146  6196 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 13:41:26.281  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 13:41:26.281  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.281  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.281  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.281  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.281  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
,09-09 13:41:26.281  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.281  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:26.281  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.281  6146  6196 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 13:41:26.281  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:26.281  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.281  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.281  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.281  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.281  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.281  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.281  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.281  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.281  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:26.291  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:26.291  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:26.291  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:26.291  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:26.291  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:26.291  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 13:41:26.291  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:26.291  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 13:41:26.291  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.291  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.291  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.291  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.291  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.291  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.291  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.291  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.291  6146  6196 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.291  6146  6196 E io.jxcore.node,.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 13:41:26.291  6146  6196 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
,09-09 13:41:26.291  6146  6196 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 13:41:26.291  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 13:41:26.291  6146  6196 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 13:41:26.291  6146  6196 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:26.291  6146  6196 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 13:41:26.291  6146  6196 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.291  6146  6196 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:26.291  6146  6196 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 13:41:26.291  6146  6196 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.291  6146  6196 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 13:41:26.291  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 13:41:26.301  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 13:41:26.301  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 13:41:26.301  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 13:41:26.301  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 13:41:26.301  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 13:41:26.301  6146  6196 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 13:41:26.301  6146  6196 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 13:41:26.301  6146  6196 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 13:41:26.301  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.301  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.301  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.301  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 13:41:26.301  6146  6297 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1168)
09-09 13:41:26.301  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.301  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.301  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.301  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.301  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.301  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.301  6146  6298 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1168
09-09 13:41:26.311  6146  6196 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 13:41:26.311  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.311  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.311  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.311  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.311  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.311  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.311  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.311  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.311  6146  6196 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 13:41:26.311  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.311  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.311  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.311  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.311  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.311  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.311  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.311  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 13:41:26.311  6146  6196 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 13:41:26.311  6146  6196 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:26.311  6146  6196 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:26.311  6146  6196 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 13:41:26.311  6146  6196 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 13:41:26.311  6146  6196 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 13:41:26.311  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.311  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.311  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.311  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.311  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.311  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.311  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.311  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.311  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.311  6146  6196 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-09 13:41:26.311  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.321  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:26.321  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.321  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:26.321  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:26.321  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.321  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.321  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:26.321  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:26.321  6146  6297 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-09 13:41:26.321  6146  6297 D BluetoothSocket: connect(): myUserId = 0
09-09 13:41:26.321  6146  6297 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:26.321  2657  2665 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:26.321  6146  6297 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-09 13:41:26.321  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.321  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:26.331  6146  6196 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-09 13:41:26.331  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-09 13:41:26.331  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:26.331  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:26.331  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:26.331  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.331  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:26.331  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:26.331  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:26.331  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:26.331  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:26.331  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:26.331  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:26.331  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.331  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 13:41:26.331  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:26.331  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:26.331  6146  6299 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:26.331  6146  6299 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:26.341  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 13:41:26.341  6146  6299 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
09-09 13:41:26.341  6146  6299 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:26.341  6146  6299 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:26.341  6146  6299 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1202f0bc
09-09 13:41:26.341  6146  6299 D BluetoothSocket: channel: 6
09-09 13:41:26.341  6146  6299 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-09 13:41:26.341  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:26.341  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-09 13:41:26.341  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:26.341  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 7C F9 0E 37 96 AB
09-09 13:41:26.341  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:26.341  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:26.341  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 13:41:26.341  2657  2917 D BtGatt.GattService: registerClient() - UUID=09120a0a-32ac-4181-9c77-9427128982d7
,09-09 13:41:26.381  2657  2725 D BtGatt.GattService: onClientRegistered() - UUID=09120a0a-32ac-4181-9c77-9427128982d7, clientIf=6
,09-09 13:41:26.381  6146  6155 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:26.391  2657  2727 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:26.401  2657  2727 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 12
,09-09 13:41:26.401  2657  2727 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:41:26.401  2657  2727 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:26.401  2657  2727 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:26.401  2657  2727 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:26.401  2657  2725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:26.401  2657  2727 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:26.411  2657  2725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:26.411  2657  2727 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:26.411  2657  2727 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:26.411  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-09 13:41:26.411  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:26.411  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:26.411  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:26.411  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:26.411  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:26.411  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:41:26.411  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:26.411  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:26.421  6146  6196 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 13:41:26.421  6146  6146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:26.421  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:26.691   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-09 13:41:26.921  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:26.921  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:26.921  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 13:41:26.921  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:26.921  6146  6196 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@ad9eb9a, channel: 6, state: LISTENING
,09-09 13:41:26.921  6146  6146 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:41:26.921  6146  6196 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@ad9eb9a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1202f0bc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@17ae6ccbmSocket: android.net.LocalSocket@2a6c5ca8 impl:android.net.LocalSocketImpl@264ed3c1 fd:FileDescriptor[110]
09-09 13:41:26.921  6146  6196 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a6c5ca8 impl:android.net.LocalSocketImpl@264ed3c1 fd:FileDescriptor[110]
,09-09 13:41:26.921  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 13:41:26.921  6146  6299 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@ad9eb9a, channel: 6, state: CLOSED
09-09 13:41:26.921  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 13:41:26.921  6146  6299 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:26.921  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:26.921  6146  6299 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:26.921  6146  6299 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:26.921  6146  6146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 13:41:26.921  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.921  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.921  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:26.921  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:26.921  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:26.921  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 13:41:26.921  6146  6196 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:26.921  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:26.921  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-09 13:41:26.931  2657  2727 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:26.931  2657  2727 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:41:26.931  2657  2727 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
,09-09 13:41:26.931  2657  2727 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:26.931  2657  2725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,09-09 13:41:26.931  2657  2725 D BtGatt.GattService: Client app is not null!
,09-09 13:41:26.931  2657  2665 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:26.941  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 13:41:26.941  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:26.941  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 13:41:26.941  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:26.941  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:26.941  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:26.941  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:26.941  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:26.941  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:26.941  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:26.941  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:26.941  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:26.941  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.941  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.941  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.941  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:26.941  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:26.941  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.941  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
,09-09 13:41:26.941  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.951  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
,09-09 13:41:26.951  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.951  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:26.951  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:26.951  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.951  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:26.951  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.951  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:26.951  6146  6303 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:26.951  6146  6303 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:26.951  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.951  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.951  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.951  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.961  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:26.961  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:26.961  6146  6146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:26.961  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:26.961  6146  6196 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 13:41:26.961  6146  6196 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 13:41:26.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 13:41:26.961  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:26.961  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 13:41:26.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:26.961  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.961  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.961  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.961  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.961  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
,09-09 13:41:26.961  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.961  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.961  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-09 13:41:26.971  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.971  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.971  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.971  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.971  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.971  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.971  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.971  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.971  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.971  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.971  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:26.971  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7ae365 not in the list
09-09 13:41:26.971  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.971  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db9c83a not in the list
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.971  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.971  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.971  6146  6196 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-09 13:41:26.971  6146  6196 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-09 13:41:26.971  6146  6196 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 13:41:26.971  6146  6196 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 13:41:26.971  6146  6196 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-09 13:41:26.971  6146  6196 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 13:41:26.971  6146  6196 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing,
,09-09 13:41:26.981  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 13:41:26.981  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37b50aa7 added. We now have 3 listener(s)
,09-09 13:41:26.981  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:26.981  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:26.981  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:26.981  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:26.981  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57e9b54 added. We now have 3 listener(s)
09-09 13:41:26.981  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:26.981  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:26.981  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:26.991  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:26.991  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:26.991  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:26.991  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:26.991  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:26.991  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:26.991  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:26.991  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:26.991  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:26.991  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:26.991  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:26.991  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:26.991  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:26.991  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:26.991  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:26.991  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:26.991  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37b50aa7 removed from the list
09-09 13:41:26.991  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:26.991  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57e9b54 removed from the list
09-09 13:41:26.991  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:26.991  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:26.991  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:26.991  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@316253f2 added. We now have 3 listener(s)
,09-09 13:41:27.001  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:41:27.001  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:27.001  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:27.001  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:27.001  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b9daa43 added. We now have 3 listener(s)
09-09 13:41:27.001  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:27.001  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:27.001  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:27.011  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:27.011  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:27.011  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:27.011  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:27.011  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:27.011  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:27.011  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:27.011  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:27.011  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:27.011  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:27.011  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.011  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.021  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:27.021  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 13:41:27.021  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:27.021  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:27.021  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@316253f2 removed from the list
09-09 13:41:27.021  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:27.021  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b9daa43 removed from the list
09-09 13:41:27.021  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:27.021  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:27.021  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:27.021  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45939f9 added. We now have 3 listener(s)
,09-09 13:41:27.021  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:41:27.021  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:27.021  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 13:41:27.021  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:27.021  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@193dbd3e added. We now have 3 listener(s)
,09-09 13:41:27.021  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:27.021  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:27.021  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:27.031  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:27.031  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:27.031  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:27.031  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:27.031  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:27.031  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:27.031  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:27.031  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:27.031  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:27.031  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:27.031  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.031  1014  1342 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:41:27.031  1014  1342 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:41:27.031  1014  1342 D SecContentProvider2: mCursor = null
,09-09 13:41:27.041  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.041  1014  1342 D WifiService: setWifiEnabled: false pid=6146, uid=10155
,09-09 13:41:27.041  1014  1342 D SettingsProvider: name = wifi_on
,09-09 13:41:27.041  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:41:27.051  2102  2102 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:27.051  2102  2102 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 13:41:27.051  2102  2102 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-09 13:41:27.051  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-09 13:41:27.051  2102  2102 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:27.071  1014  1125 E WifiNative-wlan0: do suspend true,
,09-09 13:41:27.221  2102  2102 I wpa_supplicant: Scan aborted because the firmware maybe busy.,
09-09 13:41:27.221  2102  2102 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
09-09 13:41:27.221  2102  2102 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,09-09 13:41:27.221  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-09 13:41:27.221  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:27.221  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 13:41:27.221  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:27.221  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.221  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.221  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.221  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.231   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:27.231  1946  4531 V NativeCrypto: Read error: ssl=0xb8475e60: I/O error during system call, Connection timed out
09-09 13:41:27.241  1014  1027 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
09-09 13:41:27.231  1946  4531 V NativeCrypto: SSL shutdown failed: ssl=0xb8475e60: I/O error during system call, Broken pipe
09-09 13:41:27.241  1946  4531 E GCM     : Wifi connection closed with errorCode 20
09-09 13:41:27.241  1014  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.241  1014  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.241  1014  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:27.241  1014  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.241  1014  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-09 13:41:27.241  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:27.241  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:27.241  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:27.241  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,09-09 13:41:27.251  1014  2219 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:41:27.251  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:41:27.251  1014  2219 I qtaguid : Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
09-09 13:41:27.251  1014  2219 I qtaguid : Untagging socket 360
09-09 13:41:27.251  1014  2219 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:27.261  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:27.261  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:27.271  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:27.271  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.271  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.271  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:27.271  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
,09-09 13:41:27.271  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 13:41:27.271  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 13:41:27.271  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 13:41:27.271  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:27.281  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-09 13:41:27.281  1014  3125 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:27.281  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.281  1014  3125 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:27.281  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:27.281  1014  3125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:27.281  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:27.281  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 13:41:27.281  3632  3632 I Hs20UtilService: Starting #8
09-09 13:41:27.281  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:27.281  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:27.281  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:27.281  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:27.281  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:27.291  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:27.291  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:27.291  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:41:27.291  1014  1124 D WifiP2pService: P2pDisablingState
09-09 13:41:27.291  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:41:27.291  1014  1124 D WifiP2pService: p2p socket connection lost
09-09 13:41:27.291  1014  1124 D WifiP2pService: P2pDisabledState
09-09 13:41:27.301  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
09-09 13:41:27.301  1014  1125 E WifiNative-wlan0: do suspend true
09-09 13:41:27.301  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:41:27.301  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-09 13:41:27.301  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:27.301  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:27.301  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 13:41:27.301  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:27.301  1014  1044 D WifiDisplayController: disconnect
09-09 13:41:27.301  1014  1044 D WifiDisplayController: updateConnection
09-09 13:41:27.301  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:27.301  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-09 13:41:27.301  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:27.301  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:41:27.301  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-09 13:41:27.301  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:41:27.301  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:27.301  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:27.301  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:27.311  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:41:27.311  1014  1535 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:27.311  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:41:27.321   277   992 D EnterpriseController: uids 1000
,09-09 13:41:27.321   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:27.321  1014  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 13:41:27.321   277   992 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-09 13:41:27.321  1014  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502],
,09-09 13:41:27.321  1014  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 13:41:27.321  1014  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:27.321  1014  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-09 13:41:27.321  1014  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 13:41:27.321  1014  2219 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:27.321  1014  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-09 13:41:27.321  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:27.321  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:27.321  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:27.321  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:27.321  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:27.321  1453  1453 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:27.321  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:41:27.321  1014  3126 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-09 13:41:27.321  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:27.321  1014  3126 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:27.321  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:41:27.331  1014  3126 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:41:27.331  1014  3126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.331  1014  3126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.331  1014  3126 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.341  6312  6312 E Zygote  : MountEmulatedStorage(),
,09-09 13:41:27.341  6312  6312 E Zygote  : v2
09-09 13:41:27.341  6312  6312 I libpersona: KNOX_SDCARD checking this for 10104
,09-09 13:41:27.341  6312  6312 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:27.341  6312  6312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:41:27.341  1014  3126 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6312 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 13:41:27.351   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:27.351  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
09-09 13:41:27.351  1014  1132 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:27.351  1014  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 13:41:27.351  1014  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow(),
09-09 13:41:27.351  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:27.351  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:27.351  1014  1122 V NetworkStats: updateIfacesLocked()
09-09 13:41:27.351  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:27.351  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:27.351  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.351  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:27.351  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:27.351  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.351  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.351  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.351  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.351  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:27.351  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:27.351  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:41:27.351  6312  6312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:41:27.351  1014  1122 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:27.351  6312  6312 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-09 13:41:27.351  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.361  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:41:27.361  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:27.361  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:27.361  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:41:27.361  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:41:27.361  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:41:27.361  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:41:27.361  2102  2102 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-09 13:41:27.361  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.361  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.361  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.371  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:27.371  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:27.371  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:27.371  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:27.371  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:27.371  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:27.371  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:27.381  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.381  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:27.381  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:27.381  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:27.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.381  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:27.381  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 13:41:27.381  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:41:27.381  6312  6312 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-09 13:41:27.381  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:27.381  6312  6312 D ActivityThread: Added TimaKeyStore provider
09-09 13:41:27.381  1294  1294 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:27.381  1173  1173 D HotspotTile: onReceive : 0, 0
,09-09 13:41:27.391  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:27.391  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:27.391  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:27.391  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:27.391  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:27.391  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:27.391  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:27.391  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:27.391  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:27.401  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 13:41:27.401  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:27.401  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:27.401  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:27.401  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:27.401  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:27.401  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:27.401  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:27.401  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:27.411  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:27.411  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:27.411  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:27.411  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:27.411  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:27.411  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:27.411  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:27.411  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:27.411  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:27.421  6312  6312 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 13:41:27.451  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.451  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.451  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.451  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.451  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.461  6146  6146 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:27.461  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.461  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.461  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:41:27.461  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.461  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.461  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.461  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.461  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.461  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.471  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.471  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.471  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.471  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.471  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.471  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.471  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.481  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.481  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.481  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.481  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.481  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.481  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.481  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.481  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:27.481  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:27.491  2102  2102 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:27.521  2102  2102 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 13:41:27.521  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:41:27.521  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:27.521  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:27.541  2102  2102 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-09 13:41:27.541  2102  2102 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 13:41:27.541  2102  2102 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 13:41:27.541  2102  2102 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 13:41:27.541  2102  2102 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:41:27.551  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:41:27.551  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.551  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:27.551  1014  1132 D Tethering: InitialState.processMessage what=4
09-09 13:41:27.551  1014  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-09 13:41:27.551  1014  1132 E Tethering: No numeric data
09-09 13:41:27.551  1014  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:41:27.551  1014  1132 D Tethering: clearTetheredNotification()
09-09 13:41:27.551  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.551  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.551  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:27.551  1014  1214 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 13:41:27.551  1014  1214 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:41:27.551  1014  1214 D SecContentProvider2: mCursor = null
,09-09 13:41:27.551  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.551  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.551  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:27.551  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:27.551  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.551  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.551  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.551  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:27.551  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:27.551  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:41:27.561  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:27.561  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:27.561  1014  1214 D WifiService: setWifiEnabled: true pid=6146, uid=10155
09-09 13:41:27.561  1014  1214 W ActivityManager: Permission Denial: getCurrentUser() from pid=6146, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:27.561  1014  1214 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:41:27.561  1014  1214 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6146, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:27.561  1014  1214 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 13:41:27.561  1014  1214 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 13:41:27.561  1014  1214 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 13:41:27.561  1014  1214 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 13:41:27.561  1014  1214 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 13:41:27.561  1014  1214 D SettingsProvider: name = wifi_on
09-09 13:41:27.561  1014  1122 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:27.561  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.561  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:27.561  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:27.601   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84957c8
09-09 13:41:27.601   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-09 13:41:27.601   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-09 13:41:27.601   272   308 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203153608)
,09-09 13:41:27.621  6312  6352 I Babel   : MmsConfig: mnc/mcc: 0/0,
09-09 13:41:27.621  6312  6352 I Babel   : MmsConfig.loadMmsSettings
09-09 13:41:27.621  6312  6352 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-09 13:41:27.621  6312  6352 I Babel   : MmsConfig.loadFromDatabase
,09-09 13:41:27.631  6312  6352 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-09 13:41:27.631  6312  6352 I Babel   : MmsConfig.loadFromResources
,09-09 13:41:27.631  6312  6352 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 13:41:27.631  6312  6352 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-09 13:41:27.641   272   308 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-09 13:41:27.641   272   308 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,09-09 13:41:27.641   272   308 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203153608) wakelock released: 1, error no: 0
09-09 13:41:27.641   272   308 I rmt_storage: 
,09-09 13:41:27.641   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb84957c8
,09-09 13:41:27.651  1014  1214 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-09 13:41:27.651  1014  1214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-09 13:41:27.651  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:27.651  1014  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:27.651  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:41:27.661  6312  6312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:27.701  6312  6312 I Babel_StickerModule: App launched.
,09-09 13:41:27.701  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:27.701  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:27.701  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:27.711  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:41:27.711  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:27.711  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:41:27.711  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:27.711  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-09 13:41:27.711  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.711  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.711  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.711  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.721  6354  6354 E Zygote  : MountEmulatedStorage()
09-09 13:41:27.721  6354  6354 E Zygote  : v2
09-09 13:41:27.721  6354  6354 I libpersona: KNOX_SDCARD checking this for 10068
09-09 13:41:27.721  6354  6354 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:27.731  6354  6354 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:41:27.731  6354  6354 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:27.731  6354  6354 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:27.741   282   699 W QCamera2Factory: getCameraInfo: E, camera_id = 0
09-09 13:41:27.741   282   699 W QCamera2Factory: getCameraInfo: X
,09-09 13:41:27.741  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6354 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:27.761  6354  6354 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:27.761  6354  6354 D ActivityThread: Added TimaKeyStore provider
09-09 13:41:27.761   282   673 W QCamera2Factory: getCameraInfo: E, camera_id = 1
09-09 13:41:27.761   282   673 W QCamera2Factory: getCameraInfo: X
,09-09 13:41:27.771  2102  2102 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:27.771  6354  6354 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:41:27.781  6312  6312 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 13:41:27.781  6354  6354 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:27.791  6312  6312 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:41:27.791  6354  6354 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:41:27.791  6312  6312 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:41:27.791  6312  6312 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-09 13:41:27.791  6312  6312 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-09 13:41:27.801  6312  6312 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 13:41:27.801  6312  6312 W AudioCapabilities: Unsupported mime audio/x-ima
,09-09 13:41:27.801  6312  6312 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 13:41:27.801  6312  6312 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 13:41:27.811  6312  6312 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 13:41:27.811  6312  6312 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 13:41:27.821  6312  6312 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-09 13:41:27.821  6312  6312 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 13:41:27.821  6312  6312 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 13:41:27.821  6312  6312 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-09 13:41:27.821  2102  2102 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 13:41:27.831  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.831  6312  6312 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
09-09 13:41:27.831  6354  6354 D FileShare-Client: Outbound.stopDelayTimer - 
09-09 13:41:27.831  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:27.831  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:27.831  6312  6312 W VideoCapabilities: Unsupported mime video/mp43
09-09 13:41:27.831  1014  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 13:41:27.831  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.831  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.831  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:27.831  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:27.831  6312  6312 W VideoCapabilities: Unsupported mime video/sorenson,
,09-09 13:41:27.841  6312  6312 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 13:41:27.851  6369  6369 E Zygote  : MountEmulatedStorage()
,09-09 13:41:27.851  6369  6369 E Zygote  : v2
09-09 13:41:27.851  6369  6369 I libpersona: KNOX_SDCARD checking this for 10069
09-09 13:41:27.851  6369  6369 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:27.851  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:27.851  6369  6369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:41:27.851  1014  1483 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6369 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-09 13:41:27.851  1014  1483 I ActivityManager: Killing 5695:com.google.android.gms:car/u0a12 (adj 15): empty #31
,09-09 13:41:27.861  6369  6369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:27.861  6369  6369 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:27.861  1014  1014 I ApplicationPolicy: updateDataUsageMap
,09-09 13:41:27.871  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.891  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.891  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.901  6312  6312 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 13:41:27.901  6369  6369 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:27.901  6369  6369 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:27.901  3144  3144 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-09 13:41:27.911  3144  3144 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-09 13:41:27.931  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:27.931  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 13:41:27.931  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:41:27.931  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 13:41:27.941  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:27.941  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-09 13:41:27.941  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:27.941  1946  2129 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:27.941  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.941  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.941  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:27.941  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:27.941  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 13:41:27.941  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:27.941  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:27.941  1173  1173 D HotspotTile: onReceive : 1, 0
,09-09 13:41:27.951  1294  1294 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:27.951  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.951  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.951  6369  6369 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:27.951  1014  1535 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
09-09 13:41:27.951  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-09 13:41:27.951  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:27.951  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:27.951  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 13:41:27.951  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:27.961  1014  1027 I ActivityManager: Killing 4988:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,09-09 13:41:27.961  1014  3126 I ActivityManager: Killing 5419:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-09 13:41:27.971  1014  1326 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:27.971  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:27.971  6312  6312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:27.971  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:27.971  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:27.971  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:27.971  3632  3632 I Hs20UtilService: Starting #9
,09-09 13:41:27.971  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:27.971  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:27.971  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:27.971  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:27.971  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:41:27.971  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 13:41:27.981  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:41:27.981  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:27.981  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:27.981  1014  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:27.981  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.331  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:28.331  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:28.331  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:28.331  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.331  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:28.331  3632  3632 I Hs20UtilService: Starting #10
,09-09 13:41:28.331  1014  1326 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-09 13:41:28.331  3632  3664 I Hs20UtilService: Message received 5011
09-09 13:41:28.331  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.331  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.331  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.331  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.341  6385  6385 E Zygote  : MountEmulatedStorage(),
09-09 13:41:28.341  6385  6385 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:28.341  6385  6385 E Zygote  : v2
09-09 13:41:28.341  6385  6385 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.341  6385  6385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-09 13:41:28.341  1014  1326 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6385 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 13:41:28.351  6385  6385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:41:28.351  6385  6385 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.371  6385  6385 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.371  6385  6385 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.411  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:28.411  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:28.411  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:28.411  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:28.411  1014  1137 I ActivityManager: Killing 5672:com.samsung.android.sm/1000 (adj 15): empty #31
,09-09 13:41:28.421  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.421  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.421  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.431  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.431  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.431  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.431  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.431  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.431  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.431  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.431  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.431  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.441  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.441  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.441  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.441  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.441  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.441  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.441  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.441  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.441  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.451  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.451  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.451  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.451  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.451  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.451  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.451  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.451  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.451  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.461  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.461  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.461  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.461  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:28.461  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.461  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.461  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:28.461  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.461  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.471  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:28.471  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:28.471  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:28.471  5792  5792 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:41:28.481  5792  5792 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:41:28.481  5792  5792 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:41:28.481  5792  5792 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:28.481  1014  1539 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-09 13:41:28.481  1014  1539 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:41:28.481  1014  1539 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-09 13:41:28.481  5792  6401 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 13:41:28.481  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.481  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.481  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.481  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.491  6403  6403 E Zygote  : MountEmulatedStorage(),
09-09 13:41:28.491  6403  6403 E Zygote  : v2
09-09 13:41:28.491  6403  6403 I libpersona: KNOX_SDCARD checking this for 10111
09-09 13:41:28.491  6403  6403 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.491  1014  1539 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6403 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:28.501  6403  6403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:41:28.501  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-09 13:41:28.501  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.501  6403  6403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:41:28.501  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.501  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.501  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.501  1014  1041 D Tethering: interfaceRemoved wlan0
09-09 13:41:28.501  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 13:41:28.501  6403  6403 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.521  6417  6417 E Zygote  : MountEmulatedStorage()
09-09 13:41:28.521  6417  6417 E Zygote  : v2
09-09 13:41:28.521  6417  6417 I libpersona: KNOX_SDCARD checking this for 10009
09-09 13:41:28.521  6417  6417 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.521  6417  6417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:41:28.521  6417  6417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-09 13:41:28.521  6403  6403 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.521  6417  6417 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-09 13:41:28.521  6403  6403 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.521  1014  1039 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6417 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:28.531  1727  1727 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:28.541  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-09 13:41:28.541  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.541  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.541  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.541  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.551  6417  6417 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.551  6417  6417 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.551  6433  6433 E Zygote  : MountEmulatedStorage()
,09-09 13:41:28.551  6433  6433 E Zygote  : v2
09-09 13:41:28.551  6433  6433 I libpersona: KNOX_SDCARD checking this for 10145
09-09 13:41:28.551  6433  6433 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:28.551  6433  6433 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:41:28.561  6433  6433 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-09 13:41:28.561  1014  1039 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6433 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-09 13:41:28.561  6433  6433 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.571  1727  1727 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-09 13:41:28.571  1727  1727 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-09 13:41:28.571  1727  1727 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-09 13:41:28.571  1727  1727 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:28.571  1727  1727 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:28.581  1727  1727 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-09 13:41:28.581  1312  1589 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,09-09 13:41:28.581  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-09 13:41:28.581  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.581  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.581  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.581  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.591  6447  6447 E Zygote  : MountEmulatedStorage(),
09-09 13:41:28.591  6447  6447 I libpersona: KNOX_SDCARD checking this for 10081
09-09 13:41:28.591  6447  6447 E Zygote  : v2
09-09 13:41:28.591  6447  6447 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:28.601  6447  6447 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:41:28.601  1014  1026 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6447 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:28.601  6447  6447 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:41:28.601  6447  6447 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.611  6433  6433 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.611  6433  6433 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.611  1727  1727 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-09 13:41:28.621  6447  6447 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.621  6447  6447 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.631  1014  1041 D Tethering: interfaceRemoved p2p0
09-09 13:41:28.631  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 13:41:28.641  6433  6433 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 13:41:28.641  6433  6433 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:41:28.641  6433  6433 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:41:28.641  6433  6433 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:41:28.641  6433  6433 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:41:28.651  1014  1026 I ActivityManager: Killing 5510:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-09 13:41:28.651  6403  6403 I MusicStore: Database version: 108
,09-09 13:41:28.661  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:41:28 GMT+02:00 2016
,09-09 13:41:28.661  1014  3126 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:41:28.661  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:28.661  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:28.661  1014  3126 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:28.661  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:41:28.671   290   290 E SMD     : DCD OFF
,09-09 13:41:28.671  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:41:28.681  1014  3124 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-09 13:41:28.681  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.681  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.681  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.681  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.681  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 13:41:28.691  3666  3666 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:41:28.691  3666  3666 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:41:28.691  3666  6468 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:41:28.691  6470  6470 E Zygote  : MountEmulatedStorage()
09-09 13:41:28.691  6470  6470 E Zygote  : v2
09-09 13:41:28.691  6470  6470 I libpersona: KNOX_SDCARD checking this for 10034
09-09 13:41:28.691  6470  6470 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.691  3666  6468 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-09 13:41:28.691  6470  6470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:41:28.701  3666  6468 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 13:41:28.701  6470  6470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:28.701  6470  6470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.701  3666  6468 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-09 13:41:28.701  1014  3124 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6470 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-09 13:41:28.711  1014  3126 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:41:28.711  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
09-09 13:41:28.711  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:28.711  1014  3126 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:28.711  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:28.711  1014  1483 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:28.711  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-09 13:41:28.721  6470  6470 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:28.721  6470  6470 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:28.731  1014  3126 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:28.751  1014  1539 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 13:41:28.751  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.751  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.751  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.751  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.761  6489  6489 E Zygote  : MountEmulatedStorage(),
09-09 13:41:28.771  6489  6489 E Zygote  : v2
,09-09 13:41:28.771  6489  6489 I libpersona: KNOX_SDCARD checking this for 10113
09-09 13:41:28.771  6489  6489 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:28.771  6489  6489 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:41:28.771  1014  1539 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6489 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-09 13:41:28.771  1014  1539 I ActivityManager: Killing 5053:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-09 13:41:28.771  6489  6489 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:28.771  6489  6489 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:41:28.781  1014  1535 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:28.801  6489  6489 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:41:28.801  6489  6489 D ActivityThread: Added TimaKeyStore provider
09-09 13:41:28.801  6470  6470 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-09 13:41:28.811  1014  3125 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:28.841  3205  6509 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 13:41:28.841  3205  6509 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
09-09 13:41:28.841  6403  6403 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 13:41:28.841  6403  6403 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 13:41:28.851  3205  6509 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-09 13:41:28.851  5840  5840 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 13:41:28.851  6042  6042 I SA      : [DM] init START
,09-09 13:41:28.861  6042  6042 I SA      : [DM] This device is not a Vodafone
,09-09 13:41:28.861  1014  1137 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 13:41:28.861  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:41:28.861  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:28.861  1014  1137 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:28.861  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:41:28.871  3205  6509 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-09 13:41:28.871  3205  6509 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:41:28.871  6042  6042 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-09 13:41:28.871  6042  6042 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-09 13:41:28.871  6042  6042 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-09 13:41:28.871  6042  6042 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
09-09 13:41:28.871  6042  6042 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,09-09 13:41:28.881  6042  6042 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,09-09 13:41:28.881  6042  6042 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-09 13:41:28.881  1014  1137 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:28.891  6042  6042 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-09 13:41:28.891  5840  6512 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-09 13:41:28.891  5957  5966 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,09-09 13:41:28.891  6042  6042 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-09 13:41:28.911  6403  6403 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 13:41:28.911  1014  1214 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:28.911  5957  5966 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-09 13:41:28.911  5957  5966 D BadgeProvider: sendNotify, [notify] : null
,09-09 13:41:28.921  5957  5966 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,09-09 13:41:28.921  5957  5966 D BadgeProvider: update, [BadgeCount] : badgecount=0
,09-09 13:41:28.921  5957  5966 D BadgeProvider: update, [UpdateCount] : 1
09-09 13:41:28.921  1474  1474 D Launcher.Model: reloadBadges entered.
,09-09 13:41:28.921  6042  6042 I SA      : [SCU] isHaveSA() - false
09-09 13:41:28.921  6042  6042 I SA      : support phone number id : false
09-09 13:41:28.921  6042  6042 I SA      : [DM] Supports Ref Jpn : true
,09-09 13:41:28.921  6042  6042 I SA      : [DM] init END
09-09 13:41:28.921  6042  6042 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-09 13:41:28.921  6042  6042 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 13:41:28.921  6042  6042 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:28.931  6042  6042 I SA      : [SLFUCHKMGR] constructor called
,09-09 13:41:28.941  6042  6042 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:41:28.941  6042  6042 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:41:28.951  6042  6042 I SA      : [SCU] == networkStateCheck == false
,09-09 13:41:28.951  6042  6042 I SA      : [OR] onReceive END
,09-09 13:41:28.951  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:28.961  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:28.961  6403  6403 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 13:41:28.961  6403  6403 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c251cbc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 13:41:28.971  6403  6403 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 13:41:28.971  6403  6403 D AndroidMusic: GMSCore installation verified
,09-09 13:41:28.971  1014  1137 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:28.981  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:28.981  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:28.981  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:28.981  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:28.981  1014  1342 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-09 13:41:28.981  1014  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.981  1014  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:28.981  1014  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:28.981  1014  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.001  6520  6520 E Zygote  : MountEmulatedStorage()
09-09 13:41:29.001  1014  1342 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6520 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:41:29.001  6520  6520 E Zygote  : v2
09-09 13:41:29.001  6520  6520 I libpersona: KNOX_SDCARD checking this for 10159
09-09 13:41:29.001  6520  6520 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:41:29.001  6520  6520 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:29.001  1014  1342 I ActivityManager: Killing 5809:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
09-09 13:41:29.001  1014  1214 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:41:29.001  1014  1214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
09-09 13:41:29.001  6520  6520 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:41:29.001  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.001  1014  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.001  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-09 13:41:29.001  6520  6520 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-09 13:41:29.021  6403  6403 I ConfigStore: Config Database version: 1
,09-09 13:41:29.031   306   306 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 34.539ms
,09-09 13:41:29.051   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.324ms
,09-09 13:41:29.061  6520  6520 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-09 13:41:29.061  6520  6520 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:29.071   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 18.343ms,
,09-09 13:41:29.101  1014  1342 I ActivityManager: Killing 5822:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-09 13:41:29.101  1014  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:29.101  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.111  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.111  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.111  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:29.121  3798  3798 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:41:29.121  3798  4542 I iu.UploadsManager: num queued entries: 0
,09-09 13:41:29.121  3798  4542 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:29.121  3798  4542 I iu.SyncManager: NEXT; no task
,09-09 13:41:29.151   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 13:41:29.151   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:29.151  6403  6403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 13:41:29.151   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 13:41:29.151   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:29.151  6403  6403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 13:41:29.161   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 13:41:29.161   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:29.161  6403  6403 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 13:41:29.171  1014  1541 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-09 13:41:29.171  1014  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.171  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.171  1014  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.171  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-09 13:41:29.171   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:29.171   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:29.171  6489  6537 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 13:41:29.181   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:29.181   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:29.181  6489  6537 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 13:41:29.201   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 13:41:29.201   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:29.201  6489  6542 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 13:41:29.201   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 13:41:29.201   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:41:29.201  6489  6542 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 13:41:29.291  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:41:29.291  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:41:29.331  1014  1541 I art     : Explicit concurrent mark sweep GC freed 55494(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.638ms total 158.942ms
,09-09 13:41:29.331  1014  1214 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:41:29.331  1014  1214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-09 13:41:29.331  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.331  1014  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:29.331  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:29.361  1014  3124 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:29.371  1014  3125 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:29.371  1014  1535 I AudioService: getStreamVolume 3 index 0
,09-09 13:41:29.381  6403  6403 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 13:41:29.381  6403  6403 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 13:41:29.411  1014  1214 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-09 13:41:29.411  1014  1214 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-09 13:41:29.411  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.411  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.421  1014  1342 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:41:29.421  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:41:29.421  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.421  1014  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.421  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:29.421  1014  1326 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:41:29.421  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.421  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.421  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.421  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:29.431  1014  1541 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:41:29.431  1014  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.431  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:29.431  1014  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.431  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:29.441  1014  3126 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:29.451  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 13:41:29.451  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.451  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.451  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.451  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.461  6555  6555 E Zygote  : MountEmulatedStorage(),
09-09 13:41:29.471  6555  6555 E Zygote  : v2
09-09 13:41:29.471  6555  6555 I libpersona: KNOX_SDCARD checking this for 10002
09-09 13:41:29.471  6555  6555 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:29.471  6555  6555 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:41:29.471  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6555 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:29.471  6555  6555 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:29.481  6555  6555 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:29.511  6555  6555 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:29.511  6555  6555 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:29.511  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
09-09 13:41:29.511  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-09 13:41:29.511  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:41:29.511  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.511  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-09 13:41:29.521  6403  6403 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-09 13:41:29.521  1014  1541 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:41:29.521  1014  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:41:29.521  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.521  1014  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.521  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:29.531  1014  1535 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:29.531  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:29.531  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:29.531  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 13:41:29.551  6489  6489 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-09 13:41:29.561  6489  6489 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1776-1777)
,09-09 13:41:29.561  6489  6489 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:41:29.571  6489  6489 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d8426fd}
,09-09 13:41:29.571  6489  6489 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 13:41:29.571  1014  3125 I ActivityManager: Killing 5443:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-09 13:41:29.571  6489  6489 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 13:41:29.581  1014  1535 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-09 13:41:29.581  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.581  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.581  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.581  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.591  6586  6586 E Zygote  : MountEmulatedStorage()
09-09 13:41:29.591  1014  1535 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6586 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-09 13:41:29.591  6586  6586 E Zygote  : v2
09-09 13:41:29.591  6586  6586 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:29.591  6586  6586 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:41:29.591  6586  6586 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:29.601  6489  6489 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 13:41:29.601  6489  6489 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 13:41:29.601  6489  6489 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 13:41:29.601  6586  6586 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:29.601  6586  6586 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:41:29.621  6586  6586 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:29.621  6586  6586 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:29.631  6489  6489 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-09 13:41:29.631  6489  6489 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,09-09 13:41:29.641  6489  6489 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-09 13:41:29.641  6489  6489 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 13:41:29.641  6489  6489 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 13:41:29.641  6489  6489 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 13:41:29.641  6489  6489 I Adreno-EGL: Local Branch: 
09-09 13:41:29.641  6489  6489 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 13:41:29.641  6489  6489 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 13:41:29.641  6489  6489 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 13:41:29.661  6586  6586 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 13:41:29.671  1014  1041 D Tethering: interfaceAdded wlan0
,09-09 13:41:29.681  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-09 13:41:29.681  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:29.681  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:29.681  1014  1132 E Tethering: No numeric data
09-09 13:41:29.681  1014  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:29.681  1014  1132 D Tethering: clearTetheredNotification()
,09-09 13:41:29.681  1014  1132 D Tethering: InitialState.processMessage what=4,
,09-09 13:41:29.681  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:29.681  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:29.681  1014  1132 E Tethering: No numeric data
,09-09 13:41:29.681  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:29.681  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:29.691  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:29.691  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:41:29.691  1014  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:29.691  1014  1132 D Tethering: clearTetheredNotification()
,09-09 13:41:29.691  1014  1041 D Tethering: interfaceAdded p2p0
09-09 13:41:29.691  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 13:41:29.701  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-09 13:41:29.701  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:29.701  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:29.701   277   996 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 13:41:29.701  1014  1122 V NetworkStats: performPollLocked() took 14ms
,09-09 13:41:29.701   277   996 D SoftapController: Softap fwReload - Ok
,09-09 13:41:29.701  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:29.701   277   996 D CommandListener: Setting iface cfg
09-09 13:41:29.701   277   996 D CommandListener: Trying to bring down wlan0
,09-09 13:41:29.701  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:29.711   277   996 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:29.711  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 13:41:29.711  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:29.711  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:29.711  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:29.711  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:29.711  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:29.711  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:29.711  1014  1122 V NetworkStats: performPollLocked() took 4ms
09-09 13:41:29.711  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:29.711  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
09-09 13:41:29.711  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:29.711  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:29.741  6489  6613 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 13:41:29.741  6489  6489 I NSApplication: Starting up...
,09-09 13:41:29.751  6616  6616 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 13:41:29.751  6616  6616 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 13:41:29.751  6616  6616 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:41:29.761  1014  3126 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-09 13:41:29.761  1014  3126 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:41:29.761  1014  3126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.761  1014  3126 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:29.761  1014  3126 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:29.771  6616  6616 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-09 13:41:29.771   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6616,
09-09 13:41:29.771   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 13:41:29.771  6616  6616 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:41:29.771  6616  6616 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:29.771  6616  6616 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
09-09 13:41:29.771  6616  6616 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 13:41:29.771   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6616
09-09 13:41:29.771   378   378 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-09 13:41:29.781  6620  6620 E Zygote  : MountEmulatedStorage()
,09-09 13:41:29.781  6620  6620 E Zygote  : v2
09-09 13:41:29.781  6620  6620 I libpersona: KNOX_SDCARD checking this for 10120
09-09 13:41:29.781  6620  6620 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:29.781  1014  3126 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6620 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 13:41:29.781  6620  6620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:41:29.781  6620  6620 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:41:29.781  1014  3126 I ActivityManager: Killing 5773:com.android.mms/u0a46 (adj 15): empty #31
09-09 13:41:29.781  1014  3126 I ActivityManager: Killing 5872:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #32
09-09 13:41:29.781  1014  3126 I ActivityManager: Killing 5477:com.sec.knox.bridge/1000 (adj 15): empty #33
,09-09 13:41:29.791  6620  6620 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 13:41:29.811  6586  6586 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-09 13:41:29.811  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:41:29.821  6620  6620 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:29.821  6620  6620 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:29.821  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:29.821  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
,09-09 13:41:29.821  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:29.821  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:29.821  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:29.821  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:29.821  1173  1173 D HotspotTile: onReceive : 2, 0
09-09 13:41:29.821  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:29.821  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:29.821  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:29.821  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 13:41:29.821  6586  6586 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
09-09 13:41:29.821  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:29.831  1294  1294 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:29.831  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:29.831  6586  6586 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 13:41:29.831  6586  6586 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:41:29.841  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.841  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.841  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:29.841  1014  1214 I ActivityManager: Killing 5977:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-09 13:41:29.861  6620  6620 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:29.881  1014  1535 D CountryDetector: No listener is left
,09-09 13:41:29.971   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-09 13:41:29.981  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-09 13:41:30.051  6616  6616 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 13:41:30.051  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:41:30.061  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-09 13:41:30.061   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6616
09-09 13:41:30.061   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 13:41:30.061  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:41:30.061  6616  6616 I wpa_supplicant: ssSupport state is = 1
,09-09 13:41:30.061  6616  6616 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:30.061  6616  6616 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:30.061  6616  6616 E wpa_supplicant: SIM READ ERROR,
09-09 13:41:30.061  6616  6616 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:30.061  6616  6616 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:30.061  6616  6616 E wpa_supplicant: SIM READ ERROR
09-09 13:41:30.061  6616  6616 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:30.071  6616  6616 I wpa_supplicant: wpa_default_ap_write_once,
09-09 13:41:30.071  6616  6616 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:41:30.071  6616  6616 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-09 13:41:30.071  6616  6616 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 13:41:30.071  6616  6616 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:30.071  6616  6616 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 13:41:30.071  6616  6616 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-09 13:41:30.071  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.071  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:30.071  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:30.141  6616  6616 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-09 13:41:30.151  1014  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 13:41:30.151  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:30.151  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:30.151  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:30.151  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:30.161  6642  6642 E Zygote  : MountEmulatedStorage()
,09-09 13:41:30.161  6642  6642 E Zygote  : v2
09-09 13:41:30.161  6642  6642 I libpersona: KNOX_SDCARD checking this for 10125
09-09 13:41:30.161  6642  6642 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:30.161  6642  6642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 13:41:30.171  1014  1539 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6642 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,09-09 13:41:30.171  1014  1539 I ActivityManager: Killing 5992:com.wsomacp/u0a25 (adj 15): empty #31,
,09-09 13:41:30.171  6642  6642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:30.171  6642  6642 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:30.191  6642  6642 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:30.201  6642  6642 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:30.211  6642  6642 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:41:30.211  6642  6642 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:41:30.211  6642  6642 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:41:30.221  6642  6642 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:30.231  6642  6642 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 13:41:30.231  6642  6642 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:41:30.231  1014  3124 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 13:41:30.231  1014  3124 I ActivityManager: Killing 6015:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-09 13:41:30.241  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:30.241  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:30.241  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:30.241  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.241  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:30.241  3632  3632 I Hs20UtilService: Starting #11
,09-09 13:41:30.241  3632  3664 I Hs20UtilService: Message received 5011
,09-09 13:41:30.251  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:30.251  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:30.251  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:30.251  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:30.261  1014  1342 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:30.261  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:30.261  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:30.261  1014  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.261  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:30.261  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:30.261  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:30.261  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:30.261  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:30.271  3632  3632 I Hs20UtilService: Starting #12
,09-09 13:41:30.271  3632  3664 I Hs20UtilService: Message received 5011
,09-09 13:41:30.421  6616  6616 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-09 13:41:30.421  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:41:30.431  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-09 13:41:30.431   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6616
09-09 13:41:30.431   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 13:41:30.431  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:41:30.431  6616  6616 I wpa_supplicant: ssSupport state is = 1
,09-09 13:41:30.431  6616  6616 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 13:41:30.431  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 13:41:30.451  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-09 13:41:30.451   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6616
09-09 13:41:30.451   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,09-09 13:41:30.451  6616  6616 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 13:41:30.451  6616  6616 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:30.451  6616  6616 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:30.451  6616  6616 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:30.451  6616  6616 E wpa_supplicant: SIM READ ERROR
,09-09 13:41:30.451  6616  6616 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:41:30.451  6616  6616 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:41:30.451  6616  6616 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:41:30.451  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:30.451  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:30.451  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:30.451  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 13:41:30.451  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:30.451  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:30.511  6616  6616 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 13:41:30.511  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 13:41:30.551  6616  6616 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 13:41:30.551  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 13:41:30.551  6616  6616 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 13:41:30.561  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-09 13:41:30.561  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:41:30.561  6616  6616 I wpa_supplicant: HOTSPOT20_ENABLE called
09-09 13:41:30.561  6616  6616 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 13:41:30.561  6616  6616 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:30.561  6616  6616 E wpa_supplicant: SIM READ ERROR
,09-09 13:41:30.561  6616  6616 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:30.591  6616  6616 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 13:41:30.601  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-09 13:41:30.601  6616  6616 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 13:41:30.601  1014  1125 D WifiConfigStore: Loading config and enabling all networks ,
09-09 13:41:30.601  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,09-09 13:41:30.601  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:30.601  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:30.601  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-09 13:41:30.611  1173  1173 D HotspotTile: onReceive : 3, 0,
,09-09 13:41:30.601  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:30.601  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:30.601  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:41:30.601  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:30.601  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:30.601  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3),
09-09 13:41:30.611  1294  1294 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:30.621  1014  1125 E WifiConfigStore: Not a HS20
,09-09 13:41:30.621  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:41:30.621  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:30.621  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.621  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.621  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.621  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.621  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.621  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.621  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:30.621  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:41:30.621  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.621  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 13:41:30.621  6616  6616 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:41:30.621  6616  6616 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:41:30.631  6616  6616 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:30.631  1014  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:30.631  6616  6616 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:30.631  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:30.631  6616  6616 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 13:41:30.631  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 13:41:30.631  6616  6616 I wpa_supplicant: First Scan Start
,09-09 13:41:30.631  6616  6616 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:30.631  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:30.631  1014  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:30.631  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:30.631  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:30.631  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.631  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.631  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.631  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.631  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.631  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.631  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:30.631  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.631  3632  3632 I Hs20UtilService: Starting #13
,09-09 13:41:30.641  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:41:30.641  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:30.641  1014  1125 I WifiNative-HAL: startHal
09-09 13:41:30.641  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9c71588c
09-09 13:41:30.641  1014  1125 I WifiNative-HAL: Could not start hal
,09-09 13:41:30.641  3632  3664 I Hs20UtilService: Message received 5011
09-09 13:41:30.641  6312  6312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:30.641  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:30.641  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:30.641  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:30.641  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:30.641  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 13:41:30.641  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 13:41:30.651  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:30.651  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:30.651  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:30.651  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:30.651  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:30.651  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:30.651  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:30.651  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:30.651   277   996 D CommandListener: Setting iface cfg
09-09 13:41:30.651   277   996 D CommandListener: Trying to bring up p2p0
,09-09 13:41:30.651  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 13:41:30.651  1014  1124 D WifiP2pService: P2pEnablingState
,09-09 13:41:30.651  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:41:30.651  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 13:41:30.651  1014  1124 D WifiP2pService: P2p socket connection successful
,09-09 13:41:30.651  1014  1124 D WifiP2pService: P2pEnabledState
,09-09 13:41:30.651  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 13:41:30.651  1014  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:30.651  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:41:30.651  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:41:30.651  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-09 13:41:30.651  1014  1148 I WifiNative-HAL: startHal
09-09 13:41:30.651  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9d8c79bc
09-09 13:41:30.651  1014  1148 I WifiNative-HAL: Could not start hal
09-09 13:41:30.651  1014  1148 E WifiScanningService: could not start HAL
,09-09 13:41:30.661  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:30.661  1014  1014 D RttService: SCAN_AVAILABLE : 3,
09-09 13:41:30.661  6616  6616 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:41:30.661  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
09-09 13:41:30.661  1014  1131 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:30.661  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 13:41:30.661  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 13:41:30.661  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:30.661  6616  6616 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 13:41:30.661  1014  1044 D WifiDisplayController: disconnect
09-09 13:41:30.661  1014  1149 D RttService: DefaultState got{ when=-4ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:30.661  1014  1044 D WifiDisplayController: updateConnection
09-09 13:41:30.661  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:30.661  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:30.661  6616  6616 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-09 13:41:30.661  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:30.661  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:30.661  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:30.661  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:30.671  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:41:30.671  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,09-09 13:41:30.671  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-09 13:41:30.671  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:30.671  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:30.671  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-09 13:41:30.671  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:41:30.671  1014  1342 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:41:30.671  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-09 13:41:30.671  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:41:30.671  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:30.671  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:30.671  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:30.671  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:30.671  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:30.671  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:30.671  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 13:41:30.671  1014  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-09 13:41:30.681  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-09 13:41:30.681  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  secondary type: null
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  wps: 0
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  grpcapab: 0
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  devcapab: 0
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  status: 3
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  wfdInfo: null
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  groupownerAddress: null
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  GOdeviceName: null
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  interfaceAddress: 
09-09 13:41:30.681  1014  1044 D WifiDisplayController:  SConnectInfo : null
,09-09 13:41:30.681  1014  1125 D SecContentProvider2: mCursor = null
09-09 13:41:30.681  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:30.681  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:30.681  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:30.681  6354  6354 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:30.681  6354  6354 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 13:41:30.681  6354  6354 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:30.691  6369  6369 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:30.701  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:41:30.701  1014  1124 D WifiP2pService: InactiveState
,09-09 13:41:30.701  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:41:30.701  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:41:30.701  6616  6616 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-09 13:41:30.701  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-09 13:41:30.701  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:41:31.071  6146  6196 D BluetoothAdapter: enable(),
,09-09 13:41:31.081  6146  6196 D BluetoothAdapter: enable(): BT is already enabled..!,
,09-09 13:41:31.681   290   290 E SMD     : DCD OFF,
,09-09 13:41:31.961  6616  6616 I wpa_supplicant: nl80211: Received scan results (8 BSSes),
,09-09 13:41:31.961  6616  6616 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-09 13:41:31.961  6616  6616 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-09 13:41:31.961  1014  6659 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 13:41:31.971  6616  6616 I wpa_supplicant: Trying to associate with  'G700'
,09-09 13:41:31.971  6616  6616 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-09 13:41:31.971  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-09 13:41:31.981  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:31.981  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:32.231  6616  6616 E wpa_supplicant: Cmd 35605 not handled
,09-09 13:41:32.231  6616  6616 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:41:32.231  6616  6616 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-09 13:41:32.231  6616  6616 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 13:41:32.231  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:41:32.231  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:32.231  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:32.231  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 13:41:32.231  6616  6616 I wpa_supplicant: Associated with F4.99.3E
,09-09 13:41:32.231  6616  6616 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:41:32.231  6616  6616 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 13:41:32.231  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:41:32.231  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:32.231  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:41:32.231  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:32.231  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:32.231  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:32.231  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:32.231  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:41:32.231  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:41:32.231  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-09 13:41:32.231  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:32.231  1014  1125 D SecContentProvider2: mCursor = null
09-09 13:41:32.231  1014  1132 E Tethering: No numeric data
09-09 13:41:32.241  1014  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:32.241  1014  1132 D Tethering: clearTetheredNotification()
,09-09 13:41:32.241  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:32.241  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:32.241  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:41:32.241  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:32.241  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:32.241  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:41:32.241  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:32.241  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:32.251  1014  1122 V NetworkStats: performPollLocked() took 8ms
,09-09 13:41:32.251  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:32.251  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:32.251  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:32.331  6616  6616 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:41:32.331  6616  6616 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 13:41:32.331  6616  6616 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 13:41:32.331  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:41:32.331  6616  6616 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:32.331  6616  6616 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-09 13:41:32.331  6616  6616 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 13:41:32.331  6616  6616 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 13:41:32.331  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:41:32.331  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true,
09-09 13:41:32.331  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:41:32.331  1014  1041 D Tethering: interfaceStatusChanged wlan0, true,
,09-09 13:41:32.341  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:41:32.341  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-09 13:41:32.351  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 13:41:32.351  1014  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 13:41:32.351  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:32.351  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:41:32.351  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:41:32.351  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,09-09 13:41:32.351  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:32.351  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:41:32.351  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:32.351  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:32.361  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:32.361  1014  1541 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:32.361  1014  1541 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:32.361  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:32.361  1014  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:32.361  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:32.371  3632  3632 I Hs20UtilService: Starting #14
,09-09 13:41:32.371  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:32.371  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:32.371  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:32.371  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:32.371  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
09-09 13:41:32.371  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 13:41:32.371  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:32.371  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:32.381  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:32.391   277   996 D CommandListener: Setting iface cfg,
,09-09 13:41:32.391  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,09-09 13:41:32.391  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:32.391  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:32.411  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:32.411  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:32.411  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:32.411  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:32.411  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:32.411  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:32.421  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:32.421  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:32.421  1014  1125 E WifiNative-wlan0: do suspend false
,09-09 13:41:32.421  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:41:32.421  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:32.641  6666  6666 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 13:41:32.641  6666  6666 I dhcpcd  : version 5.5.6 starting
,09-09 13:41:32.641  6666  6666 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:41:32.701  6666  6666 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 13:41:32.701  6666  6666 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 13:41:32.701  6666  6666 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-09 13:41:32.701  6666  6666 I dhcpcd  : bssid match
09-09 13:41:32.701  6666  6666 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111,
,09-09 13:41:32.821  6666  6666 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-09 13:41:32.901  6666  6666 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-09 13:41:33.241  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 13:41:33.291  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:41:33.291  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:33.291  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:33.291  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:33.291  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.301  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.301  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.301  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.301  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 13:41:33.301  1014  1125 E WifiStateMachine: VerifyingLinkState enter
,09-09 13:41:33.301  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-09 13:41:33.301  1014  1131 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:33.301  1014  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-09 13:41:33.301  1014  1131 D ConnectivityService: Adding iface wlan0 to network 503
,09-09 13:41:33.311  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-09 13:41:33.321  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:41:33.321  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:41:33.321  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:41:33.321  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:41:33.321  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:33.321  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:33.321  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.321  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.321  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.321  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:33.331  1014  1326 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-09 13:41:33.331  1014  1326 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:41:33.331  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:33.331  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:33.331  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:33.331  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-09 13:41:33.341  1014  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,09-09 13:41:33.341  3632  3632 I Hs20UtilService: Starting #15
,09-09 13:41:33.341  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:33.341  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:33.341  1294  1294 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 13:41:33.341  1014  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-09 13:41:33.341  1014  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,09-09 13:41:33.351  1014  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 13:41:33.351  1014  1131 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,09-09 13:41:33.351  1014  1131 D ConnectivityService: LTETest block dns file not exists
,09-09 13:41:33.351  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 13:41:33.351  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 13:41:33.351  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:41:33.361  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:33.361  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:33.361  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:33.361  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:33.361  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.361  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:33.361  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:41:33.361  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 13:41:33.361  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,09-09 13:41:33.371  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-09 13:41:33.371  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:33.371  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:33.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:33.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:33.381  1014  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:33.381  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:33.381  1014  1131 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:33.381  1014  1342 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:33.381  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:33.381  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:33.381  1014  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-09 13:41:33.381  1014  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:33.381  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:33.381  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 13:41:33.381  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:33.381  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-09 13:41:33.381  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:33.381  1014  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:33.381  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:33.381  1014  6664 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:33.391   277   992 D EnterpriseController: uids 1000
09-09 13:41:33.391   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:33.391   277   992 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,09-09 13:41:33.391  1014  1131 D ConnectivityService:    accepting network in place of null
,09-09 13:41:33.391  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 13:41:33.391  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:33.391  1453  1453 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 13:41:33.391  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-09 13:41:33.401  1014  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,09-09 13:41:33.401  1014  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,09-09 13:41:33.401  3632  3632 I Hs20UtilService: Starting #16
,09-09 13:41:33.401  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 13:41:33.401  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:33.401  1014  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-09 13:41:33.401  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-09 13:41:33.401  1014  1132 D Tethering: MasterInitialState.processMessage what=3
,09-09 13:41:33.401  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:33.401  1014  1122 V NetworkStats: updateIfacesLocked()
09-09 13:41:33.401  1014  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:33.401  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.401  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:33.401  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:33.411  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:33.411  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:33.411  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,09-09 13:41:33.411  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:33.411  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:33.411  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:41:33.411  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:41:33.411  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:41:33.411  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:33.411  1014  1122 V NetworkStats: performPollLocked() took 7ms
09-09 13:41:33.411  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.411  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:33.411  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-09 13:41:33.411  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:33.411  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.411  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:41:33.411  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.411  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.421  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 13:41:33.421  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:41:33.421  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:33.421  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-09 13:41:33.421  1294  1294 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 13:41:33.421  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:41:33.421  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:33.421  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:33.421  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.421  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.421  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.421  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:33.421  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:33.421  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:33.421  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:33.421  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:33.421  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:33.421  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:33.421  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:33.431  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:33.431  1294  1294 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:41:33.431  3632  3632 I Hs20UtilService: Starting #17
,09-09 13:41:33.431  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:33.441  1014  1541 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 13:41:33.441  1014  3125 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,09-09 13:41:33.441  1014  3125 D SecContentProvider2: mCursor = null
,09-09 13:41:33.441  1014  1535 D SecContentProvider2: uri = 15 selection = getToastGravity
,09-09 13:41:33.441  1014  1535 D SecContentProvider2: mCursor = null
,09-09 13:41:33.441  1014  1500 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-09 13:41:33.441  1014  1500 D SecContentProvider2: mCursor = null,
09-09 13:41:33.441  1014  1342 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,09-09 13:41:33.441  1014  1342 D SecContentProvider2: mCursor = null
,09-09 13:41:33.451  1014  1026 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-09 13:41:33.451  1014  1026 D SecContentProvider2: mCursor = null
,09-09 13:41:33.451  1014  1027 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,09-09 13:41:33.451  1014  1027 D SecContentProvider2: mCursor = null
,09-09 13:41:33.481  2657  2804 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-09 13:41:33.481  2657  2804 E bt-btif : DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
09-09 13:41:33.481   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-09 13:41:33.481  2657  2895 W bt-btif : invalid rfc slot id: 7
,09-09 13:41:33.481  6146  6297 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f4200ec, channel: -1, state: INIT
,09-09 13:41:33.481  6146  6297 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f4200ec, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dea7cb5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37d46f4amSocket: android.net.LocalSocket@1c981ebb impl:android.net.LocalSocketImpl@5c43fd8 fd:FileDescriptor[109]
,09-09 13:41:33.481  6146  6297 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c981ebb impl:android.net.LocalSocketImpl@5c43fd8 fd:FileDescriptor[109]
,09-09 13:41:33.481  6146  6297 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1168)
,09-09 13:41:33.501  1014  1541 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,09-09 13:41:33.511  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:41:33.871  1014  6664 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:33.901  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:33.911  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:33.931  3144  3144 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-09 13:41:33.951  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:33 GMT], X-Android-Received-Millis=[1473421293957], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421293907]}
09-09 13:41:33.951  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:33.951  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 13:41:33.951  1014  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-09 13:41:33.951  1014  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-09 13:41:33.951  1014  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-09 13:41:33.951  1014  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:33.951  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:33.951  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:33.951  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:33.971  6403  6403 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:33.971  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:33.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:33.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:33.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:33.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:33.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:33.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:33.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:33.981  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:33.981  1014  1326 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:33.981  1014  1326 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4193, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 13:41:33.981  1014  1326 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 13:41:33.981  1014  1326 D BatteryService: stay LED for charging
09-09 13:41:33.981  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:33.991  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:41:33.991  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:33.991  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:33.991  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:41:33.991  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:41:33.991  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:41:33.991  5792  5792 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 13:41:33.991  5792  5792 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:41:33.991  5792  5792 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:41:33.991  5792  5792 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:33.991  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-09 13:41:33.991  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-09 13:41:33.991  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:41:33.991  1014  1014 I MotionRecognitionService: Plugged
09-09 13:41:34.001  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:34.001  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.001  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.001  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:34.001  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.001  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.001  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.001  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:34.001  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:34.001  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:34.001  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:34.001  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:34.001  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:34.001  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:34.001  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:34.001  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:34.001  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:34.001  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 13:41:34.001  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,09-09 13:41:34.001  1014  1539 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 13:41:34.001  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:34.001  1014  1539 D SecContentProvider2: mCursor = null
,09-09 13:41:34.011  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:34.011  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:34.011  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:34.011  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:34.011  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:34.011  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:34.011  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:34.011  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:34.011  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:34.021  2657  2657 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:41:34.021  2657  2729 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:34.021  1014  1137 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-09 13:41:34.021  1014  1137 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:41:34.031  6403  6403 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 13:41:34.031  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
09-09 13:41:34.031  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:34.031  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:34.041  1727  1727 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:34.051  6417  6417 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-09 13:41:34.051  1727  1727 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:41:34.051  1727  1727 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-09 13:41:34.051  1727  1727 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-09 13:41:34.051  1727  1727 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:34.051  1014  1326 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:34.061  1014  1342 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:34.071  1312  1330 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,09-09 13:41:34.071  6417  6417 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-09 13:41:34.071  6417  6417 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-09 13:41:34.081  1727  1727 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:34.081  1727  1727 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
09-09 13:41:34.081  6417  6417 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-09 13:41:34.081  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:34.081  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:34.081  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:34.081  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:34.091  1727  1727 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-09 13:41:34.091  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:41:34 GMT+02:00 2016
,09-09 13:41:34.091  1014  1535 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 13:41:34.091  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.091  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.091  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:34.091  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:41:34.101  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:41:34.101  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:34.111  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
09-09 13:41:34.111  6586  6586 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-09 13:41:34.111  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
09-09 13:41:34.111  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-09 13:41:34.111  3666  3666 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:41:34.121  3666  3666 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:41:34.121  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 13:41:34.121  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.121  3666  6703 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:41:34.121  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.121  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:34.121  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 13:41:34.131  1014  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:34.131  3666  6703 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-09 13:41:34.131  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.131  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.131  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.131  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:34.131  1014  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:41:34.131  1014  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:34.131  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:41:34.131  1014  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:34.131  3666  6703 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-09 13:41:34.141  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:41:34.141   277   992 D EnterpriseController: uids 10012
09-09 13:41:34.141   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:34.141   277   992 D Netd    : getNetworkForDns: using netid 503 for uid 10012
,09-09 13:41:34.141  3666  6703 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,09-09 13:41:34.141  3666  6703 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,09-09 13:41:34.141  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:41:34.151  3798  3798 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:41:34.151  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:41:34.161  3798  4542 I iu.UploadsManager: num queued entries: 0
,09-09 13:41:34.161  3798  4542 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:34.161  3798  4542 I iu.SyncManager: NEXT; no task
,09-09 13:41:34.161  3666  6703 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,09-09 13:41:34.161  3666  6703 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-09 13:41:34.171  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-09 13:41:34.171  5921  5921 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-09 13:41:34.191  1014  1539 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-09 13:41:34.191  6642  6642 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
09-09 13:41:34.191  1014  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.191  1014  1539 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.191  1014  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.191  1014  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 13:41:34.191  6642  6642 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 13:41:34.201  6489  6538 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
09-09 13:41:34.201  6642  6642 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:41:34.201  5840  5840 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-09 13:41:34.201  3205  6714 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:41:34.201  3205  6714 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-09 13:41:34.211  3205  6714 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
09-09 13:41:34.211  6042  6042 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-09 13:41:34.211  6042  6042 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-09 13:41:34.211  6042  6042 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:34.211  6042  6042 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:41:34.211  6042  6042 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:41:34.211  6042  6042 I SA      : [SCU] == networkStateCheck == true
,09-09 13:41:34.221  6042  6042 I SA      : [DM] getCountryCodeFromCSC : PL
,09-09 13:41:34.221  6042  6042 I SA      : isChinaCountryCode : false
09-09 13:41:34.221  6042  6042 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-09 13:41:34.221  6042  6042 I SA      : [OR] == networkStateCheck true ==
,09-09 13:41:34.221  6042  6042 I SA      : [OR] GetMyCountryZoneTask
,09-09 13:41:34.221  6042  6042 I SA      : [OR] onReceive END
,09-09 13:41:34.241  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:34.241  1014  3124 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-09 13:41:34.241  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.241  6042  6719 I SA      : [SRS] prepareGetMyCountryZone
,09-09 13:41:34.241  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.241  1014  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:34.241  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-09 13:41:34.251  6042  6719 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:41:34.251  6042  6719 I SA      : [SSP] query invoked
09-09 13:41:34.251  3205  6714 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
09-09 13:41:34.261  6042  6719 I SA      : [TPMU] GetMccFromDB : null
09-09 13:41:34.261  6042  6719 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:41:34.261  6042  6719 I SA      : [LBE] isSupportCheckDomainRegion : false
09-09 13:41:34.261  6042  6719 I SA      : [TPM] isNoProxy(default) : true
,09-09 13:41:34.261  3205  6714 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-09 13:41:34.261  3205  6714 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-09 13:41:34.261  3205  6714 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-09 13:41:34.261  3205  6714 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-09 13:41:34.261  3205  6714 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-09 13:41:34.261  3205  6714 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-09 13:41:34.261  6042  6719 E File    : fail readDirectory() errno=2
,09-09 13:41:34.271  1014  1214 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,09-09 13:41:34.271  1014  1214 D SecContentProvider2: mCursor = null
,09-09 13:41:34.271  3205  6714 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-09 13:41:34.281  3205  6714 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-09 13:41:34.291  1946  6706 I qtaguid : Tagging socket 48 with tag 1000040700000000{268436487,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:34.291  3205  6714 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:41:34.381  1014  3125 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:41:34.381  1014  3125 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.381  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.381  1014  3125 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:34.381  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:41:34.391  5921  5921 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-09 13:41:34.391  5921  5921 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-09 13:41:34.391  5921  5921 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-09 13:41:34.391  5921  5921 D InitializeManagerStateMachine: exit::IDLE
09-09 13:41:34.391  5921  5921 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-09 13:41:34.401  1014  1027 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 13:41:34.401  5921  5921 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,09-09 13:41:34.401  5921  5921 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-09 13:41:34.401  5921  5921 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-09 13:41:34.401  5921  5921 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-09 13:41:34.401  5921  5921 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-09 13:41:34.401  5921  5921 D InitializeManagerStateMachine: entry::SUCCESS
09-09 13:41:34.401  5921  5921 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-09 13:41:34.401  5921  5921 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-09 13:41:34.401  1014  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
09-09 13:41:34.401  5921  5921 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-09 13:41:34.411  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.411  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.411  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:34.411  5921  5921 D InitializeManagerStateMachine: exit::SUCCESS
,09-09 13:41:34.411  5921  5921 D InitializeManagerStateMachine: entry::IDLE
,09-09 13:41:34.421  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-09 13:41:34.421  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.421  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.421  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.421  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:34.431  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.431  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.431  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:34.441  1014  1483 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 13:41:34.441  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.441  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.441  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:34.441  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:34.441  1014  1500 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:41:34.441  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.451  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.451  1014  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.451  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:34.451  1014  1137 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:41:34.451  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:41:34.451  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:34.451  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.451  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:34.461  1014  1214 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-09 13:41:34.461  1014  1214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-09 13:41:34.471  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.471  1014  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.471  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:34.491  1014  1500 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:34.491  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.491  1014  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.491  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-09 13:41:34.491  1946  1946 D WearableService: callingUid 10012, callindPid: 1946
,09-09 13:41:34.501  1014  1539 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.501  1014  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.501  1014  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:41:34.511  1014  3126 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 13:41:34.511  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 13:41:34.511  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:34.511  1014  3126 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:34.511  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 13:41:34.531  6403  6728 I MusicLeanback: Conditions not met for autocaching.,
,09-09 13:41:34.531  6403  6728 I MusicLeanback: Stop autocaching.
,09-09 13:41:34.551  6403  6403 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-09 13:41:34.561  6403  6733 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-09 13:41:34.671   290   290 E SMD     : DCD OFF
,09-09 13:41:34.691  1014  2772 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:41:34.701  6042  6719 I SA      : [RC New] Execute method=[GET] start
,09-09 13:41:34.741  6042  6719 I SA      : [RC New] Security=[true]
,09-09 13:41:34.741  6042  6719 I System.out: Thread-1030(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,09-09 13:41:34.741  6042  6719 I System.out: Thread-1030(ApacheHTTPLog):isSBSettingEnabled false
09-09 13:41:34.741  6042  6719 I System.out: Thread-1030(ApacheHTTPLog):isShipBuild true
09-09 13:41:34.741  6042  6719 I System.out: Thread-1030(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-09 13:41:34.741  6042  6719 I System.out: Thread-1030(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 13:41:34.741   277   992 D EnterpriseController: uids 10041
09-09 13:41:34.741   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:34.741   277   992 D Netd    : getNetworkForDns: using netid 503 for uid 10041
,09-09 13:41:35.151  1014  2730 D SSRM:n  : SIOP:: AP = 380
,09-09 13:41:35.361  6042  6719 I SA      : [RC New] [v2liruge] api execute + 620
,09-09 13:41:35.361  6042  6719 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,09-09 13:41:35.361  6042  6719 I System.out: AsyncTask #1 calls detatch()
,09-09 13:41:35.371  6042  6719 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-09 13:41:35.391  6042  6719 I SA      : [OCP] update openData : PL
,09-09 13:41:35.391  6042  6719 I SA      : [TPMU] getNetworkMcc : 
,09-09 13:41:35.401  6042  6719 I SA      : [SCU] saveMccToPreferece Start
,09-09 13:41:35.401  6042  6719 I SA      : [SCU] RegionMCC : 260
,09-09 13:41:35.401  6042  6719 I SA      : [SSP] query invoked
,09-09 13:41:35.401  6042  6719 I SA      : [TPMU] GetMccFromDB : null
,09-09 13:41:35.401  6042  6719 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-09 13:41:35.401  6042  6719 I SA      : [SCU] saveMccToPreferece End
,09-09 13:41:35.401  6042  6719 I SA      : [RC New] executeRequest [v2liruge] end. 700
09-09 13:41:35.401  6042  6719 I SA      : [RC New] Execute end
,09-09 13:41:35.401  6042  6042 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-09 13:41:35.401  6042  6042 I SA      : [OR] GetMyCountryZoneTask Success
,09-09 13:41:36.101  6146  6663 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
,09-09 13:41:36.101  6146  6196 D BluetoothAdapter: disable()
,09-09 13:41:36.101  1014  3125 D SettingsProvider: name = bluetooth_on
,09-09 13:41:36.111  2657  2722 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-09 13:41:36.111  2657  2722 D BluetoothAdapterProperties: Setting state to 13
,09-09 13:41:36.111  2657  2722 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 13:41:36.111  2657  2722 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 13:41:36.111  2657  2722 D BluetoothAdapterService: updateAdapterState state is 13
,09-09 13:41:36.111  1014  1535 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:36.121  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
,09-09 13:41:36.121  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.121  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.121  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:36.121  2657  2657 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-09 13:41:36.121  2657  2722 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:36.121  2657  2657 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@362788cb, channel: 19, state: LISTENING
09-09 13:41:36.121  2657  2657 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@362788cb, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15782253, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@328548a8mSocket: android.net.LocalSocket@38d34fc1 impl:android.net.LocalSocketImpl@48bf366 fd:FileDescriptor[76]
09-09 13:41:36.121  2657  2657 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38d34fc1 impl:android.net.LocalSocketImpl@48bf366 fd:FileDescriptor[76]
,09-09 13:41:36.121  2657  2722 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 13:41:36.121  2657  2722 D BluetoothAdapterService: terminating service from this receiver
,09-09 13:41:36.131  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:36.131  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-09 13:41:36.141  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-09 13:41:36.141  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:41:36.141  1173  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:41:36.141  1173  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:41:36.141  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:36.151  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-09 13:41:36.151  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 13:41:36.151  1294  1294 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:36.151  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 13:41:36.161  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.161  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:36.161  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:36.161  1774  1774 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-09 13:41:36.161  1014  1342 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:41:36.161  1014  3124 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:41:36.161  2657  2722 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 13:41:36.161  1014  3125 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:36.161  1014  3125 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:41:36.161  2657  2722 D BluetoothAdapterProperties: mDiscovering is false
,09-09 13:41:36.161  1014  3126 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 13:41:36.171  2657  2722 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 13:41:36.171  6146  6146 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:36.171  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:36.171  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.171  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:36.171  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.171  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:36.171  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:36.171  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:36.171  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:36.171  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.171  1014  3125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:36.171  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:41:36.171  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 13:41:36.171  6146  6146 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 13:41:36.171  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:36.181  2657  2725 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 13:41:36.181  2657  2725 D BluetoothAdapterProperties: Scan Mode:20
,09-09 13:41:36.181  2657  2722 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 13:41:36.181  2657  2722 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-09 13:41:36.181  2657  2722 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-09 13:41:36.181  2657  2722 E bt-btif : cmd socket is not created
,09-09 13:41:36.181  2657  2804 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-09 13:41:36.181  2657  2804 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-09 13:41:36.181  2657  2722 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 13:41:36.181  2657  4950 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 13:41:36.181  6146  6146 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:36.181  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:36.181  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.181  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:36.181  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.181  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:36.181  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:36.181  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:36.181  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:36.191  2657  2804 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 13:41:36.191  2657  2657 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3aa3e6a7, channel: 5, state: LISTENING
09-09 13:41:36.191  2657  2804 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:36.191  2657  2804 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:41:36.191  2657  2657 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3aa3e6a7, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@345a6242, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@343a4754mSocket: android.net.LocalSocket@3d8426fd impl:android.net.LocalSocketImpl@19d3dff2 fd:FileDescriptor[74]
09-09 13:41:36.191  2657  2657 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d8426fd impl:android.net.LocalSocketImpl@19d3dff2 fd:FileDescriptor[74]
09-09 13:41:36.191  2657  2657 I BtOppRfcommListener: stopping Accept Thread
09-09 13:41:36.191  2657  2657 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@349e4643, channel: 12, state: LISTENING
09-09 13:41:36.191  2657  2657 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@349e4643, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ff6b445, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b9e84c0mSocket: android.net.LocalSocket@1b7135f9 impl:android.net.LocalSocketImpl@253c093e fd:FileDescriptor[80]
09-09 13:41:36.191  2657  2657 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b7135f9 impl:android.net.LocalSocketImpl@253c093e fd:FileDescriptor[80]
,09-09 13:41:36.191  2657  4950 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 13:41:36.191  6146  6146 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:36.191  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:36.191  6146  6146 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:36.191  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:36.191  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:36.191  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:36.191  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:36.191  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:36.191  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:36.191  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:36.191  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:36.191  6146  6146 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:36.191  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:36.191  2657  2657 V BluetoothOppManager: cleanUp...
,09-09 13:41:36.201  1294  1294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:36.201  1014  3124 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 13:41:36.201  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:41:36.201  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:36.201  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.201  1014  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.201  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:41:36.201  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:36.211  1294  1294 D BluetoothPbap: Proxy object disconnected
09-09 13:41:36.211  1294  1294 D PbapServerProfile: Bluetooth service disconnected
,09-09 13:41:36.211  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:36.221  1294  1294 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:36.221  1294  1294 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:41:36.221  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:36.221  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 13:41:36.221  1014  1342 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 13:41:36.221  1014  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:36.221  1014  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:36.231  1014  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:36.231  1014  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:36.231  1014  1328 E Watchdog: !@Sync 4
,09-09 13:41:36.241  6740  6740 E Zygote  : MountEmulatedStorage(),
09-09 13:41:36.241  1014  1342 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6740 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
09-09 13:41:36.241  6740  6740 E Zygote  : v2
09-09 13:41:36.241  6740  6740 I libpersona: KNOX_SDCARD checking this for 10003
09-09 13:41:36.241  6740  6740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-09 13:41:36.241  6740  6740 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:36.251  6740  6740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:36.251  6740  6740 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:36.281  6740  6740 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:36.281  6740  6740 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:36.311  6740  6740 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 13:41:36.341  6740  6740 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-09 13:41:36.341  6740  6740 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,09-09 13:41:36.351  6740  6740 D UserAnalysis: Create SecureDbHelper
,09-09 13:41:36.351  6740  6740 D IntelligenceServiceApplication: onCreate()
,09-09 13:41:36.361  1014  3124 I ActivityManager: Killing 5894:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-09 13:41:36.361  1014  3125 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 13:41:36.371  1014  3125 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:41:36.371  1014  3125 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:36.371  6740  6740 D IntelligenceServiceApplication: no applications having user consent for prediction
09-09 13:41:36.371  1014  3125 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:36.371  1014  3125 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-09 13:41:36.381  6758  6758 E Zygote  : MountEmulatedStorage(),
,09-09 13:41:36.381  2657  2804 W bt-l2cap: btif_mce_execute_service enable:0,
09-09 13:41:36.381  6758  6758 I libpersona: KNOX_SDCARD checking this for 10107,
09-09 13:41:36.381  2657  2804 W bt-l2cap: HC lib lpm enable=0 not found for deregistration
09-09 13:41:36.381  6758  6758 I libpersona: KNOX_SDCARD not a persona
09-09 13:41:36.381  2657  2804 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:41:36.381  2657  2804 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:36.381  2657  2804 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:36.381  2657  2804 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:41:36.381  2657  2804 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 13:41:36.381  1014  3125 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6758 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-09 13:41:36.381  6758  6758 E Zygote  : v2
,09-09 13:41:36.381  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-09 13:41:36.381  2657  2804 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 13:41:36.381  2657  2804 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 13:41:36.381  2657  2804 W bt-btif : ag scb idx 1 not allocated
09-09 13:41:36.381  2657  2804 W bt-btif : ag scb idx 2 not allocated
09-09 13:41:36.381  2657  2804 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 13:41:36.381  1014  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,09-09 13:41:36.381  2657  2851 I bt_userial_mct: exiting userial_read_thread
09-09 13:41:36.381  2657  2851 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 13:41:36.381  2657  2725 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 13:41:36.381  2657  2807 I bt_vendor: hw_epilog_process
09-09 13:41:36.381  6758  6758 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:41:36.381  2657  2725 D bt_userial_mct: userial_close
09-09 13:41:36.381  2657  2725 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 13:41:36.391  6740  6740 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-09 13:41:36.391  6758  6758 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:41:36.391  6758  6758 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-09 13:41:36.401  6740  6740 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-09 13:41:36.401  6758  6758 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:36.411  6758  6758 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:36.581  1014  1214 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,09-09 13:41:36.581  1014  1214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 13:41:36.581  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:36.581  1014  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:36.581  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 13:41:36.591  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:36.591  1946  1946 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 13:41:36.641  6758  6758 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:36.641  6758  6758 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:36.641  6758  6758 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:36.641  6758  6758 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:36.641  6758  6758 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:36.641  6758  6758 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:36.641  6758  6758 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.k.c(PG:583)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:36.641  6758  6758 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 13:41:36.641  6758  6758 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 13:41:36.641  1014  1137 I ActivityManager: Killing 5851:com.google.android.apps.docs/u0a91 (adj 15): empty #31
09-09 13:41:36.641  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-09 13:41:36.651  2657  2725 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 13:41:36.651  2657  2725 I bt_vendor: bluetooth satus is on
09-09 13:41:36.651  2657  2725 I bt_vendor: bt-vendor : resetting BT status
09-09 13:41:36.651  2657  2725 I bt_vendor: Starting hciattach daemon
09-09 13:41:36.651  2657  2725 I bt_vendor: try to set false
09-09 13:41:36.651  2657  2725 I bt_vendor: Starting hciattach daemon
09-09 13:41:36.651  2657  2725 I bt_vendor: try to set false
09-09 13:41:36.651  2657  2725 I bt_vendor: cleanup
09-09 13:41:36.651  2657  2804 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-09 13:41:36.661  2657  2725 I GKI_LINUX: GKI_exit_task 0 done
09-09 13:41:36.661  2657  2725 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 13:41:36.661  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:41:36.661  2657  2722 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 13:41:36.661  2657  2722 D BtConfig.SecureMode: isSecureModeOn:false
09-09 13:41:36.661  2657  2722 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 13:41:36.661  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 13:41:36.661  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:41:36.661  2657  2722 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-09 13:41:36.661  1014  1326 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:36.661  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-09 13:41:36.661  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.661  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.661  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:36.671  2657  2657 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:41:36.671  2657  2657 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 13:41:36.671  2657  2657 D BtGatt.GattService: stop()
09-09 13:41:36.671  2657  2657 D BtGatt.AdvertiseManager: advertise clients cleared
09-09 13:41:36.671  2657  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc573e8
09-09 13:41:36.671  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:41:36.671  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:41:36.671  2657  2722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 13:41:36.671  1014  3126 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:36.671  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-09 13:41:36.671  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.671  1014  3126 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.671  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:36.681  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 13:41:36.681  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:41:36.681  2657  2722 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-09 13:41:36.681  1014  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:36.681  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 13:41:36.681  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.681  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.681  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:36.681  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 13:41:36.681  1014  3124 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 13:41:36.681  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:36.681  2657  2722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 13:41:36.681  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.681  1014  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:36.681  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 13:41:36.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...
09-09 13:41:36.691  1014  1535 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:36.691  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 13:41:36.691  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.691  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.691  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:36.691  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 13:41:36.691  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:41:36.691  2657  2722 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 13:41:36.691  1014  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:36.691  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 13:41:36.691  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.691  1014  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.691  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:36.701  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 13:41:36.701  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:41:36.701  2657  2722 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 13:41:36.701  1014  3126 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:36.701  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 13:41:36.701  6758  6780 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-09 13:41:36.701  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.701  1014  3126 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.701  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:36.701  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.701  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.701  2657  2722 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.701  1014  1342 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:36.701  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-09 13:41:36.711  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.711  1014  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.711  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 13:41:36.711  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-09 13:41:36.711  1014  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:36.711  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-09 13:41:36.711  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.711  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.711  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:36.711  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:36.711  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 13:41:36.711  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 13:41:36.711  2657  2722 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 13:41:36.711  2657  2722 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:41:36.711  1014  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 13:41:36.711  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.711  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:36.711  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-09 13:41:36.721  2657  2722 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 13:41:36.721  2657  2722 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 13:41:36.721  2657  2657 E BluetoothAdapterService(751137768): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-09 13:41:36.721  2657  2657 D HeadsetService: Received stop request...Stopping profile...
,09-09 13:41:36.721  2657  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc573e8
,09-09 13:41:36.721  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-09 13:41:36.721  2657  2657 D A2dpService: Received stop request...Stopping profile...
09-09 13:41:36.721  1294  1294 D HeadsetProfile: Bluetooth service disconnected
,09-09 13:41:36.731  2657  2733 D A2dpStateMachine: Exit Disconnected: -1
,09-09 13:41:36.731  2657  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc573e8
,09-09 13:41:36.731  1014  1014 D BluetoothA2dp: Proxy object disconnected
,09-09 13:41:36.731  1294  1294 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:36.731  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-09 13:41:36.731  1294  1294 D A2dpProfile: Bluetooth service disconnected
09-09 13:41:36.731  2872  2872 D BluetoothA2dp: Proxy object disconnected
,09-09 13:41:36.731  2657  2657 D HidService: Received stop request...Stopping profile...
,09-09 13:41:36.731  2657  2657 D HidService: Stopping Bluetooth HidService
09-09 13:41:36.731  2657  2657 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 13:41:36.731  2657  2657 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 13:41:36.731  2657  2657 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 13:41:36.731  2657  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc573e8
,09-09 13:41:36.741  2657  2657 D HealthService: Received stop request...Stopping profile...
,09-09 13:41:36.741  2657  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc573e8
09-09 13:41:36.741  1294  1294 D BluetoothInputDevice: Proxy object disconnected
,09-09 13:41:36.741  1294  1294 D HidProfile: Bluetooth service disconnected
09-09 13:41:36.741  2657  2657 D PanService: Received stop request...Stopping profile...
09-09 13:41:36.741  2657  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc573e8
,09-09 13:41:36.741  2657  2657 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 13:41:36.741  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 13:41:36.741  1294  1294 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 13:41:36.741  1294  1294 D PanProfile: Bluetooth service disconnected
,09-09 13:41:36.741  2657  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc573e8
,09-09 13:41:36.741  2657  2657 D SapService: Received stop request...Stopping profile...
,09-09 13:41:36.751  1294  1294 D BluetoothMap: Proxy object disconnected
09-09 13:41:36.751  1294  1294 D MapProfile: Bluetooth service disconnected
,09-09 13:41:36.751  2657  2657 D SapService: Stopping Bluetooth SapService
,09-09 13:41:36.751  2657  2657 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc573e8
,09-09 13:41:36.751  1294  1294 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 13:41:36.751  1294  1294 D SapProfile: Bluetooth service disconnected
,09-09 13:41:36.751  2657  2657 E BluetoothAdapterService(751137768): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 13:41:36.751  2657  2657 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:36.751  2657  2657 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 13:41:36.751  2657  2657 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-09 13:41:36.751  2657  2657 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 13:41:36.751  2657  2657 E BluetoothAdapterService(751137768): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 13:41:36.751  2657  2657 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:36.751  2657  2657 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 13:41:36.751  2657  2657 D BluetoothA2dp: Proxy object disconnected
09-09 13:41:36.751  2657  2657 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-09 13:41:36.751  2657  2735 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-09 13:41:36.751  2657  2657 I GKI_LINUX: GKI_exit_task 2 done
09-09 13:41:36.751  2657  2657 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-09 13:41:36.751  2657  2657 E BluetoothAdapterService(751137768): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 13:41:36.751  2657  2657 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.751  2657  2657 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-09 13:41:36.751  2657  2657 E BluetoothAdapterService(751137768): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 13:41:36.751  2657  2657 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.751  2657  2657 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.751  2657  2657 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...,
09-09 13:41:36.751  2657  2657 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 13:41:36.751  2657  2657 E BluetoothAdapterService(751137768): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 13:41:36.751  2657  2657 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.751  2657  2657 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.751  2657  2657 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-09 13:41:36.761  2657  2657 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 13:41:36.761  2657  2657 E BluetoothAdapterService(751137768): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-09 13:41:36.761  2657  2657 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:41:36.761  2657  2657 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-09 13:41:36.761  2657  2657 E BluetoothAdapterService(751137768): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-09 13:41:36.761  2657  2657 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,09-09 13:41:36.761  2657  2657 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-09 13:41:36.761  2657  2722 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-09 13:41:36.761  2657  2722 D BluetoothAdapterProperties: Setting state to 10
09-09 13:41:36.761  2657  2722 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 13:41:36.761  2657  2722 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:36.761  2657  2722 D BluetoothAdapterService: updateAdapterState state is 10
09-09 13:41:36.761  2657  2722 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:36.761  2657  2722 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 13:41:36.761  2872  2878 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:36.761  2872  2878 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:36.761  2657  2722 I BluetoothAdapterState: Entering OffState
,09-09 13:41:36.761  6146  6155 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:41:36.761  6146  6155 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:36.761  6146  6155 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 13:41:36.761  6146  6155 D BluetoothLeAdvertiser: Exit stop advertising
09-09 13:41:36.761  6146  6155 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-09 13:41:36.761  6146  6155 D BluetoothLeScanner: Exiting stopAllScan
09-09 13:41:36.761  1294  1308 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:41:36.771  1294  1311 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 13:41:36.771  1294  6785 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 13:41:36.771  6758  6768 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:41:36.771  6758  6768 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:36.771  1294  1311 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 13:41:36.771  2657  2917 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:41:36.771  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:41:36.771  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:36.771  1424  1447 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:36.771  1424  1447 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:36.771  1453  2158 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:36.771  1453  2158 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:36.771  1294  6785 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:41:36.781  1294  6785 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:36.781  1441  1451 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:41:36.781  1441  1451 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 13:41:36.781  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:41:36.781  1173  2341 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 13:41:36.781  1173  2341 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:36.781  2657  2918 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:36.781  2657  2918 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:36.781  1946  1959 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 13:41:36.781  1946  1959 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 13:41:36.781  1294  1311 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 13:41:36.781  1294  1311 D Bluetoothsap: Unbinding service...
,09-09 13:41:36.781  2872  2930 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 13:41:36.781  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-09 13:41:36.791  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 13:41:36.791  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:36.791  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-09 13:41:36.791  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:41:36.801  2657  2725 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 13:41:36.801  2657  2657 I GKI_LINUX: GKI_exit_task 1 done
09-09 13:41:36.801  2657  2657 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 13:41:36.801  2657  2657 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 13:41:36.801  1173  1173 D BluetoothAdapter: 754599201: getState() :  mService = null. Returning STATE_OFF
09-09 13:41:36.801  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:41:36.801  1173  1704 D BluetoothAdapter: 754599201: getState() :  mService = null. Returning STATE_OFF
,09-09 13:41:36.801  2657  2657 I art     : System.exit called, status: 0
09-09 13:41:36.801  2657  2657 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 13:41:36.801  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:36.801  1173  1173 D BluetoothTile:  getBluetoothState : 10
,09-09 13:41:36.801  1173  1704 D BluetoothAdapter: 754599201: getState() :  mService = null. Returning STATE_OFF
,09-09 13:41:36.801  1173  1173 D BluetoothAdapter: 754599201: getState() :  mService = null. Returning STATE_OFF
09-09 13:41:36.801  1173  1173 D BluetoothAdapter: 754599201: getState() :  mService = null. Returning STATE_OFF
,09-09 13:41:36.801  1014  3124 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:41:36.801  1774  1774 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:41:36.801  1014  3125 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 13:41:36.801  1294  1294 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:36.811  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:41:36.811  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:36.811  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:41:36.811  1946  2129 D BluetoothAdapter: 726492058: getState() :  mService = null. Returning STATE_OFF
,09-09 13:41:36.811  1946  2129 D BluetoothAdapter: 726492058: getState() :  mService = null. Returning STATE_OFF
,09-09 13:41:36.811  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:36.811  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:36.811  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:36.811  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:36.821  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:36.821  1294  1294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:36.821  1014  1500 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 13:41:36.821  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 13:41:36.821  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:36.821  1014  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:36.821  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-09 13:41:36.821  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:36.831  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 13:41:36.831  1294  1294 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:36.831  1294  1294 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:41:36.841  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:36.841  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 13:41:36.851  1014  1539 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-09 13:41:36.851  1014  1539 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-09 13:41:36.861  1014  1539 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-09 13:41:36.861  1014  1539 W BroadcastQueue: android.os.TransactionTooLargeException
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-09 13:41:36.861  1014  1539 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 13:41:36.861  1014  1539 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-09 13:41:36.861  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:36.861  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:36.861  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:36.861  1014  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:41:36.871  6792  6792 E Zygote  : MountEmulatedStorage()
,09-09 13:41:36.871  6792  6792 I libpersona: KNOX_SDCARD checking this for 1002
,09-09 13:41:36.871  6792  6792 E Zygote  : v2,
09-09 13:41:36.871  6792  6792 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:36.871  6792  6792 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-09 13:41:36.881  1014  1539 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6792 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-09 13:41:36.871  6792  6792 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:41:36.881  6792  6792 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:41:36.901  6792  6792 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:36.901  6792  6792 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:36.901  6666  6666 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:41:36.911  6792  6792 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-09 13:41:36.911  6792  6792 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 13:41:36.931  6792  6792 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-09 13:41:36.961   257  1052 I SurfaceFlinger: id=15 Removed Uoast (8/9),
,09-09 13:41:36.961  1014  1026 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 139177
09-09 13:41:36.961   257   452 I SurfaceFlinger: id=15 Removed Uoast (-2/9)
09-09 13:41:36.961  1014  1026 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
09-09 13:41:36.961  1014  1026 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=3464)
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding GattService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding HeadsetService,
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding A2dpService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding HidService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding HealthService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding PanService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding SapService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding SapClientService
09-09 13:41:36.971  6792  6792 D BtSettings.ProfileConfig: Adding HidDevService
09-09 13:41:36.971  6792  6792 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******,
,09-09 13:41:36.971  1014  1541 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
09-09 13:41:36.971  1014  1541 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.971  1014  1541 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.971  1014  1541 D SettingsProvider: selectionArgs: false
09-09 13:41:36.971  1014  1541 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.971  1014  1541 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.971  1014  1541 D SettingsProvider: ret = -1
09-09 13:41:36.971  1014  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-09 13:41:36.971  1014  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.971  1014  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.971  1014  1137 D SettingsProvider: selectionArgs: false
09-09 13:41:36.971  1014  1137 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.971  1014  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.971  1014  1137 D SettingsProvider: ret = -1
,09-09 13:41:36.971  1014  1342 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-09 13:41:36.971  1014  1342 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.971  1014  1342 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.971  1014  1342 D SettingsProvider: selectionArgs: false
09-09 13:41:36.971  1014  1342 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.971  1014  1342 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.971  1014  1342 D SettingsProvider: ret = -1
09-09 13:41:36.971  1014  3126 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-09 13:41:36.971  1014  3126 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.971  1014  3126 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.971  1014  3126 D SettingsProvider: selectionArgs: false
09-09 13:41:36.971  1014  3126 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.971  1014  3126 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-09 13:41:36.971  1014  3126 D SettingsProvider: ret = -1
,09-09 13:41:36.981  1014  1539 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-09 13:41:36.981  1014  1539 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.981  1014  1539 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.981  1014  1539 D SettingsProvider: selectionArgs: false
09-09 13:41:36.981  1014  1539 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.981  1014  1539 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.981  1014  1539 D SettingsProvider: ret = -1
,09-09 13:41:36.981  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-09 13:41:36.981  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.981  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.981  1014  1027 D SettingsProvider: selectionArgs: false
09-09 13:41:36.981  1014  1027 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.981  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 13:41:36.981  1014  1027 D SettingsProvider: ret = -1
,09-09 13:41:36.981  1014  1535 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-09 13:41:36.981  1014  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.981  1014  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.981  1014  1535 D SettingsProvider: selectionArgs: false
09-09 13:41:36.981  1014  1535 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.981  1014  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.981  1014  1535 D SettingsProvider: ret = -1
,09-09 13:41:36.981  1014  3124 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-09 13:41:36.981  1014  3124 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.981  1014  3124 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.981  1014  3124 D SettingsProvider: selectionArgs: false
09-09 13:41:36.981  1014  3124 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.981  1014  3124 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 13:41:36.981  1014  3124 D SettingsProvider: ret = -1
09-09 13:41:36.981  1014  1326 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:36.981  1014  1326 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.981  1014  1326 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.981  1014  1326 D SettingsProvider: selectionArgs: false
09-09 13:41:36.981  1014  1326 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.981  1014  1326 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.981  1014  1326 D SettingsProvider: ret = -1
,09-09 13:41:36.981  1014  1214 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:36.981  1014  1214 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.981  1014  1214 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.981  1014  1214 D SettingsProvider: selectionArgs: false
09-09 13:41:36.981  1014  1214 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.981  1014  1214 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.981  1014  1214 D SettingsProvider: ret = -1
09-09 13:41:36.981  1014  3125 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-09 13:41:36.981  1014  3125 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-09 13:41:36.981  1014  3125 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.981  1014  3125 D SettingsProvider: selectionArgs: false
09-09 13:41:36.981  1014  3125 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.981  1014  3125 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.981  1014  3125 D SettingsProvider: ret = -1
,09-09 13:41:36.981  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-09 13:41:36.981  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:36.981  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:36.981  1014  1026 D SettingsProvider: selectionArgs: false
09-09 13:41:36.981  1014  1026 D SettingsProvider: selectionArgs: 1002
09-09 13:41:36.991  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:36.991  1014  1026 D SettingsProvider: ret = -1
,09-09 13:41:36.991  1014  1541 I ActivityManager: Killing 6072:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-09 13:41:37.001  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:37.001  1014  1541 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:37.001  1014  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.001  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:37.001  1014  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:37.001  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:37.011  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 13:41:37.011  1946  6808 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 13:41:37.161  1014  1326 I art     : Explicit concurrent mark sweep GC freed 68359(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 2.507ms total 150.053ms,
,09-09 13:41:37.161  1014  3126 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:37.161  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.161  1014  3126 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 13:41:37.161  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:37.181  1014  3125 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:37.181  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:37.181  1014  3125 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:37.181  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:37.191  1946  6808 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-09 13:41:37.201  1014  3125 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-09 13:41:37.211  1014  3125 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:41:37.211  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:37.211  1014  3125 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:37.211  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:41:37.681   290   290 E SMD     : DCD OFF,
,09-09 13:41:37.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:38.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:39.011  5792  5792 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,09-09 13:41:39.021  5792  6810 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,09-09 13:41:39.041  5792  6810 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,09-09 13:41:39.041  5792  6810 I ReactiveServiceManager: Supported : 1
,09-09 13:41:39.041  1014  3126 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,09-09 13:41:39.041  1014  3126 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 13:41:39.061  1014  3126 D QSEECOMAPI: : Loaded image: APP id = 12
,09-09 13:41:39.071  1014  3126 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-09 13:41:39.071  1014  3126 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
,09-09 13:41:39.071  1014  3126 E terrier : handleString: Failed to handle string(-4)
09-09 13:41:39.071  1014  3126 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,09-09 13:41:39.071  5792  6810 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
09-09 13:41:39.071  5792  6810 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,09-09 13:41:39.071  5792  6810 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 13:41:39.071  5792  6810 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:41:39.071  5792  6810 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:41:39.071  5792  6810 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,09-09 13:41:39.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:40.491  1014  2001 V SAMP_SPCM_test: CSC File load.. ,
,09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time,
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi,
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering,
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email,
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-09 13:41:40.501  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-09 13:41:40.531  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
,09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall,
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 13:41:40.541  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-09 13:41:40.551  1014  2001 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-09 13:41:40.561  1014  2001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,09-09 13:41:40.561  1014  2001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-09 13:41:40.561  1014  2001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-09 13:41:40.561  1014  2001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account,
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction,
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 13:41:40.551  1014  2001 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-09 13:41:40.571  1014  2001 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6813 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 13:41:40.571  6813  6813 E Zygote  : MountEmulatedStorage()
,09-09 13:41:40.571  6813  6813 E Zygote  : v2
,09-09 13:41:40.571  6813  6813 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:41:40.571  6813  6813 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:41:40.571  6813  6813 I libpersona: KNOX_SDCARD not a persona
,09-09 13:41:40.581  6813  6813 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 13:41:40.581  6813  6813 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 13:41:40.601  6813  6813 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:41:40.601  6813  6813 D ActivityThread: Added TimaKeyStore provider
,09-09 13:41:40.631  6813  6813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:41:40.681  1014  2001 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-09 13:41:40.681   290   290 E SMD     : DCD OFF
,09-09 13:41:40.681  1014  1014 I ActivityManager: Killing 6096:com.samsung.helphub/1000 (adj 15): empty #31
,09-09 13:41:40.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:41:40.911  6666  6666 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:41:41.141  6146  6736 E io.jxcore.node.ConnectivityMonitorTest: BT state didn't change after 5s!
09-09 13:41:41.141  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:41.141  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:41.141  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:41.141  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:41.141  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:41.141  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:41.141  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45939f9 removed from the list
09-09 13:41:41.141  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:41.141  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@193dbd3e removed from the list
09-09 13:41:41.141  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:41.141  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:41.141  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:41.141  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:41.141  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39132f31 added. We now have 3 listener(s)
09-09 13:41:41.141  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:41.141  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:41.141  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:41.141  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:41.141  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16723616 added. We now have 3 listener(s)
09-09 13:41:41.141  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 13:41:41.141  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:41.141  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-09 13:41:41.141  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-09 13:41:41.141  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:41.141  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-09 13:41:41.141  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:41.141  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:41.141  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:41.141  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.141  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:41.141  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:41.141  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.141  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.141  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:41.151  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:41.151  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:41.151  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:41.151  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:41.151  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39132f31 removed from the list
09-09 13:41:41.151  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:41.151  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16723616 removed from the list
09-09 13:41:41.151  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.151  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.151  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 13:41:41.151  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:41.161  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:41.161  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23298184 added. We now have 3 listener(s)
,09-09 13:41:41.161  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:41.161  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:41.161  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:41.161  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:41.161  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3a8d6d added. We now have 3 listener(s)
09-09 13:41:41.161  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:41.161  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:41.161  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:41.161  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.161  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:41.161  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:41.161  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:41.161  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:41.161  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 13:41:41.161  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.161  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:41.161  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:41.161  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 13:41:41.161  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:41.161  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:41.161  6146  6196 D BluetoothAdapter: disable()
,09-09 13:41:41.171  1014  1026 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-09 13:41:41.171  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:41.171  6146  6196 D BluetoothAdapter: enable()
,09-09 13:41:41.181  1014  3126 W ActivityManager: Permission Denial: getCurrentUser() from pid=6146, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:41:41.181  1014  3126 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 13:41:41.181  1014  3126 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6146, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:41.181  1014  3126 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 13:41:41.181  1014  3126 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-09 13:41:41.181  1014  3126 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-09 13:41:41.181  1014  3126 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-09 13:41:41.181  1014  3126 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 13:41:41.181  1014  3126 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 13:41:41.181  1014  3126 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:41:41.181  1014  3126 D SettingsProvider: name = bluetooth_on
,09-09 13:41:41.191  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 13:41:41.191  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:41:41.191  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-09 13:41:41.191  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-09 13:41:41.211  6792  6792 D BluetoothAdapterState: make
,09-09 13:41:41.221  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.221  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 13:41:41.221  6792  6792 I bluedroid: init
,09-09 13:41:41.221  6792  6832 I BluetoothAdapterState: Entering OffState
,09-09 13:41:41.231  6792  6792 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 13:41:41.231  6792  6792 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 13:41:41.231  6792  6792 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 13:41:41.231  6792  6792 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 13:41:41.231  6792  6792 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-09 13:41:41.231  6792  6792 I bluedroid: get_profile_interface socket
09-09 13:41:41.231  6792  6792 I bluedroid: get_profile_interface map_client
09-09 13:41:41.231  6792  6835 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 13:41:41.231  6792  6835 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-09 13:41:41.231  6792  6835 E BluetoothServiceJni: populateRssiValuesNative
09-09 13:41:41.231  6792  6835 I bluedroid: getModelRssiValues
09-09 13:41:41.231  6792  6835 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 13:41:41.231  6792  6835 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-09 13:41:41.231  6792  6835 D BluetoothAdapterProperties: Name is: A5-1
09-09 13:41:41.231  1014  1014 D SettingsProvider: name = bluetooth_name
09-09 13:41:41.231  6792  6792 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-09 13:41:41.241  6792  6792 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:41.241  1014  3124 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:41:41.241  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.241  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:41.241  1014  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.241  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.241  6792  6801 I bluedroid: config_hci_snoop_log
,09-09 13:41:41.241  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-09 13:41:41.251  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
09-09 13:41:41.251  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 13:41:41.251  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
09-09 13:41:41.251  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 13:41:41.251  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 13:41:41.251  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 13:41:41.251  6792  6792 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-09 13:41:41.251  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 13:41:41.261  6792  6832 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 13:41:41.261  6792  6832 D BluetoothAdapterProperties: Setting state to 11
,09-09 13:41:41.261  6792  6832 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-09 13:41:41.261  6792  6832 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:41.261  6792  6832 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 13:41:41.261  6792  6832 D BluetoothAdapterService: Autoconnection is available 
,09-09 13:41:41.261  6792  6832 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-09 13:41:41.261  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:41.261  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-09 13:41:41.271  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:41:41.271  6792  6832 D BluetoothSecureManager: getInstant: null
09-09 13:41:41.271  6792  6832 D BluetoothSecureManager: calling getMethod for getService
09-09 13:41:41.271  6792  6832 D BluetoothSecureManager: calling getService
,09-09 13:41:41.271  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:41.271  1173  1173 D BluetoothTile:  getBluetoothState : 11
09-09 13:41:41.271  6792  6832 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@186b742c
,09-09 13:41:41.271  1014  1027 D BluetoothSecureManagerService: isSecureModeEnabled
,09-09 13:41:41.271  1014  1027 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-09 13:41:41.281  6792  6832 D BtConfig.SecureMode: isSecureModeOn:false
09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 13:41:41.281  6792  6832 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:41:41.281  1774  1774 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 13:41:41.281  6792  6832 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 13:41:41.281  6792  6832 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 13:41:41.281  6792  6832 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService,
09-09 13:41:41.281  1014  3124 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:41:41.281  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 13:41:41.281  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 13:41:41.281  1173  1704 D BluetoothTile:  handleUpdatestate:false name:null
09-09 13:41:41.281  6792  6832 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-09 13:41:41.281  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:41:41.281  6792  6832 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:41.281  6792  6832 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 13:41:41.281  1294  1294 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:41.281  6792  6832 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-09 13:41:41.281  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 13:41:41.291  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.291  6792  6832 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:41.291  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 13:41:41.291  6792  6832 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:41.291  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:41:41.291  6792  6832 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 13:41:41.291  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 13:41:41.291  6792  6832 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-09 13:41:41.291  1014  1326 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:41.291  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.291  6792  6832 D BluetoothBondStateMachine: make
09-09 13:41:41.291  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 13:41:41.291  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.301  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.301  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:41.301  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:41.301  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 13:41:41.301  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 13:41:41.301  6792  6832 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-09 13:41:41.301  6792  6836 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 13:41:41.301  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.301  1014  3125 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:41.301  1014  3125 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.301  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.301  1294  1294 D BluetoothNotiBroadcastReceiver: onReceive
09-09 13:41:41.301  1014  3125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:41.301  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.311  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 13:41:41.311  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 13:41:41.311  6792  6832 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 13:41:41.311  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:41.311  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.311  6792  6792 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 13:41:41.311  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.311  6792  6792 D BtGatt.GattService: Received start request. Starting profile...
09-09 13:41:41.311  6792  6792 D BtGatt.GattService: start()
09-09 13:41:41.311  6792  6792 D BtGatt.GattService: start()
09-09 13:41:41.311  6792  6792 I bluedroid: get_profile_interface gatt
09-09 13:41:41.311  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.311  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.311  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
09-09 13:41:41.311  6792  6792 D BtGatt.AdvertiseManager: advertise manager created
,09-09 13:41:41.311  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 13:41:41.311  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 13:41:41.311  6792  6832 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 13:41:41.321  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:41.321  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.321  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:41.321  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 13:41:41.321  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.321  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.321  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.321  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-09 13:41:41.331  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 13:41:41.331  6792  6832 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 13:41:41.331  6792  6792 D BtGatt.GattService: mStartError = false
09-09 13:41:41.331  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
,09-09 13:41:41.331  1014  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:41.331  1014  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.331  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.331  1014  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.331  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.331  6792  6792 D HeadsetService: Received start request. Starting profile...
09-09 13:41:41.331  6792  6792 D HeadsetService: start()
,09-09 13:41:41.331  6792  6792 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 13:41:41.331  6792  6792 D HeadsetStateMachine: make
,09-09 13:41:41.331  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-09 13:41:41.331  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 13:41:41.331  6792  6832 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 13:41:41.341  6792  6792 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 13:41:41.341  1014  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:41.351  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.351  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.351  1014  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.351  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.351  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 13:41:41.351  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 13:41:41.351  6792  6832 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 13:41:41.351  1014  3126 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-09 13:41:41.351  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.351  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.351  1014  3126 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.351  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 13:41:41.351  1014  3124 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:41.351  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.361  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:41.361  1014  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.361  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.361  1014  1539 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 13:41:41.361  1014  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.361  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 13:41:41.361  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 13:41:41.361  6792  6832 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 13:41:41.361  1014  1539 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.361  1014  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.361  1014  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 13:41:41.361  6792  6792 I bluedroid: get_profile_interface handsfree
,09-09 13:41:41.361  1014  1326 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 13:41:41.361  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.361  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:41.361  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.361  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.371  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-09 13:41:41.371  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 13:41:41.371  6792  6832 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 13:41:41.371  1014  1483 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:41.371  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:41:41.371  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:41.371  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:41.371  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:41.371  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 13:41:41.371  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:41.381  6792  6832 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 13:41:41.381  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:41.381  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:41.381  6792  6832 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 13:41:41.381  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 13:41:41.381  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 13:41:41.381  6792  6832 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 13:41:41.381  6792  6832 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 13:41:41.381  6792  6832 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 13:41:41.381  6792  6832 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 13:41:41.381  6792  6832 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 13:41:41.381  6792  6792 I DualScoManager: Instantiating Dual Sco Manager
,09-09 13:41:41.381  6792  6792 I DualScoManager: Set HeadsetServiceHelper
,09-09 13:41:41.381  6792  6792 D BluetoothAtMessage: createCMTIContentObservers
,09-09 13:41:41.381  1014  1342 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-09 13:41:41.381  1014  1342 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:41.381  1014  1342 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:41.381  1014  1342 D SettingsProvider: selectionArgs: false
09-09 13:41:41.381  1014  1342 D SettingsProvider: selectionArgs: 1002
09-09 13:41:41.381  1014  1342 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:41.381  1014  1342 D SettingsProvider: ret = -1
,09-09 13:41:41.381  6792  6840 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 13:41:41.391  6792  6792 D HeadsetService: mStartError = false
09-09 13:41:41.391  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
,09-09 13:41:41.391  6792  6840 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-09 13:41:41.391  6792  6840 D HeadsetStateMachine: map size, before remove : 0
09-09 13:41:41.391  6792  6840 D HeadsetStateMachine: map size, after remove: 0
09-09 13:41:41.391  6792  6792 D A2dpService: Received start request. Starting profile...
09-09 13:41:41.391  6792  6792 D A2dpService: start()
,09-09 13:41:41.391  6792  6792 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 13:41:41.391  6792  6792 I bluedroid: get_profile_interface avrcp
,09-09 13:41:41.401  6792  6792 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 13:41:41.411  6792  6792 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 13:41:41.411  6792  6844 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 13:41:41.411  6792  6792 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 13:41:41.411  6792  6792 D A2dpStateMachine: make
,09-09 13:41:41.421  6792  6792 I bluedroid: get_profile_interface a2dp
09-09 13:41:41.421  6792  6846 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 13:41:41.421  6792  6792 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 13:41:41.421  6792  6792 D A2dpService: mStartError = false
09-09 13:41:41.421  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
,09-09 13:41:41.421  6792  6792 E BluetoothAdapterService(560083110): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-09 13:41:41.421  6792  6792 I BluetoothHidServiceJni: classInitNative: succeeds
09-09 13:41:41.421  6792  6845 D A2dpStateMachine: Enter Disconnected: -2
,09-09 13:41:41.421  6792  6792 D HidService: Received start request. Starting profile...
09-09 13:41:41.421  6792  6792 D HidService: start()
09-09 13:41:41.421  6792  6792 I bluedroid: get_profile_interface hidhost
09-09 13:41:41.421  6792  6792 D HidService: setHidService(): set to: null
09-09 13:41:41.421  6792  6792 D HidService: mStartError = false
09-09 13:41:41.421  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
,09-09 13:41:41.421  6792  6792 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 13:41:41.431  6792  6792 D HealthService: Received start request. Starting profile...
09-09 13:41:41.431  6792  6792 D HealthService: start()
,09-09 13:41:41.431  6792  6792 I bluedroid: get_profile_interface health
,09-09 13:41:41.431  6792  6792 D HealthService: mStartError = false
09-09 13:41:41.431  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
09-09 13:41:41.431  6792  6792 D HeadsetStateMachine: Try to query the phonestate on bind
,09-09 13:41:41.431  1424  1437 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 13:41:41.431  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-09 13:41:41.431  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 13:41:41.431  1424  1437 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 13:41:41.431  6792  6792 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 13:41:41.441  6792  6844 D BluetoothMediaBrowser: no now playing list
09-09 13:41:41.441  6792  6844 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 13:41:41.441  6792  6792 D PanService: Received start request. Starting profile...
09-09 13:41:41.441  6792  6792 D PanService: start()
09-09 13:41:41.441  6792  6792 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 13:41:41.441  6792  6792 I bluedroid: get_profile_interface pan
,09-09 13:41:41.441  6792  6792 D PanService: mStartError = false
09-09 13:41:41.441  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
,09-09 13:41:41.441  6792  6792 D HeadsetStateMachine: Proxy object connected
,09-09 13:41:41.441  6792  6792 D BluetoothMapService: Received start request. Starting profile...
,09-09 13:41:41.441  6792  6792 D BluetoothMapService: start()
,09-09 13:41:41.441  6792  6792 D BluetoothMapService: mStartError = false
,09-09 13:41:41.441  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
,09-09 13:41:41.441  6792  6792 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-09 13:41:41.441  6792  6840 D HeadsetStateMachine: Disconnected process message: 11
,09-09 13:41:41.441  6792  6792 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-09 13:41:41.451  6792  6792 D SapService: Received start request. Starting profile...
09-09 13:41:41.451  6792  6792 D SapService: start()
09-09 13:41:41.451  6792  6792 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 13:41:41.451  6792  6792 I bluedroid: get_profile_interface sap
09-09 13:41:41.451  6792  6792 D SapService: mStartError = false
09-09 13:41:41.451  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
09-09 13:41:41.451  6792  6792 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 13:41:41.451  6792  6792 D HeadsetPhoneState: Signal level : previous=0 curr=0
,09-09 13:41:41.451  6792  6792 E BluetoothAdapterService(560083110): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-09 13:41:41.451  6792  6792 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 13:41:41.451  6792  6792 D BluetoothA2dp: Proxy object connected
09-09 13:41:41.451  6792  6792 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-09 13:41:41.451  6792  6792 E BluetoothAdapterService(560083110): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 13:41:41.451  6792  6792 E BluetoothAdapterService(560083110): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 13:41:41.451  6792  6792 E BluetoothAdapterService(560083110): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-09 13:41:41.451  6792  6840 D HeadsetStateMachine: Disconnected process message: 18
09-09 13:41:41.451  6792  6840 D HeadsetStateMachine: Disconnected process message: 10
09-09 13:41:41.451  6792  6840 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 13:41:41.451  6792  6840 D HeadsetStateMachine: Disconnected process message: 11
,09-09 13:41:41.451  6792  6792 E BluetoothAdapterService(560083110): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-09 13:41:41.471  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:41.481  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 13:41:41.481  6792  6792 E BluetoothAdapterService(560083110): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-09 13:41:41.481  6792  6792 E BluetoothAdapterService(560083110): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 13:41:41.481  6792  6832 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-09 13:41:41.491  6792  6832 I bluedroid: enable
,09-09 13:41:41.491  6792  6832 I bt_hci_bdroid: init
,09-09 13:41:41.491  6792  6850 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-09 13:41:41.491  6792  6832 I bt_vendor: bt-vendor : init
,09-09 13:41:41.491  6792  6832 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 13:41:41.491  6792  6832 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 13:41:41.491  6792  6832 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
,09-09 13:41:41.491  6792  6832 D bt_userial_mct: userial_init
09-09 13:41:41.491  6792  6832 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 13:41:41.491  6792  6832 I bt_vendor: Starting hciattach daemon
,09-09 13:41:41.491  6792  6832 I bt_vendor: try to set false
,09-09 13:41:41.491  6792  6832 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
09-09 13:41:41.491  6792  6832 I bt_vendor: Starting hciattach daemon
09-09 13:41:41.491  6792  6832 I bt_vendor: try to set true
,09-09 13:41:41.511  6854  6854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-09 13:41:41.551  6860  6860 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-09 13:41:41.561  6861  6861 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 13:41:41.581  6863  6863 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 13:41:41.591  6864  6864 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-09 13:41:41.601  6865  6865 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-09 13:41:41.601  6866  6866 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-09 13:41:41.691   319   319 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-09 13:41:41.791  6869  6869 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
,09-09 13:41:41.801  6870  6870 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 13:41:41.851  6792  6832 I bt_vendor: bluetooth satus is on
09-09 13:41:41.851  6792  6852 D bt_userial_mct: userial_open(port:0)
09-09 13:41:41.851  6792  6852 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-09 13:41:41.851  6792  6852 I bt_vendor: Done intiailizing UART
09-09 13:41:41.851  6792  6852 I bt_vendor: Done intiailizing UART
09-09 13:41:41.851  6792  6852 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 13:41:41.851  6792  6852 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 13:41:41.851  6792  6872 D bt_userial_mct: Entering userial_read_thread()
,09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_SAP
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 13:41:41.861  6792  6850 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-09 13:41:41.951  6792  6850 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-09 13:41:41.951  6792  6850 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40a36e9 
,09-09 13:41:41.951  6792  6850 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40a36e9 
,09-09 13:41:41.961  6792  6835 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-09 13:41:41.961  6792  6835 E bt-btif : Calling BTA_HhEnable
,09-09 13:41:41.961  6792  6835 E bt-btif : BTA got event 0x122c,
09-09 13:41:41.961  6792  6835 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-09 13:41:41.961  6792  6835 E BluetoothServiceJni: populateRssiValuesNative
09-09 13:41:41.961  6792  6835 I bluedroid: getModelRssiValues
09-09 13:41:41.961  6792  6835 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 13:41:41.961  6792  6835 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 13:41:41.961  6792  6835 D BluetoothAdapterProperties: Name is: A5-1
,09-09 13:41:41.971  1014  1014 D SettingsProvider: name = bluetooth_name
,09-09 13:41:41.971  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.971  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.981  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:41.981  6792  6835 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 13:41:41.981  6792  6835 D BluetoothAdapterProperties: Scan Mode:20
09-09 13:41:41.981  6792  6835 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:41:41.981  6792  6835 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-09 13:41:41.981  6792  6835 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-09 13:41:41.981  6792  6835 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-09 13:41:41.981  6792  6835 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-09 13:41:41.981  6792  6835 E bt-btif : btif_sock_init: !vhci_init
09-09 13:41:41.981  6792  6835 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-09 13:41:41.981  6792  6872 E bt_mct  : hci lib postload completed
,09-09 13:41:41.981  6792  6835 D IOP_DB_BT: db_open: db_open : handle 3028484112l, read 13894 bytes onto local cache
,09-09 13:41:41.991  6792  6835 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-09 13:41:41.991  6792  6835 D IOP_DB_BT: db_query: result 1
,09-09 13:41:41.991  6792  6835 I         : iop_db_open: iop_db_open status 0
,09-09 13:41:41.991  6792  6835 D bte_conf: Device ID record 1 : primary
09-09 13:41:41.991  6792  6835 D bte_conf:   vendorId            = 0075
09-09 13:41:41.991  6792  6835 D bte_conf:   vendorIdSource      = 0001
09-09 13:41:41.991  6792  6835 D bte_conf:   product             = 0100
,09-09 13:41:41.991  6792  6835 D bte_conf:   version             = 0200
09-09 13:41:41.991  6792  6835 D bte_conf:   clientExecutableURL = 
09-09 13:41:41.991  6792  6835 D bte_conf:   serviceDescription  = 
09-09 13:41:41.991  6792  6835 D bte_conf:   documentationURL    = 
09-09 13:41:41.991  6792  6835 D bte_conf: bte_load_did_conf no section named DID2.
,09-09 13:41:41.991  6792  6835 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 13:41:41.991  6792  6832 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-09 13:41:41.991  6792  6832 D BluetoothAdapterProperties: ScanMode =  20
09-09 13:41:41.991  6792  6832 D BluetoothAdapterProperties: State =  11
,09-09 13:41:42.001  1014  1539 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 13:41:42.001  6792  6832 D BluetoothAdapterProperties: Setting state to 12
09-09 13:41:42.001  6792  6832 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 13:41:42.001  6792  6835 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 13:41:42.001  6792  6835 D BluetoothAdapterProperties: Scan Mode:21
,09-09 13:41:42.001  1014  1137 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-09 13:41:42.001  1014  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 13:41:42.001  1014  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 13:41:42.001  1014  1137 D SettingsProvider: selectionArgs: false
09-09 13:41:42.001  1014  1137 D SettingsProvider: selectionArgs: 1002
09-09 13:41:42.001  1014  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 13:41:42.001  1014  1137 D SettingsProvider: ret = -1
09-09 13:41:42.001  6792  6832 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 13:41:42.001  6792  6832 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 13:41:42.001  6792  6835 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 13:41:42.001  1014  1535 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:42.001  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.011  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.011  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.011  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.011  6146  6146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-09 13:41:42.021  6792  6832 D BluetoothAdapterService: Autoconnection is available 
09-09 13:41:42.021  6792  6832 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 13:41:42.021  6792  6832 D BluetoothAdapterService: starting service from this receiver
,09-09 13:41:42.021  2872  2930 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.021  1014  1326 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:42.021  2872  2930 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:42.021  6146  6154 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.021  6146  6154 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:42.021  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.021  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.021  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.021  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.021  6792  6832 I BluetoothAdapterState: Entering On State from state = 11
,09-09 13:41:42.021  6146  6146 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-09 13:41:42.021  1294  6785 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:41:42.031  1294  6785 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:42.031  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:41:42.031  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.031  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.031  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.031  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:42.031  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.031  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.031  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.031  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.031  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.031  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.031  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:42.031  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.031  1294  1294 D BluetoothA2dp: Proxy object connected
09-09 13:41:42.031  1294  1294 D A2dpProfile: Bluetooth service connected
,09-09 13:41:42.041  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:42.041  1424  1447 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:42.041  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:42.041  6792  6792 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
09-09 13:41:42.041  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:42.041  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.041  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.041  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.041  1424  1447 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:41:42.051  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:42.051  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:42.051  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:41:42.051  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:42.051  1294  1308 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 13:41:42.051  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:42.051  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.051  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.051  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.051  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.051  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.051  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.051  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:42.051  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice,
09-09 13:41:42.051  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.051  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-09 13:41:42.051  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.051  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.061  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:42.061  6792  6792 I BluetoothPbapService: Handler(): got msg=1
,09-09 13:41:42.061  1294  1311 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 13:41:42.061  1014  3126 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 13:41:42.061  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-09 13:41:42.061  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.061  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.061  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.061  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.071  2872  2881 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
09-09 13:41:42.071  6792  6877 V BluetoothPbapService: PBAP Service initSocket try: 0
09-09 13:41:42.071  1294  1294 D BluetoothInputDevice: Proxy object connected
09-09 13:41:42.071  1294  1294 D HidProfile: Bluetooth service connected
09-09 13:41:42.071  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:42.071  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.071  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.071  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.071  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.071  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.071  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.071  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:42.071  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:42.071  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:42.071  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.071  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.071  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.071  2872  2881 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:41:42.071  1424  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 13:41:42.071  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.071  1294  1294 D BluetoothPbap: Proxy object connected
09-09 13:41:42.071  1294  1294 D PbapServerProfile: Bluetooth service connected
,09-09 13:41:42.081  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:42.081  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:42.081  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.081  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.081  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.081  1424  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:41:42.081  6792  6875 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:41:42.081  1294  1311 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:42.081  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:41:42.081  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:42.081  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.081  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.081  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.091  1294  1311 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:41:42.091  6792  6877 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:42.091  6792  6877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:42.091  6758  6769 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.091  6758  6769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:42.091  1014  1043 D BluetoothPan: Binding service...
,09-09 13:41:42.091  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 13:41:42.091  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.091  6792  6801 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.091  6792  6801 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:42.091  6792  6877 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-09 13:41:42.091  6792  6877 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:42.091  6792  6877 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:42.091  6792  6877 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15782253
09-09 13:41:42.091  1294  1294 D HeadsetProfile: Bluetooth service connected
,09-09 13:41:42.091  6792  6877 D BluetoothSocket: channel: 19
,09-09 13:41:42.091  6792  6877 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-09 13:41:42.091  1294  1308 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 13:41:42.091  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 13:41:42.091  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-09 13:41:42.091  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.091  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.091  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.091  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.101  1453  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 13:41:42.101  1294  1294 D BluetoothMap: Proxy object connected
09-09 13:41:42.101  1294  1294 D MapProfile: Bluetooth service connected
09-09 13:41:42.101  1294  1294 D BluetoothMap: getConnectedDevices()
,09-09 13:41:42.101  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 13:41:42.101  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:42.101  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.101  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.101  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.101  1453  1468 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 13:41:42.101  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.101  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:42.101  1424  1447 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.101  1424  1447 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:42.101  1453  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 13:41:42.101  1453  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:42.101  1294  6785 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.101  1294  6785 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:42.111  1424  6784 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:42.111  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 13:41:42.111  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 13:41:42.111  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.111  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.111  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.111  1424  6784 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 13:41:42.111  1441  2786 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 13:41:42.111  1441  2786 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:42.111  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:41:42.111  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-09 13:41:42.111  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 13:41:42.111  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.111  1014  1014 D BluetoothA2dp: Proxy object connected
,09-09 13:41:42.121  1294  1308 D BluetoothPan: Binding service...
,09-09 13:41:42.121  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-09 13:41:42.121  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.121  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.121  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.121  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.121  1173  1942 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.121  1173  1942 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 13:41:42.121  1946  2842 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 13:41:42.121  1946  2842 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 13:41:42.121  1294  6785 D Bluetoothsap: onBluetoothStateChange: up=true
,09-09 13:41:42.121  1294  6785 D Bluetoothsap: Binding service...
09-09 13:41:42.121  1294  1294 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 13:41:42.121  1294  1294 D PanProfile: Bluetooth service connected
,09-09 13:41:42.121  1294  6785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 13:41:42.121  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 13:41:42.121  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.121  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.121  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.121  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.121  1294  6785 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-09 13:41:42.121  2872  2930 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 13:41:42.131  2872  2930 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 13:41:42.131  1294  1294 D Bluetoothsap: BluetoothSAP Proxy object connected
09-09 13:41:42.131  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 13:41:42.131  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.131  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.131  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.131  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-09 13:41:42.131  1294  1294 D SapProfile: Bluetooth service connected
09-09 13:41:42.131  1294  1294 D Bluetoothsap: getConnectedDevices()
,09-09 13:41:42.131  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 13:41:42.131  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
09-09 13:41:42.131  2872  2872 D BluetoothA2dp: Proxy object connected
,09-09 13:41:42.131  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:42.131  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-09 13:41:42.131  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 13:41:42.141  1424  1424 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1d3d43de, true
,09-09 13:41:42.141  1424  1424 D BluetoothHeadset: registerMessageListener
09-09 13:41:42.141  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-09 13:41:42.141  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 13:41:42.141  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:42.141  1173  1173 D BluetoothTile:  getBluetoothState : 12
,09-09 13:41:42.141  1173  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:41:42.141  1774  1774 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-09 13:41:42.141  1294  1294 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 13:41:42.151  1173  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:41:42.151  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:42.151  1014  1539 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:42.151  1014  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.151  6792  6878 D HeadsetService: registerMessageListener
,09-09 13:41:42.151  6792  6878 D HeadsetService: registerMessageListener
09-09 13:41:42.151  6792  6840 D HeadsetStateMachine: Disconnected process message: 70
,09-09 13:41:42.151  6792  6840 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1dce1790
,09-09 13:41:42.151  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-09 13:41:42.151  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 13:41:42.151  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:42.161  1014  1539 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.161  1014  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:42.161  1014  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:42.161  1014  1214 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:41:42.161  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:42.161  1173  1704 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 13:41:42.161  1294  1294 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 13:41:42.161  1294  1294 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 13:41:42.161  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 13:41:42.161  1294  1294 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 13:41:42.161  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-09 13:41:42.161  1294  1294 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-09 13:41:42.161  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-09 13:41:42.161  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 13:41:42.161  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 13:41:42.161  6792  6880 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 13:41:42.171  6792  6840 D HeadsetStateMachine: Disconnected process message: 9
,09-09 13:41:42.171  6792  6840 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-09 13:41:42.181  1294  1294 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 13:41:42.181  1014  3126 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 13:41:42.181  1014  3126 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-09 13:41:42.181  6792  6880 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:42.181  6792  6880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:42.181  1014  3126 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.181  1014  3126 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.181   282   673 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 13:41:42.181   282   673 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 13:41:42.181   282   673 V voice   : voice_set_parameters: exit with code(-2)
09-09 13:41:42.181   282   673 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 13:41:42.181   282   673 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 13:41:42.181   282   673 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 13:41:42.181   282   673 V audio_hw_primary: adev_set_parameters: exit
09-09 13:41:42.181  6792  6840 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 13:41:42.181  1014  3126 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 13:41:42.191  6792  6880 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-09 13:41:42.191  6792  6880 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:42.191  6792  6880 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:42.191  6792  6880 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@54e1889
,09-09 13:41:42.191  6792  6880 D BluetoothSocket: channel: 5
,09-09 13:41:42.201  1294  1294 D DockEventReceiver: finishStartingService: stopping service
,09-09 13:41:42.201  1294  1294 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 13:41:42.201  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:42.201  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:42.201  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:42.201  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 13:41:42.201  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:42.201  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23298184 removed from the list
09-09 13:41:42.201  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:42.201  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3a8d6d removed from the list
,09-09 13:41:42.201  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:42.201  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:42.211  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:42.211  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bedaa33 added. We now have 3 listener(s)
,09-09 13:41:42.211  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 13:41:42.211  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 13:41:42.211  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:42.211  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:42.211  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:42.211  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:42.211  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47f31f0 added. We now have 3 listener(s)
09-09 13:41:42.211  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:42.211  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 13:41:42.221  6792  6792 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
,09-09 13:41:42.221  6792  6792 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 13:41:42.221  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:42.221  1014  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 13:41:42.221  1014  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.221  1014  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.221  1014  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.221  1014  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 13:41:42.231  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:42.231  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.231  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.231  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:42.231  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.231  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:42.231  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:42.231  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:42.231  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:42.231  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 13:41:42.231  1014  1500 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 13:41:42.231  1014  1500 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:41:42.231  1014  1500 D SecContentProvider2: mCursor = null
,09-09 13:41:42.231  1014  1500 D WifiService: setWifiEnabled: false pid=6146, uid=10155
,09-09 13:41:42.231  1014  1500 D SettingsProvider: name = wifi_on
,09-09 13:41:42.241  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:42.241  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:42.241  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 13:41:42.241  6616  6616 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:42.241  6616  6616 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 13:41:42.251  6616  6616 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-09 13:41:42.251  6616  6616 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:42.251  1946  1946 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 13:41:42.251  1014  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 13:41:42.251  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:42.251  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.251  1014  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:42.251  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:42.251  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:42.261  1014  1539 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 13:41:42.271  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 13:41:42.271  1946  1946 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 13:41:42.271  1946  6891 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 13:41:42.271  1014  1342 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:42.271  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.271  1014  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:42.271  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:42.281  6792  6892 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:41:42.281  6792  6892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:42.291  1014  1214 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 13:41:42.291  6792  6892 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-09 13:41:42.291  6792  6892 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:42.291  6792  6892 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:42.291  6792  6892 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ff6b445
09-09 13:41:42.291  6792  6892 D BluetoothSocket: channel: 12
09-09 13:41:42.291  6792  6892 I BtOppRfcommListener: Accept thread started.
,09-09 13:41:42.291  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.291  1014  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:42.291  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:42.301  1946  6891 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-09 13:41:42.421  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-09 13:41:42.421  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:42.421   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:42.431  1946  6724 V NativeCrypto: Read error: ssl=0xb8475e60: I/O error during system call, Connection timed out
,09-09 13:41:42.431  1946  6724 V NativeCrypto: SSL shutdown failed: ssl=0xb8475e60: I/O error during system call, Broken pipe
09-09 13:41:42.431  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:42.431  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:42.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:41:42.431  1946  6724 E GCM     : Wifi connection closed with errorCode 20
09-09 13:41:42.441  1014  1131 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:42.441  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:42.441  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 13:41:42.441  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 3
,09-09 13:41:42.441  1014  1326 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10012
,09-09 13:41:42.441  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:41:42.441  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.441  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.441  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 13:41:42.441  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:42.441  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-09 13:41:42.451  1014  6664 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:42.451  1014  6664 I qtaguid : Tagging socket 404 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
,09-09 13:41:42.461  1014  6664 I qtaguid : Untagging socket 404
,09-09 13:41:42.461  1014  6664 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 13:41:42.471  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:42.471  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:42.471  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:42.471  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:42.471  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.471  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:42.471  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
,09-09 13:41:42.481  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
09-09 13:41:42.481  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 13:41:42.481  1014  3124 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:42.481  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:42.481  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.481  1014  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.481  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:42.481  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 13:41:42.481  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,09-09 13:41:42.481  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:42.481  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-09 13:41:42.481  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:42.491  3632  3632 I Hs20UtilService: Starting #18
,09-09 13:41:42.491  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:42.491   277   992 D EnterpriseController: uids 1000
09-09 13:41:42.491   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:42.491   277   992 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-09 13:41:42.491  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.491  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:42.491  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:42.491  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 13:41:42.491  1014  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-09 13:41:42.491  1014  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-09 13:41:42.501  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 13:41:42.501  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 13:41:42.501  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:42.501  1014  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:42.501  1014  6664 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:42.501  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-09 13:41:42.501  1014  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 13:41:42.501  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:42.501  1014  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
09-09 13:41:42.501  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:42.501  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:42.501  1453  1453 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
09-09 13:41:42.501  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
09-09 13:41:42.501  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:41:42.501  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:41:42.501  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-09 13:41:42.501  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:42.501  1014  1044 D WifiDisplayController: disconnect
09-09 13:41:42.501  1014  1044 D WifiDisplayController: updateConnection
09-09 13:41:42.501  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:42.501  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:42.511  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:42.511  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:42.511  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 13:41:42.511  1014  1500 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:42.511  1014  1124 D WifiP2pService: P2pDisablingState
,09-09 13:41:42.511  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 13:41:42.511  1014  1124 D WifiP2pService: p2p socket connection lost
,09-09 13:41:42.511  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 13:41:42.521  1014  1125 E WifiNative-wlan0: do suspend true
09-09 13:41:42.521  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 13:41:42.521  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:42.521  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:42.521  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:42.521  1014  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 13:41:42.521  1014  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 13:41:42.521  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:42.521  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:42.521  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 13:41:42.521  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:41:42.521   277   996 D CommandListener: Clearing all IP addresses on wlan0
09-09 13:41:42.521  1014  1124 D WifiP2pService: P2pDisabledState
09-09 13:41:42.521  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-09 13:41:42.521  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-09 13:41:42.521  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 13:41:42.521  1014  1132 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:42.521  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-09 13:41:42.521  1014  1122 V NetworkStats: updateIfacesLocked()
09-09 13:41:42.521  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:42.521  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:42.521  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:42.521  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:42.521  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:42.521  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:42.521  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:42.521  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:42.521  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:42.521  1014  1122 V NetworkStats: performPollLocked() took 4ms
,09-09 13:41:42.531  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-09 13:41:42.531  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:42.531  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:42.531  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:41:42.531  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,09-09 13:41:42.531  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:42.531  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:41:42.531  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:42.531  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:42.531  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-09 13:41:42.531  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:42.541  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:42.541  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.541  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:42.541  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 13:41:42.541  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:42.541  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:42.551  6616  6616 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-09 13:41:42.551  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:42.551  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:42.551  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.551  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.551  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.551  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:42.551  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.551  1014  3124 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:42.551  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:41:42.561  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:42.561  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:42.571  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:42.571  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:42.571  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.571  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.571  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.571  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:42.571  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:42.571  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 13:41:42.571  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:42.571  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:42.571  1173  1173 D HotspotTile: onReceive : 0, 0
,09-09 13:41:42.571  1294  1294 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:42.571  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:42.571  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.571  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.571  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:42.571  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.571  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:42.571  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:42.571  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:42.581  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:42.581  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:42.581  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.581  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.581  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:42.581  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.581  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:42.581  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:42.581  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:42.581  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:42.581  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:42.581  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:42.591  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,09-09 13:41:42.591  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:42.591  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:42.591  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 13:41:42.591  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:42.591  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:42.591  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:42.591  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:42.591  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 13:41:42.591  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:42.591  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:42.591  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:42.591  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:42.591  6354  6354 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:42.591  6354  6354 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:41:42.591  6354  6354 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:42.601  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:42.601  6369  6369 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:42.611  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.611  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:42.611  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.621  1014  3125 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:42.621  1014  3125 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:42.621  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.621  1014  3125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.621  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:42.621  3632  3632 I Hs20UtilService: Starting #19
,09-09 13:41:42.621  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:42.631  6616  6616 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:42.631  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:42.631  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:42.631  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:42.631  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:42.631  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:42.631  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:42.631  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:42.641  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.641  1014  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.641  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.651  1014  3124 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-09 13:41:42.651  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.651  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 13:41:42.651  1014  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.651  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:42.651  3632  3632 I Hs20UtilService: Starting #20
,09-09 13:41:42.651  3632  3664 I Hs20UtilService: Message received 5011
,09-09 13:41:42.661  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:42.661  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:42.661  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:42.661  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:42.671  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.671  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.671  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.681  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.681  1014  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.681  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-09 13:41:42.681  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.681  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.681  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.681  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.681  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.681  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.681  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.681  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.681  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:41:42.691  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.691  6616  6616 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 13:41:42.691  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:42.691  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:42.691  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:42.691  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.691  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.691  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.691  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.691  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.691  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:41:42.691  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.691  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:41:42.691  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.691  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.701  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.701  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.701  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.701  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.701  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:41:42.701  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.701  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:42.701  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-09 13:41:42.701  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.701  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-09 13:41:42.701  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.701  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.701  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.701  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.701  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.711  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.711  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:41:42.711  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.711  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.711  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.711  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-09 13:41:42.711  6616  6616 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 13:41:42.711  6616  6616 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 13:41:42.711  6616  6616 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 13:41:42.711  6616  6616 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 13:41:42.711  6616  6616 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-09 13:41:42.711  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-09 13:41:42.711  1014  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-09 13:41:42.711  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:42.711  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:42.711  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:42.711  1014  1132 D Tethering: InitialState.processMessage what=4
09-09 13:41:42.711  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.711  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:42.711  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.711  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.711  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.711  1014  1132 E Tethering: No numeric data
09-09 13:41:42.711  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:42.711  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:42.711  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 13:41:42.721  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:42.721  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:42.721  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:42.721  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 13:41:42.721  1014  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 13:41:42.721  1014  1132 D Tethering: clearTetheredNotification()
,09-09 13:41:42.721  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:42.721  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:42.721  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 13:41:42.721  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:41:42.721  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 13:41:42.721  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:42.721  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.721  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.721  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.721  1014  1122 V NetworkStats: performPollLocked() took 6ms
,09-09 13:41:42.731  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:42.731  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-09 13:41:42.731  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.731  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.731  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:42.731  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:42.731  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.731  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.731  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.741  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:42.741  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.741  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.741  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:42.741  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:42.741  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 13:41:42.751  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:42.751  1014  1342 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 13:41:42.751  1014  1342 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 13:41:42.751  1014  1342 D SecContentProvider2: mCursor = null
,09-09 13:41:42.751  1014  1342 D WifiService: setWifiEnabled: true pid=6146, uid=10155
,09-09 13:41:42.761  1014  1342 W ActivityManager: Permission Denial: getCurrentUser() from pid=6146, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 13:41:42.761  1014  1342 W WifiService: Failed getting userId using ActivityManagerNative
09-09 13:41:42.761  1014  1342 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6146, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 13:41:42.761  1014  1342 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 13:41:42.761  1014  1342 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 13:41:42.761  1014  1342 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 13:41:42.761  1014  1342 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 13:41:42.761  1014  1342 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 13:41:42.761  1014  1342 D SettingsProvider: name = wifi_on
,09-09 13:41:42.911  6616  6616 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:43.001  6616  6616 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 13:41:43.001  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:43.001  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:43.001  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:43.021  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:43.021  1014  1014 I ApplicationPolicy: updateDataUsageMap
,09-09 13:41:43.031  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:43.031  3144  3144 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-09 13:41:43.041  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.051  3144  3144 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-09 13:41:43.051  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.061  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.071  5792  5792 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:41:43.071  5792  5792 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:41:43.071  5792  5792 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:41:43.071  5792  5792 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:43.071  1014  1539 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-09 13:41:43.071  1014  1539 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:41:43.071  5792  6915 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 13:41:43.071  6403  6403 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 13:41:43.091  1727  1727 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:43.101  1727  1727 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:41:43.101  1727  1727 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,09-09 13:41:43.101  1727  1727 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-09 13:41:43.101  1727  1727 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:43.111  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:41:43 GMT+02:00 2016
,09-09 13:41:43.111  1014  1342 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:43.111  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 13:41:43.111  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 13:41:43.111  1014  1326 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:41:43.111  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
09-09 13:41:43.111  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:43.111  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:43.111  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:43.111  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:41:43.121  6312  6312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:43.121  1727  1727 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-09 13:41:43.121  1312  1589 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,09-09 13:41:43.121  1014  1137 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:43.121  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:41:43.121  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:43.121  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-09 13:41:43.121  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:43.121  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:43.121  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:43.121  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:43.121  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:43.121  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-09 13:41:43.121  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:43.121  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:43.131  1727  1727 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-09 13:41:43.131  1294  1294 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:43.131  1173  1173 D HotspotTile: onReceive : 1, 0
,09-09 13:41:43.131  1946  2129 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:43.131  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.131  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 13:41:43.131  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.131  3666  3666 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:41:43.131  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:43.141  1727  1727 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-09 13:41:43.141  3666  3666 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:41:43.141  3666  6916 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:41:43.141  3666  6916 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:41:43.151  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:43.151  6470  6470 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-09 13:41:43.151  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 13:41:43.151  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:43.151  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:43.151  3666  6916 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 13:41:43.161  3666  6916 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-09 13:41:43.161  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-09 13:41:43.181  1014  1342 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:43.181  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:41:43.181  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:43.181  1014  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:43.181  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:43.181  3205  6917 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 13:41:43.191  5840  5840 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 13:41:43.191  3205  6917 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-09 13:41:43.191  3205  6917 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-09 13:41:43.191  3205  6917 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-09 13:41:43.201  3798  3798 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 13:41:43.201  6042  6042 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-09 13:41:43.201  6042  6042 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 13:41:43.201  6042  6042 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:43.201  1014  1535 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 13:41:43.201  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 13:41:43.201  3205  6917 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
09-09 13:41:43.201  3798  4542 I iu.UploadsManager: num queued entries: 0
09-09 13:41:43.201  3798  4542 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:43.201  3798  4542 I iu.SyncManager: NEXT; no task
,09-09 13:41:43.201  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:43.201  1014  1535 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:43.201  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:41:43.211  5840  6918 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 13:41:43.211  6642  6642 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:43.211  6042  6042 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:41:43.211  6042  6042 I SA      : [OR] == isSIMCardReady false ==
,09-09 13:41:43.221  6642  6642 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-09 13:41:43.221  6642  6642 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:41:43.221  6042  6042 I SA      : [SCU] == networkStateCheck == false
09-09 13:41:43.221  6042  6042 I SA      : [OR] onReceive END
,09-09 13:41:43.231  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:43.561  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:43.561  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:43.561  6586  6586 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 13:41:43.561  6586  6586 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 13:41:43.561  1014  3125 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,09-09 13:41:43.561  1014  1535 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:43.561  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:43.561  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:43.561  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:43.561  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:43.571  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:43.571  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:43.571  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:43.571  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-09 13:41:43.571  3632  3632 I Hs20UtilService: Starting #21
,09-09 13:41:43.571  3632  3664 I Hs20UtilService: Message received 5011
,09-09 13:41:43.681   290   290 E SMD     : DCD OFF,
,09-09 13:41:43.821  1014  1041 D Tethering: interfaceRemoved wlan0
,09-09 13:41:43.821  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 13:41:44.051  1014  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:44.051  1014  1541 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4203, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 13:41:44.051  1014  1541 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-09 13:41:44.051  1014  1541 D BatteryService: stay LED for charging
09-09 13:41:44.051  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:44.061  1014  1014 I MotionRecognitionService: Plugged
,09-09 13:41:44.061  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:44.061  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:44.061  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:44.061  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:44.061  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,09-09 13:41:44.081  6792  6792 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:41:44.081  6792  6840 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:44.091  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:44.091  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:44.091  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:44.091  1014  1041 D Tethering: interfaceRemoved p2p0
,09-09 13:41:44.091  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 13:41:44.391  1014  1137 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-09 13:41:44.391  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:41:44.391  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:44.391  1014  1137 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:44.391  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:41:44.401  5921  5921 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,09-09 13:41:44.401  5921  5921 D PreloadUpdateManagerStateMachine: exit::IDLE
,09-09 13:41:44.411  5921  5921 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:41:44.411  5921  5921 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,09-09 13:41:44.421  5921  5921 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,09-09 13:41:44.421  5921  5921 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-09 13:41:44.421  5921  5921 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:41:44.421  5921  5921 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-09 13:41:44.951  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 13:41:44.951  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 13:41:45.171  1014  2730 D SSRM:n  : SIOP:: AP = 370
,09-09 13:41:45.311  1014  1041 D Tethering: interfaceAdded wlan0
,09-09 13:41:45.311  1014  1132 E Tethering: No numeric data
,09-09 13:41:45.311  1014  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 13:41:45.311  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:45.311  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:45.311  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:45.321  1014  1132 D Tethering: clearTetheredNotification()
,09-09 13:41:45.321  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:41:45.321  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-09 13:41:45.321  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:45.321  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-09 13:41:45.321  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:45.321  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:45.321  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:45.331  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:41:45.331  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:45.331  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:45.331  1014  1132 D Tethering: InitialState.processMessage what=4
,09-09 13:41:45.331  1014  1132 E Tethering: No numeric data
,09-09 13:41:45.331  1014  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 13:41:45.331  1014  1132 D Tethering: clearTetheredNotification()
,09-09 13:41:45.331  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:45.331  1173  1173 D HotspotTile: updateTetherState():false, false
,09-09 13:41:45.341  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:45.341  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 13:41:45.341  1014  1041 D Tethering: interfaceAdded p2p0
,09-09 13:41:45.341  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring,
,09-09 13:41:45.341  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-09 13:41:45.341  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:45.351  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:41:45.351  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 13:41:45.351  1014  1122 V NetworkStats: performPollLocked() took 14ms
09-09 13:41:45.351  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:41:45.351  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:45.351   277   996 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-09 13:41:45.351   277   996 D SoftapController: Softap fwReload - Ok
09-09 13:41:45.351  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:45.351  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:45.351   277   996 D CommandListener: Setting iface cfg
09-09 13:41:45.351   277   996 D CommandListener: Trying to bring down wlan0
,09-09 13:41:45.361   277   996 D CommandListener: Clearing all IP addresses on wlan0
,09-09 13:41:45.361  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 13:41:45.371  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 13:41:45.371  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:41:45.371  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 13:41:45.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:45.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:45.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:45.371  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:45.381  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:45.381  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 13:41:45.381  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:45.381  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 13:41:45.381  1173  1173 D HotspotTile: onReceive : 2, 0
,09-09 13:41:45.391  1294  1294 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:45.391  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:45.391  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:45.391  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:45.401  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-09 13:41:45.401  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:45.401  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:45.401  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:45.401  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:45.401  3632  3632 I Hs20UtilService: Starting #22
,09-09 13:41:45.411  3632  3664 I Hs20UtilService: Message received 5011
,09-09 13:41:45.411  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 13:41:45.411  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:45.411  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:45.411  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:45.431  6929  6929 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-09 13:41:45.431  6929  6929 I wpa_supplicant: Successfully initialized wpa_supplicant
09-09 13:41:45.431  6929  6929 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 13:41:45.441  6929  6929 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-09 13:41:45.441   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6929
09-09 13:41:45.441   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-09 13:41:45.441  6929  6929 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 13:41:45.441  6929  6929 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:45.441  6929  6929 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 13:41:45.441  6929  6929 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-09 13:41:45.441   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6929
09-09 13:41:45.441   378   378 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-09 13:41:45.591   378   378 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-09 13:41:45.601  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,09-09 13:41:45.661  6929  6929 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 13:41:45.661  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 13:41:45.671  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 13:41:45.671   378   378 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6929
09-09 13:41:45.671   378   378 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-09 13:41:45.671  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 13:41:45.671  6929  6929 I wpa_supplicant: ssSupport state is = 1,
09-09 13:41:45.681  6929  6929 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:45.681  6929  6929 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:45.681  6929  6929 E wpa_supplicant: SIM READ ERROR
09-09 13:41:45.681  6929  6929 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:45.681  6929  6929 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:45.681  6929  6929 E wpa_supplicant: SIM READ ERROR,
09-09 13:41:45.681  6929  6929 I wpa_supplicant: Blacklist: Clear (all) 
09-09 13:41:45.681  6929  6929 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:41:45.681  6929  6929 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:41:45.681  6929  6929 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:45.681  6929  6929 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 13:41:45.681  6929  6929 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:45.681  6929  6929 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-09 13:41:45.681  6929  6929 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 13:41:45.681  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 13:41:45.681  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:45.681  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:45.741  6929  6929 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 13:41:45.951  6929  6929 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 13:41:45.951  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,09-09 13:41:45.961  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 13:41:45.961   378   378 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6929
09-09 13:41:45.961   378   378 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-09 13:41:45.971  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running,
09-09 13:41:45.971  6929  6929 I wpa_supplicant: ssSupport state is = 1
09-09 13:41:45.971  6929  6929 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 13:41:45.971  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 13:41:45.981  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 13:41:45.981   378   378 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6929
09-09 13:41:45.981   378   378 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-09 13:41:45.981  6929  6929 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 13:41:45.981  6929  6929 I wpa_supplicant: ssSupport state is = 1
,09-09 13:41:45.981  6929  6929 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:45.981  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:45.981  6929  6929 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 13:41:45.981  6929  6929 E wpa_supplicant: SIM READ ERROR
09-09 13:41:45.981  6929  6929 I wpa_supplicant: wpa_default_ap_write_once
09-09 13:41:45.981  6929  6929 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 13:41:45.981  6929  6929 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-09 13:41:45.981  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:45.991  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 13:41:45.981  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
09-09 13:41:45.991  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:45.991  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:46.031  6929  6929 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 13:41:46.031  6929  6929 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 13:41:46.091  6929  6929 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 13:41:46.091  6929  6929 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 13:41:46.091  6929  6929 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 13:41:46.101  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-09 13:41:46.101  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-09 13:41:46.101  6929  6929 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-09 13:41:46.101  6929  6929 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 13:41:46.101  6929  6929 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 13:41:46.101  6929  6929 E wpa_supplicant: SIM READ ERROR
09-09 13:41:46.101  6929  6929 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 13:41:46.111  6929  6929 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 13:41:46.131  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210],
09-09 13:41:46.131  6929  6929 I wpa_supplicant: Skip scan - bUseNetwork false
09-09 13:41:46.131  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
09-09 13:41:46.131  1173  1704 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 13:41:46.131  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:46.131  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:46.131  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:46.131  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:46.131  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-09 13:41:46.131  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:46.131  1173  1173 D HotspotTile: onReceive : 3, 0
09-09 13:41:46.131  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:46.131  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 13:41:46.131  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-09 13:41:46.141  1294  1294 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 13:41:46.141  1014  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:46.141  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:46.141  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:46.141  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:46.141  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:46.141  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:46.141  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:46.141  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:46.141  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:46.141  1014  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:46.151  1014  1125 E WifiConfigStore: Not a HS20
09-09 13:41:46.151  1014  1483 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:46.151  1014  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:46.151  1014  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:46.151  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:46.151  3632  3632 I Hs20UtilService: Starting #23
,09-09 13:41:46.151  3632  3664 I Hs20UtilService: Message received 5011
,09-09 13:41:46.151  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:46.151  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:46.151  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:46.151  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:46.151  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:46.151  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:46.151  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:46.151  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:46.151  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 13:41:46.151  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 13:41:46.161  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:46.161  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:46.161  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:46.161  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
09-09 13:41:46.161  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:46.161  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 13:41:46.161  6929  6929 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 13:41:46.161  6929  6929 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 13:41:46.161  6929  6929 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 13:41:46.161  6929  6929 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 13:41:46.161  6929  6929 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 13:41:46.161  6929  6929 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 13:41:46.161  6929  6929 I wpa_supplicant: First Scan Start
,09-09 13:41:46.161  6929  6929 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 13:41:46.161  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:46.161  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:46.161  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:46.161  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:46.161  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:46.161  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:46.161  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:46.161  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 13:41:46.161  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 13:41:46.171  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-09 13:41:46.171  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 13:41:46.171  1014  1125 I WifiNative-HAL: startHal
09-09 13:41:46.171  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9c71588c
09-09 13:41:46.171  1014  1125 I WifiNative-HAL: Could not start hal
,09-09 13:41:46.171  6312  6312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 13:41:46.171  1014  1125 E WifiNative-wlan0: do suspend true,
,09-09 13:41:46.181  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
09-09 13:41:46.181  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 13:41:46.181  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 13:41:46.181  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:46.181  1014  1148 I WifiNative-HAL: startHal
09-09 13:41:46.181  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9d8c79bc
09-09 13:41:46.181  1014  1148 I WifiNative-HAL: Could not start hal
09-09 13:41:46.181  1014  1148 E WifiScanningService: could not start HAL
09-09 13:41:46.181  1014  1014 D RttService: SCAN_AVAILABLE : 3
,09-09 13:41:46.181  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 13:41:46.181   277   996 D CommandListener: Setting iface cfg
09-09 13:41:46.181  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-09 13:41:46.181  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:41:46.181  1014  1124 D WifiP2pService: P2pEnablingState
09-09 13:41:46.181  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-09 13:41:46.181  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 13:41:46.181   277   996 D CommandListener: Trying to bring up p2p0
09-09 13:41:46.181  1014  1124 D WifiP2pService: P2p socket connection successful
09-09 13:41:46.181  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
09-09 13:41:46.181  1014  1124 D WifiP2pService: P2pEnabledState
09-09 13:41:46.181  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 13:41:46.181  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 13:41:46.181  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-09 13:41:46.181  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 13:41:46.181  1014  1131 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:46.181  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 13:41:46.181  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 13:41:46.181  6929  6929 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:41:46.181  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:46.191  1014  1044 D WifiDisplayController: disconnect
09-09 13:41:46.191  1014  1044 D WifiDisplayController: updateConnection
09-09 13:41:46.191  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 13:41:46.191  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:46.191  6929  6929 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:41:46.191  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 13:41:46.191  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 13:41:46.191  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 13:41:46.191  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 13:41:46.191  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 13:41:46.191  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:46.191  6929  6929 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-09 13:41:46.191  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 13:41:46.201  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-09 13:41:46.201  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 13:41:46.201  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:46.201  1014  1125 D SecContentProvider2: mCursor = null
09-09 13:41:46.201  1014  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
09-09 13:41:46.201  1014  1342 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:41:46.201  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-09 13:41:46.201  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  secondary type: null,
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  wps: 0
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  grpcapab: 0
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  devcapab: 0
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  status: 3
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  wfdInfo: null
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  groupownerAddress: null
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  GOdeviceName: null
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  interfaceAddress: 
09-09 13:41:46.201  1014  1044 D WifiDisplayController:  SConnectInfo : null
09-09 13:41:46.201  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:46.201  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:46.201  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:46.201  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:46.201  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:46.201  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:46.201  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:46.201  6354  6354 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:46.211  6354  6354 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 13:41:46.211  6354  6354 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 13:41:46.211  6369  6369 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 13:41:46.221  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 13:41:46.221  1014  1124 D WifiP2pService: InactiveState
,09-09 13:41:46.221  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:41:46.221  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:41:46.221  6929  6929 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 13:41:46.221  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-09 13:41:46.221  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 13:41:46.271  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 13:41:46.271  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:46.271  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:46.271  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:46.271  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:46.271  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bedaa33 removed from the list
09-09 13:41:46.271  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:46.271  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47f31f0 removed from the list
09-09 13:41:46.271  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:46.271  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:46.301  6146  6936 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-09 13:41:46.301  6146  6936 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:41:46.331  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 13:41:46.331  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 13:41:46.331  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 13:41:46.681   290   290 E SMD     : DCD OFF,
,09-09 13:41:46.781   277   992 D EnterpriseController: uids 10155
,09-09 13:41:46.781   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:46.781   277   992 D Netd    : getNetworkForDns: using netid 0 for uid 10155
,09-09 13:41:46.791  6146  6936 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 13:41:46.791  6146  6936 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:46.791  6146  6936 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes,
09-09 13:41:46.791  6146  6936 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:46.791  6146  6936 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:41:46.791  6146  6938 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-09 13:41:46.791  6146  6938 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:46.791  6146  6938 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:46.791  6146  6938 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:46.791  6146  6938 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:41:46.791  6146  6941 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1229, name: OutgoingSocketThread/Sender)
,09-09 13:41:46.791  6146  6942 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1230, name: OutgoingSocketThread/Receiver)
09-09 13:41:46.791  6146  6942 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1230, thread name: OutgoingSocketThread/Receiver)
09-09 13:41:46.791  6146  6942 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:46.791  6146  6942 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1230, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 13:41:46.801  6146  6944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1232, name: IncomingSocketThread/Receiver)
,09-09 13:41:46.801  6146  6944 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1232, thread name: IncomingSocketThread/Receiver)
09-09 13:41:46.801  6146  6943 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1231, name: IncomingSocketThread/Sender)
,09-09 13:41:46.801  6146  6944 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:46.801  6146  6944 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1232, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:41:47.241  6929  6929 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
09-09 13:41:47.241  6929  6929 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-09 13:41:47.241  6929  6929 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 13:41:47.241  6929  6929 I wpa_supplicant: Trying to associate with  'G700'
09-09 13:41:47.241  6929  6929 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,09-09 13:41:47.241  6929  6929 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-09 13:41:47.241  1014  6934 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-09 13:41:47.251  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:47.251  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:47.281  6146  6196 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 13:41:47.281  6146  6196 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 13:41:47.291  6146  6196 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2531a718 Bundle[{}]
,09-09 13:41:47.291  6146  6196 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 13:41:47.291  6146  6196 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 13:41:47.291  6146  6196 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 13:41:47.291  6146  6196 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 13:41:47.291  6146  6196 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 13:41:47.291  6146  6196 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 13:41:47.301  6146  6945 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-09 13:41:47.301  6146  6945 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 13:41:47.351  6929  6929 E wpa_supplicant: Cmd 35605 not handled
,09-09 13:41:47.361  6929  6929 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 13:41:47.361  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:47.361  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:47.361  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 13:41:47.361  6929  6929 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 13:41:47.361  6929  6929 I wpa_supplicant: Associated with F4.99.3E
,09-09 13:41:47.361  6929  6929 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 13:41:47.361  6929  6929 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 13:41:47.361  6929  6929 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:41:47.361  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:47.361  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 13:41:47.361  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:47.361  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 13:41:47.361  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 13:41:47.361  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 13:41:47.361  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-09 13:41:47.361  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:41:47.361  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-09 13:41:47.371  6929  6929 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-09 13:41:47.371  6929  6929 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-09 13:41:47.371  6929  6929 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-09 13:41:47.371  6929  6929 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:41:47.371  6929  6929 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 13:41:47.371  6929  6929 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-09 13:41:47.371  1014  1132 E Tethering: No numeric data
09-09 13:41:47.371  6929  6929 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 13:41:47.371  1014  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 13:41:47.371  1014  1132 D Tethering: clearTetheredNotification()
09-09 13:41:47.371  6929  6929 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 13:41:47.371  6929  6929 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-09 13:41:47.371  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 13:41:47.371  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 13:41:47.371  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
09-09 13:41:47.371  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:47.371  1014  1125 D SecContentProvider2: mCursor = null
09-09 13:41:47.371  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:47.371  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:47.371  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 13:41:47.371  1173  1173 D HotspotTile: updateTetherState():false, false
09-09 13:41:47.381  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:47.381  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:41:47.381  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 13:41:47.381  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:47.381  1014  1122 V NetworkStats: performPollLocked() took 6ms
,09-09 13:41:47.381  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 13:41:47.381  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 13:41:47.391  1014  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-09 13:41:47.391  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:47.391  1014  1131 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:47.391  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:47.391  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:47.391  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:47.391  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:47.391  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:47.391  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:47.401  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-09 13:41:47.401  1014  1214 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:47.401  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 13:41:47.401  1014  1214 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:47.401  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:47.401  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:47.401  1014  1214 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:47.401  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:47.401  3632  3632 I Hs20UtilService: Starting #24
09-09 13:41:47.401  3632  3664 I Hs20UtilService: Message received 5007
09-09 13:41:47.401  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:47.411  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 13:41:47.411  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 13:41:47.411  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 13:41:47.411  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 13:41:47.411  1294  1294 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 13:41:47.411  1294  3033 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 13:41:47.421  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 13:41:47.431   277   996 D CommandListener: Setting iface cfg,
09-09 13:41:47.431  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 3
09-09 13:41:47.431  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:47.431  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:47.441  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 13:41:47.441  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:47.441  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:47.441  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:47.451  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:47.451  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:47.451  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:47.451  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:47.451  1014  1125 E WifiNative-wlan0: do suspend false
,09-09 13:41:47.451  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-09 13:41:47.451  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:47.461  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 13:41:47.461  1014  1125 D SecContentProvider2: mCursor = null
,09-09 13:41:47.671  6949  6949 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 13:41:47.671  6949  6949 I dhcpcd  : version 5.5.6 starting
,09-09 13:41:47.671  6949  6949 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 13:41:47.721  6949  6949 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 13:41:47.721  6949  6949 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 13:41:47.721  6949  6949 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 13:41:47.721  6949  6949 I dhcpcd  : bssid match
09-09 13:41:47.721  6949  6949 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111,
,09-09 13:41:47.781  6949  6949 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,09-09 13:41:47.801  6146  6956 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775,
09-09 13:41:47.801  6146  6956 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:47.801  6146  6956 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:47.801  6146  6956 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:47.801  6146  6956 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-09 13:41:47.801  6146  6945 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-09 13:41:47.801  6146  6945 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 13:41:47.801  6146  6945 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:47.801  6146  6945 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 13:41:47.801  6146  6958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1243, name: IncomingSocketThread/Sender)
09-09 13:41:47.801  6146  6945 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 13:41:47.811  6146  6959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1244, name: IncomingSocketThread/Receiver),
09-09 13:41:47.811  6146  6959 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1244, thread name: IncomingSocketThread/Receiver)
09-09 13:41:47.811  6146  6959 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 13:41:47.811  6146  6959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1244, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 13:41:47.811  6146  6960 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1245, name: OutgoingSocketThread/Sender)
,09-09 13:41:47.811  6146  6961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1246, name: OutgoingSocketThread/Receiver)
,09-09 13:41:47.811  6146  6961 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1246, thread name: OutgoingSocketThread/Receiver)
,09-09 13:41:47.811  6146  6961 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 13:41:47.811  6146  6961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1246, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 13:41:47.901  6949  6949 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-09 13:41:48.001  6792  6833 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,09-09 13:41:48.261  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 13:41:48.291  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-09 13:41:48.291  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 13:41:48.301  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 13:41:48.301  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:48.301  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.301  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 13:41:48.301  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-09 13:41:48.301  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.301  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-09 13:41:48.301  1014  1125 E WifiStateMachine: VerifyingLinkState enter
09-09 13:41:48.301  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-09 13:41:48.301  1014  1131 E ConnectivityService: updateNetworkInfo()
,09-09 13:41:48.311  1014  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-09 13:41:48.311  1014  1131 D ConnectivityService: Adding iface wlan0 to network 504
,09-09 13:41:48.321  6146  6196 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1255)
,09-09 13:41:48.321  6146  6196 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-09 13:41:48.321  6146  6196 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1256)
09-09 13:41:48.321  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
09-09 13:41:48.321  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:41:48.321  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:41:48.321  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:41:48.321  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 13:41:48.321  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 13:41:48.321  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29f1f1ee added. We now have 3 listener(s)
,09-09 13:41:48.331  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:48.331  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:48.331  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.331  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.331  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:48.331  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:48.341  1014  3125 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 13:41:48.341  1014  3125 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:48.341  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-09 13:41:48.351  1014  3125 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:48.351  1014  3125 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:48.351  1014  3125 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:48.351  3632  3632 I Hs20UtilService: Starting #25
09-09 13:41:48.351  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:48.351  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:48.351  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 13:41:48.351  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 13:41:48.351  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 13:41:48.351  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fceb68f added. We now have 3 listener(s)
09-09 13:41:48.351  6146  6196 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 13:41:48.361  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 13:41:48.361  1014  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-09 13:41:48.361  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:48.361  1014  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-09 13:41:48.361  1294  1294 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 13:41:48.361  1014  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-09 13:41:48.371  1014  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-09 13:41:48.371  1014  1131 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-09 13:41:48.371  1014  1131 D ConnectivityService: LTETest block dns file not exists
09-09 13:41:48.371  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 13:41:48.381  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:48.381  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 13:41:48.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.381  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.381  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:48.381  6146  6196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 13:41:48.381  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:48.381  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:48.381  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:48.381  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:48.381  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 13:41:48.381  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 13:41:48.381  6146  6196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 13:41:48.381  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:48.381  1014  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:48.381  1014  1131 E ConnectivityService: updateNetworkInfo()
09-09 13:41:48.381  1014  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 13:41:48.381  1014  6947 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:48.381  1014  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:48.381  1014  6947 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 13:41:48.381  1014  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-09 13:41:48.381  1014  6947 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 13:41:48.381  1014  6947 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-09 13:41:48.381  1014  6947 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 13:41:48.391   277   992 D EnterpriseController: uids 1000
09-09 13:41:48.391   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:48.391   277   992 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-09 13:41:48.391  6146  6196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 13:41:48.391  6146  6196 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 13:41:48.401  1014  1131 D ConnectivityService:    accepting network in place of null
09-09 13:41:48.401  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 13:41:48.401  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:48.401  1453  1453 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 13:41:48.401  1014  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 13:41:48.401  1014  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-09 13:41:48.401  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:48.401  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 13:41:48.401  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:48.401  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 13:41:48.401  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 13:41:48.401  6146  6196 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29f1f1ee removed from the list
09-09 13:41:48.401  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:48.401  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fceb68f removed from the list
09-09 13:41:48.401  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 13:41:48.401  1014  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-09 13:41:48.411  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 13:41:48.411  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 13:41:48.411  1014  1132 D Tethering: MasterInitialState.processMessage what=3
09-09 13:41:48.411  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:48.411  1014  1122 V NetworkStats: updateIfacesLocked()
09-09 13:41:48.411  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 13:41:48.411  1014  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:48.411  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 13:41:48.411  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 13:41:48.411  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 13:41:48.411  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:48.411  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:48.421  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,09-09 13:41:48.421  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-09 13:41:48.421  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:48.421  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:48.421  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:41:48.421  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:41:48.421  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-09 13:41:48.421  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:48.421  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:48.421  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:48.421  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:48.421  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:48.421  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:48.421  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:48.421  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:48.421  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:48.421  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:48.421  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:48.421  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 13:41:48.421  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:48.421  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:41:48.431  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-09 13:41:48.431  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 13:41:48.431  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,09-09 13:41:48.431  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:41:48.431  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:48.431  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 13:41:48.431  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:48.431  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 13:41:48.431  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.431  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:48.441  1014  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:48.441  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:48.441  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:48.441  1014  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:48.441  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 13:41:48.441  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:48.441  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:41:48.441  3632  3632 I Hs20UtilService: Starting #26
09-09 13:41:48.441  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:48.451  6146  6196 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-09 13:41:48.451  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-09 13:41:48.451  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:48.451  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 13:41:48.451  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:48.451  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 13:41:48.451  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 13:41:48.451  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:48.451  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:41:48.451  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:48.451  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:48.451  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:48.451  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 13:41:48.451  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 13:41:48.451  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 13:41:48.451  1294  1294 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 13:41:48.451  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-09 13:41:48.461  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:48.461  6146  6988 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 13:41:48.461  6146  6988 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 13:41:48.461  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 13:41:48.461  1294  1294 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-09 13:41:48.461  1294  1294 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 13:41:48.461  6146  6988 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
09-09 13:41:48.461  6146  6988 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:48.461  6146  6988 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:48.461  6146  6988 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@160f3efa
09-09 13:41:48.461  6146  6988 D BluetoothSocket: channel: 6
09-09 13:41:48.461  6146  6988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:48.461  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:48.471  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:48.471  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:48.471  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 13:41:48.471  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 7C F9 0E 37 96 AB
09-09 13:41:48.471  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:48.471  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 13:41:48.471  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:48.471  6792  6800 D BtGatt.GattService: registerClient() - UUID=dc40893a-87d6-42f5-9f07-aa5058c1caa1
,09-09 13:41:48.471  1014  1326 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 13:41:48.471  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 13:41:48.481  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:48.481  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:48.481  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 13:41:48.481  3632  3632 I Hs20UtilService: Starting #27
,09-09 13:41:48.481  3632  3664 I Hs20UtilService: Message received 5007
,09-09 13:41:48.481  1294  1294 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 13:41:48.481  1294  1294 I NearbySettings: MountReceiver.onReceive - Keep current state
09-09 13:41:48.481  1014  6947 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 13:41:48.491  1014  1500 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
,09-09 13:41:48.491  1014  3126 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState,
,09-09 13:41:48.491  1014  3126 D SecContentProvider2: mCursor = null,
09-09 13:41:48.491  1014  1483 D SecContentProvider2: uri = 15 selection = getToastGravity,
09-09 13:41:48.491  1014  1483 D SecContentProvider2: mCursor = null
09-09 13:41:48.491  1014  1342 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-09 13:41:48.491  1014  1342 D SecContentProvider2: mCursor = null
09-09 13:41:48.491  1014  1539 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-09 13:41:48.491  1014  1539 D SecContentProvider2: mCursor = null
,09-09 13:41:48.491  1014  1326 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-09 13:41:48.491  1014  1326 D SecContentProvider2: mCursor = null
09-09 13:41:48.501  1014  1535 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-09 13:41:48.501  1014  1535 D SecContentProvider2: mCursor = null
,09-09 13:41:48.521  6792  6835 D BtGatt.GattService: onClientRegistered() - UUID=dc40893a-87d6-42f5-9f07-aa5058c1caa1, clientIf=6
,09-09 13:41:48.521  6146  6155 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:48.521  6792  6838 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:48.521   257   257 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=4, Uoast
,09-09 13:41:48.531  1014  6947 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 11:41:48 GMT], X-Android-Received-Millis=[1473421308541], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473421308517]}
,09-09 13:41:48.531  1014  6947 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-09 13:41:48.531  1014  6947 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-09 13:41:48.531  1014  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-09 13:41:48.531  1014  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-09 13:41:48.531  1014  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-09 13:41:48.531  1014  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
,09-09 13:41:48.531  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 13:41:48.531  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-09 13:41:48.531  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 13:41:48.531  1014  3126 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,09-09 13:41:48.541  6792  6838 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 13
,09-09 13:41:48.541  6792  6838 D BtGatt.AdvertiseManager: number of adv instance running0,
09-09 13:41:48.541  6792  6838 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:48.541  6792  6838 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:48.541  6792  6838 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:48.551  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:41:48.551  6792  6835 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0,
09-09 13:41:48.551  6792  6838 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:48.551  6792  6835 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:48.551  6792  6838 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:48.551  6792  6838 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
09-09 13:41:48.551  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:48.551  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: EthernetConnected: false,
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 13:41:48.561  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 13:41:48.561  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:48.561  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything,
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 13:41:48.561  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 13:41:48.561  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:48.561  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:41:48.561  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:48.561  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 13:41:48.561  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.561  6146  6146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 13:41:48.561  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-09 13:41:48.561  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 13:41:48.911  1014  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,09-09 13:41:48.921  3144  3144 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-09 13:41:48.921  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:48.941  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:48.941  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:48.941  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:48.941  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:48.941  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:48.941  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:48.941  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:48.941  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 13:41:48.941  6403  6403 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 13:41:48.951  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:48.951  5792  5792 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 13:41:48.951  5792  5792 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:41:48.951  5792  5792 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:41:48.951  5792  5792 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:48.961  1014  1342 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-09 13:41:48.961  1014  1342 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 13:41:48.961  6403  6403 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 13:41:48.971  6146  6146 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 13:41:48.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 13:41:48.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 13:41:48.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 13:41:48.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 13:41:48.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 13:41:48.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 13:41:48.971  6146  6146 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 13:41:48.971  6146  6146 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 13:41:48.971  6417  6417 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-09 13:41:48.981  1727  1727 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:48.981  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:48.981  1014  1539 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 13:41:48.991  6417  6417 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-09 13:41:48.991  6417  6417 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-09 13:41:48.991  6417  6417 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-09 13:41:48.991  1727  1727 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-09 13:41:49.001  1727  1727 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,09-09 13:41:49.001  1727  1727 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-09 13:41:49.001  1727  1727 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:49.001  1312  1330 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-09 13:41:49.011  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 13:41:49.011  6385  6385 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 13:41:49.011  6385  6385 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 13:41:49.011  6385  6385 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 13:41:49.021  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:41:49 GMT+02:00 2016
,09-09 13:41:49.021  1727  1727 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-09 13:41:49.021  1727  1727 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 13:41:49.021  1727  1727 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-09 13:41:49.021  1014  1535 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 13:41:49.021  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.031  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:49.031  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:41:49.031  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:41:49.031  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:41:49.041  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:49.041  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 13:41:49.051  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 13:41:49.051  6586  6586 I DIAGMON_AGENT: ./extraInfo: "NG700"
,09-09 13:41:49.051  6586  6586 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-09 13:41:49.051  3666  3666 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 13:41:49.061  3666  3666 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:41:49.061  3666  6995 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
09-09 13:41:49.061  6146  6146 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-09 13:41:49.061  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything,
09-09 13:41:49.061  6146  6146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:41:49.061  3666  6995 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-09 13:41:49.061  3666  6995 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-09 13:41:49.071  3666  6995 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,09-09 13:41:49.071  3666  6995 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,09-09 13:41:49.071  1014  1214 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 13:41:49.071  1014  1214 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.071  1014  1214 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:49.071  1014  1214 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:49.071  1014  1214 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 13:41:49.081  3666  6995 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,09-09 13:41:49.081  1014  1326 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-09 13:41:49.081  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.091  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:49.091  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:49.091  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 13:41:49.091   277   992 D EnterpriseController: uids 10012
09-09 13:41:49.091   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:49.091   277   992 D Netd    : getNetworkForDns: using netid 504 for uid 10012
,09-09 13:41:49.091  3798  3798 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 13:41:49.091  3798  4542 I iu.UploadsManager: num queued entries: 0
,09-09 13:41:49.091  3798  4542 I iu.UploadsManager: num updated entries: 0
,09-09 13:41:49.101  3798  4542 I iu.SyncManager: NEXT; no task
,09-09 13:41:49.101  3666  6995 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-09 13:41:49.111  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-09 13:41:49.121  6642  6642 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:49.121  6642  6642 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-09 13:41:49.121  6642  6642 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 13:41:49.121  3205  6998 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
09-09 13:41:49.121  3205  6998 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-09 13:41:49.131  5921  5921 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-09 13:41:49.131  1014  1026 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-09 13:41:49.131  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.131  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:49.131  1014  1026 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:49.131  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:41:49.131  5840  5840 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-09 13:41:49.131  3205  6998 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-09 13:41:49.131  5921  5921 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-09 13:41:49.131  5921  5921 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-09 13:41:49.131  5921  5921 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
09-09 13:41:49.131  5921  5921 D InitializeManagerStateMachine: exit::IDLE
09-09 13:41:49.131  5921  5921 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-09 13:41:49.141  5921  5921 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,09-09 13:41:49.141  5921  5921 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-09 13:41:49.141  5921  5921 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-09 13:41:49.141  5921  5921 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-09 13:41:49.141  5921  5921 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-09 13:41:49.141  5921  5921 D InitializeManagerStateMachine: entry::SUCCESS
09-09 13:41:49.141  5921  5921 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-09 13:41:49.141  6042  6042 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-09 13:41:49.141  6042  6042 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,09-09 13:41:49.141  6042  6042 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 13:41:49.141  5921  5921 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:41:49.141  5921  5921 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-09 13:41:49.151  5921  5921 D InitializeManagerStateMachine: exit::SUCCESS
,09-09 13:41:49.151  5921  5921 D InitializeManagerStateMachine: entry::IDLE
,09-09 13:41:49.151  6042  6042 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 13:41:49.151  6042  6042 I SA      : [OR] == isSIMCardReady false ==
09-09 13:41:49.151  6042  6042 I SA      : [SCU] == networkStateCheck == true
09-09 13:41:49.151  6042  6042 I SA      : [DM] getCountryCodeFromCSC : PL
09-09 13:41:49.151  6042  6042 I SA      : isChinaCountryCode : false
09-09 13:41:49.151  6042  6042 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-09 13:41:49.151  6042  6042 I SA      : [OR] == networkStateCheck true ==
09-09 13:41:49.151  6042  6042 I SA      : [OR] GetMyCountryZoneTask
09-09 13:41:49.151  6042  6042 I SA      : [OR] onReceive END
,09-09 13:41:49.161  6042  6999 I SA      : [SRS] prepareGetMyCountryZone
,09-09 13:41:49.161  1224  1224 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 13:41:49.171  3205  6998 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-09 13:41:49.171  1014  1342 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,09-09 13:41:49.171  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-09 13:41:49.171  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:49.171  3205  6998 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
09-09 13:41:49.171  1014  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:41:49.171  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-09 13:41:49.171  3205  6998 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-09 13:41:49.171  3205  6998 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-09 13:41:49.171  6042  6999 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-09 13:41:49.171  6042  6999 I SA      : [SSP] query invoked
,09-09 13:41:49.171  3205  6998 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-09 13:41:49.171  3205  6998 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-09 13:41:49.181  3205  6998 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-09 13:41:49.181  3205  6998 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-09 13:41:49.191  1014  1541 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,09-09 13:41:49.191  3205  6998 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-09 13:41:49.201  3205  6998 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-09 13:41:49.221  1946  6996 I qtaguid : Tagging socket 48 with tag 1000040700000000{268436487,0} for uid -1, pid: 1946, getuid(): 10012
,09-09 13:41:49.341  1014  3125 I art     : Explicit concurrent mark sweep GC freed 97413(5MB) AllocSpace objects, 6(144KB) LOS objects, 33% free, 28MB/42MB, paused 2.507ms total 162.129ms
,09-09 13:41:49.341  6042  6999 I SA      : [TPMU] GetMccFromDB : null
09-09 13:41:49.341  6042  6999 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:41:49.341  6042  6999 I SA      : [LBE] isSupportCheckDomainRegion : false
09-09 13:41:49.341  6042  6999 I SA      : [TPM] isNoProxy(default) : true
,09-09 13:41:49.341  6042  6999 I SA      : [RC New] Execute method=[GET] start
,09-09 13:41:49.351  1014  1326 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-09 13:41:49.351  1014  1326 D SecContentProvider2: mCursor = null
,09-09 13:41:49.381  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:41:49.381  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 13:41:49.381  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 13:41:49.391  6042  6999 I SA      : [RC New] Security=[true]
,09-09 13:41:49.391  6042  6999 I System.out: Thread-1032(ApacheHTTPLog):isSBSettingEnabled false
09-09 13:41:49.391  6042  6999 I System.out: Thread-1032(ApacheHTTPLog):isShipBuild true
09-09 13:41:49.391  6042  6999 I System.out: Thread-1032(ApacheHTTPLog):SMARTBONDING_ENABLED is false
09-09 13:41:49.391  6042  6999 I System.out: Thread-1032(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 13:41:49.391   277   992 D EnterpriseController: uids 10041
09-09 13:41:49.391   277   992 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 13:41:49.391   277   992 D Netd    : getNetworkForDns: using netid 504 for uid 10041
,09-09 13:41:49.411  1014  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 503] cleared because we found a replacement network,
,09-09 13:41:49.691   290   290 E SMD     : DCD OFF,
,09-09 13:41:50.001  6042  6999 I SA      : [RC New] [v2liruge] api execute + 610
,09-09 13:41:50.001  6042  6999 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,09-09 13:41:50.001  6042  6999 I System.out: AsyncTask #2 calls detatch()
09-09 13:41:50.001  6042  6999 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,09-09 13:41:50.011  6042  6999 I SA      : [OCP] update openData : PL,
09-09 13:41:50.011  6042  6999 I SA      : [TPMU] getNetworkMcc : 
,09-09 13:41:50.011  6042  6999 I SA      : [SCU] saveMccToPreferece Start
09-09 13:41:50.011  6042  6999 I SA      : [SCU] RegionMCC : 260
09-09 13:41:50.011  6042  6999 I SA      : [SSP] query invoked,
09-09 13:41:50.011  6042  6999 I SA      : [TPMU] GetMccFromDB : null
09-09 13:41:50.011  6042  6999 I SA      : [SCU] getMccFromPreferece mcc = 260
09-09 13:41:50.011  6042  6999 I SA      : [SCU] saveMccToPreferece End
,09-09 13:41:50.021  6042  6999 I SA      : [RC New] executeRequest [v2liruge] end. 669
09-09 13:41:50.021  6042  6999 I SA      : [RC New] Execute end
09-09 13:41:50.021  6042  6042 I SA      : [OR] GetMyCountryZoneTask mcc = 260
09-09 13:41:50.021  6042  6042 I SA      : [OR] GetMyCountryZoneTask Success
,09-09 13:41:50.041  1014  1046 I PowerManagerService: [PWL] Off : 75s ago
,09-09 13:41:51.401  1014  1147 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.,
,09-09 13:41:51.571  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
09-09 13:41:51.571  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 13:41:51.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-09 13:41:51.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:51.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:51.571  6146  6196 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a334f08, channel: 6, state: LISTENING
,09-09 13:41:51.571  6146  6196 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a334f08, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@160f3efa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@321d46a1mSocket: android.net.LocalSocket@38250c6 impl:android.net.LocalSocketImpl@323ce887 fd:FileDescriptor[112]
09-09 13:41:51.571  6146  6196 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38250c6 impl:android.net.LocalSocketImpl@323ce887 fd:FileDescriptor[112]
09-09 13:41:51.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-09 13:41:51.571  6146  6988 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a334f08, channel: 6, state: CLOSED
09-09 13:41:51.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:51.571  6146  6988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
09-09 13:41:51.571  6146  6988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 13:41:51.571  6146  6988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-09 13:41:51.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 13:41:51.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 13:41:51.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:51.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:41:51.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:51.571  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 13:41:51.571  6146  6196 D BluetoothLeScanner: could not find callback wrapper
09-09 13:41:51.571  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 13:41:51.571  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 13:41:51.571  6792  6838 D BtGatt.AdvertiseManager: message : 1
,09-09 13:41:51.571  6792  6838 D BtGatt.AdvertiseManager: stop advertise for client 6
09-09 13:41:51.571  6792  6838 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-09 13:41:51.581  6792  6838 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:51.591  6792  6835 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-09 13:41:51.591  6792  6835 D BtGatt.GattService: Client app is not null!
,09-09 13:41:51.591  6792  6801 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 13:41:51.591  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:51.591  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 13:41:51.591  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:41:51.591  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 13:41:51.591  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-09 13:41:51.601  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:51.601  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 13:41:51.601  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:51.601  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:51.601  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:51.601  6146  6146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 13:41:51.601  6146  6146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:51.601  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:51.601  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:51.601  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:51.611  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:51.611  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:51.611  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:51.611  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29f1f1ee not in the list
09-09 13:41:51.611  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:51.611  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fceb68f not in the list
09-09 13:41:51.611  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:51.611  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:51.611  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:51.611  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:51.611  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:51.611  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 13:41:51.611  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 13:41:51.611  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:51.611  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 13:41:51.611  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:51.621  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:51.621  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:51.621  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 13:41:51.621  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 13:41:51.631  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:41:51.631  6792  6800 D BtGatt.GattService: registerClient() - UUID=1058b6a0-a316-4af6-89cf-f8c6bd74ca2a
,09-09 13:41:51.681  6792  6835 D BtGatt.GattService: onClientRegistered() - UUID=1058b6a0-a316-4af6-89cf-f8c6bd74ca2a, clientIf=6,
09-09 13:41:51.681  6146  6155 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:51.681  6792  6878 D BtGatt.GattService: start scan with filters
,09-09 13:41:51.681  6792  6839 D BtGatt.ScanManager: handling starting scan,
09-09 13:41:51.681  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 13:41:51.681  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 13:41:51.681  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 13:41:51.681  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 13:41:51.681  6792  6839 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@216230a6
,09-09 13:41:51.691  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 13:41:51.691  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-09 13:41:51.691  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 13:41:51.691  6792  6835 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 13:41:51.691  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:51.691  6792  6839 D BtGatt.ScanManager: allow scan with filters
09-09 13:41:51.691  6792  6839 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 13:41:51.691  6792  6839 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-09 13:41:51.691  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:51.691  6792  6835 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 13:41:51.691  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:51.701  6792  6839 D BtGatt.ScanManager: Starting BLE batch scan
09-09 13:41:51.701  6792  6839 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 13:41:51.701  1014  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-09 13:41:51.701  1014  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-09 13:41:51.701  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:41:51.711  1014  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 13:41:51.711  6792  6835 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 13:41:51.711  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:51.711  1173  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-09 13:41:51.711  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:41:51.711  6792  6835 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
,09-09 13:41:51.711  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:51.711  3798  6212 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-09 13:41:51.741  6792  6839 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 16
,09-09 13:41:51.911  6949  6949 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
,09-09 13:41:52.011   257  1743 I SurfaceFlinger: id=16 Removed Uoast (8/9),
,09-09 13:41:52.011  1014  1539 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1014) eventTime = 154228
09-09 13:41:52.011   257   450 I SurfaceFlinger: id=16 Removed Uoast (-2/9)
09-09 13:41:52.021  1014  1539 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014 (0x0)
09-09 13:41:52.021  1014  1539 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1014, ws=WorkSource{10054}) (elapsedTime=3482)
,09-09 13:41:52.141  1014  1500 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:52.141  1014  1500 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 13:41:52.141  1014  1500 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:52.141  1014  1500 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-09 13:41:52.141  1014  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 13:41:52.191  6146  6146 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 13:41:52.191  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 13:41:52.191  6146  6146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:52.211  1014  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:41:52.221  6792  6792 D BtGatt.ScanManager: awakened up at time 154430
,09-09 13:41:52.221  6792  6839 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:52.221  6792  6835 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:52.221  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:52.691   290   290 E SMD     : DCD OFF
,09-09 13:41:52.721  1014  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:41:52.721  6792  6792 D BtGatt.ScanManager: awakened up at time 154937
,09-09 13:41:52.731  6792  6839 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:52.731  6792  6835 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
09-09 13:41:52.731  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:52.731  6792  6835 D BtGatt.GattService: current time is 154946484834
,09-09 13:41:52.731  6792  6835 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -74, 83, 1, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:41:52.741  6792  6835 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 13:41:52.741  6792  6835 D ScanRecord: parseFromBytes
,09-09 13:41:52.741  6792  6835 D ScanRecord: first manudata for manu ID
,09-09 13:41:52.741  6792  6835 D BtGatt.GattService: result: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-74, mTimestampNanos=137997472803}
,09-09 13:41:52.741  6792  6835 D BtGatt.GattService: filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 13:41:52.741  6146  6155 D ScanRecord: parseFromBytes
,09-09 13:41:52.751  6146  6155 D ScanRecord: first manudata for manu ID
,09-09 13:41:53.231  1014  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:41:53.241  6792  6792 D BtGatt.ScanManager: awakened up at time 155451
,09-09 13:41:53.241  6792  6839 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:53.241  6792  6835 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:53.241  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:53.751  1014  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:41:53.751  6792  6792 D BtGatt.ScanManager: awakened up at time 155962
,09-09 13:41:53.751  6792  6839 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:53.761  6792  6835 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:53.761  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:53.961  5792  5792 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,09-09 13:41:53.961  5792  7012 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,09-09 13:41:53.971  5792  7012 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,09-09 13:41:53.971  5792  7012 I ReactiveServiceManager: Supported : 1
,09-09 13:41:53.971  1014  1535 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,09-09 13:41:53.981  1014  1535 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 13:41:53.991  1014  1535 D QSEECOMAPI: : Loaded image: APP id = 13
,09-09 13:41:54.001  1014  1535 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-09 13:41:54.001  1014  1535 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 13
,09-09 13:41:54.001  1014  1535 E terrier : handleString: Failed to handle string(-4)
,09-09 13:41:54.001  1014  1535 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,09-09 13:41:54.001  5792  7012 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
,09-09 13:41:54.001  5792  7012 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,09-09 13:41:54.011  5792  7012 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 13:41:54.011  5792  7012 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-09 13:41:54.011  5792  7012 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-09 13:41:54.011  5792  7012 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,09-09 13:41:54.121  1014  3125 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 13:41:54.121  1014  3125 D BatteryService: level:96, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 13:41:54.121  1014  3125 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-09 13:41:54.121  1014  3125 D BatteryService: stay LED for charging
09-09 13:41:54.121  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 13:41:54.121  1014  1014 I MotionRecognitionService: Plugged
,09-09 13:41:54.121  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 13:41:54.131  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 13:41:54.131  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 13:41:54.131  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 13:41:54.131  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 96
,09-09 13:41:54.141  6792  6792 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 13:41:54.141  6792  6840 D HeadsetStateMachine: Disconnected process message: 10
,09-09 13:41:54.151  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:54.151  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:54.151  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:96 status:2 health:2
,09-09 13:41:54.261  1014  1093 V AlarmManager: waitForAlarm result :4
,09-09 13:41:54.261  6792  6792 D BtGatt.ScanManager: awakened up at time 156476
,09-09 13:41:54.271  6792  6839 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:54.271  6792  6835 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 13:41:54.271  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:54.701  1014  2772 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:41:54.701  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:54.701  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:54.701  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-09 13:41:54.701  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29f1f1ee not in the list
09-09 13:41:54.701  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:54.701  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-09 13:41:54.701  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 13:41:54.701  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 13:41:54.701  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:54.701  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 13:41:54.701  6792  6879 D BtGatt.GattService: stopScan() - queue size =1
09-09 13:41:54.701  6792  6839 D BtGatt.ScanManager: filter size is 1
09-09 13:41:54.701  6792  6839 D BtGatt.ScanManager: delete FilterIndex - 3
09-09 13:41:54.701  6792  6800 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 13:41:54.701  6792  6835 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 13:41:54.701  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 13:41:54.701  6792  6839 D BtGatt.ScanManager: stopping BLe Batch
09-09 13:41:54.711  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:54.711  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:54.711  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 13:41:54.711  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 13:41:54.711  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 13:41:54.711  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:54.711  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-09 13:41:54.711  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:54.711  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-09 13:41:54.711  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:54.711  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 13:41:54.711  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:54.711  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:54.711  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fceb68f not in the list
09-09 13:41:54.711  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 13:41:54.711  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:54.711  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:54.711  6146  6196 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-09 13:41:54.711  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-09 13:41:54.721  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:54.721  6146  6196 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-09 13:41:54.721  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 13:41:54.721  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-09 13:41:54.721  6792  6835 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 13:41:54.721  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:54.721  6792  6839 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 13:41:54.721  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 13:41:54.721  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 13:41:54.721  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-09 13:41:54.721  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 13:41:54.721  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 13:41:54.721  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 13:41:54.721  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
09-09 13:41:54.721  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 13:41:54.721  6792  6835 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 13:41:54.721  6792  6835 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 13:41:54.731  6146  6196 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 13:41:54.731  6146  7015 D BluetoothSocket: bindListen(): myUserId = 0
09-09 13:41:54.731  6146  7015 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 13:41:54.741  6146  7015 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
09-09 13:41:54.741  6146  7015 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 13:41:54.741  6146  7015 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 13:41:54.741  6146  7015 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b6728d9
09-09 13:41:54.741  6146  7015 D BluetoothSocket: channel: 6
09-09 13:41:54.741  6146  7015 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 13:41:54.741  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 13:41:54.741  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 13:41:54.741  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 13:41:54.741  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 13:41:54.741  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 7C F9 0E 37 96 AB
,09-09 13:41:54.741  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:41:54.741  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 124, -7, 14, 55, -106, -85]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 13:41:54.741  6146  6196 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-09 13:41:54.751  6792  6879 D BtGatt.GattService: registerClient() - UUID=0accb694-bfa5-4971-a6a9-5ab117e51f9d
,09-09 13:41:54.791  6792  6835 D BtGatt.GattService: onClientRegistered() - UUID=0accb694-bfa5-4971-a6a9-5ab117e51f9d, clientIf=6
,09-09 13:41:54.791  6146  6155 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,09-09 13:41:54.791  6792  6838 D BtGatt.AdvertiseManager: message : 0
,09-09 13:41:54.811  6792  6838 D BtGatt.AdvertiseManager: 1. app : com.android.bluetooth 2. Action : LEAV 3. Callng app : com.test.thalitest 4. Count : 14
,09-09 13:41:54.811  6792  6838 D BtGatt.AdvertiseManager: number of adv instance running0
,09-09 13:41:54.811  6792  6838 D BtGatt.AdvertiseManager: size of list is =0
,09-09 13:41:54.811  6792  6838 D BtGatt.AdvertiseManager: starting advertising
,09-09 13:41:54.811  6792  6838 D BtGatt.AdvertiseManager: isStandardAdvfalse
,09-09 13:41:54.821  6792  6835 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,09-09 13:41:54.821  6792  6838 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 13:41:54.821  6792  6835 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,09-09 13:41:54.821  6792  6838 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,09-09 13:41:54.821  6792  6838 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,09-09 13:41:54.821  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 13:41:54.821  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 13:41:54.831  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 13:41:54.831  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 13:41:54.831  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-09 13:41:54.831  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 13:41:54.831  6146  6146 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-09 13:41:54.831  6146  6146 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 13:41:54.831  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 13:41:54.831  6146  6146 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:54.831  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 13:41:55.191  1014  2730 D SSRM:n  : SIOP:: AP = 350
,09-09 13:41:55.341  6146  6146 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 13:41:55.341  6146  6146 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 13:41:55.341  6146  6146 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 13:41:55.691   290   290 E SMD     : DCD OFF
,09-09 13:41:55.921  6949  6949 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,09-09 13:41:56.701   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:57.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:57.841  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 13:41:57.841  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 13:41:57.841  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 13:41:57.841  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 13:41:57.841  6146  6196 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b10617f, channel: 6, state: LISTENING
09-09 13:41:57.841  6146  6196 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b10617f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2b6728d9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ae8654cmSocket: android.net.LocalSocket@18987995 impl:android.net.LocalSocketImpl@c355aaa fd:FileDescriptor[112]
09-09 13:41:57.841  6146  6196 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@18987995 impl:android.net.LocalSocketImpl@c355aaa fd:FileDescriptor[112]
,09-09 13:41:57.841  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
09-09 13:41:57.841  6146  6196 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 13:41:57.841  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29f1f1ee not in the list
09-09 13:41:57.841  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 13:41:57.841  6146  6146 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 13:41:57.841  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 13:41:57.841  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 13:41:57.841  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 13:41:57.841  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 13:41:57.841  6146  7015 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b10617f, channel: 6, state: CLOSED
09-09 13:41:57.841  6146  7015 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 13:41:57.841  6146  7015 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 13:41:57.841  6146  7015 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 13:41:57.841  6146  6196 D BluetoothLeScanner: could not find callback wrapper
,09-09 13:41:57.841  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 13:41:57.841  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
09-09 13:41:57.841  6792  6838 D BtGatt.AdvertiseManager: message : 1
09-09 13:41:57.841  6792  6838 D BtGatt.AdvertiseManager: stop advertise for client 6
,09-09 13:41:57.841  6792  6838 D BtGatt.AdvertiseManager:  standardAdvClientIf = 0client.clientIf6
09-09 13:41:57.841  6792  6838 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,09-09 13:41:57.851  6792  6835 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0,
09-09 13:41:57.851  6792  6835 D BtGatt.GattService: Client app is not null!
,09-09 13:41:57.851  6792  6875 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 13:41:57.851  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 13:41:57.851  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-09 13:41:57.851  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-09 13:41:57.851  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-09 13:41:57.851  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 13:41:57.861  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 13:41:57.861  6146  6196 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 13:41:57.861  6146  6196 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 13:41:57.861  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 13:41:57.861  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:57.861  6146  6146 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 13:41:57.861  6146  6146 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 13:41:57.861  6146  6146 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 13:41:57.861  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fceb68f not in the list
09-09 13:41:57.861  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:57.861  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:57.861  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:57.861  6146  6196 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 13:41:57.861  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:57.861  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:57.861  6146  6196 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29f1f1ee not in the list
09-09 13:41:57.861  6146  6196 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 13:41:57.861  6146  6196 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fceb68f not in the list
09-09 13:41:57.861  6146  6196 D io.jxcore.node.ConnectivityMonitor: stop
09-09 13:41:57.861  6146  6196 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 13:41:57.861  6146  6196 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 13:41:57.861  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:57.861  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 13:41:57.861  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 13:41:57.861  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 13:41:57.861  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 13:41:57.861  6146  6196 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 13:41:57.871  6146  7018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1276, name: My test thread name)
,09-09 13:41:58.361  6146  6146 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 13:41:58.691   290   290 E SMD     : DCD OFF,
,09-09 13:41:58.691   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:59.151  1014  1026 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps,
09-09 13:41:59.151  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,09-09 13:41:59.151  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:41:59.151  1014  1026 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 13:41:59.151  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-09 13:41:59.161  5921  5921 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE,
09-09 13:41:59.161  5921  5921 D PreloadUpdateManagerStateMachine: exit::IDLE
09-09 13:41:59.161  5921  5921 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,09-09 13:41:59.161  5921  5921 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-09 13:41:59.161  5921  5921 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,09-09 13:41:59.161  5921  5921 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
09-09 13:41:59.161  5921  5921 D PreloadUpdateManagerStateMachine: entry::IDLE
,09-09 13:41:59.701   319   319 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 13:41:59.881  6146  6196 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1276,
09-09 13:41:59.881  6146  6196 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1276, name: My test thread name)
,09-09 13:41:59.881  6146  7021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1277, name: My test thread name)
09-09 13:41:59.881  6146  7018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1276, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154,
09-09 13:41:59.881  6146  7021 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1277, thread name: My test thread name)
09-09 13:41:59.881  6146  7021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1277, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-09 13:41:59.881  6146  6196 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 13:41:59.881  6146  7022 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1281, name: My test thread name)
,09-09 13:41:59.881  6146  7022 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1281, thread name: My test thread name): Test exception.
09-09 13:41:59.881  6146  7022 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1281, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-09 13:41:59.881  6146  6196 I jxcore-log: Total number of executed tests:  82
09-09 13:41:59.881  6146  6196 I jxcore-log: 
09-09 13:41:59.881  6146  6196 I jxcore-log: Number of passed tests:  82
09-09 13:41:59.881  6146  6196 I jxcore-log: 
09-09 13:41:59.881  6146  6196 I jxcore-log: Number of failed tests:  0
09-09 13:41:59.881  6146  6196 I jxcore-log: 
09-09 13:41:59.881  6146  6196 I jxcore-log: Number of ignored tests:  0
09-09 13:41:59.881  6146  6196 I jxcore-log: 
09-09 13:41:59.881  6146  6196 I jxcore-log: Total duration:  35153
09-09 13:41:59.881  6146  6196 I jxcore-log: 
09-09 13:41:59.881  6146  6196 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 13:41:59.881  6146  6196 I jxcore-log: 
09-09 13:41:59.881  6146  6196 I jxcore-log: My device name is: samsung-SM-A500FU
09-09 13:41:59.881  6146  6196 I jxcore-log: 
09-09 13:41:59.891  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.891  6146  6196 I jxcore-log: 
,09-09 13:41:59.901  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.901  6146  6196 I jxcore-log: 
09-09 13:41:59.901  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.901  6146  6196 I jxcore-log: 
09-09 13:41:59.901  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:59.901  6146  6196 I jxcore-log: 
09-09 13:41:59.901  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.901  6146  6196 I jxcore-log: 
09-09 13:41:59.901  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:59.901  6146  6196 I jxcore-log: 
09-09 13:41:59.901  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.901  6146  6196 I jxcore-log: 
,09-09 13:41:59.901  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:59.901  6146  6196 I jxcore-log: 
09-09 13:41:59.901  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.901  6146  6196 I jxcore-log: 
09-09 13:41:59.911  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.911  6146  6196 I jxcore-log: 
,09-09 13:41:59.911  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.911  6146  6196 I jxcore-log: 
09-09 13:41:59.911  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:59.911  6146  6196 I jxcore-log: 
09-09 13:41:59.911  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:59.911  6146  6196 I jxcore-log: 
09-09 13:41:59.911  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:59.911  6146  6196 I jxcore-log: 
,09-09 13:41:59.911  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:59.911  6146  6196 I jxcore-log: 
,09-09 13:41:59.911  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:59.911  6146  6196 I jxcore-log: 
09-09 13:41:59.921  6949  6949 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-09 13:41:59.921  6949  6949 I dhcpcd  : wlan0: no IPv6 Routers available
09-09 13:41:59.921  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:59.921  6146  6196 I jxcore-log: 
09-09 13:41:59.921  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:59.921  6146  6196 I jxcore-log: 
09-09 13:41:59.921  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.921  6146  6196 I jxcore-log: 
09-09 13:41:59.921  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.921  6146  6196 I jxcore-log: 
09-09 13:41:59.921  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.921  6146  6196 I jxcore-log: 
09-09 13:41:59.921  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.921  6146  6196 I jxcore-log: 
09-09 13:41:59.921  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.921  6146  6196 I jxcore-log: 
09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
,09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
,09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
09-09 13:41:59.931  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 13:41:59.931  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
,09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
09-09 13:41:59.941  6146  6196 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 13:41:59.941  6146  6196 I jxcore-log: 
,09-09 13:41:59.991  1014  1093 V AlarmManager: waitForAlarm result :8,
,09-09 13:42:00.181  7023  7023 D AndroidRuntime: 
09-09 13:42:00.181  7023  7023 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 13:42:00.181  7023  7023 D AndroidRuntime: CheckJNI is OFF,
09-09 13:42:00.181  7023  7023 D AndroidRuntime: readGMSProperty: start
09-09 13:42:00.181  7023  7023 D AndroidRuntime: readGMSProperty: already setted!!
09-09 13:42:00.181  7023  7023 D AndroidRuntime: propertySet: couldn't set property (it is from app),
09-09 13:42:00.181  7023  7023 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 13:42:00.181  7023  7023 D AndroidRuntime: readGMSProperty: end
09-09 13:42:00.181  7023  7023 D AndroidRuntime: addProductProperty: start
,09-09 13:42:00.311  7023  7023 E AffinityControl: AffinityControl: registerfunction enter,
,09-09 13:42:00.331  7023  7023 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 13:42:00.351  1014  3126 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-09 13:42:00.351  1014  3126 D PackageManager: START PACKAGE DELETE: observer{325842199},
09-09 13:42:00.351  1014  3126 D PackageManager: pkg{<packageName>}
09-09 13:42:00.351  1014  3126 D PackageManager: user{0}
09-09 13:42:00.351  1014  3126 D PackageManager: caller{2000}
09-09 13:42:00.351  1014  3126 D PackageManager: flags{2}
09-09 13:42:00.351  1014  3126 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-09 13:42:00.351  1014  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 13:42:00.351  1014  3126 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
09-09 13:42:00.351  1014  1055 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
09-09 13:42:00.351  1014  3126 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 13:42:00.351  1014  3126 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 13:42:00.351  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-09 13:42:00.351  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-09 13:42:00.351  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 13:42:00.351  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 13:42:00.361  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,09-09 13:42:00.361  1014  1039 I ActivityManager: Killing 6146:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-09 13:42:00.361  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{1055b9ba u0 com.test.thalitest/.MainActivity t128}
,09-09 13:42:00.361  1014  1039 W ActivityManager: mDVFSHelper.acquire()
,09-09 13:42:00.471  3798  4345 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 13:42:00.481  1014  1055 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-09 13:42:00.481  1014  1055 I ActivityManager:   Force finishing activity ActivityRecord{1055b9ba u0 com.test.thalitest/.MainActivity t128 f}
09-09 13:42:00.481  1014  1055 W ActivityManager: Duplicate finish request for ActivityRecord{1055b9ba u0 com.test.thalitest/.MainActivity t128 f}
,09-09 13:42:00.481  1014  1539 I WindowState: WIN DEATH: Window{2f4c9d1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-09 13:42:00.481   257  1052 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,09-09 13:42:00.481   257  1743 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,09-09 13:42:00.501  1014  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also,
,09-09 13:42:00.511  1014  1539 D InputDispatcher: Focus left window: 6146
,09-09 13:42:00.511  1014  1039 D InputDispatcher: Focused application released
,09-09 13:42:00.521  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 13:42:00.521  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:42:00.521  5607  5607 I art     : Explicit concurrent mark sweep GC freed 2557(151KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 758us total 32.674ms
,09-09 13:42:00.541  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 13:42:00.551  1946  2118 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 13:42:00.561  1774  1774 E SamsungIME: mOCRHelper is null
,09-09 13:42:00.561  5401  5401 I art     : Explicit concurrent mark sweep GC freed 655(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 740us total 60.863ms
,09-09 13:42:00.571  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-09 13:42:00.571  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 13:42:00.571  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-09 13:42:00.571  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 13:42:00.581  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 13:42:00.581  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-09 13:42:00.591  1014  1122 V NetworkStats: performPollLocked() took 18ms
,09-09 13:42:00.591  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:42:00.601  1441  1441 D PersonaManager: isKioskContainerExistOnDevice,
,09-09 13:42:00.601  1441  1441 D RegisteredServicesCache: empty dynamic service
,09-09 13:42:00.601  3798  3798 I art     : Explicit concurrent mark sweep GC freed 4512(172KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 1.293ms total 96.172ms
,09-09 13:42:00.611  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-09 13:42:00.611  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 13:42:00 GMT+02:00 2016
09-09 13:42:00.611  1014  3124 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 13:42:00.611  1014  3124 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 13:42:00.611  1014  3124 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:42:00.611  1014  3124 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:42:00.611  1014  3124 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 13:42:00.621  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,09-09 13:42:00.621  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:42:00.621  3666  3666 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 13:42:00.621  1014  1027 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,09-09 13:42:00.621  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-09 13:42:00.621  1014  1027 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 13:42:00.631  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 13:42:00.631  3666  3666 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
09-09 13:42:00.631  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 13:42:00.631  3666  3666 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 13:42:00.641  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:00.641  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:00.641  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:00.641  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:00.641  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-09 13:42:00.641  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-09 13:42:00.651  3666  7034 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 13:42:00.651  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-09 13:42:00.651  7035  7035 E Zygote  : MountEmulatedStorage()
09-09 13:42:00.651  7035  7035 I libpersona: KNOX_SDCARD checking this for 10094
09-09 13:42:00.651  7035  7035 E Zygote  : v2
09-09 13:42:00.651  7035  7035 I libpersona: KNOX_SDCARD not a persona
09-09 13:42:00.661  7035  7035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:00.661  7035  7035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:42:00.661  7035  7035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:42:00.661  1014  1027 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7035 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,09-09 13:42:00.671  3144  3144 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-09 13:42:00.671  3666  7034 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,09-09 13:42:00.681  3666  7034 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 13:42:00.681  1014  1014 I art     : Explicit concurrent mark sweep GC freed 27250(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/42MB, paused 6.313ms total 189.388ms
,09-09 13:42:00.681  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-09 13:42:00.691  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:42:00.691  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 13:42:00.691  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-09 13:42:00.701  1014  1055 I art     : WaitForGcToComplete blocked for 171.798ms for cause Explicit
,09-09 13:42:00.701   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 13:42:00.701  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-09 13:42:00.711  3666  7034 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-09 13:42:00.711  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 13:42:00.711  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:00.711  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:00.711  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:00.731  7050  7050 E Zygote  : MountEmulatedStorage()
09-09 13:42:00.731  7050  7050 E Zygote  : v2
09-09 13:42:00.731  7050  7050 I libpersona: KNOX_SDCARD checking this for 10044
09-09 13:42:00.731  7050  7050 I libpersona: KNOX_SDCARD not a persona
09-09 13:42:00.731  7050  7050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:00.731  7050  7050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:42:00.731  7050  7050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:42:00.731  1014  1039 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7050 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-09 13:42:00.741  7035  7035 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:00.741  7035  7035 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:00.741  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-09 13:42:00.751  1014  1027 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-09 13:42:00.751  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-09 13:42:00.751  1014  3126 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-09 13:42:00.751  1014  3126 D SecContentProvider2: mCursor = null
,09-09 13:42:00.751  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:00.751  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:00.761  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:00.761  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:00.761  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-09 13:42:00.771  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-09 13:42:00.781  7050  7050 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:42:00.781  7050  7050 D ActivityThread: Added TimaKeyStore provider
09-09 13:42:00.781  3144  3144 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-09 13:42:00.781  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
09-09 13:42:00.781  3144  3144 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
09-09 13:42:00.781  3144  3144 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-09 13:42:00.791  7066  7066 E Zygote  : MountEmulatedStorage()
09-09 13:42:00.791  7066  7066 E Zygote  : v2
09-09 13:42:00.791  7066  7066 I libpersona: KNOX_SDCARD checking this for 10149
09-09 13:42:00.791  7066  7066 I libpersona: KNOX_SDCARD not a persona
,09-09 13:42:00.791  7066  7066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:00.791  7066  7066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:42:00.791  7066  7066 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:42:00.791  3666  7034 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-09 13:42:00.801  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7066 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:42:00.811  3666  7034 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-09 13:42:00.811  7066  7066 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:00.811   306   306 I art     : Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 22.529ms
,09-09 13:42:00.821  7066  7066 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:00.821  1014  1026 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 13:42:00.821  1014  1026 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 13:42:00.821  1014  1026 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 13:42:00.821  3666  7034 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-09 13:42:00.831  3144  3144 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-09 13:42:00.841   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 22.204ms
,09-09 13:42:00.861   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.205ms
,09-09 13:42:00.861   257   257 I SurfaceFlinger: id=17 createSurf (720x1280),1 flag=404, YUIInstallC,
09-09 13:42:00.861  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 13:42:00.861  3666  3666 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
09-09 13:42:00.861  6813  7059 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched),
,09-09 13:42:00.871  1014  1214 D InputDispatcher: Focus entered window: 3144
,09-09 13:42:00.871  6813  6813 I art     : Explicit concurrent mark sweep GC freed 658(49KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 761us total 43.540ms
,09-09 13:42:00.871  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 13:42:00.871  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 13:42:00.871  3144  3144 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 13:42:00.891  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,09-09 13:42:00.891  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 13:42:00.891  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-09 13:42:00.891  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-09 13:42:00.891  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-09 13:42:00.891  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-09 13:42:00.901  3144  3144 V ActivityThread: updateVisibility : ActivityRecord{1512de6c token=android.os.BinderProxy@144d4633 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-09 13:42:00.901  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-09 13:42:00.901  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 13:42:00.901  1014  1137 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-09 13:42:00.901  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-09 13:42:00.901  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 13:42:00.901  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 13:42:00.901  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 13:42:00.911  5957  5966 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-09 13:42:00.911  5957  5966 D BadgeProvider: sendNotify, [notify] : null
,09-09 13:42:00.911  5957  5966 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
,09-09 13:42:00.911  7050  7050 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:42:00.911  7050  7050 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 13:42:00.911  7050  7050 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:42:00.911  7050  7050 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:00.911  7050  7050 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 13:42:00.911  7050  7050 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:42:00.911  7050  7050 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:42:00.911  7050  7050 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:42:00.911  5957  5966 D BadgeProvider: update, [BadgeCount] : badgecount=0
,09-09 13:42:00.911  5957  5966 D BadgeProvider: update, [UpdateCount] : 1
,09-09 13:42:00.911  1014  7083 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 13:42:00.911  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 13:42:00.911  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 13:42:00.911  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-09 13:42:00.911  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 13:42:00.911  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-09 13:42:00.921  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 13:42:00.921  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 13:42:00.921  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 13:42:00.921  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-09 13:42:00.921  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 13:42:00.921  1014  1137 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6146 uid 10155
,09-09 13:42:00.921  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-09 13:42:00.921  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 13:42:00.921  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
09-09 13:42:00.921  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 13:42:00.921  1014  2730 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-09 13:42:00.921  7035  7035 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-09 13:42:00.931  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-09 13:42:00.931  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-09 13:42:00.931  7035  7035 D elm:15183: ELMEngine.ELMEngine( context ).
,09-09 13:42:00.931  1774  1774 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-09 13:42:00.941  7035  7035 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-09 13:42:00.941  3144  3144 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@144d4633 time:163158
,09-09 13:42:00.941  1014  3124 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-09 13:42:00.951  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:00.951  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:00.951  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:00.951  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:00.961  1173  1173 D PanelView: There is/are notification(s) 
,09-09 13:42:00.971  7087  7087 E Zygote  : MountEmulatedStorage(),
09-09 13:42:00.971  7087  7087 E Zygote  : v2
09-09 13:42:00.971  7087  7087 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:42:00.971  7087  7087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:00.971  7087  7087 I libpersona: KNOX_SDCARD not a persona
,09-09 13:42:00.971  1173  1173 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-09 13:42:00.971  7087  7087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:42:00.971  7087  7087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:42:00.971  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:42:00.971  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
,09-09 13:42:00.981  1173  1173 D PanelView: There is/are notification(s) 
,09-09 13:42:00.981  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-09 13:42:00.981  1014  3124 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 13:42:00.991  1014  1326 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-09 13:42:00.991  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-09 13:42:00.991  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:42:00.991  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:42:00.991  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:42:00.991  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
09-09 13:42:00.991  1173  1173 D PanelView: There is/are notification(s) 
09-09 13:42:00.991  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true,
,09-09 13:42:00.991  7035  7035 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 13:42:00.991  1014  1044 W ActivityManager: mDVFSHelper.release()
09-09 13:42:00.991  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12a89f6e u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:163208
,09-09 13:42:00.991  7066  7066 D ThemeInfoUtil: getCurrentFestivalName is [null]
,09-09 13:42:01.001  7066  7066 D ThemeInfoUtil: isCurrentFestival = false
,09-09 13:42:01.001  7035  7035 D elm:15183: ElmAgentService : onCreate()
,09-09 13:42:01.001  7035  7098 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-09 13:42:01.001  7035  7098 D elm:15183: MainReceiver.listeningToPackageRemoved()
,09-09 13:42:01.001  7035  7098 D elm:15183: MDMBridge.getInstance()
09-09 13:42:01.001  7035  7098 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 13:42:01.011  3335  3335 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
09-09 13:42:01.011  7087  7087 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:01.011  7087  7087 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:01.011  7035  7098 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 13:42:01.021  3335  3335 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-09 13:42:01.021  3335  3335 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-09 13:42:01.021  3335  3335 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-09 13:42:01.021  3335  3335 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-09 13:42:01.021  3335  3335 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-09 13:42:01.021  3335  3335 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-09 13:42:01.021  3335  3335 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 13:42:01.021  3335  3335 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 13:42:01.021  3335  3335 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,09-09 13:42:01.021  3335  3335 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 13:42:01.021  3335  3335 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372),
09-09 13:42:01.021  3335  3335 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,09-09 13:42:01.021  3335  3335 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 13:42:01.021  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-09 13:42:01.021  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.031  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.031  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.031  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.051  7104  7104 E Zygote  : MountEmulatedStorage()
09-09 13:42:01.051  7104  7104 I libpersona: KNOX_SDCARD checking this for 10152
09-09 13:42:01.051  7104  7104 E Zygote  : v2
09-09 13:42:01.051  7104  7104 I libpersona: KNOX_SDCARD not a persona
09-09 13:42:01.051  7104  7104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:01.051  1173  1173 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
09-09 13:42:01.051  7104  7104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-09 13:42:01.051  7104  7104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:42:01.051  1014  1027 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7104 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
,09-09 13:42:01.061  1014  1055 I art     : Explicit concurrent mark sweep GC freed 11910(787KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 5.195ms total 350.287ms
,09-09 13:42:01.071  7035  7035 D elm:15183: ElmAgentService : onDestroy().
,09-09 13:42:01.081  7104  7104 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:01.081  7104  7104 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:01.101  5792  5792 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 13:42:01.101  5792  5792 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 13:42:01.101  5792  5792 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 13:42:01.101  5792  5792 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-09 13:42:01.111  1014  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-09 13:42:01.111  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.111  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.111  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.111  1014  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.121  7121  7121 E Zygote  : MountEmulatedStorage()
,09-09 13:42:01.131  7121  7121 E Zygote  : v2
09-09 13:42:01.131  7121  7121 I libpersona: KNOX_SDCARD checking this for 10032
09-09 13:42:01.131  7121  7121 I libpersona: KNOX_SDCARD not a persona
,09-09 13:42:01.131  1014  1055 D PackageManager: delete codoeFile: 
,09-09 13:42:01.131  7121  7121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:01.131  7121  7121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:42:01.131  7121  7121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:42:01.131  1014  1483 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7121 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-09 13:42:01.141  1014  1483 I ActivityManager: Killing 5401:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-09 13:42:01.151  1014  1055 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
09-09 13:42:01.151  1014  1055 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-09 13:42:01.151  7104  7104 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-09 13:42:01.161  7087  7087 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-09 13:42:01.161  1014  1342 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-09 13:42:01.161  1014  1342 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 13:42:01.161  1014  1342 W ActivityManager: userId = 0, bbcId = -10000
,09-09 13:42:01.161  1014  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 13:42:01.171  1014  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 13:42:01.171  1014  1055 D PackageManager: result of delete: 1{325842199}
09-09 13:42:01.171  7121  7121 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:01.171  7121  7121 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:01.171  1014  1535 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,09-09 13:42:01.171  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-09 13:42:01.171  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
09-09 13:42:01.171  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 13:42:01.171  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-09 13:42:01.181  7050  7050 D NearbySource: Nearby Source Create!
,09-09 13:42:01.181  7050  7050 D NearbyContext: Nearby Context Create!
,09-09 13:42:01.181  7023  7023 D AndroidRuntime: Shutting down VM
,09-09 13:42:01.181  1014  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 13:42:01.181  1014  1055 D PackageManager: userId{-1}
09-09 13:42:01.181  1014  1055 D PackageManager: andCode{true}
,09-09 13:42:01.191  1014  1326 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-09 13:42:01.191  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.191  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.191  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.191  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.201  7138  7138 E Zygote  : MountEmulatedStorage()
09-09 13:42:01.201  7138  7138 E Zygote  : v2
09-09 13:42:01.201  7138  7138 I libpersona: KNOX_SDCARD checking this for 1000
09-09 13:42:01.201  7138  7138 I libpersona: KNOX_SDCARD not a persona
,09-09 13:42:01.211  1014  1326 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7138 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 13:42:01.211  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:01.211  1014  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 13:42:01.211  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:42:01.211  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:42:01.221  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-09 13:42:01.221  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-09 13:42:01.221  1014  1038 W TextServicesManagerService: no available spell checker services found
,09-09 13:42:01.221   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-09 13:42:01.221   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 13:42:01.231  7050  7050 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-09 13:42:01.231  7050  7050 D SLinkSource: Samsung link source created
,09-09 13:42:01.241  1014  1541 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-09 13:42:01.241  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:01.241  7138  7138 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:01.241  1014  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.241  1014  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.241  1014  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.241  1014  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.241  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.261  7154  7154 E Zygote  : MountEmulatedStorage()
09-09 13:42:01.261  7154  7154 E Zygote  : v2
09-09 13:42:01.261  7154  7154 I libpersona: KNOX_SDCARD checking this for 10156
09-09 13:42:01.261  7154  7154 I libpersona: KNOX_SDCARD not a persona
09-09 13:42:01.261  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:01.261  1014  1541 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7154 uid=10156 gids={50156, 9997} abi=armeabi-v7a,
,09-09 13:42:01.261  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:42:01.261  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:42:01.261  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 13:42:01.271  1014  1326 D PersonaManager: isKioskContainerExistOnDevice
09-09 13:42:01.271  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.291  1014  1541 I ActivityManager: Killing 5531:com.android.vending/u0a28 (adj 15): empty #31
,09-09 13:42:01.291  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:01.291  7154  7154 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:01.301  1014  3124 I ActivityManager: Killing 6226:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,09-09 13:42:01.301  7138  7138 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:42:01.321  7121  7170 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-09 13:42:01.331  1014  3124 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 13:42:01.331  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.331  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.331  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.331  1014  3124 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.351  7173  7173 E Zygote  : MountEmulatedStorage(),
09-09 13:42:01.351  7173  7173 E Zygote  : v2
09-09 13:42:01.351  7173  7173 I libpersona: KNOX_SDCARD checking this for 10035
09-09 13:42:01.351  7173  7173 I libpersona: KNOX_SDCARD not a persona
,09-09 13:42:01.351  7173  7173 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:42:01.351  1014  3124 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7173 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 13:42:01.351  1014  3124 I ActivityManager: Killing 1656:com.google.process.gapps/u0a12 (adj 15): empty #31
,09-09 13:42:01.351  7173  7173 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:42:01.351  7173  7173 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 13:42:01.361  7050  7171 D ContactProvider: getAllContactInfoList Start
09-09 13:42:01.361  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
09-09 13:42:01.361  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.371  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.371  7154  7154 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-09 13:42:01.381  7138  7138 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-09 13:42:01.381  1014  1137 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-09 13:42:01.381  1014  1137 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-09 13:42:01.381  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:42:01.381  7154  7154 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
09-09 13:42:01.381  1014  1539 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 13:42:01.391  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:42:01.391  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:42:01.391  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:42:01.391  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.391  7023  7023 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 13:42:01.401  7154  7154 I TapandpayWidget:Utils: Clear T&P info.,
,09-09 13:42:01.401  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.411  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.411  1014  1326 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-09 13:42:01.411  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.411  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.411  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:42:01.411  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.411  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-09 13:42:01.411  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.411  7173  7173 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:01.411  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.411  7173  7173 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:01.421  7154  7154 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-09 13:42:01.421  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 13:42:01.421  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:42:01.421  6813  6813 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-09 13:42:01.421  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 13:42:01.421  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 13:42:01.431  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,09-09 13:42:01.431  7189  7189 E Zygote  : MountEmulatedStorage()
09-09 13:42:01.431  7189  7189 E Zygote  : v2
09-09 13:42:01.431  7189  7189 I libpersona: KNOX_SDCARD checking this for 10091
09-09 13:42:01.431  7189  7189 I libpersona: KNOX_SDCARD not a persona
,09-09 13:42:01.431  7189  7189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:42:01.431  7189  7189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:42:01.431  1014  1326 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7189 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 13:42:01.431  7189  7189 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 13:42:01.431  1014  1326 I ActivityManager: Killing 6740:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
09-09 13:42:01.451  5957  7082 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-09 13:42:01.451  5957  7082 D BadgeProvider: sendNotify, [notify] : null
09-09 13:42:01.451  5957  7082 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-09 13:42:01.451  5957  7082 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 13:42:01.451  5957  7082 D BadgeProvider: update, [UpdateCount] : 1
09-09 13:42:01.451  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 13:42:01.451  1014  1326 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
09-09 13:42:01.451  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-09 13:42:01.451  7121  7170 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-09 13:42:01.451  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-09 13:42:01.451  7121  7170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:42:01.451  7121  7170 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:42:01.451  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.451  7121  7170 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 13:42:01.451  7121  7170 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-09 13:42:01.461  7050  7050 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-09 13:42:01.461  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.461  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.461  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.461  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.461  7121  7170 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-09 13:42:01.461  7121  7170 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 13:42:01.461  7121  7170 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:42:01.461  7121  7170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:42:01.461  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.461  7121  7170 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
09-09 13:42:01.471  7189  7189 D TimaK,eyStoreProvider: TimaSignature is unavailable
09-09 13:42:01.471  7189  7189 D ActivityThread: Added TimaKeyStore provider
09-09 13:42:01.471  7205  7205 E Zygote  : MountEmulatedStorage()
09-09 13:42:01.471  7205  7205 E Zygote  : v2
09-09 13:42:01.471  7205  7205 I libpersona: KNOX_SDCARD checking this for 10160
09-09 13:42:01.471  7205  7205 I libpersona: KNOX_SDCARD not a persona
09-09 13:42:01.471  7205  7205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 13:42:01.471  7205  7205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:42:01.471  7205  7205 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 13:42:01.471  1014  1326 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7205 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
09-09 13:42:01.481  1014  1326 I ActivityManager: Killing 6758:com.google.android.apps.maps/u0a107 (adj 15): empty #31
09-09 13:42:01.481  1014  1137 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
09-09 13:42:01.481  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.481  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.481  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.481  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.481  7121  7170 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:42:01.481  7121  7170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:42:01.481  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.491  7205  7205 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:42:01.491  7205  7205 D ActivityThread: Added TimaKeyStore provider
09-09 13:42:01.501  7219  7219 E Zygote  : MountEmulatedStorage()
09-09 13:42:01.501  7219  7219 E Zygote  : v2
09-09 13:42:01.501  7219  7219 I libpersona: KNOX_SDCARD checking this for 10046
09-09 13:42:01.501  7219  7219 I libpersona: KNOX_SDCARD not a persona
09-09 13:42:01.501  7219  7219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:01.501  7121  7170 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 13:42:01.501  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.501  7121  7170 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 13:42:01.501  7219  7219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 13:42:01.501  1014  1137 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7219 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-09 13:42:01.501  7219  7219 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 13:42:01.501  1014  1137 I ActivityManager: Killing 6354:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,09-09 13:42:01.521  7121  7170 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:42:01.521  7121  7170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:42:01.521  7121  7170 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:42:01.521  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.521  7121  7170 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-09 13:42:01.521  7121  7170 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 13:42:01.521  7121  7170 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:42:01.521  7121  7170 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:42:01.531  7050  7171 D ContactProvider: getAllContactInfoList End
,09-09 13:42:01.531  7050  7171 I syncContacts: thread: 1158, sync time = 207
,09-09 13:42:01.541  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.541  7121  7170 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:42:01.541  7121  7170 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:42:01.541  7219  7219 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 13:42:01.541  7219  7219 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:01.561  7121  7170 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-09 13:42:01.561  7121  7170 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:42:01.561  7121  7170 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:42:01.561  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.561  7121  7170 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:42:01.561  7173  7236 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-09 13:42:01.561  7173  7236 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-09 13:42:01.571  1014  1137 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,09-09 13:42:01.571  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.571  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.571  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 13:42:01.571  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 13:42:01.571  7121  7170 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-09 13:42:01.571  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.571  7121  7170 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 13:42:01.571  7121  7170 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:42:01.581  7205  7205 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 13:42:01.591  7121  7170 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-09 13:42:01.591  7121  7170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:42:01.591  7121  7170 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:42:01.591  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.591  7121  7170 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 13:42:01.591  7238  7238 E Zygote  : MountEmulatedStorage()
09-09 13:42:01.591  7238  7238 E Zygote  : v2
09-09 13:42:01.591  7238  7238 I libpersona: KNOX_SDCARD checking this for 10038
09-09 13:42:01.591  7238  7238 I libpersona: KNOX_SDCARD not a persona
09-09 13:42:01.591  7219  7219 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-09 13:42:01.591  7219  7219 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 13:42:01.591  7219  7219 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:42:01.591  7219  7219 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.591  7219  7219 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 13:42:01.591  7219  7219 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 13:42:01.601  1014  1137 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7238 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,09-09 13:42:01.601  1014  1137 I ActivityManager: Killing 6369:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,09-09 13:42:01.601  7238  7238 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 13:42:01.611  7238  7238 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 13:42:01.611  7238  7238 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 13:42:01.611  7121  7170 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-09 13:42:01.611  7121  7170 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-09 13:42:01.621  7173  7236 D SPPClientService: PushLog.txt file is not deleted.
09-09 13:42:01.621  7173  7236 D SPPClientService: PushLog.txt file is not deleted.
09-09 13:42:01.621  7173  7236 D SPPClientService: ============PushLog. stop!
,09-09 13:42:01.631  7205  7205 D [0]UMC:UMCContentProvider: @onCreate
,09-09 13:42:01.631  1474  1474 D Launcher.Model: reloadBadges entered.
,09-09 13:42:01.631  1474  1474 D Launcher.Model: reloadBadges entered.
,09-09 13:42:01.631  7173  7173 W FileUtils: Failed to chmod(/data/data/com.sec.spp.push/databases/push_noti_db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-09 13:42:01.631  7205  7205 D [0]UMC:Core: onCreate(): 
09-09 13:42:01.631  7205  7205 D [0]UMC:Core: @isManagedProfileUser
09-09 13:42:01.631  7205  7205 D [0]UMC:Core: userId: 0
,09-09 13:42:01.631  7205  7205 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13},
09-09 13:42:01.631  7205  7205 D [0]UMC:Core: userInfo.isManagedProfile() : false
09-09 13:42:01.641  7238  7238 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 13:42:01.641  7238  7238 D ActivityThread: Added TimaKeyStore provider
,09-09 13:42:01.661  7121  7170 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 13:42:01.661  7121  7170 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-09 13:42:01.661  7121  7170 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 13:42:01.661  7121  7170 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 13:42:01.661  7121  7170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 13:42:01.661  7121  7170 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:42:01.661  7238  7238 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 13:42:01.661  7238  7238 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 13:42:01.671  7189  7189 E PhotosPlugin: Loading PhotosPlugin
,09-09 13:42:01.671  7205  7205 D [0]UMC:DeviceInfo: USA==US==
,09-09 13:42:01.671  7219  7219 D Mms/MmsApp: [start]    onCreate() consume time = 0.0

```
