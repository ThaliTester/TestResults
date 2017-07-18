#### Test 130589065a18bb20_thali04_samsung-SM-G930F Logs


```
--------- beginning of main
,07-18 09:37:36.544  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:37:36.544  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
07-18 09:37:37.249  9830  9830 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9830 | app_process
07-18 09:37:37.249  9830  9830 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-18 09:37:37.255  9830  9830 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-18 09:37:37.255  9830  9830 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-18 09:37:37.260  9830  9830 D AndroidRuntime: CheckJNI is OFF
07-18 09:37:37.261  9830  9830 D AndroidRuntime: addProductProperty: start
07-18 09:37:37.320  9830  9830 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-18 09:37:37.320  9830  9830 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-18 09:37:37.339  9830  9830 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-18 09:37:37.339  9830  9830 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-18 09:37:37.339  9830  9830 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-18 09:37:37.466  9830  9830 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-18 09:37:37.530  9830  9830 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-18 09:37:37.571  9830  9830 I Enhanced Zygote ASLR: DISABLED!
07-18 09:37:37.572  9830  9830 I Radio-JNI: register_android_hardware_Radio DONE
07-18 09:37:37.579  9830  9830 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-18 09:37:37.579  9830  9830 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-18 09:37:37.581  9830  9830 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-18 09:37:37.597  9830  9830 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-18 09:37:37.622  3695  6646 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.example.hello/com.example.hello.MainActivity}} from uid 2000 on display 0
07-18 09:37:37.639  3695  6646 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-18 09:37:37.643  3695  6646 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3695  pkgName : AMS_RESUME@CPU_MIN@7
07-18 09:37:37.648  3695  6646 D ActivityManager: mActivityResumeBooster.acquire()
07-18 09:37:37.650  3695  6646 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{4716fa3d0 #9 A=com.example.hello U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-18 09:37:37.650  3695  6646 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{4716fa3d0 #9 A=com.example.hello U=0 StackId=1 sz=1}
07-18 09:37:37.651  3695  6646 D InputDispatcher: Focused application set to: xxxx
07-18 09:37:37.651  3695  6646 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{4716fa3d0 #9 A=com.example.hello U=0 StackId=1 sz=1} next=ActivityRecord{bc53a07d0 u0 com.example.hello/.MainActivity t9} mFocusedStack=ActivityStack{a1d149ed0 stackId=1, 2 tasks}
07-18 09:37:37.652  3695  6646 D MountService: getExternalStorageMountMode : 1
07-18 09:37:37.652  3695  6646 D MountService: getExternalStorageMountMode : 3
07-18 09:37:37.652  3695  6646 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10054, packageName : com.example.hello
07-18 09:37:37.659  3695  3814 D WindowManager: addWindow: android.view.ViewRootImpl$W@cb3301b displayId=0
07-18 09:37:37.659  3695  3814 D InputTransport: Input channel constructed: fd=453
07-18 09:37:37.659  3695  3814 D InputTransport: Input channel constructed: fd=454
07-18 09:37:37.660  3695  3814 D ViewRootImpl@9d56a2a[hello]: setView = DecorView@b610f91[hello] touchMode=true
07-18 09:37:37.668  9840  9840 E Zygote  : v2
07-18 09:37:37.668  9840  9840 I libpersona: KNOX_SDCARD checking this for 10054
07-18 09:37:37.668  9840  9840 I libpersona: KNOX_SDCARD not a persona
07-18 09:37:37.669  3695  6646 I ActivityManager: Start proc 9840:com.example.hello/u0a54 for activity com.example.hello/.MainActivity
07-18 09:37:37.669  9840  9840 E Zygote  : accessInfo : 0
07-18 09:37:37.672  3695  3814 V WindowManager: Relayout Window{d5e5b8d0 u0 Starting com.example.hello}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-18 09:37:37.673  9830  9830 D AndroidRuntime: Shutting down VM
07-18 09:37:37.673  3114  3114 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, iello
07-18 09:37:37.678  9840  9840 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-18 09:37:37.679  9840  9840 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.hello 
07-18 09:37:37.701  9840  9840 D TimaKeyStoreProvider: TimaSignature is unavailable
07-18 09:37:37.702  9840  9840 D ActivityThread: Added TimaKeyStore provider
07-18 09:37:37.704  3695  3926 I ActivityManager: DSS on for com.example.hello and scale is 1.0
07-18 09:37:37.706  3695  3926 I WindowManager: Failed to capture screenshot of Token{2c974c ActivityRecord{ade1b7fd0 u0 com.samsung.android.MtpApplication/.USBConnection t8}} appWin=Window{7fae26fd0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-18 09:37:37.707  9830  9830 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-18 09:37:37.707  9830  9830 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-18 09:37:37.707  9830  9830 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-18 09:37:37.707  9830  9830 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-18 09:37:37.709  3695  3814 V WindowManager: Now policy hidden: Window{d5e5b8d0 u0 Starting com.example.hello}
07-18 09:37:37.714  3695  3930 V WindowManager: Relayout Window{7fae26fd0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-18 09:37:37.716  3695  3926 D GameManagerService: sem_perfomance_mode: 0
07-18 09:37:37.717  3695  3695 D GameManagerService: NotifyRunnable. pkg: com.example.hello, type: 4, isMinimized: false, isTunableApp: false
07-18 09:37:37.717  3695  3695 D GameManagerService: unexpected mPrevNotiType: -1
07-18 09:37:37.719  3695  4838 V WindowManager: Relayout Window{7df91a2d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-18 09:37:37.723  4930  4930 D Launcher: onTrimMemory. Level: 20
07-18 09:37:37.724  3695  3814 D WindowManager: finishDrawingWindow: Window{d5e5b8d0 u0 Starting com.example.hello} mDrawState=DRAW_PENDING
07-18 09:37:37.724  3695  3926 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-18 09:37:37.724  3695  3926 D GameManagerService: sem_perfomance_mode: 0
07-18 09:37:37.724  3695  3814 D ViewRootImpl@9d56a2a[hello]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-18 09:37:37.726  4768  4784 D ForegroundUtils: could not check pending caller
07-18 09:37:37.726  3695  5815 D GameManagerService: identifyGamePackage. com.example.hello
07-18 09:37:37.726  3695  5815 D GameManagerService: identifyGamePackage. com.example.hello
07-18 09:37:37.727  8252  8331 I ServiceManager: [#CMH#]   IPService already paused:
07-18 09:37:37.727  8252  8331 I ServiceManager: [#CMH#]   FaceService already paused:
07-18 09:37:37.727  8252  8331 I ServiceManager: [#CMH#]   StoryService already paused:
07-18 09:37:37.730  4768  4784 D ForegroundUtils: could not check pending caller
07-18 09:37:37.731  4768  4784 D ForegroundUtils: could not check pending caller
07-18 09:37:37.734  3695  3814 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.AppWindowToken.destroySurfaces:412 com.android.server.wm.AppWindowToken.destroySurfaces:376 com.android.server.wm.WindowStateAnimator.finishExit:654 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:564 com.android.server.wm.WindowAnimator.updateWindowsLocked:439 
07-18 09:37:37.734  3114  4661 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-18 09:37:37.734  3114  3894 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
07-18 09:37:37.735  3695  3814 D WindowManager: finishDrawingWindow: Window{d5e5b8d0 u0 Starting com.example.hello} mDrawState=HAS_DRAWN
,07-18 09:37:37.738  3695  5815 D GameManagerService: identifyGamePackage. com.example.hello
07-18 09:37:37.738  9840  9840 W System  : ClassLoader referenced unknown path: /data/app/com.example.hello-1/lib/arm64
,07-18 09:37:37.740  3695  5815 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 09:37:37.744  3695  3914 V WindowManager: Relayout Window{7df91a2d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-18 09:37:37.746  3695  6646 V WindowManager: Relayout Window{2b7fa50d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,07-18 09:37:37.750  9840  9840 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-18 09:37:37.759  3695  4839 V WindowManager: Relayout Window{7fae26fd0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-18 09:37:37.765  9840  9840 I CordovaLog: Changing log level to DEBUG(3)
07-18 09:37:37.765  9840  9840 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-18 09:37:37.765  9840  9840 D CordovaActivity: CordovaActivity.onCreate()
,07-18 09:37:37.773  9840  9840 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm64
,07-18 09:37:37.778  9840  9840 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-18 09:37:37.821  9840  9840 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 180-184)
07-18 09:37:37.821  9840  9840 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-18 09:37:37.833  9840  9840 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-18 09:37:37.836  9840  9840 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-18 09:37:37.845  9840  9840 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-18 09:37:37.856  3695  3991 D MdnieScenarioControlService:  packageName : com.example.hello    className : com.example.hello.MainActivity
,07-18 09:37:37.995  3695  6646 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10054
07-18 09:37:37.995  3695  6646 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-18 09:37:37.997  3695  3695 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
,07-18 09:37:37.997  3695  3916 I KnoxVpnEngineService: vpn handle : Message received
,07-18 09:37:38.052  9840  9840 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-18 09:37:38.058  9840  9840 D PluginManager: init()
,07-18 09:37:38.061  9840  9840 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-18 09:37:38.072  9840  9840 I cr_Ime  : ImeThread is enabled.
,07-18 09:37:38.075  9840  9880 W cr_media: Requires BLUETOOTH permission
,07-18 09:37:38.099  9840  9840 D CordovaActivity: Started the activity.
,07-18 09:37:38.101  9840  9840 D CordovaActivity: Resumed the activity.
,07-18 09:37:38.114  3695  3930 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@e577b83 displayId=0
,07-18 09:37:38.114  3695  3930 D InputTransport: Input channel constructed: fd=455
07-18 09:37:38.114  3695  3930 D InputTransport: Input channel constructed: fd=456
,07-18 09:37:38.115  3695  3930 D InputTransport: Input channel destroyed: fd=456
07-18 09:37:38.115  9840  9840 D InputTransport: Input channel constructed: fd=98
07-18 09:37:38.116  9840  9840 D ViewRootImpl@d8b96f6[MainActivity]: setView = DecorView@4b26af7[MainActivity] touchMode=true
07-18 09:37:38.116  3695  3731 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-18 09:37:38.116  3695  3731 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,07-18 09:37:38.116  9840  9840 D CordovaActivity: Paused the activity.
07-18 09:37:38.117  3695  3695 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,07-18 09:37:38.118  3695  3695 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-18 09:37:38.120  3695  3780 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-18 09:37:38.136  3695  4838 V WindowManager: Relayout Window{4f08d39d0 u0 com.example.hello/com.example.hello.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-18 09:37:38.137  3114  3114 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-18 09:37:38.147  9840  9888 I OpenGLRenderer: Initialized EGL, version 1.4
07-18 09:37:38.147  9840  9888 D OpenGLRenderer: Swap behavior 1
,07-18 09:37:38.150  9840  9888 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.example.hello
,07-18 09:37:38.155  9840  9888 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-18 09:37:38.156  9840  9840 D CordovaActivity: Stopped the activity.
,07-18 09:37:38.161  3695  3814 V WindowManager: Now policy hidden: Window{4f08d39d0 u0 com.example.hello/com.example.hello.MainActivity}
,07-18 09:37:38.245  3695  4838 D WindowManager: finishDrawingWindow: Window{4f08d39d0 u0 com.example.hello/com.example.hello.MainActivity} mDrawState=DRAW_PENDING
,07-18 09:37:38.246  9840  9840 D ViewRootImpl@d8b96f6[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-18 09:37:38.253  3695  3814 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-18 09:37:38.253  3695  3695 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
,07-18 09:37:38.254  3695  3695 I KnoxTimeoutHandler: SD activityfalse
07-18 09:37:38.254  3695  3695 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
,07-18 09:37:38.254  3695  3814 I ActivityManager: Displayed com.example.hello/.MainActivity: +530ms (total +603ms)
07-18 09:37:38.255  3695  3780 D ActivityManager: mActivityResumeBoosterTail.acquire()
07-18 09:37:38.256  3695  3814 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3695  tag : AMS_RESUME@CPU_MIN@7
07-18 09:37:38.256  3695  3814 D ActivityManager: mActivityResumeBooster.release()
,07-18 09:37:38.256  3695  3814 D ViewRootImpl@9d56a2a[hello]: dispatchDetachedFromWindow
,07-18 09:37:38.257  3695  3814 I WindowManager: Destroying surface Surface(name=Starting com.example.hello) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
07-18 09:37:38.257  3114  4661 I SurfaceFlinger: id=15 Removed iello (3/5)
07-18 09:37:38.257  3695  3780 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3695  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
,07-18 09:37:38.258  3114  4660 I SurfaceFlinger: id=15 Removed iello (-2/5)
,07-18 09:37:38.260  3695  3814 D InputTransport: Input channel destroyed: fd=453
,07-18 09:37:38.261  3695  3814 D InputTransport: Input channel destroyed: fd=454
,07-18 09:37:38.262  3695  4546 D WindowManager: finishDrawingWindow: Window{4f08d39d0 u0 com.example.hello/com.example.hello.MainActivity} mDrawState=HAS_DRAWN
,07-18 09:37:38.271  9840  9840 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,07-18 09:37:38.282  9840  9894 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-18 09:37:38.293  9840  9894 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-18 09:37:38.293  9840  9894 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-18 09:37:38.295  9840  9894 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-18 09:37:38.295  9840  9894 W AudioCapabilities: Unsupported mime audio/x-ima
,07-18 09:37:38.296  9840  9894 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-18 09:37:38.296  9840  9894 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-18 09:37:38.296  9840  9894 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.299  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.300  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.306  9840  9894 W VideoCapabilities: Unsupported mime video/wvc1
07-18 09:37:38.307  9840  9894 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-18 09:37:38.311  9840  9894 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-18 09:37:38.311  9840  9894 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-18 09:37:38.311  9840  9894 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-18 09:37:38.312  9840  9894 W VideoCapabilities: Unsupported mime video/wvc1
07-18 09:37:38.313  9840  9894 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-18 09:37:38.314  9840  9894 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
07-18 09:37:38.315  9840  9894 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
07-18 09:37:38.316  9840  9894 W VideoCapabilities: Unsupported mime video/mp43
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.318  9840  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-18 09:37:38.321  9840  9894 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-18 09:37:38.321  9840  9894 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-18 09:37:38.321  9840  9894 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-18 09:37:38.334  9840  9894 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-18 09:37:38.346  9840  9894 W VideoCapabilities: Unsupported mime video/sorenson
,07-18 09:37:38.363  9840  9894 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.example.hello
,07-18 09:37:38.384  9840  9840 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9840
,07-18 09:37:38.412  9840  9840 D SystemWebChromeClient: file:///android_asset/www/index.html: Line 10 : The key "target-densitydpi" is not supported.
07-18 09:37:38.412  9840  9840 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,07-18 09:37:38.415  9840  9899 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
,07-18 09:37:38.471  9840  9840 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-18 09:37:38.511  9840  9840 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-18 09:37:38.558  3695  3695 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3695  tag : AMS_RESUME_TAIL@CPU_MIN@13
,07-18 09:37:39.559  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:37:39.560  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 09:37:39.591  4647  4647 D io_stats: !@   8,0 r 24864 2281788 w 4147 69332 d 544 18592 f 1807 1807 iot 10200 9587 th 484116 0 0 pt 0 inp 0 0 151.954
,07-18 09:37:39.727  3695  5815 D SSRM:f  : SIOP:: AP = 280, PST = 285 (W:6), CP = 227, CUR = 143, LCD = 57
,07-18 09:37:42.593  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:37:42.594  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 09:37:43.423  3695  3816 I PowerManagerService: [PWL] On : 0 (155787 ms ago)
07-18 09:37:43.424  3695  3816 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-18 09:37:43.635  3695  3914 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-18 09:37:43.729  3695  5815 D GameManagerService: identifyGamePackage. com.example.hello
,07-18 09:37:44.596  4647  4647 D io_stats: !@   8,0 r 24865 2281792 w 4177 69552 d 544 18592 f 1809 1809 iot 10210 9598 th 487756 0 0 pt 0 inp 0 0 156.958
,07-18 09:37:45.618  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:37:45.618  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 09:37:45.730  8252  8277 I ReschedulableTimer: [#CMH#] ReschedulableTimer started 
,07-18 09:37:47.665  3695  3810 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-18 09:37:47.690  3695  3810 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-18 09:37:47.691  3695  3810 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-18 09:37:48.653  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:37:48.653  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 09:37:48.958  3297  3794 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 09:37:49.601  4647  4647 D io_stats: !@   8,0 r 24865 2281792 w 4186 69740 d 544 18592 f 1812 1812 iot 10220 9602 th 487764 0 0 pt 0 inp 0 0 161.964
,07-18 09:37:49.749  3695  5815 D SSRM:f  : SIOP:: AP = 270, PST = 273 (W:6), CP = 226, CUR = 145, LCD = 57
,07-18 09:37:50.669  3297  3794 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 09:37:51.283  3695  3695 D UsbMonitorService: readUsbState++
,07-18 09:37:51.284  3695  3695 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-18 09:37:51.286  3695  3695 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-18 09:37:51.286  3695  3695 D UsbMonitorService: Posting Message again
,07-18 09:37:51.687  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:37:51.687  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:37:51.903  3695  3864 D SamsungAlarmManager: Expired : 4
,07-18 09:37:51.908  3695  3864 D SamsungAlarmManager: setInexact Intent (T:1/F:8/AC:false) 20170808T131358 - CU:1000/CP:3695
,07-18 09:37:51.908  3695  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170718T094736, SetElapsed=749162, nowELAPSED=164272
07-18 09:37:51.909  3695  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170718T093800, SetElapsed=172364, nowELAPSED=164273
07-18 09:37:51.910  3695  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@ccee0b0 alarm=Alarm{68d458a type 2 when 154299 android}
,07-18 09:37:51.914  3695  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
07-18 09:37:51.915  3695  3864 V SamsungAlarmManager: Sending to uid : 10019 action=com.google.android.gms.gcm.ACTION_CHECK_QUEUE alarm=Alarm{812d7fb type 2 when 164267 com.google.android.gms}
,07-18 09:37:51.917  3695  3864 V SamsungAlarmManager: Sending to uid : 1000 action=com.mobeam.barcodeService.UPLOAD_BEAM_RECORD alarm=Alarm{4f6a018 type 1 when 1500363451406 com.mobeam.barcodeService}
,07-18 09:37:51.918  4268  4268 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-18 09:37:51.919  4268  4268 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-18 09:37:51.935  4268  4268 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-18 09:37:51.936  3695  3864 D MountService: getExternalStorageMountMode : 1
07-18 09:37:51.937  3695  3864 D MountService: getExternalStorageMountMode : 3
07-18 09:37:51.937  3695  3864 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.mobeam.barcodeService
,07-18 09:37:51.971  9905  9905 E Zygote  : v2
07-18 09:37:51.971  9905  9905 I libpersona: KNOX_SDCARD checking this for 1000
07-18 09:37:51.971  9905  9905 I libpersona: KNOX_SDCARD not a persona
,07-18 09:37:51.973  9905  9905 E Zygote  : accessInfo : 0
,07-18 09:37:51.980  3695  3864 I ActivityManager: Start proc 9905:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-18 09:37:51.984  9905  9905 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-18 09:37:51.986  9905  9905 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.mobeam.barcodeService 
,07-18 09:37:51.986  3695  3928 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170718T093959 - CU:1000/CP:3695
07-18 09:37:51.987  3695  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170718T093959, SetElapsed=292278, nowELAPSED=164350
07-18 09:37:51.988  3695  3731 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4732 / op:PendingIntent{8823056: PendingIntentRecord{859d74f com.google.android.gms broadcastIntent}}
,07-18 09:37:51.990  3695  3958 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170718T093806 - CU:1000/CP:3695
07-18 09:37:51.990  3695  3958 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170718T093806, SetElapsed=179290, nowELAPSED=164354
,07-18 09:37:52.019  9905  9905 D TimaKeyStoreProvider: TimaSignature is unavailable
07-18 09:37:52.020  9905  9905 D ActivityThread: Added TimaKeyStore provider
,07-18 09:37:52.022  3695  3732 I ActivityManager: DSS on for com.mobeam.barcodeService and scale is 1.0
,07-18 09:37:52.048  9905  9905 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,07-18 09:37:52.065  9905  9905 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-18 09:37:52.089  3695  4544 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103546 - CU:10019/CP:4732
,07-18 09:37:52.143  3695  4546 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103546 - CU:10019/CP:4732
,07-18 09:37:52.153  3695  4544 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4732 / op:PendingIntent{308fbe2: PendingIntentRecord{859d74f com.google.android.gms broadcastIntent}}
,07-18 09:37:52.289  3291  3291 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:9765)
,07-18 09:37:52.293  3695  4841 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103608 - CU:10019/CP:4732
,07-18 09:37:52.312  3695  4545 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103608 - CU:10019/CP:4732
,07-18 09:37:52.320  9765  9794 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 09:37:52.321  9765  9794 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-18 09:37:52.330  3291  3291 D WVCdm   : Instantiating CDM.
,07-18 09:37:52.332  3291  3365 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:9765)
07-18 09:37:52.332  3291  3365 I WVCdm   : CdmEngine::OpenSession
07-18 09:37:52.332  3291  3365 I WVCdm   : Level3 Library 4445 Mar 30 2016 13:23:54
,07-18 09:37:52.339  3695  3732 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103608 - CU:10019/CP:4732
07-18 09:37:52.340  3291  3365 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-18 09:37:52.341  3291  3365 E wv_dash : No saved usage table. Creating new table.
,07-18 09:37:52.354  3695  6643 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4732 / op:PendingIntent{645b5eb: PendingIntentRecord{859d74f com.google.android.gms broadcastIntent}}
,07-18 09:37:52.360  3291  3365 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
,07-18 09:37:52.375  3695  6641 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103546 - CU:10019/CP:4732
,07-18 09:37:52.383  3291  3365 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,07-18 09:37:52.414  3291  3365 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-18 09:37:52.415  3291  3291 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-18 09:37:52.418  3291  3291 D WVCdm   : PrepareKeyRequest: nonce=1755935367
,07-18 09:37:52.746  3291  9786 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:9765)
07-18 09:37:52.746  3291  9786 I WVCdm   : CdmEngine::CloseSession
,07-18 09:37:52.752  3291  9786 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
,07-18 09:37:53.392  3695  4463 E Watchdog: !@Sync 5 [18_lip_09_37_53.392]
,07-18 09:37:53.399  5223  6590 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-18 09:37:53.399  5223  6590 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-18 09:37:53.401  3297  3798 D EnterpriseController: netId is 0
07-18 09:37:53.401  3297  3798 D Netd    : getNetworkForDns: using netid 502 for uid 10019
07-18 09:37:53.401  3297  3798 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-18 09:37:53.706  3695  3954 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-18 09:37:54.415  3695  3732 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4732 / op:PendingIntent{3c7c5c7: PendingIntentRecord{859d74f com.google.android.gms broadcastIntent}}
,07-18 09:37:54.551  3695  3926 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103608 - CU:10019/CP:4732
,07-18 09:37:54.567  3695  4544 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103608 - CU:10019/CP:4732
,07-18 09:37:54.599  3695  4839 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103608 - CU:10019/CP:4732
,07-18 09:37:54.604  4647  4647 D io_stats: !@   8,0 r 24874 2281844 w 4233 70232 d 547 18692 f 1835 1835 iot 10290 9623 th 483764 0 0 pt 0 inp 0 0 166.967
,07-18 09:37:54.613  3695  3942 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4732 / op:PendingIntent{30baf60: PendingIntentRecord{859d74f com.google.android.gms broadcastIntent}}
,07-18 09:37:54.633  3695  4546 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170718T103546 - CU:10019/CP:4732
,07-18 09:37:54.709  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:37:54.710  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 09:37:55.912  3297  3795 D Netd    : Iface wlan0 link up
,07-18 09:37:55.914  4268  4268 I wpa_supplicant: nl80211: Received scan results (39 BSSes)
,07-18 09:37:55.919  3695  3812 D Tethering: interfaceLinkStateChanged wlan0, true
07-18 09:37:55.919  3695  3812 D Tethering: interfaceStatusChanged wlan0, true
,07-18 09:37:55.923  3695  3958 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3695 / listener:android.app.AlarmManager$ListenerWrapper@2acf8d7
,07-18 09:37:55.926  3695  3958 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170718T093959, SetElapsed=292278, nowELAPSED=168289
,07-18 09:37:57.736  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:37:57.737  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -42
,07-18 09:37:59.609  4647  4647 D io_stats: !@   8,0 r 24874 2281844 w 4254 70332 d 547 18692 f 1835 1835 iot 10290 9629 th 483580 0 0 pt 0 inp 0 0 171.971
,07-18 09:37:59.780  3695  5815 D SSRM:f  : SIOP:: AP = 270, PST = 273 (W:6), CP = 226, CUR = 142, LCD = 57
,07-18 09:38:00.003  3695  3864 D SamsungAlarmManager: Expired : 8
07-18 09:38:00.004  3695  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{fa91c19 type 3 when 172364 android}
,07-18 09:38:00.019  3695  3695 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170718T093900 - CU:1000/CP:3695
07-18 09:38:00.020  3695  3695 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170718T093900, SetElapsed=232364, nowELAPSED=172384
,07-18 09:38:00.026  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-18 09:38:00.027  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-18 09:38:00.027  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-18 09:38:00.046  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-18 09:38:00.047  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-18 09:38:00.049  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-18 09:38:00.057  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-18 09:38:00.059  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 09:38:00.062  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
07-18 09:38:00.065  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 09:38:00.084  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-18 09:38:00.086  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
07-18 09:38:00.087  4070  4070 V hong    : mid yDiff = 438
07-18 09:38:00.087  4070  4070 V hong    : mid yDiff = 438
,07-18 09:38:00.089  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-18 09:38:00.089  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-18 09:38:00.094  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
07-18 09:38:00.096  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 09:38:00.116  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-18 09:38:00.117  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-18 09:38:00.134  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-18 09:38:00.137  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-18 09:38:00.143  5430  5430 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-18 09:38:00.144  5430  5430 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
07-18 09:38:00.150  5430  5430 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-18 09:38:00.155  5430  5430 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-18 09:38:00.156  5430  5430 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
07-18 09:38:00.158  5430  5430 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-18 09:38:00.159  5430  5430 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-18 09:38:00.160  5430  5430 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-18 09:38:00.165  5430  5430 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-18 09:38:00.166  5430  5430 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C87D2ABE5F12D695C38F6DAA1D2A72F9F391EF980C58C708FBC3760245599C659528C61B75770AFD602E4BE9B9B5EC2F5]}
,07-18 09:38:00.167  5430  5430 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-18 09:38:00.764  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:00.764  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:03.782  3695  4547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-18 09:38:03.783  3695  4547 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-18 09:38:03.783  3695  4547 D BatteryService: online:4, current avg:140, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:124
,07-18 09:38:03.790  3695  3695 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-18 09:38:03.802  3695  3695 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-18 09:38:03.802  3695  3695 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-18 09:38:03.803  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:03.803  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
07-18 09:38:03.805  3695  3695 D GameManagerService: new battery level: 100
,07-18 09:38:03.811  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-18 09:38:03.812  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-18 09:38:03.819  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-18 09:38:03.823  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-18 09:38:03.824  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-18 09:38:03.827  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-18 09:38:03.831  4057  4057 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-18 09:38:03.833  4057  4746 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-18 09:38:04.614  4647  4647 D io_stats: !@   8,0 r 24874 2281844 w 4265 70424 d 548 18696 f 1839 1839 iot 10300 9634 th 483560 0 0 pt 0 inp 0 0 176.977
,07-18 09:38:06.831  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:06.831  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:09.437  3297  3794 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 09:38:09.620  4647  4647 D io_stats: !@   8,0 r 24874 2281844 w 4266 70444 d 548 18696 f 1840 1840 iot 10300 9635 th 483600 0 0 pt 0 inp 0 0 181.982
,07-18 09:38:09.802  3695  5815 D SSRM:f  : SIOP:: AP = 260, PST = 270 (W:6), CP = 225, CUR = 81, LCD = 57
,07-18 09:38:09.865  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:09.865  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:10.697  3297  3794 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 09:38:11.919  3695  4020 D WifiWatchdogStateMachine:  [|216] []
,07-18 09:38:12.899  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:12.899  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:14.625  4647  4647 D io_stats: !@   8,0 r 24874 2281844 w 4270 70472 d 548 18696 f 1841 1841 iot 10300 9636 th 483568 0 0 pt 0 inp 0 0 186.987
,07-18 09:38:15.925  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:15.925  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:18.957  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:18.957  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:19.829  3695  5815 D SSRM:f  : SIOP:: AP = 260, PST = 268 (W:10), CP = 223, CUR = 33, LCD = 57
,07-18 09:38:21.288  3695  3695 D UsbMonitorService: readUsbState++
,07-18 09:38:21.289  3695  3695 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-18 09:38:21.291  3695  3695 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-18 09:38:21.291  3695  3695 D UsbMonitorService: Posting Message again
,07-18 09:38:21.986  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:21.986  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:23.394  3695  4463 E Watchdog: !@Sync 6 [18_lip_09_38_23.393]
,07-18 09:38:23.442  3695  3816 I PowerManagerService: [PWL] On : 0 (195806 ms ago)
07-18 09:38:23.443  3695  3816 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-18 09:38:25.020  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:25.020  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:26.035  4923  4998 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-18 09:38:26.035  4923  4998 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-18 09:38:26.035  4923  4998 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-18 09:38:26.051  4923  4998 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 14ms lastUpdatedAfter : 60049 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-18 09:38:27.077  3297  3794 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-18 09:38:27.099  3695  3954 I ActivityManager: KPU : put [com.sec.android.soagent] : 26776 K
,07-18 09:38:27.099  3695  3954 I ActivityManager: Killing 9229:com.sec.android.soagent/1000 (adj 906): DHA:empty #33
,07-18 09:38:27.144  3695  6646 D ActivityManager: cleanUpApplicationRecord -- 9229
,07-18 09:38:27.146  4768  4784 D ForegroundUtils: could not check pending caller
,07-18 09:38:28.053  3695  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-18 09:38:28.054  3695  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-18 09:38:29.640  4647  4647 D io_stats: !@   8,0 r 24874 2281844 w 4276 70568 d 549 18700 f 1843 1843 iot 10310 9640 th 484488 0 0 pt 0 inp 0 0 202.002

```
