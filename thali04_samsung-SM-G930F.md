#### Test 130589065c7d4296_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,07-17 15:35:46.212  3713  5429 D SSRM:f  : SIOP:: AP = 260, PST = 275 (W:10), CP = 222, CUR = 153, LCD = 57
07-17 15:35:46.766  4561  4561 D io_stats: !@   8,0 r 23987 2192520 w 3979 66036 d 519 18344 f 1734 1732 iot 9760 9133 th 502056 0 0 pt 0 inp 2 0 151.553
--------- beginning of main
07-17 15:35:46.951  9173  9173 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9173 | app_process
07-17 15:35:46.951  9173  9173 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-17 15:35:46.959  9173  9173 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-17 15:35:46.959  9173  9173 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-17 15:35:46.966  9173  9173 D AndroidRuntime: CheckJNI is OFF
07-17 15:35:46.966  9173  9173 D AndroidRuntime: addProductProperty: start
07-17 15:35:47.038  9173  9173 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-17 15:35:47.038  9173  9173 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-17 15:35:47.059  9173  9173 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-17 15:35:47.059  9173  9173 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-17 15:35:47.059  9173  9173 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-17 15:35:47.204  9173  9173 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-17 15:35:47.257  9173  9173 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-17 15:35:47.282  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:35:47.283  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
07-17 15:35:47.302  9173  9173 I Enhanced Zygote ASLR: DISABLED!
07-17 15:35:47.303  9173  9173 I Radio-JNI: register_android_hardware_Radio DONE
07-17 15:35:47.310  9173  9173 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-17 15:35:47.310  9173  9173 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-17 15:35:47.312  9173  9173 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-17 15:35:47.328  9173  9173 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-17 15:35:47.354  3713  4740 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.example.hello/com.example.hello.MainActivity}} from uid 2000 on display 0
07-17 15:35:47.369  3713  4740 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-17 15:35:47.373  3713  4740 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3713  pkgName : AMS_RESUME@CPU_MIN@7
07-17 15:35:47.377  3713  4740 D ActivityManager: mActivityResumeBooster.acquire()
07-17 15:35:47.379  3713  4740 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{f594888d0 #9 A=com.example.hello U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-17 15:35:47.379  3713  4740 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{f594888d0 #9 A=com.example.hello U=0 StackId=1 sz=1}
07-17 15:35:47.380  3713  4740 D InputDispatcher: Focused application set to: xxxx
07-17 15:35:47.380  3713  4740 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{f594888d0 #9 A=com.example.hello U=0 StackId=1 sz=1} next=ActivityRecord{9eede9cd0 u0 com.example.hello/.MainActivity t9} mFocusedStack=ActivityStack{be12a11d0 stackId=1, 2 tasks}
07-17 15:35:47.381  3713  4740 D MountService: getExternalStorageMountMode : 1
07-17 15:35:47.381  3713  4740 D MountService: getExternalStorageMountMode : 3
07-17 15:35:47.381  3713  4740 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10054, packageName : com.example.hello
07-17 15:35:47.384  3713  3797 D WindowManager: addWindow: android.view.ViewRootImpl$W@336a0a0 displayId=0
07-17 15:35:47.385  3713  3797 D InputTransport: Input channel constructed: fd=454
07-17 15:35:47.385  3713  3797 D InputTransport: Input channel constructed: fd=455
07-17 15:35:47.385  3713  3797 D ViewRootImpl@a17e5a3[hello]: setView = DecorView@724381e[hello] touchMode=true
07-17 15:35:47.398  3713  3797 V WindowManager: Relayout Window{ef35459d0 u0 Starting com.example.hello}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-17 15:35:47.398  9183  9183 E Zygote  : v2
07-17 15:35:47.398  9183  9183 I libpersona: KNOX_SDCARD checking this for 10054
07-17 15:35:47.398  9183  9183 I libpersona: KNOX_SDCARD not a persona
07-17 15:35:47.398  3112  3112 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, iello
07-17 15:35:47.399  9183  9183 E Zygote  : accessInfo : 0
07-17 15:35:47.401  3713  4740 I ActivityManager: Start proc 9183:com.example.hello/u0a54 for activity com.example.hello/.MainActivity
07-17 15:35:47.404  9183  9183 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-17 15:35:47.405  9183  9183 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.hello 
07-17 15:35:47.409  9173  9173 D AndroidRuntime: Shutting down VM
07-17 15:35:47.420  3713  3797 V WindowManager: Now policy hidden: Window{ef35459d0 u0 Starting com.example.hello}
07-17 15:35:47.422  3713  3797 D WindowManager: finishDrawingWindow: Window{ef35459d0 u0 Starting com.example.hello} mDrawState=DRAW_PENDING
07-17 15:35:47.428  9183  9183 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 15:35:47.428  9183  9183 D ActivityThread: Added TimaKeyStore provider
07-17 15:35:47.430  3713  4746 I ActivityManager: DSS on for com.example.hello and scale is 1.0
07-17 15:35:47.432  3713  4746 I WindowManager: Failed to capture screenshot of Token{7469177 ActivityRecord{3d64776d0 u0 com.samsung.android.MtpApplication/.USBConnection t8}} appWin=Window{a3d7a26d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-17 15:35:47.435  9173  9173 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-17 15:35:47.435  9173  9173 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-17 15:35:47.435  9173  9173 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-17 15:35:47.435  9173  9173 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-17 15:35:47.441  3713  4746 D GameManagerService: sem_perfomance_mode: 0
07-17 15:35:47.442  3713  3713 D GameManagerService: NotifyRunnable. pkg: com.example.hello, type: 4, isMinimized: false, isTunableApp: false
07-17 15:35:47.442  3713  3713 D GameManagerService: unexpected mPrevNotiType: -1
07-17 15:35:47.442  3713  3934 V WindowManager: Relayout Window{dadd054d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-17 15:35:47.445  3713  3921 V WindowManager: Relayout Window{a3d7a26d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-17 15:35:47.446  4794  4794 D Launcher: onTrimMemory. Level: 20
07-17 15:35:47.450  3713  4746 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-17 15:35:47.451  3713  4746 D GameManagerService: sem_perfomance_mode: 0
07-17 15:35:47.452  4671  4690 D ForegroundUtils: could not check pending caller
07-17 15:35:47.453  4671  4690 D ForegroundUtils: could not check pending caller
07-17 15:35:47.453  4671  4690 D ForegroundUtils: could not check pending caller
07-17 15:35:47.453  3713  5429 D GameManagerService: identifyGamePackage. com.example.hello
07-17 15:35:47.454  3713  5429 D GameManagerService: identifyGamePackage. com.example.hello
07-17 15:35:47.459  3713  3797 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.AppWindowToken.destroySurfaces:412 com.android.server.wm.AppWindowToken.destroySurfaces:376 com.android.server.wm.WindowStateAnimator.finishExit:654 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:564 com.android.server.wm.WindowAnimator.updateWindowsLocked:439 
07-17 15:35:47.459  3112  3284 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-17 15:35:47.460  3112  3117 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
07-17 15:35:47.462  3713  4310 V WindowManager: Relayout Window{c29ec8bd0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
07-17 15:35:47.467  3713  5429 D GameManagerService: identifyGamePackage. com.example.hello
,07-17 15:35:47.468  9183  9183 W System  : ClassLoader referenced unknown path: /data/app/com.example.hello-1/lib/arm64
07-17 15:35:47.468  3713  3914 V WindowManager: Relayout Window{dadd054d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-17 15:35:47.469  3713  3797 D ViewRootImpl@a17e5a3[hello]: MSG_RESIZED: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-17 15:35:47.470  3713  5429 D GameManagerService: identifyGamePackage. com.example.hello
,07-17 15:35:47.473  3713  4758 V WindowManager: Relayout Window{a3d7a26d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-17 15:35:47.477  3713  3797 V WindowManager: Relayout Window{ef35459d0 u0 Starting com.example.hello}: viewVisibility=0 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-17 15:35:47.480  9183  9183 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 15:35:47.485  3713  3797 D WindowManager: finishDrawingWindow: Window{ef35459d0 u0 Starting com.example.hello} mDrawState=HAS_DRAWN
,07-17 15:35:47.496  9183  9183 I CordovaLog: Changing log level to DEBUG(3)
07-17 15:35:47.496  9183  9183 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-17 15:35:47.496  9183  9183 D CordovaActivity: CordovaActivity.onCreate()
,07-17 15:35:47.505  9183  9183 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm64
,07-17 15:35:47.509  9183  9183 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-17 15:35:47.578  9183  9183 I cr_LibraryLoader: Time to load native libraries: 16 ms (timestamps 2351-2367)
07-17 15:35:47.578  9183  9183 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-17 15:35:47.584  3713  3991 D MdnieScenarioControlService:  packageName : com.example.hello    className : com.example.hello.MainActivity
,07-17 15:35:47.592  9183  9183 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-17 15:35:47.600  9183  9183 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-17 15:35:47.609  9183  9183 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-17 15:35:47.768  3713  6658 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10054
07-17 15:35:47.768  3713  6658 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-17 15:35:47.769  3713  3713 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
,07-17 15:35:47.770  3713  3916 I KnoxVpnEngineService: vpn handle : Message received
,07-17 15:35:47.828  9183  9183 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-17 15:35:47.833  9183  9183 D PluginManager: init()
,07-17 15:35:47.837  9183  9183 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-17 15:35:47.854  9183  9183 I cr_Ime  : ImeThread is enabled.
,07-17 15:35:47.863  9183  9222 W cr_media: Requires BLUETOOTH permission
,07-17 15:35:47.871  9183  9183 D CordovaActivity: Started the activity.
,07-17 15:35:47.873  9183  9183 D CordovaActivity: Resumed the activity.
,07-17 15:35:47.884  3713  3914 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@a43aae8 displayId=0
,07-17 15:35:47.884  3713  3914 D InputTransport: Input channel constructed: fd=456
07-17 15:35:47.884  3713  3914 D InputTransport: Input channel constructed: fd=457
,07-17 15:35:47.885  3713  3914 D InputTransport: Input channel destroyed: fd=457
07-17 15:35:47.885  9183  9183 D InputTransport: Input channel constructed: fd=98
07-17 15:35:47.886  9183  9183 D ViewRootImpl@ea9ec4[MainActivity]: setView = DecorView@7a11ce2[MainActivity] touchMode=true
,07-17 15:35:47.886  3713  3934 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-17 15:35:47.886  3713  3934 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-17 15:35:47.887  3713  3713 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,07-17 15:35:47.887  9183  9183 D CordovaActivity: Paused the activity.
,07-17 15:35:47.888  3713  3713 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-17 15:35:47.889  3713  3764 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-17 15:35:47.904  3713  3914 V WindowManager: Relayout Window{53cbfa6d0 u0 com.example.hello/com.example.hello.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-17 15:35:47.904  3112  3112 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-17 15:35:47.909  9183  9230 I OpenGLRenderer: Initialized EGL, version 1.4
07-17 15:35:47.909  9183  9230 D OpenGLRenderer: Swap behavior 1
,07-17 15:35:47.912  9183  9230 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.example.hello
,07-17 15:35:47.914  9183  9230 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-17 15:35:47.914  9183  9183 D CordovaActivity: Stopped the activity.
,07-17 15:35:47.924  3713  3797 V WindowManager: Now policy hidden: Window{53cbfa6d0 u0 com.example.hello/com.example.hello.MainActivity}
,07-17 15:35:48.009  3713  4755 D WindowManager: finishDrawingWindow: Window{53cbfa6d0 u0 com.example.hello/com.example.hello.MainActivity} mDrawState=DRAW_PENDING
,07-17 15:35:48.010  9183  9183 D ViewRootImpl@ea9ec4[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-17 15:35:48.016  3713  3797 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-17 15:35:48.016  3713  3713 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
,07-17 15:35:48.017  3713  3797 I ActivityManager: Displayed com.example.hello/.MainActivity: +566ms (total +636ms)
07-17 15:35:48.017  3713  3764 D ActivityManager: mActivityResumeBoosterTail.acquire()
07-17 15:35:48.017  3713  3713 I KnoxTimeoutHandler: SD activityfalse
07-17 15:35:48.017  3713  3713 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
,07-17 15:35:48.017  3713  3797 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3713  tag : AMS_RESUME@CPU_MIN@7
07-17 15:35:48.017  3713  3797 D ActivityManager: mActivityResumeBooster.release()
,07-17 15:35:48.018  3713  3797 D ViewRootImpl@a17e5a3[hello]: dispatchDetachedFromWindow
07-17 15:35:48.019  3713  3797 I WindowManager: Destroying surface Surface(name=Starting com.example.hello) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
,07-17 15:35:48.020  3713  3764 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3713  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
,07-17 15:35:48.021  3112  9055 I SurfaceFlinger: id=15 Removed iello (3/5)
,07-17 15:35:48.021  3112  3904 I SurfaceFlinger: id=15 Removed iello (-2/5)
,07-17 15:35:48.024  3713  3797 D InputTransport: Input channel destroyed: fd=454
,07-17 15:35:48.025  3713  3797 D InputTransport: Input channel destroyed: fd=455
07-17 15:35:48.025  3713  3736 D WindowManager: finishDrawingWindow: Window{53cbfa6d0 u0 com.example.hello/com.example.hello.MainActivity} mDrawState=HAS_DRAWN
,07-17 15:35:48.035  9183  9183 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,07-17 15:35:48.048  9183  9236 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-17 15:35:48.062  9183  9236 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-17 15:35:48.062  9183  9236 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-17 15:35:48.063  9183  9236 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-17 15:35:48.064  9183  9236 W AudioCapabilities: Unsupported mime audio/x-ima
07-17 15:35:48.065  9183  9236 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 15:35:48.065  9183  9236 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 15:35:48.065  9183  9236 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.068  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.069  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.069  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.069  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.069  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.069  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.070  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.076  9183  9236 W VideoCapabilities: Unsupported mime video/wvc1
07-17 15:35:48.077  9183  9236 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-17 15:35:48.080  9183  9236 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 15:35:48.081  9183  9236 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 15:35:48.081  9183  9236 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-17 15:35:48.082  9183  9236 W VideoCapabilities: Unsupported mime video/wvc1
07-17 15:35:48.083  9183  9236 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-17 15:35:48.084  9183  9236 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
07-17 15:35:48.085  9183  9236 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
07-17 15:35:48.086  9183  9236 W VideoCapabilities: Unsupported mime video/mp43
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.088  9183  9236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 15:35:48.091  9183  9236 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 15:35:48.091  9183  9236 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 15:35:48.091  9183  9236 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-17 15:35:48.104  9183  9236 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-17 15:35:48.116  9183  9236 W VideoCapabilities: Unsupported mime video/sorenson
,07-17 15:35:48.135  9183  9236 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.example.hello
,07-17 15:35:48.154  9183  9183 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9183
,07-17 15:35:48.179  9183  9241 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
07-17 15:35:48.179  9183  9183 D SystemWebChromeClient: file:///android_asset/www/index.html: Line 10 : The key "target-densitydpi" is not supported.
,07-17 15:35:48.180  9183  9183 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,07-17 15:35:48.236  9183  9183 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-17 15:35:48.279  9183  9183 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-17 15:35:48.321  3713  3713 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3713  tag : AMS_RESUME_TAIL@CPU_MIN@13
,07-17 15:35:50.318  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:35:50.318  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:35:50.602  3713  3801 I PowerManagerService: [PWL] On : 0 (155391 ms ago)
07-17 15:35:50.602  3713  3801 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-17 15:35:51.209  3713  4746 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 15:35:51.771  4561  4561 D io_stats: !@   8,0 r 24652 2258932 w 3998 66408 d 520 18348 f 1774 1772 iot 9990 9389 th 491448 0 0 pt 0 inp 0 0 156.559
,07-17 15:35:52.252  3294  3769 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 15:35:53.354  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:35:53.354  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:35:53.457  3713  5429 D GameManagerService: identifyGamePackage. com.example.hello
,07-17 15:35:56.240  3713  5429 D SSRM:f  : SIOP:: AP = 260, PST = 270 (W:14), CP = 223, CUR = 144, LCD = 57
,07-17 15:35:56.381  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:35:56.381  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:35:56.777  4561  4561 D io_stats: !@   8,0 r 24652 2258932 w 4029 66564 d 520 18348 f 1775 1773 iot 9990 9392 th 494524 0 0 pt 0 inp 0 0 161.564
,07-17 15:35:57.260  3294  3769 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 15:35:57.394  3713  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-17 15:35:57.421  3713  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-17 15:35:57.421  3713  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-17 15:35:58.871  3713  3713 D UsbMonitorService: readUsbState++
,07-17 15:35:58.872  3713  3713 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 15:35:58.874  3713  3713 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 15:35:58.874  3713  3713 D UsbMonitorService: Posting Message again
,07-17 15:35:59.415  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:35:59.415  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:35:59.468  3713  4202 E Watchdog: !@Sync 5 [17_lip_15_35_59.467]
,07-17 15:36:00.000  3713  3864 D SamsungAlarmManager: Expired : 8
,07-17 15:36:00.002  3713  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{c70f183 type 3 when 164789 android}
,07-17 15:36:00.011  3713  3713 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170717T153700 - CU:1000/CP:3713
,07-17 15:36:00.016  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-17 15:36:00.017  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
,07-17 15:36:00.019  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-17 15:36:00.040  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-17 15:36:00.040  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-17 15:36:00.044  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-17 15:36:00.058  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 15:36:00.061  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 15:36:00.064  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 15:36:00.067  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 15:36:00.083  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 15:36:00.085  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 15:36:00.087  4070  4070 V hong    : mid yDiff = 438
07-17 15:36:00.087  4070  4070 V hong    : mid yDiff = 438
,07-17 15:36:00.088  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-17 15:36:00.089  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-17 15:36:00.095  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
07-17 15:36:00.098  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-17 15:36:00.103  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 15:36:00.106  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 15:36:00.119  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 15:36:00.121  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 15:36:00.126  4958  4958 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
07-17 15:36:00.128  4958  4958 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-17 15:36:00.132  4958  4958 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-17 15:36:00.137  4958  4958 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-17 15:36:00.138  4958  4958 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-17 15:36:00.140  4958  4958 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-17 15:36:00.141  4958  4958 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-17 15:36:00.142  4958  4958 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-17 15:36:00.148  4958  4958 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-17 15:36:00.149  4958  4958 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C2F84DCA3AF99E356842C7BA4382D9148D7E42E4A2D448C0C87011203EBEF249BB143262577CAA90CFA78C8DB1988176A]}
,07-17 15:36:00.152  4958  4958 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-17 15:36:01.266  3713  6658 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 15:36:01.782  4561  4561 D io_stats: !@   8,0 r 24652 2258932 w 4034 66724 d 520 18348 f 1778 1776 iot 9990 9398 th 494564 0 0 pt 0 inp 0 0 166.570
,07-17 15:36:02.444  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:36:02.444  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:36:05.466  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:36:05.467  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:36:06.268  3713  5429 D SSRM:f  : SIOP:: AP = 260, PST = 265 (W:14), CP = 222, CUR = 142, LCD = 57
,07-17 15:36:06.788  4561  4561 D io_stats: !@   8,0 r 24652 2258932 w 4039 66796 d 521 18420 f 1779 1777 iot 9990 9400 th 494576 0 0 pt 0 inp 0 0 171.575
,07-17 15:36:08.500  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:36:08.501  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:36:11.334  3713  3737 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 15:36:11.335  3713  3737 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 15:36:11.335  3713  3737 D BatteryService: online:4, current avg:141, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:142
07-17 15:36:11.336  3713  3713 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 15:36:11.347  3713  3713 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 15:36:11.347  3713  3713 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 15:36:11.352  3713  3713 D GameManagerService: new battery level: 100
07-17 15:36:11.357  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 15:36:11.358  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 15:36:11.369  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-17 15:36:11.376  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 15:36:11.376  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 15:36:11.385  4056  4056 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-17 15:36:11.386  4056  4460 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 15:36:11.403  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 15:36:11.533  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:36:11.533  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:36:11.793  4561  4561 D io_stats: !@   8,0 r 24652 2258932 w 4051 66860 d 521 18420 f 1782 1780 iot 9990 9403 th 494576 0 0 pt 0 inp 0 0 176.581
,07-17 15:36:12.292  3294  3769 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 15:36:14.567  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:36:14.568  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:36:16.296  3713  5429 D SSRM:f  : SIOP:: AP = 260, PST = 263 (W:14), CP = 220, CUR = 89, LCD = 57
,07-17 15:36:16.799  4561  4561 D io_stats: !@   8,0 r 24652 2258932 w 4053 66900 d 522 18424 f 1783 1781 iot 9990 9405 th 494576 0 0 pt 0 inp 0 0 181.586
,07-17 15:36:17.285  3294  3769 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 15:36:17.595  3713  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 15:36:17.595  3713  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -48
,07-17 15:36:18.513  3713  4018 D WifiWatchdogStateMachine:  [|219] []

```
