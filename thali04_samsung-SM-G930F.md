#### Test 13058906542a01a0_thali04_samsung-SM-G930F Logs


```
--------- beginning of main
,07-18 08:07:47.176  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:07:47.176  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
--------- beginning of system
07-18 08:07:47.504  4656  4656 D io_stats: !@   8,0 r 23915 2207192 w 4164 70636 d 570 19416 f 1785 1785 iot 9760 9314 th 506648 0 0 pt 0 inp 0 0 152.201
07-18 08:07:47.576  3682  5689 D SSRM:f  : SIOP:: AP = 270, PST = 284 (W:10), CP = 228, CUR = 150, LCD = 57
07-18 08:07:47.949  9594  9594 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9594 | app_process
07-18 08:07:47.949  9594  9594 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-18 08:07:47.957  9594  9594 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-18 08:07:47.957  9594  9594 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-18 08:07:47.965  9594  9594 D AndroidRuntime: CheckJNI is OFF
07-18 08:07:47.965  9594  9594 D AndroidRuntime: addProductProperty: start
07-18 08:07:48.036  9594  9594 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-18 08:07:48.036  9594  9594 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-18 08:07:48.059  9594  9594 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-18 08:07:48.059  9594  9594 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-18 08:07:48.059  9594  9594 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-18 08:07:48.194  9594  9594 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-18 08:07:48.247  9594  9594 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-18 08:07:48.285  9594  9594 I Enhanced Zygote ASLR: DISABLED!
07-18 08:07:48.286  9594  9594 I Radio-JNI: register_android_hardware_Radio DONE
07-18 08:07:48.293  9594  9594 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-18 08:07:48.294  9594  9594 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-18 08:07:48.295  9594  9594 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-18 08:07:48.311  9594  9594 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-18 08:07:48.334  3682  4930 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.example.hello/com.example.hello.MainActivity}} from uid 2000 on display 0
07-18 08:07:48.345  3682  4930 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-18 08:07:48.348  3682  4930 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3682  pkgName : AMS_RESUME@CPU_MIN@7
07-18 08:07:48.351  3682  4930 D ActivityManager: mActivityResumeBooster.acquire()
07-18 08:07:48.353  3682  4930 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{8495a8fd0 #9 A=com.example.hello U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-18 08:07:48.353  3682  4930 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{8495a8fd0 #9 A=com.example.hello U=0 StackId=1 sz=1}
07-18 08:07:48.358  3682  3799 D WindowManager: addWindow: android.view.ViewRootImpl$W@2e80c87 displayId=0
07-18 08:07:48.358  3682  3799 D InputTransport: Input channel constructed: fd=453
07-18 08:07:48.358  3682  3799 D InputTransport: Input channel constructed: fd=454
07-18 08:07:48.359  3682  3799 D ViewRootImpl@51384c6[hello]: setView = DecorView@8006fdd[hello] touchMode=true
07-18 08:07:48.359  3682  4930 D InputDispatcher: Focused application set to: xxxx
07-18 08:07:48.360  3682  4930 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{8495a8fd0 #9 A=com.example.hello U=0 StackId=1 sz=1} next=ActivityRecord{d460e33d0 u0 com.example.hello/.MainActivity t9} mFocusedStack=ActivityStack{8690c5dd0 stackId=1, 2 tasks}
07-18 08:07:48.360  3682  4930 D MountService: getExternalStorageMountMode : 1
07-18 08:07:48.360  3682  4930 D MountService: getExternalStorageMountMode : 3
07-18 08:07:48.360  3682  4930 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10054, packageName : com.example.hello
07-18 08:07:48.366  3682  3799 V WindowManager: Relayout Window{808a7b4d0 u0 Starting com.example.hello}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-18 08:07:48.366  3110  3110 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, iello
07-18 08:07:48.378  9604  9604 E Zygote  : v2
07-18 08:07:48.378  9604  9604 I libpersona: KNOX_SDCARD checking this for 10054
07-18 08:07:48.378  9604  9604 I libpersona: KNOX_SDCARD not a persona
07-18 08:07:48.378  9604  9604 E Zygote  : accessInfo : 0
07-18 08:07:48.379  3682  4930 I ActivityManager: Start proc 9604:com.example.hello/u0a54 for activity com.example.hello/.MainActivity
07-18 08:07:48.384  9604  9604 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-18 08:07:48.384  3682  3799 D WindowManager: finishDrawingWindow: Window{808a7b4d0 u0 Starting com.example.hello} mDrawState=DRAW_PENDING
07-18 08:07:48.385  9594  9594 D AndroidRuntime: Shutting down VM
07-18 08:07:48.385  9604  9604 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.hello 
07-18 08:07:48.399  3682  3799 V WindowManager: Now policy hidden: Window{808a7b4d0 u0 Starting com.example.hello}
07-18 08:07:48.410  9604  9604 D TimaKeyStoreProvider: TimaSignature is unavailable
07-18 08:07:48.410  9604  9604 D ActivityThread: Added TimaKeyStore provider
07-18 08:07:48.412  3682  4716 I ActivityManager: DSS on for com.example.hello and scale is 1.0
07-18 08:07:48.414  3682  4716 I WindowManager: Failed to capture screenshot of Token{53c1aa3 ActivityRecord{36cc9d2d0 u0 com.samsung.android.MtpApplication/.USBConnection t8}} appWin=Window{3574b82d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-18 08:07:48.414  9594  9594 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-18 08:07:48.414  9594  9594 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-18 08:07:48.414  9594  9594 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-18 08:07:48.414  9594  9594 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-18 08:07:48.419  3682  4962 V WindowManager: Relayout Window{3574b82d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-18 08:07:48.422  3682  3953 V WindowManager: Relayout Window{57d1a61d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-18 08:07:48.424  3682  4716 D GameManagerService: sem_perfomance_mode: 0
07-18 08:07:48.424  3682  3682 D GameManagerService: NotifyRunnable. pkg: com.example.hello, type: 4, isMinimized: false, isTunableApp: false
07-18 08:07:48.424  3682  3682 D GameManagerService: unexpected mPrevNotiType: -1
07-18 08:07:48.427  4957  4957 D Launcher: onTrimMemory. Level: 20
07-18 08:07:48.430  3682  4716 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-18 08:07:48.430  3682  4716 D GameManagerService: sem_perfomance_mode: 0
07-18 08:07:48.434  3682  3799 D ViewRootImpl@51384c6[hello]: MSG_RESIZED: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-18 08:07:48.435  3682  5689 D GameManagerService: identifyGamePackage. com.example.hello
07-18 08:07:48.435  3682  5689 D GameManagerService: identifyGamePackage. com.example.hello
07-18 08:07:48.437  4780  4793 D ForegroundUtils: could not check pending caller
07-18 08:07:48.437  4780  4793 D ForegroundUtils: could not check pending caller
07-18 08:07:48.437  4780  4793 D ForegroundUtils: could not check pending caller
07-18 08:07:48.441  3682  4554 V WindowManager: Relayout Window{57d1a61d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity EXITING}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-18 08:07:48.445  3682  4181 V WindowManager: Relayout Window{5a56df7d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,07-18 08:07:48.448  9604  9604 W System  : ClassLoader referenced unknown path: /data/app/com.example.hello-1/lib/arm64
,07-18 08:07:48.448  3682  5689 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 08:07:48.452  3682  5689 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 08:07:48.454  3682  3799 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.AppWindowToken.destroySurfaces:412 com.android.server.wm.AppWindowToken.destroySurfaces:376 com.android.server.wm.WindowStateAnimator.finishExit:654 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:564 com.android.server.wm.WindowAnimator.updateWindowsLocked:439 
,07-18 08:07:48.455  3110  4560 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-18 08:07:48.455  3110  3121 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
,07-18 08:07:48.456  3682  4929 V WindowManager: Relayout Window{3574b82d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-18 08:07:48.459  9604  9604 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-18 08:07:48.459  3682  3799 V WindowManager: Relayout Window{808a7b4d0 u0 Starting com.example.hello}: viewVisibility=0 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-18 08:07:48.469  3682  3799 D WindowManager: finishDrawingWindow: Window{808a7b4d0 u0 Starting com.example.hello} mDrawState=HAS_DRAWN
,07-18 08:07:48.475  9604  9604 I CordovaLog: Changing log level to DEBUG(3)
07-18 08:07:48.475  9604  9604 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-18 08:07:48.475  9604  9604 D CordovaActivity: CordovaActivity.onCreate()
,07-18 08:07:48.483  9604  9604 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm64
,07-18 08:07:48.488  9604  9604 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-18 08:07:48.529  9604  9604 I cr_LibraryLoader: Time to load native libraries: 3 ms (timestamps 3224-3227)
07-18 08:07:48.530  9604  9604 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-18 08:07:48.540  9604  9604 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-18 08:07:48.543  9604  9604 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-18 08:07:48.551  9604  9604 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-18 08:07:48.562  3682  3991 D MdnieScenarioControlService:  packageName : com.example.hello    className : com.example.hello.MainActivity
,07-18 08:07:48.693  3682  4855 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10054
,07-18 08:07:48.693  3682  4855 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-18 08:07:48.694  3682  3682 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
07-18 08:07:48.695  3682  3916 I KnoxVpnEngineService: vpn handle : Message received
,07-18 08:07:48.751  9604  9604 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-18 08:07:48.757  9604  9604 D PluginManager: init()
,07-18 08:07:48.761  9604  9604 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-18 08:07:48.772  9604  9604 I cr_Ime  : ImeThread is enabled.
,07-18 08:07:48.774  9604  9642 W cr_media: Requires BLUETOOTH permission
,07-18 08:07:48.786  9604  9604 D CordovaActivity: Started the activity.
,07-18 08:07:48.788  9604  9604 D CordovaActivity: Resumed the activity.
,07-18 08:07:48.801  3682  3922 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@6e74c6f displayId=0
,07-18 08:07:48.802  3682  3922 D InputTransport: Input channel constructed: fd=455
07-18 08:07:48.802  3682  3922 D InputTransport: Input channel constructed: fd=456
,07-18 08:07:48.804  3682  3922 D InputTransport: Input channel destroyed: fd=456
,07-18 08:07:48.805  9604  9604 D InputTransport: Input channel constructed: fd=98
,07-18 08:07:48.805  9604  9604 D ViewRootImpl@b534975[MainActivity]: setView = DecorView@8561d0a[MainActivity] touchMode=true
07-18 08:07:48.805  3682  4554 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-18 08:07:48.805  3682  4554 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-18 08:07:48.806  3682  3682 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-18 08:07:48.806  9604  9604 D CordovaActivity: Paused the activity.
,07-18 08:07:48.807  3682  3682 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-18 08:07:48.809  3682  3765 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-18 08:07:48.827  3682  4848 V WindowManager: Relayout Window{8f33605d0 u0 com.example.hello/com.example.hello.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-18 08:07:48.828  3110  3110 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-18 08:07:48.838  9604  9650 I OpenGLRenderer: Initialized EGL, version 1.4
07-18 08:07:48.838  9604  9650 D OpenGLRenderer: Swap behavior 1
,07-18 08:07:48.841  9604  9650 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.example.hello
,07-18 08:07:48.846  9604  9650 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-18 08:07:48.847  9604  9604 D CordovaActivity: Stopped the activity.
,07-18 08:07:48.848  9604  9604 D ViewRootImpl@b534975[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-18 08:07:48.852  3682  3799 V WindowManager: Now policy hidden: Window{8f33605d0 u0 com.example.hello/com.example.hello.MainActivity}
,07-18 08:07:48.925  3682  4554 D WindowManager: finishDrawingWindow: Window{8f33605d0 u0 com.example.hello/com.example.hello.MainActivity} mDrawState=DRAW_PENDING
,07-18 08:07:48.933  3682  3799 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
,07-18 08:07:48.933  3682  3682 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
,07-18 08:07:48.935  3682  3682 I KnoxTimeoutHandler: SD activityfalse
07-18 08:07:48.935  3682  3682 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
,07-18 08:07:48.937  3682  3799 I ActivityManager: Displayed com.example.hello/.MainActivity: +505ms (total +576ms)
07-18 08:07:48.937  3682  3765 D ActivityManager: mActivityResumeBoosterTail.acquire()
,07-18 08:07:48.938  3682  3799 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3682  tag : AMS_RESUME@CPU_MIN@7
07-18 08:07:48.938  3682  3799 D ActivityManager: mActivityResumeBooster.release()
07-18 08:07:48.938  3682  3799 D ViewRootImpl@51384c6[hello]: dispatchDetachedFromWindow
,07-18 08:07:48.939  3682  3799 I WindowManager: Destroying surface Surface(name=Starting com.example.hello) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
07-18 08:07:48.939  3110  4560 I SurfaceFlinger: id=15 Removed iello (3/5)
07-18 08:07:48.940  3110  3887 I SurfaceFlinger: id=15 Removed iello (-2/5)
,07-18 08:07:48.940  3682  3765 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3682  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
,07-18 08:07:48.943  3682  3799 D InputTransport: Input channel destroyed: fd=453
,07-18 08:07:48.943  3682  3799 D InputTransport: Input channel destroyed: fd=454
,07-18 08:07:48.949  9604  9604 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,07-18 08:07:48.963  9604  9656 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-18 08:07:48.978  9604  9656 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-18 08:07:48.978  9604  9656 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-18 08:07:48.979  9604  9656 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-18 08:07:48.980  9604  9656 W AudioCapabilities: Unsupported mime audio/x-ima
,07-18 08:07:48.981  9604  9656 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-18 08:07:48.981  9604  9656 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-18 08:07:48.981  9604  9656 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.984  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:48.985  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-18 08:07:48.991  9604  9656 W VideoCapabilities: Unsupported mime video/wvc1
,07-18 08:07:48.992  9604  9656 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-18 08:07:48.995  9604  9656 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-18 08:07:48.995  9604  9656 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-18 08:07:48.995  9604  9656 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-18 08:07:48.997  9604  9656 W VideoCapabilities: Unsupported mime video/wvc1
,07-18 08:07:48.997  9604  9656 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-18 08:07:48.998  9604  9656 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-18 08:07:49.000  9604  9656 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-18 08:07:49.001  9604  9656 W VideoCapabilities: Unsupported mime video/mp43
,07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 08:07:49.003  9604  9656 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-18 08:07:49.006  9604  9656 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-18 08:07:49.006  9604  9656 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-18 08:07:49.006  9604  9656 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-18 08:07:49.019  9604  9656 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-18 08:07:49.030  9604  9656 W VideoCapabilities: Unsupported mime video/sorenson
,07-18 08:07:49.049  9604  9656 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.example.hello
,07-18 08:07:49.066  9604  9604 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9604
,07-18 08:07:49.094  9604  9604 D SystemWebChromeClient: file:///android_asset/www/index.html: Line 10 : The key "target-densitydpi" is not supported.
07-18 08:07:49.094  9604  9604 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,07-18 08:07:49.095  9604  9661 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,07-18 08:07:49.151  9604  9604 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-18 08:07:49.191  9604  9604 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-18 08:07:49.240  3682  3682 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3682  tag : AMS_RESUME_TAIL@CPU_MIN@13
,07-18 08:07:50.195  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:07:50.195  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:07:51.250  3682  3922 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-18 08:07:51.369  3682  3805 I PowerManagerService: [PWL] On : 0 (156066 ms ago)
07-18 08:07:51.369  3682  3805 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-18 08:07:52.510  4656  4656 D io_stats: !@   8,0 r 24719 2268664 w 4182 71000 d 571 19420 f 1824 1824 iot 10060 9569 th 493944 0 0 pt 0 inp 0 0 157.206
,07-18 08:07:53.217  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:07:53.218  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:07:53.783  3301  3785 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 08:07:54.438  3682  5689 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 08:07:56.251  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:07:56.251  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:07:57.515  4656  4656 D io_stats: !@   8,0 r 24719 2268664 w 4206 71184 d 573 19884 f 1825 1825 iot 10060 9573 th 497328 0 0 pt 0 inp 0 0 162.212
,07-18 08:07:57.603  3682  5689 D SSRM:f  : SIOP:: AP = 270, PST = 279 (W:14), CP = 229, CUR = 144, LCD = 57
,07-18 08:07:58.333  3301  3785 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 08:07:58.372  3682  3795 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-18 08:07:58.387  3682  3795 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-18 08:07:58.387  3682  3795 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-18 08:07:58.931  3682  3682 D UsbMonitorService: readUsbState++
,07-18 08:07:58.933  3682  3682 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-18 08:07:58.935  3682  3682 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-18 08:07:58.935  3682  3682 D UsbMonitorService: Posting Message again
,07-18 08:07:59.285  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:07:59.285  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:08:00.000  3682  3865 D SamsungAlarmManager: Expired : 8
,07-18 08:08:00.002  3682  3865 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{6f4de26 type 3 when 164698 android}
,07-18 08:08:00.011  3682  3682 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170718T080900 - CU:1000/CP:3682
,07-18 08:08:00.016  4071  4071 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-18 08:08:00.017  4071  4071 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-18 08:08:00.017  4071  4071 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-18 08:08:00.041  4071  4071 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-18 08:08:00.041  4071  4071 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-18 08:08:00.045  4071  4071 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-18 08:08:00.058  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-18 08:08:00.062  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 08:08:00.069  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : start
07-18 08:08:00.072  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 08:08:00.091  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-18 08:08:00.093  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 08:08:00.095  4071  4071 V hong    : mid yDiff = 438
07-18 08:08:00.095  4071  4071 V hong    : mid yDiff = 438
07-18 08:08:00.096  4071  4071 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-18 08:08:00.096  4071  4071 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-18 08:08:00.108  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-18 08:08:00.110  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 08:08:00.124  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-18 08:08:00.126  4071  4071 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 08:08:00.141  4071  4071 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-18 08:08:00.145  4071  4071 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-18 08:08:00.151  5091  5091 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-18 08:08:00.153  5091  5091 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-18 08:08:00.157  5091  5091 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-18 08:08:00.163  5091  5091 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-18 08:08:00.164  5091  5091 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-18 08:08:00.165  5091  5091 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-18 08:08:00.166  5091  5091 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-18 08:08:00.167  5091  5091 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-18 08:08:00.173  5091  5091 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
07-18 08:08:00.174  5091  5091 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C467D93EBE52B1955DBAA50EE9DDB94F9AA30AEA37AD65F10FBC24301C034C406C5327DB85EF8F83DF3AD3BE8A2EECF8D]}
07-18 08:08:00.175  5091  5091 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-18 08:08:01.077  3682  4471 E Watchdog: !@Sync 5 [18_lip_08_08_01.077]
,07-18 08:08:01.311  3682  3930 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-18 08:08:02.318  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:02.319  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:08:02.521  4656  4656 D io_stats: !@   8,0 r 24719 2268664 w 4209 71300 d 573 19884 f 1826 1826 iot 10060 9575 th 497332 0 0 pt 0 inp 0 0 167.217
,07-18 08:08:05.350  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:05.351  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:08:07.526  4656  4656 D io_stats: !@   8,0 r 24719 2268664 w 4218 71392 d 574 19956 f 1827 1827 iot 10060 9577 th 497332 0 0 pt 0 inp 0 0 172.223
,07-18 08:08:07.629  3682  5689 D SSRM:f  : SIOP:: AP = 270, PST = 274 (W:14), CP = 228, CUR = 141, LCD = 57
,07-18 08:08:08.374  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:08.374  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:08:11.385  3682  4554 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-18 08:08:11.386  3682  4554 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
,07-18 08:08:11.386  3682  4554 D BatteryService: online:4, current avg:140, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:137
07-18 08:08:11.387  3682  3682 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-18 08:08:11.406  3682  3682 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-18 08:08:11.406  3682  3682 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-18 08:08:11.412  4071  4071 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-18 08:08:11.412  4071  4071 D KeyguardUpdateMonitor: handleBatteryUpdate
07-18 08:08:11.413  3682  3682 D GameManagerService: new battery level: 100
07-18 08:08:11.413  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:11.413  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:08:11.418  4071  4071 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-18 08:08:11.425  4071  4071 D BatteryMeterDrawable: isSomethingChanged - false
07-18 08:08:11.425  4058  4058 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-18 08:08:11.426  4071  4071 D BatteryMeterDrawable: isSomethingChanged - false
07-18 08:08:11.426  4058  4711 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-18 08:08:11.429  4071  4071 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-18 08:08:12.532  4656  4656 D io_stats: !@   8,0 r 24719 2268664 w 4228 71432 d 574 19956 f 1828 1828 iot 10060 9579 th 497304 0 0 pt 0 inp 0 0 177.228
,07-18 08:08:13.383  3301  3785 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 08:08:14.446  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:14.447  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:08:17.475  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:17.475  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 08:08:17.537  4656  4656 D io_stats: !@   8,0 r 24719 2268664 w 4231 71484 d 575 19960 f 1830 1830 iot 10060 9581 th 497304 0 0 pt 0 inp 0 0 182.234
,07-18 08:08:17.655  3682  5689 D SSRM:f  : SIOP:: AP = 270, PST = 272 (W:14), CP = 226, CUR = 79, LCD = 57
,07-18 08:08:18.360  3301  3785 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 08:08:20.509  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:20.509  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 08:08:22.543  4656  4656 D io_stats: !@   8,0 r 24719 2268664 w 4237 71516 d 575 19960 f 1830 1830 iot 10060 9582 th 497280 0 0 pt 0 inp 0 0 187.239
,07-18 08:08:23.535  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:23.536  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 08:08:26.567  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:26.568  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 08:08:27.683  3682  5689 D SSRM:f  : SIOP:: AP = 260, PST = 270 (W:14), CP = 225, CUR = 31, LCD = 57
,07-18 08:08:28.936  3682  3682 D UsbMonitorService: readUsbState++
,07-18 08:08:28.938  3682  3682 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-18 08:08:28.939  3682  3682 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-18 08:08:28.939  3682  3682 D UsbMonitorService: Posting Message again
,07-18 08:08:29.603  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:29.603  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 08:08:31.079  3682  4471 E Watchdog: !@Sync 6 [18_lip_08_08_31.078]
,07-18 08:08:31.389  3682  3805 I PowerManagerService: [PWL] On : 0 (196087 ms ago)
07-18 08:08:31.389  3682  3805 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-18 08:08:32.633  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:32.633  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 08:08:33.383  3301  3785 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 08:08:34.062  4936  5009 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-18 08:08:34.062  4936  5009 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-18 08:08:34.062  4936  5009 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-18 08:08:34.070  4936  5009 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60106 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-18 08:08:35.248  3682  3865 D SamsungAlarmManager: Expired : 4
,07-18 08:08:35.253  3682  3865 D SamsungAlarmManager: setInexact Intent (T:1/F:8/AC:false) 20170808T114406 - CU:1000/CP:3682
07-18 08:08:35.253  3682  3865 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170718T081454, SetElapsed=579268, nowELAPSED=199951
07-18 08:08:35.254  3682  3865 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170718T080900, SetElapsed=224698, nowELAPSED=199952
,07-18 08:08:35.255  3682  3865 V SamsungAlarmManager: Sending to uid : 10019 action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE alarm=Alarm{bfa1014 type 2 when 161130 com.google.android.gms}
,07-18 08:08:35.260  3682  3865 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@5851b2e alarm=Alarm{dd720bd type 2 when 165088 android}
,07-18 08:08:35.261  3682  3865 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@8e9e85c alarm=Alarm{fc0b6b2 type 2 when 199946 android}
07-18 08:08:35.261  3682  3865 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@b88c6cf alarm=Alarm{c643603 type 2 when 199946 android}
07-18 08:08:35.262  3682  3865 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@617afad alarm=Alarm{8721980 type 2 when 199946 android}
07-18 08:08:35.262  3682  3865 V SamsungAlarmManager: Sending to uid : 1000 action=com.mobeam.barcodeService.UPLOAD_BEAM_RECORD alarm=Alarm{55a0bb9 type 1 when 1500358058770 com.mobeam.barcodeService}
,07-18 08:08:35.265  3682  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-18 08:08:35.269  4287  4287 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-18 08:08:35.270  4287  4287 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-18 08:08:35.287  3682  3865 D MountService: getExternalStorageMountMode : 1
07-18 08:08:35.287  3682  3865 D MountService: getExternalStorageMountMode : 3
07-18 08:08:35.287  3682  3865 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.mobeam.barcodeService
,07-18 08:08:35.290  4287  4287 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-18 08:08:35.316  9672  9672 E Zygote  : v2
07-18 08:08:35.316  9672  9672 I libpersona: KNOX_SDCARD checking this for 1000
07-18 08:08:35.316  9672  9672 I libpersona: KNOX_SDCARD not a persona
07-18 08:08:35.317  9672  9672 E Zygote  : accessInfo : 0
,07-18 08:08:35.319  3682  3865 I ActivityManager: Start proc 9672:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-18 08:08:35.324  3682  3682 D SamsungAlarmManager: setInexact Listener (T:2/F:0/AC:false) 20170718T090544 - CU:1000/CP:3682
,07-18 08:08:35.326  3682  3928 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170718T081043 - CU:1000/CP:3682
,07-18 08:08:35.327  3682  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170718T081043, SetElapsed=327963, nowELAPSED=200025
07-18 08:08:35.327  9672  9672 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-18 08:08:35.329  3682  3958 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170718T080850 - CU:1000/CP:3682
07-18 08:08:35.329  9672  9672 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.mobeam.barcodeService 
07-18 08:08:35.329  3682  3958 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170718T080850, SetElapsed=214974, nowELAPSED=200027
07-18 08:08:35.332  3682  3682 D SamsungAlarmManager: setInexact Listener (T:2/F:0/AC:false) 20170718T090544 - CU:1000/CP:3682
,07-18 08:08:35.333  3682  3719 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4740 / op:PendingIntent{9c46a0a: PendingIntentRecord{5f7f121 com.google.android.gms broadcastIntent}}
,07-18 08:08:35.337  3682  3682 D SamsungAlarmManager: setInexact Listener (T:2/F:0/AC:false) 20170718T090544 - CU:1000/CP:3682
,07-18 08:08:35.354  9672  9672 D TimaKeyStoreProvider: TimaSignature is unavailable
07-18 08:08:35.354  9672  9672 D ActivityThread: Added TimaKeyStore provider
,07-18 08:08:35.357  3682  4554 I ActivityManager: DSS on for com.mobeam.barcodeService and scale is 1.0
,07-18 08:08:35.381  9672  9672 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,07-18 08:08:35.395  9672  9672 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-18 08:08:35.427  3682  4929 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T090553 - CU:10019/CP:4740
,07-18 08:08:35.487  3682  3937 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T090553 - CU:10019/CP:4740
,07-18 08:08:35.498  3682  4929 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4740 / op:PendingIntent{5471cd6: PendingIntentRecord{5f7f121 com.google.android.gms broadcastIntent}}
,07-18 08:08:35.588  3682  3695 I art     : Background sticky concurrent mark sweep GC freed 219535(11MB) AllocSpace objects, 110(2MB) LOS objects, 26% free, 41MB/56MB, paused 3.699ms total 120.506ms
,07-18 08:08:35.613  3682  4930 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T090616 - CU:10019/CP:4740
,07-18 08:08:35.633  3682  4855 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T090616 - CU:10019/CP:4740
,07-18 08:08:35.646  3682  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 08:08:35.647  3682  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 08:08:35.659  3682  4856 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T090616 - CU:10019/CP:4740
,07-18 08:08:37.558  4656  4656 D io_stats: !@   8,0 r 24726 2268704 w 4249 71680 d 577 19968 f 1836 1836 iot 10080 9591 th 496328 0 0 pt 0 inp 0 0 202.254
,07-18 08:08:37.709  3682  5689 D SSRM:f  : SIOP:: AP = 260, PST = 269 (W:14), CP = 224, CUR = 12, LCD = 57

```
