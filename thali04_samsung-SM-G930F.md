#### Test 145917619d0aee2c_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,10-11 13:47:36.030  4648  4648 D io_stats: !@   8,0 r 25231 2235444 w 4881 203352 d 602 74608 f 1948 1948 iot 11270 10518 th 500836 0 0 pt 0 inp 0 0 167.165
--------- beginning of main
10-11 13:47:36.519  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:47:36.519  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
10-11 13:47:36.544  9779  9779 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9779 | app_process
10-11 13:47:36.544  9779  9779 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
10-11 13:47:36.550  9779  9779 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
10-11 13:47:36.550  9779  9779 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-11 13:47:36.552  9779  9779 D AndroidRuntime: CheckJNI is OFF
10-11 13:47:36.552  9779  9779 D AndroidRuntime: addProductProperty: start
10-11 13:47:36.590  9779  9779 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
10-11 13:47:36.590  9779  9779 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
10-11 13:47:36.606  9779  9779 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
10-11 13:47:36.606  9779  9779 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
10-11 13:47:36.606  9779  9779 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
10-11 13:47:36.649  9779  9779 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
10-11 13:47:36.667  9779  9779 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-11 13:47:36.689  9779  9779 I Enhanced Zygote ASLR: DISABLED!
10-11 13:47:36.689  9779  9779 I Radio-JNI: register_android_hardware_Radio DONE
10-11 13:47:36.692  9779  9779 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
10-11 13:47:36.692  9779  9779 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
10-11 13:47:36.692  9779  9779 E SemAffinityControl: SemAffinityControl: registerfunction enter
10-11 13:47:36.700  9779  9779 D AndroidRuntime: Calling main entry com.android.commands.am.Am
10-11 13:47:36.719  3701  3919 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}} from uid 2000 on display 0
10-11 13:47:36.762  3701  3919 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
10-11 13:47:36.765  3701  3919 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3701  pkgName : AMS_RESUME@CPU_MIN@7
10-11 13:47:36.768  3701  3919 D ActivityManager: mActivityResumeBooster.acquire()
10-11 13:47:36.770  3701  3919 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{e4a67a8d0 #6 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
10-11 13:47:36.770  3701  3919 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{e4a67a8d0 #6 A=com.thaliproject.thalitest U=0 StackId=1 sz=1}
10-11 13:47:36.771  3701  3919 D InputDispatcher: Focused application set to: xxxx
10-11 13:47:36.771  3701  3919 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{e4a67a8d0 #6 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} next=ActivityRecord{1864bbcd0 u0 com.thaliproject.thalitest/.MainActivity t6} mFocusedStack=ActivityStack{d40adb0d0 stackId=1, 3 tasks}
10-11 13:47:36.772  3701  3919 D MountService: getExternalStorageMountMode : 1
10-11 13:47:36.772  3701  3919 D MountService: getExternalStorageMountMode : 3
10-11 13:47:36.772  3701  3919 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10033, packageName : com.thaliproject.thalitest
10-11 13:47:36.776  3701  3798 D WindowManager: addWindow: android.view.ViewRootImpl$W@90883c0 displayId=0
10-11 13:47:36.776  3701  3798 D InputTransport: Input channel constructed: fd=452
10-11 13:47:36.776  3701  3798 D InputTransport: Input channel constructed: fd=453
10-11 13:47:36.777  3701  3798 D ViewRootImpl@384e143[thalitest]: setView = DecorView@71ba03e[thalitest] touchMode=true
10-11 13:47:36.779  3701  3798 V WindowManager: Relayout Window{744c8f9d0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
10-11 13:47:36.779  3113  3113 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, uhalitest
10-11 13:47:36.786  9789  9789 E Zygote  : v2
10-11 13:47:36.786  9789  9789 I libpersona: KNOX_SDCARD checking this for 10033
10-11 13:47:36.787  3701  3919 I ActivityManager: Start proc 9789:com.thaliproject.thalitest/u0a33 for activity com.thaliproject.thalitest/.MainActivity
10-11 13:47:36.788  9789  9789 I libpersona: KNOX_SDCARD not a persona
10-11 13:47:36.789  9789  9789 E Zygote  : accessInfo : 0
10-11 13:47:36.795  9789  9789 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-11 13:47:36.796  9789  9789 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
10-11 13:47:36.807  3701  3798 D WindowManager: finishDrawingWindow: Window{744c8f9d0 u0 Starting com.thaliproject.thalitest} mDrawState=DRAW_PENDING
10-11 13:47:36.807  9779  9779 D AndroidRuntime: Shutting down VM
10-11 13:47:36.821  3701  3798 V WindowManager: Now policy hidden: Window{744c8f9d0 u0 Starting com.thaliproject.thalitest}
10-11 13:47:36.832  9789  9789 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:47:36.833  9789  9789 D ActivityThread: Added TimaKeyStore provider
10-11 13:47:36.835  3701  4928 I ActivityManager: DSS on for com.thaliproject.thalitest and scale is 1.0
10-11 13:47:36.837  9779  9779 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
10-11 13:47:36.837  9779  9779 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
10-11 13:47:36.837  9779  9779 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
10-11 13:47:36.837  9779  9779 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
10-11 13:47:36.837  3701  4928 I WindowManager: Failed to capture screenshot of Token{41e59d0 ActivityRecord{330593d0 u0 com.samsung.android.MtpApplication/.USBConnection t5}} appWin=Window{e787983d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
10-11 13:47:36.837  3701  4928 I WindowManager: Failed to capture screenshot of Token{53f33ae ActivityRecord{f95c429d0 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity t4}} appWin=Window{34e57d2d0 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity} drawState=4
10-11 13:47:36.841  3701  4923 V WindowManager: Relayout Window{e787983d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
10-11 13:47:36.847  3701  4928 D GameManagerService: sem_perfomance_mode: 0
10-11 13:47:36.848  3701  3701 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
10-11 13:47:36.848  3701  3701 D GameManagerService: unexpected mPrevNotiType: -1
10-11 13:47:36.853  3701  4928 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
10-11 13:47:36.853  3701  4928 D GameManagerService: sem_perfomance_mode: 0
10-11 13:47:36.855  4803  6438 D ForegroundUtils: could not check pending caller
10-11 13:47:36.856  4803  4819 D ForegroundUtils: could not check pending caller
10-11 13:47:36.856  3701  5735 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
10-11 13:47:36.856  4803  4819 D ForegroundUtils: could not check pending caller
10-11 13:47:36.856  4803  4819 D ForegroundUtils: could not check pending caller
10-11 13:47:36.856  3701  5735 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
10-11 13:47:36.857  3701  3798 D ViewRootImpl@384e143[thalitest]: MSG_RESIZED: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
10-11 13:47:36.860  3701  3798 V WindowManager: Relayout Window{744c8f9d0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,10-11 13:47:36.863  3701  4541 V WindowManager: Relayout Window{e787983d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,10-11 13:47:36.868  3701  4542 V WindowManager: Relayout Window{69b321ed0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,10-11 13:47:36.868  3701  4542 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowManagerService.tryStartExitingAnimation:3504 com.android.server.wm.WindowManagerService.relayoutWindow:3360 com.android.server.wm.Session.relayoutEx:244 android.view.IWindowSession$Stub.onTransact:407 com.android.server.wm.Session.onTransact:151 
10-11 13:47:36.869  3113  3119 I SurfaceFlinger: id=12 Removed MauncherAct (1/6)
10-11 13:47:36.869  3113  3890 I SurfaceFlinger: id=12 Removed MauncherAct (-2/6)
,10-11 13:47:36.872  3701  4913 V WindowManager: Relayout Window{34e57d2d0 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: viewVisibility=4 req=0x0 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800802 fmt=-2 wanim=0x103038b vsysui=0x2000 surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
10-11 13:47:36.872  3701  5735 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
10-11 13:47:36.873  4961  4961 D Launcher: onTrimMemory. Level: 20
10-11 13:47:36.874  3701  5735 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,10-11 13:47:36.878  3701  3798 D WindowManager: finishDrawingWindow: Window{744c8f9d0 u0 Starting com.thaliproject.thalitest} mDrawState=HAS_DRAWN
10-11 13:47:36.879  3701  4887 V WindowManager: Relayout Window{8c2f594d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,10-11 13:47:36.889  3701  4923 V WindowManager: Relayout Window{34e57d2d0 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: viewVisibility=8 req=0x0 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800802 fmt=-2 wanim=0x103038b vsysui=0x2000 surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,10-11 13:47:36.892  3701  4928 V WindowManager: Relayout Window{69b321ed0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,10-11 13:47:36.897  9789  9789 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:47:36.922  9789  9789 I CordovaLog: Changing log level to DEBUG(3)
10-11 13:47:36.922  9789  9789 I CordovaActivity: Apache Cordova native platform version 6.1.2 is starting
10-11 13:47:36.922  9789  9789 D CordovaActivity: CordovaActivity.onCreate()
,10-11 13:47:36.934  9789  9789 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm
,10-11 13:47:36.941  9789  9789 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,10-11 13:47:36.986  3701  3990 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,10-11 13:47:36.993  9789  9789 I cr_LibraryLoader: Time to load native libraries: 15 ms (timestamps 8114-8129)
10-11 13:47:36.993  9789  9789 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,10-11 13:47:37.013  9789  9789 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,10-11 13:47:37.020  9789  9789 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,10-11 13:47:37.041  9789  9789 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,10-11 13:47:37.181  3701  4541 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10033
,10-11 13:47:37.182  3701  4541 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,10-11 13:47:37.184  3701  3701 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
10-11 13:47:37.184  3701  3917 I KnoxVpnEngineService: vpn handle : Message received
,10-11 13:47:37.215  9789  9789 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9789
,10-11 13:47:37.217  3701  3729 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9789 for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-11 13:47:37.218  3701  3960 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
10-11 13:47:37.218  3701  3960 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]
10-11 13:47:37.218  3701  3960 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
10-11 13:47:37.218  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:47:37.218  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.218  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.218  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.218  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-11 13:47:37.219  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.219  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.219  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.219  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:47:37.219  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:47:37.219  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.219  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-11 13:47:37.261  9789  9789 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,10-11 13:47:37.267  9789  9789 D PluginManager: init()
,10-11 13:47:37.271  9789  9789 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,10-11 13:47:37.287  9789  9789 I cr_Ime  : ImeThread is enabled.
,10-11 13:47:37.299  9789  9789 D CordovaActivity: Started the activity.
,10-11 13:47:37.301  9789  9789 D CordovaActivity: Resumed the activity.
,10-11 13:47:37.313  3701  4915 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@993edaa displayId=0
,10-11 13:47:37.313  3701  4915 D InputTransport: Input channel constructed: fd=454
10-11 13:47:37.314  3701  4915 D InputTransport: Input channel constructed: fd=456
,10-11 13:47:37.314  3701  4915 D InputTransport: Input channel destroyed: fd=456
10-11 13:47:37.315  9789  9789 D InputTransport: Input channel constructed: fd=98
,10-11 13:47:37.315  9789  9789 D ViewRootImpl@17ea6d1[MainActivity]: setView = DecorView@66e536[MainActivity] touchMode=true
10-11 13:47:37.315  3701  3927 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
10-11 13:47:37.315  3701  3927 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
10-11 13:47:37.316  3701  3701 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,10-11 13:47:37.316  9789  9789 D CordovaActivity: Paused the activity.
,10-11 13:47:37.317  3701  3701 I KnoxTimeoutHandler: Shared devices show user statefalse
,10-11 13:47:37.319  3701  3763 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,10-11 13:47:37.327  9789  9789 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9789
,10-11 13:47:37.328  3701  4928 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9789 for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-11 13:47:37.329  3701  3960 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
10-11 13:47:37.329  3701  3960 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
,10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:47:37.329  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-11 13:47:37.340  3701  4913 V WindowManager: Relayout Window{814d538d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,10-11 13:47:37.341  3113  3113 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, NainActivit
,10-11 13:47:37.361  9789  9837 I OpenGLRenderer: Initialized EGL, version 1.4
10-11 13:47:37.361  9789  9837 D OpenGLRenderer: Swap behavior 1
,10-11 13:47:37.364  9789  9837 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,10-11 13:47:37.366  9789  9837 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,10-11 13:47:37.366  9789  9789 D CordovaActivity: Stopped the activity.
,10-11 13:47:37.375  3701  3798 V WindowManager: Now policy hidden: Window{814d538d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}
,10-11 13:47:37.384  9789  9842 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,10-11 13:47:37.399  9789  9842 W AudioCapabilities: Unsupported mime audio/mpeg-L1
10-11 13:47:37.400  9789  9842 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,10-11 13:47:37.401  9789  9842 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,10-11 13:47:37.402  9789  9842 W AudioCapabilities: Unsupported mime audio/x-ima
,10-11 13:47:37.403  9789  9842 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
10-11 13:47:37.403  9789  9842 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
10-11 13:47:37.403  9789  9842 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.406  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.408  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,10-11 13:47:37.416  9789  9842 W VideoCapabilities: Unsupported mime video/wvc1
10-11 13:47:37.417  9789  9842 W VideoCapabilities: Unsupported mime video/x-ms-wmv
10-11 13:47:37.419  3701  3729 D WindowManager: finishDrawingWindow: Window{814d538d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=DRAW_PENDING
10-11 13:47:37.421  9789  9789 D ViewRootImpl@17ea6d1[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
10-11 13:47:37.424  9789  9842 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
10-11 13:47:37.424  9789  9842 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
10-11 13:47:37.424  9789  9842 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
10-11 13:47:37.424  3701  3798 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
10-11 13:47:37.425  3701  3701 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
10-11 13:47:37.426  3701  3701 I KnoxTimeoutHandler: SD activityfalse
10-11 13:47:37.426  3701  3701 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
10-11 13:47:37.426  3701  4540 D WindowManager: finishDrawingWindow: Window{814d538d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=HAS_DRAWN
10-11 13:47:37.426  3701  3798 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +573ms (total +655ms)
10-11 13:47:37.427  3701  3763 D ActivityManager: mActivityResumeBoosterTail.acquire()
10-11 13:47:37.427  9789  9789 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
10-11 13:47:37.427  3701  3798 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3701  tag : AMS_RESUME@CPU_MIN@7
10-11 13:47:37.427  3701  3798 D ActivityManager: mActivityResumeBooster.release()
10-11 13:47:37.428  9789  9842 W VideoCapabilities: Unsupported mime video/wvc1
10-11 13:47:37.429  3701  3798 D ViewRootImpl@384e143[thalitest]: dispatchDetachedFromWindow
10-11 13:47:37.430  3701  3798 I WindowManager: Destroying surface Surface(name=Starting com.thaliproject.thalitest) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
10-11 13:47:37.431  3113  3119 I SurfaceFlinger: id=17 Removed uhalitest (4/6)
10-11 13:47:37.431  3113  8198 I SurfaceFlinger: id=17 Removed uhalitest (-2/6)
10-11 13:47:37.432  3701  3763 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3701  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
10-11 13:47:37.433  9789  9842 W VideoCapabilities: Unsupported mime video/x-ms-wmv
10-11 13:47:37.434  3701  3798 D InputTransport: Input channel destroyed: fd=452
10-11 13:47:37.435  3701  3798 D InputTransport: Input channel destroyed: fd=453
10-11 13:47:37.435  9789  9842 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
10-11 13:47:37.437  9789  9842 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
10-11 13:47:37.438  9789  9842 W VideoCapabilities: Unsupported mime video/mp43
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-11 13:47:37.441  9789  9842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,10-11 13:47:37.444  9789  9842 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
10-11 13:47:37.444  9789  9842 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
10-11 13:47:37.444  9789  9842 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
10-11 13:47:37.458  9789  9842 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
10-11 13:47:37.471  9789  9842 W VideoCapabilities: Unsupported mime video/sorenson
,10-11 13:47:37.487  9789  9842 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,10-11 13:47:37.512  9789  9789 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9789
,10-11 13:47:37.660  9789  9789 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,10-11 13:47:37.671  9789  9789 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,10-11 13:47:37.711  9789  9850 D jxcore_app_log: JniHelper::setJavaVM(0xe73b4000), pthread_self() = -1066927840
,10-11 13:47:37.715  9789  9850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-11 13:47:37.715  9789  9850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-11 13:47:37.715  9789  9850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-11 13:47:37.715  9789  9850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-11 13:47:37.715  9789  9850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-11 13:47:37.715  9789  9850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7422928 added. We now have 1 listener(s)
,10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7422928 added. We now have 1 listener(s)
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-11 13:47:37.716  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-11 13:47:37.721  9789  9850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
10-11 13:47:37.721  9789  9850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
10-11 13:47:37.722  9789  9850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-11 13:47:37.722  9789  9850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,10-11 13:47:37.723  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-11 13:47:37.723  9789  9850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78ca127 added. We now have 2 listener(s)
10-11 13:47:37.724  9789  9850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-11 13:47:37.729  9789  9850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-11 13:47:37.729  9789  9850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 43005
,10-11 13:47:37.730  9789  9850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 116
10-11 13:47:37.730  9789  9850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-11 13:47:37.730  9789  9850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-11 13:47:37.730  9789  9850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-11 13:47:37.730  9789  9850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 116
,10-11 13:47:37.732  3701  3701 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3701  tag : AMS_RESUME_TAIL@CPU_MIN@13
,10-11 13:47:37.737  9789  9850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-11 13:47:37.737  9789  9850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,10-11 13:47:37.746  9789  9850 D BluetoothAdapter: STATE_ON
,10-11 13:47:37.749  9789  9850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:47:37.749  9789  9850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-11 13:47:37.749  9789  9850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-11 13:47:37.749  9789  9850 D io.jxcore.node.ConnectivityMonitor: start: OK
10-11 13:47:37.749  9789  9850 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-11 13:47:37.754  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:47:37.758  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:47:37.762  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:47:37.764  9789  9789 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
10-11 13:47:37.765  9789  9789 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,10-11 13:47:37.862  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:47:38.409  9789  9853 W jxcore-log: Initializing JXcore engine
10-11 13:47:38.409  9789  9853 W jxcore-log: JXcore engine is ready
,10-11 13:47:38.428  3244  3244 E audit   : type=1400 audit(1507722458.416:536): avc:  denied  { ioctl } for  pid=9853 comm="Thread-9" path="socket:[64219]" dev="sockfs" ino=64219 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0 SEPF_SECMOBILE_7.0_0006
,10-11 13:47:38.428  3701  3791 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / /system/bin/sh /system/bin/install-recovery.sh
10-11 13:47:38.428  3244  3244 E audit   : type=1300 audit(1507722458.416:536): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3 a1=5451 a2=978c810d a3=22 items=0 ppid=3272 pid=9853 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-11 13:47:38.429  3701  3791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
10-11 13:47:38.431  3701  3791 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
10-11 13:47:38.431  3701  3763 D MountService: getExternalStorageMountMode : 1
10-11 13:47:38.431  3701  3763 D MountService: getExternalStorageMountMode : 3
10-11 13:47:38.431  3701  3763 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.securitylogagent
,10-11 13:47:38.431  3244  3244 E audit   : type=1327 audit(1507722458.416:536): proctitle="com.thaliproject.thalitest"
10-11 13:47:38.432  3244  3244 E audit   : type=1320 audit(1507722458.416:536): 
10-11 13:47:38.432  3244  3244 E audit   : type=1400 audit(1507722458.416:537): avc:  denied  { ioctl } for  pid=9853 comm="Thread-9" path="/dev/pmsg0" dev="tmpfs" ino=1619 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0 SEPF_SECMOBILE_7.0_0006
10-11 13:47:38.432  3244  3244 E audit   : type=1300 audit(1507722458.416:537): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=4 a1=5451 a2=978c810d a3=22 items=0 ppid=3272 pid=9853 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-11 13:47:38.433  3244  3244 E audit   : type=1327 audit(1507722458.416:537): proctitle="com.thaliproject.thalitest"
10-11 13:47:38.433  3244  3244 E audit   : type=1320 audit(1507722458.416:537): 
10-11 13:47:38.433  3701  3791 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / "com.thaliproject.thalitest"
10-11 13:47:38.433  3244  3244 E audit   : type=1400 audit(1507722458.416:538): avc:  denied  { ioctl } for  pid=9853 comm="Thread-9" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4124 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs_trace_marker:s0 tclass=file permissive=0 SEPF_SECMOBILE_7.0_0006
10-11 13:47:38.434  3244  3244 E audit   : type=1300 audit(1507722458.416:538): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=5 a1=5451 a2=978c810d a3=22 items=0 ppid=3272 pid=9853 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-11 13:47:38.434  3701  3791 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,10-11 13:47:38.434  9789  9853 W jxcore-log: Starting JXcore engine
10-11 13:47:38.436  3244  3244 E audit   : type=1327 audit(1507722458.416:538): proctitle="com.thaliproject.thalitest"
10-11 13:47:38.436  3244  3244 E audit   : type=1320 audit(1507722458.416:538): 
10-11 13:47:38.436  3244  3244 E audit   : type=1400 audit(1507722458.416:539): avc:  denied  { ioctl } for  pid=9853 comm="Thread-9" path="socket:[64255]" dev="sockfs" ino=64255 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0 SEPF_SECMOBILE_7.0_0006
10-11 13:47:38.436  3244  3244 E audit   : type=1300 audit(1507722458.416:539): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=54 a1=5451 a2=978c810d a3=22 items=0 ppid=3272 pid=9853 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-11 13:47:38.437  3244  3244 E audit   : type=1327 audit(1507722458.416:539): proctitle="com.thaliproject.thalitest"
10-11 13:47:38.437  3244  3244 E audit   : type=1320 audit(1507722458.416:539): 
,10-11 13:47:38.448  9856  9856 E Zygote  : v2
10-11 13:47:38.448  9856  9856 I libpersona: KNOX_SDCARD checking this for 1000
10-11 13:47:38.448  9856  9856 I libpersona: KNOX_SDCARD not a persona
,10-11 13:47:38.448  9856  9856 E Zygote  : accessInfo : 0
,10-11 13:47:38.452  9856  9856 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:47:38.452  9856  9856 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.securitylogagent 
,10-11 13:47:38.455  3701  3763 I ActivityManager: Start proc 9856:com.samsung.android.securitylogagent/1000 for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,10-11 13:47:38.456  3701  3791 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,10-11 13:47:38.466  9856  9856 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:47:38.466  9856  9856 D ActivityThread: Added TimaKeyStore provider
,10-11 13:47:38.468  3701  4181 I ActivityManager: DSS on for com.samsung.android.securitylogagent and scale is 1.0
,10-11 13:47:38.472  9789  9853 W jxcore-log: Platform android
10-11 13:47:38.472  9789  9853 W jxcore-log: 
10-11 13:47:38.472  9789  9853 W jxcore-log: Process ARCH arm
10-11 13:47:38.472  9789  9853 W jxcore-log: 
,10-11 13:47:38.482  9856  9856 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,10-11 13:47:38.492  9856  9856 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:47:38.495  9856  9856 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,10-11 13:47:38.501  9856  9856 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,10-11 13:47:38.507  3701  3927 I ActivityManager: KPU : put [com.sec.android.app.sbrowser:CustomLogger] : 21268 K
10-11 13:47:38.507  3701  3927 I ActivityManager: Killing 9091:com.sec.android.app.sbrowser:CustomLogger/u0a134 (adj 906): DHA:empty #33
,10-11 13:47:38.535  3701  4928 D ActivityManager: cleanUpApplicationRecord -- 9091
,10-11 13:47:38.540  4803  4817 D ForegroundUtils: could not check pending caller
,10-11 13:47:38.622  9789  9853 I jxcore-log: JXcore Cordova bridge is ready
10-11 13:47:38.622  9789  9853 I jxcore-log: 
10-11 13:47:38.622  9789  9853 W jxcore-log: JXcore engine is started
,10-11 13:47:38.626  9789  9850 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-11 13:47:38.629  9789  9789 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,10-11 13:47:38.629  9789  9789 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-11 13:47:39.541  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:47:39.541  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:47:41.034  4648  4648 D io_stats: !@   8,0 r 25741 2286020 w 4914 204108 d 609 74636 f 1995 1995 iot 11550 10725 th 471076 0 0 pt 0 inp 0 0 172.170
,10-11 13:47:41.499  3701  5735 D SSRM:f  : SIOP:: AP = 340, PST = 301 (W:6), CP = 257, CUR = 45, LCD = 57
,10-11 13:47:42.576  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:47:42.576  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:47:42.858  3701  5735 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,10-11 13:47:44.916  3701  4917 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:47:44.917  3701  4917 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4262, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:47:44.917  3701  4917 D BatteryService: online:4, current avg:-47, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:-359
10-11 13:47:44.917  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:47:44.924  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-11 13:47:44.924  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:47:44.927  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:47:44.931  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:47:44.931  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:47:44.938  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-11 13:47:44.942  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:47:44.942  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:47:44.951  4057  4057 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-11 13:47:44.952  4057  4707 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:47:44.965  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:47:45.601  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:47:45.601  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:47:45.962  9789  9853 I jxcore-log: 2017-10-11 11:47:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-11 13:47:45.962  9789  9853 I jxcore-log: 
,10-11 13:47:45.963  9789  9853 I jxcore-log: 2017-10-11 11:47:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-11 13:47:45.963  9789  9853 I jxcore-log: 
10-11 13:47:45.963  9789  9853 I jxcore-log: 2017-10-11 11:47:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
10-11 13:47:45.963  9789  9853 I jxcore-log: 
,10-11 13:47:45.972  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:47:45.977  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-11 13:47:45.980  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:45.984  9789  9853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,10-11 13:47:45.985  9789  9853 I jxcore-log: 2017-10-11 11:47:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-11 13:47:45.985  9789  9853 I jxcore-log: 
10-11 13:47:45.986  9789  9853 I jxcore-log: 2017-10-11 11:47:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
10-11 13:47:45.986  9789  9853 I jxcore-log: 
10-11 13:47:45.987  9789  9853 I jxcore-log: 2017-10-11 11:47:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-11 13:47:45.987  9789  9853 I jxcore-log: 
,10-11 13:47:46.039  4648  4648 D io_stats: !@   8,0 r 25741 2286020 w 4952 204348 d 609 74636 f 1996 1996 iot 11560 10729 th 473828 0 0 pt 0 inp 0 0 177.174
,10-11 13:47:46.263  9789  9853 D ExecuteNativeTests: Running unit tests
10-11 13:47:46.264  9789  9853 D BluetoothAdapter: enable()
,10-11 13:47:46.269  4057  4922 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-11 13:47:46.270  4057  4922 D AdapterProvider: query
,10-11 13:47:46.286  4057  4922 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@8b48664
,10-11 13:47:46.289  4057  4922 D BluetoothAdapterService: updateEvent - already set, update
,10-11 13:47:46.289  4057  4922 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:47:46.290  4057  4922 D AdapterProvider: update
,10-11 13:47:46.297  4057  4922 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:47:46.301  9789  9853 D BluetoothAdapter: enable(): BT is already enabled..!
,10-11 13:47:46.313  3701  4923 D WifiService: setWifiEnabled: true pid=9789, uid=10033
10-11 13:47:46.314  3701  4923 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-11 13:47:46.315  3701  4923 D WifiControlHistoryProvider: query
,10-11 13:47:46.343  3701  4923 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-11 13:47:46.345  3701  4923 D SecContentProvider: called from android.uid.system:1000
,10-11 13:47:46.346  3701  4923 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-11 13:47:46.352  3701  4923 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-11 13:47:46.353  3701  4923 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-11 13:47:46.825  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-11 13:47:46.852  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-11 13:47:46.852  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-11 13:47:48.628  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:47:48.628  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:47:51.044  4648  4648 D io_stats: !@   8,0 r 25751 2286376 w 4961 204572 d 609 74636 f 2000 2000 iot 11580 10738 th 474148 0 0 pt 0 inp 0 0 182.179
,10-11 13:47:51.525  3701  5735 D SSRM:f  : SIOP:: AP = 340, PST = 306 (W:6), CP = 268, CUR = 51, LCD = 57
,10-11 13:47:51.661  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:47:51.661  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:47:52.904  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:47:54.681  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:47:54.682  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:47:54.982  3701  4180 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
10-11 13:47:54.983  3701  4180 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:47:54.983  3701  4180 D BatteryService: online:4, current avg:105, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:244
,10-11 13:47:54.983  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:47:54.993  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-11 13:47:54.993  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:47:54.997  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:47:55.004  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:47:55.004  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:47:55.012  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-11 13:47:55.026  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:47:55.026  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:47:55.030  4057  4057 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-11 13:47:55.032  4057  4707 D HeadsetStateMachine: Disconnected process message: 10, size: 0
10-11 13:47:55.035  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:47:56.050  4648  4648 D io_stats: !@   8,0 r 25751 2286376 w 4973 204684 d 610 74708 f 2002 2002 iot 11580 10742 th 474120 0 0 pt 0 inp 0 0 187.185
,10-11 13:47:56.360  9789  9853 I com.test.thalitest.ThaliTestRunner: Running UT
,10-11 13:47:56.483  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-11 13:47:56.483  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fabc233 added. We now have 2 listener(s)
10-11 13:47:56.483  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fabc233 added. We now have 3 listener(s)
10-11 13:47:56.483  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-11 13:47:56.484  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
10-11 13:47:56.484  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-11 13:47:56.484  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
10-11 13:47:56.484  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-11 13:47:56.484  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bf69f0 added. We now have 4 listener(s)
10-11 13:47:56.484  9789  9853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-11 13:47:56.486  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-11 13:47:56.496  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:56.504  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
10-11 13:47:56.504  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-11 13:47:56.504  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-11 13:47:56.504  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-11 13:47:56.505  9789  9853 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
10-11 13:47:56.505  9789  9853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-11 13:47:56.505  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-11 13:47:56.505  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-11 13:47:56.505  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-11 13:47:56.506  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,10-11 13:47:56.508  9789  9853 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-11 13:47:56.510  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,10-11 13:47:56.512  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
10-11 13:47:56.512  9789  9853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-11 13:47:56.525  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-11 13:47:56.538  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:47:56.543  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-11 13:47:56.543  9789  9853 D io.jxcore.node.ConnectivityMonitor: start: OK
10-11 13:47:56.543  9789  9853 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
10-11 13:47:56.543  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
,10-11 13:47:56.549  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:47:56.558  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:56.558  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:56.559  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:47:56.559  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.560  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:47:56.568  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:56.568  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:56.569  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.569  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-11 13:47:56.570  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-11 13:47:56.570  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-11 13:47:56.570  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-11 13:47:56.573  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:47:56.574  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-11 13:47:56.576  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-11 13:47:56.576  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-11 13:47:56.576  9789  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-11 13:47:56.576  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-11 13:47:56.576  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-11 13:47:56.577  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-11 13:47:56.577  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-11 13:47:56.577  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-11 13:47:56.580  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:47:56.580  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-11 13:47:56.582  9789  9874 D BluetoothSocket: bindListen(): myUserId = 0
10-11 13:47:56.582  9789  9874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-11 13:47:56.587  9789  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-11 13:47:56.588  9789  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@d564e8f, port: 6, type: 1, local socket address: null, socket type: 0
10-11 13:47:56.592  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-11 13:47:56.592  9789  9853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-11 13:47:56.592  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-11 13:47:56.597  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:56.598  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:56.599  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:56.601  9789  9853 D BluetoothAdapter: isSecureModeEnabled
10-11 13:47:56.602  4057  4708 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:47:56.603  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.603  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-11 13:47:56.605  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:56.606  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:56.607  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-11 13:47:56.608  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-11 13:47:56.608  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,10-11 13:47:56.610  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:56.613  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.613  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.613  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-11 13:47:56.613  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,10-11 13:47:56.614  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "c1e767dc-b61f-4a4c-b0d7-5c4c58423897", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-11 13:47:56.614  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
,10-11 13:47:56.616  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:47:56.616  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-11 13:47:56.617  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.617  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.617  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-11 13:47:56.618  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:47:56.618  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.619  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.619  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.620  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:56.621  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:56.622  9789  9853 D BluetoothAdapter: isSecureModeEnabled
10-11 13:47:56.622  4057  4069 D BtConfig.SecureMode: isSecureModeOn:false
,10-11 13:47:56.622  9789  9853 D BluetoothLeAdvertiser: start advertising
10-11 13:47:56.623  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:56.632  4057  4069 D BtGatt.GattService: registerClient() - UUID=edb86328-73d1-46db-b331-ba2f9fe8a87a
,10-11 13:47:56.735  4057  4179 D BtGatt.GattService: onClientRegistered() - UUID=edb86328-73d1-46db-b331-ba2f9fe8a87a, clientIf=5, status=0
,10-11 13:47:56.736  9789  9800 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-11 13:47:56.739  4057  4068 E BtGatt.ContextMap: Context not found for ID 5
10-11 13:47:56.740  4057  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-11 13:47:56.741  4057  4570 D BtGatt.AdvertiseManager: message : 0
10-11 13:47:56.742  4057  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-11 13:47:56.742  4057  4570 D BtGatt.AdvertiseManager: size of list is =0
,10-11 13:47:56.747  4057  4570 D BtGatt.AdvertiseManager: starting advertising
,10-11 13:47:56.750  4057  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-11 13:47:56.753  4057  4636 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-11 13:47:56.767  4057  4179 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-11 13:47:56.770  4057  4570 D BtGatt.AdvertiseManager: starting multi advertising
,10-11 13:47:56.777  4057  4179 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-11 13:47:56.777  4057  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-11 13:47:56.777  4057  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-11 13:47:56.778  4057  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
10-11 13:47:56.778  4057  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,10-11 13:47:56.779  9789  9801 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-11 13:47:56.781  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.781  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.782  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-11 13:47:56.783  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.784  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.785  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.786  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.786  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.786  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-11 13:47:56.789  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-11 13:47:56.790  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.793  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.794  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:56.795  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:56.796  9789  9853 I io.jxcore.node.ConnectionHelper: start: OK
,10-11 13:47:56.796  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-11 13:47:56.798  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-11 13:47:56.798  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-11 13:47:56.798  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-11 13:47:56.799  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,10-11 13:47:56.800  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,10-11 13:47:56.801  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,10-11 13:47:56.802  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:47:56.802  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-11 13:47:56.802  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-11 13:47:56.803  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:47:56.804  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,10-11 13:47:56.805  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,10-11 13:47:56.806  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
10-11 13:47:56.807  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-11 13:47:56.811  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-11 13:47:56.812  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-11 13:47:56.813  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-11 13:47:56.813  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-11 13:47:56.814  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-11 13:47:57.299  9789  9876 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,10-11 13:47:57.302  9789  9853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-11 13:47:57.303  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
10-11 13:47:57.303  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
10-11 13:47:57.304  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,10-11 13:47:57.304  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
10-11 13:47:57.304  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
10-11 13:47:57.304  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
10-11 13:47:57.305  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
10-11 13:47:57.305  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
10-11 13:47:57.305  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
10-11 13:47:57.305  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
,10-11 13:47:57.305  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
10-11 13:47:57.305  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
10-11 13:47:57.306  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
10-11 13:47:57.306  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
10-11 13:47:57.306  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
10-11 13:47:57.306  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
10-11 13:47:57.307  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
10-11 13:47:57.307  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
10-11 13:47:57.307  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
10-11 13:47:57.307  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
10-11 13:47:57.307  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
,10-11 13:47:57.308  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
10-11 13:47:57.308  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
10-11 13:47:57.308  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
10-11 13:47:57.308  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
,10-11 13:47:57.309  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
10-11 13:47:57.309  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
10-11 13:47:57.309  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
10-11 13:47:57.309  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
10-11 13:47:57.310  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
10-11 13:47:57.310  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
10-11 13:47:57.310  9789  9853 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-11 13:47:57.311  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-11 13:47:57.311  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-11 13:47:57.312  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-11 13:47:57.312  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-11 13:47:57.312  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-11 13:47:57.313  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-11 13:47:57.313  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-11 13:47:57.314  9789  9874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-11 13:47:57.314  9789  9874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-11 13:47:57.314  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-11 13:47:57.314  9789  9874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-11 13:47:57.314  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-11 13:47:57.314  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-11 13:47:57.315  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-11 13:47:57.316  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.316  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-11 13:47:57.316  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-11 13:47:57.318  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.319  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.321  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.322  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.325  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.328  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.329  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-11 13:47:57.332  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.336  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:57.336  9789  9853 D BluetoothLeScanner: could not find callback wrapper
10-11 13:47:57.337  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-11 13:47:57.338  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.339  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.340  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.341  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-11 13:47:57.342  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.345  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.348  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:57.348  9789  9853 D BluetoothLeAdvertiser: stop advertising
,10-11 13:47:57.350  4057  4922 E BtGatt.ContextMap: Context not found for ID 5
,10-11 13:47:57.351  4057  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,10-11 13:47:57.353  4057  4570 D BtGatt.AdvertiseManager: message : 1
,10-11 13:47:57.355  4057  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
10-11 13:47:57.355  4057  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-11 13:47:57.358  4057  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-11 13:47:57.366  4057  4179 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-11 13:47:57.366  4057  4179 D BtGatt.GattService: Client app is not null!
,10-11 13:47:57.367  9789  9800 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-11 13:47:57.369  4057  4708 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-11 13:47:57.371  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-11 13:47:57.372  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.372  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-11 13:47:57.373  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.374  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.375  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.375  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-11 13:47:57.375  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-11 13:47:57.377  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-11 13:47:57.378  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.382  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.382  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-11 13:47:57.383  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.384  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.385  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-11 13:47:57.385  9789  9789 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-11 13:47:57.386  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-11 13:47:57.386  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-11 13:47:57.386  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-11 13:47:57.387  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:47:57.387  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:47:57.387  9789  9877 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
10-11 13:47:57.388  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-11 13:47:57.388  9789  9853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-11 13:47:57.388  9789  9853 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-11 13:47:57.388  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:47:57.389  9789  9853 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
10-11 13:47:57.389  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-11 13:47:57.389  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-11 13:47:57.389  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,10-11 13:47:57.389  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
10-11 13:47:57.389  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:47:57.390  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-11 13:47:57.391  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:47:57.391  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-11 13:47:57.396  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:57.396  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:57.397  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.397  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:47:57.402  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:57.403  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:57.404  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.404  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-11 13:47:57.404  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-11 13:47:57.405  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-11 13:47:57.405  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-11 13:47:57.407  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-11 13:47:57.408  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-11 13:47:57.408  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-11 13:47:57.408  9789  9878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-11 13:47:57.408  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-11 13:47:57.409  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-11 13:47:57.409  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-11 13:47:57.409  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-11 13:47:57.409  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-11 13:47:57.409  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-11 13:47:57.412  9789  9878 D BluetoothSocket: bindListen(): myUserId = 0
10-11 13:47:57.412  9789  9878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-11 13:47:57.417  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-11 13:47:57.417  9789  9853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-11 13:47:57.417  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-11 13:47:57.419  9789  9878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,10-11 13:47:57.420  9789  9878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@e428708, port: 6, type: 1, local socket address: null, socket type: 0
,10-11 13:47:57.422  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.424  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.427  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.431  9789  9853 D BluetoothAdapter: isSecureModeEnabled
,10-11 13:47:57.432  4057  4708 D BtConfig.SecureMode: isSecureModeOn:false
,10-11 13:47:57.433  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.433  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-11 13:47:57.435  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.437  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.437  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-11 13:47:57.438  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-11 13:47:57.438  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,10-11 13:47:57.441  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.446  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.447  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.447  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-11 13:47:57.447  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,10-11 13:47:57.447  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "c1e767dc-b61f-4a4c-b0d7-5c4c58423897", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-11 13:47:57.448  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
,10-11 13:47:57.448  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:47:57.449  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-11 13:47:57.449  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.450  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.450  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-11 13:47:57.451  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-11 13:47:57.451  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.452  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.453  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.455  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.457  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.457  9789  9853 D BluetoothAdapter: isSecureModeEnabled
10-11 13:47:57.457  4057  4069 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:47:57.458  9789  9853 D BluetoothLeAdvertiser: start advertising
,10-11 13:47:57.460  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:57.467  4057  4069 D BtGatt.GattService: registerClient() - UUID=f782dc6a-8dee-49b0-8870-93a265522820
,10-11 13:47:57.571  4057  4179 D BtGatt.GattService: onClientRegistered() - UUID=f782dc6a-8dee-49b0-8870-93a265522820, clientIf=5, status=0
,10-11 13:47:57.572  9789  9801 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-11 13:47:57.575  4057  4922 E BtGatt.ContextMap: Context not found for ID 5
,10-11 13:47:57.575  4057  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-11 13:47:57.576  4057  4570 D BtGatt.AdvertiseManager: message : 0
10-11 13:47:57.577  4057  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-11 13:47:57.578  4057  4570 D BtGatt.AdvertiseManager: size of list is =0
,10-11 13:47:57.582  4057  4570 D BtGatt.AdvertiseManager: starting advertising
,10-11 13:47:57.586  4057  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-11 13:47:57.588  4057  4636 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-11 13:47:57.602  4057  4179 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-11 13:47:57.604  4057  4570 D BtGatt.AdvertiseManager: starting multi advertising
,10-11 13:47:57.611  4057  4179 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-11 13:47:57.611  4057  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,10-11 13:47:57.612  4057  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-11 13:47:57.612  4057  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
10-11 13:47:57.612  4057  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
10-11 13:47:57.612  9789  9800 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-11 13:47:57.614  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.614  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.614  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-11 13:47:57.615  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.616  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.616  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.617  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.618  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.618  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-11 13:47:57.621  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-11 13:47:57.621  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.621  9789  9853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,10-11 13:47:57.625  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.626  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:57.627  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:57.628  9789  9853 I io.jxcore.node.ConnectionHelper: start: OK
10-11 13:47:57.628  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-11 13:47:57.629  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.630  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-11 13:47:57.630  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-11 13:47:57.631  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
10-11 13:47:57.632  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.633  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,10-11 13:47:57.634  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:47:57.634  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-11 13:47:57.634  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-11 13:47:57.635  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.636  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.637  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.638  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.639  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.646  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-11 13:47:57.646  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-11 13:47:57.647  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.647  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,10-11 13:47:57.648  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-11 13:47:57.705  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:47:57.705  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:47:57.874  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:47:58.131  9789  9880 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,10-11 13:47:58.136  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,10-11 13:47:58.136  9789  9853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-11 13:47:58.137  9789  9853 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-11 13:47:58.137  9789  9853 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-11 13:47:58.137  9789  9853 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
10-11 13:47:58.137  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-11 13:47:58.138  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:47:58.146  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:58.147  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:58.148  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.148  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
10-11 13:47:58.150  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-11 13:47:58.157  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:58.157  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:58.157  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 43005
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-11 13:47:58.158  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.158  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,10-11 13:47:58.159  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.160  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.160  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.162  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.164  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.165  9789  9853 D BluetoothLeAdvertiser: stop advertising
,10-11 13:47:58.166  4057  4068 E BtGatt.ContextMap: Context not found for ID 5
10-11 13:47:58.167  4057  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,10-11 13:47:58.168  4057  4570 D BtGatt.AdvertiseManager: message : 1
10-11 13:47:58.169  4057  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
,10-11 13:47:58.169  4057  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-11 13:47:58.171  4057  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-11 13:47:58.178  4057  4179 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-11 13:47:58.178  4057  4179 D BtGatt.GattService: Client app is not null!
,10-11 13:47:58.179  9789  9801 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-11 13:47:58.180  4057  4708 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-11 13:47:58.182  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-11 13:47:58.183  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.183  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-11 13:47:58.184  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.184  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.185  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.185  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-11 13:47:58.186  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.187  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.188  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.188  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-11 13:47:58.188  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,10-11 13:47:58.188  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "c1e767dc-b61f-4a4c-b0d7-5c4c58423897", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,10-11 13:47:58.189  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
10-11 13:47:58.189  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:47:58.190  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-11 13:47:58.191  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.192  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.192  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-11 13:47:58.192  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-11 13:47:58.193  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.194  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.195  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.197  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.198  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:58.198  9789  9853 D BluetoothAdapter: isSecureModeEnabled
,10-11 13:47:58.199  4057  4068 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:47:58.199  9789  9853 D BluetoothLeAdvertiser: start advertising
10-11 13:47:58.201  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.207  4057  4068 D BtGatt.GattService: registerClient() - UUID=a60d46a3-e747-4bbc-9b01-838c7b423304
,10-11 13:47:58.310  4057  4179 D BtGatt.GattService: onClientRegistered() - UUID=a60d46a3-e747-4bbc-9b01-838c7b423304, clientIf=5, status=0
,10-11 13:47:58.311  9789  9800 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-11 13:47:58.315  4057  4708 E BtGatt.ContextMap: Context not found for ID 5
10-11 13:47:58.316  4057  4570 D BtGatt.AdvertiseManager: message : 0
10-11 13:47:58.316  4057  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-11 13:47:58.317  4057  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-11 13:47:58.318  4057  4570 D BtGatt.AdvertiseManager: size of list is =0
10-11 13:47:58.327  4057  4570 D BtGatt.AdvertiseManager: starting advertising
10-11 13:47:58.331  4057  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
10-11 13:47:58.335  4057  4636 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-11 13:47:58.354  4057  4179 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-11 13:47:58.358  4057  4570 D BtGatt.AdvertiseManager: starting multi advertising
,10-11 13:47:58.368  4057  4179 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-11 13:47:58.369  4057  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,10-11 13:47:58.369  4057  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-11 13:47:58.369  4057  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
10-11 13:47:58.369  4057  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
10-11 13:47:58.370  9789  9801 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-11 13:47:58.372  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.373  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.374  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-11 13:47:58.374  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.375  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.376  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.377  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.378  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.379  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.379  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-11 13:47:58.380  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.381  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-11 13:47:58.381  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-11 13:47:58.381  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-11 13:47:58.382  9789  9853 I io.jxcore.node.ConnectionHelper: start: OK
10-11 13:47:58.383  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.384  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-11 13:47:58.384  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-11 13:47:58.385  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.386  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,10-11 13:47:58.387  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,10-11 13:47:58.388  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.389  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-11 13:47:58.389  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-11 13:47:58.390  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.391  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,10-11 13:47:58.392  9789  9883 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
10-11 13:47:58.393  9789  9853 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-11 13:47:58.394  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-11 13:47:58.394  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-11 13:47:58.394  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-11 13:47:58.394  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-11 13:47:58.394  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-11 13:47:58.395  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-11 13:47:58.395  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-11 13:47:58.395  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-11 13:47:58.395  9789  9878 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-11 13:47:58.396  9789  9878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-11 13:47:58.396  9789  9878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-11 13:47:58.396  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-11 13:47:58.396  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-11 13:47:58.396  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-11 13:47:58.397  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.397  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-11 13:47:58.397  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-11 13:47:58.398  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.399  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.400  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.401  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.403  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.406  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:58.406  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-11 13:47:58.409  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.412  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:58.412  9789  9853 D BluetoothLeScanner: could not find callback wrapper
10-11 13:47:58.412  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-11 13:47:58.413  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.415  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.416  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.416  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-11 13:47:58.417  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.419  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.420  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:58.421  9789  9853 D BluetoothLeAdvertiser: stop advertising
,10-11 13:47:58.422  4057  4068 E BtGatt.ContextMap: Context not found for ID 5
,10-11 13:47:58.423  4057  4570 D BtGatt.AdvertiseManager: message : 1
10-11 13:47:58.423  4057  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,10-11 13:47:58.424  4057  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
,10-11 13:47:58.424  4057  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-11 13:47:58.427  4057  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-11 13:47:58.433  4057  4179 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-11 13:47:58.433  4057  4179 D BtGatt.GattService: Client app is not null!
,10-11 13:47:58.434  9789  9800 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-11 13:47:58.436  4057  4708 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-11 13:47:58.438  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-11 13:47:58.439  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.439  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-11 13:47:58.440  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.440  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.441  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.441  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-11 13:47:58.441  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-11 13:47:58.443  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-11 13:47:58.444  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.447  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.447  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-11 13:47:58.448  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.449  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.450  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-11 13:47:58.450  9789  9789 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-11 13:47:58.450  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-11 13:47:58.450  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-11 13:47:58.450  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:47:58.450  9789  9884 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
10-11 13:47:58.451  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:47:58.451  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-11 13:47:58.452  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.452  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-11 13:47:58.452  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-11 13:47:58.453  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.453  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
10-11 13:47:58.454  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,10-11 13:47:58.454  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-11 13:47:58.454  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.454  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8703dd added. We now have 3 listener(s)
10-11 13:47:58.454  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8703dd added. We now have 5 listener(s)
10-11 13:47:58.455  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-11 13:47:58.455  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-11 13:47:58.459  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:58.459  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-11 13:47:58.459  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:58.460  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-11 13:47:58.460  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f982b52 added. We now have 6 listener(s)
10-11 13:47:58.460  9789  9853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-11 13:47:58.461  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-11 13:47:58.468  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-11 13:47:58.478  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:47:58.482  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-11 13:47:58.482  9789  9853 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-11 13:47:58.490  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:47:58.497  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:47:58.508  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:47:58.518  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:47:58.522  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-11 13:47:58.522  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-11 13:47:58.522  9789  9853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-11 13:47:58.522  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-11 13:47:58.522  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-11 13:47:58.523  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-11 13:47:58.523  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8703dd removed from the list
10-11 13:47:58.523  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8703dd removed from the list
10-11 13:47:58.523  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-11 13:47:58.523  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f982b52 removed from the list
,10-11 13:47:58.529  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:47:58.530  9789  9853 D io.jxcore.node.ConnectivityMonitor: stop
10-11 13:47:58.530  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-11 13:47:58.533  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,10-11 13:47:58.534  9789  9853 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-11 13:47:58.537  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,10-11 13:47:58.538  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,10-11 13:47:58.540  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
10-11 13:47:58.541  9789  9853 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-11 13:47:58.543  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
10-11 13:47:58.544  9789  9853 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,10-11 13:47:58.546  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
10-11 13:47:58.546  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-11 13:47:58.547  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-11 13:47:58.547  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-11 13:47:58.547  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-11 13:47:58.548  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-11 13:47:58.548  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-11 13:47:58.548  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-11 13:47:58.549  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-11 13:47:58.549  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-11 13:47:58.551  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
10-11 13:47:58.552  9789  9853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-11 13:47:58.552  9789  9853 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-11 13:47:58.552  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,10-11 13:47:58.559  9789  9853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-11 13:47:58.560  9789  9853 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,10-11 13:47:58.560  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
,10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
,10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
10-11 13:47:58.561  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
10-11 13:47:58.562  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
10-11 13:47:58.563  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
10-11 13:47:58.563  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
10-11 13:47:58.563  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
10-11 13:47:58.563  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
10-11 13:47:58.563  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
,10-11 13:47:58.563  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
10-11 13:47:58.563  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
10-11 13:47:58.563  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
10-11 13:47:58.564  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
10-11 13:47:58.564  9789  9853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-11 13:47:58.564  9789  9853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-11 13:47:58.564  9789  9853 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-11 13:47:58.565  9789  9853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-11 13:47:58.565  9789  9853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-11 13:47:58.565  9789  9853 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-11 13:47:58.565  9789  9853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-11 13:47:58.565  9789  9853 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-11 13:47:58.565  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
10-11 13:47:58.576  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-11 13:47:58.577  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
10-11 13:47:58.577  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,10-11 13:47:58.578  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-11 13:47:58.578  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,10-11 13:47:58.578  9789  9853 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,10-11 13:47:58.578  9789  9885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 191)
10-11 13:47:58.578  9789  9853 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-11 13:47:58.578  9789  9885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
10-11 13:47:58.578  9789  9853 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-11 13:47:58.578  9789  9885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
10-11 13:47:58.579  9789  9885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
,10-11 13:47:58.581  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
10-11 13:47:58.581  9789  9853 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,10-11 13:47:58.583  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,10-11 13:47:58.584  9789  9853 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-11 13:47:58.586  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,10-11 13:47:58.586  9789  9853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-11 13:47:58.587  9789  9853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,10-11 13:47:58.587  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-11 13:47:58.587  9789  9853 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-11 13:47:58.587  9789  9853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-11 13:47:58.587  9789  9853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-11 13:47:58.588  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-11 13:47:58.588  9789  9853 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-11 13:47:58.588  9789  9853 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-11 13:47:58.588  9789  9853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-11 13:47:58.588  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-11 13:47:58.588  9789  9853 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-11 13:47:58.589  9789  9885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,10-11 13:47:58.589  9789  9885 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,10-11 13:47:58.590  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-11 13:47:58.590  9789  9853 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-11 13:47:58.591  9789  9853 V io.jxcore.node.ConnectivityMonitor: start: Already started
,10-11 13:47:58.591  9789  9853 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-11 13:47:58.591  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,10-11 13:47:58.591  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:47:58.595  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,10-11 13:47:58.595  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:58.596  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.596  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:47:58.599  9789  9885 D BluetoothSocket: connect(): myUserId = 0
,10-11 13:47:58.599  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:58.599  9789  9885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-11 13:47:58.599  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-11 13:47:58.600  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.600  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-11 13:47:58.600  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-11 13:47:58.600  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-11 13:47:58.600  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-11 13:47:58.602  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-11 13:47:58.603  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-11 13:47:58.603  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-11 13:47:58.603  9789  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-11 13:47:58.603  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-11 13:47:58.603  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-11 13:47:58.603  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-11 13:47:58.603  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-11 13:47:58.603  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-11 13:47:58.603  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-11 13:47:58.606  9789  9886 D BluetoothSocket: bindListen(): myUserId = 0
,10-11 13:47:58.607  9789  9886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-11 13:47:58.610  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-11 13:47:58.610  9789  9853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-11 13:47:58.610  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-11 13:47:58.611  9789  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-11 13:47:58.611  9789  9886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@47500d9, port: 6, type: 1, local socket address: null, socket type: 0
,10-11 13:47:58.614  3701  3729 D SecContentProvider: insert(), uri = 2
10-11 13:47:58.614  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.615  3701  3729 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:47:58.616  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.616  4057  4636 W bt_btif : bta_dm_bl_change_cback : reason=0
,10-11 13:47:58.618  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.618  4057  4179 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,10-11 13:47:58.622  9789  9853 D BluetoothAdapter: isSecureModeEnabled
,10-11 13:47:58.622  4057  4922 D BtConfig.SecureMode: isSecureModeOn:false
,10-11 13:47:58.623  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.623  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-11 13:47:58.625  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.626  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:58.626  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-11 13:47:58.626  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-11 13:47:58.626  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,10-11 13:47:58.628  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.631  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.631  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.632  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-11 13:47:58.632  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
10-11 13:47:58.632  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "c1e767dc-b61f-4a4c-b0d7-5c4c58423897", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,10-11 13:47:58.632  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
10-11 13:47:58.633  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:47:58.633  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-11 13:47:58.633  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.634  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.634  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,10-11 13:47:58.634  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:47:58.635  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.635  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.636  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.637  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.638  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:58.638  9789  9853 D BluetoothAdapter: isSecureModeEnabled
10-11 13:47:58.639  4057  4069 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:47:58.639  9789  9853 D BluetoothLeAdvertiser: start advertising
,10-11 13:47:58.640  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:58.644  4057  4069 D BtGatt.GattService: registerClient() - UUID=de8e425b-96e2-4a0c-a671-4077444295b7
,10-11 13:47:58.709  3701  4018 D WifiWatchdogStateMachine:  [|210] []
,10-11 13:47:58.747  4057  4179 D BtGatt.GattService: onClientRegistered() - UUID=de8e425b-96e2-4a0c-a671-4077444295b7, clientIf=5, status=0
,10-11 13:47:58.748  9789  9800 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-11 13:47:58.752  4057  4708 E BtGatt.ContextMap: Context not found for ID 5
10-11 13:47:58.753  4057  4570 D BtGatt.AdvertiseManager: message : 0
10-11 13:47:58.753  4057  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,10-11 13:47:58.755  4057  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-11 13:47:58.755  4057  4570 D BtGatt.AdvertiseManager: size of list is =0
,10-11 13:47:58.765  4057  4570 D BtGatt.AdvertiseManager: starting advertising
,10-11 13:47:58.769  4057  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-11 13:47:58.773  4057  4636 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-11 13:47:58.793  4057  4179 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-11 13:47:58.797  4057  4570 D BtGatt.AdvertiseManager: starting multi advertising
,10-11 13:47:58.808  4057  4179 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-11 13:47:58.809  4057  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,10-11 13:47:58.809  4057  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-11 13:47:58.809  4057  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
10-11 13:47:58.809  4057  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
10-11 13:47:58.810  9789  9801 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-11 13:47:58.812  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.813  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.813  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-11 13:47:58.814  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.815  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.816  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.817  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.818  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.819  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-11 13:47:58.822  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-11 13:47:58.824  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.824  9789  9853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,10-11 13:47:58.829  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:58.830  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.831  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:58.832  9789  9853 I io.jxcore.node.ConnectionHelper: start: OK
10-11 13:47:58.832  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-11 13:47:58.834  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,10-11 13:47:58.835  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,10-11 13:47:58.836  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-11 13:47:58.836  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.837  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.838  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-11 13:47:58.838  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.838  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-11 13:47:58.838  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-11 13:47:58.839  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.839  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.840  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.840  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.841  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-11 13:47:58.847  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-11 13:47:58.847  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-11 13:47:58.848  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-11 13:47:58.849  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-11 13:47:58.849  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-11 13:47:59.334  9789  9876 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
10-11 13:47:59.335  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-11 13:47:59.336  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-11 13:47:59.336  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-11 13:47:59.336  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-11 13:47:59.336  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-11 13:47:59.337  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-11 13:47:59.337  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-11 13:47:59.337  9789  9886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-11 13:47:59.337  9789  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-11 13:47:59.337  9789  9886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-11 13:47:59.337  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-11 13:47:59.338  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-11 13:47:59.338  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-11 13:47:59.338  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-11 13:47:59.338  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-11 13:47:59.340  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fabc233 removed from the list
10-11 13:47:59.341  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fabc233 removed from the list
10-11 13:47:59.341  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-11 13:47:59.341  9789  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 191
10-11 13:47:59.341  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-11 13:47:59.341  9789  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,10-11 13:47:59.341  9789  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 191)
,10-11 13:47:59.342  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.342  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-11 13:47:59.342  9789  9888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 191)
10-11 13:47:59.342  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-11 13:47:59.344  4057  4783 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
10-11 13:47:59.344  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.345  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.346  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.347  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.348  9789  9885 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
10-11 13:47:59.348  9789  9885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
,10-11 13:47:59.350  9789  9885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 191)
10-11 13:47:59.350  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:59.354  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:59.354  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-11 13:47:59.357  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:59.360  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:59.361  9789  9853 D BluetoothLeScanner: could not find callback wrapper
10-11 13:47:59.361  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-11 13:47:59.362  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:59.363  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:59.364  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.365  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-11 13:47:59.366  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:59.369  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:47:59.371  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:47:59.371  9789  9853 D BluetoothLeAdvertiser: stop advertising
,10-11 13:47:59.374  4057  4068 E BtGatt.ContextMap: Context not found for ID 5
,10-11 13:47:59.375  4057  4570 D BtGatt.AdvertiseManager: message : 1
10-11 13:47:59.375  4057  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,10-11 13:47:59.377  4057  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
10-11 13:47:59.377  4057  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-11 13:47:59.380  4057  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-11 13:47:59.391  4057  4179 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-11 13:47:59.391  4057  4179 D BtGatt.GattService: Client app is not null!
,10-11 13:47:59.392  9789  9800 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-11 13:47:59.395  4057  4922 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-11 13:47:59.397  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-11 13:47:59.399  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.399  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-11 13:47:59.400  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:59.401  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.402  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.402  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-11 13:47:59.402  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-11 13:47:59.405  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-11 13:47:59.406  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:59.411  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:47:59.411  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-11 13:47:59.412  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:59.413  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:47:59.413  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bf69f0 removed from the list
10-11 13:47:59.413  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:47:59.413  9789  9853 D io.jxcore.node.ConnectivityMonitor: stop
10-11 13:47:59.414  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-11 13:47:59.414  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:47:59.414  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-11 13:47:59.415  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,10-11 13:47:59.416  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:47:59.416  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-11 13:47:59.417  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-11 13:47:59.417  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-11 13:47:59.418  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,10-11 13:47:59.419  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:47:59.420  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-11 13:47:59.749  3701  4018 D IcmpEchoPeer: res : -1, -1062731519 : 0 / 1008
,10-11 13:47:59.922  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-11 13:48:00.001  3701  3864 D SamsungAlarmManager: Expired : 8
,10-11 13:48:00.002  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{f634f98 type 3 when 191137 android}
,10-11 13:48:00.011  3701  3701 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171011T134900 - CU:1000/CP:3701
10-11 13:48:00.012  3701  3701 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171011T134900, SetElapsed=251137, nowELAPSED=191149
,10-11 13:48:00.017  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,10-11 13:48:00.018  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-11 13:48:00.018  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-11 13:48:00.047  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
10-11 13:48:00.047  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-11 13:48:00.049  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-11 13:48:00.058  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:48:00.060  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:48:00.067  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:48:00.069  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:48:00.080  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:48:00.081  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:48:00.090  4070  4070 V hong    : mid yDiff = 438
10-11 13:48:00.090  4070  4070 V hong    : mid yDiff = 438
10-11 13:48:00.090  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
,10-11 13:48:00.090  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-11 13:48:00.092  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:48:00.095  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:48:00.110  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:48:00.112  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:48:00.127  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-11 13:48:00.131  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-11 13:48:00.136  5166  5166 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-11 13:48:00.138  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-11 13:48:00.142  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-11 13:48:00.148  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-11 13:48:00.149  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,10-11 13:48:00.151  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
10-11 13:48:00.152  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-11 13:48:00.153  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-11 13:48:00.158  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-11 13:48:00.159  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CCC51ED6ECAC67D3269459B179A63D262AB9C31F4A872D6DE3AC9A8E9708D55BC068728AAE4253B0C52ADE5E8DA7A864470502753EF972651964E7A9C66CFD5D6]}
,10-11 13:48:00.160  5166  5166 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-11 13:48:00.728  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:00.728  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:01.055  4648  4648 D io_stats: !@   8,0 r 25791 2287464 w 5018 205520 d 625 74768 f 2018 2018 iot 11680 10776 th 474280 0 0 pt 0 inp 0 0 192.190
,10-11 13:48:01.558  3701  5735 D SSRM:f  : SIOP:: AP = 310, PST = 310 (W:14), CP = 266, CUR = 163, LCD = 57
,10-11 13:48:02.367  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:48:02.369  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-11 13:48:02.371  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:48:02.371  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:48:03.748  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:03.749  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:04.417  9789  9877 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,10-11 13:48:04.422  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-11 13:48:04.425  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-11 13:48:04.425  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-11 13:48:04.429  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-11 13:48:04.431  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-11 13:48:04.431  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-11 13:48:04.432  9789  9889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-11 13:48:04.432  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-11 13:48:04.432  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-11 13:48:04.432  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-11 13:48:04.433  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-11 13:48:04.436  9789  9889 D BluetoothSocket: bindListen(): myUserId = 0
10-11 13:48:04.436  9789  9889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-11 13:48:04.437  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,10-11 13:48:04.439  9789  9853 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
,10-11 13:48:04.440  9789  9853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-11 13:48:04.441  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-11 13:48:04.443  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-11 13:48:04.446  9789  9889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-11 13:48:04.446  9789  9889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@5adf97f, port: 6, type: 1, local socket address: null, socket type: 0
10-11 13:48:04.447  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,10-11 13:48:04.459  9789  9853 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-11 13:48:04.461  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-11 13:48:04.461  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-11 13:48:04.461  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-11 13:48:04.461  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-11 13:48:04.461  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-11 13:48:04.461  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-11 13:48:04.462  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-11 13:48:04.462  9789  9889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-11 13:48:04.462  9789  9889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-11 13:48:04.462  9789  9853 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fabc233 not in the list
10-11 13:48:04.462  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-11 13:48:04.462  9789  9889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-11 13:48:04.462  9789  9853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fabc233 not in the list
10-11 13:48:04.462  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-11 13:48:04.462  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-11 13:48:04.462  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-11 13:48:04.462  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-11 13:48:04.463  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:04.463  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-11 13:48:04.463  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-11 13:48:04.464  9789  9853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-11 13:48:04.464  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-11 13:48:04.464  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:04.468  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:04.468  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-11 13:48:04.469  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:04.469  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:04.470  9789  9853 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bf69f0 not in the list
10-11 13:48:04.470  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:48:04.470  9789  9853 D io.jxcore.node.ConnectivityMonitor: stop
10-11 13:48:04.470  9789  9853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-11 13:48:04.470  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-11 13:48:04.470  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:48:04.470  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-11 13:48:04.473  9789  9853 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
10-11 13:48:04.474  9789  9853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-11 13:48:04.474  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-11 13:48:04.475  9789  9853 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-11 13:48:04.475  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-11 13:48:04.475  9789  9853 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-11 13:48:04.475  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-11 13:48:04.477  9789  9853 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,10-11 13:48:04.480  9789  9853 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,10-11 13:48:04.482  9789  9853 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,10-11 13:48:04.483  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
10-11 13:48:04.483  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
10-11 13:48:04.485  9789  9853 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,10-11 13:48:04.486  9789  9853 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-11 13:48:04.487  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-11 13:48:04.487  9789  9853 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-11 13:48:04.487  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-11 13:48:04.487  9789  9853 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,10-11 13:48:04.487  9789  9853 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,10-11 13:48:04.489  9789  9853 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,10-11 13:48:04.490  9789  9853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-11 13:48:04.490  9789  9853 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-11 13:48:04.491  9789  9853 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,10-11 13:48:04.492  9789  9853 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-11 13:48:04.492  9789  9853 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,10-11 13:48:04.493  9789  9853 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-11 13:48:04.493  9789  9853 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-11 13:48:04.495  9789  9853 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,10-11 13:48:04.496  3701  4459 E Watchdog: !@Sync 6 [11_paź_13_48_04.496]
10-11 13:48:04.496  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-11 13:48:04.497  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4521d4c added. We now have 2 listener(s)
10-11 13:48:04.497  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4521d4c added. We now have 3 listener(s)
10-11 13:48:04.497  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-11 13:48:04.500  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,10-11 13:48:04.500  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-11 13:48:04.500  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-11 13:48:04.501  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-11 13:48:04.501  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abd195 added. We now have 4 listener(s)
,10-11 13:48:04.501  9789  9853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-11 13:48:04.502  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-11 13:48:04.507  9789  9853 D BluetoothAdapter: enable()
,10-11 13:48:04.511  4057  4708 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-11 13:48:04.512  4057  4708 D AdapterProvider: query
,10-11 13:48:04.519  4057  4708 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@2c9c93
,10-11 13:48:04.520  4057  4708 D BluetoothAdapterService: updateEvent - already set, update
10-11 13:48:04.520  4057  4708 W BluetoothAdapterService: updateEvent - alreadySet is true
,10-11 13:48:04.520  4057  4708 D AdapterProvider: update
,10-11 13:48:04.524  4057  4708 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:04.526  9789  9853 D BluetoothAdapter: enable(): BT is already enabled..!
,10-11 13:48:04.530  3701  4913 D WifiService: setWifiEnabled: true pid=9789, uid=10033
10-11 13:48:04.530  3701  4913 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-11 13:48:04.531  3701  4913 D WifiControlHistoryProvider: query
,10-11 13:48:04.536  3701  4913 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-11 13:48:04.537  3701  4913 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:04.538  3701  4913 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-11 13:48:04.541  3701  4913 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-11 13:48:04.541  3701  4913 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-11 13:48:04.544  9789  9853 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,10-11 13:48:04.546  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:04.550  9789  9853 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,10-11 13:48:04.552  9789  9853 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,10-11 13:48:04.554  9789  9853 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,10-11 13:48:04.557  9789  9890 D BluetoothAdapter: disable()
,10-11 13:48:04.561  4057  4069 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : false
10-11 13:48:04.561  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:04.561  4057  4069 D AdapterProvider: query
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:48:04.569  9789  9853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-11 13:48:04.575  4057  4069 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@d51cfce
,10-11 13:48:04.577  4057  4069 D BluetoothAdapterService: updateEvent - already set, update
,10-11 13:48:04.577  4057  4069 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:48:04.577  4057  4069 D AdapterProvider: update
,10-11 13:48:04.581  4057  4069 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:04.588  3701  3797 D SecContentProvider: insert(), uri = 2
,10-11 13:48:04.589  3701  3797 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:04.590  4057  4172 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,10-11 13:48:04.592  4057  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-11 13:48:04.592  4057  4172 D BluetoothAdapterService: Bluetooth PBAP supported is true
,10-11 13:48:04.595  4057  4057 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,10-11 13:48:04.595  4057  4172 D BluetoothAdapterService: Autoconnection is available 
10-11 13:48:04.595  4057  4172 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
10-11 13:48:04.595  4057  4172 D BluetoothAdapterService: terminating service from this receiver
10-11 13:48:04.595  3701  3797 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,10-11 13:48:04.604  4070  4070 D BluetoothPbap: Proxy object disconnected
10-11 13:48:04.604  4070  4070 D PbapServerProfile: Bluetooth service disconnected
,10-11 13:48:04.605  4057  4172 W bt_btif : btif_dm_cancel_discovery
,10-11 13:48:04.607  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
10-11 13:48:04.607  3701  4928 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
10-11 13:48:04.607  4057  4057 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
10-11 13:48:04.607  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:04.607  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:04.609  3701  4928 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:04.610  3701  3919 D SecContentProvider: insert(), uri = 2
10-11 13:48:04.611  3701  3919 D SecContentProvider: called from android.uid.bluetooth:1002
10-11 13:48:04.612  4057  4172 I BluetoothAdapterState: Entering PendingCommandState
,10-11 13:48:04.615  4070  4293 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:04.615  4070  4293 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
10-11 13:48:04.617  3701  3701 D BluetoothPhoneService: Bluetooth Adapter state : 13
,10-11 13:48:04.624  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
10-11 13:48:04.624  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:04.624  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,10-11 13:48:04.634  3701  4913 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{71963f1: PendingIntentRecord{fa92bd6 com.google.android.gms broadcastIntent}}
,10-11 13:48:04.634  4057  4179 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,10-11 13:48:04.635  4057  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
10-11 13:48:04.635  3701  4928 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4057 / op:PendingIntent{3e70e57: PendingIntentRecord{e09cd44 com.android.bluetooth broadcastIntent}}
10-11 13:48:04.639  4057  4172 E BluetoothServiceJni: disableBrEdrNative:
10-11 13:48:04.639  4057  4172 E bt_btif : disable_bredr
10-11 13:48:04.639  9789  9789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:48:04.640  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-11 13:48:04.640  4057  4784 W bt_osi_thread: run_thread: thread id 4784, thread name btif_sock exited
,10-11 13:48:04.641  4057  4179 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:04.644  9789  9789 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-11 13:48:04.644  9789  9789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
10-11 13:48:04.645  4057  4174 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-11 13:48:04.645  4057  4174 E bt_btif : BTA_DisableBluetoothOnly
10-11 13:48:04.645  4057  5029 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-11 13:48:04.645  4057  5026 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-11 13:48:04.646  4057  5029 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-11 13:48:04.646  4057  4636 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
10-11 13:48:04.647  4057  5026 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-11 13:48:04.648  9211  9211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-11 13:48:04.651  4057  5556 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-11 13:48:04.654  3701  4541 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{d4f4e2d: PendingIntentRecord{8642f62 com.google.android.gms broadcastIntent}}
10-11 13:48:04.655  4057  4179 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:04.660  4057  4636 W bt_btm  : btm_sec_connected
10-11 13:48:04.660  4057  4636 W bt_btif : bta_dm_bl_change_cback : reason=2
10-11 13:48:04.660  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:48:04.660  4057  4636 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
10-11 13:48:04.660  4057  4636 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
10-11 13:48:04.660  4057  4636 W bt_btif : bta_dm_bl_change_cback : reason=2
10-11 13:48:04.667  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
10-11 13:48:04.667  4057  4057 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
10-11 13:48:04.667  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:04.667  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:04.667  4057  4057 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:04.668  4057  4179 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:04.668  4057  4057 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
10-11 13:48:04.668  4057  4057 D BluetoothSdpJni: SDP Remove record success - handle: 0
10-11 13:48:04.668  4057  4057 I BtOppRfcommListener: stopping Accept Thread
10-11 13:48:04.669  4057  5556 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-11 13:48:04.670  4057  4763 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
10-11 13:48:04.670  4057  4763 D BluetoothSdpJni: SDP Remove record success - handle: 1
10-11 13:48:04.670  4057  4763 D BluetoothMapMasInstance: RemoveSDPrecord returns true
10-11 13:48:04.670  4057  4763 D ObexServerSockets: shutdown(block = true)
10-11 13:48:04.670  4057  4763 D ObexServerSockets: shutdown called from another thread - interrupt().
10-11 13:48:04.670  4057  4763 D ObexServerSockets: shutdown called from another thread - interrupt().
10-11 13:48:04.676  4057  4179 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:04.678  9211  9211 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
10-11 13:48:04.679  4057  4179 W bt_btif : bti,f_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
10-11 13:48:04.679  4057  4179 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
10-11 13:48:04.688  4057  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:04.690  4057  4179 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 1
10-11 13:48:04.693  9211  9211 D LocalBluetoothManager: LocalBluetoothManager :: constructor
10-11 13:48:04.695  9211  9211 D BluetoothEventManager: BluetoothEventManager Constructor :: 
10-11 13:48:04.699  4057  4179 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
10-11 13:48:04.699  4057  4179 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 241
10-11 13:48:04.699  4070  4293 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
10-11 13:48:04.700  4057  4057 V BluetoothOppManager: cleanUp...
,10-11 13:48:04.705  9211  9211 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
10-11 13:48:04.706  9211  9211 D LocalBluetoothProfileManager: PANU : true
,10-11 13:48:04.718  9211  9211 D BluetoothSap: Create BluetoothSap proxy object
,10-11 13:48:04.724  9211  9211 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
10-11 13:48:04.724  9211  9211 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,10-11 13:48:04.730  9211  9211 D DockEventReceiver: finishStartingService: stopping service
,10-11 13:48:04.737  9211  9211 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:04.737  9211  9211 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
10-11 13:48:04.738  9211  9211 D BluetoothPan: BluetoothPAN Proxy object connected
,10-11 13:48:04.738  9211  9211 D PanProfile: Bluetooth service connected
10-11 13:48:04.740  9211  9211 D BluetoothSap: Proxy object connected
,10-11 13:48:04.740  9211  9211 D SapProfile: Bluetooth service connected
,10-11 13:48:04.792  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-11 13:48:04.800  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-11 13:48:04.800  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-11 13:48:04.826  3701  3800 I PowerManagerService: [PWL] On : 0 (195962 ms ago)
10-11 13:48:04.826  3701  3800 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-11 13:48:04.847  4057  4179 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_BT_EVT
10-11 13:48:04.847  4057  4179 E BluetoothAdapterState: stateChangeCallback : 16
10-11 13:48:04.847  4057  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,10-11 13:48:04.971  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-11 13:48:04.981  4057  4172 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:48:04.982  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,10-11 13:48:04.987  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,10-11 13:48:04.988  4057  4057 D HeadsetService: Received stop request...Stopping profile...
,10-11 13:48:04.992  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
10-11 13:48:04.995  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:04.995  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
10-11 13:48:04.995  4057  4057 D HeadsetService: notifyProfileServiceStateChanged
10-11 13:48:05.000  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
10-11 13:48:05.003  4070  4070 D HeadsetProfile: Bluetooth service disconnected
10-11 13:48:05.004  3701  3701 W BluetoothHeadset: Proxy not attached to service
10-11 13:48:05.004  3701  3701 I Telecom : SecBluetoothManager : not single connected gear
10-11 13:48:05.004  3701  3701 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
10-11 13:48:05.005  3701  3701 D BluetoothHeadset: unRegisterMessageListener : 11
10-11 13:48:05.005  3701  3701 W BluetoothHeadset: Proxy not attached to service
10-11 13:48:05.005  3701  3701 I Telecom : SecBluetoothManager : unregister MessageListener
10-11 13:48:05.005  3701  4553 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACY_0
10-11 13:48:05.005  3701  4553 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACY_0
10-11 13:48:05.005  3701  4553 I Telecom : SecBluetoothManager : mBluetoothHeadset is null
10-11 13:48:05.006  3701  4553 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACY_0
,10-11 13:48:05.008  4057  4057 D A2dpService: Received stop request...Stopping profile...
,10-11 13:48:05.009  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,10-11 13:48:05.013  4057  4755 D A2dpStateMachine: Exit Disconnected: -1
,10-11 13:48:05.018  4057  4057 D Avrcp   : unregisterContentObserver
,10-11 13:48:05.020  4057  4057 D Avrcp   : removeOnActiveSessionsChangedListener
,10-11 13:48:05.021  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.021  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
10-11 13:48:05.021  4057  4057 D A2dpService: notifyProfileServiceStateChanged
10-11 13:48:05.025  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:05.025  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
10-11 13:48:05.025  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
,10-11 13:48:05.025  4057  4057 V BluetoothAdapterState: isTurningOff()=true
10-11 13:48:05.025  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.025  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:05.025  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:05.028  4057  4057 D HidService: Received stop request...Stopping profile...
10-11 13:48:05.029  4057  4057 D HidService: Stopping Bluetooth HidService
10-11 13:48:05.029  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.029  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
10-11 13:48:05.029  4057  4057 D HidService: notifyProfileServiceStateChanged
10-11 13:48:05.031  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
10-11 13:48:05.032  4070  4070 D BluetoothInputDevice: Proxy object disconnected
10-11 13:48:05.032  4070  4070 D HidProfile: Bluetooth service disconnected
10-11 13:48:05.035  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.036  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
10-11 13:48:05.036  4057  4172 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
10-11 13:48:05.036  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
10-11 13:48:05.037  4057  4172 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
10-11 13:48:05.037  4057  4172 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
10-11 13:48:05.037  4070  4070 D A2dpProfile: Bluetooth service disconnected
,10-11 13:48:05.042  3701  3729 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:48:05.043  3701  3729 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:48:05.043  3701  3729 D BatteryService: online:4, current avg:175, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:187
,10-11 13:48:05.044  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:48:05.044  4057  4057 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-11 13:48:05.045  4057  4057 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-11 13:48:05.047  4057  4057 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
10-11 13:48:05.049  4057  4057 D HealthService: Received stop request...Stopping profile...
10-11 13:48:05.049  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.050  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
10-11 13:48:05.050  4057  4057 D HealthService: notifyProfileServiceStateChanged
,10-11 13:48:05.050  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,10-11 13:48:05.050  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
10-11 13:48:05.053  3701  3701 D GameManagerService: new battery level: 100
10-11 13:48:05.055  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:48:05.055  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:48:05.059  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
10-11 13:48:05.061  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
10-11 13:48:05.062  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:48:05.064  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:48:05.070  4057  4057 D PanService: Received stop request...Stopping profile...
,10-11 13:48:05.072  4057  4057 D EnhancedTetheringManager: stop
,10-11 13:48:05.074  4057  4057 D EnhancedTetheringManager: tetherEnabled : false
,10-11 13:48:05.074  4057  4057 D ETMLeHelper: stopAdvertise
10-11 13:48:05.075  4057  4057 D BluetoothAdapter: STATE_TURNING_OFF
,10-11 13:48:05.077  3701  3710 I art     : Background sticky concurrent mark sweep GC freed 166641(11MB) AllocSpace objects, 89(1780KB) LOS objects, 24% free, 41MB/55MB, paused 1.680ms total 132.168ms
,10-11 13:48:05.081  4057  4057 D BluetoothAdapter: STATE_TURNING_OFF
,10-11 13:48:05.081  4057  4057 D BluetoothLeAdvertiser: stop advertising
10-11 13:48:05.082  4057  4057 D BluetoothLeAdvertiser: wrapper is null
10-11 13:48:05.082  4057  4057 D EnhancedTetheringManager: removeNapWakeAlarm
10-11 13:48:05.084  3701  4927 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4057 / op:PendingIntent{cd3905e: PendingIntentRecord{2c54c3f com.android.bluetooth broadcastIntent}}
10-11 13:48:05.085  4057  4057 D EnhancedTetheringManager: cancelFindTetherServer
10-11 13:48:05.085  4057  4057 D ETMLeHelper: stopScan
,10-11 13:48:05.086  4057  4057 D BluetoothAdapter: STATE_TURNING_OFF
,10-11 13:48:05.087  4057  4057 D BluetoothAdapter: STATE_TURNING_OFF
10-11 13:48:05.088  4057  4057 D BluetoothLeScanner: could not find callback wrapper
,10-11 13:48:05.088  4057  4057 D EnhancedTetheringManager: removePanuWakeAlarm
,10-11 13:48:05.090  3701  4928 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4057 / op:PendingIntent{2f6d90c: PendingIntentRecord{4844255 com.android.bluetooth broadcastIntent}}
,10-11 13:48:05.091  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.092  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
10-11 13:48:05.092  4057  4057 D PanService: notifyProfileServiceStateChanged
10-11 13:48:05.093  4070  4070 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-11 13:48:05.093  4070  4070 D PanProfile: Bluetooth service disconnected
10-11 13:48:05.094  9211  9211 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-11 13:48:05.094  9211  9211 D PanProfile: Bluetooth service disconnected
10-11 13:48:05.095  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:05.095  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
10-11 13:48:05.095  4057  4057 V BluetoothAdapterState: isTurningOff()=true
10-11 13:48:05.095  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.095  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:05.096  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:05.096  9789  9890 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:48:05.096  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-11 13:48:05.096  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.097  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:05.097  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
10-11 13:48:05.097  4057  4057 V BluetoothAdapterState: isTurningOff()=true
10-11 13:48:05.097  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.097  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:05.097  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:05.099  4057  4057 D BluetoothMapService: Received stop request...Stopping profile...
,10-11 13:48:05.102  4057  4756 W bt_osi_thread: run_thread: thread id 4756, thread name media_worker exited
,10-11 13:48:05.105  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:05.107  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
,10-11 13:48:05.107  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
10-11 13:48:05.107  4057  4057 D BluetoothMapService: notifyProfileServiceStateChanged
10-11 13:48:05.110  4070  4070 D BluetoothMap: Proxy object disconnected
10-11 13:48:05.110  4070  4070 D MapProfile: Bluetooth service disconnected
10-11 13:48:05.111  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.111  4057  4057 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-11 13:48:05.111  4057  4057 W bt_btif : cleanup: HH disabling or disabled already, status = 0
10-11 13:48:05.112  4057  4057 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-11 13:48:05.115  4057  4057 D SapService: Received stop request...Stopping profile...
,10-11 13:48:05.115  4057  4057 V SapService: stop()
,10-11 13:48:05.117  9789  9890 D BluetoothAdapter: enable()
10-11 13:48:05.118  3701  4916 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{b44546a: PendingIntentRecord{1cc6d5b com.google.android.gms broadcastIntent}}
10-11 13:48:05.119  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.119  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
10-11 13:48:05.119  4057  4057 D SapService: notifyProfileServiceStateChanged
10-11 13:48:05.122  4070  4070 D BluetoothSap: Proxy object disconnected
,10-11 13:48:05.122  4057  4057 D HidDevService: Received stop request...Stopping profile...
10-11 13:48:05.122  4070  4070 D SapProfile: Bluetooth service disconnected
10-11 13:48:05.122  4057  4057 D HidDevService: stop()
10-11 13:48:05.122  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.122  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Message sending
10-11 13:48:05.122  4057  4057 D HidDevService: notifyProfileServiceStateChanged
10-11 13:48:05.124  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:05.124  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
10-11 13:48:05.124  4057  4057 V BluetoothAdapterState: isTurningOff()=true
10-11 13:48:05.124  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.124  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:05.124  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:05.124  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.124  4057  4057 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-11 13:48:05.125  4057  4057 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-11 13:48:05.125  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:05.125  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
10-11 13:48:05.125  4057  4057 V BluetoothAdapterState: isTurningOff()=true
10-11 13:48:05.125  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.125  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
,10-11 13:48:05.125  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:05.125  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.125  4057  4057 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-11 13:48:05.125  4057  4057 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-11 13:48:05.127  3701  4928 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{cbe79f8: PendingIntentRecord{413aed1 com.google.android.gms broadcastIntent}}
10-11 13:48:05.128  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:05.128  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
10-11 13:48:05.128  4057  4057 V BluetoothAdapterState: isTurningOff()=true
10-11 13:48:05.128  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.128  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:05.128  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:05.128  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.128  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:05.129  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
,10-11 13:48:05.133  4057  4057 V BluetoothAdapterState: isTurningOff()=true
10-11 13:48:05.134  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.134  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:05.134  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:05.134  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
,10-11 13:48:05.134  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Before synchronized
10-11 13:48:05.134  4057  4057 V BluetoothAdapterState: isTurningOff()=true
10-11 13:48:05.134  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.134  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:05.134  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:05.134  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.134  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.134  4057  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
10-11 13:48:05.134  4057  4057 D HidDevService: cleanup()
10-11 13:48:05.135  4057  4057 V BluetoothHidDevServiceJni: cleanupNative enter
10-11 13:48:05.135  4057  4057 I BluetoothHidDevServiceJni: Cleaning up interface
10-11 13:48:05.135  4057  4057 I BluetoothHidDevServiceJni: Cleaning up callback object
10-11 13:48:05.135  4057  4057 V BluetoothHidDevServiceJni: cleanupNative done
,10-11 13:48:05.142  4057  4708 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,10-11 13:48:05.142  4057  4708 D AdapterProvider: query
10-11 13:48:05.145  9211  9211 D BluetoothSap: Proxy object disconnected
10-11 13:48:05.146  9211  9211 D SapProfile: Bluetooth service disconnected
,10-11 13:48:05.148  4057  4172 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@ea3f347
,10-11 13:48:05.149  4057  4172 D BtGatt.GattService: serverDisconnectIncomingConnClients()
,10-11 13:48:05.149  4057  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-11 13:48:05.149  4057  4172 D BluetoothAdapterService: Bluetooth PBAP supported is true
,10-11 13:48:05.149  4057  4636 W bt_btif : BTA got unregistered event id 32
,10-11 13:48:05.151  4765  6852 W NearbyMessages: NetworkPollManager:  No operations for client(com.google.android.gms#0p:discoverer). It should not be in the tracker.
10-11 13:48:05.151  4765  6852 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
10-11 13:48:05.158  4057  4708 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@74c3c01
10-11 13:48:05.159  4057  4708 D BluetoothAdapterService: updateEvent - already set, update
10-11 13:48:05.159  4057  4708 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:48:05.159  4057  4708 D AdapterProvider: update
10-11 13:48:05.161  4057  4172 D BluetoothAdapterService: Autoconnection is available 
10-11 13:48:05.161  4057  4172 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
10-11 13:48:05.161  4057  4172 I BluetoothAdapterState: Entering BleOnState
10-11 13:48:05.163  4057  4065 E System  : Uncaught exception thrown by finalizer
10-11 13:48:05.164  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
10-11 13:48:05.164  4057  4057 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
10-11 13:48:05.164  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.164  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.170  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
10-11 13:48:05.170  4057  4057 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
10-11 13:48:05.170  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.170  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.172  4765  6863 I BeaconBle: Client requested to stop, listener=hjz@8708299
10-11 13:48:05.173  4057  4065 E System  : java.io.IOException: socket not created
10-11 13:48:05.173  4057  4065 E System  : 	at android.net.LocalSocketImpl.shutdownInput(LocalSocketImpl.java:404)
10-11 13:48:05.173  4057  4065 E System  : 	at android.net.LocalSocket.shutdownInput(LocalSocket.java:207)
10-11 13:48:05.173  4057  4065 E System  : 	at android.bluetooth.BluetoothSocket.close(BluetoothSocket.java:800)
10-11 13:48:05.173  4057  4065 E System  : 	at android.bluetooth.BluetoothSocket.finalize(BluetoothSocket.java:309)
10-11 13:48:05.173  4057  4065 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:222)
10-11 13:48:05.173  4057  4065 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:209)
10-11 13:48:05.173  4057  4065 E System  : 	at java.lang.Thread.run(Thread.java:762)
10-11 13:48:05.174  4057  4065 E System  : Uncaught exception thrown by finalizer
10-11 13:48:05.176  4057  4708 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:05.181  9789  9801 D BluetoothAdapter: onBluetoothStateChange: up=false
,10-11 13:48:05.181  9789  9801 D BluetoothAdapter: Bluetooth is turned off, stop adv
,10-11 13:48:05.181  9789  9801 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
10-11 13:48:05.181  9789  9801 D BluetoothLeAdvertiser: Exit stop advertising
10-11 13:48:05.182  4057  4065 E System  : java.io.IOException: socket not created
10-11 13:48:05.182  4057  4065 E System  : 	at android.net.LocalSocketImpl.shutdownInput(LocalSocketImpl.java:404)
10-11 13:48:05.182  4057  4065 E System  : 	at android.net.LocalSocket.shutdownInput(LocalSocket.java:207)
10-11 13:48:05.182  4057  4065 E System  : 	at android.bluetooth.BluetoothSocket.close(BluetoothSocket.java:800)
10-11 13:48:05.182  4057  4065 E System  : 	at android.bluetooth.BluetoothSocket.finalize(BluetoothSocket.java:309)
10-11 13:48:05.182  4057  4065 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:222)
10-11 13:48:05.182  4057  4065 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:209)
10-11 13:48:05.182  4057  4065 E System  : 	at java.lang.Thread.run(Thread.java:762)
10-11 13:48:05.183  4765  6863 I BeaconBle: Scan canceled successfully.
10-11 13:48:05.184  3701  4918 W ActivityManager: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-11 13:48:05.185  9789  9801 D BluetoothAdapter: There are no active google scan apps, stop scan
,10-11 13:48:05.186  9789  9801 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
10-11 13:48:05.186  9789  9801 D BluetoothLeScanner: Exiting stopAllScan
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-11 13:48:05.186  3701  4918 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-11 13:48:05.186  3701  4918 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
10-11 13:48:05.186  7713  7725 D BluetoothAdapter: onBluetoothStateChange: up=false
10-11 13:48:05.186  7713  7725 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-11 13:48:05.188  3701  4918 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
10-11 13:48:05.188  3701  4542 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{bf706c2: PendingIntentRecord{8492cd3 com.google.android.gms broadcastIntent}}
10-11 13:48:05.188  3701  4918 D SecContentProvider: called from com.thaliproject.thalitest
10-11 13:48:05.189  4057  4172 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.189  7713  7725 D BluetoothAdapter: There are no active google scan apps, stop scan
10-11 13:48:05.190  4070  4547 D BluetoothSap: onBluetoothStateChange: up=false
10-11 13:48:05.199  4803  4817 D BluetoothAdapter: onBluetoothStateChange: up=false
10-11 13:48:05.199  4803  4817 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-11 13:48:05.200  4803  4817 D BluetoothAdapter: There are no active google scan apps, stop scan
,10-11 13:48:05.202  4070  4085 D BluetoothPbap: onBluetoothStateChange: up=false
,10-11 13:48:05.204  4070  4084 D BluetoothPan: onBluetoothStateChange on: false
,10-11 13:48:05.205  4070  4547 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-11 13:48:05.207  4765  6895 D BluetoothAdapter: onBluetoothStateChange: up=false
10-11 13:48:05.207  4765  6895 D BluetoothAdapter: Bluetooth is turned off, stop adv
,10-11 13:48:05.207  4765  6895 D BluetoothAdapter: There are no active google scan apps, stop scan
10-11 13:48:05.207  4765  6895 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
10-11 13:48:05.208  4765  6895 D BluetoothLeScanner: Exiting stopAllScan
,10-11 13:48:05.208  4057  4922 D BluetoothAdapter: onBluetoothStateChange: up=false
,10-11 13:48:05.210  9211  9222 D BluetoothAdapter: onBluetoothStateChange: up=false
,10-11 13:48:05.210  9211  9222 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-11 13:48:05.211  9211  9222 D BluetoothAdapter: There are no active google scan apps, stop scan
10-11 13:48:05.211  3701  3797 D BluetoothAdapter: onBluetoothStateChange: up=false
10-11 13:48:05.211  3701  3797 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-11 13:48:05.211  3701  3797 D BluetoothAdapter: There are no active google scan apps, stop scan
,10-11 13:48:05.211  4070  4085 D BluetoothAdapter: onBluetoothStateChange: up=false
,10-11 13:48:05.211  4070  4085 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-11 13:48:05.212  4070  4085 D BluetoothAdapter: There are no active google scan apps, stop scan
,10-11 13:48:05.213  4044  4055 D BluetoothAdapter: onBluetoothStateChange: up=false
10-11 13:48:05.213  4044  4055 D BluetoothAdapter: Bluetooth is turned off, stop adv
,10-11 13:48:05.214  4044  4055 D BluetoothAdapter: There are no active google scan apps, stop scan
,10-11 13:48:05.215  9211  9223 D BluetoothPan: onBluetoothStateChange on: false
,10-11 13:48:05.216  4070  4084 D BluetoothMap: onBluetoothStateChange: up=false
,10-11 13:48:05.217  9211  9222 D BluetoothSap: onBluetoothStateChange: up=false
,10-11 13:48:05.220  4057  4172 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,10-11 13:48:05.222  3701  3797 W BluetoothManagerService: BT is in BLE_ON State
,10-11 13:48:05.223  4057  4068 E BluetoothBondStateMachine: initStateMachine
,10-11 13:48:05.224  4070  4293 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,10-11 13:48:05.225  4070  4293 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
10-11 13:48:05.225  3701  3701 D Telecom : SecBluetoothManager : unregister BluetoothHeadset after STATE_OFF : null
10-11 13:48:05.225  3701  3701 D Telecom : SecBluetoothManager : unRegisterBluetoothHeadsetMessageListener fail
10-11 13:48:05.226  3701  3701 D BluetoothPhoneService: Bluetooth Adapter state : 10
,10-11 13:48:05.229  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,10-11 13:48:05.229  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:05.229  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,10-11 13:48:05.235  9211  9211 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:05.236  9211  9211 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,10-11 13:48:05.237  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:05.240  4057  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-11 13:48:05.240  4057  4172 D BluetoothAdapterService: Bluetooth PBAP supported is true
,10-11 13:48:05.241  3701  3797 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
,10-11 13:48:05.241  4057  4172 D BluetoothAdapterService: Autoconnection is available 
,10-11 13:48:05.242  4057  4172 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
10-11 13:48:05.243  3701  4916 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
10-11 13:48:05.243  3701  4917 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{1029010: PendingIntentRecord{25c6709 com.google.android.gms broadcastIntent}}
10-11 13:48:05.246  3701  4916 D SecContentProvider: called from android.uid.bluetooth:1002
10-11 13:48:05.246  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
10-11 13:48:05.246  4057  4057 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
10-11 13:48:05.247  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
,10-11 13:48:05.247  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.249  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
10-11 13:48:05.249  4057  4057 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
10-11 13:48:05.249  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.249  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.249  3701  3729 D SecContentProvider: insert(), uri = 2
10-11 13:48:05.250  3701  3729 D SecContentProvider: called from android.uid.bluetooth:1002
10-11 13:48:05.250  4057  4174 E bt_btif : BTM_SetConnectability
10-11 13:48:05.250  4057  4172 I BluetoothAdapterState: Entering PendingCommandState
10-11 13:48:05.254  4057  4174 I bt_core_module: module_shut_down Shutting down module "btif_config_module"
10-11 13:48:05.255  4057  4636 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,10-11 13:48:05.256  4057  4179 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
10-11 13:48:05.256  4057  4179 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:05.260  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:48:05.262  3701  4887 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{2b2cd0e: PendingIntentRecord{76fc32f com.google.android.gms broadcastIntent}}
10-11 13:48:05.264  9211  9211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-11 13:48:05.266  4057  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_ON
10-11 13:48:05.267  4057  4179 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:05.271  4057  4172 I BluetoothAdapterState: Deferring USER_TURN_ON request...
10-11 13:48:05.274  4057  4174 I bt_core_module: module_shut_down Shutdown of module "btif_config_module" completed
,10-11 13:48:05.281  9211  9211 D DockEventReceiver: finishStartingService: stopping service
,10-11 13:48:05.285  9211  9211 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:05.285  9211  9211 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,10-11 13:48:05.391  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-11 13:48:05.396  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-11 13:48:05.396  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-11 13:48:05.457  4057  4179 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
,10-11 13:48:05.458  4057  4179 I bt_core_module: module_shut_down Shutting down module "hci_module"
10-11 13:48:05.458  4057  4179 I bt_hci  : shut_down
,10-11 13:48:05.523  4057  4586 D bt_hwcfg: hw_epilog_process
10-11 13:48:05.534  4057  4586 I bt_vendor: low_power_mode_cb
,10-11 13:48:05.541  4057  4586 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-11 13:48:05.541  4057  4586 I bt_vendor: epilog_cb
10-11 13:48:05.541  4057  4586 I bt_hci  : epilog_finished_callback
10-11 13:48:05.544  4057  4586 W bt_osi_thread: run_thread: thread id 4586, thread name hci_thread exited
10-11 13:48:05.545  4057  4179 I bt_hci_h4: hal_close
10-11 13:48:05.546  4057  4598 W bt_osi_thread: run_thread: thread id 4598, thread name hci_single_chann exited
10-11 13:48:05.546  4057  4179 I bt_userial_vendor: device fd = 96 close
10-11 13:48:05.547  4057  4179 I bt_upio : upio_set_bluetooth_power(on: 0)
10-11 13:48:05.549  5202  6781 I Authzen : [PermitStore] Getting all permits...
10-11 13:48:05.551  4057  4179 I bt_core_module: module_shut_down Shutdown of module "hci_module" completed
10-11 13:48:05.551  4057  4179 I bt_core_module: module_shut_down Shutting down module "btsnoop_module"
10-11 13:48:05.551  4057  4179 I bt_core_module: module_shut_down Shutdown of module "btsnoop_module" completed
10-11 13:48:05.552  4057  4179 I bt_core_module: module_clean_up Cleaning up module "bte_logmsg_module"
10-11 13:48:05.552  4057  4179 I bt_core_module: module_clean_up Cleanup of module "bte_logmsg_module" completed
10-11 13:48:05.552  4057  4636 W bt_osi_thread: run_thread: thread id 4636, thread name bt_workqueue exited
,10-11 13:48:05.554  4057  4174 I bt_core_module: module_shut_down Shutting down module "controller_module"
,10-11 13:48:05.555  4057  4174 I bt_core_module: module_shut_down Shutdown of module "controller_module" completed
10-11 13:48:05.555  4057  4179 E BluetoothAdapterState: stateChangeCallback : 0
10-11 13:48:05.555  4057  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
10-11 13:48:05.562  4057  4057 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-11 13:48:05.563  4057  4172 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-11 13:48:05.569  4057  4057 D BtGatt.GattService: Received stop request...Stopping profile...
10-11 13:48:05.569  4057  4057 D BtGatt.GattService: stop()
10-11 13:48:05.569  4057  4057 D BtGatt.GattService: cleanup binder
10-11 13:48:05.569  4057  4057 D BtGatt.AdvertiseManager: advertise clients cleared
10-11 13:48:05.569  4057  4057 D BtGatt.ScanManager: cleanup
10-11 13:48:05.570  3701  4181 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4057 / op:PendingIntent{ddf6fe6: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
,10-11 13:48:05.572  4057  4057 D BtGatt.ScanManager: cleanup handler
,10-11 13:48:05.576  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:05.576  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
10-11 13:48:05.576  4057  4057 D BtGatt.GattService: notifyProfileServiceStateChanged
10-11 13:48:05.581  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:05.581  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
10-11 13:48:05.581  4057  4057 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:05.581  4057  4057 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:05.581  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:05.581  4057  4057 V BluetoothAdapterState: isBleTurningOff()=true
10-11 13:48:05.582  4057  4172 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,10-11 13:48:05.585  4057  4172 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-11 13:48:05.585  4057  4172 D BluetoothAdapterService: Bluetooth PBAP supported is true
,10-11 13:48:05.586  4057  4172 D BluetoothAdapterService: Autoconnection is available 
10-11 13:48:05.586  4057  4172 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
,10-11 13:48:05.586  3701  3797 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-11 13:48:05.586  4057  4172 I BluetoothAdapterState: Entering OffState
10-11 13:48:05.594  4057  4057 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-11 13:48:05.594  4057  4057 W BluetoothSdpJni: Cleaning up Bluetooth SDP object
10-11 13:48:05.594  4057  4174 E BluetoothServiceJni: Callback env check fail: env: 0x0, callback: 0xdb7eb380
10-11 13:48:05.594  4057  4174 E BluetoothServiceJni: Callback: 'callback_thread_event' is not called on the correct thread
10-11 13:48:05.594  4057  4179 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:05.594  4057  4179 E bt_btif_dm: ### ASSERT : system/bt/btif/src/btif_dm.c line 2983 Callback is NULL (0) ###
10-11 13:48:05.595  4057  4179 W bt_osi_thread: run_thread: thread id 4179, thread name bt_jni_workqueue exited
10-11 13:48:05.596  3701  4927 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{95d57d4: PendingIntentRecord{f792d7d com.google.android.gms broadcastIntent}}
10-11 13:48:05.597  4057  4174 I bt_core_module: module_clean_up Cleaning up module "stack_config_module"
10-11 13:48:05.597  4057  4174 I bt_core_module: module_clean_up Cleanup of module "stack_config_module" completed
10-11 13:48:05.597  4057  4174 I bt_core_module: module_clean_up Cleaning up module "interop_module"
10-11 13:48:05.597  4057  4174 I bt_core_module: module_clean_up Cleanup of module "interop_module" completed
10-11 13:48:05.597  4057  4174 I bt_core_module: module_clean_up Cleaning up module "btif_config_module"
,10-11 13:48:05.598  4057  4172 E BluetoothAdapterState: Received message in OffState after cleanup: USER_TURN_ON
,10-11 13:48:05.604  4057  4174 I bt_core_module: module_clean_up Cleanup of module "btif_config_module" completed
,10-11 13:48:05.607  4057  4174 I bt_core_module: module_clean_up Cleaning up module "bt_utils_module"
10-11 13:48:05.607  4057  4174 I bt_core_module: module_clean_up Cleanup of module "bt_utils_module" completed
10-11 13:48:05.608  4057  4174 I bt_core_module: module_clean_up Cleaning up module "osi_module"
,10-11 13:48:05.608  4057  4178 D bt_osi_alarm: callback_dispatch Callback thread exited
10-11 13:48:05.608  4057  4178 W bt_osi_thread: run_thread: thread id 4178, thread name alarm_dispatcher exited
,10-11 13:48:05.609  4057  4177 W bt_osi_thread: run_thread: thread id 4177, thread name alarm_default_ca exited
10-11 13:48:05.609  4057  4174 I bt_core_module: module_clean_up Cleanup of module "osi_module" completed
10-11 13:48:05.609  4057  4057 I BluetoothServiceJni: cleanupNative: return from cleanup
10-11 13:48:05.609  4057  4057 D DOWNLOADABLE_DB: cleanup
,10-11 13:48:05.618  4057  4057 I art     : System.exit called, status: 0
10-11 13:48:05.618  4057  4057 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-11 13:48:05.631  4765  6852 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,10-11 13:48:05.648  3701  4181 I ActivityManager: Process com.android.bluetooth (pid 4057) has died(56,1812)
10-11 13:48:05.648  3701  4181 D ActivityManager: cleanUpApplicationRecord -- 4057
,10-11 13:48:05.651  4803  6438 D ForegroundUtils: could not check pending caller
,10-11 13:48:05.690  9789  9890 D BluetoothAdapter: enable()
,10-11 13:48:05.701  3701  4927 W ActivityManager: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-11 13:48:05.703  3701  4927 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-11 13:48:05.703  3701  4927 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-11 13:48:05.703  3701  4927 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-11 13:48:05.703  3701  4927 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-11 13:48:05.703  3701  4927 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-11 13:48:05.703  3701  4927 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-11 13:48:05.703  3701  4927 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-11 13:48:05.703  3701  4927 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-11 13:48:05.703  3701  4927 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-11 13:48:05.703  3701  4927 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-11 13:48:05.707  3701  4927 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,10-11 13:48:05.709  3701  4927 D SecContentProvider: called from com.thaliproject.thalitest
,10-11 13:48:05.718  3701  3797 D MountService: getExternalStorageMountMode : 3
10-11 13:48:05.718  3701  3797 D MountService: getExternalStorageMountMode : 3
10-11 13:48:05.718  3701  3797 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 1002, packageName : com.android.bluetooth
,10-11 13:48:05.762  9917  9917 E Zygote  : v2
10-11 13:48:05.762  9917  9917 I libpersona: KNOX_SDCARD checking this for 1002
10-11 13:48:05.762  9917  9917 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:05.764  3701  3797 I ActivityManager: Start proc 9917:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
10-11 13:48:05.764  9917  9917 E Zygote  : accessInfo : 0
,10-11 13:48:05.775  9917  9917 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:05.777  9917  9917 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.bluetooth 
,10-11 13:48:05.810  9917  9917 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:05.810  9917  9917 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:05.813  3701  4915 I ActivityManager: DSS on for com.android.bluetooth and scale is 1.0
,10-11 13:48:05.885  9917  9917 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,10-11 13:48:05.893  9917  9917 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:05.901  9917  9917 I HeadsetProvider: onCreate
,10-11 13:48:05.912  9917  9917 D BtSettings.ProfileConfig: Adding GattService
10-11 13:48:05.912  9917  9917 D BtSettings.ProfileConfig: Adding HeadsetService
,10-11 13:48:05.912  9917  9917 D BtSettings.ProfileConfig: Adding A2dpService
10-11 13:48:05.912  9917  9917 D BtSettings.ProfileConfig: Adding HidService
10-11 13:48:05.913  9917  9917 D BtSettings.ProfileConfig: Adding HealthService
10-11 13:48:05.913  9917  9917 D BtSettings.ProfileConfig: Adding PanService
10-11 13:48:05.913  9917  9917 D BtSettings.ProfileConfig: Adding BluetoothMapService
10-11 13:48:05.913  9917  9917 D BtSettings.ProfileConfig: Adding SapService
10-11 13:48:05.913  9917  9917 D BtSettings.ProfileConfig: Adding HeadsetClientService
10-11 13:48:05.913  9917  9917 D BtSettings.ProfileConfig: Adding A2dpSinkService
10-11 13:48:05.913  9917  9917 D BtSettings.ProfileConfig: Adding HidDevService
10-11 13:48:05.913  9917  9917 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,10-11 13:48:05.920  3701  4543 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.922  3701  4543 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.925  3701  4923 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.926  3701  4923 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.930  3701  4181 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.931  3701  4181 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.934  3701  4181 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.935  3701  4181 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.939  3701  4917 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.940  3701  4917 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.942  3701  4927 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.942  3701  4927 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.945  3701  4916 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.946  3701  4916 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.948  3701  4928 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.949  3701  4928 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.951  3701  4915 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.951  3701  4915 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.954  3701  3919 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.955  3701  3919 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:05.957  3701  4921 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:05.958  3701  4921 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:06.056  9917  9917 D BluetoothAdapterState: make() - Creating AdapterState
,10-11 13:48:06.058  4648  4648 D io_stats: !@   8,0 r 25904 2293876 w 5078 206604 d 643 74860 f 2043 2043 iot 11780 10835 th 474188 0 0 pt 0 inp 0 0 197.194
,10-11 13:48:06.060  9917  9930 I BluetoothAdapterState: Entering OffState
,10-11 13:48:06.063  9917  9932 W bt_osi_thread: run_thread: thread id 9932, thread name stack_manager started
,10-11 13:48:06.063  9917  9932 I bt_core_module: module_init Initializing module "osi_module"
10-11 13:48:06.063  9917  9932 I bt_core_module: module_init Initialized module "osi_module"
10-11 13:48:06.063  9917  9932 I bt_core_module: module_init Initializing module "bt_utils_module"
10-11 13:48:06.063  9917  9932 I bt_core_module: module_init Initialized module "bt_utils_module"
10-11 13:48:06.064  9917  9932 I bt_core_module: module_init Initializing module "btif_config_module"
,10-11 13:48:06.065  9917  9935 W bt_osi_thread: run_thread: thread id 9935, thread name alarm_default_ca started
,10-11 13:48:06.066  9917  9936 W bt_osi_thread: run_thread: thread id 9936, thread name alarm_dispatcher started
10-11 13:48:06.066  9917  9932 I bt_core_module: module_init Initialized module "btif_config_module"
10-11 13:48:06.066  9917  9932 I bt_core_module: module_init Initializing module "interop_module"
10-11 13:48:06.066  9917  9932 I bt_core_module: module_init Initialized module "interop_module"
10-11 13:48:06.066  9917  9932 I bt_core_module: module_init Initializing module "stack_config_module"
,10-11 13:48:06.068  9917  9932 I bt_core_module: module_init Initialized module "stack_config_module"
,10-11 13:48:06.069  9917  9937 W bt_osi_thread: run_thread: thread id 9937, thread name bt_jni_workqueue started
,10-11 13:48:06.070  9917  9917 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
10-11 13:48:06.070  9917  9917 W bt_btif : btif_get_adapter_property 2
10-11 13:48:06.070  9917  9917 W bt_btif : btif_get_adapter_property 1
,10-11 13:48:06.072  9917  9937 E BluetoothServiceJni: populateRssiValuesNative
,10-11 13:48:06.072  9917  9937 I bt_btif : getModelRssiValues
10-11 13:48:06.072  9917  9937 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,10-11 13:48:06.074  9917  9917 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,10-11 13:48:06.076  9917  9917 D BluetoothAdapterService: makeHashMapAvPerformance: Loading from conf
,10-11 13:48:06.091  3701  3797 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,10-11 13:48:06.096  9917  9930 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,10-11 13:48:06.099  9917  9929 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-11 13:48:06.099  9917  9929 D AdapterProvider: query
,10-11 13:48:06.109  9917  9930 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-11 13:48:06.109  9917  9930 D BluetoothAdapterService: Bluetooth PBAP supported is true
10-11 13:48:06.110  3701  3797 D BluetoothManagerService: Ble Turning On/Off, G state: 0, S state: 0
,10-11 13:48:06.113  9917  9930 D BluetoothAdapterService: Autoconnection is available 
10-11 13:48:06.113  9917  9929 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@5268de5
10-11 13:48:06.113  9917  9930 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
,10-11 13:48:06.115  9917  9929 D BluetoothAdapterService: updateEvent - already set, update
,10-11 13:48:06.115  9917  9930 D BluetoothAdapterState: Set Downloadbale DB
10-11 13:48:06.115  9917  9930 D DOWNLOADABLE_DB: initBluetoothDatabase
,10-11 13:48:06.116  9917  9929 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:48:06.116  9917  9929 D AdapterProvider: update
10-11 13:48:06.117  9917  9930 D DOWNLOADABLE_DB: initBroadcastReceiver
,10-11 13:48:06.121  9917  9929 E BluetoothAdapterService: updateEvent - update success 1
10-11 13:48:06.121  9917  9930 D DOWNLOADABLE_DB: cleanupLooper
10-11 13:48:06.121  9917  9930 D DOWNLOADABLE_DB: quit init handler
,10-11 13:48:06.142  9917  9930 D DOWNLOADABLE_DB: verifyPolicyVersion
,10-11 13:48:06.146  3701  3915 D MountService: getExternalStorageMountMode : 1
10-11 13:48:06.146  3701  3915 D MountService: getExternalStorageMountMode : 3
10-11 13:48:06.146  3701  3915 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10135, packageName : com.samsung.android.sm.policy
,10-11 13:48:06.171  9940  9940 E Zygote  : v2
10-11 13:48:06.171  9940  9940 I libpersona: KNOX_SDCARD checking this for 10135
10-11 13:48:06.171  9940  9940 I libpersona: KNOX_SDCARD not a persona
,10-11 13:48:06.173  9940  9940 E Zygote  : accessInfo : 0
,10-11 13:48:06.177  3701  3915 I ActivityManager: Start proc 9940:com.samsung.android.sm.policy/u0a135 for content provider com.samsung.android.sm.policy/.db.PolicyClientProvider
,10-11 13:48:06.183  9940  9940 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:06.185  9940  9940 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,10-11 13:48:06.215  9789  9890 D BluetoothAdapter: enable()
,10-11 13:48:06.226  9917  9928 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-11 13:48:06.227  9917  9928 D AdapterProvider: query
,10-11 13:48:06.231  9940  9940 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-11 13:48:06.233  9940  9940 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:06.238  3701  4181 I ActivityManager: DSS on for com.samsung.android.sm.policy and scale is 1.0
,10-11 13:48:06.245  9917  9928 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@fd86774
,10-11 13:48:06.247  9917  9928 D BluetoothAdapterService: updateEvent - already set, update
,10-11 13:48:06.247  9917  9928 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:48:06.248  9917  9928 D AdapterProvider: update
,10-11 13:48:06.252  9917  9928 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:06.260  3701  4915 W ActivityManager: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-11 13:48:06.261  3701  4915 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-11 13:48:06.261  3701  4915 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-11 13:48:06.261  3701  4915 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-11 13:48:06.261  3701  4915 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-11 13:48:06.261  3701  4915 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-11 13:48:06.261  3701  4915 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-11 13:48:06.261  3701  4915 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-11 13:48:06.261  3701  4915 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-11 13:48:06.261  3701  4915 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-11 13:48:06.261  3701  4915 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-11 13:48:06.263  3701  4915 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,10-11 13:48:06.264  3701  4915 D SecContentProvider: called from com.thaliproject.thalitest
,10-11 13:48:06.280  9940  9940 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient_N/lib/arm64
,10-11 13:48:06.300  9940  9940 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:06.343  9917  9930 D DOWNLOADABLE_DB: Local DB version is = 20160428 SCPM Client DB version is= 20160428
10-11 13:48:06.343  9917  9930 D DOWNLOADABLE_DB: latest polices have already been updated for BT_HFP
,10-11 13:48:06.359  9917  9930 D DOWNLOADABLE_DB: verifyPolicyVersion
,10-11 13:48:06.381  9917  9930 D DOWNLOADABLE_DB: Local DB version is = 20160617 SCPM Client DB version is= 20160617
,10-11 13:48:06.381  9917  9930 D DOWNLOADABLE_DB: latest polices have already been updated for BT_BLE
,10-11 13:48:06.399  9917  9930 D DOWNLOADABLE_DB: verifyPolicyVersion
,10-11 13:48:06.425  9917  9930 D DOWNLOADABLE_DB: Local DB version is = 201612050001 SCPM Client DB version is= 201612050001
10-11 13:48:06.425  9917  9930 D DOWNLOADABLE_DB: latest polices have already been updated for BT_A2DP
,10-11 13:48:06.440  9917  9930 D BluetoothSecureManager: getInstant: null
10-11 13:48:06.440  9917  9930 D BluetoothSecureManager: calling getMethod for getService
,10-11 13:48:06.441  9917  9930 D BluetoothSecureManager: calling getService
,10-11 13:48:06.443  9917  9930 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1424d12
,10-11 13:48:06.446  3701  4887 D BluetoothSecureManagerService: isSecureModeEnabled
10-11 13:48:06.446  3701  4887 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,10-11 13:48:06.447  9917  9930 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:48:06.447  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,10-11 13:48:06.449  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,10-11 13:48:06.449  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,10-11 13:48:06.451  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
10-11 13:48:06.451  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,10-11 13:48:06.453  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
10-11 13:48:06.453  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,10-11 13:48:06.455  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,10-11 13:48:06.455  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,10-11 13:48:06.457  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
10-11 13:48:06.457  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,10-11 13:48:06.459  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
10-11 13:48:06.459  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,10-11 13:48:06.460  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,10-11 13:48:06.461  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,10-11 13:48:06.462  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
,10-11 13:48:06.462  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
10-11 13:48:06.464  9917  9930 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
10-11 13:48:06.465  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,10-11 13:48:06.467  9917  9930 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
10-11 13:48:06.467  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,10-11 13:48:06.468  9917  9930 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidDevService
,10-11 13:48:06.469  9917  9930 D BluetoothBondStateMachine: make
,10-11 13:48:06.472  9917  9953 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-11 13:48:06.482  9917  9930 I BluetoothAdapterState: Entering PendingCommandState
,10-11 13:48:06.484  9917  9917 I BtGatt.JNI: classInitNative(L979): classInitNative: Success!
,10-11 13:48:06.493  9917  9917 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-11 13:48:06.494  9917  9917 D BtGatt.GattService: Received start request. Starting profile...
10-11 13:48:06.494  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:06.495  9917  9917 D BtGatt.GattService: start()
,10-11 13:48:06.496  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:06.497  9917  9917 D BtGatt.AdvertiseManager: advertise manager created
10-11 13:48:06.497  9917  9917 D BtGatt.AdvertiseManager: start
,10-11 13:48:06.504  9917  9917 D BtGatt.ScanManager: start
,10-11 13:48:06.529  9917  9917 D BtGatt.GattService: setGattService(): set to: com.android.bluetooth.gatt.GattService@eafba55
10-11 13:48:06.529  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:06.529  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:06.529  9917  9917 D BtGatt.GattService: refreshAbusiveScanPackages
,10-11 13:48:06.530  9917  9917 D DOWNLOADABLE_DB: getAbuseScanPackages
,10-11 13:48:06.540  9917  9917 D BtGatt.GattService: refreshAbusiveScanValue()
,10-11 13:48:06.541  9917  9917 D DOWNLOADABLE_DB: getAbuseMaxScanCount
,10-11 13:48:06.550  9917  9917 D DOWNLOADABLE_DB: getAbuseAccumulatedScanTime
,10-11 13:48:06.560  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
,10-11 13:48:06.560  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
10-11 13:48:06.560  9917  9917 D BtGatt.GattService: notifyProfileServiceStateChanged
10-11 13:48:06.561  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:06.561  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
10-11 13:48:06.561  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:06.561  9917  9917 V BluetoothAdapterState: isTurningOn()=false
10-11 13:48:06.561  9917  9917 V BluetoothAdapterState: isBleTurningOn()=true
10-11 13:48:06.562  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
,10-11 13:48:06.563  9917  9930 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,10-11 13:48:06.575  9917  9932 I bt_core_module: module_start_up Starting module "btif_config_module"
10-11 13:48:06.575  9917  9932 I bt_core_module: module_start_up Started module "btif_config_module"
,10-11 13:48:06.575  9917  9932 I bt_core_module: module_start_up Starting module "btsnoop_module"
10-11 13:48:06.575  9917  9932 I bt_core_module: module_start_up Started module "btsnoop_module"
10-11 13:48:06.575  9917  9932 I bt_core_module: module_start_up Starting module "hci_module"
10-11 13:48:06.575  9917  9932 I bt_hci  : start_up
10-11 13:48:06.575  9917  9937 W bt_btif : btif_dm_generic_evt: event=33035
,10-11 13:48:06.576  9917  9967 W bt_osi_thread: run_thread: thread id 9967, thread name hci_thread started
,10-11 13:48:06.590  9917  9932 I bt_vendor: alloc value 0xdd511d35
10-11 13:48:06.590  9917  9932 I bt_vendor: init
10-11 13:48:06.590  9917  9932 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-11 13:48:06.590  9917  9932 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
10-11 13:48:06.590  9917  9932 I bt_upio : upio_set_bluetooth_power(on: 0)
,10-11 13:48:06.591  9917  9932 I bt_upio : upio_set_bluetooth_power(on: 1)
,10-11 13:48:06.694  9917  9932 D bt_hci  : start_up starting async portion
,10-11 13:48:06.695  9917  9967 I bt_hci  : event_finish_startup
10-11 13:48:06.695  9917  9967 I bt_hci_h4: hal_open
10-11 13:48:06.695  9917  9967 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,10-11 13:48:06.697  9917  9967 I bt_userial_vendor: userial_vendor_open():UART is setup
10-11 13:48:06.697  9917  9967 I bt_userial_vendor: device fd = 95 open
,10-11 13:48:06.697  9917  9970 W bt_osi_thread: run_thread: thread id 9970, thread name hci_single_chann started
10-11 13:48:06.698  9917  9967 E bt_hwcfg: Start CFG HW, HCI reset
,10-11 13:48:06.707  9917  9967 E bt_hwcfg: Read Local Name after HCI reset
,10-11 13:48:06.732  9917  9967 D bt_hwcfg: Chipset BCM4359C0
10-11 13:48:06.732  9917  9967 D bt_hwcfg: Target name = [BCM4359C0]
10-11 13:48:06.733  9917  9967 I bt_hwcfg: module_type[semco_b90s_c0].
,10-11 13:48:06.734  9917  9967 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
10-11 13:48:06.734  9917  9967 E bt_hwcfg: ORG patchram base 0092
10-11 13:48:06.734  9917  9967 E bt_hwcfg: ORG patchram minor 0143
10-11 13:48:06.734  9917  9967 E bt_hwcfg: fw ver (org)92.143
10-11 13:48:06.734  9917  9967 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
,10-11 13:48:06.757  9917  9967 I bt_hwcfg: Axi patch failure or not include AXI patching
,10-11 13:48:06.761  9917  9967 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,10-11 13:48:06.769  9789  9890 D BluetoothAdapter: enable()
,10-11 13:48:06.775  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:06.775  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
10-11 13:48:06.776  9917  9929 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-11 13:48:06.776  9917  9929 D AdapterProvider: query
,10-11 13:48:06.784  9917  9929 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@66e536
,10-11 13:48:06.785  9917  9929 D BluetoothAdapterService: updateEvent - already set, update
10-11 13:48:06.786  9917  9929 W BluetoothAdapterService: updateEvent - alreadySet is true
,10-11 13:48:06.786  9917  9929 D AdapterProvider: update
,10-11 13:48:06.790  9917  9929 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:06.796  3701  4541 W ActivityManager: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-11 13:48:06.797  3701  4541 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-11 13:48:06.797  3701  4541 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-11 13:48:06.797  3701  4541 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-11 13:48:06.797  3701  4541 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-11 13:48:06.797  3701  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-11 13:48:06.797  3701  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-11 13:48:06.797  3701  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-11 13:48:06.797  3701  4541 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-11 13:48:06.797  3701  4541 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-11 13:48:06.798  3701  4541 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
10-11 13:48:06.799  3701  4541 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
10-11 13:48:06.800  3701  4541 D SecContentProvider: called from com.thaliproject.thalitest
,10-11 13:48:07.305  9789  9890 D BluetoothAdapter: enable()
,10-11 13:48:07.317  9917  9929 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,10-11 13:48:07.318  9917  9929 D AdapterProvider: query
,10-11 13:48:07.333  9917  9967 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-11 13:48:07.334  9917  9967 I bt_hwcfg: FW Download delta = 626975
10-11 13:48:07.334  9917  9967 D bt_hwcfg: Settlement delay -- 100 ms
10-11 13:48:07.334  9917  9967 I bt_hwcfg: Setting fw settlement delay to 100 
,10-11 13:48:07.339  9917  9929 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@b75df0d
,10-11 13:48:07.344  9917  9929 D BluetoothAdapterService: updateEvent - already set, update
10-11 13:48:07.345  9917  9929 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:48:07.345  9917  9929 D AdapterProvider: update
,10-11 13:48:07.350  9917  9929 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:07.358  3701  4917 W ActivityManager: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-11 13:48:07.359  3701  4917 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-11 13:48:07.359  3701  4917 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-11 13:48:07.359  3701  4917 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-11 13:48:07.359  3701  4917 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-11 13:48:07.359  3701  4917 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-11 13:48:07.359  3701  4917 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-11 13:48:07.359  3701  4917 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-11 13:48:07.359  3701  4917 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-11 13:48:07.359  3701  4917 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-11 13:48:07.360  3701  4917 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-11 13:48:07.362  3701  4917 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
10-11 13:48:07.363  3701  4917 D SecContentProvider: called from com.thaliproject.thalitest
,10-11 13:48:07.461  9917  9967 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,10-11 13:48:07.565  9917  9967 I bt_hwcfg: vendor lib fwcfg completed
10-11 13:48:07.565  9917  9967 I bt_vendor: firmware callback
10-11 13:48:07.565  9917  9967 I bt_hci  : firmware_config_callback
10-11 13:48:07.566  9917  9932 I bt_core_module: module_start_up Started module "hci_module"
,10-11 13:48:07.567  9917  9971 W bt_osi_thread: run_thread: thread id 9971, thread name bt_workqueue started
,10-11 13:48:07.575  9917  9971 I bt_core_module: module_init Initializing module "bte_logmsg_module"
10-11 13:48:07.575  9917  9971 I bt_core_module: module_init Initialized module "bte_logmsg_module"
10-11 13:48:07.576  9917  9937 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,10-11 13:48:07.584  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9917
10-11 13:48:07.585  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
10-11 13:48:07.586  9917  9937 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,10-11 13:48:07.586  9917  9937 W bt_btif : get_secure_storage_key - ss_is_supported = 1
10-11 13:48:07.586  9917  9937 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
10-11 13:48:07.586  9917  9937 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:07.588  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,10-11 13:48:07.591  9917  9937 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
10-11 13:48:07.592  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9917
10-11 13:48:07.593  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,10-11 13:48:07.742  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-11 13:48:07.742  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-11 13:48:07.742  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-11 13:48:07.748  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 5ms lastUpdatedAfter : 60062 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-11 13:48:07.838  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,10-11 13:48:07.840  9917  9937 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,10-11 13:48:07.841  9917  9972 W bt_osi_thread: run_thread: thread id 9972, thread name module_wrapper started
,10-11 13:48:07.842  9917  9972 I bt_core_module: module_start_up Starting module "controller_module"
,10-11 13:48:07.869  9789  9890 D BluetoothAdapter: enable()
,10-11 13:48:07.875  9917  9929 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-11 13:48:07.875  9917  9929 D AdapterProvider: query
,10-11 13:48:07.884  9917  9929 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@a816810
,10-11 13:48:07.886  9917  9929 D BluetoothAdapterService: updateEvent - already set, update
,10-11 13:48:07.886  9917  9929 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:48:07.887  9917  9929 D AdapterProvider: update
,10-11 13:48:07.891  9917  9929 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:07.899  3701  4542 W ActivityManager: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-11 13:48:07.900  3701  4542 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-11 13:48:07.900  3701  4542 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-11 13:48:07.900  3701  4542 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-11 13:48:07.900  3701  4542 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-11 13:48:07.900  3701  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-11 13:48:07.900  3701  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-11 13:48:07.900  3701  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-11 13:48:07.900  3701  4542 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-11 13:48:07.900  3701  4542 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-11 13:48:07.900  3701  4542 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-11 13:48:07.901  3701  4542 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,10-11 13:48:07.902  3701  4542 D SecContentProvider: called from com.thaliproject.thalitest
,10-11 13:48:07.929  9917  9972 I bt_core_module: module_start_up Started module "controller_module"
,10-11 13:48:07.929  9917  9972 W bt_osi_thread: run_thread: thread id 9972, thread name module_wrapper exited
,10-11 13:48:07.946  9917  9937 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,10-11 13:48:07.953  9917  9937 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
,10-11 13:48:07.953  9917  9937 W bt_btif : btif_dm_generic_evt: event=33035
,10-11 13:48:07.956  9917  9937 D bt_hci  : do_postload posting postload work item
10-11 13:48:07.956  9917  9967 I bt_hci  : event_postload
10-11 13:48:07.956  9917  9937 E bt_btif_sock: btif_sock_init: !vhci_init
10-11 13:48:07.956  9917  9967 D bt_hwcfg: hw_sco_config
10-11 13:48:07.956  9917  9937 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:227 ##
10-11 13:48:07.956  9917  9967 I bt_hwcfg: I2SPCM config {0x1, 0x0, 0x0, 0x1}
10-11 13:48:07.956  9917  9967 I bt_vendor: sco_config_cb
10-11 13:48:07.956  9917  9967 I bt_hci  : sco_config_callback postload finished.
,10-11 13:48:07.961  9917  9937 I         : iop_db_open: iop_db_open status 0
,10-11 13:48:07.961  9917  9937 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
,10-11 13:48:07.961  9917  9937 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
10-11 13:48:07.961  9917  9937 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
,10-11 13:48:07.961  9917  9937 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Grace SWB-B90S eLNA-0092
10-11 13:48:07.962  9917  9937 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0092.0143_semco.hcd
10-11 13:48:07.962  9917  9937 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
10-11 13:48:07.962  9917  9937 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true
10-11 13:48:07.962  9917  9937 E BluetoothAdapterState: stateChangeCallback : 1
10-11 13:48:07.963  9917  9930 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,10-11 13:48:07.967  9917  9930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:07.967  9917  9930 D DOWNLOADABLE_DB: refreshDbFile
10-11 13:48:07.967  9917  9930 D BluetoothServiceJni: refreshDownloadableDbFileNative:
10-11 13:48:07.967  9917  9930 I bt_btif : refreshDownloadableDbFile
,10-11 13:48:07.969  9917  9967 I bt_hwcfg: SCO PCM configure {0x0, 0x1, 0x0, 0x0, 0x0}
10-11 13:48:07.971  9917  9967 I bt_vendor: low_power_mode_cb
10-11 13:48:07.973  9917  9930 I         : iop_db_open: iop_db_open status 0
10-11 13:48:07.973  9917  9930 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-11 13:48:07.973  9917  9930 D BluetoothAdapterService: Bluetooth PBAP supported is true
,10-11 13:48:07.979  9917  9930 D BluetoothAdapterService: Autoconnection is available 
10-11 13:48:07.979  9917  9930 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
10-11 13:48:07.979  9917  9930 I BluetoothAdapterState: Entering BleOnState
,10-11 13:48:07.986  3701  3797 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-11 13:48:07.988  3701  3797 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
10-11 13:48:07.989  3701  3797 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:07.991  9917  9938 E BluetoothBondStateMachine: initStateMachine
10-11 13:48:07.991  9917  9930 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,10-11 13:48:07.994  9917  9930 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-11 13:48:07.994  9917  9930 D BluetoothAdapterService: Bluetooth PBAP supported is true
,10-11 13:48:07.996  9917  9930 D BluetoothAdapterService: Autoconnection is available 
10-11 13:48:07.996  9917  9930 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
10-11 13:48:07.996  3701  3797 D BluetoothManagerService: Turning On/Off, G state: 0, S state: 0, mBLE count: 0, s BLE count: 0
,10-11 13:48:07.998  9917  9930 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
10-11 13:48:07.998  9917  9930 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
10-11 13:48:07.999  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,10-11 13:48:08.002  4070  4293 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,10-11 13:48:08.003  4070  4293 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
10-11 13:48:08.005  3701  3701 D BluetoothPhoneService: Bluetooth Adapter state : 11
10-11 13:48:08.010  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
10-11 13:48:08.010  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:08.010  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,10-11 13:48:08.014  9211  9211 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:08.014  9211  9211 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,10-11 13:48:08.021  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:08.034  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
10-11 13:48:08.036  9917  9917 D HeadsetService: Received start request. Starting profile...
10-11 13:48:08.036  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
,10-11 13:48:08.041  3701  4541 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{33f2e5d: PendingIntentRecord{af543d2 com.google.android.gms broadcastIntent}}
,10-11 13:48:08.055  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
10-11 13:48:08.062  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
10-11 13:48:08.066  9917  9917 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
,10-11 13:48:08.072  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,10-11 13:48:08.077  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,10-11 13:48:08.078  9917  9917 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-11 13:48:08.079  9917  9917 D HeadsetStateMachine: make
,10-11 13:48:08.080  9917  9917 E HeadsetStateMachine: # of Max HF connection is 3
,10-11 13:48:08.083  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,10-11 13:48:08.092  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,10-11 13:48:08.092  9917  9930 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,10-11 13:48:08.093  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
10-11 13:48:08.093  9917  9930 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
10-11 13:48:08.093  9917  9930 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
10-11 13:48:08.101  9917  9930 I BluetoothAdapterState: Entering PendingCommandState
,10-11 13:48:08.110  9917  9917 I DualScoManager: Instantiating Dual Sco Manager
10-11 13:48:08.110  9917  9917 I DualScoManager: Set HeadsetServiceHelper
10-11 13:48:08.110  9917  9917 I DualScoManager: setNotificationManager
10-11 13:48:08.110  9917  9917 I DualScoManager: setAudioManager
,10-11 13:48:08.111  9917  9917 D BluetoothAtMessage: createCMTIContentObservers
,10-11 13:48:08.120  9917  9917 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@e06f540
,10-11 13:48:08.122  9917  9917 I HeadsetService: getHeadsetDB(true) - 44:78:3E:94:4A:XX, 300, 1
10-11 13:48:08.122  9917  9917 I DualScoManager: setSystemAudioInbandSupported : true
,10-11 13:48:08.123  9917  9917 I HeadsetStateMachine: isAutoAppInstalled : false
10-11 13:48:08.123  9917  9917 I HeadsetStateMachine: IBR : true (SysA : 1 / DB : 1)
,10-11 13:48:08.126  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
,10-11 13:48:08.127  9917  9917 D DOWNLOADABLE_DB: getNotAllowedVoiceRecognitionDeviceList
,10-11 13:48:08.134  9917  9974 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,10-11 13:48:08.136  9917  9967 I bt_hwcfg: SCO PCM data format {0x0, 0x0, 0x3, 0x0, 0x0}
,10-11 13:48:08.139  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.139  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
10-11 13:48:08.139  9917  9917 D HeadsetService: notifyProfileServiceStateChanged
,10-11 13:48:08.139  9917  9967 I bt_hwcfg: sco I2S/PCM config result 0 [0-Success, 1-Fail]
10-11 13:48:08.140  9917  9967 I bt_vendor: sco_audiostate_cb(status: 0)
10-11 13:48:08.140  9917  9974 D HeadsetStateMachine: Clear mHeadsetBrsf
10-11 13:48:08.140  9917  9974 D HeadsetStateMachine: map size, before remove : 0
,10-11 13:48:08.141  9917  9974 D HeadsetStateMachine: map size, after remove: 0
10-11 13:48:08.141  9917  9974 D HeadsetStateMachine: connectNextConnectingDevice(false) : null
,10-11 13:48:08.143  9917  9917 D A2dpService: Received start request. Starting profile...
10-11 13:48:08.143  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
,10-11 13:48:08.144  9917  9917 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-11 13:48:08.146  9211  9211 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:08.147  9211  9211 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,10-11 13:48:08.158  9917  9917 I Avrcp   : No of Audio players :: 1
10-11 13:48:08.158  9917  9917 I Avrcp   : App Package name is GM
,10-11 13:48:08.174  9917  9917 V Avrcp   : MediaPlayerInfo: mPlayerId=1
10-11 13:48:08.177  9917  9917 I Avrcp   : No of Video players :: 2
10-11 13:48:08.177  9917  9917 I Avrcp   : Video App Package name is VP
,10-11 13:48:08.185  9917  9917 V Avrcp   : MediaPlayerInfo: mPlayerId=2
10-11 13:48:08.185  9917  9917 I Avrcp   : Video App Package name is others
,10-11 13:48:08.194  9917  9917 V Avrcp   : MediaPlayerInfo: mPlayerId=3
10-11 13:48:08.194  9917  9917 I Avrcp   : Add tempPlayer
10-11 13:48:08.194  9917  9917 V Avrcp   : MediaPlayerInfo: mPlayerId=4
10-11 13:48:08.194  9917  9917 V Avrcp   : no_of_players : 4
10-11 13:48:08.194  9917  9917 I Avrcp   : Total no of players: 4
10-11 13:48:08.194  9917  9917 V Avrcp   : Samsung player is the 1st player
,10-11 13:48:08.195  9917  9917 D Avrcp   : Compose Browsing Service Candidate
,10-11 13:48:08.196  9917  9917 D Avrcp   : ResolveInfo info ResolveInfo{73c67ca com.android.bluetooth/.a2dpsink.mbs.A2dpMediaBrowserService m=0x108000}
10-11 13:48:08.197  9917  9917 D Avrcp   : ResolveInfo info ResolveInfo{c93ed3b com.google.android.music/.browse.MediaBrowserService m=0x108000}
10-11 13:48:08.197  9917  9917 D Avrcp   : Initialize Media Controller
,10-11 13:48:08.198  9917  9917 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,10-11 13:48:08.359  9917  9917 E Avrcp   : getActiveSessions
10-11 13:48:08.359  9917  9917 D Avrcp   : pick active media Controller
10-11 13:48:08.359  9917  9917 D Avrcp   : Get the active Media Controller 
,10-11 13:48:08.362  9917  9917 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-11 13:48:08.363  9917  9917 D A2dpStateMachine: make
,10-11 13:48:08.374  9917  9984 W bt_osi_thread: run_thread: thread id 9984, thread name media_worker started
10-11 13:48:08.374  9917  9917 E bt_btif : warning : media task started media_task_refcnt 1 
10-11 13:48:08.375  9917  9917 W bt_btif : btif_ar_init
10-11 13:48:08.375  9917  9937 W bt_btif : av start inhibit off
,10-11 13:48:08.382  9917  9917 E A2dpStateMachine: isDualPlayEnabled : Dual Play not supported
10-11 13:48:08.383  9917  9983 D A2dpStateMachine: Enter Disconnected: -2
,10-11 13:48:08.387  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
,10-11 13:48:08.387  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
10-11 13:48:08.387  9917  9917 D A2dpService: notifyProfileServiceStateChanged
,10-11 13:48:08.389  9917  9917 I BluetoothHidServiceJni: classInitNative: succeeds
,10-11 13:48:08.394  9917  9917 D HidService: Received start request. Starting profile...
10-11 13:48:08.395  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.395  9917  9917 D HidService: setHidService(): set to: null
10-11 13:48:08.395  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.395  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
10-11 13:48:08.395  9917  9917 D HidService: notifyProfileServiceStateChanged
,10-11 13:48:08.397  9917  9917 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-11 13:48:08.403  9917  9917 D HealthService: Received start request. Starting profile...
,10-11 13:48:08.404  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.406  9789  9890 D BluetoothAdapter: enable()
10-11 13:48:08.407  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.407  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
10-11 13:48:08.407  9917  9917 D HealthService: notifyProfileServiceStateChanged
10-11 13:48:08.408  9917  9917 I BluetoothPanServiceJni: classInitNative(L139): succeeds
,10-11 13:48:08.412  9917  9939 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-11 13:48:08.413  9917  9939 D AdapterProvider: query
10-11 13:48:08.419  9917  9917 D PanService: Received start request. Starting profile...
10-11 13:48:08.419  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.420  9917  9917 D BluetoothPanServiceJni: initializeNative(L144): pan
10-11 13:48:08.427  9917  9939 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@4b27146
10-11 13:48:08.429  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.429  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
10-11 13:48:08.429  9917  9917 D PanService: notifyProfileServiceStateChanged
10-11 13:48:08.430  9917  9939 D BluetoothAdapterService: updateEvent - already set, update
10-11 13:48:08.431  9917  9939 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:48:08.431  9917  9939 D AdapterProvider: update
,10-11 13:48:08.434  9917  9917 D BluetoothMapService: Received start request. Starting profile...
10-11 13:48:08.435  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.435  9917  9939 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:08.446  3701  4541 W ActivityManager: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-11 13:48:08.446  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.446  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
10-11 13:48:08.446  9917  9917 D BluetoothMapService: notifyProfileServiceStateChanged
,10-11 13:48:08.448  3701  4541 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-11 13:48:08.448  3701  4541 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9789, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-11 13:48:08.448  3701  4541 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-11 13:48:08.448  3701  4541 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-11 13:48:08.448  3701  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-11 13:48:08.448  3701  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-11 13:48:08.448  3701  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-11 13:48:08.448  3701  4541 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-11 13:48:08.448  3701  4541 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-11 13:48:08.448  3701  4541 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-11 13:48:08.449  3701  4541 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,10-11 13:48:08.450  3701  4541 D SecContentProvider: called from com.thaliproject.thalitest
,10-11 13:48:08.455  9917  9917 V SapService: SapBinder()
,10-11 13:48:08.459  9917  9917 D SapService: Received start request. Starting profile...
10-11 13:48:08.459  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.459  9917  9917 V SapService: start()
10-11 13:48:08.459  9917  9917 D SapService: Disable sap : false
10-11 13:48:08.462  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.462  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
10-11 13:48:08.462  9917  9917 D SapService: notifyProfileServiceStateChanged
,10-11 13:48:08.464  9917  9917 V BluetoothHidDevServiceJni: classInitNative: done
10-11 13:48:08.465  4765  6852 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,10-11 13:48:08.470  9917  9917 D HidDevService: Received start request. Starting profile...
10-11 13:48:08.470  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.470  9917  9917 D HidDevService: start()
10-11 13:48:08.470  9917  9917 V BluetoothHidDevServiceJni: initNative enter
10-11 13:48:08.471  9917  9917 V BluetoothHidDevServiceJni: initNative done
10-11 13:48:08.471  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:08.471  9917  9917 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Message sending
10-11 13:48:08.471  9917  9917 D HidDevService: notifyProfileServiceStateChanged
10-11 13:48:08.471  9917  9917 D HeadsetStateMachine: Proxy object connected
10-11 13:48:08.472  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:08.472  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
10-11 13:48:08.472  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:08.472  9917  9917 V BluetoothAdapterState: isTurningOn()=true
10-11 13:48:08.472  9917  9917 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:08.472  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:08.474  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-11 13:48:08.474  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:08.474  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
10-11 13:48:08.474  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:08.474  9917  9917 V BluetoothAdapterState: isTurningOn()=true
10-11 13:48:08.474  9917  9917 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:08.474  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:08.474  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
10-11 13:48:08.474  9917  9917 D A2dpService: A2dpService - WIFI_STATE_ENABLED
10-11 13:48:08.474  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:08.474  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
10-11 13:48:08.474  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:08.474  9917  9917 V BluetoothAdapterState: isTurningOn()=true
10-11 13:48:08.474  9917  9917 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:08.474  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:08.475  9917  9974 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-11 13:48:08.475  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:08.475  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
10-11 13:48:08.475  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:08.475  9917  9917 V BluetoothAdapterState: isTurningOn()=true
10-11 13:48:08.475  9917  9917 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:08.475  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:08.475  9917  9974 D HeadsetStateMachine: Disconnected process message: 11, size: 0
10-11 13:48:08.475  9917  9974 E HeadsetStateMachine: Unknown message: 11
10-11 13:48:08.476  9917  9917 D BluetoothUtils: readSalesCode :: sales code is XEO
10-11 13:48:08.476  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:08.476  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanServ,ice, state=12, Before synchronized
10-11 13:48:08.476  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:08.477  9917  9917 V BluetoothAdapterState: isTurningOn()=true
10-11 13:48:08.477  9917  9917 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:08.477  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:08.477  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:08.477  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
10-11 13:48:08.477  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:08.477  9917  9917 V BluetoothAdapterState: isTurningOn()=true
10-11 13:48:08.477  9917  9917 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:08.477  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:08.478  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:08.478  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
10-11 13:48:08.478  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:08.478  9917  9917 V BluetoothAdapterState: isTurningOn()=true
10-11 13:48:08.478  9917  9917 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:08.478  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
10-11 13:48:08.479  9917  9917 E BluetoothAdapterService: handleMessage() - Message: 1
10-11 13:48:08.479  9917  9917 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Before synchronized
10-11 13:48:08.479  9917  9917 V BluetoothAdapterState: isTurningOff()=false
10-11 13:48:08.479  9917  9917 V BluetoothAdapterState: isTurningOn()=true
10-11 13:48:08.479  9917  9917 V BluetoothAdapterState: isBleTurningOn()=false
10-11 13:48:08.479  9917  9917 V BluetoothAdapterState: isBleTurningOff()=false
,10-11 13:48:08.479  9917  9917 I BluetoothA2dpServiceJni: Attempting to set busy level
10-11 13:48:08.479  9917  9930 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
10-11 13:48:08.485  9917  9930 E BluetoothServiceJni: enableBrEdrNative:
10-11 13:48:08.486  9917  9930 I bt_btif : enable_bredr
10-11 13:48:08.486  9917  9937 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:08.488  9917  9937 W bt_btif : btif_dm_generic_evt: event=33035
,10-11 13:48:08.490  9917  9937 W bt_btif : IsSoftphone: 
10-11 13:48:08.490  9917  9937 E bt_btif : btif_transfer_context, is_orig 1hread is BTIF thread. Don't try context switch.
10-11 13:48:08.490  9917  9937 W bt_btif : btif_dm_generic_evt: event=33035
10-11 13:48:08.491  9917  9971 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
10-11 13:48:08.497  9917  9937 E BluetoothServiceJni: populateRssiValuesNative
10-11 13:48:08.497  9917  9937 I bt_btif : getModelRssiValues
10-11 13:48:08.497  9917  9937 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
10-11 13:48:08.499  9917  9971 D CODEC_IF_MOD: codec_open: codec_open
10-11 13:48:08.499  9917  9971 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
10-11 13:48:08.499  9917  9971 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
10-11 13:48:08.499  9917  9971 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
10-11 13:48:08.499  9917  9971 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-11 13:48:08.499  9917  9971 D CODEC_IF: codec_if_close: codec_if_close hdl -624926716
10-11 13:48:08.499  9917  9971 D CODEC_IF_MOD: codec_close: codec_close
10-11 13:48:08.499  9917  9971 D CODEC_IF_MOD: codec_close: freed apt-x encoder
10-11 13:48:08.499  9917  9971 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
10-11 13:48:08.499  9917  9971 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,10-11 13:48:08.508  9917  9971 D CODEC_IF_SSHD: codec_open: codec_open
10-11 13:48:08.508  9917  9971 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
10-11 13:48:08.508  9917  9971 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
10-11 13:48:08.508  9917  9971 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-11 13:48:08.508  9917  9971 D CODEC_IF: codec_if_close: codec_if_close hdl -992752256
10-11 13:48:08.508  9917  9971 D CODEC_IF_SSHD: codec_close: codec_close
10-11 13:48:08.508  9917  9971 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
10-11 13:48:08.509  9917  9971 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
10-11 13:48:08.509  9917  9971 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
10-11 13:48:08.512  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:08.514  9917  9937 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
10-11 13:48:08.515  9917  9937 E bt_btif : btif_handle_bluetooth_enable_evt
,10-11 13:48:08.515  9917  9937 E bt_btif : ANT+ socket does not initialize.
,10-11 13:48:08.517  9917  9990 W bt_osi_thread: run_thread: thread id 9990, thread name btif_sock started
10-11 13:48:08.518  9917  9971 D CODEC_IF_SSHD2: codec_open: codec_open
10-11 13:48:08.518  9917  9971 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
10-11 13:48:08.518  9917  9971 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
10-11 13:48:08.518  9917  9971 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-11 13:48:08.518  9917  9937 E BluetoothAdapterState: stateChangeCallback : 17
10-11 13:48:08.518  9917  9971 D CODEC_IF: codec_if_close: codec_if_close hdl -992382976
10-11 13:48:08.518  9917  9971 D CODEC_IF_SSHD2: codec_close: codec_close
10-11 13:48:08.518  9917  9971 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
10-11 13:48:08.518  9917  9937 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
10-11 13:48:08.518  9917  9971 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
10-11 13:48:08.518  9917  9930 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
10-11 13:48:08.519  9917  9937 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
10-11 13:48:08.519  9917  9937 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
10-11 13:48:08.519  9917  9937 E bt_btif : no av control block available at state:3
10-11 13:48:08.519  9917  9937 E bt_btif : no av control block available at state:3
10-11 13:48:08.519  9917  9937 E bt_btif : no av control block available at state:2
10-11 13:48:08.519  9917  9937 E bt_btif : warning : no command pending, ignore ack
10-11 13:48:08.519  9917  9937 E bt_btif : no av control block available at state:3
10-11 13:48:08.519  9917  9937 E bt_btif : no av control block available at state:2
10-11 13:48:08.519  9917  9937 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
10-11 13:48:08.519  9917  9984 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
10-11 13:48:08.519  9917  9984 E bt_btif : warning : no command pending, ignore ack
10-11 13:48:08.520  9917  9971 D CODEC_IF_MOD: codec_open: codec_open
10-11 13:48:08.520  9917  9971 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
10-11 13:48:08.520  9917  9971 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
10-11 13:48:08.520  9917  9971 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
10-11 13:48:08.520  9917  9971 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-11 13:48:08.520  9917  9971 D CODEC_IF: codec_if_close: codec_if_close hdl -624926716
10-11 13:48:08.520  9917  9971 D CODEC_IF_MOD: codec_close: codec_close
10-11 13:48:08.520  9917  9971 D CODEC_IF_MOD: codec_close: freed apt-x encoder
,10-11 13:48:08.520  9917  9971 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
10-11 13:48:08.521  9917  9971 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
10-11 13:48:08.522  9917  9930 D BluetoothAdapterProperties: ScanMode =  20
10-11 13:48:08.522  9917  9930 D BluetoothAdapterProperties: State =  11
10-11 13:48:08.522  9917  9971 D CODEC_IF_SSHD: codec_open: codec_open
10-11 13:48:08.522  9917  9971 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
,10-11 13:48:08.522  9917  9971 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
10-11 13:48:08.522  9917  9971 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-11 13:48:08.522  9917  9971 D CODEC_IF: codec_if_close: codec_if_close hdl -992752256
10-11 13:48:08.522  9917  9971 D CODEC_IF_SSHD: codec_close: codec_close
10-11 13:48:08.522  9917  9971 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
10-11 13:48:08.522  9917  9971 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
10-11 13:48:08.522  9917  9971 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
10-11 13:48:08.524  9917  9971 D CODEC_IF_SSHD2: codec_open: codec_open
10-11 13:48:08.524  9917  9971 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
10-11 13:48:08.524  9917  9971 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
10-11 13:48:08.524  9917  9971 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-11 13:48:08.524  9917  9971 D CODEC_IF: codec_if_close: codec_if_close hdl -992382976
10-11 13:48:08.524  9917  9971 D CODEC_IF_SSHD2: codec_close: codec_close
10-11 13:48:08.524  9917  9971 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
,10-11 13:48:08.525  9917  9937 E bt_btif : bta_av_co_get_peer pe, is_orig 1, psm 0x0011255
10-11 13:48:08.525  9917  9937 E bt_btif :                : sec: 0x80No active peer with this handle 0x0
10-11 13:48:08.525  9917  9937 E bt_btif : no av control block available at state:3
10-11 13:48:08.525  9917  9937 E bt_btif : no av control block available at state:3
10-11 13:48:08.525  9917  9937 E bt_btif : no av control block available at state:2
10-11 13:48:08.525  9917  9937 E bt_btif : warning : no command pending, ignore ack
10-11 13:48:08.525  9917  9937 E bt_btif : no av control block available at state:3
10-11 13:48:08.525  9917  9937 E bt_btif : no av control block available at state:2
10-11 13:48:08.525  9917  9937 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
10-11 13:48:08.525  9917  9984 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
10-11 13:48:08.525  9917  9984 E bt_btif : warning : no command pending, ignore ack
,10-11 13:48:08.528  3701  4181 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,10-11 13:48:08.529  3701  4181 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:08.530  3701  4917 D SecContentProvider: insert(), uri = 2
,10-11 13:48:08.532  3701  4917 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:08.533  9917  9930 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-11 13:48:08.533  9917  9930 D BluetoothAdapterService: [VendorCapa] prevState: 11, newState: 12
10-11 13:48:08.536  9917  9937 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
10-11 13:48:08.536  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-11 13:48:08.537  9917  9930 I bt_btif : vsc_getvendorcapabilities
10-11 13:48:08.537  9917  9930 D BluetoothAdapterService: Bluetooth PBAP supported is true
10-11 13:48:08.538  9917  9937 D BluetoothPanServiceJni: control_state_callback(L64): state:0, local_role:3, ifname:bt-pan
10-11 13:48:08.540  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:08.541  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:08.545  9789  9789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-11 13:48:08.549  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:08.551  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:08.553  9789  9789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-11 13:48:08.562  9917  9930 D BluetoothAdapterService: Autoconnection is available 
10-11 13:48:08.562  9917  9930 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
10-11 13:48:08.562  9917  9930 D BluetoothAdapterService: starting service from this receiver
10-11 13:48:08.562  3701  3797 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
10-11 13:48:08.564  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:48:08.571  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-11 13:48:08.573  9917  9937 W bt_btif : btif_dm_generic_evt: event=34050
10-11 13:48:08.573  9917  9937 D BluetoothAdapterProperties: [VendorCapa] : mDbfwSupported: 1 , mA2dpLinkFeedbackSupported: 1
10-11 13:48:08.575  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:08.582  9789  9789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
10-11 13:48:08.587  9917  9917 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
10-11 13:48:08.587  4070  4084 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
10-11 13:48:08.589  9917  9930 I BluetoothAdapterState: Entering OnState
,10-11 13:48:08.591  9789  9801 D BluetoothAdapter: onBluetoothStateChange: up=true
10-11 13:48:08.591  9789  9801 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-11 13:48:08.592  7713  7725 D BluetoothAdapter: onBluetoothStateChange: up=true
10-11 13:48:08.592  7713  7725 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-11 13:48:08.594  4070  4547 D BluetoothSap: onBluetoothStateChange: up=true
10-11 13:48:08.594  4070  4547 D BluetoothSap: Binding service...
,10-11 13:48:08.600  4803  6438 D BluetoothAdapter: onBluetoothStateChange: up=true
,10-11 13:48:08.600  4803  6438 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-11 13:48:08.602  4070  4085 D BluetoothPbap: onBluetoothStateChange: up=true
10-11 13:48:08.607  4070  4070 D A2dpProfile: Bluetooth service connected
,10-11 13:48:08.609  9917  9917 I BluetoothPbapService: Handler(): got msg=1
10-11 13:48:08.611  4070  4547 D BluetoothPan: onBluetoothStateChange on: true
,10-11 13:48:08.611  9917  9939 D A2dpStateMachine: getConnectedDevices : size=0
,10-11 13:48:08.612  9917  9992 V BluetoothPbapService: PBAP Service initSocket try: 0
10-11 13:48:08.614  4070  4070 D BluetoothSap: Proxy object connected
10-11 13:48:08.615  4070  4070 D SapProfile: Bluetooth service connected
10-11 13:48:08.618  4070  4070 D BluetoothPbap: Proxy object connected
10-11 13:48:08.618  4070  4070 D PbapServerProfile: Bluetooth service connected
10-11 13:48:08.619  9917  9992 D BluetoothSocket: bindListen(): myUserId = 0
10-11 13:48:08.620  9917  9938 D A2dpStateMachine: getConnectedDevices : size=0
10-11 13:48:08.620  9917  9992 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-11 13:48:08.621  4070  4070 D BluetoothPan: BluetoothPAN Proxy object connected
10-11 13:48:08.621  4070  4070 D PanProfile: Bluetooth service connected
10-11 13:48:08.621  9917  9992 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
10-11 13:48:08.621  4070  4547 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-11 13:48:08.629  4765  6857 D BluetoothAdapter: onBluetoothStateChange: up=true
10-11 13:48:08.629  4765  6857 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-11 13:48:08.629  4070  4070 D BluetoothInputDevice: Proxy object connected
10-11 13:48:08.629  4070  4070 D HidProfile: Bluetooth service connected
10-11 13:48:08.630  4070  4084 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,10-11 13:48:08.634  9211  9223 D BluetoothAdapter: onBluetoothStateChange: up=true
10-11 13:48:08.634  9211  9223 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-11 13:48:08.635  9917  9929 D BluetoothAdapter: onBluetoothStateChange: up=true
10-11 13:48:08.635  9917  9929 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-11 13:48:08.635  3701  3797 D BluetoothAdapter: onBluetoothStateChange: up=true
10-11 13:48:08.635  3701  3797 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-11 13:48:08.636  4070  4547 D BluetoothAdapter: onBluetoothStateChange: up=true
10-11 13:48:08.636  4070  4547 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-11 13:48:08.636  4044  9170 D BluetoothAdapter: onBluetoothStateChange: up=true
10-11 13:48:08.636  4044  9170 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-11 13:48:08.637  9211  9222 D BluetoothPan: onBluetoothStateChange on: true
,10-11 13:48:08.641  9211  9211 D BluetoothPan: BluetoothPAN Proxy object connected
10-11 13:48:08.642  9211  9211 D PanProfile: Bluetooth service connected
,10-11 13:48:08.642  4070  4389 D BluetoothMap: onBluetoothStateChange: up=true
,10-11 13:48:08.647  9211  9223 D BluetoothSap: onBluetoothStateChange: up=true
10-11 13:48:08.648  9211  9223 D BluetoothSap: Binding service...
,10-11 13:48:08.649  4070  4070 D BluetoothMap: Proxy object connected
10-11 13:48:08.649  4070  4070 D MapProfile: Bluetooth service connected
10-11 13:48:08.649  4070  4070 D BluetoothMap: getConnectedDevices()
,10-11 13:48:08.652  9211  9211 D BluetoothSap: Proxy object connected
10-11 13:48:08.652  9211  9211 D SapProfile: Bluetooth service connected
,10-11 13:48:08.656  3701  3701 D Telecom : SecBluetoothManager : register BluetoothHeadset after STATE_ON : null
10-11 13:48:08.656  3701  3701 D Telecom : SecBluetoothManager : registerBluetoothHeadsetMessageListener fail
10-11 13:48:08.656  3701  3701 D BluetoothPhoneService: Bluetooth Adapter state : 12
10-11 13:48:08.656  3701  3701 I BluetoothPhoneService: queryPhoneState
10-11 13:48:08.656  3701  3701 I BluetoothPhoneService: updateHeadsetWithCallState : true
,10-11 13:48:08.660  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,10-11 13:48:08.660  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:08.660  3701  3701 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
10-11 13:48:08.661  4070  4293 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:08.662  4070  4293 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
10-11 13:48:08.662  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-11 13:48:08.664  9917  9917 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,10-11 13:48:08.664  9917  9917 D PanService: BT STATE ON
10-11 13:48:08.665  9917  9917 D EnhancedTetheringManager: EnhancedTetheringManager()
10-11 13:48:08.665  9917  9917 D EnhancedTetheringManager: start
10-11 13:48:08.668  9211  9211 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:08.668  9211  9211 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
10-11 13:48:08.674  9917  9917 D ETMLeHelper: ETMLeHelper()
10-11 13:48:08.674  9917  9917 D ETMLeHelper: initTetherAdv
10-11 13:48:08.675  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:48:08.675  3701  4913 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{2a23a51: PendingIntentRecord{87db2b6 com.google.android.gms broadcastIntent}}
10-11 13:48:08.676  9211  9211 E BluetoothEventManager: unregisterProfileIntentReceiver :: mProfileConnectionReceiver was not registered.
10-11 13:48:08.676  9211  9211 D LocalBluetoothProfileManager: Adding local A2DP profile
10-11 13:48:08.678  9917  9917 D BluetoothAdapter: STATE_ON
,10-11 13:48:08.680  4070  4293 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
10-11 13:48:08.681  9917  9917 D BluetoothAdapter: STATE_ON
,10-11 13:48:08.681  4070  4293 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
10-11 13:48:08.681  4070  4293 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
10-11 13:48:08.681  4070  4293 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
10-11 13:48:08.681  4070  4293 W LocalBluetoothProfileManager: updateLocalProfiles :: Spp profile was created already 
10-11 13:48:08.682  9917  9917 D BluetoothAdapter: STATE_ON
,10-11 13:48:08.685  9211  9211 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
10-11 13:48:08.685  9917  9917 D BluetoothAdapter: isSecureModeEnabled
,10-11 13:48:08.685  9917  9917 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:48:08.686  9917  9917 D ETMLeHelper: initTetherScan
10-11 13:48:08.687  9917  9917 D BluetoothAdapter: STATE_ON
,10-11 13:48:08.688  9917  9917 D BluetoothAdapter: STATE_ON
,10-11 13:48:08.689  9211  9211 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-11 13:48:08.691  9917  9917 D BluetoothMapUtils: [RCS] imsConfigCscFeatures : , enableCpmFeature : false
,10-11 13:48:08.691  9917  9917 D BluetoothMapUtils: mRcsSupported : false
10-11 13:48:08.693  9211  9211 E BluetoothHeadset: BTStateChangeCB is registed
,10-11 13:48:08.695  9211  9211 D BluetoothMap: Create BluetoothMap proxy object
10-11 13:48:08.697  3701  4540 D MountService: getExternalStorageMountMode : 1
10-11 13:48:08.698  3701  4540 D MountService: getExternalStorageMountMode : 3
10-11 13:48:08.698  3701  4540 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,10-11 13:48:08.719  9995  9995 E Zygote  : v2
,10-11 13:48:08.719  9995  9995 I libpersona: KNOX_SDCARD checking this for 10049
10-11 13:48:08.719  9995  9995 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:08.719  3701  4540 I ActivityManager: Start proc 9995:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
10-11 13:48:08.720  9995  9995 E Zygote  : isSdpEnabledProcess - SDP enabled
,10-11 13:48:08.721  9995  9995 E Zygote  : accessInfo : 64
10-11 13:48:08.721  9995  9995 E Zygote  : isSdpEnabledProcess - SDP enabled
10-11 13:48:08.721  9995  9995 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,10-11 13:48:08.731  9995  9995 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:08.731  9211  9211 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,10-11 13:48:08.733  9995  9995 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,10-11 13:48:08.740  9211  9211 D LocalBluetoothProfileManager: Adding local Spp profile
,10-11 13:48:08.752  9211  9211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-11 13:48:08.763  9211  9211 D A2dpProfile: Bluetooth service connected
,10-11 13:48:08.766  9917  9938 D A2dpStateMachine: getConnectedDevices : size=0
,10-11 13:48:08.767  9211  9211 D BluetoothMap: Proxy object connected
10-11 13:48:08.768  9211  9211 D MapProfile: Bluetooth service connected
10-11 13:48:08.768  9211  9211 D BluetoothMap: getConnectedDevices()
10-11 13:48:08.769  9995  9995 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-11 13:48:08.770  9995  9995 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:08.772  9211  9211 D BluetoothPbap: Proxy object connected
10-11 13:48:08.772  3701  4543 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,10-11 13:48:08.773  9211  9211 D PbapServerProfile: Bluetooth service connected
10-11 13:48:08.773  9211  9211 D BluetoothInputDevice: Proxy object connected
10-11 13:48:08.774  9211  9211 D HidProfile: Bluetooth service connected
,10-11 13:48:08.785  9211  9211 D DockEventReceiver: finishStartingService: stopping service
,10-11 13:48:08.814  9995  9995 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
,10-11 13:48:08.833  9995  9995 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:08.851  3701  4927 D RCPManagerService: exchangeData() failure , invalid userId
,10-11 13:48:08.875  9995  9995 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
10-11 13:48:08.876  9995  9995 I QBNRClientHelper: init SyncClientHelper : Email
10-11 13:48:08.876  9995  9995 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : EMAILFOLDER, 55LAYJm0O2, com.samsung.android.email.provider.service.sCloudBNRService2
10-11 13:48:08.876  9995  9995 I QBNRClientHelper: init SyncClientHelper : EMAILFOLDER
,10-11 13:48:08.920  3701  4923 D RCPManagerService: exchangeData() failure , invalid userId
,10-11 13:48:08.924  9995 10010 D skia    : ---- fAsset->read(8192) returned 0
10-11 13:48:08.925  9995 10010 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-11 13:48:08.930  3701  4543 D MountService: getExternalStorageMountMode : 1
,10-11 13:48:08.930  9995  9995 D SamsungAnalytics:1.8.25: cf feature is supported
10-11 13:48:08.930  3701  4543 D MountService: getExternalStorageMountMode : 3
10-11 13:48:08.930  3701  4543 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,10-11 13:48:08.934  9995  9995 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
,10-11 13:48:08.938  9995 10010 D skia    : ---- fAsset->read(8192) returned 0
10-11 13:48:08.938  9995 10010 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-11 13:48:08.940  9995 10010 D skia    : ---- fAsset->read(8192) returned 0
,10-11 13:48:08.940  9995 10010 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-11 13:48:08.954 10014 10014 E Zygote  : v2
,10-11 13:48:08.954 10014 10014 I libpersona: KNOX_SDCARD checking this for 10049
10-11 13:48:08.954 10014 10014 I libpersona: KNOX_SDCARD not a persona
,10-11 13:48:08.955 10014 10014 E Zygote  : isSdpEnabledProcess - SDP enabled
10-11 13:48:08.956 10014 10014 E Zygote  : accessInfo : 64
10-11 13:48:08.956 10014 10014 E Zygote  : isSdpEnabledProcess - SDP enabled
10-11 13:48:08.956 10014 10014 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
10-11 13:48:08.956  3701  4543 I ActivityManager: Start proc 10014:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,10-11 13:48:08.962 10014 10014 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:08.963  9789  9890 D BluetoothAdapter: STATE_ON
,10-11 13:48:08.964 10014 10014 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:48:08.968  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-11 13:48:08.969  9789  9853 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,10-11 13:48:08.974  3701  4913 D WifiService: setWifiEnabled: false pid=9789, uid=10033
10-11 13:48:08.975  3701  4913 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-11 13:48:08.975  3701  4913 D WifiControlHistoryProvider: query
10-11 13:48:08.976  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:08.981  3701  4913 D WifiNative-wlan0: callSECApiVoid - ID [312]
,10-11 13:48:08.981  3701  4016 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
,10-11 13:48:08.983  3701  4913 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-11 13:48:08.985  3701  3701 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,10-11 13:48:08.986  3701  4913 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:08.986 10014 10014 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:08.986  3701  4913 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
10-11 13:48:08.987 10014 10014 D ActivityThread: Added TimaKeyStore provider
10-11 13:48:08.989  3701  4913 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-11 13:48:08.990  3701  3929 D SecContentProvider: insert(), uri = 2
10-11 13:48:08.992  3701  4543 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
10-11 13:48:08.995  3701  3929 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:08.996  3701  3929 D SecContentProvider: insert(), uri = 2
,10-11 13:48:09.000  3701  3929 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:09.001  3701  3930 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-11 13:48:09.003  3701  3930 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@bc6eb89
10-11 13:48:09.004  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135427, SetElapsed=578954, nowELAPSED=200141
10-11 13:48:09.005  3701  3930 D WifiStateMachine: isFindLocationId() - Location Id : 1
10-11 13:48:09.005  3701  3930 D WifiStateMachine: ConnectedState - exit() - stopLearning id : 1
10-11 13:48:09.005  3701  3930 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
10-11 13:48:09.006  3701  3930 D SLocation: system
10-11 13:48:09.006  3701  3930 D SLocation: stopLearning ID = 1
10-11 13:48:09.006  3701  3930 D SLocation: setLearningStatus ID = 1 / status = false
10-11 13:48:09.006  3701  3930 D SecContentProvider: insert(), uri = 2
,10-11 13:48:09.009  3701  3930 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:09.009  3701  3930 D WifiStateMachine: Wifi got Disconnected in connectedstate, Send provisioning intent mAutoRoamingfalse
10-11 13:48:09.010  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiStateMachine$ConnectedState.exit:11809 com.android.internal.util.StateMachine$SmHandler.invokeExitMethods:1009 com.android.internal.util.StateMachine$SmHandler.performTransitions:865 com.android.internal.util.StateMachine$SmHandler.handleMessage:809 
10-11 13:48:09.010  3701  3930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-11 13:48:09.012  3701  3935 D DhcpClient: doQuit
10-11 13:48:09.012  3701  3935 D ApfFilter: (wlan0): shutting down
10-11 13:48:09.014  3701  5199 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@d75b145
10-11 13:48:09.014  3701  3925 D WifiP2pService: InactiveState{ what=143375 }
10-11 13:48:09.015  3701  3925 D WifiP2pService: P2pEnabledState{ what=143375 }
10-11 13:48:09.015  3701  5199 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@d6f4dcb
10-11 13:48:09.016  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-11 13:48:09.016  3701  5199 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@bc51cc1
10-11 13:48:09.016  3701  4016 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
10-11 13:48:09.016  3701  3960 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-11 13:48:09.016  3701  3960 D ConnectivityService: ignoring duplicate network state non-change
10-11 13:48:09.016  3701  3960 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 12
10-11 13:48:09.017  3701  5199 D DhcpClient: onQuitting
10-11 13:48:09.018  3701  3960 V NetworkStats: updateIfacesLocked()
10-11 13:48:09.018  3701  3960 V NetworkStats: performPollLocked(flags=0x1)
10-11 13:48:09.018  3701  3960 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:09.019  3701  3930 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
10-11 13:48:09.019  3701  3930 I WifiConnectivityManager: Set WiFi disabled
10-11 13:48:09.019  3701  3930 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@f31347a
10-11 13:48:09.019  3701  3930 I WifiStateMachine: deinitGeofence
10-11 13:48:09.019  3701  3701 I WifiTrafficPoller: evaluateTrafficStatsPolling
10-11 13:48:09.021  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-11 13:48:09.021  3701  3701 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
,10-11 13:48:09.021  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-11 13:48:09.022  3701  3956 I WifiHs20Service: Message received 5007
,10-11 13:48:09.026  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
10-11 13:48:09.029  3701  3960 V NetworkStats: performPollLocked() took 11ms
,10-11 13:48:09.029  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-11 13:48:09.029  3701  3960 D NtpTrustedTime: currentTimeMillis() cache hit
,10-11 13:48:09.034  3701  3930 D SLocation: stopGeofence ID = 1
,10-11 13:48:09.034  3701  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,10-11 13:48:09.035  3701  3701 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,10-11 13:48:09.035 10014 10014 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
10-11 13:48:09.036  3701  3960 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
10-11 13:48:09.036  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.036  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:09.037  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:09.037  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:09.037  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:09.037  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.037  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.038  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.038  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.038  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.038  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.038  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.038  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.039  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.039  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.039  4527  4612 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [false]
,10-11 13:48:09.039  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:09.039  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:09.039  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.039  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.040  4527  4616 D PdnController: handleMessage: what 106
10-11 13:48:09.040  4527  4616 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [false]
10-11 13:48:09.040  4527  4616 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [false]
,10-11 13:48:09.041  4527  4612 D GeolocationController: WIFI : onLost
10-11 13:48:09.042  3701  4014 D DnsEventListenerService: Logging 28 results for netId 502
10-11 13:48:09.044  9917  9917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
,10-11 13:48:09.044  9917  9917 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:48:09.044  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:09.044  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:09.045  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:09.045  3701  3960 D ConnectivityService: sending notification LOST for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:09.046  4527  4616 D ResipRegiMgr: handleMessage(): 3
10-11 13:48:09.046  4527  4616 D RegiMgrBase: handleMessage: what 3
10-11 13:48:09.048  3701  5190 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:09.048  3701  5190 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: unregister CaptivePortalReceiver
10-11 13:48:09.050  3701  3960 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.050  3701  3925 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.050  3701  3925 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:09.050  3701  3925 D WIFI_P2P: evalRequest
10-11 13:48:09.050  3701  3925 D WIFI_P2P:   done
10-11 13:48:09.052  9917  9988 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
10-11 13:48:09.052  3701  3701 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.bluetooth.SecBluetoothMessageListener@7621d4a
10-11 13:48:09.052  3701  3701 D BluetoothHeadset: registerMessageListener
10-11 13:48:09.053  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:09.053  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:09.054  3701  4025 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.054  3701  4025 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
10-11 13:48:09.054  3701  4025 D Ethernet: evalRequest
10-11 13:48:09.054  3701  4025 D Ethernet:   done
10-11 13:48:09.055  4044  4044 D PhoneSwitcherNetworkRequstListener: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.055  4044  4044 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
10-11 13:48:09.055  4044  4044 D PhoneSwitcherNetworkRequstListener: evalRequest
10-11 13:48:09.055  4044  4044 D PhoneSwitcherNetworkRequstListener:   done
10-11 13:48:09.057 10014 10014 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
10-11 13:48:09.058  3701  3797 D EntConnectivity: Not allowed due to - mEnabled false
10-11 13:48:09.068  9211  9211 D HeadsetProfile: Bluetooth service connected
10-11 13:48:09.070  4070  4070 D HeadsetProfile: Bluetooth service connected
10-11 13:48:09.070  3244  3244 E audit   : type=1320 audit(1507722489.056:540): 
10-11 13:48:09.080  9917  9929 D HeadsetService: registerMessageListener
10-11 13:48:09.081  9917  9929 D HeadsetService: registerMessageListener
,10-11 13:48:09.081  9917  9988 D BluetoothSocket: bindListen(): myUserId = 0
10-11 13:48:09.082  9917  9988 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-11 13:48:09.082  9917  9974 D HeadsetStateMachine: Disconnected process message: 70, size: 0
10-11 13:48:09.082  9917  9974 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@75ebcc9
,10-11 13:48:09.082  3701  3701 I Telecom : SecBluetoothManager : register MessageListener
10-11 13:48:09.083  3244  3244 E audit   : type=1320 audit(1507722489.066:541): 
,10-11 13:48:09.084  3294  3786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-11 13:48:09.084  9211  9211 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
10-11 13:48:09.084  9211  9211 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,10-11 13:48:09.090  9917  9917 D BluetoothUtils: readSalesCode :: sales code is XEO
,10-11 13:48:09.093  3701  3930 E SLocation: pendingIntent set to null
10-11 13:48:09.093  3701  3930 D SLocation: setStatus ID = 1 / status = 0
10-11 13:48:09.093  3701  3930 D SLocation: updateSession : trigger = false
10-11 13:48:09.093  3701  3930 D SLocation: updateSession : mSessionStatus = 0
,10-11 13:48:09.094  3701  3930 D WifiStateMachine:  stopGeofence() - id : 1
10-11 13:48:09.095  3701  4487 D SLocation: Session stopped
10-11 13:48:09.095  3701  4487 D SLocation: triggerAlarm
10-11 13:48:09.095  3701  4487 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / op:PendingIntent{d8c9dd8: PendingIntentRecord{a073531 android broadcastIntent}}
10-11 13:48:09.095  3701  4487 D SLocation: All alarm stopped
,10-11 13:48:09.098  3244  3244 E audit   : type=1320 audit(1507722489.086:542): 
,10-11 13:48:09.102  9917  9988 D BluetoothSocket: bindListen(): myUserId = 0
,10-11 13:48:09.102  9917  9988 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-11 13:48:09.106  9917  9917 V BtOppService: isOwner == true
,10-11 13:48:09.109  3701  3930 D SLocation: stopGeofence ID = 2
10-11 13:48:09.109  9917  9988 D ObexServerSockets: Succeed to create listening sockets 
10-11 13:48:09.109  9917  9988 D ObexServerSockets: startAccept()
,10-11 13:48:09.111  9917  9988 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,10-11 13:48:09.112  9917 10038 D ObexServerSockets: Accepting socket connection for masId0
10-11 13:48:09.113  9917 10037 D ObexServerSockets: Accepting socket connection for masId0
10-11 13:48:09.113  9917 10035 D BluetoothSocket: bindListen(): myUserId = 0
10-11 13:48:09.114  9917 10035 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-11 13:48:09.116  9917  9988 D BluetoothSdpJni: SDP Create record success - handle: 0
10-11 13:48:09.119  3244  3244 E audit   : type=1320 audit(1507722489.106:543): 
10-11 13:48:09.119  3294  3786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-11 13:48:09.122  3701  3960 D ConnectivityService: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
10-11 13:48:09.123  3701  3960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-11 13:48:09.130  3294  3786 D CommandListener: Clearing all IP addresses on wlan0
,10-11 13:48:09.137  3701  3701 I Telecom : SecBluetoothManager : not single connected gear
10-11 13:48:09.138  3701  3797 D EntConnectivity: Not allowed due to - mEnabled false
,10-11 13:48:09.141  3701  3930 E SLocation: pendingIntent set to null
10-11 13:48:09.141  3701  3930 D SLocation: setStatus ID = 2 / status = 0
10-11 13:48:09.141  3701  3930 D SLocation: updateSession : trigger = false
10-11 13:48:09.141  3701  3930 D SLocation: updateSession : mSessionStatus = 0
10-11 13:48:09.141  3701  3930 D WifiStateMachine:  stopGeofence() - id : 2
10-11 13:48:09.141  3701  3930 D wifi    : android_net_wifi_reset_alert_handler = 0x70b01278c0
10-11 13:48:09.142  3701  3930 E WifiHAL : failed to request reset; result = -95
10-11 13:48:09.142  3701  3930 D wifi    : android_net_wifi_reset_log_handler = 0x70b01278c0
10-11 13:48:09.142  3701  3930 I WifiHAL : Failed to remove command 1: 0x0
10-11 13:48:09.142  3701  3930 D WifiHAL : Success to clear alerthandler
10-11 13:48:09.142  3701  4487 D SLocation: Session stopped
10-11 13:48:09.142  3701  4487 D SLocation: triggerAlarm
10-11 13:48:09.142  3701  4487 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / op:PendingIntent{d8c9dd8: PendingIntentRecord{a073531 android broadcastIntent}}
10-11 13:48:09.142  3701  4487 D SLocation: All alarm stopped
,10-11 13:48:09.146  9917 10035 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-11 13:48:09.147  9917 10035 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-11 13:48:09.154  3701  4181 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,10-11 13:48:09.155  3701  4181 D SecContentProvider: called from android.uid.bluetooth:1002
,10-11 13:48:09.158  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:09.158  4070  4293 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
,10-11 13:48:09.168  5202  5202 I CastMediaRouteProvider: Network connectivity changed
,10-11 13:48:09.169  3701  3921 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
10-11 13:48:09.169  5166  5166 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF50EC62EA054297E5426D68FE61E03F7CB63D06B4FC0A78A26416AA7E048F840EFBC21D921AABB61599A4C4654ABE1206043CF566A086A1148D0FC76C5AA3DFC0]}
10-11 13:48:09.169  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:09.169  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:09.169  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:09.170  3701  3921 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
10-11 13:48:09.170  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:09.170  5166  5166 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF006507037EF1FC27CFA959C112FA7F2D870458BE3926C900C8D0246DBBD82F5FF9735DB64481160EAC5657CBD115B580]}
10-11 13:48:09.171  3701  3921 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
,10-11 13:48:09.186  8060  8060 I FOTA_AGENT: [com.samsung.android.app.syncmldm.llllIIIllIlIIIIllllI(243/onReceive)] m_DataReceiver: g_nResumeStatus: 0 m_nWaitWifiConnectMode: 0
,10-11 13:48:09.188  9385  9385 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
10-11 13:48:09.188  9385  9385 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
10-11 13:48:09.192  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-11 13:48:09.196  9443  9443 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@bfcf53c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-11 13:48:09.194  4863  4863 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-11 13:48:09.197  9385  9385 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
10-11 13:48:09.201  3701  3930 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-11 13:48:09.201  3701  3930 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.201  3701  3930 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:09.201  3701  3930 D WIFI    : evalRequest
10-11 13:48:09.201  3701  3930 D WIFI    :   needNetworkFor
10-11 13:48:09.202  3701  3925 D WifiP2pService: InactiveState{ what=131204 }
10-11 13:48:09.202  3701  3930 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:09.202  3701  3930 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:09.202  3701  3930 D WIFI_UT : evalRequest
10-11 13:48:09.202  3701  3930 D WIFI_UT :   done
10-11 13:48:09.202  3701  3925 D WifiP2pService: P2pEnabledState{ what=131204 }
10-11 13:48:09.210  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:09.215  3701  3701 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
10-11 13:48:09.216  3701  4553 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
10-11 13:48:09.217  3701  4553 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-11 13:48:09.227  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-11 13:48:09.229  9385  9385 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
10-11 13:48:09.229  9385  9385 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
10-11 13:48:09.230  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:09.230  9917 10043 D BluetoothSocket: bindListen(): myUserId = 0
10-11 13:48:09.230 , 9917 10043 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-11 13:48:09.241  9443  9443 I NetworkConnectivity: Network state changed: null
10-11 13:48:09.241  4291  4291 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
10-11 13:48:09.241  4291  4291 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
10-11 13:48:09.241  9789  9789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-11 13:48:09.242  3701  3925 D WifiP2pService: sending p2p connection changed broadcast: FAILED
10-11 13:48:09.248  3701  4553 I Telecom : SecBluetoothManager : not single connected gear
10-11 13:48:09.248  3701  4553 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
10-11 13:48:09.255  8060  8060 W FOTA_AGENT: [lIIlllIlIIlllIIIIlII(74/llIIIIlllllIIllIIllI)] NetworkInfo is null
10-11 13:48:09.257  8060  8060 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1152/IIIllIIllIllIlIIlIIl)] WiFi network Connected : false
10-11 13:48:09.265  3294  3778 I Netd    : Destroyed 15 sockets on 192.168.1.102 in 1.3 ms
10-11 13:48:09.265  4765  6853 V NativeCrypto: Read error: ssl=0x70b6bd8f00: I/O error during system call, Software caused connection abort
10-11 13:48:09.268  3701  3919 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BleCentralService newState = 1 callingPackage = 10019
10-11 13:48:09.271  3701  3701 I BluetoothPhoneService: updateHeadsetWithCallState : true
10-11 13:48:09.271  9917 10043 I BtOppRfcommListener: Accept thread started.
10-11 13:48:09.276  3701  4542 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BlePeripheralService newState = 1 callingPackage = 10019
10-11 13:48:09.276  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-11 13:48:09.276  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
10-11 13:48:09.279  8060  8060 W FOTA_AGENT: [lIIlllIlIIlllIIIIlII(74/llIIIIlllllIIllIIllI)] NetworkInfo is null
10-11 13:48:09.279  9443  9443 I NetworkPolicyMonitor: Download-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
10-11 13:48:09.281  3244  3244 E audit   : type=1320 audit(1507722489.266:544): 
10-11 13:48:09.285  3701  4921 D RCPManagerService: exchangeData() failure , invalid userId
10-11 13:48:09.285  4765  6853 V NativeCrypto: SSL shutdown failed: ssl=0x70b6bd8f00: I/O error during system call, Broken pipe
10-11 13:48:09.291  3701  3798 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
,10-11 13:48:09.294 10014 10014 D SamsungAnalytics:1.8.25: cf feature is supported
10-11 13:48:09.301  3701  3919 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{eb03fee: PendingIntentRecord{ce8845d com.google.android.gms broadcastIntent}}
10-11 13:48:09.301  9917  9974 D HeadsetStateMachine: Disconnected process message: 9, size: 0
10-11 13:48:09.301  3244  3244 E audit   : type=1320 audit(1507722489.286:545): 
10-11 13:48:09.301  3701  3701 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
10-11 13:48:09.302  3701  3701 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = true
10-11 13:48:09.301  9917  9974 D A2dpSinkService: getA2dpSinkService(): service is NULL
10-11 13:48:09.302  3701  3701 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
10-11 13:48:09.302  3701  3701 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
10-11 13:48:09.302  9917  9974 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
10-11 13:48:09.302  3701  3919 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T140508, SetElapsed=1219968, nowELAPSED=200439
10-11 13:48:09.302  3701  3701 D Tethering: Tethering got CONNECTIVITY_ACTION
10-11 13:48:09.303  3701  3962 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
10-11 13:48:09.303  3701  3962 D Tethering: MasterInitialState.processMessage what=327683
10-11 13:48:09.303  3701  3925 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
10-11 13:48:09.303  3701  3916 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
10-11 13:48:09.303  3701  3916 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
10-11 13:48:09.303  4765  6853 E GCM     : Wifi connection closed with errorCode 20
10-11 13:48:09.304  3701  3701 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
10-11 13:48:09.305  3701  4487 D SLocation: checkWifiInfo
10-11 13:48:09.305  3701  3701 V MARsPolicyManager: DataConnection: false
10-11 13:48:09.305  3701  4487 W SLocation: No Active Data Connection
10-11 13:48:09.305  3701  4487 W SLocation: No Active Data Connection
10-11 13:48:09.305  3701  3701 D RttService: SCAN_AVAILABLE : 1
10-11 13:48:09.305  3701  3957 I WifiScanningService: wifi driver unloaded
10-11 13:48:09.306  3701  3957 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.scanner.SupplicantWifiScannerImpl$2@499ec8f
10-11 13:48:09.306  9443  9443 I NetworkPolicyMonitor: Stream-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
10-11 13:48:09.306  3701  3959 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:09.308  3701 10059 I ApplicationPolicy: updateDataUsageMap
10-11 13:48:09.310  3701  3798 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
10-11 13:48:09.310  3701  3798 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
,10-11 13:48:09.310  3701  3798 D WifiDisplayController: disconnect
10-11 13:48:09.310  3701  3798 D WifiDisplayAdapter: onFeatureStateChanged empty
10-11 13:48:09.310  3701  3798 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,10-11 13:48:09.320  3701  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,10-11 13:48:09.320  3275  7299 D audio_hw_primary: adev_set_parameters: enter: kvpairs: A2dpSuspended=false
10-11 13:48:09.321  9917  9974 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,10-11 13:48:09.326 10014 10046 D skia    : ---- fAsset->read(8192) returned 0
10-11 13:48:09.326 10014 10046 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-11 13:48:09.332  3701  3917 I KnoxVpnEngineService: vpn handle : Message received
10-11 13:48:09.332  3701  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
10-11 13:48:09.333  3701  3917 I KnoxVpnEngineService: vpn handle : Message received
10-11 13:48:09.333  3701  3917 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = true
,10-11 13:48:09.337  3294  3786 E Netd    : netlink response contains error (No such file or directory)
,10-11 13:48:09.338  3294  3781 D EnterpriseController: netId is 0
,10-11 13:48:09.338  3294  3781 D Netd    : getNetworkForDns: using netid 0 for uid 10001
10-11 13:48:09.339  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
10-11 13:48:09.340 10014 10046 D skia    : ---- fAsset->read(8192) returned 0
10-11 13:48:09.340 10014 10046 D skia    : --- SkAndroidCodec::NewFromStream returned null
10-11 13:48:09.344 10014 10046 D skia    : ---- fAsset->read(8192) returned 0
10-11 13:48:09.344 10014 10046 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-11 13:48:09.347  3701  3960 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED
,10-11 13:48:09.347  3701  3960 D ConnectivityService: ignoring duplicate network state non-change
10-11 13:48:09.347  5218 10045 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
10-11 13:48:09.347  5218 10045 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
10-11 13:48:09.347  5218 10045 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
10-11 13:48:09.347  5218 10045 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
10-11 13:48:09.347  5218 10045 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
10-11 13:48:09.347  5218 10045 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
10-11 13:48:09.347  5218 10045 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
10-11 13:48:09.347  5218 10045 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
10-11 13:48:09.347  5218 10045 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
10-11 13:48:09.347  5218 10045 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
10-11 13:48:09.347  5218 10045 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
10-11 13:48:09.347  5218 10045 E         : 	at java.lang.Thread.run(Thread.java:762)
10-11 13:48:09.347  5218 10045 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
10-11 13:48:09.347  5218 10045 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
10-11 13:48:09.347  5218 10045 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
10-11 13:48:09.347  5218 10045 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
10-11 13:48:09.347  5218 10045 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
10-11 13:48:09.347  5218 10045 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
10-11 13:48:09.347  5218 10045 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
10-11 13:48:09.347  5218 10045 E         : 	... 9 more
10-11 13:48:09.347  5218 10045 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
10-11 13:48:09.347  5218 10045 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Me,thod)
10-11 13:48:09.347  5218 10045 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
10-11 13:48:09.347  5218 10045 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
10-11 13:48:09.347  5218 10045 E         : 	... 26 more
10-11 13:48:09.347  5218 10045 E         : 
,10-11 13:48:09.349  5218 10045 E         : Unable to fetch advertisement frequency.
10-11 13:48:09.349  5218 10045 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
10-11 13:48:09.349  5218 10045 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
10-11 13:48:09.349  5218 10045 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
10-11 13:48:09.349  5218 10045 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
10-11 13:48:09.349  5218 10045 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
10-11 13:48:09.349  5218 10045 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
10-11 13:48:09.349  5218 10045 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
10-11 13:48:09.349  5218 10045 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
10-11 13:48:09.349  5218 10045 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
10-11 13:48:09.349  5218 10045 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
10-11 13:48:09.349  5218 10045 E         : 	at java.lang.Thread.run(Thread.java:762)
10-11 13:48:09.349  5218 10045 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
10-11 13:48:09.349  5218 10045 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
10-11 13:48:09.349  5218 10045 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
10-11 13:48:09.349  5218 10045 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
10-11 13:48:09.349  5218 10045 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
10-11 13:48:09.349  5218 10045 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
10-11 13:48:09.349  5218 10045 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
10-11 13:48:09.349  5218 10045 E         : 	... 9 more
10-11 13:48:09.349  5218 10045 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
10-11 13:48:09.349  5218 10045 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
10-11 13:48:09.349  5218 10045 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
10-11 13:48:09.349  5218 1004,5 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
10-11 13:48:09.349  5218 10045 E         : 	... 26 more
10-11 13:48:09.349  5218 10045 E         : 
,10-11 13:48:09.391 10014 10014 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
10-11 13:48:09.395  3701  3925 D SecContentProvider: insert(), uri = 2
,10-11 13:48:09.400  3701  3925 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:09.401  3701  3925 D WifiP2pService: P2pDisablingState
10-11 13:48:09.401  3701  3925 D WifiP2pService: P2pDisablingState{ what=147458 }
10-11 13:48:09.402  3701  3925 D WifiP2pService: p2p socket connection lost
10-11 13:48:09.402  3701  3925 D SecContentProvider: insert(), uri = 2
10-11 13:48:09.405  3701  3798 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: false, roaming: false, metered: false]
,10-11 13:48:09.406  3701  3925 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:09.410  3701  3930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-11 13:48:09.412  3701  3925 D WifiP2pService: P2pDisabledState
10-11 13:48:09.413  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-11 13:48:09.414  3701  4016 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
10-11 13:48:09.415  3701  3930 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-11 13:48:09.414  3701  3925 D WifiP2pService: P2pDisabledState{ what=143375 }
10-11 13:48:09.416  4291  4291 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
10-11 13:48:09.416  3701  3925 D WifiP2pService: DefaultState{ what=143375 }
10-11 13:48:09.418  5202  6781 I Authzen : [PermitStore] Getting all permits...
10-11 13:48:09.421  3701  3701 I WifiTrafficPoller: evaluateTrafficStatsPolling
10-11 13:48:09.422  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-11 13:48:09.423  3701  3701 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
10-11 13:48:09.423  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-11 13:48:09.423  3701  3956 I WifiHs20Service: Message received 5007
10-11 13:48:09.424  5202  5715 W MdnsClient_Cast: Multicast lock held. Releasing. Subtypes:"805741C9"
,10-11 13:48:09.426  3701  3930 D SecContentProvider: insert(), uri = 2
,10-11 13:48:09.431  4765  6863 I BeaconBle: Client requested scan, settings=BleSettings [scanMode=LOW_LATENCY, callbackType=ALL_MATCHES, reportDelayMillis=0, 3 filters, 0 clients, callingClientName=Nearby], listener=hjz@8eb2c05
,10-11 13:48:09.447  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
10-11 13:48:09.451  9917  9917 D BluetoothUtils: readSalesCode :: sales code is XEO
,10-11 13:48:09.452  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:09.464  3294  3778 D Netd    : Iface p2p0 link up
,10-11 13:48:09.470  3701  3796 D Tethering: interfaceLinkStateChanged p2p0, true
10-11 13:48:09.471  3701  3796 D Tethering: interfaceStatusChanged p2p0, true
,10-11 13:48:09.523  4291  4291 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,10-11 13:48:09.527  4291  4291 E wpa_supplicant: can't get BSS information
10-11 13:48:09.527  4291  4291 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.E6.C2 reason=3 locally_generated=1
,10-11 13:48:09.532  3294  3778 D Netd    : Iface wlan0 link up
10-11 13:48:09.534  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:09.534  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:09.541  5202  5715 W MdnsClient: unicast receiver thread is already dead.
,10-11 13:48:09.541  3701  3930 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:09.550  9789  9890 D BluetoothAdapter: STATE_ON
,10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-11 13:48:09.554  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-11 13:48:09.558  9789  9853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:48:09.560  3701  4923 D WifiService: setWifiEnabled: true pid=9789, uid=10033
,10-11 13:48:09.564  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-11 13:48:09.566  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135179 arg1=182 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:09.569  3701  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
10-11 13:48:09.569  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
10-11 13:48:09.569  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,10-11 13:48:09.569  3701  3956 I WifiHs20Service: Message received 5011
10-11 13:48:09.569  3701  3701 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
10-11 13:48:09.569  3701  3701 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
10-11 13:48:09.569  3701  4487 D SLocation: checkWifiInfo
10-11 13:48:09.570  3701  4487 D SLocation: wifi available : false
10-11 13:48:09.570  3701  4487 D SLocation: Session stopped
10-11 13:48:09.570  3701  4487 D SLocation: triggerAlarm
10-11 13:48:09.570  3701  4487 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / op:PendingIntent{d8c9dd8: PendingIntentRecord{a073531 android broadcastIntent}}
10-11 13:48:09.570  3701  4487 D SLocation: All alarm stopped
10-11 13:48:09.571  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=-2ms what=135173 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-11 13:48:09.573  3701  4923 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-11 13:48:09.573  3701  4923 D WifiControlHistoryProvider: query
10-11 13:48:09.574  3701  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
10-11 13:48:09.576  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:09.576  9443  9443 I DevicePlayback: Got network change: mobile=falsewifi=false
10-11 13:48:09.576  9443  9443 I DevicePlayback: Disabling Woodstock in 200000ms
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-11 13:48:09.582  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-11 13:48:09.582  3701  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
10-11 13:48:09.584  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:09.587  9789  9789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-11 13:48:09.589  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:09.598  4765  6863 I BeaconBle: 'L' hardware scan: 3 filters, scanMode=2, reportdelay=0, callback type=1, #clients=1
10-11 13:48:09.600  9211  9211 I WifiApBroadcastReceiver: onReceive: action com.samsung.intent.action.START_PROVISIONING userID :0
10-11 13:48:09.601  3701  4923 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-11 13:48:09.603  4765  6863 I BeaconBle: Starting scan on delegate scanner - BT state: 12
10-11 13:48:09.603  4765  6863 D BluetoothLeScanner: Start Scan
10-11 13:48:09.606  4765  6863 D BluetoothAdapter: STATE_ON
10-11 13:48:09.607  3701  4923 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:09.607  3701  4923 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
10-11 13:48:09.608  4765  6863 D BluetoothAdapter: STATE_ON
10-11 13:48:09.609  3701  3728 I WifiService: Wi-Fi Sharing settings has not been accessed
10-11 13:48:09.612  3701  4923 I WifiService: Wi-Fi Sharing settings has not been accessed
10-11 13:48:09.612  4765  6863 D BluetoothAdapter: STATE_ON
10-11 13:48:09.614  4070  4210 D vol.MediaSessions: onQueueChanged com.google.android.music []
10-11 13:48:09.615  4765  6863 D BluetoothAdapter: STATE_ON
10-11 13:48:09.615  3701  4923 D WifiService: unRegisterForSContext() : skip - it does not registered.
10-11 13:48:09.616  3701  3929 D SecContentProvider: insert(), uri = 2
10-11 13:48:09.618  3701  3929 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:09.618  3701  3929 D SecContentProvider: insert(), uri = 2
10-11 13:48:09.618  9917  9928 D BtGatt.GattService: registerClient() - UUID=4de5d889-bd3d-4c37-be38-73a936a1d463
10-11 13:48:09.619  3701  3929 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:09.626  3701  3710 I art     : Background partial concurrent mark sweep GC freed 140179(16MB) AllocSpace objects, 8(176KB) LOS objects, 27% free, 41MB/57MB, paused 1.455ms total 161.274ms
,10-11 13:48:09.631  3701  4915 D MountService: getExternalStorageMountMode : 3
,10-11 13:48:09.632  3701  4915 D MountService: getExternalStorageMountMode : 3
10-11 13:48:09.632  3701  4915 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 5017, packageName : com.samsung.android.radiobasedlocation
10-11 13:48:09.644  4291  4291 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-11 13:48:09.648 10067 10067 E Zygote  : v2
10-11 13:48:09.648 10067 10067 I libpersona: KNOX_SDCARD checking this for 5017
10-11 13:48:09.648 10067 10067 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:09.649 10067 10067 E Zygote  : accessInfo : 0
,10-11 13:48:09.652 10067 10067 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:09.652 10067 10067 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.radiobasedlocation 
,10-11 13:48:09.656  3701  4915 I ActivityManager: Start proc 10067:com.samsung.android.radiobasedlocation/5017 for broadcast com.samsung.android.radiobasedlocation/.RblServiceReceiver
,10-11 13:48:09.661  4765  6852 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,10-11 13:48:09.664 10067 10067 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-11 13:48:09.664 10067 10067 D ActivityThread: Added TimaKeyStore provider
10-11 13:48:09.667  3701  3729 I ActivityManager: DSS on for com.samsung.android.radiobasedlocation and scale is 1.0
,10-11 13:48:09.682 10067 10067 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-11 13:48:09.683 10067 10067 W System  : ClassLoader referenced unknown path: /system/priv-app/RadioBasedLocation/lib/arm64
,10-11 13:48:09.686  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:09.686  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:09.686  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:09.686  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:09.686  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:09.686  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:09.686  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:09.686  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:09.687  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:09.687  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:09.693 10067 10067 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:09.698 10067 10067 I [RBL] PathProvider: @onCreate
,10-11 13:48:09.701 10067 10067 I [RBL] ServiceReceiver: @onReceive - rawData : null
,10-11 13:48:09.704  3294  3778 D Netd    : Iface wlan0 link up
10-11 13:48:09.704  4291  4291 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-11 13:48:09.704  3294  3778 D Netd    : Iface wlan0 link up
10-11 13:48:09.704  4291  4291 I wpa_supplicant: CTRL_IFACE: Detach monitor that cannot receive messages: /data/misc/wifi/sockets/wpa_ctrl_3701-2\x00
,10-11 13:48:09.706  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
,10-11 13:48:09.706  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
10-11 13:48:09.707  3701  3919 I ActivityManager: KPU : put [com.samsung.android.bbc.bbcagent] : 26120 K
10-11 13:48:09.707  3701  3919 I ActivityManager: Killing 9198:com.samsung.android.bbc.bbcagent/1000 (adj 906): DHA:empty #33
,10-11 13:48:09.708  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:09.708  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:09.714  3701  3919 D MountService: getExternalStorageMountMode : 1
,10-11 13:48:09.714  3701  3919 D MountService: getExternalStorageMountMode : 3
10-11 13:48:09.714  3701  3919 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.diagmonagent
,10-11 13:48:09.723  9917  9937 D BtGatt.GattService: onClientRegistered() - UUID=4de5d889-bd3d-4c37-be38-73a936a1d463, clientIf=5, status=0
,10-11 13:48:09.724  4765  4777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,10-11 13:48:09.726  9917  9939 D BtGatt.GattService: start scan with filters
,10-11 13:48:09.729  9917  9939 D BtGatt.GattService: getScanSettings
,10-11 13:48:09.737 10082 10082 E Zygote  : v2
10-11 13:48:09.737 10082 10082 I libpersona: KNOX_SDCARD checking this for 1000
10-11 13:48:09.737 10082 10082 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:09.738 10082 10082 E Zygote  : accessInfo : 0
,10-11 13:48:09.743 10082 10082 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:09.744 10082 10082 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.diagmonagent 
,10-11 13:48:09.747  3701  3919 I ActivityManager: Start proc 10082:com.sec.android.diagmonagent/1000 for broadcast com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,10-11 13:48:09.749  3701  3728 D ActivityManager: cleanUpApplicationRecord -- 9198
10-11 13:48:09.751  4803  4819 D ForegroundUtils: could not check pending caller
,10-11 13:48:09.756  9917  9939 D BtGatt.GattService: Is it foreground application = false
10-11 13:48:09.756  9917  9939 D BtGatt.GattService: Its third party background application, change scanmode to low power
,10-11 13:48:09.760  3701  3930 D wifi    : In wifi stop Hal
10-11 13:48:09.760  3701  3930 D wifi    : halHandle = 0x70b0108c00, mVM = 0x70dc090300, mCls = 0x1010ee
10-11 13:48:09.760  3701  4289 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-11 13:48:09.760  3701  4289 D WifiHAL : Got a signal to exit!!!
10-11 13:48:09.760  3701  4289 I WifiHAL : Exit wifi_event_loop
10-11 13:48:09.761  3701  3930 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-11 13:48:09.762  3701  3930 E WifiHAL : Event processing terminated
,10-11 13:48:09.767 10082 10082 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:09.768 10082 10082 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:09.768  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
10-11 13:48:09.769  3701  3955 D HS20StateMachine: WIFI_STATE_DISABLED
10-11 13:48:09.769  3701  3955 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
,10-11 13:48:09.772  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,10-11 13:48:09.772  3701  3956 I WifiHs20Service: Message received 5011
10-11 13:48:09.772  3294  3778 D Netd    : Iface p2p0 link down
10-11 13:48:09.774  3701  3796 D Tethering: interfaceLinkStateChanged p2p0, false
10-11 13:48:09.775  3701  3796 D Tethering: interfaceStatusChanged p2p0, false
10-11 13:48:09.776  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:09.781  3701  3701 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
10-11 13:48:09.781  3701  4487 D SLocation: checkWifiInfo
,10-11 13:48:09.782  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-11 13:48:09.783  3701  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,10-11 13:48:09.785  4765  5201 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-11 13:48:09.788  9917  9917 D A2dpService: A2dpService - WIFI_STATE_DISABLED
10-11 13:48:09.788  9917  9917 I BluetoothA2dpServiceJni: Attempting to set busy level
,10-11 13:48:09.788  3701  4541 I ActivityManager: DSS on for com.sec.android.diagmonagent and scale is 1.0
,10-11 13:48:09.789  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_START_SCAN
,10-11 13:48:09.790  9917  9955 D BtGatt.ScanManager: handling starting scan
10-11 13:48:09.790  9917  9955 D BtGatt.ScanManager: isFilteringSupported
10-11 13:48:09.790  9917  9955 D BluetoothAdapter: enableStandAloneBleMode=
10-11 13:48:09.790  9917  9955 D BluetoothAdapter: STATE_ON
,10-11 13:48:09.791  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:48:09.791  9917  9955 D BluetoothAdapter: STATE_ON
,10-11 13:48:09.793  9917  9955 D BluetoothAdapter: STATE_ON
10-11 13:48:09.795  3701  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
10-11 13:48:09.795  9917  9955 D BluetoothAdapter: STATE_ON
10-11 13:48:09.796  9917  9955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:09.798  9917  9955 D BluetoothAdapter: STATE_ON
10-11 13:48:09.798  9917  9955 D BluetoothAdapter: STATE_ON
,10-11 13:48:09.806  9917  9937 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-11 13:48:09.806  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:09.808  9917  9955 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
10-11 13:48:09.808  9917  9955 D BtGatt.ScanManager: addFilterToController: 5
,10-11 13:48:09.813  9917  9937 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=47
10-11 13:48:09.813  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:09.814  9917  9955 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-11 13:48:09.814  9917  9955 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-11 13:48:09.814  9917  9955 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,10-11 13:48:09.816  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-11 13:48:09.819 10082 10082 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
10-11 13:48:09.820  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-11 13:48:09.820  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:09.820  9917  9955 D BtGatt.ScanManager: set filter index= 4 for clientIf= 5
10-11 13:48:09.820  9917  9955 D BtGatt.ScanManager: addFilterToController: 5
,10-11 13:48:09.824  3701  3930 D wifi    : In wifi cleaned up handler
10-11 13:48:09.824  3701  3930 I WifiHAL : Internal cleanup completed
,10-11 13:48:09.825  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-11 13:48:09.825  9917  9937 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=46
10-11 13:48:09.825  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:09.826  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
10-11 13:48:09.826  9917  9955 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-11 13:48:09.826  9917  9955 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-11 13:48:09.826  9917  9955 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,10-11 13:48:09.832  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=30
,10-11 13:48:09.832  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:09.832  9917  9955 D BtGatt.ScanManager: set filter index= 5 for clientIf= 5
10-11 13:48:09.832  9917  9955 D BtGatt.ScanManager: addFilterToController: 2
,10-11 13:48:09.833 10082 10082 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:09.837  9917  9937 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=45
10-11 13:48:09.837  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:09.837  9917  9955 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-11 13:48:09.837  9917  9955 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-11 13:48:09.837  9917  9955 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,10-11 13:48:09.841  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=29
,10-11 13:48:09.842  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:09.842  9917  9955 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
10-11 13:48:09.842  9917  9955 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=0 mLastConfiguredScanSetting=-2147483648
10-11 13:48:09.842  9917  9955 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 800
,10-11 13:48:09.848  9917  9937 D BtGatt.GattService: onScanParamSetupCompleted() status=0, clientIf=5
10-11 13:48:09.848  9917  9937 D BtGatt.GattService: onScanParamSetupCompleted : 0
,10-11 13:48:09.854 10082 10082 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,10-11 13:48:09.897 10082 10082 E SQLiteLog: (1) no such column: currentid
,10-11 13:48:09.899 10082 10082 E DIAGMON_AGENT: [llllIIIIlllIIIlIllIl(906/lllIlIlIIIllIIlIllIl)] android.database.sqlite.SQLiteException: no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1
10-11 13:48:09.899 10082 10082 E DIAGMON_AGENT: #################################################################
10-11 13:48:09.899 10082 10082 E DIAGMON_AGENT: Error Code : 1 (SQLITE_ERROR)
10-11 13:48:09.899 10082 10082 E DIAGMON_AGENT: Caused By : SQL(query) error or missing database.
10-11 13:48:09.899 10082 10082 E DIAGMON_AGENT: 	(no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1)
10-11 13:48:09.899 10082 10082 E DIAGMON_AGENT: #################################################################
,10-11 13:48:09.932 10082 10082 E SQLiteLog: (1) table profilelist has no column named currentid
,10-11 13:48:09.933 10082 10082 E SQLiteDatabase: Error inserting number=0 len=0 profilename3=Mformation notiretrycount=0 currentid=-1 size=0 oplevel=0 serviceid= appid=0 profilename2=dm-Server notievent=0 sessionid=null profilename1=api-server status=0 uictype=0 text= holdingid=-1 sessionsavestate=0 profileindex=0 opmode= result=0 pushjobid= notiuievent=0
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: android.database.sqlite.SQLiteException: table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: #################################################################
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: Error Code : 1 (SQLITE_ERROR)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: Caused By : SQL(query) error or missing database.
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	(table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?))
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: #################################################################
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1005)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.prepare(SQLiteConnection.java:570)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:588)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:59)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1771)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1643)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:667)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:399)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:116)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:60)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1032)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5885)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap3(ActivityThread.java)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1703)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:154)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6692)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke,(Native Method)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1468)
10-11 13:48:09.933 10082 10082 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1358)
,10-11 13:48:09.969 10082 10082 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(64/onCreate)] nStatus : 0
,10-11 13:48:09.976 10082 10082 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(77/onCreate)] DiagMon DM Application Start !
10-11 13:48:09.976 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,10-11 13:48:09.977 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-11 13:48:09.977 10082 10082 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
10-11 13:48:09.977 10082 10082 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,10-11 13:48:09.983  3701  3728 D MountService: getExternalStorageMountMode : 1
,10-11 13:48:09.983  3701  3728 D MountService: getExternalStorageMountMode : 3
10-11 13:48:09.984  3701  3728 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.app.RilErrorNotifier
,10-11 13:48:10.021 10096 10096 E Zygote  : v2
10-11 13:48:10.021 10096 10096 I libpersona: KNOX_SDCARD checking this for 1000
10-11 13:48:10.021 10096 10096 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:10.022 10096 10096 E Zygote  : accessInfo : 0
10-11 13:48:10.023  3701  3728 I ActivityManager: Start proc 10096:com.sec.app.RilErrorNotifier/1000 for broadcast com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
,10-11 13:48:10.030 10096 10096 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:10.031 10096 10096 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.app.RilErrorNotifier 
,10-11 13:48:10.033  3701  3728 I ActivityManager: KPU : put [com.facebook.system] : 26292 K
10-11 13:48:10.033  3701  3728 I ActivityManager: Killing 9262:com.facebook.system/u0a12 (adj 906): DHA:empty #33
,10-11 13:48:10.058 10096 10096 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:10.058 10096 10096 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:10.060  3701  4927 I ActivityManager: DSS on for com.sec.app.RilErrorNotifier and scale is 1.0
,10-11 13:48:10.071  3701  3919 D ActivityManager: cleanUpApplicationRecord -- 9262
,10-11 13:48:10.074  4803  4817 D ForegroundUtils: could not check pending caller
,10-11 13:48:10.090 10096 10096 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,10-11 13:48:10.095  4765  6863 I BeaconBle: Client requested to stop, listener=hjz@8eb2c05
,10-11 13:48:10.109 10096 10096 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:10.111  4765  6863 I BeaconBle: Stopping scan on delegate scanner - BT state: 12
,10-11 13:48:10.113  4765  6863 D BluetoothAdapter: STATE_ON
,10-11 13:48:10.115  4765  6863 D BluetoothAdapter: STATE_ON
10-11 13:48:10.115  4765  6863 D BluetoothLeScanner: Stop Scan
10-11 13:48:10.115 10096 10096 I PhoneErrorReceiver: onReceive
,10-11 13:48:10.116  9917  9929 D BtGatt.GattService: stopScan() - queue size =1
,10-11 13:48:10.116  9917  9929 D BtGatt.GattService: stopScan() - queue size =1
10-11 13:48:10.117  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_STOP_SCAN
,10-11 13:48:10.118  9917  9955 D BtGatt.ScanManager: stop scan
,10-11 13:48:10.118  9917  9955 D BtGatt.ScanManager: delete FilterIndex - 3
,10-11 13:48:10.121  3701  4918 D MountService: getExternalStorageMountMode : 1
10-11 13:48:10.121  3701  4918 D MountService: getExternalStorageMountMode : 3
,10-11 13:48:10.121  3701  4918 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.knox.switcher
,10-11 13:48:10.126  3701  3919 D WifiService: setWifiEnabled: true pid=9789, uid=10033
,10-11 13:48:10.130  9917  9928 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-11 13:48:10.134  4765  6863 D BluetoothAdapter: STATE_ON
10-11 13:48:10.135  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=30
10-11 13:48:10.135  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:10.136  9917  9955 D BtGatt.ScanManager: delete FilterIndex - 4
10-11 13:48:10.138  4765  6863 D BluetoothAdapter: STATE_ON
10-11 13:48:10.138  4765  6863 I BeaconBle: Resetting - new scanner available: true
10-11 13:48:10.139  4765  6863 I BeaconBle: 'L' hardware scan: scan stopped, no clients
,10-11 13:48:10.139  4765  6863 I BeaconBle: Scan canceled successfully.
10-11 13:48:10.140  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=31
10-11 13:48:10.141  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:10.141  9917  9955 D BtGatt.ScanManager: delete FilterIndex - 5
10-11 13:48:10.146  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-11 13:48:10.146  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:10.146  9917  9955 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
10-11 13:48:10.146  9917  9955 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=0
10-11 13:48:10.146  9917  9955 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
10-11 13:48:10.160 10110 10110 E Zygote  : v2
10-11 13:48:10.160 10110 10110 I libpersona: KNOX_SDCARD checking this for 1000
10-11 13:48:10.160 10110 10110 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:10.160  3701  4918 I ActivityManager: Start proc 10110:com.sec.knox.switcher/1000 for broadcast com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
10-11 13:48:10.160  3701  3919 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-11 13:48:10.161  3701  3919 D WifiControlHistoryProvider: query
10-11 13:48:10.161 10110 10110 E Zygote  : accessInfo : 0
,10-11 13:48:10.163  3701  3729 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{bfc5ec6: PendingIntentRecord{278de87 com.google.android.gms broadcastIntent}}
10-11 13:48:10.167  4765  6863 W NearbyMessages: Runnable[ScanComplete] not posted since EventLoop is destroyed
,10-11 13:48:10.168  3701  4918 I ActivityManager: KPU : put [com.google.android.apps.docs] : 41396 K
10-11 13:48:10.168  3701  4918 I ActivityManager: Killing 9277:com.google.android.apps.docs/u0a93 (adj 906): DHA:empty #33
,10-11 13:48:10.171 10110 10110 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:10.171  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-11 13:48:10.172  3701  3919 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-11 13:48:10.173 10110 10110 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.knox.switcher 
10-11 13:48:10.173  3701  3919 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:10.174  3701  3919 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-11 13:48:10.178  3701  3919 I WifiService: Wi-Fi Sharing settings has not been accessed
10-11 13:48:10.178  3701  3919 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-11 13:48:10.179  3701  3929 E WifiController: illegal state found both WifiController and WifiStateMachine
,10-11 13:48:10.194  4765  4765 I BeaconBle: 'L' hardware scan: scan stopped, no clients
,10-11 13:48:10.201 10110 10110 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:10.202 10110 10110 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:10.204  3701  4928 I ActivityManager: DSS on for com.sec.knox.switcher and scale is 1.0
,10-11 13:48:10.211  3701  3927 D ActivityManager: cleanUpApplicationRecord -- 9277
,10-11 13:48:10.216  4803  6438 D ForegroundUtils: could not check pending caller
,10-11 13:48:10.227 10110 10110 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,10-11 13:48:10.243 10110 10110 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:10.250 10110 10110 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
10-11 13:48:10.250 10110 10110 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,10-11 13:48:10.250 10110 10110 D ShareFileProvider: ShareFileProvider | onCreate [0]
10-11 13:48:10.250 10110 10110 D ShareFileDBHelper: getInstance - ShareFileDBHelper
10-11 13:48:10.250 10110 10110 D ShareFileDBHelper: null == mDbHelperInstance - ShareFileDBHelper
10-11 13:48:10.250 10110 10110 D ShareFileDBHelper: ShareFileDBHelper - Constructor
,10-11 13:48:10.253 10110 10110 I usagelog: received in receiver
,10-11 13:48:10.253 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,10-11 13:48:10.257 10110 10110 I KnoxUsageLogPro: premStatus:2
,10-11 13:48:10.263 10110 10110 I KnoxUsageLogPro: isEulaShown : false
10-11 13:48:10.263 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,10-11 13:48:10.266  3701  4921 D MountService: getExternalStorageMountMode : 1
10-11 13:48:10.266  3701  4921 D MountService: getExternalStorageMountMode : 3
,10-11 13:48:10.266  3701  4921 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10003, packageName : com.sec.android.provider.badge
,10-11 13:48:10.285 10123 10123 E Zygote  : v2
10-11 13:48:10.285 10123 10123 I libpersona: KNOX_SDCARD checking this for 10003
10-11 13:48:10.285 10123 10123 I libpersona: KNOX_SDCARD not a persona
,10-11 13:48:10.286 10123 10123 E Zygote  : accessInfo : 0
10-11 13:48:10.286  3701  4921 I ActivityManager: Start proc 10123:com.sec.android.provider.badge/u0a3 for broadcast com.sec.android.provider.badge/.BadgeCountReceiver
,10-11 13:48:10.290  3701  4921 I ActivityManager: KPU : put [com.facebook.appmanager] : 23044 K
10-11 13:48:10.290  3701  4921 I ActivityManager: Killing 9239:com.facebook.appmanager/u0a98 (adj 906): DHA:empty #33
,10-11 13:48:10.293 10123 10123 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:10.295 10123 10123 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,10-11 13:48:10.307  3701  4488 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / op:PendingIntent{6e53121: PendingIntentRecord{5142946 android broadcastIntent}}
,10-11 13:48:10.311  3701  4543 D ActivityManager: cleanUpApplicationRecord -- 9239
,10-11 13:48:10.312  4803  6438 D ForegroundUtils: could not check pending caller
,10-11 13:48:10.314  3701  4488 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20171012T134810 - CU:1000/CP:3701
,10-11 13:48:10.324 10123 10123 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:10.325 10123 10123 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:10.327  3701  3927 I ActivityManager: DSS on for com.sec.android.provider.badge and scale is 1.0
,10-11 13:48:10.352 10123 10123 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_N/lib/arm64
,10-11 13:48:10.366 10123 10123 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:10.373 10123 10123 D BadgeProvider: onCreate
10-11 13:48:10.374 10123 10123 D BadgeProvider: DatabaseHelper
,10-11 13:48:10.376 10123 10123 D BadgeCountReceiver: badge intent : Intent { act=com.sec.intent.action.BADGE_COUNT_UPDATE flg=0x10 cmp=com.sec.android.provider.badge/.BadgeCountReceiver launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-11 13:48:10.376 10123 10123 D BadgeCountReceiver: packageName: com.samsung.android.email.provider, className: com.samsung.android.email.ui.activity.MessageListXL, count: 0
,10-11 13:48:10.381 10123 10123 D BadgeProvider: onOpen
,10-11 13:48:10.384 10123 10123 D BaseReflect: null getOwnClass TEST
10-11 13:48:10.385 10123 10123 D MethodReflector: android.content.ContentResolver getClass TEST
10-11 13:48:10.385 10123 10123 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
10-11 13:48:10.385 10123 10123 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,10-11 13:48:10.387 10123 10123 D MethodReflector: notifyChange is called
10-11 13:48:10.387  4961  4961 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
,10-11 13:48:10.388 10123 10123 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
10-11 13:48:10.388 10123 10123 D BadgeProvider: sendNotify, [notify] : null
,10-11 13:48:10.389 10123 10123 D BadgeProvider: update, getCallingPackage() : com.sec.android.provider.badge
,10-11 13:48:10.389  4961  4961 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
10-11 13:48:10.389 10123 10123 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
10-11 13:48:10.389 10123 10123 D BadgeProvider: update, [uri.query] : null
10-11 13:48:10.389 10123 10123 D BadgeProvider: update, [BadgeCount] : badgecount=0
10-11 13:48:10.389 10123 10123 D BadgeProvider: update, [UpdateCount] : 1
,10-11 13:48:10.394  3701  4928 I ActivityManager: KPU : put [com.google.android.partnersetup] : 26172 K
,10-11 13:48:10.394  3294  3778 D Netd    : Iface wlan0 link down
10-11 13:48:10.394  3701  4928 I ActivityManager: Killing 9324:com.google.android.partnersetup/u0a23 (adj 906): DHA:empty #33
,10-11 13:48:10.397  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, false
10-11 13:48:10.397  3701  4289 D wifi    : set interface wlan0 flags (DOWN)
10-11 13:48:10.397  3701  3796 D Tethering: interfaceStatusChanged wlan0, false
10-11 13:48:10.397  3701  3930 D WifiNative-HAL: HAL event thread stopped successfully
,10-11 13:48:10.422  3701  4923 D ActivityManager: cleanUpApplicationRecord -- 9324
,10-11 13:48:10.423  4803  6438 D ForegroundUtils: could not check pending caller
,10-11 13:48:10.425  5202  5202 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-11 13:48:10.427  5202  8287 I iu.UploadsManager: num queued entries: 0
10-11 13:48:10.428  5202  8287 I iu.UploadsManager: num updated entries: 0
,10-11 13:48:10.429  5202  8287 I iu.SyncManager: NEXT; no task
,10-11 13:48:10.433  3701  4928 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:10.451  3701  4181 D MountService: getExternalStorageMountMode : 1
10-11 13:48:10.451  3701  4181 D MountService: getExternalStorageMountMode : 3
10-11 13:48:10.451  3701  4181 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10041, packageName : com.osp.app.signin
,10-11 13:48:10.471 10136 10136 E Zygote  : v2
10-11 13:48:10.471 10136 10136 I libpersona: KNOX_SDCARD checking this for 10041
10-11 13:48:10.471 10136 10136 I libpersona: KNOX_SDCARD not a persona
,10-11 13:48:10.472 10136 10136 E Zygote  : accessInfo : 0
,10-11 13:48:10.477  3701  4181 I ActivityManager: Start proc 10136:com.osp.app.signin/u0a41 for broadcast com.osp.app.signin/.OspReceiver
,10-11 13:48:10.482 10136 10136 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:10.484 10136 10136 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.osp.app.signin 
,10-11 13:48:10.511  3701  4913 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20171011T141810 - CU:10124/CP:5148
,10-11 13:48:10.515 10136 10136 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:10.515 10136 10136 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:10.518  3701  4887 I ActivityManager: DSS on for com.osp.app.signin and scale is 1.0
,10-11 13:48:10.589  4961  4961 D LauncherApplication: run: mBadgeRefreshHandler reloadBadges
10-11 13:48:10.589  4961  4961 D Launcher.Model: reloadBadges entered.
,10-11 13:48:10.596 10136 10136 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-11 13:48:10.599 10136 10136 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Dream/lib/arm64
,10-11 13:48:10.600  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-11 13:48:10.606 10123 10134 D BadgeProvider: query, [selection] : null
10-11 13:48:10.607  3701  3930 E WifiHW  : ##################### set firmware type 0 #####################
10-11 13:48:10.611  3294  3786 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,10-11 13:48:10.612  3294  3786 I WifiHW  : module is semco
10-11 13:48:10.613  3294  3786 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
10-11 13:48:10.613  3294  3786 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
10-11 13:48:10.613  3294  3786 E WifiHW  : TEMP_FAILURE_RETRY complete
10-11 13:48:10.615  3294  3786 D SoftapController: Softap fwReload - Ok
10-11 13:48:10.617  3701  3930 E NetworkManagement: wifiFirmwareReload Error reloading wlan0 fw in STA mode: event = 200 219 Softap operation succeeded
,10-11 13:48:10.619  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:10.620  4961  5056 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
10-11 13:48:10.620  4961  5056 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
,10-11 13:48:10.620  4961  5056 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
10-11 13:48:10.621  4961  5056 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
10-11 13:48:10.621  4961  5056 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
10-11 13:48:10.621  4961  5056 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
10-11 13:48:10.621  4961  5056 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
10-11 13:48:10.621  4961  5056 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.lool = 0
10-11 13:48:10.621  4961  5056 D BadgeCache: 1. updateBadgeCounts: com.wssyncmldm = 1
10-11 13:48:10.621  4961  5056 D BadgeCache: 2. updateBadgeCounts: com.wssyncmldm/com.samsung.android.app.fotaclient.FotaApplication = 1
10-11 13:48:10.623  3294  3786 D CommandListener: Setting iface cfg
10-11 13:48:10.623  3294  3786 D CommandListener: Trying to bring down wlan0
,10-11 13:48:10.626  4961  5056 D BadgeCache: updated Badged:2
10-11 13:48:10.626  4961  5056 D BadgeCache: updateBadgeCounts:2
10-11 13:48:10.626  4961  5056 D Launcher.Model: reloadBadges, badges count : 2
10-11 13:48:10.626  4961  5056 D Launcher.Model: appItems:0 homeItems:0
10-11 13:48:10.627  3294  3786 D CommandListener: Clearing all IP addresses on wlan0
,10-11 13:48:10.631 10136 10136 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:10.636  3701  3930 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-11 13:48:10.648 10136 10136 I SA      : [SSP] onCreated
,10-11 13:48:10.683 10136 10136 D SamsungAnalytics:1.8.22: cf feature is supported
,10-11 13:48:10.688  3701  4887 D WifiService: setWifiEnabled: true pid=9789, uid=10033
10-11 13:48:10.689  3701  4887 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-11 13:48:10.689  3701  4887 D WifiControlHistoryProvider: query
,10-11 13:48:10.693 10136 10136 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
,10-11 13:48:10.700 10136 10136 I SA      : LBE isSupportBixbyModel() FALSE
,10-11 13:48:10.701  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:10.702  3701  4887 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-11 13:48:10.704  3701  4887 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:10.706  3701  4887 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-11 13:48:10.712  3701  4887 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-11 13:48:10.713  3701  4887 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-11 13:48:10.714  3701  3929 E WifiController: illegal state found both WifiController and WifiStateMachine
10-11 13:48:10.715 10136 10136 I SA      : [TPM] There is no property file
,10-11 13:48:10.727 10136 10136 I SA      : [SCU] isHaveSA() - false
,10-11 13:48:10.735 10136 10136 I SA      : [SS] no samsung account is signed in
,10-11 13:48:10.740 10136 10136 I SA      : [TPM] getModelProperty : null
10-11 13:48:10.740 10136 10136 I SA      : [TPM] getCSCProperty : null
,10-11 13:48:10.743 10136 10136 I SA      : [SCU] isHaveSA() - false
,10-11 13:48:10.746 10136 10136 I SA      : [SCU] == networkStateCheck == false
10-11 13:48:10.746 10136 10136 I SA      : [SS] network off, couldn't connect to DIR
,10-11 13:48:10.753 10136 10136 D BixbyApi_0.1.6: Version Name:2.2.03-46
,10-11 13:48:10.756 10136 10136 I SA      : [DM] init START
,10-11 13:48:10.764 10136 10136 I SA      : [DM] This device is not a Vodafone
,10-11 13:48:10.770 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.771 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.771 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.771 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.772 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.772 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.773 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.773 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.773 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.774 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.774 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.775 10136 10136 W ResourceType: Failure getting entry for 0x7f0b0002 (t=10 e=2) (error -75)
10-11 13:48:10.775 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.776 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.776 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.777 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.777 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.778 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.778 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.779 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.779 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.779 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.780 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.780 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.781 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.781 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.782 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.782 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.783 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.783 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.784 10136 10136 W ResourceType: Failure getting entry for 0x7f0b0005 (t=10 e=5) (error -75)
,10-11 13:48:10.784 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.785 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.785 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.786 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.786 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.787 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.787 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.788 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.788 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.789 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.789 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.790 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.790 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.790 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.791 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.791 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-11 13:48:10.792 10136 10136 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-11 13:48:10.795 10136 10136 I SA      : support phone number id : true
10-11 13:48:10.795 10136 10136 I SA      : [DM] Supports Ref Jpn : true
10-11 13:48:10.795 10136 10136 I SA      : [DM] init END
,10-11 13:48:10.796 10136 10136 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,10-11 13:48:10.799 10136 10136 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
10-11 13:48:10.799 10136 10136 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,10-11 13:48:10.811 10136 10136 I SA      : [SLFUCHKMGR] constructor called
,10-11 13:48:10.826 10136 10136 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
10-11 13:48:10.826 10136 10136 I SA      : [OR] == isSIMCardReady false ==
,10-11 13:48:10.826 10136 10136 I SA      : [SCU] == networkStateCheck == false
10-11 13:48:10.826 10136 10136 I SA      : [OR] onReceive END
,10-11 13:48:10.837  3701  3763 D MountService: getExternalStorageMountMode : 1
10-11 13:48:10.837  3701  3763 D MountService: getExternalStorageMountMode : 3
10-11 13:48:10.837  3701  3763 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.svcagent
,10-11 13:48:10.859 10159 10159 E Zygote  : v2
10-11 13:48:10.859 10159 10159 I libpersona: KNOX_SDCARD checking this for 1000
10-11 13:48:10.859 10159 10159 I libpersona: KNOX_SDCARD not a persona
,10-11 13:48:10.860 10159 10159 E Zygote  : accessInfo : 0
,10-11 13:48:10.866  3701  3763 I ActivityManager: Start proc 10159:com.samsung.android.svcagent/1000 for broadcast com.samsung.android.svcagent/com.samsung.android.service.svcagent.BootReceiver
,10-11 13:48:10.870 10159 10159 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:10.872 10159 10159 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.svcagent 
,10-11 13:48:10.907 10159 10159 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:10.908 10159 10159 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:10.911  3701  4923 I ActivityManager: DSS on for com.samsung.android.svcagent and scale is 1.0
,10-11 13:48:10.936 10159 10159 W System  : ClassLoader referenced unknown path: /system/priv-app/SVCAgent/lib/arm64
,10-11 13:48:10.956 10159 10159 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:10.964 10159 10159 I SVCAgent: Ignore network change.
,10-11 13:48:10.967  3701  4915 D MountService: getExternalStorageMountMode : 1
10-11 13:48:10.967  3701  4915 D MountService: getExternalStorageMountMode : 3
10-11 13:48:10.967  3701  4915 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10064, packageName : com.samsung.android.themestore
,10-11 13:48:11.003 10172 10172 E Zygote  : v2
,10-11 13:48:11.003 10172 10172 I libpersona: KNOX_SDCARD checking this for 10064
10-11 13:48:11.003 10172 10172 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:11.004 10172 10172 E Zygote  : accessInfo : 0
,10-11 13:48:11.008  3701  4915 I ActivityManager: Start proc 10172:com.samsung.android.themestore/u0a64 for broadcast com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,10-11 13:48:11.010 10172 10172 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:11.012 10172 10172 I SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,10-11 13:48:11.015  3701  4915 I ActivityManager: KPU : put [com.samsung.android.SettingsReceiver] : 26156 K
10-11 13:48:11.015  3701  4915 I ActivityManager: Killing 8420:com.samsung.android.SettingsReceiver/1000 (adj 906): DHA:empty #33
,10-11 13:48:11.034 10172 10172 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:11.035 10172 10172 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:11.037  3701  4913 I ActivityManager: DSS on for com.samsung.android.themestore and scale is 1.0
,10-11 13:48:11.045  3701  4540 D ActivityManager: cleanUpApplicationRecord -- 8420
,10-11 13:48:11.050  4803  6438 D ForegroundUtils: could not check pending caller
,10-11 13:48:11.060  4648  4648 D io_stats: !@   8,0 r 25978 2297772 w 5230 209100 d 676 75036 f 2100 2100 iot 11940 10942 th 472324 0 0 pt 0 inp 0 0 202.196
,10-11 13:48:11.069 10172 10172 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-11 13:48:11.071 10172 10172 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyThemes/lib/arm64
,10-11 13:48:11.090 10172 10172 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:11.112 10172 10172 D a       : Exist Config : false
,10-11 13:48:11.114 10172 10172 D a       : getMcc
,10-11 13:48:11.119 10172 10172 D as      : isQaMode
,10-11 13:48:11.126 10172 10172 D a       : getMnc
10-11 13:48:11.126 10172 10172 D a       : getCsc
,10-11 13:48:11.126 10172 10172 D a       : getSystemCountryCode
10-11 13:48:11.126 10172 10172 D a       : getImei
,10-11 13:48:11.131 10172 10172 D as      : getMd5HashString
,10-11 13:48:11.132 10172 10172 D as      : getSha256HashString
10-11 13:48:11.132 10172 10172 D a       : getModelName
10-11 13:48:11.133 10172 10172 D a       : getVirtualModelName
10-11 13:48:11.133 10172 10172 D a       : getAndroidSDKVersion
,10-11 13:48:11.133 10172 10172 D a       : getLanguageCode
10-11 13:48:11.133 10172 10172 D a       : getCountryCode
,10-11 13:48:11.135 10172 10172 D a       : getNetworkType
,10-11 13:48:11.140 10172 10172 D w       : isSupportedAodSystemFeature
,10-11 13:48:11.143 10172 10172 D a       : getThemeFrameworkVersion
,10-11 13:48:11.150 10172 10172 D a       : isLogPrintMode
,10-11 13:48:11.154 10172 10172 D as      : isQaMode
,10-11 13:48:11.164 10172 10172 D a       : getVerName
,10-11 13:48:11.166 10172 10172 D a       : getVerCode
,10-11 13:48:11.168 10172 10172 D a       : getPackageName
10-11 13:48:11.168 10172 10172 D a       : getAutoUpgradeInterval
,10-11 13:48:11.170 10172 10172 D a       : loadCountrySearchEx
,10-11 13:48:11.176 10172 10172 D a       : com.samsung.android.themestore.g.c.b.u; class invalid for deserialization
,10-11 13:48:11.177 10172 10172 I a       : # initConfig Time : 68
10-11 13:48:11.177 10172 10172 I a       : ● MCC/NNC: /0
10-11 13:48:11.177 10172 10172 I a       : ● Model: SM-G930F_TM
10-11 13:48:11.177 10172 10172 I a       : ● MyApp Version: 2.1.56-70306
10-11 13:48:11.177 10172 10172 I a       : ● OS Version: 24
10-11 13:48:11.177 10172 10172 I a       : ● IsSupportedSView: true
,10-11 13:48:11.203 10172 10172 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,10-11 13:48:11.221  3701  4915 D WifiService: setWifiEnabled: true pid=9789, uid=10033
10-11 13:48:11.222  3701  4915 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-11 13:48:11.222  3701  4915 D WifiControlHistoryProvider: query
,10-11 13:48:11.235  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:11.235  3701  4915 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-11 13:48:11.237  3701  4915 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:11.238 10172 10172 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
10-11 13:48:11.238  3701  4915 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-11 13:48:11.242  3701  4915 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-11 13:48:11.243  3701  4915 D WifiService: unRegisterForSContext() : skip - it does not registered.
10-11 13:48:11.243  3701  3929 E WifiController: illegal state found both WifiController and WifiStateMachine
,10-11 13:48:11.251  3701  3763 I ActivityManager: KPU : put [com.samsung.android.app.mirrorlink] : 20780 K
10-11 13:48:11.252  3701  3763 I ActivityManager: Killing 9344:com.samsung.android.app.mirrorlink/1000 (adj 906): DHA:empty #33
,10-11 13:48:11.257  8016  8016 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
10-11 13:48:11.257  8016  8016 E SPPClientService: [SystemStateMoniter] Current Time : 202394
10-11 13:48:11.258  8016  8016 E SPPClientService: [SystemStateMoniter] No Connect : true
,10-11 13:48:11.280  3701  4180 D MountService: getExternalStorageMountMode : 1
10-11 13:48:11.280  3701  4180 D MountService: getExternalStorageMountMode : 3
10-11 13:48:11.280  3701  4180 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 5005, packageName : com.samsung.android.allshare.service.fileshare
,10-11 13:48:11.283  8016 10198 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,10-11 13:48:11.300 10199 10199 E Zygote  : v2
,10-11 13:48:11.301 10199 10199 I libpersona: KNOX_SDCARD checking this for 5005
10-11 13:48:11.301 10199 10199 I libpersona: KNOX_SDCARD not a persona
,10-11 13:48:11.302 10199 10199 E Zygote  : accessInfo : 0
10-11 13:48:11.302  3701  4180 I ActivityManager: Start proc 10199:com.samsung.android.allshare.service.fileshare/5005 for broadcast com.samsung.android.allshare.service.fileshare/.FileShareBroadcastReceiver
,10-11 13:48:11.303  3701  3728 D ActivityManager: cleanUpApplicationRecord -- 9344
,10-11 13:48:11.310  4803  4819 D ForegroundUtils: could not check pending caller
,10-11 13:48:11.312 10199 10199 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:11.314 10199 10199 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.allshare.service.fileshare 
,10-11 13:48:11.346 10199 10199 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:11.347 10199 10199 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:11.349  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:48:11.349  3701  4543 I ActivityManager: DSS on for com.samsung.android.allshare.service.fileshare and scale is 1.0
10-11 13:48:11.351  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:11.351  3701  3930 D wifi    : set interface wlan0 flags (UP)
10-11 13:48:11.351  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
10-11 13:48:11.351  3701  3930 I WifiHAL : Initializing wifi
10-11 13:48:11.351  3701  3930 I WifiHAL : Creating socket
10-11 13:48:11.355  3701  3930 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-11 13:48:11.355  3701  3930 D wifi    : Did set static halHandle = 0x70b0108c00
10-11 13:48:11.355  3701  3930 D wifi    : halHandle = 0x70b0108c00, mVM = 0x70dc090300, mCls = 0x203026
10-11 13:48:11.355  3701  3930 D wifi    : array field set
10-11 13:48:11.356  3701  3930 I WifiHW  : CCMode is disabled, skip verifying wpa_supplicant
,10-11 13:48:11.356  3701 10213 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=483990211584
10-11 13:48:11.357  3701 10213 D wifi    : waitForHalEvents called, vm = 0x70dc090300, obj = 0x203026, env = 0x70b1b51f80
10-11 13:48:11.357  3701  3930 E WifiHW  : supplicant_name : p2p_supplicant
,10-11 13:48:11.386 10199 10199 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:11.392 10199 10199 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,10-11 13:48:11.394 10199 10199 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
,10-11 13:48:11.412 10199 10199 D FileShare: Outbound.stopDelayTimer - 
,10-11 13:48:11.428 10214 10214 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 10214 | /system/bin/wpa_supplicant
10-11 13:48:11.428 10214 10214 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
,10-11 13:48:11.430 10214 10214 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,10-11 13:48:11.430 10214 10214 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-11 13:48:11.433 10214 10214 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x400008), vendorssid_list()
10-11 13:48:11.433 10214 10214 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
10-11 13:48:11.434  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10214
10-11 13:48:11.434  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
10-11 13:48:11.435 10214 10214 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
10-11 13:48:11.435 10214 10214 I wpa_supplicant: ssSupport state is = 1
10-11 13:48:11.435 10214 10214 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
10-11 13:48:11.435 10214 10214 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
10-11 13:48:11.435  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
10-11 13:48:11.435  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10214
10-11 13:48:11.435  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,10-11 13:48:11.443 10067 10067 I [RBL] ServiceReceiver: @onReceive - rawData : null
,10-11 13:48:11.453  3701  4542 I ActivityManager: KPU : put [com.samsung.android.sm.provider] : 27212 K
10-11 13:48:11.454  3701  4542 I ActivityManager: Killing 4659:com.samsung.android.sm.provider/1000 (adj 906): DHA:empty #33
,10-11 13:48:11.459  3701  3930 D SecContentProvider: insert(), uri = 2
10-11 13:48:11.459  3701  3930 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:11.461  3701  3930 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
10-11 13:48:11.462  3701  3930 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
10-11 13:48:11.466  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
10-11 13:48:11.467  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
10-11 13:48:11.467  3701  3956 I WifiHs20Service: Message received 5011
10-11 13:48:11.468  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135173 arg1=2 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-11 13:48:11.471  3701  3701 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
10-11 13:48:11.471  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-11 13:48:11.472  3701  4487 D SLocation: checkWifiInfo
10-11 13:48:11.472  3701  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
10-11 13:48:11.476  3701  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
10-11 13:48:11.478  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:11.501 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
10-11 13:48:11.501 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-11 13:48:11.501 10082 10082 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,10-11 13:48:11.514  3701  4541 D ActivityManager: cleanUpApplicationRecord -- 4659
,10-11 13:48:11.514 10096 10096 I PhoneErrorReceiver: onReceive
,10-11 13:48:11.523  4803  6438 D ForegroundUtils: could not check pending caller
,10-11 13:48:11.531 10110 10110 I usagelog: received in receiver
10-11 13:48:11.532 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,10-11 13:48:11.533 10110 10110 I KnoxUsageLogPro: premStatus:2
10-11 13:48:11.534 10110 10110 I KnoxUsageLogPro: isEulaShown : false
10-11 13:48:11.534 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,10-11 13:48:11.544  9856  9856 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
10-11 13:48:11.544  9856  9856 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,10-11 13:48:11.549  3701  3919 D MountService: getExternalStorageMountMode : 1
10-11 13:48:11.549  3701  3919 D MountService: getExternalStorageMountMode : 3
10-11 13:48:11.549  3701  3919 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10172, packageName : com.example.ThaliTestApp
,10-11 13:48:11.573 10215 10215 E Zygote  : v2
,10-11 13:48:11.573 10215 10215 I libpersona: KNOX_SDCARD checking this for 10172
10-11 13:48:11.573 10215 10215 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:11.573  3701  3919 I ActivityManager: Start proc 10215:com.example.ThaliTestApp/u0a172 for broadcast com.example.ThaliTestApp/io.jxcore.node.ConnectivityChangeListener
10-11 13:48:11.574 10215 10215 E Zygote  : accessInfo : 0
,10-11 13:48:11.582  3701  5735 D SSRM:f  : SIOP:: AP = 320, PST = 312 (W:10), CP = 264, CUR = 177, LCD = 57
,10-11 13:48:11.585 10215 10215 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:11.585  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,10-11 13:48:11.587 10215 10215 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.ThaliTestApp 
,10-11 13:48:11.593 10215 10215 I art     : Late-enabling -Xcheck:jni
,10-11 13:48:11.620 10214 10214 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,10-11 13:48:11.626 10215 10215 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:11.626 10215 10215 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:11.629  3701  4923 I ActivityManager: DSS on for com.example.ThaliTestApp and scale is 1.0
,10-11 13:48:11.653 10214 10214 W wpa_supplicant: Loading system cred
,10-11 13:48:11.653 10214 10214 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
10-11 13:48:11.654  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10214
10-11 13:48:11.654  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
10-11 13:48:11.654 10214 10214 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
10-11 13:48:11.654 10214 10214 I wpa_supplicant: ssSupport state is = 1
,10-11 13:48:11.654  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
10-11 13:48:11.655 10214 10214 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
10-11 13:48:11.655 10214 10214 I wpa_supplicant: [getIMSI]: sim_num 0
,10-11 13:48:11.668 10215 10215 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-11 13:48:11.690 10215 10215 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:11.699  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.700  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.700  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.700  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.700  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.701  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.701  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.701  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.702  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.702  3701  4543 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.705 10214 10214 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-11 13:48:11.706  3294  3778 D Netd    : Iface wlan0 link up
10-11 13:48:11.707  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:48:11.709  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:11.709  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:11.711  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:11.712  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:11.741 10215 10215 D jxcore_app_log: JniHelper::setJavaVM(0xe73b4000), pthread_self() = -359676620
10-11 13:48:11.741 10215 10215 E JX-Cordova: JXcore wasn't initialized yet
,10-11 13:48:11.748  3701  4541 D MountService: getExternalStorageMountMode : 1
,10-11 13:48:11.748  3701  4541 D MountService: getExternalStorageMountMode : 3
10-11 13:48:11.748  3701  4541 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10173, packageName : com.rockwellautomation.AppPlatformP2P
,10-11 13:48:11.751  3701  4918 D WifiService: setWifiEnabled: true pid=9789, uid=10033
,10-11 13:48:11.773 10230 10230 E Zygote  : v2
10-11 13:48:11.773 10230 10230 I libpersona: KNOX_SDCARD checking this for 10173
,10-11 13:48:11.773 10230 10230 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:11.774 10230 10230 E Zygote  : accessInfo : 0
,10-11 13:48:11.775  3701  4541 I ActivityManager: Start proc 10230:com.rockwellautomation.AppPlatformP2P/u0a173 for broadcast com.rockwellautomation.AppPlatformP2P/io.jxcore.node.ConnectivityChangeListener
,10-11 13:48:11.781  3701  4541 I ActivityManager: KPU : put [com.samsung.android.scloud] : 27724 K
10-11 13:48:11.781  3701  4541 I ActivityManager: Killing 9362:com.samsung.android.scloud/5009 (adj 906): DHA:empty #33
10-11 13:48:11.782 10230 10230 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-11 13:48:11.782  3701  4918 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-11 13:48:11.783  3701  4918 D WifiControlHistoryProvider: query
10-11 13:48:11.784 10230 10230 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.rockwellautomation.AppPlatformP2P 
10-11 13:48:11.786 10230 10230 I art     : Late-enabling -Xcheck:jni
,10-11 13:48:11.790  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-11 13:48:11.791  3701  4918 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-11 13:48:11.792  3701  4918 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:11.792  3701  4918 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-11 13:48:11.796  3701  4918 I WifiService: Wi-Fi Sharing settings has not been accessed
10-11 13:48:11.797  3701  4918 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-11 13:48:11.806 10214 10214 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,10-11 13:48:11.806 10214 10214 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
10-11 13:48:11.807  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10214
10-11 13:48:11.807  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
10-11 13:48:11.807 10214 10214 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
10-11 13:48:11.807 10214 10214 I wpa_supplicant: ssSupport state is = 1
,10-11 13:48:11.808  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,10-11 13:48:11.810 10214 10214 E wpa_supplicant: nl80211: Could not configure driver mode
,10-11 13:48:11.810 10214 10214 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
10-11 13:48:11.810 10214 10214 E wpa_supplicant: p2p0: Failed to initialize driver interface
10-11 13:48:11.811 10230 10230 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:11.812 10230 10230 D ActivityThread: Added TimaKeyStore provider
10-11 13:48:11.812 10214 10214 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
10-11 13:48:11.812  3701  4913 D ActivityManager: cleanUpApplicationRecord -- 9362
10-11 13:48:11.812 10214 10214 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
10-11 13:48:11.812  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10214
10-11 13:48:11.812  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
10-11 13:48:11.812 10214 10214 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
10-11 13:48:11.812 10214 10214 I wpa_supplicant: ssSupport state is = 1
10-11 13:48:11.812  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,10-11 13:48:11.816  4803  6438 D ForegroundUtils: could not check pending caller
10-11 13:48:11.817  3701  4921 I ActivityManager: DSS on for com.rockwellautomation.AppPlatformP2P and scale is 1.0
,10-11 13:48:11.846 10230 10230 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-11 13:48:11.866 10214 10214 I wpa_supplicant: rfkill: Cannot get wiphy information
,10-11 13:48:11.868 10230 10230 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:11.881 10214 10214 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,10-11 13:48:11.891  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.892  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.892  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.892  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.892  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.893  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.893  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.894  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.894  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.895  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.938 10230 10230 D jxcore_app_log: JniHelper::setJavaVM(0xe73b4000), pthread_self() = -359676620
10-11 13:48:11.938 10230 10230 E JX-Cordova: JXcore wasn't initialized yet
,10-11 13:48:11.951  3701  4887 I ActivityManager: KPU : put [com.samsung.android.sm.devicesecurity] : 26712 K
10-11 13:48:11.951  3701  4887 I ActivityManager: Killing 7155:com.samsung.android.sm.devicesecurity/5012 (adj 906): DHA:empty #33
,10-11 13:48:11.961  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.962  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.962  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.963  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.963  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.964  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.964  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.964  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.965  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.965  3701  4923 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.978  9856  9856 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
10-11 13:48:11.978  9856  9856 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,10-11 13:48:11.991  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:11.991  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.992  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.992  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.992  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.992  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.992  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.992  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.992  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.992  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:11.995  3701  4913 D ActivityManager: cleanUpApplicationRecord -- 7155
,10-11 13:48:11.996  4803  4817 D ForegroundUtils: could not check pending caller
,10-11 13:48:12.009  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.009  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.010  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.010  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.010  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.010  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.010  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.010  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.010  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.011  3701  4915 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.021  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.021  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.021  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.021  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.021  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.021  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.022  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.022  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.022  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.022  3701  4180 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.030  9856  9856 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
10-11 13:48:12.031  9856  9856 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,10-11 13:48:12.041  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.042  3701  4540 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.053  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.054  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.054  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.054  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.054  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.054  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.054  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.054  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.054  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.055  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.063  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.064  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.064  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.064  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.064  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.064  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.064  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.064  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.064  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.065  3701  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.307  3701  3728 D WifiService: setWifiEnabled: true pid=9789, uid=10033
10-11 13:48:12.308  3701  3728 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-11 13:48:12.309  3701  3728 D WifiControlHistoryProvider: query
,10-11 13:48:12.322  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:12.322  3701  3728 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-11 13:48:12.324  3701  3728 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:12.326  3701  3728 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-11 13:48:12.334  3701  3728 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-11 13:48:12.335  3701  3728 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-11 13:48:12.499  3701  3769 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=203609 mStackState=3 mControllerTxTimeMs=0 mControllerTxTimePerLevelMs=[] mControllerRxTimeMs=0 mControllerIdleTimeMs=0 mControllerEnergyUsed=0 }
,10-11 13:48:12.523 10214 10214 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,10-11 13:48:12.526  3701  3930 I WifiConnectivityManager: User band preference: 0
,10-11 13:48:12.529  3701  3930 D WifiConfigManager: Loading config and enabling all networks 
,10-11 13:48:12.542  3701  3930 D WifiConfigStore: readNetwork skipInternetCheck
,10-11 13:48:12.568  3701  3930 D WifiConfigStore: readNetwork skipInternetCheck
,10-11 13:48:12.588  3701  3930 D WifiConfigStore: readNetwork skipInternetCheck
,10-11 13:48:12.615  3701  3930 D WifiConfigStore: readNetwork skipInternetCheck
,10-11 13:48:12.643  3701  3930 D WifiConfigStore: readNetwork skipInternetCheck
,10-11 13:48:12.668  3701  3930 D WifiConfigStore: readNetwork skipInternetCheck
,10-11 13:48:12.697  3701  3930 W WifiNetworkHistory: Upgrading network 4 to android.uid.system:1000
,10-11 13:48:12.698  3701  3930 W WifiNetworkHistory: Upgrading network 0 to android.uid.system:1000
10-11 13:48:12.699  3701  3930 W WifiNetworkHistory: Upgrading network 1 to android.uid.system:1000
10-11 13:48:12.700  3701  3930 W WifiNetworkHistory: Upgrading network 5 to android.uid.system:1000
,10-11 13:48:12.701  3701  3930 W WifiNetworkHistory: Upgrading network 2 to android.uid.system:1000
10-11 13:48:12.702  3701  3930 W WifiNetworkHistory: Upgrading network 3 to android.uid.system:1000
,10-11 13:48:12.705  3701  3930 D WifiConfigManager: loaded 0 passpoint configs
,10-11 13:48:12.713  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,10-11 13:48:12.714  3701  3701 D WifiHs20Service: reason: 2
10-11 13:48:12.714  3701  3930 D WifiNative-wlan0: callSECApiBoolean - ID [301]
10-11 13:48:12.714  3701  3956 I WifiHs20Service: Message received 5014
10-11 13:48:12.714  3701  3956 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
10-11 13:48:12.714  3701  3956 E WifiHs20Service: The changed config is NULL
10-11 13:48:12.715 10214 10214 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,10-11 13:48:12.731  3701  3930 D WifiNative-wlan0: callSECApiInt - ID [65]
,10-11 13:48:12.735  3701  3701 D WifiController: [FCC]setFccChannel() is called !!!
,10-11 13:48:12.735  3701  3701 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,10-11 13:48:12.735  3701  3701 D WifiStateMachine: setFccChannel: channel = 0
10-11 13:48:12.736  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
10-11 13:48:12.737  3701  3955 D HS20StateMachine: WIFI_STATE_ENABLED
10-11 13:48:12.737  3701  3955 D HS20StateMachine: reloadCredentialsToSupplicant
10-11 13:48:12.737  3701  3955 D WifiHs20DBHandler: getCredentialIds
10-11 13:48:12.737  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
10-11 13:48:12.738  3701  3956 I WifiHs20Service: Message received 5011
,10-11 13:48:12.740  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=3 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:12.745  3701  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,10-11 13:48:12.745  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:12.748  3701  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,10-11 13:48:12.750  3701  3701 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
10-11 13:48:12.750  3701  4487 D SLocation: checkWifiInfo
10-11 13:48:12.750  3701  4487 W SLocation: No Active Data Connection
,10-11 13:48:12.753  3701  3930 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,10-11 13:48:12.753 10214 10214 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,10-11 13:48:12.757  9917  9917 D A2dpService: A2dpService - WIFI_STATE_ENABLED
10-11 13:48:12.757  9917  9917 I BluetoothA2dpServiceJni: Attempting to set busy level
,10-11 13:48:12.761  9789  9789 D BluetoothAdapter: STATE_ON
,10-11 13:48:12.765  9856  9856 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
10-11 13:48:12.765  9856  9856 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-11 13:48:12.765  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-11 13:48:12.766  3701  3955 D MountService: getExternalStorageMountMode : 1
,10-11 13:48:12.766  3701  3955 D MountService: getExternalStorageMountMode : 3
10-11 13:48:12.766  3701  3955 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10114, packageName : com.samsung.hs20provider
,10-11 13:48:12.769  9789  9789 D BluetoothAdapter: STATE_ON
,10-11 13:48:12.772  9789  9789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-11 13:48:12.791 10248 10248 E Zygote  : v2
10-11 13:48:12.791 10248 10248 I libpersona: KNOX_SDCARD checking this for 10114
10-11 13:48:12.791 10248 10248 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:12.792 10248 10248 E Zygote  : accessInfo : 0
,10-11 13:48:12.798  3701  3955 I ActivityManager: Start proc 10248:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,10-11 13:48:12.800  3701  3930 D WifiNative-HAL: Setting external_sim to 1
,10-11 13:48:12.801  3701  3930 D wifi    : setting dfs flag to true, 0x709f3efde0
10-11 13:48:12.801 10248 10248 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-11 13:48:12.802  3701  3930 D WifiStateMachine: Setting OUI to DA-A1-19
,10-11 13:48:12.802  3701  3930 D wifi    : setting scan oui 0x709f3efde0
10-11 13:48:12.802  3701  3930 D WifiHAL : Sending mac address OUI
10-11 13:48:12.802  9856  9856 D SecurityLogAgent: NetworkReceiver : SendSecurityReport is off
10-11 13:48:12.803 10248 10248 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
10-11 13:48:12.804  3701  3930 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
10-11 13:48:12.804  3701  3930 E WifiStateMachine: SupplicantStarted - enter() isAirplaneModeEnabled !!  
10-11 13:48:12.804  3701  3930 D WifiCountryCode: [setCountryCodeNative] Default CSC Country Code : PL
,10-11 13:48:12.811  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.811  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.811  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.812  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.813  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.814  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.815  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.815  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.816  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.816  3701  3729 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.828  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.828  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.829  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.829  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.829  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.829  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.829  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.829  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.829  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.829  3701  4913 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.840 10248 10248 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:12.841  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.841 10248 10248 D ActivityThread: Added TimaKeyStore provider
10-11 13:48:12.842  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.842  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.842  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.843  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.843  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.844  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.844  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.844  3701  4928 I ActivityManager: DSS on for com.samsung.hs20provider and scale is 1.0
10-11 13:48:12.844  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
10-11 13:48:12.844  3701  4541 W NetworkIdentity: Active mobile network without subscriber!
,10-11 13:48:12.849  9789  9890 D BluetoothAdapter: STATE_ON
,10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-11 13:48:12.853  9789  9890 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-11 13:48:12.855  9789  9853 D BluetoothAdapter: enable()
,10-11 13:48:12.859 10214 10214 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,10-11 13:48:12.861  9917  9928 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-11 13:48:12.861  3701  3930 D WifiCountryCode: Succeeded to set country code to: PL
,10-11 13:48:12.861  9917  9928 D AdapterProvider: query
10-11 13:48:12.861  3701  3930 D wifi    : android_net_wifi_get_firmware_version = 0x709f3efde0
10-11 13:48:12.861  3701  3930 E WifiHAL : Failed to register debug response; result = -95
10-11 13:48:12.861  3701  3930 E wifi    : Fail to get Firmware version
10-11 13:48:12.862  3701  3930 D wifi    : android_net_wifi_get_driver_version = 0x709f3efde0
10-11 13:48:12.862  3701  3930 E WifiHAL : Failed to register debug response; result = -95
10-11 13:48:12.862  3701  3930 E wifi    : Fail to get driver version
10-11 13:48:12.862  3701  3930 D wifi    : android_net_wifi_set_log_handler = 0x709f3efde0
10-11 13:48:12.862  3701  3930 D wifi    : android_net_wifi_get_ring_buffer_status = 0x709f3efde0
10-11 13:48:12.862  3701  3930 E WifiHAL : Failed to register debug response; result = -95
10-11 13:48:12.862  3701  3930 E WifiLogger: no ring buffers found
10-11 13:48:12.862  3701  3930 D WifiHAL : Start get packet fate command
10-11 13:48:12.862  3701  3930 D WifiHAL : createRequest Monitor packet fate request
10-11 13:48:12.862  3701  3930 E WifiHAL : Failed to register get pkt fate response; result = -95
10-11 13:48:12.862  3701  3930 E WifiLogger: Failed to start packet fate monitoring
10-11 13:48:12.869  9917  9928 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@3562b32
10-11 13:48:12.869  3701  4016 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
,10-11 13:48:12.871  9917  9928 D BluetoothAdapterService: updateEvent - already set, update
,10-11 13:48:12.871  9917  9928 W BluetoothAdapterService: updateEvent - alreadySet is true
10-11 13:48:12.872  9917  9928 D AdapterProvider: update
10-11 13:48:12.876 10248 10248 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,10-11 13:48:12.878  9917  9928 E BluetoothAdapterService: updateEvent - update success 1
,10-11 13:48:12.880  9789  9853 D BluetoothAdapter: enable(): BT is already enabled..!
,10-11 13:48:12.885  3701  3728 D WifiService: setWifiEnabled: true pid=9789, uid=10033
10-11 13:48:12.885  3701  3728 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-11 13:48:12.886  3701  3728 D WifiControlHistoryProvider: query
,10-11 13:48:12.891 10248 10248 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:12.892  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:12.893  3701  3728 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-11 13:48:12.896  3701  3728 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:12.897  3701  3728 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-11 13:48:12.901  3701  3728 I WifiService: Wi-Fi Sharing settings has not been accessed
10-11 13:48:12.902  3701  3925 D WifiP2pService: P2pDisabledState{ what=131203 }
10-11 13:48:12.902  3701  3930 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-11 13:48:12.902  3701  3930 I WifiConnectivityManager: Set WiFi enabled
10-11 13:48:12.902  3701  3930 E WifiStateMachine: ConnectModeState - enter !! - mIsSupportGeofence !!
,10-11 13:48:12.903  3701  3957 I WifiScanningService: wifi driver loaded with scan capabilities: max buckets=16
,10-11 13:48:12.904  3701  3930 D WifiStateMachine: Remembered scan first is enabled
10-11 13:48:12.905  3701  3701 I WifiStateMachine: initGeofence
10-11 13:48:12.905  3701  3930 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@f31347a
10-11 13:48:12.905  3294  3786 D CommandListener: Setting iface cfg
10-11 13:48:12.905  3294  3786 D CommandListener: Trying to bring up p2p0
10-11 13:48:12.906  3701  3930 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
10-11 13:48:12.906  3701  3728 D WifiService: unRegisterForSContext() : skip - it does not registered.
10-11 13:48:12.906  3294  3778 D Netd    : Iface p2p0 link up
10-11 13:48:12.907  3701  3925 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
10-11 13:48:12.907  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-11 13:48:12.908  9789  9853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-11 13:48:12.908  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-11 13:48:12.908  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-11 13:48:12.908  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-11 13:48:12.908  3701  3925 D SecContentProvider: insert(), uri = 2
10-11 13:48:12.908  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4521d4c removed from the list
10-11 13:48:12.908  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4521d4c removed from the list
10-11 13:48:12.908  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-11 13:48:12.908  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@abd195 removed from the list
10-11 13:48:12.908  9789  9853 D io.jxcore.node.ConnectivityMonitor: stop
10-11 13:48:12.908  9789  9853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-11 13:48:12.908  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,10-11 13:48:12.908  3701  3796 D Tethering: interfaceLinkStateChanged p2p0, true
10-11 13:48:12.909  3701  3796 D Tethering: interfaceStatusChanged p2p0, true
10-11 13:48:12.910  3701  3930 E wifi    : failed to get channel list : -95
10-11 13:48:12.910  3701  3930 D WifiConfigManager: getChannelsForBand(WifiScanner.WIFI_BAND_24_GHZ) is null. So set default 2.4GHz 14 channels.
10-11 13:48:12.910  9789  9853 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
10-11 13:48:12.912 10214 10214 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-11 13:48:12.912 10214 10214 I wpa_supplicant: P2P: Current p2p state = IDLE
10-11 13:48:12.914  3701  3930 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20171011T134820 - CU:1000/CP:3701
10-11 13:48:12.914  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134820, SetElapsed=212046, nowELAPSED=204051
10-11 13:48:12.914  3701  3925 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:12.915  3701  3925 D WifiP2pService: P2pEnablingState
10-11 13:48:12.915  9789 10261 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
10-11 13:48:12.915  9789 10261 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
10-11 13:48:12.918  3701  3925 D WifiP2pService: P2pEnablingState{ what=147457 }
10-11 13:48:12.918 10214 10214 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
10-11 13:48:12.918  3701  3957 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T134827 - CU:1000/CP:3701
10-11 13:48:12.918  3701  3925 D WifiP2pService: P2p socket connection successful
10-11 13:48:12.920  3294  3781 D EnterpriseController: netId is 0
10-11 13:48:12.921  3294  3781 D Netd    : getNetworkForDns: using netid 0 for uid 10033
10-11 13:48:12.921  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
10-11 13:48:12.922  3701  3925 D WifiP2pService: P2pEnabledState
10-11 13:48:12.923  3701  3925 D SecContentProvider: insert(), uri = 2
10-11 13:48:12.923  3701  3930 D WifiStateMachine: setFccChannelNative: channel = 0
10-11 13:48:12.924  3701  3930 D WifiNative-wlan0: callSECApiInt - ID [230]
,10-11 13:48:12.925  9789 10263 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
10-11 13:48:12.925  9789 10261 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
10-11 13:48:12.927  3701  3925 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:12.927  9789 10261 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-11 13:48:12.928  9789 10263 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-11 13:48:12.928  9789 10261 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:12.928  9789 10263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:12.928  9789 10261 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:12.928  9789 10263 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:12.929  9789 10261 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
10-11 13:48:12.929  9789 10263 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-11 13:48:12.929  3701  3925 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 220, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread:  id: 74
10-11 13:48:12.930  3701  3960 D ConnectivityService: ignoring duplicate network state non-change
10-11 13:48:12.930  9789 10266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 219, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.930  9789 10266 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:12.930  9789 10266 D io.jxcore.node.StreamCopyingThread:  id: 75
10-11 13:48:12.930  3701  3798 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 220, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread:  id: 74
10-11 13:48:12.930  3701  3798 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread:  id: 74
10-11 13:48:12.930  3701  3798 D WifiDisplayController: disconnect
10-11 13:48:12.930  9789 10267 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:12.931  3701  3798 D WifiDisplayAdapter: onFeatureStateChanged empty
10-11 13:48:12.931  9789 10267 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:12.931  3701  3798 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
10-11 13:48:12.931  9789 10265 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 218, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-,11 13:48:12.931  9789 10265 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:12.931  9789 10265 D io.jxcore.node.StreamCopyingThread:  id: 74
,10-11 13:48:12.931  9789 10268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 221, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.931  9789 10268 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:12.931  9789 10268 D io.jxcore.node.StreamCopyingThread:  id: 75
10-11 13:48:12.931  9789 10268 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 221, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.931  9789 10268 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:12.931  9789 10268 D io.jxcore.node.StreamCopyingThread:  id: 75
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread:  id: 75
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:12.932  9789 10268 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-11 13:48:12.932  9789 10266 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 219, thread name: IncomingSocketThread/Sender): Socket closed
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 221, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:12.932  9789 10268 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-11 13:48:12.932  9789 10266 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 219, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.932  9789 10266 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:12.932  9789 10266 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-11 13:48:12.932  9789 10266 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-11 13:48:12.932  9789 10266 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-11 13:48:12.932  9789 10266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 219, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.932  9789 10266 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:12.932  9789 10266 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-11 13:48:12.933  9789 10267 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:12.933  9789 10267 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:12.933  9789 10267 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:12.933  9789 10267 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-11 13:48:12.933  9789 10267 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 220, name: OutgoingSocketThread/Recei,ver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.933  9789 10267 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:12.933  9789 10267 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-11 13:48:12.934  9789 10265 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 218, thread name: OutgoingSocketThread/Sender): Socket closed
10-11 13:48:12.934  9789 10265 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 218, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.934  9789 10265 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:12.934  9789 10265 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-11 13:48:12.934  9789 10265 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-11 13:48:12.934  9789 10265 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-11 13:48:12.934  9789 10265 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 218, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:12.934  9789 10265 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:12.934  9789 10265 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-11 13:48:12.938 10214 10214 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
10-11 13:48:12.938  3701  3798 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
10-11 13:48:12.941 10214 10214 I wpa_supplicant: P2P: Set Samsung Discovery name = 
10-11 13:48:12.943 10248 10260 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
10-11 13:48:12.944 10248 10260 D HotspotProvider: CREDENTIAL
10-11 13:48:12.944 10248 10260 D HotspotProvider: No prepend tags
10-11 13:48:12.946  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
10-11 13:48:12.949 10199 10199 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
10-11 13:48:12.949 10199 10199 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
10-11 13:48:12.949 10199 10199 D FileShare: Outbound.stopDelayTimer - 
10-11 13:48:12.956  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
10-11 13:48:12.960  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:48:12.960  4044  4230 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,10-11 13:48:12.965  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:12.966  3701  3930 D WifiNative-wlan0: callSECApiVoid - ID [311]
10-11 13:48:12.968  3701  3955 D HS20StateMachine: updateNumOfHS20Cred, numOfHS20Cred = 1
10-11 13:48:12.968  3701  3955 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
10-11 13:48:12.968  3701  3955 D HS20StateMachine: enter : DiscoveringState
,10-11 13:48:12.979  3701  3701 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
10-11 13:48:12.979  3701  3701 D SLocation: system
,10-11 13:48:12.979  3701  3701 D SLocation: startGeofence ID = 1
,10-11 13:48:12.985  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 2ms lastUpdatedAfter : 5237 ms mFlush_time_threasold : 2000 mCurrentSize : 184
,10-11 13:48:12.986  3701  3925 E WifiP2pService: Failed to set my phone number info into probe response
,10-11 13:48:12.989  3701  3925 D WifiNative-HAL: p2pGetDeviceAddress
10-11 13:48:12.989  3701  3925 D WifiNative-HAL: p2pGetDeviceAddress returning 4e:66:41:a9:15:41
,10-11 13:48:12.990  3701  3925 D WifiP2pService: DeviceAddress: 4e:15:41
,10-11 13:48:12.991  3701  3798 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:15:41
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  primary type: 10-0050F204-5
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  secondary type: null
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  wps: 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  grpcapab: 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  devcapab: 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  status: 3
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  WFD CtrlPort: 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  WFD MaxThroughput: 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  groupownerAddress: null
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  GOdeviceName: null
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  interfaceAddress: 
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  SConnectInfo : null
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  contactInfoHash : null
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  ssDevInfo : 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  iconIdx : 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  semSamsungDeviceType : 0
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  serviceData : null
10-11 13:48:12.991  3701  3798 D WifiDisplayController:  fw_invite : 0
,10-11 13:48:12.999  3701  3925 D WifiP2pService: sending p2p persistent groups changed broadcast
10-11 13:48:12.999  3701  3925 D WifiP2pService: InactiveState
,10-11 13:48:12.999  3701  3925 D WifiP2pService: InactiveState{ what=143376 }
10-11 13:48:12.999  3701  3925 D WifiP2pService: P2pEnabledState{ what=143376 }
10-11 13:48:12.999  3701  3925 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,10-11 13:48:13.010  3701  3701 D SLocation: addReceiver type4
10-11 13:48:13.010  3701  3701 D SLocation: already exsit record!
,10-11 13:48:13.041  3701  3701 D SLocation: setPendingIntent
10-11 13:48:13.041  3701  3701 D SLocation: setStatus ID = 1 / status = 3
,10-11 13:48:13.117  3701  3701 D SLocation: geofence id (1) detected : 0
,10-11 13:48:13.118  3701  3701 D WifiStateMachine: startGeofence() - id : 1
,10-11 13:48:13.127  4044  4230 D TelephonyProvider: query: match = 7
,10-11 13:48:13.150  3701  3701 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
10-11 13:48:13.151  3701  3701 D SLocation: system
,10-11 13:48:13.151  3701  3701 D SLocation: startGeofence ID = 2
,10-11 13:48:13.177  3701  3701 D SLocation: addReceiver type4
10-11 13:48:13.177  3701  3701 D SLocation: already exsit record!
,10-11 13:48:13.203  3701  3701 D SLocation: setPendingIntent
10-11 13:48:13.204  3701  3701 D SLocation: setStatus ID = 2 / status = 3
,10-11 13:48:13.275  3701  3701 D SLocation: geofence id (1) detected : 0
,10-11 13:48:13.345  3701  3701 D SLocation: geofence id (2) detected : 0
,10-11 13:48:13.346  3701  3701 D WifiStateMachine: startGeofence() - id : 2
10-11 13:48:13.346  3701  3701 D RttService: SCAN_AVAILABLE : 3
10-11 13:48:13.347  3701  3959 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-11 13:48:13.351  3701  3701 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
10-11 13:48:13.351  3701  3701 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,10-11 13:48:13.354  3701  3701 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,10-11 13:48:13.361  3701  3701 D SLocation: PendingIntent onSendFinished id:1
10-11 13:48:13.361  3701  3701 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
10-11 13:48:13.361  3701  3701 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,10-11 13:48:13.365  3701  3701 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,10-11 13:48:13.371  3701  3701 D SLocation: PendingIntent onSendFinished id:1
10-11 13:48:13.371  3701  3701 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [2], direction [0]
10-11 13:48:13.371  3701  3701 D WifiStateMachine: BroadcastReceiver() - configKey : "ktwtestwifi"WPA_EAP IN. Reduce scan max interval
,10-11 13:48:13.374  3701  3701 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,10-11 13:48:13.381  3701  3701 D SLocation: PendingIntent onSendFinished id:2
,10-11 13:48:13.494  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:48:13.496 10214 10214 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
,10-11 13:48:13.497  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
,10-11 13:48:13.498  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:13.501  3701  3957 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@c15177f
,10-11 13:48:13.531  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-11 13:48:13.545  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:13.557  3701  3930 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=4 roam=false
,10-11 13:48:13.559  3701  3930 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=4
,10-11 13:48:13.574  3701  3930 D WifiConfigStore: saveNetwork skipInternetCheck
,10-11 13:48:13.584  3701  3930 D WifiConfigStore: readNetwork skipInternetCheck
,10-11 13:48:13.599  3701 10269 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
10-11 13:48:13.599  3701 10269 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
,10-11 13:48:13.600  3701 10269 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
10-11 13:48:13.600  3701 10269 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
10-11 13:48:13.601  3701 10269 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
,10-11 13:48:13.601  3701 10269 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
10-11 13:48:13.602  3701 10269 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: true
10-11 13:48:13.602  3701 10269 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
,10-11 13:48:13.603  3701 10269 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
10-11 13:48:13.603  3701 10269 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
,10-11 13:48:13.604  3701 10269 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
10-11 13:48:13.604  3701 10269 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,10-11 13:48:13.606  3701  3930 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=4
10-11 13:48:13.607  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
10-11 13:48:13.607  3701  3701 D WifiHs20Service: reason: 2
,10-11 13:48:13.607  3701  3956 I WifiHs20Service: Message received 5014
10-11 13:48:13.607  3701  3956 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,10-11 13:48:13.610  3701 10270 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
10-11 13:48:13.610  3701 10270 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
,10-11 13:48:13.611  3701 10270 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
10-11 13:48:13.611  3701 10270 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
10-11 13:48:13.611 10214 10214 I wpa_supplicant: Trying to associate with F4.E6.C2 (SSID='NG700' freq=2472 MHz)
10-11 13:48:13.611  3701 10270 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
10-11 13:48:13.611  3701 10270 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
10-11 13:48:13.612  3701 10270 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: true
10-11 13:48:13.612  3701 10270 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
10-11 13:48:13.612  3701  3930 D SecContentProvider: insert(), uri = 2
10-11 13:48:13.612  3701 10270 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
10-11 13:48:13.612  3701 10270 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
10-11 13:48:13.613  3701 10270 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
10-11 13:48:13.613  3701 10270 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
10-11 13:48:13.613  3701  3930 D SecContentProvider: called from android.uid.system:1000
,10-11 13:48:13.628  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-11 13:48:13.637  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:13.743  3294  3778 D Netd    : Iface wlan0 link up
10-11 13:48:13.744  3294  3778 D Netd    : Iface wlan0 link up
10-11 13:48:13.744  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:48:13.747  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:13.747  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
10-11 13:48:13.749  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:13.750  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:13.752  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:13.752  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:13.759 10214 10214 I wpa_supplicant: Associated with F4.E6.C2
,10-11 13:48:13.760 10214 10214 I wpa_supplicant: wlan0: CTRL-EVENT-SUBNET-STATUS-UPDATE status=0
,10-11 13:48:13.772  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-11 13:48:13.784  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-11 13:48:13.792 10214 10214 I wpa_supplicant: WPA: Key negotiation completed with F4.E6.C2 [PTK=CCMP GTK=CCMP]
,10-11 13:48:13.793 10214 10214 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.E6.C2 completed [id=4 id_str=%7B%22creatorUid%22%3A%221000%22%2C%22configKey%22%3A%22%5C%22NG700%5C%22WPA_PSK%22%7D]
10-11 13:48:13.793  3294  3778 D Netd    : Iface wlan0 link up
10-11 13:48:13.795  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-11 13:48:13.797  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:13.797  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:13.804  3701  3930 D WifiNative-wlan0: callSECApiVoid - ID [50]
,10-11 13:48:13.807  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:13.814  3701  3930 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@a22809e
,10-11 13:48:13.815  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T140508, SetElapsed=1219968, nowELAPSED=204952
10-11 13:48:13.816  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-11 13:48:13.817  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-11 13:48:13.817  3701  3956 I WifiHs20Service: Message received 5007
,10-11 13:48:13.818  3701  3930 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: mIsSupportAdvancedCaptivePortal is true
10-11 13:48:13.819  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=69632 obj=com.android.internal.util.AsyncChannel@e74415f target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:13.819  3701 10271 D NetworkMonitor: Async - Half connection with WWSM established
10-11 13:48:13.819  3701  3930 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-11 13:48:13.820  3701  4016 D WifiWatchdogStateMachine: Async - Half connection with NetworkMonitor established
10-11 13:48:13.820  3701  4016 D WifiWatchdogStateMachine: Async - Full connection with NetworkMonitor established
,10-11 13:48:13.820  3701  3960 D ConnectivityService: Got NetworkAgent Messenger
,10-11 13:48:13.821  3701  3960 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-11 13:48:13.821  3701  3960 D ConnectivityService: NetworkAgent connected
10-11 13:48:13.821  3701  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
10-11 13:48:13.825  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
10-11 13:48:13.826  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:13.830  9917  9917 D BluetoothUtils: readSalesCode :: sales code is XEO
,10-11 13:48:13.835  3701  3925 D WifiP2pService: InactiveState{ what=143375 }
10-11 13:48:13.835  3701  3925 D WifiP2pService: P2pEnabledState{ what=143375 }
10-11 13:48:13.836  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-11 13:48:13.838  3701  3930 D WifiHAL : Getting APF capabilities, halHandle = 0x709f3efde0
10-11 13:48:13.838  3701  3930 I WifiHAL : 
10-11 13:48:13.838  3701  3930 I WifiHAL : createRequest: APF get capabilities request
10-11 13:48:13.840  3701  3930 D WifiHAL : In SetAPFCommand::handleResponse
10-11 13:48:13.840  3701  3930 D WifiHAL : Id = 0, subcmd = 0, len = 16
10-11 13:48:13.840  3701  3930 D WifiHAL : Response recieved for get packet filter capabilities command
10-11 13:48:13.840  3701  3930 I WifiHAL : APF version is 2
10-11 13:48:13.840  3701  3930 I WifiHAL : APF max len is 2048
10-11 13:48:13.840  3701  3930 I WifiHAL : Done!
10-11 13:48:13.840  3701  3930 D WifiHAL : Getting APF capability, version = 2, max_len = 2048
10-11 13:48:13.841  3701  3930 D wifi    : APF version supported: 2
10-11 13:48:13.841  3701  3930 D wifi    : Maximum APF program size: 2048
10-11 13:48:13.845  3701  3930 D WifiStateMachine: Start Dhcp Watchdog 2
,10-11 13:48:13.851 10067 10067 I [RBL] ServiceReceiver: @onReceive - rawData : null
,10-11 13:48:13.855  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-11 13:48:13.872  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:13.880 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,10-11 13:48:13.880 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-11 13:48:13.880 10082 10082 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
10-11 13:48:13.881 10082 10082 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,10-11 13:48:13.887  3701  3930 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true)
,10-11 13:48:13.887  3701  3960 D ConnectivityService: ignoring duplicate network state non-change
10-11 13:48:13.887  3701  3930 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true) returned: -95
10-11 13:48:13.887  3701  3960 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-11 13:48:13.887  3701  3960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
10-11 13:48:13.887  3701  3960 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
10-11 13:48:13.887  3701  3930 D WifiHAL : Setting APF program, halHandle = 0x709f3efde0
10-11 13:48:13.887  3701  3930 I WifiHAL : 
10-11 13:48:13.887  3701  3930 I WifiHAL : createRequest: APF set program request
10-11 13:48:13.888  3701  3930 I WifiHAL : Done!
,10-11 13:48:13.889  3701  3930 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
10-11 13:48:13.890  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:13.894  3701 10272 D ApfFilter: (wlan0): begin monitoring
,10-11 13:48:13.897 10096 10096 I PhoneErrorReceiver: onReceive
,10-11 13:48:13.899 10214 10214 I wpa_supplicant: Interworking: Fetch ANQP after connect
,10-11 13:48:13.909  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-11 13:48:13.913 10110 10110 I usagelog: received in receiver
10-11 13:48:13.913 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
10-11 13:48:13.913 10110 10110 I KnoxUsageLogPro: premStatus:2
10-11 13:48:13.915 10110 10110 I KnoxUsageLogPro: isEulaShown : false
10-11 13:48:13.915 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,10-11 13:48:13.938  3701  3935 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171011T134849 - CU:1000/CP:3701
10-11 13:48:13.938  3701  3935 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134849, SetElapsed=241073, nowELAPSED=205075
,10-11 13:48:13.940  3701  3960 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
10-11 13:48:13.940  3701  4016 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,10-11 13:48:13.941  3701  4016 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-11 13:48:13.941  3701  4016 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
10-11 13:48:13.941  3701  4016 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,10-11 13:48:13.942  3701  4016 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,10-11 13:48:14.012  3701  3935 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171011T134850 - CU:1000/CP:3701
,10-11 13:48:14.120  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=start target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-11 13:48:14.121  3701  3925 D WifiP2pService: InactiveState{ what=143375 }
10-11 13:48:14.121  3701  3925 D WifiP2pService: P2pEnabledState{ what=143375 }
,10-11 13:48:14.127  3701 10273 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171011T134816 - CU:1000/CP:3701
10-11 13:48:14.127  3701 10273 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134816, SetElapsed=207344, nowELAPSED=205264
,10-11 13:48:15.102  3701  3927 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:48:15.274  3701  4918 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{c114186: PendingIntentRecord{8f3ea47 com.google.android.gms broadcastIntent}}
,10-11 13:48:15.655  5202  5211 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,10-11 13:48:16.065  4648  4648 D io_stats: !@   8,0 r 26061 2311472 w 5307 209956 d 686 75080 f 2118 2118 iot 12040 11026 th 473528 0 0 pt 0 inp 0 0 207.200
,10-11 13:48:16.208  3701  3864 D SamsungAlarmManager: Expired : 4
,10-11 13:48:16.209  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134849, SetElapsed=241073, nowELAPSED=207345
10-11 13:48:16.209  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@4428261 alarm=Alarm{b269274 type 2 when 207344 android}
,10-11 13:48:16.222  3701 10273 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171011T134820 - CU:1000/CP:3701
10-11 13:48:16.222  3701 10273 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134820, SetElapsed=211592, nowELAPSED=207359
,10-11 13:48:16.239  3701 10273 D DhcpClient: Got pending lease: IP address 192.168.1.102/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
10-11 13:48:16.239  3701 10273 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@9c3e39d
,10-11 13:48:16.242  3701 10273 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134849, SetElapsed=241073, nowELAPSED=207379
,10-11 13:48:16.248  3701 10273 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171011T134834 - CU:1000/CP:3701
10-11 13:48:16.249  3701 10273 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134834, SetElapsed=225379, nowELAPSED=207386
,10-11 13:48:16.261  3701 10273 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171011T134818 - CU:1000/CP:3701
10-11 13:48:16.262  3701 10273 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134818, SetElapsed=209250, nowELAPSED=207398
,10-11 13:48:16.272  3701 10273 D DhcpClient: Confirmed lease: IP address 192.168.1.102/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
,10-11 13:48:16.273  3701 10273 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@d5461e0
10-11 13:48:16.273  3701  3935 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@b60926b
,10-11 13:48:16.276  3701 10273 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134834, SetElapsed=225379, nowELAPSED=207413
,10-11 13:48:16.277  3701 10273 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@f7ae3e3
10-11 13:48:16.279  3701 10273 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134849, SetElapsed=241073, nowELAPSED=207415
10-11 13:48:16.279  3701  3925 D WifiP2pService: InactiveState{ what=143375 }
10-11 13:48:16.279  3701  3925 D WifiP2pService: P2pEnabledState{ what=143375 }
,10-11 13:48:16.282  3294  3786 D CommandListener: Setting iface cfg
,10-11 13:48:16.286  3701  4016 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-11 13:48:16.287  3701  3960 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-11 13:48:16.289  3701  4016 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
10-11 13:48:16.290  3701  4016 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-11 13:48:16.290  3701  4016 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
10-11 13:48:16.291  3701  4016 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-11 13:48:16.291  3701  3960 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
10-11 13:48:16.292  3701  4016 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-11 13:48:16.293  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-11 13:48:16.294  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-11 13:48:16.294  3701  3935 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@94ca3ba
10-11 13:48:16.294  3701  3956 I WifiHs20Service: Message received 5007
10-11 13:48:16.295  3701  3930 D WifiHAL : Setting APF program, halHandle = 0x709f3efde0
10-11 13:48:16.295  3701  3930 I WifiHAL : 
10-11 13:48:16.295  3701  3930 I WifiHAL : createRequest: APF set program request
10-11 13:48:16.295  3701  3935 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T140508, SetElapsed=1219968, nowELAPSED=207432
10-11 13:48:16.296  3701  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,10-11 13:48:16.297  3701  3930 I WifiHAL : Done!
,10-11 13:48:16.298  3701  3960 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
10-11 13:48:16.298  3701  3960 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-11 13:48:16.300  3701  3930 E WifiNative-HAL: setBssidBlacklist cmd 2 size 0
10-11 13:48:16.301  3701  3930 D wifi    : configure BSSID black list request [4] = 0x709f3efde0
10-11 13:48:16.301  3701  3930 D wifi    : Added 0 bssids
10-11 13:48:16.301  3701  4016 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
10-11 13:48:16.301  3701  3930 E WifiHAL : Failed to execute bssid blacklist request, result = -95
10-11 13:48:16.301  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
10-11 13:48:16.301  3701  3930 D WifiStateMachine: sendConnectedState - setManualConnection: false!
10-11 13:48:16.302  3701  4016 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-11 13:48:16.303  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:16.303  3701  4016 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-11 13:48:16.304  3701  4016 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-11 13:48:16.306  3701  3960 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-11 13:48:16.307  9917  9917 D BluetoothUtils: readSalesCode :: sales code is XEO
10-11 13:48:16.309  3701  3960 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
10-11 13:48:16.309  3701  3960 D ConnectivityService: Adding iface wlan0 to network 503
,10-11 13:48:16.317  3701 10273 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171011T193352 - CU:1000/CP:3701
,10-11 13:48:16.322  3701 10273 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T001816 - CU:1000/CP:3701
10-11 13:48:16.323  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:16.330  3701  3930 D SecContentProvider: insert(), uri = 2
10-11 13:48:16.331 10067 10067 I [RBL] ServiceReceiver: @onReceive - rawData : null
,10-11 13:48:16.331  3701  3930 D SecContentProvider: called from android.uid.system:1000
10-11 13:48:16.332  3244  3244 E audit   : type=1320 audit(1507722496.316:546): 
,10-11 13:48:16.333  3701  3930 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-11 13:48:16.334  3701 10273 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T014816 - CU:1000/CP:3701
10-11 13:48:16.334  3701 10273 D DhcpClient: Scheduling renewal in 20735s
10-11 13:48:16.334  3701 10273 D DhcpClient: Scheduling rebind in 37799s
10-11 13:48:16.334  3701 10273 D DhcpClient: Scheduling expiry in 43199s
10-11 13:48:16.335  3701  3930 I WifiConnectivityManager: scheduleWatchdogTimer
10-11 13:48:16.336  3701  3701 I WifiTrafficPoller: evaluateTrafficStatsPolling
10-11 13:48:16.337  3701  3701 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-11 13:48:16.337  3701  3701 D HS20StateMachine: SSID : "NG700"
10-11 13:48:16.337  3701  3701 D HS20StateMachine: NetId : 4
10-11 13:48:16.337  3701  3701 D HS20StateMachine: checkifOSUAP  null
10-11 13:48:16.338  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-11 13:48:16.338  3701  3956 I WifiHs20Service: Message received 5007
10-11 13:48:16.339  3701  4016 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,10-11 13:48:16.342  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,10-11 13:48:16.344  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:16.351  3244  3244 E audit   : type=1320 audit(1507722496.336:547): 
10-11 13:48:16.354  9917  9917 D BluetoothUtils: readSalesCode :: sales code is XEO
10-11 13:48:16.355  3701  3960 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,10-11 13:48:16.358  3701  3960 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
10-11 13:48:16.361  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T140107, SetElapsed=978385, nowELAPSED=207498
10-11 13:48:16.362  3701  3930 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T140816 - CU:1000/CP:3701
10-11 13:48:16.362  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T140816, SetElapsed=1407472, nowELAPSED=207499
,10-11 13:48:16.363  3701  3960 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
10-11 13:48:16.368  3701  3960 D ConnectivityService: Setting DNS servers for network 503 to [/192.168.1.1]
10-11 13:48:16.369  3294  3294 D ResolverController: DNSDBG::server[0] 192.168.1.1
10-11 13:48:16.369  3294  3294 D ResolverController: DNSDBG::netId 503 search_domain lan
10-11 13:48:16.369  3294  3294 D ResolverController: DNSDBG::netId 503 searchDomains lan
10-11 13:48:16.369  3294  3294 D ResolverController: DNSDBG::server[0] 192.168.1.1
10-11 13:48:16.371  3701  3930 D WifiStateMachine: isFindLocationId() - Location Id : 1
,10-11 13:48:16.377  3701  3930 D WifiGeofenceDBHelper: update() - 1*1507722496371
10-11 13:48:16.378 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
10-11 13:48:16.379 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-11 13:48:16.379 10082 10082 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
10-11 13:48:16.380 10082 10082 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
10-11 13:48:16.386  3701  3960 V NetworkStats: updateIfacesLocked()
10-11 13:48:16.386  3701  3960 V NetworkStats: performPollLocked(flags=0x1)
10-11 13:48:16.386  3701  3960 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:16.396  3701  3960 V NetworkStats: performPollLocked() took 11ms
10-11 13:48:16.396  3701  3960 D NtpTrustedTime: currentTimeMillis() cache hit
,10-11 13:48:16.400  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:16.400  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:16.400  3701  3960 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
10-11 13:48:16.400  3701  3960 D ConnectivityService: Not required to send intent.
10-11 13:48:16.401  3701  3960 V NetworkStats: updateIfacesLocked()
10-11 13:48:16.401  3701  3960 V NetworkStats: performPollLocked(flags=0x1)
10-11 13:48:16.401  3701  3960 D NtpTrustedTime: currentTimeMillis() cache hit
,10-11 13:48:16.407  3701  3960 V NetworkStats: performPollLocked() took 6ms
10-11 13:48:16.408  3701  3960 D NtpTrustedTime: currentTimeMillis() cache hit
,10-11 13:48:16.413  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:16.414  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:16.414  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:16.414  3701  3960 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
10-11 13:48:16.414  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
10-11 13:48:16.414  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: register CaptivePortalReceiver
10-11 13:48:16.414  3701  3960 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
10-11 13:48:16.414  3701  3960 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-11 13:48:16.414  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.414  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.414  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.414  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:16.414  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-11 13:48:16.415  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.415  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.415  3701  4016 D WifiWatchdogStateMachine: Connected - Move to CaptivePortalState
10-11 13:48:16.415  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.415  3701  3960 D ConnectivityService: currentScore = 0, newScore = 20
10-11 13:48:16.415  3701  3960 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
10-11 13:48:16.415  3701  3960 D ConnectivityService:    accepting network in place of null
,10-11 13:48:16.415  3701  3960 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.415  3701  3925 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.415  3701  3925 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:16.416  3701  3925 D WIFI_P2P: evalRequest
10-11 13:48:16.416  3701  3925 D WIFI_P2P:   done
10-11 13:48:16.416  3701  4025 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.416  3701  4025 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
10-11 13:48:16.416  3701  4025 D Ethernet: evalRequest
10-11 13:48:16.416  3701  4025 D Ethernet:   done
10-11 13:48:16.417  4044  4044 D PhoneSwitcherNetworkRequstListener: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.417  4044  4044 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
10-11 13:48:16.417  4044  4044 D PhoneSwitcherNetworkRequstListener: evalRequest
10-11 13:48:16.417  4044  4044 D PhoneSwitcherNetworkRequstListener:   done
10-11 13:48:16.418  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:16.418  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.418  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.418  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.418  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.419  3701  3960 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-11 13:48:16.421 10096 10096 I PhoneErrorReceiver: onReceive
,10-11 13:48:16.422  3701  4016 E WifiWatchdogStateMachine: current state: com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalState@3e44638
,10-11 13:48:16.433  3244  3244 E audit   : type=1320 audit(1507722496.416:548): 
,10-11 13:48:16.434  3701  3930 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
,10-11 13:48:16.437 10110 10110 I usagelog: received in receiver
10-11 13:48:16.437 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
10-11 13:48:16.437 10110 10110 I KnoxUsageLogPro: premStatus:2
10-11 13:48:16.438  3701  3930 D SLocation: system
10-11 13:48:16.438  3701  3930 D SLocation: startGeofence ID = 1
,10-11 13:48:16.438 10110 10110 I KnoxUsageLogPro: isEulaShown : false
10-11 13:48:16.438 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
10-11 13:48:16.439  3701  4016 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
10-11 13:48:16.439  3701  4016 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
10-11 13:48:16.440  3701  4016 D WifiWatchdogStateMachine: start to check Captive portal
,10-11 13:48:16.445  3244  3244 E audit   : type=1320 audit(1507722496.436:549): 
,10-11 13:48:16.446  3294  3786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-11 13:48:16.457  3244  3244 E audit   : type=1320 audit(1507722496.446:550): 
,10-11 13:48:16.460 10067 10067 I [RBL] ServiceReceiver: @onReceive - rawData : null
10-11 13:48:16.460 10067 10067 W [RBL] ServiceReceiver: @onReceive - NETWORK_STATE_CHANGED_ACTION
,10-11 13:48:16.469  3244  3244 E audit   : type=1320 audit(1507722496.456:551): 
,10-11 13:48:16.469  3294  3786 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-11 13:48:16.472  3701  3930 E SLocation: id 1 is already started
10-11 13:48:16.472  3701  3930 D WifiStateMachine: startGeofence() - id : 1, ERROR !!, mResult : -5
,10-11 13:48:16.473  3701  3930 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
10-11 13:48:16.473  3701  3930 D SLocation: system
10-11 13:48:16.473  3701  3930 D SLocation: startLearning ID = 1
10-11 13:48:16.473  3701  3930 D SLocation: setLearningStatus ID = 1 / status = true
10-11 13:48:16.474  3701  3930 D WifiStateMachine: ConnectedState - enter() - startLearning id : 1
10-11 13:48:16.474  3701  3930 D WifiStateMachine: ConnectedState()- id : 1,  startLearning Success !!
,10-11 13:48:16.476  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:16.482  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-11 13:48:16.482  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.483  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.484  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:16.485  4527  4612 D GeolocationController: WIFI : onAvailable
10-11 13:48:16.485  4527  4612 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [true]
10-11 13:48:16.485  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.485  3701  3797 D EntConnectivity: Not allowed due to - mEnabled false
10-11 13:48:16.486  4527  4616 D PdnController: handleMessage: what 105
10-11 13:48:16.487  3701  3930 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-11 13:48:16.487  4527  4616 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [true]
10-11 13:48:16.487  4527  4616 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [true]
10-11 13:48:16.487  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.487  3701  3930 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.488  3701  3930 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:16.488  3701  3930 D WIFI    : evalRequest
10-11 13:48:16.488  3701  3930 D WIFI    :   done
10-11 13:48:16.488  4527  4616 D ResipRegiMgr: handleMessage(): 3
10-11 13:48:16.488  3701  3930 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-11 13:48:16.488  4527  4616 D RegiMgrBase: handleMessage: what 3
10-11 13:48:16.488  3701  3930 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:16.488  3701  3930 D WIFI_UT : evalRequest
10-11 13:48:16.488  3701  3930 D WIFI_UT :   done
10-11 13:48:16.488  3701  3930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-11 13:48:16.489  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.489  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:16.489  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.489  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.490  3701  3960 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.494  3701  3960 D ConnectivityService: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
10-11 13:48:16.494  3701  3960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-11 13:48:16.500  3701  3797 D EntConnectivity: Not allowed due to - mEnabled false
,10-11 13:48:16.501  3701  3960 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
10-11 13:48:16.501  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.501  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:16.501  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:16.501  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:16.501  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:16.502  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.502  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.502 10067 10067 D [RBL] StoredRequest: @Oncreate
10-11 13:48:16.504  4527  4616 D RegiMgrBase: onNetworkEventChanged: new=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=true, isEpdgConnected=false]
10-11 13:48:16.504  4527  4616 D RegiMgrBase: onNetworkEventChanged: old=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=false, isEpdgConnected=false]
10-11 13:48:16.504 10067 10067 I [RBL] GuardedSuspension: @getInstance
10-11 13:48:16.504  4527  4616 D RegiMgrBase: out of service.
10-11 13:48:16.504  4527  4616 D RegiMgrBase: onNetworkEventChanged: nTask= 0 nRegisteredTask= 0 bExistRetryTimer= false bHaveRegisteringTask= false
10-11 13:48:16.504 10067 10067 I [RBL] GuardedSuspension: GuardedSuspension
10-11 13:48:16.505  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.505  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.505  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-11 13:48:16.505  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.506  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.506  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.507  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.507  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.508  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.508  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.508  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.509  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:16.509  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.509  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.509  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.509  3701  3960 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:16.510  3701  3960 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-11 13:48:16.512  3701  3701 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
10-11 13:48:16.512  3701  3701 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = false
10-11 13:48:16.512  3701  3701 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
10-11 13:48:16.512  3701  3701 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
10-11 13:48:16.512  3701  3916 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
10-11 13:48:16.512  3701  3916 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
10-11 13:48:16.513  3701  3916 D EnterprisePremiumVpnPolicyServiceV2: run all vpn : runAllVpnService beginning
10-11 13:48:16.513  3701  3701 D Tethering: Tethering got CONNECTIVITY_ACTION
10-11 13:48:16.513  3701  3962 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
10-11 13:48:16.513  3701  3962 D Tethering: MasterInitialState.processMessage what=327683
10-11 13:48:16.513  3701  3917 I KnoxVpnEngineService: vpn handle : Message received
10-11 13:48:16.513  3701  3917 I KnoxVpnEngineService: vpn handle : Message received
,10-11 13:48:16.513  3701  3917 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = false
10-11 13:48:16.513  3701  3917 D KnoxVpnEngineService: run all vpn : runAllVpnService beginning
10-11 13:48:16.514 10067 10067 I [RBL] GuardedSuspension: @getInstance
10-11 13:48:16.514 10067 10067 D [RBL] RblSAccountUtil: @open
10-11 13:48:16.514 10067 10067 D [RBL] RblSAccountUtil:     - client : 1
10-11 13:48:16.515  4527  4616 D RegiMgrBase: onNetworkEventChanged: tryRegister
10-11 13:48:16.515  4527  4616 D RegiMgrBase: tryRegister:
,10-11 13:48:16.520  4527  4616 D RegiMgrBase: RegisterTask(s) -
10-11 13:48:16.520  4527  4616 D ResipRegiMgr: handleMessage(): 32
10-11 13:48:16.520  4527  4616 D RegiMgrBase: handleMessage: what 32
10-11 13:48:16.520  4527  4616 D RegiMgrBase: onPendingUpdateRegistration: 
,10-11 13:48:16.521  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:16.522  4070  4293 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
,10-11 13:48:16.529  5166  5166 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF50EC62EA054297E5426D68FE61E03F7CB63D06B4FC0A78A26416AA7E048F840EFBC21D921AABB61599A4C4654ABE1206043CF566A086A1148D0FC76C5AA3DFC0]}
,10-11 13:48:16.530  5166  5166 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF006507037EF1FC27CFA959C112FA7F2D1F670CE973374D2DC76D44F7D5EE5AC4ACC17241AE6937FB763E957545037025]}
10-11 13:48:16.530  5166  5166 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF0553125B1A7ADEFBA03E3A7F9CEA3D9489139B6F35BA5D5C6F631797333959D1]}
10-11 13:48:16.531  3701  3921 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
10-11 13:48:16.531  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:16.531  5166  5166 D [WeatherWidget(1434)]  AutoRefresh: {[7D74CB60CAF3D3413AB6BB573C0D2852DB29E43AA0DFF8610F50F000609916CC778EE20F4C0BF92710C3F9097DA62F0495DABD0101A657F929F38259D0F4F774]}
,10-11 13:48:16.532  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
,10-11 13:48:16.532  5202  5202 I CastMediaRouteProvider: Network connectivity changed
10-11 13:48:16.532  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
10-11 13:48:16.533  3701  3921 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
10-11 13:48:16.533  3701  3921 D NtpTrustedTime: currentTimeMillis() cache hit
,10-11 13:48:16.541  3701  3921 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
,10-11 13:48:16.550  9385  9385 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
,10-11 13:48:16.550  9385  9385 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
10-11 13:48:16.550 10067 10067 D [RBL] RblSAccountUtil:     - DB is opened
10-11 13:48:16.550 10067 10067 D [RBL] CellDbHelper: @open
10-11 13:48:16.550 10067 10067 D [RBL] CellDbHelper:     - client : 1
10-11 13:48:16.551  8060  8060 I FOTA_AGENT: [com.samsung.android.app.syncmldm.llllIIIllIlIIIIllllI(243/onReceive)] m_DataReceiver: g_nResumeStatus: 0 m_nWaitWifiConnectMode: 0
10-11 13:48:16.552  3701  3701 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
10-11 13:48:16.552  3701  4487 D SLocation: checkWifiInfo
,10-11 13:48:16.556  3701  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,10-11 13:48:16.560 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
10-11 13:48:16.561 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-11 13:48:16.561 10082 10082 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,10-11 13:48:16.566  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:16.567 10082 10082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 android.content.ContextWrapper.sendBroadcast:452 android.content.ContextWrapper.sendBroadcast:452 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3306 
,10-11 13:48:16.568  3701  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,10-11 13:48:16.568  3701  3701 V MARsPolicyManager: DataConnection: true
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-11 13:48:16.569  9789  9789 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-11 13:48:16.572  4863  4863 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-11 13:48:16.580  9385  9385 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
10-11 13:48:16.580  9385  9385 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
10-11 13:48:16.580  9385  9385 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
10-11 13:48:16.580 10096 10096 I PhoneErrorReceiver: onReceive
10-11 13:48:16.580  9443  9443 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@bfcf53c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-11 13:48:16.582 10067 10067 D [RBL] CellDbHelper:     - DB is opened
10-11 13:48:16.582 10067 10067 D [RBL] PolicyDbHelper: @open
10-11 13:48:16.582 10067 10067 D [RBL] PolicyDbHelper:     - client : 1
10-11 13:48:16.582  9789  9789 D BluetoothAdapter: STATE_ON
10-11 13:48:16.584  8838  8838 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
10-11 13:48:16.585  3701  4487 D SLocation: cellLocation is null
,10-11 13:48:16.587  9789  9789 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
10-11 13:48:16.591  9443  9443 I NetworkConnectivity: Network state changed: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]
10-11 13:48:16.597  8838  8838 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
10-11 13:48:16.598  8060  8060 I FOTA_AGENT: [lIIlllIlIIlllIIIIlII(93/llllIIIllIlIIIIllllI)] WiFi Network is connected
10-11 13:48:16.599 10110 10110 I usagelog: received in receiver
10-11 13:48:16.599 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
10-11 13:48:16.599 10110 10110 I KnoxUsageLogPro: premStatus:2
10-11 13:48:16.600 10110 10110 I KnoxUsageLogPro: isEulaShown : false
10-11 13:48:16.600 10110 10110 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
10-11 13:48:16.605  8838  8838 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
10-11 13:48:16.611 10067 10067 D [RBL] PolicyDbHelper:     - DB is opened
10-11 13:48:16.612 10067 10284 D [RBL] StoredRequest: @onHandleIntent
10-11 13:48:16.615  5166  5166 D [WeatherWidget(1434)]  WidgetCount: {[65C2FDBB08E09D2E8E78BEFE0D618279BC32024A311F60279E75A9FD2AD8BED1]}
10-11 13:48:16.615  5166  5166 D [WeatherWidget(1434)]  WidgetCount: {[51D05FFECDA2C35BD99FAAEAA7B9A301F0BE9CFAFD994C3F7B3209384CC66988]}
10-11 13:48:16.621 10067 10067 D [RBL] CellDbHelper: @close
10-11 13:48:16.621 10067 10067 D [RBL] CellDbHelper:     - client : 0
10-11 13:48:16.621 10067 10067 D [RBL] CellDbHelper:     - DB is closed
10-11 13:48:16.621 10067 10067 D [RBL] PolicyDbHelper: @close
10-11 13:48:16.621 10067 10067 D [RBL] PolicyDbHelper:     - client : 0
10-11 13:48:16.621 10067 10067 D [RBL] PolicyDbHelper:     - DB is closed
10-11 13:48:16.621 10067 10067 D [RBL] RblSAccountUtil: @close
10-11 13:48:16.621 10067 10067 D [RBL] RblSAccountUtil:     - client : 0
10-11 13:48:16.621 10067 10067 D [RBL] RblSAccountUtil:     - DB is closed
10-11 13:48:16.621 10067 10067 D [RBL] StoredRequest: @onDestroy
10-11 13:48:16.637  5166  5166 E [WeatherWidget(1434)]  WidgetCount: {[575702F8165D33B66FFE59737B1A62BA08307BCFA3F3A497389D8A1664DA7207C61FE3795BDDA6ED7149C0C90BBA0789F02F175F5575CC50CF5DAAE8904C8914F88792B902BC3E22CDAD80A066BB3E6979730FC110332D83BB2D465425F6B25F89D3F8672D6293DD63CA48A914D2FE41578525C7DFC817959D978B0D1E4AEA3E8237DDDE31DA9CCBB38800CB9D7B42E57A86DA9FF9D55CAD67CE294EA9DE56535F45722BD7BAE690537BE548FCDE8E57ED456836297CA885487DA18C55446062]}
,10-11 13:48:16.648  5166  5166 W [WeatherWidget(1434)]  AutoRefresh: {[FD51A315D37AAFC2E139641098576D046D458C57EE37DB6B9263681FFCD40CF01A6772634AEDA0D4B0B223A0763A58EE4BED955A823F243BEAE3A45567F08DD2321854D08A27F4D40285D5771BC7B0FC95FCD4E704A2C776AC2C52FEDFAEF037]}
10-11 13:48:16.652  3701  4917 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@a0ffae6 displayId=0
,10-11 13:48:16.652  5166  5166 D [WeatherWidget(1434)]  AutoRefresh: {[D66993CEC2139B42825F15423C8FC37CB81F28161A53B5553937AF4F1AAAEBA916B5697044B6E04751F07B003D46E660A784CB9E3B462E87AEB1AD3F809D90C23EB9D3B97867E467A798739D729C38BF02F8E7F88FD79BFB6259D7DAEFCF9DEF]}
,10-11 13:48:16.652  3701  4917 D InputTransport: Input channel constructed: fd=458
10-11 13:48:16.653  3701  4917 D InputTransport: Input channel constructed: fd=459
10-11 13:48:16.653  5166  5166 D [WeatherWidget(1434)]  AutoRefresh: {[3B620F0E62100CD008166B45665AC4E0990189A1A2BD5FD130A6F5AC98AF999B]}
10-11 13:48:16.654  9443  9443 I NetworkPolicyMonitor: Download-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
10-11 13:48:16.657  3701  4917 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
10-11 13:48:16.658  3701  4917 D InputTransport: Input channel destroyed: fd=459
10-11 13:48:16.659  3701  4918 D SamsungAlarmManager: Cancel Alarm calling from uid:10159 pid :5166 / op:PendingIntent{2df747d: PendingIntentRecord{450df72 com.sec.android.daemonapp broadcastIntent}}
10-11 13:48:16.659  4070  4293 D InputTransport: Input channel constructed: fd=150
10-11 13:48:16.659  4070  4293 D ViewRootImpl@72b8b49[Toast]: setView = android.widget.LinearLayout{570bc4e V.E...... ......I. 0,0-0,0 #10204d0 android:id/toast_layout_root} touchMode=true
10-11 13:48:16.660  5166  5166 D [WeatherWidget(1434)]  AutoRefresh: {[13EBFE39826C141B196DBEF817B05C2B8704215167EB2523B0284BC069F64B74]}
10-11 13:48:16.663  3701  3915 V WindowManager: Relayout Window{2e45ad4d0 u0 Toast}: viewVisibility=0 req=755x150 WM.LayoutParams{(0,192)(wrapxwrap) gr=#51 sim=#20 ty=2005 fl=#1040088 fmt=-3 wanim=0x1030004 naviIconColor=0}
10-11 13:48:16.664  3113  3113 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=4, Uoast
10-11 13:48:16.668  3701  4487 D SLocation: geofence id (1) detected : 0
10-11 13:48:16.669  9443  9443 I NetworkPolicyMonitor: Stream-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
,10-11 13:48:16.679  5202  5580 W MdnsClient_Cast: #acquireLock. Multicast lock not held. Acquiring. Subtypes:"805741C9"
,10-11 13:48:16.680  3701  3930 D WifiHAL : Setting APF program, halHandle = 0x709f3efde0
10-11 13:48:16.680  3701  3930 I WifiHAL : 
10-11 13:48:16.680  3701  3930 I WifiHAL : createRequest: APF set program request
,10-11 13:48:16.683  3701  3930 I WifiHAL : Done!
,10-11 13:48:16.687  3294  3781 D EnterpriseController: netId is 0
10-11 13:48:16.687  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10001
10-11 13:48:16.687  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:16.689  3294  3781 D EnterpriseController: netId is 0
10-11 13:48:16.689  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10019
10-11 13:48:16.689  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:16.692  3701  3915 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3701 ws=WorkSource{10062} pkg=android
10-11 13:48:16.693  3701  3915 D PowerManagerService: mDisplayReady: false
10-11 13:48:16.693  3701  3800 D DisplayPowerController: animateScreenStateChange[0]: target=2
10-11 13:48:16.693  3701  3800 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
10-11 13:48:16.694  3701  3800 D DisplayPowerController: Tracking Direct to etc : 102
10-11 13:48:16.694  3701  3800 D DisplayPowerController: getFinalBrightness : Summary is 102 -> 102
10-11 13:48:16.694  3701  3800 D DisplayPowerController: Animating brightness: target=102, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-11 13:48:16.694  3701  3800 D DisplayPowerController: animateScreenStateChange[0]: target=2
10-11 13:48:16.694  3701  3800 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
10-11 13:48:16.694  3701  3800 D DisplayPowerController: getFinalBrightness : Summary is 102 -> 102
10-11 13:48:16.694  3701  4038 D lights  : lcd : 102 +
10-11 13:48:16.694  3701  3800 D DisplayPowerController: Animating brightness: target=102, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-11 13:48:16.694  3701  3800 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-11 13:48:16.695  3701  3800 D PowerManagerService: mDisplayReady: true
,10-11 13:48:16.699  3701  4038 D lights  : lcd : 102 -
10-11 13:48:16.699  3701  4038 D DisplayPowerState: Tracking!!: 102
10-11 13:48:16.699  5202  5202 E MDM     : [1] SitrepChimeraService.a: No Google accounts; deferring server state update.
10-11 13:48:16.700  3701  4181 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.ConnectivityReceiver newState = 2 callingPackage = 10019
,10-11 13:48:16.706  4070  4293 D ViewRootImpl@72b8b49[Toast]: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,10-11 13:48:16.709  9443  9443 I DevicePlayback: Got network change: mobile=falsewifi=true
10-11 13:48:16.709  9443  9443 I DevicePlayback: Connectivity restored - clearing all queued disable runnables
,10-11 13:48:16.710  4070  4228 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [755x150]-format:1
,10-11 13:48:16.724  5202  5202 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-11 13:48:16.726  3701  3729 D WifiScanController: isNLPPackage:com.google.android.gms, true
10-11 13:48:16.726  3701  3930 I WifiScanController: location is disabled
10-11 13:48:16.728  3701  4487 D SLocation: geofence id (2) detected : 0
10-11 13:48:16.730  5202  8287 I iu.UploadsManager: num queued entries: 0
10-11 13:48:16.731  5202  8287 I iu.UploadsManager: num updated entries: 0
10-11 13:48:16.733  5202  8287 I iu.SyncManager: NEXT; no task
,10-11 13:48:16.757  3701  4915 D WindowManager: finishDrawingWindow: Window{2e45ad4d0 u0 Toast} mDrawState=DRAW_PENDING
,10-11 13:48:16.769  9443  9502 I DevicePlayback: Allowing woodstock playback due to restored connection
,10-11 13:48:16.772 10136 10136 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,10-11 13:48:16.773 10136 10136 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? ]
10-11 13:48:16.773 10136 10136 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,10-11 13:48:16.781 10136 10136 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
10-11 13:48:16.781 10136 10136 I SA      : [OR] == isSIMCardReady false ==
10-11 13:48:16.782 10136 10136 I SA      : [SCU] == networkStateCheck == true
,10-11 13:48:16.783 10136 10136 I SA      : [DM] getCountryCodeFromCSC : PL
10-11 13:48:16.783 10136 10136 I SA      : isChinaCountryCode : false
10-11 13:48:16.783 10136 10136 I SA      : [SCU] is ChinestModel Data Restricted   : false
10-11 13:48:16.783 10136 10136 I SA      : [OR] == networkStateCheck true ==
,10-11 13:48:16.798  4070  4210 D vol.MediaSessions: onQueueChanged com.google.android.music []
,10-11 13:48:16.807  3701  3919 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20171011T141816 - CU:10124/CP:5148
,10-11 13:48:16.816  3701  4021 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: GW is reachable. - 275 msec.
,10-11 13:48:16.828 10136 10136 I SA      : [OR] GetMyCountryZoneTask
10-11 13:48:16.829 10136 10136 I SA      : [OR] onReceive END
,10-11 13:48:16.850 10159 10159 I SVCAgent: Ignore network change.
,10-11 13:48:16.859 10172 10172 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,10-11 13:48:16.874  8016  8016 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
10-11 13:48:16.874  8016  8016 E SPPClientService: [SystemStateMoniter] Current Time : 208011
,10-11 13:48:16.875  8016  8016 E SPPClientService: [SystemStateMoniter] No Connect : false
,10-11 13:48:16.889 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,10-11 13:48:16.889 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-11 13:48:16.890 10082 10082 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,10-11 13:48:16.898  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:16.898  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
10-11 13:48:16.898  3701  3930 D WifiStateMachine: User moved, open or psk 24GHz, currentRssi = -52, mQnsUpperRssiThreshold = 200
10-11 13:48:16.902  3701  3930 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@f31347a
10-11 13:48:16.902  3701  3930 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,10-11 13:48:16.906  3701  3930 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20171011T134820 - CU:1000/CP:3701
10-11 13:48:16.906  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134820, SetElapsed=212043, nowELAPSED=208043
,10-11 13:48:16.916 10136 10296 I SA      : [SRS] prepareGetMyCountryZone
10-11 13:48:16.917  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-11 13:48:16.932 10136 10296 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
10-11 13:48:16.932  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-11 13:48:16.933  3701  3791 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-11 13:48:16.934 10136 10296 I SA      : [SSP] query invoked
,10-11 13:48:16.947 10136 10296 I SA      : [TPMU] GetMccFromDB : null
10-11 13:48:16.947 10136 10296 I SA      : [SCU] getMccFromPreferece mcc = 260
10-11 13:48:16.948 10136 10296 I SA      : [LBE] isSupportCheckDomainRegion : true
10-11 13:48:16.948 10136 10296 I SA      : [TPM] isNoProxy(default) : true
10-11 13:48:16.951 10136 10296 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,10-11 13:48:16.966  3701  4923 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{cbc0922: PendingIntentRecord{569d371 com.google.android.gms broadcastIntent}}
,10-11 13:48:16.975  3701  4540 D MountService: getExternalStorageMountMode : 1
10-11 13:48:16.975  3701  4540 D MountService: getExternalStorageMountMode : 3
10-11 13:48:16.975  3701  4540 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.policydm
,10-11 13:48:17.001 10300 10300 E Zygote  : v2
10-11 13:48:17.001 10300 10300 I libpersona: KNOX_SDCARD checking this for 1000
10-11 13:48:17.001 10300 10300 I libpersona: KNOX_SDCARD not a persona
,10-11 13:48:17.002  3701  4540 I ActivityManager: Start proc 10300:com.policydm/1000 for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider
10-11 13:48:17.002 10300 10300 E Zygote  : accessInfo : 0
,10-11 13:48:17.012 10300 10300 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:17.014 10300 10300 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.policydm 
,10-11 13:48:17.036  3701  4021 D WifiWatchdogStateMachine:  [|205]
,10-11 13:48:17.039 10300 10300 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:17.040 10300 10300 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:17.042  3701  3728 I ActivityManager: DSS on for com.policydm and scale is 1.0
10-11 13:48:17.042  4765 10313 I VacuumService: Vacuum at: now=1507722497042 tag=VacuumService
,10-11 13:48:17.063 10300 10300 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,10-11 13:48:17.077 10300 10300 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:17.090 10300 10300 I FOTA    : [lllIIIIIIlllIlIIIIII(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,10-11 13:48:17.090 10300 10300 I FOTA    : [lllIIIIIIlllIlIIIIII(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,10-11 13:48:17.109  3701  4918 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144547 - CU:10019/CP:4765
,10-11 13:48:17.121 10300 10300 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,10-11 13:48:17.131 10300 10312 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,10-11 13:48:17.140 10300 10312 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,10-11 13:48:17.149  3701  4921 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20171011T135727 - CU:10019/CP:4765
,10-11 13:48:17.149  3701  4887 D MountService: getExternalStorageMountMode : 3
10-11 13:48:17.149  3701  4887 D MountService: getExternalStorageMountMode : 3
10-11 13:48:17.149  3701  4887 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 10019, packageName : com.google.android.gms
10-11 13:48:17.151 10300 10312 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,10-11 13:48:17.156  3701  4928 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
10-11 13:48:17.156  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:17.156  3701 10271 D NetworkMonitor: handled
,10-11 13:48:17.168 10300 10300 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(186/llIIIIlllllIIllIIllI)] try read dbString
,10-11 13:48:17.172  3701  4887 I ActivityManager: Start proc 10320:com.google.android.gms.unstable/u0a19 for service com.google.android.gms/.droidguard.DroidGuardService
10-11 13:48:17.174 10320 10320 E Zygote  : v2
10-11 13:48:17.174 10320 10320 I libpersona: KNOX_SDCARD checking this for 10019
10-11 13:48:17.174 10320 10320 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:17.175 10320 10320 E Zygote  : accessInfo : 0
,10-11 13:48:17.181 10300 10311 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,10-11 13:48:17.184 10300 10311 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
10-11 13:48:17.186 10320 10320 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-11 13:48:17.188 10320 10320 I SELinux : SELinux: seapp_context_lookup: seinfo=gmscore, level=s0:c512,c768, pkgname=com.google.android.gms.unstable 
10-11 13:48:17.188 10300 10311 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,10-11 13:48:17.198  3701  3927 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144547 - CU:10019/CP:4765
10-11 13:48:17.198  3701  4927 D MountService: getExternalStorageMountMode : 1
10-11 13:48:17.198  3701  4927 D MountService: getExternalStorageMountMode : 3
10-11 13:48:17.198  3701  4927 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.soagent
,10-11 13:48:17.201  3701  4928 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
10-11 13:48:17.202  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:17.202  3701 10271 D NetworkMonitor: handled
,10-11 13:48:17.207  3701  4916 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
10-11 13:48:17.207  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:17.207  3701 10271 D NetworkMonitor: handled
10-11 13:48:17.212  3701  4181 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{b568c9c: PendingIntentRecord{ce8845d com.google.android.gms broadcastIntent}}
,10-11 13:48:17.218 10320 10320 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:17.218 10320 10320 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:17.234 10333 10333 E Zygote  : v2
10-11 13:48:17.234 10333 10333 I libpersona: KNOX_SDCARD checking this for 1000
10-11 13:48:17.234 10333 10333 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:17.235 10333 10333 E Zygote  : accessInfo : 0
,10-11 13:48:17.237  3701  4927 I ActivityManager: Start proc 10333:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
10-11 13:48:17.238 10300 10300 I DBG_POLICYDM: [com.policydm.db.XDB(231/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
10-11 13:48:17.238  3701  3915 I ActivityManager: DSS on for com.google.android.gms and scale is 1.0
,10-11 13:48:17.256 10333 10333 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:17.258 10333 10333 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.soagent 
,10-11 13:48:17.259  3701  4543 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20171011T135727 - CU:10019/CP:4765
,10-11 13:48:17.310 10333 10333 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:17.310 10333 10333 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:17.313  4044  4054 I art     : Background partial concurrent mark sweep GC freed 62440(3MB) AllocSpace objects, 7(144KB) LOS objects, 39% free, 7MB/12MB, paused 263us total 103.154ms
,10-11 13:48:17.319  3701  4918 I ActivityManager: DSS on for com.sec.android.soagent and scale is 1.0
10-11 13:48:17.320 10320 10320 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
10-11 13:48:17.337  3701  4915 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144547 - CU:10019/CP:4765
,10-11 13:48:17.346 10333 10333 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,10-11 13:48:17.347 10320 10320 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:17.352 10320 10320 I LoadedApk: No resource references to update in package FFFFFFFFFFFFFFFFFFFFFF
,10-11 13:48:17.356 10300 10300 I DBG_POLICYDM: [com.policydm.XDMService(164/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,10-11 13:48:17.361 10333 10333 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:17.367 10300 10300 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(455/IIIIIIlIIIllllllIlII)] xdbGetFUMOStatus : 0
,10-11 13:48:17.369 10300 10300 I DBG_POLICYDM: [com.policydm.XDMService(588/llIlIllllllllllllllI)] get NotibarState : 0
,10-11 13:48:17.370  3701  4540 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{af1f821: PendingIntentRecord{569d371 com.google.android.gms broadcastIntent}}
,10-11 13:48:17.397  3701  4928 D MountService: getExternalStorageMountMode : 1
10-11 13:48:17.397  3701  4928 D MountService: getExternalStorageMountMode : 3
10-11 13:48:17.397  3701  4928 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10134, packageName : com.sec.android.app.sbrowser
,10-11 13:48:17.402 10320 10320 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 242 native methods...
,10-11 13:48:17.415 10320 10320 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,10-11 13:48:17.415 10354 10354 E Zygote  : v2
,10-11 13:48:17.415 10354 10354 I libpersona: KNOX_SDCARD checking this for 10134
10-11 13:48:17.415 10354 10354 I libpersona: KNOX_SDCARD not a persona
10-11 13:48:17.415 10354 10354 E Zygote  : isSdpEnabledProcess - SDP enabled
10-11 13:48:17.416 10354 10354 E Zygote  : accessInfo : 64
10-11 13:48:17.416 10354 10354 E Zygote  : isSdpEnabledProcess - SDP enabled
10-11 13:48:17.416 10354 10354 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10134 / [uid]: 10134
10-11 13:48:17.417 10320 10320 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
10-11 13:48:17.418  3701  4928 I ActivityManager: Start proc 10354:com.sec.android.app.sbrowser:CustomLogger/u0a134 for content provider com.sec.android.app.sbrowser/.logging.CustomLoggingProvider
,10-11 13:48:17.422 10354 10354 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:17.423 10354 10354 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser:CustomLogger 
,10-11 13:48:17.449 10354 10354 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:17.449 10354 10354 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:17.451  3701  4542 I ActivityManager: DSS on for com.sec.android.app.sbrowser and scale is 1.0
,10-11 13:48:17.482 10354 10354 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_5.0/lib/arm
,10-11 13:48:17.483  3701  3960 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
10-11 13:48:17.494 10354 10354 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:17.513 10354 10354 I cr_ApplicationStatus: initialize application : com.sec.android.app.sbrowser.SBrowserApplication@7f52fe
,10-11 13:48:17.517 10354 10354 D ReflectField: Cannot load field: SDL_INT
10-11 13:48:17.517 10354 10354 E ReflectField: Incorrect type : Fallback exception
10-11 13:48:17.517 10354 10354 D ReflectField: Cannot load field: KEYCODE_EMAIL
10-11 13:48:17.518 10354 10354 E ReflectField: Incorrect type : Fallback exception
,10-11 13:48:17.527  3701  4020 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
10-11 13:48:17.528  3701  4020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
10-11 13:48:17.530  3701  4016 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
10-11 13:48:17.531  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:17.531  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: MaybeNotifyState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:17.531  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:17.531  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: CMD_ACCEPT_UNVALIDATED_WIFI
10-11 13:48:17.531  3701  3960 D ConnectivityService: NetworkMonitor.CMD_ACCEPT_UNVALIDATED_WIFI network
10-11 13:48:17.531  3701  3960 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
10-11 13:48:17.531  3701  3960 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-11 13:48:17.531  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.531  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.531  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.531  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:17.531  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.531  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.532  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.532  3701  3960 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
10-11 13:48:17.532  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:17.532  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.532  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.532  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.532  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.532  3701  3960 D ConnectivityService: sending new Min Network Score(100): NetworkReques,t [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.532  3701  3930 D WIFI    : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.532  3701  3930 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:17.532  3701  3930 D WIFI    : evalRequest
10-11 13:48:17.532  3701  3930 D WIFI    :   releaseNetworkFor
10-11 13:48:17.533  3701  3930 D WIFI_UT : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.533  3701  3930 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:17.533  3701  3930 D WIFI_UT : evalRequest
10-11 13:48:17.533  3701  3930 D WIFI_UT :   done
10-11 13:48:17.533  3701  4025 D Ethernet: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.533  3701  4025 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
10-11 13:48:17.533  3701  4025 D Ethernet: evalRequest
10-11 13:48:17.533  3701  4025 D Ethernet:   done
10-11 13:48:17.533  4044  4044 D PhoneSwitcherNetworkRequstListener: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.533  4044  4044 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
10-11 13:48:17.534  4044  4044 D PhoneSwitcherNetworkRequstListener: evalRequest
10-11 13:48:17.534  3701  3925 D WIFI_P2P: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.534  4044  4044 D PhoneSwitcherNetworkRequstListener:   done
10-11 13:48:17.534  3701  3925 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-11 13:48:17.534  3701  3925 D WIFI_P2P: evalRequest
10-11 13:48:17.534  3701  3925 D WIFI_P2P:   done
10-11 13:48:17.536  3701  4916 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144528 - CU:10019/CP:4765
,10-11 13:48:17.542  3701  3701 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,10-11 13:48:17.543  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=151655 target=com.android.internal.util.StateMachine$SmHandler }
10-11 13:48:17.543  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: RESULT_VALID
10-11 13:48:17.543  3701 10271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,10-11 13:48:17.543  3701  3960 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-11 13:48:17.544  3701  3960 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-11 13:48:17.544  3701  3960 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation passed
10-11 13:48:17.544  3701  3960 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-11 13:48:17.545  3701  3960 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
10-11 13:48:17.545  3701  3960 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-11 13:48:17.547  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-11 13:48:17.547  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.547  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.547  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:17.547  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-11 13:48:17.547  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
10-11 13:48:17.548  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-11 13:48:17.548  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,10-11 13:48:17.548  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:17.548  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [] ]
10-11 13:48:17.549  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.549  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.554  3701  4488 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / op:PendingIntent{6e53121: PendingIntentRecord{5142946 android broadcastIntent}}
10-11 13:48:17.557  3701  4488 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20171012T134817 - CU:1000/CP:3701
10-11 13:48:17.555  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.562  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.562  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.562  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-11 13:48:17.563  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.563  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.564  3701  4927 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144528 - CU:10019/CP:4765
,10-11 13:48:17.568  3701  3701 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
10-11 13:48:17.569  3701  3701 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
10-11 13:48:17.571  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.573  3701  3701 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,10-11 13:48:17.581  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.581  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.582  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-11 13:48:17.583  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.583  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-11 13:48:17.583  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.583  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.584  3701  3960 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.584  3701  3960 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-11 13:48:17.584  3701  3960 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-11 13:48:17.584  3701  4921 I ActivityManager: KPU : put [com.samsung.android.themecenter] : 22976 K
10-11 13:48:17.584  3701  4921 I ActivityManager: Killing 7399:com.samsung.android.themecenter/1000 (adj 906): DHA:empty #33
10-11 13:48:17.593  3701  3930 D WifiConfigManager: update usableInternet : true
10-11 13:48:17.594  3701 10377 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
10-11 13:48:17.594  3701 10377 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
10-11 13:48:17.594  3701 10377 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
10-11 13:48:17.594  3701 10377 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
10-11 13:48:17.594  3701 10377 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
10-11 13:48:17.594  3701 10377 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
,10-11 13:48:17.594  3701 10377 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: true
10-11 13:48:17.594  3701 10377 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
10-11 13:48:17.594  3701 10377 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
10-11 13:48:17.594  3701 10377 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
10-11 13:48:17.594  3701 10377 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
10-11 13:48:17.594  3701 10377 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
10-11 13:48:17.602  3701  3701 D SLocation: PendingIntent onSendFinished id:1
10-11 13:48:17.602  3701  3701 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [2], direction [0]
10-11 13:48:17.603  3701  3701 D WifiStateMachine: BroadcastReceiver() - configKey : "ktwtestwifi"WPA_EAP IN. Reduce scan max interval
10-11 13:48:17.605  3701  3701 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
10-11 13:48:17.609  4070  4293 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-11 13:48:17.610  4070  4293 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
10-11 13:48:17.611  3291  3291 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:10320)
,10-11 13:48:17.620  3701  3701 D SLocation: PendingIntent onSendFinished id:2
,10-11 13:48:17.625  3701  3930 D WifiConfigStore: saveNetwork skipInternetCheck
,10-11 13:48:17.637  3701  3729 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144528 - CU:10019/CP:4765
,10-11 13:48:17.639  3701  3919 D ActivityManager: cleanUpApplicationRecord -- 7399
,10-11 13:48:17.644  3701  3930 D WifiConfigStore: readNetwork skipInternetCheck
,10-11 13:48:17.650  4803  4817 D ForegroundUtils: could not check pending caller
,10-11 13:48:17.656  3701  4887 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{a782b91: PendingIntentRecord{569d371 com.google.android.gms broadcastIntent}}
,10-11 13:48:17.659  3701 10380 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
10-11 13:48:17.659  3701 10380 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
10-11 13:48:17.659  3701 10380 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
10-11 13:48:17.659  3701 10380 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
10-11 13:48:17.659  3701 10380 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
10-11 13:48:17.659  3701 10380 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
10-11 13:48:17.660  3701 10380 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: true
10-11 13:48:17.660  3701 10380 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
10-11 13:48:17.660  3701 10380 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
10-11 13:48:17.660  3701 10380 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
10-11 13:48:17.660  3701 10380 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
10-11 13:48:17.660  3701 10380 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,10-11 13:48:17.665  3701  3701 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,10-11 13:48:17.665  3701  3701 D WifiHs20Service: reason: 2
10-11 13:48:17.665  3701  3956 I WifiHs20Service: Message received 5014
10-11 13:48:17.665  3701  3956 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,10-11 13:48:17.675  3291  3367 D WVCdm   : Instantiating CDM.
,10-11 13:48:17.678  3291  3367 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:10320)
,10-11 13:48:17.678  3291  3367 I WVCdm   : CdmEngine::OpenSession
10-11 13:48:17.678  3291  3367 I WVCdm   : Level3 Library 4445 Mar 30 2016 13:23:54
,10-11 13:48:17.682  3291  3367 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,10-11 13:48:17.684  3291  3367 E wv_dash : No saved usage table. Creating new table.
,10-11 13:48:17.691  3291  3367 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
,10-11 13:48:17.717  3291  3367 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,10-11 13:48:17.745  3291  3367 I WVCdm   : CdmEngine::QueryKeyControlInfo
,10-11 13:48:17.746  3291  3291 I WVCdm   : CdmEngine::GenerateKeyRequest
,10-11 13:48:17.748  3291  3291 D WVCdm   : PrepareKeyRequest: nonce=420989657
,10-11 13:48:17.782  3701  4541 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144547 - CU:10019/CP:4765
10-11 13:48:17.797 10320 10331 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
10-11 13:48:17.797  3701  3915 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144547 - CU:10019/CP:4765
10-11 13:48:17.797 10320 10331 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
10-11 13:48:17.799  3294  3781 D EnterpriseController: netId is 0
10-11 13:48:17.800  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10019
10-11 13:48:17.800  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:17.815  3701  4540 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171011T144547 - CU:10019/CP:4765
,10-11 13:48:17.857  3701  4018 D WifiWatchdogStateMachine:  [|212] []
,10-11 13:48:17.906 10136 10296 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
,10-11 13:48:17.906 10136 10296 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,10-11 13:48:17.909 10136 10296 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,10-11 13:48:17.911 10136 10296 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-11 13:48:17.911 10136 10296 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-11 13:48:17.914  3294  3781 D EnterpriseController: netId is 0
,10-11 13:48:17.914  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10041
10-11 13:48:17.914  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:18.080  3291  3367 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:10320)
10-11 13:48:18.080  3291  3367 I WVCdm   : CdmEngine::CloseSession
,10-11 13:48:18.086  3291  3367 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
,10-11 13:48:18.420  9789  9853 I io.jxcore.node.IncomingSocketThreadTest: testRun
,10-11 13:48:18.424  9789 10389 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
10-11 13:48:18.424  9789 10389 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-11 13:48:18.428  3294  3781 D EnterpriseController: netId is 0
10-11 13:48:18.428  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10033
10-11 13:48:18.428  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:18.431  9789 10391 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
10-11 13:48:18.431  9789 10391 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-11 13:48:18.432  9789 10391 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:18.432  9789 10389 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
10-11 13:48:18.432  9789 10389 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,10-11 13:48:18.432  9789 10389 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:18.432  9789 10391 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:18.433  9789 10389 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:18.433  9789 10391 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-11 13:48:18.433  9789 10389 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-11 13:48:18.435  9789 10393 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 225, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.435  9789 10393 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:18.435  9789 10393 D io.jxcore.node.StreamCopyingThread:  id: 77
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 227, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread:  id: 77
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 227, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread:  id: 77
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread:  id: 77
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:18.435  9789 10395 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:18.436  9789 10395 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:18.436  9789 10395 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:18.436  9789 10395 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:18.436  9789 10395 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,10-11 13:48:18.436  9789 10395 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 227, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.436  9789 10395 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:18.436  9789 10395 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-11 13:48:18.436  9789 10393 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 225, thread name: IncomingSocketThread/Sender): Socket closed
10-11 13:48:18.436  9789 10393 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 225, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.436  9789 10393 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:18.436  9789 10393 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-11 13:48:18.436  9789 10393 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,10-11 13:48:18.436  9789 10396 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 228, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.436  9789 10396 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:18.436  9789 10396 D io.jxcore.node.StreamCopyingThread:  id: 78
10-11 13:48:18.436  9789 10393 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-11 13:48:18.437  9789 10393 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 225, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.437  9789 10393 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:18.437  9789 10393 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 228, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread:  id: 78
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread:  id: 78
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:18.437  9789 10396 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 228, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:18.437  9789 10396 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-11 13:48:18.438  9789 10394 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 226, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.438  9789 10394 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:18.438  9789 10394 D io.jxcore.node.StreamCopyingThread:  id: 78
10-11 13:48:18.438  9789 10394 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 226, thread name: OutgoingSocketThread/Sender): Socket closed
10-11 13:48:18.438  9789 10394 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 226, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.438  9789 10394 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:18.438  9789 10394 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-11 13:48:18.438  9789 10394 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-11 13:48:18.439  9789 10394 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-11 13:48:18.439  9789 10394 D io.jxcore.node.StreamCopyin,gThread: Exiting thread (ID: 226, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:18.439  9789 10394 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:18.439  9789 10394 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,10-11 13:48:18.638  4070  4293 D ViewRootImpl@72b8b49[Toast]: dispatchDetachedFromWindow
,10-11 13:48:18.643  3701  4927 D InputTransport: Input channel destroyed: fd=458
10-11 13:48:18.644  3701  4927 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3701) eventTime = 209780
10-11 13:48:18.644  3701  4927 D PowerManagerService: [s] UserActivityState : 4 -> 1
,10-11 13:48:18.645  3701  4927 D PowerManagerService: [api] release WakeLock SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3701, ws=WorkSource{10062}) (uid=1000, pid=3701, ws=WorkSource{10062}, pkg=android, elapsedTime=1952) (0x0)
10-11 13:48:18.645  3701  4927 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3701, ws=WorkSource{10062}) (uid=1000, pid=3701, ws=WorkSource{10062}, pkg=android, elapsedTime=1952)
10-11 13:48:18.646  4070  4293 D InputTransport: Input channel destroyed: fd=150
,10-11 13:48:18.692 10136 10296 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 783
,10-11 13:48:18.737 10397 10397 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-fd=67 --oat-location=/data/user/0/com.google.android.gms/app_fb/f.dex --compiler-filter=speed
,10-11 13:48:18.748 10136 10296 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,10-11 13:48:18.749 10136 10296 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,10-11 13:48:18.752 10136 10296 I SA      : [OCP]  Cursor is not null
,10-11 13:48:18.756 10136 10296 I SA      : [OCP] update openData : EU
,10-11 13:48:18.761 10136 10296 I SA      : [TPMU] getNetworkMcc : 
,10-11 13:48:18.765 10136 10296 I SA      : [SRS] prepareGetMyCountryZone
,10-11 13:48:18.773 10136 10296 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
10-11 13:48:18.773 10136 10296 I SA      : [SSP] query invoked
,10-11 13:48:18.778 10136 10296 I SA      : [TPMU] GetMccFromDB : null
10-11 13:48:18.779 10136 10296 I SA      : [SCU] getMccFromPreferece mcc = 260
10-11 13:48:18.779 10136 10296 I SA      : [LBE] isSupportCheckDomainRegion : true
10-11 13:48:18.779 10136 10296 I SA      : [TPM] isNoProxy(default) : true
,10-11 13:48:18.781 10136 10296 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
10-11 13:48:18.781 10136 10296 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,10-11 13:48:18.783 10136 10296 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,10-11 13:48:18.784 10136 10296 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
10-11 13:48:18.785 10136 10296 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-11 13:48:18.876 10397 10397 I dex2oat : ----------------------------------------------------
10-11 13:48:18.876 10397 10397 I dex2oat : <SS>: S T A R T I N G . . .
10-11 13:48:18.876 10397 10397 E dex2oat : <SS>: oat location is not valid /data/user/0/com.google.android.gms/app_fb/f.dex
10-11 13:48:18.876 10397 10397 I dex2oat : dex2oat took 140.239ms (threads: 8) arena alloc=814KB (834384B) java alloc=98KB (100432B) native alloc=1064KB (1090176B) free=2MB (3104128B)
,10-11 13:48:18.888 10320 10331 W System  : ClassLoader referenced unknown path: 
,10-11 13:48:19.181  3701  3798 I WindowManager: Destroying surface Surface(name=Toast) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementInner:499 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementLoop:274 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacement:222 com.android.server.wm.WindowManagerService$H.handleMessage:9166 android.os.Handler.dispatchMessage:102 
,10-11 13:48:19.182  3113  3121 I SurfaceFlinger: id=19 Removed Uoast (6/6)
10-11 13:48:19.183  3113  3119 I SurfaceFlinger: id=19 Removed Uoast (-2/6)
,10-11 13:48:19.291  5202  6508 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
10-11 13:48:19.291  5202  6508 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-11 13:48:19.293  3294  3781 D EnterpriseController: netId is 0
10-11 13:48:19.293  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10019
10-11 13:48:19.293  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:19.572 10136 10296 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 789
,10-11 13:48:19.574 10136 10296 I SA      : [ODM] saveOpenData( GEO_IP, EU )
10-11 13:48:19.574 10136 10296 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,10-11 13:48:19.576 10136 10296 I SA      : [OCP]  Cursor is not null
,10-11 13:48:19.581 10136 10296 I SA      : [OCP] update openData : EU
,10-11 13:48:19.584 10136 10296 I SA      : [TPMU] getNetworkMcc : 
,10-11 13:48:19.585 10136 10296 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 803
10-11 13:48:19.586 10136 10296 I SA_HTTPURLCONNECTION: [RC New] Execute end
10-11 13:48:19.586 10136 10296 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1679
10-11 13:48:19.586 10136 10296 I SA_HTTPURLCONNECTION: [RC New] Execute end
,10-11 13:48:19.587 10136 10136 I SA      : [OR] GetMyCountryZoneTask mcc = null
10-11 13:48:19.587 10136 10136 I SA      : [OR] GetMyCountryZoneTask Fail
,10-11 13:48:19.922  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:19.923  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:20.907  3701  3864 D SamsungAlarmManager: Expired : 4
10-11 13:48:20.907  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135727, SetElapsed=758350, nowELAPSED=212044
,10-11 13:48:20.908  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@49b76ed alarm=Alarm{5cc88fc type 2 when 212043 android}
,10-11 13:48:20.912  3701  3930 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,10-11 13:48:20.916 10214 10214 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-11 13:48:20.916 10214 10214 I wpa_supplicant: P2P: Current p2p state = IDLE
10-11 13:48:20.918  3701  3930 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20171011T134828 - CU:1000/CP:3701
10-11 13:48:20.922  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134828, SetElapsed=220049, nowELAPSED=212058
,10-11 13:48:20.928  3701  3957 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T134835 - CU:1000/CP:3701
,10-11 13:48:20.932 10214 10214 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-11 13:48:21.070  4648  4648 D io_stats: !@   8,0 r 26141 2315720 w 5431 211608 d 697 75192 f 2194 2194 iot 12100 11097 th 466400 0 0 pt 0 inp 0 0 212.205
,10-11 13:48:21.608  3701  5735 D SSRM:f  : SIOP:: AP = 320, PST = 312 (W:10), CP = 265, CUR = 161, LCD = 102
,10-11 13:48:22.646  3701  3800 D PowerManagerService: [s] UserActivityState : 1 -> 4
10-11 13:48:22.646  3701  3800 D PowerManagerService: mDisplayReady: false
10-11 13:48:22.646  3701  3800 I PowerManagerService: [PWL] On : 0 (213783 ms ago)
10-11 13:48:22.646  3701  3800 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
10-11 13:48:22.647  3701  3800 D DisplayPowerController: animateScreenStateChange[0]: target=2
10-11 13:48:22.647  3701  3800 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
10-11 13:48:22.647  3701  3800 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
10-11 13:48:22.647  3701  3800 D DisplayPowerController: Animating brightness: target=57, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,10-11 13:48:22.648  3701  3800 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-11 13:48:22.648  3701  3800 D PowerManagerService: mDisplayReady: true
,10-11 13:48:22.653  3701  4038 D lights  : lcd : 96 +
,10-11 13:48:22.660  3701  4038 D lights  : lcd : 96 -
,10-11 13:48:22.670  3701  4038 D lights  : lcd : 63 +
,10-11 13:48:22.672  3701  4038 D lights  : lcd : 63 -
,10-11 13:48:22.686  3701  3800 D DisplayPowerController: animateScreenStateChange[0]: target=2
10-11 13:48:22.686  3701  4038 D lights  : lcd : 57 +
10-11 13:48:22.686  3701  3800 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
10-11 13:48:22.686  3701  3800 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
10-11 13:48:22.686  3701  3800 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,10-11 13:48:22.688  3701  4038 D lights  : lcd : 57 -
,10-11 13:48:22.944  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:22.945  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:23.428  9789  9853 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 9
10-11 13:48:23.428  9789  9853 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = 
10-11 13:48:23.428  9789  9853 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,10-11 13:48:23.434  9789 10427 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
10-11 13:48:23.434  9789 10427 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-11 13:48:23.442  3294  3781 D EnterpriseController: netId is 0
,10-11 13:48:23.442  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10033
10-11 13:48:23.442  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:23.447  9789 10429 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
10-11 13:48:23.447  9789 10429 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,10-11 13:48:23.448  9789 10429 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:23.448  9789 10427 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
10-11 13:48:23.448  9789 10429 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:23.448  9789 10427 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-11 13:48:23.448  9789 10427 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:23.449  9789 10429 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-11 13:48:23.449  9789 10427 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:23.449  9789 10427 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-11 13:48:23.451  9789 10431 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 232, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.451  9789 10431 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:23.451  9789 10431 D io.jxcore.node.StreamCopyingThread:  id: 80
,10-11 13:48:23.451  9789 10433 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 234, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.451  9789 10433 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:23.451  9789 10433 D io.jxcore.node.StreamCopyingThread:  id: 81
,10-11 13:48:23.451  9789 10432 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 233, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.451  9789 10432 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:23.451  9789 10432 D io.jxcore.node.StreamCopyingThread:  id: 80
,10-11 13:48:23.451  9789 10434 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 235, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.451  9789 10434 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:23.451  9789 10434 D io.jxcore.node.StreamCopyingThread:  id: 81
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 233, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread:  id: 80
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 235, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread:  id: 81
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread:  id: 80
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread:  id: 81
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:23.452  9789 10432 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-11 13:48:23.452  9789 10434 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 233, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:23.452  9789 10432 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 235, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:23.452  9789 10434 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-11 13:48:23.454  9789 10433 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 234, thread name: OutgoingSocketThrea,d/Sender): Socket closed
10-11 13:48:23.454  9789 10431 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 232, thread name: IncomingSocketThread/Sender): Socket closed
10-11 13:48:23.454  9789 10433 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 234, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.454  9789 10433 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:23.454  9789 10433 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-11 13:48:23.454  9789 10433 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-11 13:48:23.454  9789 10431 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 232, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.454  9789 10431 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:23.454  9789 10431 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
10-11 13:48:23.454  9789 10433 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-11 13:48:23.454  9789 10431 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-11 13:48:23.455  9789 10431 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-11 13:48:23.455  9789 10433 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 234, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.455  9789 10433 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:23.455  9789 10433 D io.jxcore.node.StreamCopyingThread:  id: 81 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-11 13:48:23.455  9789 10431 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 232, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:23.455  9789 10431 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:23.455  9789 10431 D io.jxcore.node.StreamCopyingThread:  id: 80 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,10-11 13:48:23.959  3701  3763 I ActivityManager: Waited long enough for: ServiceRecord{5ac8b3e u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,10-11 13:48:24.276  3701  4540 I ActivityManager: KPU : put [com.samsung.svoice.sync] : 17452 K
10-11 13:48:24.276  3701  4540 I ActivityManager: Killing 9404:com.samsung.svoice.sync/u0a40 (adj 906): DHA:empty #33
,10-11 13:48:24.324  3701  4887 D ActivityManager: cleanUpApplicationRecord -- 9404
,10-11 13:48:24.325  4803  4817 D ForegroundUtils: could not check pending caller
,10-11 13:48:24.785  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:48:24.788 10214 10214 I wpa_supplicant: nl80211: Received scan results (30 BSSes)
10-11 13:48:24.789  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:24.790  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:24.794  3701  3957 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@69fddda
,10-11 13:48:25.168  3701  4927 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:48:25.977  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:25.978  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:26.076  4648  4648 D io_stats: !@   8,0 r 26141 2315720 w 5453 211788 d 698 75200 f 2199 2199 iot 12110 11103 th 471404 0 0 pt 0 inp 0 0 217.211
,10-11 13:48:26.347  3701 10436 D WifiMHD::s: req(2):1, 7, 1
,10-11 13:48:26.351  3701 10436 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-11 13:48:26.352  3701 10436 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-11 13:48:26.356  3294  3781 D EnterpriseController: netId is 0
10-11 13:48:26.356  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,10-11 13:48:26.356  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:26.805  4070  4070 D ShortcutManager: onReceive : android.intent.action.PACKAGE_CHANGED
,10-11 13:48:26.825  3701  3884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-11 13:48:26.840  3701  3813 D PackageManager: com.google.android.gms.permission.CAR_FUEL is a new runtime permission
10-11 13:48:26.841  3701  3813 D PackageManager: com.google.android.gms.permission.CAR_MILEAGE is a new runtime permission
10-11 13:48:26.841  3701  3813 D PackageManager: com.google.android.gms.permission.CAR_SPEED is a new runtime permission
10-11 13:48:26.841  3701  3813 D PackageManager: com.google.android.gms.permission.CAR_VENDOR_EXTENSION is a new runtime permission
10-11 13:48:26.841  3701  3813 D PackageManager: Permission Group is null for permission com.sec.smartcard.permission.SMARTCARD_ADAPTER
10-11 13:48:26.841  3701  3813 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_READ
10-11 13:48:26.841  3701  3813 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_WRITE
10-11 13:48:26.842  3701  3813 D ApplicationPolicy: groups[android.permission-group.SMS, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.LOCATION, android.permission-group.MESSAGES, android.permission-group.SMS, android.permission-group.SENSORS, android.permission-group.LOCATION, android.permission-group.SMS, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.MESSAGES, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.SMS, android.permission-group.PHONE, android.permission-group.CONTACTS, android.permission-group.CAMERA, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.SMS, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, android.permission-group.CONTACTS, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.STORAGE, com.samsung.android.memo.EXTRA_READ, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.MICROPHONE, android.permission-group.CONTACTS, com.samsung.android.memo.EXTRA_WRITE, android.permission-group.PHONE]
10-11 13:48:26.842  3701  3813 D ApplicationPolicy: Permission GRoups [android.permission-group.CONTACTS, android.permission-group.CALENDAR, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.MICROPHONE, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, com.samsung.android.memo.EXTRA_READ, com.samsung.android.memo.EXTRA_WRITE]
,10-11 13:48:26.846  4803  4803 D RegisteredServicesCache: invalidateCache
10-11 13:48:26.854  3701  4542 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5148, uid=10124 that is not exported from uid 10122
,10-11 13:48:26.863  4803  4803 D ApduServiceInfo: seId: 0
,10-11 13:48:26.867  4803  4803 D ApduServiceInfo: seId: 0
,10-11 13:48:26.867  4803  4803 D RegisteredOthersCache: start invalidate
10-11 13:48:26.868  4803  4803 D RegisteredOthersCache: update valid otherService: ComponentInfo{com.google.android.apps.walletnfcrel/com.google.commerce.tapandpay.android.hce.service.ValuableApduService} AIDs: [4F53452E5641532E3031, A000000476D0000101, A000000476D0000111]
10-11 13:48:26.868  4803  4803 D RegisteredOthersCache: Existed other serivcee
10-11 13:48:26.868  4803  4803 D RegisteredPoliciesCache: invalidate
,10-11 13:48:26.868  4803  4803 D RegisteredAidCache: onServicePolicyUpdated
10-11 13:48:26.868  4803  4803 D RegisteredAidCache: generateAidPolicyMapLocked
10-11 13:48:26.868  4803  4803 D AidPolicyManager: print policy
10-11 13:48:26.868  4803  4803 D AidPolicyManager: table size : 0
,10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
,10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.877  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidPolicyManager: There are not service policy for this aid
10-11 13:48:26.878  4803  4803 D AidRoutingManager: Override power table is not changed
,10-11 13:48:26.882  4803  4803 D RegisteredNfcFServicesCache: Service unchanged, not updating
,10-11 13:48:26.886  4044  4044 D CarrierSvcBindHelper: No carrier app for: 0
,10-11 13:48:26.889  4803  4803 D RegisteredComponentCache: Collect Tech packages for Knox
,10-11 13:48:26.924  3701  3813 D PackageManager: com.google.android.gms.permission.CAR_FUEL is a new runtime permission
10-11 13:48:26.924  3701  3813 D PackageManager: com.google.android.gms.permission.CAR_MILEAGE is a new runtime permission
,10-11 13:48:26.924  3701  3813 D PackageManager: com.google.android.gms.permission.CAR_SPEED is a new runtime permission
10-11 13:48:26.924  3701  3813 D PackageManager: com.google.android.gms.permission.CAR_VENDOR_EXTENSION is a new runtime permission
10-11 13:48:26.924  3701  3813 D PackageManager: Permission Group is null for permission com.sec.smartcard.permission.SMARTCARD_ADAPTER
10-11 13:48:26.924  3701  3813 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_READ
10-11 13:48:26.924  3701  3813 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_WRITE
10-11 13:48:26.924  3701  3813 D ApplicationPolicy: groups[android.permission-group.SMS, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.LOCATION, android.permission-group.MESSAGES, android.permission-group.SMS, android.permission-group.SENSORS, android.permission-group.LOCATION, android.permission-group.SMS, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.MESSAGES, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.SMS, android.permission-group.PHONE, android.permission-group.CONTACTS, android.permission-group.CAMERA, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.SMS, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, android.permission-group.CONTACTS, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.STORAGE, com.samsung.android.memo.EXTRA_READ, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.MICROPHONE, android.permission-group.CONTACTS, com.samsung.android.memo.EXTRA_WRITE, android.permission-group.PHONE]
10-11 13:48:26.924  3701  3813 D ApplicationPolicy: Permission GRoups [android.permission-group.CONTACTS, android.permission-group.CALENDAR, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.MICROPHONE, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, com.samsung.android.memo.EXTRA_READ, com.samsung.android.memo.EXTRA_WRITE]
,10-11 13:48:26.948  3701  3701 D UcmService: onReceive android.intent.action.PACKAGE_CHANGED
10-11 13:48:26.948  3701  3701 D UcmService: Package update in userId-0 and uid-10019
10-11 13:48:26.948  3701  3701 D UcmService: isUCMPlugin pkgName-com.google.android.gsf.login
10-11 13:48:26.948  3701  3701 D UcmService: enforcePermission : com.google.android.gsf.login
10-11 13:48:26.948  3701  3701 D UcmService: isUCMPlugin pkgName-com.google.android.gsf
,10-11 13:48:26.948  3701  3701 D UcmService: enforcePermission : com.google.android.gsf
10-11 13:48:26.948  3701  3701 D UcmService: isUCMPlugin pkgName-com.google.android.backuptransport
10-11 13:48:26.948  3701  3701 D UcmService: enforcePermission : com.google.android.backuptransport
10-11 13:48:26.949  3701  3701 D UcmService: isUCMPlugin pkgName-com.google.android.gms
10-11 13:48:26.949  3701  3701 D UcmService: enforcePermission : com.google.android.gms
10-11 13:48:26.949  3701  3701 D UcmService: isPCSCService pkgName-com.google.android.gsf.login
10-11 13:48:26.949  3701  3701 D UcmService: isPCSCService pkgName-com.google.android.gsf
10-11 13:48:26.949  3701  3701 D UcmService: isPCSCService pkgName-com.google.android.backuptransport
10-11 13:48:26.949  3701  3701 D UcmService: isPCSCService pkgName-com.google.android.gms
10-11 13:48:26.949  3701  3701 D UcmService: Updated app is not valid UCM plugin so ignoring refresh agent list....
10-11 13:48:26.950  3701  3701 W PackageManager: STAHP USING HIDDEN APIS KTHX
,10-11 13:48:26.952  3701  3701 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x44000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-11 13:48:26.952  3701  3701 I BackupManagerService: Package com.google.android.gms changed; rechecking
10-11 13:48:26.952  3701  3701 I BackupManagerService:    * com.google.android.gms.mdm.receivers.ConnectivityReceiver
10-11 13:48:26.952  3701  3701 I BackupManagerService: Checking need to rebind com.google.android.gms.backup.BackupTransportService
,10-11 13:48:27.111  3701  3762 W SearchableInfo: Invalid searchable metadata for com.samsung.android.themestore/.activity.WTSearchActivity: Search label must be a resource reference.
,10-11 13:48:27.130  3701  3710 I art     : Background sticky concurrent mark sweep GC freed 226175(12MB) AllocSpace objects, 32(736KB) LOS objects, 26% free, 41MB/57MB, paused 3.129ms total 123.527ms
,10-11 13:48:27.150  3701  3762 I PrintManagerService: onPackageModified com.google.android.gms
,10-11 13:48:27.153  3701  3762 I PrintManagerService:  - hadPrintService false
10-11 13:48:27.153  3701  3762 I PrintManagerService:  - hasPrintService false
10-11 13:48:27.153  3701  3762 I RemotePrintSpooler: pruneApprovedPrintServices
,10-11 13:48:27.153  3701  3762 I RemotePrintSpooler: [user: 0] bindLocked() 
10-11 13:48:27.153  3701  3762 I RemotePrintSpooler: bindLocked binding service java.lang.Object@8828d1a
,10-11 13:48:27.156  3701  3762 D MountService: getExternalStorageMountMode : 1
10-11 13:48:27.156  3701  3762 D MountService: getExternalStorageMountMode : 3
10-11 13:48:27.156  3701  3762 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10138, packageName : com.android.printspooler
,10-11 13:48:27.186 10438 10438 E Zygote  : v2
10-11 13:48:27.186 10438 10438 I libpersona: KNOX_SDCARD checking this for 10138
10-11 13:48:27.186 10438 10438 I libpersona: KNOX_SDCARD not a persona
,10-11 13:48:27.187 10438 10438 E Zygote  : accessInfo : 0
10-11 13:48:27.189  3701  3762 I ActivityManager: Start proc 10438:com.android.printspooler/u0a138 for service com.android.printspooler/.model.PrintSpoolerService
10-11 13:48:27.189  3701  3762 I RemotePrintSpooler: bindLocked waiting. remainingMillis: 8000
,10-11 13:48:27.192 10438 10438 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-11 13:48:27.194 10438 10438 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.printspooler 
,10-11 13:48:27.216 10438 10438 D TimaKeyStoreProvider: TimaSignature is unavailable
10-11 13:48:27.216 10438 10438 D ActivityThread: Added TimaKeyStore provider
,10-11 13:48:27.219  3701  4927 I ActivityManager: DSS on for com.android.printspooler and scale is 1.0
,10-11 13:48:27.227  3701  4927 I ActivityManager: KPU : put [com.sec.android.app.sbrowser] : 17684 K
10-11 13:48:27.227  3701  4927 I ActivityManager: Killing 9460:com.sec.android.app.sbrowser/u0a134 (adj 906): DHA:empty #33
,10-11 13:48:27.253  3701  3728 D ActivityManager: cleanUpApplicationRecord -- 9460
,10-11 13:48:27.255  4803  4817 D ForegroundUtils: could not check pending caller
,10-11 13:48:27.270 10438 10438 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-11 13:48:27.280 10438 10438 D PrintSpoolerService: No existing print spooler state.
,10-11 13:48:27.282  3701  3701 I RemotePrintSpooler: onServiceConnected
,10-11 13:48:27.283  3701  3762 I RemotePrintSpooler: [user: 0] pruneApprovedPrintServices()
,10-11 13:48:27.296  4765  4765 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,10-11 13:48:27.322  4961  4961 D Launcher.Model: onPackageChanged:com.google.android.gms user:UserHandle{0}
10-11 13:48:27.322  4961  4961 D Launcher.Model: isValidStateInKnoxMode:false user:UserHandle{0}
10-11 13:48:27.322  4961  4961 E Launcher.Model: onPackageChanged :com.google.android.gms
,10-11 13:48:27.323  3701  4180 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-11 13:48:27.325  4961  5056 D LauncherApps: getActivityList callingUid: 0 user: 0
10-11 13:48:27.328  4961  5056 D MenuAppLoader: There is no package to remove in mApps:com.google.android.gms
,10-11 13:48:27.330  4961  5056 D LauncherApps: getActivityList callingUid: 0 user: 0
10-11 13:48:27.331  3701  4541 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{852ec57: PendingIntentRecord{76d082d com.google.android.gms broadcastIntent}}
10-11 13:48:27.332  4961  5056 D Launcher.MenuWidgetsLoader: packageChanged : com.google.android.gms
10-11 13:48:27.333  4961  4961 D Launcher.MenuWidgetsLoader: MenuWidgetLoade-loadMenuWidgets : false
10-11 13:48:27.333  3701  4180 D SecContentProvider: called from com.google.uid.shared:10019
10-11 13:48:27.334  4961  4961 D MenuView: packageChanged:
10-11 13:48:27.334  3701  4927 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{19b5344: PendingIntentRecord{cf982f3 com.google.android.gms broadcastIntent}}
10-11 13:48:27.334  4961  4961 D MenuView: packagesChanged:2
,10-11 13:48:27.334  4961  4961 D MenuView: frag:null
,10-11 13:48:27.334  4961  4961 D MenuView: frag:MenuAppsGridFragment{feed8a4 #0 id=0x1020011 APPS}
10-11 13:48:27.336  3701  4540 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{d195c2d: PendingIntentRecord{2befa29 com.google.android.gms broadcastIntent}}
10-11 13:48:27.337  3701  4887 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{5b02562: PendingIntentRecord{69f5b4f com.google.android.gms broadcastIntent}}
,10-11 13:48:27.344  3701  3915 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{32ff6f3: PendingIntentRecord{e240fe5 com.google.android.gms broadcastIntent}}
10-11 13:48:27.349  3701  3729 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{b9c5fb0: PendingIntentRecord{b205d6b com.google.android.gms broadcastIntent}}
10-11 13:48:27.352  3701  4915 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{8dc8e29: PendingIntentRecord{ac561 com.google.android.gms broadcastIntent}}
,10-11 13:48:27.354  4961 10452 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-start : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@1ef70c , false
10-11 13:48:27.354  3701  4541 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{5ef35ae: PendingIntentRecord{c656547 com.google.android.gms broadcastIntent}}
10-11 13:48:27.355  3701  4921 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{bc90f4f: PendingIntentRecord{d4d569d com.google.android.gms broadcastIntent}}
,10-11 13:48:27.359  3701  3915 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4765 / op:PendingIntent{d5fc6dc: PendingIntentRecord{8090ee3 com.google.android.gms broadcastIntent}}
,10-11 13:48:27.391  3701  3762 D LocationProviderProxy: applying state to connected service
10-11 13:48:27.392  3701  3762 D LocationProviderProxy: applying state to connected service
,10-11 13:48:27.419  4765  5114 W GCoreFlp: No location to return for getLastLocation()
,10-11 13:48:27.420  4765  5114 W GCoreFlp: No location to return for getLastLocation()
,10-11 13:48:27.446  4961  4961 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-done : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@1ef70c , update : false , size : 48
,10-11 13:48:28.439  9789  9853 I io.jxcore.node.IncomingSocketThreadTest: IncomingSocketThreadTest failed, attempts left 8
10-11 13:48:28.439  9789  9853 I io.jxcore.node.IncomingSocketThreadTest: outgoingOutputStream.toString() = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
10-11 13:48:28.439  9789  9853 I io.jxcore.node.IncomingSocketThreadTest: textIncoming = Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed.
,10-11 13:48:28.440  9789  9853 I !!      :  finally closed
,10-11 13:48:28.448  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,10-11 13:48:28.449  9789  9853 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-11 13:48:28.453  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,10-11 13:48:28.453  9789  9853 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-11 13:48:28.457  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,10-11 13:48:28.462  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,10-11 13:48:28.463  9789  9853 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@e18c3d6 Bundle[{}]
,10-11 13:48:28.467  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
10-11 13:48:28.468  9789  9853 I io.jxcore.node.LifeCycleMonitor: start: OK
10-11 13:48:28.468  9789  9853 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-11 13:48:28.472  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
10-11 13:48:28.472  9789  9853 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-11 13:48:28.476  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
10-11 13:48:28.477  9789  9853 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-11 13:48:28.479  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
10-11 13:48:28.479  9789  9853 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-11 13:48:28.482  9789  9853 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,10-11 13:48:28.482  9789  9853 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-11 13:48:28.485  9789  9853 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,10-11 13:48:28.487  9789  9853 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,10-11 13:48:28.490  9789  9853 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,10-11 13:48:28.492  9789  9853 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,10-11 13:48:28.498  9789  9853 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,10-11 13:48:28.500  9789  9853 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,10-11 13:48:28.502  9789  9853 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,10-11 13:48:28.505  9789 10453 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
10-11 13:48:28.506  9789 10453 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-11 13:48:28.508  3294  3781 D EnterpriseController: netId is 0
10-11 13:48:28.508  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10033
10-11 13:48:28.509  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:48:28.512  9789 10455 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
10-11 13:48:28.512  9789 10455 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-11 13:48:28.512  9789 10455 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:28.512  9789 10453 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
10-11 13:48:28.512  9789 10453 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-11 13:48:28.512  9789 10453 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:28.512  9789 10455 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-11 13:48:28.513  9789 10455 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-11 13:48:28.513  9789 10453 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-11 13:48:28.514  9789 10457 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 239, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.514  9789 10457 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:28.514  9789 10457 D io.jxcore.node.StreamCopyingThread:  id: 83
10-11 13:48:28.514  9789 10458 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 241, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.514  9789 10458 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:28.514  9789 10458 D io.jxcore.node.StreamCopyingThread:  id: 83
,10-11 13:48:28.526  9789 10453 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
10-11 13:48:28.526  9789 10459 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 240, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.526  9789 10459 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:28.526  9789 10459 D io.jxcore.node.StreamCopyingThread:  id: 84
,10-11 13:48:28.533  9789 10460 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 242, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.533  9789 10460 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:28.533  9789 10460 D io.jxcore.node.StreamCopyingThread:  id: 84
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 242, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread:  id: 84
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread:  id: 84
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:28.534  9789 10460 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 242, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:28.534  9789 10460 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-11 13:48:28.534  9789 10459 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 240, thread name: OutgoingSocketThread/Sender): Socket closed
,10-11 13:48:28.535  9789 10459 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 240, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.535  9789 10459 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:28.535  9789 10459 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 24576 and the total number of bytes written 24576
10-11 13:48:28.535  9789 10459 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-11 13:48:28.535  9789 10459 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-11 13:48:28.535  9789 10459 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 240, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.535  9789 10459 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:28.535  9789 10459 D io.jxcore.node.StreamCopyingThread:  id: 84 .During the lifetime of the thread the total number of bytes read was 24576 and the total number of bytes written 24576
10-11 13:48:28.535  9789 10457 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 239, thread name: IncomingSocketThread/Sender): Connection reset
10-11 13:48:28.536  9789 10457 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 239, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.536  9789 10457 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:28.536  9789 10457 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-11 13:48:28.536  9789 10457 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Connection reset
10-11 13:48:28.536  9789 10457 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-11 13:48:28.536  9789 10457 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 239, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.536  9789 10457 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:28.536  9789 10457 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-11 13:48:28.536  9789 10458 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 241, thread name: IncomingSocketThread/Receiver): Broken pipe
10-11 13:48:28.537  9789 10458 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 241, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.537  9789 10458 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:28.537  9789 10458 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 135168 and the total number of bytes written 131072
10-11 13:48:28.537  9789 10458 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: Broken pipe", this is likely due to peer having disconnected
10-11 13:48:28.537  9789 10458 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
10-11 13:48:28.537  9789 10458 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 241, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:28.537  9789 10458 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-11 13:48:28.537  9789 10458 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 135168 and the total number of bytes written 131072
,10-11 13:48:28.913  3701  3864 D SamsungAlarmManager: Expired : 4
10-11 13:48:28.914  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135727, SetElapsed=758350, nowELAPSED=220050
,10-11 13:48:28.914  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@8bb4b85 alarm=Alarm{2c482e3 type 2 when 220049 android}
,10-11 13:48:28.918  3701  3930 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,10-11 13:48:28.922 10214 10214 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,10-11 13:48:28.922 10214 10214 I wpa_supplicant: P2P: Current p2p state = IDLE
,10-11 13:48:28.924  3701  3930 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T134844 - CU:1000/CP:3701
10-11 13:48:28.928  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134844, SetElapsed=236055, nowELAPSED=220064
,10-11 13:48:28.935  3701  3957 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T134843 - CU:1000/CP:3701
,10-11 13:48:28.938 10214 10214 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-11 13:48:28.997  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:28.997  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:31.081  4648  4648 D io_stats: !@   8,0 r 26147 2315744 w 5455 211824 d 698 75200 f 2201 2201 iot 12110 11105 th 468328 0 0 pt 0 inp 0 0 222.216
,10-11 13:48:31.635  3701  5735 D SSRM:f  : SIOP:: AP = 310, PST = 312 (W:10), CP = 262, CUR = 192, LCD = 57
,10-11 13:48:32.017  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:32.017  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:32.296  3701  4927 I RemotePrintSpooler: [user: 0] unbindLocked()
,10-11 13:48:32.316  3701  4913 I ActivityManager: KPU : put [com.google.android.gm] : 25848 K
10-11 13:48:32.316  3701  4913 I ActivityManager: Killing 8898:com.google.android.gm/u0a108 (adj 906): DHA:empty #33
10-11 13:48:32.318  3701  4913 I ActivityManager: KPU : put [com.wssnps] : 19988 K
10-11 13:48:32.318  3701  4913 I ActivityManager: Killing 9503:com.wssnps/1000 (adj 906): DHA:empty #33
10-11 13:48:32.320  3701  4913 I ActivityManager: KPU : put [com.sec.android.widgetapp.samsungapps] : 20020 K
10-11 13:48:32.320  3701  4913 I ActivityManager: Killing 9478:com.sec.android.widgetapp.samsungapps/u0a105 (adj 906): DHA:empty #33
,10-11 13:48:32.373  3701  3701 D UsbMonitorService: readUsbState++
10-11 13:48:32.374  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-11 13:48:32.374  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:48:32.374  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:48:32.398  3701  3728 D ActivityManager: cleanUpApplicationRecord -- 9503
10-11 13:48:32.399  4803  4819 D ForegroundUtils: could not check pending caller
,10-11 13:48:32.405  3701  4921 D ActivityManager: cleanUpApplicationRecord -- 9478
,10-11 13:48:32.408  4803  6438 D ForegroundUtils: could not check pending caller
10-11 13:48:32.411  3701  4928 D ActivityManager: cleanUpApplicationRecord -- 8898
,10-11 13:48:32.418  4803  4817 D ForegroundUtils: could not check pending caller
,10-11 13:48:32.930  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:48:32.933 10214 10214 I wpa_supplicant: nl80211: Received scan results (25 BSSes)
,10-11 13:48:32.934  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:32.934  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:32.939  3701  3957 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@6d85399
,10-11 13:48:34.010  9789  9853 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,10-11 13:48:34.014  9789  9853 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,10-11 13:48:34.018  9789  9853 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,10-11 13:48:34.498  3701  4459 E Watchdog: !@Sync 7 [11_paź_13_48_34.497]
,10-11 13:48:34.544  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:34.557  3701  3763 I ActivityManager: KPU : put [com.sec.android.app.shealth] : 25808 K
10-11 13:48:34.557  3701  3763 I ActivityManager: Killing 7690:com.sec.android.app.shealth/u0a36 (adj 906): DHA:empty #33
,10-11 13:48:34.609  3701  3919 D ActivityManager: cleanUpApplicationRecord -- 7690
,10-11 13:48:34.611  4803  4817 D ForegroundUtils: could not check pending caller
,10-11 13:48:35.028  9789  9853 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,10-11 13:48:35.036  9789  9853 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,10-11 13:48:35.040  9789  9853 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,10-11 13:48:35.041  9789  9853 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 250)
,10-11 13:48:35.045  9789  9853 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,10-11 13:48:35.046  9789  9853 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-11 13:48:35.046  9789  9853 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 251)
10-11 13:48:35.047  9789  9794 I art     : Do partial code cache collection, code=19KB, data=30KB
10-11 13:48:35.047  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:35.048  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
10-11 13:48:35.048  9789  9794 I art     : After code cache collection, code=18KB, data=29KB
10-11 13:48:35.048  9789  9794 I art     : Increasing code cache capacity to 128KB
10-11 13:48:35.049  9789  9853 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
10-11 13:48:35.051  9789  9853 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,10-11 13:48:35.054  9789  9853 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,10-11 13:48:35.056  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-11 13:48:35.056  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8839977 added. We now have 2 listener(s)
10-11 13:48:35.056  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8839977 added. We now have 3 listener(s)
10-11 13:48:35.056  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-11 13:48:35.060  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-11 13:48:35.060  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-11 13:48:35.060  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,10-11 13:48:35.061  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-11 13:48:35.061  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d4c9e4 added. We now have 4 listener(s)
10-11 13:48:35.061  9789  9853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-11 13:48:35.062  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-11 13:48:35.070  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.075  9789  9853 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,10-11 13:48:35.076  9789  9853 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
10-11 13:48:35.077  9789  9853 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
10-11 13:48:35.077  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,10-11 13:48:35.077  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:48:35.080  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
10-11 13:48:35.080  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,10-11 13:48:35.081  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.081  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:48:35.084  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
10-11 13:48:35.085  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,10-11 13:48:35.085  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.085  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-11 13:48:35.085  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-11 13:48:35.086  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-11 13:48:35.086  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-11 13:48:35.087  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-11 13:48:35.088  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-11 13:48:35.088  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-11 13:48:35.088  9789 10463 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-11 13:48:35.088  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-11 13:48:35.089  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-11 13:48:35.089  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-11 13:48:35.089  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-11 13:48:35.089  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-11 13:48:35.089  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-11 13:48:35.091  9789 10463 D BluetoothSocket: bindListen(): myUserId = 0
,10-11 13:48:35.091  9789 10463 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-11 13:48:35.095  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-11 13:48:35.096  9789  9853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-11 13:48:35.096  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-11 13:48:35.098  9789 10463 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-11 13:48:35.098  9789 10463 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@fde0d02, port: 6, type: 1, local socket address: null, socket type: 0
,10-11 13:48:35.099  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.101  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.102  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.105  9789  9853 D BluetoothAdapter: isSecureModeEnabled
,10-11 13:48:35.106  9917  9929 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:48:35.107  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.107  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-11 13:48:35.108  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.109  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.110  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-11 13:48:35.110  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-11 13:48:35.110  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,10-11 13:48:35.112  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.116  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.116  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.117  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-11 13:48:35.117  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,10-11 13:48:35.117  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "c1e767dc-b61f-4a4c-b0d7-5c4c58423897", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-11 13:48:35.117  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 4A 3E
,10-11 13:48:35.118  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:48:35.118  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-11 13:48:35.119  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.120  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.120  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-11 13:48:35.120  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-11 13:48:35.121  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.121  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.122  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.124  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.125  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:35.125  9789  9853 D BluetoothAdapter: isSecureModeEnabled
10-11 13:48:35.126  9917  9938 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:48:35.126  9789  9853 D BluetoothLeAdvertiser: start advertising
,10-11 13:48:35.127  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.132  9917  9938 D BtGatt.GattService: registerClient() - UUID=f8d9ab82-c941-4237-9579-6e234706d969
,10-11 13:48:35.212  3701  4921 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:48:35.235  9917  9937 D BtGatt.GattService: onClientRegistered() - UUID=f8d9ab82-c941-4237-9579-6e234706d969, clientIf=5, status=0
,10-11 13:48:35.237  9789  9801 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-11 13:48:35.241  9917  9928 E BtGatt.ContextMap: Context not found for ID 5
10-11 13:48:35.242  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,10-11 13:48:35.243  9917  9954 D BtGatt.AdvertiseManager: message : 0
,10-11 13:48:35.245  9917  9954 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-11 13:48:35.246  9917  9954 D BtGatt.AdvertiseManager: size of list is =0
,10-11 13:48:35.254  9917  9954 D BtGatt.AdvertiseManager: starting advertising
,10-11 13:48:35.259  9917  9954 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-11 13:48:35.262  9917  9971 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-11 13:48:35.274  9917  9937 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-11 13:48:35.277  9917  9954 D BtGatt.AdvertiseManager: starting multi advertising
,10-11 13:48:35.286  9917  9937 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-11 13:48:35.286  9917  9954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-11 13:48:35.287  9917  9954 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-11 13:48:35.287  9917  9954 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
10-11 13:48:35.287  9917  9954 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,10-11 13:48:35.288  9789  9800 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-11 13:48:35.289  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.290  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.290  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-11 13:48:35.291  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.292  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.293  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.294  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.294  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.295  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-11 13:48:35.298  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-11 13:48:35.298  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.302  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.303  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.304  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.304  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-11 13:48:35.306  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,10-11 13:48:35.307  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:35.307  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-11 13:48:35.308  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.309  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.310  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:35.310  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.310  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-11 13:48:35.310  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-11 13:48:35.311  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-11 13:48:35.311  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.311  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.312  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.312  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-11 13:48:35.319  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.320  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-11 13:48:35.320  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.321  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,10-11 13:48:35.322  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-11 13:48:35.810  9789  9853 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-11 13:48:35.811  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-11 13:48:35.811  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-11 13:48:35.811  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-11 13:48:35.811  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-11 13:48:35.812  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-11 13:48:35.812  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-11 13:48:35.813  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-11 13:48:35.813  9789 10463 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-11 13:48:35.813  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-11 13:48:35.813  9789 10463 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-11 13:48:35.813  9789 10463 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-11 13:48:35.813  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-11 13:48:35.814  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-11 13:48:35.814  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-11 13:48:35.815  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.816  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-11 13:48:35.816  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-11 13:48:35.817  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.818  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.819  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.820  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.824  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.827  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:35.827  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-11 13:48:35.831  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.835  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:35.835  9789  9853 D BluetoothLeScanner: could not find callback wrapper
10-11 13:48:35.835  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-11 13:48:35.836  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.837  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.839  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.839  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-11 13:48:35.840  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.844  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:35.848  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:35.848  9789  9853 D BluetoothLeAdvertiser: stop advertising
,10-11 13:48:35.850  9917  9939 E BtGatt.ContextMap: Context not found for ID 5
10-11 13:48:35.851  9917  9954 D BtGatt.AdvertiseManager: message : 1
10-11 13:48:35.851  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,10-11 13:48:35.853  9917  9954 D BtGatt.AdvertiseManager: stop advertise for client =  5
10-11 13:48:35.853  9917  9954 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-11 13:48:35.857  9917  9954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-11 13:48:35.867  9917  9937 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-11 13:48:35.868  9917  9937 D BtGatt.GattService: Client app is not null!
,10-11 13:48:35.869  9789  9801 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-11 13:48:35.871  9917  9929 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-11 13:48:35.873  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-11 13:48:35.874  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.875  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-11 13:48:35.876  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.877  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.878  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.878  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-11 13:48:35.878  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-11 13:48:35.881  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,10-11 13:48:35.881  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.887  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.887  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-11 13:48:35.888  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:35.889  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:35.890  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-11 13:48:35.890  9789  9789 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-11 13:48:35.891  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-11 13:48:35.891  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-11 13:48:35.892  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:48:35.892  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-11 13:48:35.892  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-11 13:48:35.894  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:35.895  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.895  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-11 13:48:35.895  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-11 13:48:35.896  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.897  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-11 13:48:35.897  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,10-11 13:48:35.898  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-11 13:48:36.087  4648  4648 D io_stats: !@   8,0 r 26147 2315744 w 5468 211992 d 699 75204 f 2205 2205 iot 12120 11110 th 478140 0 0 pt 0 inp 0 0 227.222
,10-11 13:48:36.400  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-11 13:48:38.080  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:38.080  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:38.735  3701  4921 I ActivityManager: KPU : put [com.samsung.android.app.watchmanager:contentprovider] : 20236 K
10-11 13:48:38.735  3701  4921 I ActivityManager: Killing 9520:com.samsung.android.app.watchmanager:contentprovider/u0a18 (adj 906): DHA:empty #33
,10-11 13:48:38.778  3701  4181 D ActivityManager: cleanUpApplicationRecord -- 9520
,10-11 13:48:38.780  4803  4819 D ForegroundUtils: could not check pending caller
,10-11 13:48:38.898  9789  9853 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,10-11 13:48:38.899  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-11 13:48:38.900  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-11 13:48:38.900  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-11 13:48:38.900  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-11 13:48:38.901  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-11 13:48:38.901  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-11 13:48:38.913  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-11 13:48:38.914  9789  9853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-11 13:48:38.914  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-11 13:48:38.922  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.926  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.929  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.938  9789  9853 D BluetoothAdapter: isSecureModeEnabled
,10-11 13:48:38.939  9917  9929 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:48:38.941  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:38.941  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-11 13:48:38.945  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.949  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.950  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-11 13:48:38.950  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-11 13:48:38.950  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,10-11 13:48:38.958  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.961  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.971  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.974  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.978  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:38.979  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-11 13:48:38.979  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-11 13:48:38.979  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 43005
,10-11 13:48:38.981  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=43005, mManufacturerData=null, mManufacturerDataMask=null]
,10-11 13:48:38.983  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:38.983  9789  9853 D BluetoothLeScanner: Start Scan
,10-11 13:48:38.986  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.989  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:38.990  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.995  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:38.998  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:39.010  9917  9938 D BtGatt.GattService: registerClient() - UUID=51124e3b-6448-4a41-b4a0-8dfb3c87c5fa
,10-11 13:48:39.115  9917  9937 D BtGatt.GattService: onClientRegistered() - UUID=51124e3b-6448-4a41-b4a0-8dfb3c87c5fa, clientIf=5, status=0
,10-11 13:48:39.116  9789  9801 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,10-11 13:48:39.117  9917  9928 D BtGatt.GattService: start scan with filters
,10-11 13:48:39.122  9917  9928 D BtGatt.GattService: getScanSettings
,10-11 13:48:39.125  9917  9928 D BtGatt.GattService: Is it foreground application = true
10-11 13:48:39.125  9917  9928 D BtGatt.GattService: not a background application
,10-11 13:48:39.138  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,10-11 13:48:39.139  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-11 13:48:39.139  9917  9965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:39.140  9917  9955 D BtGatt.ScanManager: handling starting scan
10-11 13:48:39.140  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:39.140  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-11 13:48:39.141  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:39.142  9917  9955 D BluetoothAdapter: STATE_ON
10-11 13:48:39.142  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-11 13:48:39.144  9917  9955 D BluetoothAdapter: STATE_ON
10-11 13:48:39.144  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:39.145  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:48:39.145  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-11 13:48:39.145  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-11 13:48:39.146  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:48:39.147  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-11 13:48:39.147  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:48:39.149  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
10-11 13:48:39.153  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-11 13:48:39.155  9917  9937 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-11 13:48:39.155  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:39.155  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:39.155  9917  9955 D BtGatt.ScanManager: set filter index= 6 for clientIf= 5
,10-11 13:48:39.156  9917  9955 D BtGatt.ScanManager: High Rssi Filter value is = -128
,10-11 13:48:39.156  9917  9955 D BtGatt.ScanManager: Low Rssi Filter value is = -128
,10-11 13:48:39.156  9917  9955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
,10-11 13:48:39.168  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-11 13:48:39.168  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:39.169  9917  9955 D BtGatt.ScanManager: Starting BLE batch scan
10-11 13:48:39.169  9917  9955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-11 13:48:39.171  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:39.171  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-11 13:48:39.172  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:39.173  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:39.174  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-11 13:48:39.182  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-11 13:48:39.182  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-11 13:48:39.183  9917  9937 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-11 13:48:39.183  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-11 13:48:39.183  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-11 13:48:39.184  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-11 13:48:39.191  9917  9937 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-11 13:48:39.192  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-11 13:48:39.193  3701  4540 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{1e7dcd1: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
,10-11 13:48:39.203  3701  4915 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134839 - CU:1002/CP:9917
,10-11 13:48:39.204  3701  4915 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134840, SetElapsed=231331, nowELAPSED=230340
,10-11 13:48:39.685  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-11 13:48:39.686  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-11 13:48:39.686  9789  9789 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-11 13:48:40.195  3701  3864 D SamsungAlarmManager: Expired : 4
10-11 13:48:40.196  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134844, SetElapsed=236055, nowELAPSED=231332
,10-11 13:48:40.196  3701  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{fa6e336 type 2 when 230831 com.android.bluetooth}
,10-11 13:48:40.202  9917  9917 D BtGatt.ScanManager: awakened up at time 231338
,10-11 13:48:40.204  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-11 13:48:40.229  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,10-11 13:48:40.229  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-11 13:48:40.229  9917  9937 D BtGatt.GattService: current time is 231366092257
10-11 13:48:40.229  9917  9937 D BtGatt.GattService: Batch record : [-30, -13, -36, -52, 124, 102, 1, -128, -60, 9, 0, 29, 17, 7, -105, 56, 66, 88, 76, 92, -41, -80, 76, 74, 31, -74, -36, 103, -25, -63, 10, 22, -36, 103, 4, 68, 120, 62, -108, 44, -26, 0]
10-11 13:48:40.230  3701  4181 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{50d6237: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
10-11 13:48:40.232  9917  9937 D BtGatt.GattService: ScanRecord : [17, 7, -105, 56, 66, 88, 76, 92, -41, -80, 76, 74, 31, -74, -36, 103, -25, -63, 10, 22, -36, 103, 4, 68, 120, 62, -108, 44, -26]
10-11 13:48:40.232  9917  9937 D ScanRecord: parseFromBytes
10-11 13:48:40.235  9789  9800 D ScanRecord: parseFromBytes
,10-11 13:48:40.237  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=66:7C:CC:DC:F3:E2, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={000067dc-0000-1000-8000-00805f9b34fb=[4, 68, 120, 62, -108, 44, -26]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=230916514026}
,10-11 13:48:40.238  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 4]
,10-11 13:48:40.239  9789  9789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
,10-11 13:48:40.240  3701  4928 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134840 - CU:1002/CP:9917
10-11 13:48:40.240  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = c1e767dc-b61f-4a4c-b0d7-5c4c58423897, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 4]
10-11 13:48:40.240  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [44:78:3E:94:2C:E6 4]
10-11 13:48:40.240  3701  4928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134841, SetElapsed=232368, nowELAPSED=231377
10-11 13:48:40.241  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [44:78:3E:94:2C:E6 4]
10-11 13:48:40.241  9789  9789 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [44:78:3E:94:2C:E6 4]
10-11 13:48:40.241  9789  9789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
10-11 13:48:40.241  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [44:78:3E:94:2C:E6 4]
10-11 13:48:40.242  9789  9789 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [44:78:3E:94:2C:E6 4], added - the peer count is 1
,10-11 13:48:40.243  9789  9789 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [44:78:3E:94:2C:E6 4], Bluetooth address: 44:78:3E:94:2C:E6, device name: 'null', device address: 'null'
,10-11 13:48:40.614  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:41.092  4648  4648 D io_stats: !@   8,0 r 26147 2315744 w 5485 212284 d 704 75224 f 2211 2211 iot 12130 11120 th 479200 0 0 pt 0 inp 0 0 232.227
,10-11 13:48:41.110  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:41.110  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:41.231  3701  3864 D SamsungAlarmManager: Expired : 4
,10-11 13:48:41.233  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134844, SetElapsed=236055, nowELAPSED=232369
10-11 13:48:41.234  3701  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{829c3a4 type 2 when 231867 com.android.bluetooth}
,10-11 13:48:41.239  9917  9917 D BtGatt.ScanManager: awakened up at time 232376
,10-11 13:48:41.242  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-11 13:48:41.262  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,10-11 13:48:41.262  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:41.262  9917  9937 D BtGatt.GattService: current time is 232399485256
10-11 13:48:41.263  9917  9937 D BtGatt.GattService: Batch record : [-30, -13, -36, -52, 124, 102, 1, -128, -57, 8, 0, 29, 17, 7, -105, 56, 66, 88, 76, 92, -41, -80, 76, 74, 31, -74, -36, 103, -25, -63, 10, 22, -36, 103, 5, 68, 120, 62, -108, 44, -26, 0]
,10-11 13:48:41.263  3701  4917 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{83c750d: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
10-11 13:48:41.263  9917  9937 D BtGatt.GattService: ScanRecord : [17, 7, -105, 56, 66, 88, 76, 92, -41, -80, 76, 74, 31, -74, -36, 103, -25, -63, 10, 22, -36, 103, 5, 68, 120, 62, -108, 44, -26]
10-11 13:48:41.263  9917  9937 D ScanRecord: parseFromBytes
10-11 13:48:41.264  9789  9801 D ScanRecord: parseFromBytes
10-11 13:48:41.265  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=66:7C:CC:DC:F3:E2, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={000067dc-0000-1000-8000-00805f9b34fb=[5, 68, 120, 62, -108, 44, -26]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-57, mTimestampNanos=231999667487}
10-11 13:48:41.267  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 5]
,10-11 13:48:41.268  9789  9789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
10-11 13:48:41.269  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = c1e767dc-b61f-4a4c-b0d7-5c4c58423897, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 5]
,10-11 13:48:41.269  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [44:78:3E:94:2C:E6 5]
10-11 13:48:41.270  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [44:78:3E:94:2C:E6 5]
,10-11 13:48:41.270  9789  9789 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [44:78:3E:94:2C:E6 5]
,10-11 13:48:41.271  9789  9789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: true
10-11 13:48:41.271  9789  9789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerUpdated. Listeners size = 1
10-11 13:48:41.272  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerUpdated: [44:78:3E:94:2C:E6 5]
,10-11 13:48:41.273  3701  3915 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134841 - CU:1002/CP:9917
10-11 13:48:41.273  9789  9789 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [44:78:3E:94:2C:E6 5] updated - the peer count is 1
10-11 13:48:41.273  3701  3915 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134842, SetElapsed=233401, nowELAPSED=232410
10-11 13:48:41.274  9789  9789 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [44:78:3E:94:2C:E6 5], device name: 'null', device address: 'null'
,10-11 13:48:41.660  3701  5735 D SSRM:f  : SIOP:: AP = 300, PST = 311 (W:10), CP = 259, CUR = 199, LCD = 57
,10-11 13:48:42.178  9789  9853 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
10-11 13:48:42.179  9789  9853 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
10-11 13:48:42.179  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
10-11 13:48:42.180  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:48:42.187  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
10-11 13:48:42.187  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,10-11 13:48:42.188  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.189  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-11 13:48:42.196  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
10-11 13:48:42.197  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,10-11 13:48:42.198  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 43005
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-11 13:48:42.199  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.199  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
,10-11 13:48:42.200  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.201  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.202  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-11 13:48:42.202  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-11 13:48:42.203  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.205  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.206  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.208  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.210  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.211  9917  9938 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
10-11 13:48:42.211  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-11 13:48:42.212  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-11 13:48:42.214  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.215  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:42.215  9789  9853 D BluetoothLeScanner: Stop Scan
10-11 13:48:42.217  9917  9939 D BtGatt.GattService: stopScan() - queue size =1
10-11 13:48:42.217  9917  9939 D BtGatt.GattService: stopScan() - queue size =1
10-11 13:48:42.218  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
10-11 13:48:42.219  9917  9939 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-11 13:48:42.221  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-11 13:48:42.222  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.222  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-11 13:48:42.222  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.223  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-11 13:48:42.224  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.224  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.224  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-11 13:48:42.225  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-11 13:48:42.225  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 43005
10-11 13:48:42.225  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=43005, mManufacturerData=null, mManufacturerDataMask=null]
10-11 13:48:42.225  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.226  9789  9853 D BluetoothLeScanner: Start Scan
10-11 13:48:42.226  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
10-11 13:48:42.226  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:42.226  9917  9937 D BtGatt.GattService: current time is 233363284909
10-11 13:48:42.226  9917  9937 D BtGatt.GattService: Batch record : [-30, -13, -36, -52, 124, 102, 1, -128, -60, 6, 0, 29, 17, 7, -105, 56, 66, 88, 76, 92, -41, -80, 76, 74, 31, -74, -36, 103, -25, -63, 10, 22, -36, 103, 5, 68, 120, 62, -108, 44, -26, 0]
10-11 13:48:42.227  9917  9937 D BtGatt.GattService: ScanRecord : [17, 7, -105, 56, 66, 88, 76, 92, -41, -80, 76, 74, 31, -74, -36, 103, -25, -63, 10, 22, -36, 103, 5, 68, 120, 62, -108, 44, -26]
10-11 13:48:42.227  9917  9937 D ScanRecord: parseFromBytes
10-11 13:48:42.227  9917  9937 E BtGatt.ContextMap: Context not found for ID 5
10-11 13:48:42.228  3701  4915 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{275fcc2: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
10-11 13:48:42.229  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:42.230  3701  4915 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134844, SetElapsed=236055, nowELAPSED=233366
,10-11 13:48:42.232  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.236  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.238  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.241  9917  9928 D BtGatt.GattService: registerClient() - UUID=bd1861a3-3ae0-487c-aa68-7ec25eb13e78
,10-11 13:48:42.243  3701  4923 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134842 - CU:1002/CP:9917
10-11 13:48:42.244  3701  4923 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134843, SetElapsed=234367, nowELAPSED=233380
,10-11 13:48:42.245  9917  9955 D BtGatt.ScanManager: filter size is 1
10-11 13:48:42.245  9917  9955 D BtGatt.ScanManager: delete FilterIndex - 6
,10-11 13:48:42.251  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-11 13:48:42.251  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-11 13:48:42.251  9917  9955 D BtGatt.ScanManager: stopping BLe Batch
,10-11 13:48:42.257  9917  9937 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-11 13:48:42.257  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-11 13:48:42.257  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-11 13:48:42.262  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-11 13:48:42.263  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-11 13:48:42.263  3701  4916 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{f4bead3: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
,10-11 13:48:42.265  3701  4916 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134844, SetElapsed=236055, nowELAPSED=233402
,10-11 13:48:42.266  3701  4541 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{7117610: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
,10-11 13:48:42.344  9917  9937 D BtGatt.GattService: onClientRegistered() - UUID=bd1861a3-3ae0-487c-aa68-7ec25eb13e78, clientIf=5, status=0
,10-11 13:48:42.344  9789  9800 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
10-11 13:48:42.345  9917  9938 D BtGatt.GattService: start scan with filters
,10-11 13:48:42.347  9917  9938 D BtGatt.GattService: getScanSettings
,10-11 13:48:42.349  9917  9938 D BtGatt.GattService: Is it foreground application = true
10-11 13:48:42.349  9917  9938 D BtGatt.GattService: not a background application
,10-11 13:48:42.355  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,10-11 13:48:42.355  9917  9965 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c3b70f3
10-11 13:48:42.356  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-11 13:48:42.356  9917  9955 D BtGatt.ScanManager: handling starting scan
10-11 13:48:42.356  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.356  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-11 13:48:42.357  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.357  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.357  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:42.358  9917  9955 D BluetoothAdapter: STATE_ON
10-11 13:48:42.358  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-11 13:48:42.358  9789  9853 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-11 13:48:42.358  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.358  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-11 13:48:42.358  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-11 13:48:42.358  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-11 13:48:42.358  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-11 13:48:42.358  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.359  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.359  9917  9955 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.361  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-11 13:48:42.364  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-11 13:48:42.364  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-11 13:48:42.364  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-11 13:48:42.364  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-11 13:48:42.364  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-11 13:48:42.364  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-11 13:48:42.366  9917  9937 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-11 13:48:42.366  9789 10470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-11 13:48:42.366  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:42.366  9917  9955 D BtGatt.ScanManager: set filter index= 7 for clientIf= 5
10-11 13:48:42.366  9917  9955 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-11 13:48:42.366  9917  9955 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-11 13:48:42.366  9917  9955 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
,10-11 13:48:42.372  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-11 13:48:42.373  9789  9853 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-11 13:48:42.375  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-11 13:48:42.376  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:42.376  9917  9955 D BtGatt.ScanManager: Starting BLE batch scan
10-11 13:48:42.376  9917  9955 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-11 13:48:42.377  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:42.379  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.387  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:42.389  9789 10470 D BluetoothSocket: bindListen(): myUserId = 0
10-11 13:48:42.390  9789 10470 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-11 13:48:42.390  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:42.395  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:42.399  9789 10470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-11 13:48:42.399  9789 10470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@ecc3a5a, port: 6, type: 1, local socket address: null, socket type: 0
,10-11 13:48:42.401  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.401  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.402  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.402  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-11 13:48:42.402  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
10-11 13:48:42.403  9917  9937 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-11 13:48:42.403  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "c1e767dc-b61f-4a4c-b0d7-5c4c58423897", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-11 13:48:42.403  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:42.404  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 4A 3E
10-11 13:48:42.405  9789  9853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:48:42.405  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:48:42.405  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.406  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.406  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-11 13:48:42.407  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-11 13:48:42.407  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.408  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.409  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={c1e767dc-b61f-4a4c-b0d7-5c4c58423897=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.409  9917  9937 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-11 13:48:42.409  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:42.411  3701  4540 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{4c85509: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
10-11 13:48:42.413  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:42.414  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:42.414  9789  9853 D BluetoothAdapter: isSecureModeEnabled
10-11 13:48:42.415  9917  9939 D BtConfig.SecureMode: isSecureModeOn:false
10-11 13:48:42.415  9789  9853 D BluetoothLeAdvertiser: start advertising
10-11 13:48:42.417  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:42.421  3701  3728 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134842 - CU:1002/CP:9917
10-11 13:48:42.421  3701  3728 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134843, SetElapsed=234549, nowELAPSED=233558
10-11 13:48:42.424  9917  9939 D BtGatt.GattService: registerClient() - UUID=88234f8f-f4ab-4d17-a59f-6a3557ce1657
,10-11 13:48:42.483  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:42.498  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:42.517  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:42.527  9917  9937 D BtGatt.GattService: onClientRegistered() - UUID=88234f8f-f4ab-4d17-a59f-6a3557ce1657, clientIf=6, status=0
,10-11 13:48:42.529  9789  9801 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,10-11 13:48:42.533  9917  9938 E BtGatt.ContextMap: Context not found for ID 6
,10-11 13:48:42.534  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-11 13:48:42.535  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
10-11 13:48:42.539  9917  9954 D BtGatt.AdvertiseManager: message : 0
,10-11 13:48:42.541  9917  9954 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-11 13:48:42.541  9917  9954 D BtGatt.AdvertiseManager: size of list is =0
,10-11 13:48:42.550  9917  9954 D BtGatt.AdvertiseManager: starting advertising
,10-11 13:48:42.551  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:42.557  9917  9954 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-11 13:48:42.559  9917  9971 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-11 13:48:42.572  9917  9937 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,10-11 13:48:42.574  9917  9954 D BtGatt.AdvertiseManager: starting multi advertising
,10-11 13:48:42.583  9917  9937 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
10-11 13:48:42.583  9917  9954 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-11 13:48:42.584  9917  9954 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-11 13:48:42.584  9917  9954 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
10-11 13:48:42.584  9917  9954 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,10-11 13:48:42.584  9789  9800 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-11 13:48:42.585  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.586  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.586  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-11 13:48:42.587  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.587  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.588  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.588  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.589  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.589  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.590  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.590  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.591  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-11 13:48:42.591  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
10-11 13:48:42.591  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-11 13:48:42.593  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-11 13:48:42.594  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.598  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.599  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:42.599  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:42.600  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-11 13:48:42.600  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.601  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:42.601  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-11 13:48:42.601  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.602  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.602  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:42.602  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.603  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
10-11 13:48:42.603  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-11 13:48:42.603  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-11 13:48:42.603  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.604  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.605  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.605  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-11 13:48:42.611  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.611  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-11 13:48:42.612  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-11 13:48:42.612  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,10-11 13:48:42.613  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-11 13:48:42.934  3701  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-11 13:48:43.114  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,10-11 13:48:43.114  9789  9789 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-11 13:48:43.115  9789  9789 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-11 13:48:43.412  3701  3864 D SamsungAlarmManager: Expired : 4
10-11 13:48:43.414  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134844, SetElapsed=236055, nowELAPSED=234550
,10-11 13:48:43.415  3701  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{12b230e type 2 when 234048 com.android.bluetooth}
,10-11 13:48:43.420  9917  9917 D BtGatt.ScanManager: awakened up at time 234557
,10-11 13:48:43.423  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-11 13:48:43.444  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
10-11 13:48:43.444  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-11 13:48:43.444  9917  9937 D BtGatt.GattService: current time is 234581093332
10-11 13:48:43.444  9917  9937 D BtGatt.GattService: Batch record : [-30, -13, -36, -52, 124, 102, 1, -128, -58, 18, 0, 29, 17, 7, -105, 56, 66, 88, 76, 92, -41, -80, 76, 74, 31, -74, -36, 103, -25, -63, 10, 22, -36, 103, 5, 68, 120, 62, -108, 44, -26, 0]
10-11 13:48:43.445  9917  9937 D BtGatt.GattService: ScanRecord : [17, 7, -105, 56, 66, 88, 76, 92, -41, -80, 76, 74, 31, -74, -36, 103, -25, -63, 10, 22, -36, 103, 5, 68, 120, 62, -108, 44, -26]
10-11 13:48:43.445  9917  9937 D ScanRecord: parseFromBytes
10-11 13:48:43.445  3701  4927 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{ee0612f: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
10-11 13:48:43.446  9789  9801 D ScanRecord: parseFromBytes
,10-11 13:48:43.447  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=66:7C:CC:DC:F3:E2, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[c1e767dc-b61f-4a4c-b0d7-5c4c58423897], mManufacturerSpecificData={}, mServiceData={000067dc-0000-1000-8000-00805f9b34fb=[5, 68, 120, 62, -108, 44, -26]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=233681287101}
10-11 13:48:43.448  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 5]
10-11 13:48:43.448  9789  9789 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
10-11 13:48:43.448  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = c1e767dc-b61f-4a4c-b0d7-5c4c58423897, bluetoothMacAddress = 44:78:3E:94:2C:E6, provideBluetoothMacAddressRequestId = nullextra info = 5]
10-11 13:48:43.448  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [44:78:3E:94:2C:E6 5]
10-11 13:48:43.449  9789  9789 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [44:78:3E:94:2C:E6 5]
10-11 13:48:43.449  9789  9789 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [44:78:3E:94:2C:E6 5]
10-11 13:48:43.449  9789  9789 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
10-11 13:48:43.449  9789  9789 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [44:78:3E:94:2C:E6 5] updated - the peer count is 1
10-11 13:48:43.454  3701  4543 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134843 - CU:1002/CP:9917
10-11 13:48:43.455  3701  4543 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134844, SetElapsed=235583, nowELAPSED=234592
,10-11 13:48:44.130  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:44.130  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:44.447  3701  3864 D SamsungAlarmManager: Expired : 4
,10-11 13:48:44.448  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134844, SetElapsed=236055, nowELAPSED=235584
10-11 13:48:44.449  3701  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{c7fe33c type 2 when 235082 com.android.bluetooth}
,10-11 13:48:44.454  9917  9917 D BtGatt.ScanManager: awakened up at time 235591
,10-11 13:48:44.457  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-11 13:48:44.471  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-11 13:48:44.471  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:44.473  3701  4917 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{61838c5: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
,10-11 13:48:44.490  3701  4923 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134844 - CU:1002/CP:9917
10-11 13:48:44.491  3701  4923 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134845, SetElapsed=236612, nowELAPSED=235628
,10-11 13:48:45.283  3701  4928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:48:45.476  3701  3864 D SamsungAlarmManager: Expired : 4
,10-11 13:48:45.477  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135727, SetElapsed=758350, nowELAPSED=236613
,10-11 13:48:45.477  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@c1f14e0 alarm=Alarm{6fa621a type 2 when 236055 android}
,10-11 13:48:45.480  3701  3930 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 32000: mInRange : true
10-11 13:48:45.481  3701  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{c9be14b type 2 when 236110 com.android.bluetooth}
10-11 13:48:45.484 10214 10214 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-11 13:48:45.484 10214 10214 I wpa_supplicant: P2P: Current p2p state = IDLE
,10-11 13:48:45.494  3701  3930 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T134917 - CU:1000/CP:3701
,10-11 13:48:45.495  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134917, SetElapsed=268618, nowELAPSED=236631
,10-11 13:48:45.496  9917  9917 D BtGatt.ScanManager: awakened up at time 236632
10-11 13:48:45.498  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-11 13:48:45.505 10214 10214 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
10-11 13:48:45.508  3701  3957 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T134900 - CU:1000/CP:3701
,10-11 13:48:45.508  3701  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134900, SetElapsed=251623, nowELAPSED=236645
10-11 13:48:45.509  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-11 13:48:45.509  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:45.510  3701  4916 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{c4c85e6: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
,10-11 13:48:45.527  3701  4542 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134846 - CU:1002/CP:9917
,10-11 13:48:45.527  3701  4542 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134846, SetElapsed=237650, nowELAPSED=236664
,10-11 13:48:45.608  9789  9853 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,10-11 13:48:45.609  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-11 13:48:45.610  9789  9853 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-11 13:48:45.610  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-11 13:48:45.610  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-11 13:48:45.612  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-11 13:48:45.612  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-11 13:48:45.612  9789 10470 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-11 13:48:45.612  9789  9853 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-11 13:48:45.612  9789 10470 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-11 13:48:45.613  9789 10470 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-11 13:48:45.613  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-11 13:48:45.613  9789  9789 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-11 13:48:45.613  9789  9853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8839977 removed from the list
10-11 13:48:45.614  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8839977 removed from the list
10-11 13:48:45.614  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-11 13:48:45.614  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-11 13:48:45.614  9789  9789 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-11 13:48:45.614  9789  9853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-11 13:48:45.615  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.615  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-11 13:48:45.616  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-11 13:48:45.617  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:45.618  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.619  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.620  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-11 13:48:45.620  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:45.624  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:45.627  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:45.628  9917  9938 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,10-11 13:48:45.629  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
10-11 13:48:45.631  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-11 13:48:45.633  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:45.637  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:45.637  9789  9853 D BluetoothLeScanner: Stop Scan
,10-11 13:48:45.641  9917  9938 D BtGatt.GattService: stopScan() - queue size =1
10-11 13:48:45.641  9917  9938 D BtGatt.GattService: stopScan() - queue size =1
,10-11 13:48:45.641  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-11 13:48:45.642  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:45.642  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
10-11 13:48:45.644  9917  9928 D BtGatt.GattService: unregisterClient() - clientIf=5
10-11 13:48:45.646  3701  4917 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{3454727: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
10-11 13:48:45.647  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-11 13:48:45.648  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.648  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-11 13:48:45.649  3701  4917 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134900, SetElapsed=251623, nowELAPSED=236785
,10-11 13:48:45.649  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.650  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.651  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.651  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-11 13:48:45.652  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:45.656  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:45.659  9789  9853 D BluetoothAdapter: STATE_ON
10-11 13:48:45.660  9789  9853 D BluetoothLeAdvertiser: stop advertising
,10-11 13:48:45.661  9917  9939 E BtGatt.ContextMap: Context not found for ID 6
,10-11 13:48:45.662  9917  9965 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
10-11 13:48:45.662  9917  9954 D BtGatt.AdvertiseManager: message : 1
10-11 13:48:45.662  3701  4923 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171011T134846 - CU:1002/CP:9917
10-11 13:48:45.663  3701  4923 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134846, SetElapsed=237787, nowELAPSED=236799
10-11 13:48:45.663  9917  9954 D BtGatt.AdvertiseManager: stop advertise for client =  6
10-11 13:48:45.663  9917  9954 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,10-11 13:48:45.665  9917  9954 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-11 13:48:45.666  9917  9955 D BtGatt.ScanManager: filter size is 1
10-11 13:48:45.666  9917  9955 D BtGatt.ScanManager: delete FilterIndex - 7
,10-11 13:48:45.671  9917  9937 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
10-11 13:48:45.672  9917  9937 D BtGatt.GattService: Client app is not null!
,10-11 13:48:45.672  9789  9800 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
10-11 13:48:45.674  9917  9928 D BtGatt.GattService: unregisterClient() - clientIf=6
10-11 13:48:45.676  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-11 13:48:45.677  9917  9937 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-11 13:48:45.677  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:45.677  9917  9955 D BtGatt.ScanManager: stopping BLe Batch
10-11 13:48:45.677  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.678  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-11 13:48:45.679  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:45.681  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:45.682  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:45.682  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-11 13:48:45.682  9789  9853 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-11 13:48:45.684  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,10-11 13:48:45.684  9789  9853 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
10-11 13:48:45.684  9917  9937 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-11 13:48:45.684  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:45.684  9917  9955 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-11 13:48:45.684  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,10-11 13:48:45.690  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.690  9917  9937 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-11 13:48:45.690  9917  9937 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-11 13:48:45.690  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-11 13:48:45.690  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.691  3701  4928 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{f575dd4: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
10-11 13:48:45.691  9789  9853 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
10-11 13:48:45.691  9789  9853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d4c9e4 removed from the list
10-11 13:48:45.691  9789  9853 D io.jxcore.node.ConnectivityMonitor: stop
10-11 13:48:45.691  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:48:45.691  9789  9853 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-11 13:48:45.692  9789  9853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-11 13:48:45.692  9789  9789 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-11 13:48:45.692  3701  4928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134900, SetElapsed=251623, nowELAPSED=236829
10-11 13:48:45.692  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:45.693  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:48:45.693  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-11 13:48:45.693  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
10-11 13:48:45.693  3701  4921 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9917 / op:PendingIntent{cc1bb7d: PendingIntentRecord{e1ee927 com.android.bluetooth broadcastIntent}}
10-11 13:48:45.694  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:48:45.694  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-11 13:48:45.694  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
10-11 13:48:45.694  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-11 13:48:45.694  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:48:45.695  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-11 13,:48:45.695  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-11 13:48:45.695  9789  9789 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-11 13:48:45.695  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-11 13:48:45.695  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-11 13:48:45.695  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-11 13:48:45.695  9789  9853 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-11 13:48:45.695  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-11 13:48:45.695  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-11 13:48:45.696  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-11 13:48:45.696  9789  9789 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-11 13:48:45.696  9789  9789 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-11 13:48:45.697  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,10-11 13:48:45.699  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,10-11 13:48:45.700  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,10-11 13:48:45.702  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,10-11 13:48:45.704  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,10-11 13:48:45.706  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,10-11 13:48:45.707  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,10-11 13:48:45.709  9789  9853 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-11 13:48:46.097  4648  4648 D io_stats: !@   8,0 r 26147 2315744 w 5503 212596 d 709 75244 f 2217 2217 iot 12140 11130 th 479236 0 0 pt 0 inp 0 0 237.232
,10-11 13:48:46.198  9789  9789 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-11 13:48:47.018  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 7ms lastUpdatedAfter : 34033 ms mFlush_time_threasold : 2000 mCurrentSize : 229
,10-11 13:48:47.046  5202 10475 W IcingInternalCorpora: getNumBytesRead when not calculated.
,10-11 13:48:47.051  5202  5580 I Icing   : App usage reports: 1
10-11 13:48:47.052  5202  5580 I Icing   : Usage reports 1 indexed 0 rejected 0 imm upload false
,10-11 13:48:47.114  5202  5580 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-11 13:48:47.141  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:47.141  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:47.156  5202  5580 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-11 13:48:47.185  5202  5580 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-11 13:48:47.230  5202  5580 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-11 13:48:47.259  5202  5580 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-11 13:48:47.290  5202  5580 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-11 13:48:47.716  9789  9853 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-11 13:48:47.849  9789 10476 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 264, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:47.849  9789 10476 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:47.849  9789 10476 D io.jxcore.node.StreamCopyingThread:  id: 89
,10-11 13:48:48.614  9789 10476 W !!      : call onHalfStreamCopied
10-11 13:48:48.614  9789 10476 I testCopyDataAndClose: closing input stream
,10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 264, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread:  id: 89
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread:  id: 89
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 264, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:49.270  9789 10476 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-11 13:48:49.525  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:48:49.526 10214 10214 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
10-11 13:48:49.527  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:48:49.527  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:48:49.531  3701  3957 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@cc89c41
,10-11 13:48:49.534  3701  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134917, SetElapsed=268618, nowELAPSED=240670
,10-11 13:48:49.573  3701  3763 I ActivityManager: KPU : put [com.samsung.enhanceservice] : 20212 K
10-11 13:48:49.573  3701  3763 I ActivityManager: Killing 9564:com.samsung.enhanceservice/5004 (adj 906): DHA:empty #33
,10-11 13:48:49.607  3701  4916 D ActivityManager: cleanUpApplicationRecord -- 9564
,10-11 13:48:49.609  4803  4819 D ForegroundUtils: could not check pending caller
,10-11 13:48:50.165  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:50.166  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:50.708  9789  9853 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-11 13:48:50.738  9789 10477 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 267, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:50.738  9789 10477 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:50.738  9789 10477 D io.jxcore.node.StreamCopyingThread:  id: 91
,10-11 13:48:51.035  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 4ms lastUpdatedAfter : 4017 ms mFlush_time_threasold : 2000 mCurrentSize : 232
,10-11 13:48:51.102  4648  4648 D io_stats: !@   8,0 r 26147 2315744 w 5546 213380 d 724 75304 f 2240 2240 iot 12210 11170 th 471480 0 0 pt 0 inp 0 0 242.237
,10-11 13:48:51.680  3701  5735 D SSRM:f  : SIOP:: AP = 340, PST = 314 (W:6), CP = 259, CUR = 58, LCD = 57
,10-11 13:48:52.045  9789 10477 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 267, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:52.045  9789 10477 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:52.045  9789 10477 D io.jxcore.node.StreamCopyingThread:  id: 91
10-11 13:48:52.045  9789 10477 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:52.045  9789 10477 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:52.045  9789 10477 D io.jxcore.node.StreamCopyingThread:  id: 91
10-11 13:48:52.046  9789 10477 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:52.046  9789 10477 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:52.046  9789 10477 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:52.046  9789 10477 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:52.046  9789 10477 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:52.046  9789 10477 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 267, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:52.046  9789 10477 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:52.046  9789 10477 D io.jxcore.node.StreamCopyingThread:  id: 91 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-11 13:48:53.190  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:53.190  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:53.368  9789  9853 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 269, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread:  id: 92
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 269, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread:  id: 92
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread:  id: 92
,10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 269, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:53.369  9789 10478 D io.jxcore.node.StreamCopyingThread:  id: 92 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-11 13:48:53.370  9789  9853 I StreamCopyingThreadTest: Starting test: testSetBufferSize
10-11 13:48:53.370  9789  9853 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-11 13:48:53.370  9789  9853 I StreamCopyingThreadTest: Starting test: testRunWithException
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 273, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread:  id: 95
10-11 13:48:53.371  9789 10479 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 273, thread name: My test thread name): Test exception.
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 273, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread:  id: 95 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 273, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-11 13:48:53.371  9789 10479 D io.jxcore.node.StreamCopyingThread:  id: 95 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-11 13:48:53.372  9789  9853 I jxcore-log: 2017-10-11 11:48:53 - DEBUG UnitTest_app: 'Running unit tests'
10-11 13:48:53.372  9789  9853 I jxcore-log: 
10-11 13:48:53.372  9789  9853 I jxcore-log: *Native tests were executed*
10-11 13:48:53.372  9789  9853 I jxcore-log: 
10-11 13:48:53.372  9789  9853 I jxcore-log: Total number of executed tests:  78
10-11 13:48:53.372  9789  9853 I jxcore-log: 
10-11 13:48:53.372  9789  9853 I jxcore-log: Number of passed tests:  76
10-11 13:48:53.372  9789  9853 I jxcore-log: 
10-11 13:48:53.372  9789  9853 I jxcore-log: Number of failed tests:  0
10-11 13:48:53.372  9789  9853 I jxcore-log: 
10-11 13:48:53.372  9789  9853 I jxcore-log: Number of ignored tests:  2
10-11 13:48:53.372  9789  9853 I jxcore-log: 
10-11 13:48:53.372  9789  9853 I jxcore-log: Total duration:  56892
10-11 13:48:53.372  9789  9853 I jxcore-log: 
10-11 13:48:53.372  9789  9853 I jxcore-log: 2017-10-11 11:48:53 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
10-11 13:48:53.372  9789  9853 I jxcore-log: 
10-11 13:48:53.373  9789  9853 I jxcore-log: 2017-10-11 11:48:53 - WARN testUtils: 'myNameCallback not set!'
10-11 13:48:53.373  9789  9853 I jxcore-log: 
,10-11 13:48:53.744  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:48:54.858  9789  9853 I jxcore-log: 2017-10-11 11:48:54 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
10-11 13:48:54.858  9789  9853 I jxcore-log: 
,10-11 13:48:54.862  9789  9853 I jxcore-log: 2017-10-11 11:48:54 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-11 13:48:54.862  9789  9853 I jxcore-log: 
,10-11 13:48:54.872  9789  9853 I jxcore-log: 2017-10-11 11:48:54 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-11 13:48:54.872  9789  9853 I jxcore-log: 
,10-11 13:48:55.030  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-11 13:48:55.030  9789  9853 I jxcore-log: 
,10-11 13:48:55.059  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-11 13:48:55.059  9789  9853 I jxcore-log: 
,10-11 13:48:55.148  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-11 13:48:55.148  9789  9853 I jxcore-log: 
,10-11 13:48:55.182  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-11 13:48:55.182  9789  9853 I jxcore-log: 
,10-11 13:48:55.200  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-11 13:48:55.200  9789  9853 I jxcore-log: 
,10-11 13:48:55.204  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-11 13:48:55.204  9789  9853 I jxcore-log: 
,10-11 13:48:55.247  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
10-11 13:48:55.247  9789  9853 I jxcore-log: 
,10-11 13:48:55.251  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
10-11 13:48:55.251  9789  9853 I jxcore-log: 
,10-11 13:48:55.254  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-11 13:48:55.254  9789  9853 I jxcore-log: 
,10-11 13:48:55.257  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-11 13:48:55.257  9789  9853 I jxcore-log: 
,10-11 13:48:55.333  3701  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
10-11 13:48:55.334  3701  4913 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4258, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:48:55.334  3701  4913 D BatteryService: online:4, current avg:-45, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:-399
,10-11 13:48:55.335  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:48:55.341  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-11 13:48:55.341  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:48:55.343  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:48:55.347  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:48:55.348  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:48:55.353  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-11 13:48:55.357  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:48:55.358  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:48:55.371  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-11 13:48:55.372  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:48:55.383  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:48:55.480  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-11 13:48:55.480  9789  9853 I jxcore-log: 
,10-11 13:48:55.486  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-11 13:48:55.486  9789  9853 I jxcore-log: 
,10-11 13:48:55.550  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
10-11 13:48:55.550  9789  9853 I jxcore-log: 
,10-11 13:48:55.553  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-11 13:48:55.553  9789  9853 I jxcore-log: 
,10-11 13:48:55.571  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-11 13:48:55.571  9789  9853 I jxcore-log: 
,10-11 13:48:55.575  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-11 13:48:55.575  9789  9853 I jxcore-log: 
,10-11 13:48:55.607  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-11 13:48:55.607  9789  9853 I jxcore-log: 
,10-11 13:48:55.649  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-11 13:48:55.649  9789  9853 I jxcore-log: 
,10-11 13:48:55.682  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-11 13:48:55.682  9789  9853 I jxcore-log: 
,10-11 13:48:55.712  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-11 13:48:55.712  9789  9853 I jxcore-log: 
,10-11 13:48:55.720  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-11 13:48:55.720  9789  9853 I jxcore-log: 
,10-11 13:48:55.767  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-11 13:48:55.767  9789  9853 I jxcore-log: 
,10-11 13:48:55.796  9789  9853 I jxcore-log: 2017-10-11 11:48:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-11 13:48:55.796  9789  9853 I jxcore-log: 
,10-11 13:48:56.106  4648  4648 D io_stats: !@   8,0 r 26147 2315744 w 5582 213592 d 724 75304 f 2241 2241 iot 12210 11174 th 461768 0 0 pt 0 inp 0 0 247.242
,10-11 13:48:56.206  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:56.206  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:48:56.485  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-11 13:48:56.485  9789  9853 I jxcore-log: 
,10-11 13:48:56.510  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-11 13:48:56.510  9789  9853 I jxcore-log: 
,10-11 13:48:56.514  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-11 13:48:56.514  9789  9853 I jxcore-log: 
,10-11 13:48:56.518  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-11 13:48:56.518  9789  9853 I jxcore-log: 
,10-11 13:48:56.534  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-11 13:48:56.534  9789  9853 I jxcore-log: 
,10-11 13:48:56.552  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-11 13:48:56.552  9789  9853 I jxcore-log: 
,10-11 13:48:56.565  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-11 13:48:56.565  9789  9853 I jxcore-log: 
,10-11 13:48:56.573  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-11 13:48:56.573  9789  9853 I jxcore-log: 
,10-11 13:48:56.580  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-11 13:48:56.580  9789  9853 I jxcore-log: 
,10-11 13:48:56.589  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-11 13:48:56.589  9789  9853 I jxcore-log: 
,10-11 13:48:56.604  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-11 13:48:56.604  9789  9853 I jxcore-log: 
,10-11 13:48:56.616  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-11 13:48:56.616  9789  9853 I jxcore-log: 
,10-11 13:48:56.623  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-11 13:48:56.623  9789  9853 I jxcore-log: 
,10-11 13:48:56.699  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-11 13:48:56.699  9789  9853 I jxcore-log: 
,10-11 13:48:56.776  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
10-11 13:48:56.776  9789  9853 I jxcore-log: 
,10-11 13:48:56.789  9789  9853 D BluetoothAdapter: STATE_ON
,10-11 13:48:56.795  9789  9853 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-11 13:48:56.795  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO testUtils: 'BLE multiple advertisement supported'
10-11 13:48:56.795  9789  9853 I jxcore-log: 
,10-11 13:48:56.797  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-11 13:48:56.797  9789  9853 I jxcore-log: 
,10-11 13:48:56.804  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
10-11 13:48:56.804  9789  9853 I jxcore-log: 
10-11 13:48:56.805  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-11 13:48:56.805  9789  9853 I jxcore-log: 
,10-11 13:48:56.805  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
10-11 13:48:56.805  9789  9853 I jxcore-log: 
10-11 13:48:56.806  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-11 13:48:56.806  9789  9853 I jxcore-log: 
10-11 13:48:56.806  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
10-11 13:48:56.806  9789  9853 I jxcore-log: 
10-11 13:48:56.806  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-11 13:48:56.806  9789  9853 I jxcore-log: 
10-11 13:48:56.806  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
10-11 13:48:56.806  9789  9853 I jxcore-log: 
,10-11 13:48:56.807  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-11 13:48:56.807  9789  9853 I jxcore-log: 
10-11 13:48:56.807  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
10-11 13:48:56.807  9789  9853 I jxcore-log: 
10-11 13:48:56.807  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-11 13:48:56.807  9789  9853 I jxcore-log: 
10-11 13:48:56.807  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
10-11 13:48:56.807  9789  9853 I jxcore-log: 
10-11 13:48:56.807  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-11 13:48:56.807  9789  9853 I jxcore-log: 
10-11 13:48:56.808  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
10-11 13:48:56.808  9789  9853 I jxcore-log: 
10-11 13:48:56.808  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-11 13:48:56.808  9789  9853 I jxcore-log: 
,10-11 13:48:56.816  9789  9789 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,10-11 13:48:56.817  9789  9789 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-11 13:48:56.841  9789  9853 I jxcore-log: 2017-10-11 11:48:56 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
10-11 13:48:56.841  9789  9853 I jxcore-log: 
,10-11 13:48:56.862  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:48:57.166  9789  9853 I jxcore-log: 2017-10-11 11:48:57 - DEBUG CoordinatedClient: 'connected to the test server'
10-11 13:48:57.166  9789  9853 I jxcore-log: 
,10-11 13:48:59.236  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:48:59.237  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:00.001  3701  3864 D SamsungAlarmManager: Expired : 8
,10-11 13:49:00.002  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{b1d7ded type 3 when 251137 android}
,10-11 13:49:00.011  3701  3701 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171011T134959 - CU:1000/CP:3701
,10-11 13:49:00.015  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
10-11 13:49:00.016  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-11 13:49:00.016  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-11 13:49:00.021  3701  4018 D WifiWatchdogStateMachine:  [|215] []
,10-11 13:49:00.041  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,10-11 13:49:00.050  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-11 13:49:00.054  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-11 13:49:00.069  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:49:00.072  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:49:00.075  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:49:00.078  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:49:00.093  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
10-11 13:49:00.094  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
10-11 13:49:00.097  4070  4070 V hong    : mid yDiff = 438
10-11 13:49:00.097  4070  4070 V hong    : mid yDiff = 438
10-11 13:49:00.098  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-11 13:49:00.098  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-11 13:49:00.104  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:49:00.108  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:49:00.125  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:49:00.127  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:49:00.142  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-11 13:49:00.145  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-11 13:49:00.150  5166  5166 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-11 13:49:00.152  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-11 13:49:00.154  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
10-11 13:49:00.157  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
10-11 13:49:00.157  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
10-11 13:49:00.158  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-11 13:49:00.158  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-11 13:49:00.159  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-11 13:49:00.161  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-11 13:49:00.162  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CCC51ED6ECAC67D3269459B179A63D26281409B2A3E87EA0F2A3BB5B3FCB51308642A2830C4091D3DB3B7FF9CAFEDF1496D8EBE8B53FD8AF0F3BF9D7B5684D527]}
10-11 13:49:00.162  5166  5166 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-11 13:49:01.111  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5584 213680 d 725 75308 f 2243 2243 iot 12220 11178 th 461852 0 0 pt 0 inp 0 0 252.247
,10-11 13:49:01.702  3701  5735 D SSRM:f  : SIOP:: AP = 350, PST = 323 (W:6), CP = 270, CUR = 23, LCD = 57
,10-11 13:49:02.271  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:02.272  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:02.376  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:49:02.377  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-11 13:49:02.379  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:49:02.379  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:49:04.499  3701  4459 E Watchdog: !@Sync 8 [11_paź_13_49_04.499]
,10-11 13:49:05.305  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:05.306  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:05.400  3701  4540 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:49:05.401  3701  4540 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:49:05.401  3701  4540 D BatteryService: online:4, current avg:83, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:215
10-11 13:49:05.401  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:49:05.412  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-11 13:49:05.412  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:49:05.417  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:49:05.421  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:49:05.421  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:49:05.430  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-11 13:49:05.434  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
10-11 13:49:05.436  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:49:05.460  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-11 13:49:05.460  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:49:05.465  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:49:06.117  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5600 213824 d 725 75308 f 2245 2245 iot 12220 11180 th 461952 0 0 pt 0 inp 0 0 257.252
,10-11 13:49:07.756  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-11 13:49:07.756  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-11 13:49:07.756  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({system=1, android.process.acore=1, com.google.android.gms=2})  ]
,10-11 13:49:07.764  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 7ms lastUpdatedAfter : 16729 ms mFlush_time_threasold : 2000 mCurrentSize : 293
,10-11 13:49:08.339  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:08.339  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:11.122  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5605 213924 d 726 75312 f 2248 2248 iot 12220 11186 th 461956 0 0 pt 0 inp 0 0 262.257
,10-11 13:49:11.367  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:11.367  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:11.728  3701  5735 D SSRM:f  : SIOP:: AP = 320, PST = 323 (W:14), CP = 268, CUR = 145, LCD = 57
,10-11 13:49:12.653  3701  3800 I PowerManagerService: [PWL] On : 0 (263789 ms ago)
10-11 13:49:12.653  3701  3800 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-11 13:49:14.402  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:14.402  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:15.104  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:49:15.464  3701  4928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:49:16.128  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5610 213980 d 727 75316 f 2250 2250 iot 12220 11189 th 463620 0 0 pt 0 inp 0 0 267.263
,10-11 13:49:17.427  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:17.427  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:17.481  3701  3864 D SamsungAlarmManager: Expired : 4
10-11 13:49:17.482  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135727, SetElapsed=758350, nowELAPSED=268619
,10-11 13:49:17.483  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171011T135000, SetElapsed=311136, nowELAPSED=268619
10-11 13:49:17.484  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@805f728 alarm=Alarm{a3b0422 type 2 when 268618 android}
,10-11 13:49:17.487  3701  3930 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 64000: mInRange : true
,10-11 13:49:17.491 10214 10214 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-11 13:49:17.492 10214 10214 I wpa_supplicant: P2P: Current p2p state = IDLE
,10-11 13:49:17.496  3701  3930 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T135021 - CU:1000/CP:3701
,10-11 13:49:17.497  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135021, SetElapsed=332625, nowELAPSED=268633
,10-11 13:49:17.507  3701  3957 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T134932 - CU:1000/CP:3701
10-11 13:49:17.507  3701  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T134932, SetElapsed=283634, nowELAPSED=268644
,10-11 13:49:17.515 10214 10214 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-11 13:49:17.619  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:49:20.449  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:20.449  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:21.133  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5618 214024 d 727 75316 f 2251 2251 iot 12220 11190 th 463588 0 0 pt 0 inp 0 0 272.268
,10-11 13:49:21.374  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:49:21.375 10214 10214 I wpa_supplicant: nl80211: Received scan results (30 BSSes)
10-11 13:49:21.377  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:49:21.378  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:49:21.382  3701  3957 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@8113c70
10-11 13:49:21.385  3701  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135021, SetElapsed=332625, nowELAPSED=272522
,10-11 13:49:21.752  3701  5735 D SSRM:f  : SIOP:: AP = 310, PST = 320 (W:14), CP = 263, CUR = 184, LCD = 57
,10-11 13:49:23.479  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:23.479  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:25.532  3701  3728 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
10-11 13:49:25.533  3701  3728 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:49:25.534  3701  3728 D BatteryService: online:4, current avg:189, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:202
10-11 13:49:25.534  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:49:25.549  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,10-11 13:49:25.550  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:49:25.554  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:49:25.562  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,10-11 13:49:25.563  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:49:25.574  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-11 13:49:25.579  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
10-11 13:49:25.579  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:49:25.592  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-11 13:49:25.592  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:49:25.600  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:49:26.138  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5619 214028 d 727 75316 f 2252 2252 iot 12220 11191 th 464044 0 0 pt 0 inp 0 0 277.273
,10-11 13:49:26.512  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:26.512  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:29.546  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:29.546  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:31.144  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5620 214040 d 727 75316 f 2253 2253 iot 12220 11192 th 464020 0 0 pt 0 inp 0 0 282.279
,10-11 13:49:31.781  3701  5735 D SSRM:f  : SIOP:: AP = 300, PST = 320 (W:14), CP = 260, CUR = 192, LCD = 57
,10-11 13:49:32.380  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:49:32.381  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-11 13:49:32.383  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:49:32.383  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:49:32.573  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:32.573  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:34.501  3701  4459 E Watchdog: !@Sync 9 [11_paź_13_49_34.500]
,10-11 13:49:35.605  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:35.606  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:35.613  3701  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:49:38.637  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:38.637  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:41.154  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5622 214056 d 727 75316 f 2255 2255 iot 12220 11193 th 463960 0 0 pt 0 inp 0 0 292.288
,10-11 13:49:41.671  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:41.671  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:41.809  3701  5735 D SSRM:f  : SIOP:: AP = 300, PST = 320 (W:14), CP = 258, CUR = 191, LCD = 57
,10-11 13:49:44.728  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:44.728  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:45.688  3701  4923 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:49:46.159  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5623 214060 d 727 75316 f 2256 2256 iot 12230 11197 th 463928 0 0 pt 0 inp 0 0 297.294
,10-11 13:49:47.760  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:47.760  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:50.791  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:50.791  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:51.165  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5624 214072 d 727 75316 f 2257 2257 iot 12230 11198 th 463900 0 0 pt 0 inp 0 0 302.300
,10-11 13:49:51.836  3701  5735 D SSRM:f  : SIOP:: AP = 300, PST = 317 (W:14), CP = 257, CUR = 188, LCD = 57
,10-11 13:49:53.823  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:53.824  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:55.755  3701  4541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:49:55.756  3701  4541 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:49:55.756  3701  4541 D BatteryService: online:4, current avg:186, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:183
10-11 13:49:55.757  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:49:55.766  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-11 13:49:55.766  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:49:55.769  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:49:55.775  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:49:55.776  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:49:55.785  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
10-11 13:49:55.788  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:49:55.789  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
10-11 13:49:55.792  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:49:55.807  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-11 13:49:55.807  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:49:56.170  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5625 214076 d 727 75316 f 2258 2258 iot 12240 11199 th 463884 0 0 pt 0 inp 0 0 307.305
,10-11 13:49:56.844  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:56.844  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:49:59.877  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:49:59.878  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:00.000  3701  3864 D SamsungAlarmManager: Expired : 8
,10-11 13:50:00.001  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{725af9c type 3 when 311136 android}
,10-11 13:50:00.010  3701  3701 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171011T135059 - CU:1000/CP:3701
,10-11 13:50:00.015  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
10-11 13:50:00.015  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-11 13:50:00.016  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-11 13:50:00.038  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
10-11 13:50:00.038  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-11 13:50:00.042  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-11 13:50:00.055  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
10-11 13:50:00.057  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:50:00.061  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
10-11 13:50:00.063  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:50:00.077  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:50:00.079  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
10-11 13:50:00.080  4070  4070 V hong    : mid yDiff = 438
10-11 13:50:00.081  4070  4070 V hong    : mid yDiff = 438
10-11 13:50:00.082  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-11 13:50:00.082  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-11 13:50:00.088  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:50:00.090  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:50:00.103  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:50:00.105  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:50:00.120  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-11 13:50:00.124  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-11 13:50:00.129  5166  5166 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-11 13:50:00.131  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-11 13:50:00.134  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-11 13:50:00.140  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-11 13:50:00.141  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,10-11 13:50:00.142  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-11 13:50:00.146  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-11 13:50:00.147  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
10-11 13:50:00.151  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
10-11 13:50:00.152  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CCC51ED6ECAC67D3269459B179A63D2622B3CC7C99C42B2A59C2755FADD17A24EECA44DE5F29E6B28F3B91521745F44E95A3872B9BA7DA8A0087F9192EF355A9A]}
,10-11 13:50:00.153  5166  5166 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-11 13:50:01.175  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5626 214088 d 727 75316 f 2259 2259 iot 12240 11200 th 463856 0 0 pt 0 inp 0 0 312.310
,10-11 13:50:01.864  3701  5735 D SSRM:f  : SIOP:: AP = 300, PST = 313 (W:14), CP = 256, CUR = 183, LCD = 57
,10-11 13:50:02.385  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:50:02.386  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-11 13:50:02.388  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:50:02.388  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:50:02.907  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:02.908  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:04.503  3701  4459 E Watchdog: !@Sync 10 [11_paź_13_50_04.502]
,10-11 13:50:05.267  3701  4018 D WifiWatchdogStateMachine:  [|214] []
,10-11 13:50:05.820  3701  4916 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:50:05.940  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:05.940  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:07.066  3701  4543 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20171011T183338 - CU:10007/CP:4820
,10-11 13:50:07.660  3701  3800 I PowerManagerService: [PWL] On : 0 (318797 ms ago)
10-11 13:50:07.660  3701  3800 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-11 13:50:07.868  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-11 13:50:07.868  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-11 13:50:07.868  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-11 13:50:07.876  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60111 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-11 13:50:08.972  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:08.973  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:11.185  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5632 214192 d 728 75320 f 2263 2263 iot 12240 11205 th 463840 0 0 pt 0 inp 0 0 322.320
,10-11 13:50:11.891  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 311 (W:14), CP = 255, CUR = 177, LCD = 57
,10-11 13:50:11.999  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:12.000  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:15.032  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:15.033  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:15.887  3701  4887 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:50:16.191  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5636 214244 d 729 75324 f 2265 2265 iot 12240 11208 th 463864 0 0 pt 0 inp 0 0 327.326
,10-11 13:50:18.062  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-11 13:50:18.062  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:21.097  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:21.097  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:21.196  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5644 214288 d 729 75324 f 2266 2266 iot 12240 11210 th 464008 0 0 pt 0 inp 0 0 332.331
,10-11 13:50:21.489  3701  3864 D SamsungAlarmManager: Expired : 4
,10-11 13:50:21.490  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135727, SetElapsed=758350, nowELAPSED=332626
10-11 13:50:21.490  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171011T135059, SetElapsed=371136, nowELAPSED=332627
10-11 13:50:21.491  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@aaf4eb3 alarm=Alarm{6acf57a type 2 when 332625 android}
,10-11 13:50:21.495  3701  3930 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,10-11 13:50:21.499 10214 10214 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,10-11 13:50:21.499 10214 10214 I wpa_supplicant: P2P: Current p2p state = IDLE
,10-11 13:50:21.503  3701  3930 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T135229 - CU:1000/CP:3701
10-11 13:50:21.504  3701  3930 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135229, SetElapsed=460632, nowELAPSED=332640
,10-11 13:50:21.510  3701  3957 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T135036 - CU:1000/CP:3701
10-11 13:50:21.510  3701  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135036, SetElapsed=347640, nowELAPSED=332647
,10-11 13:50:21.516 10214 10214 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-11 13:50:21.918  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 309 (W:14), CP = 254, CUR = 174, LCD = 57
,10-11 13:50:24.120  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:24.120  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:25.498  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:50:25.500 10214 10214 I wpa_supplicant: nl80211: Received scan results (25 BSSes)
10-11 13:50:25.502  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:50:25.502  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:50:25.507  3701  3957 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@7ac2988
10-11 13:50:25.509  3701  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135229, SetElapsed=460632, nowELAPSED=336646
,10-11 13:50:25.955  3701  3919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:50:26.201  4648  4648 D io_stats: !@   8,0 r 26151 2316016 w 5645 214292 d 729 75324 f 2267 2267 iot 12250 11210 th 463920 0 0 pt 0 inp 0 0 337.336
,10-11 13:50:27.152  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:27.152  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:29.505  3701  3878 I TLC_TIMA_PKM_initialize: initializing...
,10-11 13:50:29.505  3701  3878 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
10-11 13:50:29.505  3701  3878 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: root = 0, root_len = 1
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: device_id = 0x0
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: tlc_open() was called
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: Opening MobiCore device
10-11 13:50:29.506  3701  3878 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,10-11 13:50:29.509  3701  3878 I TZ: mc_tlc_communication: Opening the session
,10-11 13:50:29.557  3701  3878 I TZ: mc_tlc_communication: tlc_open() succeeded
10-11 13:50:29.557  3701  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,10-11 13:50:29.568  3701  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,10-11 13:50:29.577  3701  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,10-11 13:50:29.586  3701  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,10-11 13:50:29.614  3701  3878 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,10-11 13:50:30.175  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:30.175  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:31.207  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5645 214292 d 729 75324 f 2267 2267 iot 12260 11215 th 463764 0 0 pt 0 inp 0 0 342.342
,10-11 13:50:31.446  8838  8887 I PlayCommon: [744] com.google.android.play.a.g.e(932): Preparing logs for uploading
,10-11 13:50:31.453  8838  8887 W PlayCommon: [744] com.google.android.play.a.g.a(1239): No account for auth token provided
,10-11 13:50:31.455  8838  8887 I PlayCommon: [744] com.google.android.play.a.g.a(1035): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,10-11 13:50:31.461  8838  8887 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-11 13:50:31.462  8838  8887 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-11 13:50:31.467  3294  3781 D EnterpriseController: netId is 0
10-11 13:50:31.468  3294  3781 D Netd    : getNetworkForDns: using netid 503 for uid 10032
10-11 13:50:31.468  3294  3781 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-11 13:50:31.820  8838  8887 I PlayCommon: [744] com.google.android.play.a.g.a(1113): Successfully uploaded logs.
,10-11 13:50:31.943  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 307 (W:14), CP = 254, CUR = 169, LCD = 57
,10-11 13:50:32.390  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:50:32.391  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-11 13:50:32.393  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:50:32.393  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:50:33.197  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:33.198  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:33.746  3701  3878 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
10-11 13:50:33.746  3701  3878 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,10-11 13:50:34.504  3701  4459 E Watchdog: !@Sync 11 [11_paź_13_50_34.504]
,10-11 13:50:36.021  3701  4915 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:50:36.212  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5647 214308 d 729 75324 f 2269 2269 iot 12260 11216 th 463656 0 0 pt 0 inp 0 0 347.347
,10-11 13:50:36.230  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:36.230  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:39.259  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:39.260  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:41.217  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5656 214396 d 731 75332 f 2270 2270 iot 12260 11219 th 463576 0 0 pt 0 inp 0 0 352.353
,10-11 13:50:41.970  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 305 (W:14), CP = 253, CUR = 166, LCD = 57
,10-11 13:50:42.293  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:42.293  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:45.326  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:45.327  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:46.082  3701  3919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:50:46.223  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5659 214432 d 731 75332 f 2273 2273 iot 12260 11222 th 463580 0 0 pt 0 inp 0 0 357.358
,10-11 13:50:48.352  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:48.353  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:51.387  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:51.387  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:51.997  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 302 (W:14), CP = 253, CUR = 163, LCD = 57
,10-11 13:50:53.904  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:50:54.418  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:54.419  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:56.146  3701  4921 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:50:56.233  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5664 214460 d 731 75332 f 2275 2275 iot 12260 11224 th 463588 0 0 pt 0 inp 0 0 367.368
,10-11 13:50:57.451  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:50:57.451  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:50:58.886  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:51:00.000  3701  3864 D SamsungAlarmManager: Expired : 8
,10-11 13:51:00.001  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{3e6bc5d type 3 when 371136 android}
,10-11 13:51:00.010  3701  3701 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171011T135200 - CU:1000/CP:3701
10-11 13:51:00.010  3701  3701 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171011T135200, SetElapsed=431137, nowELAPSED=371147
,10-11 13:51:00.015  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,10-11 13:51:00.016  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-11 13:51:00.016  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-11 13:51:00.036  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
10-11 13:51:00.037  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-11 13:51:00.041  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-11 13:51:00.054  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:51:00.057  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:51:00.060  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
10-11 13:51:00.063  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:51:00.086  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:51:00.088  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:51:00.089  4070  4070 V hong    : mid yDiff = 438
10-11 13:51:00.090  4070  4070 V hong    : mid yDiff = 438
,10-11 13:51:00.091  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-11 13:51:00.091  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-11 13:51:00.097  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:51:00.099  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:51:00.116  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:51:00.118  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:51:00.133  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-11 13:51:00.136  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-11 13:51:00.141  5166  5166 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-11 13:51:00.143  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-11 13:51:00.148  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-11 13:51:00.155  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-11 13:51:00.156  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
10-11 13:51:00.158  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
10-11 13:51:00.159  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-11 13:51:00.160  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-11 13:51:00.167  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-11 13:51:00.168  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CCC51ED6ECAC67D3269459B179A63D262AD2579C291BA547CB4E32306407998907BB0FCE78FEDC2EA72685577527D329CA750CFE9912F322B23C1F0D3E9923835]}
,10-11 13:51:00.169  5166  5166 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-11 13:51:00.484  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:00.484  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:02.028  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 300 (W:14), CP = 252, CUR = 161, LCD = 57
,10-11 13:51:02.264  3701  3710 I art     : Background partial concurrent mark sweep GC freed 259926(13MB) AllocSpace objects, 109(2MB) LOS objects, 28% free, 40MB/56MB, paused 1.988ms total 252.958ms
,10-11 13:51:02.395  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:51:02.396  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-11 13:51:02.398  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:51:02.398  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:51:03.509  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:03.510  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:03.994  4765  9690 V NativeCrypto: SSL shutdown failed: ssl=0x70b6972180: I/O error during system call, Software caused connection abort
,10-11 13:51:04.506  3701  4459 E Watchdog: !@Sync 12 [11_paź_13_51_04.506]
,10-11 13:51:06.208  3701  4887 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:51:06.209  3701  4887 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:51:06.210  3701  4887 D BatteryService: online:4, current avg:160, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:157
10-11 13:51:06.210  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:51:06.222  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,10-11 13:51:06.222  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:51:06.226  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:51:06.232  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:51:06.233  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:51:06.242  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
10-11 13:51:06.243  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5666 214476 d 731 75332 f 2277 2277 iot 12260 11225 th 464176 0 0 pt 0 inp 0 0 377.378
,10-11 13:51:06.249  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:51:06.250  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:51:06.267  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-11 13:51:06.268  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:51:06.274  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:51:06.544  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:06.545  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:07.661  3701  3800 I PowerManagerService: [PWL] On : 0 (378797 ms ago)
10-11 13:51:07.661  3701  3800 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-11 13:51:07.974  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-11 13:51:07.974  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-11 13:51:07.974  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-11 13:51:07.999  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 2ms lastUpdatedAfter : 60123 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-11 13:51:09.579  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:09.580  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:11.249  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5670 214564 d 732 75336 f 2279 2279 iot 12270 11229 th 465232 0 0 pt 0 inp 0 0 382.385
,10-11 13:51:12.056  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 298 (W:14), CP = 252, CUR = 159, LCD = 57
,10-11 13:51:12.611  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:12.611  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:15.646  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:15.646  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:16.256  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5675 214628 d 733 75340 f 2281 2281 iot 12270 11233 th 465236 0 0 pt 0 inp 0 0 387.390
,10-11 13:51:16.272  3701  4923 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:51:17.304  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:51:18.671  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:18.671  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:18.907  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:51:19.549  3701  4018 D WifiWatchdogStateMachine:  [|215] []
,10-11 13:51:21.262  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5683 214664 d 733 75340 f 2282 2282 iot 12270 11234 th 465240 0 0 pt 0 inp 0 0 392.397
,10-11 13:51:21.702  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:21.703  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:22.082  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 296 (W:14), CP = 251, CUR = 156, LCD = 57
,10-11 13:51:24.736  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:24.736  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:26.269  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5684 214676 d 733 75340 f 2283 2283 iot 12270 11235 th 465244 0 0 pt 0 inp 0 0 397.403
,10-11 13:51:26.337  3701  4913 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:51:27.766  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:27.766  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:30.800  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:30.801  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:31.275  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5685 214680 d 733 75340 f 2284 2284 iot 12270 11236 th 465244 0 0 pt 0 inp 0 0 402.410
,10-11 13:51:32.109  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 294 (W:14), CP = 251, CUR = 154, LCD = 57
,10-11 13:51:32.399  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:51:32.401  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-11 13:51:32.402  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:51:32.402  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:51:33.826  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:33.826  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:34.508  3701  4459 E Watchdog: !@Sync 13 [11_paź_13_51_34.507]
,10-11 13:51:36.280  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5686 214692 d 733 75340 f 2285 2285 iot 12270 11237 th 465960 0 0 pt 0 inp 0 0 407.415
,10-11 13:51:36.405  3701  4181 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:51:36.859  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:36.859  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:39.901  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:39.901  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:42.139  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 292 (W:14), CP = 251, CUR = 152, LCD = 57
,10-11 13:51:42.928  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:42.928  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:45.961  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:45.962  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:46.290  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5688 214708 d 733 75340 f 2287 2287 iot 12270 11239 th 465972 0 0 pt 0 inp 0 0 417.425
,10-11 13:51:46.470  3701  3729 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:51:48.990  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:48.990  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:51.296  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5689 214712 d 733 75340 f 2288 2288 iot 12270 11240 th 465940 0 0 pt 0 inp 0 0 422.431
,10-11 13:51:52.022  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:52.022  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:52.168  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 292 (W:14), CP = 250, CUR = 150, LCD = 57
,10-11 13:51:55.044  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:55.044  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:51:56.301  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5690 214724 d 733 75340 f 2289 2289 iot 12270 11241 th 465912 0 0 pt 0 inp 0 0 427.436
,10-11 13:51:56.539  3701  3728 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:51:58.066  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:51:58.066  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:00.000  3701  3864 D SamsungAlarmManager: Expired : 8
10-11 13:52:00.001  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{57c159 type 3 when 431137 android}
,10-11 13:52:00.012  3701  3701 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171011T135300 - CU:1000/CP:3701
,10-11 13:52:00.021  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,10-11 13:52:00.022  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-11 13:52:00.023  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-11 13:52:00.039  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,10-11 13:52:00.039  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-11 13:52:00.041  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-11 13:52:00.052  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:52:00.054  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:52:00.057  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:52:00.060  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:52:00.072  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:52:00.074  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
10-11 13:52:00.075  4070  4070 V hong    : mid yDiff = 438
10-11 13:52:00.076  4070  4070 V hong    : mid yDiff = 438
,10-11 13:52:00.077  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
,10-11 13:52:00.077  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-11 13:52:00.085  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:52:00.087  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:52:00.099  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
10-11 13:52:00.101  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:52:00.116  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
10-11 13:52:00.120  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-11 13:52:00.126  5166  5166 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-11 13:52:00.127  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
10-11 13:52:00.131  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-11 13:52:00.137  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-11 13:52:00.139  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,10-11 13:52:00.141  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-11 13:52:00.142  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,10-11 13:52:00.145  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-11 13:52:00.149  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-11 13:52:00.151  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CCC51ED6ECAC67D3269459B179A63D26253E390080A74CC3B90F9B008C5D28762A3B3F3EB2235767A5F5B783C24F612ED356792FCEFA090BB1DF044BF0504BF47]}
,10-11 13:52:00.152  5166  5166 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-11 13:52:01.087  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:01.087  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:02.193  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 291 (W:14), CP = 250, CUR = 147, LCD = 57
,10-11 13:52:02.404  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:52:02.405  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-11 13:52:02.407  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:52:02.407  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:52:04.120  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:04.120  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:04.509  3701  4459 E Watchdog: !@Sync 14 [11_paź_13_52_04.509]
,10-11 13:52:06.311  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5692 214740 d 733 75340 f 2291 2291 iot 12270 11242 th 466040 0 0 pt 0 inp 0 0 437.446
,10-11 13:52:06.604  3701  4921 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:52:06.605  3701  4921 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:52:06.606  3701  4921 D BatteryService: online:4, current avg:146, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:161
10-11 13:52:06.606  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:52:06.616  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,10-11 13:52:06.617  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:52:06.620  3701  3701 D GameManagerService: new battery level: 100
10-11 13:52:06.626  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:52:06.626  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:52:06.636  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-11 13:52:06.640  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:52:06.641  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:52:06.663  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
10-11 13:52:06.665  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-11 13:52:06.665  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:52:07.152  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-11 13:52:07.152  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:08.103  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-11 13:52:08.103  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-11 13:52:08.103  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-11 13:52:08.110  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60110 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-11 13:52:10.175  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:10.175  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:11.316  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5697 214832 d 734 75344 f 2294 2294 iot 12280 11247 th 466016 0 0 pt 0 inp 0 0 442.452
,10-11 13:52:12.221  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 250, CUR = 145, LCD = 57
,10-11 13:52:12.667  3701  3800 I PowerManagerService: [PWL] On : 0 (443803 ms ago)
10-11 13:52:12.667  3701  3800 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-11 13:52:13.207  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:13.207  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:13.984  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:52:16.241  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:16.241  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:16.322  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5701 214892 d 735 75348 f 2296 2296 iot 12280 11250 th 465984 0 0 pt 0 inp 0 0 447.457
,10-11 13:52:16.671  3701  3919 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:52:17.337  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:52:19.272  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:19.272  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:19.781  3701  4018 D WifiWatchdogStateMachine:  [|214] []
,10-11 13:52:21.327  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5709 214928 d 735 75348 f 2297 2297 iot 12280 11252 th 465988 0 0 pt 0 inp 0 0 452.462
,10-11 13:52:22.249  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 250, CUR = 144, LCD = 57
,10-11 13:52:22.306  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:22.306  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:25.329  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:25.329  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:26.333  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5710 214940 d 735 75348 f 2298 2298 iot 12280 11253 th 465988 0 0 pt 0 inp 0 0 457.468
,10-11 13:52:26.736  3701  4543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:52:28.361  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:28.362  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:29.496  3701  3864 D SamsungAlarmManager: Expired : 4
,10-11 13:52:29.497  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135727, SetElapsed=758350, nowELAPSED=460633
10-11 13:52:29.497  3701  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171011T135300, SetElapsed=491136, nowELAPSED=460634
10-11 13:52:29.498  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@cbe12b alarm=Alarm{e7bedff type 2 when 460632 android}
,10-11 13:52:29.502  3701  3930 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,10-11 13:52:29.505 10214 10214 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-11 13:52:29.506 10214 10214 I wpa_supplicant: P2P: Current p2p state = IDLE
,10-11 13:52:29.516  3701  3957 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171011T135244 - CU:1000/CP:3701
10-11 13:52:29.517  3701  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135244, SetElapsed=475646, nowELAPSED=460653
,10-11 13:52:29.519 10214 10214 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-11 13:52:31.338  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5711 214944 d 735 75348 f 2299 2299 iot 12290 11253 th 465988 0 0 pt 0 inp 0 0 462.473
,10-11 13:52:31.383  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:31.384  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:32.275  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 249, CUR = 143, LCD = 57
,10-11 13:52:32.408  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:52:32.410  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-11 13:52:32.411  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:52:32.411  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:52:33.573  3294  3778 D Netd    : Iface wlan0 link up
,10-11 13:52:33.574 10214 10214 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
10-11 13:52:33.577  3701  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-11 13:52:33.577  3701  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-11 13:52:33.581  3701  3957 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3701 / listener:android.app.AlarmManager$ListenerWrapper@f8237cc
10-11 13:52:33.584  3701  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171011T135727, SetElapsed=758350, nowELAPSED=464720
,10-11 13:52:34.417  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:34.417  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:34.511  3701  4459 E Watchdog: !@Sync 15 [11_paź_13_52_34.510]
,10-11 13:52:34.864  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:52:36.344  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5712 214956 d 735 75348 f 2300 2300 iot 12290 11254 th 465992 0 0 pt 0 inp 0 0 467.478
,10-11 13:52:36.804  3701  4921 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:52:37.450  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:37.450  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:39.002  3294  3775 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-11 13:52:40.475  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:40.476  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:41.349  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5713 214960 d 735 75348 f 2301 2301 iot 12290 11255 th 466000 0 0 pt 0 inp 0 0 472.484
,10-11 13:52:42.300  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 249, CUR = 141, LCD = 57
,10-11 13:52:43.509  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:43.509  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:46.354  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5714 214972 d 735 75348 f 2302 2302 iot 12290 11256 th 465972 0 0 pt 0 inp 0 0 477.489
,10-11 13:52:46.537  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:46.537  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:46.877  3701  4887 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:52:46.878  3701  4887 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:52:46.878  3701  4887 D BatteryService: online:4, current avg:139, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:123
10-11 13:52:46.878  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:52:46.888  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-11 13:52:46.889  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:52:46.892  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:52:46.898  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:52:46.899  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:52:46.910  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-11 13:52:46.915  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
10-11 13:52:46.915  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
10-11 13:52:46.921  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:52:46.931  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-11 13:52:46.932  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:52:47.477  9789  9853 I jxcore-log: 2017-10-11 11:52:47 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-11 13:52:47.477  9789  9853 I jxcore-log: 
,10-11 13:52:49.570  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:49.570  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:50.509  9789  9853 I jxcore-log: 2017-10-11 11:52:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:52:50.509  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:52:50.509  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:52:50.509  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:52:50.509  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:52:50.509  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:52:50.509  9789  9853 I jxcore-log: 
,10-11 13:52:50.512  9789  9853 I jxcore-log: 2017-10-11 11:52:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:52:50.512  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:52:50.512  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:52:50.512  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:52:50.512  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:52:50.512  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:52:50.512  9789  9853 I jxcore-log: 
,10-11 13:52:51.360  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5716 214980 d 735 75348 f 2304 2304 iot 12290 11257 th 465892 0 0 pt 0 inp 0 0 482.495
,10-11 13:52:52.326  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 249, CUR = 85, LCD = 57
,10-11 13:52:52.604  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:52.604  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:54.046  9789  9853 I jxcore-log: 2017-10-11 11:52:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:52:54.046  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:52:54.046  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:52:54.046  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:52:54.046  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:52:54.046  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:52:54.046  9789  9853 I jxcore-log: 
,10-11 13:52:54.050  9789  9853 I jxcore-log: 2017-10-11 11:52:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:52:54.050  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:52:54.050  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:52:54.050  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:52:54.050  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:52:54.050  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:52:54.050  9789  9853 I jxcore-log: 
,10-11 13:52:54.396  3295  3295 I bootchecker: bootchecker wake up!!
,10-11 13:52:55.631  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:55.631  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:56.365  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5717 214996 d 735 75348 f 2305 2305 iot 12290 11258 th 465900 0 0 pt 0 inp 0 0 487.500
,10-11 13:52:58.665  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:52:58.666  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:52:59.999  3701  3864 D SamsungAlarmManager: Expired : 8
,10-11 13:53:00.001  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{dab6b1b type 3 when 491136 android}
,10-11 13:53:00.011  3701  3701 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171011T135359 - CU:1000/CP:3701
10-11 13:53:00.011  3701  3701 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171011T135359, SetElapsed=551136, nowELAPSED=491148
,10-11 13:53:00.016  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,10-11 13:53:00.016  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
,10-11 13:53:00.017  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-11 13:53:00.035  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,10-11 13:53:00.035  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
10-11 13:53:00.037  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-11 13:53:00.055  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:53:00.057  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:53:00.060  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
10-11 13:53:00.062  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:53:00.074  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
10-11 13:53:00.075  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
10-11 13:53:00.076  4070  4070 V hong    : mid yDiff = 438
10-11 13:53:00.077  4070  4070 V hong    : mid yDiff = 438
,10-11 13:53:00.078  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-11 13:53:00.078  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-11 13:53:00.083  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
10-11 13:53:00.085  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:53:00.102  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:53:00.104  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:53:00.118  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-11 13:53:00.122  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-11 13:53:00.127  5166  5166 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
10-11 13:53:00.129  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-11 13:53:00.132  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-11 13:53:00.138  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-11 13:53:00.139  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
10-11 13:53:00.140  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-11 13:53:00.141  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-11 13:53:00.142  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
10-11 13:53:00.147  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
10-11 13:53:00.149  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CCC51ED6ECAC67D3269459B179A63D262600790EBE4B62CBEB9BA9502287ECCACE0D59A9D3D14AC8E52F4473F5C188D9AB013E6884B7CA8D198E9A4CB96D9BB8F]}
10-11 13:53:00.150  5166  5166 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-11 13:53:01.695  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:01.695  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:02.061  9789  9853 I jxcore-log: 2017-10-11 11:53:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:02.061  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:02.061  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:02.061  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:02.061  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:02.061  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:02.061  9789  9853 I jxcore-log: 
,10-11 13:53:02.066  9789  9853 I jxcore-log: 2017-10-11 11:53:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:02.066  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:02.066  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:02.066  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:02.066  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:02.066  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:02.066  9789  9853 I jxcore-log: 
,10-11 13:53:02.351  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, CUR = 34, LCD = 57
,10-11 13:53:02.413  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:53:02.414  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-11 13:53:02.416  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:53:02.416  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:53:04.513  3701  4459 E Watchdog: !@Sync 16 [11_paź_13_53_04.512]
,10-11 13:53:04.728  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:04.728  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:07.764  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:07.765  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:08.156  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-11 13:53:08.156  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-11 13:53:08.156  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-11 13:53:08.164  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60054 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-11 13:53:10.791  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-11 13:53:10.791  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:11.380  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5723 215092 d 736 75352 f 2307 2307 iot 12290 11262 th 465876 0 0 pt 0 inp 0 0 502.515
,10-11 13:53:12.095  9789  9853 I jxcore-log: 2017-10-11 11:53:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:12.095  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:12.095  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:12.095  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:12.095  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:12.095  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:12.095  9789  9853 I jxcore-log: 
,10-11 13:53:12.098  9789  9853 I jxcore-log: 2017-10-11 11:53:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:12.098  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:12.098  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:12.098  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:12.098  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:12.098  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:12.098  9789  9853 I jxcore-log: 
,10-11 13:53:12.375  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, CUR = 13, LCD = 57
,10-11 13:53:13.824  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:13.824  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:16.386  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5727 215144 d 737 75356 f 2308 2308 iot 12290 11265 th 465816 0 0 pt 0 inp 0 0 507.521
,10-11 13:53:16.853  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:16.853  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:16.931  3701  4180 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
10-11 13:53:16.932  3701  4180 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:53:16.933  3701  4180 D BatteryService: online:4, current avg:9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
,10-11 13:53:16.933  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:53:16.943  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-11 13:53:16.943  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:53:16.948  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:53:16.954  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,10-11 13:53:16.955  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:53:16.964  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
10-11 13:53:16.974  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
10-11 13:53:16.975  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:53:16.992  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:53:16.994  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-11 13:53:16.994  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:53:19.876  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:19.876  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:20.019  3701  4018 D WifiWatchdogStateMachine:  [|215] []
,10-11 13:53:21.392  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5735 215180 d 737 75356 f 2309 2309 iot 12290 11266 th 465864 0 0 pt 0 inp 0 0 512.527
,10-11 13:53:22.132  9789  9853 I jxcore-log: 2017-10-11 11:53:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:22.132  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:22.132  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:22.132  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:22.132  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:22.132  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:22.132  9789  9853 I jxcore-log: 
,10-11 13:53:22.136  9789  9853 I jxcore-log: 2017-10-11 11:53:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:22.136  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:22.136  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:22.136  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:22.136  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:22.136  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:22.136  9789  9853 I jxcore-log: 
,10-11 13:53:22.401  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, CUR = 5, LCD = 57
,10-11 13:53:22.668  3701  3800 I PowerManagerService: [PWL] On : 0 (513804 ms ago)
10-11 13:53:22.668  3701  3800 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-11 13:53:22.911  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:22.911  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:25.940  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:25.940  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:26.397  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5736 215192 d 737 75356 f 2310 2310 iot 12290 11267 th 465864 0 0 pt 0 inp 0 0 517.532
,10-11 13:53:28.975  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:28.976  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:32.005  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:32.005  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:32.169  9789  9853 I jxcore-log: 2017-10-11 11:53:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:32.169  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:32.169  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:32.169  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:32.169  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:32.169  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:32.169  9789  9853 I jxcore-log: 
,10-11 13:53:32.172  9789  9853 I jxcore-log: 2017-10-11 11:53:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:32.172  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:32.172  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:32.172  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:32.172  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:32.172  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:32.172  9789  9853 I jxcore-log: 
,10-11 13:53:32.417  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:53:32.418  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-11 13:53:32.419  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
,10-11 13:53:32.420  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:53:32.427  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 248, CUR = 2, LCD = 57
,10-11 13:53:34.514  3701  4459 E Watchdog: !@Sync 17 [11_paź_13_53_34.514]
,10-11 13:53:35.039  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:35.039  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:38.065  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:38.065  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:41.096  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:41.096  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:42.213  9789  9853 I jxcore-log: 2017-10-11 11:53:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:42.213  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:42.213  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:42.213  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:42.213  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:42.213  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:42.213  9789  9853 I jxcore-log: 
,10-11 13:53:42.216  9789  9853 I jxcore-log: 2017-10-11 11:53:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:42.216  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:42.216  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:42.216  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:42.216  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:42.216  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:42.216  9789  9853 I jxcore-log: 
,10-11 13:53:42.454  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 247, LCD = 57
,10-11 13:53:44.128  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:44.128  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:46.987  3701  4918 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-11 13:53:46.988  3701  4918 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-11 13:53:46.989  3701  4918 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
10-11 13:53:46.989  3701  3701 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-11 13:53:47.001  3701  3701 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-11 13:53:47.001  3701  3701 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-11 13:53:47.005  3701  3701 D GameManagerService: new battery level: 100
,10-11 13:53:47.011  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-11 13:53:47.012  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-11 13:53:47.022  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-11 13:53:47.027  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
10-11 13:53:47.028  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,10-11 13:53:47.037  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-11 13:53:47.061  9917  9917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-11 13:53:47.061  9917  9974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-11 13:53:47.141  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:47.141  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:50.171  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:50.171  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:51.423  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5738 215200 d 737 75356 f 2311 2311 iot 12290 11268 th 465820 0 0 pt 0 inp 0 0 542.558
,10-11 13:53:52.249  9789  9853 I jxcore-log: 2017-10-11 11:53:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:52.249  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:52.249  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:52.249  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:52.249  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:52.249  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:52.249  9789  9853 I jxcore-log: 
,10-11 13:53:52.252  9789  9853 I jxcore-log: 2017-10-11 11:53:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:53:52.252  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:53:52.252  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:53:52.252  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:53:52.252  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:53:52.252  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:53:52.252  9789  9853 I jxcore-log: 
,10-11 13:53:52.480  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 247, LCD = 57
,10-11 13:53:53.199  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:53.199  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:56.232  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:56.232  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:53:56.428  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5739 215212 d 737 75356 f 2312 2312 iot 12290 11269 th 465788 0 0 pt 0 inp 0 0 547.563
,10-11 13:53:59.254  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:53:59.255  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:54:00.000  3701  3864 D SamsungAlarmManager: Expired : 8
,10-11 13:54:00.001  3701  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{58b9df7 type 3 when 551136 android}
,10-11 13:54:00.009  3701  3701 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171011T135500 - CU:1000/CP:3701
10-11 13:54:00.010  3701  3701 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171011T135500, SetElapsed=611137, nowELAPSED=551147
,10-11 13:54:00.015  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,10-11 13:54:00.016  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-11 13:54:00.016  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-11 13:54:00.038  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,10-11 13:54:00.049  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-11 13:54:00.060  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-11 13:54:00.072  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:54:00.075  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:54:00.080  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:54:00.082  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:54:00.091  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:54:00.093  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:54:00.094  4070  4070 V hong    : mid yDiff = 438
10-11 13:54:00.094  4070  4070 V hong    : mid yDiff = 438
10-11 13:54:00.096  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-11 13:54:00.096  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-11 13:54:00.101  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:54:00.104  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:54:00.124  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-11 13:54:00.125  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-11 13:54:00.141  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-11 13:54:00.144  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-11 13:54:00.149  5166  5166 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-11 13:54:00.151  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-11 13:54:00.159  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-11 13:54:00.165  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-11 13:54:00.165  5166  5166 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
10-11 13:54:00.166  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-11 13:54:00.166  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-11 13:54:00.167  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-11 13:54:00.169  5166  5166 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-11 13:54:00.170  5166  5166 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CCC51ED6ECAC67D3269459B179A63D262BB98D87D645D898DB8C4121EAF327209F7BA7E2586C52EDE5EA03611C5A9E1AA5D616B6448064F2FEA2ABFDD8ABBFB2B]}
10-11 13:54:00.170  5166  5166 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-11 13:54:02.289  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:54:02.290  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:54:02.291  9789  9853 I jxcore-log: 2017-10-11 11:54:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:54:02.291  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:54:02.291  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:54:02.291  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:54:02.291  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:54:02.291  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:54:02.291  9789  9853 I jxcore-log: 
,10-11 13:54:02.294  9789  9853 I jxcore-log: 2017-10-11 11:54:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-11 13:54:02.294  9789  9853 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-11 13:54:02.294  9789  9853 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-11 13:54:02.294  9789  9853 I jxcore-log: emit@events.js:82:1
10-11 13:54:02.294  9789  9853 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-11 13:54:02.294  9789  9853 I jxcore-log: emit@events.js:82:1''
10-11 13:54:02.294  9789  9853 I jxcore-log: 
,10-11 13:54:02.420  3701  3701 D UsbMonitorService: readUsbState++
,10-11 13:54:02.421  3701  3701 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-11 13:54:02.423  3701  3701 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-11 13:54:02.423  3701  3701 D UsbMonitorService: Posting Message again
,10-11 13:54:02.507  3701  5735 D SSRM:f  : SIOP:: AP = 290, PST = 290 (W:14), CP = 247, LCD = 57
,10-11 13:54:04.516  3701  4459 E Watchdog: !@Sync 18 [11_paź_13_54_04.516]
,10-11 13:54:05.322  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-11 13:54:05.322  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:54:08.263  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-11 13:54:08.263  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-11 13:54:08.263  4993  5046 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-11 13:54:08.270  4993  5046 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60106 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-11 13:54:08.344  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:54:08.345  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:54:10.926  5202  5208 I art     : Do full code cache collection, code=121KB, data=117KB
10-11 13:54:10.927  5202  5208 I art     : After code cache collection, code=107KB, data=87KB
,10-11 13:54:11.378  3701  3930 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-11 13:54:11.379  3701  3930 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-11 13:54:11.443  4648  4648 D io_stats: !@   8,0 r 26161 2316976 w 5744 215304 d 738 75360 f 2314 2314 iot 12290 11274 th 465600 0 0 pt 0 inp 0 0 562.578

```
