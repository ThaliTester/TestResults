#### Test 113351851ae9ffea_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,07-21 16:01:20.081  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
--------- beginning of main
07-21 16:01:20.599 10084 10084 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 10084 | app_process
07-21 16:01:20.599 10084 10084 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-21 16:01:20.605 10084 10084 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-21 16:01:20.605 10084 10084 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-21 16:01:20.607 10084 10084 D AndroidRuntime: CheckJNI is OFF
07-21 16:01:20.607 10084 10084 D AndroidRuntime: addProductProperty: start
07-21 16:01:20.648 10084 10084 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-21 16:01:20.648 10084 10084 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-21 16:01:20.664 10084 10084 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-21 16:01:20.664 10084 10084 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-21 16:01:20.664 10084 10084 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-21 16:01:20.710 10084 10084 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-21 16:01:20.728 10084 10084 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-21 16:01:20.750 10084 10084 I Enhanced Zygote ASLR: DISABLED!
07-21 16:01:20.750 10084 10084 I Radio-JNI: register_android_hardware_Radio DONE
07-21 16:01:20.753 10084 10084 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-21 16:01:20.753 10084 10084 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-21 16:01:20.754 10084 10084 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-21 16:01:20.762 10084 10084 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-21 16:01:20.778  3675  4178 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}} from uid 2000 on display 0
07-21 16:01:20.817  3675  4178 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-21 16:01:20.820  3675  4178 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3675  pkgName : AMS_RESUME@CPU_MIN@7
07-21 16:01:20.823  3675  4178 D ActivityManager: mActivityResumeBooster.acquire()
07-21 16:01:20.825  3675  4178 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{a6eb5f7d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-21 16:01:20.825  3675  4178 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{a6eb5f7d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1}
07-21 16:01:20.826  3675  4178 D InputDispatcher: Focused application set to: xxxx
07-21 16:01:20.826  3675  4178 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{a6eb5f7d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} next=ActivityRecord{20d031bd0 u0 com.thaliproject.thalitest/.MainActivity t5} mFocusedStack=ActivityStack{ed66897d0 stackId=1, 2 tasks}
07-21 16:01:20.827  3675  4178 D MountService: getExternalStorageMountMode : 1
07-21 16:01:20.827  3675  4178 D MountService: getExternalStorageMountMode : 3
07-21 16:01:20.827  3675  4178 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10033, packageName : com.thaliproject.thalitest
07-21 16:01:20.831  3675  3786 D WindowManager: addWindow: android.view.ViewRootImpl$W@5206cef displayId=0
07-21 16:01:20.831  3675  3786 D InputTransport: Input channel constructed: fd=455
07-21 16:01:20.831  3675  3786 D InputTransport: Input channel constructed: fd=456
07-21 16:01:20.832  3675  3786 D ViewRootImpl@f905ce[thalitest]: setView = DecorView@cee8a85[thalitest] touchMode=true
07-21 16:01:20.842 10094 10094 E Zygote  : v2
07-21 16:01:20.842 10094 10094 I libpersona: KNOX_SDCARD checking this for 10033
07-21 16:01:20.842 10094 10094 I libpersona: KNOX_SDCARD not a persona
07-21 16:01:20.843  3675  4178 I ActivityManager: Start proc 10094:com.thaliproject.thalitest/u0a33 for activity com.thaliproject.thalitest/.MainActivity
07-21 16:01:20.844 10094 10094 E Zygote  : accessInfo : 0
07-21 16:01:20.845 10084 10084 D AndroidRuntime: Shutting down VM
07-21 16:01:20.848  3675  3786 V WindowManager: Relayout Window{fd963fcd0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-21 16:01:20.849  3112  3112 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
07-21 16:01:20.850 10094 10094 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-21 16:01:20.853 10094 10094 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
07-21 16:01:20.873 10084 10084 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-21 16:01:20.873 10084 10084 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-21 16:01:20.873 10084 10084 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-21 16:01:20.873 10084 10084 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-21 16:01:20.876 10094 10094 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:20.876 10094 10094 D ActivityThread: Added TimaKeyStore provider
07-21 16:01:20.880  3675  4987 I ActivityManager: DSS on for com.thaliproject.thalitest and scale is 1.0
07-21 16:01:20.884  3675  4987 I WindowManager: Failed to capture screenshot of Token{245d26d ActivityRecord{f2ba84d0 u0 com.samsung.android.MtpApplication/.USBConnection t4}} appWin=Window{53bccb4d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-21 16:01:20.887  3675  3786 D WindowManager: finishDrawingWindow: Window{fd963fcd0 u0 Starting com.thaliproject.thalitest} mDrawState=DRAW_PENDING
07-21 16:01:20.895  3675  4987 D GameManagerService: sem_perfomance_mode: 0
07-21 16:01:20.895  3675  3675 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-21 16:01:20.895  3675  3675 D GameManagerService: unexpected mPrevNotiType: -1
07-21 16:01:20.900  3675  4939 V WindowManager: Relayout Window{53bccb4d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-21 16:01:20.900  3675  4987 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-21 16:01:20.901  3675  4987 D GameManagerService: sem_perfomance_mode: 0
,07-21 16:01:20.904  3675  3720 V WindowManager: Relayout Window{aeb15b2d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-21 16:01:20.904  3675  3720 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowManagerService.tryStartExitingAnimation:3504 com.android.server.wm.WindowManagerService.relayoutWindow:3360 com.android.server.wm.Session.relayoutEx:244 android.view.IWindowSession$Stub.onTransact:407 com.android.server.wm.Session.onTransact:151 
,07-21 16:01:20.904  3112  9736 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-21 16:01:20.905  3112  3892 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
,07-21 16:01:20.906  3675  5817 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-21 16:01:20.906  3675  5817 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-21 16:01:20.906  4768  4781 D ForegroundUtils: could not check pending caller
07-21 16:01:20.906  4768  4781 D ForegroundUtils: could not check pending caller
07-21 16:01:20.906  4768  4781 D ForegroundUtils: could not check pending caller
,07-21 16:01:20.911  4896  4896 D Launcher: onTrimMemory. Level: 20
,07-21 16:01:20.915  3675  3927 V WindowManager: Relayout Window{aeb15b2d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-21 16:01:20.916  3675  5817 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-21 16:01:20.917  3675  5817 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-21 16:01:20.919  3675  4942 V WindowManager: Relayout Window{4357ba1d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,07-21 16:01:20.922  3675  4988 V WindowManager: Relayout Window{53bccb4d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-21 16:01:20.946 10094 10094 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:20.972 10094 10094 I CordovaLog: Changing log level to DEBUG(3)
07-21 16:01:20.972 10094 10094 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-21 16:01:20.972 10094 10094 D CordovaActivity: CordovaActivity.onCreate()
,07-21 16:01:20.986 10094 10094 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm
,07-21 16:01:20.991 10094 10094 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-21 16:01:21.037  3675  3986 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,07-21 16:01:21.044 10094 10094 I cr_LibraryLoader: Time to load native libraries: 15 ms (timestamps 8809-8824)
07-21 16:01:21.044 10094 10094 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-21 16:01:21.065 10094 10094 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-21 16:01:21.072 10094 10094 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-21 16:01:21.092 10094 10094 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-21 16:01:21.231  3675  3927 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10033
,07-21 16:01:21.231  3675  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-21 16:01:21.233  3675  3675 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
,07-21 16:01:21.233  3675  3913 I KnoxVpnEngineService: vpn handle : Message received
,07-21 16:01:21.255  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:21.255  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:01:21.271 10094 10094 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 10094
,07-21 16:01:21.273  3675  3720 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/10094 for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-21 16:01:21.274  3675  3956 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-21 16:01:21.274  3675  3956 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-21 16:01:21.274  3675  3956 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-21 16:01:21.274  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:01:21.274  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.274  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.274  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.274  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:21.274  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.274  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.274  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.275  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
,07-21 16:01:21.275  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:21.275  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.275  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-21 16:01:21.318 10094 10094 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-21 16:01:21.327 10094 10094 D PluginManager: init()
,07-21 16:01:21.331 10094 10094 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-21 16:01:21.348 10094 10094 I cr_Ime  : ImeThread is enabled.
,07-21 16:01:21.363 10094 10094 D CordovaActivity: Started the activity.
,07-21 16:01:21.365 10094 10094 D CordovaActivity: Resumed the activity.
,07-21 16:01:21.379  3675  4865 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@ee25648 displayId=0
,07-21 16:01:21.379  3675  4865 D InputTransport: Input channel constructed: fd=457
07-21 16:01:21.379  3675  4865 D InputTransport: Input channel constructed: fd=459
,07-21 16:01:21.380  3675  4865 D InputTransport: Input channel destroyed: fd=459
,07-21 16:01:21.381 10094 10094 D InputTransport: Input channel constructed: fd=98
07-21 16:01:21.381 10094 10094 D ViewRootImpl@57af524[MainActivity]: setView = DecorView@9e3888d[MainActivity] touchMode=true
,07-21 16:01:21.382  3675  4987 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-21 16:01:21.383  3675  4987 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-21 16:01:21.383  3675  3675 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-21 16:01:21.383 10094 10094 D CordovaActivity: Paused the activity.
,07-21 16:01:21.384  3675  3675 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-21 16:01:21.387  3675  3758 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-21 16:01:21.394 10094 10094 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 10094
,07-21 16:01:21.395  3675  3939 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/10094 for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-21 16:01:21.396  3675  3956 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-21 16:01:21.396  3675  3956 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
,07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:21.396  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-21 16:01:21.408  3675  3720 V WindowManager: Relayout Window{28ca06d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-21 16:01:21.408  3112  3112 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-21 16:01:21.418 10094 10141 I OpenGLRenderer: Initialized EGL, version 1.4
07-21 16:01:21.418 10094 10141 D OpenGLRenderer: Swap behavior 1
,07-21 16:01:21.422 10094 10141 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-21 16:01:21.424 10094 10141 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-21 16:01:21.424 10094 10094 D CordovaActivity: Stopped the activity.
,07-21 16:01:21.432  3675  3786 V WindowManager: Now policy hidden: Window{28ca06d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}
,07-21 16:01:21.455 10094 10146 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-21 16:01:21.468 10094 10146 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-21 16:01:21.468 10094 10146 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-21 16:01:21.470 10094 10146 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-21 16:01:21.471 10094 10146 W AudioCapabilities: Unsupported mime audio/x-ima
,07-21 16:01:21.472 10094 10146 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-21 16:01:21.472 10094 10146 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-21 16:01:21.472 10094 10146 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.476 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-21 16:01:21.477  3675  4178 D WindowManager: finishDrawingWindow: Window{28ca06d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=DRAW_PENDING
,07-21 16:01:21.478 10094 10094 D ViewRootImpl@57af524[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.478 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.479 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.479 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-21 16:01:21.485  3675  4179 D WindowManager: finishDrawingWindow: Window{28ca06d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=HAS_DRAWN
,07-21 16:01:21.486 10094 10094 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,07-21 16:01:21.487  3675  3786 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-21 16:01:21.487  3675  3675 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
,07-21 16:01:21.488  3675  3675 I KnoxTimeoutHandler: SD activityfalse
07-21 16:01:21.488  3675  3675 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
,07-21 16:01:21.489 10094 10146 W VideoCapabilities: Unsupported mime video/wvc1
07-21 16:01:21.489  3675  3786 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +588ms (total +663ms)
,07-21 16:01:21.490  3675  3758 D ActivityManager: mActivityResumeBoosterTail.acquire()
,07-21 16:01:21.490  3675  3786 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3675  tag : AMS_RESUME@CPU_MIN@7
07-21 16:01:21.490  3675  3786 D ActivityManager: mActivityResumeBooster.release()
07-21 16:01:21.491  3675  3786 D ViewRootImpl@f905ce[thalitest]: dispatchDetachedFromWindow
07-21 16:01:21.491  3675  3786 I WindowManager: Destroying surface Surface(name=Starting com.thaliproject.thalitest) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
,07-21 16:01:21.492  3112  3122 I SurfaceFlinger: id=15 Removed uhalitest (3/5)
07-21 16:01:21.493  3675  3758 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3675  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
07-21 16:01:21.493 10094 10146 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-21 16:01:21.494  3112  9737 I SurfaceFlinger: id=15 Removed uhalitest (-2/5)
,07-21 16:01:21.496  3675  3786 D InputTransport: Input channel destroyed: fd=455
,07-21 16:01:21.496  3675  3786 D InputTransport: Input channel destroyed: fd=456
,07-21 16:01:21.500 10094 10146 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-21 16:01:21.500 10094 10146 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-21 16:01:21.500 10094 10146 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-21 16:01:21.502 10094 10146 W VideoCapabilities: Unsupported mime video/wvc1
,07-21 16:01:21.503 10094 10146 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-21 16:01:21.504 10094 10146 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-21 16:01:21.505 10094 10146 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-21 16:01:21.506 10094 10146 W VideoCapabilities: Unsupported mime video/mp43
,07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.509 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.510 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-21 16:01:21.510 10094 10146 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-21 16:01:21.512 10094 10146 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-21 16:01:21.513 10094 10146 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-21 16:01:21.513 10094 10146 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-21 16:01:21.527 10094 10146 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-21 16:01:21.539 10094 10146 W VideoCapabilities: Unsupported mime video/sorenson
,07-21 16:01:21.555 10094 10146 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-21 16:01:21.581 10094 10094 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 10094
,07-21 16:01:21.722 10094 10094 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-21 16:01:21.732 10094 10094 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-21 16:01:21.773 10094 10154 D jxcore_app_log: JniHelper::setJavaVM(0xf0134000), pthread_self() = -918554336
,07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4f2ea7 added. We now have 1 listener(s)
,07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4f2ea7 added. We now have 1 listener(s)
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-21 16:01:21.777 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-21 16:01:21.779 10094 10154 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,07-21 16:01:21.780 10094 10154 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
07-21 16:01:21.780 10094 10154 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-21 16:01:21.780 10094 10154 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,07-21 16:01:21.782 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-21 16:01:21.782 10094 10154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8cdc7f2 added. We now have 2 listener(s)
07-21 16:01:21.782 10094 10154 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-21 16:01:21.784 10094 10154 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-21 16:01:21.785 10094 10154 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 38881
07-21 16:01:21.785 10094 10154 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 124
07-21 16:01:21.785 10094 10154 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-21 16:01:21.785 10094 10154 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-21 16:01:21.785 10094 10154 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
07-21 16:01:21.785 10094 10154 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 124
,07-21 16:01:21.788 10094 10154 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:01:21.788 10094 10154 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,07-21 16:01:21.794 10094 10154 D BluetoothAdapter: STATE_ON
,07-21 16:01:21.796 10094 10154 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-21 16:01:21.797  3675  3675 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3675  tag : AMS_RESUME_TAIL@CPU_MIN@13
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:21.797 10094 10154 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-21 16:01:21.797 10094 10154 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-21 16:01:21.797 10094 10154 D io.jxcore.node.ConnectivityMonitor: start: OK
07-21 16:01:21.797 10094 10154 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-21 16:01:21.803 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:21.807 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:21.811 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:21.814 10094 10094 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
07-21 16:01:21.814 10094 10094 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,07-21 16:01:22.444 10094 10157 W jxcore-log: Initializing JXcore engine
07-21 16:01:22.444 10094 10157 W jxcore-log: JXcore engine is ready
,07-21 16:01:22.462  3241  3241 E audit   : type=1400 audit(1500645682.456:530): avc:  denied  { ioctl } for  pid=10157 comm="Thread-9" path="socket:[65049]" dev="sockfs" ino=65049 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0 SEPF_SECMOBILE_7.0_0006
07-21 16:01:22.463  3675  3782 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / /system/bin/sh /system/bin/install-recovery.sh
07-21 16:01:22.463  3241  3241 E audit   : type=1300 audit(1500645682.456:530): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3 a1=5451 a2=9089eae5 a3=22 items=0 ppid=3275 pid=10157 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-21 16:01:22.463  3675  3782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-21 16:01:22.466  3675  3782 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-21 16:01:22.466  3241  3241 E audit   : type=1327 audit(1500645682.456:530): proctitle="com.thaliproject.thalitest"
07-21 16:01:22.466  3241  3241 E audit   : type=1320 audit(1500645682.456:530): 
07-21 16:01:22.466  3241  3241 E audit   : type=1400 audit(1500645682.456:531): avc:  denied  { ioctl } for  pid=10157 comm="Thread-9" path="/dev/pmsg0" dev="tmpfs" ino=9181 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0 SEPF_SECMOBILE_7.0_0006
07-21 16:01:22.466  3241  3241 E audit   : type=1300 audit(1500645682.456:531): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=4 a1=5451 a2=9089eae5 a3=22 items=0 ppid=3275 pid=10157 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,07-21 16:01:22.469  3241  3241 E audit   : type=1327 audit(1500645682.456:531): proctitle="com.thaliproject.thalitest"
,07-21 16:01:22.469  3241  3241 E audit   : type=1320 audit(1500645682.456:531): 
,07-21 16:01:22.469  3241  3241 E audit   : type=1400 audit(1500645682.456:532): avc:  denied  { ioctl } for  pid=10157 comm="Thread-9" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4351 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs_trace_marker:s0 tclass=file permissive=0 SEPF_SECMOBILE_7.0_0006
07-21 16:01:22.470  3241  3241 E audit   : type=1300 audit(1500645682.456:532): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=5 a1=5451 a2=9089eae5 a3=22 items=0 ppid=3275 pid=10157 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-21 16:01:22.470  3241  3241 E audit   : type=1327 audit(1500645682.456:532): proctitle="com.thaliproject.thalitest"
07-21 16:01:22.471  3241  3241 E audit   : type=1320 audit(1500645682.456:532): 
07-21 16:01:22.471  3241  3241 E audit   : type=1400 audit(1500645682.456:533): avc:  denied  { ioctl } for  pid=10157 comm="Thread-9" path="socket:[61069]" dev="sockfs" ino=61069 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0 SEPF_SECMOBILE_7.0_0006
07-21 16:01:22.471  3241  3241 E audit   : type=1300 audit(1500645682.456:533): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=54 a1=5451 a2=9089eae5 a3=22 items=0 ppid=3275 pid=10157 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-21 16:01:22.471  3675  3782 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / "com.thaliproject.thalitest"
,07-21 16:01:22.472  3675  3782 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-21 16:01:22.472  9967  9967 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
07-21 16:01:22.473  3241  3241 E audit   : type=1327 audit(1500645682.456:533): proctitle="com.thaliproject.thalitest"
07-21 16:01:22.473  3241  3241 E audit   : type=1320 audit(1500645682.456:533): 
,07-21 16:01:22.474 10094 10157 W jxcore-log: Starting JXcore engine
07-21 16:01:22.475  3675  3782 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-21 16:01:22.478  9967  9967 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-21 16:01:22.509 10094 10157 W jxcore-log: Platform android
07-21 16:01:22.509 10094 10157 W jxcore-log: 
07-21 16:01:22.509 10094 10157 W jxcore-log: Process ARCH arm
07-21 16:01:22.509 10094 10157 W jxcore-log: 
,07-21 16:01:22.605  3675  3685 I art     : Background partial concurrent mark sweep GC freed 207146(11MB) AllocSpace objects, 68(2MB) LOS objects, 28% free, 40MB/56MB, paused 1.514ms total 141.256ms
,07-21 16:01:22.658 10094 10157 I jxcore-log: JXcore Cordova bridge is ready!
07-21 16:01:22.658 10094 10157 I jxcore-log: 
07-21 16:01:22.659 10094 10157 W jxcore-log: JXcore engine is started
,07-21 16:01:22.668 10094 10154 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-21 16:01:22.674 10094 10094 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
07-21 16:01:22.674 10094 10094 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-21 16:01:24.279  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-21 16:01:24.279  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:01:24.322  4645  4645 D io_stats: !@   8,0 r 25859 2297928 w 4677 199092 d 608 73472 f 1917 1917 iot 11260 10668 th 476656 0 0 pt 0 inp 0 0 182.102
,07-21 16:01:24.766  3675  5817 D SSRM:f  : SIOP:: AP = 300, PST = 261 (W:6), CP = 217, CUR = 11, LCD = 57
,07-21 16:01:26.908  3675  5817 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-21 16:01:27.299  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:27.299  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:01:29.327  4645  4645 D io_stats: !@   8,0 r 25859 2297928 w 4719 199324 d 608 73472 f 1917 1917 iot 11260 10673 th 478452 0 0 pt 0 inp 0 0 187.106
,07-21 16:01:29.692 10094 10157 I jxcore-log: 2017-07-21 14:01:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
07-21 16:01:29.692 10094 10157 I jxcore-log: 
,07-21 16:01:29.693 10094 10157 I jxcore-log: 2017-07-21 14:01:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
07-21 16:01:29.693 10094 10157 I jxcore-log: 
07-21 16:01:29.694 10094 10157 I jxcore-log: 2017-07-21 14:01:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
07-21 16:01:29.694 10094 10157 I jxcore-log: 
,07-21 16:01:29.704 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:29.708 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-21 16:01:29.712 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:29.717 10094 10157 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-21 16:01:29.717 10094 10157 I jxcore-log: 2017-07-21 14:01:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
07-21 16:01:29.717 10094 10157 I jxcore-log: 
07-21 16:01:29.718 10094 10157 I jxcore-log: 2017-07-21 14:01:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
07-21 16:01:29.718 10094 10157 I jxcore-log: 
,07-21 16:01:29.719 10094 10157 I jxcore-log: 2017-07-21 14:01:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
07-21 16:01:29.719 10094 10157 I jxcore-log: 
,07-21 16:01:29.984 10094 10157 D ExecuteNativeTests: Running unit tests
07-21 16:01:29.984 10094 10157 D BluetoothAdapter: enable()
,07-21 16:01:29.991  4054  4065 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-21 16:01:29.992  4054  4065 D AdapterProvider: query
,07-21 16:01:29.999  3675  3758 I ActivityManager: KPU : put [com.facebook.appmanager] : 23412 K
,07-21 16:01:30.000  3675  3758 I ActivityManager: Killing 9198:com.facebook.appmanager/u0a98 (adj 906): DHA:empty #33
,07-21 16:01:30.010  4054  4065 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@14bfc50
,07-21 16:01:30.013  4054  4065 D BluetoothAdapterService: updateEvent - already set, update
07-21 16:01:30.013  4054  4065 W BluetoothAdapterService: updateEvent - alreadySet is true
07-21 16:01:30.014  4054  4065 D AdapterProvider: update
,07-21 16:01:30.020  4054  4065 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:30.023 10094 10157 D BluetoothAdapter: enable(): BT is already enabled..!
,07-21 16:01:30.029  3675  3720 D WifiService: setWifiEnabled: true pid=10094, uid=10033
07-21 16:01:30.030  3675  3720 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-21 16:01:30.030  3675  3720 D WifiControlHistoryProvider: query
,07-21 16:01:30.040  3675  4942 D ActivityManager: cleanUpApplicationRecord -- 9198
,07-21 16:01:30.042  4768  4787 D ForegroundUtils: could not check pending caller
,07-21 16:01:30.051  3675  3720 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-21 16:01:30.053  3675  3720 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:30.054  3675  3720 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-21 16:01:30.058  3675  3720 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-21 16:01:30.060  3675  3720 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-21 16:01:30.332  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:30.332  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:01:30.882  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-21 16:01:30.906  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-21 16:01:30.906  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-21 16:01:33.354  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:33.354  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:01:34.332  4645  4645 D io_stats: !@   8,0 r 25866 2297992 w 4727 199532 d 608 73472 f 1920 1920 iot 11270 10679 th 481048 0 0 pt 0 inp 0 0 192.111
,07-21 16:01:34.792  3675  5817 D SSRM:f  : SIOP:: AP = 300, PST = 266 (W:6), CP = 228, CUR = -60, LCD = 57
,07-21 16:01:35.100  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-21 16:01:35.774  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:01:35.776  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-21 16:01:35.777  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:01:35.778  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:01:36.387  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:36.387  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:01:37.844  3675  4460 E Watchdog: !@Sync 6 [21_lip_16_01_37.844]
,07-21 16:01:38.182  3675  3790 I PowerManagerService: [PWL] On : 0 (195963 ms ago)
07-21 16:01:38.182  3675  3790 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-21 16:01:39.337  4645  4645 D io_stats: !@   8,0 r 25866 2297992 w 4737 199632 d 609 73544 f 1921 1921 iot 11270 10681 th 481052 0 0 pt 0 inp 0 0 197.116
,07-21 16:01:39.417  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:39.417  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:01:40.065 10094 10157 I com.test.thalitest.ThaliTestRunner: Running UT
,07-21 16:01:40.105  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-21 16:01:40.140 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-21 16:01:40.140 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7e051b added. We now have 2 listener(s)
07-21 16:01:40.140 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7e051b added. We now have 3 listener(s)
07-21 16:01:40.140 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-21 16:01:40.141 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
07-21 16:01:40.141 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-21 16:01:40.141 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
07-21 16:01:40.142 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-21 16:01:40.142 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1896b8 added. We now have 4 listener(s)
07-21 16:01:40.142 10094 10157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-21 16:01:40.143 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-21 16:01:40.151 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.156 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,07-21 16:01:40.157 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-21 16:01:40.157 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-21 16:01:40.157 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-21 16:01:40.157 10094 10157 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
07-21 16:01:40.158 10094 10157 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-21 16:01:40.158 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-21 16:01:40.158 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-21 16:01:40.158 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-21 16:01:40.159 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
07-21 16:01:40.160 10094 10157 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-21 16:01:40.161 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,07-21 16:01:40.164 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
07-21 16:01:40.164 10094 10157 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,07-21 16:01:40.169 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-21 16:01:40.178 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:40.182 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-21 16:01:40.182 10094 10157 D io.jxcore.node.ConnectivityMonitor: start: OK
07-21 16:01:40.182 10094 10157 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
07-21 16:01:40.182 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
07-21 16:01:40.182 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:01:40.184 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:40.184 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:40.184 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.184 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:01:40.185 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:40.185 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:40.185 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.186 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-21 16:01:40.186 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-21 16:01:40.186 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-21 16:01:40.186 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:01:40.188 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-21 16:01:40.188 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:40.189 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-21 16:01:40.189 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-21 16:01:40.189 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-21 16:01:40.189 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-21 16:01:40.189 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-21 16:01:40.189 10094 10162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,07-21 16:01:40.189 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:01:40.189 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-21 16:01:40.194 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:40.196 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-21 16:01:40.196 10094 10162 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:01:40.196 10094 10162 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:01:40.196 10094 10157 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-21 16:01:40.196 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-21 16:01:40.200 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:40.201 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:40.201 10094 10162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-21 16:01:40.201 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-21 16:01:40.202 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:40.202 10094 10162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@aedd7f7, port: 6, type: 1, local socket address: null, socket type: 0
07-21 16:01:40.203 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:40.206 10094 10157 D BluetoothAdapter: isSecureModeEnabled
07-21 16:01:40.206  4054  4065 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:40.207 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.207 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-21 16:01:40.209 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.211 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.211 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-21 16:01:40.212 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-21 16:01:40.212 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,07-21 16:01:40.214 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.217 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.217 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.218 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-21 16:01:40.218 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-21 16:01:40.218 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "a4d24f35-892b-461f-a6f3-a89e39f3eaf7", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-21 16:01:40.219 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
,07-21 16:01:40.221 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:40.221 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:40.221 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.222 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.222 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-21 16:01:40.222 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-21 16:01:40.223 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.223 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.224 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.225 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.227 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:40.227 10094 10157 D BluetoothAdapter: isSecureModeEnabled
,07-21 16:01:40.227  4054  4825 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:40.228 10094 10157 D BluetoothLeAdvertiser: start advertising
,07-21 16:01:40.230 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.237  4054  4825 D BtGatt.GattService: registerClient() - UUID=247f2ccd-6ec6-45e2-8fb3-bdd12717a9c2
,07-21 16:01:40.341  4054  4176 D BtGatt.GattService: onClientRegistered() - UUID=247f2ccd-6ec6-45e2-8fb3-bdd12717a9c2, clientIf=5, status=0
,07-21 16:01:40.343 10094 10106 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-21 16:01:40.347  4054  4066 E BtGatt.ContextMap: Context not found for ID 5
,07-21 16:01:40.348  4054  4581 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-21 16:01:40.349  4054  4570 D BtGatt.AdvertiseManager: message : 0
07-21 16:01:40.351  4054  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-21 16:01:40.352  4054  4570 D BtGatt.AdvertiseManager: size of list is =0
,07-21 16:01:40.360  4054  4570 D BtGatt.AdvertiseManager: starting advertising
,07-21 16:01:40.366  4054  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-21 16:01:40.371  4054  4635 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-21 16:01:40.389  4054  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-21 16:01:40.393  4054  4570 D BtGatt.AdvertiseManager: starting multi advertising
,07-21 16:01:40.405  4054  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-21 16:01:40.405  4054  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-21 16:01:40.406  4054  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-21 16:01:40.406  4054  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-21 16:01:40.407  4054  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-21 16:01:40.408 10094 10105 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-21 16:01:40.410 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.412 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.412 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-21 16:01:40.414 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.416 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.417 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.418 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.419 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.419 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-21 16:01:40.424 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-21 16:01:40.425 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.431 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.432 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.433 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.434 10094 10157 I io.jxcore.node.ConnectionHelper: start: OK
07-21 16:01:40.435 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-21 16:01:40.437 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-21 16:01:40.438 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-21 16:01:40.438 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-21 16:01:40.440 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-21 16:01:40.442 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-21 16:01:40.444 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-21 16:01:40.445 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:01:40.446 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,07-21 16:01:40.446 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-21 16:01:40.447 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-21 16:01:40.451 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-21 16:01:40.453 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:01:40.454 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-21 16:01:40.454 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-21 16:01:40.460 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-21 16:01:40.461 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-21 16:01:40.462 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-21 16:01:40.462 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-21 16:01:40.463 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-21 16:01:40.778  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-21 16:01:40.778  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-21 16:01:40.778  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-21 16:01:40.786  4924  5006 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60086 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-21 16:01:40.939 10094 10164 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-21 16:01:40.941 10094 10157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-21 16:01:40.942 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
07-21 16:01:40.943 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
,07-21 16:01:40.943 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
07-21 16:01:40.943 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-21 16:01:40.943 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
07-21 16:01:40.944 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-21 16:01:40.944 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-21 16:01:40.944 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
07-21 16:01:40.945 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
,07-21 16:01:40.945 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-21 16:01:40.945 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-21 16:01:40.946 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-21 16:01:40.946 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-21 16:01:40.946 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-21 16:01:40.946 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-21 16:01:40.947 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
,07-21 16:01:40.947 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-21 16:01:40.947 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-21 16:01:40.948 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-21 16:01:40.948 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-21 16:01:40.948 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-21 16:01:40.949 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-21 16:01:40.949 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-21 16:01:40.950 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,07-21 16:01:40.950 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-21 16:01:40.950 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-21 16:01:40.950 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-21 16:01:40.951 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-21 16:01:40.951 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-21 16:01:40.951 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-21 16:01:40.952 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
,07-21 16:01:40.952 10094 10157 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-21 16:01:40.953 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-21 16:01:40.953 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-21 16:01:40.953 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-21 16:01:40.953 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-21 16:01:40.954 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,07-21 16:01:40.954 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-21 16:01:40.955 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,07-21 16:01:40.955 10094 10162 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,07-21 16:01:40.955 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-21 16:01:40.955 10094 10162 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-21 16:01:40.955 10094 10162 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-21 16:01:40.955 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-21 16:01:40.956 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-21 16:01:40.956 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-21 16:01:40.957 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.958 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-21 16:01:40.958 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-21 16:01:40.969 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.970 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.971 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.972 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.974 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.976 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.977 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-21 16:01:40.979 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:40.981 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:40.982 10094 10157 D BluetoothLeScanner: could not find callback wrapper
,07-21 16:01:40.982 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-21 16:01:40.983 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.983 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:40.984 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.984 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,07-21 16:01:40.985 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:40.987 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:40.989 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:40.989 10094 10157 D BluetoothLeAdvertiser: stop advertising
,07-21 16:01:40.991  4054  4568 E BtGatt.ContextMap: Context not found for ID 5
07-21 16:01:40.992  4054  4581 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-21 16:01:40.992  4054  4570 D BtGatt.AdvertiseManager: message : 1
,07-21 16:01:40.994  4054  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
,07-21 16:01:40.994  4054  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-21 16:01:40.996  4054  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-21 16:01:41.002  4054  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-21 16:01:41.002  4054  4176 D BtGatt.GattService: Client app is not null!
,07-21 16:01:41.003 10094 10106 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-21 16:01:41.004  4054  4065 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-21 16:01:41.009 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-21 16:01:41.010 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.010 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-21 16:01:41.010 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.011 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.012 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.012 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-21 16:01:41.012 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-21 16:01:41.013 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-21 16:01:41.014 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.017 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.017 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-21 16:01:41.017 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.018 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.018 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-21 16:01:41.019 10094 10094 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-21 16:01:41.019 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-21 16:01:41.019 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-21 16:01:41.020 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:01:41.020 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:01:41.020 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-21 16:01:41.020 10094 10165 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-21 16:01:41.021 10094 10157 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-21 16:01:41.021 10094 10157 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-21 16:01:41.021 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-21 16:01:41.021 10094 10157 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
07-21 16:01:41.021 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
07-21 16:01:41.021 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.021 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-21 16:01:41.021 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-21 16:01:41.021 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-21 16:01:41.022 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.022 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.023 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.023 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-21 16:01:41.025 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:41.025 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:41.027 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.027 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-21 16:01:41.030 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:41.030 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:41.031 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.031 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-21 16:01:41.031 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-21 16:01:41.032 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-21 16:01:41.032 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:01:41.033 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-21 16:01:41.034 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-21 16:01:41.034 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-21 16:01:41.034 10094 10166 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-21 16:01:41.034 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-21 16:01:41.035 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-21 16:01:41.035 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-21 16:01:41.035 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-21 16:01:41.035 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:01:41.035 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-21 16:01:41.037 10094 10166 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:01:41.037 10094 10166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:01:41.041 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-21 16:01:41.041 10094 10157 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-21 16:01:41.042 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-21 16:01:41.043 10094 10166 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-21 16:01:41.043 10094 10166 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@c6b84d0, port: 6, type: 1, local socket address: null, socket type: 0
07-21 16:01:41.046 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.047 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.049 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.053 10094 10157 D BluetoothAdapter: isSecureModeEnabled
07-21 16:01:41.053  4054  4066 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:41.054 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.055 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-21 16:01:41.056 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.057 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.058 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-21 16:01:41.058 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-21 16:01:41.058 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
07-21 16:01:41.061 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:41.065 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.065 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.065 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-21 16:01:41.065 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-21 16:01:41.065 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "a4d24f35-892b-461f-a6f3-a89e39f3eaf7", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-21 16:01:41.066 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
07-21 16:01:41.066 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:41.066 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:41.067 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.068 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.068 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-21 16:01:41.068 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:41.069 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.069 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.070 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.071 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.073 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.073 10094 10157 D BluetoothAdapter: isSecureModeEnabled
07-21 16:01:41.073  4054  4065 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:41.073 10094 10157 D BluetoothLeAdvertiser: start advertising
07-21 16:01:41.075 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.080  4054  4065 D BtGatt.GattService: registerClient() - UUID=c4368f00-e84c-40e4-9832-409497902d08
,07-21 16:01:41.186  4054  4176 D BtGatt.GattService: onClientRegistered() - UUID=c4368f00-e84c-40e4-9832-409497902d08, clientIf=5, status=0
,07-21 16:01:41.188 10094 10105 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-21 16:01:41.192  4054  4568 E BtGatt.ContextMap: Context not found for ID 5
,07-21 16:01:41.193  4054  4581 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-21 16:01:41.194  4054  4570 D BtGatt.AdvertiseManager: message : 0
07-21 16:01:41.196  4054  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-21 16:01:41.196  4054  4570 D BtGatt.AdvertiseManager: size of list is =0
,07-21 16:01:41.208  4054  4570 D BtGatt.AdvertiseManager: starting advertising
,07-21 16:01:41.213  4054  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-21 16:01:41.216  4054  4635 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-21 16:01:41.231  4054  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-21 16:01:41.234  4054  4570 D BtGatt.AdvertiseManager: starting multi advertising
,07-21 16:01:41.243  4054  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-21 16:01:41.244  4054  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-21 16:01:41.244  4054  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-21 16:01:41.244  4054  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-21 16:01:41.244  4054  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-21 16:01:41.245 10094 10106 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-21 16:01:41.246 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.247 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.247 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-21 16:01:41.247 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.248 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.249 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.250 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.251 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.251 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-21 16:01:41.254 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-21 16:01:41.255 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.255 10094 10157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-21 16:01:41.259 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.260 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.260 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.261 10094 10157 I io.jxcore.node.ConnectionHelper: start: OK
07-21 16:01:41.261 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-21 16:01:41.263 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.263 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,07-21 16:01:41.263 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-21 16:01:41.264 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.265 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.265 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-21 16:01:41.266 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-21 16:01:41.266 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-21 16:01:41.266 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-21 16:01:41.267 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-21 16:01:41.268 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-21 16:01:41.268 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.269 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-21 16:01:41.270 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-21 16:01:41.276 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.276 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-21 16:01:41.277 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-21 16:01:41.277 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-21 16:01:41.278 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-21 16:01:41.764 10094 10168 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-21 16:01:41.769 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,07-21 16:01:41.770 10094 10157 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-21 16:01:41.770 10094 10157 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-21 16:01:41.770 10094 10157 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-21 16:01:41.770 10094 10157 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
07-21 16:01:41.771 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
07-21 16:01:41.771 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:01:41.777 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:41.778 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-21 16:01:41.779 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.779 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-21 16:01:41.779 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-21 16:01:41.787 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:41.788 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:41.789 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 38881
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-21 16:01:41.790 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.790 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,07-21 16:01:41.791 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.792 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.793 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.795 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:41.797 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.797 10094 10157 D BluetoothLeAdvertiser: stop advertising
,07-21 16:01:41.799  4054  4825 E BtGatt.ContextMap: Context not found for ID 5
,07-21 16:01:41.800  4054  4570 D BtGatt.AdvertiseManager: message : 1
07-21 16:01:41.800  4054  4581 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,07-21 16:01:41.801  4054  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-21 16:01:41.801  4054  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-21 16:01:41.803  4054  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-21 16:01:41.810  4054  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-21 16:01:41.810  4054  4176 D BtGatt.GattService: Client app is not null!
,07-21 16:01:41.811 10094 10105 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-21 16:01:41.813  4054  4066 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-21 16:01:41.814 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-21 16:01:41.815 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.815 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-21 16:01:41.816 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.816 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.817 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.817 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-21 16:01:41.818 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.818 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.819 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.819 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-21 16:01:41.819 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-21 16:01:41.819 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "a4d24f35-892b-461f-a6f3-a89e39f3eaf7", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-21 16:01:41.820 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
07-21 16:01:41.820 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:41.821 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-21 16:01:41.822 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.822 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:41.822 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-21 16:01:41.823 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:41.823 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.824 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.825 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:41.827 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:41.828 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:41.828 10094 10157 D BluetoothAdapter: isSecureModeEnabled
,07-21 16:01:41.829  4054  4825 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:41.829 10094 10157 D BluetoothLeAdvertiser: start advertising
,07-21 16:01:41.831 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:41.837  4054  4825 D BtGatt.GattService: registerClient() - UUID=afb212b5-97b3-4a75-9f9e-f96f1ecedf9e
,07-21 16:01:41.940  4054  4176 D BtGatt.GattService: onClientRegistered() - UUID=afb212b5-97b3-4a75-9f9e-f96f1ecedf9e, clientIf=5, status=0
,07-21 16:01:41.942 10094 10106 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-21 16:01:41.946  4054  4066 E BtGatt.ContextMap: Context not found for ID 5
,07-21 16:01:41.947  4054  4581 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-21 16:01:41.947  4054  4570 D BtGatt.AdvertiseManager: message : 0
07-21 16:01:41.949  4054  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
,07-21 16:01:41.949  4054  4570 D BtGatt.AdvertiseManager: size of list is =0
,07-21 16:01:41.958  4054  4570 D BtGatt.AdvertiseManager: starting advertising
,07-21 16:01:41.963  4054  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-21 16:01:41.967  4054  4635 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-21 16:01:41.989  4054  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-21 16:01:41.993  4054  4570 D BtGatt.AdvertiseManager: starting multi advertising
,07-21 16:01:42.006  4054  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-21 16:01:42.006  4054  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-21 16:01:42.007  4054  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-21 16:01:42.007  4054  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-21 16:01:42.007  4054  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-21 16:01:42.008 10094 10105 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-21 16:01:42.010 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.011 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.012 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-21 16:01:42.013 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.014 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.015 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.017 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.018 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.019 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.020 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-21 16:01:42.021 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.021 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-21 16:01:42.022 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-21 16:01:42.023 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-21 16:01:42.023 10094 10157 I io.jxcore.node.ConnectionHelper: start: OK
07-21 16:01:42.024 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.025 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-21 16:01:42.025 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-21 16:01:42.026 10094 10170 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-21 16:01:42.026 10094 10157 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-21 16:01:42.026 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.027 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-21 16:01:42.027 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-21 16:01:42.027 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-21 16:01:42.027 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.027 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-21 16:01:42.027 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,07-21 16:01:42.028 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-21 16:01:42.028 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-21 16:01:42.028 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-21 16:01:42.028 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-21 16:01:42.029 10094 10166 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-21 16:01:42.029 10094 10166 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-21 16:01:42.029 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-21 16:01:42.029 10094 10166 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-21 16:01:42.029 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-21 16:01:42.029 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.030 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.030 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-21 16:01:42.030 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-21 16:01:42.030 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-21 16:01:42.030 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-21 16:01:42.031 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.032 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.032 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-21 16:01:42.033 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.034 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.035 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.037 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.040 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.042 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.042 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-21 16:01:42.044 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.045 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:42.045 10094 10157 D BluetoothLeScanner: could not find callback wrapper
,07-21 16:01:42.045 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-21 16:01:42.046 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.047 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.047 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.047 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-21 16:01:42.048 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.050 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.052 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:42.052 10094 10157 D BluetoothLeAdvertiser: stop advertising
,07-21 16:01:42.053  4054  4825 E BtGatt.ContextMap: Context not found for ID 5
07-21 16:01:42.054  4054  4570 D BtGatt.AdvertiseManager: message : 1
07-21 16:01:42.054  4054  4581 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-21 16:01:42.055  4054  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-21 16:01:42.055  4054  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
07-21 16:01:42.057  4054  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-21 16:01:42.063  4054  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-21 16:01:42.063  4054  4176 D BtGatt.GattService: Client app is not null!
,07-21 16:01:42.064 10094 10106 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-21 16:01:42.065  4054  4066 D BtGatt.GattService: unregisterClient() - clientIf=5
07-21 16:01:42.067 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-21 16:01:42.068 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.068 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-21 16:01:42.068 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.069 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.070 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.070 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-21 16:01:42.070 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-21 16:01:42.071 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-21 16:01:42.072 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.075 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.076 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-21 16:01:42.076 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.077 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.077 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-21 16:01:42.078 10094 10094 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-21 16:01:42.078 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-21 16:01:42.078 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-21 16:01:42.078 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:01:42.079 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:01:42.079 10094 10171 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-21 16:01:42.080 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-21 16:01:42.080 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.081 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-21 16:01:42.081 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-21 16:01:42.081 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.082 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.083 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.083 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
07-21 16:01:42.083 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-21 16:01:42.084 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-21 16:01:42.084 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@773bc85 added. We now have 3 listener(s)
07-21 16:01:42.084 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@773bc85 added. We now have 5 listener(s)
07-21 16:01:42.084 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-21 16:01:42.088 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:42.088 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-21 16:01:42.088 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:42.089 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-21 16:01:42.090 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395fada added. We now have 6 listener(s)
07-21 16:01:42.090 10094 10157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-21 16:01:42.091 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-21 16:01:42.096 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:01:42.107 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:42.112 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-21 16:01:42.112 10094 10157 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-21 16:01:42.118 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:42.124 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:42.129 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:42.135 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:42.142 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:42.145 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-21 16:01:42.146 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-21 16:01:42.146 10094 10157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-21 16:01:42.146 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-21 16:01:42.146 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-21 16:01:42.146 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-21 16:01:42.146 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@773bc85 removed from the list
07-21 16:01:42.146 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@773bc85 removed from the list
07-21 16:01:42.146 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-21 16:01:42.147 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395fada removed from the list
07-21 16:01:42.147 10094 10157 D io.jxcore.node.ConnectivityMonitor: stop
07-21 16:01:42.147 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-21 16:01:42.150 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
07-21 16:01:42.150 10094 10157 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,07-21 16:01:42.152 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,07-21 16:01:42.153 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,07-21 16:01:42.155 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,07-21 16:01:42.156 10094 10157 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-21 16:01:42.157 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
07-21 16:01:42.158 10094 10157 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,07-21 16:01:42.160 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
07-21 16:01:42.160 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-21 16:01:42.160 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-21 16:01:42.161 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-21 16:01:42.161 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-21 16:01:42.161 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-21 16:01:42.161 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-21 16:01:42.161 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-21 16:01:42.162 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-21 16:01:42.162 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-21 16:01:42.163 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,07-21 16:01:42.164 10094 10157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-21 16:01:42.164 10094 10157 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-21 16:01:42.164 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,07-21 16:01:42.171 10094 10157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-21 16:01:42.172 10094 10157 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-21 16:01:42.172 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-21 16:01:42.172 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
07-21 16:01:42.172 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-21 16:01:42.172 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
07-21 16:01:42.172 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-21 16:01:42.172 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-21 16:01:42.173 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
07-21 16:01:42.173 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-21 16:01:42.174 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnect,ions: Peer: [37:2710:2710:2710:2710:2710]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-21 16:01:42.175 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-21 16:01:42.175 10094 10157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-21 16:01:42.175 10094 10157 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-21 16:01:42.176 10094 10157 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-21 16:01:42.178 10094 10157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-21 16:01:42.178 10094 10157 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-21 16:01:42.178 10094 10157 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-21 16:01:42.179 10094 10157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-21 16:01:42.179 10094 10157 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-21 16:01:42.179 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,07-21 16:01:42.190 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,07-21 16:01:42.191 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
07-21 16:01:42.191 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,07-21 16:01:42.192 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,07-21 16:01:42.192 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-21 16:01:42.193 10094 10157 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-21 16:01:42.193 10094 10157 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-21 16:01:42.193 10094 10157 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,07-21 16:01:42.193 10094 10172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 199)
07-21 16:01:42.193 10094 10172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
07-21 16:01:42.193 10094 10172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
07-21 16:01:42.194 10094 10172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
07-21 16:01:42.195 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
07-21 16:01:42.195 10094 10157 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-21 16:01:42.197 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
07-21 16:01:42.197 10094 10157 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-21 16:01:42.200 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
07-21 16:01:42.200 10094 10157 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-21 16:01:42.200 10094 10157 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-21 16:01:42.200 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-21 16:01:42.201 10094 10157 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-21 16:01:42.201 10094 10157 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-21 16:01:42.201 10094 10157 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-21 16:01:42.201 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-21 16:01:42.201 10094 10172 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
07-21 16:01:42.201 10094 10157 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-21 16:01:42.201 10094 10172 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
07-21 16:01:42.201 10094 10157 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-21 16:01:42.202 10094 10157 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-21 16:01:42.202 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-21 16:01:42.202 10094 10157 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-21 16:01:42.203 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
07-21 16:01:42.204 10094 10157 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-21 16:01:42.204 10094 10157 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-21 16:01:42.204 10094 10157 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
07-21 16:01:42.204 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
07-21 16:01:42.204 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:01:42.210 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:42.210 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:42.210 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.210 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:01:42.211 10094 10172 D BluetoothSocket: connect(): myUserId = 0
07-21 16:01:42.211 10094 10172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-21 16:01:42.212 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-21 16:01:42.212 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:42.213 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.213 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-21 16:01:42.213 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-21 16:01:42.213 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-21 16:01:42.213 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-21 16:01:42.215 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-21 16:01:42.216 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-21 16:01:42.216 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-21 16:01:42.216 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,07-21 16:01:42.216 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-21 16:01:42.216 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-21 16:01:42.216 10094 10173 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-21 16:01:42.216 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:01:42.216 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-21 16:01:42.216 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-21 16:01:42.219 10094 10173 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:01:42.219 10094 10173 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-21 16:01:42.223 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-21 16:01:42.223 10094 10157 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-21 16:01:42.223 10094 10173 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-21 16:01:42.223 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-21 16:01:42.223 10094 10173 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@b89c01, port: 6, type: 1, local socket address: null, socket type: 0
,07-21 16:01:42.225  3675  3720 D SecContentProvider: insert(), uri = 2
,07-21 16:01:42.226  3675  3720 D SecContentProvider: called from android.uid.bluetooth:1002
07-21 16:01:42.226 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.227  4054  4635 W bt_btif : bta_dm_bl_change_cback : reason=0
07-21 16:01:42.228  4054  4176 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,07-21 16:01:42.230 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:42.231 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.234 10094 10157 D BluetoothAdapter: isSecureModeEnabled
,07-21 16:01:42.235  4054  4825 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:42.235 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.235 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-21 16:01:42.237 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.238 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:42.238 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-21 16:01:42.238 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-21 16:01:42.238 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,07-21 16:01:42.241 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.244 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.245 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.245 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-21 16:01:42.245 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-21 16:01:42.245 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "a4d24f35-892b-461f-a6f3-a89e39f3eaf7", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-21 16:01:42.245 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
07-21 16:01:42.245 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:42.245 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:42.246 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.246 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.246 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-21 16:01:42.246 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:01:42.246 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.246 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.247 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.248 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.249 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:42.250 10094 10157 D BluetoothAdapter: isSecureModeEnabled
,07-21 16:01:42.250  4054  4066 D BtConfig.SecureMode: isSecureModeOn:false
,07-21 16:01:42.251 10094 10157 D BluetoothLeAdvertiser: start advertising
,07-21 16:01:42.252 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.255  4054  4066 D BtGatt.GattService: registerClient() - UUID=ce5e927b-ec7e-4e86-b088-96a7c1351354
,07-21 16:01:42.358  4054  4176 D BtGatt.GattService: onClientRegistered() - UUID=ce5e927b-ec7e-4e86-b088-96a7c1351354, clientIf=5, status=0
,07-21 16:01:42.360 10094 10105 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-21 16:01:42.364  4054  4065 E BtGatt.ContextMap: Context not found for ID 5
,07-21 16:01:42.365  4054  4581 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-21 16:01:42.366  4054  4570 D BtGatt.AdvertiseManager: message : 0
,07-21 16:01:42.369  4054  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-21 16:01:42.369  4054  4570 D BtGatt.AdvertiseManager: size of list is =0
,07-21 16:01:42.378  4054  4570 D BtGatt.AdvertiseManager: starting advertising
,07-21 16:01:42.383  4054  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-21 16:01:42.386  4054  4635 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-21 16:01:42.408  4054  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-21 16:01:42.413  4054  4570 D BtGatt.AdvertiseManager: starting multi advertising
,07-21 16:01:42.425  4054  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-21 16:01:42.426  4054  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,07-21 16:01:42.426  4054  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-21 16:01:42.426  4054  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-21 16:01:42.426  4054  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-21 16:01:42.427 10094 10106 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-21 16:01:42.434 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.435 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.435 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-21 16:01:42.436 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.438 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.438 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.440 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.441 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.441 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-21 16:01:42.442  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:42.442  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:01:42.448 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-21 16:01:42.449 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.450 10094 10157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-21 16:01:42.454 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.454 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.455 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.455 10094 10157 I io.jxcore.node.ConnectionHelper: start: OK
07-21 16:01:42.455 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-21 16:01:42.457 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-21 16:01:42.457 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,07-21 16:01:42.457 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-21 16:01:42.458 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.459 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-21 16:01:42.460 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-21 16:01:42.460 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-21 16:01:42.461 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,07-21 16:01:42.461 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-21 16:01:42.462 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.462 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-21 16:01:42.463 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.463 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.464 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-21 16:01:42.470 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.470 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-21 16:01:42.471 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-21 16:01:42.472 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-21 16:01:42.472 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-21 16:01:42.960 10094 10164 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-21 16:01:42.961 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-21 16:01:42.961 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-21 16:01:42.961 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-21 16:01:42.961 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,07-21 16:01:42.962 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-21 16:01:42.962 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-21 16:01:42.962 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-21 16:01:42.962 10094 10173 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-21 16:01:42.962 10094 10173 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-21 16:01:42.962 10094 10173 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-21 16:01:42.962 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-21 16:01:42.963 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-21 16:01:42.963 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-21 16:01:42.963 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-21 16:01:42.964 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-21 16:01:42.965 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7e051b removed from the list
07-21 16:01:42.966 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7e051b removed from the list
07-21 16:01:42.966 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-21 16:01:42.966 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-21 16:01:42.966 10094 10175 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 199
,07-21 16:01:42.967 10094 10175 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
07-21 16:01:42.967 10094 10175 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 199)
07-21 16:01:42.967  4054  4749 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
07-21 16:01:42.969 10094 10175 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 199)
07-21 16:01:42.967 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.971 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-21 16:01:42.971 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-21 16:01:42.972 10094 10172 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
07-21 16:01:42.972 10094 10172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
,07-21 16:01:42.972 10094 10172 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 199)
07-21 16:01:42.972 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.973 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.973 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.974 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.976 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.977 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:42.978 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-21 16:01:42.980 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.981 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:42.982 10094 10157 D BluetoothLeScanner: could not find callback wrapper
07-21 16:01:42.982 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-21 16:01:42.982 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.983 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.983 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:42.984 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-21 16:01:42.984 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:42.986 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:42.987 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:42.987 10094 10157 D BluetoothLeAdvertiser: stop advertising
,07-21 16:01:42.988  4054  4568 E BtGatt.ContextMap: Context not found for ID 5
,07-21 16:01:42.989  4054  4581 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-21 16:01:42.989  4054  4570 D BtGatt.AdvertiseManager: message : 1
,07-21 16:01:42.990  4054  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-21 16:01:42.990  4054  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-21 16:01:42.992  4054  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-21 16:01:42.998  4054  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-21 16:01:42.998  4054  4176 D BtGatt.GattService: Client app is not null!
,07-21 16:01:42.998 10094 10105 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
07-21 16:01:43.000  4054  4825 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-21 16:01:43.001 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-21 16:01:43.002 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:43.002 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-21 16:01:43.003 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:43.003 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:43.004 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:43.004 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-21 16:01:43.004 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-21 16:01:43.006 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-21 16:01:43.006 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:43.009 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:43.009 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-21 16:01:43.010 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:43.010 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:43.011 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1896b8 removed from the list
07-21 16:01:43.011 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:01:43.011 10094 10157 D io.jxcore.node.ConnectivityMonitor: stop
07-21 16:01:43.011 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-21 16:01:43.011 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-21 16:01:43.011 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-21 16:01:43.012 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,07-21 16:01:43.012 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:01:43.012 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-21 16:01:43.012 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,07-21 16:01:43.013 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:01:43.013 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-21 16:01:43.014 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-21 16:01:43.014 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-21 16:01:43.516 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-21 16:01:44.342  4645  4645 D io_stats: !@   8,0 r 25893 2298332 w 4788 200536 d 625 73608 f 1937 1937 iot 11330 10729 th 482764 0 0 pt 0 inp 0 0 202.122
,07-21 16:01:44.819  3675  5817 D SSRM:f  : SIOP:: AP = 270, PST = 270 (W:14), CP = 226, CUR = -24, LCD = 57
,07-21 16:01:45.462  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:45.462  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -43
,07-21 16:01:45.721  4268  4268 I wpa_supplicant: WPA: Group rekeying completed with F4.E6.C2 [GTK=CCMP]
,07-21 16:01:45.725  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:01:45.738  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:01:45.753 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:45.765 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:45.822  4268  4268 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-21 16:01:48.014 10094 10165 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,07-21 16:01:48.018 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,07-21 16:01:48.022 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-21 16:01:48.022 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-21 16:01:48.025 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-21 16:01:48.028 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-21 16:01:48.028 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-21 16:01:48.028 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-21 16:01:48.028 10094 10176 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-21 16:01:48.029 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-21 16:01:48.029 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-21 16:01:48.029 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-21 16:01:48.034 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,07-21 16:01:48.034 10094 10176 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:01:48.034 10094 10176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:01:48.035 10094 10157 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
07-21 16:01:48.036 10094 10157 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-21 16:01:48.037 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-21 16:01:48.037 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-21 16:01:48.041 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,07-21 16:01:48.048 10094 10176 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-21 16:01:48.048 10094 10176 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@80eace7, port: 6, type: 1, local socket address: null, socket type: 0
,07-21 16:01:48.061 10094 10157 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,07-21 16:01:48.063 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-21 16:01:48.063 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-21 16:01:48.063 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-21 16:01:48.063 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-21 16:01:48.064 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-21 16:01:48.064 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-21 16:01:48.064 10094 10176 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,07-21 16:01:48.064 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-21 16:01:48.064 10094 10176 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-21 16:01:48.065 10094 10176 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-21 16:01:48.065 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-21 16:01:48.065 10094 10157 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7e051b not in the list
07-21 16:01:48.065 10094 10157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7e051b not in the list
07-21 16:01:48.065 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-21 16:01:48.065 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-21 16:01:48.065 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-21 16:01:48.066 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-21 16:01:48.066 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:48.067 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-21 16:01:48.067 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-21 16:01:48.067 10094 10157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-21 16:01:48.068 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-21 16:01:48.068 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:48.074 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:48.075 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-21 16:01:48.076 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:01:48.076 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:01:48.077 10094 10157 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1896b8 not in the list
07-21 16:01:48.077 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:01:48.077 10094 10157 D io.jxcore.node.ConnectivityMonitor: stop
07-21 16:01:48.077 10094 10157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-21 16:01:48.077 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:01:48.077 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-21 16:01:48.078 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-21 16:01:48.082 10094 10157 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,07-21 16:01:48.084 10094 10157 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-21 16:01:48.084 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-21 16:01:48.085 10094 10157 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-21 16:01:48.085 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-21 16:01:48.085 10094 10157 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-21 16:01:48.086 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-21 16:01:48.089 10094 10157 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,07-21 16:01:48.093 10094 10157 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,07-21 16:01:48.096 10094 10157 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,07-21 16:01:48.098 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,07-21 16:01:48.099 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
07-21 16:01:48.102 10094 10157 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,07-21 16:01:48.103 10094 10157 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-21 16:01:48.103 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-21 16:01:48.104 10094 10157 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-21 16:01:48.104 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-21 16:01:48.104 10094 10157 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,07-21 16:01:48.104 10094 10157 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-21 16:01:48.106 10094 10157 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
07-21 16:01:48.107 10094 10157 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-21 16:01:48.108 10094 10157 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-21 16:01:48.110 10094 10157 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,07-21 16:01:48.111 10094 10157 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-21 16:01:48.111 10094 10157 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-21 16:01:48.111 10094 10157 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-21 16:01:48.112 10094 10157 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-21 16:01:48.114 10094 10157 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,07-21 16:01:48.116 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-21 16:01:48.116 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8983094 added. We now have 2 listener(s)
,07-21 16:01:48.116 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8983094 added. We now have 3 listener(s)
07-21 16:01:48.116 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-21 16:01:48.120 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-21 16:01:48.121 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-21 16:01:48.121 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-21 16:01:48.121 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-21 16:01:48.122 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e11f73d added. We now have 4 listener(s)
07-21 16:01:48.122 10094 10157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-21 16:01:48.123 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-21 16:01:48.127 10094 10157 D BluetoothAdapter: enable()
,07-21 16:01:48.133  4054  4825 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-21 16:01:48.133  4054  4825 D AdapterProvider: query
,07-21 16:01:48.142  4054  4825 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@2184c6f
07-21 16:01:48.143  4054  4825 D BluetoothAdapterService: updateEvent - already set, update
07-21 16:01:48.144  4054  4825 W BluetoothAdapterService: updateEvent - alreadySet is true
07-21 16:01:48.144  4054  4825 D AdapterProvider: update
,07-21 16:01:48.148  4054  4825 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:48.150 10094 10157 D BluetoothAdapter: enable(): BT is already enabled..!
,07-21 16:01:48.157  3675  3720 D WifiService: setWifiEnabled: true pid=10094, uid=10033
07-21 16:01:48.158  3675  3720 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-21 16:01:48.158  3675  3720 D WifiControlHistoryProvider: query
,07-21 16:01:48.168  3675  3720 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-21 16:01:48.168  3675  3720 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:48.169  3675  3720 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-21 16:01:48.172  3675  3720 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-21 16:01:48.172  3675  3720 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-21 16:01:48.178 10094 10157 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,07-21 16:01:48.183 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:01:48.188 10094 10157 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,07-21 16:01:48.190 10094 10157 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,07-21 16:01:48.191 10094 10157 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,07-21 16:01:48.198 10094 10177 D BluetoothAdapter: disable()
,07-21 16:01:48.202 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:01:48.202  4054  4066 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : false
07-21 16:01:48.202  4054  4066 D AdapterProvider: query
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:48.205 10094 10157 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-21 16:01:48.209  4054  4066 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@c86b65a
07-21 16:01:48.211  4054  4066 D BluetoothAdapterService: updateEvent - already set, update
07-21 16:01:48.211  4054  4066 W BluetoothAdapterService: updateEvent - alreadySet is true
07-21 16:01:48.211  4054  4066 D AdapterProvider: update
,07-21 16:01:48.215  4054  4066 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:48.219  3675  3785 D SecContentProvider: insert(), uri = 2
,07-21 16:01:48.220  3675  3785 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:48.221  4054  4169 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,07-21 16:01:48.223  4054  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-21 16:01:48.223  4054  4169 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-21 16:01:48.226  4054  4054 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-21 16:01:48.226  4054  4169 D BluetoothAdapterService: Autoconnection is available 
07-21 16:01:48.226  4054  4169 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-21 16:01:48.226  3675  3785 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
07-21 16:01:48.226  4054  4169 D BluetoothAdapterService: terminating service from this receiver
,07-21 16:01:48.231  4054  4169 W bt_btif : btif_dm_cancel_discovery
,07-21 16:01:48.233  3675  3927 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-21 16:01:48.235  3675  3927 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:48.239  3675  4177 D SecContentProvider: insert(), uri = 2
07-21 16:01:48.240  4068  4068 D BluetoothPbap: Proxy object disconnected
07-21 16:01:48.240  4068  4068 D PbapServerProfile: Bluetooth service disconnected
,07-21 16:01:48.243  3675  4177 D SecContentProvider: called from android.uid.bluetooth:1002
07-21 16:01:48.244  3675  3939 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{795c366: PendingIntentRecord{33176a7 com.google.android.gms broadcastIntent}}
,07-21 16:01:48.246  4054  4169 I BluetoothAdapterState: Entering PendingCommandState
,07-21 16:01:48.252  4268  4268 I wpa_supplicant: WPA: Group rekeying completed with F4.E6.C2 [GTK=CCMP]
07-21 16:01:48.254  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:01:48.256  4068  4289 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:48.257  4068  4289 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
07-21 16:01:48.259  3675  3675 D BluetoothPhoneService: Bluetooth Adapter state : 13
,07-21 16:01:48.265  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-21 16:01:48.265  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:48.265  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-21 16:01:48.274  4268  4268 I wpa_supplicant: WPA: Group rekeying completed with F4.E6.C2 [GTK=CCMP]
,07-21 16:01:48.276  3675  3758 D MountService: getExternalStorageMountMode : 1
07-21 16:01:48.276  3675  3758 D MountService: getExternalStorageMountMode : 3
07-21 16:01:48.276  3675  3758 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.android.settings
,07-21 16:01:48.290 10094 10094 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:48.290 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-21 16:01:48.292 10094 10094 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-21 16:01:48.292 10094 10094 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-21 16:01:48.303 10179 10179 E Zygote  : v2
07-21 16:01:48.303 10179 10179 I libpersona: KNOX_SDCARD checking this for 1000
07-21 16:01:48.303 10179 10179 I libpersona: KNOX_SDCARD not a persona
07-21 16:01:48.303  3675  3758 I ActivityManager: Start proc 10179:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-21 16:01:48.304 10179 10179 E Zygote  : accessInfo : 0
07-21 16:01:48.305  4054  4176 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,07-21 16:01:48.308  4054  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
07-21 16:01:48.308  3675  3988 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{a609754: PendingIntentRecord{83436fd com.google.android.gms broadcastIntent}}
07-21 16:01:48.311  3675  4942 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4054 / op:PendingIntent{baaaff2: PendingIntentRecord{74d643 com.android.bluetooth broadcastIntent}}
07-21 16:01:48.313 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:48.313  4054  4169 E BluetoothServiceJni: disableBrEdrNative:
07-21 16:01:48.313  4054  4169 E bt_btif : disable_bredr
07-21 16:01:48.314  4054  4750 W bt_osi_thread: run_thread: thread id 4750, thread name btif_sock exited
07-21 16:01:48.314  4054  4176 W bt_btif : btif_dm_generic_evt: event=33035
07-21 16:01:48.314 10179 10179 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:48.316  4054  4171 E bt_btif : SOCK_LIST: fre]: id 56) - NO app_fd!
07-21 16:01:48.316  4054  4171 E bt_btif : BTA_DisableBluetoothOnly
07-21 16:01:48.316  4054  5000 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-21 16:01:48.316  4054  5000 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-21 16:01:48.317  4054  5001 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-21 16:01:48.317  4054  5001 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-21 16:01:48.317 10179 10179 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.settings 
07-21 16:01:48.317  4054  4635 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-21 16:01:48.318  4054  5679 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-21 16:01:48.319  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-21 16:01:48.328  4054  4176 W bt_btif : btif_dm_generic_evt: event=33035
07-21 16:01:48.332  3675  3720 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-21 16:01:48.333  3675  3720 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-21 16:01:48.333  3675  3720 D BatteryService: online:4, current avg:-17, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-21 16:01:48.333  4054  4635 W bt_btm  : btm_sec_connected
07-21 16:01:48.333  4054  4635 W bt_btif : bta_dm_bl_change_cback : reason=2
07-21 16:01:48.333  4054  4635 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
07-21 16:01:48.334  4054  4635 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
07-21 16:01:48.334  4054  4635 W bt_btif : bta_dm_bl_change_cback : reason=2
,07-21 16:01:48.334  3675  3675 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-21 16:01:48.336  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-21 16:01:48.341  4054  4176 W bt_btif : btif_dm_generic_evt: event=33035
,07-21 16:01:48.341 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:48.344 10179 10179 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:48.344 10179 10179 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:48.348 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:48.348  3675  3675 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-21 16:01:48.348  3675  3675 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-21 16:01:48.350  3675  3675 D GameManagerService: new battery level: 100
,07-21 16:01:48.352  4268  4268 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-21 16:01:48.356  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-21 16:01:48.356  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-21 16:01:48.362  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-21 16:01:48.364  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:01:48.365  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:01:48.367  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-21 16:01:48.371  4054  4054 D DOWNLOADABLE_DB: onReceive of BR
07-21 16:01:48.371  4054  4054 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-21 16:01:48.371  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.371  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.372  4054  4054 D DOWNLOADABLE_DB: onReceive of BR
07-21 16:01:48.372  4054  4054 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-21 16:01:48.372  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.372  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.372  4054  4054 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:48.373  4054  4054 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-21 16:01:48.373  4054  4717 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-21 16:01:48.373  4054  4717 D BluetoothSdpJni: SDP Remove record success - handle: 0
07-21 16:01:48.373  4054  4717 D BluetoothMapMasInstance: RemoveSDPrecord returns true
07-21 16:01:48.373  4054  4717 D ObexServerSockets: shutdown(block = true)
07-21 16:01:48.373  4054  4717 D ObexServerSockets: shutdown called from another thread - interrupt().
07-21 16:01:48.373  4054  4717 D ObexServerSockets: shutdown called from another thread - interrupt().
07-21 16:01:48.375  4268  4268 I wpa_supplicant: Interworking: Fetch ANQP after connect
07-21 16:01:48.379  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:01:48.380  4054  4054 D BluetoothSdpJni: SDP Remove record success - handle: 1
07-21 16:01:48.380  4054  4054 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-21 16:01:48.380  4054  4176 W bt_btif : btif_dm_generic_evt: event=33035
07-21 16:01:48.383  3675  3939 I ActivityManager: DSS on for com.android.settings and scale is 1.0
,07-21 16:01:48.384  4054  4688 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-21 16:01:48.386  4054  4054 I BtOppRfcommListener: stopping Accept Thread
07-21 16:01:48.387 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:48.388  4054  5679 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-21 16:01:48.392  4054  4176 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
07-21 16:01:48.392  4054  4176 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
,07-21 16:01:48.398  4054  4054 V BluetoothOppManager: cleanUp...
07-21 16:01:48.399  4054  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
,07-21 16:01:48.402  4054  4176 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 1
,07-21 16:01:48.403 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:48.404  4054  4176 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-21 16:01:48.404  4054  4176 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 241
,07-21 16:01:48.406  4068  4289 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,07-21 16:01:48.419  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-21 16:01:48.424 10179 10179 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
,07-21 16:01:48.425  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-21 16:01:48.425  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-21 16:01:48.454 10179 10179 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:48.472  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:48.472  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,07-21 16:01:48.495 10179 10179 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.samsung.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
,07-21 16:01:48.496 10179 10179 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
07-21 16:01:48.496 10179 10179 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.samsung.android.settings.wifi.mobileap.WifiApBackupRestore
07-21 16:01:48.497 10179 10179 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
07-21 16:01:48.497 10179 10179 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.samsung.android.settings.wifi.WifiBackupRestore
,07-21 16:01:48.497 10179 10179 I QBNRClientHelper: init SyncClientHelper : WiFi
,07-21 16:01:48.516 10179 10179 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-21 16:01:48.524 10179 10179 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
07-21 16:01:48.525  4054  4176 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_BT_EVT
07-21 16:01:48.525  4054  4176 E BluetoothAdapterState: stateChangeCallback : 16
07-21 16:01:48.525  4054  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,07-21 16:01:48.529 10179 10179 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-21 16:01:48.530 10179 10179 D BluetoothEventManager: BluetoothEventManager Constructor :: 
07-21 16:01:48.530  4054  4169 D BtConfig.SecureMode: isSecureModeOn:false
,07-21 16:01:48.530  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-21 16:01:48.536  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-21 16:01:48.537  4054  4054 D HeadsetService: Received stop request...Stopping profile...
07-21 16:01:48.537 10179 10179 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
,07-21 16:01:48.538 10179 10179 D LocalBluetoothProfileManager: PANU : true
,07-21 16:01:48.540  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.540  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-21 16:01:48.540  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
07-21 16:01:48.540  4054  4054 D HeadsetService: notifyProfileServiceStateChanged
,07-21 16:01:48.544  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-21 16:01:48.545  4054  4054 D A2dpService: Received stop request...Stopping profile...
,07-21 16:01:48.545  4068  4068 D HeadsetProfile: Bluetooth service disconnected
07-21 16:01:48.546  3675  3675 W BluetoothHeadset: Proxy not attached to service
07-21 16:01:48.546  3675  3675 I Telecom : SecBluetoothManager : not single connected gear
07-21 16:01:48.546  3675  3675 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-21 16:01:48.546  3675  3675 D BluetoothHeadset: unRegisterMessageListener : 11
07-21 16:01:48.546  3675  3675 W BluetoothHeadset: Proxy not attached to service
07-21 16:01:48.546  3675  3675 I Telecom : SecBluetoothManager : unregister MessageListener
07-21 16:01:48.547  3675  4565 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
07-21 16:01:48.547  3675  4565 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
07-21 16:01:48.548  3675  4565 I Telecom : SecBluetoothManager : mBluetoothHeadset is null
07-21 16:01:48.548  3675  4565 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
,07-21 16:01:48.548  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-21 16:01:48.549  4054  4709 D A2dpStateMachine: Exit Disconnected: -1
07-21 16:01:48.550  4054  4054 D Avrcp   : unregisterContentObserver
07-21 16:01:48.551 10179 10179 D BluetoothSap: Create BluetoothSap proxy object
07-21 16:01:48.551  4054  4054 D Avrcp   : removeOnActiveSessionsChangedListener
07-21 16:01:48.552  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-21 16:01:48.553  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.553  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
07-21 16:01:48.554  4054  4054 D A2dpService: notifyProfileServiceStateChanged
,07-21 16:01:48.556  4068  4068 D A2dpProfile: Bluetooth service disconnected
,07-21 16:01:48.556  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:48.557  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
07-21 16:01:48.557  4054  4054 V BluetoothAdapterState: isTurningOff()=true
07-21 16:01:48.557  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:48.557  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:48.557  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:48.557 10179 10179 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-21 16:01:48.557  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.558 10179 10179 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
07-21 16:01:48.558  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-21 16:01:48.561  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-21 16:01:48.561  4054  4169 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-21 16:01:48.562  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
07-21 16:01:48.562  4054  4169 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
,07-21 16:01:48.562  4054  4169 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-21 16:01:48.565  4054  4054 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-21 16:01:48.565  4054  4054 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-21 16:01:48.568  4054  4054 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
,07-21 16:01:48.570 10179 10179 D DockEventReceiver: finishStartingService: stopping service
07-21 16:01:48.570  4054  4054 D HidService: Received stop request...Stopping profile...
07-21 16:01:48.570  4054  4054 D HidService: Stopping Bluetooth HidService
07-21 16:01:48.570  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.570  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
07-21 16:01:48.570  4054  4054 D HidService: notifyProfileServiceStateChanged
,07-21 16:01:48.572  4068  4068 D BluetoothInputDevice: Proxy object disconnected
,07-21 16:01:48.572  4068  4068 D HidProfile: Bluetooth service disconnected
07-21 16:01:48.574  4054  4054 D HealthService: Received stop request...Stopping profile...
,07-21 16:01:48.575  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.575  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
07-21 16:01:48.575  4054  4054 D HealthService: notifyProfileServiceStateChanged
,07-21 16:01:48.578  4054  4054 D PanService: Received stop request...Stopping profile...
,07-21 16:01:48.578 10179 10179 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:48.578 10179 10179 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
07-21 16:01:48.579 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
07-21 16:01:48.579 10179 10179 D BluetoothPan: BluetoothPAN Proxy object connected
07-21 16:01:48.580 10179 10179 D PanProfile: Bluetooth service connected
,07-21 16:01:48.582 10179 10179 D BluetoothSap: Proxy object connected
,07-21 16:01:48.582 10179 10179 D SapProfile: Bluetooth service connected
,07-21 16:01:48.590  3675  4941 I ActivityManager: KPU : put [com.google.android.partnersetup] : 26972 K
07-21 16:01:48.590  3675  4941 I ActivityManager: Killing 9317:com.google.android.partnersetup/u0a23 (adj 906): DHA:empty #33
,07-21 16:01:48.592  4054  4054 D EnhancedTetheringManager: stop
,07-21 16:01:48.598  4054  4054 D EnhancedTetheringManager: tetherEnabled : false
07-21 16:01:48.598  4054  4054 D ETMLeHelper: stopAdvertise
07-21 16:01:48.599  4054  4054 D BluetoothAdapter: STATE_TURNING_OFF
07-21 16:01:48.600  4054  4054 D BluetoothAdapter: STATE_TURNING_OFF
07-21 16:01:48.600  4054  4054 D BluetoothLeAdvertiser: stop advertising
07-21 16:01:48.600  4054  4054 D BluetoothLeAdvertiser: wrapper is null
07-21 16:01:48.600  4054  4054 D EnhancedTetheringManager: removeNapWakeAlarm
,07-21 16:01:48.610  3675  4179 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4054 / op:PendingIntent{ae7d633: PendingIntentRecord{66bedf0 com.android.bluetooth broadcastIntent}}
,07-21 16:01:48.611  4054  4054 D EnhancedTetheringManager: cancelFindTetherServer
07-21 16:01:48.611  4054  4054 D ETMLeHelper: stopScan
,07-21 16:01:48.612  4054  4054 D BluetoothAdapter: STATE_TURNING_OFF
,07-21 16:01:48.613  4054  4054 D BluetoothAdapter: STATE_TURNING_OFF
,07-21 16:01:48.613  4054  4054 D BluetoothLeScanner: could not find callback wrapper
07-21 16:01:48.613  4054  4054 D EnhancedTetheringManager: removePanuWakeAlarm
,07-21 16:01:48.628  3675  4931 D ActivityManager: cleanUpApplicationRecord -- 9317
,07-21 16:01:48.631  4768  4781 D ForegroundUtils: could not check pending caller
,07-21 16:01:48.794  3675  4939 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4054 / op:PendingIntent{23fa28f: PendingIntentRecord{239f91c com.android.bluetooth broadcastIntent}}
07-21 16:01:48.795  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
,07-21 16:01:48.795  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
07-21 16:01:48.795  4054  4054 D PanService: notifyProfileServiceStateChanged
,07-21 16:01:48.804  4068  4068 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-21 16:01:48.804  4068  4068 D PanProfile: Bluetooth service disconnected
07-21 16:01:48.806  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:48.806  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
07-21 16:01:48.806  4054  4054 V BluetoothAdapterState: isTurningOff()=true
07-21 16:01:48.806 10094 10177 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-21 16:01:48.807  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:48.807  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:48.807  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:48.807 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-21 16:01:48.810  4054  4054 D BluetoothMapService: Received stop request...Stopping profile...
07-21 16:01:48.812 10094 10177 D BluetoothAdapter: enable()
07-21 16:01:48.821 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:48.822 10179 10179 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-21 16:01:48.822 10179 10179 D PanProfile: Bluetooth service disconnected
,07-21 16:01:48.838  4054  4825 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-21 16:01:48.839  4054  4825 D AdapterProvider: query
07-21 16:01:48.845  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.845  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
07-21 16:01:48.845  4054  4054 D BluetoothMapService: notifyProfileServiceStateChanged
,07-21 16:01:48.852  4068  4068 D BluetoothMap: Proxy object disconnected
07-21 16:01:48.852  4068  4068 D MapProfile: Bluetooth service disconnected
,07-21 16:01:48.853  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
,07-21 16:01:48.856  4054  4710 W bt_osi_thread: run_thread: thread id 4710, thread name media_worker exited
,07-21 16:01:48.856  4054  4054 D SapService: Received stop request...Stopping profile...
07-21 16:01:48.856  4054  4054 V SapService: stop()
07-21 16:01:48.859  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.859  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
07-21 16:01:48.859  4054  4054 D SapService: notifyProfileServiceStateChanged
07-21 16:01:48.860  4054  4825 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@1e9de26
07-21 16:01:48.861  4068  4068 D BluetoothSap: Proxy object disconnected
07-21 16:01:48.861  4068  4068 D SapProfile: Bluetooth service disconnected
07-21 16:01:48.862  4054  4825 D BluetoothAdapterService: updateEvent - already set, update
07-21 16:01:48.863  4054  4054 D HidDevService: Received stop request...Stopping profile...
07-21 16:01:48.863  4054  4054 D HidDevService: stop()
07-21 16:01:48.863  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.863  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Message sending
07-21 16:01:48.863  4054  4054 D HidDevService: notifyProfileServiceStateChanged
07-21 16:01:48.864  4054  4825 W BluetoothAdapterService: updateEvent - alreadySet is true
07-21 16:01:48.864  4054  4825 D AdapterProvider: update
07-21 16:01:48.867  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:48.867  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
07-21 16:01:48.867  4054  4054 V BluetoothAdapterState: isTurningOff()=true
07-21 16:01:48.867  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:48.868  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:48.868  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:48.868  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.868  4054  4054 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-21 16:01:48.868  4054  4054 W bt_btif : cleanup: HH disabling or disabled already, status = 0
07-21 16:01:48.868  4054  4054 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-21 16:01:48.869  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:48.869  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
07-21 16:01:48.869  4054  4054 V BluetoothAdapterState: isTurningOff()=true
07-21 16:01:48.869  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:48.869  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:48.869  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:48.869  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.869  4054  4054 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-21 16:01:48.870  4054  4054 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-21 16:01:48.871  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:48.871  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
07-21 16:01:48.871  4054  4054 V BluetoothAdapterState: isTurningOff()=true
07-21 16:01:48.871  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:48.871  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:48.871  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
,07-21 16:01:48.871  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
,07-21 16:01:48.872  4054  4054 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-21 16:01:48.872  4054  4054 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-21 16:01:48.874  4054  4825 E BluetoothAdapterService: updateEvent - update success 1
07-21 16:01:48.870 10179 10179 D BluetoothSap: Proxy object disconnected
07-21 16:01:48.875 10179 10179 D SapProfile: Bluetooth service disconnected
,07-21 16:01:48.877  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:48.877  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
07-21 16:01:48.877  4054  4054 V BluetoothAdapterState: isTurningOff()=true
07-21 16:01:48.878  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:48.878  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:48.878  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:48.878  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.878  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:48.879  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
07-21 16:01:48.879  4054  4054 V BluetoothAdapterState: isTurningOff()=true
07-21 16:01:48.879  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:48.879  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:48.879  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:48.879  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.880  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:48.880  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Before synchronized
07-21 16:01:48.880  4054  4054 V BluetoothAdapterState: isTurningOff()=true
07-21 16:01:48.880  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:48.880  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:48.880  4054  4054 V BluetoothAdapterState: isBleTurningOff()=false
,07-21 16:01:48.883  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.883  4054  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
07-21 16:01:48.883  4054  4054 D HidDevService: cleanup()
07-21 16:01:48.883  4054  4054 V BluetoothHidDevServiceJni: cleanupNative enter
07-21 16:01:48.883  4054  4054 I BluetoothHidDevServiceJni: Cleaning up interface
07-21 16:01:48.883  4054  4054 I BluetoothHidDevServiceJni: Cleaning up callback object
07-21 16:01:48.883  4054  4054 V BluetoothHidDevServiceJni: cleanupNative done
,07-21 16:01:48.885  4054  4169 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@92e9892
07-21 16:01:48.886  4054  4169 D BtGatt.GattService: serverDisconnectIncomingConnClients()
07-21 16:01:48.886  4054  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-21 16:01:48.886  3675  3988 W ActivityManager: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-21 16:01:48.886  4054  4169 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-21 16:01:48.887  4054  4635 W bt_btif : BTA got unregistered event id 32
,07-21 16:01:48.889  3675  3988 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-21 16:01:48.889  3675  3988 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-21 16:01:48.889  3675  3988 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-21 16:01:48.889  3675  3988 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-21 16:01:48.889  3675  3988 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-21 16:01:48.889  3675  3988 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-21 16:01:48.889  3675  3988 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-21 16:01:48.889  3675  3988 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-21 16:01:48.889  3675  3988 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-21 16:01:48.889  3675  3988 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-21 16:01:48.891  3675  3988 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-21 16:01:48.891  4054  4169 D BluetoothAdapterService: Autoconnection is available 
07-21 16:01:48.891  4054  4169 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
07-21 16:01:48.891  3675  3988 D SecContentProvider: called from com.thaliproject.thalitest
07-21 16:01:48.893  4054  4054 D DOWNLOADABLE_DB: onReceive of BR
07-21 16:01:48.893  4054  4054 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-21 16:01:48.893  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.893  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.893  4054  4169 I BluetoothAdapterState: Entering BleOnState
,07-21 16:01:48.897  4054  4054 D DOWNLOADABLE_DB: onReceive of BR
07-21 16:01:48.897  4054  4054 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-21 16:01:48.897  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:48.897  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
,07-21 16:01:48.898  3675  3785 D BluetoothAdapter: onBluetoothStateChange: up=false
07-21 16:01:48.898  3675  3785 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-21 16:01:48.899  3675  3785 D BluetoothAdapter: There are no active google scan apps, stop scan
07-21 16:01:48.901  4054  4169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
,07-21 16:01:48.905 10094 10106 D BluetoothAdapter: onBluetoothStateChange: up=false
07-21 16:01:48.905 10094 10106 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-21 16:01:48.906 10094 10106 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
07-21 16:01:48.906 10094 10106 D BluetoothLeAdvertiser: Exit stop advertising
,07-21 16:01:48.907  4735  6873 I BeaconBle: Client requested to stop, listener=hjz@e310bf5
,07-21 16:01:48.915 10094 10106 D BluetoothAdapter: There are no active google scan apps, stop scan
07-21 16:01:48.915 10094 10106 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-21 16:01:48.915 10094 10106 D BluetoothLeScanner: Exiting stopAllScan
07-21 16:01:48.916  4068  4547 D BluetoothMap: onBluetoothStateChange: up=false
07-21 16:01:48.917  4735  6873 I BeaconBle: Scan canceled successfully.
07-21 16:01:48.919 10179 10192 D BluetoothAdapter: onBluetoothStateChange: up=false
07-21 16:01:48.919 10179 10192 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-21 16:01:48.921 10179 10192 D BluetoothAdapter: There are no active google scan apps, stop scan
07-21 16:01:48.921  3675  3927 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{d7b8b08: PendingIntentRecord{226d2a1 com.google.android.gms broadcastIntent}}
07-21 16:01:48.921  4735  4748 D BluetoothAdapter: onBluetoothStateChange: up=false
07-21 16:01:48.921  4735  4748 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-21 16:01:48.922  4735  4748 D BluetoothAdapter: There are no active google scan apps, stop scan
07-21 16:01:48.922  4735  4748 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-21 16:01:48.922  4735  4748 D BluetoothLeScanner: Exiting stopAllScan
07-21 16:01:48.923  4041  4052 D BluetoothAdapter: onBluetoothStateChange: up=false
07-21 16:01:48.923  4041  4052 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-21 16:01:48.924  4041  4052 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-21 16:01:48.930 10179 10191 D BluetoothPan: onBluetoothStateChange on: false
,07-21 16:01:48.931  9495  9507 D BluetoothAdapter: onBluetoothStateChange: up=false
07-21 16:01:48.932  9495  9507 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-21 16:01:48.933  9495  9507 D BluetoothAdapter: There are no active google scan apps, stop scan
07-21 16:01:48.933  4068  4239 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-21 16:01:48.934  4768  4787 D BluetoothAdapter: onBluetoothStateChange: up=false
07-21 16:01:48.934  4768  4787 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-21 16:01:48.936  4768  4787 D BluetoothAdapter: There are no active google scan apps, stop scan
07-21 16:01:48.936  4068  4082 D BluetoothSap: onBluetoothStateChange: up=false
07-21 16:01:48.937  4068  4083 D BluetoothPan: onBluetoothStateChange on: false
,07-21 16:01:48.939  4068  6260 D BluetoothPbap: onBluetoothStateChange: up=false
07-21 16:01:48.941  4068  4239 D BluetoothAdapter: onBluetoothStateChange: up=false
07-21 16:01:48.941  4068  4239 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-21 16:01:48.946  4068  4239 D BluetoothAdapter: There are no active google scan apps, stop scan
07-21 16:01:48.946 10179 10192 D BluetoothSap: onBluetoothStateChange: up=false
,07-21 16:01:48.948  4054  4568 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-21 16:01:48.951  4054  4169 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,07-21 16:01:48.953  3675  3785 W BluetoothManagerService: BT is in BLE_ON State
07-21 16:01:48.953  4054  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-21 16:01:48.953  4054  4169 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-21 16:01:48.954  4054  4169 D BluetoothAdapterService: Autoconnection is available 
07-21 16:01:48.954  4054  4568 E BluetoothBondStateMachine: initStateMachine
07-21 16:01:48.954  4054  4169 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
07-21 16:01:48.955  3675  3785 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
07-21 16:01:48.956  3675  3719 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-21 16:01:48.957  3675  3719 D SecContentProvider: called from android.uid.bluetooth:1002
07-21 16:01:48.959  3675  4544 D SecContentProvider: insert(), uri = 2
07-21 16:01:48.959  3675  3675 D Telecom : SecBluetoothManager : unregister BluetoothHeadset after STATE_OFF : null
07-21 16:01:48.959  3675  3675 D Telecom : SecBluetoothManager : unRegisterBluetoothHeadsetMessageListener fail
,07-21 16:01:48.961  3675  4544 D SecContentProvider: called from android.uid.bluetooth:1002
07-21 16:01:48.963  4054  4171 E bt_btif : btif_vhci_sock_cleanup
07-21 16:01:48.963  4054  4169 I BluetoothAdapterState: Entering PendingCommandState
07-21 16:01:48.967  4054  4635 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-21 16:01:48.967  3675  3675 D BluetoothPhoneService: Bluetooth Adapter state : 10
07-21 16:01:48.967  4054  4171 I bt_core_module: module_shut_down Shutting down module "btif_config_module"
07-21 16:01:48.972  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-21 16:01:48.972  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:48.972  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-21 16:01:48.981 10179 10179 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:48.981 10179 10179 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-21 16:01:48.982  4054  4171 I bt_core_module: module_shut_down Shutdown of module "btif_config_module" completed
07-21 16:01:48.983 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:48.987  4054  4176 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-21 16:01:48.988  4054  4176 W bt_btif : btif_dm_generic_evt: event=33035
07-21 16:01:48.988  4068  4289 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:48.988  3675  4179 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{b3cf7dd: PendingIntentRecord{e690f52 com.google.android.gms broadcastIntent}}
07-21 16:01:48.989  4068  4289 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,07-21 16:01:48.998  4054  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_ON
,07-21 16:01:49.002  4054  4054 D DOWNLOADABLE_DB: onReceive of BR
07-21 16:01:49.002  4054  4054 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
,07-21 16:01:49.002  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
,07-21 16:01:49.002  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
,07-21 16:01:49.008 10179 10179 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-21 16:01:49.008  4054  4054 D DOWNLOADABLE_DB: onReceive of BR
07-21 16:01:49.008  4054  4054 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
,07-21 16:01:49.009  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:49.009  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:49.010 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:49.015  4054  4169 I BluetoothAdapterState: Deferring USER_TURN_ON request...
07-21 16:01:49.017  3675  4931 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{60eb320: PendingIntentRecord{99634d9 com.google.android.gms broadcastIntent}}
,07-21 16:01:49.020  4735  6871 W NearbyMessages: NetworkPollManager:  No operations for client(com.google.android.gms#0p:discoverer). It should not be in the tracker.
07-21 16:01:49.021  4054  4176 W bt_btif : btif_dm_generic_evt: event=33035
07-21 16:01:49.021  4735  6871 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
07-21 16:01:49.022 10179 10179 D DockEventReceiver: finishStartingService: stopping service
,07-21 16:01:49.040  3675  4987 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{1e4ce9e: PendingIntentRecord{1944d7f com.google.android.gms broadcastIntent}}
,07-21 16:01:49.055 10179 10179 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:49.055 10179 10179 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,07-21 16:01:49.056  3675  4931 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{afbe14c: PendingIntentRecord{8ac4595 com.google.android.gms broadcastIntent}}
,07-21 16:01:49.073  4054  4062 E System  : Uncaught exception thrown by finalizer
,07-21 16:01:49.082  4054  4062 E System  : java.io.IOException: socket not created
07-21 16:01:49.082  4054  4062 E System  : 	at android.net.LocalSocketImpl.shutdownInput(LocalSocketImpl.java:404)
07-21 16:01:49.082  4054  4062 E System  : 	at android.net.LocalSocket.shutdownInput(LocalSocket.java:207)
07-21 16:01:49.082  4054  4062 E System  : 	at android.bluetooth.BluetoothSocket.close(BluetoothSocket.java:800)
07-21 16:01:49.082  4054  4062 E System  : 	at android.bluetooth.BluetoothSocket.finalize(BluetoothSocket.java:309)
07-21 16:01:49.082  4054  4062 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:222)
07-21 16:01:49.082  4054  4062 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:209)
07-21 16:01:49.082  4054  4062 E System  : 	at java.lang.Thread.run(Thread.java:762)
07-21 16:01:49.082  4054  4062 E System  : Uncaught exception thrown by finalizer
07-21 16:01:49.083  4054  4062 E System  : java.io.IOException: socket not created
07-21 16:01:49.083  4054  4062 E System  : 	at android.net.LocalSocketImpl.shutdownInput(LocalSocketImpl.java:404)
07-21 16:01:49.083  4054  4062 E System  : 	at android.net.LocalSocket.shutdownInput(LocalSocket.java:207)
07-21 16:01:49.083  4054  4062 E System  : 	at android.bluetooth.BluetoothSocket.close(BluetoothSocket.java:800)
07-21 16:01:49.083  4054  4062 E System  : 	at android.bluetooth.BluetoothSocket.finalize(BluetoothSocket.java:309)
07-21 16:01:49.083  4054  4062 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:222)
07-21 16:01:49.083  4054  4062 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:209)
07-21 16:01:49.083  4054  4062 E System  : 	at java.lang.Thread.run(Thread.java:762)
,07-21 16:01:49.095  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-21 16:01:49.104  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-21 16:01:49.105  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-21 16:01:49.169  4054  4176 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
,07-21 16:01:49.170  4054  4176 I bt_core_module: module_shut_down Shutting down module "hci_module"
07-21 16:01:49.170  4054  4176 I bt_hci  : shut_down
,07-21 16:01:49.289  4054  4583 I bt_vendor: low_power_mode_cb
07-21 16:01:49.291  5251  6667 I Authzen : [PermitStore] Getting all permits...
07-21 16:01:49.295  4054  4583 D bt_hwcfg: hw_epilog_process
,07-21 16:01:49.298  4054  4583 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-21 16:01:49.298  4054  4583 I bt_vendor: epilog_cb
07-21 16:01:49.298  4054  4583 I bt_hci  : epilog_finished_callback
07-21 16:01:49.298  4054  4583 W bt_osi_thread: run_thread: thread id 4583, thread name hci_thread exited
07-21 16:01:49.300  4054  4176 I bt_hci_h4: hal_close
07-21 16:01:49.300  4054  4588 W bt_osi_thread: run_thread: thread id 4588, thread name hci_single_chann exited
07-21 16:01:49.301  4054  4176 I bt_userial_vendor: device fd = 96 close
07-21 16:01:49.302  4054  4176 I bt_upio : upio_set_bluetooth_power(on: 0)
,07-21 16:01:49.310  4054  4176 I bt_core_module: module_shut_down Shutdown of module "hci_module" completed
07-21 16:01:49.310  4054  4176 I bt_core_module: module_shut_down Shutting down module "btsnoop_module"
07-21 16:01:49.310  4054  4176 I bt_core_module: module_shut_down Shutdown of module "btsnoop_module" completed
07-21 16:01:49.311  4054  4176 I bt_core_module: module_clean_up Cleaning up module "bte_logmsg_module"
07-21 16:01:49.311  4054  4176 I bt_core_module: module_clean_up Cleanup of module "bte_logmsg_module" completed
07-21 16:01:49.312  4054  4635 W bt_osi_thread: run_thread: thread id 4635, thread name bt_workqueue exited
,07-21 16:01:49.314  4054  4171 I bt_core_module: module_shut_down Shutting down module "controller_module"
,07-21 16:01:49.314  4054  4171 I bt_core_module: module_shut_down Shutdown of module "controller_module" completed
07-21 16:01:49.315  4054  4176 E BluetoothAdapterState: stateChangeCallback : 0
07-21 16:01:49.315  4054  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,07-21 16:01:49.323  4054  4169 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-21 16:01:49.323  4054  4054 D BtGatt.DebugUtils: handleDebugAction() action=null
07-21 16:01:49.324  4054  4054 D BtGatt.GattService: Received stop request...Stopping profile...
,07-21 16:01:49.325  4054  4054 D BtGatt.GattService: stop()
,07-21 16:01:49.325  4054  4054 D BtGatt.GattService: cleanup binder
07-21 16:01:49.325  4054  4054 D BtGatt.AdvertiseManager: advertise clients cleared
07-21 16:01:49.325  4054  4054 D BtGatt.ScanManager: cleanup
07-21 16:01:49.326  3675  4931 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4054 / op:PendingIntent{8606d77: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:01:49.328  4054  4054 D BtGatt.ScanManager: cleanup handler
,07-21 16:01:49.332  4054  4054 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@139c6cf
07-21 16:01:49.332  4054  4054 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
07-21 16:01:49.332  4054  4054 D BtGatt.GattService: notifyProfileServiceStateChanged
,07-21 16:01:49.334  4054  4054 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:49.334  4054  4054 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
07-21 16:01:49.334  4054  4054 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:49.334  4054  4054 V BluetoothAdapterState: isTurningOn()=false
07-21 16:01:49.334  4054  4054 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:49.334  4054  4054 V BluetoothAdapterState: isBleTurningOff()=true
,07-21 16:01:49.335  4054  4169 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,07-21 16:01:49.337  4054  4169 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-21 16:01:49.337  4054  4169 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-21 16:01:49.338  4054  4169 D BluetoothAdapterService: Autoconnection is available 
07-21 16:01:49.338  3675  3785 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
07-21 16:01:49.338  4054  4169 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
07-21 16:01:49.338  4054  4169 I BluetoothAdapterState: Entering OffState
07-21 16:01:49.341  4054  4169 D BluetoothAdapterState: Current state: OFF, message: USER_TURN_ON
,07-21 16:01:49.346  4645  4645 D io_stats: !@   8,0 r 25941 2302272 w 4837 201416 d 641 73712 f 1956 1956 iot 11410 10770 th 481560 0 0 pt 0 inp 0 0 207.126
,07-21 16:01:49.348  4054  4054 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-21 16:01:49.348  4054  4054 W BluetoothSdpJni: Cleaning up Bluetooth SDP object
07-21 16:01:49.349  4054  4171 E BluetoothServiceJni: Callback env check fail: env: 0x0, callback: 0xe2df8570
07-21 16:01:49.349  4054  4171 E BluetoothServiceJni: Callback: 'callback_thread_event' is not called on the correct thread
07-21 16:01:49.350  4054  4176 W bt_btif : btif_dm_generic_evt: event=33035
07-21 16:01:49.350  4054  4176 E bt_btif_dm: ### ASSERT : system/bt/btif/src/btif_dm.c line 2983 Callback is NULL (0) ###
07-21 16:01:49.350  4054  4176 W bt_osi_thread: run_thread: thread id 4176, thread name bt_jni_workqueue exited
07-21 16:01:49.351  4054  4171 I bt_core_module: module_clean_up Cleaning up module "stack_config_module"
07-21 16:01:49.351  4054  4171 I bt_core_module: module_clean_up Cleanup of module "stack_config_module" completed
07-21 16:01:49.351  4054  4171 I bt_core_module: module_clean_up Cleaning up module "interop_module"
07-21 16:01:49.351  4054  4171 I bt_core_module: module_clean_up Cleanup of module "interop_module" completed
07-21 16:01:49.352  4054  4171 I bt_core_module: module_clean_up Cleaning up module "btif_config_module"
,07-21 16:01:49.355  3675  4543 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{890924d: PendingIntentRecord{6aff102 com.google.android.gms broadcastIntent}}
,07-21 16:01:49.359  4054  4171 I bt_core_module: module_clean_up Cleanup of module "btif_config_module" completed
,07-21 16:01:49.359  4054  4171 I bt_core_module: module_clean_up Cleaning up module "bt_utils_module"
07-21 16:01:49.359  4054  4171 I bt_core_module: module_clean_up Cleanup of module "bt_utils_module" completed
07-21 16:01:49.359  4054  4171 I bt_core_module: module_clean_up Cleaning up module "osi_module"
,07-21 16:01:49.360  4054  4175 D bt_osi_alarm: callback_dispatch Callback thread exited
07-21 16:01:49.360  4054  4175 W bt_osi_thread: run_thread: thread id 4175, thread name alarm_dispatcher exited
07-21 16:01:49.361  4054  4174 W bt_osi_thread: run_thread: thread id 4174, thread name alarm_default_ca exited
07-21 16:01:49.361  4054  4171 I bt_core_module: module_clean_up Cleanup of module "osi_module" completed
07-21 16:01:49.362  4054  4054 I BluetoothServiceJni: cleanupNative: return from cleanup
07-21 16:01:49.362  4054  4054 D DOWNLOADABLE_DB: cleanup
,07-21 16:01:49.369  4054  4054 I art     : System.exit called, status: 0
07-21 16:01:49.369  4054  4054 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-21 16:01:49.392  4735  6871 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-21 16:01:49.394 10094 10177 D BluetoothAdapter: enable()
,07-21 16:01:49.397  3675  4939 I ActivityManager: Process com.android.bluetooth (pid 4054) has died(87,1815)
07-21 16:01:49.398  3675  4939 D ActivityManager: cleanUpApplicationRecord -- 4054
07-21 16:01:49.403  4768  4781 D ForegroundUtils: could not check pending caller
07-21 16:01:49.406  3675  4982 W ActivityManager: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-21 16:01:49.407  3675  4982 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-21 16:01:49.407  3675  4982 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-21 16:01:49.407  3675  4982 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-21 16:01:49.407  3675  4982 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-21 16:01:49.407  3675  4982 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-21 16:01:49.407  3675  4982 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-21 16:01:49.407  3675  4982 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-21 16:01:49.407  3675  4982 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-21 16:01:49.407  3675  4982 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-21 16:01:49.408  3675  4982 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-21 16:01:49.410  3675  4982 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-21 16:01:49.411  3675  4982 D SecContentProvider: called from com.thaliproject.thalitest
,07-21 16:01:49.414  3675  3785 D MountService: getExternalStorageMountMode : 3
07-21 16:01:49.414  3675  3785 D MountService: getExternalStorageMountMode : 3
07-21 16:01:49.415  3675  3785 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 1002, packageName : com.android.bluetooth
,07-21 16:01:49.434 10217 10217 E Zygote  : v2
07-21 16:01:49.434 10217 10217 I libpersona: KNOX_SDCARD checking this for 1002
07-21 16:01:49.434 10217 10217 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:49.435  3675  3785 I ActivityManager: Start proc 10217:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
07-21 16:01:49.436 10217 10217 E Zygote  : accessInfo : 0
,07-21 16:01:49.447 10217 10217 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:49.449 10217 10217 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.bluetooth 
,07-21 16:01:49.481 10217 10217 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:49.482 10217 10217 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:49.484  3675  3719 I ActivityManager: DSS on for com.android.bluetooth and scale is 1.0
,07-21 16:01:49.536 10217 10217 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-21 16:01:49.542 10217 10217 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:49.549 10217 10217 I HeadsetProvider: onCreate
,07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding GattService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding HeadsetService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding A2dpService
,07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding HidService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding HealthService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding PanService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding SapService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-21 16:01:49.561 10217 10217 D BtSettings.ProfileConfig: Adding HidDevService
07-21 16:01:49.562 10217 10217 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-21 16:01:49.567  3675  4865 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.570  3675  4865 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.573  3675  4179 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.574  3675  4179 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.578  3675  3939 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.579  3675  3939 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.582  3675  4939 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.584  3675  4939 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.587  3675  4982 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.588  3675  4982 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.592  3675  3920 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.593  3675  3920 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.595  3675  4987 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.596  3675  4987 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.598  3675  3719 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.599  3675  3719 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.602  3675  4931 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.603  3675  4931 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.605  3675  4942 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.606  3675  4942 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.608  3675  3988 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-21 16:01:49.609  3675  3988 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:49.705 10217 10217 D BluetoothAdapterState: make() - Creating AdapterState
,07-21 16:01:49.709 10217 10230 I BluetoothAdapterState: Entering OffState
,07-21 16:01:49.712 10217 10232 W bt_osi_thread: run_thread: thread id 10232, thread name stack_manager started
,07-21 16:01:49.713 10217 10232 I bt_core_module: module_init Initializing module "osi_module"
07-21 16:01:49.713 10217 10232 I bt_core_module: module_init Initialized module "osi_module"
07-21 16:01:49.713 10217 10232 I bt_core_module: module_init Initializing module "bt_utils_module"
07-21 16:01:49.713 10217 10232 I bt_core_module: module_init Initialized module "bt_utils_module"
07-21 16:01:49.713 10217 10232 I bt_core_module: module_init Initializing module "btif_config_module"
,07-21 16:01:49.715 10217 10235 W bt_osi_thread: run_thread: thread id 10235, thread name alarm_default_ca started
,07-21 16:01:49.716 10217 10236 W bt_osi_thread: run_thread: thread id 10236, thread name alarm_dispatcher started
07-21 16:01:49.716 10217 10232 I bt_core_module: module_init Initialized module "btif_config_module"
07-21 16:01:49.716 10217 10232 I bt_core_module: module_init Initializing module "interop_module"
07-21 16:01:49.716 10217 10232 I bt_core_module: module_init Initialized module "interop_module"
07-21 16:01:49.716 10217 10232 I bt_core_module: module_init Initializing module "stack_config_module"
,07-21 16:01:49.718 10217 10232 I bt_core_module: module_init Initialized module "stack_config_module"
,07-21 16:01:49.719 10217 10237 W bt_osi_thread: run_thread: thread id 10237, thread name bt_jni_workqueue started
07-21 16:01:49.719 10217 10217 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
07-21 16:01:49.720 10217 10217 W bt_btif : btif_get_adapter_property 2
07-21 16:01:49.720 10217 10217 W bt_btif : btif_get_adapter_property 1
,07-21 16:01:49.721 10217 10237 E BluetoothServiceJni: populateRssiValuesNative
07-21 16:01:49.721 10217 10237 I bt_btif : getModelRssiValues
07-21 16:01:49.721 10217 10237 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,07-21 16:01:49.723 10217 10217 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-21 16:01:49.725 10217 10217 D BluetoothAdapterService: makeHashMapAvPerformance: Loading from conf
,07-21 16:01:49.745  3675  3785 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-21 16:01:49.750 10217 10230 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-21 16:01:49.753 10217 10230 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-21 16:01:49.758 10217 10230 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-21 16:01:49.758 10217 10229 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-21 16:01:49.759 10217 10229 D AdapterProvider: query
07-21 16:01:49.759 10217 10230 D BluetoothAdapterService: Autoconnection is available 
07-21 16:01:49.759 10217 10230 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
07-21 16:01:49.759  3675  3785 D BluetoothManagerService: Ble Turning On/Off, G state: 0, S state: 0
07-21 16:01:49.761 10217 10230 D BluetoothAdapterState: Set Downloadbale DB
07-21 16:01:49.761 10217 10230 D DOWNLOADABLE_DB: initBluetoothDatabase
07-21 16:01:49.762 10217 10230 D DOWNLOADABLE_DB: initBroadcastReceiver
,07-21 16:01:49.765 10217 10230 D DOWNLOADABLE_DB: cleanupLooper
07-21 16:01:49.765 10217 10230 D DOWNLOADABLE_DB: quit init handler
,07-21 16:01:49.772 10217 10229 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@e1e6206
,07-21 16:01:49.774 10217 10229 D BluetoothAdapterService: updateEvent - already set, update
,07-21 16:01:49.774 10217 10229 W BluetoothAdapterService: updateEvent - alreadySet is true
07-21 16:01:49.775 10217 10229 D AdapterProvider: update
,07-21 16:01:49.778 10217 10229 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:49.787 10217 10230 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-21 16:01:49.791  3675  3927 D MountService: getExternalStorageMountMode : 1
07-21 16:01:49.791  3675  3927 D MountService: getExternalStorageMountMode : 3
07-21 16:01:49.791  3675  3927 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10135, packageName : com.samsung.android.sm.policy
,07-21 16:01:49.816 10240 10240 E Zygote  : v2
07-21 16:01:49.816 10240 10240 I libpersona: KNOX_SDCARD checking this for 10135
07-21 16:01:49.816 10240 10240 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:49.817 10240 10240 E Zygote  : accessInfo : 0
,07-21 16:01:49.823  3675  3927 I ActivityManager: Start proc 10240:com.samsung.android.sm.policy/u0a135 for content provider com.samsung.android.sm.policy/.db.PolicyClientProvider
,07-21 16:01:49.828 10240 10240 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:49.830 10240 10240 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-21 16:01:49.866 10240 10240 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:49.867 10240 10240 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:49.872  3675  4179 I ActivityManager: DSS on for com.samsung.android.sm.policy and scale is 1.0
,07-21 16:01:49.912 10240 10240 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient_N/lib/arm64
,07-21 16:01:49.915 10094 10177 D BluetoothAdapter: enable()
,07-21 16:01:49.920 10217 10228 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-21 16:01:49.920 10217 10228 D AdapterProvider: query
,07-21 16:01:49.928 10217 10228 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@e3fa263
,07-21 16:01:49.937 10217 10228 D BluetoothAdapterService: updateEvent - already set, update
07-21 16:01:49.937 10240 10240 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-21 16:01:49.937 10217 10228 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-21 16:01:49.937 10217 10228 D AdapterProvider: update
,07-21 16:01:49.941 10217 10228 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:49.948  3675  4865 W ActivityManager: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-21 16:01:49.949  3675  4865 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-21 16:01:49.949  3675  4865 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-21 16:01:49.949  3675  4865 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-21 16:01:49.949  3675  4865 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-21 16:01:49.949  3675  4865 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-21 16:01:49.949  3675  4865 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-21 16:01:49.949  3675  4865 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-21 16:01:49.949  3675  4865 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-21 16:01:49.949  3675  4865 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-21 16:01:49.949  3675  4865 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-21 16:01:49.951  3675  4865 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-21 16:01:49.952  3675  4865 D SecContentProvider: called from com.thaliproject.thalitest
,07-21 16:01:49.975 10217 10230 D DOWNLOADABLE_DB: Local DB version is = 20160428 SCPM Client DB version is= 20160428
07-21 16:01:49.975 10217 10230 D DOWNLOADABLE_DB: latest polices have already been updated for BT_HFP
,07-21 16:01:49.990 10217 10230 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-21 16:01:50.005 10217 10230 D DOWNLOADABLE_DB: Local DB version is = 20160617 SCPM Client DB version is= 20160617
07-21 16:01:50.005 10217 10230 D DOWNLOADABLE_DB: latest polices have already been updated for BT_BLE
,07-21 16:01:50.018 10217 10230 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-21 16:01:50.034 10217 10230 D DOWNLOADABLE_DB: Local DB version is = 201612050001 SCPM Client DB version is= 201612050001
,07-21 16:01:50.034 10217 10230 D DOWNLOADABLE_DB: latest polices have already been updated for BT_A2DP
,07-21 16:01:50.045 10217 10230 D BluetoothSecureManager: getInstant: null
07-21 16:01:50.045 10217 10230 D BluetoothSecureManager: calling getMethod for getService
07-21 16:01:50.045 10217 10230 D BluetoothSecureManager: calling getService
,07-21 16:01:50.046 10217 10230 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@c4b3f19
,07-21 16:01:50.048  3675  4543 D BluetoothSecureManagerService: isSecureModeEnabled
,07-21 16:01:50.048  3675  4543 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-21 16:01:50.048 10217 10230 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:50.049 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-21 16:01:50.051 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-21 16:01:50.051 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-21 16:01:50.052 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-21 16:01:50.052 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-21 16:01:50.055 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-21 16:01:50.055 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-21 16:01:50.056 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-21 16:01:50.057 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-21 16:01:50.058 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-21 16:01:50.058 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-21 16:01:50.059 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-21 16:01:50.059 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-21 16:01:50.060 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-21 16:01:50.061 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-21 16:01:50.062 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
07-21 16:01:50.062 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-21 16:01:50.063 10217 10230 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-21 16:01:50.063 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,07-21 16:01:50.064 10217 10230 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-21 16:01:50.064 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-21 16:01:50.066 10217 10230 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidDevService
,07-21 16:01:50.067 10217 10230 D BluetoothBondStateMachine: make
,07-21 16:01:50.069 10217 10253 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-21 16:01:50.077 10217 10230 I BluetoothAdapterState: Entering PendingCommandState
,07-21 16:01:50.079 10217 10217 I BtGatt.JNI: classInitNative(L979): classInitNative: Success!
,07-21 16:01:50.086 10217 10217 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-21 16:01:50.087 10217 10217 D BtGatt.GattService: Received start request. Starting profile...
,07-21 16:01:50.087 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:50.087 10217 10217 D BtGatt.GattService: start()
,07-21 16:01:50.089 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:50.089 10217 10217 D BtGatt.AdvertiseManager: advertise manager created
07-21 16:01:50.089 10217 10217 D BtGatt.AdvertiseManager: start
,07-21 16:01:50.095 10217 10217 D BtGatt.ScanManager: start
,07-21 16:01:50.127 10217 10217 D BtGatt.GattService: setGattService(): set to: com.android.bluetooth.gatt.GattService@4c7b978
07-21 16:01:50.127 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:50.127 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:50.127 10217 10217 D BtGatt.GattService: refreshAbusiveScanPackages
,07-21 16:01:50.128 10217 10217 D DOWNLOADABLE_DB: getAbuseScanPackages
,07-21 16:01:50.137 10217 10217 D BtGatt.GattService: refreshAbusiveScanValue()
,07-21 16:01:50.138 10217 10217 D DOWNLOADABLE_DB: getAbuseMaxScanCount
,07-21 16:01:50.145 10217 10217 D DOWNLOADABLE_DB: getAbuseAccumulatedScanTime
,07-21 16:01:50.153 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:50.153 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
07-21 16:01:50.153 10217 10217 D BtGatt.GattService: notifyProfileServiceStateChanged
07-21 16:01:50.154 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:50.154 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,07-21 16:01:50.154 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:50.154 10217 10217 V BluetoothAdapterState: isTurningOn()=false
,07-21 16:01:50.155 10217 10217 V BluetoothAdapterState: isBleTurningOn()=true
07-21 16:01:50.155 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:50.155 10217 10230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-21 16:01:50.161 10217 10232 I bt_core_module: module_start_up Starting module "btif_config_module"
07-21 16:01:50.161 10217 10232 I bt_core_module: module_start_up Started module "btif_config_module"
07-21 16:01:50.161 10217 10232 I bt_core_module: module_start_up Starting module "btsnoop_module"
07-21 16:01:50.161 10217 10232 I bt_core_module: module_start_up Started module "btsnoop_module"
07-21 16:01:50.161 10217 10232 I bt_core_module: module_start_up Starting module "hci_module"
07-21 16:01:50.161 10217 10232 I bt_hci  : start_up
07-21 16:01:50.161 10217 10237 W bt_btif : btif_dm_generic_evt: event=33035
,07-21 16:01:50.162 10217 10267 W bt_osi_thread: run_thread: thread id 10267, thread name hci_thread started
,07-21 16:01:50.168 10217 10232 I bt_vendor: alloc value 0xe627ed35
07-21 16:01:50.168 10217 10232 I bt_vendor: init
07-21 16:01:50.168 10217 10232 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-21 16:01:50.168 10217 10232 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-21 16:01:50.168 10217 10232 I bt_upio : upio_set_bluetooth_power(on: 0)
,07-21 16:01:50.169 10217 10232 I bt_upio : upio_set_bluetooth_power(on: 1)
,07-21 16:01:50.280 10217 10232 D bt_hci  : start_up starting async portion
,07-21 16:01:50.281 10217 10267 I bt_hci  : event_finish_startup
07-21 16:01:50.281 10217 10267 I bt_hci_h4: hal_open
,07-21 16:01:50.281 10217 10267 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
07-21 16:01:50.284 10217 10267 I bt_userial_vendor: userial_vendor_open():UART is setup
07-21 16:01:50.284 10217 10267 I bt_userial_vendor: device fd = 95 open
,07-21 16:01:50.285 10217 10270 W bt_osi_thread: run_thread: thread id 10270, thread name hci_single_chann started
07-21 16:01:50.286 10217 10267 E bt_hwcfg: Start CFG HW, HCI reset
,07-21 16:01:50.295 10217 10267 E bt_hwcfg: Read Local Name after HCI reset
,07-21 16:01:50.320 10217 10267 D bt_hwcfg: Chipset BCM4359C0
07-21 16:01:50.320 10217 10267 D bt_hwcfg: Target name = [BCM4359C0]
,07-21 16:01:50.321 10217 10267 I bt_hwcfg: module_type[semco_b90s_c0].
07-21 16:01:50.322 10217 10267 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
,07-21 16:01:50.322 10217 10267 E bt_hwcfg: ORG patchram base 0092
07-21 16:01:50.322 10217 10267 E bt_hwcfg: ORG patchram minor 0143
07-21 16:01:50.322 10217 10267 E bt_hwcfg: fw ver (org)92.143
07-21 16:01:50.322 10217 10267 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
,07-21 16:01:50.334 10217 10267 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-21 16:01:50.338 10217 10267 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-21 16:01:50.458 10094 10177 D BluetoothAdapter: enable()
,07-21 16:01:50.468 10217 10229 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-21 16:01:50.469 10217 10229 D AdapterProvider: query
,07-21 16:01:50.486 10217 10229 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@9e3888d
,07-21 16:01:50.490 10217 10229 D BluetoothAdapterService: updateEvent - already set, update
,07-21 16:01:50.491 10217 10229 W BluetoothAdapterService: updateEvent - alreadySet is true
07-21 16:01:50.491 10217 10229 D AdapterProvider: update
,07-21 16:01:50.500 10217 10229 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:50.511  3675  3927 W ActivityManager: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-21 16:01:50.513  3675  3927 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-21 16:01:50.513  3675  3927 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-21 16:01:50.513  3675  3927 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-21 16:01:50.513  3675  3927 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-21 16:01:50.513  3675  3927 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-21 16:01:50.513  3675  3927 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-21 16:01:50.513  3675  3927 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-21 16:01:50.513  3675  3927 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-21 16:01:50.513  3675  3927 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-21 16:01:50.513  3675  3927 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
07-21 16:01:50.515  3675  3927 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-21 16:01:50.516  3675  3927 D SecContentProvider: called from com.thaliproject.thalitest
,07-21 16:01:50.852 10217 10267 I bt_hwcfg: bt vendor lib: set UART baud 115200
07-21 16:01:50.853 10217 10267 I bt_hwcfg: FW Download delta = 557433
07-21 16:01:50.853 10217 10267 D bt_hwcfg: Settlement delay -- 100 ms
07-21 16:01:50.853 10217 10267 I bt_hwcfg: Setting fw settlement delay to 100 
,07-21 16:01:50.980 10217 10267 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-21 16:01:51.022 10094 10177 D BluetoothAdapter: enable()
,07-21 16:01:51.032 10217 10229 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-21 16:01:51.033 10217 10229 D AdapterProvider: query
,07-21 16:01:51.055 10217 10229 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@a043f90
,07-21 16:01:51.057 10217 10229 D BluetoothAdapterService: updateEvent - already set, update
,07-21 16:01:51.057 10217 10229 W BluetoothAdapterService: updateEvent - alreadySet is true
07-21 16:01:51.058 10217 10229 D AdapterProvider: update
,07-21 16:01:51.063 10217 10229 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:51.072  3675  4543 W ActivityManager: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-21 16:01:51.073  3675  4543 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-21 16:01:51.073  3675  4543 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-21 16:01:51.073  3675  4543 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-21 16:01:51.073  3675  4543 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-21 16:01:51.073  3675  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-21 16:01:51.073  3675  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-21 16:01:51.073  3675  4543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-21 16:01:51.073  3675  4543 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-21 16:01:51.073  3675  4543 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-21 16:01:51.073  3675  4543 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-21 16:01:51.075  3675  4543 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-21 16:01:51.076  3675  4543 D SecContentProvider: called from com.thaliproject.thalitest
,07-21 16:01:51.082 10217 10267 I bt_hwcfg: vendor lib fwcfg completed
07-21 16:01:51.082 10217 10267 I bt_vendor: firmware callback
07-21 16:01:51.083 10217 10267 I bt_hci  : firmware_config_callback
07-21 16:01:51.083 10217 10232 I bt_core_module: module_start_up Started module "hci_module"
,07-21 16:01:51.083 10217 10271 W bt_osi_thread: run_thread: thread id 10271, thread name bt_workqueue started
,07-21 16:01:51.085 10217 10271 I bt_core_module: module_init Initializing module "bte_logmsg_module"
07-21 16:01:51.085 10217 10271 I bt_core_module: module_init Initialized module "bte_logmsg_module"
07-21 16:01:51.085 10217 10237 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-21 16:01:51.087  3113  3113 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 10217
07-21 16:01:51.088  3113  3113 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
07-21 16:01:51.088 10217 10237 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-21 16:01:51.088 10217 10237 W bt_btif : get_secure_storage_key - ss_is_supported = 1
07-21 16:01:51.088 10217 10237 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-21 16:01:51.088 10217 10237 W bt_btif : btif_dm_generic_evt: event=33035
07-21 16:01:51.088  3113  3113 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,07-21 16:01:51.091 10217 10237 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-21 16:01:51.091  3113  3113 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 10217
07-21 16:01:51.091  3113  3113 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,07-21 16:01:51.285  3113  3113 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-21 16:01:51.286 10217 10237 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,07-21 16:01:51.288 10217 10272 W bt_osi_thread: run_thread: thread id 10272, thread name module_wrapper started
07-21 16:01:51.289 10217 10272 I bt_core_module: module_start_up Starting module "controller_module"
,07-21 16:01:51.392 10217 10272 I bt_core_module: module_start_up Started module "controller_module"
,07-21 16:01:51.393 10217 10272 W bt_osi_thread: run_thread: thread id 10272, thread name module_wrapper exited
,07-21 16:01:51.434 10217 10237 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,07-21 16:01:51.442 10217 10237 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-21 16:01:51.442 10217 10237 W bt_btif : btif_dm_generic_evt: event=33035
,07-21 16:01:51.445 10217 10237 D bt_hci  : do_postload posting postload work item
07-21 16:01:51.445 10217 10267 I bt_hci  : event_postload
07-21 16:01:51.445 10217 10237 E bt_btif_sock: btif_sock_init: !vhci_init
07-21 16:01:51.445 10217 10267 D bt_hwcfg: hw_sco_config
07-21 16:01:51.445 10217 10237 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:227 ##
07-21 16:01:51.445 10217 10267 I bt_hwcfg: I2SPCM config {0x1, 0x0, 0x0, 0x1}
07-21 16:01:51.445 10217 10267 I bt_vendor: sco_config_cb
07-21 16:01:51.445 10217 10267 I bt_hci  : sco_config_callback postload finished.
,07-21 16:01:51.451 10217 10237 I         : iop_db_open: iop_db_open status 0
07-21 16:01:51.452 10217 10237 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-21 16:01:51.452 10217 10237 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
07-21 16:01:51.452 10217 10237 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
07-21 16:01:51.452 10217 10237 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Grace SWB-B90S eLNA-0092
07-21 16:01:51.452 10217 10237 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0092.0143_semco.hcd
07-21 16:01:51.452 10217 10237 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
07-21 16:01:51.452 10217 10237 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true
07-21 16:01:51.453 10217 10237 E BluetoothAdapterState: stateChangeCallback : 1
07-21 16:01:51.453 10217 10230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,07-21 16:01:51.458 10217 10230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.458 10217 10230 D DOWNLOADABLE_DB: refreshDbFile
07-21 16:01:51.458 10217 10230 D BluetoothServiceJni: refreshDownloadableDbFileNative:
07-21 16:01:51.458 10217 10267 I bt_hwcfg: SCO PCM configure {0x0, 0x1, 0x0, 0x0, 0x0}
07-21 16:01:51.458 10217 10230 I bt_btif : refreshDownloadableDbFile
,07-21 16:01:51.460 10217 10267 I bt_vendor: low_power_mode_cb
,07-21 16:01:51.465 10217 10230 I         : iop_db_open: iop_db_open status 0
,07-21 16:01:51.466 10217 10230 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-21 16:01:51.466 10217 10230 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-21 16:01:51.471 10217 10230 D BluetoothAdapterService: Autoconnection is available 
,07-21 16:01:51.471 10217 10230 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-21 16:01:51.471 10217 10230 I BluetoothAdapterState: Entering BleOnState
,07-21 16:01:51.490  3675  3785 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-21 16:01:51.492  3675  3785 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-21 16:01:51.495  3675  3785 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:51.497 10217 10230 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
07-21 16:01:51.497 10217 10238 E BluetoothBondStateMachine: initStateMachine
,07-21 16:01:51.502  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:01:51.502  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -49
07-21 16:01:51.503 10217 10230 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-21 16:01:51.503 10217 10230 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-21 16:01:51.504  3675  3785 D BluetoothManagerService: Turning On/Off, G state: 0, S state: 0, mBLE count: 0, s BLE count: 0
,07-21 16:01:51.505 10217 10230 D BluetoothAdapterService: Autoconnection is available 
07-21 16:01:51.505 10217 10230 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-21 16:01:51.506 10217 10230 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-21 16:01:51.506 10217 10230 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-21 16:01:51.506 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-21 16:01:51.510  4068  4289 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:51.510  4068  4289 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-21 16:01:51.511  3675  3675 D BluetoothPhoneService: Bluetooth Adapter state : 11
,07-21 16:01:51.515  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-21 16:01:51.515  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:51.515  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-21 16:01:51.521 10179 10179 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:51.522 10179 10179 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-21 16:01:51.526 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:51.538  3675  3920 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{9493b2d: PendingIntentRecord{6041862 com.google.android.gms broadcastIntent}}
,07-21 16:01:51.549 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-21 16:01:51.555 10217 10217 D HeadsetService: Received start request. Starting profile...
07-21 16:01:51.555 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.555 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-21 16:01:51.569 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-21 16:01:51.570 10217 10217 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
07-21 16:01:51.573 10217 10217 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-21 16:01:51.573 10217 10217 D HeadsetStateMachine: make
,07-21 16:01:51.575 10217 10217 E HeadsetStateMachine: # of Max HF connection is 3
,07-21 16:01:51.577 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-21 16:01:51.580 10094 10177 D BluetoothAdapter: enable()
,07-21 16:01:51.584 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-21 16:01:51.587 10217 10228 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-21 16:01:51.587 10217 10228 D AdapterProvider: query
,07-21 16:01:51.592 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-21 16:01:51.597 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-21 16:01:51.597 10217 10230 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-21 16:01:51.597 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
07-21 16:01:51.597 10217 10230 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
07-21 16:01:51.597 10217 10230 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-21 16:01:51.602 10217 10228 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@a17ef54
,07-21 16:01:51.603 10217 10228 D BluetoothAdapterService: updateEvent - already set, update
07-21 16:01:51.603 10217 10230 I BluetoothAdapterState: Entering PendingCommandState
,07-21 16:01:51.605 10217 10228 W BluetoothAdapterService: updateEvent - alreadySet is true
07-21 16:01:51.605 10217 10228 D AdapterProvider: update
,07-21 16:01:51.608 10217 10228 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:51.612 10217 10217 I DualScoManager: Instantiating Dual Sco Manager
07-21 16:01:51.612 10217 10217 I DualScoManager: Set HeadsetServiceHelper
07-21 16:01:51.612 10217 10217 I DualScoManager: setNotificationManager
07-21 16:01:51.612 10217 10217 I DualScoManager: setAudioManager
07-21 16:01:51.613 10217 10217 D BluetoothAtMessage: createCMTIContentObservers
,07-21 16:01:51.615  3675  3720 W ActivityManager: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-21 16:01:51.616  3675  3720 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-21 16:01:51.616  3675  3720 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=10094, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-21 16:01:51.616  3675  3720 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-21 16:01:51.616  3675  3720 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-21 16:01:51.616  3675  3720 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-21 16:01:51.616  3675  3720 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-21 16:01:51.616  3675  3720 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-21 16:01:51.616  3675  3720 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-21 16:01:51.616  3675  3720 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-21 16:01:51.617  3675  3720 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-21 16:01:51.619  3675  3720 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-21 16:01:51.620  3675  3720 D SecContentProvider: called from com.thaliproject.thalitest
,07-21 16:01:51.624 10217 10217 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@c214b9f
,07-21 16:01:51.626 10217 10217 I HeadsetService: getHeadsetDB(true) - 44:78:3E:94:4A:XX, 300, 1
07-21 16:01:51.626 10217 10217 I DualScoManager: setSystemAudioInbandSupported : true
,07-21 16:01:51.627 10217 10217 I HeadsetStateMachine: isAutoAppInstalled : false
07-21 16:01:51.627 10217 10217 I HeadsetStateMachine: IBR : true (SysA : 1 / DB : 1)
,07-21 16:01:51.629 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
,07-21 16:01:51.630 10217 10217 D DOWNLOADABLE_DB: getNotAllowedVoiceRecognitionDeviceList
,07-21 16:01:51.637 10217 10274 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-21 16:01:51.641 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.641 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-21 16:01:51.641 10217 10217 D HeadsetService: notifyProfileServiceStateChanged
07-21 16:01:51.641 10217 10274 D HeadsetStateMachine: Clear mHeadsetBrsf
,07-21 16:01:51.642 10217 10274 D HeadsetStateMachine: map size, before remove : 0
07-21 16:01:51.642 10217 10274 D HeadsetStateMachine: map size, after remove: 0
,07-21 16:01:51.642 10217 10274 D HeadsetStateMachine: connectNextConnectingDevice(false) : null
07-21 16:01:51.646 10217 10217 D A2dpService: Received start request. Starting profile...
07-21 16:01:51.646 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.647 10217 10217 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-21 16:01:51.649 10179 10179 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:51.650 10179 10179 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,07-21 16:01:51.669 10217 10217 I Avrcp   : No of Audio players :: 1
07-21 16:01:51.670 10217 10217 I Avrcp   : App Package name is GM
,07-21 16:01:51.690 10217 10267 I bt_hwcfg: SCO PCM data format {0x0, 0x0, 0x3, 0x0, 0x0}
,07-21 16:01:51.692 10217 10217 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,07-21 16:01:51.693 10217 10267 I bt_hwcfg: sco I2S/PCM config result 0 [0-Success, 1-Fail]
07-21 16:01:51.693 10217 10267 I bt_vendor: sco_audiostate_cb(status: 0)
,07-21 16:01:51.694 10217 10217 I Avrcp   : No of Video players :: 2
07-21 16:01:51.695 10217 10217 I Avrcp   : Video App Package name is VP
,07-21 16:01:51.701 10217 10217 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-21 16:01:51.701 10217 10217 I Avrcp   : Video App Package name is others
,07-21 16:01:51.710 10217 10217 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-21 16:01:51.710 10217 10217 I Avrcp   : Add tempPlayer
07-21 16:01:51.710 10217 10217 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-21 16:01:51.710 10217 10217 V Avrcp   : no_of_players : 4
07-21 16:01:51.710 10217 10217 I Avrcp   : Total no of players: 4
07-21 16:01:51.710 10217 10217 V Avrcp   : Samsung player is the 1st player
,07-21 16:01:51.711 10217 10217 D Avrcp   : Compose Browsing Service Candidate
,07-21 16:01:51.859 10217 10217 D Avrcp   : ResolveInfo info ResolveInfo{8d8b331 com.android.bluetooth/.a2dpsink.mbs.A2dpMediaBrowserService m=0x108000}
07-21 16:01:51.859 10217 10217 D Avrcp   : ResolveInfo info ResolveInfo{3c36a16 com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-21 16:01:51.859 10217 10217 D Avrcp   : Initialize Media Controller
,07-21 16:01:51.861 10217 10217 D Avrcp   : Get the Context Package Name: com.android.bluetooth
07-21 16:01:51.879 10217 10217 E Avrcp   : getActiveSessions
07-21 16:01:51.879 10217 10217 D Avrcp   : pick active media Controller
07-21 16:01:51.879 10217 10217 D Avrcp   : Get the active Media Controller 
,07-21 16:01:51.882 10217 10217 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-21 16:01:51.882 10217 10217 D A2dpStateMachine: make
,07-21 16:01:51.885 10217 10284 W bt_osi_thread: run_thread: thread id 10284, thread name media_worker started
07-21 16:01:51.886 10217 10217 E bt_btif : warning : media task started media_task_refcnt 1 
07-21 16:01:51.886 10217 10217 W bt_btif : btif_ar_init
07-21 16:01:51.886 10217 10237 W bt_btif : av start inhibit off
,07-21 16:01:51.892 10217 10217 E A2dpStateMachine: isDualPlayEnabled : Dual Play not supported
07-21 16:01:51.893 10217 10283 D A2dpStateMachine: Enter Disconnected: -2
,07-21 16:01:51.896 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.896 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-21 16:01:51.896 10217 10217 D A2dpService: notifyProfileServiceStateChanged
07-21 16:01:51.897 10217 10217 I BluetoothHidServiceJni: classInitNative: succeeds
07-21 16:01:51.902 10217 10217 D HidService: Received start request. Starting profile...
07-21 16:01:51.903 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.903 10217 10217 D HidService: setHidService(): set to: null
07-21 16:01:51.903 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.903 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-21 16:01:51.903 10217 10217 D HidService: notifyProfileServiceStateChanged
07-21 16:01:51.904 10217 10217 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-21 16:01:51.909 10217 10217 D HealthService: Received start request. Starting profile...
07-21 16:01:51.910 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
,07-21 16:01:51.912 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.912 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
,07-21 16:01:51.912 10217 10217 D HealthService: notifyProfileServiceStateChanged
,07-21 16:01:51.916 10217 10217 I BluetoothPanServiceJni: classInitNative(L139): succeeds
,07-21 16:01:51.920 10217 10217 D PanService: Received start request. Starting profile...
07-21 16:01:51.920 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.921 10217 10217 D BluetoothPanServiceJni: initializeNative(L144): pan
,07-21 16:01:51.928 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.928 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
07-21 16:01:51.928 10217 10217 D PanService: notifyProfileServiceStateChanged
,07-21 16:01:51.936 10217 10217 D BluetoothMapService: Received start request. Starting profile...
07-21 16:01:51.936 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
,07-21 16:01:51.941 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
,07-21 16:01:51.941 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
07-21 16:01:51.941 10217 10217 D BluetoothMapService: notifyProfileServiceStateChanged
,07-21 16:01:51.946  4735  6871 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-21 16:01:51.949 10217 10217 V SapService: SapBinder()
,07-21 16:01:51.951 10217 10217 D SapService: Received start request. Starting profile...
07-21 16:01:51.951 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.951 10217 10217 V SapService: start()
07-21 16:01:51.951 10217 10217 D SapService: Disable sap : false
,07-21 16:01:51.954 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.954 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
07-21 16:01:51.954 10217 10217 D SapService: notifyProfileServiceStateChanged
,07-21 16:01:51.955 10217 10217 V BluetoothHidDevServiceJni: classInitNative: done
,07-21 16:01:51.961 10217 10217 D HidDevService: Received start request. Starting profile...
07-21 16:01:51.961 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.961 10217 10217 D HidDevService: start()
07-21 16:01:51.961 10217 10217 V BluetoothHidDevServiceJni: initNative enter
07-21 16:01:51.961 10217 10217 V BluetoothHidDevServiceJni: initNative done
07-21 16:01:51.961 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:51.961 10217 10217 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Message sending
07-21 16:01:51.961 10217 10217 D HidDevService: notifyProfileServiceStateChanged
07-21 16:01:51.961 10217 10217 D HeadsetStateMachine: Proxy object connected
,07-21 16:01:51.962 10217 10217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-21 16:01:51.962 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:51.962 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
07-21 16:01:51.963 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:51.963 10217 10217 V BluetoothAdapterState: isTurningOn()=true
07-21 16:01:51.963 10217 10274 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-21 16:01:51.963 10217 10217 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:51.963 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
,07-21 16:01:51.963 10217 10274 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-21 16:01:51.964 10217 10274 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-21 16:01:51.964 10217 10274 E HeadsetStateMachine: Unknown message: 11
07-21 16:01:51.964 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:51.965 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isTurningOn()=true
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:51.965 10217 10217 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-21 16:01:51.965 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:51.965 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isTurningOn()=true
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:51.965 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:51.965 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isTurningOn()=true
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:51.965 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:51.967 10217 10217 D BluetoothUtils: readSalesCode :: sales code is XEO
07-21 16:01:51.967 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:51.967 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-21 16:01:51.967 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:51.967 10217 10217 V BluetoothAdapterState: isTurningOn()=true
07-21 16:01:51.967 10217 10217 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:51.967 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:51.967 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:51.967 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
07-21 16:01:51.967 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:51.967 10217 10217 V BluetoothAdapterState: isTurningOn()=true
07-21 16:01:51.967 10217 10217 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:51.967 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:51.968 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:51.968 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
07-21 16:01:51.968 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:51.968 10217 10217 V BluetoothAdapterState: isTurningOn()=true
07-21 16:01:51.968 10217 10217 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:51.968 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:51.968 10217 10217 E BluetoothAdapterService: handleMessage() - Message: 1
07-21 16:01:51.968 10217 10217 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=c,om.android.bluetooth.hid.HidDevService, state=12, Before synchronized
07-21 16:01:51.968 10217 10217 V BluetoothAdapterState: isTurningOff()=false
07-21 16:01:51.968 10217 10217 V BluetoothAdapterState: isTurningOn()=true
07-21 16:01:51.969 10217 10217 V BluetoothAdapterState: isBleTurningOn()=false
07-21 16:01:51.969 10217 10217 V BluetoothAdapterState: isBleTurningOff()=false
07-21 16:01:51.969 10217 10217 I BluetoothA2dpServiceJni: Attempting to set busy level
07-21 16:01:51.969 10217 10230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-21 16:01:51.971 10217 10230 E BluetoothServiceJni: enableBrEdrNative:
07-21 16:01:51.971 10217 10230 I bt_btif : enable_bredr
07-21 16:01:51.972 10217 10237 W bt_btif : btif_dm_generic_evt: event=33035
,07-21 16:01:51.974 10217 10237 W bt_btif : btif_dm_generic_evt: event=33035
,07-21 16:01:51.976 10217 10237 W bt_btif : IsSoftphone: 
,07-21 16:01:51.977 10217 10237 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-21 16:01:51.977 10217 10237 W bt_btif : btif_dm_generic_evt: event=33035
07-21 16:01:51.977 10217 10271 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
,07-21 16:01:51.985 10217 10237 E BluetoothServiceJni: populateRssiValuesNative
,07-21 16:01:51.985 10217 10237 I bt_btif : getModelRssiValues
07-21 16:01:51.985 10217 10237 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-21 16:01:51.991 10217 10271 D CODEC_IF_MOD: codec_open: codec_open
07-21 16:01:51.991 10217 10271 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-21 16:01:51.991 10217 10271 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-21 16:01:51.991 10217 10271 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-21 16:01:51.991 10217 10271 D CODEC_IF: codec_if_open: codec module opened (v0.1
,07-21 16:01:51.991 10217 10271 D CODEC_IF: codec_if_close: codec_if_close hdl -567689212
07-21 16:01:51.991 10217 10271 D CODEC_IF_MOD: codec_close: codec_close
07-21 16:01:51.991 10217 10271 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-21 16:01:51.991 10217 10271 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-21 16:01:51.991 10217 10271 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,07-21 16:01:52.004 10217 10271 D CODEC_IF_SSHD: codec_open: codec_open
,07-21 16:01:52.004 10217 10271 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-21 16:01:52.004 10217 10237 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-21 16:01:52.004 10217 10271 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-21 16:01:52.004 10217 10271 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-21 16:01:52.004 10217 10271 D CODEC_IF: codec_if_close: codec_if_close hdl -844370560
07-21 16:01:52.004 10217 10271 D CODEC_IF_SSHD: codec_close: codec_close
07-21 16:01:52.004 10217 10237 E bt_btif : btif_handle_bluetooth_enable_evt
07-21 16:01:52.004 10217 10271 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
,07-21 16:01:52.004 10217 10237 E bt_btif : ANT+ socket does not initialize.
07-21 16:01:52.004 10217 10271 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-21 16:01:52.004 10217 10271 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
07-21 16:01:52.005 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:52.006 10217 10290 W bt_osi_thread: run_thread: thread id 10290, thread name btif_sock started
07-21 16:01:52.006 10217 10237 E BluetoothAdapterState: stateChangeCallback : 17
07-21 16:01:52.006 10217 10237 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
07-21 16:01:52.007 10217 10230 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,07-21 16:01:52.009 10217 10230 D BluetoothAdapterProperties: ScanMode =  20
07-21 16:01:52.009 10217 10230 D BluetoothAdapterProperties: State =  11
,07-21 16:01:52.012  3675  4178 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-21 16:01:52.013  3675  4178 D SecContentProvider: called from android.uid.bluetooth:1002
,07-21 16:01:52.013 10217 10271 D CODEC_IF_SSHD2: codec_open: codec_open
07-21 16:01:52.013 10217 10271 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-21 16:01:52.013 10217 10271 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-21 16:01:52.013 10217 10271 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-21 16:01:52.013 10217 10271 D CODEC_IF: codec_if_close: codec_if_close hdl -810270720
07-21 16:01:52.013 10217 10271 D CODEC_IF_SSHD2: codec_close: codec_close
07-21 16:01:52.013 10217 10271 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
07-21 16:01:52.014 10217 10271 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
07-21 16:01:52.014 10217 10237 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-21 16:01:52.014 10217 10237 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-21 16:01:52.014 10217 10237 E bt_btif : no av control block available at state:3
07-21 16:01:52.014 10217 10237 E bt_btif : no av control block available at state:3
07-21 16:01:52.014 10217 10237 E bt_btif : no av control block available at state:2
07-21 16:01:52.014 10217 10237 E bt_btif : warning : no command pending, ignore ack
07-21 16:01:52.014 10217 10237 E bt_btif : no av control block available at state:3
,07-21 16:01:52.014 10217 10237 E bt_btif : no av control block available at state:2
07-21 16:01:52.014 10217 10237 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-21 16:01:52.015  3675  3920 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.015 10217 10284 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-21 16:01:52.015 10217 10284 E bt_btif : warning : no command pending, ignore ack
07-21 16:01:52.015  3675  3920 D SecContentProvider: called from android.uid.bluetooth:1002
07-21 16:01:52.016 10217 10271 D CODEC_IF_MOD: codec_open: codec_open
07-21 16:01:52.016 10217 10230 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-21 16:01:52.016 10217 10271 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-21 16:01:52.016 10217 10271 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-21 16:01:52.016 10217 10271 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-21 16:01:52.016 10217 10271 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-21 16:01:52.016 10217 10271 D CODEC_IF: codec_if_close: codec_if_close hdl -567689212
07-21 16:01:52.016 10217 10271 D CODEC_IF_MOD: codec_close: codec_close
07-21 16:01:52.016 10217 10271 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-21 16:01:52.016 10217 10271 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-21 16:01:52.017 10217 10271 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
07-21 16:01:52.017 10217 10230 D BluetoothAdapterService: [VendorCapa] prevState: 11, newState: 12
07-21 16:01:52.019 10217 10230 I bt_btif : vsc_getvendorcapabilities
07-21 16:01:52.019 10217 10271 D CODEC_IF_SSHD: codec_open: codec_open
07-21 16:01:52.019 10217 10271 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-21 16:01:52.019 10217 10271 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-21 16:01:52.019 10217 10271 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-21 16:01:52.019 10217 10271 D CODEC_IF: codec_if_close: codec_if_close hdl -844370560
07-21 16:01:52.019 10217 10271 D CODEC_IF_SSHD: codec_close: codec_close
07-21 16:01:52.019 10217 10271 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-21 16:01:52.019 10217 10271 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-21 16:01:52.019 10217 10271 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
07-21 16:01:52.020 10217 10230 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-21 16:01:52.021 10217 10271 D CODEC_IF_SSHD2: codec_open: codec_open
07-21 16:01:52.021 10217 10271 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-21 16:01:52.022 10217 10271 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-21 16:01:52.022 10217 10271 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-21 16:01:52.022 10217 10271 D CODEC_IF: codec_if_close: codec_if_close hdl -810270720
07-21 16:01:52.022 10217 10271 D CODEC_IF_SSHD2: codec_close: codec_close
07-21 16:01:52.022 10217 10271 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
,07-21 16:01:52.022 10217 10237 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-21 16:01:52.022 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
07-21 16:01:52.022 10217 10237 E bt_btif : bta_av_co_get]: id 12, is_orig 0t of bounds:255
07-21 16:01:52.022 10217 10237 E bt_btif :                : sec: 0x1086 active peer with this handle 0x0
07-21 16:01:52.022 10217 10237 E bt_btif : no av control block available at state:3
07-21 16:01:52.022 10217 10237 E bt_btif : no av control block available at state:3
07-21 16:01:52.022 10217 10237 E bt_btif : no av control block available at state:2
07-21 16:01:52.022 10217 10237 E bt_btif : warning : no command , is_orig 0nore ack
07-21 16:01:52.022 10217 10237 E bt_btif : no av control block available at state:3
07-21 16:01:52.022 10217 10237 E bt_btif : no av control block available at state:2
07-21 16:01:52.022 10217 10284 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-21 16:01:52.022 10217 10237 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-21 16:01:52.022 10217 10284 E bt_btif : warning : no command pending, ignore ack
,07-21 16:01:52.027 10094 10094 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.029 10094 10094 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.032 10217 10230 D BluetoothAdapterService: Autoconnection is available 
,07-21 16:01:52.032 10217 10230 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,07-21 16:01:52.032 10217 10230 D BluetoothAdapterService: starting service from this receiver
07-21 16:01:52.033 10094 10094 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
07-21 16:01:52.038 10094 10094 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.039 10217 10237 D BluetoothPanServiceJni: control_state_callback(L64): state:0, local_role:3, ifname:bt-pan
07-21 16:01:52.039 10217 10237 W bt_btif : btif_dm_generic_evt: event=34050
07-21 16:01:52.040 10217 10237 D BluetoothAdapterProperties: [VendorCapa] : mDbfwSupported: 1 , mA2dpLinkFeedbackSupported: 1
07-21 16:01:52.040 10094 10094 D BluetoothAdapter: STATE_ON
07-21 16:01:52.043  4068  4083 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-21 16:01:52.043 10094 10094 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-21 16:01:52.047 10217 10229 D BluetoothAdapter: onBluetoothStateChange: up=true
07-21 16:01:52.047 10217 10229 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-21 16:01:52.047 10217 10230 I BluetoothAdapterState: Entering OnState
07-21 16:01:52.047  3675  3785 D BluetoothAdapter: onBluetoothStateChange: up=true
07-21 16:01:52.047  3675  3785 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-21 16:01:52.052 10094 10106 D BluetoothAdapter: onBluetoothStateChange: up=true
07-21 16:01:52.052 10094 10106 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-21 16:01:52.052  4068  6260 D BluetoothMap: onBluetoothStateChange: up=true
07-21 16:01:52.055 10094 10094 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.059 10179 10191 D BluetoothAdapter: onBluetoothStateChange: up=true
07-21 16:01:52.059 10179 10191 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-21 16:01:52.060  4735  4747 D BluetoothAdapter: onBluetoothStateChange: up=true
07-21 16:01:52.060  4735  4747 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:52.060 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-21 16:01:52.061  4041  4361 D BluetoothAdapter: onBluetoothStateChange: up=true
07-21 16:01:52.061  4041  4361 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-21 16:01:52.063 10094 10094 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.068 10094 10094 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-21 16:01:52.069 10179 10192 D BluetoothPan: onBluetoothStateChange on: true
,07-21 16:01:52.072 10217 10217 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-21 16:01:52.081  3675  3785 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-21 16:01:52.084  9495  9507 D BluetoothAdapter: onBluetoothStateChange: up=true
07-21 16:01:52.084  9495  9507 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-21 16:01:52.085  4068  4082 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-21 16:01:52.091  4768  4781 D BluetoothAdapter: onBluetoothStateChange: up=true
07-21 16:01:52.091  4768  4781 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-21 16:01:52.092  4068  4083 D BluetoothSap: onBluetoothStateChange: up=true
07-21 16:01:52.092  4068  4083 D BluetoothSap: Binding service...
,07-21 16:01:52.094  4068  4068 D A2dpProfile: Bluetooth service connected
,07-21 16:01:52.097 10217 10217 I BluetoothPbapService: Handler(): got msg=1
,07-21 16:01:52.099 10217 10292 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-21 16:01:52.101 10217 10228 D A2dpStateMachine: getConnectedDevices : size=0
,07-21 16:01:52.102  4068  4068 D BluetoothMap: Proxy object connected
07-21 16:01:52.102  4068  4068 D MapProfile: Bluetooth service connected
07-21 16:01:52.102  4068  4068 D BluetoothMap: getConnectedDevices()
07-21 16:01:52.103 10179 10179 D BluetoothPan: BluetoothPAN Proxy object connected
07-21 16:01:52.103 10179 10179 D PanProfile: Bluetooth service connected
07-21 16:01:52.103 10217 10239 D A2dpStateMachine: getConnectedDevices : size=0
,07-21 16:01:52.107 10217 10292 D BluetoothSocket: bindListen(): myUserId = 0
,07-21 16:01:52.107 10217 10292 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:01:52.109  4068  4068 D BluetoothInputDevice: Proxy object connected
07-21 16:01:52.110  4068  4068 D HidProfile: Bluetooth service connected
07-21 16:01:52.111  4068  4547 D BluetoothPan: onBluetoothStateChange on: true
,07-21 16:01:52.114 10217 10292 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-21 16:01:52.117  4068  4068 D BluetoothSap: Proxy object connected
,07-21 16:01:52.117  4068  4068 D SapProfile: Bluetooth service connected
07-21 16:01:52.117  4068  4068 D BluetoothPan: BluetoothPAN Proxy object connected
07-21 16:01:52.117  4068  4068 D PanProfile: Bluetooth service connected
07-21 16:01:52.120  4068  4083 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-21 16:01:52.124  4068  4239 D BluetoothPbap: onBluetoothStateChange: up=true
,07-21 16:01:52.127  4068  6260 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-21 16:01:52.127  4068  6260 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-21 16:01:52.128 10179 10192 D BluetoothSap: onBluetoothStateChange: up=true
07-21 16:01:52.128 10179 10192 D BluetoothSap: Binding service...
07-21 16:01:52.130  4068  4068 D BluetoothPbap: Proxy object connected
07-21 16:01:52.130  4068  4068 D PbapServerProfile: Bluetooth service connected
,07-21 16:01:52.133 10179 10179 D BluetoothSap: Proxy object connected
07-21 16:01:52.133 10094 10177 D BluetoothAdapter: STATE_ON
07-21 16:01:52.133 10179 10179 D SapProfile: Bluetooth service connected
,07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:01:52.135 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-21 16:01:52.137  4068  4289 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:52.137 10094 10157 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
07-21 16:01:52.137  4068  4289 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
07-21 16:01:52.137  3675  3675 D Telecom : SecBluetoothManager : register BluetoothHeadset after STATE_ON : null
07-21 16:01:52.138  3675  3675 D Telecom : SecBluetoothManager : registerBluetoothHeadsetMessageListener fail
,07-21 16:01:52.139  3675  3675 D BluetoothPhoneService: Bluetooth Adapter state : 12
,07-21 16:01:52.140  3675  3675 I BluetoothPhoneService: queryPhoneState
07-21 16:01:52.140  3675  3675 I BluetoothPhoneService: updateHeadsetWithCallState : true
07-21 16:01:52.143  3675  4941 D WifiService: setWifiEnabled: false pid=10094, uid=10033
07-21 16:01:52.144 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:52.145  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-21 16:01:52.145  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:52.145  3675  3675 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-21 16:01:52.149 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,07-21 16:01:52.150 10179 10179 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:52.150 10179 10179 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-21 16:01:52.153 10217 10217 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:52.153 10217 10217 D PanService: BT STATE ON
,07-21 16:01:52.154 10217 10217 D EnhancedTetheringManager: EnhancedTetheringManager()
07-21 16:01:52.154 10217 10217 D EnhancedTetheringManager: start
,07-21 16:01:52.156 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:52.164  3675  4941 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-21 16:01:52.164  3675  4941 D WifiControlHistoryProvider: query
07-21 16:01:52.166 10217 10217 D ETMLeHelper: ETMLeHelper()
07-21 16:01:52.166 10217 10217 D ETMLeHelper: initTetherAdv
07-21 16:01:52.167 10179 10179 E BluetoothEventManager: unregisterProfileIntentReceiver :: mProfileConnectionReceiver was not registered.
07-21 16:01:52.167 10179 10179 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-21 16:01:52.168  3675  3720 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{3f32c07: PendingIntentRecord{a5e1134 com.google.android.gms broadcastIntent}}
,07-21 16:01:52.171 10217 10217 D BluetoothAdapter: STATE_ON
07-21 16:01:52.172 10217 10217 D BluetoothAdapter: STATE_ON
07-21 16:01:52.172  3675  4941 D WifiNative-wlan0: callSECApiVoid - ID [312]
07-21 16:01:52.173 10217 10217 D BluetoothAdapter: STATE_ON
07-21 16:01:52.173  3675  4012 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
07-21 16:01:52.174  3675  4941 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-21 16:01:52.175  3675  4941 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:52.175  3675  3675 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-21 16:01:52.175  3675  4941 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-21 16:01:52.177 10179 10179 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-21 16:01:52.178  3675  4941 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-21 16:01:52.179 10217 10217 D BluetoothAdapter: isSecureModeEnabled
07-21 16:01:52.179 10217 10217 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:52.180 10217 10217 D ETMLeHelper: initTetherScan
07-21 16:01:52.181 10217 10217 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.181 10179 10179 D LocalBluetoothProfileManager: Adding local HEADSET profile
07-21 16:01:52.182  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135179 arg1=192 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-21 16:01:52.182  3675  3924 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.182  4068  4289 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
07-21 16:01:52.182  4068  4289 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
07-21 16:01:52.182  4068  4289 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-21 16:01:52.182  4068  4289 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
07-21 16:01:52.182  4068  4289 W LocalBluetoothProfileManager: updateLocalProfiles :: Spp profile was created already 
07-21 16:01:52.182 10217 10217 D BluetoothAdapter: STATE_ON
07-21 16:01:52.185 10179 10179 E BluetoothHeadset: BTStateChangeCB is registed
07-21 16:01:52.185  3675  3924 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:52.186  3675  3924 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.186  3675  3924 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:52.187 10217 10217 D BluetoothMapUtils: [RCS] imsConfigCscFeatures : , enableCpmFeature : false
07-21 16:01:52.187 10217 10217 D BluetoothMapUtils: mRcsSupported : false
07-21 16:01:52.187  3675  3925 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-21 16:01:52.188 10179 10179 D BluetoothMap: Create BluetoothMap proxy object
07-21 16:01:52.188  3675  3925 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@6883b0f
,07-21 16:01:52.191  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160800, SetElapsed=578741, nowELAPSED=209971
07-21 16:01:52.191  3675  3925 D WifiStateMachine: isFindLocationId() - Location Id : 1
07-21 16:01:52.191  3675  3925 D WifiStateMachine: ConnectedState - exit() - stopLearning id : 1
07-21 16:01:52.191  3675  3925 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-21 16:01:52.192  3675  3925 D SLocation: system
,07-21 16:01:52.192  3675  3925 D SLocation: stopLearning ID = 1
07-21 16:01:52.192  3675  3925 D SLocation: setLearningStatus ID = 1 / status = false
07-21 16:01:52.193  3675  3925 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.194  3675  4982 D MountService: getExternalStorageMountMode : 1
07-21 16:01:52.194  3675  4982 D MountService: getExternalStorageMountMode : 3
07-21 16:01:52.194  3675  4982 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
07-21 16:01:52.194  3675  3925 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:52.194  3675  3925 D WifiStateMachine: Wifi got Disconnected in connectedstate, Send provisioning intent mAutoRoamingfalse
07-21 16:01:52.195  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiStateMachine$ConnectedState.exit:11809 com.android.internal.util.StateMachine$SmHandler.invokeExitMethods:1009 com.android.internal.util.StateMachine$SmHandler.performTransitions:865 com.android.internal.util.StateMachine$SmHandler.handleMessage:809 
,07-21 16:01:52.215 10298 10298 E Zygote  : v2
07-21 16:01:52.215 10298 10298 I libpersona: KNOX_SDCARD checking this for 10049
07-21 16:01:52.215 10298 10298 I libpersona: KNOX_SDCARD not a persona
07-21 16:01:52.216 10298 10298 E Zygote  : isSdpEnabledProcess - SDP enabled
,07-21 16:01:52.217 10298 10298 E Zygote  : accessInfo : 64
07-21 16:01:52.217 10298 10298 E Zygote  : isSdpEnabledProcess - SDP enabled
07-21 16:01:52.217 10298 10298 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,07-21 16:01:52.222  3675  4982 I ActivityManager: Start proc 10298:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,07-21 16:01:52.224  3675  3925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-21 16:01:52.226  3675  3931 D DhcpClient: doQuit
07-21 16:01:52.227  3675  3931 D ApfFilter: (wlan0): shutting down
07-21 16:01:52.227  3675  5125 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@eaeaeb4
,07-21 16:01:52.227  3675  5125 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@616359e
07-21 16:01:52.227 10298 10298 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-21 16:01:52.228  3675  5125 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@23e1895
07-21 16:01:52.229 10298 10298 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,07-21 16:01:52.231  3675  3921 D WifiP2pService: InactiveState{ what=143375 }
07-21 16:01:52.232  3675  3921 D WifiP2pService: P2pEnabledState{ what=143375 }
07-21 16:01:52.233  3675  3956 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-21 16:01:52.233  3675  3956 D ConnectivityService: ignoring duplicate network state non-change
07-21 16:01:52.233  3675  3956 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 12
07-21 16:01:52.235  3675  3956 V NetworkStats: updateIfacesLocked()
07-21 16:01:52.235  3675  3956 V NetworkStats: performPollLocked(flags=0x1)
07-21 16:01:52.235  3675  3956 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:01:52.236  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=-4ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-21 16:01:52.237  3675  4012 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-21 16:01:52.239  3675  3925 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-21 16:01:52.240  3675  3675 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-21 16:01:52.241  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-21 16:01:52.241  3675  3925 I WifiConnectivityManager: Set WiFi disabled
07-21 16:01:52.241  3675  3675 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
07-21 16:01:52.242  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-21 16:01:52.242  3675  3952 I WifiHs20Service: Message received 5007
07-21 16:01:52.246  3675  3925 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@b42b869
07-21 16:01:52.246  3675  3925 I WifiStateMachine: deinitGeofence
07-21 16:01:52.248  4041  4041 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-21 16:01:52.253 10298 10298 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:52.254  3675  3956 V NetworkStats: performPollLocked() took 19ms
,07-21 16:01:52.254  3675  3956 D NtpTrustedTime: currentTimeMillis() cache hit
,07-21 16:01:52.254 10298 10298 D ActivityThread: Added TimaKeyStore provider
07-21 16:01:52.255  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:01:52.258  3675  4012 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-21 16:01:52.259  3675  3675 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
,07-21 16:01:52.259  3675  3925 D SLocation: stopGeofence ID = 1
07-21 16:01:52.259  3675  4177 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,07-21 16:01:52.272 10179 10179 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-21 16:01:52.273  3675  3956 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-21 16:01:52.273  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.273  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:01:52.273  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:01:52.273  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:01:52.273  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:01:52.274  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.274  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-21 16:01:52.275  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:01:52.276  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:01:52.276  3675  4011 D DnsEventListenerService: Logging 32 results for netId 502
,07-21 16:01:52.278  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.278  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.278  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.278  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.279  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.280  3675  5125 D DhcpClient: onQuitting
07-21 16:01:52.280  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.280  4528  4604 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [false]
07-21 16:01:52.282  4528  4614 D PdnController: handleMessage: what 106
07-21 16:01:52.283  4528  4614 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [false]
07-21 16:01:52.284  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.284  4528  4614 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [false]
07-21 16:01:52.284  4528  4614 D ResipRegiMgr: handleMessage(): 3
07-21 16:01:52.284  4528  4614 D RegiMgrBase: handleMessage: what 3
07-21 16:01:52.285  3675  3785 D EntConnectivity: Not allowed due to - mEnabled false
07-21 16:01:52.285  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.286  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:52.286  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:52.286  4528  4604 D GeolocationController: WIFI : onLost
07-21 16:01:52.287  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.287  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.291  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:52.291  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:52.291  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:52.291  3675  3956 D ConnectivityService: sending notification LOST for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:01:52.292  3675  3956 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.292  3675  5113 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachi,ne$SmHandler }
07-21 16:01:52.292  3675  3921 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.292  3675  5113 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: unregister CaptivePortalReceiver
07-21 16:01:52.292  3675  3921 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:01:52.292  3675  3921 D WIFI_P2P: evalRequest
07-21 16:01:52.292  3675  3921 D WIFI_P2P:   done
07-21 16:01:52.292 10298 10298 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
07-21 16:01:52.293  3675  4021 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.293  3675  4021 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-21 16:01:52.293  3675  4021 D Ethernet: evalRequest
07-21 16:01:52.293  3675  4021 D Ethernet:   done
07-21 16:01:52.293  4041  4041 D PhoneSwitcherNetworkRequstListener: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.293  3291  3777 D CommandListener: Clearing all IP addresses on wlan0
07-21 16:01:52.293  4041  4041 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-21 16:01:52.293  4041  4041 D PhoneSwitcherNetworkRequstListener: evalRequest
07-21 16:01:52.293  4041  4041 D PhoneSwitcherNetworkRequstListener:   done
07-21 16:01:52.297 10179 10179 D LocalBluetoothProfileManager: Adding local Spp profile
07-21 16:01:52.315 10298 10298 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:52.323 10179 10179 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-21 16:01:52.329  3241  3241 E audit   : type=1320 audit(1500645712.316:534): 
07-21 16:01:52.330 10179 10179 D A2dpProfile: Bluetooth service connected
,07-21 16:01:52.331  3675  3925 E SLocation: pendingIntent set to null
,07-21 16:01:52.331  3675  3925 D SLocation: setStatus ID = 1 / status = 0
07-21 16:01:52.331  3675  3925 D SLocation: updateSession : trigger = false
07-21 16:01:52.331  3675  3925 D SLocation: updateSession : mSessionStatus = 0
07-21 16:01:52.331  3675  3925 D WifiStateMachine:  stopGeofence() - id : 1
07-21 16:01:52.332  3675  3925 D wifi    : android_net_wifi_reset_alert_handler = 0x798fee2520
07-21 16:01:52.332  3675  4488 D SLocation: Session stopped
07-21 16:01:52.332  3675  3925 E WifiHAL : failed to request reset; result = -95
07-21 16:01:52.332  3675  3925 D wifi    : android_net_wifi_reset_log_handler = 0x798fee2520
07-21 16:01:52.332  3675  3925 I WifiHAL : Failed to remove command 1: 0x0
07-21 16:01:52.332  3675  4488 D SLocation: triggerAlarm
07-21 16:01:52.332  3675  3925 D WifiHAL : Success to clear alerthandler
07-21 16:01:52.332  3675  4488 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / op:PendingIntent{54206fc: PendingIntentRecord{e25f185 android broadcastIntent}}
07-21 16:01:52.333  3675  4488 D SLocation: All alarm stopped
,07-21 16:01:52.337  3675  3719 D RCPManagerService: exchangeData() failure , invalid userId
,07-21 16:01:52.337  3675  3925 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-21 16:01:52.338  3675  3925 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.338  3675  3925 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:01:52.338  3675  3925 D WIFI    : evalRequest
07-21 16:01:52.338  3675  3925 D WIFI    :   needNetworkFor
07-21 16:01:52.338  3675  3925 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:01:52.338  3675  3925 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:01:52.338  3675  3925 D WIFI_UT : evalRequest
,07-21 16:01:52.338  3675  3925 D WIFI_UT :   done
07-21 16:01:52.338  3675  3921 D WifiP2pService: InactiveState{ what=131204 }
07-21 16:01:52.338  3675  3921 D WifiP2pService: P2pEnabledState{ what=131204 }
07-21 16:01:52.341 10217 10294 D A2dpStateMachine: getConnectedDevices : size=0
07-21 16:01:52.342 10179 10179 D BluetoothMap: Proxy object connected
07-21 16:01:52.342  3675  3954 I WifiScanningService: wifi driver unloaded
07-21 16:01:52.343  3675  3954 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.scanner.SupplicantWifiScannerImpl$2@79c8bda
07-21 16:01:52.343  3675  3675 D RttService: SCAN_AVAILABLE : 1
,07-21 16:01:52.343  3291  3769 I Netd    : Destroyed 19 sockets on 192.168.1.105 in 1.4 ms
07-21 16:01:52.344  4735  6889 V NativeCrypto: Read error: ssl=0x79afcdda00: I/O error during system call, Software caused connection abort
,07-21 16:01:52.344 10179 10179 D MapProfile: Bluetooth service connected
07-21 16:01:52.344 10179 10179 D BluetoothMap: getConnectedDevices()
07-21 16:01:52.348  3675  3955 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:01:52.349  3241  3241 E audit   : type=1320 audit(1500645712.336:535): 
,07-21 16:01:52.353  4735  6889 V NativeCrypto: SSL shutdown failed: ssl=0x79afcdda00: I/O error during system call, Broken pipe
,07-21 16:01:52.354  4268  4268 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-21 16:01:52.354  4268  4268 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
07-21 16:01:52.356  3675  3921 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-21 16:01:52.357  3675  4177 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{4e0280b: PendingIntentRecord{6bc9329 com.google.android.gms broadcastIntent}}
07-21 16:01:52.358  3675  4177 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161841, SetElapsed=1219386, nowELAPSED=210139
07-21 16:01:52.360  3675  3786 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
07-21 16:01:52.364  4735  6889 E GCM     : Wifi connection closed with errorCode 20
,07-21 16:01:52.367 10298 10298 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
07-21 16:01:52.367 10298 10298 I QBNRClientHelper: init SyncClientHelper : Email
07-21 16:01:52.368 10298 10298 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : EMAILFOLDER, 55LAYJm0O2, com.samsung.android.email.provider.service.sCloudBNRService2
07-21 16:01:52.368 10298 10298 I QBNRClientHelper: init SyncClientHelper : EMAILFOLDER
07-21 16:01:52.370  3675  3921 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-21 16:01:52.371  3675  3786 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-21 16:01:52.371  3675  3786 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-21 16:01:52.371  3675  3786 D WifiDisplayController: disconnect
07-21 16:01:52.371  3675  3786 D WifiDisplayAdapter: onFeatureStateChanged empty
07-21 16:01:52.373 10179 10179 D BluetoothPbap: Proxy object connected
07-21 16:01:52.373 10179 10179 D PbapServerProfile: Bluetooth service connected
07-21 16:01:52.373 10179 10179 D BluetoothInputDevice: Proxy object connected
07-21 16:01:52.373 10179 10179 D HidProfile: Bluetooth service connected
,07-21 16:01:52.377  3675  3786 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-21 16:01:52.378  3675  3921 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.379  3675  3921 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:52.380  3675  3921 D WifiP2pService: P2pDisablingState
07-21 16:01:52.380  3675  3786 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: false, roaming: false, metered: false]
07-21 16:01:52.380  3675  3921 D WifiP2pService: P2pDisablingState{ what=147458 }
07-21 16:01:52.381  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-21 16:01:52.381  3675  3921 D WifiP2pService: p2p socket connection lost
07-21 16:01:52.381  3675  3921 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.384  3675  3921 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:52.384  3675  3925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-21 16:01:52.385  3675  3921 D WifiP2pService: P2pDisabledState
07-21 16:01:52.386  3675  3921 D WifiP2pService: P2pDisabledState{ what=143375 }
07-21 16:01:52.386  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-21 16:01:52.386  3675  3921 D WifiP2pService: DefaultState{ what=143375 }
07-21 16:01:52.386  3675  4012 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-21 16:01:52.391  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-21 16:01:52.392  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
07-21 16:01:52.393  3675  3925 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-21 16:01:52.394  3675  3925 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.394  4268  4268 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-21 16:01:52.394  3675  3675 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-21 16:01:52.395  3675  3925 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:52.396  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-21 16:01:52.397  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-21 16:01:52.397  3675  3952 I WifiHs20Service: Message received 5007
07-21 16:01:52.399  3291  3777 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-21 16:01:52.402  4041  4041 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-21 16:01:52.403  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-21 16:01:52.405 10179 10179 D DockEventReceiver: finishStartingService: stopping service
07-21 16:01:52.407  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:01:52.416  3241  3241 E audit   : type=1320 audit(1500645712.406:536): 
,07-21 16:01:52.421  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-21 16:01:52.424  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-21 16:01:52.424  3675  4012 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-21 16:01:52.424  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-21 16:01:52.425  3675  3952 I WifiHs20Service: Message received 5011
07-21 16:01:52.425  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:01:52.425  3675  3675 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-21 16:01:52.425  3675  4488 D SLocation: checkWifiInfo
07-21 16:01:52.426  3675  4488 D SLocation: wifi available : false
07-21 16:01:52.426  3675  4488 D SLocation: Session stopped
07-21 16:01:52.426  3241  3241 E audit   : type=1320 audit(1500645712.416:537): 
07-21 16:01:52.426  3675  4488 D SLocation: triggerAlarm
07-21 16:01:52.426  3675  4488 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / op:PendingIntent{54206fc: PendingIntentRecord{e25f185 android broadcastIntent}}
,07-21 16:01:52.426  3675  4488 D SLocation: All alarm stopped
07-21 16:01:52.427  3291  3777 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-21 16:01:52.432  3675  4038 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-21 16:01:52.432 10094 10094 D BluetoothAdapter: STATE_ON
07-21 16:01:52.432  3675  3956 D ConnectivityService: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
07-21 16:01:52.432  3675  3956 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-21 16:01:52.434  3675  3675 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-21 16:01:52.435 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-21 16:01:52.440  3675  4988 D RCPManagerService: exchangeData() failure , invalid userId
07-21 16:01:52.443  3675  4038 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-21 16:01:52.444  3675  3785 D EntConnectivity: Not allowed due to - mEnabled false
07-21 16:01:52.444 10094 10094 D BluetoothAdapter: STATE_ON
07-21 16:01:52.448  3675  3675 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-21 16:01:52.448  3675  3675 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = true
07-21 16:01:52.449  3675  3675 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-21 16:01:52.449  3675  3675 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-21 16:01:52.449  3675  3912 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
,07-21 16:01:52.449  3675  3912 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-21 16:01:52.450 10298 10317 D skia    : ---- fAsset->read(8192) returned 0
07-21 16:01:52.450 10298 10317 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-21 16:01:52.450 10094 10094 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
07-21 16:01:52.451  3675  3913 I KnoxVpnEngineService: vpn handle : Message received
07-21 16:01:52.451  3675  3675 D Tethering: Tethering got CONNECTIVITY_ACTION
07-21 16:01:52.451  3675  3958 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-21 16:01:52.452  3675  3958 D Tethering: MasterInitialState.processMessage what=327683
07-21 16:01:52.451  3675  3913 I KnoxVpnEngineService: vpn handle : Message received
,07-21 16:01:52.454  3675 10318 I ApplicationPolicy: updateDataUsageMap
07-21 16:01:52.454  3675  3913 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = true
07-21 16:01:52.458  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:01:52.462  3291  3769 D Netd    : Iface p2p0 link up
07-21 16:01:52.464  3675  3784 D Tethering: interfaceLinkStateChanged p2p0, true
07-21 16:01:52.464  3675  3784 D Tethering: interfaceStatusChanged p2p0, true
07-21 16:01:52.472  3241  3241 E audit   : type=1320 audit(1500645712.466:538): 
07-21 16:01:52.472  3675  3916 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
07-21 16:01:52.472  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:01:52.473  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:01:52.473  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:01:52.473  3675  3916 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-21 16:01:52.473  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
,07-21 16:01:52.475  3675  3916 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
,07-21 16:01:52.478  5251  5251 I CastMediaRouteProvider: Network connectivity changed
,07-21 16:01:52.481 10298 10317 D skia    : ---- fAsset->read(8192) returned 0
07-21 16:01:52.481 10298 10317 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-21 16:01:52.483 10298 10317 D skia    : ---- fAsset->read(8192) returned 0
07-21 16:01:52.483 10298 10317 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-21 16:01:52.484  3241  3241 E audit   : type=1320 audit(1500645712.476:539): 
,07-21 16:01:52.487  9398  9398 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-21 16:01:52.487  9398  9398 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
,07-21 16:01:52.490  9459  9459 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@a2e50cb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-21 16:01:52.509  4268  4268 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-21 16:01:52.515  4268  4268 E wpa_supplicant: can't get BSS information
07-21 16:01:52.516  4268  4268 I wpa_supplicant: CTRL_IFACE: Detach monitor that cannot receive messages: /data/misc/wifi/sockets/wpa_ctrl_3675-2\x00
07-21 16:01:52.516  4268  4268 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.E6.C2 reason=3 locally_generated=1
,07-21 16:01:52.525  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:01:52.532  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:01:52.532  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
07-21 16:01:52.533  3675  4946 D MountService: getExternalStorageMountMode : 1
07-21 16:01:52.533  3675  4946 D MountService: getExternalStorageMountMode : 3
07-21 16:01:52.533  3675  4946 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
07-21 16:01:52.534 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:52.535 10298 10298 D SamsungAnalytics:1.8.25: cf feature is supported
07-21 16:01:52.539  4959  4959 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-21 16:01:52.540  9398  9398 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
07-21 16:01:52.544 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:52.546  9398  9398 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
07-21 16:01:52.546 10298 10298 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
07-21 16:01:52.546  9459  9459 I NetworkConnectivity: Network state changed: null
07-21 16:01:52.547  9398  9398 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-21 16:01:52.551  3291  3777 E Netd    : netlink response contains error (No such file or directory)
07-21 16:01:52.559  3675  3956 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED
07-21 16:01:52.559  3675  3956 D ConnectivityService: ignoring duplicate network state non-change
07-21 16:01:52.559  4068  4289 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
,07-21 16:01:52.569  3675  4946 I ActivityManager: Start proc 10330:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
07-21 16:01:52.569 10330 10330 E Zygote  : v2
07-21 16:01:52.569 10330 10330 I libpersona: KNOX_SDCARD checking this for 10049
07-21 16:01:52.569 10330 10330 I libpersona: KNOX_SDCARD not a persona
07-21 16:01:52.570 10330 10330 E Zygote  : isSdpEnabledProcess - SDP enabled
07-21 16:01:52.570 10330 10330 E Zygote  : accessInfo : 64
07-21 16:01:52.570 10330 10330 E Zygote  : isSdpEnabledProcess - SDP enabled
07-21 16:01:52.570 10330 10330 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
07-21 16:01:52.572  9459  9459 I NetworkPolicyMonitor: Download-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
07-21 16:01:52.575  3675  3675 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-21 16:01:52.575  3675  3675 V MARsPolicyManager: DataConnection: false
07-21 16:01:52.575  3675  4488 D SLocation: checkWifiInfo
07-21 16:01:52.576  3675  4488 W SLocation: No Active Data Connection
07-21 16:01:52.576 10330 10330 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-21 16:01:52.577 10330 10330 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
07-21 16:01:52.577  3675  4038 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-21 16:01:52.582  3675  4038 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-21 16:01:52.592  9459  9459 I NetworkPolicyMonitor: Stream-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
,07-21 16:01:52.598  5251  5827 W MdnsClient_Cast: Multicast lock held. Releasing. Subtypes:"805741C9"
07-21 16:01:52.600 10330 10330 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:52.600 10330 10330 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:52.602  3675  4177 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,07-21 16:01:52.603  5251  5827 W MdnsClient: unicast receiver thread is already dead.
,07-21 16:01:52.618  4068  4068 D HeadsetProfile: Bluetooth service connected
07-21 16:01:52.619  3675  3675 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.bluetooth.SecBluetoothMessageListener@76739e7
07-21 16:01:52.619  3675  3675 D BluetoothHeadset: registerMessageListener
07-21 16:01:52.621 10217 10217 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-21 16:01:52.623 10217 10294 D HeadsetService: registerMessageListener
07-21 16:01:52.623 10217 10294 D HeadsetService: registerMessageListener
07-21 16:01:52.623 10217 10274 D HeadsetStateMachine: Disconnected process message: 70, size: 0
,07-21 16:01:52.623  3675  3675 I Telecom : SecBluetoothManager : register MessageListener
07-21 16:01:52.624 10217 10274 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@a1afe49
07-21 16:01:52.624 10217 10217 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:01:52.624 10217 10217 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:01:52.631 10179 10179 D HeadsetProfile: Bluetooth service connected
07-21 16:01:52.632 10217 10288 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
07-21 16:01:52.634 10217 10217 D BluetoothUtils: readSalesCode :: sales code is XEO
07-21 16:01:52.638 10330 10330 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
07-21 16:01:52.641  3291  3772 D EnterpriseController: netId is 0
07-21 16:01:52.642  3291  3772 D Netd    : getNetworkForDns: using netid 0 for uid 10001
07-21 16:01:52.642  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-21 16:01:52.642 10217 10288 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:01:52.642 10217 10288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:01:52.649 10330 10330 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:52.653 10179 10179 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-21 16:01:52.653 10179 10179 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
07-21 16:01:52.655  5235 10335 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
07-21 16:01:52.655  5235 10335 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-21 16:01:52.655  5235 10335 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-21 16:01:52.655  5235 10335 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-21 16:01:52.655  5235 10335 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-21 16:01:52.655  5235 10335 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-21 16:01:52.655  5235 10335 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-21 16:01:52.655  5235 10335 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-21 16:01:52.655  5235 10335 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-21 16:01:52.655  5235 10335 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-21 16:01:52.655  5235 10335 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-21 16:01:52.655  5235 10335 E         : 	at java.lang.Thread.run(Thread.java:762)
07-21 16:01:52.655  5235 10335 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-21 16:01:52.655  5235 10335 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-21 16:01:52.655  5235 10335 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-21 16:01:52.655  5235 10335 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-21 16:01:52.655  5235 10335 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-21 16:01:52.655  5235 10335 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-21 16:01:52.655  5235 10335 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-21 16:01:52.655  5235 10335 E         : 	... 9 more
07-21 16:01:52.655  5235 10335 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associat,ed with hostname)
07-21 16:01:52.655  5235 10335 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-21 16:01:52.655  5235 10335 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-21 16:01:52.655  5235 10335 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-21 16:01:52.655  5235 10335 E         : 	... 26 more
07-21 16:01:52.655  5235 10335 E         : 
07-21 16:01:52.658  3675  3675 I Telecom : SecBluetoothManager : not single connected gear
07-21 16:01:52.659  4268  4268 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
07-21 16:01:52.667  5235 10335 E         : Unable to fetch advertisement frequency.
07-21 16:01:52.667  5235 10335 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-21 16:01:52.667  5235 10335 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-21 16:01:52.667  5235 10335 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-21 16:01:52.667  5235 10335 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-21 16:01:52.667  5235 10335 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-21 16:01:52.667  5235 10335 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-21 16:01:52.667  5235 10335 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-21 16:01:52.667  5235 10335 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-21 16:01:52.667  5235 10335 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-21 16:01:52.667  5235 10335 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-21 16:01:52.667  5235 10335 E         : 	at java.lang.Thread.run(Thread.java:762)
07-21 16:01:52.667  5235 10335 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-21 16:01:52.667  5235 10335 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-21 16:01:52.667  5235 10335 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-21 16:01:52.667  5235 10335 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-21 16:01:52.667  5235 10335 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-21 16:01:52.667  5235 10335 E ,        : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-21 16:01:52.667  5235 10335 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-21 16:01:52.667  5235 10335 E         : 	... 9 more
07-21 16:01:52.667  5235 10335 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-21 16:01:52.667  5235 10335 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-21 16:01:52.667  5235 10335 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-21 16:01:52.667  5235 10335 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-21 16:01:52.667  5235 10335 E         : 	... 26 more
07-21 16:01:52.667  5235 10335 E         : 
07-21 16:01:52.669  3675  3675 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-21 16:01:52.669  3675  3675 I BluetoothPhoneService: updateHeadsetWithCallState : true
07-21 16:01:52.671  3675  4565 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
07-21 16:01:52.671  3675  4565 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
07-21 16:01:52.672 10217 10288 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:01:52.673 10217 10288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:01:52.673  3675  4565 I Telecom : SecBluetoothManager : not single connected gear
07-21 16:01:52.674  3675  4565 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
07-21 16:01:52.675 10217 10274 D HeadsetStateMachine: Disconnected process message: 9, size: 0
07-21 16:01:52.675 10217 10274 D A2dpSinkService: getA2dpSinkService(): service is NULL
07-21 16:01:52.676 10217 10274 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-21 16:01:52.677 10217 10347 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:01:52.677 10217 10347 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:01:52.680  3278  3278 D audio_hw_primary: adev_set_parameters: enter: kvpairs: A2dpSuspended=false
07-21 16:01:52.680 10217 10347 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-21 16:01:52.680 10217 10347 D BluetoothSdpJni: SDP Create record success - handle: 0
07-21 16:01:52.681 10217 10274 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-21 16:01:52.682 10217 10217 V BtOppService: isOwner == true
07-21 16:01:52.688  4735  6873 I BeaconBle: Client requested scan, settings=BleSettings [scanMode=LOW_LATENCY, callbackType=ALL_MATCHES, reportDelayMillis=0, 3 filters, 0 clients, callingClientName=Nearby], listener=hjz@2adafef
07-21 16:01:52.690 10094 10177 D BluetoothAdapter: STATE_ON
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-21 16:01:52.692 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-21 16:01:52.694 10217 10288 D ObexServerSockets: Succeed to create listening sockets 
07-21 16:01:52.694 10217 10288 D ObexServerSockets: startAccept()
07-21 16:01:52.697 10217 10288 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-21 16:01:52.697 10217 10348 D ObexServerSockets: Accepting socket connection for masId0
07-21 16:01:52.697 10094 10157 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:52.697 10217 10349 D ObexServerSockets: Accepting socket connection for masId0
07-21 16:01:52.697 10217 10288 D BluetoothSdpJni: SDP Create record success - handle: 1
07-21 16:01:52.699  9459  9459 I DevicePlayback: Got network change: mobile=falsewifi=false
07-21 16:01:52.699  9459  9459 I DevicePlayback: Disabling Woodstock in 200000ms
07-21 16:01:52.704  3675  3988 D WifiService: setWifiEnabled: true pid=10094, uid=10033
07-21 16:01:52.705  3675  3988 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-21 16:01:52.705  3675  3988 D WifiControlHistoryProvider: query
07-21 16:01:52.705  3675  4946 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-21 16:01:52.708  3675  4946 D SecContentProvider: called from android.uid.bluetooth:1002
07-21 16:01:52.709  3291  3769 D Netd    : Iface wlan0 link up
07-21 16:01:52.709  3291  3769 D Netd    : Iface wlan0 link up
07-21 16:01:52.710  4268  4268 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-21 16:01:52.710  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:01:52.710  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
07-21 16:01:52.711  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:01:52.711  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
07-21 16:01:52.716  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-21 16:01:52.716 10217 10353 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:01:52.716 10217 10353 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:01:52.717  3675  3988 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-21 16:01:52.718  3675  3988 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:52.718  3675  3988 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-21 16:01:52.720  3675  3988 I WifiService: Wi-Fi Sharing settings has not been accessed
07-21 16:01:52.721  3675  3988 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-21 16:01:52.721  3675  3924 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.722  3675  3924 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:52.723  3675  3924 D SecContentProvider: insert(), uri = 2
07-21 16:01:52.724 10217 10353 I BtOppRfcommListener: Accept thread started.
07-21 16:01:52.726 10330 10354 D skia    : ---- fAsset->read(8192) returned 0
07-21 16:01:52.726 10330 10354 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-21 16:01:52.730 10330 10354 D skia    : ---- fAsset->read(8192) returned 0
07-21 16:01:52.730 10330 10354 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-21 16:01:52.730  3675  4987 D RCPManagerService: exchangeData() failure , invalid userId
07-21 16:01:52.730  3675  3924 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:52.731 10330 10354 D skia    : ---- fAsset->read(8192) returned 0
07-21 16:01:52.731 10330 10354 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-21 16:01:52.739 10330 10330 D SamsungAnalytics:1.8.25: cf feature is supported
07-21 16:01:52.743 10330 10330 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
,07-21 16:01:52.780  4735  6873 I BeaconBle: 'L' hardware scan: 3 filters, scanMode=2, reportdelay=0, callback type=1, #clients=1
07-21 16:01:52.785  4735  6873 I BeaconBle: Starting scan on delegate scanner - BT state: 12
07-21 16:01:52.785  4735  6873 D BluetoothLeScanner: Start Scan
07-21 16:01:52.786  4735  6873 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.787  4735  6873 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.790  4735  6873 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.794  4735  6873 D BluetoothAdapter: STATE_ON
,07-21 16:01:52.802  4068  4209 D vol.MediaSessions: onQueueChanged com.google.android.music []
,07-21 16:01:52.923  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-21 16:01:52.931  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-21 16:01:52.932  3675  3782 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-21 16:01:52.952 10217 10228 D BtGatt.GattService: registerClient() - UUID=c74ed368-f05a-4e5e-830d-0cd1e47cd065
,07-21 16:01:52.962  3675  3988 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BleCentralService newState = 1 callingPackage = 10019
,07-21 16:01:52.972  3675  4177 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BlePeripheralService newState = 1 callingPackage = 10019
07-21 16:01:52.977  3675  3925 D wifi    : In wifi stop Hal
07-21 16:01:52.977  3675  3925 D wifi    : halHandle = 0x798fe610e0, mVM = 0x79bd490300, mCls = 0x101042
07-21 16:01:52.977  3675  4267 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-21 16:01:52.977  3675  4267 D WifiHAL : Got a signal to exit!!!
07-21 16:01:52.977  3675  4267 I WifiHAL : Exit wifi_event_loop
07-21 16:01:52.978  3675  3925 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-21 16:01:52.978  3675  3925 E WifiHAL : Event processing terminated
07-21 16:01:52.982  5251  6667 I Authzen : [PermitStore] Getting all permits...
,07-21 16:01:52.986  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-21 16:01:52.987  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-21 16:01:52.988  3675  3951 D HS20StateMachine: WIFI_STATE_DISABLED
07-21 16:01:52.988  3675  3951 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
,07-21 16:01:52.989  3675  3952 I WifiHs20Service: Message received 5011
,07-21 16:01:52.989  3291  3769 D Netd    : Iface p2p0 link down
07-21 16:01:52.992  3675  3784 D Tethering: interfaceLinkStateChanged p2p0, false
07-21 16:01:52.992  3675  3784 D Tethering: interfaceStatusChanged p2p0, false
07-21 16:01:52.995  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-21 16:01:53.000  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:01:53.000  3675  3675 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-21 16:01:53.000  3675  4488 D SLocation: checkWifiInfo
,07-21 16:01:53.002  3675  4038 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-21 16:01:53.005 10217 10217 D A2dpService: A2dpService - WIFI_STATE_DISABLED
07-21 16:01:53.005 10217 10217 I BluetoothA2dpServiceJni: Attempting to set busy level
07-21 16:01:53.006  4735  5314 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-21 16:01:53.007 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:53.015  3675  4038 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-21 16:01:53.021  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:53.021  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:53.021  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:53.021  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:53.021  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:53.022  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:53.022  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:53.022  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:53.022  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:53.022  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:53.048 10179 10179 I WifiApBroadcastReceiver: onReceive: action com.samsung.intent.action.START_PROVISIONING userID :0
,07-21 16:01:53.056  3675  4987 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-21 16:01:53.059  3675  3925 D wifi    : In wifi cleaned up handler
,07-21 16:01:53.059  3675  3925 I WifiHAL : Internal cleanup completed
,07-21 16:01:53.061  3675  4987 D MountService: getExternalStorageMountMode : 1
07-21 16:01:53.061  3675  4987 D MountService: getExternalStorageMountMode : 3
07-21 16:01:53.061  3675  4987 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10106, packageName : com.enhance.gameservice
,07-21 16:01:53.064 10217 10237 D BtGatt.GattService: onClientRegistered() - UUID=c74ed368-f05a-4e5e-830d-0cd1e47cd065, clientIf=5, status=0
07-21 16:01:53.065  4735  6872 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,07-21 16:01:53.066 10217 10295 D BtGatt.GattService: start scan with filters
,07-21 16:01:53.069 10217 10295 D BtGatt.GattService: getScanSettings
,07-21 16:01:53.085 10370 10370 E Zygote  : v2
07-21 16:01:53.085 10370 10370 I libpersona: KNOX_SDCARD checking this for 10106
07-21 16:01:53.085 10370 10370 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:53.086 10370 10370 E Zygote  : accessInfo : 0
,07-21 16:01:53.092  3675  4987 I ActivityManager: Start proc 10370:com.enhance.gameservice/u0a106 for broadcast com.enhance.gameservice/.GameServiceReceiver
,07-21 16:01:53.094  4735  6871 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
07-21 16:01:53.094 10217 10295 D BtGatt.GattService: Is it foreground application = false
07-21 16:01:53.094 10217 10295 D BtGatt.GattService: Its third party background application, change scanmode to low power
,07-21 16:01:53.096 10370 10370 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:53.098 10370 10370 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.enhance.gameservice 
,07-21 16:01:53.102 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_START_SCAN
,07-21 16:01:53.102 10217 10255 D BtGatt.ScanManager: handling starting scan
07-21 16:01:53.103 10217 10255 D BtGatt.ScanManager: isFilteringSupported
07-21 16:01:53.103 10217 10255 D BluetoothAdapter: enableStandAloneBleMode=
07-21 16:01:53.104 10217 10255 D BluetoothAdapter: STATE_ON
07-21 16:01:53.105 10217 10255 D BluetoothAdapter: STATE_ON
,07-21 16:01:53.106 10217 10255 D BluetoothAdapter: STATE_ON
,07-21 16:01:53.107 10217 10255 D BluetoothAdapter: STATE_ON
,07-21 16:01:53.108 10217 10255 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
,07-21 16:01:53.110 10217 10255 D BluetoothAdapter: STATE_ON
,07-21 16:01:53.111 10217 10255 D BluetoothAdapter: STATE_ON
,07-21 16:01:53.118 10217 10237 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-21 16:01:53.118 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-21 16:01:53.119 10217 10255 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
07-21 16:01:53.119 10217 10255 D BtGatt.ScanManager: addFilterToController: 5
,07-21 16:01:53.124 10217 10237 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=47
07-21 16:01:53.124 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:01:53.124 10217 10255 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-21 16:01:53.125 10217 10255 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-21 16:01:53.125 10217 10255 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
07-21 16:01:53.125 10370 10370 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:53.126 10370 10370 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:53.128  3675  4988 I ActivityManager: DSS on for com.enhance.gameservice and scale is 1.0
,07-21 16:01:53.131 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-21 16:01:53.131 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-21 16:01:53.132 10217 10255 D BtGatt.ScanManager: set filter index= 4 for clientIf= 5
07-21 16:01:53.132 10217 10255 D BtGatt.ScanManager: addFilterToController: 5
,07-21 16:01:53.136 10217 10237 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=46
07-21 16:01:53.136 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:01:53.137 10217 10255 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-21 16:01:53.137 10217 10255 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-21 16:01:53.137 10217 10255 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,07-21 16:01:53.144 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=30
07-21 16:01:53.144 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:01:53.144 10217 10255 D BtGatt.ScanManager: set filter index= 5 for clientIf= 5
07-21 16:01:53.144 10217 10255 D BtGatt.ScanManager: addFilterToController: 2
,07-21 16:01:53.152 10217 10237 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=45
07-21 16:01:53.153 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:01:53.153 10217 10255 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-21 16:01:53.153 10217 10255 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-21 16:01:53.153 10217 10255 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,07-21 16:01:53.153 10370 10370 W System  : ClassLoader referenced unknown path: /system/app/GameOptimizer/lib/arm64
,07-21 16:01:53.157 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=29
07-21 16:01:53.158 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:01:53.158 10217 10255 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-21 16:01:53.159 10217 10255 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=0 mLastConfiguredScanSetting=-2147483648
07-21 16:01:53.159 10217 10255 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 800
,07-21 16:01:53.161 10217 10237 D BtGatt.GattService: onScanParamSetupCompleted() status=0, clientIf=5
07-21 16:01:53.161 10217 10237 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-21 16:01:53.165 10370 10370 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:53.173  3675  4982 D MountService: getExternalStorageMountMode : 3
07-21 16:01:53.173  3675  4982 D MountService: getExternalStorageMountMode : 3
07-21 16:01:53.174  3675  4982 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 5017, packageName : com.samsung.android.radiobasedlocation
,07-21 16:01:53.195 10384 10384 E Zygote  : v2
07-21 16:01:53.195 10384 10384 I libpersona: KNOX_SDCARD checking this for 5017
07-21 16:01:53.195 10384 10384 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:53.196 10384 10384 E Zygote  : accessInfo : 0
,07-21 16:01:53.201  3675  4982 I ActivityManager: Start proc 10384:com.samsung.android.radiobasedlocation/5017 for broadcast com.samsung.android.radiobasedlocation/.RblServiceReceiver
,07-21 16:01:53.205  3675  4982 I ActivityManager: KPU : put [com.samsung.android.app.mirrorlink] : 21252 K
07-21 16:01:53.205  3675  4982 I ActivityManager: Killing 9348:com.samsung.android.app.mirrorlink/1000 (adj 906): DHA:empty #33
07-21 16:01:53.206 10384 10384 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:53.208 10384 10384 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.radiobasedlocation 
,07-21 16:01:53.225  3675  4544 D ActivityManager: cleanUpApplicationRecord -- 9348
,07-21 16:01:53.226  4768  6456 D ForegroundUtils: could not check pending caller
07-21 16:01:53.227  3675  4942 D WifiService: setWifiEnabled: true pid=10094, uid=10033
,07-21 16:01:53.228  3675  4942 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-21 16:01:53.229  3675  4942 D WifiControlHistoryProvider: query
,07-21 16:01:53.234 10384 10384 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:53.235 10384 10384 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:53.235  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:01:53.235  3675  4942 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-21 16:01:53.237  3675  4942 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:53.237  3675  4946 I ActivityManager: DSS on for com.samsung.android.radiobasedlocation and scale is 1.0
,07-21 16:01:53.237  3675  4942 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-21 16:01:53.240  3675  4942 I WifiService: Wi-Fi Sharing settings has not been accessed
07-21 16:01:53.241  3675  4942 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-21 16:01:53.241  3675  3924 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-21 16:01:53.262 10384 10384 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-21 16:01:53.264 10384 10384 W System  : ClassLoader referenced unknown path: /system/priv-app/RadioBasedLocation/lib/arm64
,07-21 16:01:53.280 10384 10384 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:53.290 10384 10384 I [RBL] PathProvider: @onCreate
,07-21 16:01:53.296 10384 10384 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-21 16:01:53.315  3675  4865 I ActivityManager: KPU : put [com.samsung.android.sm.provider] : 28392 K
07-21 16:01:53.315  3675  4865 I ActivityManager: Killing 9127:com.samsung.android.sm.provider/1000 (adj 906): DHA:empty #33
,07-21 16:01:53.332  3675  4865 D MountService: getExternalStorageMountMode : 1
07-21 16:01:53.332  3675  4865 D MountService: getExternalStorageMountMode : 3
07-21 16:01:53.332  3675  4865 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.diagmonagent
,07-21 16:01:53.361 10398 10398 E Zygote  : v2
07-21 16:01:53.361 10398 10398 I libpersona: KNOX_SDCARD checking this for 1000
07-21 16:01:53.361 10398 10398 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:53.362 10398 10398 E Zygote  : accessInfo : 0
,07-21 16:01:53.365  3675  4865 I ActivityManager: Start proc 10398:com.sec.android.diagmonagent/1000 for broadcast com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,07-21 16:01:53.366  3675  3720 D ActivityManager: cleanUpApplicationRecord -- 9127
,07-21 16:01:53.372 10398 10398 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:53.374 10398 10398 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.diagmonagent 
,07-21 16:01:53.375  4768  6456 D ForegroundUtils: could not check pending caller
,07-21 16:01:53.400 10398 10398 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:53.400 10398 10398 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:53.402  3675  4946 I ActivityManager: DSS on for com.sec.android.diagmonagent and scale is 1.0
,07-21 16:01:53.427 10398 10398 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,07-21 16:01:53.446 10398 10398 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:53.467 10398 10398 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-21 16:01:53.513 10398 10398 E SQLiteLog: (1) no such column: currentid
,07-21 16:01:53.514 10398 10398 E DIAGMON_AGENT: [llllIIIIlllIIIlIllIl(906/lllIlIlIIIllIIlIllIl)] android.database.sqlite.SQLiteException: no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1
07-21 16:01:53.514 10398 10398 E DIAGMON_AGENT: #################################################################
07-21 16:01:53.514 10398 10398 E DIAGMON_AGENT: Error Code : 1 (SQLITE_ERROR)
07-21 16:01:53.514 10398 10398 E DIAGMON_AGENT: Caused By : SQL(query) error or missing database.
07-21 16:01:53.514 10398 10398 E DIAGMON_AGENT: 	(no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1)
07-21 16:01:53.514 10398 10398 E DIAGMON_AGENT: #################################################################
,07-21 16:01:53.551 10398 10398 E SQLiteLog: (1) table profilelist has no column named currentid
,07-21 16:01:53.552 10398 10398 E SQLiteDatabase: Error inserting number=0 len=0 profilename3=Mformation notiretrycount=0 currentid=-1 size=0 oplevel=0 serviceid= appid=0 profilename2=dm-Server notievent=0 sessionid=null profilename1=api-server status=0 uictype=0 text= holdingid=-1 sessionsavestate=0 profileindex=0 opmode= result=0 pushjobid= notiuievent=0
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: android.database.sqlite.SQLiteException: table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: #################################################################
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: Error Code : 1 (SQLITE_ERROR)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: Caused By : SQL(query) error or missing database.
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	(table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?))
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: #################################################################
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1005)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.prepare(SQLiteConnection.java:570)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:588)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:59)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1771)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1643)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:667)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:399)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:116)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:60)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1032)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5885)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap3(ActivityThread.java)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1703)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:154)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6692)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke,(Native Method)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1468)
07-21 16:01:53.552 10398 10398 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1358)
,07-21 16:01:53.579  3675  4491 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / op:PendingIntent{e6d5f52: PendingIntentRecord{308c223 android broadcastIntent}}
,07-21 16:01:53.586  3675  4491 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170722T160153 - CU:1000/CP:3675
,07-21 16:01:53.588 10398 10398 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(64/onCreate)] nStatus : 0
,07-21 16:01:53.595 10398 10398 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(77/onCreate)] DiagMon DM Application Start !
07-21 16:01:53.596 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-21 16:01:53.597 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-21 16:01:53.597 10398 10398 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-21 16:01:53.597 10398 10398 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-21 16:01:53.602  3675  3720 D MountService: getExternalStorageMountMode : 1
,07-21 16:01:53.602  3675  3720 D MountService: getExternalStorageMountMode : 3
07-21 16:01:53.602  3675  3720 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.app.RilErrorNotifier
,07-21 16:01:53.647 10411 10411 E Zygote  : v2
07-21 16:01:53.648 10411 10411 I libpersona: KNOX_SDCARD checking this for 1000
07-21 16:01:53.648 10411 10411 I libpersona: KNOX_SDCARD not a persona
07-21 16:01:53.649 10411 10411 E Zygote  : accessInfo : 0
,07-21 16:01:53.650  3675  3720 W ActivityManager: Slow operation: 51ms so far, now at startProcess: returned from zygote!
07-21 16:01:53.651  3675  3720 W ActivityManager: Slow operation: 52ms so far, now at startProcess: done updating battery stats
07-21 16:01:53.651  3675  3720 W ActivityManager: Slow operation: 52ms so far, now at startProcess: building log message
07-21 16:01:53.651  3675  3720 I ActivityManager: Start proc 10411:com.sec.app.RilErrorNotifier/1000 for broadcast com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
07-21 16:01:53.651  3675  3720 W ActivityManager: Slow operation: 52ms so far, now at startProcess: starting to update pids map
07-21 16:01:53.651  3675  3720 W ActivityManager: Slow operation: 52ms so far, now at startProcess: done updating pids map
07-21 16:01:53.652  3675  3720 W ActivityManager: Slow operation: 52ms so far, now at startProcess: done starting proc!
,07-21 16:01:53.658  3675  3720 I ActivityManager: KPU : put [com.samsung.android.sm.devicesecurity] : 27568 K
,07-21 16:01:53.658  3675  3720 I ActivityManager: Killing 7190:com.samsung.android.sm.devicesecurity/5012 (adj 906): DHA:empty #33
07-21 16:01:53.658 10411 10411 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:53.660 10411 10411 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.app.RilErrorNotifier 
,07-21 16:01:53.679  3291  3769 D Netd    : Iface wlan0 link down
,07-21 16:01:53.683  3675  4267 D wifi    : set interface wlan0 flags (DOWN)
07-21 16:01:53.683  3675  3925 D WifiNative-HAL: HAL event thread stopped successfully
,07-21 16:01:53.685  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, false
,07-21 16:01:53.685  3675  3784 D Tethering: interfaceStatusChanged wlan0, false
,07-21 16:01:53.689  3675  4865 D ActivityManager: cleanUpApplicationRecord -- 7190
,07-21 16:01:53.689 10411 10411 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:53.690 10411 10411 D ActivityThread: Added TimaKeyStore provider
07-21 16:01:53.691  4768  4787 D ForegroundUtils: could not check pending caller
07-21 16:01:53.694  3675  4931 I ActivityManager: DSS on for com.sec.app.RilErrorNotifier and scale is 1.0
,07-21 16:01:53.715 10411 10411 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,07-21 16:01:53.732 10411 10411 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:53.739 10411 10411 I PhoneErrorReceiver: onReceive
,07-21 16:01:53.749  3675  4865 D WifiService: setWifiEnabled: true pid=10094, uid=10033
,07-21 16:01:53.753  3675  4865 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-21 16:01:53.754  3675  4865 D WifiControlHistoryProvider: query
,07-21 16:01:53.755 10007 10007 I usagelog: received in receiver
,07-21 16:01:53.755 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-21 16:01:53.757 10007 10007 I KnoxUsageLogPro: premStatus:2
,07-21 16:01:53.760 10007 10007 I KnoxUsageLogPro: isEulaShown : false
07-21 16:01:53.760 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-21 16:01:53.767  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:01:53.768  3675  4543 D MountService: getExternalStorageMountMode : 1
07-21 16:01:53.768  3675  4543 D MountService: getExternalStorageMountMode : 3
07-21 16:01:53.768  3675  4543 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 5005, packageName : com.samsung.android.allshare.service.fileshare
,07-21 16:01:53.796 10425 10425 E Zygote  : v2
07-21 16:01:53.796 10425 10425 I libpersona: KNOX_SDCARD checking this for 5005
07-21 16:01:53.796 10425 10425 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:53.797 10425 10425 E Zygote  : accessInfo : 0
,07-21 16:01:53.803  3675  4543 I ActivityManager: Start proc 10425:com.samsung.android.allshare.service.fileshare/5005 for broadcast com.samsung.android.allshare.service.fileshare/.FileShareBroadcastReceiver
,07-21 16:01:53.804  3675  4865 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-21 16:01:53.805  3675  4865 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:53.806  3675  4865 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-21 16:01:53.808 10425 10425 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:53.810  3675  4865 I WifiService: Wi-Fi Sharing settings has not been accessed
07-21 16:01:53.810 10425 10425 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.allshare.service.fileshare 
07-21 16:01:53.810  3675  4865 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-21 16:01:53.810  3675  3924 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-21 16:01:53.812  3675  4543 I ActivityManager: KPU : put [com.samsung.android.themecenter] : 26740 K
,07-21 16:01:53.812  3675  4543 I ActivityManager: Killing 9385:com.samsung.android.themecenter/1000 (adj 906): DHA:empty #33
,07-21 16:01:53.837  3675  3920 D ActivityManager: cleanUpApplicationRecord -- 9385
,07-21 16:01:53.838  4768  4781 D ForegroundUtils: could not check pending caller
07-21 16:01:53.840 10425 10425 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:53.840 10425 10425 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:53.843  3675  4988 I ActivityManager: DSS on for com.samsung.android.allshare.service.fileshare and scale is 1.0
,07-21 16:01:53.885  3675  3925 E WifiHW  : ##################### set firmware type 0 #####################
,07-21 16:01:53.887  3291  3777 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-21 16:01:53.888  3291  3777 I WifiHW  : module is semco
07-21 16:01:53.888  3291  3777 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-21 16:01:53.888  3291  3777 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-21 16:01:53.888  3291  3777 E WifiHW  : TEMP_FAILURE_RETRY complete
,07-21 16:01:53.888  3291  3777 D SoftapController: Softap fwReload - Ok
07-21 16:01:53.889  3675  3925 E NetworkManagement: wifiFirmwareReload Error reloading wlan0 fw in STA mode: event = 200 216 Softap operation succeeded
,07-21 16:01:53.892 10425 10425 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:53.894  3291  3777 D CommandListener: Setting iface cfg
07-21 16:01:53.894  3291  3777 D CommandListener: Trying to bring down wlan0
,07-21 16:01:53.896  3291  3777 D CommandListener: Clearing all IP addresses on wlan0
,07-21 16:01:53.897 10425 10425 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-21 16:01:53.899 10425 10425 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
,07-21 16:01:53.902  3675  3925 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-21 16:01:53.917 10425 10425 D FileShare: Outbound.stopDelayTimer - 
,07-21 16:01:53.922  4735  6873 I BeaconBle: Client requested to stop, listener=hjz@2adafef
,07-21 16:01:53.937 10384 10384 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-21 16:01:53.947  3675  4177 I ActivityManager: KPU : put [com.samsung.svoice.sync] : 21260 K
,07-21 16:01:53.947  3675  4177 I ActivityManager: Killing 9417:com.samsung.svoice.sync/u0a40 (adj 906): DHA:empty #33
,07-21 16:01:53.954  4735  6873 I BeaconBle: Stopping scan on delegate scanner - BT state: 12
,07-21 16:01:53.960  4735  6873 D BluetoothAdapter: STATE_ON
,07-21 16:01:53.962 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-21 16:01:53.962  4735  6873 D BluetoothAdapter: STATE_ON
07-21 16:01:53.962  4735  6873 D BluetoothLeScanner: Stop Scan
07-21 16:01:53.962 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-21 16:01:53.963 10398 10398 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-21 16:01:53.964 10217 10229 D BtGatt.GattService: stopScan() - queue size =1
,07-21 16:01:53.964 10217 10229 D BtGatt.GattService: stopScan() - queue size =1
07-21 16:01:53.965 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_STOP_SCAN
,07-21 16:01:53.967 10217 10255 D BtGatt.ScanManager: stop scan
,07-21 16:01:53.967 10217 10255 D BtGatt.ScanManager: delete FilterIndex - 3
07-21 16:01:53.968 10217 10239 D BtGatt.GattService: unregisterClient() - clientIf=5
07-21 16:01:53.972  4735  6873 D BluetoothAdapter: STATE_ON
,07-21 16:01:53.974  4735  6873 D BluetoothAdapter: STATE_ON
07-21 16:01:53.974  4735  6873 I BeaconBle: Resetting - new scanner available: true
07-21 16:01:53.975  4735  6873 I BeaconBle: 'L' hardware scan: scan stopped, no clients
07-21 16:01:53.975  4735  6873 I BeaconBle: Scan canceled successfully.
,07-21 16:01:53.982  3675  4865 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{3a18a18: PendingIntentRecord{a6b4c71 com.google.android.gms broadcastIntent}}
07-21 16:01:53.982 10411 10411 I PhoneErrorReceiver: onReceive
,07-21 16:01:53.986  4735  6873 W NearbyMessages: Runnable[ScanComplete] not posted since EventLoop is destroyed
,07-21 16:01:53.991 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=30
07-21 16:01:53.991 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-21 16:01:53.992 10217 10255 D BtGatt.ScanManager: delete FilterIndex - 4
,07-21 16:01:53.997 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=31
,07-21 16:01:53.997 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:01:53.997 10217 10255 D BtGatt.ScanManager: delete FilterIndex - 5
07-21 16:01:54.000 10007 10007 I usagelog: received in receiver
07-21 16:01:54.000 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-21 16:01:54.000  3675  3939 D ActivityManager: cleanUpApplicationRecord -- 9417
07-21 16:01:54.000 10007 10007 I KnoxUsageLogPro: premStatus:2
07-21 16:01:54.001 10007 10007 I KnoxUsageLogPro: isEulaShown : false
07-21 16:01:54.001 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-21 16:01:54.002 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-21 16:01:54.002 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-21 16:01:54.005 10217 10255 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-21 16:01:54.005 10217 10255 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=0
07-21 16:01:54.006 10217 10255 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
07-21 16:01:54.006  4768  4787 D ForegroundUtils: could not check pending caller
,07-21 16:01:54.017  9967  9967 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-21 16:01:54.017  9967  9967 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,07-21 16:01:54.020  3675  4941 D MountService: getExternalStorageMountMode : 1
07-21 16:01:54.020  3675  4941 D MountService: getExternalStorageMountMode : 3
07-21 16:01:54.020  3675  4941 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10172, packageName : com.example.ThaliTestApp
,07-21 16:01:54.041 10438 10438 E Zygote  : v2
07-21 16:01:54.041 10438 10438 I libpersona: KNOX_SDCARD checking this for 10172
07-21 16:01:54.041 10438 10438 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:54.042 10438 10438 E Zygote  : accessInfo : 0
,07-21 16:01:54.044  3675  4941 I ActivityManager: Start proc 10438:com.example.ThaliTestApp/u0a172 for broadcast com.example.ThaliTestApp/io.jxcore.node.ConnectivityChangeListener
,07-21 16:01:54.053 10438 10438 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:54.055 10438 10438 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.ThaliTestApp 
,07-21 16:01:54.062 10438 10438 I art     : Late-enabling -Xcheck:jni
,07-21 16:01:54.078  3241  3241 E audit   : type=1320 audit(1500645714.066:540): 
,07-21 16:01:54.094  3241  3241 E audit   : type=1320 audit(1500645714.086:541): 
07-21 16:01:54.094 10438 10438 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:54.095 10438 10438 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:54.100  3675  3988 I ActivityManager: DSS on for com.example.ThaliTestApp and scale is 1.0
,07-21 16:01:54.117  3241  3241 E audit   : type=1320 audit(1500645714.106:542): 
,07-21 16:01:54.132  3241  3241 E audit   : type=1320 audit(1500645714.126:543): 
,07-21 16:01:54.144 10438 10438 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-21 16:01:54.170 10438 10438 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:54.180  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.181  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.181  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.181  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.181  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:54.181  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.181  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.182  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.182  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.182  3675  4931 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:54.223 10438 10438 D jxcore_app_log: JniHelper::setJavaVM(0xf0134000), pthread_self() = -211311308
07-21 16:01:54.223 10438 10438 E JX-Cordova: JXcore wasn't initialized yet
,07-21 16:01:54.226  3675  3720 D MountService: getExternalStorageMountMode : 3
07-21 16:01:54.226  3675  3720 D MountService: getExternalStorageMountMode : 3
,07-21 16:01:54.226  3675  3720 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 10173, packageName : com.rockwellautomation.AppPlatformP2P
,07-21 16:01:54.244 10457 10457 E Zygote  : v2
07-21 16:01:54.244 10457 10457 I libpersona: KNOX_SDCARD checking this for 10173
07-21 16:01:54.244 10457 10457 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:54.246 10457 10457 E Zygote  : accessInfo : 0
,07-21 16:01:54.254  3675  3720 I ActivityManager: Start proc 10457:com.rockwellautomation.AppPlatformP2P/u0a173 for broadcast com.rockwellautomation.AppPlatformP2P/io.jxcore.node.ConnectivityChangeListener
,07-21 16:01:54.255 10457 10457 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:54.256 10457 10457 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.rockwellautomation.AppPlatformP2P 
,07-21 16:01:54.258 10457 10457 I art     : Late-enabling -Xcheck:jni
,07-21 16:01:54.261  3675  3720 I ActivityManager: KPU : put [com.sec.android.app.sbrowser] : 21824 K
07-21 16:01:54.261  3675  3720 I ActivityManager: Killing 9473:com.sec.android.app.sbrowser/u0a134 (adj 906): DHA:empty #33
,07-21 16:01:54.275  3241  3241 E audit   : type=1320 audit(1500645714.266:544): 
,07-21 16:01:54.278 10457 10457 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:54.278 10457 10457 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:54.281  3675  4939 I ActivityManager: DSS on for com.rockwellautomation.AppPlatformP2P and scale is 1.0
,07-21 16:01:54.287  3241  3241 E audit   : type=1320 audit(1500645714.276:545): 
,07-21 16:01:54.288  3675  4987 D ActivityManager: cleanUpApplicationRecord -- 9473
,07-21 16:01:54.295  4768  4787 D ForegroundUtils: could not check pending caller
,07-21 16:01:54.302  3241  3241 E audit   : type=1320 audit(1500645714.296:546): 
,07-21 16:01:54.307 10457 10457 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-21 16:01:54.314  3675  4931 D WifiService: setWifiEnabled: true pid=10094, uid=10033
07-21 16:01:54.314  3675  4931 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-21 16:01:54.315  3675  4931 D WifiControlHistoryProvider: query
07-21 16:01:54.316  3241  3241 E audit   : type=1320 audit(1500645714.306:547): 
,07-21 16:01:54.323  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-21 16:01:54.323  3675  4931 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-21 16:01:54.323  3675  4931 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:54.324  3675  4931 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-21 16:01:54.327 10457 10457 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:54.328  3675  4931 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-21 16:01:54.328  3675  4931 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-21 16:01:54.329  3675  3924 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-21 16:01:54.341  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.341  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.341  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.341  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:54.341  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.341  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.342  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.342  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.342  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.342  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:54.348  4645  4645 D io_stats: !@   8,0 r 26114 2315764 w 4993 204148 d 675 73900 f 2014 2014 iot 11660 10918 th 474164 0 0 pt 0 inp 0 0 212.128
,07-21 16:01:54.378 10457 10457 D jxcore_app_log: JniHelper::setJavaVM(0xf0134000), pthread_self() = -211311308
07-21 16:01:54.378 10457 10457 E JX-Cordova: JXcore wasn't initialized yet
,07-21 16:01:54.391  3675  4982 I ActivityManager: KPU : put [com.sec.android.widgetapp.samsungapps] : 26816 K
07-21 16:01:54.391  3675  4982 I ActivityManager: Killing 9533:com.sec.android.widgetapp.samsungapps/u0a105 (adj 906): DHA:empty #33
,07-21 16:01:54.397  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:54.398  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.398  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:54.398  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.398  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.398  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.398  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.398  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.399  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:54.399  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:54.423  3675  3719 D ActivityManager: cleanUpApplicationRecord -- 9533
,07-21 16:01:54.424  4768  4787 D ForegroundUtils: could not check pending caller
,07-21 16:01:54.446  5251  5251 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-21 16:01:54.453  5251  8204 I iu.UploadsManager: num queued entries: 0
07-21 16:01:54.454  5251  8204 I iu.UploadsManager: num updated entries: 0
07-21 16:01:54.457  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:54.466  5251  8204 I iu.SyncManager: NEXT; no task
,07-21 16:01:54.489  3675  4543 D MountService: getExternalStorageMountMode : 1
07-21 16:01:54.489  3675  4543 D MountService: getExternalStorageMountMode : 3
,07-21 16:01:54.489  3675  4543 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10041, packageName : com.osp.app.signin
,07-21 16:01:54.514 10476 10476 E Zygote  : v2
07-21 16:01:54.514 10476 10476 I libpersona: KNOX_SDCARD checking this for 10041
07-21 16:01:54.514 10476 10476 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:54.516 10476 10476 E Zygote  : accessInfo : 0
,07-21 16:01:54.523  3675  4543 I ActivityManager: Start proc 10476:com.osp.app.signin/u0a41 for broadcast com.osp.app.signin/.OspReceiver
,07-21 16:01:54.526 10476 10476 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:54.528 10476 10476 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.osp.app.signin 
,07-21 16:01:54.562  3675  4988 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170721T163154 - CU:10124/CP:5163
07-21 16:01:54.562 10476 10476 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:54.563 10476 10476 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:54.566  3675  4939 I ActivityManager: DSS on for com.osp.app.signin and scale is 1.0
,07-21 16:01:54.612  3291  3769 D Netd    : Iface wlan0 link up
07-21 16:01:54.612  3675  3925 D wifi    : set interface wlan0 flags (UP)
07-21 16:01:54.612  3675  3925 I WifiHAL : Initializing wifi
07-21 16:01:54.612  3675  3925 I WifiHAL : Creating socket
,07-21 16:01:54.615  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:01:54.615  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:01:54.619  3675  3925 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-21 16:01:54.619  3675  3925 D wifi    : Did set static halHandle = 0x798fe610e0
07-21 16:01:54.619  3675  3925 D wifi    : halHandle = 0x798fe610e0, mVM = 0x79bd490300, mCls = 0x103166
07-21 16:01:54.619  3675  3925 D wifi    : array field set
,07-21 16:01:54.620  3675  3925 I WifiHW  : CCMode is disabled, skip verifying wpa_supplicant
,07-21 16:01:54.621  3675 10492 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=522105262304
07-21 16:01:54.621  3675 10492 D wifi    : waitForHalEvents called, vm = 0x79bd490300, obj = 0x103166, env = 0x7993988780
07-21 16:01:54.621  3675  3925 E WifiHW  : supplicant_name : p2p_supplicant
,07-21 16:01:54.642 10476 10476 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-21 16:01:54.645 10476 10476 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Dream/lib/arm64
,07-21 16:01:54.670 10476 10476 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:54.686 10476 10476 I SA      : [SSP] onCreated
,07-21 16:01:54.693 10493 10493 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 10493 | /system/bin/wpa_supplicant
07-21 16:01:54.694 10493 10493 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
,07-21 16:01:54.696 10493 10493 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-21 16:01:54.696 10493 10493 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-21 16:01:54.700 10493 10493 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x400008), vendorssid_list()
07-21 16:01:54.700 10493 10493 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-21 16:01:54.702  3113  3113 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10493
07-21 16:01:54.703  3113  3113 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-21 16:01:54.703 10493 10493 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-21 16:01:54.703 10493 10493 I wpa_supplicant: ssSupport state is = 1
07-21 16:01:54.703 10493 10493 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-21 16:01:54.703 10493 10493 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-21 16:01:54.703  3113  3113 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
07-21 16:01:54.704  3113  3113 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10493
07-21 16:01:54.704  3113  3113 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-21 16:01:54.724  3675  3925 D SecContentProvider: insert(), uri = 2
,07-21 16:01:54.724 10476 10476 D SamsungAnalytics:1.8.22: cf feature is supported
,07-21 16:01:54.726  3675  3925 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:54.728  3675  3925 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-21 16:01:54.731  3675  3925 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,07-21 16:01:54.734  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-21 16:01:54.736  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-21 16:01:54.736  3675  3952 I WifiHs20Service: Message received 5011
,07-21 16:01:54.739  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=2 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:01:54.748  3675  4038 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-21 16:01:54.753  3675  4038 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-21 16:01:54.753  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-21 16:01:54.754  3675  3675 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-21 16:01:54.755  3675  4488 D SLocation: checkWifiInfo
,07-21 16:01:54.765 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:01:54.766 10476 10476 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
,07-21 16:01:54.790 10476 10476 I SA      : LBE isSupportBixbyModel() FALSE
,07-21 16:01:54.810 10476 10476 I SA      : [TPM] There is no property file
,07-21 16:01:54.834 10476 10476 I SA      : [SCU] isHaveSA() - false
,07-21 16:01:54.834  3675  4178 D WifiService: setWifiEnabled: true pid=10094, uid=10033
,07-21 16:01:54.835  3675  4178 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-21 16:01:54.836  3675  4178 D WifiControlHistoryProvider: query
07-21 16:01:54.840  3675  5817 D SSRM:f  : SIOP:: AP = 280, PST = 272 (W:10), CP = 224, CUR = -15, LCD = 57
07-21 16:01:54.847 10476 10476 I SA      : [SS] no samsung account is signed in
07-21 16:01:54.850  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:01:54.851  3675  4178 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-21 16:01:54.852  3675  4178 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:54.853  3675  4178 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-21 16:01:54.856 10476 10476 I SA      : [TPM] getModelProperty : null
07-21 16:01:54.856 10476 10476 I SA      : [TPM] getCSCProperty : null
07-21 16:01:54.857  3675  4178 I WifiService: Wi-Fi Sharing settings has not been accessed
07-21 16:01:54.857  3675  4178 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-21 16:01:54.859 10476 10476 I SA      : [SCU] isHaveSA() - false
,07-21 16:01:54.862 10476 10476 I SA      : [SCU] == networkStateCheck == false
,07-21 16:01:54.862 10476 10476 I SA      : [SS] network off, couldn't connect to DIR
,07-21 16:01:54.870 10476 10476 D BixbyApi_0.1.6: Version Name:2.2.03-46
,07-21 16:01:54.874  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-21 16:01:54.875 10476 10476 I SA      : [DM] init START
,07-21 16:01:54.879 10476 10476 I SA      : [DM] This device is not a Vodafone
,07-21 16:01:54.883 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.883 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.884 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.884 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.885 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.885 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.886 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.886 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.887 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.888 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.888 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.888 10476 10476 W ResourceType: Failure getting entry for 0x7f0b0002 (t=10 e=2) (error -75)
,07-21 16:01:54.889 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.890 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.890 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.891 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.891 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.892 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.892 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.893 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.893 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.894 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.894 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.895 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.895 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.896 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.896 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.897 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.897 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.897 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.898 10476 10476 W ResourceType: Failure getting entry for 0x7f0b0005 (t=10 e=5) (error -75)
,07-21 16:01:54.898 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.899 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.899 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.900 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.900 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.901 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.901 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.902 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.902 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.903 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.903 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.904 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.904 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.905 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.905 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.905 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-21 16:01:54.906 10476 10476 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-21 16:01:54.916 10493 10493 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,07-21 16:01:54.919 10476 10476 I SA      : support phone number id : true
07-21 16:01:54.919 10476 10476 I SA      : [DM] Supports Ref Jpn : true
07-21 16:01:54.919 10476 10476 I SA      : [DM] init END
,07-21 16:01:54.919 10476 10476 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,07-21 16:01:54.922 10476 10476 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
07-21 16:01:54.922 10476 10476 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-21 16:01:54.933 10476 10476 I SA      : [SLFUCHKMGR] constructor called
,07-21 16:01:54.948 10493 10493 W wpa_supplicant: Loading system cred
07-21 16:01:54.948 10493 10493 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-21 16:01:54.948  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10493
07-21 16:01:54.948  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-21 16:01:54.949 10493 10493 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-21 16:01:54.949 10493 10493 I wpa_supplicant: ssSupport state is = 1
07-21 16:01:54.949  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-21 16:01:54.949 10493 10493 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-21 16:01:54.949 10493 10493 I wpa_supplicant: [getIMSI]: sim_num 0
,07-21 16:01:54.956 10476 10476 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-21 16:01:54.956 10476 10476 I SA      : [OR] == isSIMCardReady false ==
,07-21 16:01:54.956 10476 10476 I SA      : [SCU] == networkStateCheck == false
07-21 16:01:54.956 10476 10476 I SA      : [OR] onReceive END
,07-21 16:01:54.964  3675  4179 I ActivityManager: KPU : put [com.wssnps] : 26768 K
07-21 16:01:54.964  3675  4179 I ActivityManager: Killing 9554:com.wssnps/1000 (adj 906): DHA:empty #33
,07-21 16:01:54.967  3675  3758 D MountService: getExternalStorageMountMode : 1
07-21 16:01:54.968  3675  3758 D MountService: getExternalStorageMountMode : 3
,07-21 16:01:54.968  3675  3758 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.svcagent
,07-21 16:01:54.988 10502 10502 E Zygote  : v2
07-21 16:01:54.988 10502 10502 I libpersona: KNOX_SDCARD checking this for 1000
07-21 16:01:54.988 10502 10502 I libpersona: KNOX_SDCARD not a persona
07-21 16:01:54.989 10502 10502 E Zygote  : accessInfo : 0
07-21 16:01:54.989  3675  3758 I ActivityManager: Start proc 10502:com.samsung.android.svcagent/1000 for broadcast com.samsung.android.svcagent/com.samsung.android.service.svcagent.BootReceiver
,07-21 16:01:54.990  3675  3920 D ActivityManager: cleanUpApplicationRecord -- 9554
,07-21 16:01:54.994  4768  4787 D ForegroundUtils: could not check pending caller
,07-21 16:01:54.995 10502 10502 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:54.996 10502 10502 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.svcagent 
,07-21 16:01:55.018 10502 10502 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:55.019 10502 10502 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:55.021 10493 10493 I wpa_supplicant: rfkill: Cannot open RFKILL control device
07-21 16:01:55.021  3675  4988 I ActivityManager: DSS on for com.samsung.android.svcagent and scale is 1.0
07-21 16:01:55.022  3291  3769 D Netd    : Iface wlan0 link up
07-21 16:01:55.022  3291  3769 D Netd    : Iface wlan0 link up
07-21 16:01:55.023  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
,07-21 16:01:55.023  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
07-21 16:01:55.024  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:01:55.024  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:01:55.044 10502 10502 W System  : ClassLoader referenced unknown path: /system/priv-app/SVCAgent/lib/arm64
,07-21 16:01:55.059 10502 10502 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:55.069 10502 10502 I SVCAgent: Ignore network change.
,07-21 16:01:55.072  3675  4544 D MountService: getExternalStorageMountMode : 1
07-21 16:01:55.072  3675  4544 D MountService: getExternalStorageMountMode : 3
07-21 16:01:55.072  3675  4544 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10064, packageName : com.samsung.android.themestore
,07-21 16:01:55.093 10515 10515 E Zygote  : v2
,07-21 16:01:55.093 10515 10515 I libpersona: KNOX_SDCARD checking this for 10064
07-21 16:01:55.093 10515 10515 I libpersona: KNOX_SDCARD not a persona
07-21 16:01:55.094 10515 10515 E Zygote  : accessInfo : 0
07-21 16:01:55.094  3675  4544 I ActivityManager: Start proc 10515:com.samsung.android.themestore/u0a64 for broadcast com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,07-21 16:01:55.099  3675  4544 I ActivityManager: KPU : put [com.sec.android.service.health] : 20820 K
,07-21 16:01:55.099  3675  4544 I ActivityManager: Killing 9596:com.sec.android.service.health/u0a24 (adj 906): DHA:empty #33
07-21 16:01:55.100 10515 10515 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-21 16:01:55.101 10493 10493 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-21 16:01:55.101 10493 10493 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-21 16:01:55.102 10515 10515 I SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,07-21 16:01:55.102  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10493
07-21 16:01:55.102  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-21 16:01:55.103  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-21 16:01:55.103 10493 10493 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-21 16:01:55.103 10493 10493 I wpa_supplicant: ssSupport state is = 1
,07-21 16:01:55.105 10493 10493 E wpa_supplicant: nl80211: Could not configure driver mode
,07-21 16:01:55.106 10493 10493 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-21 16:01:55.106 10493 10493 E wpa_supplicant: p2p0: Failed to initialize driver interface
,07-21 16:01:55.107 10493 10493 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
,07-21 16:01:55.107 10493 10493 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-21 16:01:55.107  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10493
07-21 16:01:55.107  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-21 16:01:55.107 10493 10493 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,07-21 16:01:55.108 10493 10493 I wpa_supplicant: ssSupport state is = 1
07-21 16:01:55.108  3113  3113 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-21 16:01:55.114  3241  3241 E audit   : type=1320 audit(1500645715.106:548): 
,07-21 16:01:55.121  3675  4179 D ActivityManager: cleanUpApplicationRecord -- 9596
,07-21 16:01:55.123  4768  4787 D ForegroundUtils: could not check pending caller
,07-21 16:01:55.125 10515 10515 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:55.126 10515 10515 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:55.128  3675  3927 I ActivityManager: DSS on for com.samsung.android.themestore and scale is 1.0
,07-21 16:01:55.128  3241  3241 E audit   : type=1320 audit(1500645715.116:549): 
,07-21 16:01:55.145  3241  3241 E audit   : type=1320 audit(1500645715.136:550): 
,07-21 16:01:55.154 10515 10515 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-21 16:01:55.155 10515 10515 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyThemes/lib/arm64
,07-21 16:01:55.158  3241  3241 E audit   : type=1320 audit(1500645715.146:551): 
,07-21 16:01:55.170 10515 10515 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:55.187 10515 10515 D a       : Exist Config : false
,07-21 16:01:55.189 10515 10515 D a       : getMcc
07-21 16:01:55.189 10493 10493 I wpa_supplicant: rfkill: Cannot get wiphy information
,07-21 16:01:55.194 10515 10515 D as      : isQaMode
,07-21 16:01:55.197 10493 10493 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-21 16:01:55.198 10515 10515 D a       : getMnc
07-21 16:01:55.198 10515 10515 D a       : getCsc
07-21 16:01:55.199 10515 10515 D a       : getSystemCountryCode
07-21 16:01:55.199 10515 10515 D a       : getImei
,07-21 16:01:55.202 10515 10515 D as      : getMd5HashString
,07-21 16:01:55.202 10515 10515 D as      : getSha256HashString
,07-21 16:01:55.203 10515 10515 D a       : getModelName
07-21 16:01:55.203 10515 10515 D a       : getVirtualModelName
07-21 16:01:55.203 10515 10515 D a       : getAndroidSDKVersion
07-21 16:01:55.203 10515 10515 D a       : getLanguageCode
07-21 16:01:55.203 10515 10515 D a       : getCountryCode
,07-21 16:01:55.204 10515 10515 D a       : getNetworkType
,07-21 16:01:55.207 10515 10515 D w       : isSupportedAodSystemFeature
,07-21 16:01:55.209 10515 10515 D a       : getThemeFrameworkVersion
,07-21 16:01:55.213 10515 10515 D a       : isLogPrintMode
,07-21 16:01:55.215 10515 10515 D as      : isQaMode
,07-21 16:01:55.218 10515 10515 D a       : getVerName
,07-21 16:01:55.220 10515 10515 D a       : getVerCode
,07-21 16:01:55.221 10515 10515 D a       : getPackageName
07-21 16:01:55.221 10515 10515 D a       : getAutoUpgradeInterval
,07-21 16:01:55.222 10515 10515 D a       : loadCountrySearchEx
,07-21 16:01:55.226 10515 10515 D a       : com.samsung.android.themestore.g.c.b.u; class invalid for deserialization
,07-21 16:01:55.226 10515 10515 I a       : # initConfig Time : 41
07-21 16:01:55.226 10515 10515 I a       : ● MCC/NNC: /0
07-21 16:01:55.226 10515 10515 I a       : ● Model: SM-G930F_TM
07-21 16:01:55.226 10515 10515 I a       : ● MyApp Version: 2.1.56-70306
07-21 16:01:55.227 10515 10515 I a       : ● OS Version: 24
07-21 16:01:55.227 10515 10515 I a       : ● IsSupportedSView: true
,07-21 16:01:55.235 10515 10515 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-21 16:01:55.253 10515 10515 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-21 16:01:55.266  3675  4544 I ActivityManager: KPU : put [com.samsung.android.app.watchmanager:contentprovider] : 26996 K
07-21 16:01:55.266  3675  4544 I ActivityManager: Killing 9614:com.samsung.android.app.watchmanager:contentprovider/u0a18 (adj 906): DHA:empty #33
07-21 16:01:55.280  8043  8043 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-21 16:01:55.281  8043  8043 E SPPClientService: [SystemStateMoniter] Current Time : 213061
,07-21 16:01:55.282  8043  8043 E SPPClientService: [SystemStateMoniter] No Connect : true
,07-21 16:01:55.299  8043 10545 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
07-21 16:01:55.301  3675  3758 D MountService: getExternalStorageMountMode : 1
07-21 16:01:55.301  3675  3758 D MountService: getExternalStorageMountMode : 3
07-21 16:01:55.301  3675  3758 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10003, packageName : com.sec.android.provider.badge
,07-21 16:01:55.326 10546 10546 E Zygote  : v2
07-21 16:01:55.326 10546 10546 I libpersona: KNOX_SDCARD checking this for 10003
07-21 16:01:55.326 10546 10546 I libpersona: KNOX_SDCARD not a persona
,07-21 16:01:55.328 10546 10546 E Zygote  : accessInfo : 0
07-21 16:01:55.328  3675  3758 I ActivityManager: Start proc 10546:com.sec.android.provider.badge/u0a3 for broadcast com.sec.android.provider.badge/.BadgeCountReceiver
,07-21 16:01:55.333  3675  4178 D ActivityManager: cleanUpApplicationRecord -- 9614
,07-21 16:01:55.337  4768  4787 D ForegroundUtils: could not check pending caller
07-21 16:01:55.338 10546 10546 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:55.340 10546 10546 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,07-21 16:01:55.363  3675  4987 D WifiService: setWifiEnabled: true pid=10094, uid=10033
07-21 16:01:55.364  3675  4987 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-21 16:01:55.364  3675  4987 D WifiControlHistoryProvider: query
,07-21 16:01:55.372  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-21 16:01:55.372  3675  4987 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-21 16:01:55.373  3675  4987 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:55.374  3675  4987 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-21 16:01:55.377 10546 10546 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:01:55.378 10546 10546 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:55.378  3675  4987 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-21 16:01:55.379  3675  4987 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-21 16:01:55.381  3675  4177 I ActivityManager: DSS on for com.sec.android.provider.badge and scale is 1.0
,07-21 16:01:55.409 10546 10546 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_N/lib/arm64
,07-21 16:01:55.427 10546 10546 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:55.435 10546 10546 D BadgeProvider: onCreate
07-21 16:01:55.435 10546 10546 D BadgeProvider: DatabaseHelper
,07-21 16:01:55.439 10546 10546 D BadgeCountReceiver: badge intent : Intent { act=com.sec.intent.action.BADGE_COUNT_UPDATE flg=0x10 cmp=com.sec.android.provider.badge/.BadgeCountReceiver launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:01:55.439 10546 10546 D BadgeCountReceiver: packageName: com.samsung.android.email.provider, className: com.samsung.android.email.ui.activity.MessageListXL, count: 0
,07-21 16:01:55.448 10546 10546 D BadgeProvider: onOpen
,07-21 16:01:55.452 10546 10546 D BaseReflect: null getOwnClass TEST
07-21 16:01:55.452 10546 10546 D MethodReflector: android.content.ContentResolver getClass TEST
07-21 16:01:55.452 10546 10546 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
07-21 16:01:55.452 10546 10546 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-21 16:01:55.456 10546 10546 D MethodReflector: notifyChange is called
,07-21 16:01:55.457  4896  4896 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
,07-21 16:01:55.458 10546 10546 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-21 16:01:55.458 10546 10546 D BadgeProvider: sendNotify, [notify] : null
07-21 16:01:55.458  4896  4896 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
,07-21 16:01:55.460 10546 10546 D BadgeProvider: update, getCallingPackage() : com.sec.android.provider.badge
07-21 16:01:55.460 10546 10546 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-21 16:01:55.460 10546 10546 D BadgeProvider: update, [uri.query] : null
07-21 16:01:55.460 10546 10546 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-21 16:01:55.460 10546 10546 D BadgeProvider: update, [UpdateCount] : 1
,07-21 16:01:55.477  9967  9967 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
,07-21 16:01:55.477  9967  9967 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,07-21 16:01:55.494  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.494  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.494  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.495  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.495  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.495  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.495  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.495  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.496  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.496  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.508  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.508  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.509  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.509  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.509  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.509  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.510  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.510  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.510  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.510  3675  4987 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.518  3675  4177 I ActivityManager: KPU : put [com.android.vending] : 36100 K
07-21 16:01:55.518  3675  4177 I ActivityManager: Killing 8708:com.android.vending/u0a32 (adj 906): DHA:empty #33
,07-21 16:01:55.523  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.523  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.523  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.523  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.523  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.523  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.523  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.523  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.524  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.524  3675  4544 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.533  9967  9967 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-21 16:01:55.533  9967  9967 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,07-21 16:01:55.543  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.543  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.543  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.543  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.544  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.544  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.544  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.544  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.544  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.544  3675  4942 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.554  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.555  3675  4988 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.557  3675  3720 D ActivityManager: cleanUpApplicationRecord -- 8708
,07-21 16:01:55.568  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:55.569  3675  3988 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:55.571  4768  6456 D ForegroundUtils: could not check pending caller
,07-21 16:01:55.659  4896  4896 D LauncherApplication: run: mBadgeRefreshHandler reloadBadges
07-21 16:01:55.660  4896  4896 D Launcher.Model: reloadBadges entered.
,07-21 16:01:55.690 10546 10558 D BadgeProvider: query, [selection] : null
,07-21 16:01:55.700  4896  5038 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
07-21 16:01:55.701  4896  5038 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
07-21 16:01:55.701  4896  5038 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
07-21 16:01:55.701  4896  5038 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-21 16:01:55.701  4896  5038 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-21 16:01:55.701  4896  5038 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
07-21 16:01:55.701  4896  5038 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.lool = 0
07-21 16:01:55.701  4896  5038 D BadgeCache: 1. updateBadgeCounts: com.wssyncmldm = 0
,07-21 16:01:55.711  4896  5038 D BadgeCache: updated Badged:0
,07-21 16:01:55.712  4896  5038 D BadgeCache: updateBadgeCounts:0
,07-21 16:01:55.767  3675  3763 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=213524 mStackState=3 mControllerTxTimeMs=0 mControllerTxTimePerLevelMs=[] mControllerRxTimeMs=0 mControllerIdleTimeMs=0 mControllerEnergyUsed=0 }
,07-21 16:01:55.796 10493 10493 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-21 16:01:55.799  3675  3925 I WifiConnectivityManager: User band preference: 0
,07-21 16:01:55.801  3675  3925 D WifiConfigManager: Loading config and enabling all networks 
,07-21 16:01:55.813  3675  3925 D WifiConfigStore: readNetwork skipInternetCheck
,07-21 16:01:55.826  3675  3925 D WifiConfigStore: readNetwork skipInternetCheck
,07-21 16:01:55.856  3675  3925 D WifiConfigStore: readNetwork skipInternetCheck
,07-21 16:01:55.890  3675  4939 D WifiService: setWifiEnabled: true pid=10094, uid=10033
07-21 16:01:55.891  3675  4939 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-21 16:01:55.892  3675  4939 D WifiControlHistoryProvider: query
,07-21 16:01:55.904  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:01:55.905  3675  4939 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-21 16:01:55.905  3675  3925 D WifiConfigStore: readNetwork skipInternetCheck
,07-21 16:01:55.907  3675  4939 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:55.908  3675  4939 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-21 16:01:55.916  3675  4939 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-21 16:01:55.917  3675  4939 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-21 16:01:55.938  3675  3925 D WifiConfigStore: readNetwork skipInternetCheck
,07-21 16:01:55.958  3675  3925 D WifiConfigStore: readNetwork skipInternetCheck
,07-21 16:01:55.973  3675  3925 W WifiNetworkHistory: Upgrading network 4 to android.uid.system:1000
07-21 16:01:55.974  3675  3925 W WifiNetworkHistory: Upgrading network 0 to android.uid.system:1000
,07-21 16:01:55.975  3675  3925 W WifiNetworkHistory: Upgrading network 1 to android.uid.system:1000
07-21 16:01:55.975  3675  3925 W WifiNetworkHistory: Upgrading network 5 to android.uid.system:1000
,07-21 16:01:55.976  3675  3925 W WifiNetworkHistory: Upgrading network 2 to android.uid.system:1000
07-21 16:01:55.977  3675  3925 W WifiNetworkHistory: Upgrading network 3 to android.uid.system:1000
,07-21 16:01:55.979  3675  3925 D WifiConfigManager: loaded 0 passpoint configs
,07-21 16:01:55.986  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,07-21 16:01:55.986  3675  3675 D WifiHs20Service: reason: 2
07-21 16:01:55.986  3675  3925 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-21 16:01:55.987  3675  3952 I WifiHs20Service: Message received 5014
07-21 16:01:55.987  3675  3952 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-21 16:01:55.987  3675  3952 E WifiHs20Service: The changed config is NULL
07-21 16:01:55.987 10493 10493 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,07-21 16:01:56.004  3675  3925 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-21 16:01:56.008  3675  3675 D WifiController: [FCC]setFccChannel() is called !!!
,07-21 16:01:56.008  3675  3675 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-21 16:01:56.008  3675  3675 D WifiStateMachine: setFccChannel: channel = 0
07-21 16:01:56.009  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-21 16:01:56.011  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-21 16:01:56.011  3675  3951 D HS20StateMachine: WIFI_STATE_ENABLED
07-21 16:01:56.011  3675  3951 D HS20StateMachine: reloadCredentialsToSupplicant
07-21 16:01:56.011  3675  3951 D WifiHs20DBHandler: getCredentialIds
07-21 16:01:56.012  3675  3952 I WifiHs20Service: Message received 5011
07-21 16:01:56.013  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135173 arg1=3 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:01:56.017  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:01:56.018  3675  4038 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-21 16:01:56.018  3675  3675 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-21 16:01:56.018  3675  4488 D SLocation: checkWifiInfo
07-21 16:01:56.019  3675  4488 W SLocation: No Active Data Connection
07-21 16:01:56.023  3675  4038 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-21 16:01:56.024  3675  3925 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-21 16:01:56.024 10493 10493 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-21 16:01:56.025 10217 10217 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-21 16:01:56.026 10217 10217 I BluetoothA2dpServiceJni: Attempting to set busy level
,07-21 16:01:56.033 10094 10094 D BluetoothAdapter: STATE_ON
07-21 16:01:56.033  9967  9967 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-21 16:01:56.033  9967  9967 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
07-21 16:01:56.035  9967  9967 D SecurityLogAgent: NetworkReceiver : SendSecurityReport is off
,07-21 16:01:56.036  3675  3951 D MountService: getExternalStorageMountMode : 1
07-21 16:01:56.036  3675  3951 D MountService: getExternalStorageMountMode : 3
07-21 16:01:56.036  3675  3951 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10114, packageName : com.samsung.hs20provider
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-21 16:01:56.037 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-21 16:01:56.041 10094 10094 D BluetoothAdapter: STATE_ON
,07-21 16:01:56.044 10094 10094 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-21 16:01:56.059 10562 10562 E Zygote  : v2
07-21 16:01:56.059 10562 10562 I libpersona: KNOX_SDCARD checking this for 10114
,07-21 16:01:56.059 10562 10562 I libpersona: KNOX_SDCARD not a persona
07-21 16:01:56.061 10562 10562 E Zygote  : accessInfo : 0
,07-21 16:01:56.064  3675  3951 I ActivityManager: Start proc 10562:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,07-21 16:01:56.066  3675  3925 D WifiNative-HAL: Setting external_sim to 1
,07-21 16:01:56.067  3675  3925 D wifi    : setting dfs flag to true, 0x7985c8e9c0
,07-21 16:01:56.068  3675  3925 D WifiStateMachine: Setting OUI to DA-A1-19
,07-21 16:01:56.069  3675  3925 D wifi    : setting scan oui 0x7985c8e9c0
07-21 16:01:56.069  3675  3925 D WifiHAL : Sending mac address OUI
07-21 16:01:56.070  3675  3925 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-21 16:01:56.070  3675  3925 E WifiStateMachine: SupplicantStarted - enter() isAirplaneModeEnabled !!  
07-21 16:01:56.071  3675  3925 D WifiCountryCode: [setCountryCodeNative] Default CSC Country Code : PL
07-21 16:01:56.071 10562 10562 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:01:56.073 10562 10562 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
07-21 16:01:56.075  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:56.075  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:56.075  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.075  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.075  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.075  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.075  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.075  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.076  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.076  3675  3720 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:56.091  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:56.091  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.092  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.092  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.092  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.092  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.092  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.092  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.092  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.092  3675  4939 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:56.103 10562 10562 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:01:56.103  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.103 10562 10562 D ActivityThread: Added TimaKeyStore provider
,07-21 16:01:56.104  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.104  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:56.105  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.105  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.105  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.105  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.105  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.106  3675  4941 I ActivityManager: DSS on for com.samsung.hs20provider and scale is 1.0
07-21 16:01:56.106  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
07-21 16:01:56.107  3675  3920 W NetworkIdentity: Active mobile network without subscriber!
,07-21 16:01:56.116 10493 10493 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-21 16:01:56.118  3675  3925 D WifiCountryCode: Succeeded to set country code to: PL
07-21 16:01:56.118  3675  3925 D wifi    : android_net_wifi_get_firmware_version = 0x7985c8e9c0
,07-21 16:01:56.118  3675  3925 E WifiHAL : Failed to register debug response; result = -95
07-21 16:01:56.119  3675  3925 E wifi    : Fail to get Firmware version
07-21 16:01:56.119  3675  3925 D wifi    : android_net_wifi_get_driver_version = 0x7985c8e9c0
,07-21 16:01:56.119  3675  3925 E WifiHAL : Failed to register debug response; result = -95
07-21 16:01:56.119  3675  3925 E wifi    : Fail to get driver version
07-21 16:01:56.119  3675  3925 D wifi    : android_net_wifi_set_log_handler = 0x7985c8e9c0
07-21 16:01:56.119  3675  3925 D wifi    : android_net_wifi_get_ring_buffer_status = 0x7985c8e9c0
,07-21 16:01:56.120  3675  3925 E WifiHAL : Failed to register debug response; result = -95
07-21 16:01:56.120  3675  3925 E WifiLogger: no ring buffers found
07-21 16:01:56.120  3675  3925 D WifiHAL : Start get packet fate command
07-21 16:01:56.120  3675  3925 D WifiHAL : createRequest Monitor packet fate request
07-21 16:01:56.120  3675  3925 E WifiHAL : Failed to register get pkt fate response; result = -95
,07-21 16:01:56.120  3675  3925 E WifiLogger: Failed to start packet fate monitoring
07-21 16:01:56.122  3675  4012 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
,07-21 16:01:56.126 10562 10562 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,07-21 16:01:56.138 10562 10562 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:01:56.148  3675  3921 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-21 16:01:56.148  3675  3925 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-21 16:01:56.148  3675  3925 I WifiConnectivityManager: Set WiFi enabled
07-21 16:01:56.148  3675  3925 E WifiStateMachine: ConnectModeState - enter !! - mIsSupportGeofence !!
07-21 16:01:56.149  3675  3925 D WifiStateMachine: Remembered scan first is enabled
07-21 16:01:56.149  3675  3675 I WifiStateMachine: initGeofence
07-21 16:01:56.150  3675  3925 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@b42b869
,07-21 16:01:56.151  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
07-21 16:01:56.151  3675  3925 E wifi    : failed to get channel list : -95
07-21 16:01:56.151  3675  3925 D WifiConfigManager: getChannelsForBand(WifiScanner.WIFI_BAND_24_GHZ) is null. So set default 2.4GHz 14 channels.
07-21 16:01:56.151  3291  3777 D CommandListener: Setting iface cfg
07-21 16:01:56.151  3291  3777 D CommandListener: Trying to bring up p2p0
07-21 16:01:56.152  3291  3769 D Netd    : Iface p2p0 link up
07-21 16:01:56.155  3675  3921 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-21 16:01:56.155  3675  3921 D SecContentProvider: insert(), uri = 2
07-21 16:01:56.157  3675  3784 D Tethering: interfaceLinkStateChanged p2p0, true
07-21 16:01:56.157  3675  3784 D Tethering: interfaceStatusChanged p2p0, true
07-21 16:01:56.160  3675  3925 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170721T160204 - CU:1000/CP:3675
07-21 16:01:56.160  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160204, SetElapsed=221932, nowELAPSED=213941
07-21 16:01:56.161 10562 10574 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-21 16:01:56.161 10562 10574 D HotspotProvider: CREDENTIAL
07-21 16:01:56.161 10562 10574 D HotspotProvider: No prepend tags
07-21 16:01:56.166  3675  3925 D WifiStateMachine: setFccChannelNative: channel = 0
07-21 16:01:56.166  3675  3925 D WifiNative-wlan0: callSECApiInt - ID [230]
07-21 16:01:56.169  3675  3921 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:56.170  3675  3925 E WifiConnectivityManager: SingleScanListener onFailure: reason: -1 description: not available
07-21 16:01:56.170  3675  3921 D WifiP2pService: P2pEnablingState
07-21 16:01:56.171  3675  3921 D WifiP2pService: P2pEnablingState{ what=147457 }
07-21 16:01:56.171  3675  3921 D WifiP2pService: P2p socket connection successful
07-21 16:01:56.172  3675  3921 D WifiP2pService: P2pEnabledState
07-21 16:01:56.172  3675  3921 D SecContentProvider: insert(), uri = 2
07-21 16:01:56.173  3675  3921 D SecContentProvider: called from android.uid.system:1000
07-21 16:01:56.174  3675  3921 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-21 16:01:56.174  3675  3925 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170721T160158 - CU:1000/CP:3675
07-21 16:01:56.174  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160158, SetElapsed=215951, nowELAPSED=213955
07-21 16:01:56.174  3675  3956 D ConnectivityService: ignoring duplicate network state non-change
,07-21 16:01:56.176  3675  3786 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-21 16:01:56.176  3675  3786 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-21 16:01:56.176  3675  3786 D WifiDisplayController: disconnect
07-21 16:01:56.176  3675  3786 D WifiDisplayAdapter: onFeatureStateChanged empty
07-21 16:01:56.176  3675  3786 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-21 16:01:56.177 10493 10493 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
07-21 16:01:56.180 10493 10493 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,07-21 16:01:56.192  3675  3786 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
,07-21 16:01:56.193  4041  4053 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-21 16:01:56.196 10425 10425 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-21 16:01:56.196  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-21 16:01:56.197 10425 10425 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
07-21 16:01:56.197 10425 10425 D FileShare: Outbound.stopDelayTimer - 
,07-21 16:01:56.209 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:56.211  3675  3925 D WifiNative-wlan0: callSECApiVoid - ID [311]
,07-21 16:01:56.213  3675  3675 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-21 16:01:56.213  3675  3951 D HS20StateMachine: updateNumOfHS20Cred, numOfHS20Cred = 1
,07-21 16:01:56.213  3675  3951 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-21 16:01:56.213  3675  3675 D SLocation: system
07-21 16:01:56.213  3675  3951 D HS20StateMachine: enter : DiscoveringState
07-21 16:01:56.213  3675  3675 D SLocation: startGeofence ID = 1
,07-21 16:01:56.221  4924  5006 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 2ms lastUpdatedAfter : 15434 ms mFlush_time_threasold : 2000 mCurrentSize : 184
,07-21 16:01:56.223  3675  3921 E WifiP2pService: Failed to set my phone number info into probe response
,07-21 16:01:56.226  3675  3921 D WifiNative-HAL: p2pGetDeviceAddress
,07-21 16:01:56.227  3675  3921 D WifiNative-HAL: p2pGetDeviceAddress returning 4e:66:41:a9:15:41
,07-21 16:01:56.227  3675  3921 D WifiP2pService: DeviceAddress: 4e:15:41
,07-21 16:01:56.229  3675  3786 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:15:41
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  primary type: 10-0050F204-5
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  secondary type: null
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  wps: 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  grpcapab: 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  devcapab: 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  status: 3
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  WFD CtrlPort: 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  WFD MaxThroughput: 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  groupownerAddress: null
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  GOdeviceName: null
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  interfaceAddress: 
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  SConnectInfo : null
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  contactInfoHash : null
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  ssDevInfo : 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  iconIdx : 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  semSamsungDeviceType : 0
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  serviceData : null
07-21 16:01:56.229  3675  3786 D WifiDisplayController:  fw_invite : 0
,07-21 16:01:56.237  3675  3921 D WifiP2pService: sending p2p persistent groups changed broadcast
07-21 16:01:56.237  3675  3921 D WifiP2pService: InactiveState
,07-21 16:01:56.238  3675  3921 D WifiP2pService: InactiveState{ what=143376 }
07-21 16:01:56.238  3675  3921 D WifiP2pService: P2pEnabledState{ what=143376 }
07-21 16:01:56.238  3675  3921 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-21 16:01:56.251  3675  3675 D SLocation: addReceiver type4
07-21 16:01:56.251  3675  3675 D SLocation: already exsit record!
,07-21 16:01:56.284  3675  3675 D SLocation: setPendingIntent
07-21 16:01:56.284  3675  3675 D SLocation: setStatus ID = 1 / status = 3
,07-21 16:01:56.351  3675  3675 D SLocation: geofence id (1) detected : 0
,07-21 16:01:56.351  3675  3675 D WifiStateMachine: startGeofence() - id : 1
07-21 16:01:56.352  3675  3675 D RttService: SCAN_AVAILABLE : 3
,07-21 16:01:56.352  3675  3955 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:01:56.353  3675  3954 I WifiScanningService: wifi driver loaded with scan capabilities: max buckets=16
,07-21 16:01:56.358  3675  3675 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
07-21 16:01:56.358  3675  3675 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,07-21 16:01:56.359  4041  4053 D TelephonyProvider: query: match = 7
,07-21 16:01:56.364  3675  3675 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,07-21 16:01:56.369  3675  3675 D SLocation: PendingIntent onSendFinished id:1
,07-21 16:01:56.434 10094 10177 D BluetoothAdapter: STATE_ON
,07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-21 16:01:56.442 10094 10177 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-21 16:01:56.444 10094 10157 D BluetoothAdapter: enable()
,07-21 16:01:56.456 10217 10239 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-21 16:01:56.457 10217 10239 D AdapterProvider: query
,07-21 16:01:56.475 10217 10239 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@91020bd
,07-21 16:01:56.481 10217 10239 D BluetoothAdapterService: updateEvent - already set, update
07-21 16:01:56.482 10217 10239 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-21 16:01:56.482 10217 10239 D AdapterProvider: update
,07-21 16:01:56.487 10217 10239 E BluetoothAdapterService: updateEvent - update success 1
,07-21 16:01:56.489 10094 10157 D BluetoothAdapter: enable(): BT is already enabled..!
,07-21 16:01:56.496  3675  3920 D WifiService: setWifiEnabled: true pid=10094, uid=10033
07-21 16:01:56.496  3675  3920 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-21 16:01:56.496  3675  3920 D WifiControlHistoryProvider: query
,07-21 16:01:56.504  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-21 16:01:56.505  3675  3920 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-21 16:01:56.506  3675  3920 D SecContentProvider: called from android.uid.system:1000
,07-21 16:01:56.507  3675  3920 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-21 16:01:56.511  3675  3920 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-21 16:01:56.511  3675  3920 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-21 16:01:56.512 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-21 16:01:56.512 10094 10157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-21 16:01:56.512 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-21 16:01:56.512 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,07-21 16:01:56.513 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-21 16:01:56.513 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8983094 removed from the list
07-21 16:01:56.513 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8983094 removed from the list
07-21 16:01:56.513 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-21 16:01:56.513 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e11f73d removed from the list
07-21 16:01:56.513 10094 10157 D io.jxcore.node.ConnectivityMonitor: stop
07-21 16:01:56.513 10094 10157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-21 16:01:56.513 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-21 16:01:56.516 10094 10157 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
07-21 16:01:56.520 10094 10575 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
07-21 16:01:56.520 10094 10575 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-21 16:01:57.029  3291  3772 D EnterpriseController: netId is 0
07-21 16:01:57.029  3291  3772 D Netd    : getNetworkForDns: using netid 0 for uid 10033
07-21 16:01:57.029  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-21 16:01:57.036 10094 10577 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,07-21 16:01:57.038 10094 10575 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,07-21 16:01:57.041 10094 10577 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,07-21 16:01:57.041 10094 10575 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-21 16:01:57.041 10094 10577 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-21 16:01:57.042 10094 10575 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-21 16:01:57.042 10094 10577 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-21 16:01:57.043 10094 10577 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,07-21 16:01:57.046 10094 10580 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 228, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.046 10094 10580 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:01:57.046 10094 10580 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-21 16:01:57.046 10094 10579 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 226, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.046 10094 10579 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:01:57.046 10094 10579 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-21 16:01:57.047 10094 10575 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-21 16:01:57.047 10094 10580 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 228, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.047 10094 10580 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:01:57.047 10094 10580 D io.jxcore.node.StreamCopyingThread:  id: 74
07-21 16:01:57.047 10094 10580 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.047 10094 10580 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:01:57.047 10094 10580 D io.jxcore.node.StreamCopyingThread:  id: 74
07-21 16:01:57.047 10094 10581 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 227, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.047 10094 10581 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:01:57.047 10094 10581 D io.jxcore.node.StreamCopyingThread:  id: 75
07-21 16:01:57.047 10094 10580 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-21 16:01:57.048 10094 10580 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-21 16:01:57.048 10094 10580 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-21 16:01:57.048 10094 10580 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-21 16:01:57.048 10094 10580 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-21 16:01:57.048 10094 10580 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
07-21 16:01:57.048 10094 10580 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 228, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.048 10094 10580 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:01:57.048 10094 10580 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-21 16:01:57.048 10094 10579 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 226, thread name: IncomingSocketThread/Sender): Socket closed
07-21 16:01:57.048 10094 10579 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 226, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.048 10094 10579 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:01:57.048 10094 10579 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-21 16:01:57.048 10094 10575 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
07-21 16:01:57.049 10094 10579 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-21 16:01:57.049 10094 10579 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-21 16:01:57.049 10094 10579 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 226, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.049 10094 10579 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:01:57.049 10094 10579 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-21 16:01:57.049 10094 10582 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 229, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.049 10094 10582 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.,
07-21 16:01:57.049 10094 10582 D io.jxcore.node.StreamCopyingThread:  id: 75
07-21 16:01:57.050 10094 10582 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 229, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.050 10094 10582 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:01:57.050 10094 10582 D io.jxcore.node.StreamCopyingThread:  id: 75
07-21 16:01:57.050 10094 10582 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.050 10094 10582 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:01:57.050 10094 10582 D io.jxcore.node.StreamCopyingThread:  id: 75
07-21 16:01:57.050 10094 10582 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-21 16:01:57.050 10094 10582 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-21 16:01:57.054 10094 10582 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-21 16:01:57.054 10094 10582 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-21 16:01:57.054 10094 10582 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-21 16:01:57.054 10094 10582 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-21 16:01:57.054 10094 10582 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 229, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.054 10094 10582 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:01:57.054 10094 10582 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
07-21 16:01:57.054 10094 10581 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 227, thread name: OutgoingSocketThread/Sender): Socket closed
07-21 16:01:57.054 10094 10581 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 227, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.054 10094 10581 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:01:57.054 10094 10581 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-21 16:01:57.054 10094 10581 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-21 16:01:57.054 10094 10581 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-21 16:01:57.055 10094 10581 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 227, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:01:57.055 10094 10581 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:01:57.055 10094 10581 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,07-21 16:01:58.170  3675  3861 D SamsungAlarmManager: Expired : 4
07-21 16:01:58.171  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160204, SetElapsed=221932, nowELAPSED=215952
07-21 16:01:58.171  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@5b3ddcf alarm=Alarm{d322d1d type 2 when 215951 android}
,07-21 16:01:58.175 10493 10493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-21 16:01:58.175 10493 10493 I wpa_supplicant: P2P: Current p2p state = IDLE
07-21 16:01:58.178  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:01:58.180  3675  3954 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160213 - CU:1000/CP:3675
,07-21 16:01:58.188 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:01:58.232 10493 10493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-21 16:01:58.680  3675  4179 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{2ee0963: PendingIntentRecord{bc85960 com.google.android.gms broadcastIntent}}
,07-21 16:01:58.998  4735  4735 I BeaconBle: 'L' hardware scan: scan stopped, no clients
,07-21 16:01:59.350  4645  4645 D io_stats: !@   8,0 r 26157 2322196 w 5075 205024 d 682 73928 f 2032 2032 iot 11760 10969 th 477636 0 0 pt 0 inp 0 0 217.130
,07-21 16:01:59.408  5251  5260 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-21 16:01:59.617  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:01:59.619 10493 10493 I wpa_supplicant: nl80211: Received scan results (34 BSSes)
07-21 16:01:59.620  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:01:59.621  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:01:59.622  3675  3954 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@98a3b92
,07-21 16:01:59.655  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:01:59.666 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:02:00.000  3675  3861 D SamsungAlarmManager: Expired : 8
,07-21 16:02:00.001  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{fc97e19 type 3 when 217781 android}
,07-21 16:02:00.010  3675  3675 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170721T160300 - CU:1000/CP:3675
,07-21 16:02:00.014  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-21 16:02:00.015  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-21 16:02:00.016  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-21 16:02:00.036  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-21 16:02:00.036  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-21 16:02:00.038  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-21 16:02:00.047  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:02:00.048  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:02:00.051  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:02:00.053  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:02:00.058  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:00.073  4068  4068 V hong    : mid yDiff = 438
07-21 16:02:00.073  4068  4068 V hong    : mid yDiff = 438
,07-21 16:02:00.080  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:02:00.082  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:02:00.085  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-21 16:02:00.086  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-21 16:02:00.090  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:02:00.092  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:02:00.112  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:02:00.114  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:02:00.129  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-21 16:02:00.132  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-21 16:02:00.136  5421  5421 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-21 16:02:00.138  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-21 16:02:00.140  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-21 16:02:00.149  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-21 16:02:00.150  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
07-21 16:02:00.151  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-21 16:02:00.152  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-21 16:02:00.153  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-21 16:02:00.157  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-21 16:02:00.159  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C2514A0CC6C8F04ED8328A696DC40F869C31B69A11BBBCB026F182CDB97722C94DFE3BB3F65DE6265D631807046B1E17C]}
07-21 16:02:00.160  5421  5421 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-21 16:02:02.527 10094 10157 I io.jxcore.node.IncomingSocketThreadTest: testRun
,07-21 16:02:02.528 10094 10157 I !!      :  finally closed
,07-21 16:02:02.534 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,07-21 16:02:02.535 10094 10157 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-21 16:02:02.540 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
07-21 16:02:02.541 10094 10157 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-21 16:02:02.544 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,07-21 16:02:02.552 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
07-21 16:02:02.553 10094 10157 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@f90afad Bundle[{}]
,07-21 16:02:02.555 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
07-21 16:02:02.556 10094 10157 I io.jxcore.node.LifeCycleMonitor: start: OK
07-21 16:02:02.556 10094 10157 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-21 16:02:02.558 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
07-21 16:02:02.558 10094 10157 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-21 16:02:02.561 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
07-21 16:02:02.561 10094 10157 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-21 16:02:02.563 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,07-21 16:02:02.564 10094 10157 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-21 16:02:02.566 10094 10157 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
07-21 16:02:02.567 10094 10157 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-21 16:02:02.572 10094 10157 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,07-21 16:02:02.574 10094 10157 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,07-21 16:02:02.576 10094 10157 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,07-21 16:02:02.578 10094 10157 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,07-21 16:02:02.580 10094 10157 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,07-21 16:02:02.582 10094 10157 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,07-21 16:02:02.584 10094 10157 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,07-21 16:02:02.589 10094 10583 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
07-21 16:02:02.589 10094 10583 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-21 16:02:02.593  3291  3772 D EnterpriseController: netId is 0
07-21 16:02:02.593  3291  3772 D Netd    : getNetworkForDns: using netid 0 for uid 10033
07-21 16:02:02.593  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-21 16:02:02.596 10094 10585 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
07-21 16:02:02.596 10094 10585 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-21 16:02:02.596 10094 10585 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-21 16:02:02.597 10094 10583 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
07-21 16:02:02.597 10094 10583 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-21 16:02:02.597 10094 10585 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-21 16:02:02.597 10094 10583 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-21 16:02:02.597 10094 10585 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
07-21 16:02:02.597 10094 10583 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-21 16:02:02.598 10094 10583 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,07-21 16:02:02.600 10094 10588 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 234, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.600 10094 10588 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:02:02.600 10094 10588 D io.jxcore.node.StreamCopyingThread:  id: 77
07-21 16:02:02.600 10094 10589 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 235, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.600 10094 10589 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:02.600 10094 10589 D io.jxcore.node.StreamCopyingThread:  id: 78
07-21 16:02:02.600 10094 10587 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 233, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.600 10094 10587 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:02:02.600 10094 10587 D io.jxcore.node.StreamCopyingThread:  id: 77
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 236, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread:  id: 78
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 236, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread:  id: 78
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread:  id: 78
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-21 16:02:02.601 10094 10590 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,07-21 16:02:02.602 10094 10589 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 235, thread name: OutgoingSocketThread/Sender): Socket closed
07-21 16:02:02.602 10094 10589 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 235, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.602 10094 10589 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:02.602 10094 10589 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-21 16:02:02.602 10094 10589 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-21 16:02:02.602 10094 10589 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-21 16:02:02.602 10094 10589 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 235, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.602 10094 10589 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:02.602 10094 10589 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,07-21 16:02:02.604 10094 10590 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-21 16:02:02.604 10094 10590 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-21 16:02:02.604 10094 10590 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-21 16:02:02.604 10094 10590 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-21 16:02:02.604 10094 10590 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 236, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.604 10094 10590 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:02.604 10094 10590 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-21 16:02:02.604 10094 10588 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 234, thread name: IncomingSocketThread/Receiver): Connection reset
07-21 16:02:02.604 10094 10588 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 234, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.604 10094 10588 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:02:02.604 10094 10588 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 20480 and the total number of bytes written 16384
07-21 16:02:02.604 10094 10588 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: Connection reset", this is likely due to peer having disconnected
07-21 16:02:02.604 10094 10588 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
,07-21 16:02:02.605 10094 10588 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 234, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.605 10094 10588 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:02:02.605 10094 10588 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 20480 and the total number of bytes written 16384
07-21 16:02:02.605 10094 10587 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 233, thread name: IncomingSocketThread/Sender): Connection reset
07-21 16:02:02.605 10094 10587 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 233, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.605 10094 10587 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:02:02.605 10094 10587 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-21 16:02:02.605 10094 10587 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Connection reset
07-21 16:02:02.605 10094 10587 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-21 16:02:02.605 10094 10587 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 233, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:02.605 10094 10587 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-21 16:02:02.605 10094 10587 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,07-21 16:02:04.151  3675  3861 D SamsungAlarmManager: Expired : 4
,07-21 16:02:04.152  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161841, SetElapsed=1219386, nowELAPSED=221933
07-21 16:02:04.153  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170721T160300, SetElapsed=277781, nowELAPSED=221934
,07-21 16:02:04.153  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@af38430 alarm=Alarm{d8c7ede type 2 when 221932 android}
,07-21 16:02:04.157  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,07-21 16:02:04.161 10493 10493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-21 16:02:04.161 10493 10493 I wpa_supplicant: P2P: Current p2p state = IDLE
07-21 16:02:04.164  3675  3925 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160220 - CU:1000/CP:3675
,07-21 16:02:04.165  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237938, nowELAPSED=221946
,07-21 16:02:04.169  3675  3954 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160219 - CU:1000/CP:3675
,07-21 16:02:04.174  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:02:04.195 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:02:04.216 10493 10493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-21 16:02:04.354  4645  4645 D io_stats: !@   8,0 r 26157 2322196 w 5089 205124 d 683 73932 f 2033 2033 iot 11760 10973 th 479132 0 0 pt 0 inp 0 0 222.134
,07-21 16:02:04.871  3675  5817 D SSRM:f  : SIOP:: AP = 270, PST = 271 (W:10), CP = 223, CUR = -5, LCD = 57
,07-21 16:02:05.781  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:02:05.782  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-21 16:02:05.784  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:02:05.784  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:02:05.988  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:02:05.991 10493 10493 I wpa_supplicant: nl80211: Received scan results (54 BSSes)
,07-21 16:02:05.992  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:02:05.992  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:02:05.998  3675  3954 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@b49ab8c
,07-21 16:02:06.092  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:02:06.106 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:02:06.132  3675  3925 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=4 roam=false
,07-21 16:02:06.135  3675  3925 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=4
,07-21 16:02:06.157  3675  3925 D WifiConfigStore: saveNetwork skipInternetCheck
,07-21 16:02:06.168  3675  3925 D WifiConfigStore: readNetwork skipInternetCheck
,07-21 16:02:06.188  3675 10591 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-21 16:02:06.188  3675 10591 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
,07-21 16:02:06.190  3675 10591 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-21 16:02:06.190  3675 10591 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-21 16:02:06.190  3675 10591 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-21 16:02:06.190  3675 10591 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-21 16:02:06.191  3675 10591 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-21 16:02:06.191  3675 10591 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-21 16:02:06.191  3675 10591 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-21 16:02:06.191  3675 10591 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
,07-21 16:02:06.192  3675 10591 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-21 16:02:06.192  3675 10591 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,07-21 16:02:06.197  3675  3925 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=4
,07-21 16:02:06.198  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-21 16:02:06.198  3675  3675 D WifiHs20Service: reason: 2
,07-21 16:02:06.200  3675  3952 I WifiHs20Service: Message received 5014
07-21 16:02:06.200  3675  3952 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-21 16:02:06.203  3675 10592 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
,07-21 16:02:06.203  3675 10592 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-21 16:02:06.204  3675 10592 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
,07-21 16:02:06.204  3675 10592 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
,07-21 16:02:06.205 10493 10493 I wpa_supplicant: Trying to associate with F4.E6.C2 (SSID='NG700' freq=2472 MHz)
,07-21 16:02:06.206  3675 10592 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-21 16:02:06.206  3675 10592 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-21 16:02:06.207  3675 10592 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-21 16:02:06.207  3675 10592 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-21 16:02:06.207  3675  3925 D SecContentProvider: insert(), uri = 2
07-21 16:02:06.208  3675 10592 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-21 16:02:06.208  3675 10592 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-21 16:02:06.209  3675 10592 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-21 16:02:06.210  3675 10592 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,07-21 16:02:06.216  3675  3925 D SecContentProvider: called from android.uid.system:1000
,07-21 16:02:06.256  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:02:06.267 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:02:06.395  3291  3769 D Netd    : Iface wlan0 link up
07-21 16:02:06.395  3291  3769 D Netd    : Iface wlan0 link up
07-21 16:02:06.395  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:02:06.399  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
,07-21 16:02:06.400  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:02:06.403  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:02:06.404  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:02:06.407 10493 10493 I wpa_supplicant: Associated with F4.E6.C2
07-21 16:02:06.410  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:02:06.410  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:02:06.413 10493 10493 I wpa_supplicant: wlan0: CTRL-EVENT-SUBNET-STATUS-UPDATE status=0
,07-21 16:02:06.423  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:02:06.429  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:02:06.434 10493 10493 I wpa_supplicant: WPA: Key negotiation completed with F4.E6.C2 [PTK=CCMP GTK=CCMP]
07-21 16:02:06.434 10493 10493 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.E6.C2 completed [id=4 id_str=%7B%22creatorUid%22%3A%221000%22%2C%22configKey%22%3A%22%5C%22NG700%5C%22WPA_PSK%22%7D]
,07-21 16:02:06.435  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:02:06.437  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:02:06.437  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
07-21 16:02:06.439 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-21 16:02:06.441  3675  3925 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-21 16:02:06.445 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:02:06.447  3675  3925 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@12dd8bf
,07-21 16:02:06.449  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161841, SetElapsed=1219386, nowELAPSED=224229
,07-21 16:02:06.449  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-21 16:02:06.449  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-21 16:02:06.450  3675  3952 I WifiHs20Service: Message received 5007
07-21 16:02:06.451  3675  4012 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-21 16:02:06.452  3675  3925 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: mIsSupportAdvancedCaptivePortal is true
07-21 16:02:06.453  3675  3925 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-21 16:02:06.453  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=69632 obj=com.android.internal.util.AsyncChannel@ddd978d target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:06.453  3675 10593 D NetworkMonitor: Async - Half connection with WWSM established
07-21 16:02:06.453  3675  4012 D WifiWatchdogStateMachine: Async - Half connection with NetworkMonitor established
07-21 16:02:06.453  3675  4012 D WifiWatchdogStateMachine: Async - Full connection with NetworkMonitor established
07-21 16:02:06.453  3675  3956 D ConnectivityService: Got NetworkAgent Messenger
,07-21 16:02:06.454  3675  3956 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-21 16:02:06.454  3675  3956 D ConnectivityService: NetworkAgent connected
,07-21 16:02:06.456  4041  4041 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-21 16:02:06.457  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-21 16:02:06.461  3675  3921 D WifiP2pService: InactiveState{ what=143375 }
07-21 16:02:06.461  3675  3921 D WifiP2pService: P2pEnabledState{ what=143375 }
07-21 16:02:06.462 10217 10217 D BluetoothUtils: readSalesCode :: sales code is XEO
07-21 16:02:06.462  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:02:06.463  3675  3925 D WifiHAL : Getting APF capabilities, halHandle = 0x7985c8e9c0
07-21 16:02:06.463  3675  3925 I WifiHAL : 
07-21 16:02:06.463  3675  3925 I WifiHAL : createRequest: APF get capabilities request
07-21 16:02:06.465  3675  3925 D WifiHAL : In SetAPFCommand::handleResponse
07-21 16:02:06.465  3675  3925 D WifiHAL : Id = 0, subcmd = 0, len = 16
07-21 16:02:06.466  3675  3925 D WifiHAL : Response recieved for get packet filter capabilities command
07-21 16:02:06.466  3675  3925 I WifiHAL : APF version is 2
07-21 16:02:06.466  3675  3925 I WifiHAL : APF max len is 2048
07-21 16:02:06.466  3675  3925 I WifiHAL : Done!
07-21 16:02:06.466  3675  3925 D WifiHAL : Getting APF capability, version = 2, max_len = 2048
07-21 16:02:06.466  3675  3925 D wifi    : APF version supported: 2
07-21 16:02:06.466  3675  3925 D wifi    : Maximum APF program size: 2048
,07-21 16:02:06.469  3675  3925 D WifiStateMachine: Start Dhcp Watchdog 2
,07-21 16:02:06.476  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:02:06.483 10384 10384 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-21 16:02:06.490 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:02:06.502  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-21 16:02:06.503  3675  3956 D ConnectivityService: ignoring duplicate network state non-change
,07-21 16:02:06.503  3675  3925 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true)
07-21 16:02:06.503  3675  3925 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true) returned: -95
07-21 16:02:06.503  3675  3956 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-21 16:02:06.503  3675  3956 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-21 16:02:06.503  3675  3956 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
07-21 16:02:06.503  3675  3925 D WifiHAL : Setting APF program, halHandle = 0x7985c8e9c0
07-21 16:02:06.503  3675  3925 I WifiHAL : 
07-21 16:02:06.503  3675  3925 I WifiHAL : createRequest: APF set program request
07-21 16:02:06.504  3675  3925 I WifiHAL : Done!
07-21 16:02:06.505  3675  3925 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-21 16:02:06.511 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-21 16:02:06.511 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-21 16:02:06.511 10398 10398 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-21 16:02:06.512 10398 10398 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-21 16:02:06.517 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-21 16:02:06.520  3675 10594 D ApfFilter: (wlan0): begin monitoring
,07-21 16:02:06.525 10411 10411 I PhoneErrorReceiver: onReceive
,07-21 16:02:06.535 10493 10493 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-21 16:02:06.546 10007 10007 I usagelog: received in receiver
07-21 16:02:06.546 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-21 16:02:06.546 10007 10007 I KnoxUsageLogPro: premStatus:2
07-21 16:02:06.547 10007 10007 I KnoxUsageLogPro: isEulaShown : false
07-21 16:02:06.547 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-21 16:02:06.564  3675  3931 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170721T160242 - CU:1000/CP:3675
07-21 16:02:06.564  3675  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160242, SetElapsed=260342, nowELAPSED=224345
,07-21 16:02:06.566  3675  4012 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-21 16:02:06.566  3675  3956 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
,07-21 16:02:06.566  3675  4012 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-21 16:02:06.566  3675  4012 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
07-21 16:02:06.567  3675  4012 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-21 16:02:06.567  3675  4012 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-21 16:02:06.625  3675  3931 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170721T160242 - CU:1000/CP:3675
,07-21 16:02:06.638  3675  3685 I art     : Background sticky concurrent mark sweep GC freed 172629(13MB) AllocSpace objects, 24(528KB) LOS objects, 26% free, 41MB/56MB, paused 4.084ms total 104.799ms
,07-21 16:02:06.746  3675  3921 D WifiP2pService: InactiveState{ what=143375 }
,07-21 16:02:06.747  3675  3921 D WifiP2pService: P2pEnabledState{ what=143375 }
07-21 16:02:06.749  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=-3ms what=131307 obj=start target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:02:06.760  3675 10595 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170721T160208 - CU:1000/CP:3675
07-21 16:02:06.761  3675 10595 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160208, SetElapsed=226545, nowELAPSED=224542
,07-21 16:02:06.792  3675 10595 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-21 16:02:06.793  3675 10595 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@886a29f
,07-21 16:02:06.796  3675 10595 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160242, SetElapsed=260342, nowELAPSED=224576
,07-21 16:02:06.802  3675 10595 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170721T160224 - CU:1000/CP:3675
07-21 16:02:06.802  3675 10595 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160224, SetElapsed=242577, nowELAPSED=224583
,07-21 16:02:06.813  3675 10595 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170721T160208 - CU:1000/CP:3675
07-21 16:02:06.813  3675 10595 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160208, SetElapsed=226398, nowELAPSED=224594
,07-21 16:02:06.840  3675 10595 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-21 16:02:06.841  3675  3931 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@20bfcf9
07-21 16:02:06.841  3675 10595 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@544e64a
,07-21 16:02:06.844  3675 10595 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160224, SetElapsed=242577, nowELAPSED=224625
07-21 16:02:06.845  3675 10595 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@7866fb5
,07-21 16:02:06.850  3675 10595 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160242, SetElapsed=260342, nowELAPSED=224631
,07-21 16:02:06.855  3675  3921 D WifiP2pService: InactiveState{ what=143375 }
07-21 16:02:06.856  3675  3921 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-21 16:02:06.858  3291  3777 D CommandListener: Setting iface cfg
,07-21 16:02:06.866  3675  4012 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-21 16:02:06.867  3675  3956 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-21 16:02:06.869  3675  3956 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-21 16:02:06.871  3675  4012 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-21 16:02:06.872  3675  4012 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-21 16:02:06.873  3675  4012 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
07-21 16:02:06.874  3675  3925 D WifiHAL : Setting APF program, halHandle = 0x7985c8e9c0
07-21 16:02:06.874  3675  4012 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-21 16:02:06.874  3675  3931 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@a5c07c0
07-21 16:02:06.875  3675  3925 I WifiHAL : 
07-21 16:02:06.875  3675  3925 I WifiHAL : createRequest: APF set program request
07-21 16:02:06.876  3675  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161841, SetElapsed=1219386, nowELAPSED=224657
07-21 16:02:06.878  3675  4012 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-21 16:02:06.878  3675  3925 I WifiHAL : Done!
07-21 16:02:06.879  3675  3956 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-21 16:02:06.880  3675  3956 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-21 16:02:06.880  3675  4012 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-21 16:02:06.884  3675  4012 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-21 16:02:06.886  3675  3925 E WifiNative-HAL: setBssidBlacklist cmd 2 size 0
07-21 16:02:06.886  3675  4012 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-21 16:02:06.886  3675  3925 D wifi    : configure BSSID black list request [4] = 0x7985c8e9c0
07-21 16:02:06.886  3675  3925 D wifi    : Added 0 bssids
07-21 16:02:06.887  3675  3925 E WifiHAL : Failed to execute bssid blacklist request, result = -95
07-21 16:02:06.887  3675  3925 D WifiStateMachine: sendConnectedState - setManualConnection: false!
07-21 16:02:06.888  3675  4012 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-21 16:02:06.889  3675  3956 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-21 16:02:06.890  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-21 16:02:06.893  3675  3956 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
07-21 16:02:06.893  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-21 16:02:06.893  3675  3956 D ConnectivityService: Adding iface wlan0 to network 503
07-21 16:02:06.894  3675  3952 I WifiHs20Service: Message received 5007
,07-21 16:02:06.898  3675  4012 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-21 16:02:06.902  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:02:06.902  4041  4041 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-21 16:02:06.907 10217 10217 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-21 16:02:06.914  3675 10595 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170721T214742 - CU:1000/CP:3675
07-21 16:02:06.916  3675  3925 D SecContentProvider: insert(), uri = 2
07-21 16:02:06.917  3675  3925 D SecContentProvider: called from android.uid.system:1000
07-21 16:02:06.917  3241  3241 E audit   : type=1320 audit(1500645726.906:552): 
07-21 16:02:06.917  3675 10595 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170722T023206 - CU:1000/CP:3675
07-21 16:02:06.918  3675  3925 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-21 16:02:06.920  3675  3925 I WifiConnectivityManager: scheduleWatchdogTimer
,07-21 16:02:06.921  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:02:06.922  3675  3675 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-21 16:02:06.925  3675  3675 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-21 16:02:06.926  3675  3675 D HS20StateMachine: SSID : "NG700"
07-21 16:02:06.926  3675  3675 D HS20StateMachine: NetId : 4
07-21 16:02:06.926  3675  3675 D HS20StateMachine: checkifOSUAP  null
07-21 16:02:06.926  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-21 16:02:06.926  3675  3952 I WifiHs20Service: Message received 5007
,07-21 16:02:06.928  3675  4012 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-21 16:02:06.931  4041  4041 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-21 16:02:06.932  3241  3241 E audit   : type=1320 audit(1500645726.926:553): 
07-21 16:02:06.932  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-21 16:02:06.936 10217 10217 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-21 16:02:06.941  3675  3956 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,07-21 16:02:06.943 10384 10384 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-21 16:02:06.944  3675  3956 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
07-21 16:02:06.945  3675 10595 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170722T040206 - CU:1000/CP:3675
07-21 16:02:06.945  3675 10595 D DhcpClient: Scheduling renewal in 20735s
07-21 16:02:06.945  3675 10595 D DhcpClient: Scheduling rebind in 37799s
07-21 16:02:06.945  3675 10595 D DhcpClient: Scheduling expiry in 43199s
07-21 16:02:06.947  3675  3956 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
07-21 16:02:06.950  3675  3956 D ConnectivityService: Setting DNS servers for network 503 to [/192.168.1.1]
07-21 16:02:06.952  3291  7131 D ResolverController: DNSDBG::server[0] 192.168.1.1
07-21 16:02:06.952  3291  7131 D ResolverController: DNSDBG::netId 503 search_domain lan
07-21 16:02:06.952  3291  7131 D ResolverController: DNSDBG::netId 503 searchDomains lan
07-21 16:02:06.952  3291  7131 D ResolverController: DNSDBG::server[0] 192.168.1.1
,07-21 16:02:06.962  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160529, SetElapsed=427523, nowELAPSED=224743
07-21 16:02:06.963  3675  3925 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T162206 - CU:1000/CP:3675
07-21 16:02:06.963  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T162206, SetElapsed=1424701, nowELAPSED=224744
07-21 16:02:06.964  3675  3956 V NetworkStats: updateIfacesLocked()
07-21 16:02:06.964  3675  3956 V NetworkStats: performPollLocked(flags=0x1)
07-21 16:02:06.964  3675  3956 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:06.975  3675  3925 D WifiStateMachine: isFindLocationId() - Location Id : 1
07-21 16:02:06.980  3675  3925 D WifiGeofenceDBHelper: update() - 1*1500645726975
,07-21 16:02:06.989  3675  3956 V NetworkStats: performPollLocked() took 24ms
07-21 16:02:06.989  3675  3956 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:06.994 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-21 16:02:06.995  3675  3956 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-21 16:02:06.995  3675  3956 D ConnectivityService: Not required to send intent.
07-21 16:02:06.995 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-21 16:02:06.995 10398 10398 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-21 16:02:06.996 10398 10398 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
07-21 16:02:06.996  3675  3956 V NetworkStats: updateIfacesLocked()
07-21 16:02:06.996  3675  3956 V NetworkStats: performPollLocked(flags=0x1)
07-21 16:02:06.996  3675  3956 D NtpTrustedTime: currentTimeMillis() cache hit
,07-21 16:02:07.003  3675  3956 V NetworkStats: performPollLocked() took 7ms
07-21 16:02:07.003  3675  3956 D NtpTrustedTime: currentTimeMillis() cache hit
,07-21 16:02:07.003 10411 10411 I PhoneErrorReceiver: onReceive
,07-21 16:02:07.007  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:07.007  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:07.007  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:07.008  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:07.008  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:07.008  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
07-21 16:02:07.008  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: register CaptivePortalReceiver
07-21 16:02:07.008  3675  3956 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
07-21 16:02:07.008  3675  3956 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-21 16:02:07.009  3675  3956 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-21 16:02:07.009  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.009  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.009  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.009  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
,07-21 16:02:07.009  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.010  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.010  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.010  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.010  3675  3956 D ConnectivityService: currentScore = 0, newScore = 20
07-21 16:02:07.010  3675  3956 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
07-21 16:02:07.010  3675  3956 D ConnectivityService:    accepting network in place of null
07-21 16:02:07.010  3675  3956 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.010  3675  3921 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.011  3675  3921 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:02:07.011  3675  3921 D WIFI_P2P: evalRequest
07-21 16:02:07.011  3675  3921 D WIFI_P2P:   done
,07-21 16:02:07.011  3675  4021 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.011  3675  4021 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-21 16:02:07.011  3675  4021 D Ethernet: evalRequest
07-21 16:02:07.011  3675  4021 D Ethernet:   done
,07-21 16:02:07.012  4041  4041 D PhoneSwitcherNetworkRequstListener: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-21 16:02:07.012  4041  4041 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-21 16:02:07.013  4041  4041 D PhoneSwitcherNetworkRequstListener: evalRequest
07-21 16:02:07.013  4041  4041 D PhoneSwitcherNetworkRequstListener:   done
07-21 16:02:07.013 10007 10007 I usagelog: received in receiver
07-21 16:02:07.013 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-21 16:02:07.013 10007 10007 I KnoxUsageLogPro: premStatus:2
07-21 16:02:07.013  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:02:07.014  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.014  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.014  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.014  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.015  3675  3956 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-21 16:02:07.015 10007 10007 I KnoxUsageLogPro: isEulaShown : false
07-21 16:02:07.015 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-21 16:02:07.024  3675  4012 D WifiWatchdogStateMachine: Connected - Move to CaptivePortalState
,07-21 16:02:07.032  3241  3241 E audit   : type=1320 audit(1500645727.026:554): 
,07-21 16:02:07.033  3675  4012 E WifiWatchdogStateMachine: current state: com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalState@3f9b791
,07-21 16:02:07.035  3675  4012 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-21 16:02:07.043 10384 10384 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-21 16:02:07.043  3675  3925 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-21 16:02:07.043 10384 10384 W [RBL] ServiceReceiver: @onReceive - NETWORK_STATE_CHANGED_ACTION
07-21 16:02:07.044 10370 10602 I DatabaseHelper: android.app.Application@2efb2e2
,07-21 16:02:07.044 10370 10602 I DatabaseHelper: Create a DatabaseHelper
,07-21 16:02:07.047  3675  4012 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-21 16:02:07.047  3241  3241 E audit   : type=1320 audit(1500645727.036:555): 
07-21 16:02:07.048  3675  4012 D WifiWatchdogStateMachine: start to check Captive portal
,07-21 16:02:07.048  3291  3777 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-21 16:02:07.054  3675  3925 D SLocation: system
07-21 16:02:07.054  3675  3925 D SLocation: startGeofence ID = 1
,07-21 16:02:07.060  3241  3241 E audit   : type=1320 audit(1500645727.056:556): 
,07-21 16:02:07.076  3241  3241 E audit   : type=1320 audit(1500645727.066:557): 
,07-21 16:02:07.077  3291  3777 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-21 16:02:07.081 10370 10602 I DataManager: checkResolution
,07-21 16:02:07.084 10370 10602 I DataManager: Create a DataManager
07-21 16:02:07.086 10384 10384 D [RBL] StoredRequest: @Oncreate
07-21 16:02:07.087  3675  3925 E SLocation: id 1 is already started
07-21 16:02:07.087  3675  3925 D WifiStateMachine: startGeofence() - id : 1, ERROR !!, mResult : -5
07-21 16:02:07.087  3675  3925 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-21 16:02:07.087  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.087 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-21 16:02:07.088  3675  3925 D SLocation: system
07-21 16:02:07.088  3675  3925 D SLocation: startLearning ID = 1
07-21 16:02:07.088  3675  3925 D SLocation: setLearningStatus ID = 1 / status = true
07-21 16:02:07.088  3675  3925 D WifiStateMachine: ConnectedState - enter() - startLearning id : 1
07-21 16:02:07.088  3675  3925 D WifiStateMachine: ConnectedState()- id : 1,  startLearning Success !!
07-21 16:02:07.088  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.088 10384 10384 I [RBL] GuardedSuspension: @getInstance
07-21 16:02:07.088 10384 10384 I [RBL] GuardedSuspension: GuardedSuspension
07-21 16:02:07.089  3675  3925 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-21 16:02:07.089  4528  4604 D GeolocationController: WIFI : onAvailable
07-21 16:02:07.090  3675  3925 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.090  3675  3925 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:02:07.090  3675  3925 D WIFI    : evalRequest
07-21 16:02:07.090  3675  3925 D WIFI    :   done
07-21 16:02:07.090  3675  3925 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-21 16:02:07.090  3675  3925 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:02:07.090  3675  3925 D WIFI_UT : evalRequest
07-21 16:02:07.090  3675  3925 D WIFI_UT :   done
07-21 16:02:07.090 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-21 16:02:07.090 10398 10398 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-21 16:02:07.090  3675  3925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-21 16:02:07.092  3675  3785 D EntConnectivity: Not allowed due to - mEnabled false
07-21 16:02:07.092  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.092  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:02:07.093  4528  4604 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [true]
07-21 16:02:07.093 10384 10384 I [RBL] GuardedSuspension: @getInstance
07-21 16:02:07.093 10384 10384 D [RBL] RblSAccountUtil: @open
07-21 16:02:07.093  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.093 10384 10384 D [RBL] RblSAccountUtil:     - client : 1
07-21 16:02:07.093  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.094  4528  4614 D PdnController: handleMessage: what 105
07-21 16:02:07.094  4528  4614 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [true]
07-21 16:02:07.095  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.095  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:02:07.095  4528  4614 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [true]
07-21 16:02:07.095  4528  4614 D ResipRegiMgr: handleMessage(): 3
07-21 16:02:07.095  4528  4614 D RegiMgrBase: handleMessage: what 3
07-21 16:02:07.095  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.096  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.096  3675  3956 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.096  3675  3956 D ConnectivityService: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-21 16:02:07.097  3675  3956 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-21 16:02:07.098 10398 10398 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 android.content.ContextWrapper.sendBroadcast:452 android.content.ContextWrapper.sendBroadcast:452 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3306 
,07-21 16:02:07.101  3675  3785 D EntConnectivity: Not allowed due to - mEnabled false
,07-21 16:02:07.105  4528  4614 D RegiMgrBase: onNetworkEventChanged: new=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=true, isEpdgConnected=false]
,07-21 16:02:07.105  4528  4614 D RegiMgrBase: onNetworkEventChanged: old=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=false, isEpdgConnected=false]
,07-21 16:02:07.105  4528  4614 D RegiMgrBase: out of service.
07-21 16:02:07.105  4528  4614 D RegiMgrBase: onNetworkEventChanged: nTask= 0 nRegisteredTask= 0 bExistRetryTimer= false bHaveRegisteringTask= false
07-21 16:02:07.106  3675  3956 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
07-21 16:02:07.106  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.106  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:02:07.107  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:02:07.107  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:02:07.107  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:02:07.107  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.108  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.108  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.108  4528  4614 D RegiMgrBase: onNetworkEventChanged: tryRegister
07-21 16:02:07.108  4528  4614 D RegiMgrBase: tryRegister:
07-21 16:02:07.108  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.109  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.109  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.109  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.109  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.110  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.110  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.110  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.110  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-21 16:02:07.110  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.110  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.110  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.110  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.111  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.111  3675  3956 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.111  3675  3956 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-21 16:02:07.112  3675  3675 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-21 16:02:07.112  3675  3912 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-21 16:02:07.112  3675  3675 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = false
07-21 16:02:07.112  3675  3912 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-21 16:02:07.112  3675  3912 D EnterprisePremiumVpnPolicyServiceV2: run all vpn : runAllVpnService beginning
07-21 16:02:07.113  4528  4614 D RegiMgrBase: RegisterTask(s) -
07-21 16:02:07.113  4528  4614 D ResipRegiMgr: handleMessage(): 32
07-21 16:02:07.113  4528  4614 D RegiMgrBase: handleMessage: what 32
07-21 16:02:07.113  4528  4614 D RegiMgrBase: onPendingUpdateRegistration: 
07-21 16:02:07.114  3675  3675 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-21 16:02:07.114  3675  3675 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-21 16:02:07.114  3675  3913 I KnoxVpnEngineService: vpn handle : Message received
07-21 16:02:07.114  3675  3913 I KnoxVpnEngineService: vpn handle : Message received
07-21 16:02:07.114  3675  3913 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = false
07-21 16:02:07.114  3675  3913 D KnoxVpnEngineService: run all vpn : runAllVpnService beginning
07-21 16:02:07.116  3675  3675 D Tethering: Tethering got CONNECTIVITY_ACTION
07-21 16:02:07.116  3675  3958 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-21 16:02:07.116  3675  3958 D Tethering: MasterInitialState.processMessage what=327683
07-21 16:02:07.121  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:02:07.124  4068  4289 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
,07-21 16:02:07.129 10384 10384 D [RBL] RblSAccountUtil:     - DB is opened
,07-21 16:02:07.129 10384 10384 D [RBL] CellDbHelper: @open
07-21 16:02:07.129 10384 10384 D [RBL] CellDbHelper:     - client : 1
07-21 16:02:07.130  5251  5251 I CastMediaRouteProvider: Network connectivity changed
07-21 16:02:07.131  3675  3916 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
07-21 16:02:07.131  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:07.131  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:07.132  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:07.132  3675  3916 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-21 16:02:07.132  3675  3916 D NtpTrustedTime: currentTimeMillis() cache hit
07-21 16:02:07.133  3675  3916 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
07-21 16:02:07.140  3675  3675 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-21 16:02:07.140  3675  4488 D SLocation: checkWifiInfo
,07-21 16:02:07.141  3675  3675 V MARsPolicyManager: DataConnection: true
07-21 16:02:07.144  3675  4038 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-21 16:02:07.149  3675  4038 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-21 16:02:07.152  9398  9398 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-21 16:02:07.152  9398  9398 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
07-21 16:02:07.155  9459  9459 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@a2e50cb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:02:07.157  9398  9398 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
07-21 16:02:07.157  9398  9398 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
07-21 16:02:07.157  9398  9398 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-21 16:02:07.160 10384 10384 D [RBL] CellDbHelper:     - DB is opened
07-21 16:02:07.160 10384 10384 D [RBL] PolicyDbHelper: @open
07-21 16:02:07.160 10384 10384 D [RBL] PolicyDbHelper:     - client : 1
07-21 16:02:07.163  4959  4959 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-21 16:02:07.166  9459  9459 I NetworkConnectivity: Network state changed: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]
07-21 16:02:07.170 10411 10411 I PhoneErrorReceiver: onReceive
07-21 16:02:07.174  3675  4488 D SLocation: cellLocation is null
07-21 16:02:07.178 10094 10094 D BluetoothAdapter: STATE_ON
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-21 16:02:07.183 10094 10094 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-21 16:02:07.186 10094 10094 D BluetoothAdapter: STATE_ON
07-21 16:02:07.190  9459  9459 I NetworkPolicyMonitor: Download-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-21 16:02:07.191 10094 10094 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-21 16:02:07.191 10384 10384 D [RBL] PolicyDbHelper:     - DB is opened
07-21 16:02:07.193 10384 10607 D [RBL] StoredRequest: @onHandleIntent
07-21 16:02:07.195 10007 10007 I usagelog: received in receiver
07-21 16:02:07.195 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-21 16:02:07.195 10007 10007 I KnoxUsageLogPro: premStatus:2
07-21 16:02:07.196 10007 10007 I KnoxUsageLogPro: isEulaShown : false
07-21 16:02:07.196 10007 10007 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-21 16:02:07.211 10384 10384 D [RBL] CellDbHelper: @close
07-21 16:02:07.211 10384 10384 D [RBL] CellDbHelper:     - client : 0
07-21 16:02:07.212 10384 10384 D [RBL] CellDbHelper:     - DB is closed
07-21 16:02:07.212 10384 10384 D [RBL] PolicyDbHelper: @close
07-21 16:02:07.212 10384 10384 D [RBL] PolicyDbHelper:     - client : 0
07-21 16:02:07.212 10384 10384 D [RBL] PolicyDbHelper:     - DB is closed
07-21 16:02:07.212 10384 10384 D [RBL] RblSAccountUtil: @close
07-21 16:02:07.212 10384 10384 ,D [RBL] RblSAccountUtil:     - client : 0
07-21 16:02:07.212 10384 10384 D [RBL] RblSAccountUtil:     - DB is closed
07-21 16:02:07.212 10384 10384 D [RBL] StoredRequest: @onDestroy
07-21 16:02:07.215  3291  3772 D EnterpriseController: netId is 0
07-21 16:02:07.215  3291  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10001
07-21 16:02:07.215  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-21 16:02:07.244  3291  3772 D EnterpriseController: netId is 0
07-21 16:02:07.244  3291  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-21 16:02:07.244  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-21 16:02:07.248  3675  3927 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@1a66620 displayId=0
07-21 16:02:07.249  3675  3927 D InputTransport: Input channel constructed: fd=461
07-21 16:02:07.250  3675  3927 D InputTransport: Input channel constructed: fd=462
07-21 16:02:07.251  3675  3927 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
07-21 16:02:07.253  3675  3927 D InputTransport: Input channel destroyed: fd=462
07-21 16:02:07.253  5251  5251 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-21 16:02:07.253  4068  4289 D InputTransport: Input channel constructed: fd=149
07-21 16:02:07.254  4068  4289 D ViewRootImpl@3d82468[Toast]: setView = android.widget.LinearLayout{e8f6081 V.E...... ......I. 0,0-0,0 #10204d0 android:id/toast_layout_root} touchMode=true
07-21 16:02:07.260  9459  9459 I NetworkPolicyMonitor: Stream-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-21 16:02:07.263  3675  4488 D SLocation: geofence id (1) detected : 0
07-21 16:02:07.266  3675  4942 V WindowManager: Relayout Window{acb399ed0 u0 Toast}: viewVisibility=0 req=755x150 WM.LayoutParams{(0,192)(wrapxwrap) gr=#51 sim=#20 ty=2005 fl=#1040088 fmt=-3 wanim=0x1030004 naviIconColor=0}
07-21 16:02:07.270  3112  3112 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=4, Uoast
07-21 16:02:07.280  3675  4942 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3675 ws=WorkSource{10062} pkg=android
07-21 16:02:07.280  3675  4942 D PowerManagerService: mDisplayReady: false
07-21 16:02:07.283  3675  3790 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-21 16:02:07.283  3675  3790 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-21 16:02:07.284  3675  3790 D DisplayPowerController: Tracking Direct to etc : 107
07-21 16:02:07.284  3675  3790 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
07-21 16:02:07.284  3675  3790 D DisplayPowerController: Animating brightness: target=107, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-21 16:02:07.284  3675  3790 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-21 16:02:07.284  3675  3790 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-21 16:02:07.284  3675  3790 D DisplayPowerController: getFinalBrightness : Summary is 107 -> 107
07-21 16:02:07.284  3675  3790 D DisplayPowerController: Animating brightness: target=107, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-21 16:02:07.285  3675  3790 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-21 16:02:07.285  3675  3790 D PowerManagerService: mDisplayReady: true
07-21 16:02:07.285 10240 10608 D NetworkSecurityConfig: No Network Security Config specified, using platform default
07-21 16:02:07.286  5251  8204 I iu.UploadsManager: num queued entries: 0
07-21 16:02:07.286  3675  4036 D lights  : lcd : 107 +
07-21 16:02:07.292  9459  9459 I DevicePlayback: Got network change: mobile=falsewifi=true
07-21 16:02:07.292  9459  9459 I DevicePlayback: Connectivity restored - clearing all queued disable runnables
,07-21 16:02:07.295  3675  4036 D lights  : lcd : 107 -
07-21 16:02:07.298  5251  8204 I iu.UploadsManager: num updated entries: 0
07-21 16:02:07.300  3675  4036 D DisplayPowerState: Tracking!!: 107
07-21 16:02:07.298 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:07.301 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:07.306  4068  4227 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [755x150]-format:1
07-21 16:02:07.309  5251  8204 I iu.SyncManager: NEXT; no task
07-21 16:02:07.311  4068  4289 D ViewRootImpl@3d82468[Toast]: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-21 16:02:07.313 10476 10476 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
07-21 16:02:07.314 10476 10476 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? ]
07-21 16:02:07.314 10476 10476 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
07-21 16:02:07.324  5251  5710 W MdnsClient_Cast: #acquireLock. Multicast lock not held. Acquiring. Subtypes:"805741C9"
07-21 16:02:07.326  3675  3925 D WifiHAL : Setting APF program, halHandle = 0x7985c8e9c0
07-21 16:02:07.326  3675  3925 I WifiHAL : 
07-21 16:02:07.326  3675  3925 I WifiHAL : createRequest: APF set program request
07-21 16:02:07.328  3291  3772 D EnterpriseController: netId is 0
07-21 16:02:07.329  3291  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10135
07-21 16:02:07.329  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-21 16:02:07.332  3675  3925 I WifiHAL : Done!
,07-21 16:02:07.343 10476 10476 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-21 16:02:07.343 10476 10476 I SA      : [OR] == isSIMCardReady false ==
,07-21 16:02:07.344 10476 10476 I SA      : [SCU] == networkStateCheck == true
07-21 16:02:07.345 10476 10476 I SA      : [DM] getCountryCodeFromCSC : PL
07-21 16:02:07.345 10476 10476 I SA      : isChinaCountryCode : false
07-21 16:02:07.345 10476 10476 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-21 16:02:07.346 10476 10476 I SA      : [OR] == networkStateCheck true ==
07-21 16:02:07.346  9459  9513 I DevicePlayback: Allowing woodstock playback due to restored connection
07-21 16:02:07.354  3675  4946 D WindowManager: finishDrawingWindow: Window{acb399ed0 u0 Toast} mDrawState=DRAW_PENDING
,07-21 16:02:07.367  3675  4946 D WifiScanController: isNLPPackage:com.google.android.gms, true
,07-21 16:02:07.370  3675  3925 I WifiScanController: location is disabled
,07-21 16:02:07.375  3675  3920 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170721T163207 - CU:10124/CP:5163
,07-21 16:02:07.382  3675  4018 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: GW is reachable. - 234 msec.
07-21 16:02:07.383 10476 10476 I SA      : [OR] GetMyCountryZoneTask
07-21 16:02:07.383 10476 10476 I SA      : [OR] onReceive END
,07-21 16:02:07.409 10502 10502 I SVCAgent: Ignore network change.
,07-21 16:02:07.419 10515 10515 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-21 16:02:07.430  4068  4209 D vol.MediaSessions: onQueueChanged com.google.android.music []
,07-21 16:02:07.433  8043  8043 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-21 16:02:07.434  8043  8043 E SPPClientService: [SystemStateMoniter] Current Time : 225214
,07-21 16:02:07.437  8043  8043 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-21 16:02:07.450 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
07-21 16:02:07.451 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-21 16:02:07.451 10398 10398 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-21 16:02:07.457  3675  4941 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{83c194d: PendingIntentRecord{cc48b54 com.google.android.gms broadcastIntent}}
,07-21 16:02:07.462 10476 10619 I SA      : [SRS] prepareGetMyCountryZone
,07-21 16:02:07.475 10476 10619 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-21 16:02:07.476 10476 10619 I SA      : [SSP] query invoked
,07-21 16:02:07.487 10476 10619 I SA      : [TPMU] GetMccFromDB : null
07-21 16:02:07.487 10476 10619 I SA      : [SCU] getMccFromPreferece mcc = 260
07-21 16:02:07.487 10476 10619 I SA      : [LBE] isSupportCheckDomainRegion : true
,07-21 16:02:07.492 10476 10619 I SA      : [TPM] isNoProxy(default) : true
07-21 16:02:07.495 10476 10619 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-21 16:02:07.507  3675  3720 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170721T161117 - CU:10019/CP:4735
07-21 16:02:07.507  3675  3720 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775272, nowELAPSED=225288
,07-21 16:02:07.514  3675  3920 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
07-21 16:02:07.514  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:07.514  3675 10593 D NetworkMonitor: handled
,07-21 16:02:07.532  3675  4988 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
07-21 16:02:07.532  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:07.532  3675 10593 D NetworkMonitor: handled
07-21 16:02:07.535  3675  4941 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
,07-21 16:02:07.536  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:07.536  3675 10593 D NetworkMonitor: handled
07-21 16:02:07.540  3675  3939 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{874c913: PendingIntentRecord{6bc9329 com.google.android.gms broadcastIntent}}
07-21 16:02:07.540  3675  3939 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T162206, SetElapsed=1424701, nowELAPSED=225321
,07-21 16:02:07.559  3675  3988 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170721T161117 - CU:10019/CP:4735
07-21 16:02:07.559  3675  3988 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775322, nowELAPSED=225340
,07-21 16:02:07.570  3675  3758 I ActivityManager: Waited long enough for: ServiceRecord{8d92101 u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,07-21 16:02:07.571  9847  9858 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-21 16:02:07.575  9847  9858 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-21 16:02:07.578  9847  9858 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-21 16:02:07.580  3675  4544 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170721T165922 - CU:10019/CP:4735
,07-21 16:02:07.584  9847  9859 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-21 16:02:07.586  9847  9859 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-21 16:02:07.587  9847  9859 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-21 16:02:07.594  3675  4018 D WifiWatchdogStateMachine:  [|207]
,07-21 16:02:07.602  3675  4939 D MountService: getExternalStorageMountMode : 1
07-21 16:02:07.602  3675  4939 D MountService: getExternalStorageMountMode : 3
07-21 16:02:07.603  3675  4939 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.soagent
,07-21 16:02:07.626 10626 10626 E Zygote  : v2
07-21 16:02:07.626 10626 10626 I libpersona: KNOX_SDCARD checking this for 1000
07-21 16:02:07.626 10626 10626 I libpersona: KNOX_SDCARD not a persona
07-21 16:02:07.627  3675  4939 I ActivityManager: Start proc 10626:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
07-21 16:02:07.628 10626 10626 E Zygote  : accessInfo : 0
,07-21 16:02:07.637 10626 10626 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:02:07.639 10626 10626 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.soagent 
,07-21 16:02:07.671 10626 10626 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-21 16:02:07.672 10626 10626 D ActivityThread: Added TimaKeyStore provider
,07-21 16:02:07.675  3675  4946 I ActivityManager: DSS on for com.sec.android.soagent and scale is 1.0
,07-21 16:02:07.698 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:07.698 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:07.699 10626 10626 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,07-21 16:02:07.717 10626 10626 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:02:07.771  3675  4941 D MountService: getExternalStorageMountMode : 1
07-21 16:02:07.771  3675  4941 D MountService: getExternalStorageMountMode : 3
07-21 16:02:07.771  3675  4941 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10134, packageName : com.sec.android.app.sbrowser
,07-21 16:02:07.791 10640 10640 E Zygote  : v2
07-21 16:02:07.791 10640 10640 I libpersona: KNOX_SDCARD checking this for 10134
07-21 16:02:07.791 10640 10640 I libpersona: KNOX_SDCARD not a persona
07-21 16:02:07.791 10640 10640 E Zygote  : isSdpEnabledProcess - SDP enabled
07-21 16:02:07.792 10640 10640 E Zygote  : accessInfo : 64
07-21 16:02:07.792 10640 10640 E Zygote  : isSdpEnabledProcess - SDP enabled
07-21 16:02:07.792 10640 10640 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10134 / [uid]: 10134
07-21 16:02:07.793  3675  4941 I ActivityManager: Start proc 10640:com.sec.android.app.sbrowser:CustomLogger/u0a134 for content provider com.sec.android.app.sbrowser/.logging.CustomLoggingProvider
,07-21 16:02:07.803 10640 10640 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:02:07.805 10640 10640 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser:CustomLogger 
,07-21 16:02:07.819  3241  3241 E audit   : type=1320 audit(1500645727.806:558): 
,07-21 16:02:07.832  3241  3241 E audit   : type=1320 audit(1500645727.826:559): 
,07-21 16:02:07.835 10640 10640 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:02:07.835 10640 10640 D ActivityThread: Added TimaKeyStore provider
07-21 16:02:07.837  3675  3927 I ActivityManager: DSS on for com.sec.android.app.sbrowser and scale is 1.0
,07-21 16:02:07.845  3675  4460 E Watchdog: !@Sync 7 [21_lip_16_02_07.845]
,07-21 16:02:07.862  3241  3241 E audit   : type=1320 audit(1500645727.856:560): 
,07-21 16:02:07.867 10640 10640 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_5.0/lib/arm
,07-21 16:02:07.877  3241  3241 E audit   : type=1320 audit(1500645727.866:561): 
,07-21 16:02:07.886 10640 10640 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:02:07.899 10640 10640 I cr_ApplicationStatus: initialize application : com.sec.android.app.sbrowser.SBrowserApplication@17f96f5
,07-21 16:02:07.904 10640 10640 D ReflectField: Cannot load field: SDL_INT
07-21 16:02:07.904 10640 10640 E ReflectField: Incorrect type : Fallback exception
,07-21 16:02:07.904 10640 10640 D ReflectField: Cannot load field: KEYCODE_EMAIL
07-21 16:02:07.904 10640 10640 E ReflectField: Incorrect type : Fallback exception
,07-21 16:02:07.916  3675  4931 D MountService: getExternalStorageMountMode : 1
07-21 16:02:07.917  3675  4931 D MountService: getExternalStorageMountMode : 3
07-21 16:02:07.917  3675  4931 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.wssyncmldm
,07-21 16:02:07.937 10658 10658 E Zygote  : v2
07-21 16:02:07.937 10658 10658 I libpersona: KNOX_SDCARD checking this for 1000
,07-21 16:02:07.937 10658 10658 I libpersona: KNOX_SDCARD not a persona
07-21 16:02:07.938  3675  4931 I ActivityManager: Start proc 10658:com.wssyncmldm/1000 for content provider com.wssyncmldm/com.samsung.android.app.fotaclient.log.MasterLogProvider
07-21 16:02:07.938 10658 10658 E Zygote  : accessInfo : 0
,07-21 16:02:07.946 10658 10658 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:02:07.948 10658 10658 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.wssyncmldm 
,07-21 16:02:07.962  4735 10624 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-21 16:02:07.971  4735 10624 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-21 16:02:07.977 10658 10658 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:02:07.977  3675  4017 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
,07-21 16:02:07.977 10658 10658 D ActivityThread: Added TimaKeyStore provider
07-21 16:02:07.978  3675  4017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
07-21 16:02:07.980  3675  4012 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
07-21 16:02:07.980  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:07.980  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: MaybeNotifyState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:07.980  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:07.980  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: CMD_ACCEPT_UNVALIDATED_WIFI
07-21 16:02:07.980  3675  4543 I ActivityManager: DSS on for com.wssyncmldm and scale is 1.0
07-21 16:02:07.981  3675  3956 D ConnectivityService: NetworkMonitor.CMD_ACCEPT_UNVALIDATED_WIFI network
07-21 16:02:07.981  3675  3956 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-21 16:02:07.981  3675  3956 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-21 16:02:07.981  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.981  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.981  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.981  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:02:07.981  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.981  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-21 16:02:07.981  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.982  3675  3956 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-21 16:02:07.982  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:02:07.982  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-21 16:02:07.982  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.982  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.982  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.982  3675  3956 D ConnectivityService: sending new Min Network Score(100): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.983  3675  3925 D WIFI    : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.983  3675  3925 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:02:07.983  3675  3925 D WIFI    : evalRequest
07-21 16:02:07.983  3675  3925 D WIFI    :   releaseNetworkFor
07-21 16:02:07.983  3675  3925 D WIFI_UT : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.983  3675  3925 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:02:07.983  4041  4041 D PhoneSwitcherNetworkRequstListener: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.983  3675  3925 D WIFI_UT : evalRequest
07-21 16:02:07.983  3675  3925 D WIFI_UT :   done
07-21 16:02:07.983  4041  4041 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-21 16:02:07.983  4041  4041 D PhoneSwitcherNetworkRequstListener: evalRequest
07-21 16:02:07.983  4041  4041 D PhoneSwitcherNetworkRequstListener:   done
07-21 16:02:07.984  3675  4021 D Ethernet: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.984  3675  4021 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-21 16:02:07.984  3675  4021 D Ethernet: evalRequest
07-21 16:02:07.984  3675  4021 D Ethernet:   done
,07-21 16:02:07.986  3675  3921 D WIFI_P2P: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-21 16:02:07.986  3675  3921 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-21 16:02:07.986  3675  3921 D WIFI_P2P: evalRequest
07-21 16:02:07.986  3675  3921 D WIFI_P2P:   done
07-21 16:02:07.986  3675  4942 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:07.992  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=151655 target=com.android.internal.util.StateMachine$SmHandler }
07-21 16:02:07.992  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: RESULT_VALID
07-21 16:02:07.992  3675 10593 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,07-21 16:02:07.994  3675  3956 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-21 16:02:07.995  3675  3956 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-21 16:02:07.995  3675  3956 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation passed
,07-21 16:02:07.996  3675  3956 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
,07-21 16:02:07.996  3675  3956 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-21 16:02:07.996  3675  3956 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
,07-21 16:02:07.996  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.996  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.996  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.996  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:02:07.996  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.996  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.996  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.996  3675  3956 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-21 16:02:07.996  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:02:07.997  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.997  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:07.997  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.997  3675  3956 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-21 16:02:07.997  3675  3956 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-21 16:02:07.997  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:07.997  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-21 16:02:07.997  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
,07-21 16:02:08.001  3675  3675 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
,07-21 16:02:08.003  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:02:08.003  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [] ]
07-21 16:02:08.005  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.005  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.006  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.006  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.007  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.007  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.009  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.009  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.011  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-21 16:02:08.011  3675  3927 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-21 16:02:08.011  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.014  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:08.015  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:08.015  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.016  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-21 16:02:08.016  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:08.017  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-21 16:02:08.017  3675  3956 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:08.017  3675  3956 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-21 16:02:08.018  3675  3956 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-21 16:02:08.021 10658 10658 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm64
07-21 16:02:08.024  4068  4289 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-21 16:02:08.026  3675  3925 D WifiConfigManager: update usableInternet : true
07-21 16:02:08.026  4068  4289 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-21 16:02:08.027  3675 10673 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-21 16:02:08.027  3675 10673 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-21 16:02:08.027  3675 10673 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-21 16:02:08.027  3675 10673 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-21 16:02:08.027  3675 10673 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-21 16:02:08.028  3675 10673 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-21 16:02:08.028  3675 10673 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-21 16:02:08.028  3675 10673 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-21 16:02:08.028  3675 10673 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-21 16:02:08.028  3675 10673 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-21 16:02:08.029  3675 10673 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-21 16:02:08.029  3675 10673 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-21 16:02:08.030 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:08.030 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:08.045  3675  3925 D WifiConfigStore: saveNetwork skipInternetCheck
07-21 16:02:08.047 10658 10658 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-21 16:02:08.056 10658 10658 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(96/onCreate)] 
,07-21 16:02:08.072  3675  3925 D WifiConfigStore: readNetwork skipInternetCheck
,07-21 16:02:08.088  3675  3956 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
07-21 16:02:08.088  3675 10674 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-21 16:02:08.088  3675 10674 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-21 16:02:08.089  3675 10674 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-21 16:02:08.089  3675 10674 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-21 16:02:08.089  3675 10674 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-21 16:02:08.089  3675 10674 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-21 16:02:08.089  3675 10674 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-21 16:02:08.089  3675 10674 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-21 16:02:08.090  3675 10674 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-21 16:02:08.090  3675 10674 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-21 16:02:08.090  3675 10674 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-21 16:02:08.090  3675 10674 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-21 16:02:08.095 10094 10157 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
07-21 16:02:08.097 10094 10157 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
07-21 16:02:08.097  3675  3675 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-21 16:02:08.097  3675  3675 D WifiHs20Service: reason: 2
07-21 16:02:08.098  3675  3952 I WifiHs20Service: Message received 5014
07-21 16:02:08.098  3675  3952 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-21 16:02:08.099 10094 10157 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,07-21 16:02:08.125 10658 10658 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(422/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-21 16:02:08.135  3675  3675 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
07-21 16:02:08.136  3675  3675 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,07-21 16:02:08.138  3675  3675 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,07-21 16:02:08.143  3675  4491 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / op:PendingIntent{e6d5f52: PendingIntentRecord{308c223 android broadcastIntent}}
,07-21 16:02:08.149  3675  3720 I ActivityManager: KPU : put [com.samsung.enhanceservice] : 26904 K
07-21 16:02:08.149  3675  3720 I ActivityManager: Killing 9743:com.samsung.enhanceservice/5004 (adj 906): DHA:empty #33
07-21 16:02:08.154  3675  4491 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170722T160208 - CU:1000/CP:3675
,07-21 16:02:08.156  4735 10624 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:08.156  4735 10624 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:08.157  3675  3675 D MountService: getExternalStorageMountMode : 1
07-21 16:02:08.158  3675  3675 D MountService: getExternalStorageMountMode : 3
07-21 16:02:08.158  3675  3675 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10112, packageName : com.google.android.talk
07-21 16:02:08.158  3291  3772 D EnterpriseController: netId is 0
07-21 16:02:08.158  3291  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-21 16:02:08.158  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-21 16:02:08.194 10681 10681 E Zygote  : v2
07-21 16:02:08.194 10681 10681 I libpersona: KNOX_SDCARD checking this for 10112
07-21 16:02:08.194 10681 10681 I libpersona: KNOX_SDCARD not a persona
07-21 16:02:08.195 10681 10681 E Zygote  : accessInfo : 0
,07-21 16:02:08.201 10681 10681 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-21 16:02:08.203 10681 10681 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
,07-21 16:02:08.205  3675  3675 I ActivityManager: Start proc 10681:com.google.android.talk/u0a112 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.broadcastreceiver.GcmStateReceiver
,07-21 16:02:08.209  3675  4946 D ActivityManager: cleanUpApplicationRecord -- 9743
,07-21 16:02:08.220  4768  4781 D ForegroundUtils: could not check pending caller
07-21 16:02:08.221  3675  3675 D SLocation: PendingIntent onSendFinished id:1
,07-21 16:02:08.230 10681 10681 D TimaKeyStoreProvider: TimaSignature is unavailable
07-21 16:02:08.231 10681 10681 D ActivityThread: Added TimaKeyStore provider
,07-21 16:02:08.233  3675  4987 I ActivityManager: DSS on for com.google.android.talk and scale is 1.0
,07-21 16:02:08.262 10658 10658 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(297/lllIlIlIIIllIIlIllIl)] Voice : true
,07-21 16:02:08.264 10658 10658 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(298/lllIlIlIIIllIIlIllIl)] SMS : true
,07-21 16:02:08.266 10658 10658 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(299/lllIlIlIIIllIIlIllIl)] isDataOnly : false
,07-21 16:02:08.268 10681 10681 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-21 16:02:08.271 10681 10681 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,07-21 16:02:08.281 10476 10619 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
,07-21 16:02:08.282 10476 10619 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-21 16:02:08.284 10476 10619 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-21 16:02:08.286 10476 10619 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:08.287 10476 10619 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:08.289  3291  3772 D EnterpriseController: netId is 0
07-21 16:02:08.289  3291  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10041
07-21 16:02:08.289  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-21 16:02:08.291 10658 10658 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(645/IllIlIIIIlIIlIIIllIl)] bootTime: 1500645522773
07-21 16:02:08.292 10681 10681 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-21 16:02:08.300 10658 10658 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(638/lllIlIlIIIllIIlIllIl)] bootTime: 1500645522773, savedBootTime: 1500000484534
07-21 16:02:08.301  3675  4015 D WifiWatchdogStateMachine:  [] [|204]
,07-21 16:02:08.310 10658 10658 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3131/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-21 16:02:08.313 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:08.314 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:08.320 10658 10658 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3184/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-21 16:02:08.330 10658 10658 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3237/IllIlIIIIlIIlIIIllIl)] xdmdbsqlGetNotiSaveState : 0
,07-21 16:02:08.348 10658 10658 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3386/llllllIllIlIlllIIlIl)] xdmdbsqlGetFumoInitType : 0
,07-21 16:02:08.351 10658 10658 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(93/onCreate)] DMApplication NOT Start !
,07-21 16:02:08.448  3675  3927 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.464  3675  4177 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.476  3675  3920 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.488  3675  4178 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.499  3675  3719 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.510  3675  3939 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.521  3675  4982 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.531  3675  4939 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.542  3675  4544 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.555  3675  4987 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.564 10681 10681 D BabelGcmRegistration: GcmRegistration: Checking GCM registration
,07-21 16:02:08.566  3675  4544 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.575 10681 10681 I Babel_telephony: TeleModule.onApplicationCreate
,07-21 16:02:08.578  3675  4179 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.579 10681 10705 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-21 16:02:08.579 10681 10705 I Babel_SMS: MmsConfig.loadMmsSettings
,07-21 16:02:08.580 10681 10705 E TelephonyManager: getCustomerPath : /system/csc/customer.xml file exist
,07-21 16:02:08.581 10681 10705 E TelephonyManager: getCustomerPath : /system/csc/customer.xml file exist
07-21 16:02:08.581 10681 10705 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: userAgent=SAMSUNG-ANDROID-MMS/uaprof, uaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
07-21 16:02:08.581 10681 10705 I Babel_SMS: MmsConfig.loadFromDatabase
,07-21 16:02:08.584 10681 10681 I Babel_App: Startup - clean
,07-21 16:02:08.586  3675  4931 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.588  3675  4543 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10112
07-21 16:02:08.589  3675  4543 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10112
07-21 16:02:08.590  3675  4543 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10112
07-21 16:02:08.593  3675  4987 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-21 16:02:08.593 10681 10705 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-21 16:02:08.593 10681 10705 I Babel_SMS: MmsConfig.loadFromResources
07-21 16:02:08.593  3675  4543 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10112
,07-21 16:02:08.594 10681 10705 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-21 16:02:08.594 10681 10705 I Babel_SMS: MmsConfig.loadMmsSettings: userAgent=SAMSUNG-ANDROID-MMS/uaprof, uaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
07-21 16:02:08.595  3675  4931 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10112
,07-21 16:02:08.603 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:08.603 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:08.611  4735 10624 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:08.611  4735 10624 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:08.622  3675  3719 D CryptdConnector: SND -> {23 cryptfs getpwtype}
,07-21 16:02:08.623  3096  3133 D VoldCryptCmdListener: cryptfs getpwtype
07-21 16:02:08.624  3675  3889 D CryptdConnector: RCV <- {213 23 default}
,07-21 16:02:08.631  3675  3720 I ActivityManager: KPU : put [com.samsung.android.oneconnect] : 26964 K
07-21 16:02:08.631  3675  3720 I ActivityManager: Killing 9757:com.samsung.android.oneconnect/u0a197 (adj 906): DHA:empty #33
,07-21 16:02:08.680  3675  4543 D ActivityManager: cleanUpApplicationRecord -- 9757
,07-21 16:02:08.684  4768  6456 D ForegroundUtils: could not check pending caller
,07-21 16:02:08.697  3675  4946 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{b12efbd: PendingIntentRecord{cc48b54 com.google.android.gms broadcastIntent}}
,07-21 16:02:08.733  3675  4988 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170721T165922 - CU:10019/CP:4735
,07-21 16:02:08.743  4735 10624 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-21 16:02:08.747  3675  4179 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-21 16:02:08.762  4735 10624 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:08.763  4735 10624 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:08.866 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:08.867 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:08.950 10476 10619 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 666
,07-21 16:02:09.023 10476 10619 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,07-21 16:02:09.024 10476 10619 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-21 16:02:09.027 10476 10619 I SA      : [OCP]  Cursor is not null
,07-21 16:02:09.032 10476 10619 I SA      : [OCP] update openData : EU
,07-21 16:02:09.038 10476 10619 I SA      : [TPMU] getNetworkMcc : 
,07-21 16:02:09.042  4735 10624 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-21 16:02:09.043 10476 10619 I SA      : [SRS] prepareGetMyCountryZone
,07-21 16:02:09.055 10476 10619 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-21 16:02:09.055 10476 10619 I SA      : [SSP] query invoked
,07-21 16:02:09.062 10476 10619 I SA      : [TPMU] GetMccFromDB : null
07-21 16:02:09.062 10476 10619 I SA      : [SCU] getMccFromPreferece mcc = 260
07-21 16:02:09.062 10476 10619 I SA      : [LBE] isSupportCheckDomainRegion : true
07-21 16:02:09.062 10476 10619 I SA      : [TPM] isNoProxy(default) : true
,07-21 16:02:09.065 10476 10619 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
07-21 16:02:09.065 10476 10619 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
07-21 16:02:09.067 10476 10619 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
07-21 16:02:09.068 10476 10619 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:09.069 10476 10619 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:09.095  3675  4942 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170721T165922 - CU:10019/CP:4735
,07-21 16:02:09.103 10094 10157 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,07-21 16:02:09.105 10094 10157 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,07-21 16:02:09.107 10094 10157 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,07-21 16:02:09.107 10094 10157 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 244)
,07-21 16:02:09.109 10094 10157 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,07-21 16:02:09.110 10094 10157 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,07-21 16:02:09.110 10094 10157 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 245)
07-21 16:02:09.110  3675  4931 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{c03cab9: PendingIntentRecord{cc48b54 com.google.android.gms broadcastIntent}}
,07-21 16:02:09.112 10094 10157 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,07-21 16:02:09.113 10094 10157 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,07-21 16:02:09.115 10094 10157 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,07-21 16:02:09.117 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-21 16:02:09.117 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abca39 added. We now have 2 listener(s)
07-21 16:02:09.117 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abca39 added. We now have 3 listener(s)
07-21 16:02:09.117 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-21 16:02:09.121 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-21 16:02:09.121 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-21 16:02:09.121 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-21 16:02:09.122 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-21 16:02:09.122 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8a87e added. We now have 4 listener(s)
07-21 16:02:09.122 10094 10157 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-21 16:02:09.123 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-21 16:02:09.132  3675  4941 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170721T165922 - CU:10019/CP:4735
07-21 16:02:09.132 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.133 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:09.135 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:09.137 10094 10157 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,07-21 16:02:09.139 10094 10157 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,07-21 16:02:09.139 10094 10157 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
07-21 16:02:09.139 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
07-21 16:02:09.140 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:02:09.143 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-21 16:02:09.143 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,07-21 16:02:09.144 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.144 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:02:09.147 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-21 16:02:09.147 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,07-21 16:02:09.147 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.148 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-21 16:02:09.148 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-21 16:02:09.148 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-21 16:02:09.148 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-21 16:02:09.150 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-21 16:02:09.150 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-21 16:02:09.151 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-21 16:02:09.151 10094 10717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-21 16:02:09.151 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-21 16:02:09.151 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-21 16:02:09.151 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-21 16:02:09.151 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:02:09.151 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-21 16:02:09.151 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-21 16:02:09.154 10094 10717 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:02:09.155 10094 10717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-21 16:02:09.157 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-21 16:02:09.157 10094 10157 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-21 16:02:09.157 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-21 16:02:09.159 10094 10717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-21 16:02:09.159 10094 10717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@6d0fe2c, port: 6, type: 1, local socket address: null, socket type: 0
,07-21 16:02:09.161 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.163 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.164 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.167 10094 10157 D BluetoothAdapter: isSecureModeEnabled
,07-21 16:02:09.167 10217 10294 D BtConfig.SecureMode: isSecureModeOn:false
,07-21 16:02:09.168 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.168 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-21 16:02:09.170 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.171 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.172 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-21 16:02:09.172 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-21 16:02:09.172 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-21 16:02:09.174 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.177 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.178 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.178 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-21 16:02:09.178 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-21 16:02:09.178 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "a4d24f35-892b-461f-a6f3-a89e39f3eaf7", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-21 16:02:09.179 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 4A 3E
07-21 16:02:09.179 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:02:09.180 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-21 16:02:09.180 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.181 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.181 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-21 16:02:09.182 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-21 16:02:09.182 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.183 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.184 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.185 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.187 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:09.187 10094 10157 D BluetoothAdapter: isSecureModeEnabled
,07-21 16:02:09.187 10217 10238 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:02:09.188 10094 10157 D BluetoothLeAdvertiser: start advertising
07-21 16:02:09.189 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.194 10217 10295 D BtGatt.GattService: registerClient() - UUID=b2b51a68-6612-4180-9992-6545965daf3d
,07-21 16:02:09.238  4068  4289 D ViewRootImpl@3d82468[Toast]: dispatchDetachedFromWindow
,07-21 16:02:09.248  3675  4941 D InputTransport: Input channel destroyed: fd=461
07-21 16:02:09.249  3675  4941 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3675) eventTime = 227029
07-21 16:02:09.249  3675  4941 D PowerManagerService: [s] UserActivityState : 4 -> 1
,07-21 16:02:09.250  3675  4941 D PowerManagerService: [api] release WakeLock SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3675, ws=WorkSource{10062}) (uid=1000, pid=3675, ws=WorkSource{10062}, pkg=android, elapsedTime=1970) (0x0)
07-21 16:02:09.250  3675  4941 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3675, ws=WorkSource{10062}) (uid=1000, pid=3675, ws=WorkSource{10062}, pkg=android, elapsedTime=1970)
,07-21 16:02:09.251  4068  4289 D InputTransport: Input channel destroyed: fd=149
,07-21 16:02:09.297 10217 10237 D BtGatt.GattService: onClientRegistered() - UUID=b2b51a68-6612-4180-9992-6545965daf3d, clientIf=5, status=0
,07-21 16:02:09.298 10094 10106 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-21 16:02:09.301 10217 10239 E BtGatt.ContextMap: Context not found for ID 5
07-21 16:02:09.303 10217 10254 D BtGatt.AdvertiseManager: message : 0
07-21 16:02:09.303 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-21 16:02:09.309 10217 10254 D BtGatt.AdvertiseManager: number of adv instance running = 0
,07-21 16:02:09.310 10217 10254 D BtGatt.AdvertiseManager: size of list is =0
,07-21 16:02:09.311  3675  4015 D WifiWatchdogStateMachine:  [|205] []
,07-21 16:02:09.318 10217 10254 D BtGatt.AdvertiseManager: starting advertising
,07-21 16:02:09.324 10217 10254 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-21 16:02:09.326 10217 10271 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-21 16:02:09.340 10217 10237 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-21 16:02:09.343 10217 10254 D BtGatt.AdvertiseManager: starting multi advertising
,07-21 16:02:09.351 10217 10237 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-21 16:02:09.358  4645  4645 D io_stats: !@   8,0 r 26172 2322948 w 5283 208312 d 726 74116 f 2105 2105 iot 11910 11087 th 472864 0 0 pt 0 inp 0 0 227.138
07-21 16:02:09.359 10217 10254 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-21 16:02:09.359 10217 10254 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-21 16:02:09.359 10217 10254 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-21 16:02:09.360 10217 10254 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-21 16:02:09.360 10094 10105 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
07-21 16:02:09.361 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.362 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.362 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-21 16:02:09.362 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.363 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.363 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.364 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.365 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.365 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-21 16:02:09.367 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-21 16:02:09.367 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.371 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.372 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.374 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.375 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-21 16:02:09.376 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.377 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-21 16:02:09.377 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-21 16:02:09.378 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.378 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.379 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-21 16:02:09.380 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.380 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-21 16:02:09.380 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-21 16:02:09.380 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.381 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.381 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-21 16:02:09.382 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.383 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-21 16:02:09.388 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.388 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-21 16:02:09.388 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-21 16:02:09.389 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.389 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-21 16:02:09.414 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:09.414 10240 10608 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:09.514  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:09.514  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
07-21 16:02:09.514  3675  3925 D WifiStateMachine: User moved, open or psk 24GHz, currentRssi = -40, mQnsUpperRssiThreshold = 200
,07-21 16:02:09.517  3675  3925 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@b42b869
,07-21 16:02:09.518  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,07-21 16:02:09.523  3675  3925 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170721T160212 - CU:1000/CP:3675
07-21 16:02:09.523  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160212, SetElapsed=229938, nowELAPSED=227304
,07-21 16:02:09.718 10476 10619 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 651
,07-21 16:02:09.723 10476 10619 I SA      : [ODM] saveOpenData( GEO_IP, EU )
07-21 16:02:09.724 10476 10619 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-21 16:02:09.729 10476 10619 I SA      : [OCP]  Cursor is not null
,07-21 16:02:09.739 10476 10619 I SA      : [OCP] update openData : EU
,07-21 16:02:09.748 10476 10619 I SA      : [TPMU] getNetworkMcc : 
,07-21 16:02:09.755 10476 10619 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 689
07-21 16:02:09.756 10476 10619 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-21 16:02:09.756 10476 10619 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1474
07-21 16:02:09.756 10476 10619 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-21 16:02:09.758 10476 10476 I SA      : [OR] GetMyCountryZoneTask mcc = null
,07-21 16:02:09.758 10476 10476 I SA      : [OR] GetMyCountryZoneTask Fail
,07-21 16:02:09.791  3675  3786 I WindowManager: Destroying surface Surface(name=Toast) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementInner:499 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementLoop:274 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacement:222 com.android.server.wm.WindowManagerService$H.handleMessage:9166 android.os.Handler.dispatchMessage:102 
,07-21 16:02:09.792  3112  3119 I SurfaceFlinger: id=17 Removed Uoast (5/5)
,07-21 16:02:09.794  3112  9737 I SurfaceFlinger: id=17 Removed Uoast (-2/5)
,07-21 16:02:09.878 10094 10157 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-21 16:02:09.879 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,07-21 16:02:09.879 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,07-21 16:02:09.880 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-21 16:02:09.880 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,07-21 16:02:09.880 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-21 16:02:09.881 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-21 16:02:09.881 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-21 16:02:09.881 10094 10717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-21 16:02:09.881 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,07-21 16:02:09.881 10094 10717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,07-21 16:02:09.881 10094 10717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,07-21 16:02:09.882 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-21 16:02:09.882 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-21 16:02:09.883 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-21 16:02:09.884 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.884 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-21 16:02:09.884 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-21 16:02:09.885 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.886 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.887 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.888 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.893 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.897 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:09.897 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-21 16:02:09.901 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.903 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:09.903 10094 10157 D BluetoothLeScanner: could not find callback wrapper
07-21 16:02:09.904 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-21 16:02:09.904 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.905 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.905 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.906 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-21 16:02:09.906 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.908 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:09.910 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:09.911 10094 10157 D BluetoothLeAdvertiser: stop advertising
,07-21 16:02:09.913 10217 10228 E BtGatt.ContextMap: Context not found for ID 5
07-21 16:02:09.913 10217 10254 D BtGatt.AdvertiseManager: message : 1
07-21 16:02:09.913 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-21 16:02:09.914 10217 10254 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-21 16:02:09.915 10217 10254 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-21 16:02:09.917 10217 10254 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-21 16:02:09.924 10217 10237 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-21 16:02:09.924 10217 10237 D BtGatt.GattService: Client app is not null!
,07-21 16:02:09.925 10094 10106 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-21 16:02:09.927 10217 10294 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-21 16:02:09.928 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-21 16:02:09.929 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.929 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-21 16:02:09.930 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.930 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.931 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.931 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-21 16:02:09.931 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-21 16:02:09.932 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-21 16:02:09.933 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.936 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.936 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-21 16:02:09.937 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:09.937 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:09.938 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-21 16:02:09.938 10094 10094 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-21 16:02:09.939 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-21 16:02:09.939 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-21 16:02:09.939 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-21 16:02:09.940 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:02:09.940 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-21 16:02:09.941 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-21 16:02:09.941 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.941 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-21 16:02:09.941 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-21 16:02:09.942 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.942 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.943 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:02:09.943 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-21 16:02:10.445 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-21 16:02:10.457  3675  4988 I ActivityManager: KPU : put [com.samsung.android.communicationservice] : 28360 K
07-21 16:02:10.457  3675  4988 I ActivityManager: Killing 9665:com.samsung.android.communicationservice/5002 (adj 906): DHA:empty #33
,07-21 16:02:10.515  3675  4177 D ActivityManager: cleanUpApplicationRecord -- 9665
07-21 16:02:10.516  4768  4781 D ForegroundUtils: could not check pending caller
,07-21 16:02:12.157  3675  3861 D SamsungAlarmManager: Expired : 4
07-21 16:02:12.158  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775322, nowELAPSED=229939
,07-21 16:02:12.159  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@c75398 alarm=Alarm{416cfd6 type 2 when 229938 android}
07-21 16:02:12.162  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,07-21 16:02:12.166 10493 10493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-21 16:02:12.167 10493 10493 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-21 16:02:12.172  3675  3925 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170721T160220 - CU:1000/CP:3675
07-21 16:02:12.173  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237944, nowELAPSED=229954
,07-21 16:02:12.187  3675  3954 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160227 - CU:1000/CP:3675
,07-21 16:02:12.196 10493 10493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-21 16:02:12.542  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:12.542  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:12.946 10094 10157 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,07-21 16:02:12.947 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-21 16:02:12.948 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-21 16:02:12.948 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-21 16:02:12.948 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-21 16:02:12.949 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:02:12.949 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-21 16:02:12.967 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-21 16:02:12.968 10094 10157 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-21 16:02:12.968 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-21 16:02:12.973 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:12.975 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:12.977 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:12.981 10094 10157 D BluetoothAdapter: isSecureModeEnabled
,07-21 16:02:12.982 10217 10239 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:02:12.983 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:12.983 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-21 16:02:12.985 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:12.987 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:12.987 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-21 16:02:12.987 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-21 16:02:12.987 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-21 16:02:12.992 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:12.994 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:12.999 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:13.002 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:13.006 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:13.006 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-21 16:02:13.007 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-21 16:02:13.007 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 38881
,07-21 16:02:13.008 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=38881, mManufacturerData=null, mManufacturerDataMask=null]
,07-21 16:02:13.009 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:13.009 10094 10157 D BluetoothLeScanner: Start Scan
,07-21 16:02:13.014 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:13.015 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:13.018 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:13.020 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:13.024 10217 10294 D BtGatt.GattService: registerClient() - UUID=82a01546-34d5-40a7-9a38-a92004fa3ba0
,07-21 16:02:13.127 10217 10237 D BtGatt.GattService: onClientRegistered() - UUID=82a01546-34d5-40a7-9a38-a92004fa3ba0, clientIf=5, status=0
,07-21 16:02:13.129 10094 10105 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
07-21 16:02:13.130 10217 10295 D BtGatt.GattService: start scan with filters
,07-21 16:02:13.134 10217 10295 D BtGatt.GattService: getScanSettings
,07-21 16:02:13.137 10217 10295 D BtGatt.GattService: Is it foreground application = true
07-21 16:02:13.137 10217 10295 D BtGatt.GattService: not a background application
,07-21 16:02:13.150 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,07-21 16:02:13.150 10217 10265 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
,07-21 16:02:13.150 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-21 16:02:13.151 10217 10255 D BtGatt.ScanManager: handling starting scan
07-21 16:02:13.151 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:13.152 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-21 16:02:13.153 10217 10255 D BluetoothAdapter: STATE_ON
,07-21 16:02:13.153 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:13.156 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-21 16:02:13.156 10217 10255 D BluetoothAdapter: STATE_ON
,07-21 16:02:13.164 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-21 16:02:13.164 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-21 16:02:13.164 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-21 16:02:13.165 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:02:13.166 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,07-21 16:02:13.167 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:02:13.168 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
07-21 16:02:13.169 10217 10237 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-21 16:02:13.169 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-21 16:02:13.169 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-21 16:02:13.170 10217 10255 D BtGatt.ScanManager: set filter index= 6 for clientIf= 5
,07-21 16:02:13.170 10217 10255 D BtGatt.ScanManager: High Rssi Filter value is = -128
,07-21 16:02:13.170 10217 10255 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-21 16:02:13.170 10217 10255 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
07-21 16:02:13.174 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-21 16:02:13.176 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:13.182  3675  3758 I ActivityManager: KPU : put [com.samsung.android.coreapps] : 30972 K
07-21 16:02:13.182  3675  3758 I ActivityManager: Killing 9683:com.samsung.android.coreapps/5011 (adj 906): DHA:empty #33
07-21 16:02:13.182 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,07-21 16:02:13.183 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:13.184 10217 10255 D BtGatt.ScanManager: Starting BLE batch scan
07-21 16:02:13.184 10217 10255 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-21 16:02:13.192 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:13.193 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-21 16:02:13.194 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:13.194 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:13.195 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
07-21 16:02:13.203 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-21 16:02:13.203 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-21 16:02:13.204 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-21 16:02:13.205 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-21 16:02:13.208 10217 10237 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-21 16:02:13.209 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-21 16:02:13.218 10217 10237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-21 16:02:13.218 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:13.219  3675  3988 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{ad8fdb0: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:13.229  3675  4939 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160213 - CU:1002/CP:10217
07-21 16:02:13.229  3675  4939 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160214, SetElapsed=232002, nowELAPSED=231010
,07-21 16:02:13.250  3675  3790 D PowerManagerService: [s] UserActivityState : 1 -> 4
07-21 16:02:13.250  3675  3790 D PowerManagerService: mDisplayReady: false
07-21 16:02:13.250  3675  3790 I PowerManagerService: [PWL] On : 0 (231031 ms ago)
07-21 16:02:13.250  3675  3790 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
07-21 16:02:13.250  3675  3790 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-21 16:02:13.251  3675  3790 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-21 16:02:13.251  3675  3790 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-21 16:02:13.251  3675  3790 D DisplayPowerController: Animating brightness: target=57, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-21 16:02:13.251  3675  3790 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-21 16:02:13.251  3675  3790 D PowerManagerService: mDisplayReady: true
,07-21 16:02:13.257  3675  4036 D lights  : lcd : 96 +
,07-21 16:02:13.261  3675  4865 D ActivityManager: cleanUpApplicationRecord -- 9683
07-21 16:02:13.263  4768  4787 D ForegroundUtils: could not check pending caller
07-21 16:02:13.263  3675  4036 D lights  : lcd : 96 -
,07-21 16:02:13.274  3675  4036 D lights  : lcd : 62 +
,07-21 16:02:13.275  3675  4036 D lights  : lcd : 62 -
,07-21 16:02:13.291  3675  3790 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-21 16:02:13.291  3675  4036 D lights  : lcd : 57 +
07-21 16:02:13.291  3675  3790 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-21 16:02:13.291  3675  3790 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-21 16:02:13.291  3675  3790 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-21 16:02:13.292  3675  4036 D lights  : lcd : 57 -
,07-21 16:02:13.706 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
07-21 16:02:13.707 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-21 16:02:13.707 10094 10094 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-21 16:02:14.221  3675  3861 D SamsungAlarmManager: Expired : 4
07-21 16:02:14.222  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237944, nowELAPSED=232003
,07-21 16:02:14.223  3675  3861 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{1cfd429 type 2 when 231501 com.android.bluetooth}
,07-21 16:02:14.229 10217 10217 D BtGatt.ScanManager: awakened up at time 232010
,07-21 16:02:14.232 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-21 16:02:14.246 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-21 16:02:14.246 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:14.248  3675  4939 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{8d803ae: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
,07-21 16:02:14.268  3675  4988 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160214 - CU:1002/CP:10217
,07-21 16:02:14.271  3675  4988 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160215, SetElapsed=233031, nowELAPSED=232051
,07-21 16:02:14.363  4645  4645 D io_stats: !@   8,0 r 26172 2322948 w 5312 208812 d 729 74128 f 2109 2109 iot 11920 11097 th 478732 0 0 pt 0 inp 0 0 232.142
,07-21 16:02:14.901  3675  5817 D SSRM:f  : SIOP:: AP = 270, PST = 271 (W:10), CP = 222, CUR = -3, LCD = 57
,07-21 16:02:15.250  3675  3861 D SamsungAlarmManager: Expired : 4
,07-21 16:02:15.251  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237944, nowELAPSED=233032
07-21 16:02:15.252  3675  3861 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{bacc54f type 2 when 232530 com.android.bluetooth}
,07-21 16:02:15.258 10217 10217 D BtGatt.ScanManager: awakened up at time 233039
,07-21 16:02:15.261 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-21 16:02:15.273 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-21 16:02:15.273 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:15.275  3675  3939 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{6c844dc: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
,07-21 16:02:15.292  3675  4543 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160215 - CU:1002/CP:10217
07-21 16:02:15.293  3675  4543 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160216, SetElapsed=234059, nowELAPSED=233074
,07-21 16:02:15.571  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:15.571  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:16.200 10094 10157 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
07-21 16:02:16.201 10094 10157 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
07-21 16:02:16.202 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,07-21 16:02:16.202 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:02:16.211 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-21 16:02:16.211 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-21 16:02:16.212 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.213 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-21 16:02:16.220 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-21 16:02:16.220 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,07-21 16:02:16.221 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 38881
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-21 16:02:16.222 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.223 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
,07-21 16:02:16.223 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.224 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.224 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-21 16:02:16.224 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-21 16:02:16.225 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.226 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.226 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.228 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:16.231 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:16.232 10217 10238 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,07-21 16:02:16.233 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-21 16:02:16.234 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-21 16:02:16.234 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:16.238 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.238 10094 10157 D BluetoothLeScanner: Stop Scan
,07-21 16:02:16.240 10217 10294 D BtGatt.GattService: stopScan() - queue size =1
07-21 16:02:16.240 10217 10294 D BtGatt.GattService: stopScan() - queue size =1
07-21 16:02:16.241 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
,07-21 16:02:16.243 10217 10295 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-21 16:02:16.247 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-21 16:02:16.248 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.248 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-21 16:02:16.248 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.249 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-21 16:02:16.249 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
07-21 16:02:16.249 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:16.249 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.250 10217 10237 D BtGatt.GattService: current time is 234030908717
07-21 16:02:16.250 10217 10237 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -93, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -94, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,07-21 16:02:16.250 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.250 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-21 16:02:16.250 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-21 16:02:16.250 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 38881
07-21 16:02:16.251 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=38881, mManufacturerData=null, mManufacturerDataMask=null]
07-21 16:02:16.251 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.251 10094 10157 D BluetoothLeScanner: Start Scan
,07-21 16:02:16.252 10217 10237 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
07-21 16:02:16.253 10217 10237 D ScanRecord: parseFromBytes
07-21 16:02:16.253 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.253 10217 10237 D ScanRecord: first manudata for manu ID
07-21 16:02:16.254 10217 10237 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,07-21 16:02:16.254 10217 10237 D ScanRecord: parseFromBytes
07-21 16:02:16.254 10217 10237 D ScanRecord: first manudata for manu ID
07-21 16:02:16.255 10217 10237 E BtGatt.ContextMap: Context not found for ID 5
07-21 16:02:16.255 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.255  3675  4931 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{66889e5: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:16.257  3675  4931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237944, nowELAPSED=234038
07-21 16:02:16.258 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:16.260 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:16.264 10217 10295 D BtGatt.GattService: registerClient() - UUID=85b64a1b-6490-44c7-97e4-7d95e078639c
,07-21 16:02:16.268  3675  4543 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160216 - CU:1002/CP:10217
,07-21 16:02:16.269  3675  4543 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160217, SetElapsed=235039, nowELAPSED=234050
,07-21 16:02:16.273 10217 10255 D BtGatt.ScanManager: filter size is 1
07-21 16:02:16.274 10217 10255 D BtGatt.ScanManager: delete FilterIndex - 6
,07-21 16:02:16.280 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-21 16:02:16.280 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:16.280 10217 10255 D BtGatt.ScanManager: stopping BLe Batch
,07-21 16:02:16.287 10217 10237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-21 16:02:16.288 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:16.288 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-21 16:02:16.288 10493 10493 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
07-21 16:02:16.291  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:02:16.293  3675  3954 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@baa1144
07-21 16:02:16.294  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:02:16.294  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
07-21 16:02:16.294 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-21 16:02:16.294 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:16.295  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160216, SetElapsed=234539, nowELAPSED=234076
07-21 16:02:16.295  3675  4988 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{a4acba: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:16.296  3675  4988 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237944, nowELAPSED=234077
,07-21 16:02:16.302  3675  4939 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{49a676b: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
,07-21 16:02:16.320  3675  3758 I ActivityManager: KPU : put [com.samsung.android.SettingsReceiver] : 26908 K
07-21 16:02:16.320  3675  3758 I ActivityManager: Killing 9335:com.samsung.android.SettingsReceiver/1000 (adj 906): DHA:empty #33
,07-21 16:02:16.342  3675  4179 D ActivityManager: cleanUpApplicationRecord -- 9335
,07-21 16:02:16.343  4768  6456 D ForegroundUtils: could not check pending caller
,07-21 16:02:16.366 10217 10237 D BtGatt.GattService: onClientRegistered() - UUID=85b64a1b-6490-44c7-97e4-7d95e078639c, clientIf=5, status=0
,07-21 16:02:16.367 10094 10106 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
07-21 16:02:16.367 10217 10239 D BtGatt.GattService: start scan with filters
,07-21 16:02:16.368 10217 10239 D BtGatt.GattService: getScanSettings
,07-21 16:02:16.369 10217 10239 D BtGatt.GattService: Is it foreground application = true
07-21 16:02:16.369 10217 10239 D BtGatt.GattService: not a background application
,07-21 16:02:16.374 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
07-21 16:02:16.374 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-21 16:02:16.374 10217 10265 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5a1b2e
07-21 16:02:16.375 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.375 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-21 16:02:16.375 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.376 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.376 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-21 16:02:16.376 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-21 16:02:16.376 10094 10157 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-21 16:02:16.376 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.376 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-21 16:02:16.376 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-21 16:02:16.376 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-21 16:02:16.376 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-21 16:02:16.376 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.377 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-21 16:02:16.379 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-21 16:02:16.379 10217 10255 D BtGatt.ScanManager: handling starting scan
,07-21 16:02:16.380 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-21 16:02:16.380 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-21 16:02:16.380 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-21 16:02:16.380 10217 10255 D BluetoothAdapter: STATE_ON
07-21 16:02:16.380 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-21 16:02:16.380 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-21 16:02:16.380 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
07-21 16:02:16.381 10217 10255 D BluetoothAdapter: STATE_ON
,07-21 16:02:16.383 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-21 16:02:16.383 10094 10729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-21 16:02:16.383 10094 10157 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-21 16:02:16.386  3675  3758 I ActivityManager: KPU : put [com.samsung.android.app.memo] : 27732 K
07-21 16:02:16.386  3675  3758 I ActivityManager: Killing 9867:com.samsung.android.app.memo/u0a145 (adj 906): DHA:empty #33
,07-21 16:02:16.386 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.387 10217 10237 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-21 16:02:16.387 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:16.387 10217 10255 D BtGatt.ScanManager: set filter index= 7 for clientIf= 5
07-21 16:02:16.387 10217 10255 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-21 16:02:16.387 10217 10255 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-21 16:02:16.387 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:16.387 10217 10255 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
07-21 16:02:16.393 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.393 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-21 16:02:16.393 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:16.393 10217 10255 D BtGatt.ScanManager: Starting BLE batch scan
07-21 16:02:16.393 10217 10255 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-21 16:02:16.396 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.396 10094 10729 D BluetoothSocket: bindListen(): myUserId = 0
07-21 16:02:16.396 10094 10729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-21 16:02:16.402 10217 10237 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-21 16:02:16.403 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:16.406 10094 10729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-21 16:02:16.406 10094 10729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@b974956, port: 6, type: 1, local socket address: null, socket type: 0
07-21 16:02:16.407 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.410 10217 10237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-21 16:02:16.410 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:16.411  3675  4942 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{902d2c8: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:16.414 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.415 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.416 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.416 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-21 16:02:16.416 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-21 16:02:16.416 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "a4d24f35-892b-461f-a6f3-a89e39f3eaf7", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-21 16:02:16.416 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 4A 3E
07-21 16:02:16.417 10094 10157 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:02:16.417 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:02:16.418 10094 10157 D org.thaliproject.p,2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.418  3675  4865 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160216 - CU:1002/CP:10217
07-21 16:02:16.419  3675  4865 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160217, SetElapsed=235193, nowELAPSED=234200
07-21 16:02:16.419 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.420 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-21 16:02:16.420 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-21 16:02:16.420 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.421 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.421 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={a4d24f35-892b-461f-a6f3-a89e39f3eaf7=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.421  3675  4543 D ActivityManager: cleanUpApplicationRecord -- 9867
07-21 16:02:16.423 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.423  4768  6456 D ForegroundUtils: could not check pending caller
,07-21 16:02:16.427 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:16.427 10094 10157 D BluetoothAdapter: isSecureModeEnabled
,07-21 16:02:16.427 10217 10294 D BtConfig.SecureMode: isSecureModeOn:false
07-21 16:02:16.428 10094 10157 D BluetoothLeAdvertiser: start advertising
,07-21 16:02:16.429 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:16.433 10217 10238 D BtGatt.GattService: registerClient() - UUID=9be6dc11-9b0c-4886-99bc-188ffc5aaf1e
,07-21 16:02:16.535 10217 10237 D BtGatt.GattService: onClientRegistered() - UUID=9be6dc11-9b0c-4886-99bc-188ffc5aaf1e, clientIf=6, status=0
,07-21 16:02:16.536 10094 10105 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,07-21 16:02:16.538 10217 10229 E BtGatt.ContextMap: Context not found for ID 6
07-21 16:02:16.538 10217 10254 D BtGatt.AdvertiseManager: message : 0
07-21 16:02:16.538 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-21 16:02:16.539 10217 10254 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-21 16:02:16.540 10217 10254 D BtGatt.AdvertiseManager: size of list is =0
,07-21 16:02:16.548 10217 10254 D BtGatt.AdvertiseManager: starting advertising
,07-21 16:02:16.553 10217 10254 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-21 16:02:16.558 10217 10271 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-21 16:02:16.580 10217 10237 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,07-21 16:02:16.584 10217 10254 D BtGatt.AdvertiseManager: starting multi advertising
,07-21 16:02:16.595 10217 10237 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
07-21 16:02:16.596 10217 10254 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-21 16:02:16.596 10217 10254 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-21 16:02:16.596 10217 10254 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
07-21 16:02:16.596 10217 10254 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
,07-21 16:02:16.598 10094 10728 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-21 16:02:16.599 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.601 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.601 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-21 16:02:16.602 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.603 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.604 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.605 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.606 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.606 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.607 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.608 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.609 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
07-21 16:02:16.609 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
07-21 16:02:16.609 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-21 16:02:16.613 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-21 16:02:16.614 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.623 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:16.624 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.624 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:16.626 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-21 16:02:16.627 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-21 16:02:16.628 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-21 16:02:16.628 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-21 16:02:16.629 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-21 16:02:16.631 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.632 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-21 16:02:16.632 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.633 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
07-21 16:02:16.633 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-21 16:02:16.633 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.634 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-21 16:02:16.634 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.635 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-21 16:02:16.636 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-21 16:02:16.641 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.641 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-21 16:02:16.642 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.642 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-21 16:02:16.643 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-21 16:02:16.936  3675 10732 D WifiMHD::s: req(2):1, 7, 1
,07-21 16:02:16.940  3675 10732 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-21 16:02:16.940  3675 10732 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-21 16:02:16.943  3291  3772 D EnterpriseController: netId is 0
,07-21 16:02:16.943  3291  3772 D Netd    : getNetworkForDns: using netid 503 for uid 1000
07-21 16:02:16.943  3291  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-21 16:02:17.145 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
07-21 16:02:17.145 10094 10094 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-21 16:02:17.145 10094 10094 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-21 16:02:17.412  3675  3861 D SamsungAlarmManager: Expired : 4
07-21 16:02:17.413  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237944, nowELAPSED=235194
,07-21 16:02:17.414  3675  3861 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{b60da86 type 2 when 234692 com.android.bluetooth}
,07-21 16:02:17.420 10217 10217 D BtGatt.ScanManager: awakened up at time 235201
,07-21 16:02:17.422 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-21 16:02:17.455 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
07-21 16:02:17.455 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:17.456 10217 10237 D BtGatt.GattService: current time is 235237076716
,07-21 16:02:17.456 10217 10237 D BtGatt.GattService: Batch record : [-102, -9, 2, -127, -47, 114, 1, -128, -56, 0, 0, 29, 17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 4, -88, -127, -107, -23, 95, 111, 0, -102, -9, 2, -127, -47, 114, 1, -128, -56, 0, 0, 29, 17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 4, -88, -127, -107, -23, 95, 111, 0]
07-21 16:02:17.457 10217 10237 D BtGatt.GattService: ScanRecord : [17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 4, -88, -127, -107, -23, 95, 111]
07-21 16:02:17.457 10217 10237 D ScanRecord: parseFromBytes
07-21 16:02:17.457  3675  4987 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{4760f47: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:17.458 10217 10237 D BtGatt.GattService: ScanRecord : [17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 4, -88, -127, -107, -23, 95, 111]
07-21 16:02:17.458 10217 10237 D ScanRecord: parseFromBytes
,07-21 16:02:17.462 10094 10106 D ScanRecord: parseFromBytes
07-21 16:02:17.462 10094 10106 D ScanRecord: parseFromBytes
,07-21 16:02:17.464 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=72:D1:81:02:F7:9A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={00004f35-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-56, mTimestampNanos=235237435639}
,07-21 16:02:17.467 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
,07-21 16:02:17.468 10094 10094 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
07-21 16:02:17.469 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = a4d24f35-892b-461f-a6f3-a89e39f3eaf7, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
,07-21 16:02:17.470 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 4]
07-21 16:02:17.471 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=72:D1:81:02:F7:9A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={00004f35-0000-1000-8000-00805f9b34fb=[4, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-56, mTimestampNanos=235237435639}
,07-21 16:02:17.473 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
07-21 16:02:17.473 10094 10094 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
07-21 16:02:17.474  3675  4178 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160217 - CU:1002/CP:10217
,07-21 16:02:17.474 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = a4d24f35-892b-461f-a6f3-a89e39f3eaf7, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 4]
07-21 16:02:17.474 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 4]
07-21 16:02:17.474  3675  4178 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160218, SetElapsed=236240, nowELAPSED=235255
07-21 16:02:17.475 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 4]
07-21 16:02:17.475 10094 10094 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 4]
07-21 16:02:17.475 10094 10094 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
07-21 16:02:17.476 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerAdded: [A8:81:95:E9:5F:6F 4]
07-21 16:02:17.477 10094 10094 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [A8:81:95:E9:5F:6F 4], added - the peer count is 1
,07-21 16:02:17.478 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 4]
07-21 16:02:17.479 10094 10094 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 4]
,07-21 16:02:17.479 10094 10094 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
07-21 16:02:17.480 10094 10094 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 4] updated - the peer count is 1
07-21 16:02:17.481 10094 10094 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [A8:81:95:E9:5F:6F 4], Bluetooth address: A8:81:95:E9:5F:6F, device name: 'null', device address: 'null'
,07-21 16:02:18.174  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:18.395  3675  4179 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:02:18.459  3675  3861 D SamsungAlarmManager: Expired : 4
,07-21 16:02:18.460  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237944, nowELAPSED=236241
07-21 16:02:18.461  3675  3861 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{6d65374 type 2 when 235739 com.android.bluetooth}
,07-21 16:02:18.468 10217 10217 D BtGatt.ScanManager: awakened up at time 236249
,07-21 16:02:18.470 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-21 16:02:18.489 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-21 16:02:18.489 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-21 16:02:18.489 10217 10237 D BtGatt.GattService: current time is 236270457908
07-21 16:02:18.489 10217 10237 D BtGatt.GattService: Batch record : [-102, -9, 2, -127, -47, 114, 1, -128, -54, 10, 0, 29, 17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 5, -88, -127, -107, -23, 95, 111, 0]
07-21 16:02:18.490 10217 10237 D BtGatt.GattService: ScanRecord : [17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 5, -88, -127, -107, -23, 95, 111]
,07-21 16:02:18.490 10217 10237 D ScanRecord: parseFromBytes
07-21 16:02:18.490  3675  3719 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{667109d: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:18.491 10094 10105 D ScanRecord: parseFromBytes
,07-21 16:02:18.492 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=72:D1:81:02:F7:9A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={00004f35-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=235770732369}
07-21 16:02:18.493 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
07-21 16:02:18.493 10094 10094 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
07-21 16:02:18.494 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = a4d24f35-892b-461f-a6f3-a89e39f3eaf7, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
07-21 16:02:18.494 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 5]
07-21 16:02:18.494 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 5]
07-21 16:02:18.494 10094 10094 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 5]
07-21 16:02:18.494 10094 10094 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: true
07-21 16:02:18.495 10094 10094 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerUpdated. Listeners size = 1
07-21 16:02:18.495 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerUpdated: [A8:81:95:E9:5F:6F 5]
07-21 16:02:18.495 10094 10094 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 5] updated - the peer count is 1
07-21 16:02:18.496 10094 10099 I art     : Do partial code cache collection, code=19KB, data=31KB
07-21 16:02:18.496 10094 10094 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [A8:81:95:E9:5F:6F 5], device name: 'null', device address: 'null'
07-21 16:02:18.497 10094 10099 I art     : After code cache collection, code=16KB, data=28KB
07-21 16:02:18.497 10094 10099 I art     : Increasing code cache capacity to 128KB
,07-21 16:02:18.500  3675  4941 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160218 - CU:1002/CP:10217
07-21 16:02:18.501  3675  4941 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160219, SetElapsed=237272, nowELAPSED=236282
,07-21 16:02:18.604  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:18.604  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-21 16:02:19.368  4645  4645 D io_stats: !@   8,0 r 26172 2322948 w 5338 209180 d 734 74148 f 2115 2115 iot 11930 11108 th 480848 0 0 pt 0 inp 0 0 237.147
,07-21 16:02:19.491  3675  3861 D SamsungAlarmManager: Expired : 4
,07-21 16:02:19.492  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160220, SetElapsed=237944, nowELAPSED=237273
07-21 16:02:19.493  3675  3861 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{7601912 type 2 when 236772 com.android.bluetooth}
,07-21 16:02:19.499 10217 10217 D BtGatt.ScanManager: awakened up at time 237280
,07-21 16:02:19.501 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-21 16:02:19.527 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
07-21 16:02:19.527 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:19.528 10217 10237 D BtGatt.GattService: current time is 237309010561
,07-21 16:02:19.528 10217 10237 D BtGatt.GattService: Batch record : [-102, -9, 2, -127, -47, 114, 1, -128, -57, 21, 0, 29, 17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 5, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -102, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
,07-21 16:02:19.529 10217 10237 D BtGatt.GattService: ScanRecord : [17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 5, -88, -127, -107, -23, 95, 111]
07-21 16:02:19.529  3675  4988 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{17a58e3: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:19.529 10217 10237 D ScanRecord: parseFromBytes
07-21 16:02:19.530 10217 10237 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
07-21 16:02:19.531 10217 10237 D ScanRecord: parseFromBytes
07-21 16:02:19.531 10217 10237 D ScanRecord: first manudata for manu ID
07-21 16:02:19.532 10094 10728 D ScanRecord: parseFromBytes
07-21 16:02:19.533 10094 10728 D ScanRecord: first manudata for manu ID
07-21 16:02:19.533 10094 10728 D ScanRecord: parseFromBytes
,07-21 16:02:19.535 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=72:D1:81:02:F7:9A, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[a4d24f35-892b-461f-a6f3-a89e39f3eaf7], mManufacturerSpecificData={}, mServiceData={00004f35-0000-1000-8000-00805f9b34fb=[5, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-57, mTimestampNanos=236259503215}
,07-21 16:02:19.537 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
07-21 16:02:19.537 10094 10094 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: Resolved advertisement type: ADVERTISEMENT_PEER_PROPERTIES
07-21 16:02:19.538 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: Parsed advertisment: [UUID = a4d24f35-892b-461f-a6f3-a89e39f3eaf7, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 5]
07-21 16:02:19.538 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult onPeerDiscovered [A8:81:95:E9:5F:6F 5]
07-21 16:02:19.540 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-102, mTimestampNanos=236309503215}
07-21 16:02:19.541 10094 10094 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [A8:81:95:E9:5F:6F 5]
07-21 16:02:19.541 10094 10094 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: [A8:81:95:E9:5F:6F 5]
07-21 16:02:19.541 10094 10094 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: has more info: false,  extra info differs: false
07-21 16:02:19.542 10094 10094 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [A8:81:95:E9:5F:6F 5] updated - the peer count is 1
,07-21 16:02:19.547  3675  4865 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160220 - CU:1002/CP:10217
,07-21 16:02:19.632 10094 10157 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,07-21 16:02:19.634 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-21 16:02:19.634 10094 10157 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-21 16:02:19.634 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-21 16:02:19.634 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-21 16:02:19.635 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-21 16:02:19.635 10094 10729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-21 16:02:19.635 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-21 16:02:19.635 10094 10729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-21 16:02:19.636 10094 10729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-21 16:02:19.636 10094 10157 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-21 16:02:19.636 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-21 16:02:19.636 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-21 16:02:19.636 10094 10157 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abca39 removed from the list
07-21 16:02:19.636 10094 10094 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-21 16:02:19.636 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@abca39 removed from the list
07-21 16:02:19.637 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-21 16:02:19.637 10094 10157 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-21 16:02:19.637 10094 10094 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-21 16:02:19.638 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.638 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-21 16:02:19.638 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-21 16:02:19.640 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.641 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:19.642 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.642 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-21 16:02:19.643 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:19.645 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:19.647 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:19.648 10217 10228 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,07-21 16:02:19.649 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-21 16:02:19.650 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-21 16:02:19.652 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:19.655 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:19.655 10094 10157 D BluetoothLeScanner: Stop Scan
07-21 16:02:19.657 10217 10229 D BtGatt.GattService: stopScan() - queue size =1
07-21 16:02:19.658 10217 10229 D BtGatt.GattService: stopScan() - queue size =1
07-21 16:02:19.658 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-21 16:02:19.660 10217 10294 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-21 16:02:19.662 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-21 16:02:19.662 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.663 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-21 16:02:19.663 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:19.664 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:19.665 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.665 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,07-21 16:02:19.665 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-21 16:02:19.665 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:19.665 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.665 10217 10237 D BtGatt.GattService: current time is 237446826022
07-21 16:02:19.666 10217 10237 D BtGatt.GattService: Batch record : [-102, -9, 2, -127, -47, 114, 1, -128, -54, 2, 0, 29, 17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 5, -88, -127, -107, -23, 95, 111, 0]
07-21 16:02:19.666 10217 10237 D BtGatt.GattService: ScanRecord : [17, 7, -9, -22, -13, 57, -98, -88, -13, -90, 31, 70, 43, -119, 53, 79, -46, -92, 10, 22, 53, 79, 5, -88, -127, -107, -23, 95, 111]
07-21 16:02:19.666 10217 10237 D ScanRecord: parseFromBytes
07-21 16:02:19.666 10217 10237 E BtGatt.ContextMap: Context not found for ID 5
07-21 16:02:19.667  3675  3939 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{abf32e0: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
,07-21 16:02:19.667 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:19.669 10094 10157 D BluetoothAdapter: STATE_ON
07-21 16:02:19.670 10094 10157 D BluetoothLeAdvertiser: stop advertising
,07-21 16:02:19.671 10217 10238 E BtGatt.ContextMap: Context not found for ID 6
07-21 16:02:19.672 10217 10265 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-21 16:02:19.672 10217 10254 D BtGatt.AdvertiseManager: message : 1
,07-21 16:02:19.673 10217 10254 D BtGatt.AdvertiseManager: stop advertise for client =  6
07-21 16:02:19.673 10217 10254 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,07-21 16:02:19.675 10217 10254 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-21 16:02:19.678  3675  3927 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170721T160220 - CU:1002/CP:10217
,07-21 16:02:19.680 10217 10255 D BtGatt.ScanManager: filter size is 1
07-21 16:02:19.680 10217 10255 D BtGatt.ScanManager: delete FilterIndex - 7
07-21 16:02:19.682 10217 10237 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
07-21 16:02:19.682 10217 10237 D BtGatt.GattService: Client app is not null!
07-21 16:02:19.682 10094 10106 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-21 16:02:19.684 10217 10229 D BtGatt.GattService: unregisterClient() - clientIf=6
,07-21 16:02:19.686 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-21 16:02:19.686 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.686 10217 10237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,07-21 16:02:19.686 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-21 16:02:19.686 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:19.687 10217 10255 D BtGatt.ScanManager: stopping BLe Batch
07-21 16:02:19.687 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.688 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.688 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.688 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-21 16:02:19.688 10094 10157 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-21 16:02:19.690 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-21 16:02:19.690 10094 10157 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
07-21 16:02:19.690 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.692 10217 10237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-21 16:02:19.693 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-21 16:02:19.693 10217 10255 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-21 16:02:19.694 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.694 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-21 16:02:19.695 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 127
,07-21 16:02:19.696 10094 10157 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 127
07-21 16:02:19.696 10094 10157 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8a87e removed from the list
07-21 16:02:19.696 10094 10157 D io.jxcore.node.ConnectivityMonitor: stop
07-21 16:02:19.696 10094 10157 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-21 16:02:19.697 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:02:19.697 10094 10157 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-21 16:02:19.697 10094 10094 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-21 16:02:19.698 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,07-21 16:02:19.700 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:02:19.700 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-21 16:02:19.700 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
07-21 16:02:19.701 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:02:19.701 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-21 16:02:19.702 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:02:19.702 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
07-21 16:02:19.702 10094 10094 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-21 16:02:19.702 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-21 16:02:19.703 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-21 16:02:19.703 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-21 16:02:19.703 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-21 16:02:19.703 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-21 16:02:19.703 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-21 16:02:19.703 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-21 16:02:19.703 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-21 16:02:19.703 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-21 16:02:19.703 10094 10094 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-21 16:02:19.703 10094 10157 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-21 16:02:19.704 10094 10094 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-21 16:02:19.704 10217 10237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-21 16:02:19.705 10217 10237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-21 16:02:19.705 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
07-21 16:02:19.705  3675  4946 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op,:PendingIntent{e291999: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:19.707 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
07-21 16:02:19.707  3675  4931 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :10217 / op:PendingIntent{2a2b45e: PendingIntentRecord{3730de4 com.android.bluetooth broadcastIntent}}
07-21 16:02:19.709 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,07-21 16:02:19.710 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,07-21 16:02:19.712 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,07-21 16:02:19.714 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,07-21 16:02:19.715 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,07-21 16:02:19.717 10094 10157 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,07-21 16:02:20.163  3675  3861 D SamsungAlarmManager: Expired : 4
,07-21 16:02:20.164  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775322, nowELAPSED=237945
07-21 16:02:20.165  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@68de257 alarm=Alarm{efa03f type 2 when 237944 android}
,07-21 16:02:20.169  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,07-21 16:02:20.172 10493 10493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-21 16:02:20.173 10493 10493 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-21 16:02:20.178  3675  3925 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160236 - CU:1000/CP:3675
07-21 16:02:20.179  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160236, SetElapsed=253950, nowELAPSED=237960
,07-21 16:02:20.184  3675  3954 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160235 - CU:1000/CP:3675
,07-21 16:02:20.187 10493 10493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-21 16:02:20.205 10094 10094 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-21 16:02:21.625  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:21.626  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-21 16:02:21.723 10094 10157 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,07-21 16:02:21.863 10094 10735 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 259, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:21.863 10094 10735 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:21.863 10094 10735 D io.jxcore.node.StreamCopyingThread:  id: 83
,07-21 16:02:22.177  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:22.630 10094 10735 W !!      : call onHalfStreamCopied
07-21 16:02:22.630 10094 10735 I testCopyDataAndClose: closing input stream
,07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 259, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread:  id: 83
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread:  id: 83
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 259, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:23.308 10094 10735 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-21 16:02:23.698  3675  4931 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10112
,07-21 16:02:23.710 10681 10681 I Babel_ConcService: Binding ConcurrentService
,07-21 16:02:23.750 10681 10737 I Babel_ConcService: Scheduling delay with GcmNetworkManager of 244813 s for task fstaccount_reg_renewal_25878_3 and tag network_connectivity_wakeup:persisted
,07-21 16:02:23.768 10681 10737 I Babel_ConcService: Scheduling delay with GcmNetworkManager of 3599 s for task fvzDB_CLEANUP_241458_1 and tag timed_wakeup
,07-21 16:02:23.771 10681 10742 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
,07-21 16:02:23.772 10681 10742 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
07-21 16:02:23.773 10681 10740 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
,07-21 16:02:23.774 10681 10740 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
07-21 16:02:23.774 10681 10741 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
07-21 16:02:23.775 10681 10738 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
07-21 16:02:23.776 10681 10738 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
07-21 16:02:23.777 10681 10739 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
,07-21 16:02:23.779 10681 10739 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-21 16:02:23.795  3675  4942 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{7c4dec5: PendingIntentRecord{cc48b54 com.google.android.gms broadcastIntent}}
,07-21 16:02:23.812  3675  3927 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170721T170208 - CU:10019/CP:4735
,07-21 16:02:23.818  3675  4177 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4735 / op:PendingIntent{c11101a: PendingIntentRecord{cc48b54 com.google.android.gms broadcastIntent}}
,07-21 16:02:23.828  3675  4946 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170721T170208 - CU:10019/CP:4735
,07-21 16:02:23.891  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:24.176  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:02:24.177 10493 10493 I wpa_supplicant: nl80211: Received scan results (29 BSSes)
07-21 16:02:24.178  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:02:24.178  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:02:24.184  3675  3954 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@268b655
,07-21 16:02:24.373  4645  4645 D io_stats: !@   8,0 r 26172 2322948 w 5362 209432 d 737 74160 f 2127 2127 iot 11950 11119 th 474076 0 0 pt 0 inp 0 0 242.153
,07-21 16:02:24.642  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:24.642  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:24.727 10094 10157 I StreamCopyingThreadTest: Starting test: testCopyBigData
,07-21 16:02:24.759 10094 10743 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 262, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:24.759 10094 10743 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:24.759 10094 10743 D io.jxcore.node.StreamCopyingThread:  id: 85
,07-21 16:02:24.923  3675  5817 D SSRM:f  : SIOP:: AP = 300, PST = 274 (W:6), CP = 221, CUR = -85, LCD = 57
,07-21 16:02:25.747  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:25.760  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:25.768  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:25.776  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:25.788  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 262, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread:  id: 85
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread:  id: 85
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 262, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:26.128 10094 10743 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-21 16:02:26.166  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:26.508  3675  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-21 16:02:27.462 10094 10157 I StreamCopyingThreadTest: Starting test: testRunNotify
,07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 264, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread:  id: 86
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 264, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread:  id: 86
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread:  id: 86
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 264, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:27.463 10094 10744 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
07-21 16:02:27.463 10094 10157 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,07-21 16:02:27.463 10094 10157 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-21 16:02:27.464 10094 10157 I StreamCopyingThreadTest: Starting test: testRunWithException
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 268, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread:  id: 89
07-21 16:02:27.464 10094 10745 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 268, thread name: My test thread name): Test exception.
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 268, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 268, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-21 16:02:27.464 10094 10745 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-21 16:02:27.465 10094 10157 I jxcore-log: 2017-07-21 14:02:27 - DEBUG UnitTest_app: 'Running unit tests'
07-21 16:02:27.465 10094 10157 I jxcore-log: 
07-21 16:02:27.465 10094 10157 I jxcore-log: *Native tests were executed*
07-21 16:02:27.465 10094 10157 I jxcore-log: 
07-21 16:02:27.465 10094 10157 I jxcore-log: Total number of executed tests:  78
07-21 16:02:27.465 10094 10157 I jxcore-log: 
07-21 16:02:27.465 10094 10157 I jxcore-log: Number of passed tests:  76
07-21 16:02:27.465 10094 10157 I jxcore-log: 
07-21 16:02:27.466 10094 10157 I jxcore-log: Number of failed tests:  0
07-21 16:02:27.466 10094 10157 I jxcore-log: 
07-21 16:02:27.466 10094 10157 I jxcore-log: Number of ignored tests:  2
07-21 16:02:27.466 10094 10157 I jxcore-log: 
07-21 16:02:27.466 10094 10157 I jxcore-log: Total duration:  47328
07-21 16:02:27.466 10094 10157 I jxcore-log: 
,07-21 16:02:27.466 10094 10157 I jxcore-log: 2017-07-21 14:02:27 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
07-21 16:02:27.466 10094 10157 I jxcore-log: 
07-21 16:02:27.466 10094 10157 I jxcore-log: 2017-07-21 14:02:27 - WARN testUtils: 'myNameCallback not set!'
07-21 16:02:27.466 10094 10157 I jxcore-log: 
,07-21 16:02:27.668  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:27.668  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:28.913 10094 10157 I jxcore-log: 2017-07-21 14:02:28 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
07-21 16:02:28.913 10094 10157 I jxcore-log: 
,07-21 16:02:28.917 10094 10157 I jxcore-log: 2017-07-21 14:02:28 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
07-21 16:02:28.917 10094 10157 I jxcore-log: 
,07-21 16:02:28.926 10094 10157 I jxcore-log: 2017-07-21 14:02:28 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
07-21 16:02:28.926 10094 10157 I jxcore-log: 
,07-21 16:02:29.085 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
07-21 16:02:29.085 10094 10157 I jxcore-log: 
,07-21 16:02:29.113 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
07-21 16:02:29.113 10094 10157 I jxcore-log: 
,07-21 16:02:29.122 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
07-21 16:02:29.122 10094 10157 I jxcore-log: 
,07-21 16:02:29.155 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
07-21 16:02:29.155 10094 10157 I jxcore-log: 
,07-21 16:02:29.173 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
07-21 16:02:29.173 10094 10157 I jxcore-log: 
,07-21 16:02:29.177 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
07-21 16:02:29.177 10094 10157 I jxcore-log: 
,07-21 16:02:29.222 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
07-21 16:02:29.222 10094 10157 I jxcore-log: 
,07-21 16:02:29.225 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
07-21 16:02:29.225 10094 10157 I jxcore-log: 
,07-21 16:02:29.228 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
07-21 16:02:29.228 10094 10157 I jxcore-log: 
,07-21 16:02:29.232 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
07-21 16:02:29.232 10094 10157 I jxcore-log: 
,07-21 16:02:29.377  4645  4645 D io_stats: !@   8,0 r 26172 2322948 w 5380 209568 d 737 74160 f 2128 2128 iot 11960 11123 th 469476 0 0 pt 0 inp 0 0 247.157
,07-21 16:02:29.382  3675  4544 I ActivityManager: KPU : put [com.samsung.android.bluelightfilter] : 19948 K
,07-21 16:02:29.382  3675  4544 I ActivityManager: Killing 9884:com.samsung.android.bluelightfilter/u0a184 (adj 906): DHA:empty #33
,07-21 16:02:29.407  3675  3920 D ActivityManager: cleanUpApplicationRecord -- 9884
,07-21 16:02:29.408  4768  6456 D ForegroundUtils: could not check pending caller
,07-21 16:02:29.550 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
07-21 16:02:29.550 10094 10157 I jxcore-log: 
,07-21 16:02:29.555 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
07-21 16:02:29.555 10094 10157 I jxcore-log: 
,07-21 16:02:29.619 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
07-21 16:02:29.619 10094 10157 I jxcore-log: 
,07-21 16:02:29.622 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
07-21 16:02:29.622 10094 10157 I jxcore-log: 
,07-21 16:02:29.638 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
07-21 16:02:29.638 10094 10157 I jxcore-log: 
,07-21 16:02:29.642 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
07-21 16:02:29.642 10094 10157 I jxcore-log: 
,07-21 16:02:29.672 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
07-21 16:02:29.672 10094 10157 I jxcore-log: 
,07-21 16:02:29.713 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
07-21 16:02:29.713 10094 10157 I jxcore-log: 
,07-21 16:02:29.746 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
07-21 16:02:29.746 10094 10157 I jxcore-log: 
,07-21 16:02:29.775 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
07-21 16:02:29.775 10094 10157 I jxcore-log: 
,07-21 16:02:29.783 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
07-21 16:02:29.783 10094 10157 I jxcore-log: 
,07-21 16:02:29.829 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
07-21 16:02:29.829 10094 10157 I jxcore-log: 
,07-21 16:02:29.858 10094 10157 I jxcore-log: 2017-07-21 14:02:29 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
07-21 16:02:29.858 10094 10157 I jxcore-log: 
,07-21 16:02:30.484 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
07-21 16:02:30.484 10094 10157 I jxcore-log: 
,07-21 16:02:30.511 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
07-21 16:02:30.511 10094 10157 I jxcore-log: 
,07-21 16:02:30.515 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
07-21 16:02:30.515 10094 10157 I jxcore-log: 
,07-21 16:02:30.519 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
07-21 16:02:30.519 10094 10157 I jxcore-log: 
,07-21 16:02:30.537 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
07-21 16:02:30.537 10094 10157 I jxcore-log: 
,07-21 16:02:30.555 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
07-21 16:02:30.555 10094 10157 I jxcore-log: 
,07-21 16:02:30.569 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
07-21 16:02:30.569 10094 10157 I jxcore-log: 
,07-21 16:02:30.577 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
07-21 16:02:30.577 10094 10157 I jxcore-log: 
,07-21 16:02:30.584 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
07-21 16:02:30.584 10094 10157 I jxcore-log: 
,07-21 16:02:30.592 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
07-21 16:02:30.592 10094 10157 I jxcore-log: 
,07-21 16:02:30.608 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
07-21 16:02:30.608 10094 10157 I jxcore-log: 
,07-21 16:02:30.620 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
07-21 16:02:30.620 10094 10157 I jxcore-log: 
,07-21 16:02:30.627 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
07-21 16:02:30.627 10094 10157 I jxcore-log: 
,07-21 16:02:30.683  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:30.683  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:30.793 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
07-21 16:02:30.793 10094 10157 I jxcore-log: 
,07-21 16:02:30.796 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
07-21 16:02:30.796 10094 10157 I jxcore-log: 
,07-21 16:02:30.809 10094 10157 D BluetoothAdapter: STATE_ON
,07-21 16:02:30.814 10094 10157 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-21 16:02:30.815 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO testUtils: 'BLE multiple advertisement supported'
07-21 16:02:30.815 10094 10157 I jxcore-log: 
07-21 16:02:30.817 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - DEBUG UnitTest_app: 'Unit Test app is loaded'
07-21 16:02:30.817 10094 10157 I jxcore-log: 
,07-21 16:02:30.824 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-21 16:02:30.824 10094 10157 I jxcore-log: 
07-21 16:02:30.824 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-21 16:02:30.824 10094 10157 I jxcore-log: 
,07-21 16:02:30.825 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-21 16:02:30.825 10094 10157 I jxcore-log: 
07-21 16:02:30.825 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-21 16:02:30.825 10094 10157 I jxcore-log: 
07-21 16:02:30.825 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-21 16:02:30.825 10094 10157 I jxcore-log: 
,07-21 16:02:30.826 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-21 16:02:30.826 10094 10157 I jxcore-log: 
07-21 16:02:30.826 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-21 16:02:30.826 10094 10157 I jxcore-log: 
07-21 16:02:30.826 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-21 16:02:30.826 10094 10157 I jxcore-log: 
07-21 16:02:30.826 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-21 16:02:30.826 10094 10157 I jxcore-log: 
07-21 16:02:30.826 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-21 16:02:30.826 10094 10157 I jxcore-log: 
07-21 16:02:30.827 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-21 16:02:30.827 10094 10157 I jxcore-log: 
07-21 16:02:30.827 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-21 16:02:30.827 10094 10157 I jxcore-log: 
,07-21 16:02:30.836 10094 10094 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,07-21 16:02:30.836 10094 10094 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,07-21 16:02:30.850 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
07-21 16:02:30.850 10094 10157 I jxcore-log: 
,07-21 16:02:30.926 10094 10157 I jxcore-log: 2017-07-21 14:02:30 - DEBUG CoordinatedClient: 'connected to the test server'
07-21 16:02:30.926 10094 10157 I jxcore-log: 
,07-21 16:02:33.716  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:33.716  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:34.382  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5383 209580 d 737 74160 f 2128 2128 iot 11970 11124 th 472316 0 0 pt 0 inp 0 0 252.162
,07-21 16:02:34.948  3675  5817 D SSRM:f  : SIOP:: AP = 310, PST = 283 (W:6), CP = 232, CUR = -114, LCD = 57
,07-21 16:02:35.785  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:02:35.787  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-21 16:02:35.789  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:02:35.789  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:02:36.169  3675  3861 D SamsungAlarmManager: Expired : 4
07-21 16:02:36.170  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775322, nowELAPSED=253951
,07-21 16:02:36.171  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@8949d0c alarm=Alarm{eff5528 type 2 when 253950 android}
,07-21 16:02:36.174  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 32000: mInRange : true
,07-21 16:02:36.178 10493 10493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-21 16:02:36.181  3675  3925 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160308 - CU:1000/CP:3675
07-21 16:02:36.182 10493 10493 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-21 16:02:36.182  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160308, SetElapsed=285956, nowELAPSED=253963
,07-21 16:02:36.190  3675  3954 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160251 - CU:1000/CP:3675
07-21 16:02:36.191  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160251, SetElapsed=268961, nowELAPSED=253972
,07-21 16:02:36.202 10493 10493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-21 16:02:36.742  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:36.742  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:37.582  4924  5006 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 8ms lastUpdatedAfter : 41361 ms mFlush_time_threasold : 2000 mCurrentSize : 229
,07-21 16:02:37.621  5251 10755 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-21 16:02:37.644  5251  5710 I Icing   : App usage reports: 1
,07-21 16:02:37.645  5251  5710 I Icing   : Usage reports 1 indexed 0 rejected 0 imm upload false
,07-21 16:02:37.701  5251  5710 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-21 16:02:37.731  5251  5710 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-21 16:02:37.770  5251  5827 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-21 16:02:37.815  5251  5710 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-21 16:02:37.846  3675  4460 E Watchdog: !@Sync 8 [21_lip_16_02_37.846]
,07-21 16:02:37.850  5251  5710 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-21 16:02:37.885  5251  5827 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-21 16:02:38.576  3675  4942 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSCM@ACs
07-21 16:02:38.576  3675  4942 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSCM@ACs
,07-21 16:02:38.590  3675  4942 I Telecom : com.android.server.telecom.PhoneAccountRegistrar: SimCallManager queried, returning: null: TSI.gSCM@ACs
,07-21 16:02:38.608 10681 10681 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-21 16:02:38.637 10681 10681 W Babel   : BAM#gBA: invalid account id: -1
,07-21 16:02:38.638 10681 10681 W Babel   : BAM#gBA: invalid account id: -1
07-21 16:02:38.638 10681 10681 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-21 16:02:38.655  3675  4946 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSCM@AC0
07-21 16:02:38.655  3675  4946 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSCM@AC0
,07-21 16:02:38.660  3675  4946 I Telecom : com.android.server.telecom.PhoneAccountRegistrar: SimCallManager queried, returning: null: TSI.gSCM@AC0
,07-21 16:02:39.388  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5420 210268 d 746 74196 f 2147 2147 iot 12030 11155 th 471992 0 0 pt 0 inp 0 0 257.166
,07-21 16:02:39.765  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:39.765  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:40.185  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:02:40.187 10493 10493 I wpa_supplicant: nl80211: Received scan results (15 BSSes)
,07-21 16:02:40.189  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:02:40.189  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:02:40.195  3675  3954 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@72013e6
,07-21 16:02:40.197  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160308, SetElapsed=285956, nowELAPSED=257978
,07-21 16:02:40.799  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-21 16:02:40.799  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-21 16:02:40.799  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({system=1, android.process.acore=1, com.google.android.gms=2})  ]
,07-21 16:02:40.806  4924  5006 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 1Kb duration : 5ms lastUpdatedAfter : 3224 ms mFlush_time_threasold : 2000 mCurrentSize : 525
,07-21 16:02:42.800  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-21 16:02:42.800  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:44.393  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5459 210584 d 750 74212 f 2149 2149 iot 12030 11164 th 472592 0 0 pt 0 inp 0 0 262.173
,07-21 16:02:44.975  3675  5817 D SSRM:f  : SIOP:: AP = 280, PST = 285 (W:14), CP = 230, CUR = -45, LCD = 57
,07-21 16:02:45.831  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:45.831  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:46.064  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-21 16:02:48.449  3675  4946 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:02:48.450  3675  4946 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4314, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-21 16:02:48.451  3675  4946 D BatteryService: online:4, current avg:-33, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-21 16:02:48.451  3675  3675 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-21 16:02:48.463  3675  3675 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-21 16:02:48.463  3675  3675 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-21 16:02:48.467  3675  3675 D GameManagerService: new battery level: 100
,07-21 16:02:48.473  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-21 16:02:48.474  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-21 16:02:48.484  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-21 16:02:48.490  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:02:48.491  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
07-21 16:02:48.496  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-21 16:02:48.510 10217 10217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-21 16:02:48.510 10217 10274 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-21 16:02:48.865  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:48.865  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:49.333  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-21 16:02:49.398  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5461 210636 d 751 74216 f 2151 2151 iot 12030 11167 th 472636 0 0 pt 0 inp 0 0 267.178
,07-21 16:02:51.894  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:51.894  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:54.404  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5476 210844 d 753 74224 f 2155 2155 iot 12030 11173 th 472580 0 0 pt 0 inp 0 0 272.183
,07-21 16:02:54.927  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:54.927  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:55.003  3675  5817 D SSRM:f  : SIOP:: AP = 270, PST = 281 (W:14), CP = 225, CUR = -18, LCD = 57
,07-21 16:02:57.961  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:02:57.962  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:02:59.409  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5488 210944 d 754 74228 f 2156 2156 iot 12030 11177 th 474232 0 0 pt 0 inp 0 0 277.189
,07-21 16:03:00.000  3675  3861 D SamsungAlarmManager: Expired : 8
,07-21 16:03:00.001  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{c8b4296 type 3 when 277781 android}
,07-21 16:03:00.011  3675  3675 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170721T160400 - CU:1000/CP:3675
,07-21 16:03:00.015  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-21 16:03:00.016  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-21 16:03:00.017  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-21 16:03:00.048  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-21 16:03:00.049  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
07-21 16:03:00.052  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-21 16:03:00.063  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:03:00.067  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
07-21 16:03:00.085  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:03:00.089  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:03:00.106  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:03:00.108  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:03:00.115  4068  4068 V hong    : mid yDiff = 438
07-21 16:03:00.115  4068  4068 V hong    : mid yDiff = 438
07-21 16:03:00.115  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-21 16:03:00.116  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-21 16:03:00.119  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:03:00.121  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:03:00.131  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:03:00.133  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:03:00.147  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-21 16:03:00.150  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-21 16:03:00.155  5421  5421 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-21 16:03:00.157  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-21 16:03:00.164  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-21 16:03:00.168  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
07-21 16:03:00.170  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-21 16:03:00.171  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-21 16:03:00.172  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-21 16:03:00.172  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-21 16:03:00.176  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-21 16:03:00.178  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C2514A0CC6C8F04ED8328A696DC40F869C43FF8FB54C1160067B0758D89FAA0505EDC7E27176DE4401C9DA1643EF7151A]}
,07-21 16:03:00.179  5421  5421 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-21 16:03:00.989  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:00.990  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:03.252  3675  3790 I PowerManagerService: [PWL] On : 0 (281033 ms ago)
07-21 16:03:03.253  3675  3790 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-21 16:03:04.024  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:04.024  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:05.029  3675  5817 D SSRM:f  : SIOP:: AP = 260, PST = 280 (W:14), CP = 222, CUR = -7, LCD = 57
,07-21 16:03:05.791  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:03:05.792  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-21 16:03:05.794  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:03:05.794  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:03:07.055  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:07.055  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:07.848  3675  4460 E Watchdog: !@Sync 9 [21_lip_16_03_07.847]
,07-21 16:03:08.175  3675  3861 D SamsungAlarmManager: Expired : 4
,07-21 16:03:08.176  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775322, nowELAPSED=285957
07-21 16:03:08.177  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170721T160400, SetElapsed=337781, nowELAPSED=285958
07-21 16:03:08.177  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@399a241 alarm=Alarm{b993e17 type 2 when 285956 android}
,07-21 16:03:08.181  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 64000: mInRange : true
,07-21 16:03:08.185 10493 10493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-21 16:03:08.186 10493 10493 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-21 16:03:08.192  3675  3925 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160412 - CU:1000/CP:3675
07-21 16:03:08.193  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160412, SetElapsed=349963, nowELAPSED=285974
,07-21 16:03:08.200  3675  3954 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160323 - CU:1000/CP:3675
,07-21 16:03:08.201  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160323, SetElapsed=300973, nowELAPSED=285982
,07-21 16:03:08.204 10493 10493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-21 16:03:09.540  3675  4015 D WifiWatchdogStateMachine:  [|215] []
,07-21 16:03:10.077  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:10.078  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:03:12.214  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:03:12.215 10493 10493 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
,07-21 16:03:12.217  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:03:12.217  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:03:12.221  3675  3954 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@d9e63ed
07-21 16:03:12.224  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160412, SetElapsed=349963, nowELAPSED=290005
,07-21 16:03:13.111  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:13.111  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:15.056  3675  5817 D SSRM:f  : SIOP:: AP = 260, PST = 280 (W:14), CP = 219, LCD = 57
,07-21 16:03:15.205  3675  3685 I art     : Background sticky concurrent mark sweep GC freed 215301(11MB) AllocSpace objects, 61(1268KB) LOS objects, 25% free, 42MB/56MB, paused 3.885ms total 149.905ms
,07-21 16:03:16.144  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:16.145  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:17.298  3675  4018 D WifiWatchdogStateMachine:  [|1]
,07-21 16:03:17.577  3675  4017 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
,07-21 16:03:17.578  3675  4017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
,07-21 16:03:18.506  3675  3720 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:03:19.183  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:19.184  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:03:19.430  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5496 210980 d 754 74228 f 2157 2157 iot 12030 11178 th 474156 0 0 pt 0 inp 0 0 297.209
,07-21 16:03:22.216  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:22.217  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:03:24.435  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5497 210992 d 754 74228 f 2158 2158 iot 12030 11179 th 474840 0 0 pt 0 inp 0 0 302.215
,07-21 16:03:25.101  3675  5817 D SSRM:f  : SIOP:: AP = 260, PST = 277 (W:14), CP = 218, LCD = 57
,07-21 16:03:25.250  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:25.250  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:03:28.284  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:28.284  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:03:29.442  4645  4645 D io_stats: !@   8,0 r 26176 2323220 w 5498 210996 d 754 74228 f 2158 2158 iot 12030 11180 th 474872 0 0 pt 0 inp 0 0 307.221
,07-21 16:03:31.314  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:31.314  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:33.782  3675  3875 I TLC_TIMA_PKM_initialize: initializing...
07-21 16:03:33.782  3675  3875 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-21 16:03:33.782  3675  3875 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-21 16:03:33.782  3675  3875 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
07-21 16:03:33.782  3675  3875 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-21 16:03:33.782  3675  3875 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-21 16:03:33.782  3675  3875 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-21 16:03:33.783  3675  3875 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-21 16:03:33.783  3675  3875 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
07-21 16:03:33.783  3675  3875 I TZ: mc_tlc_communication: device_id = 0x0
07-21 16:03:33.783  3675  3875 I TZ: mc_tlc_communication: tlc_open() was called
07-21 16:03:33.783  3675  3875 I TZ: mc_tlc_communication: Opening MobiCore device
07-21 16:03:33.783  3675  3875 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,07-21 16:03:33.785  3675  3875 I TZ: mc_tlc_communication: Opening the session
,07-21 16:03:33.835  3675  3875 I TZ: mc_tlc_communication: tlc_open() succeeded
07-21 16:03:33.836  3675  3875 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,07-21 16:03:33.847  3675  3875 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,07-21 16:03:33.881  3675  3875 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,07-21 16:03:33.887  3675  3875 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,07-21 16:03:33.892  3675  3875 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-21 16:03:34.353  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:34.353  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:34.446  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5498 210996 d 754 74228 f 2158 2158 iot 12050 11184 th 474588 0 0 pt 0 inp 0 0 312.226
,07-21 16:03:35.127  3675  5817 D SSRM:f  : SIOP:: AP = 260, PST = 273 (W:14), CP = 217, LCD = 57
,07-21 16:03:35.795  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:03:35.797  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-21 16:03:35.799  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
,07-21 16:03:35.799  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:03:37.380  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:37.380  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:37.849  3675  4460 E Watchdog: !@Sync 10 [21_lip_16_03_37.849]
,07-21 16:03:38.042  3675  3875 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-21 16:03:38.042  3675  3875 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-21 16:03:40.283  3675  4987 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170721T183338 - CU:10007/CP:4782
,07-21 16:03:40.410  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:40.411  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:40.850  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-21 16:03:40.850  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-21 16:03:40.850  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-21 16:03:40.857  4924  5006 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60051 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-21 16:03:43.445  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:43.445  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:44.456  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5502 211084 d 755 74232 f 2160 2160 iot 12060 11188 th 474540 0 0 pt 0 inp 0 0 322.236
,07-21 16:03:44.460  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-21 16:03:45.157  3675  5817 D SSRM:f  : SIOP:: AP = 260, PST = 272 (W:14), CP = 216, LCD = 57
,07-21 16:03:45.988  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-21 16:03:46.474  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:46.475  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:48.563  3675  3719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:03:49.234  5251  6671 V NativeCrypto: SSL shutdown failed: ssl=0x79b195b500: I/O error during system call, Software caused connection abort
,07-21 16:03:49.462  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5506 211136 d 756 74236 f 2162 2162 iot 12060 11190 th 474692 0 0 pt 0 inp 0 0 327.241
,07-21 16:03:49.500  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:49.500  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:52.526  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:52.527  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:54.471  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5514 211180 d 756 74236 f 2163 2163 iot 12060 11192 th 474836 0 0 pt 0 inp 0 0 332.250
,07-21 16:03:55.185  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 270 (W:14), CP = 215, LCD = 57
,07-21 16:03:55.560  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:55.560  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:03:58.271  3675  3790 I PowerManagerService: [PWL] On : 0 (336051 ms ago)
07-21 16:03:58.271  3675  3790 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-21 16:03:58.594  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:03:58.595  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:04:00.000  3675  3861 D SamsungAlarmManager: Expired : 8
,07-21 16:04:00.001  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{bcfd90f type 3 when 337781 android}
,07-21 16:04:00.011  3675  3675 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170721T160500 - CU:1000/CP:3675
,07-21 16:04:00.015  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-21 16:04:00.016  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-21 16:04:00.017  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-21 16:04:00.042  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-21 16:04:00.053  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-21 16:04:00.056  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-21 16:04:00.061  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:04:00.063  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:04:00.066  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:04:00.072  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:04:00.083  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:04:00.085  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:04:00.087  4068  4068 V hong    : mid yDiff = 438
,07-21 16:04:00.087  4068  4068 V hong    : mid yDiff = 438
07-21 16:04:00.088  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
,07-21 16:04:00.095  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-21 16:04:00.097  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:04:00.099  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:04:00.114  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:04:00.116  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:04:00.132  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
07-21 16:04:00.135  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-21 16:04:00.140  5421  5421 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-21 16:04:00.142  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
07-21 16:04:00.146  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-21 16:04:00.152  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-21 16:04:00.153  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
07-21 16:04:00.154  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-21 16:04:00.155  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-21 16:04:00.156  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-21 16:04:00.161  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
07-21 16:04:00.162  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C2514A0CC6C8F04ED8328A696DC40F8699E88589312B85FBDE4AAB0AFC0261BB5EFBD11F7E1C8825F04E97D14C8F0A025]}
07-21 16:04:00.163  5421  5421 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-21 16:04:01.620  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:01.620  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:04:04.500  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-21 16:04:04.654  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:04.654  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:04:05.213  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 267 (W:14), CP = 214, LCD = 57
,07-21 16:04:05.800  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:04:05.802  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-21 16:04:05.803  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:04:05.803  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:04:07.450  3291  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-21 16:04:07.692  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:07.693  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:04:07.848 10094 10157 I jxcore-log: TAP version 13
07-21 16:04:07.848 10094 10157 I jxcore-log: 
,07-21 16:04:07.850  3675  4460 E Watchdog: !@Sync 11 [21_lip_16_04_07.850]
,07-21 16:04:07.881 10094 10157 I jxcore-log: # setup
07-21 16:04:07.881 10094 10157 I jxcore-log: 
,07-21 16:04:09.552 10094 10157 I jxcore-log: # closeAll can close even when connections open
07-21 16:04:09.552 10094 10157 I jxcore-log: 
,07-21 16:04:10.713  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:10.713  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:10.722 10094 10157 I jxcore-log: 2017-07-21 14:04:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
07-21 16:04:10.722 10094 10157 I jxcore-log: 
,07-21 16:04:10.754 10094 10157 I jxcore-log: ok 1 not possible to connect to the server anymore
07-21 16:04:10.754 10094 10157 I jxcore-log: 
,07-21 16:04:10.767 10094 10157 I jxcore-log: # teardown
07-21 16:04:10.767 10094 10157 I jxcore-log: 
,07-21 16:04:10.773  3675  4015 D WifiWatchdogStateMachine:  [|217] []
,07-21 16:04:12.182  3675  3861 D SamsungAlarmManager: Expired : 4
,07-21 16:04:12.183  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775322, nowELAPSED=349964
07-21 16:04:12.184  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170721T160500, SetElapsed=397781, nowELAPSED=349965
07-21 16:04:12.185  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@df4a204 alarm=Alarm{e2d23a5 type 2 when 349963 android}
,07-21 16:04:12.188  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-21 16:04:12.192 10493 10493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-21 16:04:12.193 10493 10493 I wpa_supplicant: P2P: Current p2p state = IDLE
07-21 16:04:12.199  3675  3925 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160620 - CU:1000/CP:3675
07-21 16:04:12.200  3675  3925 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160620, SetElapsed=477972, nowELAPSED=349981
,07-21 16:04:12.210  3675  3954 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160427 - CU:1000/CP:3675
07-21 16:04:12.211  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160427, SetElapsed=364981, nowELAPSED=349992
,07-21 16:04:12.214 10493 10493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-21 16:04:12.371 10094 10157 I jxcore-log: # setup
07-21 16:04:12.371 10094 10157 I jxcore-log: 
,07-21 16:04:12.929 10094 10157 I jxcore-log: # closeAll with promise
07-21 16:04:12.929 10094 10157 I jxcore-log: 
,07-21 16:04:13.735  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:13.736  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:14.490 10094 10157 I jxcore-log: 2017-07-21 14:04:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
07-21 16:04:14.490 10094 10157 I jxcore-log: 
,07-21 16:04:14.524 10094 10157 I jxcore-log: ok 2 not possible to connect to the server anymore
07-21 16:04:14.524 10094 10157 I jxcore-log: 
,07-21 16:04:14.538 10094 10157 I jxcore-log: # teardown
07-21 16:04:14.538 10094 10157 I jxcore-log: 
,07-21 16:04:15.240  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 265 (W:14), CP = 214, LCD = 57
,07-21 16:04:16.236  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:04:16.239 10493 10493 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
,07-21 16:04:16.240  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:04:16.240  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:04:16.244  3675  3954 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@43af72b
,07-21 16:04:16.250  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160620, SetElapsed=477972, nowELAPSED=354031
,07-21 16:04:16.762  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:16.763  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:04:18.622  3675  4988 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-21 16:04:18.623  3675  4988 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4314, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
,07-21 16:04:18.623  3675  4988 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-21 16:04:18.624  3675  3675 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-21 16:04:18.636  3675  3675 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-21 16:04:18.636  3675  3675 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-21 16:04:18.641  3675  3675 D GameManagerService: new battery level: 100
,07-21 16:04:18.646  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-21 16:04:18.647  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-21 16:04:18.657  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-21 16:04:18.662  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:04:18.663  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:04:18.699 10217 10217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-21 16:04:18.700 10217 10274 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-21 16:04:18.701  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-21 16:04:19.403 10094 10157 I jxcore-log: # setup
07-21 16:04:19.403 10094 10157 I jxcore-log: 
,07-21 16:04:19.495  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5516 211188 d 756 74236 f 2164 2164 iot 12070 11193 th 473704 0 0 pt 0 inp 0 0 357.275
,07-21 16:04:19.795  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:19.796  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:04:22.365 10094 10157 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
07-21 16:04:22.365 10094 10157 I jxcore-log: 
,07-21 16:04:22.501 10094 10157 I jxcore-log: 2017-07-21 14:04:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
07-21 16:04:22.501 10094 10157 I jxcore-log: 
,07-21 16:04:22.510 10094 10157 I jxcore-log: ok 3 Got the right error
07-21 16:04:22.510 10094 10157 I jxcore-log: 
,07-21 16:04:22.523 10094 10157 I jxcore-log: # teardown
07-21 16:04:22.523 10094 10157 I jxcore-log: 
,07-21 16:04:22.823  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:22.823  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:24.500  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5517 211200 d 756 74236 f 2165 2165 iot 12070 11194 th 473660 0 0 pt 0 inp 0 0 362.280
,07-21 16:04:25.267  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 263 (W:14), CP = 214, LCD = 57
,07-21 16:04:25.441 10094 10157 I jxcore-log: # setup
07-21 16:04:25.441 10094 10157 I jxcore-log: 
,07-21 16:04:25.856  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:25.856  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:28.400 10094 10157 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
07-21 16:04:28.400 10094 10157 I jxcore-log: 
,07-21 16:04:28.530 10094 10157 I jxcore-log: 2017-07-21 14:04:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
07-21 16:04:28.530 10094 10157 I jxcore-log: 
,07-21 16:04:28.554 10094 10157 I jxcore-log: # teardown
07-21 16:04:28.554 10094 10157 I jxcore-log: 
,07-21 16:04:28.890  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:28.891  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:31.916  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:31.916  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:32.401 10094 10157 I jxcore-log: # setup
07-21 16:04:32.401 10094 10157 I jxcore-log: 
,07-21 16:04:32.459 10094 10157 I jxcore-log: # Call of onCheckpointReached handler on a single db change
07-21 16:04:32.459 10094 10157 I jxcore-log: 
,07-21 16:04:32.463 10094 10157 I jxcore-log: 2017-07-21 14:04:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
07-21 16:04:32.463 10094 10157 I jxcore-log: 
,07-21 16:04:34.510  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5525 211336 d 756 74236 f 2169 2169 iot 12080 11199 th 473592 0 0 pt 0 inp 0 0 372.290
,07-21 16:04:34.950  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:34.951  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:35.294  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 261 (W:14), CP = 213, LCD = 57
,07-21 16:04:35.805  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:04:35.806  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-21 16:04:35.808  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:04:35.808  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:04:36.080 10094 10157 I jxcore-log: # teardown
07-21 16:04:36.080 10094 10157 I jxcore-log: 
,07-21 16:04:37.852  3675  4460 E Watchdog: !@Sync 12 [21_lip_16_04_37.851]
,07-21 16:04:37.975  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:37.975  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:39.516  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5529 211392 d 757 74240 f 2170 2170 iot 12080 11202 th 473556 0 0 pt 0 inp 0 0 377.295
,07-21 16:04:40.405 10094 10157 I jxcore-log: # setup
07-21 16:04:40.405 10094 10157 I jxcore-log: 
,07-21 16:04:40.444 10094 10157 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
07-21 16:04:40.444 10094 10157 I jxcore-log: 
,07-21 16:04:40.448 10094 10157 I jxcore-log: 2017-07-21 14:04:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
07-21 16:04:40.448 10094 10157 I jxcore-log: 
,07-21 16:04:40.949  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-21 16:04:40.949  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-21 16:04:40.949  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-21 16:04:40.957  4924  5006 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60100 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-21 16:04:41.000  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:41.000  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:43.339 10094 10157 I jxcore-log: # teardown
07-21 16:04:43.339 10094 10157 I jxcore-log: 
,07-21 16:04:44.028  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:44.028  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:44.521  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5548 211676 d 762 74268 f 2176 2176 iot 12090 11212 th 473520 0 0 pt 0 inp 0 0 382.301
,07-21 16:04:45.325  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 259 (W:14), CP = 213, LCD = 57
,07-21 16:04:46.427 10094 10157 I jxcore-log: # setup
07-21 16:04:46.427 10094 10157 I jxcore-log: 
,07-21 16:04:46.469 10094 10157 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
07-21 16:04:46.469 10094 10157 I jxcore-log: 
,07-21 16:04:46.474 10094 10157 I jxcore-log: 2017-07-21 14:04:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
07-21 16:04:46.474 10094 10157 I jxcore-log: 
,07-21 16:04:47.061  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:47.062  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:48.678  3675  4988 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:04:49.424 10094 10157 I jxcore-log: # teardown
07-21 16:04:49.424 10094 10157 I jxcore-log: 
,07-21 16:04:49.499 10094 10157 I jxcore-log: # setup
07-21 16:04:49.499 10094 10157 I jxcore-log: 
,07-21 16:04:49.525  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5557 211872 d 767 74292 f 2182 2182 iot 12090 11219 th 473504 0 0 pt 0 inp 0 0 387.305
,07-21 16:04:50.094  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:50.094  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:52.381 10094 10157 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
07-21 16:04:52.381 10094 10157 I jxcore-log: 
,07-21 16:04:52.388 10094 10157 I jxcore-log: 2017-07-21 14:04:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
07-21 16:04:52.388 10094 10157 I jxcore-log: 
,07-21 16:04:53.121  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:53.121  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:54.530  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5571 212080 d 769 74308 f 2188 2188 iot 12100 11228 th 473556 0 0 pt 0 inp 0 0 392.309
,07-21 16:04:55.329 10094 10157 I jxcore-log: # teardown
07-21 16:04:55.329 10094 10157 I jxcore-log: 
,07-21 16:04:55.345  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 257 (W:14), CP = 213, LCD = 57
,07-21 16:04:55.366 10094 10157 I jxcore-log: # setup
07-21 16:04:55.366 10094 10157 I jxcore-log: 
,07-21 16:04:56.155  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:56.155  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:58.310  3675  3790 I PowerManagerService: [PWL] On : 0 (396091 ms ago)
07-21 16:04:58.310  3675  3790 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-21 16:04:58.398 10094 10157 I jxcore-log: # test defaultDirectory
07-21 16:04:58.398 10094 10157 I jxcore-log: 
,07-21 16:04:58.425 10094 10157 I jxcore-log: ok 4 should be equal
07-21 16:04:58.425 10094 10157 I jxcore-log: 
,07-21 16:04:58.430 10094 10157 I jxcore-log: ok 5 should be equal
07-21 16:04:58.430 10094 10157 I jxcore-log: 
,07-21 16:04:58.436 10094 10157 I jxcore-log: ok 6 should be equal
07-21 16:04:58.436 10094 10157 I jxcore-log: 
,07-21 16:04:58.448 10094 10157 I jxcore-log: # teardown
07-21 16:04:58.448 10094 10157 I jxcore-log: 
,07-21 16:04:59.182  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:04:59.182  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:04:59.535  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5581 212260 d 771 74324 f 2193 2193 iot 12100 11235 th 473488 0 0 pt 0 inp 0 0 397.315
,07-21 16:05:00.000  3675  3861 D SamsungAlarmManager: Expired : 8
,07-21 16:05:00.001  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{2377d46 type 3 when 397781 android}
,07-21 16:05:00.010  3675  3675 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170721T160600 - CU:1000/CP:3675
07-21 16:05:00.011  3675  3675 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170721T160600, SetElapsed=457781, nowELAPSED=397792
,07-21 16:05:00.016  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-21 16:05:00.017  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-21 16:05:00.017  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-21 16:05:00.041  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-21 16:05:00.048  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-21 16:05:00.051  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-21 16:05:00.057  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:05:00.059  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:05:00.065  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:05:00.068  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:05:00.082  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:05:00.084  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
07-21 16:05:00.085  4068  4068 V hong    : mid yDiff = 438
,07-21 16:05:00.085  4068  4068 V hong    : mid yDiff = 438
07-21 16:05:00.086  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-21 16:05:00.087  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-21 16:05:00.092  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:05:00.096  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:05:00.114  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:05:00.116  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:05:00.131  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-21 16:05:00.134  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-21 16:05:00.139  5421  5421 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-21 16:05:00.141  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-21 16:05:00.144  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-21 16:05:00.150  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-21 16:05:00.151  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-21 16:05:00.153  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-21 16:05:00.154  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-21 16:05:00.156  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-21 16:05:00.162  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-21 16:05:00.164  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C2514A0CC6C8F04ED8328A696DC40F869D7F03BE908FF97CE7AA718F6B5453606EC6AD29F1657C66E2B4A830497EF1448]}
,07-21 16:05:00.165  5421  5421 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-21 16:05:01.166 10094 10157 I jxcore-log: # setup
07-21 16:05:01.166 10094 10157 I jxcore-log: 
,07-21 16:05:01.189 10094 10157 I jxcore-log: # test defaultAdapter
07-21 16:05:01.189 10094 10157 I jxcore-log: 
,07-21 16:05:02.216  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:02.216  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:04.330 10094 10157 I jxcore-log: ok 7 should be equal
07-21 16:05:04.330 10094 10157 I jxcore-log: 
,07-21 16:05:04.331 10094 10157 I jxcore-log: ok 8 should be equal
07-21 16:05:04.331 10094 10157 I jxcore-log: 
,07-21 16:05:04.335 10094 10157 I jxcore-log: ok 9 should be equal
07-21 16:05:04.335 10094 10157 I jxcore-log: 
,07-21 16:05:04.337 10094 10157 I jxcore-log: ok 10 should be equal
07-21 16:05:04.337 10094 10157 I jxcore-log: 
,07-21 16:05:04.346 10094 10157 I jxcore-log: ok 11 should be equal
07-21 16:05:04.346 10094 10157 I jxcore-log: 
,07-21 16:05:04.348 10094 10157 I jxcore-log: ok 12 should be equal
07-21 16:05:04.348 10094 10157 I jxcore-log: 
,07-21 16:05:04.358 10094 10157 I jxcore-log: ok 13 should be equal
07-21 16:05:04.358 10094 10157 I jxcore-log: 
,07-21 16:05:04.359 10094 10157 I jxcore-log: ok 14 should be equal
07-21 16:05:04.359 10094 10157 I jxcore-log: 
,07-21 16:05:04.371 10094 10157 I jxcore-log: # teardown
07-21 16:05:04.371 10094 10157 I jxcore-log: 
,07-21 16:05:04.398 10094 10157 I jxcore-log: # setup
07-21 16:05:04.398 10094 10157 I jxcore-log: 
,07-21 16:05:04.540  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5587 212332 d 773 74332 f 2194 2194 iot 12100 11237 th 473376 0 0 pt 0 inp 0 0 402.320
,07-21 16:05:05.251  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:05.251  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:05.370  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 255 (W:14), CP = 212, LCD = 57
,07-21 16:05:05.809  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:05:05.811  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-21 16:05:05.812  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:05:05.812  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:05:07.767 10094 10157 I jxcore-log: # enqueue and run in order
07-21 16:05:07.767 10094 10157 I jxcore-log: 
,07-21 16:05:07.854  3675  4460 E Watchdog: !@Sync 13 [21_lip_16_05_07.853]
,07-21 16:05:07.960 10094 10157 I jxcore-log: ok 15 firstPromise setTimeout
07-21 16:05:07.960 10094 10157 I jxcore-log: 
,07-21 16:05:07.964 10094 10157 I jxcore-log: ok 16 firstPromise result
07-21 16:05:07.964 10094 10157 I jxcore-log: 
,07-21 16:05:07.966 10094 10157 I jxcore-log: ok 17 firstPromise testValue
07-21 16:05:07.966 10094 10157 I jxcore-log: 
,07-21 16:05:08.071 10094 10157 I jxcore-log: ok 18 secondPromise setTimeout
07-21 16:05:08.071 10094 10157 I jxcore-log: 
,07-21 16:05:08.074 10094 10157 I jxcore-log: ok 19 secondPromise result
07-21 16:05:08.074 10094 10157 I jxcore-log: 
,07-21 16:05:08.076 10094 10157 I jxcore-log: ok 20 secondPromise testValue
07-21 16:05:08.076 10094 10157 I jxcore-log: 
,07-21 16:05:08.080 10094 10157 I jxcore-log: ok 21 thirdPromise in promise
07-21 16:05:08.080 10094 10157 I jxcore-log: 
,07-21 16:05:08.083 10094 10157 I jxcore-log: ok 22 thirdPromise result
07-21 16:05:08.083 10094 10157 I jxcore-log: 
,07-21 16:05:08.086 10094 10157 I jxcore-log: ok 23 thirdPromise testValue
07-21 16:05:08.086 10094 10157 I jxcore-log: 
,07-21 16:05:08.096 10094 10157 I jxcore-log: # teardown
07-21 16:05:08.096 10094 10157 I jxcore-log: 
,07-21 16:05:08.276  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:08.277  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:08.434  9780  9870 V NativeCrypto: SSL shutdown failed: ssl=0x79afc84380: I/O error during system call, Software caused connection abort
,07-21 16:05:09.537  4735  7259 V NativeCrypto: SSL shutdown failed: ssl=0x79964cc400: I/O error during system call, Software caused connection abort
,07-21 16:05:11.309  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:11.309  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:12.321 10094 10157 I jxcore-log: # setup
07-21 16:05:12.321 10094 10157 I jxcore-log: 
,07-21 16:05:12.346 10094 10157 I jxcore-log: # enqueueAtTop and run backwards
07-21 16:05:12.346 10094 10157 I jxcore-log: 
,07-21 16:05:13.012  3675  4015 D WifiWatchdogStateMachine:  [|215] []
,07-21 16:05:14.342  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:14.342  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:14.550  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5591 212388 d 774 74336 f 2195 2195 iot 12100 11238 th 473296 0 0 pt 0 inp 0 0 412.330
,07-21 16:05:15.388 10094 10157 I jxcore-log: ok 24 thirdPromise - first to run
07-21 16:05:15.388 10094 10157 I jxcore-log: 
,07-21 16:05:15.392 10094 10157 I jxcore-log: ok 25 thirdPromise - in resolve
07-21 16:05:15.392 10094 10157 I jxcore-log: 
,07-21 16:05:15.394 10094 10157 I jxcore-log: ok 26 secondPromise - second to run
07-21 16:05:15.394 10094 10157 I jxcore-log: 
,07-21 16:05:15.396 10094 10157 I jxcore-log: ok 27 secondPromise - in catch
07-21 16:05:15.396 10094 10157 I jxcore-log: 
,07-21 16:05:15.399 10094 10157 I jxcore-log: ok 28 firstPromise - third to run
07-21 16:05:15.399 10094 10157 I jxcore-log: 
07-21 16:05:15.399  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 253 (W:14), CP = 212, LCD = 57
07-21 16:05:15.401 10094 10157 I jxcore-log: ok 29 firstPromise - in then
07-21 16:05:15.401 10094 10157 I jxcore-log: 
07-21 16:05:15.402 10094 10157 I jxcore-log: ok 30 testing promises
07-21 16:05:15.402 10094 10157 I jxcore-log: 
,07-21 16:05:15.413 10094 10157 I jxcore-log: # teardown
07-21 16:05:15.413 10094 10157 I jxcore-log: 
,07-21 16:05:17.375  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:17.375  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:18.372 10094 10157 I jxcore-log: # setup
07-21 16:05:18.372 10094 10157 I jxcore-log: 
,07-21 16:05:18.418 10094 10157 I jxcore-log: # mix enqueue and enqueueAtTop
07-21 16:05:18.418 10094 10157 I jxcore-log: 
,07-21 16:05:18.732  3675  4939 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:05:18.733  3675  4939 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4316, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-21 16:05:18.733  3675  4939 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-21 16:05:18.733  3675  3675 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-21 16:05:18.745  3675  3675 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-21 16:05:18.745  3675  3675 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-21 16:05:18.749  3675  3675 D GameManagerService: new battery level: 100
,07-21 16:05:18.754  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-21 16:05:18.755  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-21 16:05:18.771  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-21 16:05:18.788  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:05:18.789  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:05:18.793  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-21 16:05:18.800 10217 10217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-21 16:05:18.801 10217 10274 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-21 16:05:19.556  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5597 212420 d 774 74336 f 2196 2196 iot 12110 11239 th 473240 0 0 pt 0 inp 0 0 417.335
,07-21 16:05:20.407  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:20.407  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:21.335 10094 10157 I jxcore-log: ok 31 fourth
07-21 16:05:21.335 10094 10157 I jxcore-log: 
,07-21 16:05:21.337 10094 10157 I jxcore-log: ok 32 fourth
07-21 16:05:21.337 10094 10157 I jxcore-log: 
,07-21 16:05:21.339 10094 10157 I jxcore-log: ok 33 second
07-21 16:05:21.339 10094 10157 I jxcore-log: 
,07-21 16:05:21.341 10094 10157 I jxcore-log: ok 34 secondPromise - in then
07-21 16:05:21.341 10094 10157 I jxcore-log: 
,07-21 16:05:21.445 10094 10157 I jxcore-log: ok 35 first
07-21 16:05:21.445 10094 10157 I jxcore-log: 
,07-21 16:05:21.447 10094 10157 I jxcore-log: ok 36 firstPromise - in catch
07-21 16:05:21.447 10094 10157 I jxcore-log: 
,07-21 16:05:21.450 10094 10157 I jxcore-log: ok 37 third
07-21 16:05:21.450 10094 10157 I jxcore-log: 
,07-21 16:05:21.453 10094 10157 I jxcore-log: ok 38 thirdPromise - in then
07-21 16:05:21.453 10094 10157 I jxcore-log: 
,07-21 16:05:21.456 10094 10157 I jxcore-log: ok 39 testingPromises
07-21 16:05:21.456 10094 10157 I jxcore-log: 
,07-21 16:05:21.470 10094 10157 I jxcore-log: # teardown
07-21 16:05:21.470 10094 10157 I jxcore-log: 
,07-21 16:05:23.435  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-21 16:05:23.436  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:24.412 10094 10157 I jxcore-log: # setup
07-21 16:05:24.412 10094 10157 I jxcore-log: 
,07-21 16:05:24.439 10094 10157 I jxcore-log: # queues handled independently
07-21 16:05:24.439 10094 10157 I jxcore-log: 
,07-21 16:05:24.561  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5598 212432 d 774 74336 f 2197 2197 iot 12110 11240 th 473240 0 0 pt 0 inp 0 0 422.341
,07-21 16:05:25.428  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 252 (W:14), CP = 212, LCD = 57
,07-21 16:05:26.253 10094 10157 I jxcore-log: ok 40 all short operations completed before the long resolves
07-21 16:05:26.253 10094 10157 I jxcore-log: 
,07-21 16:05:26.259 10094 10157 I jxcore-log: # teardown
07-21 16:05:26.259 10094 10157 I jxcore-log: 
,07-21 16:05:26.282 10094 10157 I jxcore-log: # setup
07-21 16:05:26.282 10094 10157 I jxcore-log: 
,07-21 16:05:26.458  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:26.458  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:29.323 10094 10157 I jxcore-log: # enqueued function are always executed asynchronously
07-21 16:05:29.323 10094 10157 I jxcore-log: 
,07-21 16:05:29.343 10094 10157 I jxcore-log: ok 41 executor is not called here
07-21 16:05:29.343 10094 10157 I jxcore-log: 
,07-21 16:05:29.346 10094 10157 I jxcore-log: ok 42 executors is called
07-21 16:05:29.346 10094 10157 I jxcore-log: 
,07-21 16:05:29.360 10094 10157 I jxcore-log: # teardown
07-21 16:05:29.360 10094 10157 I jxcore-log: 
,07-21 16:05:29.481  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:29.482  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:29.566  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5599 212436 d 774 74336 f 2197 2197 iot 12110 11241 th 473164 0 0 pt 0 inp 0 0 427.346
,07-21 16:05:32.401 10094 10157 I jxcore-log: # setup
07-21 16:05:32.401 10094 10157 I jxcore-log: 
,07-21 16:05:32.474 10094 10157 I jxcore-log: # exceptions in the executor are properly handled
07-21 16:05:32.474 10094 10157 I jxcore-log: 
,07-21 16:05:32.497  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:32.497  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:35.454  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 252 (W:14), CP = 211, LCD = 57
,07-21 16:05:35.521  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:35.521  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:35.813  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:05:35.814  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-21 16:05:35.816  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:05:35.816  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:05:37.851 10094 10157 I jxcore-log: ok 43 got expected error
07-21 16:05:37.851 10094 10157 I jxcore-log: 
,07-21 16:05:37.855  3675  4460 E Watchdog: !@Sync 14 [21_lip_16_05_37.855]
,07-21 16:05:37.862 10094 10157 I jxcore-log: # teardown
07-21 16:05:37.862 10094 10157 I jxcore-log: 
,07-21 16:05:37.888 10094 10157 I jxcore-log: # setup
07-21 16:05:37.888 10094 10157 I jxcore-log: 
,07-21 16:05:38.560  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-21 16:05:38.561  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:40.374 10094 10157 I jxcore-log: # basic
07-21 16:05:40.374 10094 10157 I jxcore-log: 
,07-21 16:05:40.991  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-21 16:05:40.991  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-21 16:05:40.991  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-21 16:05:40.999  4924  5006 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60042 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-21 16:05:41.596  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:41.596  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:43.358 10094 10157 I jxcore-log: ok 44 sane
07-21 16:05:43.358 10094 10157 I jxcore-log: 
,07-21 16:05:43.375 10094 10157 I jxcore-log: # teardown
07-21 16:05:43.375 10094 10157 I jxcore-log: 
,07-21 16:05:43.441 10094 10157 I jxcore-log: # setup
07-21 16:05:43.441 10094 10157 I jxcore-log: 
,07-21 16:05:44.581  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5603 212528 d 775 74340 f 2199 2199 iot 12110 11244 th 473052 0 0 pt 0 inp 0 0 442.361
,07-21 16:05:44.626  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:44.626  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:45.481  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 251 (W:14), CP = 211, LCD = 57
,07-21 16:05:46.313 10094 10157 I jxcore-log: 2017-07-21 14:05:46 - DEBUG CoordinatedClient: 'device disconnected from the test server'
07-21 16:05:46.313 10094 10157 I jxcore-log: 
,07-21 16:05:47.660  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:47.660  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:48.518 10094 10157 I jxcore-log: 2017-07-21 14:05:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:05:48.518 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:05:48.518 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:05:48.518 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:05:48.518 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:05:48.518 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:05:48.518 10094 10157 I jxcore-log: 
,07-21 16:05:48.522 10094 10157 I jxcore-log: 2017-07-21 14:05:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:05:48.522 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:05:48.522 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:05:48.522 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:05:48.522 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:05:48.522 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:05:48.522 10094 10157 I jxcore-log: 
,07-21 16:05:48.788  3675  4987 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:05:49.588  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5608 212584 d 776 74344 f 2201 2201 iot 12110 11246 th 472944 0 0 pt 0 inp 0 0 447.367
,07-21 16:05:50.691  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:50.692  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:05:51.647 10094 10157 I jxcore-log: 2017-07-21 14:05:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:05:51.647 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:05:51.647 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:05:51.647 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:05:51.647 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:05:51.647 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:05:51.647 10094 10157 I jxcore-log: 
,07-21 16:05:51.651 10094 10157 I jxcore-log: 2017-07-21 14:05:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:05:51.651 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:05:51.651 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:05:51.651 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:05:51.651 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:05:51.651 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:05:51.651 10094 10157 I jxcore-log: 
,07-21 16:05:53.725  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:53.725  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:05:54.593  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5616 212628 d 776 74344 f 2202 2202 iot 12110 11248 th 472944 0 0 pt 0 inp 0 0 452.373
,07-21 16:05:55.507  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 211, LCD = 57
,07-21 16:05:56.760  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:56.760  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:05:59.786  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:05:59.786  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:00.000  3675  3861 D SamsungAlarmManager: Expired : 8
,07-21 16:06:00.001  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{6de27d2 type 3 when 457781 android}
,07-21 16:06:00.010  3675  3675 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170721T160700 - CU:1000/CP:3675
,07-21 16:06:00.014  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-21 16:06:00.015  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-21 16:06:00.015  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-21 16:06:00.037  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-21 16:06:00.045  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-21 16:06:00.048  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-21 16:06:00.052  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:06:00.054  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:06:00.057  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:06:00.062  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:06:00.070  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:06:00.071  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:06:00.077  4068  4068 V hong    : mid yDiff = 438
07-21 16:06:00.078  4068  4068 V hong    : mid yDiff = 438
,07-21 16:06:00.078  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-21 16:06:00.078  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
07-21 16:06:00.081  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:06:00.083  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:06:00.098  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:06:00.100  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:06:00.116  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-21 16:06:00.119  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-21 16:06:00.124  5421  5421 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-21 16:06:00.126  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-21 16:06:00.131  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-21 16:06:00.137  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-21 16:06:00.138  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-21 16:06:00.140  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-21 16:06:00.140  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-21 16:06:00.141  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-21 16:06:00.143  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-21 16:06:00.144  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C2514A0CC6C8F04ED8328A696DC40F869B7A36E68FFF07864702900DE9D90FCB569D6F8FF78BA58D6974B64713B93FD1F]}
07-21 16:06:00.145  5421  5421 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-21 16:06:01.683 10094 10157 I jxcore-log: 2017-07-21 14:06:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:01.683 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:01.683 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:01.683 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:01.683 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:01.683 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:01.683 10094 10157 I jxcore-log: 
,07-21 16:06:01.687 10094 10157 I jxcore-log: 2017-07-21 14:06:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:01.687 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:01.687 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:01.687 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:01.687 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:01.687 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:01.687 10094 10157 I jxcore-log: 
,07-21 16:06:02.821  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:02.821  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:03.313  3675  3790 I PowerManagerService: [PWL] On : 0 (461093 ms ago)
07-21 16:06:03.313  3675  3790 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-21 16:06:05.536  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 210, LCD = 57
,07-21 16:06:05.817  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:06:05.819  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-21 16:06:05.820  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:06:05.820  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:06:05.854  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:05.855  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:07.856  3675  4460 E Watchdog: !@Sync 15 [21_lip_16_06_07.856]
,07-21 16:06:08.889  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:08.890  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:11.723 10094 10157 I jxcore-log: 2017-07-21 14:06:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:11.723 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:11.723 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:11.723 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:11.723 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:11.723 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:11.723 10094 10157 I jxcore-log: 
,07-21 16:06:11.730 10094 10157 I jxcore-log: 2017-07-21 14:06:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:11.730 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:11.730 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:11.730 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:11.730 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:11.730 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:11.730 10094 10157 I jxcore-log: 
,07-21 16:06:11.913  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:11.913  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:06:14.940  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:14.940  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:06:15.561  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 210, LCD = 57
,07-21 16:06:17.973  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:17.973  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-21 16:06:18.850  3675  4941 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:06:18.855  3675  4941 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 241, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-21 16:06:18.855  3675  4941 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-21 16:06:18.855  3675  3675 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-21 16:06:18.873  3675  3675 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,07-21 16:06:18.873  3675  3675 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-21 16:06:18.880  3675  3675 D GameManagerService: new battery level: 100
,07-21 16:06:18.887  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-21 16:06:18.887  4068  4068 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-21 16:06:18.896  4068  4068 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-21 16:06:18.899  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:06:18.900  4068  4068 D BatteryMeterDrawable: isSomethingChanged - false
,07-21 16:06:18.903  4068  4068 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
07-21 16:06:18.915 10217 10217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-21 16:06:18.916 10217 10274 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-21 16:06:19.618  4645  4645 D io_stats: !@   8,0 r 26185 2324176 w 5618 212636 d 776 74344 f 2203 2203 iot 12110 11249 th 473212 0 0 pt 0 inp 0 0 477.397
,07-21 16:06:20.191  3675  3861 D SamsungAlarmManager: Expired : 4
,07-21 16:06:20.195  3675  3861 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170721T163529 - CU:1000/CP:3675
07-21 16:06:20.196  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775322, nowELAPSED=477977
,07-21 16:06:20.196  3675  3861 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170721T160700, SetElapsed=517781, nowELAPSED=477977
,07-21 16:06:20.202  3675  3861 V SamsungAlarmManager: Sending to uid : 10019 action=null alarm=Alarm{fd2bfa0 type 0 when 1500645929742 com.google.android.gms}
,07-21 16:06:20.206  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@b2a37a alarm=Alarm{8de8759 type 2 when 477972 android}
,07-21 16:06:20.209  3675  3925 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-21 16:06:20.212 10493 10493 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-21 16:06:20.213 10493 10493 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-21 16:06:20.226  3675  3954 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170721T160635 - CU:1000/CP:3675
,07-21 16:06:20.227  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T160635, SetElapsed=492995, nowELAPSED=478008
,07-21 16:06:20.229 10493 10493 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-21 16:06:20.316  5251 10782 I EventLogChimeraService: Aggregate from 1500644129654 (log), 1500644129654 (data)
,07-21 16:06:20.541  3675  3720 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170721T163620 - CU:10019/CP:5251
,07-21 16:06:20.995  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:20.995  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:21.770 10094 10157 I jxcore-log: 2017-07-21 14:06:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:21.770 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:21.770 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:21.770 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:21.770 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:21.770 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:21.770 10094 10157 I jxcore-log: 
,07-21 16:06:21.774 10094 10157 I jxcore-log: 2017-07-21 14:06:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:21.774 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:21.774 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:21.774 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:21.774 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:21.774 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:21.774 10094 10157 I jxcore-log: 
,07-21 16:06:22.293  3675  4015 D WifiWatchdogStateMachine:  [|211] []
,07-21 16:06:24.017  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:24.018  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:24.241  3291  3769 D Netd    : Iface wlan0 link up
,07-21 16:06:24.243 10493 10493 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
07-21 16:06:24.244  3675  3784 D Tethering: interfaceLinkStateChanged wlan0, true
07-21 16:06:24.245  3675  3784 D Tethering: interfaceStatusChanged wlan0, true
,07-21 16:06:24.249  3675  3954 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3675 / listener:android.app.AlarmManager$ListenerWrapper@bd2ef1e
,07-21 16:06:24.253  3675  3954 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170721T161117, SetElapsed=775322, nowELAPSED=482034
,07-21 16:06:24.623  4645  4645 D io_stats: !@   8,0 r 26189 2324460 w 5625 212828 d 779 74356 f 2208 2208 iot 12130 11265 th 472548 0 0 pt 0 inp 0 0 482.403
,07-21 16:06:25.573  5251 10784 W PlatformStatsUtil: Could not retrieve Usage & Diagnostics setting. Giving up.
,07-21 16:06:25.586  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 210, LCD = 57
,07-21 16:06:27.048  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:27.049  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:27.618  3292  3292 I bootchecker: bootchecker wake up!!
,07-21 16:06:29.629  4645  4645 D io_stats: !@   8,0 r 26189 2324460 w 5638 212928 d 780 74360 f 2209 2209 iot 12130 11268 th 472492 0 0 pt 0 inp 0 0 487.408
,07-21 16:06:30.081  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:30.082  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:30.660  5251 10784 W PlatformStatsUtil: Could not retrieve Usage & Diagnostics setting. Giving up.
,07-21 16:06:31.814 10094 10157 I jxcore-log: 2017-07-21 14:06:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:31.814 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:31.814 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:31.814 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:31.814 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:31.814 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:31.814 10094 10157 I jxcore-log: 
,07-21 16:06:31.817 10094 10157 I jxcore-log: 2017-07-21 14:06:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:31.817 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:31.817 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:31.817 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:31.817 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:31.817 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:31.817 10094 10157 I jxcore-log: 
,07-21 16:06:33.113  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:33.114  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:34.634  4645  4645 D io_stats: !@   8,0 r 26189 2324460 w 5648 212972 d 780 74360 f 2209 2209 iot 12130 11269 th 472496 0 0 pt 0 inp 0 0 492.414
,07-21 16:06:35.613  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 210, LCD = 57
,07-21 16:06:35.821  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:06:35.822  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-21 16:06:35.824  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:06:35.824  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:06:36.139  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:36.139  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:37.858  3675  4460 E Watchdog: !@Sync 16 [21_lip_16_06_37.857]
,07-21 16:06:39.171  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:39.171  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:41.024  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-21 16:06:41.024  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-21 16:06:41.024  4924  5006 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-21 16:06:41.031  4924  5006 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60031 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-21 16:06:41.851 10094 10157 I jxcore-log: 2017-07-21 14:06:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:41.851 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:41.851 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:41.851 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:41.851 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:41.851 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:41.851 10094 10157 I jxcore-log: 
,07-21 16:06:41.855 10094 10157 I jxcore-log: 2017-07-21 14:06:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:41.855 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:41.855 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:41.855 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:41.855 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:41.855 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:41.855 10094 10157 I jxcore-log: 
,07-21 16:06:42.200  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:42.201  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:44.644  4645  4645 D io_stats: !@   8,0 r 26189 2324460 w 5652 213064 d 781 74364 f 2211 2211 iot 12140 11273 th 472500 0 0 pt 0 inp 0 0 502.424
,07-21 16:06:45.235  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:45.235  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:45.642  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 209, LCD = 57
,07-21 16:06:48.267  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:48.268  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:48.916  3675  3939 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-21 16:06:49.650  4645  4645 D io_stats: !@   8,0 r 26189 2324460 w 5657 213120 d 782 74368 f 2213 2213 iot 12140 11275 th 472440 0 0 pt 0 inp 0 0 507.429
,07-21 16:06:51.298  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:51.299  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:51.888 10094 10157 I jxcore-log: 2017-07-21 14:06:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:51.888 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:51.888 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:51.888 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:51.888 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:51.888 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:51.888 10094 10157 I jxcore-log: 
,07-21 16:06:51.893 10094 10157 I jxcore-log: 2017-07-21 14:06:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:06:51.893 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:06:51.893 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:06:51.893 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:06:51.893 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:06:51.893 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:06:51.893 10094 10157 I jxcore-log: 
,07-21 16:06:54.332  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:54.332  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:06:54.655  4645  4645 D io_stats: !@   8,0 r 26189 2324460 w 5665 213164 d 782 74368 f 2214 2214 iot 12140 11277 th 472424 0 0 pt 0 inp 0 0 512.434
,07-21 16:06:55.667  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 209, LCD = 57
,07-21 16:06:57.355  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:06:57.355  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:07:00.000  3675  3861 D SamsungAlarmManager: Expired : 8
,07-21 16:07:00.001  3675  3861 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{56768e7 type 3 when 517781 android}
,07-21 16:07:00.011  3675  3675 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170721T160800 - CU:1000/CP:3675
07-21 16:07:00.011  3675  3675 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170721T160800, SetElapsed=577781, nowELAPSED=517792
,07-21 16:07:00.016  4068  4068 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-21 16:07:00.017  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#start
,07-21 16:07:00.017  4068  4068 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-21 16:07:00.040  4068  4068 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-21 16:07:00.048  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
07-21 16:07:00.051  4068  4068 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-21 16:07:00.067  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:07:00.068  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:07:00.074  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:07:00.077  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:07:00.087  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
07-21 16:07:00.089  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
07-21 16:07:00.090  4068  4068 V hong    : mid yDiff = 438
07-21 16:07:00.090  4068  4068 V hong    : mid yDiff = 438
,07-21 16:07:00.097  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-21 16:07:00.097  4068  4068 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-21 16:07:00.099  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:07:00.101  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:07:00.121  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-21 16:07:00.122  4068  4068 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-21 16:07:00.136  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-21 16:07:00.139  4068  4068 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-21 16:07:00.143  5421  5421 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-21 16:07:00.145  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-21 16:07:00.148  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-21 16:07:00.153  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-21 16:07:00.154  5421  5421 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
07-21 16:07:00.155  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-21 16:07:00.156  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-21 16:07:00.157  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-21 16:07:00.162  5421  5421 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-21 16:07:00.163  5421  5421 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C2514A0CC6C8F04ED8328A696DC40F869786CFB4F1A0C11AE659A86F9D863832FBE9E330CE8CF94242A39D7DE6B92CAB0]}
,07-21 16:07:00.164  5421  5421 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-21 16:07:00.386  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:07:00.387  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:07:01.923 10094 10157 I jxcore-log: 2017-07-21 14:07:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:07:01.923 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:07:01.923 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:07:01.923 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:07:01.923 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:07:01.923 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:07:01.923 10094 10157 I jxcore-log: 
,07-21 16:07:01.927 10094 10157 I jxcore-log: 2017-07-21 14:07:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-21 16:07:01.927 10094 10157 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-21 16:07:01.927 10094 10157 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-21 16:07:01.927 10094 10157 I jxcore-log: emit@events.js:82:1
07-21 16:07:01.927 10094 10157 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-21 16:07:01.927 10094 10157 I jxcore-log: emit@events.js:82:1''
07-21 16:07:01.927 10094 10157 I jxcore-log: 
,07-21 16:07:03.421  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:07:03.421  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:07:05.693  3675  5817 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 209, LCD = 57
,07-21 16:07:05.825  3675  3675 D UsbMonitorService: readUsbState++
,07-21 16:07:05.827  3675  3675 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-21 16:07:05.828  3675  3675 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-21 16:07:05.828  3675  3675 D UsbMonitorService: Posting Message again
,07-21 16:07:06.447  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:07:06.448  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-21 16:07:07.860  3675  4460 E Watchdog: !@Sync 17 [21_lip_16_07_07.859]
,07-21 16:07:09.481  3675  3925 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-21 16:07:09.481  3675  3925 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39

```
