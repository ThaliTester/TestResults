#### Test 13228325722939a4_thali04_samsung-SM-G930F Logs


```
--------- beginning of main
,07-25 18:25:52.425  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:25:52.425  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
07-25 18:25:52.934  9781  9781 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9781 | app_process
07-25 18:25:52.934  9781  9781 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-25 18:25:52.940  9781  9781 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-25 18:25:52.940  9781  9781 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-25 18:25:52.942  9781  9781 D AndroidRuntime: CheckJNI is OFF
07-25 18:25:52.942  9781  9781 D AndroidRuntime: addProductProperty: start
07-25 18:25:52.981  9781  9781 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-25 18:25:52.981  9781  9781 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-25 18:25:52.996  9781  9781 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-25 18:25:52.996  9781  9781 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-25 18:25:52.996  9781  9781 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-25 18:25:53.040  9781  9781 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-25 18:25:53.057  9781  9781 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-25 18:25:53.079  9781  9781 I Enhanced Zygote ASLR: DISABLED!
07-25 18:25:53.079  9781  9781 I Radio-JNI: register_android_hardware_Radio DONE
07-25 18:25:53.082  9781  9781 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-25 18:25:53.082  9781  9781 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-25 18:25:53.083  9781  9781 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-25 18:25:53.091  9781  9781 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-25 18:25:53.108  3697  3928 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}} from uid 2000 on display 0
07-25 18:25:53.147  3697  3928 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-25 18:25:53.149  3697  3928 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3697  pkgName : AMS_RESUME@CPU_MIN@7
07-25 18:25:53.153  3697  3928 D ActivityManager: mActivityResumeBooster.acquire()
07-25 18:25:53.154  3697  3928 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{3796579d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-25 18:25:53.155  3697  3928 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{3796579d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1}
07-25 18:25:53.155  3697  3928 D InputDispatcher: Focused application set to: xxxx
07-25 18:25:53.156  3697  3928 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{3796579d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} next=ActivityRecord{d405e7dd0 u0 com.thaliproject.thalitest/.MainActivity t5} mFocusedStack=ActivityStack{a6f0b19d0 stackId=1, 2 tasks}
07-25 18:25:53.156  3697  3928 D MountService: getExternalStorageMountMode : 1
07-25 18:25:53.156  3697  3928 D MountService: getExternalStorageMountMode : 3
07-25 18:25:53.156  3697  3928 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10033, packageName : com.thaliproject.thalitest
07-25 18:25:53.160  3697  3830 D WindowManager: addWindow: android.view.ViewRootImpl$W@f9d4ab1 displayId=0
07-25 18:25:53.161  3697  3830 D InputTransport: Input channel constructed: fd=453
07-25 18:25:53.161  3697  3830 D InputTransport: Input channel constructed: fd=454
07-25 18:25:53.162  3697  3830 D ViewRootImpl@ff9958[thalitest]: setView = DecorView@503317[thalitest] touchMode=true
07-25 18:25:53.170  9791  9791 E Zygote  : v2
07-25 18:25:53.170  9791  9791 I libpersona: KNOX_SDCARD checking this for 10033
07-25 18:25:53.170  9791  9791 I libpersona: KNOX_SDCARD not a persona
07-25 18:25:53.171  3697  3928 I ActivityManager: Start proc 9791:com.thaliproject.thalitest/u0a33 for activity com.thaliproject.thalitest/.MainActivity
07-25 18:25:53.174  9791  9791 E Zygote  : accessInfo : 0
07-25 18:25:53.174  9781  9781 D AndroidRuntime: Shutting down VM
07-25 18:25:53.175  3697  3830 V WindowManager: Relayout Window{8a0eb96d0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-25 18:25:53.176  3112  3112 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
07-25 18:25:53.180  9791  9791 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-25 18:25:53.181  9791  9791 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
07-25 18:25:53.201  9781  9781 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-25 18:25:53.201  9781  9781 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-25 18:25:53.201  9781  9781 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-25 18:25:53.201  9781  9781 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
07-25 18:25:53.203  9791  9791 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:25:53.204  9791  9791 D ActivityThread: Added TimaKeyStore provider
07-25 18:25:53.206  3697  4547 I ActivityManager: DSS on for com.thaliproject.thalitest and scale is 1.0
07-25 18:25:53.208  3697  4547 I WindowManager: Failed to capture screenshot of Token{fe6adbf ActivityRecord{4ff87ded0 u0 com.samsung.android.MtpApplication/.USBConnection t4}} appWin=Window{f8ba48ed0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-25 18:25:53.217  3697  4547 D GameManagerService: sem_perfomance_mode: 0
07-25 18:25:53.217  3697  3697 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-25 18:25:53.218  3697  3697 D GameManagerService: unexpected mPrevNotiType: -1
07-25 18:25:53.218  3697  3944 V WindowManager: Relayout Window{f8ba48ed0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-25 18:25:53.223  3697  4837 V WindowManager: Relayout Window{46ed2b8d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-25 18:25:53.227  4904  4904 D Launcher: onTrimMemory. Level: 20
07-25 18:25:53.227  3697  3830 D WindowManager: finishDrawingWindow: Window{8a0eb96d0 u0 Starting com.thaliproject.thalitest} mDrawState=DRAW_PENDING
07-25 18:25:53.227  3697  4547 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-25 18:25:53.227  3697  3830 D ViewRootImpl@ff9958[thalitest]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-25 18:25:53.227  3697  4547 D GameManagerService: sem_perfomance_mode: 0
07-25 18:25:53.229  4762  4776 D ForegroundUtils: could not check pending caller
07-25 18:25:53.229  4762  4776 D ForegroundUtils: could not check pending caller
07-25 18:25:53.230  4762  4776 D ForegroundUtils: could not check pending caller
07-25 18:25:53.231  3697  5674 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-25 18:25:53.231  3697  5674 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-25 18:25:53.236  3697  3830 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.AppWindowToken.destroySurfaces:412 com.android.server.wm.AppWindowToken.destroySurfaces:376 com.android.server.wm.WindowStateAnimator.finishExit:654 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:564 com.android.server.wm.WindowAnimator.updateWindowsLocked:439 
07-25 18:25:53.236  3112  3121 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-25 18:25:53.236  3112  4625 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
07-25 18:25:53.237  3697  4463 E Watchdog: !@Sync 8 [25_lip_18_25_53.237]
07-25 18:25:53.237  3697  3830 D WindowManager: finishDrawingWindow: Window{8a0eb96d0 u0 Starting com.thaliproject.thalitest} mDrawState=HAS_DRAWN
,07-25 18:25:53.243  3697  5674 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-25 18:25:53.244  3697  5674 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-25 18:25:53.250  3697  3928 V WindowManager: Relayout Window{46ed2b8d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-25 18:25:53.253  3697  6550 V WindowManager: Relayout Window{a74d653d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,07-25 18:25:53.265  3697  3948 V WindowManager: Relayout Window{f8ba48ed0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-25 18:25:53.272  9791  9791 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:25:53.297  9791  9791 I CordovaLog: Changing log level to DEBUG(3)
07-25 18:25:53.297  9791  9791 I CordovaActivity: Apache Cordova native platform version 6.1.2 is starting
07-25 18:25:53.297  9791  9791 D CordovaActivity: CordovaActivity.onCreate()
,07-25 18:25:53.311  9791  9791 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm
,07-25 18:25:53.316  9791  9791 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-25 18:25:53.361  3697  3993 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,07-25 18:25:53.369  9791  9791 I cr_LibraryLoader: Time to load native libraries: 16 ms (timestamps 5891-5907)
07-25 18:25:53.369  9791  9791 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-25 18:25:53.393  9791  9791 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-25 18:25:53.400  9791  9791 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-25 18:25:53.420  9791  9791 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-25 18:25:53.560  3697  3917 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10033
,07-25 18:25:53.560  3697  3917 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-25 18:25:53.563  3697  3697 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
07-25 18:25:53.563  3697  3919 I KnoxVpnEngineService: vpn handle : Message received
,07-25 18:25:53.601  9791  9791 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9791
,07-25 18:25:53.603  3697  3944 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9791 for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-25 18:25:53.604  3697  3964 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-25 18:25:53.604  3697  3964 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-25 18:25:53.604  3697  3964 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
,07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:25:53.604  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.605  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-25 18:25:53.655  9791  9791 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-25 18:25:53.664  9791  9791 D PluginManager: init()
,07-25 18:25:53.668  9791  9791 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-25 18:25:53.686  9791  9791 I cr_Ime  : ImeThread is enabled.
,07-25 18:25:53.700  9791  9791 D CordovaActivity: Started the activity.
,07-25 18:25:53.702  9791  9791 D CordovaActivity: Resumed the activity.
,07-25 18:25:53.716  3697  4547 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@133e282 displayId=0
,07-25 18:25:53.717  3697  4547 D InputTransport: Input channel constructed: fd=455
07-25 18:25:53.717  3697  4547 D InputTransport: Input channel constructed: fd=457
,07-25 18:25:53.718  3697  4547 D InputTransport: Input channel destroyed: fd=457
,07-25 18:25:53.719  9791  9791 D InputTransport: Input channel constructed: fd=98
07-25 18:25:53.719  9791  9791 D ViewRootImpl@7507e3f[MainActivity]: setView = DecorView@777230c[MainActivity] touchMode=true
,07-25 18:25:53.720  3697  3957 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-25 18:25:53.720  3697  3957 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-25 18:25:53.720  3697  3697 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,07-25 18:25:53.721  9791  9791 D CordovaActivity: Paused the activity.
,07-25 18:25:53.721  3697  3697 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-25 18:25:53.724  3697  3811 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-25 18:25:53.732  9791  9791 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9791
,07-25 18:25:53.733  3697  4837 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9791 for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-25 18:25:53.733  3697  3964 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-25 18:25:53.734  3697  3964 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:25:53.734  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-25 18:25:53.746  3697  4829 V WindowManager: Relayout Window{2aa31d0d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-25 18:25:53.746  3112  3112 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
,07-25 18:25:53.756  9791  9839 I OpenGLRenderer: Initialized EGL, version 1.4
07-25 18:25:53.756  9791  9839 D OpenGLRenderer: Swap behavior 1
,07-25 18:25:53.760  9791  9839 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-25 18:25:53.762  9791  9839 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
,07-25 18:25:53.764  9791  9791 D CordovaActivity: Stopped the activity.
,07-25 18:25:53.768  3697  3830 V WindowManager: Now policy hidden: Window{2aa31d0d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}
,07-25 18:25:53.789  9791  9844 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-25 18:25:53.805  9791  9844 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-25 18:25:53.805  9791  9844 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-25 18:25:53.807  9791  9844 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-25 18:25:53.808  9791  9844 W AudioCapabilities: Unsupported mime audio/x-ima
,07-25 18:25:53.809  9791  9844 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-25 18:25:53.809  9791  9844 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-25 18:25:53.809  9791  9844 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.812  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.814  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.820  3697  4945 D WindowManager: finishDrawingWindow: Window{2aa31d0d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=DRAW_PENDING
07-25 18:25:53.821  9791  9791 D ViewRootImpl@7507e3f[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-25 18:25:53.825  9791  9844 W VideoCapabilities: Unsupported mime video/wvc1
07-25 18:25:53.827  3697  3830 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-25 18:25:53.827  3697  3697 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-25 18:25:53.827  9791  9844 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-25 18:25:53.828  3697  3697 I KnoxTimeoutHandler: SD activityfalse
07-25 18:25:53.828  3697  3697 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
07-25 18:25:53.829  3697  3830 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +602ms (total +673ms)
07-25 18:25:53.830  3697  3811 D ActivityManager: mActivityResumeBoosterTail.acquire()
07-25 18:25:53.831  3697  3830 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3697  tag : AMS_RESUME@CPU_MIN@7
07-25 18:25:53.832  3697  3830 D ActivityManager: mActivityResumeBooster.release()
07-25 18:25:53.832  3697  3830 D ViewRootImpl@ff9958[thalitest]: dispatchDetachedFromWindow
07-25 18:25:53.832  3697  3830 I WindowManager: Destroying surface Surface(name=Starting com.thaliproject.thalitest) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
07-25 18:25:53.833  3112  4625 I SurfaceFlinger: id=15 Removed uhalitest (3/5)
07-25 18:25:53.834  3697  3811 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3697  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
07-25 18:25:53.834  3112  3121 I SurfaceFlinger: id=15 Removed uhalitest (-2/5)
07-25 18:25:53.835  9791  9844 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-25 18:25:53.835  9791  9844 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-25 18:25:53.835  9791  9844 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-25 18:25:53.837  9791  9844 W VideoCapabilities: Unsupported mime video/wvc1
07-25 18:25:53.838  9791  9844 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-25 18:25:53.840  9791  9844 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
07-25 18:25:53.842  9791  9844 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
07-25 18:25:53.842  3697  3830 D InputTransport: Input channel destroyed: fd=453
07-25 18:25:53.842  3697  3830 D InputTransport: Input channel destroyed: fd=454
07-25 18:25:53.842  3697  4838 D WindowManager: finishDrawingWindow: Window{2aa31d0d0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=HAS_DRAWN
,07-25 18:25:53.843  9791  9791 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
07-25 18:25:53.844  9791  9844 W VideoCapabilities: Unsupported mime video/mp43
,07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-25 18:25:53.848  9791  9844 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-25 18:25:53.851  9791  9844 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
,07-25 18:25:53.851  9791  9844 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-25 18:25:53.851  9791  9844 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-25 18:25:53.867  9791  9844 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-25 18:25:53.879  9791  9844 W VideoCapabilities: Unsupported mime video/sorenson
,07-25 18:25:53.895  9791  9844 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-25 18:25:53.924  9791  9791 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9791
,07-25 18:25:54.020  9791  9791 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-25 18:25:54.083  9791  9791 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-25 18:25:54.121  9791  9852 D jxcore_app_log: JniHelper::setJavaVM(0xe6f34000), pthread_self() = -1064830688
,07-25 18:25:54.125  9791  9852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-25 18:25:54.125  9791  9852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-25 18:25:54.125  9791  9852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-25 18:25:54.125  9791  9852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-25 18:25:54.125  9791  9852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-25 18:25:54.125  9791  9852 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@126070e added. We now have 1 listener(s)
,07-25 18:25:54.125  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@126070e added. We now have 1 listener(s)
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-25 18:25:54.126  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-25 18:25:54.130  9791  9852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
07-25 18:25:54.131  9791  9852 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
,07-25 18:25:54.132  9791  9852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:25:54.132  9791  9852 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,07-25 18:25:54.133  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:25:54.133  9791  9852 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5eb6cc5 added. We now have 2 listener(s)
,07-25 18:25:54.133  9791  9852 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-25 18:25:54.134  3697  3697 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3697  tag : AMS_RESUME_TAIL@CPU_MIN@13
,07-25 18:25:54.140  9791  9852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-25 18:25:54.140  9791  9852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 40909
,07-25 18:25:54.140  9791  9852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 120
,07-25 18:25:54.140  9791  9852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-25 18:25:54.140  9791  9852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-25 18:25:54.140  9791  9852 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
07-25 18:25:54.140  9791  9852 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 120
,07-25 18:25:54.146  9791  9852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:25:54.146  9791  9852 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,07-25 18:25:54.157  9791  9852 D BluetoothAdapter: STATE_ON
,07-25 18:25:54.160  9791  9852 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:25:54.160  9791  9852 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:25:54.160  9791  9852 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-25 18:25:54.160  9791  9852 D io.jxcore.node.ConnectivityMonitor: start: OK
07-25 18:25:54.160  9791  9852 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-25 18:25:54.167  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:25:54.173  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:25:54.179  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:25:54.183  9791  9791 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,07-25 18:25:54.184  9791  9791 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,07-25 18:25:54.595  4645  4645 D io_stats: !@   8,0 r 25049 2252376 w 4670 201192 d 628 73800 f 1913 1913 iot 11220 10463 th 477992 0 0 pt 0 inp 0 0 257.132
,07-25 18:25:54.907  9791  9855 W jxcore-log: Initializing JXcore engine
07-25 18:25:54.908  9791  9855 W jxcore-log: JXcore engine is ready
,07-25 18:25:54.926  3238  3238 E audit   : type=1400 audit(1500999954.911:536): avc:  denied  { ioctl } for  pid=9855 comm="Thread-9" path="socket:[63442]" dev="sockfs" ino=63442 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0 SEPF_SECMOBILE_7.0_0006
07-25 18:25:54.926  3697  3826 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / /system/bin/sh /system/bin/install-recovery.sh
,07-25 18:25:54.927  3238  3238 E audit   : type=1300 audit(1500999954.911:536): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3 a1=5451 a2=441c3c5d a3=22 items=0 ppid=3280 pid=9855 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-25 18:25:54.927  3697  3826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-25 18:25:54.928  3238  3238 E audit   : type=1327 audit(1500999954.911:536): proctitle="com.thaliproject.thalitest"
07-25 18:25:54.928  3238  3238 E audit   : type=1320 audit(1500999954.911:536): 
,07-25 18:25:54.929  3238  3238 E audit   : type=1400 audit(1500999954.911:537): avc:  denied  { ioctl } for  pid=9855 comm="Thread-9" path="/dev/pmsg0" dev="tmpfs" ino=12717 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0 SEPF_SECMOBILE_7.0_0006
07-25 18:25:54.929  3697  3826 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-25 18:25:54.929  3238  3238 E audit   : type=1300 audit(1500999954.911:537): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=4 a1=5451 a2=441c3c5d a3=22 items=0 ppid=3280 pid=9855 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-25 18:25:54.930  3238  3238 E audit   : type=1327 audit(1500999954.911:537): proctitle="com.thaliproject.thalitest"
07-25 18:25:54.930  3697  3826 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / "com.thaliproject.thalitest"
07-25 18:25:54.930  3238  3238 E audit   : type=1320 audit(1500999954.911:537): 
07-25 18:25:54.930  3238  3238 E audit   : type=1400 audit(1500999954.911:538): avc:  denied  { ioctl } for  pid=9855 comm="Thread-9" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1328 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs_trace_marker:s0 tclass=file permissive=0 SEPF_SECMOBILE_7.0_0006
07-25 18:25:54.930  3697  3826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-25 18:25:54.930  3697  3811 D MountService: getExternalStorageMountMode : 1
07-25 18:25:54.930  3697  3811 D MountService: getExternalStorageMountMode : 3
07-25 18:25:54.930  3697  3811 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.securitylogagent
07-25 18:25:54.930  3238  3238 E audit   : type=1300 audit(1500999954.911:538): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=5 a1=5451 a2=441c3c5d a3=22 items=0 ppid=3280 pid=9855 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-25 18:25:54.932  3238  3238 E audit   : type=1327 audit(1500999954.911:538): proctitle="com.thaliproject.thalitest"
07-25 18:25:54.932  3238  3238 E audit   : type=1320 audit(1500999954.911:538): 
07-25 18:25:54.932  3238  3238 E audit   : type=1400 audit(1500999954.911:539): avc:  denied  { ioctl } for  pid=9855 comm="Thread-9" path="socket:[60894]" dev="sockfs" ino=60894 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0 SEPF_SECMOBILE_7.0_0006
07-25 18:25:54.932  3238  3238 E audit   : type=1300 audit(1500999954.911:539): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=54 a1=5451 a2=441c3c5d a3=22 items=0 ppid=3280 pid=9855 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-25 18:25:54.933  9791  9855 W jxcore-log: Starting JXcore engine
07-25 18:25:54.933  3238  3238 E audit   : type=1327 audit(1500999954.911:539): proctitle="com.thaliproject.thalitest"
07-25 18:25:54.933  3238  3238 E audit   : type=1320 audit(1500999954.911:539): 
,07-25 18:25:54.948  9857  9857 E Zygote  : v2
07-25 18:25:54.948  9857  9857 I libpersona: KNOX_SDCARD checking this for 1000
07-25 18:25:54.948  9857  9857 I libpersona: KNOX_SDCARD not a persona
07-25 18:25:54.949  9857  9857 E Zygote  : accessInfo : 0
07-25 18:25:54.949  3697  3811 I ActivityManager: Start proc 9857:com.samsung.android.securitylogagent/1000 for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,07-25 18:25:54.951  3697  3826 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-25 18:25:54.952  9857  9857 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:25:54.953  9857  9857 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.securitylogagent 
,07-25 18:25:54.967  9857  9857 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:25:54.967  9857  9857 D ActivityThread: Added TimaKeyStore provider
,07-25 18:25:54.969  3697  6617 I ActivityManager: DSS on for com.samsung.android.securitylogagent and scale is 1.0
,07-25 18:25:54.970  9791  9855 W jxcore-log: Platform android
07-25 18:25:54.970  9791  9855 W jxcore-log: 
07-25 18:25:54.970  9791  9855 W jxcore-log: Process ARCH arm
07-25 18:25:54.970  9791  9855 W jxcore-log: 
,07-25 18:25:54.983  9857  9857 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,07-25 18:25:54.992  9857  9857 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:25:54.995  9857  9857 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-25 18:25:55.000  9857  9857 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-25 18:25:55.006  3697  4547 I ActivityManager: KPU : put [com.google.android.gm] : 32572 K
,07-25 18:25:55.006  3697  4547 I ActivityManager: Killing 8772:com.google.android.gm/u0a108 (adj 906): DHA:empty #33
,07-25 18:25:55.029  3697  3776 D ActivityManager: cleanUpApplicationRecord -- 8772
,07-25 18:25:55.033  4762  4776 D ForegroundUtils: could not check pending caller
,07-25 18:25:55.098  9791  9855 I jxcore-log: JXcore Cordova bridge is ready!
07-25 18:25:55.098  9791  9855 I jxcore-log: 
07-25 18:25:55.098  9791  9855 W jxcore-log: JXcore engine is started
,07-25 18:25:55.112  9791  9852 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-25 18:25:55.119  9791  9791 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
07-25 18:25:55.120  9791  9791 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-25 18:25:55.445  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:25:55.445  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:25:55.973  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-25 18:25:55.973  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-25 18:25:55.973  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-25 18:25:55.978  4885  4951 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 4ms lastUpdatedAfter : 60108 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-25 18:25:56.062  3298  3786 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-25 18:25:58.469  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:25:58.469  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:25:59.232  3697  5674 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-25 18:25:59.599  4645  4645 D io_stats: !@   8,0 r 25051 2252384 w 4724 201620 d 631 73812 f 1916 1916 iot 11220 10473 th 471236 0 0 pt 0 inp 0 0 262.136
,07-25 18:25:59.759  3697  5674 D SSRM:f  : SIOP:: AP = 340, PST = 279 (W:6), CP = 240, CUR = -122, LCD = 57
,07-25 18:26:00.000  3697  3866 D SamsungAlarmManager: Expired : 8
,07-25 18:26:00.001  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{b37503d type 3 when 262539 android}
,07-25 18:26:00.005  3697  3697 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170725T182700 - CU:1000/CP:3697
,07-25 18:26:00.008  4074  4074 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-25 18:26:00.009  4074  4074 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-25 18:26:00.009  4074  4074 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-25 18:26:00.023  4074  4074 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-25 18:26:00.023  4074  4074 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-25 18:26:00.024  4074  4074 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-25 18:26:00.037  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:26:00.038  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
07-25 18:26:00.040  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
07-25 18:26:00.041  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:26:00.053  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:26:00.055  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:26:00.056  4074  4074 V hong    : mid yDiff = 438
07-25 18:26:00.056  4074  4074 V hong    : mid yDiff = 438
07-25 18:26:00.057  4074  4074 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-25 18:26:00.057  4074  4074 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-25 18:26:00.061  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:26:00.063  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:26:00.069  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:26:00.070  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:26:00.085  4074  4074 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-25 18:26:00.088  4074  4074 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-25 18:26:00.092  5069  5069 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-25 18:26:00.093  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-25 18:26:00.096  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-25 18:26:00.100  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-25 18:26:00.101  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-25 18:26:00.105  5069  5069 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-25 18:26:00.106  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-25 18:26:00.107  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-25 18:26:00.111  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-25 18:26:00.112  5069  5069 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C3CC40EFB9853E5512D58DCA498126DE9B4B92A09A0D4E7D36D3FE10E5B2AF182843F90170F70E1C63E1F2FCF943DC0A5]}
,07-25 18:26:00.113  5069  5069 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-25 18:26:00.307  3298  3786 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-25 18:26:01.494  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:01.494  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:26:02.215  9791  9855 I jxcore-log: 2017-07-25 16:26:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
07-25 18:26:02.215  9791  9855 I jxcore-log: 
,07-25 18:26:02.216  9791  9855 I jxcore-log: 2017-07-25 16:26:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
07-25 18:26:02.216  9791  9855 I jxcore-log: 
07-25 18:26:02.216  9791  9855 I jxcore-log: 2017-07-25 16:26:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
07-25 18:26:02.216  9791  9855 I jxcore-log: 
,07-25 18:26:02.226  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:02.230  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:26:02.233  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:02.238  9791  9855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-25 18:26:02.239  9791  9855 I jxcore-log: 2017-07-25 16:26:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
07-25 18:26:02.239  9791  9855 I jxcore-log: 
07-25 18:26:02.240  9791  9855 I jxcore-log: 2017-07-25 16:26:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
07-25 18:26:02.240  9791  9855 I jxcore-log: 
,07-25 18:26:02.240  9791  9855 I jxcore-log: 2017-07-25 16:26:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
07-25 18:26:02.240  9791  9855 I jxcore-log: 
,07-25 18:26:02.507  9791  9855 D ExecuteNativeTests: Running unit tests
07-25 18:26:02.507  9791  9855 D BluetoothAdapter: enable()
,07-25 18:26:02.513  4061  4954 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-25 18:26:02.514  4061  4954 D AdapterProvider: query
,07-25 18:26:02.530  4061  4954 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@725d52a
,07-25 18:26:02.533  4061  4954 D BluetoothAdapterService: updateEvent - already set, update
07-25 18:26:02.534  4061  4954 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-25 18:26:02.534  4061  4954 D AdapterProvider: update
,07-25 18:26:02.543  4061  4954 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:02.547  9791  9855 D BluetoothAdapter: enable(): BT is already enabled..!
,07-25 18:26:02.559  3697  3948 D WifiService: setWifiEnabled: true pid=9791, uid=10033
07-25 18:26:02.560  3697  3948 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-25 18:26:02.562  3697  3948 D WifiControlHistoryProvider: query
,07-25 18:26:02.595  3697  3948 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:26:02.596  3697  3948 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:02.597  3697  3948 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:02.602  3697  3948 I WifiService: Wi-Fi Sharing settings has not been accessed
07-25 18:26:02.603  3697  3948 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-25 18:26:03.209  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-25 18:26:03.235  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-25 18:26:03.235  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-25 18:26:03.725  3697  4547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:26:04.530  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:04.530  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:26:04.604  4645  4645 D io_stats: !@   8,0 r 25061 2252740 w 4733 201828 d 631 73812 f 1920 1920 iot 11250 10483 th 470872 0 0 pt 0 inp 0 0 267.141
,07-25 18:26:07.558  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:07.559  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:26:09.609  4645  4645 D io_stats: !@   8,0 r 25061 2252740 w 4744 201936 d 632 73884 f 1922 1922 iot 11250 10486 th 470876 0 0 pt 0 inp 0 0 272.147
,07-25 18:26:09.789  3697  5674 D SSRM:f  : SIOP:: AP = 310, PST = 288 (W:14), CP = 250, CUR = -83, LCD = 57
,07-25 18:26:10.593  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:10.593  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:26:12.609  9791  9855 I com.test.thalitest.ThaliTestRunner: Running UT
,07-25 18:26:12.746  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-25 18:26:12.746  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf00b87 added. We now have 2 listener(s)
07-25 18:26:12.746  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf00b87 added. We now have 3 listener(s)
07-25 18:26:12.746  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-25 18:26:12.747  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
07-25 18:26:12.747  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:26:12.747  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
07-25 18:26:12.747  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:26:12.747  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7223ab4 added. We now have 4 listener(s)
07-25 18:26:12.748  9791  9855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-25 18:26:12.749  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-25 18:26:12.758  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.765  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
07-25 18:26:12.765  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-25 18:26:12.766  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-25 18:26:12.766  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-25 18:26:12.766  9791  9855 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
07-25 18:26:12.766  9791  9855 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-25 18:26:12.766  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-25 18:26:12.767  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-25 18:26:12.767  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-25 18:26:12.767  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
07-25 18:26:12.768  9791  9855 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-25 18:26:12.769  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
07-25 18:26:12.772  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
07-25 18:26:12.772  9791  9855 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,07-25 18:26:12.776  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:26:12.792  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:12.798  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:26:12.798  9791  9855 D io.jxcore.node.ConnectivityMonitor: start: OK
07-25 18:26:12.798  9791  9855 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
07-25 18:26:12.798  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
07-25 18:26:12.798  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-25 18:26:12.800  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:12.800  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:12.800  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:12.800  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-25 18:26:12.801  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:12.801  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:12.802  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:12.802  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:26:12.802  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:26:12.802  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:26:12.802  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:26:12.804  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-25 18:26:12.805  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-25 18:26:12.805  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:26:12.805  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:26:12.806  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:26:12.806  9791  9876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:26:12.806  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-25 18:26:12.806  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:26:12.806  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-25 18:26:12.813  9791  9876 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:12.813  9791  9876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-25 18:26:12.822  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:12.829  9791  9876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:26:12.831  9791  9876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@f37d923, port: 6, type: 1, local socket address: null, socket type: 0
,07-25 18:26:12.832  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:12.835  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-25 18:26:12.835  9791  9855 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:26:12.835  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-25 18:26:12.838  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:12.839  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-25 18:26:12.841  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.842  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.843  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.846  9791  9855 D BluetoothAdapter: isSecureModeEnabled
,07-25 18:26:12.846  4061  4954 D BtConfig.SecureMode: isSecureModeOn:false
,07-25 18:26:12.848  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:12.848  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-25 18:26:12.850  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.852  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:12.852  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:26:12.853  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:26:12.853  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,07-25 18:26:12.856  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.860  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:12.860  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:12.860  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:26:12.860  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-25 18:26:12.861  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-25 18:26:12.862  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
,07-25 18:26:12.864  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:12.864  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:12.865  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:12.865  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:12.865  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:26:12.865  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:12.866  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:12.866  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:12.866  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:12.868  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.869  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:12.869  9791  9855 D BluetoothAdapter: isSecureModeEnabled
,07-25 18:26:12.870  4061  4717 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:12.870  9791  9855 D BluetoothLeAdvertiser: start advertising
,07-25 18:26:12.872  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:12.882  4061  4072 D BtGatt.GattService: registerClient() - UUID=5374166b-d2d6-4291-924a-22b11b17779b
,07-25 18:26:12.986  4061  4180 D BtGatt.GattService: onClientRegistered() - UUID=5374166b-d2d6-4291-924a-22b11b17779b, clientIf=5, status=0
,07-25 18:26:12.988  9791  9802 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-25 18:26:12.992  4061  4717 E BtGatt.ContextMap: Context not found for ID 5
,07-25 18:26:12.994  4061  4586 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-25 18:26:12.995  4061  4572 D BtGatt.AdvertiseManager: message : 0
,07-25 18:26:12.997  4061  4572 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:26:12.997  4061  4572 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:26:13.007  4061  4572 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:26:13.013  4061  4572 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:26:13.017  4061  4655 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-25 18:26:13.036  4061  4180 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-25 18:26:13.040  4061  4572 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:26:13.052  4061  4180 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-25 18:26:13.053  4061  4572 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:26:13.053  4061  4572 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-25 18:26:13.053  4061  4572 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-25 18:26:13.054  4061  4572 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-25 18:26:13.055  9791  9803 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-25 18:26:13.058  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.059  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.059  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-25 18:26:13.062  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.064  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.065  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.066  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.067  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.068  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-25 18:26:13.073  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-25 18:26:13.074  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.081  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.082  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.083  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.085  9791  9855 I io.jxcore.node.ConnectionHelper: start: OK
,07-25 18:26:13.085  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-25 18:26:13.087  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.088  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:13.088  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-25 18:26:13.088  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.089  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.090  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-25 18:26:13.091  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.092  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:26:13.092  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-25 18:26:13.092  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.093  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.094  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.095  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.096  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.101  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.102  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:26:13.102  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.103  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.104  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:26:13.588  9791  9878 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-25 18:26:13.591  9791  9855 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-25 18:26:13.592  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
07-25 18:26:13.592  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-25 18:26:13.592  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,07-25 18:26:13.592  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-25 18:26:13.593  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
07-25 18:26:13.593  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-25 18:26:13.593  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
,07-25 18:26:13.593  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
07-25 18:26:13.594  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-25 18:26:13.594  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-25 18:26:13.594  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-25 18:26:13.594  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,07-25 18:26:13.594  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
,07-25 18:26:13.595  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-25 18:26:13.595  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
,07-25 18:26:13.595  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-25 18:26:13.595  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-25 18:26:13.595  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-25 18:26:13.596  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-25 18:26:13.596  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-25 18:26:13.596  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-25 18:26:13.596  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-25 18:26:13.596  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-25 18:26:13.597  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
,07-25 18:26:13.597  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-25 18:26:13.597  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-25 18:26:13.597  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-25 18:26:13.597  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-25 18:26:13.598  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-25 18:26:13.598  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-25 18:26:13.598  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-25 18:26:13.598  9791  9855 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-25 18:26:13.599  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-25 18:26:13.599  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-25 18:26:13.599  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:26:13.599  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:26:13.599  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:26:13.600  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-25 18:26:13.601  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:26:13.601  9791  9876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,07-25 18:26:13.601  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:26:13.601  9791  9876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:26:13.601  9791  9876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:26:13.601  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-25 18:26:13.601  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:26:13.602  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,07-25 18:26:13.603  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.603  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:26:13.603  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:26:13.608  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.609  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.610  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.612  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.615  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.619  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.620  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-25 18:26:13.623  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:13.623  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
07-25 18:26:13.624  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.626  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:13.626  9791  9855 D BluetoothLeScanner: could not find callback wrapper
07-25 18:26:13.626  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:26:13.627  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.628  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.628  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.628  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-25 18:26:13.629  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.634  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.636  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:13.636  9791  9855 D BluetoothLeAdvertiser: stop advertising
,07-25 18:26:13.638  4061  4072 E BtGatt.ContextMap: Context not found for ID 5
,07-25 18:26:13.638  4061  4572 D BtGatt.AdvertiseManager: message : 1
07-25 18:26:13.639  4061  4586 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:26:13.640  4061  4572 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-25 18:26:13.640  4061  4572 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-25 18:26:13.645  4061  4572 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:26:13.653  4061  4180 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-25 18:26:13.654  4061  4180 D BtGatt.GattService: Client app is not null!
,07-25 18:26:13.654  9791  9802 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-25 18:26:13.656  4061  4717 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-25 18:26:13.658  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:26:13.658  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.659  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-25 18:26:13.659  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.660  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.661  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.661  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-25 18:26:13.662  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-25 18:26:13.663  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-25 18:26:13.664  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.667  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.667  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:26:13.668  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.668  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.669  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-25 18:26:13.669  9791  9791 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-25 18:26:13.670  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:26:13.670  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:26:13.670  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-25 18:26:13.671  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:13.671  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-25 18:26:13.672  9791  9879 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-25 18:26:13.672  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:13.672  9791  9855 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-25 18:26:13.672  9791  9855 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-25 18:26:13.672  9791  9855 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
07-25 18:26:13.672  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.672  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
07-25 18:26:13.673  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:26:13.673  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:26:13.673  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-25 18:26:13.673  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.674  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.674  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.675  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:26:13.677  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:13.677  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:13.678  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.678  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:26:13.682  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:13.682  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:13.682  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.683  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:26:13.683  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:26:13.683  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:26:13.683  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:26:13.685  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-25 18:26:13.685  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-25 18:26:13.685  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:26:13.686  9791  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:26:13.686  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:26:13.686  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:26:13.686  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-25 18:26:13.686  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-25 18:26:13.686  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:26:13.686  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-25 18:26:13.689  9791  9880 D BluetoothSocket: bindListen(): myUserId = 0
,07-25 18:26:13.689  9791  9880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:26:13.693  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-25 18:26:13.694  9791  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:26:13.694  9791  9855 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:26:13.694  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-25 18:26:13.694  9791  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@30e2c4c, port: 6, type: 1, local socket address: null, socket type: 0
,07-25 18:26:13.697  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.698  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.699  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.702  9791  9855 D BluetoothAdapter: isSecureModeEnabled
07-25 18:26:13.703  4061  4717 D BtConfig.SecureMode: isSecureModeOn:false
,07-25 18:26:13.703  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.704  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-25 18:26:13.705  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.706  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.707  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:26:13.707  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:26:13.707  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,07-25 18:26:13.709  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.713  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.713  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.713  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:26:13.713  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-25 18:26:13.714  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-25 18:26:13.714  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
07-25 18:26:13.714  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-25 18:26:13.715  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:13.715  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.716  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.716  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:26:13.717  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-25 18:26:13.717  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.718  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.719  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.720  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.722  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:13.722  9791  9855 D BluetoothAdapter: isSecureModeEnabled
,07-25 18:26:13.722  4061  4953 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:13.723  9791  9855 D BluetoothLeAdvertiser: start advertising
,07-25 18:26:13.724  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:13.729  4061  4072 D BtGatt.GattService: registerClient() - UUID=c1da7ad3-50e3-4ec1-8d9e-991cd4d6b633
,07-25 18:26:13.832  4061  4180 D BtGatt.GattService: onClientRegistered() - UUID=c1da7ad3-50e3-4ec1-8d9e-991cd4d6b633, clientIf=5, status=0
,07-25 18:26:13.833  9791  9802 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-25 18:26:13.837  4061  4953 E BtGatt.ContextMap: Context not found for ID 5
07-25 18:26:13.838  4061  4586 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-25 18:26:13.838  4061  4572 D BtGatt.AdvertiseManager: message : 0
07-25 18:26:13.839  4061  4572 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:26:13.839  4061  4572 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:26:13.857  4061  4572 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:26:13.864  4061  4572 D BtGatt.AdvertiseManager: isStandardAdv = false
07-25 18:26:13.866  4061  4655 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-25 18:26:13.878  4061  4180 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-25 18:26:13.880  4061  4572 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:26:13.887  4061  4180 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-25 18:26:13.887  4061  4572 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:26:13.887  4061  4572 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-25 18:26:13.887  4061  4572 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-25 18:26:13.887  4061  4572 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-25 18:26:13.888  9791  9803 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-25 18:26:13.889  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.890  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.890  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-25 18:26:13.890  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.891  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.892  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.892  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:13.893  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.893  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-25 18:26:13.896  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-25 18:26:13.897  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.897  9791  9855 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-25 18:26:13.901  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.901  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.902  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:13.902  9791  9855 I io.jxcore.node.ConnectionHelper: start: OK
07-25 18:26:13.903  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-25 18:26:13.904  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.904  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:13.904  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:26:13.905  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.906  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.906  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:13.907  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.907  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:26:13.907  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:26:13.907  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.911  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.912  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.913  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.913  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.918  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.918  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
07-25 18:26:13.919  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-25 18:26:13.919  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:13.920  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:26:14.409  9791  9882 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-25 18:26:14.413  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,07-25 18:26:14.414  9791  9855 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,07-25 18:26:14.415  9791  9855 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-25 18:26:14.415  9791  9855 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-25 18:26:14.415  9791  9855 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
07-25 18:26:14.415  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
07-25 18:26:14.416  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-25 18:26:14.422  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-25 18:26:14.428  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:14.429  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:14.430  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.430  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:26:14.437  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:14.438  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:14.439  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 40909
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-25 18:26:14.440  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.441  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,07-25 18:26:14.443  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.444  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.445  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.447  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.449  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:14.449  9791  9855 D BluetoothLeAdvertiser: stop advertising
,07-25 18:26:14.451  4061  4953 E BtGatt.ContextMap: Context not found for ID 5
07-25 18:26:14.452  4061  4586 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,07-25 18:26:14.452  4061  4572 D BtGatt.AdvertiseManager: message : 1
07-25 18:26:14.454  4061  4572 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-25 18:26:14.454  4061  4572 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-25 18:26:14.456  4061  4572 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:26:14.463  4061  4180 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-25 18:26:14.463  4061  4180 D BtGatt.GattService: Client app is not null!
,07-25 18:26:14.463  9791  9803 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-25 18:26:14.465  4061  4717 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-25 18:26:14.467  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:26:14.467  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.467  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-25 18:26:14.468  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.469  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.469  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.470  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-25 18:26:14.470  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.471  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.471  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.472  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:26:14.472  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-25 18:26:14.472  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-25 18:26:14.472  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
07-25 18:26:14.473  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:14.473  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:14.474  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.475  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.475  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,07-25 18:26:14.475  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:14.476  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.476  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.477  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.479  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.481  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:14.481  9791  9855 D BluetoothAdapter: isSecureModeEnabled
,07-25 18:26:14.482  4061  4072 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:14.482  9791  9855 D BluetoothLeAdvertiser: start advertising
,07-25 18:26:14.484  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.490  4061  4073 D BtGatt.GattService: registerClient() - UUID=98de5ffd-7417-4fe6-8c3a-8f2b655bbcfe
,07-25 18:26:14.593  4061  4180 D BtGatt.GattService: onClientRegistered() - UUID=98de5ffd-7417-4fe6-8c3a-8f2b655bbcfe, clientIf=5, status=0
,07-25 18:26:14.594  9791  9802 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-25 18:26:14.599  4061  4072 E BtGatt.ContextMap: Context not found for ID 5
07-25 18:26:14.599  4061  4572 D BtGatt.AdvertiseManager: message : 0
07-25 18:26:14.600  4061  4586 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-25 18:26:14.601  4061  4572 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:26:14.602  4061  4572 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:26:14.610  4061  4572 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:26:14.614  4645  4645 D io_stats: !@   8,0 r 25073 2253552 w 4777 202456 d 641 73920 f 1931 1931 iot 11290 10507 th 472192 0 0 pt 0 inp 0 0 277.152
07-25 18:26:14.615  4061  4572 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:26:14.619  4061  4655 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-25 18:26:14.642  4061  4180 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-25 18:26:14.646  4061  4572 D BtGatt.AdvertiseManager: starting multi advertising
07-25 18:26:14.661  4061  4180 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-25 18:26:14.661  4061  4572 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:26:14.662  4061  4572 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-25 18:26:14.662  4061  4572 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-25 18:26:14.662  4061  4572 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-25 18:26:14.663  9791  9803 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
07-25 18:26:14.664  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.665  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.665  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-25 18:26:14.666  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.667  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.667  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.668  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.669  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.670  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.670  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:26:14.671  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.671  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:26:14.672  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-25 18:26:14.672  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-25 18:26:14.673  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.674  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:14.674  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:26:14.675  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.676  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.677  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:14.678  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.678  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:26:14.678  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:26:14.679  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.680  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.680  9791  9855 I io.jxcore.node.ConnectionHelper: start: OK
07-25 18:26:14.682  9791  9884 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-25 18:26:14.683  9791  9855 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-25 18:26:14.683  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-25 18:26:14.684  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-25 18:26:14.684  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:26:14.684  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:26:14.684  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:26:14.684  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-25 18:26:14.684  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:26:14.684  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:26:14.685  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-25 18:26:14.685  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:26:14.685  9791  9880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:26:14.685  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-25 18:26:14.685  9791  9880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:26:14.685  9791  9880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:26:14.685  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.686  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:26:14.686  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:26:14.686  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.687  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.687  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.688  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.690  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.692  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:14.692  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-25 18:26:14.694  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.696  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:14.696  9791  9855 D BluetoothLeScanner: could not find callback wrapper
07-25 18:26:14.696  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-25 18:26:14.696  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.697  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.698  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.698  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,07-25 18:26:14.698  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.700  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.702  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:14.702  9791  9855 D BluetoothLeAdvertiser: stop advertising
07-25 18:26:14.703  4061  4717 E BtGatt.ContextMap: Context not found for ID 5
07-25 18:26:14.704  4061  4572 D BtGatt.AdvertiseManager: message : 1
07-25 18:26:14.704  4061  4586 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:26:14.705  4061  4572 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-25 18:26:14.705  4061  4572 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-25 18:26:14.707  4061  4572 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:26:14.713  4061  4180 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-25 18:26:14.713  4061  4180 D BtGatt.GattService: Client app is not null!
,07-25 18:26:14.714  9791  9802 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-25 18:26:14.715  4061  4954 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-25 18:26:14.717  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:26:14.718  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.718  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-25 18:26:14.719  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.719  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.720  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.720  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-25 18:26:14.720  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-25 18:26:14.722  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-25 18:26:14.723  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.726  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.726  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:26:14.726  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.727  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.728  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-25 18:26:14.728  9791  9791 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-25 18:26:14.728  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,07-25 18:26:14.728  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:26:14.729  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:14.729  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:14.730  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:14.730  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.730  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:26:14.730  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:26:14.731  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:14.732  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.732  9791  9885 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-25 18:26:14.732  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:14.733  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:26:14.735  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
,07-25 18:26:14.736  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-25 18:26:14.736  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44c8511 added. We now have 3 listener(s)
,07-25 18:26:14.736  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44c8511 added. We now have 5 listener(s)
07-25 18:26:14.736  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-25 18:26:14.740  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:14.740  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:26:14.741  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:14.741  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-25 18:26:14.742  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1460676 added. We now have 6 listener(s)
07-25 18:26:14.742  9791  9855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-25 18:26:14.743  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-25 18:26:14.749  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:26:14.759  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:14.763  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:26:14.763  9791  9855 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-25 18:26:14.769  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:14.776  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:14.783  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:14.789  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:14.800  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:14.804  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:26:14.805  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-25 18:26:14.805  9791  9855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:26:14.805  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-25 18:26:14.805  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:26:14.805  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-25 18:26:14.805  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44c8511 removed from the list
07-25 18:26:14.806  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44c8511 removed from the list
07-25 18:26:14.806  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-25 18:26:14.806  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1460676 removed from the list
,07-25 18:26:14.806  9791  9855 D io.jxcore.node.ConnectivityMonitor: stop
,07-25 18:26:14.806  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-25 18:26:14.809  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,07-25 18:26:14.810  9791  9855 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,07-25 18:26:14.813  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,07-25 18:26:14.814  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
07-25 18:26:14.816  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,07-25 18:26:14.817  9791  9855 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-25 18:26:14.819  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
07-25 18:26:14.819  9791  9855 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,07-25 18:26:14.822  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
07-25 18:26:14.822  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-25 18:26:14.823  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-25 18:26:14.823  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-25 18:26:14.823  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-25 18:26:14.823  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-25 18:26:14.823  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-25 18:26:14.824  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-25 18:26:14.824  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-25 18:26:14.824  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-25 18:26:14.826  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
07-25 18:26:14.826  9791  9855 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-25 18:26:14.826  9791  9855 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-25 18:26:14.827  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,07-25 18:26:14.830  9791  9855 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-25 18:26:14.831  9791  9855 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-25 18:26:14.831  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-25 18:26:14.832  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
07-25 18:26:14.832  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-25 18:26:14.832  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
07-25 18:26:14.832  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-25 18:26:14.832  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-25 18:26:14.832  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
07-25 18:26:14.832  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
,07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-25 18:26:14.833  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-25 18:26:14.834  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-25 18:26:14.834  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-25 18:26:14.834  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-25 18:26:14.834  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-25 18:26:14.834  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-25 18:26:14.834  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-25 18:26:14.834  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-25 18:26:14.835  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-25 18:26:14.835  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
,07-25 18:26:14.835  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-25 18:26:14.835  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-25 18:26:14.835  9791  9855 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-25 18:26:14.835  9791  9855 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-25 18:26:14.835  9791  9855 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-25 18:26:14.836  9791  9855 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-25 18:26:14.836  9791  9855 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-25 18:26:14.836  9791  9855 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-25 18:26:14.836  9791  9855 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-25 18:26:14.836  9791  9855 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-25 18:26:14.837  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,07-25 18:26:14.845  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,07-25 18:26:14.846  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
07-25 18:26:14.846  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,07-25 18:26:14.848  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,07-25 18:26:14.849  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,07-25 18:26:14.849  9791  9855 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,07-25 18:26:14.849  9791  9886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 195)
,07-25 18:26:14.849  9791  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
07-25 18:26:14.849  9791  9855 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-25 18:26:14.849  9791  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
,07-25 18:26:14.849  9791  9855 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-25 18:26:14.849  9791  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
07-25 18:26:14.852  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,07-25 18:26:14.852  9791  9855 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-25 18:26:14.854  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,07-25 18:26:14.855  9791  9855 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-25 18:26:14.857  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,07-25 18:26:14.858  9791  9855 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-25 18:26:14.858  9791  9855 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,07-25 18:26:14.858  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-25 18:26:14.858  9791  9855 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,07-25 18:26:14.858  9791  9855 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-25 18:26:14.858  9791  9855 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,07-25 18:26:14.859  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-25 18:26:14.859  9791  9855 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-25 18:26:14.859  9791  9855 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-25 18:26:14.859  9791  9855 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-25 18:26:14.859  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-25 18:26:14.859  9791  9855 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-25 18:26:14.860  9791  9886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
07-25 18:26:14.861  9791  9886 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
07-25 18:26:14.861  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,07-25 18:26:14.865  9791  9855 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-25 18:26:14.865  9791  9855 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-25 18:26:14.865  9791  9855 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
07-25 18:26:14.865  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
07-25 18:26:14.866  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:26:14.869  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:14.869  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:14.870  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.870  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:26:14.873  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:14.873  9791  9886 D BluetoothSocket: connect(): myUserId = 0
07-25 18:26:14.873  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:14.873  9791  9886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:26:14.874  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.874  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-25 18:26:14.874  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:26:14.874  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:26:14.874  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:26:14.876  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-25 18:26:14.877  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-25 18:26:14.877  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,07-25 18:26:14.877  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:26:14.877  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:26:14.877  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-25 18:26:14.877  9791  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:26:14.877  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:26:14.877  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-25 18:26:14.877  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-25 18:26:14.879  9791  9887 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:14.879  9791  9887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:26:14.885  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-25 18:26:14.885  9791  9855 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:26:14.885  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-25 18:26:14.886  9791  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:26:14.886  9791  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@1e3614d, port: 6, type: 1, local socket address: null, socket type: 0
,07-25 18:26:14.888  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.890  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.890  3697  3777 D SecContentProvider: insert(), uri = 2
07-25 18:26:14.891  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:14.891  3697  3777 D SecContentProvider: called from android.uid.bluetooth:1002
07-25 18:26:14.892  4061  4655 W bt_btif : bta_dm_bl_change_cback : reason=0
07-25 18:26:14.892  4061  4180 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,07-25 18:26:14.895  9791  9855 D BluetoothAdapter: isSecureModeEnabled
07-25 18:26:14.895  4061  4953 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:14.897  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.897  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-25 18:26:14.898  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.899  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:14.899  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:26:14.899  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:26:14.899  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,07-25 18:26:14.902  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.906  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.906  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.906  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:26:14.906  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-25 18:26:14.907  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-25 18:26:14.907  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
07-25 18:26:14.907  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:14.907  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:14.907  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.908  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.908  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:26:14.908  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:14.908  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:14.908  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.909  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:14.910  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.911  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:14.911  9791  9855 D BluetoothAdapter: isSecureModeEnabled
07-25 18:26:14.911  4061  4073 D BtConfig.SecureMode: isSecureModeOn:false
,07-25 18:26:14.912  9791  9855 D BluetoothLeAdvertiser: start advertising
,07-25 18:26:14.913  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:14.918  4061  4717 D BtGatt.GattService: registerClient() - UUID=ea14b6eb-ac4e-4cbf-8f66-5d772a1a2787
,07-25 18:26:15.020  4061  4180 D BtGatt.GattService: onClientRegistered() - UUID=ea14b6eb-ac4e-4cbf-8f66-5d772a1a2787, clientIf=5, status=0
,07-25 18:26:15.022  9791  9803 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-25 18:26:15.026  4061  4073 E BtGatt.ContextMap: Context not found for ID 5
,07-25 18:26:15.027  4061  4586 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-25 18:26:15.027  4061  4572 D BtGatt.AdvertiseManager: message : 0
,07-25 18:26:15.033  4061  4572 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:26:15.033  4061  4572 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:26:15.040  4061  4572 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:26:15.046  4061  4572 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:26:15.049  4061  4655 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-25 18:26:15.071  4061  4180 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-25 18:26:15.075  4061  4572 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:26:15.087  4061  4180 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-25 18:26:15.087  4061  4572 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:26:15.088  4061  4572 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-25 18:26:15.088  4061  4572 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-25 18:26:15.088  4061  4572 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-25 18:26:15.089  9791  9802 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-25 18:26:15.091  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.092  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.093  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-25 18:26:15.094  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.095  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.096  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.098  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.099  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.099  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-25 18:26:15.105  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-25 18:26:15.106  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.106  9791  9855 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-25 18:26:15.111  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.112  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.113  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.114  9791  9855 I io.jxcore.node.ConnectionHelper: start: OK
07-25 18:26:15.114  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-25 18:26:15.116  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-25 18:26:15.117  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,07-25 18:26:15.117  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:26:15.118  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.119  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.120  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:15.121  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.122  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:26:15.122  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:26:15.123  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:15.124  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-25 18:26:15.125  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.126  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-25 18:26:15.127  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:15.136  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.136  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:26:15.137  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.138  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-25 18:26:15.139  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:26:15.622  9791  9878 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-25 18:26:15.623  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-25 18:26:15.623  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:26:15.623  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:26:15.623  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,07-25 18:26:15.624  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-25 18:26:15.624  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:26:15.625  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:26:15.625  9791  9887 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:26:15.625  9791  9887 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:26:15.625  9791  9887 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:26:15.625  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-25 18:26:15.625  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-25 18:26:15.626  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,07-25 18:26:15.627  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:26:15.628  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:26:15.628  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf00b87 removed from the list
07-25 18:26:15.629  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf00b87 removed from the list
07-25 18:26:15.629  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-25 18:26:15.629  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:26:15.629  9791  9889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 195
07-25 18:26:15.629  9791  9889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
07-25 18:26:15.629  9791  9889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 195)
07-25 18:26:15.630  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.630  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:26:15.630  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:26:15.630  9791  9889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 195)
07-25 18:26:15.631  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.632  4061  4921 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
07-25 18:26:15.633  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.634  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.635  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.635  9791  9886 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
07-25 18:26:15.635  9791  9886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
07-25 18:26:15.635  9791  9886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 195)
07-25 18:26:15.637  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:15.639  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:15.639  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-25 18:26:15.641  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:15.643  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:15.644  9791  9855 D BluetoothLeScanner: could not find callback wrapper
07-25 18:26:15.644  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:26:15.644  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.645  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.645  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.645  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-25 18:26:15.646  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.648  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:15.649  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:15.649  9791  9855 D BluetoothLeAdvertiser: stop advertising
,07-25 18:26:15.650  4061  4717 E BtGatt.ContextMap: Context not found for ID 5
,07-25 18:26:15.651  4061  4586 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,07-25 18:26:15.652  4061  4572 D BtGatt.AdvertiseManager: message : 1
07-25 18:26:15.653  4061  4572 D BtGatt.AdvertiseManager: stop advertise for client =  5
,07-25 18:26:15.653  4061  4572 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
07-25 18:26:15.655  4061  4572 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:26:15.660  4061  4180 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-25 18:26:15.660  4061  4180 D BtGatt.GattService: Client app is not null!
,07-25 18:26:15.661  9791  9803 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-25 18:26:15.662  4061  4073 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-25 18:26:15.664  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:26:15.665  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.665  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-25 18:26:15.665  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.666  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.666  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.667  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-25 18:26:15.667  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-25 18:26:15.668  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-25 18:26:15.669  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.672  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.672  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:26:15.673  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:15.673  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:15.673  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7223ab4 removed from the list
07-25 18:26:15.673  9791  9855 D io.jxcore.node.ConnectivityMonitor: stop
,07-25 18:26:15.673  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-25 18:26:15.673  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:26:15.674  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:15.674  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-25 18:26:15.674  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:15.675  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.675  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:26:15.675  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:26:15.675  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.676  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,07-25 18:26:15.676  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:15.677  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:26:16.178  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-25 18:26:16.655  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:16.655  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-25 18:26:19.620  4645  4645 D io_stats: !@   8,0 r 25074 2253556 w 4803 202800 d 647 73944 f 1937 1937 iot 11310 10519 th 472584 0 0 pt 0 inp 0 0 282.157
,07-25 18:26:19.676  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:19.676  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-25 18:26:19.815  3697  5674 D SSRM:f  : SIOP:: AP = 290, PST = 302 (W:14), CP = 247, CUR = -33, LCD = 57
,07-25 18:26:20.677  9791  9879 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,07-25 18:26:20.681  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,07-25 18:26:20.684  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:26:20.684  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:26:20.688  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-25 18:26:20.690  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-25 18:26:20.691  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:26:20.691  9791  9890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:26:20.691  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:26:20.691  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:26:20.691  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-25 18:26:20.692  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-25 18:26:20.696  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
07-25 18:26:20.696  9791  9890 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:20.696  9791  9890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:26:20.697  9791  9855 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
,07-25 18:26:20.698  9791  9855 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-25 18:26:20.698  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-25 18:26:20.701  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-25 18:26:20.705  9791  9890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,07-25 18:26:20.706  9791  9890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@f615113, port: 6, type: 1, local socket address: null, socket type: 0
07-25 18:26:20.707  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,07-25 18:26:20.717  9791  9855 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,07-25 18:26:20.718  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-25 18:26:20.718  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:26:20.719  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:26:20.719  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:26:20.719  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:26:20.719  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:26:20.719  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:26:20.719  9791  9890 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:26:20.720  9791  9855 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf00b87 not in the list
07-25 18:26:20.720  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-25 18:26:20.720  9791  9890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:26:20.720  9791  9890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:26:20.720  9791  9855 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf00b87 not in the list
07-25 18:26:20.720  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-25 18:26:20.720  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-25 18:26:20.720  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:26:20.720  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:26:20.720  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:20.721  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:26:20.721  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:26:20.721  9791  9855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:26:20.721  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-25 18:26:20.722  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:20.725  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:20.726  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:26:20.726  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:20.727  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:20.727  9791  9855 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7223ab4 not in the list
07-25 18:26:20.727  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:20.727  9791  9855 D io.jxcore.node.ConnectivityMonitor: stop
,07-25 18:26:20.727  9791  9855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:26:20.727  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:26:20.727  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:20.728  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:26:20.730  9791  9855 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,07-25 18:26:20.732  9791  9855 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-25 18:26:20.732  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-25 18:26:20.732  9791  9855 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-25 18:26:20.732  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-25 18:26:20.733  9791  9855 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-25 18:26:20.733  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-25 18:26:20.735  9791  9855 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,07-25 18:26:20.737  9791  9855 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,07-25 18:26:20.739  9791  9855 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,07-25 18:26:20.740  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
07-25 18:26:20.741  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,07-25 18:26:20.743  9791  9855 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,07-25 18:26:20.744  9791  9855 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-25 18:26:20.744  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-25 18:26:20.744  9791  9855 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-25 18:26:20.745  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-25 18:26:20.745  9791  9855 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-25 18:26:20.745  9791  9855 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-25 18:26:20.746  9791  9855 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,07-25 18:26:20.747  9791  9855 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-25 18:26:20.747  9791  9855 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-25 18:26:20.749  9791  9855 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,07-25 18:26:20.749  9791  9855 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-25 18:26:20.750  9791  9855 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,07-25 18:26:20.750  9791  9855 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-25 18:26:20.750  9791  9855 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-25 18:26:20.752  9791  9855 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,07-25 18:26:20.754  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-25 18:26:20.754  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad57f50 added. We now have 2 listener(s)
07-25 18:26:20.754  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad57f50 added. We now have 3 listener(s)
07-25 18:26:20.754  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-25 18:26:20.757  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:20.757  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-25 18:26:20.757  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:20.758  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-25 18:26:20.758  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@191c549 added. We now have 4 listener(s)
07-25 18:26:20.758  9791  9855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-25 18:26:20.759  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-25 18:26:20.763  9791  9855 D BluetoothAdapter: enable()
,07-25 18:26:20.767  4061  4073 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-25 18:26:20.768  4061  4073 D AdapterProvider: query
,07-25 18:26:20.776  4061  4073 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@2d0b691
07-25 18:26:20.777  4061  4073 D BluetoothAdapterService: updateEvent - already set, update
07-25 18:26:20.778  4061  4073 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:20.778  4061  4073 D AdapterProvider: update
,07-25 18:26:20.782  4061  4073 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:20.784  9791  9855 D BluetoothAdapter: enable(): BT is already enabled..!
,07-25 18:26:20.788  3697  4837 D WifiService: setWifiEnabled: true pid=9791, uid=10033
07-25 18:26:20.789  3697  4837 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-25 18:26:20.789  3697  4837 D WifiControlHistoryProvider: query
,07-25 18:26:20.796  3697  4837 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:26:20.797  3697  4837 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:20.797  3697  4837 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:20.800  3697  4837 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-25 18:26:20.801  3697  4837 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-25 18:26:20.803  9791  9855 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,07-25 18:26:20.807  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:20.811  9791  9855 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,07-25 18:26:20.813  9791  9855 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,07-25 18:26:20.815  9791  9855 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,07-25 18:26:20.818  9791  9891 D BluetoothAdapter: disable()
,07-25 18:26:20.823  4061  4072 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : false
,07-25 18:26:20.824  4061  4072 D AdapterProvider: query
07-25 18:26:20.824  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:20.833  4061  4072 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@f74b864
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:20.833  9791  9855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:26:20.834  4061  4072 D BluetoothAdapterService: updateEvent - already set, update
07-25 18:26:20.835  4061  4072 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:20.835  4061  4072 D AdapterProvider: update
07-25 18:26:20.839  4061  4072 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:20.844  3697  3829 D SecContentProvider: insert(), uri = 2
,07-25 18:26:20.845  3697  3829 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:20.846  4061  4173 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,07-25 18:26:20.848  4061  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-25 18:26:20.848  4061  4173 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-25 18:26:20.852  4061  4061 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-25 18:26:20.852  3697  3829 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
,07-25 18:26:20.855  4074  4074 D BluetoothPbap: Proxy object disconnected
07-25 18:26:20.856  4074  4074 D PbapServerProfile: Bluetooth service disconnected
,07-25 18:26:20.856  4061  4173 D BluetoothAdapterService: Autoconnection is available 
07-25 18:26:20.856  4061  4173 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,07-25 18:26:20.856  4061  4173 D BluetoothAdapterService: terminating service from this receiver
07-25 18:26:20.858  4061  4061 D DOWNLOADABLE_DB: onReceive of BR
07-25 18:26:20.858  4061  4061 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-25 18:26:20.858  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:20.858  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:20.859  4061  4061 D DOWNLOADABLE_DB: onReceive of BR
07-25 18:26:20.860  4061  4061 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-25 18:26:20.860  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:20.860  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:20.865  4061  4173 W bt_btif : btif_dm_cancel_discovery
,07-25 18:26:20.867  3697  6617 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-25 18:26:20.868  3697  6617 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:20.869  4074  4299 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:20.870  4074  4299 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
07-25 18:26:20.870  3697  3777 D SecContentProvider: insert(), uri = 2
,07-25 18:26:20.870  3697  3777 D SecContentProvider: called from android.uid.bluetooth:1002
07-25 18:26:20.872  4061  4173 I BluetoothAdapterState: Entering PendingCommandState
,07-25 18:26:20.873  3697  3697 D BluetoothPhoneService: Bluetooth Adapter state : 13
,07-25 18:26:20.882  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-25 18:26:20.882  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:20.882  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-25 18:26:20.893  9791  9791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:20.893  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:26:20.895  9791  9791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-25 18:26:20.895  9791  9791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-25 18:26:20.899  4061  4180 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:26:20.900  4061  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,07-25 18:26:20.902  4061  4173 E BluetoothServiceJni: disableBrEdrNative:
07-25 18:26:20.902  4061  4173 E bt_btif : disable_bredr
07-25 18:26:20.903  4061  4180 W bt_btif : btif_dm_generic_evt: event=33035
07-25 18:26:20.903  4061  4922 W bt_osi_thread: run_thread: thread id 4922, thread name btif_sock exited
07-25 18:26:20.903  3697  4893 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4061 / op:PendingIntent{7a4dca9: PendingIntentRecord{23a22e com.android.bluetooth broadcastIntent}}
07-25 18:26:20.905  4061  8162 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-25 18:26:20.905  4061  4175 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-25 18:26:20.905  4061  4988 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-25 18:26:20.906  4061  4990 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-25 18:26:20.906  4061  4988 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
07-25 18:26:20.906  4061  4175 E bt_btif : BTA_DisableBluetoothOnly
07-25 18:26:20.906  4061  4990 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-25 18:26:20.909  4061  4655 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-25 18:26:20.911  4061  4061 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:20.913  4061  4180 W bt_btif : btif_dm_generic_evt: event=33035
07-25 18:26:20.915  4061  4821 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-25 18:26:20.915  4061  4061 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-25 18:26:20.915  4061  4821 D BluetoothSdpJni: SDP Remove record success - handle: 1
07-25 18:26:20.915  4061  4061 D BluetoothSdpJni: SDP Remove record success - handle: 0
07-25 18:26:20.915  4061  4821 D BluetoothMapMasInstance: RemoveSDPrecord returns true
07-25 18:26:20.915  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:20.918  4061  4061 I BtOppRfcommListener: stopping Accept Thread
07-25 18:26:20.919  4061  8162 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-25 18:26:20.920  4061  4180 W bt_btif : btif_dm_generic_evt: event=33035
07-25 18:26:20.920  4061  4821 D ObexServerSockets: shutdown(block = true)
07-25 18:26:20.920  4061  4821 D ObexServerSockets: shutdown called from another thread - interrupt().
07-25 18:26:20.920  4061  4821 D ObexServerSockets: shutdown called from another thread - interrupt().
07-25 18:26:20.922  4061  4655 W bt_btm  : btm_sec_connected
07-25 18:26:20.922  4061  4655 W bt_btif : bta_dm_bl_change_cback : reason=2
07-25 18:26:20.923  4061  4655 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
07-25 18:26:20.923  4061  4655 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
07-25 18:26:20.923  4061  4655 W bt_btif : bta_dm_bl_change_cback : reason=2
07-25 18:26:20.928  4061  4180 W bt_btif : btif_dm_generic_evt: event=33035
07-25 18:26:20.930  4061  4180 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
07-25 18:26:20.930  4061  4180 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
07-25 18:26:20.932  4061  4061 V BluetoothOppManager: cleanUp...
07-25 18:26:20.934  9109  9109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-25 18:26:20.937  4061  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:20.939  4061  4180 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 1
,07-25 18:26:20.947  4061  4180 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:26:20.948  4061  4180 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 241
,07-25 18:26:20.949  4074  4299 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
07-25 18:26:20.950  9109  9109 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,07-25 18:26:20.965  9109  9109 D LocalBluetoothManager: LocalBluetoothManager :: constructor
,07-25 18:26:20.967  9109  9109 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,07-25 18:26:20.973  9109  9109 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
07-25 18:26:20.973  9109  9109 D LocalBluetoothProfileManager: PANU : true
,07-25 18:26:20.984  9109  9109 D BluetoothSap: Create BluetoothSap proxy object
,07-25 18:26:20.991  9109  9109 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-25 18:26:20.991  9109  9109 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-25 18:26:20.998  9109  9109 D DockEventReceiver: finishStartingService: stopping service
,07-25 18:26:20.999  9109  9109 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:21.000  9109  9109 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,07-25 18:26:21.000  9109  9109 D BluetoothPan: BluetoothPAN Proxy object connected
07-25 18:26:21.000  9109  9109 D PanProfile: Bluetooth service connected
,07-25 18:26:21.002  9109  9109 D BluetoothSap: Proxy object connected
,07-25 18:26:21.003  9109  9109 D SapProfile: Bluetooth service connected
,07-25 18:26:21.045  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-25 18:26:21.056  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-25 18:26:21.057  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-25 18:26:21.111  3697  6617 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20270723T182621 - CU:10019/CP:4718
,07-25 18:26:21.113  4061  4180 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_BT_EVT
07-25 18:26:21.113  4061  4180 E BluetoothAdapterState: stateChangeCallback : 16
,07-25 18:26:21.114  4061  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,07-25 18:26:21.117  4061  4173 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:21.117  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-25 18:26:21.122  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-25 18:26:21.124  4061  4061 D HeadsetService: Received stop request...Stopping profile...
,07-25 18:26:21.126  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.127  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
07-25 18:26:21.127  4061  4061 D HeadsetService: notifyProfileServiceStateChanged
07-25 18:26:21.128  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-25 18:26:21.131  4074  4074 D HeadsetProfile: Bluetooth service disconnected
,07-25 18:26:21.131  3697  3697 W BluetoothHeadset: Proxy not attached to service
07-25 18:26:21.132  3697  3697 I Telecom : SecBluetoothManager : not single connected gear
07-25 18:26:21.132  3697  3697 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-25 18:26:21.132  3697  3697 D BluetoothHeadset: unRegisterMessageListener : 11
07-25 18:26:21.132  3697  3697 W BluetoothHeadset: Proxy not attached to service
07-25 18:26:21.132  3697  3697 I Telecom : SecBluetoothManager : unregister MessageListener
07-25 18:26:21.134  3697  4568 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
07-25 18:26:21.134  3697  4568 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
07-25 18:26:21.134  3697  4568 I Telecom : SecBluetoothManager : mBluetoothHeadset is null
07-25 18:26:21.134  3697  4568 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACU_0
07-25 18:26:21.135  4061  4061 D A2dpService: Received stop request...Stopping profile...
07-25 18:26:21.137  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-25 18:26:21.138  4061  4767 D A2dpStateMachine: Exit Disconnected: -1
,07-25 18:26:21.143  4061  4061 D Avrcp   : unregisterContentObserver
07-25 18:26:21.143  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-25 18:26:21.145  4061  4061 D Avrcp   : removeOnActiveSessionsChangedListener
07-25 18:26:21.146  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-25 18:26:21.146  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.146  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
07-25 18:26:21.146  4061  4061 D A2dpService: notifyProfileServiceStateChanged
,07-25 18:26:21.148  4074  4074 D A2dpProfile: Bluetooth service disconnected
07-25 18:26:21.150  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.150  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
07-25 18:26:21.150  4061  4061 V BluetoothAdapterState: isTurningOff()=true
07-25 18:26:21.150  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.150  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:21.150  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
07-25 18:26:21.150  4061  4061 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:21.150  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:21.153  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:26:21.153  4061  4173 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,07-25 18:26:21.153  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
07-25 18:26:21.153  4061  4173 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
07-25 18:26:21.153  4061  4173 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-25 18:26:21.155  3697  3707 I art     : Background partial concurrent mark sweep GC freed 223528(11MB) AllocSpace objects, 119(2MB) LOS objects, 28% free, 40MB/56MB, paused 2.075ms total 202.422ms
,07-25 18:26:21.158  4061  4061 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-25 18:26:21.158  4061  4061 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-25 18:26:21.161  4061  4061 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
07-25 18:26:21.162  4061  4061 D HidService: Received stop request...Stopping profile...
07-25 18:26:21.162  4061  4061 D HidService: Stopping Bluetooth HidService
,07-25 18:26:21.162  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.162  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
07-25 18:26:21.162  4061  4061 D HidService: notifyProfileServiceStateChanged
,07-25 18:26:21.166  4074  4074 D BluetoothInputDevice: Proxy object disconnected
07-25 18:26:21.166  4074  4074 D HidProfile: Bluetooth service disconnected
07-25 18:26:21.166  4061  4061 D HealthService: Received stop request...Stopping profile...
07-25 18:26:21.167  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.167  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
07-25 18:26:21.167  4061  4061 D HealthService: notifyProfileServiceStateChanged
07-25 18:26:21.169  4061  4061 D PanService: Received stop request...Stopping profile...
,07-25 18:26:21.172  4061  4061 D EnhancedTetheringManager: stop
07-25 18:26:21.173  4061  4061 D EnhancedTetheringManager: tetherEnabled : false
07-25 18:26:21.173  4061  4061 D ETMLeHelper: stopAdvertise
07-25 18:26:21.174  4061  4061 D BluetoothAdapter: STATE_TURNING_OFF
,07-25 18:26:21.174  4061  4061 D BluetoothAdapter: STATE_TURNING_OFF
07-25 18:26:21.175  4061  4061 D BluetoothLeAdvertiser: stop advertising
07-25 18:26:21.175  4061  4061 D BluetoothLeAdvertiser: wrapper is null
07-25 18:26:21.175  4061  4061 D EnhancedTetheringManager: removeNapWakeAlarm
,07-25 18:26:21.179  3697  4837 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4061 / op:PendingIntent{8fd89a7: PendingIntentRecord{20eae54 com.android.bluetooth broadcastIntent}}
07-25 18:26:21.180  4061  4061 D EnhancedTetheringManager: cancelFindTetherServer
07-25 18:26:21.180  4061  4061 D ETMLeHelper: stopScan
07-25 18:26:21.184  3697  3697 D UsbMonitorService: readUsbState++
07-25 18:26:21.184  3697  3697 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-25 18:26:21.185  3697  3697 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-25 18:26:21.185  3697  3697 D UsbMonitorService: Posting Message again
07-25 18:26:21.185  4061  4061 D BluetoothAdapter: STATE_TURNING_OFF
,07-25 18:26:21.187  4061  4061 D BluetoothAdapter: STATE_TURNING_OFF
,07-25 18:26:21.187  4061  4061 D BluetoothLeScanner: could not find callback wrapper
07-25 18:26:21.187  4061  4061 D EnhancedTetheringManager: removePanuWakeAlarm
,07-25 18:26:21.191  3697  4945 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4061 / op:PendingIntent{fd25bc0: PendingIntentRecord{b05c0f9 com.android.bluetooth broadcastIntent}}
,07-25 18:26:21.192  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.192  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
07-25 18:26:21.192  4061  4061 D PanService: notifyProfileServiceStateChanged
,07-25 18:26:21.194  4074  4074 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-25 18:26:21.194  4074  4074 D PanProfile: Bluetooth service disconnected
,07-25 18:26:21.195  4718  4718 D BluetoothAdapter: STATE_TURNING_OFF
,07-25 18:26:21.195  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.195  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
07-25 18:26:21.195  4061  4061 V BluetoothAdapterState: isTurningOff()=true
07-25 18:26:21.195  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.195  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:21.195  4061  4061 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:21.196  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.197  4061  4768 W bt_osi_thread: run_thread: thread id 4768, thread name media_worker exited
07-25 18:26:21.198  4718  4718 D BluetoothAdapter: STATE_TURNING_OFF
07-25 18:26:21.199  4718  4718 I BeaconBle: Using BLE 'L' hardware layer
07-25 18:26:21.199  4061  4061 D BluetoothMapService: Received stop request...Stopping profile...
07-25 18:26:21.200  9109  9109 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-25 18:26:21.201  9109  9109 D PanProfile: Bluetooth service disconnected
07-25 18:26:21.205  4718  4718 W Nearby  : Bind call too late - someone already tried to get: interface atxb
07-25 18:26:21.205  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.206  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
07-25 18:26:21.206  4061  4061 D BluetoothMapService: notifyProfileServiceStateChanged
,07-25 18:26:21.207  4074  4074 D BluetoothMap: Proxy object disconnected
07-25 18:26:21.207  4074  4074 D MapProfile: Bluetooth service disconnected
,07-25 18:26:21.209  4061  4061 D SapService: Received stop request...Stopping profile...
07-25 18:26:21.209  4061  4061 V SapService: stop()
,07-25 18:26:21.210  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.210  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
07-25 18:26:21.210  4061  4061 D SapService: notifyProfileServiceStateChanged
,07-25 18:26:21.212  4074  4074 D BluetoothSap: Proxy object disconnected
07-25 18:26:21.212  4074  4074 D SapProfile: Bluetooth service disconnected
07-25 18:26:21.214  4061  4061 D HidDevService: Received stop request...Stopping profile...
07-25 18:26:21.214  4061  4061 D HidDevService: stop()
,07-25 18:26:21.214  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.214  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Message sending
07-25 18:26:21.214  4061  4061 D HidDevService: notifyProfileServiceStateChanged
07-25 18:26:21.215  9109  9109 D BluetoothSap: Proxy object disconnected
07-25 18:26:21.215  9109  9109 D SapProfile: Bluetooth service disconnected
07-25 18:26:21.216  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.216  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
07-25 18:26:21.216  4061  4061 V BluetoothAdapterState: isTurningOff()=true
07-25 18:26:21.216  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.216  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
,07-25 18:26:21.216  4061  4061 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:21.216  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.216  4061  4061 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-25 18:26:21.216  4061  4061 W bt_btif : cleanup: HH disabling or disabled already, status = 0
07-25 18:26:21.216  4061  4061 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-25 18:26:21.217  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.217  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
07-25 18:26:21.217  4061  4061 V BluetoothAdapterState: isTurningOff()=true
07-25 18:26:21.217  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.217  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:21.217  4061  4061 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:21.217  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.217  4061  4061 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-25 18:26:21.218  4061  4061 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-25 18:26:21.218  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.218  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
07-25 18:26:21.219  4061  4061 V BluetoothAdapterState: isTurningOff()=true
07-25 18:26:21.219  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.219  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:21.219  4061  4061 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:21.219  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.219  4061  4061 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-25 18:26:21.219  4061  4061 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-25 18:26:21.229  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-25 18:26:21.370  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.370  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
07-25 18:26:21.370  4061  4061 V BluetoothAdapterState: isTurningOff()=true
07-25 18:26:21.370  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.370  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:21.370  4061  4061 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:21.371  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.373  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.373  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
07-25 18:26:21.373  4061  4061 V BluetoothAdapterState: isTurningOff()=true
07-25 18:26:21.373  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.373  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:21.373  4061  4061 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:26:21.374  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.374  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.374  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Before synchronized
07-25 18:26:21.374  4061  4061 V BluetoothAdapterState: isTurningOff()=true
07-25 18:26:21.375  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.375  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:21.375  4061  4061 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:21.375  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.376  4061  4061 D HidDevService: cleanup()
07-25 18:26:21.376  4061  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
07-25 18:26:21.376  4061  4061 V BluetoothHidDevServiceJni: cleanupNative enter
07-25 18:26:21.376  4061  4061 I BluetoothHidDevServiceJni: Cleaning up interface
07-25 18:26:21.376  4061  4061 I BluetoothHidDevServiceJni: Cleaning up callback object
07-25 18:26:21.376  4061  4061 V BluetoothHidDevServiceJni: cleanupNative done
,07-25 18:26:21.381  9791  9891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:21.381  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-25 18:26:21.387  9791  9891 D BluetoothAdapter: enable()
,07-25 18:26:21.380  4061  4173 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@b5d4adc
07-25 18:26:21.390  4061  4173 D BtGatt.GattService: serverDisconnectIncomingConnClients()
07-25 18:26:21.390  4061  4655 W bt_btif : BTA got unregistered event id 32
07-25 18:26:21.391  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:21.391  4061  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-25 18:26:21.391  4061  4173 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-25 18:26:21.397  4061  4173 D BluetoothAdapterService: Autoconnection is available 
07-25 18:26:21.397  4061  4173 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
07-25 18:26:21.397  4061  4173 I BluetoothAdapterState: Entering BleOnState
,07-25 18:26:21.400  4061  4717 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-25 18:26:21.401  4061  4717 D AdapterProvider: query
07-25 18:26:21.407  4061  4061 D DOWNLOADABLE_DB: onReceive of BR
07-25 18:26:21.407  4061  4061 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-25 18:26:21.407  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.407  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.408  3697  3829 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:26:21.408  3697  3829 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:26:21.408  3697  3829 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:26:21.409  9791  9802 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:26:21.409  9791  9802 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:26:21.409  9791  9802 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
07-25 18:26:21.409  9791  9802 D BluetoothLeAdvertiser: Exit stop advertising
07-25 18:26:21.410  9791  9802 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:26:21.410  9791  9802 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-25 18:26:21.411  9791  9802 D BluetoothLeScanner: Exiting stopAllScan
07-25 18:26:21.412  4061  4061 D DOWNLOADABLE_DB: onReceive of BR
07-25 18:26:21.412  4074  4349 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:26:21.412  4061  4061 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-25 18:26:21.412  4074  4349 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:26:21.412  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.412  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.416  4061  4717 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@c7168ef
07-25 18:26:21.418  4061  4717 D BluetoothAdapterService: updateEvent - already set, update
07-25 18:26:21.418  4061  4717 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:21.418  4061  4717 D AdapterProvider: update
07-25 18:26:21.419  4074  4349 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:26:21.420  4718  6462 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:26:21.420  4718  6462 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:26:21.421  4718  6462 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:26:21.422  4718  6462 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-25 18:26:21.422  4718  6462 D BluetoothLeScanner: Exiting stopAllScan
07-25 18:26:21.422  4074  4242 D BluetoothMap: onBluetoothStateChange: up=false
07-25 18:26:21.424  4061  4717 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:21.434  3697  3917 W ActivityManager: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-25 18:26:21.437  3697  3917 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-25 18:26:21.437  3697  3917 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:26:21.437  3697  3917 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-25 18:26:21.437  3697  3917 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-25 18:26:21.437  3697  3917 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-25 18:26:21.437  3697  3917 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-25 18:26:21.437  3697  3917 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-25 18:26:21.437  3697  3917 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-25 18:26:21.437  3697  3917 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-25 18:26:21.437  4074  4242 D BluetoothSap: onBluetoothStateChange: up=false
07-25 18:26:21.437  3697  3917 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
07-25 18:26:21.438  4061  4173 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.439  3697  3917 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-25 18:26:21.442  3697  3917 D SecContentProvider: called from com.thaliproject.thalitest
07-25 18:26:21.444  4061  4954 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-25 18:26:21.450  4074  4088 D BluetoothPbap: onBluetoothStateChange: up=false
,07-25 18:26:21.452  4074  4349 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-25 18:26:21.454  4048  4295 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:26:21.454  4048  4295 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:26:21.455  4048  4295 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:26:21.459  4074  4242 D BluetoothPan: onBluetoothStateChange on: false
,07-25 18:26:21.461  9109  9121 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-25 18:26:21.461  9109  9121 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:26:21.462  9109  9121 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:26:21.466  4762  4776 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:26:21.466  4762  4776 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-25 18:26:21.468  4762  4776 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-25 18:26:21.469  9109  9120 D BluetoothSap: onBluetoothStateChange: up=false
,07-25 18:26:21.471  9400  9413 D BluetoothAdapter: onBluetoothStateChange: up=false
07-25 18:26:21.471  9400  9413 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-25 18:26:21.472  9400  9413 D BluetoothAdapter: There are no active google scan apps, stop scan
07-25 18:26:21.473  9109  9121 D BluetoothPan: onBluetoothStateChange on: false
,07-25 18:26:21.476  4061  4173 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,07-25 18:26:21.478  4061  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-25 18:26:21.479  4061  4173 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-25 18:26:21.479  4061  4173 D BluetoothAdapterService: Autoconnection is available 
07-25 18:26:21.479  3697  3829 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
07-25 18:26:21.479  4061  4173 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
07-25 18:26:21.481  3697  4830 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
,07-25 18:26:21.481  3697  4830 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:21.483  4074  4299 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:26:21.483  3697  3948 D SecContentProvider: insert(), uri = 2
,07-25 18:26:21.483  3697  3948 D SecContentProvider: called from android.uid.bluetooth:1002
07-25 18:26:21.484  4074  4299 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-25 18:26:21.484  3697  3697 D Telecom : SecBluetoothManager : unregister BluetoothHeadset after STATE_OFF : null
07-25 18:26:21.484  3697  3697 D Telecom : SecBluetoothManager : unRegisterBluetoothHeadsetMessageListener fail
07-25 18:26:21.485  4061  4175 E bt_btif : btif_vhci_sock_cleanup
07-25 18:26:21.486  3697  3697 D BluetoothPhoneService: Bluetooth Adapter state : 10
07-25 18:26:21.486  4061  4655 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-25 18:26:21.487  4061  4175 I bt_core_module: module_shut_down Shutting down module "btif_config_module"
07-25 18:26:21.489  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-25 18:26:21.490  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:21.490  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-25 18:26:21.492  4061  4173 I BluetoothAdapterState: Entering PendingCommandState
07-25 18:26:21.496  9109  9109 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:21.496  9109  9109 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-25 18:26:21.497  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:21.500  4061  4175 I bt_core_module: module_shut_down Shutdown of module "btif_config_module" completed
,07-25 18:26:21.505  4061  4180 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,07-25 18:26:21.505  4061  4180 W bt_btif : btif_dm_generic_evt: event=33035
07-25 18:26:21.505  4061  4061 D DOWNLOADABLE_DB: onReceive of BR
07-25 18:26:21.505  4061  4061 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-25 18:26:21.505  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.505  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:21.515  9109  9109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-25 18:26:21.517  4061  4061 D DOWNLOADABLE_DB: onReceive of BR
,07-25 18:26:21.517  4061  4061 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-25 18:26:21.517  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.517  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.518  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:21.518  4061  4180 W bt_btif : btif_dm_generic_evt: event=33035
,07-25 18:26:21.538  9109  9109 D DockEventReceiver: finishStartingService: stopping service
,07-25 18:26:21.542  4718  9905 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-25 18:26:21.546  9109  9109 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:21.547  9109  9109 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,07-25 18:26:21.645  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-25 18:26:21.652  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-25 18:26:21.652  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-25 18:26:21.688  4061  4180 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
07-25 18:26:21.689  4061  4180 I bt_core_module: module_shut_down Shutting down module "hci_module"
,07-25 18:26:21.689  4061  4180 I bt_hci  : shut_down
,07-25 18:26:21.786  4061  4588 D bt_hwcfg: hw_epilog_process
07-25 18:26:21.787  4061  4588 I bt_vendor: low_power_mode_cb
,07-25 18:26:21.794  4061  4588 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-25 18:26:21.794  4061  4588 I bt_vendor: epilog_cb
07-25 18:26:21.794  4061  4588 I bt_hci  : epilog_finished_callback
07-25 18:26:21.799  4061  4588 W bt_osi_thread: run_thread: thread id 4588, thread name hci_thread exited
07-25 18:26:21.800  4061  4180 I bt_hci_h4: hal_close
07-25 18:26:21.800  4061  4603 W bt_osi_thread: run_thread: thread id 4603, thread name hci_single_chann exited
07-25 18:26:21.801  4061  4180 I bt_userial_vendor: device fd = 96 close
07-25 18:26:21.802  4061  4180 I bt_upio : upio_set_bluetooth_power(on: 0)
07-25 18:26:21.806  4061  4180 I bt_core_module: module_shut_down Shutdown of module "hci_module" completed
07-25 18:26:21.806  4061  4180 I bt_core_module: module_shut_down Shutting down module "btsnoop_module"
07-25 18:26:21.806  4061  4180 I bt_core_module: module_shut_down Shutdown of module "btsnoop_module" completed
07-25 18:26:21.807  4061  4180 I bt_core_module: module_clean_up Cleaning up module "bte_logmsg_module"
07-25 18:26:21.807  4061  4180 I bt_core_module: module_clean_up Cleanup of module "bte_logmsg_module" completed
07-25 18:26:21.807  4061  4655 W bt_osi_thread: run_thread: thread id 4655, thread name bt_workqueue exited
07-25 18:26:21.811  4061  4175 I bt_core_module: module_shut_down Shutting down module "controller_module"
07-25 18:26:21.812  4061  4175 I bt_core_module: module_shut_down Shutdown of module "controller_module" completed
,07-25 18:26:21.814  4061  4180 E BluetoothAdapterState: stateChangeCallback : 0
07-25 18:26:21.815  4061  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,07-25 18:26:21.823  5224  6792 I Authzen : [PermitStore] Getting all permits...
,07-25 18:26:21.824  4061  4061 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-25 18:26:21.825  4061  4061 D BtGatt.GattService: Received stop request...Stopping profile...
,07-25 18:26:21.825  4061  4061 D BtGatt.GattService: stop()
07-25 18:26:21.825  4061  4061 D BtGatt.GattService: cleanup binder
07-25 18:26:21.826  4061  4061 D BtGatt.AdvertiseManager: advertise clients cleared
07-25 18:26:21.826  4061  4061 D BtGatt.ScanManager: cleanup
07-25 18:26:21.827  3697  4945 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4061 / op:PendingIntent{9645484: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:21.827  4061  4173 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-25 18:26:21.828  4061  4061 D BtGatt.ScanManager: cleanup handler
07-25 18:26:21.830  4061  4061 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:21.830  4061  4061 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
,07-25 18:26:21.830  4061  4061 D BtGatt.GattService: notifyProfileServiceStateChanged
07-25 18:26:21.831  4061  4061 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:21.832  4061  4061 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
07-25 18:26:21.832  4061  4061 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:21.832  4061  4061 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:21.832  4061  4061 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:21.832  4061  4061 V BluetoothAdapterState: isBleTurningOff()=true
07-25 18:26:21.832  4061  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
07-25 18:26:21.835  4061  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-25 18:26:21.835  4061  4173 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-25 18:26:21.836  4061  4173 D BluetoothAdapterService: Autoconnection is available 
07-25 18:26:21.836  4061  4173 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
,07-25 18:26:21.836  3697  3829 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
07-25 18:26:21.836  4061  4173 I BluetoothAdapterState: Entering OffState
,07-25 18:26:21.847  4061  4061 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-25 18:26:21.847  4061  4061 W BluetoothSdpJni: Cleaning up Bluetooth SDP object
07-25 18:26:21.848  4061  4175 E BluetoothServiceJni: Callback env check fail: env: 0x0, callback: 0xdb079950
07-25 18:26:21.848  4061  4175 E BluetoothServiceJni: Callback: 'callback_thread_event' is not called on the correct thread
07-25 18:26:21.848  4061  4180 W bt_btif : btif_dm_generic_evt: event=33035
07-25 18:26:21.848  4061  4180 E bt_btif_dm: ### ASSERT : system/bt/btif/src/btif_dm.c line 2983 Callback is NULL (0) ###
07-25 18:26:21.848  4061  4180 W bt_osi_thread: run_thread: thread id 4180, thread name bt_jni_workqueue exited
,07-25 18:26:21.849  4061  4175 I bt_core_module: module_clean_up Cleaning up module "stack_config_module"
,07-25 18:26:21.849  4061  4175 I bt_core_module: module_clean_up Cleanup of module "stack_config_module" completed
07-25 18:26:21.850  4061  4175 I bt_core_module: module_clean_up Cleaning up module "interop_module"
07-25 18:26:21.850  4061  4175 I bt_core_module: module_clean_up Cleanup of module "interop_module" completed
07-25 18:26:21.850  4061  4175 I bt_core_module: module_clean_up Cleaning up module "btif_config_module"
,07-25 18:26:21.857  4061  4175 I bt_core_module: module_clean_up Cleanup of module "btif_config_module" completed
07-25 18:26:21.858  4061  4175 I bt_core_module: module_clean_up Cleaning up module "bt_utils_module"
07-25 18:26:21.858  4061  4175 I bt_core_module: module_clean_up Cleanup of module "bt_utils_module" completed
,07-25 18:26:21.858  4061  4175 I bt_core_module: module_clean_up Cleaning up module "osi_module"
07-25 18:26:21.859  4061  4179 D bt_osi_alarm: callback_dispatch Callback thread exited
,07-25 18:26:21.859  4061  4179 W bt_osi_thread: run_thread: thread id 4179, thread name alarm_dispatcher exited
07-25 18:26:21.859  4061  4178 W bt_osi_thread: run_thread: thread id 4178, thread name alarm_default_ca exited
07-25 18:26:21.860  4061  4175 I bt_core_module: module_clean_up Cleanup of module "osi_module" completed
,07-25 18:26:21.861  4061  4061 I BluetoothServiceJni: cleanupNative: return from cleanup
07-25 18:26:21.861  4061  4061 D DOWNLOADABLE_DB: cleanup
,07-25 18:26:21.866  4061  4061 I art     : System.exit called, status: 0
07-25 18:26:21.866  4061  4061 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-25 18:26:21.889  4718  9905 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-25 18:26:21.898  3697  4945 I ActivityManager: Process com.android.bluetooth (pid 4061) has died(66,1801)
07-25 18:26:21.898  3697  4945 D ActivityManager: cleanUpApplicationRecord -- 4061
,07-25 18:26:21.900  4762  4777 D ForegroundUtils: could not check pending caller
,07-25 18:26:21.945  9791  9891 D BluetoothAdapter: enable()
,07-25 18:26:21.961  3697  4893 W ActivityManager: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-25 18:26:21.963  3697  4893 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-25 18:26:21.963  3697  4893 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-25 18:26:21.966  3697  4893 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-25 18:26:21.968  3697  4893 D SecContentProvider: called from com.thaliproject.thalitest
,07-25 18:26:21.977  3697  3829 D MountService: getExternalStorageMountMode : 3
07-25 18:26:21.978  3697  3829 D MountService: getExternalStorageMountMode : 3
07-25 18:26:21.978  3697  3829 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 1002, packageName : com.android.bluetooth
,07-25 18:26:22.015  9920  9920 E Zygote  : v2
07-25 18:26:22.015  9920  9920 I libpersona: KNOX_SDCARD checking this for 1002
07-25 18:26:22.015  9920  9920 I libpersona: KNOX_SDCARD not a persona
,07-25 18:26:22.017  9920  9920 E Zygote  : accessInfo : 0
07-25 18:26:22.018  3697  3829 I ActivityManager: Start proc 9920:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-25 18:26:22.028  9920  9920 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:22.030  9920  9920 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.bluetooth 
,07-25 18:26:22.055  9920  9920 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:22.056  9920  9920 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:22.058  3697  4837 I ActivityManager: DSS on for com.android.bluetooth and scale is 1.0
,07-25 18:26:22.113  9920  9920 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-25 18:26:22.119  9920  9920 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:22.127  9920  9920 I HeadsetProvider: onCreate
,07-25 18:26:22.138  9920  9920 D BtSettings.ProfileConfig: Adding GattService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding HeadsetService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding A2dpService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding HidService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding HealthService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding PanService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding SapService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-25 18:26:22.139  9920  9920 D BtSettings.ProfileConfig: Adding HidDevService
07-25 18:26:22.139  9920  9920 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-25 18:26:22.147  3697  6550 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.149  3697  6550 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.152  3697  4893 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.154  3697  4893 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.157  3697  3928 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.158  3697  3928 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.162  3697  4830 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.163  3697  4830 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.167  3697  4837 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.168  3697  4837 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.172  3697  3776 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.173  3697  3776 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.177  3697  6617 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.178  3697  6617 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.180  3697  3948 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.181  3697  3948 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.183  3697  3944 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.184  3697  3944 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.186  3697  4547 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.187  3697  4547 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.189  3697  4829 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-25 18:26:22.190  3697  4829 D SecContentProvider: called from android.uid.bluetooth:1002
,07-25 18:26:22.291  9920  9920 D BluetoothAdapterState: make() - Creating AdapterState
,07-25 18:26:22.295  9920  9933 I BluetoothAdapterState: Entering OffState
,07-25 18:26:22.298  9920  9935 W bt_osi_thread: run_thread: thread id 9935, thread name stack_manager started
,07-25 18:26:22.299  9920  9935 I bt_core_module: module_init Initializing module "osi_module"
07-25 18:26:22.299  9920  9935 I bt_core_module: module_init Initialized module "osi_module"
07-25 18:26:22.299  9920  9935 I bt_core_module: module_init Initializing module "bt_utils_module"
07-25 18:26:22.299  9920  9935 I bt_core_module: module_init Initialized module "bt_utils_module"
07-25 18:26:22.299  9920  9935 I bt_core_module: module_init Initializing module "btif_config_module"
,07-25 18:26:22.300  9920  9938 W bt_osi_thread: run_thread: thread id 9938, thread name alarm_default_ca started
07-25 18:26:22.301  9920  9939 W bt_osi_thread: run_thread: thread id 9939, thread name alarm_dispatcher started
07-25 18:26:22.301  9920  9935 I bt_core_module: module_init Initialized module "btif_config_module"
07-25 18:26:22.301  9920  9935 I bt_core_module: module_init Initializing module "interop_module"
07-25 18:26:22.301  9920  9935 I bt_core_module: module_init Initialized module "interop_module"
07-25 18:26:22.302  9920  9935 I bt_core_module: module_init Initializing module "stack_config_module"
,07-25 18:26:22.303  9920  9935 I bt_core_module: module_init Initialized module "stack_config_module"
,07-25 18:26:22.304  9920  9940 W bt_osi_thread: run_thread: thread id 9940, thread name bt_jni_workqueue started
07-25 18:26:22.305  9920  9920 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
,07-25 18:26:22.305  9920  9920 W bt_btif : btif_get_adapter_property 2
07-25 18:26:22.305  9920  9920 W bt_btif : btif_get_adapter_property 1
,07-25 18:26:22.307  9920  9940 E BluetoothServiceJni: populateRssiValuesNative
07-25 18:26:22.307  9920  9940 I bt_btif : getModelRssiValues
07-25 18:26:22.307  9920  9940 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,07-25 18:26:22.308  9920  9920 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-25 18:26:22.310  9920  9920 D BluetoothAdapterService: makeHashMapAvPerformance: Loading from conf
,07-25 18:26:22.325  3697  3829 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-25 18:26:22.328  9920  9933 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-25 18:26:22.329  9920  9931 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-25 18:26:22.330  9920  9931 D AdapterProvider: query
,07-25 18:26:22.334  9920  9933 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
07-25 18:26:22.334  9920  9933 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-25 18:26:22.335  3697  3829 D BluetoothManagerService: Ble Turning On/Off, G state: 0, S state: 0
07-25 18:26:22.339  9920  9933 D BluetoothAdapterService: Autoconnection is available 
07-25 18:26:22.339  9920  9933 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
07-25 18:26:22.339  9920  9931 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@1b7caf3
07-25 18:26:22.340  9920  9933 D BluetoothAdapterState: Set Downloadbale DB
07-25 18:26:22.340  9920  9933 D DOWNLOADABLE_DB: initBluetoothDatabase
07-25 18:26:22.340  9920  9931 D BluetoothAdapterService: updateEvent - already set, update
07-25 18:26:22.341  9920  9933 D DOWNLOADABLE_DB: initBroadcastReceiver
07-25 18:26:22.341  9920  9931 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:22.341  9920  9931 D AdapterProvider: update
,07-25 18:26:22.344  9920  9933 D DOWNLOADABLE_DB: cleanupLooper
,07-25 18:26:22.344  9920  9933 D DOWNLOADABLE_DB: quit init handler
,07-25 18:26:22.346  9920  9931 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:22.359  9920  9933 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-25 18:26:22.362  3697  4837 D MountService: getExternalStorageMountMode : 1
07-25 18:26:22.362  3697  4837 D MountService: getExternalStorageMountMode : 3
07-25 18:26:22.362  3697  4837 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10135, packageName : com.samsung.android.sm.policy
,07-25 18:26:22.384  9942  9942 E Zygote  : v2
07-25 18:26:22.384  9942  9942 I libpersona: KNOX_SDCARD checking this for 10135
,07-25 18:26:22.385  9942  9942 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:22.385  3697  4837 I ActivityManager: Start proc 9942:com.samsung.android.sm.policy/u0a135 for content provider com.samsung.android.sm.policy/.db.PolicyClientProvider
07-25 18:26:22.386  9942  9942 E Zygote  : accessInfo : 0
,07-25 18:26:22.396  9942  9942 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:22.398  9942  9942 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-25 18:26:22.422  9942  9942 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:22.423  9942  9942 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:22.426  3697  3948 I ActivityManager: DSS on for com.samsung.android.sm.policy and scale is 1.0
,07-25 18:26:22.460  9942  9942 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient_N/lib/arm64
,07-25 18:26:22.475  9791  9891 D BluetoothAdapter: enable()
,07-25 18:26:22.484  9942  9942 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:22.486  9920  9941 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-25 18:26:22.487  9920  9941 D AdapterProvider: query
,07-25 18:26:22.506  9920  9941 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@36022ba
,07-25 18:26:22.511  9920  9941 D BluetoothAdapterService: updateEvent - already set, update
07-25 18:26:22.512  9920  9941 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:22.512  9920  9941 D AdapterProvider: update
,07-25 18:26:22.517  9920  9941 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:22.525  3697  4945 W ActivityManager: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-25 18:26:22.526  3697  4945 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-25 18:26:22.526  3697  4945 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:26:22.526  3697  4945 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-25 18:26:22.526  3697  4945 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-25 18:26:22.526  3697  4945 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-25 18:26:22.526  3697  4945 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-25 18:26:22.526  3697  4945 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-25 18:26:22.526  3697  4945 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-25 18:26:22.526  3697  4945 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-25 18:26:22.526  3697  4945 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-25 18:26:22.528  9920  9933 D DOWNLOADABLE_DB: Local DB version is = 20160428 SCPM Client DB version is= 20160428
,07-25 18:26:22.528  3697  4945 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-25 18:26:22.528  9920  9933 D DOWNLOADABLE_DB: latest polices have already been updated for BT_HFP
,07-25 18:26:22.529  3697  4945 D SecContentProvider: called from com.thaliproject.thalitest
,07-25 18:26:22.543  9920  9933 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-25 18:26:22.560  9920  9933 D DOWNLOADABLE_DB: Local DB version is = 20160617 SCPM Client DB version is= 20160617
07-25 18:26:22.560  9920  9933 D DOWNLOADABLE_DB: latest polices have already been updated for BT_BLE
,07-25 18:26:22.574  9920  9933 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-25 18:26:22.591  9920  9933 D DOWNLOADABLE_DB: Local DB version is = 201612050001 SCPM Client DB version is= 201612050001
07-25 18:26:22.591  9920  9933 D DOWNLOADABLE_DB: latest polices have already been updated for BT_A2DP
,07-25 18:26:22.601  9920  9933 D BluetoothSecureManager: getInstant: null
07-25 18:26:22.601  9920  9933 D BluetoothSecureManager: calling getMethod for getService
07-25 18:26:22.601  9920  9933 D BluetoothSecureManager: calling getService
,07-25 18:26:22.603  9920  9933 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@8e238c8
,07-25 18:26:22.604  3697  3777 D BluetoothSecureManagerService: isSecureModeEnabled
,07-25 18:26:22.604  3697  3777 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-25 18:26:22.605  9920  9933 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:22.605  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-25 18:26:22.606  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-25 18:26:22.607  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-25 18:26:22.608  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-25 18:26:22.608  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-25 18:26:22.609  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-25 18:26:22.609  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-25 18:26:22.610  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-25 18:26:22.610  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-25 18:26:22.612  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-25 18:26:22.612  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-25 18:26:22.613  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-25 18:26:22.613  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-25 18:26:22.614  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,07-25 18:26:22.615  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
07-25 18:26:22.615  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
,07-25 18:26:22.616  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-25 18:26:22.617  9920  9933 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:26:22.617  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,07-25 18:26:22.618  9920  9933 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-25 18:26:22.618  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-25 18:26:22.619  9920  9933 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidDevService
,07-25 18:26:22.620  9920  9933 D BluetoothBondStateMachine: make
,07-25 18:26:22.623  9920  9955 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-25 18:26:22.631  9920  9920 I BtGatt.JNI: classInitNative(L979): classInitNative: Success!
07-25 18:26:22.632  9920  9933 I BluetoothAdapterState: Entering PendingCommandState
,07-25 18:26:22.638  9920  9920 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-25 18:26:22.639  9920  9920 D BtGatt.GattService: Received start request. Starting profile...
07-25 18:26:22.639  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:22.639  9920  9920 D BtGatt.GattService: start()
,07-25 18:26:22.640  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:22.640  9920  9920 D BtGatt.AdvertiseManager: advertise manager created
07-25 18:26:22.640  9920  9920 D BtGatt.AdvertiseManager: start
,07-25 18:26:22.650  9920  9920 D BtGatt.ScanManager: start
,07-25 18:26:22.688  9920  9920 D BtGatt.GattService: setGattService(): set to: com.android.bluetooth.gatt.GattService@ce956e3
07-25 18:26:22.688  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:22.688  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:22.688  9920  9920 D BtGatt.GattService: refreshAbusiveScanPackages
,07-25 18:26:22.691  9920  9920 D DOWNLOADABLE_DB: getAbuseScanPackages
,07-25 18:26:22.697  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:22.697  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-25 18:26:22.698  9920  9920 D BtGatt.GattService: refreshAbusiveScanValue()
,07-25 18:26:22.699  9920  9920 D DOWNLOADABLE_DB: getAbuseMaxScanCount
,07-25 18:26:22.705  9920  9920 D DOWNLOADABLE_DB: getAbuseAccumulatedScanTime
,07-25 18:26:22.712  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:22.712  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
07-25 18:26:22.712  9920  9920 D BtGatt.GattService: notifyProfileServiceStateChanged
,07-25 18:26:22.713  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:22.714  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
07-25 18:26:22.714  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:22.714  9920  9920 V BluetoothAdapterState: isTurningOn()=false
07-25 18:26:22.714  9920  9920 V BluetoothAdapterState: isBleTurningOn()=true
,07-25 18:26:22.714  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:22.715  9920  9933 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-25 18:26:22.719  9920  9935 I bt_core_module: module_start_up Starting module "btif_config_module"
07-25 18:26:22.719  9920  9935 I bt_core_module: module_start_up Started module "btif_config_module"
,07-25 18:26:22.719  9920  9935 I bt_core_module: module_start_up Starting module "btsnoop_module"
07-25 18:26:22.719  9920  9935 I bt_core_module: module_start_up Started module "btsnoop_module"
07-25 18:26:22.719  9920  9935 I bt_core_module: module_start_up Starting module "hci_module"
07-25 18:26:22.719  9920  9935 I bt_hci  : start_up
07-25 18:26:22.720  9920  9940 W bt_btif : btif_dm_generic_evt: event=33035
07-25 18:26:22.720  9920  9969 W bt_osi_thread: run_thread: thread id 9969, thread name hci_thread started
,07-25 18:26:22.726  9920  9935 I bt_vendor: alloc value 0xc72f0d35
07-25 18:26:22.726  9920  9935 I bt_vendor: init
07-25 18:26:22.726  9920  9935 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-25 18:26:22.726  9920  9935 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-25 18:26:22.726  9920  9935 I bt_upio : upio_set_bluetooth_power(on: 0)
,07-25 18:26:22.727  9920  9935 I bt_upio : upio_set_bluetooth_power(on: 1)
,07-25 18:26:22.832  9920  9935 D bt_hci  : start_up starting async portion
07-25 18:26:22.833  9920  9969 I bt_hci  : event_finish_startup
,07-25 18:26:22.833  9920  9969 I bt_hci_h4: hal_open
07-25 18:26:22.833  9920  9969 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,07-25 18:26:22.836  9920  9969 I bt_userial_vendor: userial_vendor_open():UART is setup
,07-25 18:26:22.836  9920  9969 I bt_userial_vendor: device fd = 95 open
07-25 18:26:22.837  9920  9972 W bt_osi_thread: run_thread: thread id 9972, thread name hci_single_chann started
07-25 18:26:22.838  9920  9969 E bt_hwcfg: Start CFG HW, HCI reset
,07-25 18:26:22.843  9920  9969 E bt_hwcfg: Read Local Name after HCI reset
,07-25 18:26:22.868  9920  9969 D bt_hwcfg: Chipset BCM4359C0
07-25 18:26:22.868  9920  9969 D bt_hwcfg: Target name = [BCM4359C0]
,07-25 18:26:22.869  9920  9969 I bt_hwcfg: module_type[semco_b90s_c0].
07-25 18:26:22.870  9920  9969 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
07-25 18:26:22.870  9920  9969 E bt_hwcfg: ORG patchram base 0092
07-25 18:26:22.870  9920  9969 E bt_hwcfg: ORG patchram minor 0143
07-25 18:26:22.870  9920  9969 E bt_hwcfg: fw ver (org)92.143
07-25 18:26:22.870  9920  9969 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
,07-25 18:26:22.893  9920  9969 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-25 18:26:22.897  9920  9969 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-25 18:26:23.034  9791  9891 D BluetoothAdapter: enable()
,07-25 18:26:23.045  9920  9931 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-25 18:26:23.046  9920  9931 D AdapterProvider: query
,07-25 18:26:23.068  9920  9931 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@777230c
,07-25 18:26:23.071  9920  9931 D BluetoothAdapterService: updateEvent - already set, update
,07-25 18:26:23.072  9920  9931 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:23.072  9920  9931 D AdapterProvider: update
,07-25 18:26:23.077  9920  9931 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:23.086  3697  4837 W ActivityManager: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-25 18:26:23.087  3697  4837 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-25 18:26:23.087  3697  4837 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:26:23.087  3697  4837 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-25 18:26:23.087  3697  4837 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-25 18:26:23.087  3697  4837 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-25 18:26:23.087  3697  4837 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-25 18:26:23.087  3697  4837 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-25 18:26:23.087  3697  4837 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-25 18:26:23.087  3697  4837 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-25 18:26:23.087  3697  4837 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-25 18:26:23.090  3697  4837 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-25 18:26:23.091  3697  4837 D SecContentProvider: called from com.thaliproject.thalitest
,07-25 18:26:23.238  3697  4463 E Watchdog: !@Sync 9 [25_lip_18_26_23.238]
,07-25 18:26:23.470  9920  9969 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-25 18:26:23.471  9920  9969 I bt_hwcfg: FW Download delta = 627696
07-25 18:26:23.471  9920  9969 D bt_hwcfg: Settlement delay -- 100 ms
07-25 18:26:23.471  9920  9969 I bt_hwcfg: Setting fw settlement delay to 100 
,07-25 18:26:23.597  9791  9891 D BluetoothAdapter: enable()
,07-25 18:26:23.599  9920  9969 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-25 18:26:23.607  9920  9941 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-25 18:26:23.608  9920  9941 D AdapterProvider: query
,07-25 18:26:23.634  9920  9941 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@8d8bf5b
,07-25 18:26:23.635  9920  9941 D BluetoothAdapterService: updateEvent - already set, update
07-25 18:26:23.636  9920  9941 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:23.636  9920  9941 D AdapterProvider: update
,07-25 18:26:23.640  9920  9941 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:23.651  3697  6617 W ActivityManager: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-25 18:26:23.652  3697  6617 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-25 18:26:23.652  3697  6617 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:26:23.652  3697  6617 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-25 18:26:23.652  3697  6617 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-25 18:26:23.652  3697  6617 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-25 18:26:23.652  3697  6617 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-25 18:26:23.652  3697  6617 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-25 18:26:23.652  3697  6617 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-25 18:26:23.652  3697  6617 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-25 18:26:23.653  3697  6617 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-25 18:26:23.657  3697  6617 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-25 18:26:23.658  3697  6617 D SecContentProvider: called from com.thaliproject.thalitest
,07-25 18:26:23.702  9920  9969 I bt_hwcfg: vendor lib fwcfg completed
07-25 18:26:23.702  9920  9969 I bt_vendor: firmware callback
07-25 18:26:23.702  9920  9969 I bt_hci  : firmware_config_callback
07-25 18:26:23.702  9920  9935 I bt_core_module: module_start_up Started module "hci_module"
,07-25 18:26:23.703  9920  9973 W bt_osi_thread: run_thread: thread id 9973, thread name bt_workqueue started
,07-25 18:26:23.704  9920  9973 I bt_core_module: module_init Initializing module "bte_logmsg_module"
07-25 18:26:23.705  9920  9973 I bt_core_module: module_init Initialized module "bte_logmsg_module"
,07-25 18:26:23.705  9920  9940 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-25 18:26:23.707  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9920
,07-25 18:26:23.707  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
07-25 18:26:23.707  9920  9940 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-25 18:26:23.707  9920  9940 W bt_btif : get_secure_storage_key - ss_is_supported = 1
07-25 18:26:23.707  9920  9940 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-25 18:26:23.708  9920  9940 W bt_btif : btif_dm_generic_evt: event=33035
07-25 18:26:23.708  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,07-25 18:26:23.710  9920  9940 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-25 18:26:23.710  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9920
07-25 18:26:23.710  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,07-25 18:26:23.893  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-25 18:26:23.894  9920  9940 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,07-25 18:26:23.896  9920  9974 W bt_osi_thread: run_thread: thread id 9974, thread name module_wrapper started
07-25 18:26:23.897  9920  9974 I bt_core_module: module_start_up Starting module "controller_module"
,07-25 18:26:24.010  9920  9974 I bt_core_module: module_start_up Started module "controller_module"
,07-25 18:26:24.011  9920  9974 W bt_osi_thread: run_thread: thread id 9974, thread name module_wrapper exited
,07-25 18:26:24.039  9920  9940 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,07-25 18:26:24.049  9920  9940 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-25 18:26:24.049  9920  9940 W bt_btif : btif_dm_generic_evt: event=33035
,07-25 18:26:24.053  9920  9940 D bt_hci  : do_postload posting postload work item
07-25 18:26:24.053  9920  9969 I bt_hci  : event_postload
07-25 18:26:24.053  9920  9940 E bt_btif_sock: btif_sock_init: !vhci_init
07-25 18:26:24.053  9920  9969 D bt_hwcfg: hw_sco_config
07-25 18:26:24.054  9920  9969 I bt_hwcfg: I2SPCM config {0x1, 0x0, 0x0, 0x1}
07-25 18:26:24.054  9920  9969 I bt_vendor: sco_config_cb
07-25 18:26:24.054  9920  9969 I bt_hci  : sco_config_callback postload finished.
07-25 18:26:24.054  9920  9940 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:227 ##
,07-25 18:26:24.057  9920  9940 I         : iop_db_open: iop_db_open status 0
,07-25 18:26:24.058  9920  9940 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-25 18:26:24.058  9920  9940 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
07-25 18:26:24.058  9920  9940 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
07-25 18:26:24.058  9920  9940 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Grace SWB-B90S eLNA-0092
07-25 18:26:24.059  9920  9940 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0092.0143_semco.hcd
07-25 18:26:24.059  9920  9940 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
,07-25 18:26:24.060  9920  9940 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,07-25 18:26:24.060  9920  9940 E BluetoothAdapterState: stateChangeCallback : 1
07-25 18:26:24.060  9920  9933 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
,07-25 18:26:24.065  9920  9933 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.065  9920  9969 I bt_hwcfg: SCO PCM configure {0x0, 0x1, 0x0, 0x0, 0x0}
07-25 18:26:24.065  9920  9933 D DOWNLOADABLE_DB: refreshDbFile
07-25 18:26:24.066  9920  9933 D BluetoothServiceJni: refreshDownloadableDbFileNative:
07-25 18:26:24.066  9920  9933 I bt_btif : refreshDownloadableDbFile
,07-25 18:26:24.067  9920  9969 I bt_vendor: low_power_mode_cb
,07-25 18:26:24.072  9920  9933 I         : iop_db_open: iop_db_open status 0
07-25 18:26:24.072  9920  9933 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-25 18:26:24.073  9920  9933 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-25 18:26:24.080  9920  9933 D BluetoothAdapterService: Autoconnection is available 
,07-25 18:26:24.081  9920  9933 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-25 18:26:24.081  9920  9933 I BluetoothAdapterState: Entering BleOnState
,07-25 18:26:24.087  3697  3829 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-25 18:26:24.088  3697  3829 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-25 18:26:24.089  3697  3829 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:24.091  9920  9931 E BluetoothBondStateMachine: initStateMachine
07-25 18:26:24.091  9920  9933 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,07-25 18:26:24.094  9920  9933 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-25 18:26:24.094  9920  9933 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-25 18:26:24.095  3697  3829 D BluetoothManagerService: Turning On/Off, G state: 0, S state: 0, mBLE count: 0, s BLE count: 0
07-25 18:26:24.096  9920  9933 D BluetoothAdapterService: Autoconnection is available 
07-25 18:26:24.096  9920  9933 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
,07-25 18:26:24.099  9920  9933 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:26:24.099  9920  9933 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-25 18:26:24.099  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-25 18:26:24.104  4074  4299 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:24.104  3697  3697 D BluetoothPhoneService: Bluetooth Adapter state : 11
07-25 18:26:24.104  4074  4299 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-25 18:26:24.109  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-25 18:26:24.109  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:24.109  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-25 18:26:24.112  9109  9109 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:26:24.112  9109  9109 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
07-25 18:26:24.115  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:24.129  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-25 18:26:24.140  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-25 18:26:24.141  9920  9920 D HeadsetService: Received start request. Starting profile...
07-25 18:26:24.141  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:24.153  9920  9920 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
07-25 18:26:24.155  9920  9920 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-25 18:26:24.155  9920  9920 D HeadsetStateMachine: make
,07-25 18:26:24.158  9920  9920 E HeadsetStateMachine: # of Max HF connection is 3
07-25 18:26:24.161  9791  9891 D BluetoothAdapter: enable()
07-25 18:26:24.167  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-25 18:26:24.175  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-25 18:26:24.175  9920  9931 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-25 18:26:24.176  9920  9931 D AdapterProvider: query
,07-25 18:26:24.182  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-25 18:26:24.182  9920  9931 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@126070e
,07-25 18:26:24.183  9920  9931 D BluetoothAdapterService: updateEvent - already set, update
,07-25 18:26:24.184  9920  9931 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:24.184  9920  9931 D AdapterProvider: update
,07-25 18:26:24.188  9920  9931 E BluetoothAdapterService: updateEvent - update success 1
07-25 18:26:24.190  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-25 18:26:24.197  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:26:24.197  9920  9933 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-25 18:26:24.197  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,07-25 18:26:24.197  9920  9933 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
,07-25 18:26:24.197  9920  9933 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-25 18:26:24.205  9920  9933 I BluetoothAdapterState: Entering PendingCommandState
,07-25 18:26:24.208  9920  9920 I DualScoManager: Instantiating Dual Sco Manager
07-25 18:26:24.208  9920  9920 I DualScoManager: Set HeadsetServiceHelper
07-25 18:26:24.208  9920  9920 I DualScoManager: setNotificationManager
07-25 18:26:24.208  9920  9920 I DualScoManager: setAudioManager
,07-25 18:26:24.209  9920  9920 D BluetoothAtMessage: createCMTIContentObservers
07-25 18:26:24.210  3697  3776 W ActivityManager: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9791, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-25 18:26:24.211  3697  3776 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,07-25 18:26:24.211  3697  3776 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
07-25 18:26:24.212  3697  3776 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-25 18:26:24.213  3697  3776 D SecContentProvider: called from com.thaliproject.thalitest
,07-25 18:26:24.221  9920  9920 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@c3fe9e6
,07-25 18:26:24.222  9920  9920 I HeadsetService: getHeadsetDB(true) - 44:78:3E:94:4A:XX, 300, 1
07-25 18:26:24.222  9920  9920 I DualScoManager: setSystemAudioInbandSupported : true
,07-25 18:26:24.223  9920  9920 I HeadsetStateMachine: isAutoAppInstalled : false
07-25 18:26:24.223  9920  9920 I HeadsetStateMachine: IBR : true (SysA : 1 / DB : 1)
,07-25 18:26:24.225  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.226  9920  9920 D DOWNLOADABLE_DB: getNotAllowedVoiceRecognitionDeviceList
,07-25 18:26:24.231  9920  9976 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-25 18:26:24.237  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:24.237  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
07-25 18:26:24.237  9920  9920 D HeadsetService: notifyProfileServiceStateChanged
07-25 18:26:24.237  9920  9976 D HeadsetStateMachine: Clear mHeadsetBrsf
07-25 18:26:24.237  9920  9976 D HeadsetStateMachine: map size, before remove : 0
07-25 18:26:24.237  9920  9976 D HeadsetStateMachine: map size, after remove: 0
07-25 18:26:24.238  9920  9976 D HeadsetStateMachine: connectNextConnectingDevice(false) : null
,07-25 18:26:24.241  9920  9920 D A2dpService: Received start request. Starting profile...
07-25 18:26:24.241  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.242  9920  9920 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-25 18:26:24.250  9920  9920 I Avrcp   : No of Audio players :: 1
,07-25 18:26:24.250  9920  9920 I Avrcp   : App Package name is GM
,07-25 18:26:24.253  9920  9969 I bt_hwcfg: SCO PCM data format {0x0, 0x0, 0x3, 0x0, 0x0}
,07-25 18:26:24.255  9920  9969 I bt_hwcfg: sco I2S/PCM config result 0 [0-Success, 1-Fail]
07-25 18:26:24.256  9920  9969 I bt_vendor: sco_audiostate_cb(status: 0)
,07-25 18:26:24.263  9920  9920 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,07-25 18:26:24.265  9920  9920 I Avrcp   : No of Video players :: 2
07-25 18:26:24.265  9920  9920 I Avrcp   : Video App Package name is VP
,07-25 18:26:24.270  9920  9920 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-25 18:26:24.270  9920  9920 I Avrcp   : Video App Package name is others
,07-25 18:26:24.278  9920  9920 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-25 18:26:24.278  9920  9920 I Avrcp   : Add tempPlayer
07-25 18:26:24.278  9920  9920 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-25 18:26:24.279  9920  9920 V Avrcp   : no_of_players : 4
07-25 18:26:24.279  9920  9920 I Avrcp   : Total no of players: 4
07-25 18:26:24.279  9920  9920 V Avrcp   : Samsung player is the 1st player
,07-25 18:26:24.279  9920  9920 D Avrcp   : Compose Browsing Service Candidate
,07-25 18:26:24.281  9920  9920 D Avrcp   : ResolveInfo info ResolveInfo{86ec740 com.android.bluetooth/.a2dpsink.mbs.A2dpMediaBrowserService m=0x108000}
07-25 18:26:24.281  9920  9920 D Avrcp   : ResolveInfo info ResolveInfo{3608679 com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-25 18:26:24.281  9920  9920 D Avrcp   : Initialize Media Controller
,07-25 18:26:24.283  9920  9920 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-25 18:26:24.287  9920  9920 E Avrcp   : getActiveSessions
07-25 18:26:24.287  9920  9920 D Avrcp   : pick active media Controller
07-25 18:26:24.287  9920  9920 D Avrcp   : Get the active Media Controller 
,07-25 18:26:24.288  9920  9920 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-25 18:26:24.289  9920  9920 D A2dpStateMachine: make
,07-25 18:26:24.290  9920  9979 W bt_osi_thread: run_thread: thread id 9979, thread name media_worker started
07-25 18:26:24.291  9920  9920 E bt_btif : warning : media task started media_task_refcnt 1 
07-25 18:26:24.291  9920  9920 W bt_btif : btif_ar_init
07-25 18:26:24.291  9920  9940 W bt_btif : av start inhibit off
,07-25 18:26:24.292  9920  9920 E A2dpStateMachine: isDualPlayEnabled : Dual Play not supported
,07-25 18:26:24.293  9920  9978 D A2dpStateMachine: Enter Disconnected: -2
07-25 18:26:24.295  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:24.295  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-25 18:26:24.295  9920  9920 D A2dpService: notifyProfileServiceStateChanged
,07-25 18:26:24.296  9920  9920 I BluetoothHidServiceJni: classInitNative: succeeds
,07-25 18:26:24.299  9920  9920 D HidService: Received start request. Starting profile...
,07-25 18:26:24.299  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:24.299  9920  9920 D HidService: setHidService(): set to: null
07-25 18:26:24.299  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:24.299  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-25 18:26:24.299  9920  9920 D HidService: notifyProfileServiceStateChanged
,07-25 18:26:24.301  9920  9920 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-25 18:26:24.303  9109  9109 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:26:24.303  9109  9109 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
07-25 18:26:24.304  9920  9920 D HealthService: Received start request. Starting profile...
07-25 18:26:24.304  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.306  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.306  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-25 18:26:24.306  9920  9920 D HealthService: notifyProfileServiceStateChanged
07-25 18:26:24.306  9920  9920 I BluetoothPanServiceJni: classInitNative(L139): succeeds
,07-25 18:26:24.309  9920  9920 D PanService: Received start request. Starting profile...
07-25 18:26:24.309  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.309  9920  9920 D BluetoothPanServiceJni: initializeNative(L144): pan
,07-25 18:26:24.320  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:24.320  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
07-25 18:26:24.320  9920  9920 D PanService: notifyProfileServiceStateChanged
,07-25 18:26:24.333  9920  9920 D BluetoothMapService: Received start request. Starting profile...
07-25 18:26:24.334  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.350  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:24.350  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
07-25 18:26:24.350  9920  9920 D BluetoothMapService: notifyProfileServiceStateChanged
,07-25 18:26:24.354  9920  9920 V SapService: SapBinder()
,07-25 18:26:24.518  9920  9920 D SapService: Received start request. Starting profile...
07-25 18:26:24.519  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.519  9920  9920 V SapService: start()
07-25 18:26:24.519  9920  9920 D SapService: Disable sap : false
,07-25 18:26:24.533  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.533  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
07-25 18:26:24.533  9920  9920 D SapService: notifyProfileServiceStateChanged
07-25 18:26:24.534  9920  9920 D HeadsetStateMachine: Proxy object connected
07-25 18:26:24.536  9920  9920 V BluetoothHidDevServiceJni: classInitNative: done
,07-25 18:26:24.557  9920  9920 D HidDevService: Received start request. Starting profile...
07-25 18:26:24.557  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:24.557  9920  9920 D HidDevService: start()
07-25 18:26:24.557  9920  9920 V BluetoothHidDevServiceJni: initNative enter
07-25 18:26:24.557  9920  9920 V BluetoothHidDevServiceJni: initNative done
07-25 18:26:24.557  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:24.558  9920  9920 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Message sending
07-25 18:26:24.558  9920  9920 D HidDevService: notifyProfileServiceStateChanged
07-25 18:26:24.558  9920  9920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:26:24.558  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:24.558  9920  9976 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-25 18:26:24.558  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
07-25 18:26:24.558  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:24.559  9920  9920 V BluetoothAdapterState: isTurningOn()=true
07-25 18:26:24.559  9920  9920 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:24.559  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:26:24.559  9920  9976 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-25 18:26:24.559  9920  9976 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-25 18:26:24.559  9920  9976 E HeadsetStateMachine: Unknown message: 11
,07-25 18:26:24.570  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:24.570  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
,07-25 18:26:24.570  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:24.570  9920  9920 V BluetoothAdapterState: isTurningOn()=true
07-25 18:26:24.570  9920  9920 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:24.570  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:26:24.572  9920  9920 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-25 18:26:24.572  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:24.572  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-25 18:26:24.572  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:24.572  9920  9920 V BluetoothAdapterState: isTurningOn()=true
07-25 18:26:24.572  9920  9920 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:24.572  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:26:24.572  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
,07-25 18:26:24.572  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
07-25 18:26:24.572  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:24.572  9920  9920 V BluetoothAdapterState: isTurningOn()=true
07-25 18:26:24.573  9920  9920 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:24.573  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:26:24.575  9920  9920 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-25 18:26:24.575  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:24.576  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-25 18:26:24.576  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:24.576  9920  9920 V BluetoothAdapterState: isTurningOn()=true
07-25 18:26:24.576  9920  9920 V BluetoothAdapterState: isBleTurningOn()=false
,07-25 18:26:24.576  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:24.576  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
,07-25 18:26:24.576  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,07-25 18:26:24.576  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:24.576  9920  9920 V BluetoothAdapterState: isTurningOn()=true
07-25 18:26:24.576  9920  9920 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:24.576  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:24.577  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:24.578  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
07-25 18:26:24.578  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:24.578  9920  9920 V BluetoothAdapterState: isTurningOn()=true
07-25 18:26:24.578  9920  9920 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:24.578  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
07-25 18:26:24.578  9920  9920 E BluetoothAdapterService: handleMessage() - Message: 1
07-25 18:26:24.578  9920  9920 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Before synchronized
07-25 18:26:24.578  9920  9920 V BluetoothAdapterState: isTurningOff()=false
07-25 18:26:24.578  9920  9920 V BluetoothAdapterState: isTurningOn()=true
07-25 18:26:24.578  9920  9920 V BluetoothAdapterState: isBleTurningOn()=false
07-25 18:26:24.578  9920  9920 V BluetoothAdapterState: isBleTurningOff()=false
,07-25 18:26:24.581  9920  9920 I BluetoothA2dpServiceJni: Attempting to set busy level
07-25 18:26:24.581  9920  9933 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
,07-25 18:26:24.584  9920  9933 E BluetoothServiceJni: enableBrEdrNative:
07-25 18:26:24.584  9920  9933 I bt_btif : enable_bredr
07-25 18:26:24.585  9920  9940 W bt_btif : btif_dm_generic_evt: event=33035
,07-25 18:26:24.586  9920  9940 W bt_btif : btif_dm_generic_evt: event=33035
,07-25 18:26:24.589  9920  9940 W bt_btif : BTA got event
,07-25 18:26:24.589  9920  9940 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-25 18:26:24.589  9920  9940 W bt_btif : L2CAP - L2CA_Regist: event=33035
07-25 18:26:24.589  9920  9973 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
07-25 18:26:24.595  9920  9940 E BluetoothServiceJni: populateRssiValuesNative
07-25 18:26:24.595  9920  9940 I bt_btif : getModelRssiValues
07-25 18:26:24.595  9920  9940 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,07-25 18:26:24.602  9920  9973 D CODEC_IF_MOD: codec_open: codec_open
07-25 18:26:24.602  9920  9973 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-25 18:26:24.602  9920  9973 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-25 18:26:24.602  9920  9973 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-25 18:26:24.602  9920  9973 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-25 18:26:24.602  9920  9973 D CODEC_IF: codec_if_close: codec_if_close hdl -720523260
07-25 18:26:24.602  9920  9973 D CODEC_IF_MOD: codec_close: codec_close
07-25 18:26:24.602  9920  9973 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-25 18:26:24.602  9920  9973 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-25 18:26:24.602  9920  9973 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,07-25 18:26:24.610  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:24.615  9920  9973 D CODEC_IF_SSHD: codec_open: codec_open
07-25 18:26:24.615  9920  9973 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-25 18:26:24.615  9920  9973 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-25 18:26:24.615  9920  9973 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-25 18:26:24.616  9920  9973 D CODEC_IF: codec_if_close: codec_if_close hdl -995639936
07-25 18:26:24.616  9920  9973 D CODEC_IF_SSHD: codec_close: codec_close
07-25 18:26:24.616  9920  9973 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-25 18:26:24.616  9920  9973 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-25 18:26:24.616  9920  9973 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
,07-25 18:26:24.623  4645  4645 D io_stats: !@   8,0 r 25122 2256336 w 4856 203848 d 661 74020 f 1966 1966 iot 11420 10578 th 470876 0 0 pt 0 inp 0 0 287.161
07-25 18:26:24.624  9920  9940 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:26:24.624  9920  9940 E bt_btif : btif_handle_bluetooth_enable_evt
07-25 18:26:24.624  9920  9940 E bt_btif : ANT+ socket does not initialize.
07-25 18:26:24.626  9920  9973 D CODEC_IF_SSHD2: codec_open: codec_open
07-25 18:26:24.626  9920  9973 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-25 18:26:24.626  9920  9992 W bt_osi_thread: run_thread: thread id 9992, thread name btif_sock started
07-25 18:26:24.627  9920  9940 E BluetoothAdapterState: stateChangeCallback : 17
07-25 18:26:24.627  9920  9940 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
,07-25 18:26:24.627  9920  9933 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
07-25 18:26:24.627  9920  9973 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-25 18:26:24.628  9920  9973 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-25 18:26:24.628  9920  9973 D CODEC_IF: codec_if_close: codec_if_close hdl -967933952
07-25 18:26:24.628  9920  9973 D CODEC_IF_SSHD2: codec_close: codec_close
07-25 18:26:24.628  9920  9973 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
07-25 18:26:24.628  9920  9940 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-25 18:26:24.628  9920  9973 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
07-25 18:26:24.628  9920  9940 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-25 18:26:24.628  9920  9940 E bt_btif : no av control block available at state:3
07-25 18:26:24.628  9920  9940 E bt_btif : no av control block available at state:3
07-25 18:26:24.628  9920  9940 E bt_btif : no av control block available at state:2
07-25 18:26:24.628  9920  9940 E bt_btif : warning : no command pending, ignore ack
07-25 18:26:24.628  9920  9940 E bt_btif : no av control block available at state:3
07-25 18:26:24.628  9920  9940 E bt_btif : no av control block available at state:2
07-25 18:26:24.628  9920  9940 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-25 18:26:24.629  9920  9979 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-25 18:26:24.629  9920  9979 E bt_btif : warning : no command pending, ignore ack
07-25 18:26:24.629  9920  9933 D BluetoothAdapterProperties: ScanMode =  20
07-25 18:26:24.630  9920  9933 D BluetoothAdapterProperties: State =  11
07-25 18:26:24.630  9920  9973 D CODEC_IF_MOD: codec_open: codec_open
07-25 18:26:24.631  9920  9973 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-25 18:26:24.631  9920  9973 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-25 18:26:24.631  9920  9973 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-25 18:26:24.631  9920  9973 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-25 18:26:24.631  9920  9973 D CODEC_IF: codec_if_close: codec_if_close hdl -720523260
07-25 18:26:24.631  9920  9973 D CODEC_IF_MOD: codec_close: codec_close
07-25 18:26:24.631  9920  9973 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-25 18:26:24.631  9920  9973 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-25 18:26:24.631  9920  9973 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
07-25 18:26:24.633  9920  9973 D CODEC_IF_SSHD: codec_open: codec_open
07-25 18:26:24.633  9920  9973 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-25 18:26:24.633  9920  9973 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-25 18:26:24.633  9920  9973 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-25 18:26:24.633  9920  9973 D CODEC_IF: codec_if_close: codec_if_close hdl -995639936
07-25 18:26:24.633  9920  9973 D CODEC_IF_SSHD: codec_close: codec_close
07-25 18:26:24.633  9920  9973 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-25 18:26:24.633  9920  9973 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-25 18:26:24.633  9920  9973 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
07-25 18:26:24.633  3697  3957 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-25 18:26:24.633  4718  9905 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
07-25 18:26:24.634  3697  3957 D SecContentProvider: called from android.uid.bluetooth:1002
07-25 18:26:24.634  9920  9973 D CODEC_IF_SSHD2: codec_open: codec_open
07-25 18:26:24.634  9920  9973 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-25 18:26:24.634  9920  9973 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-25 18:26:24.634  9920  9973 D CODEC_IF: codec_if_op,en: codec module opened (v0.1
07-25 18:26:24.634  9920  9973 D CODEC_IF: codec_if_close: codec_if_close hdl -967933952
07-25 18:26:24.634  9920  9973 D CODEC_IF_SSHD2: codec_close: codec_close
07-25 18:26:24.634  9920  9973 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
07-25 18:26:24.635  9920  9940 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-25 18:26:24.635  9920  9940 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-25 18:26:24.635  9920  9940 E bt_btif : no av control block availabl, Event 0x05
07-25 18:26:24.635  9920  9940 E bt_btif : no av control block available at state:3
07-25 18:26:24.635  9920  9940 E bt_btif : no av control block available at state:2
07-25 18:26:24.635  9920  9940 E bt_btif : warning : no command pending, ignore ack
07-25 18:26:24.635  9920  9979 W bt_btif : BTM_SEC_REG[8sk_aa_stop_tx : tx already stopped, ignore request
07-25 18:26:24.635  9920  9979 E bt_btif : warning : no command pending, ignore ack
07-25 18:26:24.635  9920  9940 E bt_btif : no av control block available at state:3
07-25 18:26:24.635  9920  9940 E bt_btif : no av control block available at state:2
07-25 18:26:24.635  9920  9940 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-25 18:26:24.635  3697  4830 D SecContentProvider: insert(), uri = 2
07-25 18:26:24.636  3697  4830 D SecContentProvider: called from android.uid.bluetooth:1002
07-25 18:26:24.637  9920  9933 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-25 18:26:24.637  9920  9933 D BluetoothAdapterService: [VendorCapa] prevState: 11, newState: 12
07-25 18:26:24.641  9920  9933 I bt_btif : vsc_getvendorcapabilities
07-25 18:26:24.641  9920  9933 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-25 18:26:24.644  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
07-25 18:26:24.651  9920  9940 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-25 18:26:24.657  9791  9791 D BluetoothAdapter: STATE_ON
07-25 18:26:24.659  9920  9940 D BluetoothPanServiceJni: control_state_callback(L64): state:0, local_role:3, ifname:bt-pan
07-25 18:26:24.660  9920  9941 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:26:24.660  9920  9941 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:26:24.660  9791  9791 D BluetoothAdapter: STATE_ON
07-25 18:26:24.661  3697  3829 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:26:24.661  3697  3829 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:26:24.661  9791  9802 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:26:24.661  9791  9802 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:26:24.662  9920  9933 D BluetoothAdapterService: Autoconnection is available 
07-25 18:26:24.662  9920  9933 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-25 18:26:24.662  9791  9791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
07-25 18:26:24.662  9920  9933 D BluetoothAdapterService: starting service from this receiver
07-25 18:26:24.663  4074  4088 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:26:24.663  4074  4088 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:26:24.670  9791  9791 D BluetoothAdapter: STATE_ON
,07-25 18:26:24.671  4718  6856 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:26:24.671  4718  6856 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:26:24.672  4074  4349 D BluetoothMap: onBluetoothStateChange: up=true
07-25 18:26:24.672  9791  9791 D BluetoothAdapter: STATE_ON
,07-25 18:26:24.676  9791  9791 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-25 18:26:24.676  9920  9940 W bt_btif : btif_dm_generic_evt: event=34050
07-25 18:26:24.676  9920  9940 D BluetoothAdapterProperties: [VendorCapa] : mDbfwSupported: 1 , mA2dpLinkFeedbackSupported: 1
07-25 18:26:24.687  9920  9933 I BluetoothAdapterState: Entering OnState
07-25 18:26:24.688  9791  9791 D BluetoothAdapter: STATE_ON
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:24.692  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:26:24.694  4074  4088 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-25 18:26:24.697  4074  4349 D BluetoothSap: onBluetoothStateChange: up=true
07-25 18:26:24.697  4074  4349 D BluetoothSap: Binding service...
07-25 18:26:24.697  9920  9920 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-25 18:26:24.703  9791  9791 D BluetoothAdapter: STATE_ON
,07-25 18:26:24.704  4074  4242 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-25 18:26:24.709  9791  9791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-25 18:26:24.710  4074  4089 D BluetoothPbap: onBluetoothStateChange: up=true
,07-25 18:26:24.716  4074  4088 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-25 18:26:24.718  4074  4074 D BluetoothMap: Proxy object connected
07-25 18:26:24.718  4074  4074 D MapProfile: Bluetooth service connected
07-25 18:26:24.718  4074  4074 D BluetoothMap: getConnectedDevices()
07-25 18:26:24.720  9920  9920 I BluetoothPbapService: Handler(): got msg=1
,07-25 18:26:24.724  9920  9994 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-25 18:26:24.729  4048  4059 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:26:24.729  4048  4059 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:26:24.729  4074  4074 D A2dpProfile: Bluetooth service connected
07-25 18:26:24.730  4074  4242 D BluetoothPan: onBluetoothStateChange on: true
07-25 18:26:24.731  9791  9891 D BluetoothAdapter: STATE_ON
,07-25 18:26:24.735  9920  9994 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:24.735  9920  9994 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:26:24.737  9920  9941 D A2dpStateMachine: getConnectedDevices : size=0
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:24.738  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:26:24.738  4074  4074 D BluetoothSap: Proxy object connected
,07-25 18:26:24.738  4074  4074 D SapProfile: Bluetooth service connected
,07-25 18:26:24.738  4074  4074 D BluetoothPbap: Proxy object connected
07-25 18:26:24.738  4074  4074 D PbapServerProfile: Bluetooth service connected
,07-25 18:26:24.740  9791  9855 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
07-25 18:26:24.740  9920  9994 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-25 18:26:24.743  4074  4074 D BluetoothInputDevice: Proxy object connected
07-25 18:26:24.743  4074  4074 D HidProfile: Bluetooth service connected
,07-25 18:26:24.743  9109  9120 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-25 18:26:24.743  9109  9120 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:26:24.744  4762  4777 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:26:24.744  4762  4777 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-25 18:26:24.745  9109  9121 D BluetoothSap: onBluetoothStateChange: up=true
07-25 18:26:24.745  9109  9121 D BluetoothSap: Binding service...
07-25 18:26:24.746  3697  4893 D WifiService: setWifiEnabled: false pid=9791, uid=10033
07-25 18:26:24.748  3697  4893 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-25 18:26:24.749  3697  4893 D WifiControlHistoryProvider: query
07-25 18:26:24.751  4074  4074 D BluetoothPan: BluetoothPAN Proxy object connected
07-25 18:26:24.751  4074  4074 D PanProfile: Bluetooth service connected
07-25 18:26:24.752  9109  9109 D BluetoothSap: Proxy object connected
07-25 18:26:24.752  9109  9109 D SapProfile: Bluetooth service connected
07-25 18:26:24.752  3697  3829 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-25 18:26:24.754  9400  9411 D BluetoothAdapter: onBluetoothStateChange: up=true
07-25 18:26:24.754  9400  9411 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-25 18:26:24.755  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:24.756  9109  9120 D BluetoothPan: onBluetoothStateChange on: true
07-25 18:26:24.759  9920  9941 D A2dpStateMachine: getConnectedDevices : size=0
07-25 18:26:24.759  3697  4019 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
07-25 18:26:24.760  9109  9109 D BluetoothPan: BluetoothPAN Proxy object connected
07-25 18:26:24.760  9109  9109 D PanProfile: Bluetooth service connected
07-25 18:26:24.762  3697  3697 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-25 18:26:24.763  3697  4893 D WifiNative-wlan0: callSECApiVoid - ID [312]
,07-25 18:26:24.765  4074  4299 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-25 18:26:24.765  3697  4893 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-25 18:26:24.765  3697  3697 D Telecom : SecBluetoothManager : register BluetoothHeadset after STATE_ON : null
07-25 18:26:24.766  3697  3697 D Telecom : SecBluetoothManager : registerBluetoothHeadsetMessageListener fail
07-25 18:26:24.766  3697  3697 D BluetoothPhoneService: Bluetooth Adapter state : 12
07-25 18:26:24.766  4074  4299 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
07-25 18:26:24.766  3697  3697 I BluetoothPhoneService: queryPhoneState
07-25 18:26:24.766  3697  3697 I BluetoothPhoneService: updateHeadsetWithCallState : true
,07-25 18:26:24.770  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
,07-25 18:26:24.770  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:24.770  3697  3697 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-25 18:26:24.771  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,07-25 18:26:24.772  3697  4893 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:24.773  3697  4893 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-25 18:26:24.775  9920  9920 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:24.775  9920  9920 D PanService: BT STATE ON
,07-25 18:26:24.775  9920  9920 D EnhancedTetheringManager: EnhancedTetheringManager()
07-25 18:26:24.775  9920  9920 D EnhancedTetheringManager: start
07-25 18:26:24.776  3697  4893 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-25 18:26:24.777  3697  3929 D SecContentProvider: insert(), uri = 2
07-25 18:26:24.778  3697  3929 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:24.778  3697  3929 D SecContentProvider: insert(), uri = 2
07-25 18:26:24.779  3697  3929 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:24.780  3697  3931 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-25 18:26:24.782  3697  3931 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@d2553c8
,07-25 18:26:24.783  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183405, SetElapsed=748485, nowELAPSED=287321
07-25 18:26:24.783  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170725T182700, SetElapsed=322539, nowELAPSED=287322
07-25 18:26:24.784  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:24.787  9920  9920 D ETMLeHelper: ETMLeHelper()
07-25 18:26:24.787  9920  9920 D ETMLeHelper: initTetherAdv
07-25 18:26:24.788  9109  9109 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:24.788  9109  9109 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-25 18:26:24.788  3697  3931 D WifiStateMachine: isFindLocationId() - Location Id : 1
,07-25 18:26:24.788  3697  3931 D WifiStateMachine: ConnectedState - exit() - stopLearning id : 1
07-25 18:26:24.789  3697  3931 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
,07-25 18:26:24.790  3697  3931 D SLocation: system
07-25 18:26:24.790  3697  3931 D SLocation: stopLearning ID = 1
07-25 18:26:24.790  3697  3931 D SLocation: setLearningStatus ID = 1 / status = false
07-25 18:26:24.791  3697  3931 D SecContentProvider: insert(), uri = 2
07-25 18:26:24.792  3697  3931 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:24.792  3697  3931 D WifiStateMachine: Wifi got Disconnected in connectedstate, Send provisioning intent mAutoRoamingfalse
07-25 18:26:24.792  9109  9109 E BluetoothEventManager: unregisterProfileIntentReceiver :: mProfileConnectionReceiver was not registered.
07-25 18:26:24.793  9109  9109 D LocalBluetoothProfileManager: Adding local A2DP profile
07-25 18:26:24.793  4074  4299 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
,07-25 18:26:24.793  4074  4299 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
,07-25 18:26:24.793  4074  4299 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,07-25 18:26:24.793  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiStateMachine$ConnectedState.exit:11809 com.android.internal.util.StateMachine$SmHandler.invokeExitMethods:1009 com.android.internal.util.StateMachine$SmHandler.performTransitions:865 com.android.internal.util.StateMachine$SmHandler.handleMessage:809 
07-25 18:26:24.793  4074  4299 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
07-25 18:26:24.793  4074  4299 W LocalBluetoothProfileManager: updateLocalProfiles :: Spp profile was created already 
07-25 18:26:24.795  3697  3931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-25 18:26:24.795  3697  3936 D DhcpClient: doQuit
07-25 18:26:24.795  3697  3936 D ApfFilter: (wlan0): shutting down
07-25 18:26:24.795  3697  5107 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@29cfc60
07-25 18:26:24.796  3697  5107 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@ad159de
07-25 18:26:24.797  9920  9920 D BluetoothAdapter: STATE_ON
07-25 18:26:24.798  3697  5107 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@e457e8c
07-25 18:26:24.798  3697  3926 D WifiP2pService: InactiveState{ what=143375 }
07-25 18:26:24.799  3697  3926 D WifiP2pService: P2pEnabledState{ what=143375 }
07-25 18:26:24.799  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:24.799  3697  4019 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-25 18:26:24.800  3697  3964 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-25 18:26:24.800  3697  3964 D ConnectivityService: ignoring duplicate network state non-change
07-25 18:26:24.800  9920  9920 D BluetoothAdapter: STATE_ON
,07-25 18:26:24.800  3697  3964 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 12
07-25 18:26:24.801  3697  3964 V NetworkStats: updateIfacesLocked()
07-25 18:26:24.801  3697  3964 V NetworkStats: performPollLocked(flags=0x1)
07-25 18:26:24.801  3697  3964 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:24.803  3697  3931 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-25 18:26:24.803  9920  9920 D BluetoothAdapter: STATE_ON
07-25 18:26:24.804  3697  3697 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-25 18:26:24.805  3697  3931 I WifiConnectivityManager: Set WiFi disabled
07-25 18:26:24.806  3697  3931 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@bd5993d
07-25 18:26:24.806  3697  3931 I WifiStateMachine: deinitGeofence
07-25 18:26:24.806  9920  9920 D BluetoothAdapter: isSecureModeEnabled
07-25 18:26:24.806  9920  9920 D BtConfig.SecureMode: isSecureModeOn:false
,07-25 18:26:24.808  9920  9920 D ETMLeHelper: initTetherScan
07-25 18:26:24.809  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-25 18:26:24.809  9920  9920 D BluetoothAdapter: STATE_ON
07-25 18:26:24.809  3697  3697 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
07-25 18:26:24.810  9920  9920 D BluetoothAdapter: STATE_ON
,07-25 18:26:24.813  9109  9109 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-25 18:26:24.813  9920  9920 D BluetoothMapUtils: [RCS] imsConfigCscFeatures : , enableCpmFeature : false
07-25 18:26:24.813  9920  9920 D BluetoothMapUtils: mRcsSupported : false
,07-25 18:26:24.814  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,07-25 18:26:24.814  3697  3964 V NetworkStats: performPollLocked() took 13ms
07-25 18:26:24.815  3697  3960 I WifiHs20Service: Message received 5007
,07-25 18:26:24.815  3697  3964 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:26:24.820  4048  4048 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-25 18:26:24.824  3697  3931 D SLocation: stopGeofence ID = 1
,07-25 18:26:24.825  9109  9109 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-25 18:26:24.825  3697  4019 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-25 18:26:24.826  3697  6617 D MountService: getExternalStorageMountMode : 1
07-25 18:26:24.826  3697  6617 D MountService: getExternalStorageMountMode : 3
07-25 18:26:24.826  3697  6617 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
07-25 18:26:24.828  3697  3964 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-25 18:26:24.828  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.828  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:24.828  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:24.828  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:24.829  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:24.829  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.829  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.829  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.829  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.829  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.830  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.830  3697  4018 D DnsEventListenerService: Logging 27 results for netId 502
07-25 18:26:24.831  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.831  4529  4616 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [false]
07-25 18:26:24.831  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.832  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.832  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.832  9109  9109 E BluetoothHeadset: BTStateChangeCB is registed
07-25 18:26:24.833  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:24.833  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:24.834  4529  4616 D GeolocationController: WIFI : onLost
07-25 18:26:24.834  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.834  4529  4618 D PdnController: handleMessage: what 106
0,7-25 18:26:24.834  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.834  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:24.834  4529  4618 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [false]
07-25 18:26:24.834  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:24.835  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:24.835  3697  3964 D ConnectivityService: sending notification LOST for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:24.835  4529  4618 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [false]
07-25 18:26:24.835  3697  5103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:26:24.835  3697  3964 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.835  4529  4618 D ResipRegiMgr: handleMessage(): 3
07-25 18:26:24.835  4529  4618 D RegiMgrBase: handleMessage: what 3
07-25 18:26:24.835  3697  5103 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: unregister CaptivePortalReceiver
07-25 18:26:24.836  3697  4030 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.836  3697  4030 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-25 18:26:24.836  3697  4030 D Ethernet: evalRequest
07-25 18:26:24.836  3697  4030 D Ethernet:   done
07-25 18:26:24.840  9109  9109 D BluetoothMap: Create BluetoothMap proxy object
07-25 18:26:24.843  3697  3829 D EntConnectivity: Not allowed due to - mEnabled false
07-25 18:26:24.843  4048  4048 D PhoneSwitcherNetworkRequstListener: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.844  4048  4048 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-25 18:26:24.844  4048  4048 D PhoneSwitcherNetworkRequstListener: evalRequest
07-25 18:26:24.844  4048  4048 D PhoneSwitcherNetworkRequstListener:   done
07-25 18:26:24.844  3697  3926 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.844  3697  3926 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:24.844  3697  3926 D WIFI_P2P: evalRequest
07-25 18:26:24.844  3697  3926 D WIFI_P2P:   done
07-25 18:26:24.856 10001 10001 E Zygote  : v2
07-25 18:26:24.856 10001 10001 I libpersona: KNOX_SDCARD checking this for 10049
07-25 18:26:24.856 10001 10001 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:24.856 10001 10001 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:26:24.857 10001 10001 E Zygote  : accessInfo : 64
07-25 18:26:24.857 10001 10001 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:26:24.857 10001 10001 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
07-25 18:26:24.861  3697  5107 D DhcpClient: onQuitting
07-25 18:26:24.864  3697  6617 I ActivityManager: Start proc 10001:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
07-25 18:26:24.865  3238  3238 E audit   : type=1320 audit(1500999984.851:540): 
07-25 18:26:24.868 10001 10001 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-25 18:26:24.870 10001 10001 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,07-25 18:26:24.872  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:24.872  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:24.872  3697  3697 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-25 18:26:24.873  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:24.881  9109  9109 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-25 18:26:24.883  3238  3238 E audit   : type=1320 audit(1500999984.871:541): 
07-25 18:26:24.884  3298  3795 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-25 18:26:24.891  9109  9109 D LocalBluetoothProfileManager: Adding local Spp profile
07-25 18:26:24.897  3238  3238 E audit   : type=1320 audit(1500999984.881:542): 
07-25 18:26:24.901  9109  9109 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-25 18:26:24.910  3238  3238 E audit   : type=1320 audit(1500999984.891:543): 
,07-25 18:26:24.910  3697  3931 E SLocation: pendingIntent set to null
07-25 18:26:24.910  3697  3931 D SLocation: setStatus ID = 1 / status = 0
07-25 18:26:24.911  3697  3931 D SLocation: updateSession : trigger = false
07-25 18:26:24.911  3697  3931 D SLocation: updateSession : mSessionStatus = 0
07-25 18:26:24.911  3697  3931 D WifiStateMachine:  stopGeofence() - id : 1
07-25 18:26:24.911  3298  3795 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-25 18:26:24.911  3697  3931 D wifi    : android_net_wifi_reset_alert_handler = 0x7a21ee1260
07-25 18:26:24.912  3697  3931 E WifiHAL : failed to request reset; result = -95
07-25 18:26:24.912  3697  3931 D wifi    : android_net_wifi_reset_log_handler = 0x7a21ee1260
07-25 18:26:24.912  3697  3931 I WifiHAL : Failed to remove command 1: 0x0
07-25 18:26:24.912  3697  3931 D WifiHAL : Success to clear alerthandler
07-25 18:26:24.912  3697  4491 D SLocation: Session stopped
07-25 18:26:24.912  3697  4491 D SLocation: triggerAlarm
07-25 18:26:24.912  3697  4491 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / op:PendingIntent{8bf2622: PendingIntentRecord{74dc8b3 android broadcastIntent}}
07-25 18:26:24.913  3697  4491 D SLocation: All alarm stopped
07-25 18:26:24.913 10001 10001 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:24.914 10001 10001 D ActivityThread: Added TimaKeyStore provider
07-25 18:26:24.914  3697  3931 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-25 18:26:24.914  3697  3964 D ConnectivityService: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
07-25 18:26:24.914  3697  3931 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.914  3697  3931 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:24.914  3697  3931 D WIFI    : evalRequest
07-25 18:26:24.914  3697  3931 D WIFI    :   needNetworkFor
07-25 18:26:24.914  3697  3931 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:24.914  3697  3931 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:24.914  3697  3931 D WIFI_UT : evalRequest
07-25 18:26:24.914  3697  3931 D WIFI_UT :   done
07-25 18:26:24.917  3697  3964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-25 18:26:24.919  9109  9109 D A2dpProfile: Bluetooth service connected
07-25 18:26:24.920  3697  3926 D WifiP2pService: InactiveState{ what=131204 }
07-25 18:26:24.920  3697  3926 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-25 18:26:24.929  3298  3795 D CommandListener: Clearing all IP addresses on wlan0
07-25 18:26:24.930  3697  3829 D EntConnectivity: Not allowed due to - mEnabled false
,07-25 18:26:24.932  3697  3961 I WifiScanningService: wifi driver unloaded
07-25 18:26:24.932  3697  3697 D RttService: SCAN_AVAILABLE : 1
07-25 18:26:24.933  3697  3962 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-25 18:26:24.933  3697  3961 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.scanner.SupplicantWifiScannerImpl$2@cb72e70
,07-25 18:26:24.937  3697 10017 I ApplicationPolicy: updateDataUsageMap
07-25 18:26:24.937  4293  4293 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
07-25 18:26:24.937  4293  4293 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
07-25 18:26:24.941  3697  3926 D WifiP2pService: sending p2p connection changed broadcast: FAILED
07-25 18:26:24.944  3697  3697 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-25 18:26:24.944  3697  3697 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = true
07-25 18:26:24.944  3697  3697 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-25 18:26:24.944  3697  3697 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-25 18:26:24.944  3697  3919 I KnoxVpnEngineService: vpn handle : Message received
07-25 18:26:24.944  3697  3919 I KnoxVpnEngineService: vpn handle : Message received
07-25 18:26:24.945  3697  3919 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = true
07-25 18:26:24.946  3697  3918 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-25 18:26:24.946  3697  3918 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-25 18:26:24.947  3697  3697 D Tethering: Tethering got CONNECTIVITY_ACTION
07-25 18:26:24.948  3697  3965 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-25 18:26:24.948  3697  3965 D Tethering: MasterInitialState.processMessage what=327683
07-25 18:26:24.952  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-25 18:26:24.961  5224  5224 I CastMediaRouteProvider: Network connectivity changed
,07-25 18:26:24.963  3697  3922 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
07-25 18:26:24.963  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:24.963  5069  5069 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF50EC62EA054297E5426D68FE61E03F7CB63D06B4FC0A78A26416AA7E048F840EFBC21D921AABB61599A4C4654ABE1206043CF566A086A1148D0FC76C5AA3DFC0]}
07-25 18:26:24.963  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:26:24.963  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:24.963  3697  3922 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-25 18:26:24.963  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:24.964  5069  5069 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF006507037EF1FC27CFA959C112FA7F2D870458BE3926C900C8D0246DBBD82F5FF9735DB64481160EAC5657CBD115B580]}
07-25 18:26:24.965  3697  3922 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
,07-25 18:26:24.974  9305  9305 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-25 18:26:24.974  9305  9305 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
,07-25 18:26:24.977  9366  9366 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@53a3a21 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-25 18:26:24.980  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-25 18:26:24.986  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-25 18:26:24.987  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-25 18:26:25.003  3298  3787 I Netd    : Destroyed 15 sockets on 192.168.1.105 in 1.9 ms
07-25 18:26:25.003  4718  6885 V NativeCrypto: Read error: ssl=0x7a2a11d080: I/O error during system call, Software caused connection abort
,07-25 18:26:25.013  4074  4299 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-25 18:26:25.014  3238  3238 E audit   : type=1320 audit(1500999985.001:544): 
07-25 18:26:25.015  3697  3697 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-25 18:26:25.015  3697  3697 V MARsPolicyManager: DataConnection: false
07-25 18:26:25.015  3697  4544 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
07-25 18:26:25.015  3697  4491 D SLocation: checkWifiInfo
07-25 18:26:25.015  3697  4491 W SLocation: No Active Data Connection
07-25 18:26:25.015  3697  4491 W SLocation: No Active Data Connection
07-25 18:26:25.017  4718  6885 V NativeCrypto: SSL shutdown failed: ssl=0x7a2a11d080: I/O error during system call, Broken pipe
07-25 18:26:25.019  4823  4823 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-25 18:26:25.023  3697  4045 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-25 18:26:25.025  9791  9791 D BluetoothAdapter: STATE_ON
07-25 18:26:25.026  3238  3238 E audit   : type=1320 audit(1500999985.011:545): 
07-25 18:26:25.028  3697  4045 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-25 18:26:25.031  9920  9932 D A2dpStateMachine: getConnectedDevices : size=0
07-25 18:26:25.031  9109  9109 D BluetoothMap: Proxy object connected
07-25 18:26:25.032  9109  9109 D MapProfile: Bluetooth service connected
07-25 18:26:25.032  9109  9109 D BluetoothMap: getConnectedDevices()
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:26:25.035  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-25 18:26:25.038  9305  9305 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
07-25 18:26:25.038  9305  9305 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
07-25 18:26:25.038  9791  9791 D BluetoothAdapter: STATE_ON
07-25 18:26:25.038  9305  9305 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-25 18:26:25.040  9366  9366 I NetworkConnectivity: Network state changed: null
07-25 18:26:25.041  9791  9791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
07-25 18:26:25.042  3697  3830 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
07-25 18:26:25.050  3697 10018 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{7523d0f: PendingIntentRecord{d1a0671 com.google.android.gms broadcastIntent}}
07-25 18:26:25.051  3697 10018 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T184156, SetElapsed=1219465, nowELAPSED=287590
07-25 18:26:25.052  4718  6885 E GCM     : Wifi connection closed with errorCode 20
07-25 18:26:25.059  9366  9366 I NetworkPolicyMonitor: Download-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
07-25 18:26:25.059  3298  3795 E Netd    : netlink response contains error (No such file or directory)
,07-25 18:26:25.075  3697  3926 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-25 18:26:25.077  3697  3830 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-25 18:26:25.077  3697  3830 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-25 18:26:25.077  3697  3830 D WifiDisplayController: disconnect
07-25 18:26:25.077  3697  3830 D WifiDisplayAdapter: onFeatureStateChanged empty
07-25 18:26:25.077 10001 10001 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
,07-25 18:26:25.077  9109  9109 D BluetoothPbap: Proxy object connected
07-25 18:26:25.078  3697  3830 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-25 18:26:25.078  9109  9109 D PbapServerProfile: Bluetooth service connected
07-25 18:26:25.078  9109  9109 D BluetoothInputDevice: Proxy object connected
07-25 18:26:25.079  9366  9366 I NetworkPolicyMonitor: Stream-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
07-25 18:26:25.079  9109  9109 D HidProfile: Bluetooth service connected
07-25 18:26:25.083  3697  3926 D SecContentProvider: insert(), uri = 2
07-25 18:26:25.085  3697  3964 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED
07-25 18:26:25.086  3697  3926 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:25.087  3697  3926 D WifiP2pService: P2pDisablingState
07-25 18:26:25.087  3697  3926 D WifiP2pService: P2pDisablingState{ what=147458 }
07-25 18:26:25.088  3697  3926 D WifiP2pService: p2p socket connection lost
07-25 18:26:25.088  3697  3926 D SecContentProvider: insert(), uri = 2
07-25 18:26:25.090 10001 10001 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-25 18:26:25.091  3697  3926 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:25.091  3697  3931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-25 18:26:25.091  3697  3926 D WifiP2pService: P2pDisabledState
07-25 18:26:25.094  3697  3926 D WifiP2pService: P2pDisabledState{ what=143375 }
07-25 18:26:25.095  3697  3926 D WifiP2pService: DefaultState{ what=143375 }
07-25 18:26:25.096  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:25.096  3697  4019 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-25 18:26:25.099  3697  3830 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: false, roaming: false, metered: false]
07-25 18:26:25.099  3697  3964 D ConnectivityService: ignoring duplicate network state non-change
07-25 18:26:25.099  5224  6804 W MdnsClient_Cast: Multicast lock held. Releasing. Subtypes:"805741C9"
07-25 18:26:25.100  9366  9366 I DevicePlayback: Got network change: mobile=falsewifi=false
07-25 18:26:25.100  9366  9366 I DevicePlayback: Disabling Woodstock in 200000ms
,07-25 18:26:25.108  3697  3931 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-25 18:26:25.109  5224  6804 W MdnsClient: unicast receiver thread is already dead.
07-25 18:26:25.110  4293  4293 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-25 18:26:25.111  3697  3931 D SecContentProvider: insert(), uri = 2
07-25 18:26:25.112  3697  3697 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-25 18:26:25.112  3697  3931 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:25.114  3298  3790 D EnterpriseController: netId is 0
07-25 18:26:25.114  3298  3790 D Netd    : getNetworkForDns: using netid 0 for uid 10001
07-25 18:26:25.114  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-25 18:26:25.117  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-25 18:26:25.117  3697  4837 D RCPManagerService: exchangeData() failure , invalid userId
,07-25 18:26:25.118  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-25 18:26:25.118  3697  3960 I WifiHs20Service: Message received 5007
,07-25 18:26:25.123  4048  4048 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-25 18:26:25.124  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-25 18:26:25.127  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:26:25.130 10001 10001 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
,07-25 18:26:25.131 10001 10001 I QBNRClientHelper: init SyncClientHelper : Email
07-25 18:26:25.131 10001 10001 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : EMAILFOLDER, 55LAYJm0O2, com.samsung.android.email.provider.service.sCloudBNRService2
,07-25 18:26:25.131 10001 10001 I QBNRClientHelper: init SyncClientHelper : EMAILFOLDER
07-25 18:26:25.133  5142 10023 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
07-25 18:26:25.133  5142 10023 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-25 18:26:25.133  5142 10023 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-25 18:26:25.133  5142 10023 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-25 18:26:25.133  5142 10023 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-25 18:26:25.133  5142 10023 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-25 18:26:25.133  5142 10023 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-25 18:26:25.133  5142 10023 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-25 18:26:25.133  5142 10023 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-25 18:26:25.133  5142 10023 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-25 18:26:25.133  5142 10023 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-25 18:26:25.133  5142 10023 E         : 	at java.lang.Thread.run(Thread.java:762)
07-25 18:26:25.133  5142 10023 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-25 18:26:25.133  5142 10023 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-25 18:26:25.133  5142 10023 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-25 18:26:25.133  5142 10023 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-25 18:26:25.133  5142 10023 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-25 18:26:25.133  5142 10023 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-25 18:26:25.133  5142 10023 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-25 18:26:25.133  5142 10023 E         : 	... 9 more
07-25 18:26:25.133  5142 10023 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-25 18:26:25.133  5142 10023 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-25, 18:26:25.133  5142 10023 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-25 18:26:25.133  5142 10023 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-25 18:26:25.133  5142 10023 E         : 	... 26 more
07-25 18:26:25.133  5142 10023 E         : 
,07-25 18:26:25.136  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-25 18:26:25.139  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-25 18:26:25.139  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-25 18:26:25.139  3697  4019 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-25 18:26:25.139  3697  3697 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-25 18:26:25.140  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:25.140  3697  3960 I WifiHs20Service: Message received 5011
07-25 18:26:25.140  3697  4491 D SLocation: checkWifiInfo
07-25 18:26:25.140  3697  4491 D SLocation: wifi available : false
07-25 18:26:25.140  3697  4491 D SLocation: Session stopped
,07-25 18:26:25.140  3697  4491 D SLocation: triggerAlarm
07-25 18:26:25.140  3697  4491 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / op:PendingIntent{8bf2622: PendingIntentRecord{74dc8b3 android broadcastIntent}}
07-25 18:26:25.140  3697  4491 D SLocation: All alarm stopped
07-25 18:26:25.141  3298  3787 D Netd    : Iface p2p0 link up
07-25 18:26:25.144  9791  9791 D BluetoothAdapter: STATE_ON
07-25 18:26:25.144  3697  3828 D Tethering: interfaceLinkStateChanged p2p0, true
07-25 18:26:25.144  3697  3828 D Tethering: interfaceStatusChanged p2p0, true
07-25 18:26:25.146  5142 10023 E         : Unable to fetch advertisement frequency.
07-25 18:26:25.146  5142 10023 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-25 18:26:25.146  5142 10023 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-25 18:26:25.146  5142 10023 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-25 18:26:25.146  5142 10023 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-25 18:26:25.146  5142 10023 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-25 18:26:25.146  5142 10023 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-25 18:26:25.146  5142 10023 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-25 18:26:25.146  5142 10023 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-25 18:26:25.146  5142 10023 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-25 18:26:25.146  5142 10023 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-25 18:26:25.146  5142 10023 E         : 	at java.lang.Thread.run(Thread.java:762)
07-25 18:26:25.146  5142 10023 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-25 18:26:25.146  5142 10023 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-25 18:26:25.146  5142 10023 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-25 18:26:25.146  5142 10023 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-25 18:26:25.146  5142 10023 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-25 18:26:25.146  5142 10023 E         : 	at retrofit.client.OkClient.execute(OkClient.,java:53)
07-25 18:26:25.146  5142 10023 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-25 18:26:25.146  5142 10023 E         : 	... 9 more
07-25 18:26:25.146  5142 10023 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-25 18:26:25.146  5142 10023 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-25 18:26:25.146  5142 10023 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-25 18:26:25.146  5142 10023 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-25 18:26:25.146  5142 10023 E         : 	... 26 more
07-25 18:26:25.146  5142 10023 E         : 
07-25 18:26:25.146  3697  3697 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-25 18:26:25.147  3697  4045 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:26:25.148  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-25 18:26:25.150  3697  4045 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-25 18:26:25.157  9109  9109 D DockEventReceiver: finishStartingService: stopping service
,07-25 18:26:25.157  9791  9791 D BluetoothAdapter: STATE_ON
,07-25 18:26:25.158  3697  3776 D RCPManagerService: exchangeData() failure , invalid userId
,07-25 18:26:25.160  9791  9791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-25 18:26:25.161 10001 10029 D skia    : ---- fAsset->read(8192) returned 0
,07-25 18:26:25.162 10001 10029 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-25 18:26:25.163 10001 10001 D SamsungAnalytics:1.8.25: cf feature is supported
,07-25 18:26:25.165 10001 10001 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
,07-25 18:26:25.166  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:25.166  3697  6550 D MountService: getExternalStorageMountMode : 1
07-25 18:26:25.166 10001 10029 D skia    : ---- fAsset->read(8192) returned 0
07-25 18:26:25.166 10001 10029 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-25 18:26:25.166  3697  6550 D MountService: getExternalStorageMountMode : 3
07-25 18:26:25.166  3697  6550 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
07-25 18:26:25.167 10001 10029 D skia    : ---- fAsset->read(8192) returned 0
07-25 18:26:25.167 10001 10029 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-25 18:26:25.182 10033 10033 E Zygote  : v2
,07-25 18:26:25.182 10033 10033 I libpersona: KNOX_SDCARD checking this for 10049
07-25 18:26:25.182 10033 10033 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:25.182 10033 10033 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:26:25.182 10033 10033 E Zygote  : accessInfo : 64
07-25 18:26:25.182 10033 10033 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:26:25.182 10033 10033 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
07-25 18:26:25.183  3697  6550 I ActivityManager: Start proc 10033:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,07-25 18:26:25.186 10033 10033 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:25.187 10033 10033 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
07-25 18:26:25.187  4074  4217 D vol.MediaSessions: onQueueChanged com.google.android.music []
,07-25 18:26:25.200 10033 10033 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:26:25.201 10033 10033 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:25.202  3697 10019 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,07-25 18:26:25.211  4293  4293 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-25 18:26:25.213  4293  4293 E wpa_supplicant: can't get BSS information
07-25 18:26:25.213  4293  4293 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.E6.C2 reason=3 locally_generated=1
,07-25 18:26:25.218  3298  3787 D Netd    : Iface wlan0 link up
,07-25 18:26:25.218  4293  4293 I wpa_supplicant: CTRL_IFACE: Detach monitor that cannot receive messages: /data/misc/wifi/sockets/wpa_ctrl_3697-2\x00
,07-25 18:26:25.219  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:25.219  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:26:25.225 10033 10033 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
,07-25 18:26:25.229  9109  9109 D HeadsetProfile: Bluetooth service connected
,07-25 18:26:25.229  9920  9920 D BluetoothUtils: readSalesCode :: sales code is XEO
07-25 18:26:25.231  9920  9920 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:25.231  9920  9920 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:25.232  4074  4074 D HeadsetProfile: Bluetooth service connected
,07-25 18:26:25.233  3697  3697 I BluetoothPhoneService: updateHeadsetWithCallState : true
,07-25 18:26:25.235 10033 10033 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:25.242  9920  9976 D HeadsetStateMachine: Disconnected process message: 9, size: 0
07-25 18:26:25.242  9920  9976 D A2dpSinkService: getA2dpSinkService(): service is NULL
07-25 18:26:25.242  9920  9976 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-25 18:26:25.243  3697  3697 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.bluetooth.SecBluetoothMessageListener@f7f9b2b
07-25 18:26:25.243  3697  3697 D BluetoothHeadset: registerMessageListener
,07-25 18:26:25.246  9920  9920 D BluetoothUtils: readSalesCode :: sales code is XEO
07-25 18:26:25.246  3284  3284 D audio_hw_primary: adev_set_parameters: enter: kvpairs: A2dpSuspended=false
07-25 18:26:25.247  9920  9976 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-25 18:26:25.249  9920  9983 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,07-25 18:26:25.254  9109  9109 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-25 18:26:25.254  9109  9109 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,07-25 18:26:25.260  9920  9997 D HeadsetService: registerMessageListener
,07-25 18:26:25.263  9920  9997 D HeadsetService: registerMessageListener
07-25 18:26:25.264  9920  9983 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:25.264  9920  9983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-25 18:26:25.264  9920  9976 D HeadsetStateMachine: Disconnected process message: 70, size: 0
07-25 18:26:25.264  9920  9976 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@fa419f6
07-25 18:26:25.265  3697  3697 I Telecom : SecBluetoothManager : register MessageListener
,07-25 18:26:25.273  9920 10050 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:25.273  9920 10050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:26:25.276  9920  9920 V BtOppService: isOwner == true
,07-25 18:26:25.283  9920 10050 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-25 18:26:25.283  9920 10050 D BluetoothSdpJni: SDP Create record success - handle: 0
07-25 18:26:25.286  9791  9891 D BluetoothAdapter: STATE_ON
,07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:26:25.293  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-25 18:26:25.293  3697  3697 I Telecom : SecBluetoothManager : not single connected gear
,07-25 18:26:25.295  9920  9983 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:25.295  9920  9983 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-25 18:26:25.297  9791  9855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:25.299  3697  3944 D WifiService: setWifiEnabled: true pid=9791, uid=10033
07-25 18:26:25.304  3697  3944 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-25 18:26:25.305  3697  3944 D WifiControlHistoryProvider: query
07-25 18:26:25.307  9920  9983 D ObexServerSockets: Succeed to create listening sockets 
07-25 18:26:25.307  3697  3697 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-25 18:26:25.307  9920  9983 D ObexServerSockets: startAccept()
07-25 18:26:25.307  3697  4568 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
07-25 18:26:25.308  3697  4568 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
07-25 18:26:25.311  3697  3948 D RCPManagerService: exchangeData() failure , invalid userId
07-25 18:26:25.311  4293  4293 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
07-25 18:26:25.312  9920  9983 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-25 18:26:25.312  9920  9983 D BluetoothSdpJni: SDP Create record success - handle: 1
,07-25 18:26:25.315  9920 10054 D ObexServerSockets: Accepting socket connection for masId0
07-25 18:26:25.316  9920 10053 D ObexServerSockets: Accepting socket connection for masId0
07-25 18:26:25.318 10033 10033 D SamsungAnalytics:1.8.25: cf feature is supported
,07-25 18:26:25.328  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:25.329  3697  4568 I Telecom : SecBluetoothManager : not single connected gear
,07-25 18:26:25.329  3697  4568 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACo_0
07-25 18:26:25.330 10033 10051 D skia    : ---- fAsset->read(8192) returned 0
07-25 18:26:25.330 10033 10051 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-25 18:26:25.331  3697  4838 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-25 18:26:25.332  3697  4838 D SecContentProvider: called from android.uid.bluetooth:1002
07-25 18:26:25.334  3697  3944 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-25 18:26:25.336  3697  3944 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:25.337  3697  3944 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-25 18:26:25.338 10033 10033 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
07-25 18:26:25.339 10033 10051 D skia    : ---- fAsset->read(8192) returned 0
,07-25 18:26:25.339 10033 10051 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-25 18:26:25.341 10033 10051 D skia    : ---- fAsset->read(8192) returned 0
07-25 18:26:25.341 10033 10051 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-25 18:26:25.342  3697  3944 I WifiService: Wi-Fi Sharing settings has not been accessed
07-25 18:26:25.343  3697  3944 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-25 18:26:25.344  3697  3929 D SecContentProvider: insert(), uri = 2
07-25 18:26:25.345  3697  3929 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:25.345  3697  3929 D SecContentProvider: insert(), uri = 2
07-25 18:26:25.346  3697  3929 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:25.351  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:26:25.352  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:26:25.352  4293  4293 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-25 18:26:25.354  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:25.354  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:26:25.355  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:25.355  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:26:25.356  9920 10062 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:25.356  9920 10062 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-25 18:26:25.359  9920 10062 I BtOppRfcommListener: Accept thread started.
07-25 18:26:25.364  3697  3928 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BleCentralService newState = 1 callingPackage = 10019
07-25 18:26:25.371  3697  4547 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BlePeripheralService newState = 1 callingPackage = 10019
,07-25 18:26:25.548  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-25 18:26:25.556  5224  6792 I Authzen : [PermitStore] Getting all permits...
07-25 18:26:25.557  3697  3931 D wifi    : In wifi stop Hal
07-25 18:26:25.557  3697  3931 D wifi    : halHandle = 0x7a21ed6a80, mVM = 0x7a4fc90300, mCls = 0x1010ee
,07-25 18:26:25.557  3697  4292 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-25 18:26:25.557  3697  4292 D WifiHAL : Got a signal to exit!!!
07-25 18:26:25.557  3697  4292 I WifiHAL : Exit wifi_event_loop
07-25 18:26:25.558  3697  3931 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-25 18:26:25.558  3697  3931 E WifiHAL : Event processing terminated
07-25 18:26:25.565  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-25 18:26:25.565  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-25 18:26:25.565  3697  3958 D HS20StateMachine: WIFI_STATE_DISABLED
07-25 18:26:25.566  3697  3960 I WifiHs20Service: Message received 5011
07-25 18:26:25.566  3697  3958 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
,07-25 18:26:25.567  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:25.571  3298  3787 D Netd    : Iface p2p0 link down
,07-25 18:26:25.573  3697  3828 D Tethering: interfaceLinkStateChanged p2p0, false
07-25 18:26:25.573  3697  3828 D Tethering: interfaceStatusChanged p2p0, false
,07-25 18:26:25.577  3697  4045 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-25 18:26:25.577  3697  3697 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-25 18:26:25.578  3697  4491 D SLocation: checkWifiInfo
07-25 18:26:25.581  9920  9920 D A2dpService: A2dpService - WIFI_STATE_DISABLED
07-25 18:26:25.581  9920  9920 I BluetoothA2dpServiceJni: Attempting to set busy level
07-25 18:26:25.581  4718  5250 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-25 18:26:25.582  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:25.585  3697  4045 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-25 18:26:25.586  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-25 18:26:25.587  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-25 18:26:25.587  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-25 18:26:25.589  9109  9109 I WifiApBroadcastReceiver: onReceive: action com.samsung.intent.action.START_PROVISIONING userID :0
,07-25 18:26:25.591  3697  3931 D wifi    : In wifi cleaned up handler
,07-25 18:26:25.591  3697  3931 I WifiHAL : Internal cleanup completed
,07-25 18:26:25.603  3697  3928 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-25 18:26:25.608  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:25.608  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:25.608  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:25.608  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:25.608  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:25.609  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:25.609  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:25.609  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:25.609  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:25.609  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:25.623  3697  4837 D MountService: getExternalStorageMountMode : 3
07-25 18:26:25.623  3697  4837 D MountService: getExternalStorageMountMode : 3
07-25 18:26:25.623  3697  4837 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 5017, packageName : com.samsung.android.radiobasedlocation
,07-25 18:26:25.643 10074 10074 E Zygote  : v2
07-25 18:26:25.643 10074 10074 I libpersona: KNOX_SDCARD checking this for 5017
07-25 18:26:25.643 10074 10074 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:25.644  3697  4837 I ActivityManager: Start proc 10074:com.samsung.android.radiobasedlocation/5017 for broadcast com.samsung.android.radiobasedlocation/.RblServiceReceiver
,07-25 18:26:25.644 10074 10074 E Zygote  : accessInfo : 0
,07-25 18:26:25.646  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135179 arg1=270 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:25.654 10074 10074 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-25 18:26:25.656 10074 10074 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.radiobasedlocation 
,07-25 18:26:25.661  4718  9905 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-25 18:26:25.684 10074 10074 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:26:25.684 10074 10074 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:25.687  3697  6550 I ActivityManager: DSS on for com.samsung.android.radiobasedlocation and scale is 1.0
,07-25 18:26:25.722 10074 10074 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-25 18:26:25.724 10074 10074 W System  : ClassLoader referenced unknown path: /system/priv-app/RadioBasedLocation/lib/arm64
,07-25 18:26:25.742 10074 10074 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:25.748 10074 10074 I [RBL] PathProvider: @onCreate
,07-25 18:26:25.751 10074 10074 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-25 18:26:25.759  3697 10019 I ActivityManager: KPU : put [com.android.defcontainer] : 28068 K
,07-25 18:26:25.759  3697 10019 I ActivityManager: Killing 9036:com.android.defcontainer/u0a8 (adj 906): DHA:empty #33
,07-25 18:26:25.765  3697  4830 D MountService: getExternalStorageMountMode : 1
07-25 18:26:25.765  3697  4830 D MountService: getExternalStorageMountMode : 3
07-25 18:26:25.765  3697  4830 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.diagmonagent
,07-25 18:26:25.786 10088 10088 E Zygote  : v2
07-25 18:26:25.786 10088 10088 I libpersona: KNOX_SDCARD checking this for 1000
07-25 18:26:25.786 10088 10088 I libpersona: KNOX_SDCARD not a persona
,07-25 18:26:25.787 10088 10088 E Zygote  : accessInfo : 0
,07-25 18:26:25.794  3697  4830 I ActivityManager: Start proc 10088:com.sec.android.diagmonagent/1000 for broadcast com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,07-25 18:26:25.795 10088 10088 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-25 18:26:25.795  3697  4893 D ActivityManager: cleanUpApplicationRecord -- 9036
,07-25 18:26:25.797  4762  4776 D ForegroundUtils: could not check pending caller
,07-25 18:26:25.797 10088 10088 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.diagmonagent 
,07-25 18:26:25.826 10088 10088 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:25.827 10088 10088 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:25.829  3697 10018 I ActivityManager: DSS on for com.sec.android.diagmonagent and scale is 1.0
,07-25 18:26:25.847 10088 10088 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
07-25 18:26:25.847  3697 10019 D WifiService: setWifiEnabled: true pid=9791, uid=10033
07-25 18:26:25.848  3697 10019 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-25 18:26:25.848  3697 10019 D WifiControlHistoryProvider: query
,07-25 18:26:25.854  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:25.854  3697 10019 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:26:25.855  3697 10019 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:25.856  3697 10019 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:25.859  3697 10019 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-25 18:26:25.859  3697 10019 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-25 18:26:25.859  3697  3929 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-25 18:26:25.862 10088 10088 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:25.884 10088 10088 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-25 18:26:25.928 10088 10088 E SQLiteLog: (1) no such column: currentid
,07-25 18:26:25.929 10088 10088 E DIAGMON_AGENT: [llllIIIIlllIIIlIllIl(906/lllIlIlIIIllIIlIllIl)] android.database.sqlite.SQLiteException: no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1
07-25 18:26:25.929 10088 10088 E DIAGMON_AGENT: #################################################################
07-25 18:26:25.929 10088 10088 E DIAGMON_AGENT: Error Code : 1 (SQLITE_ERROR)
07-25 18:26:25.929 10088 10088 E DIAGMON_AGENT: Caused By : SQL(query) error or missing database.
07-25 18:26:25.929 10088 10088 E DIAGMON_AGENT: 	(no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1)
07-25 18:26:25.929 10088 10088 E DIAGMON_AGENT: #################################################################
,07-25 18:26:25.965 10088 10088 E SQLiteLog: (1) table profilelist has no column named currentid
,07-25 18:26:25.966 10088 10088 E SQLiteDatabase: Error inserting number=0 len=0 profilename3=Mformation notiretrycount=0 currentid=-1 size=0 oplevel=0 serviceid= appid=0 profilename2=dm-Server notievent=0 sessionid=null profilename1=api-server status=0 uictype=0 text= holdingid=-1 sessionsavestate=0 profileindex=0 opmode= result=0 pushjobid= notiuievent=0
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: android.database.sqlite.SQLiteException: table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: #################################################################
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: Error Code : 1 (SQLITE_ERROR)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: Caused By : SQL(query) error or missing database.
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	(table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?))
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: #################################################################
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1005)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.prepare(SQLiteConnection.java:570)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:588)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:59)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1771)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1643)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:667)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:399)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:116)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:60)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1032)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5885)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap3(ActivityThread.java)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1703)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:154)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6692)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke,(Native Method)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1468)
07-25 18:26:25.966 10088 10088 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1358)
,07-25 18:26:26.002 10088 10088 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(64/onCreate)] nStatus : 0
,07-25 18:26:26.008 10088 10088 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(77/onCreate)] DiagMon DM Application Start !
07-25 18:26:26.009 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-25 18:26:26.010 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:26:26.010 10088 10088 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-25 18:26:26.010 10088 10088 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-25 18:26:26.015  3697  4838 D MountService: getExternalStorageMountMode : 1
,07-25 18:26:26.015  3697  4838 D MountService: getExternalStorageMountMode : 3
07-25 18:26:26.015  3697  4838 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.app.RilErrorNotifier
,07-25 18:26:26.018  3697  4492 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / op:PendingIntent{50bf2df: PendingIntentRecord{1908b2c android broadcastIntent}}
,07-25 18:26:26.058 10101 10101 E Zygote  : v2
07-25 18:26:26.059 10101 10101 I libpersona: KNOX_SDCARD checking this for 1000
,07-25 18:26:26.059 10101 10101 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:26.059  3697  4838 I ActivityManager: Start proc 10101:com.sec.app.RilErrorNotifier/1000 for broadcast com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
07-25 18:26:26.060 10101 10101 E Zygote  : accessInfo : 0
,07-25 18:26:26.067  3697  4838 I ActivityManager: KPU : put [com.samsung.android.bbc.bbcagent] : 26876 K
07-25 18:26:26.067  3697  4838 I ActivityManager: Killing 9094:com.samsung.android.bbc.bbcagent/1000 (adj 906): DHA:empty #33
,07-25 18:26:26.070 10101 10101 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:26.070  3697  4492 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170726T182626 - CU:1000/CP:3697
,07-25 18:26:26.072 10101 10101 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.app.RilErrorNotifier 
,07-25 18:26:26.097 10101 10101 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:26:26.098 10101 10101 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:26.098  3697  3944 D ActivityManager: cleanUpApplicationRecord -- 9094
07-25 18:26:26.101  4762  6430 D ForegroundUtils: could not check pending caller
,07-25 18:26:26.105  3697  4544 I ActivityManager: DSS on for com.sec.app.RilErrorNotifier and scale is 1.0
,07-25 18:26:26.130 10101 10101 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,07-25 18:26:26.146 10101 10101 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:26.150 10101 10101 I PhoneErrorReceiver: onReceive
,07-25 18:26:26.154  3697  6550 D MountService: getExternalStorageMountMode : 1
07-25 18:26:26.154  3697  6550 D MountService: getExternalStorageMountMode : 3
07-25 18:26:26.154  3697  6550 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.knox.switcher
,07-25 18:26:26.184 10114 10114 E Zygote  : v2
07-25 18:26:26.184 10114 10114 I libpersona: KNOX_SDCARD checking this for 1000
,07-25 18:26:26.184 10114 10114 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:26.184 10114 10114 E Zygote  : accessInfo : 0
,07-25 18:26:26.187  3697  6550 I ActivityManager: Start proc 10114:com.sec.knox.switcher/1000 for broadcast com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
,07-25 18:26:26.191 10114 10114 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:26.192 10114 10114 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.knox.switcher 
,07-25 18:26:26.195  3697  6550 I ActivityManager: KPU : put [com.facebook.system] : 27096 K
07-25 18:26:26.195  3697  6550 I ActivityManager: Killing 9176:com.facebook.system/u0a12 (adj 906): DHA:empty #33
,07-25 18:26:26.212 10114 10114 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:26.213 10114 10114 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:26.215  3697  4945 I ActivityManager: DSS on for com.sec.knox.switcher and scale is 1.0
,07-25 18:26:26.223  3697  3777 D ActivityManager: cleanUpApplicationRecord -- 9176
,07-25 18:26:26.227  4762  4777 D ForegroundUtils: could not check pending caller
,07-25 18:26:26.238 10114 10114 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,07-25 18:26:26.254 10114 10114 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:26.260 10114 10114 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
07-25 18:26:26.260 10114 10114 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,07-25 18:26:26.261 10114 10114 D ShareFileProvider: ShareFileProvider | onCreate [0]
07-25 18:26:26.261 10114 10114 D ShareFileDBHelper: getInstance - ShareFileDBHelper
07-25 18:26:26.261 10114 10114 D ShareFileDBHelper: null == mDbHelperInstance - ShareFileDBHelper
07-25 18:26:26.261 10114 10114 D ShareFileDBHelper: ShareFileDBHelper - Constructor
07-25 18:26:26.261  3298  3787 D Netd    : Iface wlan0 link down
07-25 18:26:26.263  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, false
07-25 18:26:26.263  3697  3828 D Tethering: interfaceStatusChanged wlan0, false
07-25 18:26:26.264  3697  4292 D wifi    : set interface wlan0 flags (DOWN)
,07-25 18:26:26.265  3697  3931 D WifiNative-HAL: HAL event thread stopped successfully
,07-25 18:26:26.265 10114 10114 I usagelog: received in receiver
07-25 18:26:26.266 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-25 18:26:26.268 10114 10114 I KnoxUsageLogPro: premStatus:2
,07-25 18:26:26.274 10114 10114 I KnoxUsageLogPro: isEulaShown : false
07-25 18:26:26.274 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:26:26.282  3697  4838 I ActivityManager: KPU : put [com.google.android.apps.docs] : 42240 K
07-25 18:26:26.282  3697  4838 I ActivityManager: Killing 9191:com.google.android.apps.docs/u0a93 (adj 906): DHA:empty #33
,07-25 18:26:26.332  3697  3948 D ActivityManager: cleanUpApplicationRecord -- 9191
07-25 18:26:26.333  5224  5224 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
07-25 18:26:26.335  4762  6430 D ForegroundUtils: could not check pending caller
,07-25 18:26:26.341  5224  8222 I iu.UploadsManager: num queued entries: 0
,07-25 18:26:26.342  5224  8222 I iu.UploadsManager: num updated entries: 0
,07-25 18:26:26.345  5224  8222 I iu.SyncManager: NEXT; no task
,07-25 18:26:26.348  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:26.364  3697  3777 D WifiService: setWifiEnabled: true pid=9791, uid=10033
07-25 18:26:26.365  3697  3777 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-25 18:26:26.365  3697  3777 D WifiControlHistoryProvider: query
,07-25 18:26:26.372  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:26.372  3697  3777 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-25 18:26:26.374  3697  3777 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:26.374  3697  3777 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:26.378  3697  3777 I WifiService: Wi-Fi Sharing settings has not been accessed
07-25 18:26:26.378  3697  3777 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-25 18:26:26.379  3697  3929 E WifiController: illegal state found both WifiController and WifiStateMachine
07-25 18:26:26.379  3697  4945 D MountService: getExternalStorageMountMode : 1
07-25 18:26:26.379  3697  4945 D MountService: getExternalStorageMountMode : 3
07-25 18:26:26.379  3697  4945 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10041, packageName : com.osp.app.signin
,07-25 18:26:26.404 10128 10128 E Zygote  : v2
07-25 18:26:26.404 10128 10128 I libpersona: KNOX_SDCARD checking this for 10041
07-25 18:26:26.404 10128 10128 I libpersona: KNOX_SDCARD not a persona
,07-25 18:26:26.404  3697  4945 I ActivityManager: Start proc 10128:com.osp.app.signin/u0a41 for broadcast com.osp.app.signin/.OspReceiver
07-25 18:26:26.405 10128 10128 E Zygote  : accessInfo : 0
,07-25 18:26:26.414 10128 10128 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:26.416 10128 10128 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.osp.app.signin 
,07-25 18:26:26.443  3697  3917 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170725T185626 - CU:10124/CP:5123
,07-25 18:26:26.448 10128 10128 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:26.449 10128 10128 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:26.451  3697  4829 I ActivityManager: DSS on for com.osp.app.signin and scale is 1.0
,07-25 18:26:26.466  3697  3931 E WifiHW  : ##################### set firmware type 0 #####################
,07-25 18:26:26.468  3298  3795 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-25 18:26:26.469  3298  3795 I WifiHW  : module is semco
07-25 18:26:26.469  3298  3795 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-25 18:26:26.469  3298  3795 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-25 18:26:26.469  3298  3795 E WifiHW  : TEMP_FAILURE_RETRY complete
,07-25 18:26:26.469  3298  3795 D SoftapController: Softap fwReload - Ok
,07-25 18:26:26.471  3697  3931 E NetworkManagement: wifiFirmwareReload Error reloading wlan0 fw in STA mode: event = 200 219 Softap operation succeeded
,07-25 18:26:26.477  3298  3795 D CommandListener: Setting iface cfg
07-25 18:26:26.478  3298  3795 D CommandListener: Trying to bring down wlan0
,07-25 18:26:26.480  3298  3795 D CommandListener: Clearing all IP addresses on wlan0
,07-25 18:26:26.489  3697  3931 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-25 18:26:26.530 10128 10128 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-25 18:26:26.534 10128 10128 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Dream/lib/arm64
,07-25 18:26:26.560 10128 10128 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:26.576 10128 10128 I SA      : [SSP] onCreated
,07-25 18:26:26.614 10128 10128 D SamsungAnalytics:1.8.22: cf feature is supported
,07-25 18:26:26.624 10128 10128 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
,07-25 18:26:26.631 10128 10128 I SA      : LBE isSupportBixbyModel() FALSE
,07-25 18:26:26.644 10128 10128 I SA      : [TPM] There is no property file
,07-25 18:26:26.657 10128 10128 I SA      : [SCU] isHaveSA() - false
,07-25 18:26:26.665 10128 10128 I SA      : [SS] no samsung account is signed in
,07-25 18:26:26.671 10128 10128 I SA      : [TPM] getModelProperty : null
07-25 18:26:26.671 10128 10128 I SA      : [TPM] getCSCProperty : null
,07-25 18:26:26.674 10128 10128 I SA      : [SCU] isHaveSA() - false
,07-25 18:26:26.676 10128 10128 I SA      : [SCU] == networkStateCheck == false
07-25 18:26:26.676 10128 10128 I SA      : [SS] network off, couldn't connect to DIR
,07-25 18:26:26.683 10128 10128 D BixbyApi_0.1.6: Version Name:2.2.03-46
,07-25 18:26:26.687 10128 10128 I SA      : [DM] init START
,07-25 18:26:26.695 10128 10128 I SA      : [DM] This device is not a Vodafone
,07-25 18:26:26.701 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.701 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.702 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.702 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.703 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.703 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.704 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.704 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.704 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.705 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.705 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.706 10128 10128 W ResourceType: Failure getting entry for 0x7f0b0002 (t=10 e=2) (error -75)
07-25 18:26:26.706 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.707 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.707 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.707 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.708 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.708 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.709 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.709 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.709 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.710 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.710 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.711 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.711 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.712 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.712 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.712 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.713 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.713 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.714 10128 10128 W ResourceType: Failure getting entry for 0x7f0b0005 (t=10 e=5) (error -75)
07-25 18:26:26.714 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.714 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.715 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.715 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.716 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.716 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.717 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.717 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.717 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.718 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.718 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.719 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.719 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.719 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.720 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-25 18:26:26.720 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.721 10128 10128 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-25 18:26:26.723 10128 10128 I SA      : support phone number id : true
07-25 18:26:26.723 10128 10128 I SA      : [DM] Supports Ref Jpn : true
07-25 18:26:26.724 10128 10128 I SA      : [DM] init END
07-25 18:26:26.724 10128 10128 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,07-25 18:26:26.728 10128 10128 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
07-25 18:26:26.729 10128 10128 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-25 18:26:26.743 10128 10128 I SA      : [SLFUCHKMGR] constructor called
,07-25 18:26:26.764 10128 10128 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-25 18:26:26.764 10128 10128 I SA      : [OR] == isSIMCardReady false ==
07-25 18:26:26.764 10128 10128 I SA      : [SCU] == networkStateCheck == false
07-25 18:26:26.764 10128 10128 I SA      : [OR] onReceive END
,07-25 18:26:26.774  3697  3944 I ActivityManager: KPU : put [com.facebook.appmanager] : 23344 K
07-25 18:26:26.774  3697  3944 I ActivityManager: Killing 9145:com.facebook.appmanager/u0a98 (adj 906): DHA:empty #33
,07-25 18:26:26.779  3697  3811 D MountService: getExternalStorageMountMode : 1
07-25 18:26:26.780  3697  3811 D MountService: getExternalStorageMountMode : 3
07-25 18:26:26.780  3697  3811 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.svcagent
,07-25 18:26:26.806 10151 10151 E Zygote  : v2
07-25 18:26:26.806 10151 10151 I libpersona: KNOX_SDCARD checking this for 1000
07-25 18:26:26.806 10151 10151 I libpersona: KNOX_SDCARD not a persona
,07-25 18:26:26.807 10151 10151 E Zygote  : accessInfo : 0
,07-25 18:26:26.817 10151 10151 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:26.819 10151 10151 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.svcagent 
,07-25 18:26:26.825  3697  3811 I ActivityManager: Start proc 10151:com.samsung.android.svcagent/1000 for broadcast com.samsung.android.svcagent/com.samsung.android.service.svcagent.BootReceiver
,07-25 18:26:26.826  3697  4547 D ActivityManager: cleanUpApplicationRecord -- 9145
,07-25 18:26:26.827  4762  6430 D ForegroundUtils: could not check pending caller
,07-25 18:26:26.856 10151 10151 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:26.857 10151 10151 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:26.860  3697  3777 I ActivityManager: DSS on for com.samsung.android.svcagent and scale is 1.0
,07-25 18:26:26.883  3697  4829 D WifiService: setWifiEnabled: true pid=9791, uid=10033
07-25 18:26:26.883  3697  4829 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-25 18:26:26.884 10151 10151 W System  : ClassLoader referenced unknown path: /system/priv-app/SVCAgent/lib/arm64
07-25 18:26:26.884  3697  4829 D WifiControlHistoryProvider: query
,07-25 18:26:26.889  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:26.890  3697  4829 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-25 18:26:26.891  3697  4829 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:26.891  3697  4829 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:26.894  3697  4829 I WifiService: Wi-Fi Sharing settings has not been accessed
07-25 18:26:26.895  3697  4829 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-25 18:26:26.895  3697  3929 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-25 18:26:26.907 10151 10151 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:26.919 10151 10151 I SVCAgent: Ignore network change.
,07-25 18:26:26.921  3697 10018 D MountService: getExternalStorageMountMode : 1
07-25 18:26:26.921  3697 10018 D MountService: getExternalStorageMountMode : 3
07-25 18:26:26.921  3697 10018 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10064, packageName : com.samsung.android.themestore
,07-25 18:26:26.943 10164 10164 E Zygote  : v2
07-25 18:26:26.943 10164 10164 I libpersona: KNOX_SDCARD checking this for 10064
07-25 18:26:26.943 10164 10164 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:26.943  3697 10018 I ActivityManager: Start proc 10164:com.samsung.android.themestore/u0a64 for broadcast com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
07-25 18:26:26.944 10164 10164 E Zygote  : accessInfo : 0
,07-25 18:26:26.947  3697 10018 I ActivityManager: KPU : put [com.google.android.partnersetup] : 26860 K
07-25 18:26:26.947  3697 10018 I ActivityManager: Killing 9250:com.google.android.partnersetup/u0a23 (adj 906): DHA:empty #33
,07-25 18:26:26.953 10164 10164 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:26.955 10164 10164 I SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,07-25 18:26:26.975  3697  6550 D ActivityManager: cleanUpApplicationRecord -- 9250
,07-25 18:26:26.977  4762  4777 D ForegroundUtils: could not check pending caller
,07-25 18:26:26.984 10164 10164 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:26:26.985 10164 10164 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:26.987  3697  3944 I ActivityManager: DSS on for com.samsung.android.themestore and scale is 1.0
,07-25 18:26:27.016 10164 10164 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-25 18:26:27.018 10164 10164 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyThemes/lib/arm64
,07-25 18:26:27.043 10164 10164 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:27.084 10164 10164 D a       : Exist Config : false
,07-25 18:26:27.087 10164 10164 D a       : getMcc
,07-25 18:26:27.095 10164 10164 D as      : isQaMode
,07-25 18:26:27.106 10164 10164 D a       : getMnc
07-25 18:26:27.107 10164 10164 D a       : getCsc
07-25 18:26:27.107 10164 10164 D a       : getSystemCountryCode
07-25 18:26:27.107 10164 10164 D a       : getImei
,07-25 18:26:27.115 10164 10164 D as      : getMd5HashString
07-25 18:26:27.116 10164 10164 D as      : getSha256HashString
,07-25 18:26:27.117 10164 10164 D a       : getModelName
07-25 18:26:27.118 10164 10164 D a       : getVirtualModelName
07-25 18:26:27.118 10164 10164 D a       : getAndroidSDKVersion
,07-25 18:26:27.118 10164 10164 D a       : getLanguageCode
07-25 18:26:27.118 10164 10164 D a       : getCountryCode
,07-25 18:26:27.126 10164 10164 D a       : getNetworkType
,07-25 18:26:27.133 10164 10164 D w       : isSupportedAodSystemFeature
,07-25 18:26:27.137 10164 10164 D a       : getThemeFrameworkVersion
,07-25 18:26:27.144 10164 10164 D a       : isLogPrintMode
,07-25 18:26:27.147 10164 10164 D as      : isQaMode
,07-25 18:26:27.155 10164 10164 D a       : getVerName
,07-25 18:26:27.157 10164 10164 D a       : getVerCode
,07-25 18:26:27.158 10164 10164 D a       : getPackageName
,07-25 18:26:27.158 10164 10164 D a       : getAutoUpgradeInterval
,07-25 18:26:27.162 10164 10164 D a       : loadCountrySearchEx
,07-25 18:26:27.169 10164 10164 D a       : com.samsung.android.themestore.g.c.b.u; class invalid for deserialization
,07-25 18:26:27.170 10164 10164 I a       : # initConfig Time : 93
07-25 18:26:27.170 10164 10164 I a       : ● MCC/NNC: /0
,07-25 18:26:27.171 10164 10164 I a       : ● Model: SM-G930F_TM
07-25 18:26:27.171 10164 10164 I a       : ● MyApp Version: 2.1.56-70306
,07-25 18:26:27.171 10164 10164 I a       : ● OS Version: 24
07-25 18:26:27.171 10164 10164 I a       : ● IsSupportedSView: true
,07-25 18:26:27.185 10164 10164 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-25 18:26:27.212 10164 10164 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:26:27.233  3697  3811 I ActivityManager: KPU : put [com.samsung.android.SettingsReceiver] : 26912 K
,07-25 18:26:27.233  3697  3811 I ActivityManager: Killing 8384:com.samsung.android.SettingsReceiver/1000 (adj 906): DHA:empty #33
,07-25 18:26:27.242  8013  8013 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:26:27.243  8013  8013 E SPPClientService: [SystemStateMoniter] Current Time : 289781
,07-25 18:26:27.245  8013  8013 E SPPClientService: [SystemStateMoniter] No Connect : true
,07-25 18:26:27.266  3697  3931 D wifi    : set interface wlan0 flags (UP)
,07-25 18:26:27.266  3298  3787 D Netd    : Iface wlan0 link up
,07-25 18:26:27.266  3697  3931 I WifiHAL : Initializing wifi
07-25 18:26:27.266  3697  3931 I WifiHAL : Creating socket
07-25 18:26:27.269  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:27.269  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:26:27.270  3697  3931 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
07-25 18:26:27.270  3697  3931 D wifi    : Did set static halHandle = 0x7a21ed6a80
07-25 18:26:27.270  3697  3931 D wifi    : halHandle = 0x7a21ed6a80, mVM = 0x7a4fc90300, mCls = 0x102b76
07-25 18:26:27.270  3697  3931 D wifi    : array field set
07-25 18:26:27.275  3697  3931 I WifiHW  : CCMode is disabled, skip verifying wpa_supplicant
07-25 18:26:27.275  3697 10192 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=524555217536
07-25 18:26:27.275  3697 10192 D wifi    : waitForHalEvents called, vm = 0x7a4fc90300, obj = 0x102b76, env = 0x7a23f376c0
07-25 18:26:27.276  3697  3931 E WifiHW  : supplicant_name : p2p_supplicant
07-25 18:26:27.277  8013 10191 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
07-25 18:26:27.280  3697  3811 D MountService: getExternalStorageMountMode : 1
07-25 18:26:27.280  3697  3811 D MountService: getExternalStorageMountMode : 3
07-25 18:26:27.280  3697  3811 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 5005, packageName : com.samsung.android.allshare.service.fileshare
,07-25 18:26:27.304 10194 10194 E Zygote  : v2
07-25 18:26:27.304 10194 10194 I libpersona: KNOX_SDCARD checking this for 5005
07-25 18:26:27.304 10194 10194 I libpersona: KNOX_SDCARD not a persona
,07-25 18:26:27.305 10194 10194 E Zygote  : accessInfo : 0
07-25 18:26:27.305  3697  3811 I ActivityManager: Start proc 10194:com.samsung.android.allshare.service.fileshare/5005 for broadcast com.samsung.android.allshare.service.fileshare/.FileShareBroadcastReceiver
07-25 18:26:27.306  3697  3957 D ActivityManager: cleanUpApplicationRecord -- 8384
,07-25 18:26:27.311  4762  4777 D ForegroundUtils: could not check pending caller
,07-25 18:26:27.315 10194 10194 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:27.317 10194 10194 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.allshare.service.fileshare 
,07-25 18:26:27.363 10194 10194 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:27.364 10194 10194 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:27.367  3697  4544 I ActivityManager: DSS on for com.samsung.android.allshare.service.fileshare and scale is 1.0
,07-25 18:26:27.374 10193 10193 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 10193 | /system/bin/wpa_supplicant
,07-25 18:26:27.374 10193 10193 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
,07-25 18:26:27.376 10193 10193 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-25 18:26:27.376 10193 10193 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-25 18:26:27.379  3697  3931 D SecContentProvider: insert(), uri = 2
,07-25 18:26:27.380 10193 10193 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x400008), vendorssid_list()
,07-25 18:26:27.380 10193 10193 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-25 18:26:27.380  3697  3931 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:27.381  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10193
,07-25 18:26:27.381  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-25 18:26:27.382  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
07-25 18:26:27.382 10193 10193 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-25 18:26:27.382 10193 10193 I wpa_supplicant: ssSupport state is = 1
07-25 18:26:27.382 10193 10193 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-25 18:26:27.382 10193 10193 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-25 18:26:27.382  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10193
07-25 18:26:27.382  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
07-25 18:26:27.383  3697  3931 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-25 18:26:27.385  3697  3931 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
07-25 18:26:27.387  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-25 18:26:27.388  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-25 18:26:27.389  3697  3960 I WifiHs20Service: Message received 5011
,07-25 18:26:27.390  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=2 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:27.393  3697  4045 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-25 18:26:27.397  3697  4045 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-25 18:26:27.397  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:27.397  3697  3697 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-25 18:26:27.398  3697  4491 D SLocation: checkWifiInfo
,07-25 18:26:27.400  3697  3928 D WifiService: setWifiEnabled: true pid=9791, uid=10033
,07-25 18:26:27.404  3697  3928 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-25 18:26:27.405  3697  3928 D WifiControlHistoryProvider: query
,07-25 18:26:27.410  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:27.411  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:27.411  3697  3928 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-25 18:26:27.412  3697  3928 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:27.413  3697  3928 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:27.417  3697  3928 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-25 18:26:27.417  3697  3928 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-25 18:26:27.437 10194 10194 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:27.444 10194 10194 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-25 18:26:27.446 10194 10194 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
,07-25 18:26:27.464 10194 10194 D FileShare: Outbound.stopDelayTimer - 
,07-25 18:26:27.489 10074 10074 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-25 18:26:27.502  3697  4893 I ActivityManager: KPU : put [com.samsung.android.app.mirrorlink] : 21124 K
07-25 18:26:27.502  3697  4893 I ActivityManager: Killing 9268:com.samsung.android.app.mirrorlink/1000 (adj 906): DHA:empty #33
,07-25 18:26:27.510 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-25 18:26:27.511 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,07-25 18:26:27.511 10088 10088 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-25 18:26:27.515  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-25 18:26:27.519 10101 10101 I PhoneErrorReceiver: onReceive
,07-25 18:26:27.525 10114 10114 I usagelog: received in receiver
07-25 18:26:27.525 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:26:27.525  3697  4547 D ActivityManager: cleanUpApplicationRecord -- 9268
,07-25 18:26:27.526 10114 10114 I KnoxUsageLogPro: premStatus:2
,07-25 18:26:27.526 10114 10114 I KnoxUsageLogPro: isEulaShown : false
07-25 18:26:27.527 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:26:27.531  4762  6430 D ForegroundUtils: could not check pending caller
,07-25 18:26:27.536  9857  9857 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-25 18:26:27.536  9857  9857 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,07-25 18:26:27.538  3697  4893 D MountService: getExternalStorageMountMode : 1
07-25 18:26:27.538  3697  4893 D MountService: getExternalStorageMountMode : 3
07-25 18:26:27.538  3697  4893 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10172, packageName : com.example.ThaliTestApp
,07-25 18:26:27.554  3697  4893 I ActivityManager: Start proc 10207:com.example.ThaliTestApp/u0a172 for broadcast com.example.ThaliTestApp/io.jxcore.node.ConnectivityChangeListener
,07-25 18:26:27.556 10193 10193 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
07-25 18:26:27.556 10207 10207 E Zygote  : v2
,07-25 18:26:27.556 10207 10207 I libpersona: KNOX_SDCARD checking this for 10172
07-25 18:26:27.556 10207 10207 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:27.558 10207 10207 E Zygote  : accessInfo : 0
,07-25 18:26:27.564 10207 10207 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:27.566 10207 10207 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.ThaliTestApp 
,07-25 18:26:27.569 10207 10207 I art     : Late-enabling -Xcheck:jni
,07-25 18:26:27.575  3238  3238 E audit   : type=1320 audit(1500999987.561:546): 
,07-25 18:26:27.588 10193 10193 W wpa_supplicant: Loading system cred
07-25 18:26:27.588 10193 10193 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-25 18:26:27.589  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10193
07-25 18:26:27.589  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-25 18:26:27.589 10193 10193 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-25 18:26:27.589 10193 10193 I wpa_supplicant: ssSupport state is = 1
07-25 18:26:27.589  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-25 18:26:27.589 10193 10193 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-25 18:26:27.590 10193 10193 I wpa_supplicant: [getIMSI]: sim_num 0
,07-25 18:26:27.590  3238  3238 E audit   : type=1320 audit(1500999987.571:547): 
,07-25 18:26:27.598 10207 10207 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:26:27.599 10207 10207 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:27.602  3697  4945 I ActivityManager: DSS on for com.example.ThaliTestApp and scale is 1.0
,07-25 18:26:27.608  3238  3238 E audit   : type=1320 audit(1500999987.591:548): 
,07-25 18:26:27.624  3238  3238 E audit   : type=1320 audit(1500999987.611:549): 
,07-25 18:26:27.636 10207 10207 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-25 18:26:27.657 10207 10207 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:27.666  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.666  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.666  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.667  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.667  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.667  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.667  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.667  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:27.667  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.667  3697  4830 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:27.674 10193 10193 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-25 18:26:27.675  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:26:27.675  3298  3787 D Netd    : Iface wlan0 link up
,07-25 18:26:27.676  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:27.677  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:26:27.678  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:27.678  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:26:27.706 10207 10207 D jxcore_app_log: JniHelper::setJavaVM(0xe6f34000), pthread_self() = -364198604
07-25 18:26:27.706 10207 10207 E JX-Cordova: JXcore wasn't initialized yet
,07-25 18:26:27.709  3697 10019 D MountService: getExternalStorageMountMode : 3
07-25 18:26:27.709  3697 10019 D MountService: getExternalStorageMountMode : 3
07-25 18:26:27.709  3697 10019 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 10173, packageName : com.rockwellautomation.AppPlatformP2P
,07-25 18:26:27.745 10226 10226 E Zygote  : v2
07-25 18:26:27.745 10226 10226 I libpersona: KNOX_SDCARD checking this for 10173
07-25 18:26:27.745 10226 10226 I libpersona: KNOX_SDCARD not a persona
,07-25 18:26:27.747 10226 10226 E Zygote  : accessInfo : 0
,07-25 18:26:27.748  3697 10019 I ActivityManager: Start proc 10226:com.rockwellautomation.AppPlatformP2P/u0a173 for broadcast com.rockwellautomation.AppPlatformP2P/io.jxcore.node.ConnectivityChangeListener
,07-25 18:26:27.756  3697 10019 I ActivityManager: KPU : put [com.samsung.android.sm.provider] : 28204 K
07-25 18:26:27.756  3697 10019 I ActivityManager: Killing 4659:com.samsung.android.sm.provider/1000 (adj 906): DHA:empty #33
,07-25 18:26:27.758 10226 10226 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:27.760 10226 10226 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.rockwellautomation.AppPlatformP2P 
,07-25 18:26:27.764 10226 10226 I art     : Late-enabling -Xcheck:jni
,07-25 18:26:27.774  3238  3238 E audit   : type=1320 audit(1500999987.761:550): 
,07-25 18:26:27.775 10193 10193 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-25 18:26:27.775 10193 10193 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-25 18:26:27.776  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10193
07-25 18:26:27.776  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-25 18:26:27.777  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-25 18:26:27.777 10193 10193 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-25 18:26:27.777 10193 10193 I wpa_supplicant: ssSupport state is = 1
,07-25 18:26:27.782 10193 10193 E wpa_supplicant: nl80211: Could not configure driver mode
07-25 18:26:27.782 10193 10193 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-25 18:26:27.782 10193 10193 E wpa_supplicant: p2p0: Failed to initialize driver interface
07-25 18:26:27.784 10193 10193 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-25 18:26:27.784 10193 10193 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-25 18:26:27.785  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10193
07-25 18:26:27.785  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-25 18:26:27.785  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-25 18:26:27.786 10193 10193 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-25 18:26:27.786 10193 10193 I wpa_supplicant: ssSupport state is = 1
,07-25 18:26:27.790  3238  3238 E audit   : type=1320 audit(1500999987.771:551): 
,07-25 18:26:27.793  3697  4547 D ActivityManager: cleanUpApplicationRecord -- 4659
,07-25 18:26:27.798  4762  4776 D ForegroundUtils: could not check pending caller
,07-25 18:26:27.802 10226 10226 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:27.803 10226 10226 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:27.805  3697  4945 I ActivityManager: DSS on for com.rockwellautomation.AppPlatformP2P and scale is 1.0
,07-25 18:26:27.810  3238  3238 E audit   : type=1320 audit(1500999987.791:552): 
,07-25 18:26:27.824  3238  3238 E audit   : type=1320 audit(1500999987.811:553): 
,07-25 18:26:27.835 10226 10226 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-25 18:26:27.859 10226 10226 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:27.882  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.882  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:27.883  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.883  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.883  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.883  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.884  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.884  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.884  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:27.884  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:27.888 10193 10193 I wpa_supplicant: rfkill: Cannot get wiphy information
,07-25 18:26:27.903 10193 10193 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-25 18:26:27.927  3697  4544 D WifiService: setWifiEnabled: true pid=9791, uid=10033
,07-25 18:26:27.928  3697  4544 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-25 18:26:27.929  3697  4544 D WifiControlHistoryProvider: query
,07-25 18:26:27.935 10226 10226 D jxcore_app_log: JniHelper::setJavaVM(0xe6f34000), pthread_self() = -364198604
07-25 18:26:27.935 10226 10226 E JX-Cordova: JXcore wasn't initialized yet
,07-25 18:26:27.953  3697  4945 I ActivityManager: KPU : put [com.samsung.android.scloud] : 28484 K
,07-25 18:26:27.953  3697  4945 I ActivityManager: Killing 9283:com.samsung.android.scloud/5009 (adj 906): DHA:empty #33
,07-25 18:26:27.962  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:27.963  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.963  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.963  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.963  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.963  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.964  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.964  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.964  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:27.964  3697  4837 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:27.969  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:27.972  3697  4945 D MountService: getExternalStorageMountMode : 1
07-25 18:26:27.972  3697  4945 D MountService: getExternalStorageMountMode : 3
07-25 18:26:27.972  3697  4945 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10003, packageName : com.sec.android.provider.badge
,07-25 18:26:27.998 10245 10245 E Zygote  : v2
07-25 18:26:27.998 10245 10245 I libpersona: KNOX_SDCARD checking this for 10003
,07-25 18:26:27.998 10245 10245 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:27.999 10245 10245 E Zygote  : accessInfo : 0
,07-25 18:26:28.000  3697  4945 I ActivityManager: Start proc 10245:com.sec.android.provider.badge/u0a3 for broadcast com.sec.android.provider.badge/.BadgeCountReceiver
,07-25 18:26:28.004  3697  6617 D ActivityManager: cleanUpApplicationRecord -- 9283
,07-25 18:26:28.009  3697  4544 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-25 18:26:28.009 10245 10245 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-25 18:26:28.009  4762  4776 D ForegroundUtils: could not check pending caller
07-25 18:26:28.009  3697  4544 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:28.010  3697  4544 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:28.011 10245 10245 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
07-25 18:26:28.014  3697  4544 I WifiService: Wi-Fi Sharing settings has not been accessed
07-25 18:26:28.014  3697  4544 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-25 18:26:28.043 10245 10245 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:26:28.044 10245 10245 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:28.047  3697  4830 I ActivityManager: DSS on for com.sec.android.provider.badge and scale is 1.0
,07-25 18:26:28.073 10245 10245 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_N/lib/arm64
,07-25 18:26:28.094 10245 10245 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:28.103 10245 10245 D BadgeProvider: onCreate
07-25 18:26:28.104 10245 10245 D BadgeProvider: DatabaseHelper
,07-25 18:26:28.109 10245 10245 D BadgeCountReceiver: badge intent : Intent { act=com.sec.intent.action.BADGE_COUNT_UPDATE flg=0x10 cmp=com.sec.android.provider.badge/.BadgeCountReceiver launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:28.109 10245 10245 D BadgeCountReceiver: packageName: com.samsung.android.email.provider, className: com.samsung.android.email.ui.activity.MessageListXL, count: 0
,07-25 18:26:28.118 10245 10245 D BadgeProvider: onOpen
,07-25 18:26:28.121 10245 10245 D BaseReflect: null getOwnClass TEST
07-25 18:26:28.122 10245 10245 D MethodReflector: android.content.ContentResolver getClass TEST
,07-25 18:26:28.122 10245 10245 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
07-25 18:26:28.122 10245 10245 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-25 18:26:28.128 10245 10245 D MethodReflector: notifyChange is called
,07-25 18:26:28.129  4904  4904 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
,07-25 18:26:28.131 10245 10245 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-25 18:26:28.131 10245 10245 D BadgeProvider: sendNotify, [notify] : null
,07-25 18:26:28.132 10245 10245 D BadgeProvider: update, getCallingPackage() : com.sec.android.provider.badge
07-25 18:26:28.132 10245 10245 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-25 18:26:28.133 10245 10245 D BadgeProvider: update, [uri.query] : null
07-25 18:26:28.133 10245 10245 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-25 18:26:28.133 10245 10245 D BadgeProvider: update, [UpdateCount] : 1
,07-25 18:26:28.133  4904  4904 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
,07-25 18:26:28.154  9857  9857 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-25 18:26:28.154  9857  9857 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,07-25 18:26:28.171  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.172  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.172  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.172  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.172  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.172  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.172  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.172  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.173  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.173  3697  4544 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.185  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.185  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.185  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.185  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.185  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.186  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.186  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.186  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.186  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.186  3697  3957 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.194  3697  4830 I ActivityManager: KPU : put [com.samsung.android.sm.devicesecurity] : 27408 K
07-25 18:26:28.194  3697  4830 I ActivityManager: Killing 7196:com.samsung.android.sm.devicesecurity/5012 (adj 906): DHA:empty #33
,07-25 18:26:28.200  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.200  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.200  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.200  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.200  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.200  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.201  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.201  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.201  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.201  3697 10019 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.211  9857  9857 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-25 18:26:28.211  9857  9857 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.223  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.224  3697 10018 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.225  3697  3917 D ActivityManager: cleanUpApplicationRecord -- 7196
,07-25 18:26:28.227  4762  6430 D ForegroundUtils: could not check pending caller
,07-25 18:26:28.237  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.238  3697  4829 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.247  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.248  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.323  3697  3832 I PowerManagerService: [PWL] On : 0 (290862 ms ago)
07-25 18:26:28.324  3697  3832 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-25 18:26:28.334  4904  4904 D LauncherApplication: run: mBadgeRefreshHandler reloadBadges
07-25 18:26:28.334  4904  4904 D Launcher.Model: reloadBadges entered.
,07-25 18:26:28.352 10245 10257 D BadgeProvider: query, [selection] : null
,07-25 18:26:28.359  4904  5017 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
07-25 18:26:28.359  4904  5017 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
07-25 18:26:28.359  4904  5017 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
07-25 18:26:28.359  4904  5017 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-25 18:26:28.359  4904  5017 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-25 18:26:28.359  4904  5017 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
07-25 18:26:28.359  4904  5017 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.lool = 0
07-25 18:26:28.359  4904  5017 D BadgeCache: 1. updateBadgeCounts: com.wssyncmldm = 0
,07-25 18:26:28.364  4904  5017 D BadgeCache: updated Badged:0
07-25 18:26:28.364  4904  5017 D BadgeCache: updateBadgeCounts:0
,07-25 18:26:28.418  3697  3816 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=290935 mStackState=3 mControllerTxTimeMs=0 mControllerTxTimePerLevelMs=[] mControllerRxTimeMs=0 mControllerIdleTimeMs=0 mControllerEnergyUsed=0 }
,07-25 18:26:28.443 10193 10193 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-25 18:26:28.446  3697  3931 I WifiConnectivityManager: User band preference: 0
,07-25 18:26:28.448  3697  3931 D WifiConfigManager: Loading config and enabling all networks 
,07-25 18:26:28.461  3697  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-25 18:26:28.477  3697  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-25 18:26:28.495  3697  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-25 18:26:28.525  3697  4945 D WifiService: setWifiEnabled: true pid=9791, uid=10033
,07-25 18:26:28.526  3697  4945 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-25 18:26:28.527  3697  4945 D WifiControlHistoryProvider: query
,07-25 18:26:28.535  3697  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-25 18:26:28.539  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:28.540  3697  4945 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-25 18:26:28.543  3697  4945 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:28.544  3697  4945 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:28.551  3697  4945 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-25 18:26:28.553  3697  4945 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-25 18:26:28.572  3697  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-25 18:26:28.588  3697  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-25 18:26:28.600  3697  3931 W WifiNetworkHistory: Upgrading network 4 to android.uid.system:1000
07-25 18:26:28.601  3697  3931 W WifiNetworkHistory: Upgrading network 0 to android.uid.system:1000
,07-25 18:26:28.602  3697  3931 W WifiNetworkHistory: Upgrading network 1 to android.uid.system:1000
07-25 18:26:28.603  3697  3931 W WifiNetworkHistory: Upgrading network 5 to android.uid.system:1000
,07-25 18:26:28.603  3697  3931 W WifiNetworkHistory: Upgrading network 2 to android.uid.system:1000
,07-25 18:26:28.604  3697  3931 W WifiNetworkHistory: Upgrading network 3 to android.uid.system:1000
,07-25 18:26:28.606  3697  3931 D WifiConfigManager: loaded 0 passpoint configs
,07-25 18:26:28.613  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-25 18:26:28.613  3697  3697 D WifiHs20Service: reason: 2
,07-25 18:26:28.613  3697  3960 I WifiHs20Service: Message received 5014
07-25 18:26:28.613  3697  3960 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-25 18:26:28.613  3697  3960 E WifiHs20Service: The changed config is NULL
,07-25 18:26:28.615  3697  3931 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-25 18:26:28.615 10193 10193 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,07-25 18:26:28.631  3697  3931 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-25 18:26:28.637  3697  3697 D WifiController: [FCC]setFccChannel() is called !!!
07-25 18:26:28.637  3697  3697 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
07-25 18:26:28.637  3697  3697 D WifiStateMachine: setFccChannel: channel = 0
07-25 18:26:28.638  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-25 18:26:28.639  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-25 18:26:28.639  3697  3958 D HS20StateMachine: WIFI_STATE_ENABLED
07-25 18:26:28.639  3697  3958 D HS20StateMachine: reloadCredentialsToSupplicant
07-25 18:26:28.639  3697  3958 D WifiHs20DBHandler: getCredentialIds
07-25 18:26:28.639  3697  3960 I WifiHs20Service: Message received 5011
,07-25 18:26:28.642  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=3 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:28.645  3697  3697 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-25 18:26:28.646  3697  4491 D SLocation: checkWifiInfo
07-25 18:26:28.646  3697  4491 W SLocation: No Active Data Connection
07-25 18:26:28.647  3697  3931 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-25 18:26:28.647 10193 10193 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,07-25 18:26:28.649  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:28.652  3697  4045 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-25 18:26:28.652  9920  9920 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-25 18:26:28.653  9920  9920 I BluetoothA2dpServiceJni: Attempting to set busy level
,07-25 18:26:28.656  3697  4045 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-25 18:26:28.658  9791  9791 D BluetoothAdapter: STATE_ON
,07-25 18:26:28.663  9857  9857 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
,07-25 18:26:28.663  9857  9857 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:26:28.663  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-25 18:26:28.665  3697  3958 D MountService: getExternalStorageMountMode : 1
07-25 18:26:28.665  3697  3958 D MountService: getExternalStorageMountMode : 3
07-25 18:26:28.665  3697  3958 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10114, packageName : com.samsung.hs20provider
,07-25 18:26:28.667  9791  9791 D BluetoothAdapter: STATE_ON
,07-25 18:26:28.672  9791  9791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,07-25 18:26:28.692 10261 10261 E Zygote  : v2
07-25 18:26:28.692 10261 10261 I libpersona: KNOX_SDCARD checking this for 10114
,07-25 18:26:28.692 10261 10261 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:28.693 10261 10261 E Zygote  : accessInfo : 0
,07-25 18:26:28.696  3697  3958 I ActivityManager: Start proc 10261:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,07-25 18:26:28.698  3697  3931 D WifiNative-HAL: Setting external_sim to 1
,07-25 18:26:28.699  3697  3931 D wifi    : setting dfs flag to true, 0x7a19fa1100
,07-25 18:26:28.700  3697  3931 D WifiStateMachine: Setting OUI to DA-A1-19
07-25 18:26:28.700  3697  3931 D wifi    : setting scan oui 0x7a19fa1100
07-25 18:26:28.700  3697  3931 D WifiHAL : Sending mac address OUI
07-25 18:26:28.701  9857  9857 D SecurityLogAgent: NetworkReceiver : SendSecurityReport is off
07-25 18:26:28.702  3697  3931 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-25 18:26:28.702  3697  3931 E WifiStateMachine: SupplicantStarted - enter() isAirplaneModeEnabled !!  
07-25 18:26:28.702  3697  3931 D WifiCountryCode: [setCountryCodeNative] Default CSC Country Code : PL
07-25 18:26:28.703 10261 10261 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:28.705 10261 10261 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
,07-25 18:26:28.713  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.713  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.714  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.714  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.714  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.714  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.715  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.716  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.716  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.716  3697  4945 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.730  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.731  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.732  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.732  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.733  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.734  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.734  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.734  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.735  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.736  3697  3776 W NetworkIdentity: Active mobile network without subscriber!
,07-25 18:26:28.740 10261 10261 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-25 18:26:28.741 10261 10261 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:28.747 10193 10193 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-25 18:26:28.749  3697  3931 D WifiCountryCode: Succeeded to set country code to: PL
07-25 18:26:28.749  3697 10019 I ActivityManager: DSS on for com.samsung.hs20provider and scale is 1.0
07-25 18:26:28.749  3697  3931 D wifi    : android_net_wifi_get_firmware_version = 0x7a19fa1100
07-25 18:26:28.750  3697  3931 E WifiHAL : Failed to register debug response; result = -95
07-25 18:26:28.750  3697  3931 E wifi    : Fail to get Firmware version
07-25 18:26:28.750  3697  3931 D wifi    : android_net_wifi_get_driver_version = 0x7a19fa1100
07-25 18:26:28.750  3697  3931 E WifiHAL : Failed to register debug response; result = -95
07-25 18:26:28.750  3697  3931 E wifi    : Fail to get driver version
07-25 18:26:28.750  3697  3931 D wifi    : android_net_wifi_set_log_handler = 0x7a19fa1100
07-25 18:26:28.750  3697  3931 D wifi    : android_net_wifi_get_ring_buffer_status = 0x7a19fa1100
07-25 18:26:28.750  3697  3931 E WifiHAL : Failed to register debug response; result = -95
07-25 18:26:28.750  3697  3931 E WifiLogger: no ring buffers found
07-25 18:26:28.750  3697  3931 D WifiHAL : Start get packet fate command
07-25 18:26:28.750  3697  3931 D WifiHAL : createRequest Monitor packet fate request
07-25 18:26:28.751  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.751  3697  3931 E WifiHAL : Failed to register get pkt fate response; result = -95
,07-25 18:26:28.751  3697  3931 E WifiLogger: Failed to start packet fate monitoring
07-25 18:26:28.751  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.751  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.751  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.752  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.752  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.752  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.752  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.752  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.752  3697  4893 W NetworkIdentity: Active mobile network without subscriber!
07-25 18:26:28.753  3697  4019 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
,07-25 18:26:28.781 10261 10261 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,07-25 18:26:28.785  3697  3926 D WifiP2pService: P2pDisabledState{ what=131203 }
07-25 18:26:28.785  3697  3931 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-25 18:26:28.785  3697  3931 I WifiConnectivityManager: Set WiFi enabled
07-25 18:26:28.785  3697  3931 E WifiStateMachine: ConnectModeState - enter !! - mIsSupportGeofence !!
07-25 18:26:28.786  3697  3931 D WifiStateMachine: Remembered scan first is enabled
07-25 18:26:28.786  3697  3697 I WifiStateMachine: initGeofence
07-25 18:26:28.787  3697  3931 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@bd5993d
07-25 18:26:28.788  3697  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
07-25 18:26:28.788  3697  3931 E wifi    : failed to get channel list : -95
07-25 18:26:28.788  3697  3931 D WifiConfigManager: getChannelsForBand(WifiScanner.WIFI_BAND_24_GHZ) is null. So set default 2.4GHz 14 channels.
07-25 18:26:28.790  3298  3795 D CommandListener: Setting iface cfg
07-25 18:26:28.790  3298  3795 D CommandListener: Trying to bring up p2p0
,07-25 18:26:28.791  3298  3787 D Netd    : Iface p2p0 link up
07-25 18:26:28.791  3697  3926 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-25 18:26:28.791  3697  3931 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170725T182636 - CU:1000/CP:3697
07-25 18:26:28.792  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182636, SetElapsed=299328, nowELAPSED=291330
07-25 18:26:28.792  3697  3926 D SecContentProvider: insert(), uri = 2
07-25 18:26:28.793  3697  3926 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:28.793  3697  3926 D WifiP2pService: P2pEnablingState
07-25 18:26:28.794  3697  3926 D WifiP2pService: P2pEnablingState{ what=147457 }
07-25 18:26:28.794  3697  3926 D WifiP2pService: P2p socket connection successful
07-25 18:26:28.794  3697  3926 D WifiP2pService: P2pEnabledState
,07-25 18:26:28.795  3697  3926 D SecContentProvider: insert(), uri = 2
07-25 18:26:28.795  3697  3926 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:28.799  3697  3828 D Tethering: interfaceLinkStateChanged p2p0, true
07-25 18:26:28.799  3697  3828 D Tethering: interfaceStatusChanged p2p0, true
07-25 18:26:28.799  3697  3830 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-25 18:26:28.799  3697  3830 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-25 18:26:28.799  3697  3830 D WifiDisplayController: disconnect
07-25 18:26:28.799  3697  3830 D WifiDisplayAdapter: onFeatureStateChanged empty
07-25 18:26:28.799  3697  3830 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-25 18:26:28.803  3697  3926 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-25 18:26:28.804  3697  3964 D ConnectivityService: ignoring duplicate network state non-change
07-25 18:26:28.805  3697  3830 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
07-25 18:26:28.809  3697  3931 D WifiStateMachine: setFccChannelNative: channel = 0
07-25 18:26:28.810  3697  3931 D WifiNative-wlan0: callSECApiInt - ID [230]
07-25 18:26:28.810 10261 10261 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-25 18:26:28.813  3697  3931 E WifiConnectivityManager: SingleScanListener onFailure: reason: -1 description: not available
07-25 18:26:28.820 10193 10193 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
,07-25 18:26:28.823 10193 10193 I wpa_supplicant: P2P: Set Samsung Discovery name = 
,07-25 18:26:28.825  3697  3931 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170725T182630 - CU:1000/CP:3697
07-25 18:26:28.825  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182630, SetElapsed=293352, nowELAPSED=291364
07-25 18:26:28.825  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:26:28.830 10194 10194 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-25 18:26:28.830 10194 10194 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
07-25 18:26:28.830 10194 10194 D FileShare: Outbound.stopDelayTimer - 
,07-25 18:26:28.838  4048  4060 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,07-25 18:26:28.842 10261 10272 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-25 18:26:28.842 10261 10272 D HotspotProvider: CREDENTIAL
07-25 18:26:28.842 10261 10272 D HotspotProvider: No prepend tags
07-25 18:26:28.844  3697  3697 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
,07-25 18:26:28.847  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:28.847  3697  3697 D SLocation: system
07-25 18:26:28.847  3697  3697 D SLocation: startGeofence ID = 1
,07-25 18:26:28.852  3697  3931 D WifiNative-wlan0: callSECApiVoid - ID [311]
07-25 18:26:28.853  3697  3958 D HS20StateMachine: updateNumOfHS20Cred, numOfHS20Cred = 1
07-25 18:26:28.853  3697  3958 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-25 18:26:28.853  3697  3958 D HS20StateMachine: enter : DiscoveringState
,07-25 18:26:28.858  4885  4951 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 3ms lastUpdatedAfter : 32880 ms mFlush_time_threasold : 2000 mCurrentSize : 184
,07-25 18:26:28.859  3697  3926 E WifiP2pService: Failed to set my phone number info into probe response
,07-25 18:26:28.863  3697  3926 D WifiNative-HAL: p2pGetDeviceAddress
07-25 18:26:28.863  3697  3926 D WifiNative-HAL: p2pGetDeviceAddress returning 4e:66:41:a9:15:41
,07-25 18:26:28.864  3697  3926 D WifiP2pService: DeviceAddress: 4e:15:41
07-25 18:26:28.865  3697  3830 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:15:41
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  primary type: 10-0050F204-5
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  secondary type: null
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  wps: 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  grpcapab: 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  devcapab: 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  status: 3
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  WFD CtrlPort: 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  WFD MaxThroughput: 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  groupownerAddress: null
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  GOdeviceName: null
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  interfaceAddress: 
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  SConnectInfo : null
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  contactInfoHash : null
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  ssDevInfo : 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  iconIdx : 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  semSamsungDeviceType : 0
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  serviceData : null
07-25 18:26:28.865  3697  3830 D WifiDisplayController:  fw_invite : 0
,07-25 18:26:28.874  3697  3926 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-25 18:26:28.874  3697  3926 D WifiP2pService: InactiveState
07-25 18:26:28.875  3697  3926 D WifiP2pService: InactiveState{ what=143376 }
07-25 18:26:28.875  3697  3926 D WifiP2pService: P2pEnabledState{ what=143376 }
07-25 18:26:28.875  3697  3926 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-25 18:26:28.891  3697  3697 D SLocation: addReceiver type4
07-25 18:26:28.891  3697  3697 D SLocation: already exsit record!
,07-25 18:26:28.922  3697  3697 D SLocation: setPendingIntent
07-25 18:26:28.922  3697  3697 D SLocation: setStatus ID = 1 / status = 3
,07-25 18:26:28.986  3697  3697 D SLocation: geofence id (1) detected : 0
,07-25 18:26:28.987  3697  3697 D WifiStateMachine: startGeofence() - id : 1
,07-25 18:26:28.988  3697  3697 D RttService: SCAN_AVAILABLE : 3
07-25 18:26:28.988  3697  3961 I WifiScanningService: wifi driver loaded with scan capabilities: max buckets=16
07-25 18:26:28.988  3697  3962 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-25 18:26:28.993  3697  3697 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
07-25 18:26:28.994  3697  3697 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,07-25 18:26:28.996  3697  3697 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
07-25 18:26:28.997  4048  4060 D TelephonyProvider: query: match = 7
,07-25 18:26:29.000  3697  3697 D SLocation: PendingIntent onSendFinished id:1
,07-25 18:26:29.069  9791  9891 D BluetoothAdapter: STATE_ON
,07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-25 18:26:29.077  9791  9891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-25 18:26:29.079  9791  9855 D BluetoothAdapter: enable()
,07-25 18:26:29.090  9920  9931 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-25 18:26:29.091  9920  9931 D AdapterProvider: query
,07-25 18:26:29.109  9920  9931 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@33aa6c9
,07-25 18:26:29.113  9920  9931 D BluetoothAdapterService: updateEvent - already set, update
,07-25 18:26:29.114  9920  9931 W BluetoothAdapterService: updateEvent - alreadySet is true
07-25 18:26:29.114  9920  9931 D AdapterProvider: update
,07-25 18:26:29.119  9920  9931 E BluetoothAdapterService: updateEvent - update success 1
,07-25 18:26:29.121  9791  9855 D BluetoothAdapter: enable(): BT is already enabled..!
,07-25 18:26:29.128  3697  4893 D WifiService: setWifiEnabled: true pid=9791, uid=10033
07-25 18:26:29.128  3697  4893 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-25 18:26:29.129  3697  4893 D WifiControlHistoryProvider: query
,07-25 18:26:29.137  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:29.137  3697  4893 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-25 18:26:29.138  3697  4893 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:29.139  3697  4893 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-25 18:26:29.144  3697  4893 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-25 18:26:29.144  3697  4893 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-25 18:26:29.145  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-25 18:26:29.145  9791  9855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:26:29.145  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:26:29.145  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:26:29.145  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-25 18:26:29.145  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad57f50 removed from the list
07-25 18:26:29.146  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ad57f50 removed from the list
07-25 18:26:29.146  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-25 18:26:29.146  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@191c549 removed from the list
07-25 18:26:29.146  9791  9855 D io.jxcore.node.ConnectivityMonitor: stop
07-25 18:26:29.146  9791  9855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:26:29.146  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-25 18:26:29.148  9791  9855 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,07-25 18:26:29.158  9791 10274 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
07-25 18:26:29.158  9791 10274 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-25 18:26:29.627  4645  4645 D io_stats: !@   8,0 r 25264 2272112 w 4996 205944 d 686 74160 f 2017 2017 iot 11640 10704 th 472872 0 0 pt 0 inp 0 0 292.165
,07-25 18:26:29.665  3298  3790 D EnterpriseController: netId is 0
07-25 18:26:29.665  3298  3790 D Netd    : getNetworkForDns: using netid 0 for uid 10033
07-25 18:26:29.665  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-25 18:26:29.671  9791 10276 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,07-25 18:26:29.673  9791 10274 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
07-25 18:26:29.675  9791 10276 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,07-25 18:26:29.675  9791 10274 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-25 18:26:29.675  9791 10276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:26:29.676  9791 10274 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:26:29.676  9791 10276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:26:29.677  9791 10276 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,07-25 18:26:29.678  9791 10274 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-25 18:26:29.678  9791 10278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.678  9791 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:29.678  9791 10278 D io.jxcore.node.StreamCopyingThread:  id: 74
07-25 18:26:29.679  9791 10280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.679  9791 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:29.679  9791 10280 D io.jxcore.node.StreamCopyingThread:  id: 75
07-25 18:26:29.680  9791 10279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 224, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.680  9791 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:29.680  9791 10279 D io.jxcore.node.StreamCopyingThread:  id: 74
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 224, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread:  id: 74
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread:  id: 74
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:26:29.681  9791 10274 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
07-25 18:26:29.681  9791 10279 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,07-25 18:26:29.682  9791 10279 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:26:29.682  9791 10279 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
07-25 18:26:29.682  9791 10279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 224, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.682  9791 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:29.682  9791 10279 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-25 18:26:29.682  9791 10281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 225, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.682  9791 10281 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:29.682  9791 10281 D io.jxcore.node.StreamCopyingThread:  id: 75
07-25 18:26:29.682  9791 10278 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 222, thread name: IncomingSocketThread/Sender): Socket closed
07-25 18:26:29.682  9791 10278 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.682  9791 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:29.682  9791 10278 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-25 18:26:29.683  9791 10278 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-25 18:26:29.683  9791 10278 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-25 18:26:29.683  9791 10278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 222, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.683  9791 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:29.683  9791 10278 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 223, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread:  id: 75
07-25 18:26:29.684  9791 10281 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 225, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.684  9791 10281 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:29.684  9791 10281 D io.jxcore.node.StreamCopyingThread:  id: 75
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread:  id: 75
07-25 18:26:29.684  9791 10281 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.684  9791 10281 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:29.684  9791 10281 D io.jxcore.node.StreamCopyingThread:  id: 75
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:26:29.684  9791 10281 D io.jxcore.node.StreamCopyingThread: closeOutputStr,eam. Flushing
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:26:29.684  9791 10281 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:26:29.684  9791 10280 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:26:29.684  9791 10280 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
07-25 18:26:29.685  9791 10280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.685  9791 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:29.685  9791 10280 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-25 18:26:29.687  9791 10281 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:26:29.687  9791 10281 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:26:29.687  9791 10281 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:26:29.687  9791 10281 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-25 18:26:29.687  9791 10281 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
07-25 18:26:29.687  9791 10281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 225, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:29.687  9791 10281 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:29.687  9791 10281 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,07-25 18:26:29.843  3697  5674 D SSRM:f  : SIOP:: AP = 300, PST = 304 (W:10), CP = 246, CUR = -17, LCD = 57
,07-25 18:26:30.813  3697  3866 D SamsungAlarmManager: Expired : 4
,07-25 18:26:30.814  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182636, SetElapsed=299328, nowELAPSED=293352
07-25 18:26:30.814  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@5c1a51b alarm=Alarm{2aecfce type 2 when 293352 android}
,07-25 18:26:30.817 10193 10193 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-25 18:26:30.817 10193 10193 I wpa_supplicant: P2P: Current p2p state = IDLE
07-25 18:26:30.820  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-25 18:26:30.820  3697  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182645 - CU:1000/CP:3697
,07-25 18:26:30.838  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:30.875 10193 10193 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-25 18:26:31.508  4718  4718 I BeaconBle: 'L' hardware scan: scan stopped, no clients
,07-25 18:26:31.962  5224  5235 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-25 18:26:32.264  3298  3787 D Netd    : Iface wlan0 link up
,07-25 18:26:32.266 10193 10193 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
07-25 18:26:32.268  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:32.268  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:26:32.273  3697  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@f136eef
,07-25 18:26:32.329  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:26:32.347  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:32.359  3697  3931 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=4 roam=false
,07-25 18:26:32.361  3697  3931 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=4
,07-25 18:26:32.381  3697  3931 D WifiConfigStore: saveNetwork skipInternetCheck
,07-25 18:26:32.391  3697  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-25 18:26:32.409  3697 10282 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-25 18:26:32.409  3697 10282 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-25 18:26:32.409  3697 10282 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-25 18:26:32.409  3697 10282 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
,07-25 18:26:32.410  3697 10282 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-25 18:26:32.410  3697 10282 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
,07-25 18:26:32.411  3697 10282 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-25 18:26:32.412  3697 10282 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-25 18:26:32.412  3697 10282 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-25 18:26:32.412  3697 10282 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-25 18:26:32.413  3697 10282 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
,07-25 18:26:32.413  3697 10282 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,07-25 18:26:32.415  3697  3931 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=4
07-25 18:26:32.415  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-25 18:26:32.415  3697  3697 D WifiHs20Service: reason: 2
07-25 18:26:32.416  3697  3960 I WifiHs20Service: Message received 5014
07-25 18:26:32.416  3697  3960 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-25 18:26:32.418  3697 10283 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-25 18:26:32.419  3697 10283 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-25 18:26:32.419  3697 10283 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-25 18:26:32.419  3697 10283 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
,07-25 18:26:32.420  3697 10283 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-25 18:26:32.420 10193 10193 I wpa_supplicant: Trying to associate with F4.E6.C2 (SSID='NG700' freq=2472 MHz)
07-25 18:26:32.420  3697 10283 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-25 18:26:32.420  3697 10283 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-25 18:26:32.420  3697 10283 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
,07-25 18:26:32.420  3697 10283 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-25 18:26:32.420  3697 10283 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-25 18:26:32.421  3697 10283 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-25 18:26:32.421  3697 10283 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-25 18:26:32.421  3697  3931 D SecContentProvider: insert(), uri = 2
,07-25 18:26:32.423  3697  3931 D SecContentProvider: called from android.uid.system:1000
,07-25 18:26:32.437  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:26:32.444  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:32.512  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:26:32.512  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:26:32.512  3298  3787 D Netd    : Iface wlan0 link up
,07-25 18:26:32.516  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:32.517  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:26:32.520  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:32.521  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:26:32.524  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:32.524  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:26:32.529 10193 10193 I wpa_supplicant: Associated with F4.E6.C2
,07-25 18:26:32.534 10193 10193 I wpa_supplicant: wlan0: CTRL-EVENT-SUBNET-STATUS-UPDATE status=0
,07-25 18:26:32.540  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:26:32.548  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:26:32.557  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:32.561 10193 10193 I wpa_supplicant: WPA: Key negotiation completed with F4.E6.C2 [PTK=CCMP GTK=CCMP]
,07-25 18:26:32.562 10193 10193 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.E6.C2 completed [id=4 id_str=%7B%22creatorUid%22%3A%221000%22%2C%22configKey%22%3A%22%5C%22NG700%5C%22WPA_PSK%22%7D]
07-25 18:26:32.563  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:26:32.564  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-25 18:26:32.566  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
,07-25 18:26:32.566  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:26:32.566  3697  3931 D WifiNative-wlan0: callSECApiVoid - ID [50]
,07-25 18:26:32.576  3697  3931 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@dd34415
,07-25 18:26:32.577  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T184156, SetElapsed=1219465, nowELAPSED=295116
,07-25 18:26:32.578  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-25 18:26:32.579  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-25 18:26:32.579  3697  3960 I WifiHs20Service: Message received 5007
,07-25 18:26:32.582  3697  4019 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-25 18:26:32.583  3697  3931 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: mIsSupportAdvancedCaptivePortal is true
07-25 18:26:32.584  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=69632 obj=com.android.internal.util.AsyncChannel@d3d5094 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:26:32.584  3697 10284 D NetworkMonitor: Async - Half connection with WWSM established
,07-25 18:26:32.584  3697  4019 D WifiWatchdogStateMachine: Async - Half connection with NetworkMonitor established
07-25 18:26:32.585  3697  4019 D WifiWatchdogStateMachine: Async - Full connection with NetworkMonitor established
07-25 18:26:32.586  4048  4048 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-25 18:26:32.586  3697  3931 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-25 18:26:32.587  3697  3964 D ConnectivityService: Got NetworkAgent Messenger
,07-25 18:26:32.587  3697  3964 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-25 18:26:32.587  3697  3964 D ConnectivityService: NetworkAgent connected
07-25 18:26:32.587  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:32.592  9920  9920 D BluetoothUtils: readSalesCode :: sales code is XEO
07-25 18:26:32.595  3697  3926 D WifiP2pService: InactiveState{ what=143375 }
07-25 18:26:32.595  3697  3926 D WifiP2pService: P2pEnabledState{ what=143375 }
07-25 18:26:32.596  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:32.596  3697  3931 D WifiHAL : Getting APF capabilities, halHandle = 0x7a19fa1100
07-25 18:26:32.596  3697  3931 I WifiHAL : 
07-25 18:26:32.596  3697  3931 I WifiHAL : createRequest: APF get capabilities request
07-25 18:26:32.598  3697  3931 D WifiHAL : In SetAPFCommand::handleResponse
07-25 18:26:32.598  3697  3931 D WifiHAL : Id = 0, subcmd = 0, len = 16
,07-25 18:26:32.598  3697  3931 D WifiHAL : Response recieved for get packet filter capabilities command
07-25 18:26:32.598  3697  3931 I WifiHAL : APF version is 2
07-25 18:26:32.598  3697  3931 I WifiHAL : APF max len is 2048
07-25 18:26:32.598  3697  3931 I WifiHAL : Done!
07-25 18:26:32.598  3697  3931 D WifiHAL : Getting APF capability, version = 2, max_len = 2048
07-25 18:26:32.598  3697  3931 D wifi    : APF version supported: 2
07-25 18:26:32.598  3697  3931 D wifi    : Maximum APF program size: 2048
07-25 18:26:32.602  3697  3931 D WifiStateMachine: Start Dhcp Watchdog 2
,07-25 18:26:32.609  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-25 18:26:32.612 10074 10074 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-25 18:26:32.621  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:32.632  3697  3964 D ConnectivityService: ignoring duplicate network state non-change
07-25 18:26:32.632  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:32.633  3697  3964 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:26:32.633  3697  3964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-25 18:26:32.633  3697  3964 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,07-25 18:26:32.642 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-25 18:26:32.642  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
07-25 18:26:32.644  3697  3931 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true)
07-25 18:26:32.644  3697  3931 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true) returned: -95
07-25 18:26:32.644  3697  3931 D WifiHAL : Setting APF program, halHandle = 0x7a19fa1100
07-25 18:26:32.644  3697  3931 I WifiHAL : 
07-25 18:26:32.644  3697  3931 I WifiHAL : createRequest: APF set program request
07-25 18:26:32.644 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:26:32.644 10088 10088 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,07-25 18:26:32.645 10088 10088 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
07-25 18:26:32.645  3697  3931 I WifiHAL : Done!
07-25 18:26:32.646  3697  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-25 18:26:32.654 10101 10101 I PhoneErrorReceiver: onReceive
,07-25 18:26:32.660  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-25 18:26:32.662  3697 10285 D ApfFilter: (wlan0): begin monitoring
,07-25 18:26:32.663 10193 10193 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-25 18:26:32.665 10114 10114 I usagelog: received in receiver
07-25 18:26:32.665 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:26:32.665 10114 10114 I KnoxUsageLogPro: premStatus:2
07-25 18:26:32.668 10114 10114 I KnoxUsageLogPro: isEulaShown : false
07-25 18:26:32.668 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:26:32.700  3697  3936 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170725T182708 - CU:1000/CP:3697
07-25 18:26:32.700  3697  3936 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182708, SetElapsed=331237, nowELAPSED=295239
,07-25 18:26:32.702  3697  3964 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-25 18:26:32.702  3697  4019 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-25 18:26:32.703  3697  4019 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-25 18:26:32.703  3697  4019 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
07-25 18:26:32.703  3697  4019 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-25 18:26:32.704  3697  4019 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-25 18:26:32.737  3697  3936 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170725T182708 - CU:1000/CP:3697
,07-25 18:26:32.858  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=131307 obj=start target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-25 18:26:32.858  3697  3926 D WifiP2pService: InactiveState{ what=143375 }
07-25 18:26:32.859  3697  3926 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-25 18:26:32.866  3697 10286 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170725T182634 - CU:1000/CP:3697
07-25 18:26:32.866  3697 10286 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182634, SetElapsed=297412, nowELAPSED=295405
,07-25 18:26:33.778  3697  4829 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:26:33.779  3697  4829 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4319, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-25 18:26:33.780  3697  4829 D BatteryService: online:4, current avg:-12, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-25 18:26:33.780  3697  3697 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:26:33.790  3697  3697 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-25 18:26:33.790  3697  3697 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-25 18:26:33.795  3697  3697 D GameManagerService: new battery level: 100
,07-25 18:26:33.800  4074  4074 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:26:33.800  4074  4074 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:26:33.809  4074  4074 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:26:33.815  4074  4074 D BatteryMeterDrawable: isSomethingChanged - false
07-25 18:26:33.816  4074  4074 D BatteryMeterDrawable: isSomethingChanged - false
,07-25 18:26:33.821  4074  4074 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-25 18:26:33.842  9920  9920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-25 18:26:33.843  9920  9976 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:26:34.633  4645  4645 D io_stats: !@   8,0 r 25267 2272500 w 5029 206200 d 689 74176 f 2020 2020 iot 11650 10712 th 473572 0 0 pt 0 inp 0 0 297.170
,07-25 18:26:34.873  3697  3866 D SamsungAlarmManager: Expired : 4
,07-25 18:26:34.874  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182708, SetElapsed=331237, nowELAPSED=297413
07-25 18:26:34.875  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@7824d2e alarm=Alarm{59310cf type 2 when 297412 android}
,07-25 18:26:34.889  3697 10286 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170725T182638 - CU:1000/CP:3697
07-25 18:26:34.890  3697 10286 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182638, SetElapsed=301414, nowELAPSED=297428
,07-25 18:26:34.891  3697 10286 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-25 18:26:34.892  3697 10286 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@dd76a5c
,07-25 18:26:34.895  3697 10286 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182708, SetElapsed=331237, nowELAPSED=297434
,07-25 18:26:34.902  3697 10286 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170725T182652 - CU:1000/CP:3697
07-25 18:26:34.902  3697 10286 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182652, SetElapsed=315435, nowELAPSED=297441
,07-25 18:26:34.913  3697 10286 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170725T182636 - CU:1000/CP:3697
07-25 18:26:34.914  3697 10286 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182636, SetElapsed=299346, nowELAPSED=297452
,07-25 18:26:34.918  3697 10286 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
,07-25 18:26:34.918  3697 10286 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@159eaeb
07-25 18:26:34.918  3697  3936 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@7f8cb30
,07-25 18:26:34.924  3697 10286 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182652, SetElapsed=315435, nowELAPSED=297462
,07-25 18:26:34.924  3697 10286 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@d6a0e3a
07-25 18:26:34.927  3697 10286 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182708, SetElapsed=331237, nowELAPSED=297466
07-25 18:26:34.928  3697  3926 D WifiP2pService: InactiveState{ what=143375 }
07-25 18:26:34.929  3697  3926 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-25 18:26:34.935  3298  3795 D CommandListener: Setting iface cfg
,07-25 18:26:34.937  3697  4019 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-25 18:26:34.938  3697  3964 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:26:34.942  3697  3964 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-25 18:26:34.943  3697  4019 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-25 18:26:34.944  3697  4019 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-25 18:26:34.945  3697  4019 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
07-25 18:26:34.946  3697  4019 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-25 18:26:34.947  3697  4019 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-25 18:26:34.949  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-25 18:26:34.950  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-25 18:26:34.950  3697  3960 I WifiHs20Service: Message received 5007
07-25 18:26:34.952  3697  3931 D WifiHAL : Setting APF program, halHandle = 0x7a19fa1100
07-25 18:26:34.952  3697  3931 I WifiHAL : 
07-25 18:26:34.952  3697  3931 I WifiHAL : createRequest: APF set program request
07-25 18:26:34.952  3697  4019 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-25 18:26:34.954  3697  3936 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@9d4e073
07-25 18:26:34.955  3697  3931 I WifiHAL : Done!
,07-25 18:26:34.958  4048  4048 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-25 18:26:34.959  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-25 18:26:34.962  9920  9920 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-25 18:26:34.969  3697 10286 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T001210 - CU:1000/CP:3697
,07-25 18:26:34.970  3697  3936 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T184156, SetElapsed=1219465, nowELAPSED=297509
,07-25 18:26:34.972  3697  4019 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-25 18:26:34.972  3697  3964 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-25 18:26:34.973  3697  3964 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:26:34.973  3697  4019 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-25 18:26:34.973  3697  3931 E WifiNative-HAL: setBssidBlacklist cmd 2 size 0
07-25 18:26:34.973  3697  3931 D wifi    : configure BSSID black list request [4] = 0x7a19fa1100
07-25 18:26:34.973  3697  3931 D wifi    : Added 0 bssids
07-25 18:26:34.974  3697  4019 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-25 18:26:34.974  3697  3931 E WifiHAL : Failed to execute bssid blacklist request, result = -95
07-25 18:26:34.974  3697  3931 D WifiStateMachine: sendConnectedState - setManualConnection: false!
07-25 18:26:34.974  3697  4019 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-25 18:26:34.975  3697  3964 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-25 18:26:34.980  3697 10286 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T045634 - CU:1000/CP:3697
,07-25 18:26:34.981 10074 10074 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-25 18:26:34.983  3697 10286 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170726T062634 - CU:1000/CP:3697
07-25 18:26:34.983  3697 10286 D DhcpClient: Scheduling renewal in 20735s
07-25 18:26:34.983  3697 10286 D DhcpClient: Scheduling rebind in 37799s
07-25 18:26:34.983  3697 10286 D DhcpClient: Scheduling expiry in 43199s
07-25 18:26:34.984  3697  3964 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
07-25 18:26:34.984  3697  3964 D ConnectivityService: Adding iface wlan0 to network 503
,07-25 18:26:34.990  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-25 18:26:35.000  3697  3931 D SecContentProvider: insert(), uri = 2
,07-25 18:26:35.002  3697  3931 D SecContentProvider: called from android.uid.system:1000
07-25 18:26:35.002  3697  3697 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-25 18:26:35.003  3697  3931 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-25 18:26:35.003  3697  3697 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-25 18:26:35.003  3238  3238 E audit   : type=1320 audit(1500999994.991:554): 
07-25 18:26:35.003  3697  3697 D HS20StateMachine: SSID : "NG700"
07-25 18:26:35.003  3697  3697 D HS20StateMachine: NetId : 4
07-25 18:26:35.004  3697  3697 D HS20StateMachine: checkifOSUAP  null
07-25 18:26:35.004  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-25 18:26:35.004  3697  3931 I WifiConnectivityManager: scheduleWatchdogTimer
07-25 18:26:35.004  3697  3960 I WifiHs20Service: Message received 5007
,07-25 18:26:35.006  3697  4019 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-25 18:26:35.011  4048  4048 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-25 18:26:35.012  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:35.015  9920  9920 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-25 18:26:35.019  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183338, SetElapsed=720998, nowELAPSED=297558
07-25 18:26:35.020  3697  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T184635 - CU:1000/CP:3697
,07-25 18:26:35.023  3238  3238 E audit   : type=1320 audit(1500999995.011:555): 
,07-25 18:26:35.028 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-25 18:26:35.029  3697  3931 D WifiStateMachine: isFindLocationId() - Location Id : 1
07-25 18:26:35.029  3697  3964 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
07-25 18:26:35.029 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:26:35.029 10088 10088 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-25 18:26:35.030 10088 10088 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
07-25 18:26:35.032  3697  3964 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
07-25 18:26:35.034  3697  3931 D WifiGeofenceDBHelper: update() - 1*1500999995029
07-25 18:26:35.034  3697  3964 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,07-25 18:26:35.037  3697  3964 D ConnectivityService: Setting DNS servers for network 503 to [/192.168.1.1]
07-25 18:26:35.042  3298  7135 D ResolverController: DNSDBG::server[0] 192.168.1.1
07-25 18:26:35.042  3298  7135 D ResolverController: DNSDBG::netId 503 search_domain lan
07-25 18:26:35.042  3298  7135 D ResolverController: DNSDBG::netId 503 searchDomains lan
07-25 18:26:35.042  3298  7135 D ResolverController: DNSDBG::server[0] 192.168.1.1
07-25 18:26:35.042 10101 10101 I PhoneErrorReceiver: onReceive
07-25 18:26:35.048  3697  3964 V NetworkStats: updateIfacesLocked()
07-25 18:26:35.048  3697  3964 V NetworkStats: performPollLocked(flags=0x1)
07-25 18:26:35.048  3697  3964 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.054  3697  3964 V NetworkStats: performPollLocked() took 6ms
07-25 18:26:35.055  3697  3964 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.057 10114 10114 I usagelog: received in receiver
07-25 18:26:35.057 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:26:35.057 10114 10114 I KnoxUsageLogPro: premStatus:2
07-25 18:26:35.057 10114 10114 I KnoxUsageLogPro: isEulaShown : false
07-25 18:26:35.057 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-25 18:26:35.066  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.067  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.067  3697  3964 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,07-25 18:26:35.067  3697  3964 D ConnectivityService: Not required to send intent.
07-25 18:26:35.068  3697  3964 V NetworkStats: updateIfacesLocked()
07-25 18:26:35.068  3697  3964 V NetworkStats: performPollLocked(flags=0x1)
07-25 18:26:35.068  3697  3964 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.075  3697  3964 V NetworkStats: performPollLocked() took 7ms
07-25 18:26:35.075  3697  3964 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:26:35.080  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:26:35.080  3697  3964 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
07-25 18:26:35.080  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
07-25 18:26:35.080  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: register CaptivePortalReceiver
07-25 18:26:35.080  3697  3964 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-25 18:26:35.080  3697  3964 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]
07-25 18:26:35.080  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.081  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.081  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:35.081  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.081  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.081  3697  4019 D WifiWatchdogStateMachine: Connected - Move to CaptivePortalState
07-25 18:26:35.081  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.081  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.082  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.082  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.082  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.082  3697  3964 D ConnectivityService: currentScore = 0, newScore = 20
07-25 18:26:35.082  3697  3964 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
07-25 18:26:35.082  3697  3964 D ConnectivityService:    accepting network in place of null
07-25 18:26:35.082  3697  3964 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.083  3697  4030 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.083  3697  4030 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-25 18:26:35.083  3697  4030 D Ethernet: evalRequest
07-25 18:26:35.083  3697  4030 D Ethernet:   done
07-25 18:26:35.084  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:35.084  3697  3926 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.084  3697  3926 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:35.084  3697  3964 D Con,nectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.084  3697  3926 D WIFI_P2P: evalRequest
07-25 18:26:35.084  3697  3926 D WIFI_P2P:   done
07-25 18:26:35.084  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.085  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.085  4048  4048 D PhoneSwitcherNetworkRequstListener: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.085  4048  4048 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-25 18:26:35.085  4048  4048 D PhoneSwitcherNetworkRequstListener: evalRequest
07-25 18:26:35.087  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.088  3697  4019 E WifiWatchdogStateMachine: current state: com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalState@8a751d6
07-25 18:26:35.088  4048  4048 D PhoneSwitcherNetworkRequstListener:   done
07-25 18:26:35.091  3697  3964 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-25 18:26:35.100  3697  3931 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
,07-25 18:26:35.100 10074 10074 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-25 18:26:35.101 10074 10074 W [RBL] ServiceReceiver: @onReceive - NETWORK_STATE_CHANGED_ACTION
07-25 18:26:35.101  3697  3931 D SLocation: system
07-25 18:26:35.101  3697  3931 D SLocation: startGeofence ID = 1
07-25 18:26:35.104  3697  4019 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
,07-25 18:26:35.108  3238  3238 E audit   : type=1320 audit(1500999995.091:556): 
,07-25 18:26:35.111  3697  4019 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-25 18:26:35.112  3697  4019 D WifiWatchdogStateMachine: start to check Captive portal
,07-25 18:26:35.120  3238  3238 E audit   : type=1320 audit(1500999995.101:557): 
,07-25 18:26:35.121  3298  3795 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-25 18:26:35.128 10074 10074 D [RBL] StoredRequest: @Oncreate
07-25 18:26:35.129 10074 10074 I [RBL] GuardedSuspension: @getInstance
07-25 18:26:35.129 10074 10074 I [RBL] GuardedSuspension: GuardedSuspension
07-25 18:26:35.133  3238  3238 E audit   : type=1320 audit(1500999995.121:558): 
07-25 18:26:35.133  3697  3931 E SLocation: id 1 is already started
07-25 18:26:35.133  3697  3931 D WifiStateMachine: startGeofence() - id : 1, ERROR !!, mResult : -5
07-25 18:26:35.134  3697  3931 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
,07-25 18:26:35.140 10074 10074 I [RBL] GuardedSuspension: @getInstance
07-25 18:26:35.141 10074 10074 D [RBL] RblSAccountUtil: @open
07-25 18:26:35.141 10074 10074 D [RBL] RblSAccountUtil:     - client : 1
07-25 18:26:35.142  3697  3931 D SLocation: system
07-25 18:26:35.143  3697  3931 D SLocation: startLearning ID = 1
07-25 18:26:35.143  3697  3931 D SLocation: setLearningStatus ID = 1 / status = true
07-25 18:26:35.143  3697  3931 D WifiStateMachine: ConnectedState - enter() - startLearning id : 1
07-25 18:26:35.143  3697  3931 D WifiStateMachine: ConnectedState()- id : 1,  startLearning Success !!
,07-25 18:26:35.144  3697  3931 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-25 18:26:35.144  3697  3931 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.145  3697  3931 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:35.145  3697  3931 D WIFI    : evalRequest
07-25 18:26:35.145  3697  3931 D WIFI    :   done
07-25 18:26:35.145  3697  3931 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.145  3697  3931 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:35.145  3697  3931 D WIFI_UT : evalRequest
07-25 18:26:35.145  3697  3931 D WIFI_UT :   done
07-25 18:26:35.145  3697  3931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-25 18:26:35.146  3238  3238 E audit   : type=1320 audit(1500999995.131:559): 
07-25 18:26:35.147  3298  3795 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-25 18:26:35.155  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.155  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.156  4529  4616 D GeolocationController: WIFI : onAvailable
07-25 18:26:35.156  4529  4616 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [true]
07-25 18:26:35.157  3697  3829 D EntConnectivity: Not allowed due to - mEnabled false
,07-25 18:26:35.159 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-25 18:26:35.160 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:26:35.160 10088 10088 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,07-25 18:26:35.162 10088 10088 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 android.content.ContextWrapper.sendBroadcast:452 android.content.ContextWrapper.sendBroadcast:452 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3306 
,07-25 18:26:35.162  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:35.163  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.163  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.164  4529  4618 D PdnController: handleMessage: what 105
07-25 18:26:35.164  4529  4618 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [true]
07-25 18:26:35.164  9791  9855 I io.jxcore.node.IncomingSocketThreadTest: testRun
07-25 18:26:35.165  9791  9855 I !!      :  finally closed
07-25 18:26:35.165  4529  4618 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [true]
07-25 18:26:35.165  4529  4618 D ResipRegiMgr: handleMessage(): 3
07-25 18:26:35.165  4529  4618 D RegiMgrBase: handleMessage: what 3
,07-25 18:26:35.166  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.167  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
07-25 18:26:35.167  9791  9855 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
07-25 18:26:35.168  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
07-25 18:26:35.169  9791  9855 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-25 18:26:35.169  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.169  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:35.171  4529  4618 D RegiMgrBase: onNetworkEventChanged: new=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=true, isEpdgConnected=false]
07-25 18:26:35.171  4529  4618 D RegiMgrBase: onNetworkEventChanged: old=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=false, isEpdgConnected=false]
07-25 18:26:35.172  4529  4618 D RegiMgrBase: out of service.
07-25 18:26:35.172  4529  4618 D RegiMgrBase: onNetworkEventChanged: nTask= 0 nRegisteredTask= 0 bExistRetryTimer= false bHaveRegisteringTask= false
07-25 18:26:35.172  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
07-25 18:26:35.173  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.173  3697  3829 D EntConnectivity: Not allowed due to - mEnabled false
,07-25 18:26:35.174 10101 10101 I PhoneErrorReceiver: onReceive
,07-25 18:26:35.175  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
07-25 18:26:35.175  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.175 10074 10074 D [RBL] RblSAccountUtil:     - DB is opened
07-25 18:26:35.175  9791  9855 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@b8edeac Bundle[{}]
07-25 18:26:35.175 10074 10074 D [RBL] CellDbHelper: @open
07-25 18:26:35.175 10074 10074 D [RBL] CellDbHelper:     - client : 1
07-25 18:26:35.175  3697  3964 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.176  4529  4618 D RegiMgrBase: onNetworkEventChanged: tryRegister
07-25 18:26:35.176  4529  4618 D RegiMgrBase: tryRegister:
07-25 18:26:35.177  3697  3964 D ConnectivityService: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-25 18:26:35.177  3697  3964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-25 18:26:35.178  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
07-25 18:26:35.178  9791  9855 I io.jxcore.node.LifeCycleMonitor: start: OK
07-25 18:26:35.179  9791  9855 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-25 18:26:35.180  4529  4618 D RegiMgrBase: RegisterTask(s) -
07-25 18:26:35.180  4529  4618 D ResipRegiMgr: handleMessage(): 32
07-25 18:26:35.180  4529  4618 D RegiMgrBase: handleMessage: what 32
07-25 18:26:35.180  4529  4618 D RegiMgrBase: onPendingUpdateRegistration: 
07-25 18:26:35.180  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
07-25 18:26:35.180  9791  9855 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-25 18:26:35.181  3697  3964 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
07-25 18:26:35.181  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.181  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:35.181  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:35.181  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:35.181  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:35.181  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.181  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilit,ies: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.182  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-25 18:26:35.183  3697  3964 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-25 18:26:35.183  3697  3964 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-25 18:26:35.183  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.183  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_,RESTRICTED&TRUSTED] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-25 18:26:35.184  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-25 18:26:35.184  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
07-25 18:26:35.184  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:35.184  3697  3697 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-25 18:26:35.184  9791  9855 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-25 18:26:35.184  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3697 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = false
07-25 18:26:35.184  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3697 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-25 18:26:35.184  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.184  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.185  3697  3697 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-25 18:26:35.185  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.185  3697  3919 I KnoxVpnEngineService: vpn handle : Message received
07-25 18:26:35.185  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.185  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.186  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.186  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:35.186  3697  3918 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-25 18:26:35.186  3697  3918 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-25 18:26:35.186  3697  3918 D EnterprisePremiumVpnPolicyServiceV2: run all vpn : runAllVpnService beginning
07-25 18:26:35.186  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
07-25 18:26:35.187  9791  9855 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-25 18:26:35.188  3697  3697 D Tethering: Tethering got CONNECTIVITY_ACTION
07-25 18:26:35.188  9791  9855 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
07-25 18:26:35.188  3697  3965 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-25 18:26:35.188  3697  3965 D Tethering: MasterInitialState.processMessage what=327683
07-25 18:26:35.188  9791  9855 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-25 18:26:35.192  9791  9855 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
07-25 18:26:35.193  9791  9855 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
07-25 18:26:35.195  9791  9855 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
07-25 18:26:35.195  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:35.196  3697  3919 I KnoxVpnEngineService: vpn handle : Message received
07-25 18:26:35.196  3697  3919 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = false
07-25 18:26:35.196  3697  3919 D KnoxVpnEngineService: run all vpn : runAllVpnService beginning
07-25 18:26:35.196  4074  4299 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-25 18:26:35.197  9791  9855 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
07-25 18:26:35.198  9791  9855 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
07-25 18:26:35.199  9791  9855 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
07-25 18:26:35.202  9791  9855 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
07-25 18:26:35.203 10074 10074 D [RBL] CellDbHelper:     - DB is opened
07-25 18:26:35.203 10074 10074 D [RBL] PolicyDbHelper: @open
07-25 18:26:35.203 10074 10074 D [RBL] PolicyDbHelper:     - client : 1
07-25 18:26:35.204  9791 10299 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
07-25 18:26:35.204  9791 10299 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
07-25 18:26:35.206  5069  5069 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF50EC62EA054297E5426D68FE61E03F7CB63D06B4FC0A78A26416AA7E048F840EFBC21D921AABB61599A4C4654ABE1206043CF566A086A1148D0FC76C5AA3DFC0]}
07-25 18:26:35.207  5069  5069 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF006507037EF1FC27CFA959C112FA7F2D1F670CE973374D2DC76D44F7D5EE5AC4ACC17241AE6937FB763E957545037025]}
07-25 18:26:35.208  5069  5069 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF0553125B1A7ADEFBA03E3A7F9CEA3D9489139B6F35BA5D5C6F631797333959D1]}
07-25 18:26:35.212  3697  3922 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
07-25 18:26:35.212  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.212  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.212  5069  5069 D [WeatherWidget(1434)]  AutoRefresh: {[7D74CB60CAF3D3413AB6BB573C0D2852DB29E43AA0DFF8610F50F000609916CC778EE20F4C0BF92710C3F9097DA62F0495DABD0101A657F929F38259D0F4F774]}
07-25 18:26:35.213  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-25 18:26:35.213  3697  3922 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-25 18:26:35.213  3697  3922 D NtpTrustedTime: currentTimeMillis() cache hit
,07-25 18:26:35.215  3697  3922 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
07-25 18:26:35.224  3697  3697 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-25 18:26:35.224  3697  4491 D SLocation: checkWifiInfo
07-25 18:26:35.224  3697  3697 V MARsPolicyManager: DataConnection: true
07-25 18:26:35.226  5224  5224 I CastMediaRouteProvider: Network connectivity changed
07-25 18:26:35.227 10114 10114 I usagelog: received in receiver
07-25 18:26:35.227 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-25 18:26:35.227 10114 10114 I KnoxUsageLogPro: premStatus:2
07-25 18:26:35.228 10114 10114 I KnoxUsageLogPro: isEulaShown : false
07-25 18:26:35.228 10114 10114 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-25 18:26:35.229 10074 10074 D [RBL] PolicyDbHelper:     - DB is opened
07-25 18:26:35.230 10074 10296 D [RBL] StoredRequest: @onHandleIntent
07-25 18:26:35.232  9305  9305 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-25 18:26:35.234  3697  4045 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-25 18:26:35.235  4823  4823 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-25 18:26:35.237  9305  9305 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
07-25 18:26:35.238  3697  4045 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-25 18:26:35.240  9366  9366 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@53a3a21 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:35.242  9305  9305 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
07-25 18:26:35.243  9305  9305 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
07-25 18:26:35.243  9305  9305 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-25 18:26:35.245 10074 10074 D [RBL] CellDbHelper: @close
07-25 18:26:35.245 10074 10074 D [RBL] CellDbHelper:     - client : 0
07-25 18:26:35.245 10074 10074 D [RBL] CellDbHelper:     - DB is closed
07-25 18:26:35.245 10074 10074 D [RBL] PolicyDbHelper: @close
07-25 18:26:35.245 10074 10074 D [RBL] PolicyDbHelper:     - client : 0
07-25 18:26:35.245 10074 10074 D [RBL] PolicyDbHelper:     - DB is closed
07-25 18:26:35.246 10074 10074 D [RBL] RblSAccountUtil: @close
07-25 18:26:35.246 10074 10074 D [RBL] RblSAccountUtil:     - client : 0
07-25 18:26:35.246 10074 10074 D [RBL] RblSAccountUtil:     - DB is closed
07-25 18:26:35.246 10074 10074 D [RBL] StoredRequest: @onDestroy
07-25 18:26:35.251  9791  9791 D BluetoothAdapter: STATE_ON
07-25 18:26:35.254  5069  5069 D [WeatherWidget(1434)]  WidgetCount: {[65C2FDBB08E09D2E8E78BEFE0D618279BC32024A311F60279E75A9FD2AD8BED1]}
07-25 18:26:35.256  8731  8731 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-25 18:26:35.258  9791  9791 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-25 18:26:35.260  9791  9791 D BluetoothAdapter: STATE_ON
07-25 18:26:35.258  9366  9366 I NetworkConnectivity: Network state changed: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]
07-25 18:26:35.264  9791  9791 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-25 18:26:35.265  3697  4491 D SLocation: cellLocation is null
,07-25 18:26:35.267  5069  5069 D [WeatherWidget(1434)]  WidgetCount: {[51D05FFECDA2C35BD99FAAEAA7B9A301F0BE9CFAFD994C3F7B3209384CC66988]}
07-25 18:26:35.269 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
,07-25 18:26:35.269 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-25 18:26:35.270 10088 10088 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
07-25 18:26:35.286  8731  8731 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
,07-25 18:26:35.311  3697  3928 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@b245c42 displayId=0
07-25 18:26:35.312  3697  3928 D InputTransport: Input channel constructed: fd=458
07-25 18:26:35.312  3697  3928 D InputTransport: Input channel constructed: fd=459
07-25 18:26:35.313  3697  3928 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
07-25 18:26:35.314  3697  3928 D InputTransport: Input channel destroyed: fd=459
07-25 18:26:35.315  4074  4299 D InputTransport: Input channel constructed: fd=149
07-25 18:26:35.315  4074  4299 D ViewRootImpl@1528063[Toast]: setView = android.widget.LinearLayout{2d10460 V.E...... ......I. 0,0-0,0 #10204d0 android:id/toast_layout_root} touchMode=true
07-25 18:26:35.315  9366  9366 I NetworkPolicyMonitor: Download-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-25 18:26:35.317  5069  5069 E [WeatherWidget(1434)]  WidgetCount: {[575702F8165D33B66FFE59737B1A62BA08307BCFA3F3A497389D8A1664DA7207C61FE3795BDDA6ED7149C0C90BBA0789F02F175F5575CC50CF5DAAE8904C8914F88792B902BC3E22CDAD80A066BB3E6979730FC110332D83BB2D465425F6B25F89D3F8672D6293DD63CA48A914D2FE41578525C7DFC817959D978B0D1E4AEA3E8237DDDE31DA9CCBB38800CB9D7B42E57A86DA9FF9D55CAD67CE294EA9DE56535F45722BD7BAE690537BE548FCDE8E57ED456836297CA885487DA18C55446062]}
07-25 18:26:35.318  5069  5069 W [WeatherWidget(1434)]  AutoRefresh: {[FD51A315D37AAFC2E139641098576D046D458C57EE37DB6B9263681FFCD40CF01A6772634AEDA0D4B0B223A0763A58EE4BED955A823F243BEAE3A45567F08DD2321854D08A27F4D40285D5771BC7B0FC95FCD4E704A2C776AC2C52FEDFAEF037]}
07-25 18:26:35.319  5069  5069 D [WeatherWidget(1434)]  AutoRefresh: {[D66993CEC2139B42825F15423C8FC37CB81F28161A53B5553937AF4F1AAAEBA916B5697044B6E04751F07B003D46E660A784CB9E3B462E87AEB1AD3F809D90C23EB9D3B97867E467A798739D729C38BF02F8E7F88FD79BFB6259D7DAEFCF9DEF]}
07-25 18:26:35.320  3298  3790 D EnterpriseController: netId is 0
07-25 18:26:35.320  3298  3790 D Netd    : getNetworkForDns: using netid 503 for uid 10001
07-25 18:26:35.320  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-25 18:26:35.325  9366  9366 I NetworkPolicyMonitor: Stream-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-25 18:26:35.328  3697 10019 V WindowManager: Relayout Window{b09a190d0 u0 Toast}: viewVisibility=0 req=755x150 WM.LayoutParams{(0,192)(wrapxwrap) gr=#51 sim=#20 ty=2005 fl=#1040088 fmt=-3 wanim=0x1030004 naviIconColor=0}
07-25 18:26:35.332  3112  3112 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=4, Uoast
07-25 18:26:35.334  8731  8731 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
07-25 18:26:35.357  9366  9366 I DevicePlayback: Got network change: mobile=falsewifi=true
07-25 18:26:35.357  9366  9366 I DevicePlayback: Connectivity restored - clearing all queued disable runnables
07-25 18:26:35.359  3697 10019 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3697 ws=WorkSource{10062} pkg=android
07-25 18:26:35.359  3697 10019 D PowerManagerService: mDisplayReady: false
07-25 18:26:35.360  3697  3832 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:26:35.360  3697  3832 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:26:35.360  3697  3832 D DisplayPowerController: Tracking Direct to etc : 102
07-25 18:26:35.360  3697  3832 D DisplayPowerController: getFinalBrightness : Summary is 102 -> 102
07-25 18:26:35.360  3697  3832 D DisplayPowerController: Animating brightness: target=102, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-25 18:26:35.361  3697  3832 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:26:35.361  3697  3832 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:26:35.361  3697  3832 D DisplayPowerController: getFinalBrightness : Summary is 102 -> 102
07-25 18:26:35.361  3697  3832 D DisplayPowerController: Animating brightness: target=102, rate=500 (PSM:false, AB limit:(-1 ~ -1,) MB Limit:(-1 ~ -1))
07-25 18:26:35.361  3697  3832 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-25 18:26:35.361  3697  3832 D PowerManagerService: mDisplayReady: true
07-25 18:26:35.362  3697  4043 D lights  : lcd : 102 +
,07-25 18:26:35.363  3697  4491 D SLocation: geofence id (1) detected : 0
07-25 18:26:35.367  5069  5069 D [WeatherWidget(1434)]  AutoRefresh: {[3B620F0E62100CD008166B45665AC4E0990189A1A2BD5FD130A6F5AC98AF999B]}
07-25 18:26:35.368  3697  4837 D MountService: getExternalStorageMountMode : 1
07-25 18:26:35.368  3697  4837 D MountService: getExternalStorageMountMode : 3
07-25 18:26:35.368  3697  4837 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.policydm
07-25 18:26:35.373  9942 10298 D NetworkSecurityConfig: No Network Security Config specified, using platform default
07-25 18:26:35.373  4074  4234 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [755x150]-format:1
07-25 18:26:35.375  4074  4299 D ViewRootImpl@1528063[Toast]: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-25 18:26:35.380  3697  4043 D lights  : lcd : 102 -
07-25 18:26:35.380  3697  4043 D DisplayPowerState: Tracking!!: 102
07-25 18:26:35.388  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:35.388  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:35.393  3697  4544 D WindowManager: finishDrawingWindow: Window{b09a190d0 u0 Toast} mDrawState=DRAW_PENDING
07-25 18:26:35.393 10304 10304 E Zygote  : v2
07-25 18:26:35.393 10304 10304 I libpersona: KNOX_SDCARD checking this for 1000
07-25 18:26:35.393 10304 10304 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:35.395 10304 10304 E Zygote  : accessInfo : 0
07-25 18:26:35.396  3697  4837 I ActivityManager: Start proc 10304:com.policydm/1000 for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider
07-25 18:26:35.403  3697  3917 D SamsungAlarmManager: Cancel Alarm calling from uid:10159 pid :5069 / op:PendingIntent{c25319a: PendingIntentRecord{80f3acb com.sec.android.daemonapp broadcastIntent}}
,07-25 18:26:35.405  3298  3790 D EnterpriseController: netId is 0
07-25 18:26:35.405  3298  3790 D Netd    : getNetworkForDns: using netid 503 for uid 10135
07-25 18:26:35.405  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-25 18:26:35.405  5069  5069 D [WeatherWidget(1434)]  AutoRefresh: {[13EBFE39826C141B196DBEF817B05C2B8704215167EB2523B0284BC069F64B74]}
07-25 18:26:35.405 10304 10304 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:35.407 10304 10304 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.policydm 
,07-25 18:26:35.427  5224  5864 W MdnsClient_Cast: #acquireLock. Multicast lock not held. Acquiring. Subtypes:"805741C9"
07-25 18:26:35.429  3697  3931 D WifiHAL : Setting APF program, halHandle = 0x7a19fa1100
07-25 18:26:35.429  3697  3931 I WifiHAL : 
07-25 18:26:35.429  3697  3931 I WifiHAL : createRequest: APF set program request
,07-25 18:26:35.432  3697  3931 I WifiHAL : Done!
07-25 18:26:35.435 10304 10304 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:35.436 10304 10304 D ActivityThread: Added TimaKeyStore provider
07-25 18:26:35.440  3697  3944 I ActivityManager: DSS on for com.policydm and scale is 1.0
,07-25 18:26:35.450  4074  4217 D vol.MediaSessions: onQueueChanged com.google.android.music []
07-25 18:26:35.450  9366  9420 I DevicePlayback: Allowing woodstock playback due to restored connection
,07-25 18:26:35.462  3697  4025 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: GW is reachable. - 248 msec.
07-25 18:26:35.464 10304 10304 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,07-25 18:26:35.470  3697  3928 D WifiScanController: isNLPPackage:com.google.android.gms, true
07-25 18:26:35.470  3697  3931 I WifiScanController: location is disabled
,07-25 18:26:35.479 10304 10304 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:35.494 10304 10304 I FOTA    : [lllIIIIIIlllIlIIIIII(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
07-25 18:26:35.494 10304 10304 I FOTA    : [lllIIIIIIlllIlIIIIII(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,07-25 18:26:35.518 10304 10304 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,07-25 18:26:35.529 10304 10317 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-25 18:26:35.531 10304 10317 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-25 18:26:35.533 10304 10317 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-25 18:26:35.537 10304 10316 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-25 18:26:35.539 10304 10316 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-25 18:26:35.539 10304 10304 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(186/llIIIIlllllIIllIIllI)] try read dbString
,07-25 18:26:35.541 10304 10316 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-25 18:26:35.547  3697  3917 D MountService: getExternalStorageMountMode : 1
07-25 18:26:35.547  3697  3917 D MountService: getExternalStorageMountMode : 3
07-25 18:26:35.547  3697  3917 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.soagent
,07-25 18:26:35.572 10325 10325 E Zygote  : v2
07-25 18:26:35.572 10325 10325 I libpersona: KNOX_SDCARD checking this for 1000
,07-25 18:26:35.572 10325 10325 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:35.573  3697  3917 I ActivityManager: Start proc 10325:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
07-25 18:26:35.573 10325 10325 E Zygote  : accessInfo : 0
07-25 18:26:35.574 10304 10304 I DBG_POLICYDM: [com.policydm.db.XDB(231/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
07-25 18:26:35.578 10325 10325 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-25 18:26:35.579 10325 10325 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.soagent 
,07-25 18:26:35.600 10325 10325 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:35.600 10325 10325 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:35.603  3697  3776 I ActivityManager: DSS on for com.sec.android.soagent and scale is 1.0
,07-25 18:26:35.626 10325 10325 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,07-25 18:26:35.646  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:35.646  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
07-25 18:26:35.646  3697  3931 D WifiStateMachine: User moved, open or psk 24GHz, currentRssi = -40, mQnsUpperRssiThreshold = 200
,07-25 18:26:35.647 10325 10325 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-25 18:26:35.648  3697  3931 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@bd5993d
,07-25 18:26:35.648  3697  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,07-25 18:26:35.651  3697  3931 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170725T182636 - CU:1000/CP:3697
07-25 18:26:35.651  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182636, SetElapsed=299328, nowELAPSED=298190
,07-25 18:26:35.660 10304 10304 I DBG_POLICYDM: [com.policydm.XDMService(164/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,07-25 18:26:35.668 10304 10304 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(455/IIIIIIlIIIllllllIlII)] xdbGetFUMOStatus : 0
,07-25 18:26:35.672  3697  4025 D WifiWatchdogStateMachine:  [|205]
07-25 18:26:35.673 10304 10304 I DBG_POLICYDM: [com.policydm.XDMService(588/llIlIllllllllllllllI)] get NotibarState : 0
,07-25 18:26:35.685  3697  4829 D MountService: getExternalStorageMountMode : 1
07-25 18:26:35.685  3697  4829 D MountService: getExternalStorageMountMode : 3
07-25 18:26:35.685  3697  4829 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10134, packageName : com.sec.android.app.sbrowser
,07-25 18:26:35.705 10343 10343 E Zygote  : v2
07-25 18:26:35.705 10343 10343 I libpersona: KNOX_SDCARD checking this for 10134
,07-25 18:26:35.705 10343 10343 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:35.706 10343 10343 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:26:35.706 10343 10343 E Zygote  : accessInfo : 64
07-25 18:26:35.706 10343 10343 E Zygote  : isSdpEnabledProcess - SDP enabled
07-25 18:26:35.706 10343 10343 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10134 / [uid]: 10134
07-25 18:26:35.706  3298  3790 D EnterpriseController: netId is 0
,07-25 18:26:35.707  3298  3790 D Netd    : getNetworkForDns: using netid 503 for uid 10033
07-25 18:26:35.707  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-25 18:26:35.710  9791 10346 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,07-25 18:26:35.710  9791 10346 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-25 18:26:35.711  9791 10299 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
07-25 18:26:35.711  9791 10346 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-25 18:26:35.711  9791 10299 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-25 18:26:35.712  9791 10299 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:26:35.712  9791 10346 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:26:35.712 10343 10343 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-25 18:26:35.713  9791 10299 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,07-25 18:26:35.713  9791 10349 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 229, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.713  9791 10349 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:35.713  9791 10349 D io.jxcore.node.StreamCopyingThread:  id: 77
,07-25 18:26:35.714 10343 10343 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser:CustomLogger 
07-25 18:26:35.714  9791 10299 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
07-25 18:26:35.714  9791 10346 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
07-25 18:26:35.715  3697  4829 I ActivityManager: Start proc 10343:com.sec.android.app.sbrowser:CustomLogger/u0a134 for content provider com.sec.android.app.sbrowser/.logging.CustomLoggingProvider
07-25 18:26:35.717  9791 10353 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 231, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.717  9791 10353 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:35.717  9791 10353 D io.jxcore.node.StreamCopyingThread:  id: 77
,07-25 18:26:35.717  9791 10350 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 230, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.717  9791 10350 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:35.717  9791 10350 D io.jxcore.node.StreamCopyingThread:  id: 78
07-25 18:26:35.717  9791 10352 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 232, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.717  9791 10352 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:35.717  9791 10352 D io.jxcore.node.StreamCopyingThread:  id: 78
07-25 18:26:35.718  9791 10352 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 232, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.718  9791 10352 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:35.718  9791 10352 D io.jxcore.node.StreamCopyingThread:  id: 78
07-25 18:26:35.718  9791 10352 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.718  9791 10352 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:35.718  9791 10352 D io.jxcore.node.StreamCopyingThread:  id: 78
07-25 18:26:35.718  9791 10352 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:26:35.718  9791 10352 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:26:35.719  9791 10352 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:26:35.719  9791 10352 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:26:35.719  9791 10352 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:26:35.719  9791 10352 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-25 18:26:35.719  9791 10350 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 230, thread name: OutgoingSocketThread/Sender): Socket closed
07-25 18:26:35.719  9791 10352 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 232, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.719  9791 10352 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:35.719  9791 10352 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-25 18:26:35.720  9791 10350 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 230, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.720  9791 10350 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:35.720  9791 10350 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-25 18:26:35.720  9791 10350 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-25 18:26:35.720  9791 10350 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-25 18:26:35.720  9791 10350 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 230, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.720  9791 10350 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:35.720  9791 10350 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-25 18:26:35.720  9791 10353 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 231, thread name: IncomingSocketThr,ead/Receiver): Broken pipe
07-25 18:26:35.721  9791 10353 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 231, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.721  9791 10353 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:35.721  9791 10353 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
07-25 18:26:35.721  9791 10353 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: Broken pipe", this is likely due to peer having disconnected
07-25 18:26:35.721  9791 10353 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
07-25 18:26:35.721  9791 10353 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 231, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.721  9791 10353 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:35.721  9791 10353 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 229, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread:  id: 77
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread:  id: 77
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:26:35.721  9791 10349 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:26:35.722  9791 10349 I io.jxcore.node.IncomingSocketThread: The sending thread is done
07-25 18:26:35.722  9791 10349 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 229, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:35.722  9791 10349 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-25 18:26:35.722  9791 10349 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,07-25 18:26:35.724  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:35.725  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:35.735 10343 10343 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:35.736 10343 10343 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:35.737  3697 10019 I ActivityManager: DSS on for com.sec.android.app.sbrowser and scale is 1.0
,07-25 18:26:35.757 10343 10343 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_5.0/lib/arm
,07-25 18:26:35.769 10343 10343 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:35.776 10343 10343 I cr_ApplicationStatus: initialize application : com.sec.android.app.sbrowser.SBrowserApplication@a2c8114
,07-25 18:26:35.780 10343 10343 D ReflectField: Cannot load field: SDL_INT
07-25 18:26:35.780 10343 10343 E ReflectField: Incorrect type : Fallback exception
07-25 18:26:35.780 10343 10343 D ReflectField: Cannot load field: KEYCODE_EMAIL
07-25 18:26:35.780 10343 10343 E ReflectField: Incorrect type : Fallback exception
,07-25 18:26:35.787  3697  4837 D MountService: getExternalStorageMountMode : 1
07-25 18:26:35.787  3697  4837 D MountService: getExternalStorageMountMode : 3
07-25 18:26:35.787  3697  4837 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.wssyncmldm
,07-25 18:26:35.808 10363 10363 E Zygote  : v2
07-25 18:26:35.808 10363 10363 I libpersona: KNOX_SDCARD checking this for 1000
07-25 18:26:35.808 10363 10363 I libpersona: KNOX_SDCARD not a persona
,07-25 18:26:35.809 10363 10363 E Zygote  : accessInfo : 0
,07-25 18:26:35.812 10363 10363 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-25 18:26:35.813 10363 10363 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.wssyncmldm 
,07-25 18:26:35.813  3697  4837 I ActivityManager: Start proc 10363:com.wssyncmldm/1000 for content provider com.wssyncmldm/com.samsung.android.app.fotaclient.log.MasterLogProvider
,07-25 18:26:35.824 10363 10363 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:35.825 10363 10363 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:35.826  3697  4893 I ActivityManager: DSS on for com.wssyncmldm and scale is 1.0
,07-25 18:26:35.847 10363 10363 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm64
,07-25 18:26:35.861 10363 10363 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:35.867 10363 10363 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(96/onCreate)] 
,07-25 18:26:35.947 10363 10363 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(422/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
07-25 18:26:35.953  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:35.954  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:35.983  3697  6550 I ActivityManager: KPU : put [com.samsung.svoice.sync] : 21100 K
,07-25 18:26:35.983  3697  6550 I ActivityManager: Killing 9324:com.samsung.svoice.sync/u0a40 (adj 906): DHA:empty #33
07-25 18:26:35.984  3697  6550 I ActivityManager: KPU : put [com.samsung.android.themecenter] : 25596 K
07-25 18:26:35.985  3697  6550 I ActivityManager: Killing 7445:com.samsung.android.themecenter/1000 (adj 906): DHA:empty #33
07-25 18:26:35.988  3697  4024 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
07-25 18:26:35.988  3697  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
,07-25 18:26:36.006  3697  4019 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
,07-25 18:26:36.008  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-2ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-25 18:26:36.008  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: MaybeNotifyState{ when=-2ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:26:36.008  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-2ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:26:36.008  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: CMD_ACCEPT_UNVALIDATED_WIFI
07-25 18:26:36.009  3697  3964 D ConnectivityService: NetworkMonitor.CMD_ACCEPT_UNVALIDATED_WIFI network
07-25 18:26:36.009  3697  3964 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-25 18:26:36.009  3697  3964 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-25 18:26:36.009  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:26:36.009  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.009  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.010  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:26:36.010  3697  3964 D ConnectivityService: sending new Min Network Score(100): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:26:36.011  3697  4030 D Ethernet: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:26:36.011  3697  4030 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
,07-25 18:26:36.011  3697  4030 D Ethernet: evalRequest
07-25 18:26:36.011  3697  4030 D Ethernet:   done
,07-25 18:26:36.011  3697  3931 D WIFI    : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:26:36.012  3697  3931 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:36.012  3697  3931 D WIFI    : evalRequest
07-25 18:26:36.012  3697  3931 D WIFI    :   releaseNetworkFor
07-25 18:26:36.012  3697  3931 D WIFI_UT : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.012  3697  3931 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:36.012  3697  3931 D WIFI_UT : evalRequest
07-25 18:26:36.012  3697  3931 D WIFI_UT :   done
07-25 18:26:36.013  3697  3926 D WIFI_P2P: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.013  3697  3926 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-25 18:26:36.013  3697  3926 D WIFI_P2P: evalRequest
07-25 18:26:36.013  3697  3926 D WIFI_P2P:   done
,07-25 18:26:36.014  4048  4048 D PhoneSwitcherNetworkRequstListener: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.014  4048  4048 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-25 18:26:36.014  4048  4048 D PhoneSwitcherNetworkRequstListener: evalRequest
07-25 18:26:36.014  4048  4048 D PhoneSwitcherNetworkRequstListener:   done
07-25 18:26:36.014  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=151655 target=com.android.internal.util.StateMachine$SmHandler }
07-25 18:26:36.014  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: RESULT_VALID
07-25 18:26:36.015  3697 10284 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
07-25 18:26:36.015  3697  3697 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-25 18:26:36.017  3697  3964 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-25 18:26:36.017  3697  3964 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-25 18:26:36.018  3697  3964 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation passed
07-25 18:26:36.027  3697  3964 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-25 18:26:36.028  3697  3964 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-25 18:26:36.028  3697  3964 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]
07-25 18:26:36.028  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.028  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.036  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
0,7-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.037  3697  3964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-25 18:26:36.038  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.038  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:36.038  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
07-25 18:26:36.038  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:36.038  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [] ]
07-25 18:26:36.038  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.046  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.046  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.047  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.047  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.048  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.049  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.049  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.049  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.050  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.050  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.050  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.051  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-25 18:26:36.051  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-25 18:26:36.051  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.052  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.052  3298  3790 D EnterpriseController: netId is 0
07-25 18:26:36.052  3298  3790 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-25 18:26:36.052  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-25 18:26:36.052  3697  3964 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.053  3697  3964 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-25 18:26:36.053  3697  3964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-25 18:26:36.061  3697  3931 D WifiConfigManager: update usableInternet : true
07-25 18:26:36.062  3697 10382 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-25 18:26:36.062  3697 10382 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-25 18:26:36.062  3697 10018 D ActivityManager: cleanUpApplicationRecord -- 9324
07-25 18:26:36.063  3697 10382 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-25 18:26:36.063  3697 10382 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-25 18:26:36.063  3697 10382 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-25 18:26:36.063  3697 10382 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-25 18:26:36.063  4074  4299 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:36.064  3697 10382 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-25 18:26:36.064  3697 10382 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-25 18:26:36.064  3697 10382 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-25 18:26:36.064  3697 10382 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-25 18:26:36.065  3697 10382 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-25 18:26:36.065  3697 10382 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-25 18:26:36.068  4762  6430 D ForegroundUtils: could not check pending caller
07-25 18:26:36.077  5224  5224 E MDM     : [1] SitrepChimeraService.a: No Google accounts; deferring server state update.
07-25 18:26:36.078  4074  4299 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-25 18:26:36.078  3697  4830 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.ConnectivityReceiver newState = 2 callingPackage = 10019
07-25 18:26:36.082  3697  4547 D ActivityManager: cleanUpApplicationRecord -- 7445
07-25 18:26:36.085  4762  4777 D ForegroundUtils: could not check pending caller
07-25 18:26:36.086  3697  3931 D WifiConfigStore: saveNetwork skipInternetCheck
07-25 18:26:36.102  3697  3931 D WifiConfigStore: readNetwork skipInternetCheck
07-25 18:26:36.102  5224  5224 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-25 18:26:36.121  5224  8222 I iu.UploadsManager: num queued entries: 0
07-25 18:26:36.126  5224  8222 I iu.UploadsManager: num updated entries: 0
07-25 18:26:36.130  3697 10383 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-25 18:26:36.130  3697 10383 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-25 18:26:36.130  3697 10383 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
,07-25 18:26:36.130  3697 10383 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-25 18:26:36.131  3697 10383 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-25 18:26:36.131  3697 10383 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-25 18:26:36.131  3697 10383 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-25 18:26:36.131  3697 10383 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-25 18:26:36.132  5224  8222 I iu.SyncManager: NEXT; no task
07-25 18:26:36.133  3697 10383 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-25 18:26:36.133  3697 10383 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-25 18:26:36.133  3697 10383 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-25 18:26:36.133  3697 10383 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-25 18:26:36.137 10363 10363 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(297/lllIlIlIIIllIIlIllIl)] Voice : true
07-25 18:26:36.138  3697  3697 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-25 18:26:36.138  3697  3697 D WifiHs20Service: reason: 2
07-25 18:26:36.139  3697  3960 I WifiHs20Service: Message received 5014
07-25 18:26:36.139  3697  3960 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-25 18:26:36.141 10363 10363 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(298/lllIlIlIIIllIIlIllIl)] SMS : true
07-25 18:26:36.143 10363 10363 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(299/lllIlIlIIIllIIlIllIl)] isDataOnly : false
07-25 18:26:36.155  3697  3964 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
07-25 18:26:36.160 10128 10128 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
07-25 18:26:36.160 10128 10128 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? ]
07-25 18:26:36.160 10128 10128 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-25 18:26:36.175 10128 10128 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-25 18:26:36.175 10128 10128 I SA      : [OR] == isSIMCardReady false ==
07-25 18:26:36.178 10128 10128 I SA      : [SCU] == networkStateCheck == true
,07-25 18:26:36.178 10128 10128 I SA      : [DM] getCountryCodeFromCSC : PL
07-25 18:26:36.178 10128 10128 I SA      : isChinaCountryCode : false
07-25 18:26:36.179 10128 10128 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-25 18:26:36.179 10128 10128 I SA      : [OR] == networkStateCheck true ==
,07-25 18:26:36.191 10363 10363 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(645/IllIlIIIIlIIlIIIllIl)] bootTime: 1500999718759
,07-25 18:26:36.193  3697  3957 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170725T185636 - CU:10124/CP:5123
,07-25 18:26:36.204 10363 10363 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(638/lllIlIlIIIllIIlIllIl)] bootTime: 1500999718759, savedBootTime: 1500000484534
,07-25 18:26:36.221 10363 10363 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3131/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-25 18:26:36.222 10128 10128 I SA      : [OR] GetMyCountryZoneTask
07-25 18:26:36.223 10128 10128 I SA      : [OR] onReceive END
07-25 18:26:36.232 10363 10363 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3184/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
07-25 18:26:36.233  3697  4492 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / op:PendingIntent{50bf2df: PendingIntentRecord{1908b2c android broadcastIntent}}
07-25 18:26:36.243  3697  4492 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170726T182636 - CU:1000/CP:3697
07-25 18:26:36.247 10363 10363 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3237/IllIlIIIIlIIlIIIllIl)] xdmdbsqlGetNotiSaveState : 0
,07-25 18:26:36.255 10151 10151 I SVCAgent: Ignore network change.
,07-25 18:26:36.262 10363 10363 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3386/llllllIllIlIlllIIlIl)] xdmdbsqlGetFumoInitType : 0
07-25 18:26:36.264 10363 10363 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(93/onCreate)] DMApplication NOT Start !
,07-25 18:26:36.271 10164 10164 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-25 18:26:36.284  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-25 18:26:36.295  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:36.295  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:36.297  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-25 18:26:36.297  3697  3826 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
07-25 18:26:36.299 10128 10387 I SA      : [SRS] prepareGetMyCountryZone
07-25 18:26:36.299  8013  8013 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
07-25 18:26:36.299  8013  8013 E SPPClientService: [SystemStateMoniter] Current Time : 298838
07-25 18:26:36.300  8013  8013 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-25 18:26:36.315  3697  3707 I art     : Background sticky concurrent mark sweep GC freed 180914(12MB) AllocSpace objects, 25(548KB) LOS objects, 26% free, 41MB/56MB, paused 3.578ms total 116.753ms
07-25 18:26:36.315  3697  3697 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
,07-25 18:26:36.316  3697  3697 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,07-25 18:26:36.319  3697  3697 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,07-25 18:26:36.320 10128 10387 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-25 18:26:36.323 10128 10387 I SA      : [SSP] query invoked
07-25 18:26:36.324  3697  4022 D WifiWatchdogStateMachine:  [|205] []
,07-25 18:26:36.331  3697  3697 D SLocation: PendingIntent onSendFinished id:1
07-25 18:26:36.331 10128 10387 I SA      : [TPMU] GetMccFromDB : null
07-25 18:26:36.331 10128 10387 I SA      : [SCU] getMccFromPreferece mcc = 260
07-25 18:26:36.332 10128 10387 I SA      : [LBE] isSupportCheckDomainRegion : true
07-25 18:26:36.332 10128 10387 I SA      : [TPM] isNoProxy(default) : true
,07-25 18:26:36.336 10128 10387 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-25 18:26:36.354  3697  4544 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{bcb77f9: PendingIntentRecord{f85cc4c com.google.android.gms broadcastIntent}}
,07-25 18:26:36.420  3697  4547 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170725T192235 - CU:10019/CP:4718
,07-25 18:26:36.466  3697  6550 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170725T183836 - CU:10019/CP:4718
,07-25 18:26:36.493  3697 10019 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{e8fd6ec: PendingIntentRecord{d1a0671 com.google.android.gms broadcastIntent}}
,07-25 18:26:36.500  3697  4547 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170725T183836 - CU:10019/CP:4718
,07-25 18:26:36.528  3697  4829 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{d429ab5: PendingIntentRecord{f85cc4c com.google.android.gms broadcastIntent}}
,07-25 18:26:36.549  3697  4838 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170725T192235 - CU:10019/CP:4718
,07-25 18:26:36.566  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:36.567  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:36.739  4718 10390 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-25 18:26:36.748  4718 10390 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-25 18:26:36.762  3697 10018 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:36.789  3697  3866 D SamsungAlarmManager: Expired : 4
07-25 18:26:36.789  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183338, SetElapsed=720999, nowELAPSED=299328
07-25 18:26:36.790  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@854b8a7 alarm=Alarm{8cf2d31 type 2 when 299328 android}
,07-25 18:26:36.791  3697  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
07-25 18:26:36.793 10193 10193 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-25 18:26:36.794 10193 10193 I wpa_supplicant: P2P: Current p2p state = IDLE
07-25 18:26:36.795  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:36.795  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:36.796  3697  3931 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170725T182644 - CU:1000/CP:3697
07-25 18:26:36.796  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182644, SetElapsed=307330, nowELAPSED=299335
07-25 18:26:36.796 10193 10193 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-25 18:26:36.799  3697  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182651 - CU:1000/CP:3697
,07-25 18:26:36.830  4718 10390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:36.831  4718 10390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:36.832  3298  3790 D EnterpriseController: netId is 0
07-25 18:26:36.832  3298  3790 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-25 18:26:36.832  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-25 18:26:36.908 10128 10387 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
07-25 18:26:36.908 10128 10387 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-25 18:26:36.910 10128 10387 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-25 18:26:36.912 10128 10387 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:36.912 10128 10387 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:36.914  3298  3790 D EnterpriseController: netId is 0
07-25 18:26:36.914  3298  3790 D Netd    : getNetworkForDns: using netid 503 for uid 10041
07-25 18:26:36.914  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-25 18:26:37.306  4074  4299 D ViewRootImpl@1528063[Toast]: dispatchDetachedFromWindow
,07-25 18:26:37.319  3697  3928 D InputTransport: Input channel destroyed: fd=458
07-25 18:26:37.320  3697  3928 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3697) eventTime = 299858
,07-25 18:26:37.320  3697  3928 D PowerManagerService: [s] UserActivityState : 4 -> 1
07-25 18:26:37.322  3697  3928 D PowerManagerService: [api] release WakeLock SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3697, ws=WorkSource{10062}) (uid=1000, pid=3697, ws=WorkSource{10062}, pkg=android, elapsedTime=1962) (0x0)
,07-25 18:26:37.322  3697  3928 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3697, ws=WorkSource{10062}) (uid=1000, pid=3697, ws=WorkSource{10062}, pkg=android, elapsedTime=1963)
,07-25 18:26:37.325  4074  4299 D InputTransport: Input channel destroyed: fd=149
,07-25 18:26:37.518  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:37.519  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:37.701  3697 10018 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.718  3697  6617 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.732  3697  4838 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.746  3697 10019 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.761  3697  3777 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.778  3697  3944 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.791  3697  6550 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.805  3697  4837 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-25 18:26:37.805 10128 10387 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 895
,07-25 18:26:37.819  3697  3948 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.832  3697  3917 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.842  3697  4893 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.850 10128 10387 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,07-25 18:26:37.850 10128 10387 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-25 18:26:37.853  3697  4838 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-25 18:26:37.853 10128 10387 I SA      : [OCP]  Cursor is not null
,07-25 18:26:37.858 10128 10387 I SA      : [OCP] update openData : EU
,07-25 18:26:37.864  3697  3830 I WindowManager: Destroying surface Surface(name=Toast) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementInner:499 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementLoop:274 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacement:222 com.android.server.wm.WindowManagerService$H.handleMessage:9166 android.os.Handler.dispatchMessage:102 
,07-25 18:26:37.864  3697 10018 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.864 10128 10387 I SA      : [TPMU] getNetworkMcc : 
07-25 18:26:37.864  3112  3119 I SurfaceFlinger: id=17 Removed Uoast (5/5)
07-25 18:26:37.865  3112  3121 I SurfaceFlinger: id=17 Removed Uoast (-2/5)
,07-25 18:26:37.869 10128 10387 I SA      : [SRS] prepareGetMyCountryZone
,07-25 18:26:37.877  3697  3944 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
07-25 18:26:37.878 10128 10387 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-25 18:26:37.878 10128 10387 I SA      : [SSP] query invoked
,07-25 18:26:37.883 10128 10387 I SA      : [TPMU] GetMccFromDB : null
07-25 18:26:37.883 10128 10387 I SA      : [SCU] getMccFromPreferece mcc = 260
07-25 18:26:37.883 10128 10387 I SA      : [LBE] isSupportCheckDomainRegion : true
07-25 18:26:37.883 10128 10387 I SA      : [TPM] isNoProxy(default) : true
,07-25 18:26:37.885 10128 10387 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
07-25 18:26:37.885 10128 10387 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-25 18:26:37.886  3697 10018 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:37.887 10128 10387 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-25 18:26:37.888 10128 10387 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:37.889 10128 10387 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:37.898  4718 10390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:37.899  4718 10390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:38.246  4718 10390 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-25 18:26:38.257  3697  3776 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-25 18:26:38.282  4718 10390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:38.282  4718 10390 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:38.521  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:38.523  9942 10298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:38.658  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:38.658  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:26:39.085 10128 10387 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 1198
,07-25 18:26:39.091 10128 10387 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,07-25 18:26:39.092 10128 10387 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-25 18:26:39.097 10128 10387 I SA      : [OCP]  Cursor is not null
,07-25 18:26:39.108 10128 10387 I SA      : [OCP] update openData : EU
,07-25 18:26:39.115 10128 10387 I SA      : [TPMU] getNetworkMcc : 
,07-25 18:26:39.117 10128 10387 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1231
07-25 18:26:39.118 10128 10387 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-25 18:26:39.118 10128 10387 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 2209
07-25 18:26:39.118 10128 10387 I SA_HTTPURLCONNECTION: [RC New] Execute end
,07-25 18:26:39.120 10128 10128 I SA      : [OR] GetMyCountryZoneTask mcc = null
,07-25 18:26:39.125 10128 10128 I SA      : [OR] GetMyCountryZoneTask Fail
,07-25 18:26:39.128  4718 10390 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-25 18:26:39.178  3697  3917 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170725T192235 - CU:10019/CP:4718
,07-25 18:26:39.188  3697  4945 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{65fd7ee: PendingIntentRecord{f85cc4c com.google.android.gms broadcastIntent}}
,07-25 18:26:39.207  3697  3928 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170725T192235 - CU:10019/CP:4718
,07-25 18:26:39.639  4645  4645 D io_stats: !@   8,0 r 25283 2273508 w 5197 209172 d 732 74432 f 2088 2088 iot 11750 10826 th 468980 0 0 pt 0 inp 0 0 302.176
,07-25 18:26:39.874  3697  5674 D SSRM:f  : SIOP:: AP = 300, PST = 306 (W:10), CP = 245, CUR = -6, LCD = 102
,07-25 18:26:40.185  3697  3811 I ActivityManager: Waited long enough for: ServiceRecord{538c19c u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,07-25 18:26:40.786  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:26:40.788 10193 10193 I wpa_supplicant: nl80211: Received scan results (35 BSSes)
,07-25 18:26:40.788  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:40.788  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:26:40.791  3697  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@d071997
,07-25 18:26:41.207  9791  9855 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,07-25 18:26:41.210  9791  9855 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,07-25 18:26:41.215  9791  9855 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,07-25 18:26:41.323  3697  3832 D PowerManagerService: [s] UserActivityState : 1 -> 4
07-25 18:26:41.323  3697  3832 D PowerManagerService: mDisplayReady: false
07-25 18:26:41.323  3697  3832 I PowerManagerService: [PWL] On : 0 (303862 ms ago)
07-25 18:26:41.324  3697  3832 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
07-25 18:26:41.324  3697  3832 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-25 18:26:41.324  3697  3832 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:26:41.324  3697  3832 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:26:41.324  3697  3832 D DisplayPowerController: Animating brightness: target=57, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-25 18:26:41.325  3697  3832 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-25 18:26:41.326  3697  3832 D PowerManagerService: mDisplayReady: true
,07-25 18:26:41.337  3697  4043 D lights  : lcd : 82 +
,07-25 18:26:41.344  3697  4043 D lights  : lcd : 82 -
,07-25 18:26:41.353  3697  4043 D lights  : lcd : 57 +
07-25 18:26:41.353  3697  3832 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-25 18:26:41.353  3697  3832 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-25 18:26:41.354  3697  3832 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-25 18:26:41.354  3697  3832 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-25 18:26:41.355  3697  4043 D lights  : lcd : 57 -
,07-25 18:26:41.688  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:41.689  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:26:42.225  9791  9855 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,07-25 18:26:42.228  9791  9855 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,07-25 18:26:42.233  9791  9855 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,07-25 18:26:42.233  9791  9855 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 240)
,07-25 18:26:42.237  9791  9855 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,07-25 18:26:42.238  9791  9855 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-25 18:26:42.238  9791  9855 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 241)
,07-25 18:26:42.242  9791  9855 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,07-25 18:26:42.246  9791  9855 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,07-25 18:26:42.249  9791  9855 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,07-25 18:26:42.251  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-25 18:26:42.252  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa86d05 added. We now have 2 listener(s)
07-25 18:26:42.252  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa86d05 added. We now have 3 listener(s)
07-25 18:26:42.252  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-25 18:26:42.256  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:42.256  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-25 18:26:42.256  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:42.257  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-25 18:26:42.257  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc215a added. We now have 4 listener(s)
07-25 18:26:42.257  9791  9855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-25 18:26:42.258  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-25 18:26:42.267  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.274  9791  9855 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,07-25 18:26:42.276  9791  9855 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,07-25 18:26:42.277  9791  9855 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
07-25 18:26:42.277  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
07-25 18:26:42.277  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:26:42.282  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:42.282  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:42.283  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.283  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:26:42.287  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:42.287  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:42.287  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.288  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-25 18:26:42.288  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:26:42.288  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:26:42.288  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-25 18:26:42.291  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-25 18:26:42.292  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-25 18:26:42.292  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:26:42.292  9791 10402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:26:42.292  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:26:42.292  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-25 18:26:42.292  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-25 18:26:42.293  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:26:42.293  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-25 18:26:42.293  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-25 18:26:42.296  9791 10402 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:42.296  9791 10402 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-25 18:26:42.301  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-25 18:26:42.301  9791  9855 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:26:42.301  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-25 18:26:42.302  9791 10402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:26:42.303  9791 10402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@499e868, port: 6, type: 1, local socket address: null, socket type: 0
,07-25 18:26:42.306  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.307  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.309  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.312  9791  9855 D BluetoothAdapter: isSecureModeEnabled
,07-25 18:26:42.312  9920  9931 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:42.313  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.314  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-25 18:26:42.315  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.317  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.317  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:26:42.317  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:26:42.317  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-25 18:26:42.320  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.324  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.324  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.324  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:26:42.324  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-25 18:26:42.324  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-25 18:26:42.325  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 4A 3E
07-25 18:26:42.325  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:42.325  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-25 18:26:42.326  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.327  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.327  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:26:42.327  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:42.328  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.328  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.329  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.330  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.332  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:42.332  9791  9855 D BluetoothAdapter: isSecureModeEnabled
,07-25 18:26:42.333  9920  9997 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:42.333  9791  9855 D BluetoothLeAdvertiser: start advertising
,07-25 18:26:42.335  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:42.342  9920  9932 D BtGatt.GattService: registerClient() - UUID=19e46693-ee01-462e-89c1-b6d0b8c2f626
,07-25 18:26:42.447  9920  9940 D BtGatt.GattService: onClientRegistered() - UUID=19e46693-ee01-462e-89c1-b6d0b8c2f626, clientIf=5, status=0
,07-25 18:26:42.450  9791  9803 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-25 18:26:42.455  9920  9997 E BtGatt.ContextMap: Context not found for ID 5
,07-25 18:26:42.457  9920  9967 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-25 18:26:42.457  9920  9956 D BtGatt.AdvertiseManager: message : 0
07-25 18:26:42.460  9920  9956 D BtGatt.AdvertiseManager: number of adv instance running = 0
,07-25 18:26:42.460  9920  9956 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:26:42.469  9920  9956 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:26:42.475  9920  9956 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:26:42.479  9920  9973 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-25 18:26:42.498  9920  9940 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-25 18:26:42.502  9920  9956 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:26:42.514  9920  9940 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-25 18:26:42.515  9920  9956 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-25 18:26:42.515  9920  9956 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,07-25 18:26:42.515  9920  9956 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-25 18:26:42.516  9920  9956 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-25 18:26:42.517  9791  9802 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
07-25 18:26:42.518  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.520  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.520  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-25 18:26:42.521  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.522  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.523  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.524  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.525  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.525  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-25 18:26:42.530  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-25 18:26:42.531  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.537  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:42.538  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.539  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:42.541  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-25 18:26:42.543  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-25 18:26:42.545  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:42.545  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-25 18:26:42.546  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-25 18:26:42.548  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-25 18:26:42.549  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-25 18:26:42.550  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,07-25 18:26:42.554  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-25 18:26:42.554  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-25 18:26:42.555  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:42.556  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-25 18:26:42.557  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-25 18:26:42.558  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-25 18:26:42.559  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:42.565  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-25 18:26:42.565  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:26:42.566  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:42.566  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:42.567  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-25 18:26:43.048  9791  9855 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-25 18:26:43.049  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
07-25 18:26:43.049  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-25 18:26:43.049  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-25 18:26:43.049  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-25 18:26:43.049  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,07-25 18:26:43.051  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-25 18:26:43.051  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:26:43.051  9791 10402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:26:43.051  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:26:43.052  9791 10402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:26:43.052  9791 10402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:26:43.052  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-25 18:26:43.052  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:26:43.053  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.053  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:26:43.053  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:26:43.055  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.055  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-25 18:26:43.055  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.056  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:43.057  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:43.061  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:43.065  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:43.065  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-25 18:26:43.068  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:43.071  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:43.072  9791  9855 D BluetoothLeScanner: could not find callback wrapper
07-25 18:26:43.072  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:26:43.073  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:43.074  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.076  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:43.076  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-25 18:26:43.077  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:43.080  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:43.084  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:43.084  9791  9855 D BluetoothLeAdvertiser: stop advertising
,07-25 18:26:43.087  9920  9997 E BtGatt.ContextMap: Context not found for ID 5
,07-25 18:26:43.088  9920  9956 D BtGatt.AdvertiseManager: message : 1
07-25 18:26:43.088  9920  9967 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:26:43.090  9920  9956 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-25 18:26:43.090  9920  9956 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-25 18:26:43.094  9920  9956 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:26:43.101  9920  9940 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-25 18:26:43.101  9920  9940 D BtGatt.GattService: Client app is not null!
,07-25 18:26:43.102  9791  9803 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-25 18:26:43.103  9920  9995 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-25 18:26:43.105  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-25 18:26:43.106  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.106  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-25 18:26:43.107  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.107  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.108  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.108  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-25 18:26:43.108  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-25 18:26:43.110  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:26:43.110  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:43.114  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.114  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:26:43.115  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.115  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:43.116  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-25 18:26:43.116  9791  9791 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-25 18:26:43.117  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,07-25 18:26:43.117  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:26:43.117  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:43.117  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:43.118  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-25 18:26:43.118  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:43.119  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:43.119  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:26:43.119  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-25 18:26:43.120  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:43.120  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:26:43.120  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:43.121  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-25 18:26:43.622  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-25 18:26:44.644  4645  4645 D io_stats: !@   8,0 r 25283 2273508 w 5250 209612 d 733 74436 f 2090 2090 iot 11760 10836 th 472132 0 0 pt 0 inp 0 0 307.182
,07-25 18:26:44.722  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:44.722  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:26:44.791  3697  3866 D SamsungAlarmManager: Expired : 4
,07-25 18:26:44.792  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183338, SetElapsed=720999, nowELAPSED=307331
07-25 18:26:44.793  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@4e15c16 alarm=Alarm{de9faab type 2 when 307330 android}
,07-25 18:26:44.797  3697  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,07-25 18:26:44.800 10193 10193 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-25 18:26:44.800 10193 10193 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-25 18:26:44.806  3697  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182700 - CU:1000/CP:3697
07-25 18:26:44.808  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=307346
,07-25 18:26:44.814  3697  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182659 - CU:1000/CP:3697
,07-25 18:26:44.817 10193 10193 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-25 18:26:45.013  3697 10407 D WifiMHD::s: req(2):1, 7, 1
,07-25 18:26:45.016  3697 10407 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-25 18:26:45.018  3697 10407 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:26:45.022  3298  3790 D EnterpriseController: netId is 0
,07-25 18:26:45.022  3298  3790 D Netd    : getNetworkForDns: using netid 503 for uid 1000
07-25 18:26:45.023  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-25 18:26:45.386  3697  4022 D WifiWatchdogStateMachine:  [|214] []
,07-25 18:26:46.124  9791  9855 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,07-25 18:26:46.125  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-25 18:26:46.125  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-25 18:26:46.126  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-25 18:26:46.126  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-25 18:26:46.126  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:26:46.126  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-25 18:26:46.145  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-25 18:26:46.146  9791  9855 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:26:46.146  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-25 18:26:46.156  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:46.160  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.164  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.168  9791  9855 D BluetoothAdapter: isSecureModeEnabled
07-25 18:26:46.169  9920  9932 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:46.171  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:46.171  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-25 18:26:46.174  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:46.177  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:46.177  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:26:46.177  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-25 18:26:46.177  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-25 18:26:46.184  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.186  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:46.191  4074  4074 D ShortcutManager: onReceive : android.intent.action.PACKAGE_CHANGED
,07-25 18:26:46.192  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.193  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.195  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:46.195  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-25 18:26:46.196  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-25 18:26:46.196  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 40909
07-25 18:26:46.197  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=40909, mManufacturerData=null, mManufacturerDataMask=null]
,07-25 18:26:46.197  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:46.198  9791  9855 D BluetoothLeScanner: Start Scan
07-25 18:26:46.199  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.200  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.204  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.205  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:46.209  9920  9941 D BtGatt.GattService: registerClient() - UUID=f273bb60-02e1-4d7d-a957-1e77285929d3
,07-25 18:26:46.232  3697  6550 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5123, uid=10124 that is not exported from uid 10122
,07-25 18:26:46.232  4762  4762 D RegisteredServicesCache: invalidateCache
07-25 18:26:46.234  3697  3886 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-25 18:26:46.248  3697  3838 D PackageManager: com.google.android.gms.permission.CAR_FUEL is a new runtime permission
07-25 18:26:46.248  3697  3838 D PackageManager: com.google.android.gms.permission.CAR_MILEAGE is a new runtime permission
07-25 18:26:46.248  3697  3838 D PackageManager: com.google.android.gms.permission.CAR_SPEED is a new runtime permission
,07-25 18:26:46.248  3697  3838 D PackageManager: com.google.android.gms.permission.CAR_VENDOR_EXTENSION is a new runtime permission
07-25 18:26:46.248  3697  3838 D PackageManager: Permission Group is null for permission com.sec.smartcard.permission.SMARTCARD_ADAPTER
07-25 18:26:46.248  3697  3838 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_READ
07-25 18:26:46.248  3697  3838 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_WRITE
07-25 18:26:46.248  3697  3838 D ApplicationPolicy: groups[android.permission-group.SMS, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.LOCATION, android.permission-group.MESSAGES, android.permission-group.SMS, android.permission-group.SENSORS, android.permission-group.LOCATION, android.permission-group.SMS, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.MESSAGES, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.SMS, android.permission-group.PHONE, android.permission-group.CONTACTS, android.permission-group.CAMERA, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.SMS, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, android.permission-group.CONTACTS, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.STORAGE, com.samsung.android.memo.EXTRA_READ, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.MICROPHONE, android.permission-group.CONTACTS, com.samsung.android.memo.EXTRA_WRITE, android.permission-group.PHONE]
07-25 18:26:46.248  3697  3838 D ApplicationPolicy: Permission GRoups [android.permission-group.CONTACTS, android.permission-group.CALENDAR, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.MICROPHONE, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, com.samsung.android.memo.EXTRA_READ, com.samsung.android.memo.EXTRA_WRITE]
,07-25 18:26:46.252  4762  4762 D ApduServiceInfo: seId: 0
,07-25 18:26:46.254  4762  4762 D ApduServiceInfo: seId: 0
,07-25 18:26:46.255  4762  4762 D RegisteredOthersCache: start invalidate
07-25 18:26:46.255  4762  4762 D RegisteredOthersCache: update valid otherService: ComponentInfo{com.google.android.apps.walletnfcrel/com.google.commerce.tapandpay.android.hce.service.ValuableApduService} AIDs: [4F53452E5641532E3031, A000000476D0000101, A000000476D0000111]
07-25 18:26:46.255  4762  4762 D RegisteredOthersCache: Existed other serivcee
,07-25 18:26:46.255  4762  4762 D RegisteredPoliciesCache: invalidate
07-25 18:26:46.255  4762  4762 D RegisteredAidCache: onServicePolicyUpdated
07-25 18:26:46.255  4762  4762 D RegisteredAidCache: generateAidPolicyMapLocked
07-25 18:26:46.255  4762  4762 D AidPolicyManager: print policy
07-25 18:26:46.255  4762  4762 D AidPolicyManager: table size : 0
,07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
,07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidPolicyManager: There are not service policy for this aid
07-25 18:26:46.263  4762  4762 D AidRoutingManager: Override power table is not changed
07-25 18:26:46.266  4048  4048 D CarrierSvcBindHelper: No carrier app for: 0
07-25 18:26:46.267  4762  4762 D RegisteredNfcFServicesCache: Service unchanged, not updating
,07-25 18:26:46.272  4762  4762 D RegisteredComponentCache: Collect Tech packages for Knox
,07-25 18:26:46.311  9920  9940 D BtGatt.GattService: onClientRegistered() - UUID=f273bb60-02e1-4d7d-a957-1e77285929d3, clientIf=5, status=0
,07-25 18:26:46.312  9791  9802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
07-25 18:26:46.312  9920  9931 D BtGatt.GattService: start scan with filters
,07-25 18:26:46.315  9920  9931 D BtGatt.GattService: getScanSettings
,07-25 18:26:46.319  9920  9931 D BtGatt.GattService: Is it foreground application = true
,07-25 18:26:46.319  9920  9931 D BtGatt.GattService: not a background application
07-25 18:26:46.320  3697  3697 D UcmService: onReceive android.intent.action.PACKAGE_CHANGED
07-25 18:26:46.320  3697  3697 D UcmService: Package update in userId-0 and uid-10019
07-25 18:26:46.320  3697  3697 D UcmService: isUCMPlugin pkgName-com.google.android.gms
07-25 18:26:46.320  3697  3697 D UcmService: enforcePermission : com.google.android.gms
07-25 18:26:46.320  3697  3697 D UcmService: isUCMPlugin pkgName-com.google.android.gsf.login
07-25 18:26:46.320  3697  3697 D UcmService: enforcePermission : com.google.android.gsf.login
07-25 18:26:46.320  3697  3697 D UcmService: isUCMPlugin pkgName-com.google.android.backuptransport
07-25 18:26:46.320  3697  3697 D UcmService: enforcePermission : com.google.android.backuptransport
07-25 18:26:46.320  3697  3697 D UcmService: isUCMPlugin pkgName-com.google.android.gsf
07-25 18:26:46.320  3697  3697 D UcmService: enforcePermission : com.google.android.gsf
07-25 18:26:46.320  3697  3697 D UcmService: isPCSCService pkgName-com.google.android.gms
07-25 18:26:46.320  3697  3697 D UcmService: isPCSCService pkgName-com.google.android.gsf.login
07-25 18:26:46.320  3697  3697 D UcmService: isPCSCService pkgName-com.google.android.backuptransport
07-25 18:26:46.320  3697  3697 D UcmService: isPCSCService pkgName-com.google.android.gsf
07-25 18:26:46.320  3697  3697 D UcmService: Updated app is not valid UCM plugin so ignoring refresh agent list....
07-25 18:26:46.321  3697  3697 W PackageManager: STAHP USING HIDDEN APIS KTHX
,07-25 18:26:46.322  3697  3697 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x44000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-25 18:26:46.322  3697  3697 I BackupManagerService: Package com.google.android.gms changed; rechecking
07-25 18:26:46.322  3697  3697 I BackupManagerService:    * com.google.android.gms.mdm.receivers.ConnectivityReceiver
07-25 18:26:46.323  3697  3697 I BackupManagerService: Checking need to rebind com.google.android.gms.backup.BackupTransportService
,07-25 18:26:46.325  3697  3838 D PackageManager: com.google.android.gms.permission.CAR_FUEL is a new runtime permission
07-25 18:26:46.326  3697  3838 D PackageManager: com.google.android.gms.permission.CAR_MILEAGE is a new runtime permission
,07-25 18:26:46.326  3697  3838 D PackageManager: com.google.android.gms.permission.CAR_SPEED is a new runtime permission
07-25 18:26:46.326  3697  3838 D PackageManager: com.google.android.gms.permission.CAR_VENDOR_EXTENSION is a new runtime permission
07-25 18:26:46.326  3697  3838 D PackageManager: Permission Group is null for permission com.sec.smartcard.permission.SMARTCARD_ADAPTER
07-25 18:26:46.326  3697  3838 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_READ
07-25 18:26:46.326  3697  3838 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_WRITE
07-25 18:26:46.326  3697  3838 D ApplicationPolicy: groups[android.permission-group.SMS, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.LOCATION, android.permission-group.MESSAGES, android.permission-group.SMS, android.permission-group.SENSORS, android.permission-group.LOCATION, android.permission-group.SMS, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.MESSAGES, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.SMS, android.permission-group.PHONE, android.permission-group.CONTACTS, android.permission-group.CAMERA, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.SMS, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, android.permission-group.CONTACTS, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.STORAGE, com.samsung.android.memo.EXTRA_READ, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.MICROPHONE, android.permission-group.CONTACTS, com.samsung.android.memo.EXTRA_WRITE, android.permission-group.PHONE]
07-25 18:26:46.326  3697  3838 D ApplicationPolicy: Permission GRoups [android.permission-group.CONTACTS, android.permission-group.CALENDAR, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.MICROPHONE, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, com.samsung.android.memo.EXTRA_READ, com.samsung.android.memo.EXTRA_WRITE]
07-25 18:26:46.326  9920  9967 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
07-25 18:26:46.326  9920  9967 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:46.327  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-25 18:26:46.327  9920  9957 D BtGatt.ScanManager: handling starting scan
07-25 18:26:46.328  9920  9957 D BtGatt.ScanManager: isFilteringSupported
07-25 18:26:46.328  9920  9957 D BluetoothAdapter: enableStandAloneBleMode=
07-25 18:26:46.329  9920  9957 D BluetoothAdapter: STATE_ON
07-25 18:26:46.329  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:46.329  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-25 18:26:46.329  9920  9957 D BluetoothAdapter: STATE_ON
,07-25 18:26:46.332  9920  9957 D BluetoothAdapter: STATE_ON
07-25 18:26:46.332  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:46.333  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-25 18:26:46.334  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:46.334  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:46.334  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-25 18:26:46.334  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:26:46.334  9920  9957 D BluetoothAdapter: STATE_ON
,07-25 18:26:46.335  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:46.335  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,07-25 18:26:46.335  3697  3811 I ActivityManager: KPU : put [com.sec.android.app.sbrowser] : 21532 K
07-25 18:26:46.335  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:46.335  3697  3811 I ActivityManager: Killing 9381:com.sec.android.app.sbrowser/u0a134 (adj 906): DHA:empty #33
07-25 18:26:46.336  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
07-25 18:26:46.336  9920  9957 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
07-25 18:26:46.337  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-25 18:26:46.339  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:46.347  9920  9940 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-25 18:26:46.347  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-25 18:26:46.348  9920  9957 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
07-25 18:26:46.348  9920  9957 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-25 18:26:46.348  9920  9957 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-25 18:26:46.348  9920  9957 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
,07-25 18:26:46.351  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:46.352  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-25 18:26:46.352  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:46.352  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:46.353  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
07-25 18:26:46.354  9920  9940 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-25 18:26:46.354  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:46.355  9920  9957 D BtGatt.ScanManager: Starting BLE batch scan
07-25 18:26:46.355  9920  9957 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-25 18:26:46.365  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-25 18:26:46.366  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-25 18:26:46.366  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:46.367  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-25 18:26:46.367  9920  9940 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-25 18:26:46.367  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-25 18:26:46.372  9920  9940 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-25 18:26:46.373  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:46.373  3697  4544 D ActivityManager: cleanUpApplicationRecord -- 9381
07-25 18:26:46.373  3697  4830 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{216bd41: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:46.375  4762  4776 D ForegroundUtils: could not check pending caller
,07-25 18:26:46.380  3697  3957 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182646 - CU:1002/CP:9920
07-25 18:26:46.380  3697  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182647, SetElapsed=309913, nowELAPSED=308919
,07-25 18:26:46.417  3697  3810 W SearchableInfo: Invalid searchable metadata for com.samsung.android.themestore/.activity.WTSearchActivity: Search label must be a resource reference.
,07-25 18:26:46.440  3697  3810 I PrintManagerService: onPackageModified com.google.android.gms
,07-25 18:26:46.441  3697  3810 I PrintManagerService:  - hadPrintService false
07-25 18:26:46.442  3697  3810 I PrintManagerService:  - hasPrintService false
07-25 18:26:46.442  3697  3810 I RemotePrintSpooler: pruneApprovedPrintServices
07-25 18:26:46.442  3697  3810 I RemotePrintSpooler: [user: 0] bindLocked() 
07-25 18:26:46.442  3697  3810 I RemotePrintSpooler: bindLocked binding service java.lang.Object@c2f3b4d
,07-25 18:26:46.443  3697  3810 D MountService: getExternalStorageMountMode : 1
07-25 18:26:46.443  3697  3810 D MountService: getExternalStorageMountMode : 3
07-25 18:26:46.443  3697  3810 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10138, packageName : com.android.printspooler
,07-25 18:26:46.461 10411 10411 E Zygote  : v2
07-25 18:26:46.461 10411 10411 I libpersona: KNOX_SDCARD checking this for 10138
07-25 18:26:46.461 10411 10411 I libpersona: KNOX_SDCARD not a persona
07-25 18:26:46.462 10411 10411 E Zygote  : accessInfo : 0
,07-25 18:26:46.467 10411 10411 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-25 18:26:46.468 10411 10411 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.printspooler 
,07-25 18:26:46.474  3697  3810 I ActivityManager: Start proc 10411:com.android.printspooler/u0a138 for service com.android.printspooler/.model.PrintSpoolerService
07-25 18:26:46.474  3697  3810 I RemotePrintSpooler: bindLocked waiting. remainingMillis: 8000
,07-25 18:26:46.487 10411 10411 D TimaKeyStoreProvider: TimaSignature is unavailable
07-25 18:26:46.487 10411 10411 D ActivityThread: Added TimaKeyStore provider
,07-25 18:26:46.490  3697  4838 I ActivityManager: DSS on for com.android.printspooler and scale is 1.0
,07-25 18:26:46.528 10411 10411 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-25 18:26:46.537 10411 10411 D PrintSpoolerService: No existing print spooler state.
,07-25 18:26:46.540  3697  3697 I RemotePrintSpooler: onServiceConnected
07-25 18:26:46.541  3697  3810 I RemotePrintSpooler: [user: 0] pruneApprovedPrintServices()
,07-25 18:26:46.560  4718  4718 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,07-25 18:26:46.566  4904  4904 D Launcher.Model: onPackageChanged:com.google.android.gms user:UserHandle{0}
07-25 18:26:46.567  4904  4904 D Launcher.Model: isValidStateInKnoxMode:false user:UserHandle{0}
,07-25 18:26:46.567  4904  4904 E Launcher.Model: onPackageChanged :com.google.android.gms
07-25 18:26:46.569  4904  5017 D LauncherApps: getActivityList callingUid: 0 user: 0
,07-25 18:26:46.573  4904  5017 D MenuAppLoader: There is no package to remove in mApps:com.google.android.gms
,07-25 18:26:46.579  4904  5017 D LauncherApps: getActivityList callingUid: 0 user: 0
07-25 18:26:46.582  3697  4838 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-25 18:26:46.583  4904  5017 D Launcher.MenuWidgetsLoader: packageChanged : com.google.android.gms
07-25 18:26:46.584  4904  4904 D Launcher.MenuWidgetsLoader: MenuWidgetLoade-loadMenuWidgets : false
07-25 18:26:46.584  3697  4838 D SecContentProvider: called from com.google.uid.shared:10019
07-25 18:26:46.585  4904  4904 D MenuView: packageChanged:
,07-25 18:26:46.585  4904  4904 D MenuView: packagesChanged:2
07-25 18:26:46.585  4904  4904 D MenuView: frag:null
07-25 18:26:46.585  4904  4904 D MenuView: frag:MenuAppsGridFragment{fd9199c #0 id=0x1020011 APPS}
07-25 18:26:46.587  4904 10425 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-start : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@77dc917 , false
,07-25 18:26:46.597  3697  6617 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{ad6b3c9: PendingIntentRecord{c5080f8 com.google.android.gms broadcastIntent}}
,07-25 18:26:46.598  3697  3944 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{ea7face: PendingIntentRecord{b662c36 com.google.android.gms broadcastIntent}}
,07-25 18:26:46.600  3697  4838 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{544bdef: PendingIntentRecord{d88b4a4 com.google.android.gms broadcastIntent}}
,07-25 18:26:46.608  3697  6617 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{5fde0fc: PendingIntentRecord{560d5c2 com.google.android.gms broadcastIntent}}
,07-25 18:26:46.611  3697  3917 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{68dc385: PendingIntentRecord{12fc209 com.google.android.gms broadcastIntent}}
,07-25 18:26:46.613  3697  6550 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{9ccf5da: PendingIntentRecord{eabf43c com.google.android.gms broadcastIntent}}
07-25 18:26:46.618  3697  4830 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{fc94a0b: PendingIntentRecord{f475b1a com.google.android.gms broadcastIntent}}
,07-25 18:26:46.621  3697  3928 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{cc610e8: PendingIntentRecord{f621828 com.google.android.gms broadcastIntent}}
07-25 18:26:46.622  3697  4838 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{4ec1301: PendingIntentRecord{ef00ee6 com.google.android.gms broadcastIntent}}
07-25 18:26:46.624  3697  3948 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4718 / op:PendingIntent{a1495a6: PendingIntentRecord{7fd987d com.google.android.gms broadcastIntent}}
,07-25 18:26:46.649  3697  3810 D LocationProviderProxy: applying state to connected service
07-25 18:26:46.649  3697  3810 D LocationProviderProxy: applying state to connected service
,07-25 18:26:46.675  4718  5099 W GCoreFlp: No location to return for getLastLocation()
,07-25 18:26:46.676  4718  5099 W GCoreFlp: No location to return for getLastLocation()
,07-25 18:26:46.698  4904  4904 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-done : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@77dc917 , update : false , size : 48
,07-25 18:26:46.868  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
07-25 18:26:46.869  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-25 18:26:46.869  9791  9791 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-25 18:26:47.374  3697  3866 D SamsungAlarmManager: Expired : 4
,07-25 18:26:47.376  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=309914
07-25 18:26:47.376  3697  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{54700df type 2 when 309413 com.android.bluetooth}
,07-25 18:26:47.382  9920  9920 D BtGatt.ScanManager: awakened up at time 309921
,07-25 18:26:47.385  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-25 18:26:47.408  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-25 18:26:47.409  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:47.409  9920  9940 D BtGatt.GattService: current time is 309948404739
07-25 18:26:47.410  9920  9940 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -55, 1, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
,07-25 18:26:47.412  3697  3777 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{cf9812c: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:47.414  9920  9940 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
,07-25 18:26:47.415  9920  9940 D ScanRecord: parseFromBytes
,07-25 18:26:47.418  9791  9803 D ScanRecord: parseFromBytes
,07-25 18:26:47.422  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-55, mTimestampNanos=309899175124}
,07-25 18:26:47.424  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
,07-25 18:26:47.424  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:26:47.429  3697  4945 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182647 - CU:1002/CP:9920
,07-25 18:26:47.430  3697  4945 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182648, SetElapsed=310953, nowELAPSED=309968
,07-25 18:26:47.743  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:47.744  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:26:48.414  3697  3866 D SamsungAlarmManager: Expired : 4
07-25 18:26:48.416  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=310954
,07-25 18:26:48.416  3697  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{f9f97f5 type 2 when 310452 com.android.bluetooth}
,07-25 18:26:48.422  9920  9920 D BtGatt.ScanManager: awakened up at time 310961
,07-25 18:26:48.424  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-25 18:26:48.436  3697 10018 I ActivityManager: KPU : put [com.sec.android.widgetapp.samsungapps] : 25612 K
07-25 18:26:48.436  3697 10018 I ActivityManager: Killing 9428:com.sec.android.widgetapp.samsungapps/u0a105 (adj 906): DHA:empty #33
,07-25 18:26:48.446  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-25 18:26:48.446  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-25 18:26:48.446  9920  9940 D BtGatt.GattService: current time is 310985679354
07-25 18:26:48.446  9920  9940 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -54, 1, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:26:48.447  9920  9940 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:26:48.447  9920  9940 D ScanRecord: parseFromBytes
07-25 18:26:48.448  3697  6617 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{3be898a: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:48.448  9791  9802 D ScanRecord: parseFromBytes
07-25 18:26:48.449  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-54, mTimestampNanos=310935864277}
,07-25 18:26:48.450  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:26:48.451  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:26:48.458  3697  3948 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182648 - CU:1002/CP:9920
,07-25 18:26:48.459  3697  3948 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182649, SetElapsed=311988, nowELAPSED=310997
,07-25 18:26:48.472  3697  4838 D ActivityManager: cleanUpApplicationRecord -- 9428
,07-25 18:26:48.474  4762  4777 D ForegroundUtils: could not check pending caller
,07-25 18:26:48.870  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:26:48.872 10193 10193 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
,07-25 18:26:48.874  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:26:48.874  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:26:48.879  3697  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@fd4c4a1
,07-25 18:26:48.882  3697  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182648, SetElapsed=311487, nowELAPSED=311421
,07-25 18:26:48.948  3697  3866 D SamsungAlarmManager: Expired : 4
07-25 18:26:48.949  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=311488
,07-25 18:26:48.949  3697  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{c4cbfb type 2 when 311487 com.android.bluetooth}
,07-25 18:26:48.954  9920  9920 D BtGatt.ScanManager: awakened up at time 311492
07-25 18:26:48.955  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-25 18:26:48.970  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-25 18:26:48.970  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:48.970  9920  9940 D BtGatt.GattService: current time is 311509408892
07-25 18:26:48.970  9920  9940 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -60, 0, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
,07-25 18:26:48.971  9920  9940 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:26:48.971  9920  9940 D ScanRecord: parseFromBytes
,07-25 18:26:48.972  9791  9803 D ScanRecord: parseFromBytes
07-25 18:26:48.973  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-60, mTimestampNanos=311509657623}
,07-25 18:26:48.975  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:26:48.975  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:26:48.978  3697  4544 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{9138418: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
,07-25 18:26:48.987  3697  3917 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182649 - CU:1002/CP:9920
07-25 18:26:48.988  3697  3917 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182649, SetElapsed=312519, nowELAPSED=311527
,07-25 18:26:49.357  9791  9855 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
07-25 18:26:49.357  9791  9855 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
07-25 18:26:49.358  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,07-25 18:26:49.358  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:26:49.367  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:49.367  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:49.368  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.368  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-25 18:26:49.376  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-25 18:26:49.376  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,07-25 18:26:49.377  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 40909
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-25 18:26:49.378  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.379  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
07-25 18:26:49.380  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.381  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.381  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-25 18:26:49.382  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-25 18:26:49.383  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.384  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.385  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.387  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.389  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.389  9920  9941 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
07-25 18:26:49.390  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-25 18:26:49.391  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-25 18:26:49.392  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.395  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.395  9791  9855 D BluetoothLeScanner: Stop Scan
,07-25 18:26:49.397  9920  9932 D BtGatt.GattService: stopScan() - queue size =1
07-25 18:26:49.398  9920  9932 D BtGatt.GattService: stopScan() - queue size =1
07-25 18:26:49.398  9920  9967 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-25 18:26:49.400  9920  9932 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-25 18:26:49.401  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:26:49.402  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.402  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-25 18:26:49.403  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.403  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-25 18:26:49.404  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.404  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.404  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-25 18:26:49.404  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-25 18:26:49.405  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 40909
07-25 18:26:49.405  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-25 18:26:49.405  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=40909, mManufacturerData=null, mManufacturerDataMask=null]
07-25 18:26:49.405  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:49.405  9920  9940 D BtGatt.GattService: current time is 311944276353
07-25 18:26:49.405  9920  9940 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -58, 7, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:26:49.405  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.405  9791  9855 D BluetoothLeScanner: Start Scan
07-25 18:26:49.406  9920  9940 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:26:49.406  3697  3957 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{21ebe71: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:49.406  9920  9940 D ScanRecord: parseFromBytes
07-25 18:26:49.406  9920  9940 E BtGatt.ContextMap: Context not found for ID 5
,07-25 18:26:49.407  3697  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=311946
,07-25 18:26:49.409  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.411  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:49.415  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.416  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.417  3697  3777 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182649 - CU:1002/CP:9920
07-25 18:26:49.418  3697  3777 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182650, SetElapsed=312947, nowELAPSED=311957
,07-25 18:26:49.419  9920  9957 D BtGatt.ScanManager: filter size is 1
07-25 18:26:49.419  9920  9957 D BtGatt.ScanManager: delete FilterIndex - 3
07-25 18:26:49.420  9920  9995 D BtGatt.GattService: registerClient() - UUID=02d7c033-ce19-4994-94de-63eb3d170772
,07-25 18:26:49.425  9920  9940 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-25 18:26:49.425  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:49.425  9920  9957 D BtGatt.ScanManager: stopping BLe Batch
,07-25 18:26:49.431  9920  9940 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-25 18:26:49.431  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:49.431  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-25 18:26:49.437  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-25 18:26:49.437  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-25 18:26:49.438  3697  3944 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{183b456: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
,07-25 18:26:49.439  3697  3944 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=311978
07-25 18:26:49.440  3697  4945 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{68a2cd7: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
,07-25 18:26:49.523  9920  9940 D BtGatt.GattService: onClientRegistered() - UUID=02d7c033-ce19-4994-94de-63eb3d170772, clientIf=5, status=0
,07-25 18:26:49.525  9791  9802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
07-25 18:26:49.526  9920  9997 D BtGatt.GattService: start scan with filters
,07-25 18:26:49.530  9920  9997 D BtGatt.GattService: getScanSettings
,07-25 18:26:49.533  9920  9997 D BtGatt.GattService: Is it foreground application = true
,07-25 18:26:49.533  9920  9997 D BtGatt.GattService: not a background application
,07-25 18:26:49.546  9920  9967 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,07-25 18:26:49.546  9920  9967 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b8205f1
,07-25 18:26:49.546  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-25 18:26:49.547  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.547  9920  9957 D BtGatt.ScanManager: handling starting scan
07-25 18:26:49.547  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-25 18:26:49.549  9920  9957 D BluetoothAdapter: STATE_ON
07-25 18:26:49.550  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.551  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.551  9920  9957 D BluetoothAdapter: STATE_ON
07-25 18:26:49.551  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-25 18:26:49.552  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-25 18:26:49.552  9791  9855 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-25 18:26:49.552  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.552  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-25 18:26:49.552  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-25 18:26:49.552  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-25 18:26:49.552  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-25 18:26:49.553  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.554  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.556  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-25 18:26:49.558  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-25 18:26:49.558  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-25 18:26:49.558  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-25 18:26:49.559  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-25 18:26:49.559  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,07-25 18:26:49.559  9791 10428 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-25 18:26:49.559  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
07-25 18:26:49.565  3697  3811 I ActivityManager: KPU : put [com.wssnps] : 25600 K
07-25 18:26:49.566  3697  3811 I ActivityManager: Killing 9448:com.wssnps/1000 (adj 906): DHA:empty #33
07-25 18:26:49.566  9920  9940 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-25 18:26:49.566  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:49.568  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-25 18:26:49.568  9791  9855 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-25 18:26:49.574  9791 10428 D BluetoothSocket: bindListen(): myUserId = 0
07-25 18:26:49.574  9791 10428 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-25 18:26:49.574  9920  9957 D BtGatt.ScanManager: set filter index= 4 for clientIf= 5
07-25 18:26:49.574  9920  9957 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-25 18:26:49.574  9920  9957 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-25 18:26:49.575  9920  9957 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
07-25 18:26:49.584  9791 10428 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-25 18:26:49.584  9791 10428 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@b2d81b2, port: 6, type: 1, local socket address: null, socket type: 0
07-25 18:26:49.587  9920  9940 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-25 18:26:49.588  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:49.588  9920  9957 D BtGatt.ScanManager: Starting BLE batch scan
07-25 18:26:49.588  9920  9957 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-25 18:26:49.588  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.592  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.613  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:49.614  9920  9940 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-25 18:26:49.615  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:49.615  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.621  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.628  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.629  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.630  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.630  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-25 18:26:49.630  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-25 18:26:49.630  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "56cdb199-de28-499b-9b7d-14243646ae2d", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-25 18:26:49.631  3697  4945 D ActivityManager: cleanUpApplicationRecord -- 9448
,07-25 18:26:49.631  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 4A 3E
07-25 18:26:49.632  9791  9855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:49.632  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:49.633  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.634  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.634  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-25 18:26:49.635  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-25 18:26:49.635  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.636  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.636  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[56cdb199-de28-499b-9b7d-14243646ae2d], mManufacturerSpecificData={}, mServiceData={56cdb199-de28-499b-9b7d-14243646ae2d=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.637  9920  9940 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-25 18:26:49.637  4762  4777 D ForegroundUtils: could not check pending caller
07-25 18:26:49.637  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:49.638  3697  3928 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{7c8c9c4: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
,07-25 18:26:49.640  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:49.642  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:49.642  9791  9855 D BluetoothAdapter: isSecureModeEnabled
,07-25 18:26:49.642  9920  9931 D BtConfig.SecureMode: isSecureModeOn:false
07-25 18:26:49.643  9791  9855 D BluetoothLeAdvertiser: start advertising
,07-25 18:26:49.644  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:49.647  4645  4645 D io_stats: !@   8,0 r 25300 2273868 w 5281 210132 d 742 74472 f 2099 2099 iot 11800 10858 th 470700 0 0 pt 0 inp 0 0 312.186
,07-25 18:26:49.648  3697  4829 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182650 - CU:1002/CP:9920
07-25 18:26:49.649  3697  4829 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182650, SetElapsed=313179, nowELAPSED=312188
,07-25 18:26:49.652  9920  9995 D BtGatt.GattService: registerClient() - UUID=6d99d387-aaea-4d4b-a145-235ef751de0a
,07-25 18:26:49.756  9920  9940 D BtGatt.GattService: onClientRegistered() - UUID=6d99d387-aaea-4d4b-a145-235ef751de0a, clientIf=6, status=0
,07-25 18:26:49.757  9791  9803 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,07-25 18:26:49.761  9920  9931 E BtGatt.ContextMap: Context not found for ID 6
,07-25 18:26:49.762  9920  9967 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-25 18:26:49.762  9920  9956 D BtGatt.AdvertiseManager: message : 0
,07-25 18:26:49.764  9920  9956 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-25 18:26:49.765  9920  9956 D BtGatt.AdvertiseManager: size of list is =0
,07-25 18:26:49.774  9920  9956 D BtGatt.AdvertiseManager: starting advertising
,07-25 18:26:49.778  9920  9956 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-25 18:26:49.783  9920  9973 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-25 18:26:49.803  9920  9940 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,07-25 18:26:49.807  9920  9956 D BtGatt.AdvertiseManager: starting multi advertising
,07-25 18:26:49.818  9920  9940 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
07-25 18:26:49.819  9920  9956 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,07-25 18:26:49.819  9920  9956 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-25 18:26:49.819  9920  9956 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
07-25 18:26:49.819  9920  9956 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
07-25 18:26:49.820  9791  9802 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-25 18:26:49.822  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.823  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.823  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-25 18:26:49.824  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.825  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.826  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.827  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.828  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.829  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.830  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.831  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.831  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
07-25 18:26:49.831  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
07-25 18:26:49.831  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-25 18:26:49.835  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-25 18:26:49.836  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.845  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.845  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:49.846  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:49.846  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-25 18:26:49.847  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.848  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:49.848  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-25 18:26:49.849  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.849  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.850  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:49.850  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.850  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
07-25 18:26:49.850  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-25 18:26:49.851  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.851  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.852  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-25 18:26:49.853  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-25 18:26:49.853  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-25 18:26:49.859  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.859  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-25 18:26:49.860  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-25 18:26:49.860  9791  9791 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-25 18:26:49.861  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-25 18:26:49.903  3697  5674 D SSRM:f  : SIOP:: AP = 290, PST = 304 (W:10), CP = 244, CUR = -2, LCD = 57
,07-25 18:26:50.362  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
07-25 18:26:50.363  9791  9791 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-25 18:26:50.363  9791  9791 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-25 18:26:50.641  3697  3866 D SamsungAlarmManager: Expired : 4
,07-25 18:26:50.642  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=313181
07-25 18:26:50.643  3697  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{f8fd0ad type 2 when 312679 com.android.bluetooth}
,07-25 18:26:50.649  9920  9920 D BtGatt.ScanManager: awakened up at time 313187
,07-25 18:26:50.651  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-25 18:26:50.675  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
07-25 18:26:50.675  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:50.676  9920  9940 D BtGatt.GattService: current time is 313214975083
07-25 18:26:50.676  9920  9940 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -57, 0, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0, 81, 34, 97, 112, -14, -5, 1, -128, -94, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
07-25 18:26:50.677  9920  9940 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:26:50.677  3697  3777 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{49ebfe2: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:50.677  9920  9940 D ScanRecord: parseFromBytes
,07-25 18:26:50.678  9920  9940 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
07-25 18:26:50.678  9920  9940 D ScanRecord: parseFromBytes
07-25 18:26:50.678  9920  9940 D ScanRecord: first manudata for manu ID
07-25 18:26:50.679  9791  9803 D ScanRecord: parseFromBytes
07-25 18:26:50.680  9791  9803 D ScanRecord: first manudata for manu ID
07-25 18:26:50.680  9791  9803 D ScanRecord: parseFromBytes
07-25 18:26:50.681  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-94, mTimestampNanos=312765374045}
,07-25 18:26:50.683  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
07-25 18:26:50.684  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
07-25 18:26:50.684  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-57, mTimestampNanos=313215374045}
,07-25 18:26:50.687  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:26:50.689  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:26:50.693  3697 10018 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182651 - CU:1002/CP:9920
07-25 18:26:50.693  3697 10018 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182651, SetElapsed=314218, nowELAPSED=313232
,07-25 18:26:50.719  3697  3880 I TLC_TIMA_PKM_initialize: initializing...
07-25 18:26:50.719  3697  3880 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-25 18:26:50.719  3697  3880 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: device_id = 0x0
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: tlc_open() was called
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: Opening MobiCore device
07-25 18:26:50.719  3697  3880 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,07-25 18:26:50.721  3697  3880 I TZ: mc_tlc_communication: Opening the session
,07-25 18:26:50.764  3697  3880 I TZ: mc_tlc_communication: tlc_open() succeeded
,07-25 18:26:50.765  3697  3880 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,07-25 18:26:50.770  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-25 18:26:50.770  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-25 18:26:50.776  3697  3880 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,07-25 18:26:50.785  3697  3880 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,07-25 18:26:50.798  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:50.817  3697  3880 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,07-25 18:26:50.823  3697  3880 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-25 18:26:51.186  3697  3697 D UsbMonitorService: readUsbState++
,07-25 18:26:51.188  3697  3697 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-25 18:26:51.190  3697  3697 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-25 18:26:51.190  3697  3697 D UsbMonitorService: Posting Message again
,07-25 18:26:51.554  3697  6550 I RemotePrintSpooler: [user: 0] unbindLocked()
,07-25 18:26:51.575  3697 10019 I ActivityManager: KPU : put [com.sec.android.app.shealth] : 31968 K
07-25 18:26:51.576  3697 10019 I ActivityManager: Killing 6735:com.sec.android.app.shealth/u0a36 (adj 906): DHA:empty #33
,07-25 18:26:51.630  3697  4945 D ActivityManager: cleanUpApplicationRecord -- 6735
,07-25 18:26:51.632  4762  4777 D ForegroundUtils: could not check pending caller
,07-25 18:26:51.679  3697  3866 D SamsungAlarmManager: Expired : 4
07-25 18:26:51.679  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=314218
07-25 18:26:51.680  3697  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{dabf73 type 2 when 313717 com.android.bluetooth}
,07-25 18:26:51.684  9920  9920 D BtGatt.ScanManager: awakened up at time 314222
07-25 18:26:51.685  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-25 18:26:51.696  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-25 18:26:51.696  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-25 18:26:51.696  9920  9940 D BtGatt.GattService: current time is 314235588544
07-25 18:26:51.696  9920  9940 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -58, 2, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:26:51.697  9920  9940 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:26:51.697  9920  9940 D ScanRecord: parseFromBytes
07-25 18:26:51.697  3697  3917 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{96abe30: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:51.698  9791  9802 D ScanRecord: parseFromBytes
,07-25 18:26:51.698  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-58, mTimestampNanos=314135757582}
07-25 18:26:51.699  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:26:51.699  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:26:51.704  3697  3957 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182652 - CU:1002/CP:9920
07-25 18:26:51.705  3697  3957 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182652, SetElapsed=315237, nowELAPSED=314243
,07-25 18:26:52.698  3697  3866 D SamsungAlarmManager: Expired : 4
,07-25 18:26:52.700  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=315238
07-25 18:26:52.700  3697  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{185caa9 type 2 when 314736 com.android.bluetooth}
,07-25 18:26:52.707  9920  9920 D BtGatt.ScanManager: awakened up at time 315245
07-25 18:26:52.709  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-25 18:26:52.730  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-25 18:26:52.730  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:52.730  9920  9940 D BtGatt.GattService: current time is 315269330928
07-25 18:26:52.730  9920  9940 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -57, 9, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
,07-25 18:26:52.731  9920  9940 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:26:52.731  9920  9940 D ScanRecord: parseFromBytes
07-25 18:26:52.731  3697  4547 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{16cf82e: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
,07-25 18:26:52.732  9791  9803 D ScanRecord: parseFromBytes
07-25 18:26:52.734  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=55:61:CA:51:41:3E, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[102d0c33-240a-4b12-88e5-9f2fc1133933], mManufacturerSpecificData={}, mServiceData={00000c33-0000-1000-8000-00805f9b34fb=[18, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-57, mTimestampNanos=314819586466}
07-25 18:26:52.735  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = A8:81:95:E9:5F:6F, provideBluetoothMacAddressRequestId = nullextra info = 18]
07-25 18:26:52.736  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,07-25 18:26:52.745  3697  6550 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182653 - CU:1002/CP:9920
07-25 18:26:52.745  3697  6550 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182653, SetElapsed=316272, nowELAPSED=315284
,07-25 18:26:52.852  9791  9855 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,07-25 18:26:52.854  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-25 18:26:52.854  9791  9855 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-25 18:26:52.855  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,07-25 18:26:52.855  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-25 18:26:52.855  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-25 18:26:52.856  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-25 18:26:52.856  9791  9855 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-25 18:26:52.857  9791  9791 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-25 18:26:52.857  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-25 18:26:52.858  9791  9855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa86d05 removed from the list
07-25 18:26:52.858  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa86d05 removed from the list
07-25 18:26:52.858  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-25 18:26:52.858  9791  9855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-25 18:26:52.859  9791 10428 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-25 18:26:52.859  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.859  9791 10428 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-25 18:26:52.859  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-25 18:26:52.859  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-25 18:26:52.859  9791 10428 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-25 18:26:52.859  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-25 18:26:52.859  9791  9791 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-25 18:26:52.860  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.861  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:52.861  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.861  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-25 18:26:52.862  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:52.864  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:52.865  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:52.866  9920  9997 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
07-25 18:26:52.867  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-25 18:26:52.868  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-25 18:26:52.869  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:52.871  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:52.871  9791  9855 D BluetoothLeScanner: Stop Scan
,07-25 18:26:52.872  9920  9941 D BtGatt.GattService: stopScan() - queue size =1
07-25 18:26:52.873  9920  9941 D BtGatt.GattService: stopScan() - queue size =1
07-25 18:26:52.873  9920  9967 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
,07-25 18:26:52.878  9920  9932 D BtGatt.GattService: unregisterClient() - clientIf=5
07-25 18:26:52.878  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-25 18:26:52.879  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:52.879  9920  9940 D BtGatt.GattService: current time is 315417999659
07-25 18:26:52.879  9920  9940 D BtGatt.GattService: Batch record : [62, 65, 81, -54, 97, 85, 1, -128, -55, 2, 0, 29, 17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111, 0]
07-25 18:26:52.879  9920  9940 D BtGatt.GattService: ScanRecord : [17, 7, 51, 57, 19, -63, 47, -97, -27, -120, 18, 75, 10, 36, 51, 12, 45, 16, 10, 22, 51, 12, 18, -88, -127, -107, -23, 95, 111]
07-25 18:26:52.879  3697  3948 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{97dfcf: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:52.879  9920  9940 D ScanRecord: parseFromBytes
07-25 18:26:52.879  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-25 18:26:52.880  9920  9940 E BtGatt.ContextMap: Context not found for ID 5
07-25 18:26:52.880  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.880  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-25 18:26:52.881  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.881  3697  3948 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=315420
07-25 18:26:52.881  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.882  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.882  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,07-25 18:26:52.882  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,07-25 18:26:52.884  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:26:52.886  9791  9855 D BluetoothAdapter: STATE_ON
07-25 18:26:52.886  9791  9855 D BluetoothLeAdvertiser: stop advertising
,07-25 18:26:52.888  9920  9931 E BtGatt.ContextMap: Context not found for ID 6
07-25 18:26:52.888  9920  9956 D BtGatt.AdvertiseManager: message : 1
07-25 18:26:52.888  9920  9967 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-25 18:26:52.889  9920  9956 D BtGatt.AdvertiseManager: stop advertise for client =  6
07-25 18:26:52.889  9920  9956 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
,07-25 18:26:52.890  9920  9956 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-25 18:26:52.894  3697  4829 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170725T182653 - CU:1002/CP:9920
07-25 18:26:52.894  3697  4829 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182653, SetElapsed=316421, nowELAPSED=315433
07-25 18:26:52.897  9920  9940 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
07-25 18:26:52.897  9920  9940 D BtGatt.GattService: Client app is not null!
07-25 18:26:52.897  9920  9957 D BtGatt.ScanManager: filter size is 1
07-25 18:26:52.897  9920  9957 D BtGatt.ScanManager: delete FilterIndex - 4
07-25 18:26:52.897  9791  9802 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
07-25 18:26:52.898  9920  9941 D BtGatt.GattService: unregisterClient() - clientIf=6
,07-25 18:26:52.900  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-25 18:26:52.900  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.900  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-25 18:26:52.901  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.901  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.902  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.902  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-25 18:26:52.902  9920  9940 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-25 18:26:52.902  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:52.902  9791  9855 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-25 18:26:52.902  9920  9957 D BtGatt.ScanManager: stopping BLe Batch
,07-25 18:26:52.903  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-25 18:26:52.904  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.908  9920  9940 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-25 18:26:52.908  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:52.909  9920  9957 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-25 18:26:52.909  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.909  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:26:52.909  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.910  9791  9855 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
07-25 18:26:52.910  9791  9855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc215a removed from the list
07-25 18:26:52.910  9791  9855 D io.jxcore.node.ConnectivityMonitor: stop
07-25 18:26:52.910  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:52.910  9791  9855 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-25 18:26:52.910  9791  9855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-25 18:26:52.910  9791  9791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-25 18:26:52.910  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:52.911  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:52.911  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:26:52.911  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
07-25 18:26:52.912  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:52.912  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-25 18:26:52.912  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
07-25 18:26:52.912  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-25 18:26:52.912  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:52.912  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-25 18:26:52.913  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-25 18:26:52.913  9791  9855 V io.jxcore.node.StartStopOperation: isTarg,etState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-25 18:26:52.913  9791  9791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-25 18:26:52.913  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-25 18:26:52.913  9791  9855 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-25 18:26:52.913  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-25 18:26:52.913  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-25 18:26:52.913  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-25 18:26:52.914  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-25 18:26:52.914  9920  9940 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-25 18:26:52.914  9920  9940 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-25 18:26:52.914  9791  9791 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-25 18:26:52.914  9791  9791 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-25 18:26:52.914  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
07-25 18:26:52.915  3697 10018 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{ff58d5c: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:52.916  3697 10018 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182700, SetElapsed=323336, nowELAPSED=315455
07-25 18:26:52.917  3697  4837 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9920 / op:PendingIntent{dc76865: PendingIntentRecord{390646d com.android.bluetooth broadcastIntent}}
07-25 18:26:52.919  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
07-25 18:26:52.920  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
07-25 18:26:52.922  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
07-25 18:26:52.923  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,07-25 18:26:52.925  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,07-25 18:26:52.926  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,07-25 18:26:52.928  9791  9855 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,07-25 18:26:53.240  3697  4463 E Watchdog: !@Sync 10 [25_lip_18_26_53.240]
,07-25 18:26:53.416  9791  9791 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-25 18:26:53.796  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:53.796  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-25 18:26:54.652  4645  4645 D io_stats: !@   8,0 r 25306 2274560 w 5297 210328 d 744 74480 f 2101 2101 iot 11810 10867 th 473048 0 0 pt 0 inp 0 0 317.189
,07-25 18:26:54.763  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:54.854  3697  3880 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-25 18:26:54.854  3697  3880 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-25 18:26:54.934  9791  9855 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,07-25 18:26:55.066  9791 10432 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:55.066  9791 10432 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:55.066  9791 10432 D io.jxcore.node.StreamCopyingThread:  id: 83
,07-25 18:26:55.073  9791  9796 I art     : Do partial code cache collection, code=20KB, data=30KB
07-25 18:26:55.074  9791  9796 I art     : After code cache collection, code=18KB, data=29KB
07-25 18:26:55.074  9791  9796 I art     : Increasing code cache capacity to 128KB
,07-25 18:26:55.326  3697  3917 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170725T183338 - CU:10007/CP:4778
,07-25 18:26:55.822  9791 10432 W !!      : call onHalfStreamCopied
07-25 18:26:55.822  9791 10432 I testCopyDataAndClose: closing input stream
,07-25 18:26:56.078  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-25 18:26:56.078  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-25 18:26:56.078  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({system=1, android.process.acore=1})  ]
,07-25 18:26:56.085  4885  4951 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 5ms lastUpdatedAfter : 27226 ms mFlush_time_threasold : 2000 mCurrentSize : 267
,07-25 18:26:56.471  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:56.481  3697  3811 I ActivityManager: KPU : put [com.samsung.android.app.watchmanager:contentprovider] : 20116 K
07-25 18:26:56.481  3697  3811 I ActivityManager: Killing 9467:com.samsung.android.app.watchmanager:contentprovider/u0a18 (adj 906): DHA:empty #33
,07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 254, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread:  id: 83
,07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread:  id: 83
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:26:56.495  9791 10432 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:26:56.496  9791 10432 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:56.496  9791 10432 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:56.496  9791 10432 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-25 18:26:56.511  3697 10018 D ActivityManager: cleanUpApplicationRecord -- 9467
,07-25 18:26:56.513  4762  4776 D ForegroundUtils: could not check pending caller
,07-25 18:26:56.810  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:56.810  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-25 18:26:57.917  9791  9855 I StreamCopyingThreadTest: Starting test: testCopyBigData
,07-25 18:26:57.951  9791 10433 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 257, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:57.951  9791 10433 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:57.951  9791 10433 D io.jxcore.node.StreamCopyingThread:  id: 85
,07-25 18:26:58.403  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:58.417  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:58.428  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:58.433  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:58.437  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:58.797  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:59.141  3697  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 257, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread:  id: 85
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread:  id: 85
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 257, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:26:59.249  9791 10433 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-25 18:26:59.657  4645  4645 D io_stats: !@   8,0 r 25306 2274560 w 5319 210544 d 747 74492 f 2104 2104 iot 11820 10872 th 465896 0 0 pt 0 inp 0 0 322.194
,07-25 18:26:59.837  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:26:59.837  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -41
,07-25 18:26:59.921  3697  5674 D SSRM:f  : SIOP:: AP = 330, PST = 306 (W:6), CP = 244, CUR = -117, LCD = 57
,07-25 18:27:00.000  3697  3866 D SamsungAlarmManager: Expired : 8
,07-25 18:27:00.001  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{5cb25e1 type 3 when 322539 android}
,07-25 18:27:00.008  3697  3697 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170725T182800 - CU:1000/CP:3697
,07-25 18:27:00.011  4074  4074 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-25 18:27:00.011  4074  4074 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-25 18:27:00.012  4074  4074 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-25 18:27:00.029  4074  4074 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-25 18:27:00.029  4074  4074 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-25 18:27:00.031  4074  4074 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-25 18:27:00.045  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:27:00.047  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:27:00.050  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
07-25 18:27:00.053  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:27:00.077  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:27:00.078  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:27:00.079  4074  4074 V hong    : mid yDiff = 438
07-25 18:27:00.080  4074  4074 V hong    : mid yDiff = 438
07-25 18:27:00.081  4074  4074 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-25 18:27:00.081  4074  4074 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-25 18:27:00.084  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:27:00.086  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:27:00.093  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:27:00.094  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:27:00.109  4074  4074 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
07-25 18:27:00.112  4074  4074 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-25 18:27:00.116  5069  5069 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
07-25 18:27:00.118  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-25 18:27:00.120  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-25 18:27:00.125  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-25 18:27:00.126  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
07-25 18:27:00.127  5069  5069 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-25 18:27:00.128  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-25 18:27:00.128  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-25 18:27:00.132  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-25 18:27:00.134  5069  5069 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C3CC40EFB9853E5512D58DCA498126DE9E83465AA556FF5251F42A36AECF8D1CFFAF3E6A0ABCFC4DE84592052FDD2E6AA]}
,07-25 18:27:00.134  5069  5069 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-25 18:27:00.571  9791  9855 I StreamCopyingThreadTest: Starting test: testRunNotify
,07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 259, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread:  id: 86
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 259, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread:  id: 86
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread:  id: 86
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 259, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:27:00.572  9791 10434 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
07-25 18:27:00.572  9791  9855 I StreamCopyingThreadTest: Starting test: testSetBufferSize
07-25 18:27:00.572  9791  9855 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-25 18:27:00.573  9791  9855 I StreamCopyingThreadTest: Starting test: testRunWithException
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread:  id: 89
07-25 18:27:00.573  9791 10435 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 263, thread name: My test thread name): Test exception.
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 263, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-25 18:27:00.573  9791 10435 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-25 18:27:00.574  9791  9855 I jxcore-log: 2017-07-25 16:27:00 - DEBUG UnitTest_app: 'Running unit tests'
07-25 18:27:00.574  9791  9855 I jxcore-log: 
07-25 18:27:00.574  9791  9855 I jxcore-log: *Native tests were executed*
07-25 18:27:00.574  9791  9855 I jxcore-log: 
07-25 18:27:00.574  9791  9855 I jxcore-log: Total number of executed tests:  78
07-25 18:27:00.574  9791  9855 I jxcore-log: 
07-25 18:27:00.574  9791  9855 I jxcore-log: Number of passed tests:  76
07-25 18:27:00.574  9791  9855 I jxcore-log: 
07-25 18:27:00.575  9791  9855 I jxcore-log: Number of failed tests:  0
07-25 18:27:00.575  9791  9855 I jxcore-log: 
07-25 18:27:00.575  9791  9855 I jxcore-log: Number of ignored tests:  2
07-25 18:27:00.575  9791  9855 I jxcore-log: 
07-25 18:27:00.575  9791  9855 I jxcore-log: Total duration:  47831
07-25 18:27:00.575  9791  9855 I jxcore-log: 
,07-25 18:27:00.575  9791  9855 I jxcore-log: 2017-07-25 16:27:00 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
07-25 18:27:00.575  9791  9855 I jxcore-log: 
07-25 18:27:00.575  9791  9855 I jxcore-log: 2017-07-25 16:27:00 - WARN testUtils: 'myNameCallback not set!'
07-25 18:27:00.575  9791  9855 I jxcore-log: 
,07-25 18:27:00.797  3697  3866 D SamsungAlarmManager: Expired : 4
,07-25 18:27:00.798  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183338, SetElapsed=720999, nowELAPSED=323336
07-25 18:27:00.798  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170725T182759, SetElapsed=382538, nowELAPSED=323337
07-25 18:27:00.798  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@2420508 alarm=Alarm{a0fdf06 type 2 when 323336 android}
,07-25 18:27:00.802  3697  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 32000: mInRange : true
,07-25 18:27:00.805 10193 10193 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-25 18:27:00.805 10193 10193 I wpa_supplicant: P2P: Current p2p state = IDLE
07-25 18:27:00.807  3697  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182732 - CU:1000/CP:3697
07-25 18:27:00.807  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182732, SetElapsed=355341, nowELAPSED=323346
07-25 18:27:00.814  3697  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182715 - CU:1000/CP:3697
07-25 18:27:00.815  3697  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182715, SetElapsed=338345, nowELAPSED=323353
,07-25 18:27:00.821 10193 10193 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-25 18:27:02.022  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
07-25 18:27:02.022  9791  9855 I jxcore-log: 
,07-25 18:27:02.026  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
07-25 18:27:02.026  9791  9855 I jxcore-log: 
,07-25 18:27:02.035  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
07-25 18:27:02.035  9791  9855 I jxcore-log: 
,07-25 18:27:02.193  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
07-25 18:27:02.193  9791  9855 I jxcore-log: 
,07-25 18:27:02.222  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
07-25 18:27:02.222  9791  9855 I jxcore-log: 
,07-25 18:27:02.231  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
07-25 18:27:02.231  9791  9855 I jxcore-log: 
,07-25 18:27:02.264  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
07-25 18:27:02.264  9791  9855 I jxcore-log: 
,07-25 18:27:02.282  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
07-25 18:27:02.282  9791  9855 I jxcore-log: 
,07-25 18:27:02.286  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
07-25 18:27:02.286  9791  9855 I jxcore-log: 
,07-25 18:27:02.331  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
07-25 18:27:02.331  9791  9855 I jxcore-log: 
,07-25 18:27:02.334  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
07-25 18:27:02.334  9791  9855 I jxcore-log: 
,07-25 18:27:02.337  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
07-25 18:27:02.337  9791  9855 I jxcore-log: 
,07-25 18:27:02.341  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
07-25 18:27:02.341  9791  9855 I jxcore-log: 
,07-25 18:27:02.659  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
07-25 18:27:02.659  9791  9855 I jxcore-log: 
,07-25 18:27:02.664  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
07-25 18:27:02.664  9791  9855 I jxcore-log: 
,07-25 18:27:02.728  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
07-25 18:27:02.728  9791  9855 I jxcore-log: 
,07-25 18:27:02.731  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
07-25 18:27:02.731  9791  9855 I jxcore-log: 
,07-25 18:27:02.749  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
07-25 18:27:02.749  9791  9855 I jxcore-log: 
,07-25 18:27:02.754  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
07-25 18:27:02.754  9791  9855 I jxcore-log: 
,07-25 18:27:02.785  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
07-25 18:27:02.785  9791  9855 I jxcore-log: 
,07-25 18:27:02.826  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
07-25 18:27:02.826  9791  9855 I jxcore-log: 
,07-25 18:27:02.852  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:02.852  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:02.859  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
07-25 18:27:02.859  9791  9855 I jxcore-log: 
,07-25 18:27:02.888  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
07-25 18:27:02.888  9791  9855 I jxcore-log: 
,07-25 18:27:02.897  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
07-25 18:27:02.897  9791  9855 I jxcore-log: 
,07-25 18:27:02.943  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
07-25 18:27:02.943  9791  9855 I jxcore-log: 
,07-25 18:27:02.972  9791  9855 I jxcore-log: 2017-07-25 16:27:02 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
07-25 18:27:02.972  9791  9855 I jxcore-log: 
,07-25 18:27:03.595  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
07-25 18:27:03.595  9791  9855 I jxcore-log: 
,07-25 18:27:03.622  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
07-25 18:27:03.622  9791  9855 I jxcore-log: 
,07-25 18:27:03.626  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
07-25 18:27:03.626  9791  9855 I jxcore-log: 
,07-25 18:27:03.630  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
07-25 18:27:03.630  9791  9855 I jxcore-log: 
,07-25 18:27:03.650  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
07-25 18:27:03.650  9791  9855 I jxcore-log: 
,07-25 18:27:03.668  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
07-25 18:27:03.668  9791  9855 I jxcore-log: 
,07-25 18:27:03.682  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
07-25 18:27:03.682  9791  9855 I jxcore-log: 
,07-25 18:27:03.690  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
07-25 18:27:03.690  9791  9855 I jxcore-log: 
,07-25 18:27:03.697  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
07-25 18:27:03.697  9791  9855 I jxcore-log: 
,07-25 18:27:03.706  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
07-25 18:27:03.706  9791  9855 I jxcore-log: 
,07-25 18:27:03.723  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
07-25 18:27:03.723  9791  9855 I jxcore-log: 
,07-25 18:27:03.736  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
07-25 18:27:03.736  9791  9855 I jxcore-log: 
,07-25 18:27:03.743  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
07-25 18:27:03.743  9791  9855 I jxcore-log: 
,07-25 18:27:03.824  3697  4830 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:27:03.825  3697  4830 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4259, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-25 18:27:03.825  3697  4830 D BatteryService: online:4, current avg:-199, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:-345
07-25 18:27:03.825  3697  3697 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:27:03.831  3697  3697 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-25 18:27:03.831  3697  3697 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-25 18:27:03.834  3697  3697 D GameManagerService: new battery level: 100
,07-25 18:27:03.837  4074  4074 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-25 18:27:03.838  4074  4074 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:27:03.844  4074  4074 D PowerUI : priorPlugType = 2 mPlugType =  2
07-25 18:27:03.847  4074  4074 D BatteryMeterDrawable: isSomethingChanged - false
,07-25 18:27:03.848  4074  4074 D BatteryMeterDrawable: isSomethingChanged - false
,07-25 18:27:03.851  4074  4074 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-25 18:27:03.866  9920  9920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:27:03.867  9920  9976 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:27:03.908  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
07-25 18:27:03.908  9791  9855 I jxcore-log: 
,07-25 18:27:03.983  9791  9855 I jxcore-log: 2017-07-25 16:27:03 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
07-25 18:27:03.983  9791  9855 I jxcore-log: 
,07-25 18:27:03.996  9791  9855 D BluetoothAdapter: STATE_ON
,07-25 18:27:04.002  9791  9855 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-25 18:27:04.002  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO testUtils: 'BLE multiple advertisement supported'
07-25 18:27:04.002  9791  9855 I jxcore-log: 
07-25 18:27:04.004  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG UnitTest_app: 'Unit Test app is loaded'
07-25 18:27:04.004  9791  9855 I jxcore-log: 
,07-25 18:27:04.011  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-25 18:27:04.011  9791  9855 I jxcore-log: 
07-25 18:27:04.012  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:27:04.012  9791  9855 I jxcore-log: 
,07-25 18:27:04.012  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-25 18:27:04.012  9791  9855 I jxcore-log: 
07-25 18:27:04.013  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:27:04.013  9791  9855 I jxcore-log: 
07-25 18:27:04.013  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-25 18:27:04.013  9791  9855 I jxcore-log: 
07-25 18:27:04.013  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:27:04.013  9791  9855 I jxcore-log: 
07-25 18:27:04.013  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-25 18:27:04.013  9791  9855 I jxcore-log: 
07-25 18:27:04.013  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:27:04.013  9791  9855 I jxcore-log: 
07-25 18:27:04.014  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-25 18:27:04.014  9791  9855 I jxcore-log: 
,07-25 18:27:04.014  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:27:04.014  9791  9855 I jxcore-log: 
07-25 18:27:04.014  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-25 18:27:04.014  9791  9855 I jxcore-log: 
07-25 18:27:04.014  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:27:04.014  9791  9855 I jxcore-log: 
07-25 18:27:04.014  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-25 18:27:04.014  9791  9855 I jxcore-log: 
07-25 18:27:04.014  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-25 18:27:04.014  9791  9855 I jxcore-log: 
,07-25 18:27:04.023  9791  9791 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
07-25 18:27:04.023  9791  9791 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,07-25 18:27:04.045  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
07-25 18:27:04.045  9791  9855 I jxcore-log: 
,07-25 18:27:04.096  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG CoordinatedClient: 'connected to the test server'
07-25 18:27:04.096  9791  9855 I jxcore-log: 
,07-25 18:27:04.487  9791  9855 I jxcore-log: 2017-07-25 16:27:04 - DEBUG CoordinatedClient: 'device disconnected from the test server'
07-25 18:27:04.487  9791  9855 I jxcore-log: 
,07-25 18:27:04.662  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5322 210592 d 748 74496 f 2106 2106 iot 11820 10875 th 464488 0 0 pt 0 inp 0 0 327.199
,07-25 18:27:04.823  3298  3787 D Netd    : Iface wlan0 link up
,07-25 18:27:04.825 10193 10193 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
07-25 18:27:04.827  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:27:04.827  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:27:04.831  3697  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@e542bf4
07-25 18:27:04.835  3697  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182732, SetElapsed=355341, nowELAPSED=327373
,07-25 18:27:05.653  4885  4951 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 15ms lastUpdatedAfter : 9568 ms mFlush_time_threasold : 2000 mCurrentSize : 229
,07-25 18:27:05.682  5224 10447 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-25 18:27:05.716  5224  5864 I Icing   : App usage reports: 1
07-25 18:27:05.716  5224  5864 I Icing   : Usage reports 1 indexed 0 rejected 0 imm upload false
,07-25 18:27:05.752  5224  5864 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-25 18:27:05.789  5224  5864 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-25 18:27:05.821  5224  5864 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-25 18:27:05.853  5224  5864 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-25 18:27:05.875  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:05.876  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:05.893  5224  5864 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-25 18:27:05.920  5224  5864 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-25 18:27:07.336  9791  9855 I jxcore-log: 2017-07-25 16:27:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:07.336  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:07.336  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:07.336  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:07.336  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:07.336  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:07.336  9791  9855 I jxcore-log: 
,07-25 18:27:07.340  9791  9855 I jxcore-log: 2017-07-25 16:27:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:07.340  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:07.340  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:07.340  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:07.340  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:07.340  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:07.340  9791  9855 I jxcore-log: 
,07-25 18:27:08.903  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:08.904  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:09.664  4885  4951 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 4010 ms mFlush_time_threasold : 2000 mCurrentSize : 232
,07-25 18:27:09.667  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5378 211352 d 757 74532 f 2124 2124 iot 11850 10897 th 464656 0 0 pt 0 inp 0 0 332.205
,07-25 18:27:09.945  3697  5674 D SSRM:f  : SIOP:: AP = 330, PST = 306 (W:6), CP = 255, CUR = -122, LCD = 57
,07-25 18:27:10.379  9791  9855 I jxcore-log: 2017-07-25 16:27:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:10.379  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:10.379  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:10.379  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:10.379  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:10.379  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:10.379  9791  9855 I jxcore-log: 
,07-25 18:27:10.385  9791  9855 I jxcore-log: 2017-07-25 16:27:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:10.385  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:10.385  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:10.385  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:10.385  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:10.385  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:10.385  9791  9855 I jxcore-log: 
,07-25 18:27:11.937  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:11.938  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:14.673  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5396 211552 d 761 74548 f 2126 2126 iot 11870 10904 th 465456 0 0 pt 0 inp 0 0 337.210
,07-25 18:27:14.973  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:14.973  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:17.500  3697  4837 I ActivityManager: KPU : put [com.sec.android.service.health] : 18688 K
,07-25 18:27:17.500  3697  4837 I ActivityManager: Killing 9489:com.sec.android.service.health/u0a24 (adj 906): DHA:empty #33
,07-25 18:27:17.533  3697  3777 D ActivityManager: cleanUpApplicationRecord -- 9489
,07-25 18:27:17.534  4762  4777 D ForegroundUtils: could not check pending caller
,07-25 18:27:18.007  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:18.007  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:18.290  9791  9855 I jxcore-log: 2017-07-25 16:27:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:18.290  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:18.290  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:18.290  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:18.290  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:18.290  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:18.290  9791  9855 I jxcore-log: 
,07-25 18:27:18.294  9791  9855 I jxcore-log: 2017-07-25 16:27:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:18.294  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:18.294  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:18.294  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:18.294  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:18.294  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:18.294  9791  9855 I jxcore-log: 
,07-25 18:27:18.577  8731  8763 I PlayCommon: [744] com.google.android.play.a.g.e(932): Preparing logs for uploading
,07-25 18:27:18.584  8731  8763 W PlayCommon: [744] com.google.android.play.a.g.a(1239): No account for auth token provided
,07-25 18:27:18.585  8731  8763 I PlayCommon: [744] com.google.android.play.a.g.a(1035): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-25 18:27:18.589  8731  8763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:27:18.590  8731  8763 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-25 18:27:18.595  3298  3790 D EnterpriseController: netId is 0
07-25 18:27:18.595  3298  3790 D Netd    : getNetworkForDns: using netid 503 for uid 10032
07-25 18:27:18.595  3298  3790 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-25 18:27:18.888  8731  8763 I PlayCommon: [744] com.google.android.play.a.g.a(1113): Successfully uploaded logs.
,07-25 18:27:19.678  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5411 211668 d 762 74552 f 2127 2127 iot 11870 10907 th 466288 0 0 pt 0 inp 0 0 342.215
,07-25 18:27:19.968  3697  5674 D SSRM:f  : SIOP:: AP = 300, PST = 308 (W:14), CP = 252, CUR = -50, LCD = 57
,07-25 18:27:21.040  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:21.041  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:21.191  3697  3697 D UsbMonitorService: readUsbState++
,07-25 18:27:21.192  3697  3697 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-25 18:27:21.194  3697  3697 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-25 18:27:21.194  3697  3697 D UsbMonitorService: Posting Message again
,07-25 18:27:23.242  3697  4463 E Watchdog: !@Sync 11 [25_lip_18_27_23.241]
,07-25 18:27:24.065  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:24.065  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:24.683  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5412 211720 d 764 74560 f 2128 2128 iot 11870 10909 th 466308 0 0 pt 0 inp 0 0 347.221
,07-25 18:27:27.098  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:27.098  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:28.328  9791  9855 I jxcore-log: 2017-07-25 16:27:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:28.328  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:28.328  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:28.328  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:28.328  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:28.328  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:28.328  9791  9855 I jxcore-log: 
,07-25 18:27:28.331  9791  9855 I jxcore-log: 2017-07-25 16:27:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:28.331  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:28.331  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:28.331  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:28.331  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:28.331  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:28.331  9791  9855 I jxcore-log: 
,07-25 18:27:29.996  3697  5674 D SSRM:f  : SIOP:: AP = 290, PST = 302 (W:14), CP = 247, CUR = -20, LCD = 57
,07-25 18:27:30.150  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:30.150  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:32.802  3697  3866 D SamsungAlarmManager: Expired : 4
,07-25 18:27:32.803  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183338, SetElapsed=720999, nowELAPSED=355342
07-25 18:27:32.804  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@359f9c7 alarm=Alarm{b1415b6 type 2 when 355341 android}
,07-25 18:27:32.808  3697  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 64000: mInRange : true
,07-25 18:27:32.812 10193 10193 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-25 18:27:32.812 10193 10193 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-25 18:27:32.814  3697  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182836 - CU:1000/CP:3697
07-25 18:27:32.817  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182836, SetElapsed=419347, nowELAPSED=355356
,07-25 18:27:32.826  3697  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182747 - CU:1000/CP:3697
,07-25 18:27:32.827  3697  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182747, SetElapsed=370359, nowELAPSED=355366
07-25 18:27:32.828 10193 10193 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-25 18:27:33.177  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:33.177  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:33.891  3697  3944 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:27:33.892  3697  3944 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4316, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-25 18:27:33.892  3697  3944 D BatteryService: online:4, current avg:-14, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-25 18:27:33.893  3697  3697 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-25 18:27:33.904  3697  3697 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-25 18:27:33.904  3697  3697 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-25 18:27:33.908  3697  3697 D GameManagerService: new battery level: 100
,07-25 18:27:33.914  4074  4074 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-25 18:27:33.915  4074  4074 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-25 18:27:33.924  4074  4074 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-25 18:27:33.928  4074  4074 D BatteryMeterDrawable: isSomethingChanged - false
07-25 18:27:33.931  4074  4074 D BatteryMeterDrawable: isSomethingChanged - false
,07-25 18:27:33.955  4074  4074 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-25 18:27:33.963  9920  9920 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-25 18:27:33.964  9920  9976 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-25 18:27:34.694  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5422 211780 d 764 74560 f 2130 2130 iot 11870 10911 th 467236 0 0 pt 0 inp 0 0 357.231
,07-25 18:27:36.199  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:36.199  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:36.825  3298  3787 D Netd    : Iface wlan0 link up
,07-25 18:27:36.827 10193 10193 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
07-25 18:27:36.828  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:27:36.828  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
,07-25 18:27:36.833  3697  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@d547a24
,07-25 18:27:36.837  3697  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182836, SetElapsed=419347, nowELAPSED=359376
,07-25 18:27:38.370  9791  9855 I jxcore-log: 2017-07-25 16:27:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:38.370  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:38.370  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:38.370  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:38.370  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:38.370  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:38.370  9791  9855 I jxcore-log: 
,07-25 18:27:38.373  9791  9855 I jxcore-log: 2017-07-25 16:27:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:38.373  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:38.373  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:38.373  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:38.373  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:38.373  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:38.373  9791  9855 I jxcore-log: 
,07-25 18:27:39.223  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:39.224  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:39.699  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5426 211804 d 764 74560 f 2131 2131 iot 11870 10912 th 467168 0 0 pt 0 inp 0 0 362.236
,07-25 18:27:40.022  3697  5674 D SSRM:f  : SIOP:: AP = 280, PST = 301 (W:14), CP = 244, CUR = -7, LCD = 57
,07-25 18:27:41.325  3697  3832 I PowerManagerService: [PWL] On : 0 (363864 ms ago)
07-25 18:27:41.326  3697  3832 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-25 18:27:42.256  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:42.256  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:44.704  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5427 211808 d 764 74560 f 2131 2131 iot 11870 10913 th 467232 0 0 pt 0 inp 0 0 367.241
,07-25 18:27:45.290  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:45.290  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:47.615  3697  4022 D WifiWatchdogStateMachine:  [|212] []
,07-25 18:27:48.324  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:48.324  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:48.408  9791  9855 I jxcore-log: 2017-07-25 16:27:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:48.408  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:48.408  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:48.408  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:48.408  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:48.408  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:48.408  9791  9855 I jxcore-log: 
,07-25 18:27:48.412  9791  9855 I jxcore-log: 2017-07-25 16:27:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:48.412  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:48.412  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:48.412  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:48.412  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:48.412  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:48.412  9791  9855 I jxcore-log: 
,07-25 18:27:50.050  3697  5674 D SSRM:f  : SIOP:: AP = 280, PST = 300 (W:14), CP = 243, CUR = -3, LCD = 57
,07-25 18:27:51.196  3697  3697 D UsbMonitorService: readUsbState++
,07-25 18:27:51.197  3697  3697 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-25 18:27:51.199  3697  3697 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-25 18:27:51.199  3697  3697 D UsbMonitorService: Posting Message again
,07-25 18:27:51.356  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:51.357  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:53.244  3697  4463 E Watchdog: !@Sync 12 [25_lip_18_27_53.243]
,07-25 18:27:54.381  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:54.381  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:56.192  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-25 18:27:56.192  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-25 18:27:56.192  4885  4951 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1, com.google.android.gms=2})  ]
,07-25 18:27:56.199  4885  4951 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 46535 ms mFlush_time_threasold : 2000 mCurrentSize : 283
,07-25 18:27:57.414  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:27:57.414  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:27:58.442  9791  9855 I jxcore-log: 2017-07-25 16:27:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:58.442  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:58.442  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:58.442  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:58.442  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:58.442  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:58.442  9791  9855 I jxcore-log: 
,07-25 18:27:58.445  9791  9855 I jxcore-log: 2017-07-25 16:27:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:27:58.445  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:27:58.445  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:27:58.445  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:27:58.445  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:27:58.445  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:27:58.445  9791  9855 I jxcore-log: 
,07-25 18:27:59.719  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5431 211896 d 765 74564 f 2133 2133 iot 11880 10916 th 467228 0 0 pt 0 inp 0 0 382.256
,07-25 18:27:59.999  3697  3866 D SamsungAlarmManager: Expired : 8
,07-25 18:28:00.000  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{104f353 type 3 when 382538 android}
,07-25 18:28:00.009  3697  3697 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170725T182900 - CU:1000/CP:3697
,07-25 18:28:00.013  4074  4074 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-25 18:28:00.014  4074  4074 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-25 18:28:00.015  4074  4074 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-25 18:28:00.036  4074  4074 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-25 18:28:00.036  4074  4074 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-25 18:28:00.040  4074  4074 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-25 18:28:00.055  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:28:00.056  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
07-25 18:28:00.059  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
07-25 18:28:00.062  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:28:00.083  3697  5674 D SSRM:f  : SIOP:: AP = 280, PST = 297 (W:14), CP = 241, CUR = -1, LCD = 57
,07-25 18:28:00.085  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
07-25 18:28:00.086  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:28:00.096  4074  4074 V hong    : mid yDiff = 438
07-25 18:28:00.097  4074  4074 V hong    : mid yDiff = 438
07-25 18:28:00.097  4074  4074 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-25 18:28:00.097  4074  4074 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-25 18:28:00.099  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-25 18:28:00.101  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:28:00.114  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : start
07-25 18:28:00.116  4074  4074 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-25 18:28:00.131  4074  4074 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-25 18:28:00.134  4074  4074 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-25 18:28:00.154  5069  5069 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-25 18:28:00.156  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-25 18:28:00.163  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-25 18:28:00.167  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-25 18:28:00.168  5069  5069 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-25 18:28:00.169  5069  5069 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-25 18:28:00.170  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-25 18:28:00.171  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-25 18:28:00.175  5069  5069 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-25 18:28:00.176  5069  5069 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900C3CC40EFB9853E5512D58DCA498126DE963EAC24F3F54C4A1A0F1E149B77BC1838DEF14BC320A404F15FF267A286878E9]}
07-25 18:28:00.177  5069  5069 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-25 18:28:00.191  3697  3707 I art     : Background sticky concurrent mark sweep GC freed 223053(12MB) AllocSpace objects, 69(1428KB) LOS objects, 25% free, 42MB/56MB, paused 2.305ms total 144.075ms
,07-25 18:28:00.447  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:00.448  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:03.478  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:03.479  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:03.952  3697  3928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:28:04.724  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5435 211960 d 766 74568 f 2135 2135 iot 11880 10919 th 467440 0 0 pt 0 inp 0 0 387.262
,07-25 18:28:06.512  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:06.513  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:08.479  9791  9855 I jxcore-log: 2017-07-25 16:28:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:08.479  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:08.479  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:08.479  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:08.479  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:08.479  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:08.479  9791  9855 I jxcore-log: 
,07-25 18:28:08.483  9791  9855 I jxcore-log: 2017-07-25 16:28:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:08.483  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:08.483  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:08.483  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:08.483  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:08.483  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:08.483  9791  9855 I jxcore-log: 
,07-25 18:28:09.540  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:09.540  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:09.730  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5446 212016 d 766 74568 f 2136 2136 iot 11880 10923 th 468292 0 0 pt 0 inp 0 0 392.267
,07-25 18:28:10.117  3697  5674 D SSRM:f  : SIOP:: AP = 280, PST = 293 (W:14), CP = 240, LCD = 57
,07-25 18:28:12.573  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:12.574  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:14.736  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5447 212020 d 766 74568 f 2136 2136 iot 11880 10924 th 468448 0 0 pt 0 inp 0 0 397.273
,07-25 18:28:15.608  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:15.608  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:18.518  9791  9855 I jxcore-log: 2017-07-25 16:28:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:18.518  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:18.518  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:18.518  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:18.518  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:18.518  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:18.518  9791  9855 I jxcore-log: 
,07-25 18:28:18.521  9791  9855 I jxcore-log: 2017-07-25 16:28:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:18.521  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:18.521  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:18.521  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:18.521  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:18.521  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:18.521  9791  9855 I jxcore-log: 
,07-25 18:28:18.631  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:18.631  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:20.145  3697  5674 D SSRM:f  : SIOP:: AP = 280, PST = 292 (W:14), CP = 240, LCD = 57
,07-25 18:28:21.200  3697  3697 D UsbMonitorService: readUsbState++
,07-25 18:28:21.202  3697  3697 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-25 18:28:21.204  3697  3697 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-25 18:28:21.204  3697  3697 D UsbMonitorService: Posting Message again
,07-25 18:28:21.664  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:21.664  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:23.245  3697  4463 E Watchdog: !@Sync 13 [25_lip_18_28_23.245]
,07-25 18:28:24.688  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:24.688  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:27.721  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-25 18:28:27.721  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:28.585  9791  9855 I jxcore-log: 2017-07-25 16:28:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:28.585  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:28.585  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:28.585  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:28.585  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:28.585  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:28.585  9791  9855 I jxcore-log: 
,07-25 18:28:28.591  9791  9855 I jxcore-log: 2017-07-25 16:28:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:28.591  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:28.591  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:28.591  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:28.591  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:28.591  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:28.591  9791  9855 I jxcore-log: 
,07-25 18:28:30.173  3697  5674 D SSRM:f  : SIOP:: AP = 280, PST = 290 (W:14), CP = 239, LCD = 57
,07-25 18:28:30.754  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:30.755  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:33.787  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:33.788  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-25 18:28:34.008  3697  4547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-25 18:28:36.808  3697  3866 D SamsungAlarmManager: Expired : 4
07-25 18:28:36.809  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183338, SetElapsed=720998, nowELAPSED=419348
,07-25 18:28:36.810  3697  3866 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170725T182900, SetElapsed=442539, nowELAPSED=419349
07-25 18:28:36.811  3697  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@6eee2b7 alarm=Alarm{9c9d189 type 2 when 419347 android}
,07-25 18:28:36.822  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:36.822  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -39
,07-25 18:28:36.830  3697  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-25 18:28:36.834 10193 10193 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-25 18:28:36.835 10193 10193 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-25 18:28:36.843  3697  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T183044 - CU:1000/CP:3697
07-25 18:28:36.843  3697  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183044, SetElapsed=547372, nowELAPSED=419382
,07-25 18:28:36.846  3697  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170725T182851 - CU:1000/CP:3697
,07-25 18:28:36.846  3697  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T182851, SetElapsed=434379, nowELAPSED=419385
,07-25 18:28:36.850 10193 10193 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-25 18:28:38.756  9791  9855 I jxcore-log: 2017-07-25 16:28:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:38.756  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:38.756  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:38.756  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:38.756  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:38.756  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:38.756  9791  9855 I jxcore-log: 
,07-25 18:28:38.763  9791  9855 I jxcore-log: 2017-07-25 16:28:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:38.763  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:38.763  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:38.763  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:38.763  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:38.763  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:38.763  9791  9855 I jxcore-log: 
,07-25 18:28:39.760  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5449 212036 d 766 74568 f 2138 2138 iot 11880 10925 th 470872 0 0 pt 0 inp 0 0 422.298
,07-25 18:28:39.845  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:39.845  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:40.205  3697  5674 D SSRM:f  : SIOP:: AP = 280, PST = 289 (W:14), CP = 239, CUR = 2, LCD = 57
,07-25 18:28:40.589  9654  9680 V NativeCrypto: SSL shutdown failed: ssl=0x7a4248fc00: I/O error during system call, Software caused connection abort
,07-25 18:28:40.827  3298  3787 D Netd    : Iface wlan0 link up
07-25 18:28:40.828 10193 10193 I wpa_supplicant: nl80211: Received scan results (24 BSSes)
,07-25 18:28:40.831  3697  3828 D Tethering: interfaceLinkStateChanged wlan0, true
07-25 18:28:40.831  3697  3828 D Tethering: interfaceStatusChanged wlan0, true
07-25 18:28:40.833  3697  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3697 / listener:android.app.AlarmManager$ListenerWrapper@a6171af
,07-25 18:28:40.836  3697  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170725T183044, SetElapsed=547372, nowELAPSED=423375
,07-25 18:28:41.773  4718  7476 V NativeCrypto: SSL shutdown failed: ssl=0x7a4e69d680: I/O error during system call, Software caused connection abort
,07-25 18:28:42.878  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:42.879  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:44.766  4645  4645 D io_stats: !@   8,0 r 25310 2274832 w 5450 212040 d 766 74568 f 2138 2138 iot 11880 10926 th 470876 0 0 pt 0 inp 0 0 427.303
,07-25 18:28:45.913  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-25 18:28:45.913  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:46.336  3697  3832 I PowerManagerService: [PWL] On : 0 (428874 ms ago)
07-25 18:28:46.336  3697  3832 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-25 18:28:48.799  9791  9855 I jxcore-log: 2017-07-25 16:28:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:48.799  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:48.799  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:48.799  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:48.799  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:48.799  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:48.799  9791  9855 I jxcore-log: 
,07-25 18:28:48.805  9791  9855 I jxcore-log: 2017-07-25 16:28:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-25 18:28:48.805  9791  9855 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-25 18:28:48.805  9791  9855 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-25 18:28:48.805  9791  9855 I jxcore-log: emit@events.js:82:1
07-25 18:28:48.805  9791  9855 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-25 18:28:48.805  9791  9855 I jxcore-log: emit@events.js:82:1''
07-25 18:28:48.805  9791  9855 I jxcore-log: 
,07-25 18:28:48.936  3697  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-25 18:28:48.936  3697  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -40
,07-25 18:28:49.858  3697  4022 D WifiWatchdogStateMachine:  [|215] []
,07-25 18:28:50.242  3697  5674 D SSRM:f  : SIOP:: AP = 280, PST = 287 (W:14), CP = 238, CUR = 1, LCD = 57

```
