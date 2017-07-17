#### Test 13058906585a01a3_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,07-17 14:51:37.776  3683  5526 D SSRM:f  : SIOP:: AP = 250, PST = 270 (W:10), CP = 213, CUR = 148, LCD = 57
--------- beginning of main
07-17 14:51:38.285  9362  9362 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9362 | app_process
07-17 14:51:38.285  9362  9362 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-17 14:51:38.291  9362  9362 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-17 14:51:38.291  9362  9362 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-17 14:51:38.293  9362  9362 D AndroidRuntime: CheckJNI is OFF
07-17 14:51:38.294  9362  9362 D AndroidRuntime: addProductProperty: start
07-17 14:51:38.334  9362  9362 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-17 14:51:38.334  9362  9362 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-17 14:51:38.349  9362  9362 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-17 14:51:38.349  9362  9362 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-17 14:51:38.349  9362  9362 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-17 14:51:38.349  4520  4520 D io_stats: !@   8,0 r 23855 2210612 w 3953 66592 d 527 18660 f 1789 1789 iot 10060 9222 th 502052 0 0 pt 0 inp 0 0 151.700
07-17 14:51:38.396  9362  9362 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-17 14:51:38.413  9362  9362 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-17 14:51:38.433  9362  9362 I Enhanced Zygote ASLR: DISABLED!
07-17 14:51:38.433  9362  9362 I Radio-JNI: register_android_hardware_Radio DONE
07-17 14:51:38.436  9362  9362 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-17 14:51:38.436  9362  9362 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-17 14:51:38.437  9362  9362 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-17 14:51:38.445  9362  9362 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-17 14:51:38.460  3683  3906 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.example.hello/com.example.hello.MainActivity}} from uid 2000 on display 0
07-17 14:51:38.470  3683  3906 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-17 14:51:38.473  3683  3906 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3683  pkgName : AMS_RESUME@CPU_MIN@7
07-17 14:51:38.474  3683  3906 D ActivityManager: mActivityResumeBooster.acquire()
07-17 14:51:38.476  3683  3906 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{f63e2edd0 #9 A=com.example.hello U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-17 14:51:38.476  3683  3906 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{f63e2edd0 #9 A=com.example.hello U=0 StackId=1 sz=1}
07-17 14:51:38.476  3683  3906 D InputDispatcher: Focused application set to: xxxx
07-17 14:51:38.477  3683  3906 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{f63e2edd0 #9 A=com.example.hello U=0 StackId=1 sz=1} next=ActivityRecord{20a2cb1d0 u0 com.example.hello/.MainActivity t9} mFocusedStack=ActivityStack{84ff120d0 stackId=1, 2 tasks}
07-17 14:51:38.477  3683  3906 D MountService: getExternalStorageMountMode : 1
07-17 14:51:38.478  3683  3906 D MountService: getExternalStorageMountMode : 3
07-17 14:51:38.478  3683  3906 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10054, packageName : com.example.hello
07-17 14:51:38.480  3683  3794 D WindowManager: addWindow: android.view.ViewRootImpl$W@54382a5 displayId=0
07-17 14:51:38.480  3683  3794 D InputTransport: Input channel constructed: fd=450
07-17 14:51:38.480  3683  3794 D InputTransport: Input channel constructed: fd=453
07-17 14:51:38.481  3683  3794 D ViewRootImpl@844a89c[hello]: setView = DecorView@f8dee2b[hello] touchMode=true
07-17 14:51:38.493  9372  9372 E Zygote  : v2
07-17 14:51:38.493  9372  9372 I libpersona: KNOX_SDCARD checking this for 10054
07-17 14:51:38.493  9372  9372 I libpersona: KNOX_SDCARD not a persona
07-17 14:51:38.493  3683  3794 V WindowManager: Relayout Window{2b167ad0 u0 Starting com.example.hello}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-17 14:51:38.494  9372  9372 E Zygote  : accessInfo : 0
07-17 14:51:38.494  3115  3115 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, iello
07-17 14:51:38.495  3683  3906 I ActivityManager: Start proc 9372:com.example.hello/u0a54 for activity com.example.hello/.MainActivity
07-17 14:51:38.498  9372  9372 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-17 14:51:38.499  9372  9372 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.hello 
07-17 14:51:38.512  3683  3794 D WindowManager: finishDrawingWindow: Window{2b167ad0 u0 Starting com.example.hello} mDrawState=DRAW_PENDING
07-17 14:51:38.512  9362  9362 D AndroidRuntime: Shutting down VM
07-17 14:51:38.514  9372  9372 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 14:51:38.514  9372  9372 D ActivityThread: Added TimaKeyStore provider
07-17 14:51:38.516  3683  3746 I ActivityManager: DSS on for com.example.hello and scale is 1.0
07-17 14:51:38.517  3683  3746 I WindowManager: Failed to capture screenshot of Token{9f33c9e ActivityRecord{4419ad9d0 u0 com.samsung.android.MtpApplication/.USBConnection t8}} appWin=Window{bb1ec49d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-17 14:51:38.524  3683  3746 D GameManagerService: sem_perfomance_mode: 0
07-17 14:51:38.524  3683  3683 D GameManagerService: NotifyRunnable. pkg: com.example.hello, type: 4, isMinimized: false, isTunableApp: false
07-17 14:51:38.524  3683  3683 D GameManagerService: unexpected mPrevNotiType: -1
07-17 14:51:38.530  3683  3746 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-17 14:51:38.530  3683  3746 D GameManagerService: sem_perfomance_mode: 0
07-17 14:51:38.530  3683  4180 V WindowManager: Relayout Window{bb1ec49d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-17 14:51:38.533  3683  5526 D GameManagerService: identifyGamePackage. com.example.hello
07-17 14:51:38.533  3683  5526 D GameManagerService: identifyGamePackage. com.example.hello
07-17 14:51:38.533  7797  7809 I ServiceManager: [#CMH#]   FaceService already paused:
07-17 14:51:38.534  7797  7809 I ServiceManager: [#CMH#]   IPService already paused:
07-17 14:51:38.534  7797  7809 I ServiceManager: [#CMH#]   StoryService already paused:
07-17 14:51:38.534  4662  4692 D ForegroundUtils: could not check pending caller
07-17 14:51:38.535  4662  4689 D ForegroundUtils: could not check pending caller
07-17 14:51:38.535  4662  4689 D ForegroundUtils: could not check pending caller
07-17 14:51:38.537  9362  9362 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-17 14:51:38.537  9362  9362 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-17 14:51:38.537  9362  9362 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-17 14:51:38.537  3683  3794 V WindowManager: Now policy hidden: Window{2b167ad0 u0 Starting com.example.hello}
07-17 14:51:38.537  9362  9362 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-17 14:51:38.539  3683  3794 D ViewRootImpl@844a89c[hello]: MSG_RESIZED: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-17 14:51:38.543  3683  5526 D GameManagerService: identifyGamePackage. com.example.hello
07-17 14:51:38.544  3683  3794 V WindowManager: Relayout Window{2b167ad0 u0 Starting com.example.hello}: viewVisibility=0 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-17 14:51:38.545  9372  9372 W System  : ClassLoader referenced unknown path: /data/app/com.example.hello-1/lib/arm64
07-17 14:51:38.546  3683  5526 D GameManagerService: identifyGamePackage. com.example.hello
07-17 14:51:38.548  3683  4725 V WindowManager: Relayout Window{12ff02d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
07-17 14:51:38.551  3683  3906 V WindowManager: Relayout Window{929ee82d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-17 14:51:38.551  3683  3906 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowManagerService.tryStartExitingAnimation:3504 com.android.server.wm.WindowManagerService.relayoutWindow:3360 com.android.server.wm.Session.relayoutEx:244 android.view.IWindowSession$Stub.onTransact:407 com.android.server.wm.Session.onTransact:151 
07-17 14:51:38.552  3115  3121 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-17 14:51:38.552  3115  3883 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
07-17 14:51:38.553  9372  9372 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-17 14:51:38.553  3683  3951 V WindowManager: Relayout Window{bb1ec49d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-17 14:51:38.554  4790  4790 D Launcher: onTrimMemory. Level: 20
07-17 14:51:38.558  3683  3794 D WindowManager: finishDrawingWindow: Window{2b167ad0 u0 Starting com.example.hello} mDrawState=HAS_DRAWN
,07-17 14:51:38.562  3683  3747 V WindowManager: Relayout Window{929ee82d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-17 14:51:38.566  9372  9372 I CordovaLog: Changing log level to DEBUG(3)
07-17 14:51:38.566  9372  9372 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-17 14:51:38.566  9372  9372 D CordovaActivity: CordovaActivity.onCreate()
,07-17 14:51:38.572  9372  9372 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm64
,07-17 14:51:38.575  9372  9372 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-17 14:51:38.607  9372  9372 I cr_LibraryLoader: Time to load native libraries: 2 ms (timestamps 1956-1958)
07-17 14:51:38.607  9372  9372 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-17 14:51:38.616  9372  9372 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-17 14:51:38.618  9372  9372 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-17 14:51:38.626  9372  9372 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-17 14:51:38.666  3683  3988 D MdnieScenarioControlService:  packageName : com.example.hello    className : com.example.hello.MainActivity
,07-17 14:51:38.747  3683  3746 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10054
07-17 14:51:38.747  3683  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-17 14:51:38.748  3683  3683 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
,07-17 14:51:38.748  3683  3913 I KnoxVpnEngineService: vpn handle : Message received
,07-17 14:51:38.769  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:51:38.769  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:51:38.796  9372  9372 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-17 14:51:38.800  9372  9372 D PluginManager: init()
,07-17 14:51:38.802  9372  9372 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-17 14:51:38.811  9372  9372 I cr_Ime  : ImeThread is enabled.
,07-17 14:51:38.812  9372  9411 W cr_media: Requires BLUETOOTH permission
,07-17 14:51:38.819  9372  9372 D CordovaActivity: Started the activity.
,07-17 14:51:38.821  9372  9372 D CordovaActivity: Resumed the activity.
,07-17 14:51:38.829  3683  3746 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@8d15bcd displayId=0
,07-17 14:51:38.830  3683  3746 D InputTransport: Input channel constructed: fd=454
07-17 14:51:38.830  3683  3746 D InputTransport: Input channel constructed: fd=455
,07-17 14:51:38.830  3683  3746 D InputTransport: Input channel destroyed: fd=455
07-17 14:51:38.831  9372  9372 D InputTransport: Input channel constructed: fd=98
07-17 14:51:38.831  9372  9372 D ViewRootImpl@e0b9775[MainActivity]: setView = DecorView@c93530a[MainActivity] touchMode=true
,07-17 14:51:38.831  3683  4735 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-17 14:51:38.831  3683  4735 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-17 14:51:38.832  9372  9372 D CordovaActivity: Paused the activity.
07-17 14:51:38.832  3683  3683 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,07-17 14:51:38.833  3683  3683 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-17 14:51:38.835  3683  3773 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-17 14:51:38.855  3683  3927 V WindowManager: Relayout Window{4ae0f93d0 u0 com.example.hello/com.example.hello.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-17 14:51:38.856  3115  3115 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-17 14:51:38.865  9372  9419 I OpenGLRenderer: Initialized EGL, version 1.4
07-17 14:51:38.866  9372  9419 D OpenGLRenderer: Swap behavior 1
,07-17 14:51:38.869  9372  9419 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.example.hello
,07-17 14:51:38.871  9372  9419 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-17 14:51:38.871  9372  9372 D CordovaActivity: Stopped the activity.
,07-17 14:51:38.879  3683  3794 V WindowManager: Now policy hidden: Window{4ae0f93d0 u0 com.example.hello/com.example.hello.MainActivity}
,07-17 14:51:38.963  3683  6374 D WindowManager: finishDrawingWindow: Window{4ae0f93d0 u0 com.example.hello/com.example.hello.MainActivity} mDrawState=DRAW_PENDING
,07-17 14:51:38.963  9372  9372 D ViewRootImpl@e0b9775[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-17 14:51:38.969  3683  3794 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-17 14:51:38.969  3683  3683 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
,07-17 14:51:38.970  3683  3794 I ActivityManager: Displayed com.example.hello/.MainActivity: +440ms (total +493ms)
07-17 14:51:38.970  3683  3683 I KnoxTimeoutHandler: SD activityfalse
07-17 14:51:38.970  3683  3683 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
07-17 14:51:38.970  3683  3773 D ActivityManager: mActivityResumeBoosterTail.acquire()
,07-17 14:51:38.971  3683  3794 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3683  tag : AMS_RESUME@CPU_MIN@7
07-17 14:51:38.971  3683  3794 D ActivityManager: mActivityResumeBooster.release()
07-17 14:51:38.971  3683  3794 D ViewRootImpl@844a89c[hello]: dispatchDetachedFromWindow
,07-17 14:51:38.972  3683  3794 I WindowManager: Destroying surface Surface(name=Starting com.example.hello) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
07-17 14:51:38.972  3115  9232 I SurfaceFlinger: id=15 Removed iello (3/5)
,07-17 14:51:38.972  3683  3773 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3683  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
07-17 14:51:38.973  3115  3121 I SurfaceFlinger: id=15 Removed iello (-2/5)
,07-17 14:51:38.975  3683  3794 D InputTransport: Input channel destroyed: fd=450
,07-17 14:51:38.976  3683  3794 D InputTransport: Input channel destroyed: fd=453
,07-17 14:51:38.980  3683  3915 D WindowManager: finishDrawingWindow: Window{4ae0f93d0 u0 com.example.hello/com.example.hello.MainActivity} mDrawState=HAS_DRAWN
,07-17 14:51:38.990  9372  9372 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,07-17 14:51:39.002  9372  9426 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-17 14:51:39.014  9372  9426 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-17 14:51:39.014  9372  9426 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-17 14:51:39.015  9372  9426 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-17 14:51:39.016  9372  9426 W AudioCapabilities: Unsupported mime audio/x-ima
07-17 14:51:39.017  9372  9426 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 14:51:39.017  9372  9426 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 14:51:39.017  9372  9426 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.019  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.021  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-17 14:51:39.026  9372  9426 W VideoCapabilities: Unsupported mime video/wvc1
,07-17 14:51:39.027  9372  9426 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-17 14:51:39.031  9372  9426 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 14:51:39.031  9372  9426 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 14:51:39.031  9372  9426 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-17 14:51:39.032  9372  9426 W VideoCapabilities: Unsupported mime video/wvc1
07-17 14:51:39.033  9372  9426 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-17 14:51:39.034  9372  9426 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
07-17 14:51:39.035  9372  9426 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
07-17 14:51:39.036  9372  9426 W VideoCapabilities: Unsupported mime video/mp43
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.039  9372  9426 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 14:51:39.041  9372  9426 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 14:51:39.041  9372  9426 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 14:51:39.041  9372  9426 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-17 14:51:39.055  9372  9426 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-17 14:51:39.066  9372  9426 W VideoCapabilities: Unsupported mime video/sorenson
,07-17 14:51:39.085  9372  9426 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.example.hello
,07-17 14:51:39.102  9372  9372 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9372
,07-17 14:51:39.130  9372  9372 D SystemWebChromeClient: file:///android_asset/www/index.html: Line 10 : The key "target-densitydpi" is not supported.
07-17 14:51:39.130  9372  9372 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,07-17 14:51:39.130  9372  9409 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,07-17 14:51:39.186  9372  9372 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-17 14:51:39.226  9372  9372 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-17 14:51:39.273  3683  3683 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3683  tag : AMS_RESUME_TAIL@CPU_MIN@13
,07-17 14:51:41.803  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:51:41.803  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:51:42.163  3683  3798 I PowerManagerService: [PWL] On : 0 (155515 ms ago)
07-17 14:51:42.163  3683  3798 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-17 14:51:42.678  3683  3747 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 14:51:43.355  4520  4520 D io_stats: !@   8,0 r 24216 2258172 w 3972 66968 d 528 18664 f 1800 1800 iot 10240 9391 th 493016 0 0 pt 0 inp 0 0 156.705
,07-17 14:51:43.994  4228  4228 I wpa_supplicant: WPA: Group rekeying completed with F4.E6.C2 [GTK=CCMP]
,07-17 14:51:43.999  3683  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 14:51:44.006  4228  4228 I wpa_supplicant: WPA: Group rekeying completed with F4.E6.C2 [GTK=CCMP]
,07-17 14:51:44.009  3293  3762 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 14:51:44.019  3683  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 14:51:44.028  3683  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 14:51:44.033  3683  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 14:51:44.095  4228  4228 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-17 14:51:44.107  4228  4228 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-17 14:51:44.536  3683  5526 D GameManagerService: identifyGamePackage. com.example.hello
,07-17 14:51:44.835  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:51:44.835  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:51:46.536  7797  7822 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,07-17 14:51:47.802  3683  5526 D SSRM:f  : SIOP:: AP = 260, PST = 265 (W:6), CP = 214, CUR = 135, LCD = 57
,07-17 14:51:47.863  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:51:47.864  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:51:48.361  4520  4520 D io_stats: !@   8,0 r 24216 2258172 w 4000 67188 d 529 18828 f 1802 1802 iot 10240 9397 th 495224 0 0 pt 0 inp 0 0 161.711
,07-17 14:51:48.491  3683  3790 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-17 14:51:48.515  3683  3790 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-17 14:51:48.515  3683  3790 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-17 14:51:49.016  3293  3762 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 14:51:50.362  3683  3683 D UsbMonitorService: readUsbState++
,07-17 14:51:50.363  3683  3683 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 14:51:50.365  3683  3683 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 14:51:50.365  3683  3683 D UsbMonitorService: Posting Message again
,07-17 14:51:50.895  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:51:50.895  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:51:51.136  3683  4221 E Watchdog: !@Sync 5 [17_lip_14_51_51.135]
,07-17 14:51:52.753  3683  4735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 14:51:53.366  4520  4520 D io_stats: !@   8,0 r 24216 2258172 w 4015 67356 d 529 18828 f 1804 1804 iot 10250 9402 th 496280 0 0 pt 0 inp 0 0 166.717
,07-17 14:51:53.919  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:51:53.920  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:51:56.941  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:51:56.941  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:51:57.829  3683  5526 D SSRM:f  : SIOP:: AP = 250, PST = 255 (W:6), CP = 213, CUR = 136, LCD = 57
,07-17 14:51:58.372  4520  4520 D io_stats: !@   8,0 r 24216 2258172 w 4016 67408 d 530 18900 f 1805 1805 iot 10250 9403 th 496248 0 0 pt 0 inp 0 0 171.722
,07-17 14:51:59.968  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:51:59.968  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:52:00.000  3683  3861 D SamsungAlarmManager: Expired : 8
,07-17 14:52:00.001  3683  3861 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{bf8a4fc type 3 when 173352 android}
,07-17 14:52:00.011  3683  3683 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170717T145300 - CU:1000/CP:3683
,07-17 14:52:00.016  4066  4066 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-17 14:52:00.016  4066  4066 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-17 14:52:00.017  4066  4066 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-17 14:52:00.036  4066  4066 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-17 14:52:00.044  4066  4066 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-17 14:52:00.048  4066  4066 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-17 14:52:00.056  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 14:52:00.058  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 14:52:00.061  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 14:52:00.063  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 14:52:00.078  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 14:52:00.080  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 14:52:00.081  4066  4066 V hong    : mid yDiff = 438
,07-17 14:52:00.081  4066  4066 V hong    : mid yDiff = 438
,07-17 14:52:00.084  4066  4066 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-17 14:52:00.084  4066  4066 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-17 14:52:00.088  4066  4066 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-17 14:52:00.091  4066  4066 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
07-17 14:52:00.097  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 14:52:00.099  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 14:52:00.112  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 14:52:00.113  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 14:52:00.118  5304  5304 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-17 14:52:00.120  5304  5304 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-17 14:52:00.123  5304  5304 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-17 14:52:00.128  5304  5304 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-17 14:52:00.129  5304  5304 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
07-17 14:52:00.130  5304  5304 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-17 14:52:00.131  5304  5304 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-17 14:52:00.132  5304  5304 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-17 14:52:00.137  5304  5304 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-17 14:52:00.138  5304  5304 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C53C80CE799D262D53A4D3389BB5B48E0F14920E8C81A7DF7C0ED6B994EA20530075DF101AFB74E8D6450879E56EFDE23]}
07-17 14:52:00.139  5304  5304 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-17 14:52:02.823  3683  4734 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 14:52:02.824  3683  4734 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 240, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 14:52:02.824  3683  4734 D BatteryService: online:4, current avg:136, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:148
07-17 14:52:02.825  3683  3683 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 14:52:02.834  3683  3683 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 14:52:02.835  3683  3683 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 14:52:02.839  3683  3683 D GameManagerService: new battery level: 100
,07-17 14:52:02.844  4066  4066 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 14:52:02.845  4066  4066 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 14:52:02.853  4066  4066 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-17 14:52:02.857  4066  4066 D BatteryMeterDrawable: isSomethingChanged - false
07-17 14:52:02.858  4066  4066 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 14:52:02.871  4055  4055 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-17 14:52:02.872  4055  4479 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 14:52:02.884  4066  4066 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 14:52:02.991  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:02.991  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:52:03.377  4520  4520 D io_stats: !@   8,0 r 24216 2258172 w 4028 67472 d 530 18900 f 1808 1808 iot 10250 9406 th 496324 0 0 pt 0 inp 0 0 176.728
,07-17 14:52:04.049  3293  3762 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 14:52:06.022  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:06.022  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:52:07.855  3683  5526 D SSRM:f  : SIOP:: AP = 250, PST = 253 (W:6), CP = 212, CUR = 86, LCD = 57
,07-17 14:52:08.382  4520  4520 D io_stats: !@   8,0 r 24216 2258172 w 4030 67508 d 531 18904 f 1809 1809 iot 10250 9407 th 496324 0 0 pt 0 inp 0 0 181.733
,07-17 14:52:09.049  3293  3762 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 14:52:09.057  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:09.057  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:52:10.023  3683  4018 D WifiWatchdogStateMachine:  [|216] []
,07-17 14:52:12.090  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:12.090  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:52:13.388  4520  4520 D io_stats: !@   8,0 r 24216 2258172 w 4036 67548 d 531 18904 f 1810 1810 iot 10250 9409 th 496392 0 0 pt 0 inp 0 0 186.738
,07-17 14:52:15.112  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:15.112  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:52:17.883  3683  5526 D SSRM:f  : SIOP:: AP = 250, PST = 251 (W:6), CP = 211, CUR = 35, LCD = 57
,07-17 14:52:18.135  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:18.135  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:52:20.366  3683  3683 D UsbMonitorService: readUsbState++
,07-17 14:52:20.368  3683  3683 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 14:52:20.369  3683  3683 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 14:52:20.370  3683  3683 D UsbMonitorService: Posting Message again
,07-17 14:52:21.138  3683  4221 E Watchdog: !@Sync 6 [17_lip_14_52_21.137]
,07-17 14:52:21.159  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:21.159  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:52:22.182  3683  3798 I PowerManagerService: [PWL] On : 0 (195534 ms ago)
07-17 14:52:22.183  3683  3798 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-17 14:52:24.193  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:24.193  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:52:24.748  4783  4836 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-17 14:52:24.748  4783  4836 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-17 14:52:24.748  4783  4836 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-17 14:52:24.755  4783  4836 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60111 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-17 14:52:26.973  3683  3861 D SamsungAlarmManager: Expired : 4
,07-17 14:52:26.977  3683  3861 D SamsungAlarmManager: setInexact Intent (T:1/F:8/AC:false) 20170807T182756 - CU:1000/CP:3683
,07-17 14:52:26.978  3683  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T145844, SetElapsed=577515, nowELAPSED=200330
07-17 14:52:26.979  3683  3861 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170717T145300, SetElapsed=233352, nowELAPSED=200331
07-17 14:52:26.980  3683  3861 V SamsungAlarmManager: Sending to uid : 10019 action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE alarm=Alarm{f8f59da type 2 when 159885 com.google.android.gms}
,07-17 14:52:26.985  3683  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@e1c63f3 alarm=Alarm{605de0b type 2 when 163867 android}
07-17 14:52:26.985  3683  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@249b2d6 alarm=Alarm{1a914e8 type 2 when 200325 android}
,07-17 14:52:26.988  3683  3861 V SamsungAlarmManager: Sending to uid : 1000 action=com.mobeam.barcodeService.UPLOAD_BEAM_RECORD alarm=Alarm{cccc701 type 1 when 1500295889048 com.mobeam.barcodeService}
,07-17 14:52:26.990  3683  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-17 14:52:26.994  4228  4228 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-17 14:52:26.994  4228  4228 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-17 14:52:27.001  4228  4228 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-17 14:52:27.004  3683  3861 D MountService: getExternalStorageMountMode : 1
,07-17 14:52:27.005  3683  3861 D MountService: getExternalStorageMountMode : 3
07-17 14:52:27.005  3683  3861 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.mobeam.barcodeService
,07-17 14:52:27.034  9440  9440 E Zygote  : v2
,07-17 14:52:27.034  9440  9440 I libpersona: KNOX_SDCARD checking this for 1000
07-17 14:52:27.034  9440  9440 I libpersona: KNOX_SDCARD not a persona
07-17 14:52:27.035  3683  3861 I ActivityManager: Start proc 9440:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-17 14:52:27.035  9440  9440 E Zygote  : accessInfo : 0
,07-17 14:52:27.037  3683  3683 D SamsungAlarmManager: setInexact Listener (T:2/F:0/AC:false) 20170717T154933 - CU:1000/CP:3683
,07-17 14:52:27.043  3683  3925 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T145434 - CU:1000/CP:3683
07-17 14:52:27.043  3683  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T145434, SetElapsed=328343, nowELAPSED=200395
,07-17 14:52:27.045  3683  6374 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4619 / op:PendingIntent{16e9794: PendingIntentRecord{17f336 com.google.android.gms broadcastIntent}}
,07-17 14:52:27.045  3683  3955 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T145241 - CU:1000/CP:3683
,07-17 14:52:27.045  3683  3955 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T145241, SetElapsed=215350, nowELAPSED=200397
07-17 14:52:27.045  9440  9440 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-17 14:52:27.047  9440  9440 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.mobeam.barcodeService 
,07-17 14:52:27.072  5380  5380 D [SAUI]  : Global::recovered::false
,07-17 14:52:27.076  9440  9440 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 14:52:27.076  9440  9440 D ActivityThread: Added TimaKeyStore provider
07-17 14:52:27.078  3683  4725 I ActivityManager: DSS on for com.mobeam.barcodeService and scale is 1.0
,07-17 14:52:27.084  5380  5380 D WaitQueueForNetworkActivate: notifyNetworkActivated
07-17 14:52:27.084  5380  5380 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
,07-17 14:52:27.099  9440  9440 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,07-17 14:52:27.112  9440  9440 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 14:52:27.151  3683  3915 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T154943 - CU:10019/CP:4619
,07-17 14:52:27.193  3683  3747 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T154943 - CU:10019/CP:4619
,07-17 14:52:27.204  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:27.205  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:52:27.206  3683  4734 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4619 / op:PendingIntent{f620bf5: PendingIntentRecord{17f336 com.google.android.gms broadcastIntent}}
,07-17 14:52:27.321  4619  4619 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-17 14:52:27.354  3683  6374 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T154946 - CU:10019/CP:4619
,07-17 14:52:27.372  3683  4724 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T154946 - CU:10019/CP:4619
,07-17 14:52:27.502  4619  9458 W PhenotypeChimeraConfigurator: No account for auth token provided
,07-17 14:52:27.536  4619  9458 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 14:52:27.536  4619  9458 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 14:52:27.538  3293  3766 D EnterpriseController: netId is 0
07-17 14:52:27.538  3293  3766 D Netd    : getNetworkForDns: using netid 502 for uid 10019
07-17 14:52:27.538  3293  3766 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 14:52:27.914  3683  5526 D SSRM:f  : SIOP:: AP = 250, PST = 251 (W:10), CP = 210, CUR = 19, LCD = 57
,07-17 14:52:28.401  4520  4520 D io_stats: !@   8,0 r 24225 2258244 w 4070 67940 d 535 18924 f 1826 1826 iot 10250 9428 th 495104 0 0 pt 0 inp 0 0 201.752
,07-17 14:52:28.711  4619  9458 I PhenotypeSyncScheduler: Scheduling adaptive one off task with window [14400, 604800] in seconds
,07-17 14:52:28.757  3683  4724 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T154946 - CU:10019/CP:4619
,07-17 14:52:28.776  3683  4320 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4619 / op:PendingIntent{134230: PendingIntentRecord{17f336 com.google.android.gms broadcastIntent}}
,07-17 14:52:28.796  3683  3927 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T154943 - CU:10019/CP:4619
,07-17 14:52:30.235  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:30.236  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -47
,07-17 14:52:30.989  3293  3763 D Netd    : Iface wlan0 link up
,07-17 14:52:30.993  4228  4228 I wpa_supplicant: nl80211: Received scan results (39 BSSes)
07-17 14:52:30.994  3683  3792 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 14:52:30.994  3683  3792 D Tethering: interfaceStatusChanged wlan0, true
,07-17 14:52:31.000  3683  3955 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3683 / listener:android.app.AlarmManager$ListenerWrapper@ebdd23d
,07-17 14:52:31.002  3683  3955 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T145434, SetElapsed=328343, nowELAPSED=204354
,07-17 14:52:32.878  3683  4725 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 14:52:32.879  3683  4725 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 239, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 14:52:32.880  3683  4725 D BatteryService: online:4, current avg:12, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-17 14:52:32.880  3683  3683 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 14:52:32.890  3683  3683 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 14:52:32.891  3683  3683 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 14:52:32.894  3683  3683 D GameManagerService: new battery level: 100
,07-17 14:52:32.900  4066  4066 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 14:52:32.901  4066  4066 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 14:52:32.912  4066  4066 D PowerUI : priorPlugType = 2 mPlugType =  2
07-17 14:52:32.916  4066  4066 D BatteryMeterDrawable: isSomethingChanged - false
07-17 14:52:32.917  4066  4066 D BatteryMeterDrawable: isSomethingChanged - false
07-17 14:52:32.921  4055  4055 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-17 14:52:32.922  4055  4479 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 14:52:32.946  4066  4066 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 14:52:33.270  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:33.270  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 14:52:33.405  4520  4520 D io_stats: !@   8,0 r 24225 2258244 w 4128 68432 d 538 18936 f 1839 1839 iot 10270 9443 th 494412 0 0 pt 0 inp 0 0 206.756
,07-17 14:52:36.298  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:36.299  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 14:52:37.944  3683  5526 D SSRM:f  : SIOP:: AP = 250, PST = 251 (W:10), CP = 210, CUR = 7, LCD = 57
,07-17 14:52:38.411  4520  4520 D io_stats: !@   8,0 r 24225 2258244 w 4131 68460 d 538 18936 f 1840 1840 iot 10270 9444 th 495004 0 0 pt 0 inp 0 0 211.762
,07-17 14:52:39.331  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:39.332  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 14:52:42.355  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:42.355  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 14:52:43.416  4520  4520 D io_stats: !@   8,0 r 24225 2258244 w 4134 68496 d 538 18936 f 1842 1842 iot 10270 9446 th 496224 0 0 pt 0 inp 0 0 216.767
,07-17 14:52:44.089  3293  3762 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 14:52:45.390  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:45.390  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:52:47.966  3683  5526 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:10), CP = 209, CUR = 3, LCD = 57
,07-17 14:52:48.421  4520  4520 D io_stats: !@   8,0 r 24225 2258244 w 4143 68588 d 538 18936 f 1843 1843 iot 10270 9449 th 496200 0 0 pt 0 inp 0 0 221.772
,07-17 14:52:48.426  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:48.427  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:52:49.090  3293  3762 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 14:52:49.106  3683  3951 I ActivityManager: KPU : put [com.sec.android.widgetapp.samsungapps] : 27120 K
07-17 14:52:49.106  3683  3951 I ActivityManager: Killing 8752:com.sec.android.widgetapp.samsungapps/u0a105 (adj 906): DHA:empty #33
,07-17 14:52:49.149  3683  4724 D ActivityManager: cleanUpApplicationRecord -- 8752
,07-17 14:52:49.152  4662  4689 D ForegroundUtils: could not check pending caller
,07-17 14:52:50.371  3683  3683 D UsbMonitorService: readUsbState++
,07-17 14:52:50.372  3683  3683 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 14:52:50.373  3683  3683 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 14:52:50.374  3683  3683 D UsbMonitorService: Posting Message again
,07-17 14:52:51.140  3683  4221 E Watchdog: !@Sync 7 [17_lip_14_52_51.139]
,07-17 14:52:51.455  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:51.455  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:52:53.427  4520  4520 D io_stats: !@   8,0 r 24225 2258244 w 4144 68632 d 539 18940 f 1844 1844 iot 10270 9450 th 497152 0 0 pt 0 inp 0 0 226.777
,07-17 14:52:54.490  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:54.490  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:52:57.519  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:52:57.519  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 14:52:57.992  3683  5526 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:10), CP = 208, CUR = 1, LCD = 57
,07-17 14:52:58.432  4520  4520 D io_stats: !@   8,0 r 24225 2258244 w 4152 68668 d 539 18940 f 1844 1844 iot 10270 9451 th 497120 0 0 pt 0 inp 0 0 231.783
,07-17 14:53:00.000  3683  3861 D SamsungAlarmManager: Expired : 8
07-17 14:53:00.001  3683  3861 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{d0edc65 type 3 when 233352 android}
,07-17 14:53:00.010  3683  3683 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170717T145400 - CU:1000/CP:3683
07-17 14:53:00.010  3683  3683 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170717T145400, SetElapsed=293352, nowELAPSED=233363
,07-17 14:53:00.015  4066  4066 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-17 14:53:00.016  4066  4066 D KeyguardUpdateMonitor: handleTimeUpdate#start
,07-17 14:53:00.016  4066  4066 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-17 14:53:00.042  4066  4066 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-17 14:53:00.043  4066  4066 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-17 14:53:00.047  4066  4066 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-17 14:53:00.059  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 14:53:00.060  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 14:53:00.067  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 14:53:00.070  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 14:53:00.087  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 14:53:00.089  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 14:53:00.090  4066  4066 V hong    : mid yDiff = 438
07-17 14:53:00.090  4066  4066 V hong    : mid yDiff = 438
,07-17 14:53:00.094  4066  4066 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-17 14:53:00.095  4066  4066 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
07-17 14:53:00.097  4066  4066 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
07-17 14:53:00.099  4066  4066 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-17 14:53:00.118  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 14:53:00.120  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 14:53:00.135  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 14:53:00.137  4066  4066 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 14:53:00.141  5304  5304 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
07-17 14:53:00.143  5304  5304 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-17 14:53:00.146  5304  5304 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-17 14:53:00.151  5304  5304 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-17 14:53:00.152  5304  5304 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-17 14:53:00.153  5304  5304 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-17 14:53:00.154  5304  5304 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-17 14:53:00.155  5304  5304 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-17 14:53:00.160  5304  5304 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-17 14:53:00.162  5304  5304 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C53C80CE799D262D53A4D3389BB5B48E00C1359A2875787FA787174F811A00EBC7DEDB160DDC976541E56AEC850C4592B]}
,07-17 14:53:00.163  5304  5304 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-17 14:53:00.554  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:53:00.554  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:53:02.936  3683  4735 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 14:53:03.589  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:53:03.590  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:53:04.129  3293  3762 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 14:53:06.615  3683  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 14:53:06.615  3683  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 14:53:07.190  3683  3798 I PowerManagerService: [PWL] On : 0 (240541 ms ago)
07-17 14:53:07.190  3683  3798 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4

```
