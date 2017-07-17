#### Test 1271987109197780_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,07-17 13:38:15.344  3704  4328 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
--------- beginning of main
07-17 13:38:15.836  9613  9613 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9613 | app_process
07-17 13:38:15.836  9613  9613 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
07-17 13:38:15.842  9613  9613 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
07-17 13:38:15.842  9613  9613 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-17 13:38:15.844  9613  9613 D AndroidRuntime: CheckJNI is OFF
07-17 13:38:15.845  9613  9613 D AndroidRuntime: addProductProperty: start
07-17 13:38:15.883  9613  9613 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
07-17 13:38:15.883  9613  9613 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
07-17 13:38:15.898  9613  9613 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-17 13:38:15.898  9613  9613 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
07-17 13:38:15.898  9613  9613 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
07-17 13:38:15.942  9613  9613 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
07-17 13:38:15.960  9613  9613 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-17 13:38:15.981  9613  9613 I Enhanced Zygote ASLR: DISABLED!
07-17 13:38:15.981  9613  9613 I Radio-JNI: register_android_hardware_Radio DONE
07-17 13:38:15.984  9613  9613 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
07-17 13:38:15.984  9613  9613 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
07-17 13:38:15.985  9613  9613 E SemAffinityControl: SemAffinityControl: registerfunction enter
07-17 13:38:15.993  9613  9613 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-17 13:38:16.010  3704  4183 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}} from uid 2000 on display 0
07-17 13:38:16.050  3704  4183 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
07-17 13:38:16.052  3704  4183 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3704  pkgName : AMS_RESUME@CPU_MIN@7
07-17 13:38:16.055  3704  4183 D ActivityManager: mActivityResumeBooster.acquire()
07-17 13:38:16.057  3704  4183 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{3465637d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
07-17 13:38:16.057  3704  4183 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{3465637d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1}
07-17 13:38:16.057  3704  4183 D InputDispatcher: Focused application set to: xxxx
07-17 13:38:16.058  3704  4183 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{3465637d0 #5 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} next=ActivityRecord{23f1f5bd0 u0 com.thaliproject.thalitest/.MainActivity t5} mFocusedStack=ActivityStack{b7304c1d0 stackId=1, 2 tasks}
07-17 13:38:16.059  3704  4183 D MountService: getExternalStorageMountMode : 1
07-17 13:38:16.059  3704  4183 D MountService: getExternalStorageMountMode : 3
07-17 13:38:16.059  3704  4183 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10033, packageName : com.thaliproject.thalitest
07-17 13:38:16.067  3704  3813 D WindowManager: addWindow: android.view.ViewRootImpl$W@3b0473c displayId=0
07-17 13:38:16.067  3704  3813 D InputTransport: Input channel constructed: fd=455
07-17 13:38:16.067  3704  3813 D InputTransport: Input channel constructed: fd=456
07-17 13:38:16.068  3704  3813 D ViewRootImpl@4c3d52f[thalitest]: setView = DecorView@dfb661a[thalitest] touchMode=true
07-17 13:38:16.070  3704  3813 V WindowManager: Relayout Window{c2accc5d0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-17 13:38:16.071  3111  3111 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, uhalitest
07-17 13:38:16.072  9623  9623 E Zygote  : v2
07-17 13:38:16.072  9623  9623 I libpersona: KNOX_SDCARD checking this for 10033
07-17 13:38:16.072  9623  9623 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:16.073  9623  9623 E Zygote  : accessInfo : 0
07-17 13:38:16.075  3704  4183 I ActivityManager: Start proc 9623:com.thaliproject.thalitest/u0a33 for activity com.thaliproject.thalitest/.MainActivity
07-17 13:38:16.079  9623  9623 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-17 13:38:16.080  9623  9623 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
07-17 13:38:16.085  3704  3813 D WindowManager: finishDrawingWindow: Window{c2accc5d0 u0 Starting com.thaliproject.thalitest} mDrawState=DRAW_PENDING
07-17 13:38:16.086  9613  9613 D AndroidRuntime: Shutting down VM
07-17 13:38:16.100  3704  3813 V WindowManager: Now policy hidden: Window{c2accc5d0 u0 Starting com.thaliproject.thalitest}
07-17 13:38:16.104  9623  9623 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:16.104  9623  9623 D ActivityThread: Added TimaKeyStore provider
07-17 13:38:16.107  3704  6348 I ActivityManager: DSS on for com.thaliproject.thalitest and scale is 1.0
07-17 13:38:16.109  3704  6348 I WindowManager: Failed to capture screenshot of Token{b0723a7 ActivityRecord{9b20466d0 u0 com.samsung.android.MtpApplication/.USBConnection t4}} appWin=Window{9ba5316d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
07-17 13:38:16.112  9613  9613 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
07-17 13:38:16.112  9613  9613 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
07-17 13:38:16.112  9613  9613 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
07-17 13:38:16.112  9613  9613 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
,07-17 13:38:16.117  3704  6348 I ActivityManager: KPU : put [com.samsung.android.bbc.bbcagent] : 27080 K
07-17 13:38:16.117  3704  6348 I ActivityManager: Killing 8929:com.samsung.android.bbc.bbcagent/1000 (adj 906): DHA:empty #33
07-17 13:38:16.119  3704  6348 D GameManagerService: sem_perfomance_mode: 0
07-17 13:38:16.119  3704  3704 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
07-17 13:38:16.119  3704  3704 D GameManagerService: unexpected mPrevNotiType: -1
07-17 13:38:16.124  3704  4184 V WindowManager: Relayout Window{9ba5316d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
07-17 13:38:16.124  3704  6348 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
07-17 13:38:16.125  3704  6348 D GameManagerService: sem_perfomance_mode: 0
07-17 13:38:16.127  3704  5557 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-17 13:38:16.127  3704  5557 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-17 13:38:16.128  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:16.128  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:16.129  4670  4686 D ForegroundUtils: could not check pending caller
07-17 13:38:16.134  3704  3813 D ViewRootImpl@4c3d52f[thalitest]: MSG_RESIZED: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-17 13:38:16.136  3704  3813 V WindowManager: Relayout Window{c2accc5d0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,07-17 13:38:16.141  3704  4328 V WindowManager: Relayout Window{9b30847d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
07-17 13:38:16.141  3704  5557 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-17 13:38:16.141  3704  4328 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowManagerService.tryStartExitingAnimation:3504 com.android.server.wm.WindowManagerService.relayoutWindow:3360 com.android.server.wm.Session.relayoutEx:244 android.view.IWindowSession$Stub.onTransact:407 com.android.server.wm.Session.onTransact:151 
07-17 13:38:16.142  3111  3119 I SurfaceFlinger: id=12 Removed MauncherAct (1/5)
07-17 13:38:16.142  3704  5557 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
07-17 13:38:16.142  3111  9361 I SurfaceFlinger: id=12 Removed MauncherAct (-2/5)
07-17 13:38:16.146  4799  4799 D Launcher: onTrimMemory. Level: 20
07-17 13:38:16.149  3704  3813 D WindowManager: finishDrawingWindow: Window{c2accc5d0 u0 Starting com.thaliproject.thalitest} mDrawState=HAS_DRAWN
,07-17 13:38:16.154  3704  4183 V WindowManager: Relayout Window{efee7bbd0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
07-17 13:38:16.155  3704  4338 D ActivityManager: cleanUpApplicationRecord -- 8929
,07-17 13:38:16.157  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:16.158  3704  3911 V WindowManager: Relayout Window{9b30847d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,07-17 13:38:16.160  3704  5299 V WindowManager: Relayout Window{9ba5316d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,07-17 13:38:16.168  9623  9623 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:16.193  9623  9623 I CordovaLog: Changing log level to DEBUG(3)
07-17 13:38:16.193  9623  9623 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
07-17 13:38:16.193  9623  9623 D CordovaActivity: CordovaActivity.onCreate()
,07-17 13:38:16.204  9623  9623 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm
,07-17 13:38:16.207  4528  4528 D io_stats: !@   8,0 r 25445 2234440 w 4811 204152 d 603 74212 f 1993 1993 iot 11040 10470 th 495992 0 0 pt 0 inp 0 0 166.950
,07-17 13:38:16.209  9623  9623 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,07-17 13:38:16.257  9623  9623 I cr_LibraryLoader: Time to load native libraries: 14 ms (timestamps 6986-7000)
,07-17 13:38:16.257  9623  9623 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
07-17 13:38:16.257  3704  3993 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,07-17 13:38:16.273  9623  9623 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,07-17 13:38:16.280  9623  9623 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,07-17 13:38:16.298  9623  9623 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,07-17 13:38:16.438  3704  4182 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10033
,07-17 13:38:16.439  3704  4182 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,07-17 13:38:16.441  3704  3704 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
07-17 13:38:16.441  3704  3918 I KnoxVpnEngineService: vpn handle : Message received
,07-17 13:38:16.471  9623  9623 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9623
,07-17 13:38:16.473  3704  4752 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9623 for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-17 13:38:16.474  3704  3963 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-17 13:38:16.474  3704  3963 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:16.474  3704  3963 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:16.474  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-17 13:38:16.515  9623  9623 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-17 13:38:16.522  9623  9623 D PluginManager: init()
,07-17 13:38:16.526  9623  9623 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,07-17 13:38:16.545  9623  9623 I cr_Ime  : ImeThread is enabled.
,07-17 13:38:16.557  9623  9623 D CordovaActivity: Started the activity.
,07-17 13:38:16.560  9623  9623 D CordovaActivity: Resumed the activity.
,07-17 13:38:16.574  3704  4752 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@d5907 displayId=0
,07-17 13:38:16.574  3704  4752 D InputTransport: Input channel constructed: fd=457
07-17 13:38:16.574  3704  4752 D InputTransport: Input channel constructed: fd=459
,07-17 13:38:16.575  3704  4752 D InputTransport: Input channel destroyed: fd=459
,07-17 13:38:16.576  9623  9623 D InputTransport: Input channel constructed: fd=98
07-17 13:38:16.576  9623  9623 D ViewRootImpl@e0bc5bf[MainActivity]: setView = DecorView@1fd948c[MainActivity] touchMode=true
,07-17 13:38:16.576  3704  3760 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
07-17 13:38:16.576  3704  3760 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
07-17 13:38:16.576  3704  3704 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
,07-17 13:38:16.577  9623  9623 D CordovaActivity: Paused the activity.
07-17 13:38:16.578  3704  3704 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-17 13:38:16.581  3704  3788 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,07-17 13:38:16.586  9623  9623 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9623
,07-17 13:38:16.587  3704  4184 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9623 for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-17 13:38:16.588  3704  3963 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-17 13:38:16.588  3704  3963 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:16.588  3704  3963 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
,07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:16.588  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:16.589  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-17 13:38:16.600  3704  5299 V WindowManager: Relayout Window{551d05dd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
07-17 13:38:16.601  3111  3111 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, NainActivit
07-17 13:38:16.606  9623  9671 I OpenGLRenderer: Initialized EGL, version 1.4
07-17 13:38:16.606  9623  9671 D OpenGLRenderer: Swap behavior 1
07-17 13:38:16.609  9623  9671 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
07-17 13:38:16.610  9623  9671 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
07-17 13:38:16.611  9623  9623 D CordovaActivity: Stopped the activity.
07-17 13:38:16.621  3704  3813 V WindowManager: Now policy hidden: Window{551d05dd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}
,07-17 13:38:16.657  9623  9677 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,07-17 13:38:16.661  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:16.661  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:16.683  9623  9677 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,07-17 13:38:16.684  9623  9677 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-17 13:38:16.686  3704  4182 D WindowManager: finishDrawingWindow: Window{551d05dd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=DRAW_PENDING
07-17 13:38:16.686  9623  9677 W AudioCapabilities: Unsupported mime audio/x-ms-wma
07-17 13:38:16.686  9623  9623 D ViewRootImpl@e0bc5bf[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-17 13:38:16.686  9623  9677 W AudioCapabilities: Unsupported mime audio/x-ima
,07-17 13:38:16.688  9623  9677 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 13:38:16.688  9623  9677 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 13:38:16.688  9623  9677 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.692  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.695  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-17 13:38:16.696  3704  3813 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-17 13:38:16.696  3704  3704 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
07-17 13:38:16.696  3704  3813 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +571ms (total +638ms)
07-17 13:38:16.697  3704  3788 D ActivityManager: mActivityResumeBoosterTail.acquire()
07-17 13:38:16.697  3704  3704 I KnoxTimeoutHandler: SD activityfalse
07-17 13:38:16.697  3704  3704 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
07-17 13:38:16.697  3704  3813 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3704  tag : AMS_RESUME@CPU_MIN@7
07-17 13:38:16.697  3704  3813 D ActivityManager: mActivityResumeBooster.release()
07-17 13:38:16.697  3704  3813 D ViewRootImpl@4c3d52f[thalitest]: dispatchDetachedFromWindow
07-17 13:38:16.698  3704  3813 I WindowManager: Destroying surface Surface(name=Starting com.thaliproject.thalitest) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
07-17 13:38:16.699  3111  3117 I SurfaceFlinger: id=15 Removed uhalitest (3/5)
,07-17 13:38:16.699  3704  3788 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3704  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
07-17 13:38:16.700  3111  9455 I SurfaceFlinger: id=15 Removed uhalitest (-2/5)
07-17 13:38:16.702  3704  3813 D InputTransport: Input channel destroyed: fd=455
07-17 13:38:16.702  3704  3813 D InputTransport: Input channel destroyed: fd=456
07-17 13:38:16.705  3704  6348 D WindowManager: finishDrawingWindow: Window{551d05dd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=HAS_DRAWN
07-17 13:38:16.706  9623  9623 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
07-17 13:38:16.708  9623  9677 W VideoCapabilities: Unsupported mime video/wvc1
07-17 13:38:16.709  9623  9677 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-17 13:38:16.714  9623  9677 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 13:38:16.714  9623  9677 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 13:38:16.714  9623  9677 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
07-17 13:38:16.715  9623  9677 W VideoCapabilities: Unsupported mime video/wvc1
07-17 13:38:16.716  9623  9677 W VideoCapabilities: Unsupported mime video/x-ms-wmv
07-17 13:38:16.717  9623  9677 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
07-17 13:38:16.718  9623  9677 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
07-17 13:38:16.719  9623  9677 W VideoCapabilities: Unsupported mime video/mp43
07-17 13:38:16.722  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.722  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.722  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.722  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.722  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.722  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.722  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.723  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.723  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.723  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.723  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.723  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.723  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.723  9623  9677 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
07-17 13:38:16.726  9623  9677 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
07-17 13:38:16.726  9623  9677 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
07-17 13:38:16.726  9623  9677 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,07-17 13:38:16.741  9623  9677 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
07-17 13:38:16.754  9623  9677 W VideoCapabilities: Unsupported mime video/sorenson
07-17 13:38:16.770  9623  9677 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,07-17 13:38:16.798  9623  9623 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9623
,07-17 13:38:16.940  9623  9623 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,07-17 13:38:16.951  9623  9623 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,07-17 13:38:16.995  9623  9684 D jxcore_app_log: JniHelper::setJavaVM(0xe9db4000), pthread_self() = -1024988896
,07-17 13:38:16.998  9623  9684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-17 13:38:16.998  9623  9684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-17 13:38:16.998  9623  9684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-17 13:38:16.998  9623  9684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-17 13:38:16.998  9623  9684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-17 13:38:16.998  9623  9684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c41c8e added. We now have 1 listener(s)
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c41c8e added. We now have 1 listener(s)
,07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-17 13:38:16.999  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-17 13:38:17.001  3704  3704 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3704  tag : AMS_RESUME_TAIL@CPU_MIN@13
07-17 13:38:17.001  9623  9684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,07-17 13:38:17.002  9623  9684 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
07-17 13:38:17.002  9623  9684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-17 13:38:17.002  9623  9684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,07-17 13:38:17.003  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-17 13:38:17.004  9623  9684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfaa045 added. We now have 2 listener(s)
07-17 13:38:17.004  9623  9684 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-17 13:38:17.008  9623  9684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-17 13:38:17.008  9623  9684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 36489
07-17 13:38:17.008  9623  9684 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 116
07-17 13:38:17.008  9623  9684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-17 13:38:17.008  9623  9684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-17 13:38:17.009  9623  9684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
07-17 13:38:17.009  9623  9684 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 116
,07-17 13:38:17.014  9623  9684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-17 13:38:17.014  9623  9684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,07-17 13:38:17.028  9623  9684 D BluetoothAdapter: STATE_ON
,07-17 13:38:17.030  9623  9684 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:17.031  9623  9684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-17 13:38:17.031  9623  9684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-17 13:38:17.031  9623  9684 D io.jxcore.node.ConnectivityMonitor: start: OK
07-17 13:38:17.031  9623  9684 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-17 13:38:17.035  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:17.040  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:17.044  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:17.047  9623  9623 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
07-17 13:38:17.047  9623  9623 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,07-17 13:38:17.709  9623  9687 W jxcore-log: Initializing JXcore engine
07-17 13:38:17.709  9623  9687 W jxcore-log: JXcore engine is ready
,07-17 13:38:17.727  3246  3246 E audit   : type=1400 audit(1500291497.721:228): avc:  denied  { ioctl } for  pid=9687 comm="Thread-9" path="socket:[62362]" dev="sockfs" ino=62362 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0 SEPF_SECMOBILE_7.0_0006
,07-17 13:38:17.728  3246  3246 E audit   : type=1300 audit(1500291497.721:228): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3 a1=5451 a2=2a3f88cd a3=22 items=0 ppid=3275 pid=9687 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,07-17 13:38:17.729  3704  3805 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / "com.thaliproject.thalitest"
,07-17 13:38:17.729  3246  3246 E audit   : type=1327 audit(1500291497.721:228): proctitle="com.thaliproject.thalitest"
07-17 13:38:17.729  3246  3246 E audit   : type=1320 audit(1500291497.721:228): 
,07-17 13:38:17.729  3246  3246 E audit   : type=1400 audit(1500291497.721:229): avc:  denied  { ioctl } for  pid=9687 comm="Thread-9" path="/dev/pmsg0" dev="tmpfs" ino=15096 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0 SEPF_SECMOBILE_7.0_0006
07-17 13:38:17.730  3704  3805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-17 13:38:17.730  3246  3246 E audit   : type=1300 audit(1500291497.721:229): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=4 a1=5451 a2=2a3f88cd a3=22 items=0 ppid=3275 pid=9687 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-17 13:38:17.730  3246  3246 E audit   : type=1327 audit(1500291497.721:229): proctitle="com.thaliproject.thalitest"
07-17 13:38:17.731  3246  3246 E audit   : type=1320 audit(1500291497.721:229): 
,07-17 13:38:17.731  3246  3246 E audit   : type=1400 audit(1500291497.721:230): avc:  denied  { ioctl } for  pid=9687 comm="Thread-9" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2383 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs_trace_marker:s0 tclass=file permissive=0 SEPF_SECMOBILE_7.0_0006
07-17 13:38:17.732  3246  3246 E audit   : type=1300 audit(1500291497.721:230): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=5 a1=5451 a2=2a3f88cd a3=22 items=0 ppid=3275 pid=9687 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-17 13:38:17.732  3704  3805 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-17 13:38:17.733  9623  9687 W jxcore-log: Starting JXcore engine
,07-17 13:38:17.734  3704  3788 D MountService: getExternalStorageMountMode : 1
07-17 13:38:17.734  3704  3788 D MountService: getExternalStorageMountMode : 3
07-17 13:38:17.734  3704  3788 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.securitylogagent
,07-17 13:38:17.737  3246  3246 E audit   : type=1327 audit(1500291497.721:230): proctitle="com.thaliproject.thalitest"
07-17 13:38:17.737  3246  3246 E audit   : type=1320 audit(1500291497.721:230): 
07-17 13:38:17.737  3704  3805 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / "com.thaliproject.thalitest"
07-17 13:38:17.738  3246  3246 E audit   : type=1400 audit(1500291497.721:231): avc:  denied  { ioctl } for  pid=9687 comm="Thread-9" path="socket:[62464]" dev="sockfs" ino=62464 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0 SEPF_SECMOBILE_7.0_0006
07-17 13:38:17.738  3704  3805 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-17 13:38:17.738  3246  3246 E audit   : type=1300 audit(1500291497.721:231): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=54 a1=5451 a2=2a3f88cd a3=22 items=0 ppid=3275 pid=9687 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,07-17 13:38:17.739  3246  3246 E audit   : type=1327 audit(1500291497.721:231): proctitle="com.thaliproject.thalitest"
07-17 13:38:17.739  3246  3246 E audit   : type=1320 audit(1500291497.721:231): 
,07-17 13:38:17.741  3300  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 13:38:17.757  9690  9690 E Zygote  : v2
07-17 13:38:17.757  9690  9690 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:17.757  9690  9690 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:17.757  9690  9690 E Zygote  : accessInfo : 0
,07-17 13:38:17.761  9690  9690 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:17.761  9690  9690 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.securitylogagent 
,07-17 13:38:17.766  3704  3788 I ActivityManager: Start proc 9690:com.samsung.android.securitylogagent/1000 for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,07-17 13:38:17.773  9623  9687 W jxcore-log: Platform android
07-17 13:38:17.773  9623  9687 W jxcore-log: 
,07-17 13:38:17.773  9623  9687 W jxcore-log: Process ARCH arm
07-17 13:38:17.773  9623  9687 W jxcore-log: 
07-17 13:38:17.773  3704  3805 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-17 13:38:17.785  9690  9690 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:17.785  9690  9690 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:17.787  3704  4184 I ActivityManager: DSS on for com.samsung.android.securitylogagent and scale is 1.0
,07-17 13:38:17.802  9690  9690 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,07-17 13:38:17.811  9690  9690 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:17.814  9690  9690 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-17 13:38:17.819  9690  9690 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-17 13:38:17.826  3704  6348 I ActivityManager: KPU : put [com.android.settings] : 28104 K
,07-17 13:38:17.826  3704  6348 I ActivityManager: Killing 8942:com.android.settings/1000 (adj 906): DHA:empty #33
,07-17 13:38:17.846  3704  3911 D ActivityManager: cleanUpApplicationRecord -- 8942
,07-17 13:38:17.847  4670  4687 D ForegroundUtils: could not check pending caller
,07-17 13:38:17.904  9623  9687 I jxcore-log: JXcore Cordova bridge is ready!
07-17 13:38:17.904  9623  9687 I jxcore-log: 
07-17 13:38:17.904  9623  9687 W jxcore-log: JXcore engine is started
,07-17 13:38:17.911  9623  9684 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-17 13:38:17.915  9623  9623 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
07-17 13:38:17.916  9623  9623 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-17 13:38:19.683  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:19.683  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:20.843  3704  5557 D SSRM:f  : SIOP:: AP = 310, PST = 267 (W:6), CP = 219, CUR = 13, LCD = 57
,07-17 13:38:21.209  4528  4528 D io_stats: !@   8,0 r 25806 2281632 w 4870 205152 d 610 74240 f 2006 2006 iot 11260 10659 th 461876 0 0 pt 0 inp 0 0 171.952
,07-17 13:38:22.129  3704  5557 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,07-17 13:38:22.707  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:22.707  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:24.869  9623  9687 I jxcore-log: 2017-07-17 11:38:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
07-17 13:38:24.869  9623  9687 I jxcore-log: 
,07-17 13:38:24.870  9623  9687 I jxcore-log: 2017-07-17 11:38:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
07-17 13:38:24.870  9623  9687 I jxcore-log: 
07-17 13:38:24.871  9623  9687 I jxcore-log: 2017-07-17 11:38:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
07-17 13:38:24.871  9623  9687 I jxcore-log: 
,07-17 13:38:24.880  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:24.885  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-17 13:38:24.888  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:24.892  9623  9687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-17 13:38:24.893  9623  9687 I jxcore-log: 2017-07-17 11:38:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
07-17 13:38:24.893  9623  9687 I jxcore-log: 
07-17 13:38:24.894  9623  9687 I jxcore-log: 2017-07-17 11:38:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
07-17 13:38:24.894  9623  9687 I jxcore-log: 
,07-17 13:38:24.895  9623  9687 I jxcore-log: 2017-07-17 11:38:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
07-17 13:38:24.895  9623  9687 I jxcore-log: 
,07-17 13:38:25.158  9623  9687 D ExecuteNativeTests: Running unit tests
07-17 13:38:25.158  9623  9687 D BluetoothAdapter: enable()
,07-17 13:38:25.164  4057  4502 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-17 13:38:25.165  4057  4502 D AdapterProvider: query
,07-17 13:38:25.181  4057  4502 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@89ae2aa
,07-17 13:38:25.184  4057  4502 D BluetoothAdapterService: updateEvent - already set, update
,07-17 13:38:25.185  4057  4502 W BluetoothAdapterService: updateEvent - alreadySet is true
07-17 13:38:25.185  4057  4502 D AdapterProvider: update
,07-17 13:38:25.195  4057  4502 E BluetoothAdapterService: updateEvent - update success 1
07-17 13:38:25.198  9623  9687 D BluetoothAdapter: enable(): BT is already enabled..!
,07-17 13:38:25.206  3704  4183 D WifiService: setWifiEnabled: true pid=9623, uid=10033
07-17 13:38:25.207  3704  4183 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-17 13:38:25.207  3704  4183 D WifiControlHistoryProvider: query
,07-17 13:38:25.226  3704  4183 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-17 13:38:25.227  3704  4183 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:25.228  3704  4183 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:25.233  3704  4183 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-17 13:38:25.234  3704  4183 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-17 13:38:25.414  3704  3911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:38:25.416  3704  3911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:38:25.416  3704  3911 D BatteryService: online:4, current avg:-73, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:217
07-17 13:38:25.417  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:38:25.426  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,07-17 13:38:25.426  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
07-17 13:38:25.429  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:38:25.435  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 13:38:25.436  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:38:25.448  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
07-17 13:38:25.452  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:38:25.452  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:38:25.454  4057  4057 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-17 13:38:25.455  4057  4490 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-17 13:38:25.455  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:38:25.729  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:25.729  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:26.112  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-17 13:38:26.139  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-17 13:38:26.139  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-17 13:38:26.213  4528  4528 D io_stats: !@   8,0 r 25813 2281696 w 4880 205392 d 610 74240 f 2011 2011 iot 11270 10668 th 464668 0 0 pt 0 inp 0 0 176.956
,07-17 13:38:28.761  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:28.761  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:30.881  3704  5557 D SSRM:f  : SIOP:: AP = 300, PST = 275 (W:6), CP = 230, CUR = 31, LCD = 57
,07-17 13:38:30.995  3704  3714 I art     : Background sticky concurrent mark sweep GC freed 195233(10MB) AllocSpace objects, 92(1840KB) LOS objects, 24% free, 42MB/55MB, paused 3.782ms total 144.124ms
,07-17 13:38:31.219  4528  4528 D io_stats: !@   8,0 r 25813 2281696 w 4890 205456 d 610 74240 f 2011 2011 iot 11270 10669 th 465036 0 0 pt 0 inp 0 0 181.961
,07-17 13:38:31.793  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:31.794  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:32.777  3300  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 13:38:34.826  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:34.826  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:35.240  9623  9687 I com.test.thalitest.ThaliTestRunner: Running UT
,07-17 13:38:35.314  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-17 13:38:35.314  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5e1091 added. We now have 2 listener(s)
07-17 13:38:35.314  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5e1091 added. We now have 3 listener(s)
07-17 13:38:35.314  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-17 13:38:35.315  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
07-17 13:38:35.315  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-17 13:38:35.315  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
07-17 13:38:35.315  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-17 13:38:35.315  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f6bf6 added. We now have 4 listener(s)
07-17 13:38:35.315  9623  9687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-17 13:38:35.317  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-17 13:38:35.328  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.337  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
07-17 13:38:35.337  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-17 13:38:35.337  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-17 13:38:35.337  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-17 13:38:35.338  9623  9687 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
,07-17 13:38:35.339  9623  9687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-17 13:38:35.339  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-17 13:38:35.339  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-17 13:38:35.339  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-17 13:38:35.340  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
07-17 13:38:35.341  9623  9687 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-17 13:38:35.343  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,07-17 13:38:35.347  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
07-17 13:38:35.348  9623  9687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,07-17 13:38:35.353  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-17 13:38:35.372  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:35.376  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-17 13:38:35.376  9623  9687 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-17 13:38:35.376  9623  9687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
,07-17 13:38:35.377  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
07-17 13:38:35.377  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-17 13:38:35.381  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
,07-17 13:38:35.381  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:35.382  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.382  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-17 13:38:35.383  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:35.386  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:35.386  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:35.387  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.387  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-17 13:38:35.387  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-17 13:38:35.387  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,07-17 13:38:35.388  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-17 13:38:35.389  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:35.390  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-17 13:38:35.392  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,07-17 13:38:35.392  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,07-17 13:38:35.392  9623  9707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-17 13:38:35.392  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-17 13:38:35.393  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-17 13:38:35.393  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-17 13:38:35.393  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-17 13:38:35.393  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-17 13:38:35.395  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:35.396  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-17 13:38:35.400  9623  9707 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:38:35.400  9623  9707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-17 13:38:35.403  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,07-17 13:38:35.403  9623  9687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-17 13:38:35.403  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-17 13:38:35.405  9623  9707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,07-17 13:38:35.409  9623  9707 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@64224cd, port: 6, type: 1, local socket address: null, socket type: 0
,07-17 13:38:35.413  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.414  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.415  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.418  9623  9687 D BluetoothAdapter: isSecureModeEnabled
,07-17 13:38:35.418  4057  4077 D BtConfig.SecureMode: isSecureModeOn:false
,07-17 13:38:35.420  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.420  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-17 13:38:35.422  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:35.423  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:35.424  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-17 13:38:35.425  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-17 13:38:35.425  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
07-17 13:38:35.427  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.430  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.431  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.431  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-17 13:38:35.431  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-17 13:38:35.431  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9823b41d-e4b3-4cc0-9bad-a60fa5a52179", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-17 13:38:35.432  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
07-17 13:38:35.433  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:38:35.434  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-17 13:38:35.434  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.435  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.435  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-17 13:38:35.435  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-17 13:38:35.436  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.436  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.437  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.439  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.440  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.440  9623  9687 D BluetoothAdapter: isSecureModeEnabled
07-17 13:38:35.441  4057  4375 D BtConfig.SecureMode: isSecureModeOn:false
07-17 13:38:35.441  9623  9687 D BluetoothLeAdvertiser: start advertising
,07-17 13:38:35.442  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:35.451  4057  4375 D BtGatt.GattService: registerClient() - UUID=7c7ab53a-4506-4f8d-882f-4f92975ac016
,07-17 13:38:35.457  3704  4753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:38:35.458  3704  4753 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:38:35.458  3704  4753 D BatteryService: online:4, current avg:79, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:178
07-17 13:38:35.458  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:38:35.462  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:38:35.462  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:38:35.463  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:38:35.466  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 13:38:35.466  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:38:35.472  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-17 13:38:35.476  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:38:35.476  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:38:35.478  4057  4057 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-17 13:38:35.478  4057  4490 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:38:35.489  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:38:35.555  4057  4181 D BtGatt.GattService: onClientRegistered() - UUID=7c7ab53a-4506-4f8d-882f-4f92975ac016, clientIf=5, status=0
,07-17 13:38:35.556  9623  9634 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-17 13:38:35.558  4057  4502 E BtGatt.ContextMap: Context not found for ID 5
,07-17 13:38:35.559  4057  4415 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-17 13:38:35.559  4057  4391 D BtGatt.AdvertiseManager: message : 0
,07-17 13:38:35.561  4057  4391 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-17 13:38:35.561  4057  4391 D BtGatt.AdvertiseManager: size of list is =0
,07-17 13:38:35.567  4057  4391 D BtGatt.AdvertiseManager: starting advertising
,07-17 13:38:35.570  4057  4391 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-17 13:38:35.572  4057  4474 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-17 13:38:35.584  4057  4181 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-17 13:38:35.585  4057  4391 D BtGatt.AdvertiseManager: starting multi advertising
,07-17 13:38:35.591  4057  4181 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-17 13:38:35.591  4057  4391 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-17 13:38:35.592  4057  4391 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,07-17 13:38:35.592  4057  4391 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-17 13:38:35.592  4057  4391 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-17 13:38:35.593  9623  9635 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-17 13:38:35.594  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.595  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.595  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-17 13:38:35.596  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.597  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.598  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.599  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.599  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.600  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-17 13:38:35.602  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-17 13:38:35.603  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.605  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.606  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:35.606  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:35.607  9623  9687 I io.jxcore.node.ConnectionHelper: start: OK
07-17 13:38:35.607  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-17 13:38:35.609  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.609  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-17 13:38:35.609  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-17 13:38:35.610  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.611  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.611  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-17 13:38:35.612  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:38:35.612  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-17 13:38:35.612  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-17 13:38:35.613  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.613  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.614  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.615  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.615  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.620  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-17 13:38:35.620  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-17 13:38:35.621  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-17 13:38:35.621  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-17 13:38:35.622  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-17 13:38:36.110  9623  9710 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-17 13:38:36.113  9623  9687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-17 13:38:36.113  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
07-17 13:38:36.113  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-17 13:38:36.114  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
07-17 13:38:36.114  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
,07-17 13:38:36.114  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,07-17 13:38:36.115  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
07-17 13:38:36.115  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-17 13:38:36.115  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
07-17 13:38:36.115  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-17 13:38:36.115  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-17 13:38:36.116  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-17 13:38:36.116  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-17 13:38:36.116  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-17 13:38:36.117  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-17 13:38:36.117  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
,07-17 13:38:36.117  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-17 13:38:36.118  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-17 13:38:36.118  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-17 13:38:36.118  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-17 13:38:36.118  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-17 13:38:36.119  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-17 13:38:36.119  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-17 13:38:36.119  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
,07-17 13:38:36.120  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-17 13:38:36.120  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
,07-17 13:38:36.120  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-17 13:38:36.121  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-17 13:38:36.121  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-17 13:38:36.121  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-17 13:38:36.121  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-17 13:38:36.122  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-17 13:38:36.122  9623  9687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-17 13:38:36.123  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,07-17 13:38:36.123  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-17 13:38:36.123  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-17 13:38:36.123  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-17 13:38:36.123  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-17 13:38:36.124  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-17 13:38:36.124  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-17 13:38:36.125  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-17 13:38:36.125  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-17 13:38:36.125  9623  9707 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-17 13:38:36.125  9623  9707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-17 13:38:36.125  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-17 13:38:36.126  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-17 13:38:36.126  9623  9707 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-17 13:38:36.127  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.127  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-17 13:38:36.127  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-17 13:38:36.130  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.131  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.135  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.143  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.147  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.150  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.151  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-17 13:38:36.155  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.158  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.158  9623  9687 D BluetoothLeScanner: could not find callback wrapper
07-17 13:38:36.159  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-17 13:38:36.159  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.160  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.161  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.161  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-17 13:38:36.161  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.163  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.166  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:36.166  9623  9687 D BluetoothLeAdvertiser: stop advertising
,07-17 13:38:36.167  4057  4077 E BtGatt.ContextMap: Context not found for ID 5
07-17 13:38:36.168  4057  4391 D BtGatt.AdvertiseManager: message : 1
,07-17 13:38:36.170  4057  4391 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-17 13:38:36.170  4057  4415 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-17 13:38:36.170  4057  4391 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-17 13:38:36.173  4057  4391 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-17 13:38:36.180  4057  4181 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-17 13:38:36.180  4057  4181 D BtGatt.GattService: Client app is not null!
07-17 13:38:36.181  9623  9634 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-17 13:38:36.184  4057  4069 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-17 13:38:36.186  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-17 13:38:36.186  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.187  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-17 13:38:36.187  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.188  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.189  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.189  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-17 13:38:36.189  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-17 13:38:36.190  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-17 13:38:36.191  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.193  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.194  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:38:36.194  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.195  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.195  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-17 13:38:36.195  9623  9623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-17 13:38:36.196  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-17 13:38:36.196  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-17 13:38:36.196  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,07-17 13:38:36.197  9623  9711 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-17 13:38:36.197  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:38:36.197  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:38:36.197  9623  9687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-17 13:38:36.197  9623  9687 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-17 13:38:36.197  9623  9687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,07-17 13:38:36.197  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
07-17 13:38:36.197  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,07-17 13:38:36.198  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-17 13:38:36.198  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:38:36.198  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-17 13:38:36.198  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-17 13:38:36.199  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:38:36.199  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-17 13:38:36.200  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-17 13:38:36.200  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:38:36.203  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:36.204  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,07-17 13:38:36.204  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.205  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-17 13:38:36.209  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:36.209  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,07-17 13:38:36.209  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.210  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-17 13:38:36.210  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-17 13:38:36.210  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-17 13:38:36.210  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-17 13:38:36.211  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-17 13:38:36.212  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-17 13:38:36.212  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-17 13:38:36.212  9623  9712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-17 13:38:36.213  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-17 13:38:36.213  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-17 13:38:36.213  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-17 13:38:36.213  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-17 13:38:36.213  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-17 13:38:36.213  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-17 13:38:36.215  9623  9712 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:38:36.215  9623  9712 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-17 13:38:36.219  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-17 13:38:36.219  9623  9687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-17 13:38:36.219  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-17 13:38:36.221  9623  9712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-17 13:38:36.221  9623  9712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@9b403ce, port: 6, type: 1, local socket address: null, socket type: 0
07-17 13:38:36.222  4528  4528 D io_stats: !@   8,0 r 25819 2282036 w 4905 205836 d 616 74332 f 2020 2020 iot 11320 10684 th 467108 0 0 pt 0 inp 0 0 186.965
,07-17 13:38:36.223  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.224  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.225  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.229  9623  9687 D BluetoothAdapter: isSecureModeEnabled
,07-17 13:38:36.229  4057  4502 D BtConfig.SecureMode: isSecureModeOn:false
,07-17 13:38:36.230  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.230  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-17 13:38:36.232  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.233  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.233  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-17 13:38:36.233  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-17 13:38:36.233  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,07-17 13:38:36.236  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.240  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.240  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.240  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-17 13:38:36.240  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,07-17 13:38:36.240  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9823b41d-e4b3-4cc0-9bad-a60fa5a52179", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-17 13:38:36.241  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
07-17 13:38:36.241  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-17 13:38:36.241  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:38:36.242  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.243  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.243  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-17 13:38:36.243  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-17 13:38:36.244  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.244  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.245  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.246  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.248  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:36.248  9623  9687 D BluetoothAdapter: isSecureModeEnabled
,07-17 13:38:36.248  4057  4069 D BtConfig.SecureMode: isSecureModeOn:false
07-17 13:38:36.248  9623  9687 D BluetoothLeAdvertiser: start advertising
,07-17 13:38:36.250  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.254  4057  4069 D BtGatt.GattService: registerClient() - UUID=27e84f8d-d288-4e53-af6c-4779f890aad6
,07-17 13:38:36.358  4057  4181 D BtGatt.GattService: onClientRegistered() - UUID=27e84f8d-d288-4e53-af6c-4779f890aad6, clientIf=5, status=0
,07-17 13:38:36.359  9623  9635 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-17 13:38:36.363  4057  4077 E BtGatt.ContextMap: Context not found for ID 5
,07-17 13:38:36.364  4057  4415 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-17 13:38:36.366  4057  4391 D BtGatt.AdvertiseManager: message : 0
,07-17 13:38:36.368  4057  4391 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-17 13:38:36.368  4057  4391 D BtGatt.AdvertiseManager: size of list is =0
,07-17 13:38:36.377  4057  4391 D BtGatt.AdvertiseManager: starting advertising
,07-17 13:38:36.382  4057  4391 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-17 13:38:36.385  4057  4474 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-17 13:38:36.407  4057  4181 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-17 13:38:36.411  4057  4391 D BtGatt.AdvertiseManager: starting multi advertising
,07-17 13:38:36.423  4057  4181 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-17 13:38:36.423  4057  4391 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-17 13:38:36.423  4057  4391 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-17 13:38:36.424  4057  4391 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-17 13:38:36.424  4057  4391 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-17 13:38:36.425  9623  9634 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-17 13:38:36.427  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.428  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.428  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-17 13:38:36.429  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.430  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.431  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.433  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.434  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.434  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-17 13:38:36.439  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-17 13:38:36.440  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.440  9623  9687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-17 13:38:36.446  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.447  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.448  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.449  9623  9687 I io.jxcore.node.ConnectionHelper: start: OK
07-17 13:38:36.449  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-17 13:38:36.451  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.452  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-17 13:38:36.453  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-17 13:38:36.454  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.455  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.457  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-17 13:38:36.458  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:38:36.458  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-17 13:38:36.458  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-17 13:38:36.459  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.460  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.462  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.463  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.464  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.472  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-17 13:38:36.472  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-17 13:38:36.473  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,07-17 13:38:36.474  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-17 13:38:36.475  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-17 13:38:36.953  9623  9714 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,07-17 13:38:36.958  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,07-17 13:38:36.959  9623  9687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-17 13:38:36.959  9623  9687 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-17 13:38:36.959  9623  9687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-17 13:38:36.960  9623  9687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
07-17 13:38:36.960  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,07-17 13:38:36.961  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-17 13:38:36.971  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:36.971  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-17 13:38:36.972  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.972  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-17 13:38:36.976  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-17 13:38:36.982  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:36.982  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:36.983  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 36489
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-17 13:38:36.983  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:36.983  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
,07-17 13:38:36.984  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.985  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.986  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:36.989  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:36.991  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:36.991  9623  9687 D BluetoothLeAdvertiser: stop advertising
,07-17 13:38:36.993  4057  4375 E BtGatt.ContextMap: Context not found for ID 5
,07-17 13:38:36.993  4057  4415 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-17 13:38:36.994  4057  4391 D BtGatt.AdvertiseManager: message : 1
,07-17 13:38:36.995  4057  4391 D BtGatt.AdvertiseManager: stop advertise for client =  5
,07-17 13:38:36.995  4057  4391 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-17 13:38:36.997  4057  4391 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-17 13:38:37.004  4057  4181 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-17 13:38:37.004  4057  4181 D BtGatt.GattService: Client app is not null!
,07-17 13:38:37.004  9623  9635 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-17 13:38:37.005  4057  4502 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-17 13:38:37.007  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-17 13:38:37.008  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.008  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-17 13:38:37.008  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.009  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.010  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.010  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-17 13:38:37.010  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.011  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.011  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.011  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-17 13:38:37.011  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-17 13:38:37.012  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9823b41d-e4b3-4cc0-9bad-a60fa5a52179", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-17 13:38:37.012  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
07-17 13:38:37.012  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:38:37.013  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-17 13:38:37.013  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.014  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.014  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-17 13:38:37.014  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,07-17 13:38:37.015  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.015  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.016  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.018  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:37.020  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.020  9623  9687 D BluetoothAdapter: isSecureModeEnabled
07-17 13:38:37.020  4057  4375 D BtConfig.SecureMode: isSecureModeOn:false
,07-17 13:38:37.021  9623  9687 D BluetoothLeAdvertiser: start advertising
,07-17 13:38:37.022  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:37.028  4057  4375 D BtGatt.GattService: registerClient() - UUID=5d94e8eb-3e26-469a-9f04-36f5128add5e
,07-17 13:38:37.131  4057  4181 D BtGatt.GattService: onClientRegistered() - UUID=5d94e8eb-3e26-469a-9f04-36f5128add5e, clientIf=5, status=0
,07-17 13:38:37.132  9623  9634 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-17 13:38:37.136  4057  4502 E BtGatt.ContextMap: Context not found for ID 5
,07-17 13:38:37.137  4057  4415 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-17 13:38:37.138  4057  4391 D BtGatt.AdvertiseManager: message : 0
,07-17 13:38:37.140  4057  4391 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-17 13:38:37.140  4057  4391 D BtGatt.AdvertiseManager: size of list is =0
,07-17 13:38:37.149  4057  4391 D BtGatt.AdvertiseManager: starting advertising
,07-17 13:38:37.154  4057  4391 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-17 13:38:37.158  4057  4474 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-17 13:38:37.178  4057  4181 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
07-17 13:38:37.182  4057  4391 D BtGatt.AdvertiseManager: starting multi advertising
07-17 13:38:37.193  4057  4181 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-17 13:38:37.194  4057  4391 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-17 13:38:37.194  4057  4391 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-17 13:38:37.194  4057  4391 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-17 13:38:37.194  4057  4391 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-17 13:38:37.195  9623  9635 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-17 13:38:37.197  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.198  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.198  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-17 13:38:37.199  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.200  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.201  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.202  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.203  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.204  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.204  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-17 13:38:37.205  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.205  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-17 13:38:37.206  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-17 13:38:37.207  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-17 13:38:37.207  9623  9687 I io.jxcore.node.ConnectionHelper: start: OK
07-17 13:38:37.208  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-17 13:38:37.209  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,07-17 13:38:37.209  9623  9716 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-17 13:38:37.209  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-17 13:38:37.210  9623  9687 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-17 13:38:37.210  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.210  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,07-17 13:38:37.211  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-17 13:38:37.211  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-17 13:38:37.211  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-17 13:38:37.211  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-17 13:38:37.211  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.212  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-17 13:38:37.212  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-17 13:38:37.212  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-17 13:38:37.212  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-17 13:38:37.212  9623  9712 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-17 13:38:37.212  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-17 13:38:37.212  9623  9712 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-17 13:38:37.212  9623  9712 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-17 13:38:37.213  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.213  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-17 13:38:37.213  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-17 13:38:37.213  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-17 13:38:37.214  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.214  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-17 13:38:37.215  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,07-17 13:38:37.215  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.217  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-17 13:38:37.217  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-17 13:38:37.218  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.219  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.220  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.220  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.222  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:37.224  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.224  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-17 13:38:37.225  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:37.227  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.227  9623  9687 D BluetoothLeScanner: could not find callback wrapper
07-17 13:38:37.227  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-17 13:38:37.228  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.229  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.229  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.229  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,07-17 13:38:37.230  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.232  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:37.233  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.233  9623  9687 D BluetoothLeAdvertiser: stop advertising
,07-17 13:38:37.235  4057  4375 E BtGatt.ContextMap: Context not found for ID 5
07-17 13:38:37.235  4057  4391 D BtGatt.AdvertiseManager: message : 1
07-17 13:38:37.235  4057  4415 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,07-17 13:38:37.236  4057  4391 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-17 13:38:37.237  4057  4391 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-17 13:38:37.238  4057  4391 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-17 13:38:37.245  4057  4181 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-17 13:38:37.245  4057  4181 D BtGatt.GattService: Client app is not null!
,07-17 13:38:37.245  9623  9634 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-17 13:38:37.247  4057  4502 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-17 13:38:37.249  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-17 13:38:37.249  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.250  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-17 13:38:37.250  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.251  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.252  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.252  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-17 13:38:37.252  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-17 13:38:37.253  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-17 13:38:37.254  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.257  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.257  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:38:37.258  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.259  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.259  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-17 13:38:37.259  9623  9623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-17 13:38:37.260  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,07-17 13:38:37.260  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-17 13:38:37.260  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:38:37.260  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:38:37.261  9623  9717 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
07-17 13:38:37.261  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-17 13:38:37.262  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.262  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-17 13:38:37.262  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-17 13:38:37.262  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.263  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,07-17 13:38:37.263  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
07-17 13:38:37.264  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.264  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:38:37.265  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-17 13:38:37.265  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2f6f0b added. We now have 3 listener(s)
07-17 13:38:37.265  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2f6f0b added. We now have 5 listener(s)
07-17 13:38:37.265  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-17 13:38:37.269  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:37.269  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-17 13:38:37.270  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,07-17 13:38:37.270  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-17 13:38:37.271  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d1e8 added. We now have 6 listener(s)
,07-17 13:38:37.271  9623  9687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-17 13:38:37.272  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-17 13:38:37.278  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-17 13:38:37.288  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:37.291  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-17 13:38:37.292  9623  9687 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-17 13:38:37.297  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:37.303  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:37.312  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:37.315  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-17 13:38:37.316  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-17 13:38:37.316  9623  9687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-17 13:38:37.316  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-17 13:38:37.316  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-17 13:38:37.316  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-17 13:38:37.316  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2f6f0b removed from the list
07-17 13:38:37.317  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2f6f0b removed from the list
07-17 13:38:37.317  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-17 13:38:37.317  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89d1e8 removed from the list
,07-17 13:38:37.322  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:37.327  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:37.327  9623  9687 D io.jxcore.node.ConnectivityMonitor: stop
07-17 13:38:37.328  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-17 13:38:37.331  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
07-17 13:38:37.331  9623  9687 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,07-17 13:38:37.334  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,07-17 13:38:37.335  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,07-17 13:38:37.339  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
07-17 13:38:37.340  9623  9687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-17 13:38:37.342  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
07-17 13:38:37.342  9623  9687 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,07-17 13:38:37.345  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
07-17 13:38:37.345  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-17 13:38:37.347  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-17 13:38:37.347  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-17 13:38:37.347  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-17 13:38:37.348  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-17 13:38:37.348  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-17 13:38:37.348  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-17 13:38:37.348  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-17 13:38:37.349  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-17 13:38:37.352  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,07-17 13:38:37.353  9623  9687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-17 13:38:37.353  9623  9687 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-17 13:38:37.353  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,07-17 13:38:37.361  9623  9687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-17 13:38:37.361  9623  9687 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-17 13:38:37.362  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
07-17 13:38:37.362  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,07-17 13:38:37.363  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
07-17 13:38:37.363  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
,07-17 13:38:37.363  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
,07-17 13:38:37.363  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
07-17 13:38:37.364  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
,07-17 13:38:37.364  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
07-17 13:38:37.364  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
07-17 13:38:37.364  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
07-17 13:38:37.364  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
07-17 13:38:37.364  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
07-17 13:38:37.364  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
07-17 13:38:37.364  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
07-17 13:38:37.365  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
07-17 13:38:37.366  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
07-17 13:38:37.366  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
07-17 13:38:37.366  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
07-17 13:38:37.366  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
07-17 13:38:37.366  9623  9687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-17 13:38:37.366  9623  9687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-17 13:38:37.367  9623  9687 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,07-17 13:38:37.367  9623  9687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-17 13:38:37.367  9623  9687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-17 13:38:37.368  9623  9687 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-17 13:38:37.368  9623  9687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-17 13:38:37.368  9623  9687 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-17 13:38:37.368  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
07-17 13:38:37.375  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-17 13:38:37.375  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
07-17 13:38:37.376  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-17 13:38:37.377  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-17 13:38:37.377  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-17 13:38:37.377  9623  9687 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-17 13:38:37.377  9623  9718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 191)
07-17 13:38:37.378  9623  9718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
07-17 13:38:37.378  9623  9718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
07-17 13:38:37.378  9623  9718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
07-17 13:38:37.378  9623  9687 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-17 13:38:37.378  9623  9687 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-17 13:38:37.380  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
07-17 13:38:37.381  9623  9687 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-17 13:38:37.383  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
07-17 13:38:37.383  9623  9687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-17 13:38:37.386  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
07-17 13:38:37.386  9623  9687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-17 13:38:37.387  9623  9687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-17 13:38:37.387  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-17 13:38:37.387  9623  9687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-17 13:38:37.387  9623  9718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
07-17 13:38:37.387  9623  9687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-17 13:38:37.387  9623  9718 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
07-17 13:38:37.387  9623  9687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-17 13:38:37.388  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-17 13:38:37.388  9623  9687 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-17 13:38:37.388  9623  9687 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-17 13:38:37.388  9623  9687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-17 13:38:37.388  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-17 13:38:37.388  9623  9687 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-17 13:38:37.390  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
07-17 13:38:37.391  9623  9687 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
07-17 13:38:37.391  9623  9687 V io.jxcore.node.ConnectivityMonitor: start: Already started
07-17 13:38:37.391  9623  9687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
07-17 13:38:37.391  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
07-17 13:38:37.392  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-17 13:38:37.397  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:37.397  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:37.397  9623  9718 D BluetoothSocket: connect(): myUserId = 0
07-17 13:38:37.397  9623  9718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:38:37.397  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.397  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-17 13:38:37.399  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:37.399  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:37.400  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.400  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-17 13:38:37.400  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-17 13:38:37.400  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-17 13:38:37.400  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-17 13:38:37.401  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-17 13:38:37.402  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-17 13:38:37.402  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-17 13:38:37.402  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-17 13:38:37.402  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-17 13:38:37.402  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-17 13:38:37.402  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-17 13:38:37.402  9623  9719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-17 13:38:37.403  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-17 13:38:37.403  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-17 13:38:37.405  9623  9719 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:38:37.406  9623  9719 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:38:37.408  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-17 13:38:37.409  9623  9687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-17 13:38:37.409  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-17 13:38:37.410  9623  9719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-17 13:38:37.410  9623  9719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@2e3f0e7, port: 6, type: 1, local socket address: null, socket type: 0
07-17 13:38:37.412  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.413  3704  4183 D SecContentProvider: insert(), uri = 2
07-17 13:38:37.413  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.413  3704  4183 D SecContentProvider: called from android.uid.bluetooth:1002
07-17 13:38:37.415  4057  4474 W bt_btif : bta_dm_bl_change_cback : reason=0
07-17 13:38:37.417  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.417  4057  4181 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
07-17 13:38:37.421  9623  9687 D BluetoothAdapter: isSecureModeEnabled
07-17 13:38:37.421  4057  4375 D BtConfig.SecureMode: isSecureModeOn:false
07-17 13:38:37.423  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.423  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-17 13:38:37.424  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.425  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.425  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-17 13:38:37.425  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-17 13:38:37.425  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
07-17 13:38:37.428  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.431  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.431  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.431  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-17 13:38:37.431  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-17 13:38:37.432  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9823b41d-e4b3-4cc0-9bad-a60fa5a52179", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-17 13:38:37.432  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
07-17 13:38:37.432  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:38:37.432  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:38:37.432  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.433  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.433  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-17 13:38:37.433  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:38:37.433  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.433  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.434  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.435  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.435  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:37.436  9623  9687 D BluetoothAdapter: isSecureModeEnabled
07-17 13:38:37.436  4057  4502 D BtConfig.SecureMode: isSecureModeOn:false
07-17 13:38:37.437  9623  9687 D BluetoothLeAdvertiser: start advertising
07-17 13:38:37.438  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:37.442  4057  4502 D BtGatt.GattService: registerClient() - UUID=68bd79a8-95d9-4fbe-97a7-acb1618d74b4
,07-17 13:38:37.545  4057  4181 D BtGatt.GattService: onClientRegistered() - UUID=68bd79a8-95d9-4fbe-97a7-acb1618d74b4, clientIf=5, status=0
,07-17 13:38:37.546  9623  9634 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-17 13:38:37.550  4057  4069 E BtGatt.ContextMap: Context not found for ID 5
07-17 13:38:37.551  4057  4391 D BtGatt.AdvertiseManager: message : 0
07-17 13:38:37.551  4057  4415 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-17 13:38:37.553  4057  4391 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-17 13:38:37.553  4057  4391 D BtGatt.AdvertiseManager: size of list is =0
,07-17 13:38:37.563  4057  4391 D BtGatt.AdvertiseManager: starting advertising
,07-17 13:38:37.567  4057  4391 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-17 13:38:37.571  4057  4474 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-17 13:38:37.592  4057  4181 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-17 13:38:37.596  4057  4391 D BtGatt.AdvertiseManager: starting multi advertising
,07-17 13:38:37.608  4057  4181 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
07-17 13:38:37.609  4057  4391 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,07-17 13:38:37.609  4057  4391 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-17 13:38:37.609  4057  4391 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-17 13:38:37.609  4057  4391 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
07-17 13:38:37.610  9623  9635 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-17 13:38:37.612  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.613  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.614  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-17 13:38:37.615  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.616  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.617  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.618  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.619  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.619  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-17 13:38:37.624  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-17 13:38:37.625  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.625  9623  9687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,07-17 13:38:37.631  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.632  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:37.633  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:37.634  9623  9687 I io.jxcore.node.ConnectionHelper: start: OK
07-17 13:38:37.634  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-17 13:38:37.636  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,07-17 13:38:37.637  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-17 13:38:37.638  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-17 13:38:37.639  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.640  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.641  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-17 13:38:37.641  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.642  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,07-17 13:38:37.642  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-17 13:38:37.642  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.643  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-17 13:38:37.644  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-17 13:38:37.644  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.645  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-17 13:38:37.651  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.651  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-17 13:38:37.652  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-17 13:38:37.653  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,07-17 13:38:37.653  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-17 13:38:37.778  3300  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 13:38:37.838  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:37.838  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:38.136  9623  9710 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
07-17 13:38:38.137  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-17 13:38:38.137  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-17 13:38:38.137  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-17 13:38:38.137  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,07-17 13:38:38.138  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-17 13:38:38.138  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-17 13:38:38.139  9623  9719 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-17 13:38:38.139  9623  9719 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-17 13:38:38.139  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-17 13:38:38.139  9623  9719 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-17 13:38:38.139  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-17 13:38:38.139  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-17 13:38:38.139  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-17 13:38:38.139  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,07-17 13:38:38.140  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,07-17 13:38:38.141  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5e1091 removed from the list
07-17 13:38:38.142  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5e1091 removed from the list
07-17 13:38:38.142  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-17 13:38:38.142  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-17 13:38:38.142  9623  9722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 191
07-17 13:38:38.143  9623  9722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
07-17 13:38:38.143  9623  9722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 191)
07-17 13:38:38.143  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.143  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-17 13:38:38.143  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-17 13:38:38.144  4057  4498 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
07-17 13:38:38.145  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.145  9623  9722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 191)
07-17 13:38:38.146  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.147  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.148  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:38.150  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:38.151  9623  9718 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
07-17 13:38:38.151  9623  9718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
07-17 13:38:38.151  9623  9718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 191)
,07-17 13:38:38.152  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:38.152  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-17 13:38:38.154  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:38.156  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:38.156  9623  9687 D BluetoothLeScanner: could not find callback wrapper
07-17 13:38:38.156  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-17 13:38:38.156  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.157  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:38.157  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.158  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-17 13:38:38.158  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:38.160  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:38.161  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:38:38.162  9623  9687 D BluetoothLeAdvertiser: stop advertising
,07-17 13:38:38.163  4057  4375 E BtGatt.ContextMap: Context not found for ID 5
,07-17 13:38:38.163  4057  4415 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-17 13:38:38.164  4057  4391 D BtGatt.AdvertiseManager: message : 1
,07-17 13:38:38.165  4057  4391 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-17 13:38:38.165  4057  4391 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,07-17 13:38:38.166  4057  4391 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-17 13:38:38.172  4057  4181 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-17 13:38:38.172  4057  4181 D BtGatt.GattService: Client app is not null!
07-17 13:38:38.173  9623  9634 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-17 13:38:38.174  4057  4077 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-17 13:38:38.175  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-17 13:38:38.176  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.176  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,07-17 13:38:38.177  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:38.177  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.178  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.178  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-17 13:38:38.178  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-17 13:38:38.179  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-17 13:38:38.180  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:38.182  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.183  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:38:38.183  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:38.183  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:38.184  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f6bf6 removed from the list
07-17 13:38:38.184  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:38:38.184  9623  9687 D io.jxcore.node.ConnectivityMonitor: stop
07-17 13:38:38.184  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-17 13:38:38.184  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:38:38.184  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
07-17 13:38:38.185  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-17 13:38:38.185  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:38:38.185  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,07-17 13:38:38.185  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
07-17 13:38:38.186  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,07-17 13:38:38.187  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-17 13:38:38.187  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-17 13:38:38.187  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:38:38.688  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-17 13:38:38.867  3704  4019 D WifiWatchdogStateMachine:  [] [|207]
,07-17 13:38:39.902  3704  4019 D IcmpEchoPeer: res : -1, -1062731519 : 0 / 1008
,07-17 13:38:40.868  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:40.869  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:40.904  3704  5557 D SSRM:f  : SIOP:: AP = 280, PST = 278 (W:14), CP = 228, CUR = 113, LCD = 57
,07-17 13:38:41.226  4528  4528 D io_stats: !@   8,0 r 25819 2282036 w 4938 206380 d 626 74372 f 2029 2029 iot 11350 10702 th 466880 0 0 pt 0 inp 0 0 191.968
,07-17 13:38:43.187  9623  9711 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,07-17 13:38:43.191  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,07-17 13:38:43.194  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-17 13:38:43.195  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-17 13:38:43.198  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-17 13:38:43.200  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-17 13:38:43.200  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-17 13:38:43.200  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-17 13:38:43.201  9623  9723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-17 13:38:43.201  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-17 13:38:43.201  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-17 13:38:43.201  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-17 13:38:43.205  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
07-17 13:38:43.206  9623  9723 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:38:43.206  9623  9723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:38:43.207  9623  9687 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
07-17 13:38:43.208  9623  9687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-17 13:38:43.208  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-17 13:38:43.209  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-17 13:38:43.212  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,07-17 13:38:43.218  9623  9723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-17 13:38:43.219  9623  9723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@272db3d, port: 6, type: 1, local socket address: null, socket type: 0
,07-17 13:38:43.227  9623  9687 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,07-17 13:38:43.229  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-17 13:38:43.229  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-17 13:38:43.229  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-17 13:38:43.229  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-17 13:38:43.230  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-17 13:38:43.230  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-17 13:38:43.230  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-17 13:38:43.231  9623  9723 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-17 13:38:43.231  9623  9723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-17 13:38:43.231  9623  9723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-17 13:38:43.231  9623  9687 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5e1091 not in the list
07-17 13:38:43.231  9623  9687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5e1091 not in the list
07-17 13:38:43.231  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-17 13:38:43.231  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-17 13:38:43.231  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-17 13:38:43.231  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-17 13:38:43.232  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-17 13:38:43.232  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:43.232  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,07-17 13:38:43.232  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-17 13:38:43.233  9623  9687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-17 13:38:43.233  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-17 13:38:43.233  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:38:43.238  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:43.238  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:38:43.239  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:43.240  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:38:43.240  9623  9687 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f6bf6 not in the list
,07-17 13:38:43.240  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:38:43.241  9623  9687 D io.jxcore.node.ConnectivityMonitor: stop
07-17 13:38:43.241  9623  9687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-17 13:38:43.241  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:38:43.241  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-17 13:38:43.241  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:38:43.245  9623  9687 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,07-17 13:38:43.247  9623  9687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-17 13:38:43.247  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,07-17 13:38:43.247  9623  9687 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-17 13:38:43.248  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-17 13:38:43.248  9623  9687 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-17 13:38:43.248  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-17 13:38:43.251  9623  9687 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,07-17 13:38:43.254  9623  9687 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,07-17 13:38:43.257  9623  9687 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,07-17 13:38:43.258  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
07-17 13:38:43.259  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,07-17 13:38:43.261  9623  9687 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,07-17 13:38:43.262  9623  9687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-17 13:38:43.262  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-17 13:38:43.263  9623  9687 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-17 13:38:43.263  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-17 13:38:43.263  9623  9687 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-17 13:38:43.263  9623  9687 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-17 13:38:43.265  9623  9687 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,07-17 13:38:43.267  9623  9687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-17 13:38:43.267  9623  9687 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-17 13:38:43.269  9623  9687 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,07-17 13:38:43.270  9623  9687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-17 13:38:43.270  9623  9687 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-17 13:38:43.270  9623  9687 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-17 13:38:43.271  9623  9687 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-17 13:38:43.273  9623  9687 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,07-17 13:38:43.275  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-17 13:38:43.275  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e21f32 added. We now have 2 listener(s)
07-17 13:38:43.275  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e21f32 added. We now have 3 listener(s)
07-17 13:38:43.275  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-17 13:38:43.280  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-17 13:38:43.280  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-17 13:38:43.280  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-17 13:38:43.281  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-17 13:38:43.281  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@374b483 added. We now have 4 listener(s)
07-17 13:38:43.281  9623  9687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-17 13:38:43.282  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-17 13:38:43.285  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:38:43.286  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 13:38:43.287  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:38:43.287  3704  3704 D UsbMonitorService: Posting Message again
07-17 13:38:43.288  9623  9687 D BluetoothAdapter: enable()
,07-17 13:38:43.295  4057  4069 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-17 13:38:43.296  4057  4069 D AdapterProvider: query
07-17 13:38:43.309  4057  4069 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@7fd4211
07-17 13:38:43.311  4057  4069 D BluetoothAdapterService: updateEvent - already set, update
07-17 13:38:43.311  4057  4069 W BluetoothAdapterService: updateEvent - alreadySet is true
07-17 13:38:43.311  4057  4069 D AdapterProvider: update
,07-17 13:38:43.315  4057  4069 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:43.317  9623  9687 D BluetoothAdapter: enable(): BT is already enabled..!
,07-17 13:38:43.325  3704  4338 D WifiService: setWifiEnabled: true pid=9623, uid=10033
,07-17 13:38:43.326  3704  4338 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-17 13:38:43.326  3704  4338 D WifiControlHistoryProvider: query
,07-17 13:38:43.333  3704  4338 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-17 13:38:43.334  3704  4338 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:43.335  3704  4338 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:43.339  3704  4338 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-17 13:38:43.339  3704  4338 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-17 13:38:43.349  9623  9687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,07-17 13:38:43.352  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:43.356  9623  9687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,07-17 13:38:43.358  9623  9687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,07-17 13:38:43.359  9623  9687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,07-17 13:38:43.362  9623  9724 D BluetoothAdapter: disable()
,07-17 13:38:43.367  4057  4069 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : false
,07-17 13:38:43.367  4057  4069 D AdapterProvider: query
07-17 13:38:43.367  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:38:43.373  4057  4069 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@be559e4
,07-17 13:38:43.374  4057  4069 D BluetoothAdapterService: updateEvent - already set, update
,07-17 13:38:43.375  4057  4069 W BluetoothAdapterService: updateEvent - alreadySet is true
07-17 13:38:43.375  4057  4069 D AdapterProvider: update
,07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:43.377  9623  9687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-17 13:38:43.380  4057  4069 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:43.385  3704  3812 D SecContentProvider: insert(), uri = 2
,07-17 13:38:43.386  3704  3812 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:43.387  4057  4167 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,07-17 13:38:43.389  4057  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-17 13:38:43.389  4057  4167 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-17 13:38:43.392  4057  4057 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-17 13:38:43.392  3704  3812 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
07-17 13:38:43.393  4057  4167 D BluetoothAdapterService: Autoconnection is available 
07-17 13:38:43.393  4057  4167 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-17 13:38:43.393  4057  4167 D BluetoothAdapterService: terminating service from this receiver
,07-17 13:38:43.399  4057  4167 W bt_btif : btif_dm_cancel_discovery
07-17 13:38:43.401  3704  3920 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-17 13:38:43.402  3704  3920 D SecContentProvider: called from android.uid.bluetooth:1002
07-17 13:38:43.403  3704  4740 D SecContentProvider: insert(), uri = 2
,07-17 13:38:43.405  4070  4070 D BluetoothPbap: Proxy object disconnected
07-17 13:38:43.406  4070  4070 D PbapServerProfile: Bluetooth service disconnected
,07-17 13:38:43.408  3704  4740 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:43.410  4057  4167 I BluetoothAdapterState: Entering PendingCommandState
07-17 13:38:43.417  4057  4181 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-17 13:38:43.419  3704  3759 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{662c13d: PendingIntentRecord{11b0d32 com.google.android.gms broadcastIntent}}
07-17 13:38:43.421  4057  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,07-17 13:38:43.424  4070  4357 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:43.424  3704  6348 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4057 / op:PendingIntent{d360a83: PendingIntentRecord{b889400 com.android.bluetooth broadcastIntent}}
07-17 13:38:43.425  3704  3704 D BluetoothPhoneService: Bluetooth Adapter state : 13
07-17 13:38:43.425  4070  4357 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
07-17 13:38:43.426  9623  9623 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:43.426  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-17 13:38:43.427  9623  9623 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-17 13:38:43.428  9623  9623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-17 13:38:43.433  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-17 13:38:43.434  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:43.434  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-17 13:38:43.445  3704  3788 D MountService: getExternalStorageMountMode : 1
07-17 13:38:43.445  3704  3788 D MountService: getExternalStorageMountMode : 3
07-17 13:38:43.445  3704  3788 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.android.settings
07-17 13:38:43.445  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:43.468  9726  9726 E Zygote  : v2
07-17 13:38:43.468  9726  9726 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:43.468  9726  9726 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:43.469  9726  9726 E Zygote  : accessInfo : 0
07-17 13:38:43.469  3704  3788 I ActivityManager: Start proc 9726:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-17 13:38:43.470  4057  4167 E BluetoothServiceJni: disableBrEdrNative:
07-17 13:38:43.470  4057  4167 E bt_btif : disable_bredr
,07-17 13:38:43.471  4057  4499 W bt_osi_thread: run_thread: thread id 4499, thread name btif_sock exited
07-17 13:38:43.471  4057  4181 W bt_btif : btif_dm_generic_evt: event=33035
07-17 13:38:43.473  4057  4174 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-17 13:38:43.473  4057  4590 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-17 13:38:43.473  4057  4174 E bt_btif : BTA_DisableBluetoothOnly
07-17 13:38:43.473  4057  4590 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-17 13:38:43.474  4057  4474 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-17 13:38:43.475  4057  4595 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-17 13:38:43.475  4057  4591 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-17 13:38:43.475  4057  4591 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-17 13:38:43.475  3704  4752 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{e3f3439: PendingIntentRecord{fe8ca7e com.google.android.gms broadcastIntent}}
07-17 13:38:43.479  9726  9726 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-17 13:38:43.481  9726  9726 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.settings 
07-17 13:38:43.482  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
07-17 13:38:43.482  4057  4057 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-17 13:38:43.483  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.483  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.483  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
07-17 13:38:43.483  4057  4057 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-17 13:38:43.484  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.484  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.484  4057  4057 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:43.484  4057  4057 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-17 13:38:43.485  4057  4057 D BluetoothSdpJni: SDP Remove record success - handle: 1
07-17 13:38:43.485  4057  4497 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
07-17 13:38:43.485  4057  4497 D BluetoothSdpJni: SDP Remove record success - handle: 0
07-17 13:38:43.486  4057  4181 W bt_btif : btif_dm_generic_evt: event=33035
07-17 13:38:43.489  4057  4181 W bt_btif : btif_dm_generic_evt: event=33035
07-17 13:38:43.495  4057  4474 W bt_btm  : btm_sec_connected
07-17 13:38:43.495  4057  4474 W bt_btif : bta_dm_bl_change_cback : reason=2
07-17 13:38:43.495  4057  4474 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
07-17 13:38:43.495  4057  4474 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
07-17 13:38:43.495  4057  4474 W bt_btif : bta_dm_bl_change_cback : reason=2
07-17 13:38:43.498  4057  4181 W bt_btif : btif_dm_generic_evt: event=33035
07-17 13:38:43.500  4057  4181 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
07-17 13:38:43.501  4057  4181 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
,07-17 13:38:43.504  4057  4497 D BluetoothMapMasInstance: RemoveSDPrecord returns true
07-17 13:38:43.504  4057  4497 D ObexServerSockets: shutdown(block = true)
07-17 13:38:43.504  4057  4497 D ObexServerSockets: shutdown called from another thread - interrupt().
07-17 13:38:43.504  4057  4497 D ObexServerSockets: shutdown called from another thread - interrupt().
07-17 13:38:43.507  4057  4057 I BtOppRfcommListener: stopping Accept Thread
07-17 13:38:43.508  4057  4595 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-17 13:38:43.509  9726  9726 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-17 13:38:43.510  9726  9726 D ActivityThread: Added TimaKeyStore provider
07-17 13:38:43.512  4057  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.514  3704  3920 I ActivityManager: DSS on for com.android.settings and scale is 1.0
07-17 13:38:43.515  4057  4181 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 1
,07-17 13:38:43.521  4057  4057 V BluetoothOppManager: cleanUp...
,07-17 13:38:43.523  4057  4181 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-17 13:38:43.524  4057  4181 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 241
07-17 13:38:43.525  4070  4357 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,07-17 13:38:43.546  9726  9726 W System  : ClassLoader referenced unknown path: /system/priv-app/SecSettings2/lib/arm64
,07-17 13:38:43.578  9726  9726 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:43.584  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-17 13:38:43.594  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-17 13:38:43.595  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-17 13:38:43.617  9726  9726 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : ACCESSIBILITYSETTINGS, X6qErjsfs2, com.samsung.android.settings.accessibility.sharedaccessibility.scloud.BNRTask
07-17 13:38:43.617  9726  9726 I QBNRClientHelper: init SyncClientHelper : ACCESSIBILITYSETTINGS
07-17 13:38:43.618  9726  9726 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : CONNECTIONS, C0phMaUuZZ, com.samsung.android.settings.wifi.mobileap.WifiApBackupRestore
,07-17 13:38:43.618  9726  9726 I QBNRClientHelper: init SyncClientHelper : CONNECTIONS
07-17 13:38:43.618  9726  9726 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : WiFi, C0phMaUuZZ, com.samsung.android.settings.wifi.WifiBackupRestore
07-17 13:38:43.619  9726  9726 I QBNRClientHelper: init SyncClientHelper : WiFi
,07-17 13:38:43.660  9726  9726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-17 13:38:43.680  4057  4181 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_BT_EVT
07-17 13:38:43.681  4057  4181 E BluetoothAdapterState: stateChangeCallback : 16
07-17 13:38:43.681  4057  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,07-17 13:38:43.690  4057  4167 D BtConfig.SecureMode: isSecureModeOn:false
,07-17 13:38:43.691  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-17 13:38:43.701  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-17 13:38:43.701  9726  9726 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
07-17 13:38:43.702  4057  4057 D HeadsetService: Received stop request...Stopping profile...
,07-17 13:38:43.709  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-17 13:38:43.710  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:43.710  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
07-17 13:38:43.710  4057  4057 D HeadsetService: notifyProfileServiceStateChanged
07-17 13:38:43.712  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-17 13:38:43.715  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-17 13:38:43.717  4070  4070 D HeadsetProfile: Bluetooth service disconnected
07-17 13:38:43.717  4057  4057 D A2dpService: Received stop request...Stopping profile...
07-17 13:38:43.718  3704  3704 W BluetoothHeadset: Proxy not attached to service
07-17 13:38:43.719  3704  3704 I Telecom : SecBluetoothManager : not single connected gear
07-17 13:38:43.719  3704  3704 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-17 13:38:43.719  3704  3704 D BluetoothHeadset: unRegisterMessageListener : 11
07-17 13:38:43.719  3704  3704 W BluetoothHeadset: Proxy not attached to service
07-17 13:38:43.719  3704  3704 I Telecom : SecBluetoothManager : unregister MessageListener
07-17 13:38:43.720  9726  9726 D LocalBluetoothManager: LocalBluetoothManager :: constructor
07-17 13:38:43.720  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-17 13:38:43.720  3704  4366 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
07-17 13:38:43.720  3704  4366 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
07-17 13:38:43.720  3704  4366 I Telecom : SecBluetoothManager : mBluetoothHeadset is null
07-17 13:38:43.721  3704  4366 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
,07-17 13:38:43.725  4057  4492 D A2dpStateMachine: Exit Disconnected: -1
07-17 13:38:43.725  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
07-17 13:38:43.726  4057  4057 D Avrcp   : unregisterContentObserver
07-17 13:38:43.728  9726  9726 D BluetoothEventManager: BluetoothEventManager Constructor :: 
07-17 13:38:43.728  4057  4057 D Avrcp   : removeOnActiveSessionsChangedListener
07-17 13:38:43.729  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-17 13:38:43.729  4057  4167 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-17 13:38:43.729  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
07-17 13:38:43.729  4057  4167 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
07-17 13:38:43.729  4057  4167 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-17 13:38:43.730  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.730  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
07-17 13:38:43.730  4057  4057 D A2dpService: notifyProfileServiceStateChanged
,07-17 13:38:43.733  4070  4070 D A2dpProfile: Bluetooth service disconnected
07-17 13:38:43.734  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:43.734  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
07-17 13:38:43.734  4057  4057 V BluetoothAdapterState: isTurningOff()=true
07-17 13:38:43.734  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:43.734  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:43.734  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:43.735  4057  4057 D HidService: Received stop request...Stopping profile...
07-17 13:38:43.735  4057  4057 D HidService: Stopping Bluetooth HidService
07-17 13:38:43.735  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.735  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
07-17 13:38:43.735  4057  4057 D HidService: notifyProfileServiceStateChanged
07-17 13:38:43.737  4070  4070 D BluetoothInputDevice: Proxy object disconnected
07-17 13:38:43.737  4070  4070 D HidProfile: Bluetooth service disconnected
,07-17 13:38:43.738  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.739  9726  9726 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
07-17 13:38:43.739  9726  9726 D LocalBluetoothProfileManager: PANU : true
,07-17 13:38:43.742  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-17 13:38:43.743  4057  4057 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-17 13:38:43.743  4057  4057 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-17 13:38:43.746  4057  4057 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
,07-17 13:38:43.748  4057  4057 D HealthService: Received stop request...Stopping profile...
07-17 13:38:43.748  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.748  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
07-17 13:38:43.748  4057  4057 D HealthService: notifyProfileServiceStateChanged
,07-17 13:38:43.751  4057  4057 D PanService: Received stop request...Stopping profile...
,07-17 13:38:43.754  4057  4057 D EnhancedTetheringManager: stop
,07-17 13:38:43.756  4057  4057 D EnhancedTetheringManager: tetherEnabled : false
07-17 13:38:43.756  4057  4057 D ETMLeHelper: stopAdvertise
07-17 13:38:43.757  4057  4057 D BluetoothAdapter: STATE_TURNING_OFF
07-17 13:38:43.758  4057  4057 D BluetoothAdapter: STATE_TURNING_OFF
07-17 13:38:43.758  4057  4057 D BluetoothLeAdvertiser: stop advertising
07-17 13:38:43.758  9726  9726 D BluetoothSap: Create BluetoothSap proxy object
07-17 13:38:43.759  4057  4057 D BluetoothLeAdvertiser: wrapper is null
07-17 13:38:43.759  4057  4057 D EnhancedTetheringManager: removeNapWakeAlarm
,07-17 13:38:43.761  3704  4184 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4057 / op:PendingIntent{17e9a73: PendingIntentRecord{de8fd30 com.android.bluetooth broadcastIntent}}
07-17 13:38:43.761  4057  4057 D EnhancedTetheringManager: cancelFindTetherServer
07-17 13:38:43.762  4057  4057 D ETMLeHelper: stopScan
,07-17 13:38:43.762  4057  4057 D BluetoothAdapter: STATE_TURNING_OFF
,07-17 13:38:43.764  4057  4057 D BluetoothAdapter: STATE_TURNING_OFF
07-17 13:38:43.764  4057  4057 D BluetoothLeScanner: could not find callback wrapper
07-17 13:38:43.764  4057  4057 D EnhancedTetheringManager: removePanuWakeAlarm
,07-17 13:38:43.766  9726  9726 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
07-17 13:38:43.766  9726  9726 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,07-17 13:38:43.767  3704  6347 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4057 / op:PendingIntent{71e6acf: PendingIntentRecord{798bc5c com.android.bluetooth broadcastIntent}}
07-17 13:38:43.767  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.767  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
07-17 13:38:43.768  4057  4057 D PanService: notifyProfileServiceStateChanged
,07-17 13:38:43.769  4070  4070 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-17 13:38:43.769  4070  4070 D PanProfile: Bluetooth service disconnected
,07-17 13:38:43.771  4057  4057 D BluetoothMapService: Received stop request...Stopping profile...
,07-17 13:38:43.776  9726  9726 D DockEventReceiver: finishStartingService: stopping service
,07-17 13:38:43.777  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.777  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
07-17 13:38:43.777  4057  4057 D BluetoothMapService: notifyProfileServiceStateChanged
,07-17 13:38:43.779  4070  4070 D BluetoothMap: Proxy object disconnected
07-17 13:38:43.779  4070  4070 D MapProfile: Bluetooth service disconnected
,07-17 13:38:43.780  9726  9726 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:43.780  9726  9726 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
,07-17 13:38:43.780  9726  9726 D BluetoothPan: BluetoothPAN Proxy object connected
07-17 13:38:43.781  9726  9726 D PanProfile: Bluetooth service connected
07-17 13:38:43.781  4057  4057 D SapService: Received stop request...Stopping profile...
,07-17 13:38:43.781  4057  4057 V SapService: stop()
,07-17 13:38:43.784  9726  9726 D BluetoothSap: Proxy object connected
07-17 13:38:43.784  9726  9726 D SapProfile: Bluetooth service connected
,07-17 13:38:43.785  9726  9726 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-17 13:38:43.785  9726  9726 D PanProfile: Bluetooth service disconnected
,07-17 13:38:43.788  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.788  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
07-17 13:38:43.788  4057  4057 D SapService: notifyProfileServiceStateChanged
,07-17 13:38:43.791  9726  9726 D BluetoothSap: Proxy object disconnected
07-17 13:38:43.791  9726  9726 D SapProfile: Bluetooth service disconnected
07-17 13:38:43.792  4070  4070 D BluetoothSap: Proxy object disconnected
07-17 13:38:43.792  4070  4070 D SapProfile: Bluetooth service disconnected
07-17 13:38:43.793  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:43.793  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
07-17 13:38:43.793  4057  4057 V BluetoothAdapterState: isTurningOff()=true
07-17 13:38:43.793  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:43.793  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:43.793  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
,07-17 13:38:43.794  4057  4057 D HidDevService: Received stop request...Stopping profile...
,07-17 13:38:43.794  4057  4057 D HidDevService: stop()
07-17 13:38:43.794  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.794  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Message sending
07-17 13:38:43.794  4057  4057 D HidDevService: notifyProfileServiceStateChanged
,07-17 13:38:43.799  3704  3924 I ActivityManager: KPU : put [com.enhance.gameservice] : 28560 K
07-17 13:38:43.799  3704  3924 I ActivityManager: Killing 8955:com.enhance.gameservice/u0a106 (adj 906): DHA:empty #33
,07-17 13:38:43.807  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:43.809  4057  4493 W bt_osi_thread: run_thread: thread id 4493, thread name media_worker exited
07-17 13:38:43.809  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:43.809  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
07-17 13:38:43.809  4057  4057 V BluetoothAdapterState: isTurningOff()=true
07-17 13:38:43.809  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:43.809  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:43.809  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:43.810  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.810  4057  4057 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-17 13:38:43.810  4057  4057 W bt_btif : cleanup: HH disabling or disabled already, status = 0
07-17 13:38:43.810  4057  4057 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-17 13:38:43.810  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:43.810  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
07-17 13:38:43.810  4057  4057 V BluetoothAdapterState: isTurningOff()=true
07-17 13:38:43.810  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:43.811  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:43.811  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:43.811  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.811  4057  4057 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-17 13:38:43.811  4057  4057 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-17 13:38:43.811  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:43.812  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
07-17 13:38:43.812  4057  4057 V BluetoothAdapterState: isTurningOff()=true
07-17 13:38:43.812  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:43.812  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:43.812  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:43.812  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.812  4057  4057 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-17 13:38:43.812  4057  4057 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-17 13:38:43.816  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:43.816  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
07-17 13:38:43.816  4057  4057 V BluetoothAdapterState: isTurningOff()=true
07-17 13:38:43.816  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:43.816  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:43.816  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:43.817  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.817  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:43.817  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
07-17 13:38:43.817  4057  4057 V BluetoothAdapterState: isTurningOff()=true
07-17 13:38:43.817  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:,38:43.817  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:43.817  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:43.818  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.818  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:43.818  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Before synchronized
07-17 13:38:43.818  4057  4057 V BluetoothAdapterState: isTurningOff()=true
07-17 13:38:43.818  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:43.818  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:43.818  4057  4057 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:43.819  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.819  4057  4057 D HidDevService: cleanup()
07-17 13:38:43.819  4057  4057 V BluetoothHidDevServiceJni: cleanupNative enter
07-17 13:38:43.819  4057  4057 I BluetoothHidDevServiceJni: Cleaning up interface
07-17 13:38:43.819  4057  4057 I BluetoothHidDevServiceJni: Cleaning up callback object
07-17 13:38:43.819  4057  4057 V BluetoothHidDevServiceJni: cleanupNative done
07-17 13:38:43.821  4057  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
,07-17 13:38:43.833  3704  3760 D ActivityManager: cleanUpApplicationRecord -- 8955
07-17 13:38:43.835  4057  4167 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@93c5c5c
,07-17 13:38:43.835  4057  4167 D BtGatt.GattService: serverDisconnectIncomingConnClients()
07-17 13:38:43.835  4057  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-17 13:38:43.835  4057  4167 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-17 13:38:43.836  4057  4474 W bt_btif : BTA got unregistered event id 32
07-17 13:38:43.836  4670  4687 D ForegroundUtils: could not check pending caller
07-17 13:38:43.839  4057  4167 D BluetoothAdapterService: Autoconnection is available 
07-17 13:38:43.839  4057  4167 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
07-17 13:38:43.839  4057  4167 I BluetoothAdapterState: Entering BleOnState
,07-17 13:38:43.844  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
,07-17 13:38:43.844  4057  4057 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-17 13:38:43.844  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:43.844  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:43.878  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-17 13:38:43.878  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:44.020  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
07-17 13:38:44.020  4057  4057 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-17 13:38:44.020  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:44.020  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:44.021  4057  4167 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:44.030  4626  6633 I BeaconBle: Client requested to stop, listener=hjz@58783a9
07-17 13:38:44.032  9623  9724 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-17 13:38:44.032  3704  4236 E Watchdog: !@Sync 6 [17_lip_13_38_44.032]
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:44.032  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-17 13:38:44.037  9623  9724 D BluetoothAdapter: enable()
07-17 13:38:44.042  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:44.059  4057  4375 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-17 13:38:44.059  4057  4375 D AdapterProvider: query
07-17 13:38:44.060  9726  9737 D BluetoothSap: onBluetoothStateChange: up=false
07-17 13:38:44.061  4626  6633 I BeaconBle: Scan canceled successfully.
07-17 13:38:44.064  4670  4686 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-17 13:38:44.065  4670  4686 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-17 13:38:44.066  3704  4184 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{c19606: PendingIntentRecord{cc6e4c7 com.google.android.gms broadcastIntent}}
07-17 13:38:44.066  4670  4686 D BluetoothAdapter: There are no active google scan apps, stop scan
07-17 13:38:44.067  9726  9738 D BluetoothPan: onBluetoothStateChange on: false
07-17 13:38:44.069  4070  4088 D BluetoothPan: onBluetoothStateChange on: false
07-17 13:38:44.070  4057  4375 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@e81106f
07-17 13:38:44.071  4070  7052 D BluetoothMap: onBluetoothStateChange: up=false
07-17 13:38:44.072  4057  4375 D BluetoothAdapterService: updateEvent - already set, update
07-17 13:38:44.072  4057  4375 W BluetoothAdapterService: updateEvent - alreadySet is true
07-17 13:38:44.073  4057  4375 D AdapterProvider: update
07-17 13:38:44.077  4070  4349 D BluetoothSap: onBluetoothStateChange: up=false
,07-17 13:38:44.084  9623  9635 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-17 13:38:44.084  9623  9635 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-17 13:38:44.084  9623  9635 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
07-17 13:38:44.084  9623  9635 D BluetoothLeAdvertiser: Exit stop advertising
,07-17 13:38:44.085  9623  9635 D BluetoothAdapter: There are no active google scan apps, stop scan
07-17 13:38:44.085  9623  9635 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-17 13:38:44.085  9623  9635 D BluetoothLeScanner: Exiting stopAllScan
07-17 13:38:44.085  4070  4087 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-17 13:38:44.087  4057  4375 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:44.105  4044  4225 D BluetoothAdapter: onBluetoothStateChange: up=false
07-17 13:38:44.105  4044  4225 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-17 13:38:44.106  4044  4225 D BluetoothAdapter: There are no active google scan apps, stop scan
07-17 13:38:44.107  7445  7457 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-17 13:38:44.107  7445  7457 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-17 13:38:44.108  7445  7457 D BluetoothAdapter: There are no active google scan apps, stop scan
07-17 13:38:44.108  9726  9737 D BluetoothAdapter: onBluetoothStateChange: up=false
07-17 13:38:44.108  9726  9737 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-17 13:38:44.109  9726  9737 D BluetoothAdapter: There are no active google scan apps, stop scan
07-17 13:38:44.110  3704  3812 D BluetoothAdapter: onBluetoothStateChange: up=false
07-17 13:38:44.110  3704  3812 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-17 13:38:44.110  3704  3812 D BluetoothAdapter: There are no active google scan apps, stop scan
07-17 13:38:44.111  4070  4348 D BluetoothAdapter: onBluetoothStateChange: up=false
07-17 13:38:44.111  4070  4348 D BluetoothAdapter: Bluetooth is turned off, stop adv
07-17 13:38:44.112  4070  4348 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-17 13:38:44.113  4626  4640 D BluetoothAdapter: onBluetoothStateChange: up=false
07-17 13:38:44.113  4626  4640 D BluetoothAdapter: Bluetooth is turned off, stop adv
,07-17 13:38:44.114  4626  4640 D BluetoothAdapter: There are no active google scan apps, stop scan
,07-17 13:38:44.114  4626  4640 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
07-17 13:38:44.114  4626  4640 D BluetoothLeScanner: Exiting stopAllScan
,07-17 13:38:44.115  4057  4069 D BluetoothAdapter: onBluetoothStateChange: up=false
,07-17 13:38:44.116  3704  4338 W ActivityManager: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-17 13:38:44.120  3704  4338 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-17 13:38:44.120  3704  4338 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-17 13:38:44.123  3704  4338 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-17 13:38:44.123  4070  4088 D BluetoothPbap: onBluetoothStateChange: up=false
,07-17 13:38:44.124  3704  4338 D SecContentProvider: called from com.thaliproject.thalitest
,07-17 13:38:44.130  4057  4167 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,07-17 13:38:44.132  3704  3812 W BluetoothManagerService: BT is in BLE_ON State
,07-17 13:38:44.133  4057  4077 E BluetoothBondStateMachine: initStateMachine
,07-17 13:38:44.134  3704  3704 D Telecom : SecBluetoothManager : unregister BluetoothHeadset after STATE_OFF : null
07-17 13:38:44.134  3704  3704 D Telecom : SecBluetoothManager : unRegisterBluetoothHeadsetMessageListener fail
,07-17 13:38:44.136  4070  4357 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:44.136  4070  4357 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-17 13:38:44.136  3704  3704 D BluetoothPhoneService: Bluetooth Adapter state : 10
,07-17 13:38:44.139  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-17 13:38:44.139  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:44.139  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,07-17 13:38:44.150  9726  9726 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-17 13:38:44.150  9726  9726 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
07-17 13:38:44.151  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:44.155  4057  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-17 13:38:44.155  4057  4167 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-17 13:38:44.156  4057  4167 D BluetoothAdapterService: Autoconnection is available 
07-17 13:38:44.156  4057  4167 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
07-17 13:38:44.156  3704  3812 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
,07-17 13:38:44.158  3704  3760 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-17 13:38:44.161  3704  3760 D SecContentProvider: called from android.uid.bluetooth:1002
07-17 13:38:44.163  3704  4183 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{afda21d: PendingIntentRecord{4d10c92 com.google.android.gms broadcastIntent}}
07-17 13:38:44.163  3704  4182 D SecContentProvider: insert(), uri = 2
07-17 13:38:44.164  3704  4182 D SecContentProvider: called from android.uid.bluetooth:1002
07-17 13:38:44.165  4057  4174 E bt_btif : btif_vhci_sock_cleanup
07-17 13:38:44.165  4057  4167 I BluetoothAdapterState: Entering PendingCommandState
07-17 13:38:44.168  4057  4174 I bt_core_module: module_shut_down Shutting down module "btif_config_module"
07-17 13:38:44.168  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
07-17 13:38:44.168  4057  4057 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
07-17 13:38:44.169  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:44.169  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:44.171  4057  4474 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-17 13:38:44.171  4057  4057 D DOWNLOADABLE_DB: onReceive of BR
07-17 13:38:44.171  4057  4057 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
07-17 13:38:44.171  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:44.171  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:44.174  4057  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_ON
07-17 13:38:44.176  4057  4181 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-17 13:38:44.176  4057  4181 W bt_btif : btif_dm_generic_evt: event=33035
07-17 13:38:44.178  9726  9726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-17 13:38:44.182  4057  4167 I BluetoothAdapterState: Deferring USER_TURN_ON request...
07-17 13:38:44.183  3704  4328 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{78e1260: PendingIntentRecord{7574319 com.google.android.gms broadcastIntent}}
07-17 13:38:44.187  4057  4174 I bt_core_module: module_shut_down Shutdown of module "btif_config_module" completed
07-17 13:38:44.190  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:44.193  4057  4181 W bt_btif : btif_dm_generic_evt: event=33035
,07-17 13:38:44.205  3704  6347 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{4ef5fde: PendingIntentRecord{cd5a5bf com.google.android.gms broadcastIntent}}
,07-17 13:38:44.216  9726  9726 D DockEventReceiver: finishStartingService: stopping service
,07-17 13:38:44.225  3704  4184 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{248dedb: PendingIntentRecord{54fcd78 com.google.android.gms broadcastIntent}}
,07-17 13:38:44.227  9726  9726 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:44.227  9726  9726 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,07-17 13:38:44.231  4626  6629 W NearbyMessages: NetworkPollManager:  No operations for client(com.google.android.gms#0p:discoverer). It should not be in the tracker.
07-17 13:38:44.231  4626  6629 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-17 13:38:44.326  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-17 13:38:44.332  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-17 13:38:44.332  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-17 13:38:44.372  4057  4181 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
,07-17 13:38:44.373  4057  4181 I bt_core_module: module_shut_down Shutting down module "hci_module"
07-17 13:38:44.373  4057  4181 I bt_hci  : shut_down
,07-17 13:38:44.458  4057  4419 D bt_hwcfg: hw_epilog_process
07-17 13:38:44.459  4057  4419 I bt_vendor: low_power_mode_cb
,07-17 13:38:44.465  4057  4419 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-17 13:38:44.465  4057  4419 I bt_vendor: epilog_cb
07-17 13:38:44.465  4057  4419 I bt_hci  : epilog_finished_callback
,07-17 13:38:44.469  4057  4419 W bt_osi_thread: run_thread: thread id 4419, thread name hci_thread exited
,07-17 13:38:44.470  4057  4181 I bt_hci_h4: hal_close
07-17 13:38:44.471  4057  4451 W bt_osi_thread: run_thread: thread id 4451, thread name hci_single_chann exited
07-17 13:38:44.472  4057  4181 I bt_userial_vendor: device fd = 96 close
,07-17 13:38:44.473  4057  4181 I bt_upio : upio_set_bluetooth_power(on: 0)
07-17 13:38:44.479  4057  4181 I bt_core_module: module_shut_down Shutdown of module "hci_module" completed
07-17 13:38:44.479  4057  4181 I bt_core_module: module_shut_down Shutting down module "btsnoop_module"
07-17 13:38:44.479  4057  4181 I bt_core_module: module_shut_down Shutdown of module "btsnoop_module" completed
07-17 13:38:44.480  4057  4181 I bt_core_module: module_clean_up Cleaning up module "bte_logmsg_module"
07-17 13:38:44.480  4057  4181 I bt_core_module: module_clean_up Cleanup of module "bte_logmsg_module" completed
07-17 13:38:44.480  4057  4474 W bt_osi_thread: run_thread: thread id 4474, thread name bt_workqueue exited
07-17 13:38:44.482  4057  4174 I bt_core_module: module_shut_down Shutting down module "controller_module"
07-17 13:38:44.482  4057  4174 I bt_core_module: module_shut_down Shutdown of module "controller_module" completed
07-17 13:38:44.482  4057  4181 E BluetoothAdapterState: stateChangeCallback : 0
07-17 13:38:44.483  4057  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
07-17 13:38:44.487  4989  6649 I Authzen : [PermitStore] Getting all permits...
07-17 13:38:44.490  4057  4057 D BtGatt.DebugUtils: handleDebugAction() action=null
07-17 13:38:44.491  4057  4057 D BtGatt.GattService: Received stop request...Stopping profile...
07-17 13:38:44.492  4057  4057 D BtGatt.GattService: stop()
07-17 13:38:44.492  4057  4057 D BtGatt.GattService: cleanup binder
07-17 13:38:44.492  4057  4057 D BtGatt.AdvertiseManager: advertise clients cleared
07-17 13:38:44.492  4057  4057 D BtGatt.ScanManager: cleanup
07-17 13:38:44.493  3704  6347 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4057 / op:PendingIntent{6b1be42: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
07-17 13:38:44.495  4057  4167 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
07-17 13:38:44.496  4057  4057 D BtGatt.ScanManager: cleanup handler
07-17 13:38:44.498  4057  4057 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:44.499  4057  4057 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
,07-17 13:38:44.499  4057  4057 D BtGatt.GattService: notifyProfileServiceStateChanged
07-17 13:38:44.500  4057  4057 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:44.500  4057  4057 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
07-17 13:38:44.501  4057  4057 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:44.501  4057  4057 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:44.501  4057  4057 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:44.501  4057  4057 V BluetoothAdapterState: isBleTurningOff()=true
07-17 13:38:44.501  4057  4167 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
07-17 13:38:44.503  4057  4167 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-17 13:38:44.503  4057  4167 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-17 13:38:44.504  4057  4167 D BluetoothAdapterService: Autoconnection is available 
07-17 13:38:44.504  4057  4167 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
07-17 13:38:44.504  4057  4167 I BluetoothAdapterState: Entering OffState
07-17 13:38:44.504  3704  3812 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
07-17 13:38:44.507  4057  4167 D BluetoothAdapterState: Current state: OFF, message: USER_TURN_ON
,07-17 13:38:44.511  4057  4057 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-17 13:38:44.511  4057  4057 W BluetoothSdpJni: Cleaning up Bluetooth SDP object
07-17 13:38:44.512  4057  4174 E BluetoothServiceJni: Callback env check fail: env: 0x0, callback: 0xddc1cd40
07-17 13:38:44.512  4057  4174 E BluetoothServiceJni: Callback: 'callback_thread_event' is not called on the correct thread
07-17 13:38:44.512  4057  4181 W bt_btif : btif_dm_generic_evt: event=33035
07-17 13:38:44.512  4057  4181 E bt_btif_dm: ### ASSERT : system/bt/btif/src/btif_dm.c line 2983 Callback is NULL (0) ###
07-17 13:38:44.512  4057  4181 W bt_osi_thread: run_thread: thread id 4181, thread name bt_jni_workqueue exited
07-17 13:38:44.514  4057  4174 I bt_core_module: module_clean_up Cleaning up module "stack_config_module"
07-17 13:38:44.514  4057  4174 I bt_core_module: module_clean_up Cleanup of module "stack_config_module" completed
07-17 13:38:44.514  4057  4174 I bt_core_module: module_clean_up Cleaning up module "interop_module"
07-17 13:38:44.514  4057  4174 I bt_core_module: module_clean_up Cleanup of module "interop_module" completed
07-17 13:38:44.514  4057  4174 I bt_core_module: module_clean_up Cleaning up module "btif_config_module"
,07-17 13:38:44.524  4057  4174 I bt_core_module: module_clean_up Cleanup of module "btif_config_module" completed
07-17 13:38:44.524  4057  4174 I bt_core_module: module_clean_up Cleaning up module "bt_utils_module"
07-17 13:38:44.524  4057  4174 I bt_core_module: module_clean_up Cleanup of module "bt_utils_module" completed
07-17 13:38:44.525  4057  4174 I bt_core_module: module_clean_up Cleaning up module "osi_module"
,07-17 13:38:44.525  4057  4180 D bt_osi_alarm: callback_dispatch Callback thread exited
07-17 13:38:44.525  4057  4180 W bt_osi_thread: run_thread: thread id 4180, thread name alarm_dispatcher exited
,07-17 13:38:44.526  4057  4177 W bt_osi_thread: run_thread: thread id 4177, thread name alarm_default_ca exited
07-17 13:38:44.526  4057  4174 I bt_core_module: module_clean_up Cleanup of module "osi_module" completed
07-17 13:38:44.527  4057  4057 I BluetoothServiceJni: cleanupNative: return from cleanup
07-17 13:38:44.527  4057  4057 D DOWNLOADABLE_DB: cleanup
,07-17 13:38:44.529  3704  4740 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{8fad390: PendingIntentRecord{a22489 com.google.android.gms broadcastIntent}}
,07-17 13:38:44.531  4057  4057 I art     : System.exit called, status: 0
07-17 13:38:44.532  4057  4057 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-17 13:38:44.551  4626  6629 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
,07-17 13:38:44.564  3704  6511 I ActivityManager: Process com.android.bluetooth (pid 4057) has died(62,1780)
,07-17 13:38:44.564  3704  6511 D ActivityManager: cleanUpApplicationRecord -- 4057
07-17 13:38:44.566  4670  4687 D ForegroundUtils: could not check pending caller
,07-17 13:38:44.629  9623  9724 D BluetoothAdapter: enable()
,07-17 13:38:44.646  3704  4338 W ActivityManager: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-17 13:38:44.648  3704  4338 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-17 13:38:44.648  3704  4338 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-17 13:38:44.648  3704  4338 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-17 13:38:44.648  3704  4338 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-17 13:38:44.648  3704  4338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-17 13:38:44.648  3704  4338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-17 13:38:44.648  3704  4338 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-17 13:38:44.648  3704  4338 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-17 13:38:44.648  3704  4338 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-17 13:38:44.648  3704  4338 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-17 13:38:44.651  3704  4338 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-17 13:38:44.653  3704  4338 D SecContentProvider: called from com.thaliproject.thalitest
,07-17 13:38:44.662  3704  3812 D MountService: getExternalStorageMountMode : 3
07-17 13:38:44.662  3704  3812 D MountService: getExternalStorageMountMode : 3
,07-17 13:38:44.663  3704  3812 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 1002, packageName : com.android.bluetooth
,07-17 13:38:44.711  9764  9764 E Zygote  : v2
07-17 13:38:44.711  9764  9764 I libpersona: KNOX_SDCARD checking this for 1002
07-17 13:38:44.711  3704  3812 W ActivityManager: Slow operation: 51ms so far, now at startProcess: returned from zygote!
07-17 13:38:44.711  9764  9764 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:44.711  3704  3812 W ActivityManager: Slow operation: 51ms so far, now at startProcess: done updating battery stats
07-17 13:38:44.711  3704  3812 W ActivityManager: Slow operation: 51ms so far, now at startProcess: building log message
07-17 13:38:44.712  3704  3812 I ActivityManager: Start proc 9764:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
07-17 13:38:44.712  3704  3812 W ActivityManager: Slow operation: 51ms so far, now at startProcess: starting to update pids map
07-17 13:38:44.712  3704  3812 W ActivityManager: Slow operation: 51ms so far, now at startProcess: done updating pids map
07-17 13:38:44.712  3704  3812 W ActivityManager: Slow operation: 53ms so far, now at startProcess: done starting proc!
,07-17 13:38:44.713  9764  9764 E Zygote  : accessInfo : 0
,07-17 13:38:44.724  9764  9764 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:44.726  9764  9764 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.bluetooth 
,07-17 13:38:44.759  9764  9764 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:44.760  9764  9764 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:44.762  3704  3760 I ActivityManager: DSS on for com.android.bluetooth and scale is 1.0
,07-17 13:38:44.807  9764  9764 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-17 13:38:44.811  9764  9764 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:44.818  9764  9764 I HeadsetProvider: onCreate
,07-17 13:38:44.828  9764  9764 D BtSettings.ProfileConfig: Adding GattService
07-17 13:38:44.828  9764  9764 D BtSettings.ProfileConfig: Adding HeadsetService
07-17 13:38:44.828  9764  9764 D BtSettings.ProfileConfig: Adding A2dpService
,07-17 13:38:44.828  9764  9764 D BtSettings.ProfileConfig: Adding HidService
07-17 13:38:44.828  9764  9764 D BtSettings.ProfileConfig: Adding HealthService
07-17 13:38:44.828  9764  9764 D BtSettings.ProfileConfig: Adding PanService
07-17 13:38:44.828  9764  9764 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-17 13:38:44.828  9764  9764 D BtSettings.ProfileConfig: Adding SapService
07-17 13:38:44.829  9764  9764 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-17 13:38:44.829  9764  9764 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-17 13:38:44.829  9764  9764 D BtSettings.ProfileConfig: Adding HidDevService
07-17 13:38:44.829  9764  9764 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-17 13:38:44.835  3704  3911 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.837  3704  3911 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.840  3704  4740 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.842  3704  4740 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.845  3704  4740 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.847  3704  4740 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.851  3704  4753 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.853  3704  4753 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.857  3704  3760 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.859  3704  3760 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.864  3704  4182 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.865  3704  4182 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.870  3704  3924 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.871  3704  3924 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.873  3704  4183 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.874  3704  4183 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.876  3704  5299 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.877  3704  5299 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.880  3704  3759 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,07-17 13:38:44.881  3704  3759 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.883  3704  4184 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-17 13:38:44.883  3704  4184 D SecContentProvider: called from android.uid.bluetooth:1002
,07-17 13:38:44.978  9764  9764 D BluetoothAdapterState: make() - Creating AdapterState
,07-17 13:38:44.981  9764  9777 I BluetoothAdapterState: Entering OffState
,07-17 13:38:44.984  9764  9779 W bt_osi_thread: run_thread: thread id 9779, thread name stack_manager started
07-17 13:38:44.985  9764  9779 I bt_core_module: module_init Initializing module "osi_module"
07-17 13:38:44.985  9764  9779 I bt_core_module: module_init Initialized module "osi_module"
07-17 13:38:44.985  9764  9779 I bt_core_module: module_init Initializing module "bt_utils_module"
07-17 13:38:44.985  9764  9779 I bt_core_module: module_init Initialized module "bt_utils_module"
07-17 13:38:44.985  9764  9779 I bt_core_module: module_init Initializing module "btif_config_module"
,07-17 13:38:44.987  9764  9782 W bt_osi_thread: run_thread: thread id 9782, thread name alarm_default_ca started
,07-17 13:38:44.987  9764  9783 W bt_osi_thread: run_thread: thread id 9783, thread name alarm_dispatcher started
07-17 13:38:44.988  9764  9779 I bt_core_module: module_init Initialized module "btif_config_module"
07-17 13:38:44.988  9764  9779 I bt_core_module: module_init Initializing module "interop_module"
07-17 13:38:44.988  9764  9779 I bt_core_module: module_init Initialized module "interop_module"
07-17 13:38:44.988  9764  9779 I bt_core_module: module_init Initializing module "stack_config_module"
,07-17 13:38:44.990  9764  9779 I bt_core_module: module_init Initialized module "stack_config_module"
,07-17 13:38:44.991  9764  9784 W bt_osi_thread: run_thread: thread id 9784, thread name bt_jni_workqueue started
07-17 13:38:44.991  9764  9764 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
07-17 13:38:44.991  9764  9764 W bt_btif : btif_get_adapter_property 2
07-17 13:38:44.991  9764  9764 W bt_btif : btif_get_adapter_property 1
,07-17 13:38:44.994  9764  9784 E BluetoothServiceJni: populateRssiValuesNative
07-17 13:38:44.994  9764  9784 I bt_btif : getModelRssiValues
,07-17 13:38:44.994  9764  9784 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-17 13:38:44.994  9764  9764 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-17 13:38:44.997  9764  9764 D BluetoothAdapterService: makeHashMapAvPerformance: Loading from conf
,07-17 13:38:45.002  3704  3815 I PowerManagerService: [PWL] On : 0 (195746 ms ago)
07-17 13:38:45.002  3704  3815 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-17 13:38:45.012  3704  3812 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,07-17 13:38:45.015  9764  9777 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
,07-17 13:38:45.017  9764  9775 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-17 13:38:45.017  9764  9775 D AdapterProvider: query
,07-17 13:38:45.022  9764  9777 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-17 13:38:45.022  9764  9777 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-17 13:38:45.023  3704  3812 D BluetoothManagerService: Ble Turning On/Off, G state: 0, S state: 0
,07-17 13:38:45.024  9764  9777 D BluetoothAdapterService: Autoconnection is available 
07-17 13:38:45.024  9764  9777 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
07-17 13:38:45.025  9764  9777 D BluetoothAdapterState: Set Downloadbale DB
07-17 13:38:45.025  9764  9777 D DOWNLOADABLE_DB: initBluetoothDatabase
07-17 13:38:45.027  9764  9777 D DOWNLOADABLE_DB: initBroadcastReceiver
,07-17 13:38:45.030  9764  9777 D DOWNLOADABLE_DB: cleanupLooper
07-17 13:38:45.030  9764  9777 D DOWNLOADABLE_DB: quit init handler
,07-17 13:38:45.032  9764  9775 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@371bda9
,07-17 13:38:45.034  9764  9775 D BluetoothAdapterService: updateEvent - already set, update
,07-17 13:38:45.035  9764  9775 W BluetoothAdapterService: updateEvent - alreadySet is true
07-17 13:38:45.035  9764  9775 D AdapterProvider: update
,07-17 13:38:45.039  9764  9775 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:45.049  9764  9777 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-17 13:38:45.053  3704  4753 D MountService: getExternalStorageMountMode : 1
07-17 13:38:45.053  3704  4753 D MountService: getExternalStorageMountMode : 3
07-17 13:38:45.053  3704  4753 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10135, packageName : com.samsung.android.sm.policy
,07-17 13:38:45.073  9787  9787 E Zygote  : v2
07-17 13:38:45.074  9787  9787 I libpersona: KNOX_SDCARD checking this for 10135
07-17 13:38:45.074  9787  9787 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:45.074  3704  4753 I ActivityManager: Start proc 9787:com.samsung.android.sm.policy/u0a135 for content provider com.samsung.android.sm.policy/.db.PolicyClientProvider
,07-17 13:38:45.075  9787  9787 E Zygote  : accessInfo : 0
,07-17 13:38:45.085  9787  9787 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:45.087  9787  9787 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,07-17 13:38:45.120  9787  9787 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-17 13:38:45.121  9787  9787 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:45.124  3704  4182 I ActivityManager: DSS on for com.samsung.android.sm.policy and scale is 1.0
,07-17 13:38:45.152  9787  9787 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient_N/lib/arm64
,07-17 13:38:45.158  9623  9724 D BluetoothAdapter: enable()
,07-17 13:38:45.163  9764  9785 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-17 13:38:45.163  9764  9785 D AdapterProvider: query
,07-17 13:38:45.169  9787  9787 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:45.175  9764  9785 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@765503a
,07-17 13:38:45.177  9764  9785 D BluetoothAdapterService: updateEvent - already set, update
07-17 13:38:45.177  9764  9785 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-17 13:38:45.177  9764  9785 D AdapterProvider: update
,07-17 13:38:45.181  9764  9785 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:45.191  3704  4184 W ActivityManager: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-17 13:38:45.192  3704  4184 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-17 13:38:45.192  3704  4184 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-17 13:38:45.192  3704  4184 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-17 13:38:45.192  3704  4184 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-17 13:38:45.192  3704  4184 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-17 13:38:45.192  3704  4184 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-17 13:38:45.192  3704  4184 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-17 13:38:45.192  3704  4184 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-17 13:38:45.192  3704  4184 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-17 13:38:45.192  3704  4184 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-17 13:38:45.195  3704  4184 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-17 13:38:45.197  3704  4184 D SecContentProvider: called from com.thaliproject.thalitest
,07-17 13:38:45.202  9764  9777 D DOWNLOADABLE_DB: Local DB version is = 20160428 SCPM Client DB version is= 20160428
07-17 13:38:45.202  9764  9777 D DOWNLOADABLE_DB: latest polices have already been updated for BT_HFP
,07-17 13:38:45.218  9764  9777 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-17 13:38:45.235  9764  9777 D DOWNLOADABLE_DB: Local DB version is = 20160617 SCPM Client DB version is= 20160617
,07-17 13:38:45.235  9764  9777 D DOWNLOADABLE_DB: latest polices have already been updated for BT_BLE
,07-17 13:38:45.253  9764  9777 D DOWNLOADABLE_DB: verifyPolicyVersion
,07-17 13:38:45.275  9764  9777 D DOWNLOADABLE_DB: Local DB version is = 201612050001 SCPM Client DB version is= 201612050001
07-17 13:38:45.275  9764  9777 D DOWNLOADABLE_DB: latest polices have already been updated for BT_A2DP
,07-17 13:38:45.293  9764  9777 D BluetoothSecureManager: getInstant: null
07-17 13:38:45.293  9764  9777 D BluetoothSecureManager: calling getMethod for getService
,07-17 13:38:45.294  9764  9777 D BluetoothSecureManager: calling getService
,07-17 13:38:45.295  9764  9777 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@760e248
,07-17 13:38:45.298  3704  6511 D BluetoothSecureManagerService: isSecureModeEnabled
,07-17 13:38:45.298  3704  6511 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-17 13:38:45.299  9764  9777 D BtConfig.SecureMode: isSecureModeOn:false
07-17 13:38:45.299  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-17 13:38:45.301  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-17 13:38:45.301  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-17 13:38:45.303  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-17 13:38:45.303  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-17 13:38:45.305  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-17 13:38:45.305  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-17 13:38:45.307  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-17 13:38:45.307  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-17 13:38:45.309  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-17 13:38:45.309  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-17 13:38:45.311  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,07-17 13:38:45.311  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-17 13:38:45.313  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-17 13:38:45.313  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-17 13:38:45.315  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
07-17 13:38:45.315  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-17 13:38:45.317  9764  9777 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-17 13:38:45.317  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,07-17 13:38:45.319  9764  9777 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
,07-17 13:38:45.319  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-17 13:38:45.321  9764  9777 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidDevService
,07-17 13:38:45.322  9764  9777 D BluetoothBondStateMachine: make
,07-17 13:38:45.325  9764  9800 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-17 13:38:45.339  9764  9764 I BtGatt.JNI: classInitNative(L979): classInitNative: Success!
,07-17 13:38:45.342  9764  9777 I BluetoothAdapterState: Entering PendingCommandState
,07-17 13:38:45.350  9764  9764 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-17 13:38:45.352  9764  9764 D BtGatt.GattService: Received start request. Starting profile...
07-17 13:38:45.352  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:45.352  9764  9764 D BtGatt.GattService: start()
,07-17 13:38:45.354  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:45.355  9764  9764 D BtGatt.AdvertiseManager: advertise manager created
07-17 13:38:45.355  9764  9764 D BtGatt.AdvertiseManager: start
,07-17 13:38:45.363  9764  9764 D BtGatt.ScanManager: start
,07-17 13:38:45.397  9764  9764 D BtGatt.GattService: setGattService(): set to: com.android.bluetooth.gatt.GattService@dd72663
07-17 13:38:45.397  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:45.397  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:45.397  9764  9764 D BtGatt.GattService: refreshAbusiveScanPackages
07-17 13:38:45.399  9764  9764 D DOWNLOADABLE_DB: getAbuseScanPackages
,07-17 13:38:45.409  9764  9764 D BtGatt.GattService: refreshAbusiveScanValue()
,07-17 13:38:45.410  9764  9764 D DOWNLOADABLE_DB: getAbuseMaxScanCount
,07-17 13:38:45.419  9764  9764 D DOWNLOADABLE_DB: getAbuseAccumulatedScanTime
,07-17 13:38:45.428  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:45.428  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
07-17 13:38:45.428  9764  9764 D BtGatt.GattService: notifyProfileServiceStateChanged
07-17 13:38:45.429  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:45.429  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
,07-17 13:38:45.429  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:45.429  9764  9764 V BluetoothAdapterState: isTurningOn()=false
07-17 13:38:45.430  9764  9764 V BluetoothAdapterState: isBleTurningOn()=true
07-17 13:38:45.430  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
,07-17 13:38:45.431  9764  9777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,07-17 13:38:45.436  9764  9779 I bt_core_module: module_start_up Starting module "btif_config_module"
07-17 13:38:45.436  9764  9779 I bt_core_module: module_start_up Started module "btif_config_module"
07-17 13:38:45.437  9764  9779 I bt_core_module: module_start_up Starting module "btsnoop_module"
07-17 13:38:45.437  9764  9779 I bt_core_module: module_start_up Started module "btsnoop_module"
07-17 13:38:45.437  9764  9779 I bt_core_module: module_start_up Starting module "hci_module"
07-17 13:38:45.437  9764  9779 I bt_hci  : start_up
07-17 13:38:45.437  9764  9784 W bt_btif : btif_dm_generic_evt: event=33035
,07-17 13:38:45.438  9764  9814 W bt_osi_thread: run_thread: thread id 9814, thread name hci_thread started
,07-17 13:38:45.446  9764  9779 I bt_vendor: alloc value 0xe87b8d35
07-17 13:38:45.447  9764  9779 I bt_vendor: init
07-17 13:38:45.447  9764  9779 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-17 13:38:45.447  9764  9779 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-17 13:38:45.447  9764  9779 I bt_upio : upio_set_bluetooth_power(on: 0)
,07-17 13:38:45.448  9764  9779 I bt_upio : upio_set_bluetooth_power(on: 1)
,07-17 13:38:45.521  3704  4752 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:38:45.557  9764  9779 D bt_hci  : start_up starting async portion
,07-17 13:38:45.558  9764  9814 I bt_hci  : event_finish_startup
07-17 13:38:45.558  9764  9814 I bt_hci_h4: hal_open
07-17 13:38:45.558  9764  9814 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,07-17 13:38:45.561  9764  9814 I bt_userial_vendor: userial_vendor_open():UART is setup
07-17 13:38:45.561  9764  9814 I bt_userial_vendor: device fd = 95 open
,07-17 13:38:45.562  9764  9818 W bt_osi_thread: run_thread: thread id 9818, thread name hci_single_chann started
,07-17 13:38:45.563  9764  9814 E bt_hwcfg: Start CFG HW, HCI reset
,07-17 13:38:45.574  9764  9814 E bt_hwcfg: Read Local Name after HCI reset
,07-17 13:38:45.599  9764  9814 D bt_hwcfg: Chipset BCM4359C0
07-17 13:38:45.599  9764  9814 D bt_hwcfg: Target name = [BCM4359C0]
07-17 13:38:45.600  9764  9814 I bt_hwcfg: module_type[semco_b90s_c0].
,07-17 13:38:45.601  9764  9814 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
07-17 13:38:45.601  9764  9814 E bt_hwcfg: ORG patchram base 0092
07-17 13:38:45.601  9764  9814 E bt_hwcfg: ORG patchram minor 0143
07-17 13:38:45.601  9764  9814 E bt_hwcfg: fw ver (org)92.143
,07-17 13:38:45.601  9764  9814 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
,07-17 13:38:45.608  9764  9814 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-17 13:38:45.611  9764  9814 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,07-17 13:38:45.706  9623  9724 D BluetoothAdapter: enable()
,07-17 13:38:45.718  9764  9775 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-17 13:38:45.719  9764  9775 D AdapterProvider: query
,07-17 13:38:45.732  9764  9775 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@1fd948c
,07-17 13:38:45.734  9764  9775 D BluetoothAdapterService: updateEvent - already set, update
,07-17 13:38:45.735  9764  9775 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-17 13:38:45.735  9764  9775 D AdapterProvider: update
,07-17 13:38:45.740  9764  9775 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:45.748  3704  6347 W ActivityManager: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-17 13:38:45.749  3704  6347 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-17 13:38:45.749  3704  6347 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-17 13:38:45.749  3704  6347 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-17 13:38:45.749  3704  6347 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-17 13:38:45.749  3704  6347 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-17 13:38:45.749  3704  6347 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-17 13:38:45.749  3704  6347 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-17 13:38:45.749  3704  6347 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-17 13:38:45.749  3704  6347 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-17 13:38:45.749  3704  6347 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-17 13:38:45.751  3704  6347 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-17 13:38:45.752  3704  6347 D SecContentProvider: called from com.thaliproject.thalitest
,07-17 13:38:46.231  4528  4528 D io_stats: !@   8,0 r 25968 2290684 w 5006 207660 d 646 74500 f 2059 2059 iot 11400 10792 th 466220 0 0 pt 0 inp 0 0 196.973
,07-17 13:38:46.257  9623  9724 D BluetoothAdapter: enable()
,07-17 13:38:46.259  9764  9814 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-17 13:38:46.260  9764  9814 I bt_hwcfg: FW Download delta = 685690
07-17 13:38:46.260  9764  9814 D bt_hwcfg: Settlement delay -- 100 ms
07-17 13:38:46.260  9764  9814 I bt_hwcfg: Setting fw settlement delay to 100 
,07-17 13:38:46.265  9764  9775 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,07-17 13:38:46.265  9764  9775 D AdapterProvider: query
,07-17 13:38:46.280  9764  9775 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@c0fedb
,07-17 13:38:46.282  9764  9775 D BluetoothAdapterService: updateEvent - already set, update
,07-17 13:38:46.283  9764  9775 W BluetoothAdapterService: updateEvent - alreadySet is true
07-17 13:38:46.283  9764  9775 D AdapterProvider: update
,07-17 13:38:46.288  9764  9775 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:46.297  3704  3924 W ActivityManager: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-17 13:38:46.298  3704  3924 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-17 13:38:46.298  3704  3924 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-17 13:38:46.298  3704  3924 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-17 13:38:46.298  3704  3924 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-17 13:38:46.298  3704  3924 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-17 13:38:46.298  3704  3924 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-17 13:38:46.298  3704  3924 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-17 13:38:46.298  3704  3924 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-17 13:38:46.298  3704  3924 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-17 13:38:46.298  3704  3924 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-17 13:38:46.300  3704  3924 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-17 13:38:46.301  3704  3924 D SecContentProvider: called from com.thaliproject.thalitest
,07-17 13:38:46.385  9764  9814 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,07-17 13:38:46.488  9764  9814 I bt_hwcfg: vendor lib fwcfg completed
07-17 13:38:46.489  9764  9814 I bt_vendor: firmware callback
07-17 13:38:46.489  9764  9814 I bt_hci  : firmware_config_callback
07-17 13:38:46.489  9764  9779 I bt_core_module: module_start_up Started module "hci_module"
,07-17 13:38:46.491  9764  9819 W bt_osi_thread: run_thread: thread id 9819, thread name bt_workqueue started
,07-17 13:38:46.493  9764  9819 I bt_core_module: module_init Initializing module "bte_logmsg_module"
07-17 13:38:46.493  9764  9819 I bt_core_module: module_init Initialized module "bte_logmsg_module"
07-17 13:38:46.494  9764  9784 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-17 13:38:46.499  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9764
07-17 13:38:46.500  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
07-17 13:38:46.500  9764  9784 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-17 13:38:46.501  9764  9784 W bt_btif : get_secure_storage_key - ss_is_supported = 1
07-17 13:38:46.501  9764  9784 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
07-17 13:38:46.501  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
07-17 13:38:46.501  9764  9784 W bt_btif : btif_dm_generic_evt: event=33035
,07-17 13:38:46.506  9764  9784 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-17 13:38:46.507  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9764
07-17 13:38:46.507  3114  3114 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,07-17 13:38:46.760  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-17 13:38:46.761  9764  9784 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,07-17 13:38:46.763  9764  9820 W bt_osi_thread: run_thread: thread id 9820, thread name module_wrapper started
07-17 13:38:46.764  9764  9820 I bt_core_module: module_start_up Starting module "controller_module"
,07-17 13:38:46.805  9623  9724 D BluetoothAdapter: enable()
,07-17 13:38:46.810  9764  9775 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-17 13:38:46.810  9764  9775 D AdapterProvider: query
,07-17 13:38:46.822  9764  9775 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@b902cb6
,07-17 13:38:46.824  9764  9775 D BluetoothAdapterService: updateEvent - already set, update
,07-17 13:38:46.825  9764  9775 W BluetoothAdapterService: updateEvent - alreadySet is true
07-17 13:38:46.825  9764  9775 D AdapterProvider: update
,07-17 13:38:46.831  9764  9775 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:46.842  3704  4328 W ActivityManager: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-17 13:38:46.843  3704  4328 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-17 13:38:46.843  3704  4328 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-17 13:38:46.843  3704  4328 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-17 13:38:46.843  3704  4328 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-17 13:38:46.843  3704  4328 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-17 13:38:46.843  3704  4328 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-17 13:38:46.843  3704  4328 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-17 13:38:46.843  3704  4328 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-17 13:38:46.843  3704  4328 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-17 13:38:46.843  3704  4328 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-17 13:38:46.845  3704  4328 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-17 13:38:46.846  3704  4328 D SecContentProvider: called from com.thaliproject.thalitest
,07-17 13:38:46.855  9764  9820 I bt_core_module: module_start_up Started module "controller_module"
07-17 13:38:46.855  9764  9820 W bt_osi_thread: run_thread: thread id 9820, thread name module_wrapper exited
,07-17 13:38:46.873  9764  9784 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,07-17 13:38:46.884  9764  9784 E bt_btif : bta_dm_sm_execute event:0x2
07-17 13:38:46.884  9764  9784 W bt_btif : btif_dm_generic_evt: event=33035
,07-17 13:38:46.888  9764  9784 D bt_hci  : do_postload posting postload work item
,07-17 13:38:46.889  9764  9784 E bt_btif_sock: btif_sock_init: !vhci_init
07-17 13:38:46.889  9764  9814 I bt_hci  : event_postload
07-17 13:38:46.889  9764  9784 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:227 ##
07-17 13:38:46.889  9764  9814 D bt_hwcfg: hw_sco_config
07-17 13:38:46.889  9764  9814 I bt_hwcfg: I2SPCM config {0x1, 0x0, 0x0, 0x1}
07-17 13:38:46.889  9764  9814 I bt_vendor: sco_config_cb
07-17 13:38:46.889  9764  9814 I bt_hci  : sco_config_callback postload finished.
,07-17 13:38:46.896  9764  9784 I         : iop_db_open: iop_db_open status 0
07-17 13:38:46.901  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:46.901  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:46.904  9764  9784 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
07-17 13:38:46.904  9764  9784 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
07-17 13:38:46.904  9764  9784 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
07-17 13:38:46.904  9764  9784 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Grace SWB-B90S eLNA-0092
07-17 13:38:46.904  9764  9784 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0092.0143_semco.hcd
07-17 13:38:46.904  9764  9784 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
07-17 13:38:46.905  9764  9784 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true
07-17 13:38:46.905  9764  9784 E BluetoothAdapterState: stateChangeCallback : 1
07-17 13:38:46.906  9764  9777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
07-17 13:38:46.906  9764  9814 I bt_hwcfg: SCO PCM configure {0x0, 0x1, 0x0, 0x0, 0x0}
,07-17 13:38:46.908  9764  9814 I bt_vendor: low_power_mode_cb
,07-17 13:38:46.911  9764  9777 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:46.911  9764  9777 D DOWNLOADABLE_DB: refreshDbFile
07-17 13:38:46.911  9764  9777 D BluetoothServiceJni: refreshDownloadableDbFileNative:
07-17 13:38:46.911  9764  9777 I bt_btif : refreshDownloadableDbFile
,07-17 13:38:46.921  9764  9777 I         : iop_db_open: iop_db_open status 0
07-17 13:38:46.921  9764  9777 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-17 13:38:46.921  9764  9777 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-17 13:38:46.929  9764  9777 D BluetoothAdapterService: Autoconnection is available 
07-17 13:38:46.929  9764  9777 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
07-17 13:38:46.929  9764  9777 I BluetoothAdapterState: Entering BleOnState
,07-17 13:38:46.936  3704  3812 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,07-17 13:38:46.938  3704  3812 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,07-17 13:38:46.941  3704  3812 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:46.942  9764  9777 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
07-17 13:38:46.942  9764  9785 E BluetoothBondStateMachine: initStateMachine
,07-17 13:38:46.946  9764  9777 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-17 13:38:46.946  9764  9777 D BluetoothAdapterService: Bluetooth PBAP supported is true
,07-17 13:38:46.947  9764  9777 D BluetoothAdapterService: Autoconnection is available 
07-17 13:38:46.947  9764  9777 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
07-17 13:38:46.947  3704  3812 D BluetoothManagerService: Turning On/Off, G state: 0, S state: 0, mBLE count: 0, s BLE count: 0
07-17 13:38:46.947  9764  9777 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-17 13:38:46.947  9764  9777 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
07-17 13:38:46.948  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-17 13:38:46.955  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-17 13:38:46.961  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-17 13:38:46.970  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-17 13:38:46.972  4070  4357 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,07-17 13:38:46.972  4070  4357 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,07-17 13:38:46.972  3704  3704 D BluetoothPhoneService: Bluetooth Adapter state : 11
,07-17 13:38:46.976  9764  9764 D HeadsetService: Received start request. Starting profile...
07-17 13:38:46.976  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:46.977  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-17 13:38:46.977  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:46.977  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-17 13:38:46.988  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:46.989  9726  9726 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:46.989  9726  9726 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
07-17 13:38:47.002  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-17 13:38:47.008  9764  9764 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
,07-17 13:38:47.010  9764  9764 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-17 13:38:47.010  9764  9764 D HeadsetStateMachine: make
07-17 13:38:47.012  9764  9764 E HeadsetStateMachine: # of Max HF connection is 3
,07-17 13:38:47.016  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-17 13:38:47.022  3704  4182 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{28626fa: PendingIntentRecord{25af4ab com.google.android.gms broadcastIntent}}
,07-17 13:38:47.025  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,07-17 13:38:47.035  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-17 13:38:47.035  9764  9777 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-17 13:38:47.035  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
07-17 13:38:47.036  9764  9777 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
07-17 13:38:47.036  9764  9777 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-17 13:38:47.045  9764  9777 I BluetoothAdapterState: Entering PendingCommandState
,07-17 13:38:47.055  9764  9764 I DualScoManager: Instantiating Dual Sco Manager
07-17 13:38:47.055  9764  9764 I DualScoManager: Set HeadsetServiceHelper
07-17 13:38:47.056  9764  9764 I DualScoManager: setNotificationManager
07-17 13:38:47.056  9764  9764 I DualScoManager: setAudioManager
,07-17 13:38:47.057  9764  9764 D BluetoothAtMessage: createCMTIContentObservers
,07-17 13:38:47.065  9764  9764 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@7db2f66
,07-17 13:38:47.068  9764  9764 I HeadsetService: getHeadsetDB(true) - 44:78:3E:94:4A:XX, 300, 1
07-17 13:38:47.068  9764  9764 I DualScoManager: setSystemAudioInbandSupported : true
,07-17 13:38:47.069  9764  9764 I HeadsetStateMachine: isAutoAppInstalled : false
07-17 13:38:47.069  9764  9764 I HeadsetStateMachine: IBR : true (SysA : 1 / DB : 1)
,07-17 13:38:47.071  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:47.071  9764  9764 D DOWNLOADABLE_DB: getNotAllowedVoiceRecognitionDeviceList
,07-17 13:38:47.078  9764  9822 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,07-17 13:38:47.081  9764  9814 I bt_hwcfg: SCO PCM data format {0x0, 0x0, 0x3, 0x0, 0x0}
07-17 13:38:47.081  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.081  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
,07-17 13:38:47.081  9764  9764 D HeadsetService: notifyProfileServiceStateChanged
,07-17 13:38:47.083  9764  9814 I bt_hwcfg: sco I2S/PCM config result 0 [0-Success, 1-Fail]
07-17 13:38:47.083  9764  9814 I bt_vendor: sco_audiostate_cb(status: 0)
,07-17 13:38:47.084  9764  9822 D HeadsetStateMachine: Clear mHeadsetBrsf
07-17 13:38:47.084  9764  9822 D HeadsetStateMachine: map size, before remove : 0
07-17 13:38:47.084  9764  9822 D HeadsetStateMachine: map size, after remove: 0
07-17 13:38:47.084  9764  9764 D A2dpService: Received start request. Starting profile...
07-17 13:38:47.084  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.084  9764  9822 D HeadsetStateMachine: connectNextConnectingDevice(false) : null
,07-17 13:38:47.085  9764  9764 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-17 13:38:47.093  9764  9764 I Avrcp   : No of Audio players :: 1
07-17 13:38:47.093  9764  9764 I Avrcp   : App Package name is GM
,07-17 13:38:47.106  9764  9764 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,07-17 13:38:47.108  9764  9764 I Avrcp   : No of Video players :: 2
07-17 13:38:47.108  9764  9764 I Avrcp   : Video App Package name is VP
,07-17 13:38:47.118  9764  9764 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-17 13:38:47.118  9764  9764 I Avrcp   : Video App Package name is others
,07-17 13:38:47.126  9764  9764 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-17 13:38:47.126  9764  9764 I Avrcp   : Add tempPlayer
07-17 13:38:47.126  9764  9764 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-17 13:38:47.127  9764  9764 V Avrcp   : no_of_players : 4
07-17 13:38:47.127  9764  9764 I Avrcp   : Total no of players: 4
07-17 13:38:47.127  9764  9764 V Avrcp   : Samsung player is the 1st player
,07-17 13:38:47.127  9764  9764 D Avrcp   : Compose Browsing Service Candidate
,07-17 13:38:47.129  9764  9764 D Avrcp   : ResolveInfo info ResolveInfo{113e0c0 com.android.bluetooth/.a2dpsink.mbs.A2dpMediaBrowserService m=0x108000}
07-17 13:38:47.129  9764  9764 D Avrcp   : ResolveInfo info ResolveInfo{87161f9 com.google.android.music/.browse.MediaBrowserService m=0x108000}
07-17 13:38:47.129  9764  9764 D Avrcp   : Initialize Media Controller
,07-17 13:38:47.131  9764  9764 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,07-17 13:38:47.135  9764  9764 E Avrcp   : getActiveSessions
,07-17 13:38:47.135  9764  9764 D Avrcp   : pick active media Controller
07-17 13:38:47.135  9764  9764 D Avrcp   : Get the active Media Controller 
,07-17 13:38:47.137  9764  9764 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-17 13:38:47.137  9764  9764 D A2dpStateMachine: make
,07-17 13:38:47.140  9764  9825 W bt_osi_thread: run_thread: thread id 9825, thread name media_worker started
,07-17 13:38:47.140  9764  9764 E bt_btif : warning : media task started media_task_refcnt 1 
07-17 13:38:47.140  9764  9764 W bt_btif : btif_ar_init
07-17 13:38:47.140  9764  9784 W bt_btif : av start inhibit off
,07-17 13:38:47.142  9764  9764 E A2dpStateMachine: isDualPlayEnabled : Dual Play not supported
,07-17 13:38:47.143  9764  9824 D A2dpStateMachine: Enter Disconnected: -2
,07-17 13:38:47.145  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:47.145  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
07-17 13:38:47.145  9764  9764 D A2dpService: notifyProfileServiceStateChanged
07-17 13:38:47.146  9764  9764 I BluetoothHidServiceJni: classInitNative: succeeds
,07-17 13:38:47.150  9764  9764 D HidService: Received start request. Starting profile...
07-17 13:38:47.150  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.151  9764  9764 D HidService: setHidService(): set to: null
07-17 13:38:47.151  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.151  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
07-17 13:38:47.151  9764  9764 D HidService: notifyProfileServiceStateChanged
,07-17 13:38:47.151  9764  9764 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-17 13:38:47.155  9764  9764 D HealthService: Received start request. Starting profile...
07-17 13:38:47.155  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:47.157  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.157  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
07-17 13:38:47.157  9764  9764 D HealthService: notifyProfileServiceStateChanged
,07-17 13:38:47.158  9764  9764 I BluetoothPanServiceJni: classInitNative(L139): succeeds
,07-17 13:38:47.161  9764  9764 D PanService: Received start request. Starting profile...
07-17 13:38:47.161  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.162  9764  9764 D BluetoothPanServiceJni: initializeNative(L144): pan
,07-17 13:38:47.167  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.167  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
07-17 13:38:47.167  9764  9764 D PanService: notifyProfileServiceStateChanged
,07-17 13:38:47.172  9764  9764 D BluetoothMapService: Received start request. Starting profile...
07-17 13:38:47.172  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
,07-17 13:38:47.173  9726  9726 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:47.174  9726  9726 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,07-17 13:38:47.183  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.184  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
07-17 13:38:47.184  9764  9764 D BluetoothMapService: notifyProfileServiceStateChanged
,07-17 13:38:47.188  9764  9764 V SapService: SapBinder()
,07-17 13:38:47.190  9764  9764 D SapService: Received start request. Starting profile...
07-17 13:38:47.190  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.190  9764  9764 V SapService: start()
07-17 13:38:47.190  9764  9764 D SapService: Disable sap : false
,07-17 13:38:47.209  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.209  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
07-17 13:38:47.209  9764  9764 D SapService: notifyProfileServiceStateChanged
,07-17 13:38:47.210  9764  9764 V BluetoothHidDevServiceJni: classInitNative: done
,07-17 13:38:47.214  9764  9764 D HidDevService: Received start request. Starting profile...
,07-17 13:38:47.214  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.214  9764  9764 D HidDevService: start()
07-17 13:38:47.214  9764  9764 V BluetoothHidDevServiceJni: initNative enter
07-17 13:38:47.214  9764  9764 V BluetoothHidDevServiceJni: initNative done
07-17 13:38:47.215  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.215  9764  9764 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Message sending
07-17 13:38:47.215  9764  9764 D HidDevService: notifyProfileServiceStateChanged
07-17 13:38:47.215  9764  9764 D HeadsetStateMachine: Proxy object connected
,07-17 13:38:47.216  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
,07-17 13:38:47.216  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
07-17 13:38:47.216  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:47.216  9764  9764 V BluetoothAdapterState: isTurningOn()=true
07-17 13:38:47.216  9764  9764 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:47.216  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
,07-17 13:38:47.217  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-17 13:38:47.218  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:47.218  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isTurningOn()=true
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:47.218  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-17 13:38:47.218  9764  9764 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-17 13:38:47.218  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:47.218  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isTurningOn()=true
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:47.218  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:47.218  9764  9822 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-17 13:38:47.218  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isTurningOn()=true
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:47.218  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:47.219  9764  9822 D HeadsetStateMachine: Disconnected process message: 11, size: 0
07-17 13:38:47.219  9764  9822 E HeadsetStateMachine: Unknown message: 11
,07-17 13:38:47.227  9764  9764 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-17 13:38:47.227  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:47.227  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
07-17 13:38:47.227  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:47.227  9764  9764 V BluetoothAdapterState: isTurningOn()=true
07-17 13:38:47.227  9764  9764 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:47.227  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:47.227  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:47.227  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
07-17 13:38:47.227  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:47.227  9764  9764 V BluetoothAdapterState: isTurningOn()=true
07-17 13:38:47.228  9764  9764 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:47.228  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
,07-17 13:38:47.392  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:47.392  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
07-17 13:38:47.393  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:47.393  9764  9764 V BluetoothAdapterState: isTurningOn()=true
07-17 13:38:47.393  9764  9764 V BluetoothAdapterState: isBleTurningOn()=false
,07-17 13:38:47.393  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:47.393  9764  9764 E BluetoothAdapterService: handleMessage() - Message: 1
07-17 13:38:47.393  9764  9764 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Before synchronized
07-17 13:38:47.393  9764  9764 V BluetoothAdapterState: isTurningOff()=false
07-17 13:38:47.393  9764  9764 V BluetoothAdapterState: isTurningOn()=true
07-17 13:38:47.393  9764  9764 V BluetoothAdapterState: isBleTurningOn()=false
07-17 13:38:47.393  9764  9764 V BluetoothAdapterState: isBleTurningOff()=false
07-17 13:38:47.393  9623  9724 D BluetoothAdapter: enable()
07-17 13:38:47.394  9764  9764 I BluetoothA2dpServiceJni: Attempting to set busy level
,07-17 13:38:47.396  9764  9777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
07-17 13:38:47.399  9764  9777 E BluetoothServiceJni: enableBrEdrNative:
07-17 13:38:47.399  9764  9777 I bt_btif : enable_bredr
07-17 13:38:47.400  9764  9784 W bt_btif : btif_dm_generic_evt: event=33035
,07-17 13:38:47.414  9764  9784 W bt_btif : btif_dm_generic_evt: event=33035
,07-17 13:38:47.415  9764  9775 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-17 13:38:47.416  9764  9775 D AdapterProvider: query
,07-17 13:38:47.426  9764  9784 W bt_btif : BTA got event
07-17 13:38:47.426  9764  9784 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try co
07-17 13:38:47.426  9764  9784 W bt_btif :                : se: event=3, se
07-17 13:38:47.427  9764  9819 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
,07-17 13:38:47.437  9764  9819 D CODEC_IF_MOD: codec_open: codec_open
07-17 13:38:47.437  9764  9819 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-17 13:38:47.437  9764  9819 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-17 13:38:47.437  9764  9819 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-17 13:38:47.437  9764  9819 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-17 13:38:47.437  9764  9819 D CODEC_IF: codec_if_close: codec_if_close hdl -909025276
07-17 13:38:47.437  9764  9819 D CODEC_IF_MOD: codec_close: codec_close
07-17 13:38:47.437  9764  9819 D CODEC_IF_MOD: codec_close: freed apt-x encoder
07-17 13:38:47.437  9764  9819 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-17 13:38:47.437  9764  9819 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
07-17 13:38:47.437  9764  9784 E BluetoothServiceJni: populateRssiValuesNative
07-17 13:38:47.437  9764  9784 I bt_btif : getModelRssiValues
07-17 13:38:47.437  9764  9784 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
07-17 13:38:47.442  9764  9775 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@f1f3b52
07-17 13:38:47.443  9764  9775 D BluetoothAdapterService: updateEvent - already set, update
,07-17 13:38:47.444  9764  9775 W BluetoothAdapterService: updateEvent - alreadySet is true
07-17 13:38:47.444  9764  9775 D AdapterProvider: update
,07-17 13:38:47.446  9764  9819 D CODEC_IF_SSHD: codec_open: codec_open
,07-17 13:38:47.446  9764  9819 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-17 13:38:47.446  9764  9819 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-17 13:38:47.447  9764  9819 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-17 13:38:47.447  9764  9819 D CODEC_IF: codec_if_close: codec_if_close hdl -948454016
07-17 13:38:47.447  9764  9819 D CODEC_IF_SSHD: codec_close: codec_close
07-17 13:38:47.447  9764  9819 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-17 13:38:47.447  9764  9819 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-17 13:38:47.447  9764  9819 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
,07-17 13:38:47.449  9764  9775 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:47.457  9764  9819 D CODEC_IF_SSHD2: codec_open: codec_open
,07-17 13:38:47.457  9764  9819 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-17 13:38:47.457  9764  9819 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-17 13:38:47.457  9764  9819 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-17 13:38:47.457  9764  9819 D CODEC_IF: codec_if_close: codec_if_close hdl -539154432
07-17 13:38:47.457  9764  9819 D CODEC_IF_SSHD2: codec_close: codec_close
,07-17 13:38:47.457  9764  9819 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
07-17 13:38:47.457  9764  9819 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
07-17 13:38:47.459  9764  9819 D CODEC_IF_MOD: codec_open: codec_open
07-17 13:38:47.459  9764  9819 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
07-17 13:38:47.459  9764  9819 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
07-17 13:38:47.459  9764  9819 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
07-17 13:38:47.459  9764  9819 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-17 13:38:47.459  9764  9819 D CODEC_IF: codec_if_close: codec_if_close hdl -909025276
07-17 13:38:47.459  9764  9819 D CODEC_IF_MOD: codec_close: codec_close
07-17 13:38:47.459  9764  9819 D CODEC_IF_MOD: codec_close: freed apt-x encoder
,07-17 13:38:47.459  9764  9819 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
07-17 13:38:47.459  9764  9819 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
07-17 13:38:47.461  3704  4752 W ActivityManager: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,07-17 13:38:47.462  3704  4752 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-17 13:38:47.462  3704  4752 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9623, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
07-17 13:38:47.462  3704  4752 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
07-17 13:38:47.462  3704  4752 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
07-17 13:38:47.462  3704  4752 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
07-17 13:38:47.462  3704  4752 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
07-17 13:38:47.462  3704  4752 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
07-17 13:38:47.462  3704  4752 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-17 13:38:47.462  3704  4752 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
07-17 13:38:47.462  3704  4752 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
07-17 13:38:47.462  9764  9819 D CODEC_IF_SSHD: codec_open: codec_open
07-17 13:38:47.462  9764  9819 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
07-17 13:38:47.462  9764  9819 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
07-17 13:38:47.462  9764  9819 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-17 13:38:47.462  9764  9819 D CODEC_IF: codec_if_close: codec_if_close hdl -948454016
07-17 13:38:47.462  9764  9819 D CODEC_IF_SSHD: codec_close: codec_close
07-17 13:38:47.462  9764  9819 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
07-17 13:38:47.463  9764  9819 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
07-17 13:38:47.463  9764  9819 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
07-17 13:38:47.464  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:47.464  9764  9819 D CODEC_IF_SSHD2: codec_open: codec_open
07-17 13:38:47.465  9764  9819 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
07-17 13:38:47.465  9764  9819 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
07-17 13:38:47.465  9764  9819 D CODEC_IF: codec_if_open: codec module opened (v0.1
07-17 13:38:47.465  9764  9819 D CODEC_IF: codec_if_close: codec_if_close hdl -539154432
07-17 13:38:47.465  9764  9819 D CODEC_IF_SSHD2: codec_close: codec_close
07-17 13:38:47.465  9764  9819 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
07-17 13:38:47.465  3704  4752 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
07-17 13:38:47.466  3704  4752 D SecContentProvider: called from com.thaliproject.thalitest
07-17 13:38:47.474  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-17 13:38:47.474  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-17 13:38:47.474  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-17 13:38:47.481  9764  9784 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-17 13:38:47.481  9764  9784 E bt_btif : btif_handle_bluetooth_enable_evt
07-17 13:38:47.481  9764  9784 E bt_btif : ANT+ socket does not initialize.
,07-17 13:38:47.483  9764  9838 W bt_osi_thread: run_thread: thread id 9838, thread name btif_sock started
,07-17 13:38:47.483  4783  4840 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 5ms lastUpdatedAfter : 60120 ms mFlush_time_threasold : 2000 mCurrentSize : 257
07-17 13:38:47.483  9764  9784 E BluetoothAdapterState: stateChangeCallback : 17
07-17 13:38:47.483  9764  9784 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
07-17 13:38:47.484  9764  9784 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-17 13:38:47.484  9764  9784 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:3
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:3
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:2
,07-17 13:38:47.484  9764  9784 E bt_btif : warning : no command pending, ignore ack
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:3
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:2
07-17 13:38:47.484  9764  9784 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-17 13:38:47.484  9764  9784 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
07-17 13:38:47.484  9764  9784 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:3
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:3
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:2
07-17 13:38:47.484  9764  9825 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-17 13:38:47.484  9764  9784 E bt_btif : warning : no command pending, ignore ack
07-17 13:38:47.484  9764  9825 E bt_btif : warning : no command pending, ignore ack
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:3
07-17 13:38:47.484  9764  9784 E bt_btif : no av control block available at state:2
07-17 13:38:47.484  9764  9825 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
07-17 13:38:47.484  9764  9784 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
07-17 13:38:47.484  9764  9825 E bt_btif : warning : no command pending, ignore ack
07-17 13:38:47.484  9764  9777 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
,07-17 13:38:47.488  9764  9784 D BluetoothPanServiceJni: control_state_callback(L64): state:0, local_role:3, ifname:bt-pan
,07-17 13:38:47.490  9764  9777 D BluetoothAdapterProperties: ScanMode =  20
07-17 13:38:47.490  9764  9777 D BluetoothAdapterProperties: State =  11
,07-17 13:38:47.493  4626  6629 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
07-17 13:38:47.496  3704  4183 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
07-17 13:38:47.497  3704  4183 D SecContentProvider: called from android.uid.bluetooth:1002
07-17 13:38:47.500  3704  5299 D SecContentProvider: insert(), uri = 2
07-17 13:38:47.501  3704  5299 D SecContentProvider: called from android.uid.bluetooth:1002
07-17 13:38:47.502  9764  9777 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-17 13:38:47.502  9764  9777 D BluetoothAdapterService: [VendorCapa] prevState: 11, newState: 12
07-17 13:38:47.503  9764  9777 I bt_btif : vsc_getvendorcapabilities
07-17 13:38:47.503  9764  9777 D BluetoothAdapterService: Bluetooth PBAP supported is true
07-17 13:38:47.505  9764  9784 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
07-17 13:38:47.507  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
07-17 13:38:47.511  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:47.513  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:47.514  9623  9623 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
07-17 13:38:47.519  3704  3812 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-17 13:38:47.519  9764  9777 D BluetoothAdapterService: Autoconnection is available 
07-17 13:38:47.520  9764  9777 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-17 13:38:47.520  9764  9777 D BluetoothAdapterService: starting service from this receiver
07-17 13:38:47.535  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:47.536  4070  7052 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
07-17 13:38:47.540  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:47.541  9726  9738 D BluetoothSap: onBluetoothStateChange: up=true
07-17 13:38:47.541  9726  9738 D BluetoothSap: Binding service...
,07-17 13:38:47.543  9623  9623 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-17 13:38:47.547  9764  9777 I BluetoothAdapterState: Entering OnState
,07-17 13:38:47.553  9764  9764 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
07-17 13:38:47.552  4670  4687 D BluetoothAdapter: onBluetoothStateChange: up=true
07-17 13:38:47.553  4670  4687 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-17 13:38:47.555  9726  9737 D BluetoothPan: onBluetoothStateChange on: true
07-17 13:38:47.555  9764  9784 W bt_btif : btif_dm_generic_evt: event=34050
07-17 13:38:47.555  9764  9784 D BluetoothAdapterProperties: [VendorCapa] : mDbfwSupported: 1 , mA2dpLinkFeedbackSupported: 1
07-17 13:38:47.558  9623  9623 D BluetoothAdapter: STATE_ON
,07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:47.564  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-17 13:38:47.564  4070  4349 D BluetoothPan: onBluetoothStateChange on: true
07-17 13:38:47.564  9764  9785 D A2dpStateMachine: getConnectedDevices : size=0
,07-17 13:38:47.569  9623  9623 D BluetoothAdapter: STATE_ON
,07-17 13:38:47.571  4070  4087 D BluetoothMap: onBluetoothStateChange: up=true
,07-17 13:38:47.574  9623  9623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,07-17 13:38:47.576  9726  9726 D BluetoothSap: Proxy object connected
07-17 13:38:47.576  9764  9764 I BluetoothPbapService: Handler(): got msg=1
07-17 13:38:47.576  9726  9726 D SapProfile: Bluetooth service connected
,07-17 13:38:47.578  4070  4348 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-17 13:38:47.579  9764  9840 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-17 13:38:47.581  4070  4070 D BluetoothPan: BluetoothPAN Proxy object connected
07-17 13:38:47.581  4070  4070 D PanProfile: Bluetooth service connected
,07-17 13:38:47.583  9726  9726 D BluetoothPan: BluetoothPAN Proxy object connected
07-17 13:38:47.583  9726  9726 D PanProfile: Bluetooth service connected
,07-17 13:38:47.585  4070  4087 D BluetoothSap: onBluetoothStateChange: up=true
,07-17 13:38:47.585  9764  9840 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:38:47.585  4070  4087 D BluetoothSap: Binding service...
07-17 13:38:47.585  9764  9840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:38:47.589  9764  9840 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-17 13:38:47.589  4070  4070 D A2dpProfile: Bluetooth service connected
,07-17 13:38:47.594  9764  9785 D A2dpStateMachine: getConnectedDevices : size=0
,07-17 13:38:47.594  4070  4070 D BluetoothMap: Proxy object connected
07-17 13:38:47.594  4070  4070 D MapProfile: Bluetooth service connected
07-17 13:38:47.594  4070  4070 D BluetoothMap: getConnectedDevices()
07-17 13:38:47.595  9623  9739 D BluetoothAdapter: onBluetoothStateChange: up=true
07-17 13:38:47.595  9623  9739 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-17 13:38:47.595  4070  4233 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-17 13:38:47.599  4070  4070 D BluetoothSap: Proxy object connected
07-17 13:38:47.599  4070  4070 D SapProfile: Bluetooth service connected
,07-17 13:38:47.601  4044  4056 D BluetoothAdapter: onBluetoothStateChange: up=true
07-17 13:38:47.601  4044  4056 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-17 13:38:47.601  7445  7457 D BluetoothAdapter: onBluetoothStateChange: up=true
,07-17 13:38:47.601  7445  7457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-17 13:38:47.602  9726  9738 D BluetoothAdapter: onBluetoothStateChange: up=true
07-17 13:38:47.602  9726  9738 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-17 13:38:47.602  4070  4070 D BluetoothInputDevice: Proxy object connected
07-17 13:38:47.602  4070  4070 D HidProfile: Bluetooth service connected
07-17 13:38:47.603  9764  9775 D BluetoothAdapter: onBluetoothStateChange: up=true
07-17 13:38:47.603  9764  9775 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-17 13:38:47.603  3704  3812 D BluetoothAdapter: onBluetoothStateChange: up=true
07-17 13:38:47.603  3704  3812 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-17 13:38:47.603  4070  4349 D BluetoothAdapter: onBluetoothStateChange: up=true
07-17 13:38:47.603  4070  4349 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,07-17 13:38:47.604  4626  7729 D BluetoothAdapter: onBluetoothStateChange: up=true
07-17 13:38:47.604  4626  7729 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
07-17 13:38:47.605  4070  4348 D BluetoothPbap: onBluetoothStateChange: up=true
,07-17 13:38:47.612  3704  3704 D Telecom : SecBluetoothManager : register BluetoothHeadset after STATE_ON : null
07-17 13:38:47.612  3704  3704 D Telecom : SecBluetoothManager : registerBluetoothHeadsetMessageListener fail
,07-17 13:38:47.613  3704  3704 D BluetoothPhoneService: Bluetooth Adapter state : 12
,07-17 13:38:47.613  3704  3704 I BluetoothPhoneService: queryPhoneState
,07-17 13:38:47.613  3704  3704 I BluetoothPhoneService: updateHeadsetWithCallState : true
07-17 13:38:47.616  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
07-17 13:38:47.616  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:47.616  3704  3704 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
07-17 13:38:47.618  4070  4357 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:47.618  4070  4357 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
07-17 13:38:47.619  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
07-17 13:38:47.621  9726  9726 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:47.621  9726  9726 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,07-17 13:38:47.626  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:47.631  4070  4070 D BluetoothPbap: Proxy object connected
07-17 13:38:47.631  4070  4070 D PbapServerProfile: Bluetooth service connected
,07-17 13:38:47.632  3704  3920 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{c247c74: PendingIntentRecord{f2c859d com.google.android.gms broadcastIntent}}
,07-17 13:38:47.633  9764  9764 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:47.633  9764  9764 D PanService: BT STATE ON
07-17 13:38:47.633  9726  9726 E BluetoothEventManager: unregisterProfileIntentReceiver :: mProfileConnectionReceiver was not registered.
07-17 13:38:47.633  9726  9726 D LocalBluetoothProfileManager: Adding local A2DP profile
07-17 13:38:47.633  9764  9764 D EnhancedTetheringManager: EnhancedTetheringManager()
07-17 13:38:47.633  9764  9764 D EnhancedTetheringManager: start
,07-17 13:38:47.635  4070  4357 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
07-17 13:38:47.635  4070  4357 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
07-17 13:38:47.635  4070  4357 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
07-17 13:38:47.635  4070  4357 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
07-17 13:38:47.635  4070  4357 W LocalBluetoothProfileManager: updateLocalProfiles :: Spp profile was created already 
,07-17 13:38:47.640  9764  9764 D ETMLeHelper: ETMLeHelper()
07-17 13:38:47.640  9764  9764 D ETMLeHelper: initTetherAdv
,07-17 13:38:47.644  9726  9726 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,07-17 13:38:47.649  9726  9726 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-17 13:38:47.652  9726  9726 E BluetoothHeadset: BTStateChangeCB is registed
07-17 13:38:47.652  9764  9764 D BluetoothAdapter: STATE_ON
07-17 13:38:47.653  9764  9764 D BluetoothAdapter: STATE_ON
07-17 13:38:47.654  9764  9764 D BluetoothAdapter: STATE_ON
07-17 13:38:47.655  9726  9726 D BluetoothMap: Create BluetoothMap proxy object
,07-17 13:38:47.661  9764  9764 D BluetoothAdapter: isSecureModeEnabled
07-17 13:38:47.661  9764  9764 D BtConfig.SecureMode: isSecureModeOn:false
,07-17 13:38:47.662  9764  9764 D ETMLeHelper: initTetherScan
,07-17 13:38:47.663  9764  9764 D BluetoothAdapter: STATE_ON
07-17 13:38:47.664  9764  9764 D BluetoothAdapter: STATE_ON
,07-17 13:38:47.667  9764  9764 D BluetoothMapUtils: [RCS] imsConfigCscFeatures : , enableCpmFeature : false
07-17 13:38:47.667  9764  9764 D BluetoothMapUtils: mRcsSupported : false
,07-17 13:38:47.674  3704  4338 D MountService: getExternalStorageMountMode : 1
07-17 13:38:47.674  3704  4338 D MountService: getExternalStorageMountMode : 3
07-17 13:38:47.674  3704  4338 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,07-17 13:38:47.702  9843  9843 E Zygote  : v2
07-17 13:38:47.702  9843  9843 I libpersona: KNOX_SDCARD checking this for 10049
07-17 13:38:47.702  9843  9843 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:47.702  9843  9843 E Zygote  : isSdpEnabledProcess - SDP enabled
,07-17 13:38:47.703  9843  9843 E Zygote  : accessInfo : 64
07-17 13:38:47.703  9843  9843 E Zygote  : isSdpEnabledProcess - SDP enabled
07-17 13:38:47.703  9843  9843 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,07-17 13:38:47.710  3704  4338 I ActivityManager: Start proc 9843:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,07-17 13:38:47.712  9726  9726 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,07-17 13:38:47.714  9843  9843 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:47.716  9843  9843 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
,07-17 13:38:47.718  9726  9726 D LocalBluetoothProfileManager: Adding local Spp profile
,07-17 13:38:47.734  9726  9726 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-17 13:38:47.740  9843  9843 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:47.741  9843  9843 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:47.742  9726  9726 D A2dpProfile: Bluetooth service connected
,07-17 13:38:47.746  3704  4182 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,07-17 13:38:47.753  9764  9786 D A2dpStateMachine: getConnectedDevices : size=0
,07-17 13:38:47.755  9726  9726 D BluetoothMap: Proxy object connected
07-17 13:38:47.755  9726  9726 D MapProfile: Bluetooth service connected
,07-17 13:38:47.755  9726  9726 D BluetoothMap: getConnectedDevices()
,07-17 13:38:47.760  9726  9726 D BluetoothPbap: Proxy object connected
,07-17 13:38:47.761  9726  9726 D PbapServerProfile: Bluetooth service connected
,07-17 13:38:47.761  9726  9726 D BluetoothInputDevice: Proxy object connected
07-17 13:38:47.762  9726  9726 D HidProfile: Bluetooth service connected
,07-17 13:38:47.770  9726  9726 D DockEventReceiver: finishStartingService: stopping service
,07-17 13:38:47.781  9843  9843 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
,07-17 13:38:47.801  9843  9843 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:47.816  3704  4183 D RCPManagerService: exchangeData() failure , invalid userId
,07-17 13:38:47.837  9843  9843 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
07-17 13:38:47.838  9843  9843 I QBNRClientHelper: init SyncClientHelper : Email
07-17 13:38:47.838  9843  9843 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : EMAILFOLDER, 55LAYJm0O2, com.samsung.android.email.provider.service.sCloudBNRService2
07-17 13:38:47.838  9843  9843 I QBNRClientHelper: init SyncClientHelper : EMAILFOLDER
,07-17 13:38:47.872  3704  4328 D RCPManagerService: exchangeData() failure , invalid userId
,07-17 13:38:47.878  9843  9858 D skia    : ---- fAsset->read(8192) returned 0
07-17 13:38:47.878  9843  9858 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-17 13:38:47.883  9843  9843 D SamsungAnalytics:1.8.25: cf feature is supported
,07-17 13:38:47.888  9843  9858 D skia    : ---- fAsset->read(8192) returned 0
07-17 13:38:47.888  9843  9858 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-17 13:38:47.890  9843  9858 D skia    : ---- fAsset->read(8192) returned 0
,07-17 13:38:47.890  9843  9858 D skia    : --- SkAndroidCodec::NewFromStream returned null
,07-17 13:38:47.893  9843  9843 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
,07-17 13:38:47.897  3704  4752 D MountService: getExternalStorageMountMode : 1
07-17 13:38:47.897  3704  4752 D MountService: getExternalStorageMountMode : 3
07-17 13:38:47.897  3704  4752 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,07-17 13:38:47.917  9862  9862 E Zygote  : v2
07-17 13:38:47.917  9862  9862 I libpersona: KNOX_SDCARD checking this for 10049
07-17 13:38:47.917  9862  9862 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:47.917  9862  9862 E Zygote  : isSdpEnabledProcess - SDP enabled
07-17 13:38:47.918  3704  4752 I ActivityManager: Start proc 9862:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
,07-17 13:38:47.918  9862  9862 E Zygote  : accessInfo : 64
07-17 13:38:47.918  9862  9862 E Zygote  : isSdpEnabledProcess - SDP enabled
07-17 13:38:47.918  9862  9862 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
,07-17 13:38:47.923  9862  9862 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:47.924  9862  9862 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
,07-17 13:38:47.947  9862  9862 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:47.948  9862  9862 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:47.952  3704  3920 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,07-17 13:38:47.976  3704  3714 I art     : Background partial concurrent mark sweep GC freed 128760(14MB) AllocSpace objects, 11(220KB) LOS objects, 28% free, 40MB/56MB, paused 2.144ms total 203.456ms
07-17 13:38:47.977  9623  9724 D BluetoothAdapter: STATE_ON
07-17 13:38:47.982  9862  9862 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
,07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:47.982  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-17 13:38:47.984  9623  9687 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,07-17 13:38:47.985  9764  9764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:47.986  9764  9764 D BtConfig.SecureMode: isSecureModeOn:false
,07-17 13:38:47.990  3704  5299 D WifiService: setWifiEnabled: false pid=9623, uid=10033
,07-17 13:38:47.992  4070  4070 D HeadsetProfile: Bluetooth service connected
07-17 13:38:47.993  3704  3704 I BluetoothPhoneService: updateHeadsetWithCallState : true
07-17 13:38:47.994  9726  9726 D HeadsetProfile: Bluetooth service connected
07-17 13:38:47.994  9862  9862 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-17 13:38:47.996  3704  5299 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-17 13:38:47.997  9764  9822 D HeadsetStateMachine: Disconnected process message: 9, size: 0
07-17 13:38:47.998  9764  9822 D A2dpSinkService: getA2dpSinkService(): service is NULL
07-17 13:38:47.998  9764  9822 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-17 13:38:48.003  3278  3278 D audio_hw_primary: adev_set_parameters: enter: kvpairs: A2dpSuspended=false
07-17 13:38:48.004  9764  9822 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-17 13:38:48.008  9764  9829 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
,07-17 13:38:48.009  9726  9726 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
07-17 13:38:48.009  9726  9726 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,07-17 13:38:48.017  3704  5299 D WifiControlHistoryProvider: query
07-17 13:38:48.022  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:48.022  9764  9829 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:38:48.022  9764  9829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:38:48.023  3704  3704 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.bluetooth.SecBluetoothMessageListener@2784741
07-17 13:38:48.023  3704  3704 D BluetoothHeadset: registerMessageListener
,07-17 13:38:48.024  9764  9764 V BtOppService: isOwner == true
07-17 13:38:48.025  9764  9879 D BluetoothSocket: bindListen(): myUserId = 0
,07-17 13:38:48.025  9764  9879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:38:48.028  9764  9786 D HeadsetService: registerMessageListener
07-17 13:38:48.029  9764  9879 D BluetoothSdpJni: sdpCreateSapsRecordNative:
07-17 13:38:48.029  9764  9879 D BluetoothSdpJni: SDP Create record success - handle: 0
07-17 13:38:48.029  9764  9786 D HeadsetService: registerMessageListener
07-17 13:38:48.031  9764  9822 D HeadsetStateMachine: Disconnected process message: 70, size: 0
07-17 13:38:48.031  3704  3704 I Telecom : SecBluetoothManager : register MessageListener
07-17 13:38:48.031  9764  9822 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@7491d02
07-17 13:38:48.040  9764  9829 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:38:48.040  9764  9829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:38:48.043  3704  5299 D WifiNative-wlan0: callSECApiVoid - ID [312]
07-17 13:38:48.043  3704  4017 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
07-17 13:38:48.047  3704  5299 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-17 13:38:48.051  3704  5299 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:48.051  3704  5299 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:48.053  3704  6348 D RCPManagerService: exchangeData() failure , invalid userId
07-17 13:38:48.054  3704  5299 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-17 13:38:48.055  3704  3930 D SecContentProvider: insert(), uri = 2
07-17 13:38:48.056  3704  3930 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:48.057  3704  3930 D SecContentProvider: insert(), uri = 2
07-17 13:38:48.060  9862  9880 D skia    : ---- fAsset->read(8192) returned 0
07-17 13:38:48.060  9862  9880 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-17 13:38:48.063  3704  3930 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:48.064  3704  3931 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-17 13:38:48.066  3704  3931 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@5e58d47
07-17 13:38:48.067  3704  5299 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-17 13:38:48.068  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133849, SetElapsed=200308, nowELAPSED=198811
07-17 13:38:48.068  3704  3931 D WifiStateMachine: isFindLocationId() - Location Id : 1
07-17 13:38:48.068  3704  3931 D WifiStateMachine: ConnectedState - exit() - stopLearning id : 1
07-17 13:38:48.068  3704  5299 D SecContentProvider: called from android.uid.bluetooth:1002
07-17 13:38:48.068  3704  3931 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-17 13:38:48.069  9862  9880 D skia    : ---- fAsset->read(8192) returned 0
07-17 13:38:48.070  9862  9880 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-17 13:38:48.071  3704  3704 I Telecom : SecBluetoothManager : not single connected gear
07-17 13:38:48.071  9862  9880 D skia    : ---- fAsset->read(8192) returned 0
07-17 13:38:48.071  9862  9880 D skia    : --- SkAndroidCodec::NewFromStream returned null
07-17 13:38:48.073  9862  9862 D SamsungAnalytics:1.8.25: cf feature is supported
,07-17 13:38:48.074  3704  3931 D SLocation: system
07-17 13:38:48.075  3704  3931 D SLocation: stopLearning ID = 1
07-17 13:38:48.075  3704  3931 D SLocation: setLearningStatus ID = 1 / status = false
07-17 13:38:48.075  3704  3704 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
07-17 13:38:48.075  3704  3704 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-17 13:38:48.076  3704  3931 D SecContentProvider: insert(), uri = 2
,07-17 13:38:48.077  3704  4366 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ADA_0
,07-17 13:38:48.077  3704  4366 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ADA_0
,07-17 13:38:48.081  9862  9862 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
07-17 13:38:48.083  9764  9887 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:38:48.083  9764  9887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:38:48.083  9764  9829 D ObexServerSockets: Succeed to create listening sockets 
07-17 13:38:48.083  9764  9829 D ObexServerSockets: startAccept()
07-17 13:38:48.084  3704  3931 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:48.084  3704  3931 D WifiStateMachine: Wifi got Disconnected in connectedstate, Send provisioning intent mAutoRoamingfalse
07-17 13:38:48.084  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiStateMachine$ConnectedState.exit:11809 com.android.internal.util.StateMachine$SmHandler.invokeExitMethods:1009 com.android.internal.util.StateMachine$SmHandler.performTransitions:865 com.android.internal.util.StateMachine$SmHandler.handleMessage:809 
07-17 13:38:48.085  9764  9887 I BtOppRfcommListener: Accept thread started.
07-17 13:38:48.086  3704  3931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-17 13:38:48.088  3704  3936 D DhcpClient: doQuit
07-17 13:38:48.088  3704  3936 D ApfFilter: (wlan0): shutting down
07-17 13:38:48.090  3704  5163 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@3ce7f8d
07-17 13:38:48.090  9764  9891 D ObexServerSockets: Accepting socket connection for masId0
07-17 13:38:48.091  3704  5163 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@d833953
07-17 13:38:48.091  3704  5163 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@6ba38e
07-17 13:38:48.092  3704  3927 D WifiP2pService: InactiveState{ what=143375 }
07-17 13:38:48.092  3704  3927 D WifiP2pService: P2pEnabledState{ what=143375 }
07-17 13:38:48.093  3704  5163 D DhcpClient: onQuitting
07-17 13:38:48.093  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:48.093  3704  3963 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-17 13:38:48.093  3704  4017 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-17 13:38:48.093  3704  3963 D ConnectivityService: ignoring duplicate network state non-change
07-17 13:38:48.093  3704  3963 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 12
07-17 13:38:48.094  9764  9892 D ObexServerSockets: Accepting socket connection for masId0
07-17 13:38:48.095  3704  3963 V NetworkStats: updateIfacesLocked()
07-17 13:38:48.095  3704  3963 V NetworkStats: performPollLocked(flags=0x1)
07-17 13:38:48.095  3704  3963 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:48.097  3704  3931 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-17 13:38:48.097  3704  3931 I WifiConnectivityManager: Set WiFi disabled
07-17 13:38:48.097  3704  3931 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@1235601
,07-17 13:38:48.097  3704  3931 I WifiStateMachine: deinitGeofence
07-17 13:38:48.094  9764  9829 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-17 13:38:48.099  9764  9829 D BluetoothSdpJni: SDP Create record success - handle: 1
07-17 13:38:48.103  3704  3704 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-17 13:38:48.105  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-17 13:38:48.106  3704  3704 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
07-17 13:38:48.107  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-17 13:38:48.107  3704  3959 I WifiHs20Service: Message received 5007
07-17 13:38:48.112  3704  4366 I Telecom : SecBluetoothManager : not single connected gear
07-17 13:38:48.112  3704  4366 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ADA_0
,07-17 13:38:48.116  3704  3963 V NetworkStats: performPollLocked() took 21ms
,07-17 13:38:48.116  3704  3963 D NtpTrustedTime: currentTimeMillis() cache hit
,07-17 13:38:48.121  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-17 13:38:48.122  3704  3931 D SLocation: stopGeofence ID = 1
,07-17 13:38:48.123  9764  9764 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-17 13:38:48.126  3704  4017 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-17 13:38:48.126  3704  3704 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-17 13:38:48.133  3704  3963 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-17 13:38:48.133  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-17 13:38:48.133  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
,07-17 13:38:48.133  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:48.134  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.134  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.134  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.134  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.134  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:48.134  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:48.122  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-17 13:38:48.134  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.134  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.135  3704  4015 D DnsEventListenerService: Logging 42 results for netId 502
07-17 13:38:48.135  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.136  4294  4420 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [false]
07-17 13:38:48.138  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.138  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.138  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.139  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-17 13:38:48.139  3704  3812 D EntConnectivity: Not allowed due to - mEnabled false
07-17 13:38:48.139  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:48.139  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.139  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.139  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:48.140  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:48.140  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:48.140  3704  3963 D ConnectivityService: sending notification LOST for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:48.141  3704  3963 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.141  3704  5126 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-17 13:38:48.141  3704  5126 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: unregister CaptivePortalReceiver
07-17 13:38:48.142  4044  4044 D PhoneSwitcherNetworkRequstListener: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.142  4044  4044 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-17 13:38:48.142  4044  4044 D PhoneSwitcherNetworkRequstListener: evalRequest
07-17 13:38:48.142  4044  4044 D PhoneSwitcherNetworkRequstListener:   done
07-17 13:38:48.142  3704  4026 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.143  3704  4026 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-17 13:38:48.143  3704  4026 D Ethernet: evalRequest
07-17 13:38:48.143  3704  4026 D Ethernet:   done
07-17 13:38:48.143  3704  3927 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.143  3704  3927 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-17 13:38:48.143  3704  3927 D WIFI_P2P: evalRequest
07-17 13:38:48.143  3704  3927 D WIFI_P2P:   done
07-17 13:38:48.145  4294  4435 D PdnController: handleMessage: what 106
,07-17 13:38:48.145  4294  4420 D GeolocationController: WIFI : onLost
07-17 13:38:48.146  4294  4435 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [false]
07-17 13:38:48.146  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:48.146  4294  4435 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [false]
07-17 13:38:48.146  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:48.148  4294  4435 D ResipRegiMgr: handleMessage(): 3
07-17 13:38:48.148  4294  4435 D RegiMgrBase: handleMessage: what 3
,07-17 13:38:48.164  3246  3246 E audit   : type=1320 audit(1500291528.151:232): 
,07-17 13:38:48.181  3246  3246 E audit   : type=1320 audit(1500291528.171:233): 
,07-17 13:38:48.182  3300  3777 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-17 13:38:48.184  3704  3931 E SLocation: pendingIntent set to null
07-17 13:38:48.184  3704  3931 D SLocation: setStatus ID = 1 / status = 0
07-17 13:38:48.184  3704  3931 D SLocation: updateSession : trigger = false
07-17 13:38:48.184  3704  3931 D SLocation: updateSession : mSessionStatus = 0
,07-17 13:38:48.184  3704  3931 D WifiStateMachine:  stopGeofence() - id : 1
07-17 13:38:48.185  3704  4257 D SLocation: Session stopped
07-17 13:38:48.185  3704  4257 D SLocation: triggerAlarm
07-17 13:38:48.185  3704  4257 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / op:PendingIntent{8ed91e1: PendingIntentRecord{49fdb06 android broadcastIntent}}
07-17 13:38:48.185  3704  4257 D SLocation: All alarm stopped
07-17 13:38:48.186  3704  3931 D wifi    : android_net_wifi_reset_alert_handler = 0x7d116b69a0
,07-17 13:38:48.186  3704  3931 E WifiHAL : failed to request reset; result = -95
07-17 13:38:48.186  3704  3931 D wifi    : android_net_wifi_reset_log_handler = 0x7d116b69a0
07-17 13:38:48.186  3704  3931 I WifiHAL : Failed to remove command 1: 0x0
07-17 13:38:48.186  3704  3931 D WifiHAL : Success to clear alerthandler
,07-17 13:38:48.194  3246  3246 E audit   : type=1320 audit(1500291528.181:234): 
,07-17 13:38:48.206  3246  3246 E audit   : type=1320 audit(1500291528.191:235): 
,07-17 13:38:48.206  3300  3777 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-17 13:38:48.209  3704  3963 D ConnectivityService: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
07-17 13:38:48.209  3704  3963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-17 13:38:48.215  3704  3812 D EntConnectivity: Not allowed due to - mEnabled false
,07-17 13:38:48.216  3300  3777 D CommandListener: Clearing all IP addresses on wlan0
,07-17 13:38:48.256  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-17 13:38:48.263  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-17 13:38:48.263  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-17 13:38:48.298  4626  6684 V NativeCrypto: Read error: ssl=0x7d2dd42780: I/O error during system call, Software caused connection abort
07-17 13:38:48.298  3300  3769 I Netd    : Destroyed 18 sockets on 192.168.1.105 in 1.4 ms
07-17 13:38:48.300  3704  6347 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BleCentralService newState = 1 callingPackage = 10019
07-17 13:38:48.303  4626  6684 V NativeCrypto: SSL shutdown failed: ssl=0x7d2dd42780: I/O error during system call, Broken pipe
,07-17 13:38:48.309  3704  5299 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BlePeripheralService newState = 1 callingPackage = 10019
07-17 13:38:48.310  3704  3931 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-17 13:38:48.310  3704  3931 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.310  3704  3931 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-17 13:38:48.310  3704  3931 D WIFI_UT : evalRequest
07-17 13:38:48.310  3704  3931 D WIFI_UT :   done
07-17 13:38:48.310  3704  3931 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:48.310  3704  3931 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-17 13:38:48.310  3704  3931 D WIFI    : evalRequest
07-17 13:38:48.310  3704  3931 D WIFI    :   needNetworkFor
,07-17 13:38:48.310  3704  3927 D WifiP2pService: InactiveState{ what=131204 }
07-17 13:38:48.311  4989  6649 I Authzen : [PermitStore] Getting all permits...
07-17 13:38:48.311  3704  3927 D WifiP2pService: P2pEnabledState{ what=131204 }
07-17 13:38:48.318  3704  3961 I WifiScanningService: wifi driver unloaded
07-17 13:38:48.319  3704  3961 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.scanner.SupplicantWifiScannerImpl$2@6cd9d79
07-17 13:38:48.320  3704  3704 D RttService: SCAN_AVAILABLE : 1
07-17 13:38:48.321  3704  3962 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-17 13:38:48.325  4251  4251 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
07-17 13:38:48.325  4251  4251 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
07-17 13:38:48.327  3704  3927 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-17 13:38:48.333  3704  3704 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-17 13:38:48.333  3704  3704 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = true
07-17 13:38:48.333  3704  3917 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-17 13:38:48.333  3704  3917 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-17 13:38:48.334  3704  3704 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-17 13:38:48.334  3704  3704 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-17 13:38:48.335  3704  3918 I KnoxVpnEngineService: vpn handle : Message received
07-17 13:38:48.335  3704  3918 I KnoxVpnEngineService: vpn handle : Message received
07-17 13:38:48.335  3704  3918 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = true
07-17 13:38:48.335  3704  3704 D Tethering: Tethering got CONNECTIVITY_ACTION
07-17 13:38:48.336  3704  3965 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-17 13:38:48.336  3704  3965 D Tethering: MasterInitialState.processMessage what=327683
07-17 13:38:48.336  3704  9906 I ApplicationPolicy: updateDataUsageMap
,07-17 13:38:48.341  3246  3246 E audit   : type=1320 audit(1500291528.331:236): 
,07-17 13:38:48.346  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-17 13:38:48.355  3704  3922 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
07-17 13:38:48.355  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:48.355  3246  3246 E audit   : type=1320 audit(1500291528.341:237): 
07-17 13:38:48.355  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:48.356  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:48.356  3704  3922 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-17 13:38:48.356  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
,07-17 13:38:48.357  3704  3922 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
07-17 13:38:48.358  4989  4989 I CastMediaRouteProvider: Network connectivity changed
,07-17 13:38:48.368  9147  9147 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
,07-17 13:38:48.369  9147  9147 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
,07-17 13:38:48.370  9199  9199 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@97e07b2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:48.374  3704  3759 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{1d1abe: PendingIntentRecord{dcd4f14 com.google.android.gms broadcastIntent}}
07-17 13:38:48.375  4626  6684 E GCM     : Wifi connection closed with errorCode 20
,07-17 13:38:48.389  3300  3777 E Netd    : netlink response contains error (No such file or directory)
,07-17 13:38:48.393  3704  3963 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED
,07-17 13:38:48.420  4070  4357 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
,07-17 13:38:48.420  4814  4814 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-17 13:38:48.422  3704  3813 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
,07-17 13:38:48.431  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:48.433  3704  3704 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-17 13:38:48.433  3704  4257 D SLocation: checkWifiInfo
07-17 13:38:48.433  3704  3704 V MARsPolicyManager: DataConnection: false
07-17 13:38:48.433  3704  4257 W SLocation: No Active Data Connection
07-17 13:38:48.433  3704  4257 W SLocation: No Active Data Connection
07-17 13:38:48.435  9147  9147 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
07-17 13:38:48.435  9147  9147 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-17 13:38:48.437  3704  3927 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-17 13:38:48.440  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-17 13:38:48.440  3704  3963 D ConnectivityService: ignoring duplicate network state non-change
07-17 13:38:48.443  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:48.444  3704  3813 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-17 13:38:48.444  3704  3813 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-17 13:38:48.444  3704  3813 D WifiDisplayController: disconnect
07-17 13:38:48.444  3704  3813 D WifiDisplayAdapter: onFeatureStateChanged empty
07-17 13:38:48.444  3704  3813 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-17 13:38:48.447  9199  9199 I NetworkConnectivity: Network state changed: null
07-17 13:38:48.449  9623  9623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
07-17 13:38:48.450  3704  3927 D SecContentProvider: insert(), uri = 2
07-17 13:38:48.451  3704  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-17 13:38:48.452  3704  3813 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: false, roaming: false, metered: false]
07-17 13:38:48.460  3704  3927 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:48.460  3704  3927 D WifiP2pService: P2pDisablingState
07-17 13:38:48.461  3704  3927 D WifiP2pService: P2pDisablingState{ what=147458 }
07-17 13:38:48.461  3704  3927 D WifiP2pService: p2p socket connection lost
07-17 13:38:48.462  3704  3927 D SecContentProvider: insert(), uri = 2
07-17 13:38:48.464  3704  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-17 13:38:48.464  3704  3927 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:48.465  3704  3931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-17 13:38:48.465  3704  3927 D WifiP2pService: P2pDisabledState
07-17 13:38:48.467  3704  3927 D WifiP2pService: ,P2pDisabledState{ what=143375 }
07-17 13:38:48.467  3704  3927 D WifiP2pService: DefaultState{ what=143375 }
07-17 13:38:48.471  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:48.472  3704  4017 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-17 13:38:48.474  3704  4338 D MountService: getExternalStorageMountMode : 1
07-17 13:38:48.474  3704  4338 D MountService: getExternalStorageMountMode : 3
07-17 13:38:48.474  3704  4338 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10003, packageName : com.sec.android.provider.badge
07-17 13:38:48.476  4626  6633 I BeaconBle: Client requested scan, settings=BleSettings [scanMode=LOW_LATENCY, callbackType=ALL_MATCHES, reportDelayMillis=0, 3 filters, 0 clients, callingClientName=Nearby], listener=hjz@fba5ae7
,07-17 13:38:48.489  4989  5738 W MdnsClient_Cast: Multicast lock held. Releasing. Subtypes:"805741C9"
07-17 13:38:48.495  4989  5738 W MdnsClient: unicast receiver thread is already dead.
,07-17 13:38:48.505  9914  9914 E Zygote  : v2
,07-17 13:38:48.505  9914  9914 I libpersona: KNOX_SDCARD checking this for 10003
,07-17 13:38:48.505  9914  9914 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:48.506  9914  9914 E Zygote  : accessInfo : 0
07-17 13:38:48.509  3704  4338 I ActivityManager: Start proc 9914:com.sec.android.provider.badge/u0a3 for broadcast com.sec.android.provider.badge/.BadgeCountReceiver
,07-17 13:38:48.514  9914  9914 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:48.515  9914  9914 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
07-17 13:38:48.517  9199  9199 I NetworkPolicyMonitor: Download-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
07-17 13:38:48.517  3704  3931 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
07-17 13:38:48.518  3704  3704 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-17 13:38:48.519  4251  4251 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-17 13:38:48.519  3704  3931 D SecContentProvider: insert(), uri = 2
07-17 13:38:48.520  3704  3931 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:48.523  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-17 13:38:48.525  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-17 13:38:48.525  3704  3959 I WifiHs20Service: Message received 5007
07-17 13:38:48.531  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-17 13:38:48.531  4626  6633 I BeaconBle: 'L' hardware scan: 3 filters, scanMode=2, reportdelay=0, callback type=1, #clients=1
07-17 13:38:48.532  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:48.534  9764  9764 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-17 13:38:48.535  9199  9199 I NetworkPolicyMonitor: Stream-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
07-17 13:38:48.537  9914  9914 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:48.537  9914  9914 D ActivityThread: Added TimaKeyStore provider
07-17 13:38:48.538  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-17 13:38:48.539  3704  3759 I ActivityManager: DSS on for com.sec.android.provider.badge and scale is 1.0
07-17 13:38:48.540  3704  4017 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-17 13:38:48.541  4626  6633 I BeaconBle: Starting scan on delegate scanner - BT state: 12
,07-17 13:38:48.541  4626  6633 D BluetoothLeScanner: Start Scan
,07-17 13:38:48.545  4626  6633 D BluetoothAdapter: STATE_ON
,07-17 13:38:48.546  4626  6633 D BluetoothAdapter: STATE_ON
,07-17 13:38:48.548  4626  6633 D BluetoothAdapter: STATE_ON
,07-17 13:38:48.550  4626  6633 D BluetoothAdapter: STATE_ON
,07-17 13:38:48.554  9764  9841 D BtGatt.GattService: registerClient() - UUID=4a2e734d-fcb0-401b-a1e9-269b75de0837
,07-17 13:38:48.559  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-17 13:38:48.560  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-17 13:38:48.560  3704  3959 I WifiHs20Service: Message received 5011
07-17 13:38:48.562  9623  9724 D BluetoothAdapter: STATE_ON
07-17 13:38:48.563  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135173 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-17 13:38:48.565  9914  9914 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_N/lib/arm64
,07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-17 13:38:48.567  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-17 13:38:48.567  3704  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-17 13:38:48.568  3704  3704 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,07-17 13:38:48.569  3704  4257 D SLocation: checkWifiInfo
07-17 13:38:48.570  3704  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-17 13:38:48.571  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-17 13:38:48.571  3704  6347 D WifiService: setWifiEnabled: true pid=9623, uid=10033
07-17 13:38:48.572  9623  9687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:48.573  3300  3772 D EnterpriseController: netId is 0
07-17 13:38:48.573  3300  3772 D Netd    : getNetworkForDns: using netid 0 for uid 10001
07-17 13:38:48.573  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-17 13:38:48.574  9914  9914 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-17 13:38:48.576  3704  3704 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
07-17 13:38:48.578  9914  9914 D BadgeProvider: onCreate
07-17 13:38:48.578  9914  9914 D BadgeProvider: DatabaseHelper
07-17 13:38:48.583  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-17 13:38:48.587  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-17 13:38:48.587  3300  3769 D Netd    : Iface p2p0 link up
07-17 13:38:48.590  3704  3811 D Tethering: interfaceLinkStateChanged p2p0, true
07-17 13:38:48.590  3704  3811 D Tethering: interfaceStatusChanged p2p0, true
07-17 13:38:48.591  3704  6347 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-17 13:38:48.591  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:48.591  3704  6347 D WifiControlHistoryProvider: query
07-17 13:38:48.594  9623  9623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
07-17 13:38:48.594  9914  9914 D BadgeCountReceiver: badge intent : Intent { act=com.sec.intent.action.BADGE_COUNT_UPDATE flg=0x10 cmp=com.sec.android.provider.badge/.BadgeCountReceiver launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:48.594  9914  9914 D BadgeCountReceiver: packageName: com.samsung.android.email.provider, className: com.samsung.android.email.ui.activity.MessageListXL, count: 0
07-17 13:38:48.596  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:48.598  9914  9914 D BadgeProvider: onOpen
07-17 13:38:48.599  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:48.599  3704  6347 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-17 13:38:48.599  4626  6629 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
07-17 13:38:48.600  3704  6347 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:48.600  3704  6347 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:48.602  3704  6347 I WifiService: Wi-Fi Sharing settings has not been accessed
07-17 13:38:48.603  3704  6347 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-17 13:38:48.604  3704  3930 D SecContentProvider: insert(), uri = 2
07-17 13:38:48.604  3704  3930 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:48.605  3704  3930 D SecContentProvider: insert(), uri = 2
07-17 13:38:48.605  3704  3930 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:48.606  9199  9199 I DevicePlayback: Got network change: mobile=falsewifi=false
07-17 13:38:48.606  9914  9914 D BaseReflect: null getOwnClass TEST
07-17 13:38:48.606  9914  9914 D MethodReflector: android.content.ContentResolver getClass TEST
07-17 13:38:48.606  9914  9914 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
07-17 13:38:48.606  9914  9914 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,07-17 13:38:48.607  9199  9199 I DevicePlayback: Disabling Woodstock in 200000ms
07-17 13:38:48.608  9914  9914 D MethodReflector: notifyChange is called
07-17 13:38:48.608  4799  4799 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
07-17 13:38:48.609  9914  9914 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
07-17 13:38:48.609  9914  9914 D BadgeProvider: sendNotify, [notify] : null
07-17 13:38:48.609  4799  4799 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
07-17 13:38:48.609  9914  9914 D BadgeProvider: update, getCallingPackage() : com.sec.android.provider.badge
07-17 13:38:48.609  9914  9914 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
07-17 13:38:48.609  9914  9914 D BadgeProvider: update, [uri.query] : null
07-17 13:38:48.609  9914  9914 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-17 13:38:48.609  9914  9914 D BadgeProvider: update, [UpdateCount] : 1
07-17 13:38:48.611  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:48.611  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:48.611  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:48.611  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:48.611  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:48.611  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:48.611  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:48.612  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:48.612  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:48.612  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:48.618  5104  9913 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
07-17 13:38:48.618  5104  9913 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-17 13:38:48.618  5104  9913 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-17 13:38:48.618  5104  9913 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-17 13:38:48.618  5104  9913 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-17 13:38:48.618  5104  9913 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-17 13:38:48.618  5104  9913 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-17 13:38:48.618  5104  9913 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-17 13:38:48.618  5104  9913 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-17 13:38:48.618  5104  9913 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-17 13:38:48.618  5104  9913 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-17 13:38:48.618  5104  9913 E         : 	at java.lang.Thread.run(Thread.java:762)
07-17 13:38:48.618  5104  9913 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-17 13:38:48.618  5104  9913 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-17 13:38:48.618  5104  9913 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-17 13:38:48.618  5104  9913 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.intern,al.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-17 13:38:48.618  5104  9913 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-17 13:38:48.618  5104  9913 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-17 13:38:48.618  5104  9913 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-17 13:38:48.618  5104  9913 E         : 	... 9 more
07-17 13:38:48.618  5104  9913 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-17 13:38:48.618  5104  9913 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
07-17 13:38:48.618  5104  9913 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-17 13:38:48.618  5104  9913 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-17 13:38:48.618  5104  9913 E         : 	... 26 more
07-17 13:38:48.618  5104  9913 E         : 
,07-17 13:38:48.618  4814  6503 W art     : Verification of int org.chromium.net.AndroidCellularSignalStrength.getSignalStrengthDbm(android.content.Context) took 105.084ms
07-17 13:38:48.620  5104  9913 E         : Unable to fetch advertisement frequency.
07-17 13:38:48.620  5104  9913 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-17 13:38:48.620  5104  9913 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
07-17 13:38:48.620  5104  9913 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
07-17 13:38:48.620  5104  9913 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
07-17 13:38:48.620  5104  9913 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
07-17 13:38:48.620  5104  9913 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
07-17 13:38:48.620  5104  9913 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-17 13:38:48.620  5104  9913 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
07-17 13:38:48.620  5104  9913 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
07-17 13:38:48.620  5104  9913 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
07-17 13:38:48.620  5104  9913 E         : 	at java.lang.Thread.run(Thread.java:762)
07-17 13:38:48.620  5104  9913 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
07-17 13:38:48.620  5104  9913 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
07-17 13:38:48.620  5104  9913 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
07-17 13:38:48.620  5104  9913 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
07-17 13:38:48.620  5104  9913 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
07-17 13:38:48.620  5104  9913 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
07-17 13:38:48.620  5104  9913 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
07-17 13:38:48.620  5104  9913 E         : 	... 9 more
07-17 13:38:48.620  5104  9913 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
07-17 13:38:48.620  5104  9913 E         : 	at libcore.io.Posix.androi,d_getaddrinfo(Native Method)
07-17 13:38:48.620  5104  9913 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
07-17 13:38:48.620  5104  9913 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
07-17 13:38:48.620  5104  9913 E         : 	... 26 more
07-17 13:38:48.620  5104  9913 E         : 
,07-17 13:38:48.623  9726  9726 I WifiApBroadcastReceiver: onReceive: action com.samsung.intent.action.START_PROVISIONING userID :0
,07-17 13:38:48.629  3704  4752 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-17 13:38:48.632  3704  4182 D MountService: getExternalStorageMountMode : 1
07-17 13:38:48.632  3704  4182 D MountService: getExternalStorageMountMode : 3
07-17 13:38:48.632  3704  4182 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10106, packageName : com.enhance.gameservice
,07-17 13:38:48.646  4251  4251 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-17 13:38:48.648  9932  9932 E Zygote  : v2
07-17 13:38:48.648  9932  9932 I libpersona: KNOX_SDCARD checking this for 10106
07-17 13:38:48.648  9932  9932 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:48.649  9932  9932 E Zygote  : accessInfo : 0
07-17 13:38:48.650  3704  4182 I ActivityManager: Start proc 9932:com.enhance.gameservice/u0a106 for broadcast com.enhance.gameservice/.GameServiceReceiver
07-17 13:38:48.650  4251  4251 E wpa_supplicant: can't get BSS information
07-17 13:38:48.650  4251  4251 I wpa_supplicant: CTRL_IFACE: Detach monitor that cannot receive messages: /data/misc/wifi/sockets/wpa_ctrl_3704-2\x00
07-17 13:38:48.650  4251  4251 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.E6.C2 reason=3 locally_generated=1
,07-17 13:38:48.652  9932  9932 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-17 13:38:48.653  9932  9932 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.enhance.gameservice 
,07-17 13:38:48.654  3704  4182 I ActivityManager: KPU : put [com.facebook.system] : 27348 K
07-17 13:38:48.654  3704  4182 I ActivityManager: Killing 8999:com.facebook.system/u0a12 (adj 906): DHA:empty #33
,07-17 13:38:48.655  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:38:48.656  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:38:48.656  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:48.658  9764  9784 D BtGatt.GattService: onClientRegistered() - UUID=4a2e734d-fcb0-401b-a1e9-269b75de0837, clientIf=5, status=0
,07-17 13:38:48.659  4626  4646 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,07-17 13:38:48.661  9764  9775 D BtGatt.GattService: start scan with filters
,07-17 13:38:48.663  9764  9775 D BtGatt.GattService: getScanSettings
,07-17 13:38:48.666  9764  9775 D BtGatt.GattService: Is it foreground application = false
07-17 13:38:48.667  9764  9775 D BtGatt.GattService: Its third party background application, change scanmode to low power
,07-17 13:38:48.668  4070  4204 D vol.MediaSessions: onQueueChanged com.google.android.music []
,07-17 13:38:48.670  9932  9932 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:48.670  9932  9932 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:48.671  3704  6511 I ActivityManager: DSS on for com.enhance.gameservice and scale is 1.0
,07-17 13:38:48.677  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_START_SCAN
,07-17 13:38:48.678  9764  9802 D BtGatt.ScanManager: handling starting scan
07-17 13:38:48.679  9764  9802 D BtGatt.ScanManager: isFilteringSupported
07-17 13:38:48.679  9764  9802 D BluetoothAdapter: enableStandAloneBleMode=
07-17 13:38:48.680  3704  4753 D ActivityManager: cleanUpApplicationRecord -- 8999
07-17 13:38:48.680  9764  9802 D BluetoothAdapter: STATE_ON
07-17 13:38:48.681  9764  9802 D BluetoothAdapter: STATE_ON
,07-17 13:38:48.683  9764  9802 D BluetoothAdapter: STATE_ON
07-17 13:38:48.684  4670  4687 D ForegroundUtils: could not check pending caller
07-17 13:38:48.684  9764  9802 D BluetoothAdapter: STATE_ON
07-17 13:38:48.685  9764  9802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:38:48.687  9932  9932 W System  : ClassLoader referenced unknown path: /system/app/GameOptimizer/lib/arm64
07-17 13:38:48.688  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-2ms what=135179 arg1=181 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:48.688  9764  9802 D BluetoothAdapter: STATE_ON
07-17 13:38:48.689  9764  9802 D BluetoothAdapter: STATE_ON
,07-17 13:38:48.694  9764  9784 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-17 13:38:48.694  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:38:48.695  9764  9802 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
,07-17 13:38:48.695  9764  9802 D BtGatt.ScanManager: addFilterToController: 5
,07-17 13:38:48.696  9932  9932 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-17 13:38:48.701  9764  9784 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=47
07-17 13:38:48.701  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:38:48.701  9764  9802 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-17 13:38:48.701  9764  9802 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-17 13:38:48.701  3704  4753 D MountService: getExternalStorageMountMode : 3
07-17 13:38:48.701  3704  4753 D MountService: getExternalStorageMountMode : 3
07-17 13:38:48.702  3704  4753 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 5017, packageName : com.samsung.android.radiobasedlocation
07-17 13:38:48.702  9764  9802 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,07-17 13:38:48.706  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-17 13:38:48.706  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:38:48.706  9764  9802 D BtGatt.ScanManager: set filter index= 4 for clientIf= 5
07-17 13:38:48.706  9764  9802 D BtGatt.ScanManager: addFilterToController: 5
07-17 13:38:48.710  9764  9784 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=46
07-17 13:38:48.710  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:38:48.710  9764  9802 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-17 13:38:48.710  9764  9802 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-17 13:38:48.710  9764  9802 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
07-17 13:38:48.713  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=30
07-17 13:38:48.713  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:38:48.714  9764  9802 D BtGatt.ScanManager: set filter index= 5 for clientIf= 5
07-17 13:38:48.714  9764  9802 D BtGatt.ScanManager: addFilterToController: 2
07-17 13:38:48.717  9764  9784 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=45
07-17 13:38:48.718  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:38:48.718  9764  9802 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-17 13:38:48.718  9764  9802 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-17 13:38:48.718  9764  9802 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,07-17 13:38:48.722  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=29
07-17 13:38:48.722  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:38:48.723  9764  9802 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
07-17 13:38:48.723  9764  9802 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=0 mLastConfiguredScanSetting=-2147483648
07-17 13:38:48.723  9764  9802 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 800
07-17 13:38:48.725  9764  9784 D BtGatt.GattService: onScanParamSetupCompleted() status=0, clientIf=5
07-17 13:38:48.725  9764  9784 D BtGatt.GattService: onScanParamSetupCompleted : 0
,07-17 13:38:48.734  9946  9946 E Zygote  : v2
07-17 13:38:48.734  9946  9946 I libpersona: KNOX_SDCARD checking this for 5017
07-17 13:38:48.734  9946  9946 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:48.736  9946  9946 E Zygote  : accessInfo : 0
,07-17 13:38:48.745  9946  9946 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:48.747  9946  9946 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.radiobasedlocation 
,07-17 13:38:48.748  3704  4753 I ActivityManager: Start proc 9946:com.samsung.android.radiobasedlocation/5017 for broadcast com.samsung.android.radiobasedlocation/.RblServiceReceiver
,07-17 13:38:48.752  3704  4753 I ActivityManager: KPU : put [com.google.android.apps.docs] : 42440 K
07-17 13:38:48.752  3704  4753 I ActivityManager: Killing 9014:com.google.android.apps.docs/u0a93 (adj 906): DHA:empty #33
,07-17 13:38:48.769  9946  9946 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:48.770  9946  9946 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:48.772  3704  6347 I ActivityManager: DSS on for com.samsung.android.radiobasedlocation and scale is 1.0
,07-17 13:38:48.776  4251  4251 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,07-17 13:38:48.782  3704  3920 D ActivityManager: cleanUpApplicationRecord -- 9014
,07-17 13:38:48.783  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:48.792  9946  9946 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-17 13:38:48.794  9946  9946 W System  : ClassLoader referenced unknown path: /system/priv-app/RadioBasedLocation/lib/arm64
,07-17 13:38:48.805  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,07-17 13:38:48.806  9946  9946 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:48.809  4799  4799 D LauncherApplication: run: mBadgeRefreshHandler reloadBadges
07-17 13:38:48.809  4799  4799 D Launcher.Model: reloadBadges entered.
,07-17 13:38:48.811  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
07-17 13:38:48.811  3704  3805 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,07-17 13:38:48.812  9946  9946 I [RBL] PathProvider: @onCreate
,07-17 13:38:48.816  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:38:48.816  3300  3769 D Netd    : Iface wlan0 link up
07-17 13:38:48.817  4251  4251 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-17 13:38:48.818  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:38:48.818  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:48.819  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
,07-17 13:38:48.819  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:48.819  9946  9946 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-17 13:38:48.830  9914  9926 D BadgeProvider: query, [selection] : null
,07-17 13:38:48.834  3704  4338 D MountService: getExternalStorageMountMode : 1
07-17 13:38:48.834  3704  4338 D MountService: getExternalStorageMountMode : 3
07-17 13:38:48.834  3704  4338 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.diagmonagent
,07-17 13:38:48.855  9960  9960 E Zygote  : v2
,07-17 13:38:48.855  9960  9960 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:48.855  9960  9960 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:48.856  9960  9960 E Zygote  : accessInfo : 0
07-17 13:38:48.857  3704  4338 I ActivityManager: Start proc 9960:com.sec.android.diagmonagent/1000 for broadcast com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,07-17 13:38:48.862  4799  4915 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
07-17 13:38:48.862  4799  4915 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
07-17 13:38:48.862  4799  4915 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
07-17 13:38:48.862  4799  4915 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-17 13:38:48.862  4799  4915 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
07-17 13:38:48.862  4799  4915 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
07-17 13:38:48.862  4799  4915 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.lool = 0
07-17 13:38:48.862  4799  4915 D BadgeCache: 1. updateBadgeCounts: com.wssyncmldm = 0
,07-17 13:38:48.865  4799  4915 D BadgeCache: updated Badged:0
07-17 13:38:48.865  4799  4915 D BadgeCache: updateBadgeCounts:0
,07-17 13:38:48.865  9960  9960 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:48.868  9960  9960 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.diagmonagent 
,07-17 13:38:48.893  9960  9960 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:48.893  9960  9960 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:48.895  3704  4182 I ActivityManager: DSS on for com.sec.android.diagmonagent and scale is 1.0
,07-17 13:38:48.914  9960  9960 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,07-17 13:38:48.929  9960  9960 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:48.949  9960  9960 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,07-17 13:38:48.952  3704  3931 D wifi    : In wifi stop Hal
07-17 13:38:48.952  3704  3931 D wifi    : halHandle = 0x7d116a4460, mVM = 0x7d3b290300, mCls = 0x101042
07-17 13:38:48.953  3704  4250 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
07-17 13:38:48.953  3704  4250 D WifiHAL : Got a signal to exit!!!
07-17 13:38:48.953  3704  4250 I WifiHAL : Exit wifi_event_loop
,07-17 13:38:48.955  3704  3931 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
07-17 13:38:48.955  3704  3931 E WifiHAL : Event processing terminated
,07-17 13:38:48.964  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-17 13:38:48.965  3300  3769 D Netd    : Iface p2p0 link down
07-17 13:38:48.965  3704  3958 D HS20StateMachine: WIFI_STATE_DISABLED
07-17 13:38:48.965  3704  3958 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
,07-17 13:38:48.966  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-17 13:38:48.967  3704  3959 I WifiHs20Service: Message received 5011
07-17 13:38:48.967  3704  3811 D Tethering: interfaceLinkStateChanged p2p0, false
07-17 13:38:48.967  3704  3811 D Tethering: interfaceStatusChanged p2p0, false
,07-17 13:38:48.972  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-17 13:38:48.979  3704  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-17 13:38:48.980  3704  3704 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-17 13:38:48.980  3704  4257 D SLocation: checkWifiInfo
,07-17 13:38:48.984  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:48.986  3704  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-17 13:38:48.987  9764  9764 D A2dpService: A2dpService - WIFI_STATE_DISABLED
07-17 13:38:48.988  9764  9764 I BluetoothA2dpServiceJni: Attempting to set busy level
,07-17 13:38:48.989  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:48.989  4626  5215 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-17 13:38:48.991  9960  9960 E SQLiteLog: (1) no such column: currentid
,07-17 13:38:48.992  9960  9960 E DIAGMON_AGENT: [llllIIIIlllIIIlIllIl(906/lllIlIlIIIllIIlIllIl)] android.database.sqlite.SQLiteException: no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1
07-17 13:38:48.992  9960  9960 E DIAGMON_AGENT: #################################################################
07-17 13:38:48.992  9960  9960 E DIAGMON_AGENT: Error Code : 1 (SQLITE_ERROR)
07-17 13:38:48.992  9960  9960 E DIAGMON_AGENT: Caused By : SQL(query) error or missing database.
07-17 13:38:48.992  9960  9960 E DIAGMON_AGENT: 	(no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1)
07-17 13:38:48.992  9960  9960 E DIAGMON_AGENT: #################################################################
,07-17 13:38:49.006  3704  3931 D wifi    : In wifi cleaned up handler
07-17 13:38:49.006  3704  3931 I WifiHAL : Internal cleanup completed
,07-17 13:38:49.025  9960  9960 E SQLiteLog: (1) table profilelist has no column named currentid
,07-17 13:38:49.027  9960  9960 E SQLiteDatabase: Error inserting number=0 len=0 profilename3=Mformation notiretrycount=0 currentid=-1 size=0 oplevel=0 serviceid= appid=0 profilename2=dm-Server notievent=0 sessionid=null profilename1=api-server status=0 uictype=0 text= holdingid=-1 sessionsavestate=0 profileindex=0 opmode= result=0 pushjobid= notiuievent=0
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: android.database.sqlite.SQLiteException: table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: #################################################################
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: Error Code : 1 (SQLITE_ERROR)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: Caused By : SQL(query) error or missing database.
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	(table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?))
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: #################################################################
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1005)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.prepare(SQLiteConnection.java:570)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:588)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:59)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1771)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1643)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:667)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:399)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:116)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:60)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1032)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5885)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap3(ActivityThread.java)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1703)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:154)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6692)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke,(Native Method)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1468)
07-17 13:38:49.027  9960  9960 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1358)
,07-17 13:38:49.062  9960  9960 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(64/onCreate)] nStatus : 0
,07-17 13:38:49.068  9960  9960 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(77/onCreate)] DiagMon DM Application Start !
07-17 13:38:49.068  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-17 13:38:49.069  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-17 13:38:49.069  9960  9960 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-17 13:38:49.069  9960  9960 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-17 13:38:49.074  3704  6347 D MountService: getExternalStorageMountMode : 1
07-17 13:38:49.074  3704  6347 D MountService: getExternalStorageMountMode : 3
07-17 13:38:49.074  3704  6347 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.app.RilErrorNotifier
,07-17 13:38:49.115  3704  4752 D WifiService: setWifiEnabled: true pid=9623, uid=10033
,07-17 13:38:49.120  9974  9974 E Zygote  : v2
,07-17 13:38:49.120  9974  9974 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:49.120  9974  9974 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:49.121  3704  6347 I ActivityManager: Start proc 9974:com.sec.app.RilErrorNotifier/1000 for broadcast com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
07-17 13:38:49.121  9974  9974 E Zygote  : accessInfo : 0
07-17 13:38:49.121  3704  4752 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-17 13:38:49.122  3704  4752 D WifiControlHistoryProvider: query
,07-17 13:38:49.133  3704  6347 I ActivityManager: KPU : put [com.facebook.appmanager] : 23340 K
07-17 13:38:49.133  3704  6347 I ActivityManager: Killing 8970:com.facebook.appmanager/u0a98 (adj 906): DHA:empty #33
,07-17 13:38:49.134  9974  9974 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-17 13:38:49.136  9974  9974 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.app.RilErrorNotifier 
07-17 13:38:49.139  3704  4752 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-17 13:38:49.139  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:49.140  3704  4752 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:49.141  3704  4752 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-17 13:38:49.145  3704  4752 I WifiService: Wi-Fi Sharing settings has not been accessed
07-17 13:38:49.145  3704  4752 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-17 13:38:49.146  3704  3930 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-17 13:38:49.158  9974  9974 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:49.158  9974  9974 D ActivityThread: Added TimaKeyStore provider
07-17 13:38:49.160  3704  4338 I ActivityManager: DSS on for com.sec.app.RilErrorNotifier and scale is 1.0
,07-17 13:38:49.172  4626  6633 I BeaconBle: Client requested to stop, listener=hjz@fba5ae7
,07-17 13:38:49.177  3704  4753 D ActivityManager: cleanUpApplicationRecord -- 8970
07-17 13:38:49.179  4670  4686 D ForegroundUtils: could not check pending caller
07-17 13:38:49.183  9974  9974 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,07-17 13:38:49.187  4626  6633 I BeaconBle: Stopping scan on delegate scanner - BT state: 12
,07-17 13:38:49.189  4626  6633 D BluetoothAdapter: STATE_ON
,07-17 13:38:49.191  4626  6633 D BluetoothAdapter: STATE_ON
,07-17 13:38:49.191  4626  6633 D BluetoothLeScanner: Stop Scan
,07-17 13:38:49.192  9764  9775 D BtGatt.GattService: stopScan() - queue size =1
07-17 13:38:49.193  9764  9775 D BtGatt.GattService: stopScan() - queue size =1
07-17 13:38:49.193  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_STOP_SCAN
,07-17 13:38:49.195  9764  9802 D BtGatt.ScanManager: stop scan
07-17 13:38:49.196  9764  9802 D BtGatt.ScanManager: delete FilterIndex - 3
,07-17 13:38:49.197  9764  9785 D BtGatt.GattService: unregisterClient() - clientIf=5
07-17 13:38:49.198  9974  9974 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:49.202  4626  6633 D BluetoothAdapter: STATE_ON
07-17 13:38:49.202  9974  9974 I PhoneErrorReceiver: onReceive
07-17 13:38:49.203  4626  6633 D BluetoothAdapter: STATE_ON
07-17 13:38:49.203  4626  6633 I BeaconBle: Resetting - new scanner available: true
07-17 13:38:49.204  4626  6633 I BeaconBle: 'L' hardware scan: scan stopped, no clients
07-17 13:38:49.204  4626  6633 I BeaconBle: Scan canceled successfully.
,07-17 13:38:49.207  3704  4183 D MountService: getExternalStorageMountMode : 1
,07-17 13:38:49.208  3704  4183 D MountService: getExternalStorageMountMode : 3
07-17 13:38:49.208  3704  4183 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.knox.switcher
07-17 13:38:49.210  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=30
07-17 13:38:49.210  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:38:49.210  9764  9802 D BtGatt.ScanManager: delete FilterIndex - 4
,07-17 13:38:49.215  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=31
07-17 13:38:49.215  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:38:49.216  9764  9802 D BtGatt.ScanManager: delete FilterIndex - 5
,07-17 13:38:49.228  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-17 13:38:49.228  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:38:49.228  9764  9802 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
07-17 13:38:49.228  9764  9802 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=0
07-17 13:38:49.228  9764  9802 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,07-17 13:38:49.234  9987  9987 E Zygote  : v2
07-17 13:38:49.234  9987  9987 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:49.234  9987  9987 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:49.235  9987  9987 E Zygote  : accessInfo : 0
,07-17 13:38:49.235  3704  4183 I ActivityManager: Start proc 9987:com.sec.knox.switcher/1000 for broadcast com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
07-17 13:38:49.238  3704  4338 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{32fc396: PendingIntentRecord{4f22b17 com.google.android.gms broadcastIntent}}
07-17 13:38:49.239  4626  6633 W NearbyMessages: Runnable[ScanComplete] not posted since EventLoop is destroyed
07-17 13:38:49.239  3704  4183 I ActivityManager: KPU : put [com.google.android.partnersetup] : 26944 K
07-17 13:38:49.239  3704  4183 I ActivityManager: Killing 9058:com.google.android.partnersetup/u0a23 (adj 906): DHA:empty #33
07-17 13:38:49.241  9987  9987 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:49.243  9987  9987 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.knox.switcher 
,07-17 13:38:49.261  3704  4328 D ActivityManager: cleanUpApplicationRecord -- 9058
07-17 13:38:49.262  9987  9987 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-17 13:38:49.263  9987  9987 D ActivityThread: Added TimaKeyStore provider
07-17 13:38:49.263  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:49.266  3704  3760 I ActivityManager: DSS on for com.sec.knox.switcher and scale is 1.0
,07-17 13:38:49.284  9987  9987 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
,07-17 13:38:49.298  9987  9987 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:49.303  9987  9987 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
07-17 13:38:49.303  9987  9987 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
,07-17 13:38:49.304  9987  9987 D ShareFileProvider: ShareFileProvider | onCreate [0]
07-17 13:38:49.304  9987  9987 D ShareFileDBHelper: getInstance - ShareFileDBHelper
07-17 13:38:49.304  9987  9987 D ShareFileDBHelper: null == mDbHelperInstance - ShareFileDBHelper
07-17 13:38:49.304  9987  9987 D ShareFileDBHelper: ShareFileDBHelper - Constructor
,07-17 13:38:49.306  9987  9987 I usagelog: received in receiver
07-17 13:38:49.307  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-17 13:38:49.310  9987  9987 I KnoxUsageLogPro: premStatus:2
,07-17 13:38:49.314  9987  9987 I KnoxUsageLogPro: isEulaShown : false
07-17 13:38:49.315  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-17 13:38:49.320  3704  4182 I ActivityManager: KPU : put [com.samsung.android.SettingsReceiver] : 26792 K
07-17 13:38:49.320  3704  4182 I ActivityManager: Killing 9078:com.samsung.android.SettingsReceiver/1000 (adj 906): DHA:empty #33
,07-17 13:38:49.341  4989  4989 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-17 13:38:49.342  3704  9910 D ActivityManager: cleanUpApplicationRecord -- 9078
,07-17 13:38:49.343  4670  4687 D ForegroundUtils: could not check pending caller
,07-17 13:38:49.347  4989  7986 I iu.UploadsManager: num queued entries: 0
,07-17 13:38:49.348  4989  7986 I iu.UploadsManager: num updated entries: 0
07-17 13:38:49.349  4989  7986 I iu.SyncManager: NEXT; no task
,07-17 13:38:49.353  3704  5299 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:49.373  3704  4752 D MountService: getExternalStorageMountMode : 1
07-17 13:38:49.373  3704  4752 D MountService: getExternalStorageMountMode : 3
07-17 13:38:49.373  3704  4752 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10041, packageName : com.osp.app.signin
,07-17 13:38:49.392 10000 10000 E Zygote  : v2
07-17 13:38:49.392 10000 10000 I libpersona: KNOX_SDCARD checking this for 10041
07-17 13:38:49.392 10000 10000 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:49.393 10000 10000 E Zygote  : accessInfo : 0
,07-17 13:38:49.399  3704  4752 I ActivityManager: Start proc 10000:com.osp.app.signin/u0a41 for broadcast com.osp.app.signin/.OspReceiver
,07-17 13:38:49.403 10000 10000 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:49.405 10000 10000 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.osp.app.signin 
,07-17 13:38:49.436  3704  4265 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / op:PendingIntent{a472941: PendingIntentRecord{8248ee6 android broadcastIntent}}
,07-17 13:38:49.437 10000 10000 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-17 13:38:49.438 10000 10000 D ActivityThread: Added TimaKeyStore provider
07-17 13:38:49.438  3704  4184 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170717T140849 - CU:10124/CP:4872
,07-17 13:38:49.441  3704  6348 I ActivityManager: DSS on for com.osp.app.signin and scale is 1.0
,07-17 13:38:49.452  3704  4265 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170718T133849 - CU:1000/CP:3704
,07-17 13:38:49.520 10000 10000 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-17 13:38:49.524 10000 10000 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Dream/lib/arm64
,07-17 13:38:49.551 10000 10000 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:49.564  3704  3866 D SamsungAlarmManager: Expired : 4
07-17 13:38:49.565  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T135549, SetElapsed=1219750, nowELAPSED=200309
,07-17 13:38:49.565  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@62b2f8f alarm=Alarm{81c8322 type 2 when 200308 android}
,07-17 13:38:49.567 10000 10000 I SA      : [SSP] onCreated
,07-17 13:38:49.571  3704  3704 D SamsungAlarmManager: setExact Listener (T:2/F:0/AC:false) 20170717T133849 - CU:1000/CP:3704
07-17 13:38:49.572  3704  3704 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133850, SetElapsed=201310, nowELAPSED=200316
,07-17 13:38:49.604 10000 10000 D SamsungAnalytics:1.8.22: cf feature is supported
,07-17 13:38:49.611 10000 10000 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
,07-17 13:38:49.618 10000 10000 I SA      : LBE isSupportBixbyModel() FALSE
,07-17 13:38:49.629 10000 10000 I SA      : [TPM] There is no property file
,07-17 13:38:49.637  3300  3769 D Netd    : Iface wlan0 link down
07-17 13:38:49.639 10000 10000 I SA      : [SCU] isHaveSA() - false
,07-17 13:38:49.641  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, false
07-17 13:38:49.641  3704  3811 D Tethering: interfaceStatusChanged wlan0, false
,07-17 13:38:49.647  3704  4250 D wifi    : set interface wlan0 flags (DOWN)
07-17 13:38:49.647 10000 10000 I SA      : [SS] no samsung account is signed in
,07-17 13:38:49.648  3704  3931 D WifiNative-HAL: HAL event thread stopped successfully
,07-17 13:38:49.652 10000 10000 I SA      : [TPM] getModelProperty : null
07-17 13:38:49.652 10000 10000 I SA      : [TPM] getCSCProperty : null
,07-17 13:38:49.655  3704  4752 D WifiService: setWifiEnabled: true pid=9623, uid=10033
,07-17 13:38:49.655 10000 10000 I SA      : [SCU] isHaveSA() - false
07-17 13:38:49.655  3704  4752 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-17 13:38:49.656  3704  4752 D WifiControlHistoryProvider: query
,07-17 13:38:49.659 10000 10000 I SA      : [SCU] == networkStateCheck == false
07-17 13:38:49.659 10000 10000 I SA      : [SS] network off, couldn't connect to DIR
,07-17 13:38:49.666 10000 10000 D BixbyApi_0.1.6: Version Name:2.2.03-46
,07-17 13:38:49.669  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-17 13:38:49.670 10000 10000 I SA      : [DM] init START
07-17 13:38:49.670  3704  4752 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-17 13:38:49.671  3704  4752 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:49.673  3704  4752 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:49.676 10000 10000 I SA      : [DM] This device is not a Vodafone
,07-17 13:38:49.679  3704  4752 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-17 13:38:49.680  3704  4752 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-17 13:38:49.681  3704  3930 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-17 13:38:49.685 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.685 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.686 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.686 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.687 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.687 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.688 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.689 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.689 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.690 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.690 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.691 10000 10000 W ResourceType: Failure getting entry for 0x7f0b0002 (t=10 e=2) (error -75)
,07-17 13:38:49.691 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.692 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.692 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.693 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.694 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.694 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.695 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.695 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.696 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.697 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.697 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.698 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.698 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.699 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.700 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.700 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.701 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.701 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.702 10000 10000 W ResourceType: Failure getting entry for 0x7f0b0005 (t=10 e=5) (error -75)
07-17 13:38:49.702 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.703 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.704 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.704 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.705 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.705 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.706 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.707 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.707 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.708 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.708 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.709 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.710 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.710 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.713 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.713 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
07-17 13:38:49.713 10000 10000 W ResourceType: No package identifier when getting value for resource number 0x00000000
,07-17 13:38:49.716 10000 10000 I SA      : support phone number id : true
07-17 13:38:49.716 10000 10000 I SA      : [DM] Supports Ref Jpn : true
07-17 13:38:49.717 10000 10000 I SA      : [DM] init END
,07-17 13:38:49.717 10000 10000 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,07-17 13:38:49.720 10000 10000 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
07-17 13:38:49.720 10000 10000 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-17 13:38:49.731 10000 10000 I SA      : [SLFUCHKMGR] constructor called
,07-17 13:38:49.751 10000 10000 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-17 13:38:49.751 10000 10000 I SA      : [OR] == isSIMCardReady false ==
07-17 13:38:49.751 10000 10000 I SA      : [SCU] == networkStateCheck == false
07-17 13:38:49.752 10000 10000 I SA      : [OR] onReceive END
,07-17 13:38:49.760  3704  4182 I ActivityManager: KPU : put [com.samsung.android.app.mirrorlink] : 21116 K
07-17 13:38:49.760  3704  4182 I ActivityManager: Killing 9092:com.samsung.android.app.mirrorlink/1000 (adj 906): DHA:empty #33
,07-17 13:38:49.765  3704  3788 D MountService: getExternalStorageMountMode : 1
07-17 13:38:49.765  3704  3788 D MountService: getExternalStorageMountMode : 3
07-17 13:38:49.765  3704  3788 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.svcagent
,07-17 13:38:49.791 10023 10023 E Zygote  : v2
07-17 13:38:49.791 10023 10023 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:49.791 10023 10023 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:49.792  3704  3788 I ActivityManager: Start proc 10023:com.samsung.android.svcagent/1000 for broadcast com.samsung.android.svcagent/com.samsung.android.service.svcagent.BootReceiver
07-17 13:38:49.792 10023 10023 E Zygote  : accessInfo : 0
07-17 13:38:49.793  3704  4328 D ActivityManager: cleanUpApplicationRecord -- 9092
,07-17 13:38:49.798  4670  4687 D ForegroundUtils: could not check pending caller
,07-17 13:38:49.802 10023 10023 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:49.804 10023 10023 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.svcagent 
,07-17 13:38:49.831 10023 10023 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:49.831 10023 10023 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:49.833  3704  6348 I ActivityManager: DSS on for com.samsung.android.svcagent and scale is 1.0
,07-17 13:38:49.850  3704  3931 E WifiHW  : ##################### set firmware type 0 #####################
,07-17 13:38:49.852  3300  3777 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-17 13:38:49.852  3300  3777 I WifiHW  : module is semco
07-17 13:38:49.853  3300  3777 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-17 13:38:49.853  3300  3777 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-17 13:38:49.853  3300  3777 E WifiHW  : TEMP_FAILURE_RETRY complete
07-17 13:38:49.853  3300  3777 D SoftapController: Softap fwReload - Ok
,07-17 13:38:49.854  3704  3931 E NetworkManagement: wifiFirmwareReload Error reloading wlan0 fw in STA mode: event = 200 65 Softap operation succeeded
,07-17 13:38:49.855 10023 10023 W System  : ClassLoader referenced unknown path: /system/priv-app/SVCAgent/lib/arm64
,07-17 13:38:49.858  3300  3777 D CommandListener: Setting iface cfg
07-17 13:38:49.858  3300  3777 D CommandListener: Trying to bring down wlan0
,07-17 13:38:49.861  3300  3777 D CommandListener: Clearing all IP addresses on wlan0
,07-17 13:38:49.870  3704  3931 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,07-17 13:38:49.874 10023 10023 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:49.884 10023 10023 I SVCAgent: Ignore network change.
,07-17 13:38:49.887  3704  6347 D MountService: getExternalStorageMountMode : 1
07-17 13:38:49.887  3704  6347 D MountService: getExternalStorageMountMode : 3
07-17 13:38:49.887  3704  6347 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10064, packageName : com.samsung.android.themestore
,07-17 13:38:49.927 10036 10036 E Zygote  : v2
07-17 13:38:49.927 10036 10036 I libpersona: KNOX_SDCARD checking this for 10064
07-17 13:38:49.927 10036 10036 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:49.928 10036 10036 E Zygote  : accessInfo : 0
,07-17 13:38:49.930  3704  6347 I ActivityManager: Start proc 10036:com.samsung.android.themestore/u0a64 for broadcast com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,07-17 13:38:49.936  3704  6347 I ActivityManager: KPU : put [com.samsung.android.sm.provider] : 28352 K
07-17 13:38:49.936  3704  6347 I ActivityManager: Killing 4546:com.samsung.android.sm.provider/1000 (adj 906): DHA:empty #33
,07-17 13:38:49.938 10036 10036 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:49.940 10036 10036 I SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,07-17 13:38:49.964 10036 10036 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:49.964  3704  3759 D ActivityManager: cleanUpApplicationRecord -- 4546
07-17 13:38:49.965 10036 10036 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:49.966  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:49.970  3704  9909 I ActivityManager: DSS on for com.samsung.android.themestore and scale is 1.0
,07-17 13:38:49.994 10036 10036 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-17 13:38:49.995 10036 10036 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyThemes/lib/arm64
,07-17 13:38:50.010 10036 10036 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:50.032 10036 10036 D a       : Exist Config : false
,07-17 13:38:50.034 10036 10036 D a       : getMcc
,07-17 13:38:50.040 10036 10036 D as      : isQaMode
,07-17 13:38:50.047 10036 10036 D a       : getMnc
07-17 13:38:50.048 10036 10036 D a       : getCsc
,07-17 13:38:50.048 10036 10036 D a       : getSystemCountryCode
07-17 13:38:50.048 10036 10036 D a       : getImei
,07-17 13:38:50.053 10036 10036 D as      : getMd5HashString
07-17 13:38:50.054 10036 10036 D as      : getSha256HashString
,07-17 13:38:50.054 10036 10036 D a       : getModelName
07-17 13:38:50.055 10036 10036 D a       : getVirtualModelName
07-17 13:38:50.055 10036 10036 D a       : getAndroidSDKVersion
07-17 13:38:50.055 10036 10036 D a       : getLanguageCode
07-17 13:38:50.055 10036 10036 D a       : getCountryCode
,07-17 13:38:50.057 10036 10036 D a       : getNetworkType
,07-17 13:38:50.064 10036 10036 D w       : isSupportedAodSystemFeature
,07-17 13:38:50.069 10036 10036 D a       : getThemeFrameworkVersion
,07-17 13:38:50.078 10036 10036 D a       : isLogPrintMode
,07-17 13:38:50.083 10036 10036 D as      : isQaMode
,07-17 13:38:50.092 10036 10036 D a       : getVerName
,07-17 13:38:50.093 10036 10036 D a       : getVerCode
,07-17 13:38:50.095 10036 10036 D a       : getPackageName
07-17 13:38:50.095 10036 10036 D a       : getAutoUpgradeInterval
,07-17 13:38:50.098 10036 10036 D a       : loadCountrySearchEx
,07-17 13:38:50.103 10036 10036 D a       : com.samsung.android.themestore.g.c.b.u; class invalid for deserialization
,07-17 13:38:50.104 10036 10036 I a       : # initConfig Time : 76
07-17 13:38:50.104 10036 10036 I a       : ● MCC/NNC: /0
07-17 13:38:50.104 10036 10036 I a       : ● Model: SM-G930F_TM
07-17 13:38:50.104 10036 10036 I a       : ● MyApp Version: 2.1.56-70306
07-17 13:38:50.105 10036 10036 I a       : ● OS Version: 24
07-17 13:38:50.105 10036 10036 I a       : ● IsSupportedSView: true
,07-17 13:38:50.119 10036 10036 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-17 13:38:50.150 10036 10036 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-17 13:38:50.160  3704  3760 I ActivityManager: KPU : put [com.samsung.android.scloud] : 28704 K
,07-17 13:38:50.160  3704  3760 I ActivityManager: Killing 9112:com.samsung.android.scloud/5009 (adj 906): DHA:empty #33
,07-17 13:38:50.169  7762  7762 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,07-17 13:38:50.169  7762  7762 E SPPClientService: [SystemStateMoniter] Current Time : 200913
07-17 13:38:50.170  7762  7762 E SPPClientService: [SystemStateMoniter] No Connect : true
,07-17 13:38:50.185  3704  5299 D WifiService: setWifiEnabled: true pid=9623, uid=10033
,07-17 13:38:50.185  3704  5299 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-17 13:38:50.186  3704  5299 D WifiControlHistoryProvider: query
07-17 13:38:50.188  7762 10062 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
07-17 13:38:50.188  3704  3924 D MountService: getExternalStorageMountMode : 1
07-17 13:38:50.188  3704  3924 D MountService: getExternalStorageMountMode : 3
07-17 13:38:50.188  3704  3924 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 5005, packageName : com.samsung.android.allshare.service.fileshare
,07-17 13:38:50.207 10063 10063 E Zygote  : v2
07-17 13:38:50.207 10063 10063 I libpersona: KNOX_SDCARD checking this for 5005
,07-17 13:38:50.207 10063 10063 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:50.208 10063 10063 E Zygote  : accessInfo : 0
07-17 13:38:50.208  3704  3924 I ActivityManager: Start proc 10063:com.samsung.android.allshare.service.fileshare/5005 for broadcast com.samsung.android.allshare.service.fileshare/.FileShareBroadcastReceiver
,07-17 13:38:50.212  3704  4183 D ActivityManager: cleanUpApplicationRecord -- 9112
,07-17 13:38:50.212  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-17 13:38:50.215 10063 10063 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:50.217  4670  4687 D ForegroundUtils: could not check pending caller
07-17 13:38:50.217  3704  5299 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-17 13:38:50.217 10063 10063 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.allshare.service.fileshare 
07-17 13:38:50.218  3704  5299 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:50.219  3704  5299 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:50.222  3704  5299 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-17 13:38:50.222  3704  5299 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-17 13:38:50.223  3704  3930 E WifiController: illegal state found both WifiController and WifiStateMachine
,07-17 13:38:50.247 10063 10063 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:50.248 10063 10063 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:50.250  3704  6348 I ActivityManager: DSS on for com.samsung.android.allshare.service.fileshare and scale is 1.0
,07-17 13:38:50.289 10063 10063 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:50.295 10063 10063 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-17 13:38:50.298 10063 10063 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
,07-17 13:38:50.315 10063 10063 D FileShare: Outbound.stopDelayTimer - 
,07-17 13:38:50.330  9946  9946 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-17 13:38:50.338  3704  6347 I ActivityManager: KPU : put [com.samsung.android.sm.devicesecurity] : 27612 K
07-17 13:38:50.338  3704  6347 I ActivityManager: Killing 6916:com.samsung.android.sm.devicesecurity/5012 (adj 906): DHA:empty #33
,07-17 13:38:50.352  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,07-17 13:38:50.353  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-17 13:38:50.353  9960  9960 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-17 13:38:50.358  9974  9974 I PhoneErrorReceiver: onReceive
,07-17 13:38:50.360  3704  3924 D ActivityManager: cleanUpApplicationRecord -- 6916
,07-17 13:38:50.364  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:50.370  9987  9987 I usagelog: received in receiver
07-17 13:38:50.370  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,07-17 13:38:50.371  9987  9987 I KnoxUsageLogPro: premStatus:2
,07-17 13:38:50.372  9987  9987 I KnoxUsageLogPro: isEulaShown : false
07-17 13:38:50.372  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-17 13:38:50.380  9690  9690 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-17 13:38:50.380  9690  9690 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,07-17 13:38:50.383  3704  4740 D MountService: getExternalStorageMountMode : 1
07-17 13:38:50.383  3704  4740 D MountService: getExternalStorageMountMode : 3
07-17 13:38:50.383  3704  4740 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10172, packageName : com.example.ThaliTestApp
,07-17 13:38:50.401 10076 10076 E Zygote  : v2
,07-17 13:38:50.401 10076 10076 I libpersona: KNOX_SDCARD checking this for 10172
07-17 13:38:50.401 10076 10076 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:50.402  3704  4740 I ActivityManager: Start proc 10076:com.example.ThaliTestApp/u0a172 for broadcast com.example.ThaliTestApp/io.jxcore.node.ConnectivityChangeListener
07-17 13:38:50.403 10076 10076 E Zygote  : accessInfo : 0
,07-17 13:38:50.413 10076 10076 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:50.415 10076 10076 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.ThaliTestApp 
,07-17 13:38:50.421 10076 10076 I art     : Late-enabling -Xcheck:jni
,07-17 13:38:50.450 10076 10076 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-17 13:38:50.451 10076 10076 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:50.455  3704  3920 I ActivityManager: DSS on for com.example.ThaliTestApp and scale is 1.0
,07-17 13:38:50.497 10076 10076 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-17 13:38:50.524 10076 10076 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:50.534  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.534  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.534  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.534  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.534  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.535  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.535  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.535  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.535  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.535  3704  3759 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.567  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:38:50.568  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T135549, SetElapsed=1219750, nowELAPSED=201311
,07-17 13:38:50.568  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@26461b3 alarm=Alarm{b13d6e9 type 2 when 200314 android}
,07-17 13:38:50.583  3704  3704 D SamsungAlarmManager: setInexact Listener (T:2/F:0/AC:false) 20170717T135049 - CU:1000/CP:3704
,07-17 13:38:50.586 10076 10076 D jxcore_app_log: JniHelper::setJavaVM(0xe9db4000), pthread_self() = -315427532
07-17 13:38:50.586 10076 10076 E JX-Cordova: JXcore wasn't initialized yet
,07-17 13:38:50.597  3704  3924 D MountService: getExternalStorageMountMode : 3
07-17 13:38:50.597  3704  3924 D MountService: getExternalStorageMountMode : 3
07-17 13:38:50.597  3704  3924 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 10173, packageName : com.rockwellautomation.AppPlatformP2P
07-17 13:38:50.603  3300  3769 D Netd    : Iface wlan0 link up
07-17 13:38:50.603  3704  3931 D wifi    : set interface wlan0 flags (UP)
07-17 13:38:50.604  3704  3931 I WifiHAL : Initializing wifi
07-17 13:38:50.604  3704  3931 I WifiHAL : Creating socket
,07-17 13:38:50.608  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:38:50.608  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:50.609  3704  3931 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,07-17 13:38:50.609  3704  3931 D wifi    : Did set static halHandle = 0x7d116a4460
07-17 13:38:50.609  3704  3931 D wifi    : halHandle = 0x7d116a4460, mVM = 0x7d3b290300, mCls = 0x2d66
,07-17 13:38:50.610  3704  3931 D wifi    : array field set
07-17 13:38:50.611  3704  3931 I WifiHW  : CCMode is disabled, skip verifying wpa_supplicant
07-17 13:38:50.611  3704 10092 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=537163088992
07-17 13:38:50.612  3704 10092 D wifi    : waitForHalEvents called, vm = 0x7d3b290300, obj = 0x2d66, env = 0x7d107505c0
07-17 13:38:50.612  3704  3931 E WifiHW  : supplicant_name : p2p_supplicant
,07-17 13:38:50.632 10094 10094 E Zygote  : v2
07-17 13:38:50.632 10094 10094 I libpersona: KNOX_SDCARD checking this for 10173
07-17 13:38:50.633 10094 10094 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:50.634 10094 10094 E Zygote  : accessInfo : 0
,07-17 13:38:50.639  3704  3924 I ActivityManager: Start proc 10094:com.rockwellautomation.AppPlatformP2P/u0a173 for broadcast com.rockwellautomation.AppPlatformP2P/io.jxcore.node.ConnectivityChangeListener
,07-17 13:38:50.643 10094 10094 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:50.645  3704  3924 I ActivityManager: KPU : put [com.samsung.android.themecenter] : 26692 K
07-17 13:38:50.645  3704  3924 I ActivityManager: Killing 9134:com.samsung.android.themecenter/1000 (adj 906): DHA:empty #33
,07-17 13:38:50.645 10094 10094 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.rockwellautomation.AppPlatformP2P 
,07-17 13:38:50.648 10094 10094 I art     : Late-enabling -Xcheck:jni
,07-17 13:38:50.667 10094 10094 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:50.668 10094 10094 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:50.671  3704  4184 D ActivityManager: cleanUpApplicationRecord -- 9134
,07-17 13:38:50.672  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:50.675  3704  4338 I ActivityManager: DSS on for com.rockwellautomation.AppPlatformP2P and scale is 1.0
,07-17 13:38:50.699 10093 10093 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 10093 | /system/bin/wpa_supplicant
07-17 13:38:50.699 10093 10093 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
,07-17 13:38:50.701 10093 10093 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-17 13:38:50.701 10093 10093 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-17 13:38:50.704 10094 10094 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-17 13:38:50.705 10093 10093 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x400008), vendorssid_list()
07-17 13:38:50.705 10093 10093 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-17 13:38:50.707  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10093
07-17 13:38:50.707  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-17 13:38:50.707 10093 10093 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-17 13:38:50.707 10093 10093 I wpa_supplicant: ssSupport state is = 1
07-17 13:38:50.707 10093 10093 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-17 13:38:50.707 10093 10093 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-17 13:38:50.707  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
07-17 13:38:50.708  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10093
07-17 13:38:50.708  3114  3114 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-17 13:38:50.713  3704  3931 D SecContentProvider: insert(), uri = 2
,07-17 13:38:50.714  3704  3931 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:50.716  3704  3931 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-17 13:38:50.717  3704  3931 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,07-17 13:38:50.721  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,07-17 13:38:50.723  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
,07-17 13:38:50.725  3704  3959 I WifiHs20Service: Message received 5011
,07-17 13:38:50.727 10094 10094 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
07-17 13:38:50.728  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135173 arg1=2 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-17 13:38:50.736  3704  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-17 13:38:50.738  3704  3704 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-17 13:38:50.738  3704  4257 D SLocation: checkWifiInfo
07-17 13:38:50.740  3704  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-17 13:38:50.742  3704  9910 D WifiService: setWifiEnabled: true pid=9623, uid=10033
07-17 13:38:50.743  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-17 13:38:50.749  3704  9910 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
07-17 13:38:50.749  3704  9910 D WifiControlHistoryProvider: query
07-17 13:38:50.751  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:50.753  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.753  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.753  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.753  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.753  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.754  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.754  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.754  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.754  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.754  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.758  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:50.759  3704  9910 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
07-17 13:38:50.760  3704  9910 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:50.760  3704  9910 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
07-17 13:38:50.765  3704  9910 I WifiService: Wi-Fi Sharing settings has not been accessed
07-17 13:38:50.766  3704  9910 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-17 13:38:50.791 10094 10094 D jxcore_app_log: JniHelper::setJavaVM(0xe9db4000), pthread_self() = -315427532
07-17 13:38:50.791 10094 10094 E JX-Cordova: JXcore wasn't initialized yet
,07-17 13:38:50.801  3704  3911 I ActivityManager: KPU : put [com.samsung.svoice.sync] : 21140 K
07-17 13:38:50.801  3704  3911 I ActivityManager: Killing 9162:com.samsung.svoice.sync/u0a40 (adj 906): DHA:empty #33
,07-17 13:38:50.806  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.807  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.807  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.807  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.807  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.807  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.808  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.808  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.808  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.808  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.817  9690  9690 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-17 13:38:50.817  9690  9690 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,07-17 13:38:50.834  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.834  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.834  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.834  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.834  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.834  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.834  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.834  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.835  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.835  3704  6348 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.847  3704  4328 D ActivityManager: cleanUpApplicationRecord -- 9162
,07-17 13:38:50.847  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.848  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.848  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.848  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.849  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.849  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.849  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.849  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.850  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.850  3704  4338 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.856  4670  4687 D ForegroundUtils: could not check pending caller
,07-17 13:38:50.873  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.873  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.873  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.873  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.873  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.874  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.874  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.874  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.874  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-17 13:38:50.874  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.874  3704  4184 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.881  9690  9690 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-17 13:38:50.881  9690  9690 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.890  3704  3760 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.899  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.899  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.899  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.899  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.899  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.900  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.900  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.900  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.900  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.900  3704  4752 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:50.908  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.909  3704  6511 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:50.912 10093 10093 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
07-17 13:38:50.921  3704  5557 D SSRM:f  : SIOP:: AP = 290, PST = 281 (W:10), CP = 226, CUR = 126, LCD = 57
07-17 13:38:50.943 10093 10093 W wpa_supplicant: Loading system cred
07-17 13:38:50.943 10093 10093 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-17 13:38:50.943  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10093
07-17 13:38:50.943  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-17 13:38:50.944 10093 10093 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-17 13:38:50.944 10093 10093 I wpa_supplicant: ssSupport state is = 1
07-17 13:38:50.944  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-17 13:38:50.944 10093 10093 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-17 13:38:50.944 10093 10093 I wpa_supplicant: [getIMSI]: sim_num 0
,07-17 13:38:51.010 10093 10093 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-17 13:38:51.011  3300  3769 D Netd    : Iface wlan0 link up
07-17 13:38:51.012  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:38:51.017  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:38:51.017  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
,07-17 13:38:51.020  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:38:51.021  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
,07-17 13:38:51.131 10093 10093 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-17 13:38:51.131 10093 10093 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,07-17 13:38:51.132  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10093
07-17 13:38:51.132  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-17 13:38:51.133 10093 10093 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-17 13:38:51.133  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-17 13:38:51.133 10093 10093 I wpa_supplicant: ssSupport state is = 1
,07-17 13:38:51.138 10093 10093 E wpa_supplicant: nl80211: Could not configure driver mode
07-17 13:38:51.138 10093 10093 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
07-17 13:38:51.139 10093 10093 E wpa_supplicant: p2p0: Failed to initialize driver interface
,07-17 13:38:51.141 10093 10093 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
07-17 13:38:51.141 10093 10093 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
07-17 13:38:51.142  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10093
07-17 13:38:51.143  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,07-17 13:38:51.143  3114  3114 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
07-17 13:38:51.143 10093 10093 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
07-17 13:38:51.143 10093 10093 I wpa_supplicant: ssSupport state is = 1
,07-17 13:38:51.178 10093 10093 I wpa_supplicant: rfkill: Cannot get wiphy information
,07-17 13:38:51.194 10093 10093 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,07-17 13:38:51.236  4528  4528 D io_stats: !@   8,0 r 26132 2308572 w 5145 210016 d 678 74668 f 2110 2110 iot 11640 10940 th 465476 0 0 pt 0 inp 0 0 201.978
,07-17 13:38:51.276  3704  4338 D WifiService: setWifiEnabled: true pid=9623, uid=10033
07-17 13:38:51.277  3704  4338 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-17 13:38:51.278  3704  4338 D WifiControlHistoryProvider: query
,07-17 13:38:51.290  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:51.291  3704  4338 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-17 13:38:51.293  3704  4338 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:51.294  3704  4338 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:51.301  3704  4338 I WifiService: Wi-Fi Sharing settings has not been accessed
07-17 13:38:51.302  3704  4338 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-17 13:38:51.761  3704  3793 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=202472 mStackState=3 mControllerTxTimeMs=0 mControllerTxTimePerLevelMs=[] mControllerRxTimeMs=0 mControllerIdleTimeMs=0 mControllerEnergyUsed=0 }
,07-17 13:38:51.781 10093 10093 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-17 13:38:51.784  3704  3931 I WifiConnectivityManager: User band preference: 0
,07-17 13:38:51.786  3704  3931 D WifiConfigManager: Loading config and enabling all networks 
,07-17 13:38:51.801  3704  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-17 13:38:51.810  3704  4184 D WifiService: setWifiEnabled: true pid=9623, uid=10033
07-17 13:38:51.810  3704  4184 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-17 13:38:51.811  3704  4184 D WifiControlHistoryProvider: query
,07-17 13:38:51.822  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:51.822  3704  4184 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-17 13:38:51.823  3704  4184 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:51.824  3704  4184 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:51.829  3704  4184 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-17 13:38:51.829  3704  4184 D WifiService: unRegisterForSContext() : skip - it does not registered.
,07-17 13:38:51.835  3704  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-17 13:38:51.847  3704  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-17 13:38:51.860  3704  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-17 13:38:51.877  3704  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-17 13:38:51.892  3704  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-17 13:38:51.903  3704  3931 W WifiNetworkHistory: Upgrading network 4 to android.uid.system:1000
07-17 13:38:51.904  3704  3931 W WifiNetworkHistory: Upgrading network 0 to android.uid.system:1000
,07-17 13:38:51.904  3704  3931 W WifiNetworkHistory: Upgrading network 1 to android.uid.system:1000
07-17 13:38:51.905  3704  3931 W WifiNetworkHistory: Upgrading network 5 to android.uid.system:1000
,07-17 13:38:51.905  3704  3931 W WifiNetworkHistory: Upgrading network 2 to android.uid.system:1000
07-17 13:38:51.906  3704  3931 W WifiNetworkHistory: Upgrading network 3 to android.uid.system:1000
,07-17 13:38:51.907  3704  3931 D WifiConfigManager: loaded 0 passpoint configs
,07-17 13:38:51.913  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-17 13:38:51.913  3704  3704 D WifiHs20Service: reason: 2
07-17 13:38:51.913  3704  3959 I WifiHs20Service: Message received 5014
07-17 13:38:51.913  3704  3959 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
07-17 13:38:51.913  3704  3959 E WifiHs20Service: The changed config is NULL
,07-17 13:38:51.914  3704  3931 D WifiNative-wlan0: callSECApiBoolean - ID [301]
07-17 13:38:51.914 10093 10093 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,07-17 13:38:51.930  3704  3931 D WifiNative-wlan0: callSECApiInt - ID [65]
,07-17 13:38:51.940  3704  3704 D WifiController: [FCC]setFccChannel() is called !!!
,07-17 13:38:51.941  3704  3704 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
,07-17 13:38:51.941  3704  3704 D WifiStateMachine: setFccChannel: channel = 0
07-17 13:38:51.941  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
07-17 13:38:51.943  3704  3958 D HS20StateMachine: WIFI_STATE_ENABLED
07-17 13:38:51.943  3704  3958 D HS20StateMachine: reloadCredentialsToSupplicant
07-17 13:38:51.944  3704  3958 D WifiHs20DBHandler: getCredentialIds
07-17 13:38:51.944  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
07-17 13:38:51.945  3704  3959 I WifiHs20Service: Message received 5011
,07-17 13:38:51.952  3704  3931 D WifiNative-wlan0: callSECApiBoolean - ID [13]
07-17 13:38:51.952  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=3 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,07-17 13:38:51.953 10093 10093 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-17 13:38:51.956  3704  3704 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
07-17 13:38:51.957  3704  4257 D SLocation: checkWifiInfo
07-17 13:38:51.957  3704  4257 W SLocation: No Active Data Connection
,07-17 13:38:51.957  3704  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,07-17 13:38:51.959  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:51.962  3704  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
07-17 13:38:51.965  9764  9764 D A2dpService: A2dpService - WIFI_STATE_ENABLED
07-17 13:38:51.965  9764  9764 I BluetoothA2dpServiceJni: Attempting to set busy level
,07-17 13:38:51.972  9623  9623 D BluetoothAdapter: STATE_ON
,07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-17 13:38:51.976  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-17 13:38:51.976  9690  9690 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
07-17 13:38:51.976  9690  9690 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
07-17 13:38:51.978  3704  3958 D MountService: getExternalStorageMountMode : 1
07-17 13:38:51.979  3704  3958 D MountService: getExternalStorageMountMode : 3
07-17 13:38:51.979  3704  3958 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10114, packageName : com.samsung.hs20provider
,07-17 13:38:51.982  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:51.985  9623  9623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
07-17 13:38:52.005 10112 10112 E Zygote  : v2
07-17 13:38:52.005 10112 10112 I libpersona: KNOX_SDCARD checking this for 10114
07-17 13:38:52.005 10112 10112 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:52.007 10112 10112 E Zygote  : accessInfo : 0
07-17 13:38:52.007  3704  3958 I ActivityManager: Start proc 10112:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
07-17 13:38:52.010  3704  3931 D WifiNative-HAL: Setting external_sim to 1
07-17 13:38:52.012  9690  9690 D SecurityLogAgent: NetworkReceiver : SendSecurityReport is off
07-17 13:38:52.013  3704  3931 D wifi    : setting dfs flag to true, 0x7d03737960
07-17 13:38:52.013  3704  3931 D WifiStateMachine: Setting OUI to DA-A1-19
07-17 13:38:52.014  3704  3931 D wifi    : setting scan oui 0x7d03737960
07-17 13:38:52.014  3704  3931 D WifiHAL : Sending mac address OUI
07-17 13:38:52.015  3704  3931 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
07-17 13:38:52.015  3704  3931 E WifiStateMachine: SupplicantStarted - enter() isAirplaneModeEnabled !!  
07-17 13:38:52.015  3704  3931 D WifiCountryCode: [setCountryCodeNative] Default CSC Country Code : PL
07-17 13:38:52.017 10112 10112 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:52.019 10112 10112 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
07-17 13:38:52.026  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.026  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.027  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.027  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.027  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.028  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.029  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.029  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.029  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.029  3704  4753 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.041  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.042  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.042  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.042  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.042  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.042  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.042  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.042  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.043  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.043  3704  4183 W NetworkIdentity: Active mobile network without subscriber!
,07-17 13:38:52.056  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.056  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.057  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.057  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.057  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.057  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.057  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.057  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.057  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.057  3704  4182 W NetworkIdentity: Active mobile network without subscriber!
07-17 13:38:52.058 10112 10112 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:52.059 10112 10112 D ActivityThread: Added TimaKeyStore provider
07-17 13:38:52.064 10093 10093 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
07-17 13:38:52.064  3704  9909 I ActivityManager: DSS on for com.samsung.hs20provider and scale is 1.0
07-17 13:38:52.067  3704  3931 D WifiCountryCode: Succeeded to set country code to: PL
07-17 13:38:52.067  3704  3931 D wifi    : android_net_wifi_get_firmware_version = 0x7d03737960
07-17 13:38:52.067  3704  3931 E WifiHAL : Failed to register debug response; result = -95
07-17 13:38:52.067  3704  3931 E wifi    : Fail to get Firmware version
07-17 13:38:52.068  3704  3931 D wifi    : android_net_wifi_get_driver_version = 0x7d03737960
07-17 13:38:52.068  3704  3931 E WifiHAL : Failed to register debug response; result = -95
07-17 13:38:52.068  3704  3931 E wifi    : Fail to get driver version
07-17 13:38:52.068  3704  3931 D wifi    : android_net_wifi_set_log_handler = 0x7d03737960
07-17 13:38:52.068  3704  3931 D wifi    : android_net_wifi_get_ring_buffer_status = 0x7d03737960
07-17 13:38:52.068  3704  3931 E WifiHAL : Failed to register debug response; result = -95
07-17 13:38:52.068  3704  3931 E WifiLogger: no ring buffers found
07-17 13:38:52.068  3704  3931 D WifiHAL : Start get packet fate command
07-17 13:38:52.068  3704  3931 D WifiHAL : createRequest Monitor packet fate request
07-17 13:38:52.068  3704  3931 E WifiHAL : Failed to register get pkt fate response; result = -95
07-17 13:38:52.068  3704  3931 E WifiLogger: Failed to start packet fate monitoring
07-17 13:38:52.071  3704  4017 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
07-17 13:38:52.084 10112 10112 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
07-17 13:38:52.096 10112 10112 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:52.098  3704  3927 D WifiP2pService: P2pDisabledState{ what=131203 }
07-17 13:38:52.099  3704  3931 D wifi    : android_net_wifi_setLinkLayerStats: 1
07-17 13:38:52.099  3704  3931 I WifiConnectivityManager: Set WiFi enabled
07-17 13:38:52.099  3704  3931 E WifiStateMachine: ConnectModeState - enter !! - mIsSupportGeofence !!
07-17 13:38:52.099  3704  3931 D WifiStateMachine: Remembered scan first is enabled
07-17 13:38:52.100  3704  3704 I WifiStateMachine: initGeofence
07-17 13:38:52.100  3704  3961 I WifiScanningService: wifi driver loaded with scan capabilities: max buckets=16
07-17 13:38:52.101  3704  3931 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@1235601
07-17 13:38:52.101  3704  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
07-17 13:38:52.102  3704  3931 E wifi    : failed to get channel list : -95
07-17 13:38:52.102  3704  3931 D WifiConfigManager: getChannelsForBand(WifiScanner.WIFI_BAND_24_GHZ) is null. So set default 2.4GHz 14 channels.
07-17 13:38:52.105  3704  3931 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170717T133900 - CU:1000/CP:3704
07-17 13:38:52.105  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133900, SetElapsed=210846, nowELAPSED=202849
07-17 13:38:52.113  3300  3777 D CommandListener: Setting iface cfg
07-17 13:38:52.114  3300  3777 D CommandListener: Trying to bring up p2p0
07-17 13:38:52.115  3300  3769 D Netd    : Iface p2p0 link up
07-17 13:38:52.117 10093 10093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-17 13:38:52.117 10093 10093 I wpa_supplicant: P2P: Current p2p state = IDLE
07-17 13:38:52.119  3704  3811 D Tethering: interfaceLinkStateChanged p2p0, true
07-17 13:38:52.119  3704  3811 D Tethering: interfaceStatusChanged p2p0, true
07-17 13:38:52.121  3704  3927 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-17 13:38:52.122  3704  3927 D SecContentProvider: insert(), uri = 2
07-17 13:38:52.123 10093 10093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-17 13:38:52.123 10112 10124 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
07-17 13:38:52.124 10112 10124 D HotspotProvider: CREDENTIAL
07-17 13:38:52.124 10112 10124 D HotspotProvider: No prepend tags
07-17 13:38:52.129  3704  3927 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:52.129  3704  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T133907 - CU:1000/CP:3704
07-17 13:38:52.129  3704  3927 D WifiP2pService: P2pEnablingState
07-17 13:38:52.130  3704  3927 D WifiP2pService: P2pEnablingState{ what=147457 }
07-17 13:38:52.130  3704  3927 D WifiP2pService: P2p socket connection successful
07-17 13:38:52.131  3704  3931 D WifiStateMachine: setFccChannelNative: channel = 0
07-17 13:38:52.131  3704  3931 D WifiNative-wlan0: callSECApiInt - ID [230]
07-17 13:38:52.131  3704  3927 D WifiP2pService: P2pEnabledState
,07-17 13:38:52.132  3704  3927 D SecContentProvider: insert(), uri = 2
07-17 13:38:52.133  3704  3927 D SecContentProvider: called from android.uid.system:1000
07-17 13:38:52.135  3704  3927 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-17 13:38:52.138  3704  3963 D ConnectivityService: ignoring duplicate network state non-change
07-17 13:38:52.140  3704  3931 D WifiNative-wlan0: callSECApiVoid - ID [311]
07-17 13:38:52.140  3704  3813 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-17 13:38:52.140  3704  3813 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
07-17 13:38:52.140  3704  3813 D WifiDisplayController: disconnect
07-17 13:38:52.141  3704  3813 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
07-17 13:38:52.141  3704  3813 D WifiDisplayAdapter: onFeatureStateChanged empty
07-17 13:38:52.141  3704  3813 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-17 13:38:52.146  3704  3958 D HS20StateMachine: updateNumOfHS20Cred, numOfHS20Cred = 1
07-17 13:38:52.146  3704  3958 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
07-17 13:38:52.147  3704  3958 D HS20StateMachine: enter : DiscoveringState
07-17 13:38:52.148  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-17 13:38:52.148 10093 10093 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
07-17 13:38:52.152 10093 10093 I wpa_supplicant: P2P: Set Samsung Discovery name = 
07-17 13:38:52.154  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-17 13:38:52.158 10063 10063 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-17 13:38:52.159 10063 10063 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
07-17 13:38:52.159 10063 10063 D FileShare: Outbound.stopDelayTimer - 
07-17 13:38:52.159  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:52.162  3704  3704 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-17 13:38:52.164  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:52.165  4044  4350 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
07-17 13:38:52.167  3704  3704 D SLocation: system
07-17 13:38:52.167  3704  3704 D SLocation: startGeofence ID = 1
,07-17 13:38:52.182  4783  4840 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 3ms lastUpdatedAfter : 4699 ms mFlush_time_threasold : 2000 mCurrentSize : 184
07-17 13:38:52.182  3704  3927 E WifiP2pService: Failed to set my phone number info into probe response
,07-17 13:38:52.186  3704  3927 D WifiNative-HAL: p2pGetDeviceAddress
,07-17 13:38:52.186  3704  3927 D WifiNative-HAL: p2pGetDeviceAddress returning 4e:66:41:a9:15:41
,07-17 13:38:52.187  3704  3927 D WifiP2pService: DeviceAddress: 4e:15:41
07-17 13:38:52.188  3704  3813 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:15:41
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  primary type: 10-0050F204-5
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  secondary type: null
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  wps: 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  grpcapab: 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  devcapab: 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  status: 3
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  WFD CtrlPort: 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  WFD MaxThroughput: 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  groupownerAddress: null
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  GOdeviceName: null
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  interfaceAddress: 
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  SConnectInfo : null
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  contactInfoHash : null
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  ssDevInfo : 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  iconIdx : 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  semSamsungDeviceType : 0
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  serviceData : null
07-17 13:38:52.188  3704  3813 D WifiDisplayController:  fw_invite : 0
,07-17 13:38:52.196  3704  3927 D WifiP2pService: sending p2p persistent groups changed broadcast
07-17 13:38:52.197  3704  3927 D WifiP2pService: InactiveState
,07-17 13:38:52.197  3704  3927 D WifiP2pService: InactiveState{ what=143376 }
07-17 13:38:52.197  3704  3927 D WifiP2pService: P2pEnabledState{ what=143376 }
07-17 13:38:52.197  3704  3927 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,07-17 13:38:52.204  3704  3704 D SLocation: addReceiver type4
07-17 13:38:52.204  3704  3704 D SLocation: already exsit record!
,07-17 13:38:52.235  3704  3704 D SLocation: setPendingIntent
,07-17 13:38:52.235  3704  3704 D SLocation: setStatus ID = 1 / status = 3
,07-17 13:38:52.306  3704  3704 D SLocation: geofence id (1) detected : 0
,07-17 13:38:52.306  3704  3704 D WifiStateMachine: startGeofence() - id : 1
07-17 13:38:52.307  3704  3704 D RttService: SCAN_AVAILABLE : 3
07-17 13:38:52.307  3704  3962 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-17 13:38:52.313  3704  3704 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
07-17 13:38:52.313  3704  3704 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,07-17 13:38:52.314  4044  4055 D TelephonyProvider: query: match = 7
,07-17 13:38:52.317  3704  3704 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,07-17 13:38:52.322  3704  3704 D SLocation: PendingIntent onSendFinished id:1
,07-17 13:38:52.340  9623  9724 D BluetoothAdapter: STATE_ON
,07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-17 13:38:52.346  9623  9724 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-17 13:38:52.347  9623  9687 D BluetoothAdapter: enable()
,07-17 13:38:52.358  9764  9776 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
07-17 13:38:52.359  9764  9776 D AdapterProvider: query
,07-17 13:38:52.385  9764  9776 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@9d9b968
,07-17 13:38:52.388  9764  9776 D BluetoothAdapterService: updateEvent - already set, update
07-17 13:38:52.389  9764  9776 W BluetoothAdapterService: updateEvent - alreadySet is true
,07-17 13:38:52.389  9764  9776 D AdapterProvider: update
,07-17 13:38:52.395  9764  9776 E BluetoothAdapterService: updateEvent - update success 1
,07-17 13:38:52.397  9623  9687 D BluetoothAdapter: enable(): BT is already enabled..!
,07-17 13:38:52.404  3704  6511 D WifiService: setWifiEnabled: true pid=9623, uid=10033
07-17 13:38:52.404  3704  6511 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,07-17 13:38:52.405  3704  6511 D WifiControlHistoryProvider: query
,07-17 13:38:52.413  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:52.413  3704  6511 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,07-17 13:38:52.414  3704  6511 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:52.415  3704  6511 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,07-17 13:38:52.419  3704  6511 I WifiService: Wi-Fi Sharing settings has not been accessed
,07-17 13:38:52.420  3704  6511 D WifiService: unRegisterForSContext() : skip - it does not registered.
07-17 13:38:52.420  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-17 13:38:52.421  9623  9687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-17 13:38:52.421  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-17 13:38:52.421  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-17 13:38:52.421  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-17 13:38:52.421  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e21f32 removed from the list
07-17 13:38:52.421  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e21f32 removed from the list
07-17 13:38:52.421  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-17 13:38:52.421  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@374b483 removed from the list
07-17 13:38:52.421  9623  9687 D io.jxcore.node.ConnectivityMonitor: stop
07-17 13:38:52.422  9623  9687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-17 13:38:52.422  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-17 13:38:52.425  9623  9687 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,07-17 13:38:52.430  9623 10126 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
07-17 13:38:52.430  9623 10126 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-17 13:38:52.698  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:38:52.700 10093 10093 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,07-17 13:38:52.702  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
,07-17 13:38:52.702  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:52.705  3704  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@1b0542b
,07-17 13:38:52.768  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 13:38:52.773  3704  3931 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=4 roam=false
,07-17 13:38:52.775  3704  3931 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=4
,07-17 13:38:52.779  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:52.794  3704  3931 D WifiConfigStore: saveNetwork skipInternetCheck
,07-17 13:38:52.803  3704  3931 D WifiConfigStore: readNetwork skipInternetCheck
,07-17 13:38:52.818  3704 10128 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-17 13:38:52.818  3704 10128 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-17 13:38:52.819  3704 10128 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-17 13:38:52.819  3704 10128 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
,07-17 13:38:52.819  3704 10128 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-17 13:38:52.820  3704 10128 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-17 13:38:52.820  3704 10128 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-17 13:38:52.820  3704 10128 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-17 13:38:52.820  3704 10128 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-17 13:38:52.820  3704 10128 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-17 13:38:52.821  3704 10128 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-17 13:38:52.821  3704 10128 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,07-17 13:38:52.825  3704  3931 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=4
,07-17 13:38:52.825  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
,07-17 13:38:52.825  3704  3704 D WifiHs20Service: reason: 2
07-17 13:38:52.826  3704  3959 I WifiHs20Service: Message received 5014
07-17 13:38:52.826  3704  3959 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-17 13:38:52.829  3704 10129 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
07-17 13:38:52.829  3704 10129 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
,07-17 13:38:52.830  3704 10129 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-17 13:38:52.830  3704 10129 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-17 13:38:52.830 10093 10093 I wpa_supplicant: Trying to associate with F4.E6.C2 (SSID='NG700' freq=2472 MHz)
07-17 13:38:52.830  3704 10129 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-17 13:38:52.830  3704 10129 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-17 13:38:52.831  3704 10129 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-17 13:38:52.831  3704 10129 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-17 13:38:52.831  3704 10129 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-17 13:38:52.831  3704 10129 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-17 13:38:52.831  3704  3931 D SecContentProvider: insert(), uri = 2
07-17 13:38:52.831  3704 10129 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-17 13:38:52.831  3704 10129 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-17 13:38:52.832  3704  3931 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:52.849  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 13:38:52.859  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:52.933  3300  3769 D Netd    : Iface wlan0 link up
07-17 13:38:52.933  3300  3769 D Netd    : Iface wlan0 link up
07-17 13:38:52.934  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:38:52.939  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
,07-17 13:38:52.939  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:52.939  3300  3772 D EnterpriseController: netId is 0
,07-17 13:38:52.939  3300  3772 D Netd    : getNetworkForDns: using netid 0 for uid 10033
07-17 13:38:52.940  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-17 13:38:52.944  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:38:52.944  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:52.946  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:38:52.946  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:52.946  9623 10130 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
07-17 13:38:52.947  9623 10130 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-17 13:38:52.947  9623 10130 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:38:52.948  9623 10130 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:38:52.948  9623 10126 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,07-17 13:38:52.948  9623 10130 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,07-17 13:38:52.949  9623 10132 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 219, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.949  9623 10132 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:52.949  9623 10132 D io.jxcore.node.StreamCopyingThread:  id: 74
07-17 13:38:52.949  9623 10126 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
07-17 13:38:52.950  9623 10126 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 220, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread:  id: 74
07-17 13:38:52.953  9623 10126 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 220, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread:  id: 74
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread:  id: 74
,07-17 13:38:52.953  9623 10133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-17 13:38:52.954  9623 10133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-17 13:38:52.954  9623 10133 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,07-17 13:38:52.954 10093 10093 I wpa_supplicant: Associated with F4.E6.C2
,07-17 13:38:52.954  9623 10133 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,07-17 13:38:52.954  9623 10133 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-17 13:38:52.954  9623 10133 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
07-17 13:38:52.954  9623 10133 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 220, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.954  9623 10133 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:52.954  9623 10133 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-17 13:38:52.954 10093 10093 I wpa_supplicant: wlan0: CTRL-EVENT-SUBNET-STATUS-UPDATE status=0
07-17 13:38:52.954  9623 10132 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 219, thread name: IncomingSocketThread/Sender): Socket closed
07-17 13:38:52.955  9623 10134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 221, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.955  9623 10134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:52.955  9623 10134 D io.jxcore.node.StreamCopyingThread:  id: 75
07-17 13:38:52.955  9623 10132 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 219, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.955  9623 10132 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:52.955  9623 10132 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-17 13:38:52.955  9623 10132 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-17 13:38:52.955  9623 10132 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-17 13:38:52.956  9623 10134 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 221, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.956  9623 10134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:52.956  9623 10134 D io.jxcore.node.StreamCopyingThread:  id: 75
07-17 13:38:52.957  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-17 13:38:52.958  9623 10132 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 219, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.958  9623 10132 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:52.958  9623 10132 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-17 13:38:52.958  9623 10134 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.958  9623 10134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:52.958  9623 10134 D io.jxcore.node.StreamCopyingThread:  id: 75
07-17 13:38:52.958  9623 10134 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,07-17 13:38:52.958  9623 10134 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-17 13:38:52.959  9623 10134 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-17 13:38:52.959  9623 10134 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-17 13:38:52.959  9623 10134 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-17 13:38:52.959  9623 10134 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
07-17 13:38:52.959  9623 10134 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 221, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.959  9623 10134 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:52.959  9623 10134 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-17 13:38:52.962  9623 10126 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 222, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread:  id: 75
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 222, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread:  id: 75
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread:  id: 75
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-17 13:38:52.963  9623 10135 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-17 13:38:52.967  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-17 13:38:52.967  9623 10135 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-17 13:38:52.967  9623 10135 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-17 13:38:52.967  9623 10135 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-17 13:38:52.967  9623 10135 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
07-17 13:38:52.967  9623 10135 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
07-17 13:38:52.968  9623 10135 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 222, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:52.968  9623 10135 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:52.968  9623 10135 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
07-17 13:38:52.973  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:52.984 10093 10093 I wpa_supplicant: WPA: Key negotiation completed with F4.E6.C2 [PTK=CCMP GTK=CCMP]
07-17 13:38:52.984 10093 10093 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.E6.C2 completed [id=4 id_str=%7B%22creatorUid%22%3A%221000%22%2C%22configKey%22%3A%22%5C%22NG700%5C%22WPA_PSK%22%7D]
07-17 13:38:52.984  3300  3769 D Netd    : Iface wlan0 link up
07-17 13:38:52.984  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-17 13:38:52.987  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:38:52.987  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:38:52.987  3704  3931 D WifiNative-wlan0: callSECApiVoid - ID [50]
07-17 13:38:52.993  3704  3931 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@1c9f8a5
07-17 13:38:52.995  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T135549, SetElapsed=1219750, nowELAPSED=203738
07-17 13:38:52.996  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-17 13:38:52.997  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-17 13:38:52.998  3704  3959 I WifiHs20Service: Message received 5007
07-17 13:38:52.999  3704  4017 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-17 13:38:53.001  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-17 13:38:53.004  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-17 13:38:53.005  9764  9764 D BluetoothUtils: readSalesCode :: sales code is XEO
07-17 13:38:53.006  3704  3931 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: mIsSupportAdvancedCaptivePortal is true
07-17 13:38:53.006  3704  3931 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-17 13:38:53.006  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=69632 obj=com.android.internal.util.AsyncChannel@7b12d91 target=com.android.internal.util.StateMachine$SmHandler }
07-17 13:38:53.007  3704 10136 D NetworkMonitor: Async - Half connection with WWSM established
07-17 13:38:53.007  3704  4017 D WifiWatchdogStateMachine: Async - Half connection with NetworkMonitor established
07-17 13:38:53.007  3704  4017 D WifiWatchdogStateMachine: Async - Full connection with NetworkMonitor established
07-17 13:38:53.010  3704  3963 D ConnectivityService: Got NetworkAgent Messenger
07-17 13:38:53.011  3704  3963 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-17 13:38:53.011  3704  3963 D ConnectivityService: NetworkAgent connected
07-17 13:38:53.012  3704  3927 D WifiP2pService: InactiveState{ what=143375 }
07-17 13:38:53.013  3704  3927 D WifiP2pService: P2pEnabledState{ what=143375 }
07-17 13:38:53.013  3704  3931 D WifiHAL : Getting APF capabilities, halHandle = 0x7d03737960
07-17 13:38:53.013  3704  3931 I WifiHAL : 
07-17 13:38:53.013  3704  3931 I WifiHAL : createRequest: APF get capabilities request
07-17 13:38:53.014  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:53.015  3704  3931 D WifiHAL : In SetAPFCommand::handleResponse
07-17 13:38:53.015  3704  3931 D WifiHAL : Id = 0, subcmd = 0, len = 16
07-17 13:38:53.015  3704  3931 D WifiHAL : Response recieved for get packet filter capabilities command
07-17 13:38:53.015  3704  3931 I WifiHAL : APF version is 2
07-17 13:38:53.015  3704  3931 I WifiHAL : APF max len is 2048
07-17 13:38:53.015  3704  3931 I WifiHAL : Done!
07-17 13:38:53.015  3704  3931 D WifiHAL : Getting APF capability, version = 2, max_len = 2048
07-17 13:38:53.016  3704  3931 D wifi    : APF version supported: 2
07-17 13:38:53.016  3704  3931 D wifi    : Maximum APF program size: 2048
07-17 13:38:53.018  3704  3931 D WifiStateMachine: Start Dhcp Watchdog 2
07-17 13:38:53.024  9946  9946 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-17 13:38:53.024  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
07-17 13:38:53.037  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:53.054  3704  3931 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true)
07-17 13:38:53.054  3704  3963 D ConnectivityService: ignoring duplicate network state non-change
07-17 13:38:53.055  3704  3931 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true) returned: -95
07-17 13:38:53.055  3704  3963 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:53.055  3704  3963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-17 13:38:53.055  3704  3963 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
,07-17 13:38:53.055  3704  3931 D WifiHAL : Setting APF program, halHandle = 0x7d03737960
07-17 13:38:53.055  3704  3931 I WifiHAL : 
07-17 13:38:53.055  3704  3931 I WifiHAL : createRequest: APF set program request
,07-17 13:38:53.056  3704  3931 I WifiHAL : Done!
,07-17 13:38:53.057  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 13:38:53.060  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-17 13:38:53.061  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-17 13:38:53.061  9960  9960 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-17 13:38:53.062  9960  9960 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-17 13:38:53.063  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-17 13:38:53.067  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:38:53.072  9974  9974 I PhoneErrorReceiver: onReceive
,07-17 13:38:53.080  9987  9987 I usagelog: received in receiver
07-17 13:38:53.080  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-17 13:38:53.080  9987  9987 I KnoxUsageLogPro: premStatus:2
,07-17 13:38:53.081  9987  9987 I KnoxUsageLogPro: isEulaShown : false
07-17 13:38:53.081  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-17 13:38:53.085 10093 10093 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-17 13:38:53.098  3704 10138 D ApfFilter: (wlan0): begin monitoring
,07-17 13:38:53.129  3704  3936 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170717T133929 - CU:1000/CP:3704
07-17 13:38:53.129  3704  3936 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133929, SetElapsed=239871, nowELAPSED=203873
,07-17 13:38:53.131  3704  3963 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-17 13:38:53.131  3704  4017 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-17 13:38:53.131  3704  4017 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-17 13:38:53.132  3704  4017 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
07-17 13:38:53.132  3704  4017 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-17 13:38:53.133  3704  4017 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-17 13:38:53.172  3704  3936 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170717T133929 - CU:1000/CP:3704
,07-17 13:38:53.304  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=start target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:53.305  3704  3927 D WifiP2pService: InactiveState{ what=143375 }
,07-17 13:38:53.306  3704  3927 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-17 13:38:53.318  3704 10139 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170717T133855 - CU:1000/CP:3704
07-17 13:38:53.319  3704 10139 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133855, SetElapsed=206118, nowELAPSED=204063
07-17 13:38:53.319  3704 10139 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-17 13:38:53.320  3704 10139 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@f9e2983
,07-17 13:38:53.323  3704 10139 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133929, SetElapsed=239871, nowELAPSED=204066
,07-17 13:38:53.329  3704 10139 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170717T133911 - CU:1000/CP:3704
07-17 13:38:53.329  3704 10139 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133911, SetElapsed=222067, nowELAPSED=204073
,07-17 13:38:53.339  3704 10139 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170717T133855 - CU:1000/CP:3704
07-17 13:38:53.340  3704 10139 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133855, SetElapsed=206103, nowELAPSED=204084
,07-17 13:38:53.341  3704 10139 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
07-17 13:38:53.341  3704 10139 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@d4ab57e
07-17 13:38:53.341  3704  3936 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@eb0083d
,07-17 13:38:53.343  3704 10139 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133911, SetElapsed=222067, nowELAPSED=204087
07-17 13:38:53.343  3704 10139 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@b99eb39
,07-17 13:38:53.347  3704 10139 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133929, SetElapsed=239871, nowELAPSED=204091
,07-17 13:38:53.348  3704  3927 D WifiP2pService: InactiveState{ what=143375 }
07-17 13:38:53.349  3704  3927 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-17 13:38:53.354  3300  3777 D CommandListener: Setting iface cfg
07-17 13:38:53.354  3704  4017 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
07-17 13:38:53.354  3704  3963 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
,07-17 13:38:53.356  3704  3963 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
07-17 13:38:53.357  3704  4017 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-17 13:38:53.358  3704  4017 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-17 13:38:53.359  3704  4017 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
07-17 13:38:53.359  3704  4017 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-17 13:38:53.360  3704  4017 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-17 13:38:53.363  3704  3931 D WifiHAL : Setting APF program, halHandle = 0x7d03737960
07-17 13:38:53.363  3704  3931 I WifiHAL : 
07-17 13:38:53.363  3704  3931 I WifiHAL : createRequest: APF set program request
07-17 13:38:53.365  3704  3936 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@98fe594
07-17 13:38:53.365  3704  3931 I WifiHAL : Done!
,07-17 13:38:53.367  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,07-17 13:38:53.368  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-17 13:38:53.369  3704  3959 I WifiHs20Service: Message received 5007
,07-17 13:38:53.370  3704  4017 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,07-17 13:38:53.374  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
07-17 13:38:53.375  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:53.378  9764  9764 D BluetoothUtils: readSalesCode :: sales code is XEO
,07-17 13:38:53.383  3704 10139 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170717T192429 - CU:1000/CP:3704
,07-17 13:38:53.394  9946  9946 I [RBL] ServiceReceiver: @onReceive - rawData : null
,07-17 13:38:53.397  3704 10139 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170718T000853 - CU:1000/CP:3704
,07-17 13:38:53.407  3704 10139 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20170718T013853 - CU:1000/CP:3704
07-17 13:38:53.407  3704 10139 D DhcpClient: Scheduling renewal in 20735s
07-17 13:38:53.407  3704 10139 D DhcpClient: Scheduling rebind in 37799s
07-17 13:38:53.407  3704 10139 D DhcpClient: Scheduling expiry in 43199s
,07-17 13:38:53.408  3704  3936 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T135549, SetElapsed=1219750, nowELAPSED=204152
,07-17 13:38:53.409  3704  3963 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
,07-17 13:38:53.409  3704  3963 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:53.410  3704  4017 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-17 13:38:53.410  3704  3931 E WifiNative-HAL: setBssidBlacklist cmd 2 size 0
07-17 13:38:53.410  3704  4017 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-17 13:38:53.411  3704  3931 D wifi    : configure BSSID black list request [4] = 0x7d03737960
07-17 13:38:53.411  3704  3931 D wifi    : Added 0 bssids
07-17 13:38:53.411  3704  3931 E WifiHAL : Failed to execute bssid blacklist request, result = -95
07-17 13:38:53.411  3704  3931 D WifiStateMachine: sendConnectedState - setManualConnection: false!
07-17 13:38:53.412  3704  3963 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-17 13:38:53.416  3704  3963 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
07-17 13:38:53.416  3704  4017 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-17 13:38:53.416  3704  3963 D ConnectivityService: Adding iface wlan0 to network 503
,07-17 13:38:53.417  3704  4017 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-17 13:38:53.418  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-17 13:38:53.419  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-17 13:38:53.419  9960  9960 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,07-17 13:38:53.420  9960  9960 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,07-17 13:38:53.428  9974  9974 I PhoneErrorReceiver: onReceive
,07-17 13:38:53.433  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-17 13:38:53.434  3704  3931 D SecContentProvider: insert(), uri = 2
,07-17 13:38:53.435  3704  3704 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-17 13:38:53.435  3704  3931 D SecContentProvider: called from android.uid.system:1000
,07-17 13:38:53.436  3704  3931 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-17 13:38:53.437  3704  3704 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
07-17 13:38:53.438  3704  3704 D HS20StateMachine: SSID : "NG700"
07-17 13:38:53.438  3704  3704 D HS20StateMachine: NetId : 4
07-17 13:38:53.438  3704  3704 D HS20StateMachine: checkifOSUAP  null
07-17 13:38:53.438  3704  3931 I WifiConnectivityManager: scheduleWatchdogTimer
07-17 13:38:53.438  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
07-17 13:38:53.439  3704  3959 I WifiHs20Service: Message received 5007
07-17 13:38:53.440  3704  4017 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
07-17 13:38:53.440  3246  3246 E audit   : type=1320 audit(1500291533.431:238): 
,07-17 13:38:53.443  4044  4044 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,07-17 13:38:53.445  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,07-17 13:38:53.452  9764  9764 D BluetoothUtils: readSalesCode :: sales code is XEO
07-17 13:38:53.454  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T135049, SetElapsed=920704, nowELAPSED=204198
07-17 13:38:53.454  3704  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T135853 - CU:1000/CP:3704
07-17 13:38:53.454  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T135853, SetElapsed=1404182, nowELAPSED=204198
07-17 13:38:53.457  9987  9987 I usagelog: received in receiver
07-17 13:38:53.457  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-17 13:38:53.457  9987  9987 I KnoxUsageLogPro: premStatus:2
,07-17 13:38:53.458  9987  9987 I KnoxUsageLogPro: isEulaShown : false
07-17 13:38:53.459  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-17 13:38:53.459  3246  3246 E audit   : type=1320 audit(1500291533.451:239): 
07-17 13:38:53.463  3704  3963 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,07-17 13:38:53.464  3704  3931 D WifiStateMachine: isFindLocationId() - Location Id : 1
,07-17 13:38:53.468  3704  3963 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
07-17 13:38:53.470  3704  3963 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
07-17 13:38:53.472  3704  3963 D ConnectivityService: Setting DNS servers for network 503 to [/192.168.1.1]
07-17 13:38:53.474  3300  3776 D ResolverController: DNSDBG::server[0] 192.168.1.1
07-17 13:38:53.474  3300  3776 D ResolverController: DNSDBG::netId 503 search_domain lan
07-17 13:38:53.474  3300  3776 D ResolverController: DNSDBG::netId 503 searchDomains lan
07-17 13:38:53.474  3300  3776 D ResolverController: DNSDBG::server[0] 192.168.1.1
,07-17 13:38:53.476  3704  3963 V NetworkStats: updateIfacesLocked()
07-17 13:38:53.476  3704  3963 V NetworkStats: performPollLocked(flags=0x1)
07-17 13:38:53.477  3704  3963 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.484  3704  3931 D WifiGeofenceDBHelper: update() - 1*1500291533464
07-17 13:38:53.488  9932 10144 I DatabaseHelper: android.app.Application@e921625
07-17 13:38:53.489  9932 10144 I DatabaseHelper: Create a DatabaseHelper
07-17 13:38:53.489  3704  3963 V NetworkStats: performPollLocked() took 13ms
07-17 13:38:53.489  3704  3963 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.491  9946  9946 I [RBL] ServiceReceiver: @onReceive - rawData : null
07-17 13:38:53.491  3704  3963 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-17 13:38:53.491  3704  3963 D ConnectivityService: Not required to send intent.
07-17 13:38:53.491  9946  9946 W [RBL] ServiceReceiver: @onReceive - NETWORK_STATE_CHANGED_ACTION
07-17 13:38:53.491  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.491  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.492  3704  3963 V NetworkStats: updateIfacesLocked()
07-17 13:38:53.492  3704  3963 V NetworkStats: performPollLocked(flags=0x1)
07-17 13:38:53.492  3704  3963 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.499  3704  3963 V NetworkStats: performPollLocked() took 7ms
07-17 13:38:53.499  3704  3963 D NtpTrustedTime: currentTimeMillis() cache hit
,07-17 13:38:53.503  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-17 13:38:53.503  3704  3963 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
07-17 13:38:53.503  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
07-17 13:38:53.503  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: register CaptivePortalReceiver
07-17 13:38:53.504  3704  3963 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-17 13:38:53.504  3704  3963 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:53.504  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.504  3704  3963 D ConnectivityService: currentScore = 0, newScore = 20
07-17 13:38:53.504  3704  3963 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
07-17 13:38:53.504  3704  3963 D ConnectivityService:    accepting network in place of null
07-17 13:38:53.504  3704  3963 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.510  9932 10144 I DataManager: checkResolution
,07-17 13:38:53.511  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.512  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.512  9932 10144 I DataManager: Create a DataManager
07-17 13:38:53.514  3704  4017 D WifiWatchdogStateMachine: Connected - Move to CaptivePortalState
,07-17 13:38:53.527  3704  4017 E WifiWatchdogStateMachine: current state: com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalState@e1aea89
,07-17 13:38:53.530  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:53.530  3704  4026 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-17 13:38:53.530  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.530  3704  4026 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-17 13:38:53.530  3704  4026 D Ethernet: evalRequest
07-17 13:38:53.530  3704  4026 D Ethernet:   done
07-17 13:38:53.530  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.530  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:53.530  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.531  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.531  3704  3927 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.531  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.531  3704  3927 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-17 13:38:53.531  3704  3927 D WIFI_P2P: evalRequest
07-17 13:38:53.531  3704  3927 D WIFI_P2P:   done
07-17 13:38:53.531  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.531  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.531  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.531  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.531  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.532  3704  3963 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-17 13:38:53.533  9946  9946 D [RBL] StoredRequest: @Oncreate
07-17 13:38:53.534  9946  9946 I [RBL] GuardedSuspension: @getInstance
07-17 13:38:53.535  9946  9946 I [RBL] GuardedSuspension: GuardedSuspension
07-17 13:38:53.535  3704  3,931 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-17 13:38:53.536  3704  4017 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-17 13:38:53.537  3704  3931 D SLocation: system
07-17 13:38:53.537  3704  3931 D SLocation: startGeofence ID = 1
07-17 13:38:53.544  9946  9946 I [RBL] GuardedSuspension: @getInstance
07-17 13:38:53.545  3246  3246 E audit   : type=1320 audit(1500291533.531:240): 
07-17 13:38:53.545  3704  4017 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
07-17 13:38:53.545  9946  9946 D [RBL] RblSAccountUtil: @open
07-17 13:38:53.545  9946  9946 D [RBL] RblSAccountUtil:     - client : 1
07-17 13:38:53.546  4044  4044 D PhoneSwitcherNetworkRequstListener: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.546  3704  4017 D WifiWatchdogStateMachine: start to check Captive portal
07-17 13:38:53.547  4044  4044 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-17 13:38:53.547  4044  4044 D PhoneSwitcherNetworkRequstListener: evalRequest
07-17 13:38:53.547  4044  4044 D PhoneSwitcherNetworkRequstListener:   done
07-17 13:38:53.547  9932  9932 W RequestHeader: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=3
07-17 13:38:53.548  9932  9932 W RequestHeader: java.lang.StringIndexOutOfBoundsException: length=0; index=3
07-17 13:38:53.555  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
07-17 13:38:53.555  9932  9932 W RequestHeaderForV3: java.lang.StringIndexOutOfBoundsException: length=0; regionStart=0; regionLength=3
07-17 13:38:53.555  9932  9932 W RequestHeaderForV3: java.lang.StringIndexOutOfBoundsException: length=0; index=3
07-17 13:38:53.556  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-17 13:38:53.556  9960  9960 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
07-17 13:38:53.557  9960  9960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 android.content.ContextWrapper.sendBroadcast:452 android.content.ContextWrapper.sendBroadcast:452 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3306 
07-17 13:38:53.561  3246  3246 E audit   : type=1320 audit(1500291533.551:241): 
07-17 13:38:53.562  3300  3777 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-17 13:38:53.569  3704  3931 E SLocation: id 1 is already started
07-17 13:38:53.569  3704  3931 D WifiStateMachine: startGeofence() - id : 1, ERROR !!, mResult : -5
07-17 13:38:53.570  3704  3931 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
07-17 13:38:53.571  9974  9974 I PhoneErrorReceiver: onReceive
07-17 13:38:53.576  9946  9946 D [RBL] RblSAccountUtil:     - DB is opened
07-17 13:38:53.576  3246  3246 E audit   : type=1320 audit(1500291533.561:242): 
07-17 13:38:53.576  9946  9946 D [RBL] CellDbHelper: @open
07-17 13:38:53.576  9946  9946 D [RBL] CellDbHelper:     - client : 1
07-17 13:38:53.576  3704  3931 D SLocation: system
07-17 13:38:53.577  3704  3931 D SLocation: startLearning ID = 1
07-17 13:38:53.577  3704  3931 D SLocation: setLearningStatus ID = 1 / status = true
07-17 13:38:53.577  3704  3931 D WifiStateMachine: ConnectedState - enter() - startLearning id : 1
07-17 13:38:53.577  3704  3931 D WifiStateMachine: ConnectedState()- id : 1,  startLearning Success !!
07-17 13:38:53.578  3704  3931 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-17 13:38:53.579  3704  3931 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, lega,cyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.579  3704  3931 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-17 13:38:53.579  3704  3931 D WIFI_UT : evalRequest
07-17 13:38:53.579  3704  3931 D WIFI_UT :   done
07-17 13:38:53.579  3704  3931 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.579  3704  3931 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-17 13:38:53.579  3704  3931 D WIFI    : evalRequest
07-17 13:38:53.579  3704  3931 D WIFI    :   done
07-17 13:38:53.579  3704  3931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-17 13:38:53.588  9987  9987 I usagelog: received in receiver
07-17 13:38:53.589  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
07-17 13:38:53.589  9987  9987 I KnoxUsageLogPro: premStatus:2
07-17 13:38:53.590  9987  9987 I KnoxUsageLogPro: isEulaShown : false
07-17 13:38:53.590  9987  9987 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-17 13:38:53.591  3246  3246 E audit   : type=1320 audit(1500291533.581:243): 
07-17 13:38:53.591  3300  3777 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
07-17 13:38:53.596  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:53.597  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.597  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:53.598  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.598  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.599  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.600  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.600  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.601  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.601  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.602  3704  3963 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.602  3704  3963 D ConnectivityService: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-17 13:38:53.603  3704  3963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-17 13:38:53.604  4294  4420 D GeolocationController: WIFI : onAvailable
07-17 13:38:53.604  9946  9946 D [RBL] CellDbHelper:     - DB is opened
07-17 13:38:53.604  9946  9946 D [RBL] PolicyDbHelper: @open
07-17 13:38:53.605  9946  9946 D [RBL] PolicyDbHelper:     - client : 1
07-17 13:38:53.605  4294  4420 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [true]
07-17 13:38:53.605  4294  4435 D PdnController: handleMessage: what 105
07-17 13:38:53.605  4294  4435 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [true]
07-17 13:38:53.606  4294  4435 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [true]
07-17 13:38:53.606  3704  3812 D EntConnectivity: Not allowed due to - mEnabled false
,07-17 13:38:53.615  4294  4435 D ResipRegiMgr: handleMessage(): 3
07-17 13:38:53.615  4294  4435 D RegiMgrBase: handleMessage: what 3
07-17 13:38:53.615  3704  3812 D EntConnectivity: Not allowed due to - mEnabled false
07-17 13:38:53.616  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
07-17 13:38:53.617  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
07-17 13:38:53.619  9960  9960 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
07-17 13:38:53.620  3704  3963 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
07-17 13:38:53.620  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.620  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:53.620  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:53.620  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.620  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.620  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.621  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.621  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:53.621  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:53.621  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.622  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.622  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.622  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.623  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.623  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.623  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.624  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,07-17 13:38:53.629  9946  9946 D [RBL] PolicyDbHelper:     - DB is opened
,07-17 13:38:53.630  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:53.630  9946 10147 D [RBL] StoredRequest: @onHandleIntent
07-17 13:38:53.633  9946  9946 D [RBL] CellDbHelper: @close
07-17 13:38:53.633  9946  9946 D [RBL] CellDbHelper:     - client : 0
07-17 13:38:53.634  9946  9946 D [RBL] CellDbHelper:     - DB is closed
07-17 13:38:53.634  9946  9946 D [RBL] PolicyDbHelper: @close
07-17 13:38:53.634  9946  9946 D [RBL] PolicyDbHelper:     - client : 0
07-17 13:38:53.634  9946  9946 D [RBL] PolicyDbHelper:     - DB is closed
07-17 13:38:53.634  9946  9946 D [RBL] RblSAccountUtil: @close
07-17 13:38:53.634  9946  9946 D [RBL] RblSAccountUtil:     - client : 0
07-17 13:38:53.634  9946  9946 D [RBL] RblSAccountUtil:     - DB is closed
07-17 13:38:53.634  9946  9946 D [RBL] StoredRequest: @onDestroy
07-17 13:38:53.636  3704  3704 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-17 13:38:53.636  3704  3704 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = false
07-17 13:38:53.636  3704  3917 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
07-17 13:38:53.636  3704  3917 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
07-17 13:38:53.637  3704  3917 D EnterprisePremiumVpnPolicyServiceV2: run all vpn : runAllVpnService beginning
07-17 13:38:53.637  3704  3704 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
07-17 13:38:53.637  3704  3704 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
07-17 13:38:53.637  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-17 13:38:53.638  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.639  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.639  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.639  3704  3918 I KnoxVpnEngineService: vpn handle : Message received
07-17 13:38:53.639  3704  3963 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:53.639  3704  3918 I KnoxVpnEngineService: vpn handle : Message received
07-17 13:38:53.639  3704  3918 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = false
07-17 13:38:53.639  3704  3918 D KnoxVpnEngineService: run all vpn : runAllVpnService beginning
07-17 13:38:53.640  3704  3963 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:53.641  3704  3704 D Tethering: Tethering got CONNECTIVITY_ACTION
07-17 13:38:53.643  4294  4435 D RegiMgrBase: onNetworkEventChanged: new=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=true, isEpdgConnected=false]
07-17 13:38:53.643  4294  4435 D RegiMgrBase: onNetworkEventChanged: old=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=false, isEpdgConnected=false]
07-17 13:38:53.643  4294  4435 D RegiMgrBase: out of service.
07-17 13:38:53.643  4294  4435 D RegiMgrBase: onNetworkEventChanged: nTask= 0 nRegisteredTask= 0 bExistRetryTimer= false bHaveRegisteringTask= false
07-17 13:38:53.646  3704  3965 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
07-17 13:38:53.646  3704  3965 D Tethering: MasterInitialState.processMessage what=327683
07-17 13:38:53.652  4294  4435 D RegiMgrBase: onNetworkEventChanged: tryRegister
07-17 13:38:53.652  4294  4435 D RegiMgrBase: tryRegister:
07-17 13:38:53.659  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:53.662  4294  4435 D RegiMgrBase: RegisterTask(s) -
07-17 13:38:53.662  4294  4435 D ResipRegiMgr: handleMessage(): 32
07-17 13:38:53.662  4294  4435 D RegiMgrBase: handleMessage: what 32
07-17 13:38:53.662  4294  4435 D RegiMgrBase: onPendingUpdateRegistration: 
,07-17 13:38:53.664  4070  4357 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-17 13:38:53.669  9787 10150 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-17 13:38:53.676  3704  3922 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
,07-17 13:38:53.676  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.677  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.677  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.677  3704  3922 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
07-17 13:38:53.677  3704  3922 D NtpTrustedTime: currentTimeMillis() cache hit
07-17 13:38:53.681  3704  3922 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
,07-17 13:38:53.694  4989  4989 I CastMediaRouteProvider: Network connectivity changed
07-17 13:38:53.695  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:53.701  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:38:53.705  4814  4814 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-17 13:38:53.712  9147  9147 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
07-17 13:38:53.712  9147  9147 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
07-17 13:38:53.716  8631  8631 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
07-17 13:38:53.716  9199  9199 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@97e07b2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:53.718  9147  9147 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 1
07-17 13:38:53.718  9147  9147 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
07-17 13:38:53.718  9199  9199 I NetworkConnectivity: Network state changed: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]
07-17 13:38:53.721  3704  6511 D MountService: getExternalStorageMountMode : 1
07-17 13:38:53.721  3704  6511 D MountService: getExternalStorageMountMode : 3
07-17 13:38:53.721  3704  6511 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.policydm
07-17 13:38:53.730  9623  9623 D BluetoothAdapter: STATE_ON
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-17 13:38:53.733  9623  9623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-17 13:38:53.736  9623  9623 D BluetoothAdapter: STATE_ON
,07-17 13:38:53.739  9199  9199 I NetworkPolicyMonitor: Download-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
,07-17 13:38:53.739  3300  3772 D EnterpriseController: netId is 0
07-17 13:38:53.739  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10135
07-17 13:38:53.739  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
07-17 13:38:53.740  9623  9623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
07-17 13:38:53.740  8631  8631 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
07-17 13:38:53.745  8631  8631 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
,07-17 13:38:53.749 10156 10156 E Zygote  : v2
07-17 13:38:53.750 10156 10156 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:53.750 10156 10156 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:53.751 10156 10156 E Zygote  : accessInfo : 0
07-17 13:38:53.753  9199  9199 I NetworkPolicyMonitor: Stream-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
07-17 13:38:53.758  3704  6511 I ActivityManager: Start proc 10156:com.policydm/1000 for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider
,07-17 13:38:53.761 10156 10156 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:53.763 10156 10156 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.policydm 
,07-17 13:38:53.795 10156 10156 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:53.795 10156 10156 D ActivityThread: Added TimaKeyStore provider
07-17 13:38:53.800  3704  3920 I ActivityManager: DSS on for com.policydm and scale is 1.0
,07-17 13:38:53.808  3704  6348 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@45e93c7 displayId=0
07-17 13:38:53.809  3704  6348 D InputTransport: Input channel constructed: fd=459
07-17 13:38:53.809  3704  6348 D InputTransport: Input channel constructed: fd=460
,07-17 13:38:53.812  3704  6348 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
07-17 13:38:53.813  3704  6348 D InputTransport: Input channel destroyed: fd=460
07-17 13:38:53.813  4070  4357 D InputTransport: Input channel constructed: fd=117
07-17 13:38:53.814  4070  4357 D ViewRootImpl@b1c1de4[Toast]: setView = android.widget.LinearLayout{e6c624d V.E...... ......I. 0,0-0,0 #10204d0 android:id/toast_layout_root} touchMode=true
07-17 13:38:53.814  3704  3704 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
07-17 13:38:53.814  3704  4257 D SLocation: checkWifiInfo
07-17 13:38:53.816  3704  3704 V MARsPolicyManager: DataConnection: true
,07-17 13:38:53.820  3704  4041 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
07-17 13:38:53.821  5363  5363 D [SAUI]  : Global::recovered::false
07-17 13:38:53.821  3704  4184 V WindowManager: Relayout Window{57a691dd0 u0 Toast}: viewVisibility=0 req=755x150 WM.LayoutParams{(0,192)(wrapxwrap) gr=#51 sim=#20 ty=2005 fl=#1040088 fmt=-3 wanim=0x1030004 naviIconColor=0}
07-17 13:38:53.822  3111  3111 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=4, Uoast
07-17 13:38:53.826  3704  4041 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,07-17 13:38:53.831  5363  5363 D WaitQueueForNetworkActivate: notifyNetworkActivated
07-17 13:38:53.832  9199  9199 I DevicePlayback: Got network change: mobile=falsewifi=true
07-17 13:38:53.832  9199  9199 I DevicePlayback: Connectivity restored - clearing all queued disable runnables
,07-17 13:38:53.836  3704  4184 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3704 ws=WorkSource{10062} pkg=android
07-17 13:38:53.836  3704  4184 D PowerManagerService: mDisplayReady: false
07-17 13:38:53.837 10156 10156 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
07-17 13:38:53.838  3704  3815 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-17 13:38:53.838  3704  3815 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-17 13:38:53.838  5363  5363 D [SAUI]  : NetworkStateReceiver::connected::recovered?false
07-17 13:38:53.839  3704  3815 D DisplayPowerController: Tracking Direct to etc : 118
07-17 13:38:53.839  3704  3815 D DisplayPowerController: getFinalBrightness : Summary is 118 -> 118
07-17 13:38:53.839  3704  3815 D DisplayPowerController: Animating brightness: target=118, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-17 13:38:53.839  3704  3815 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-17 13:38:53.839  3704  3815 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-17 13:38:53.839  3704  3815 D DisplayPowerController: getFinalBrightness : Summary is 118 -> 118
07-17 13:38:53.839  3704  3815 D DisplayPowerController: Animating brightness: target=118, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-17 13:38:53.840  3704  3815 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-17 13:38:53.840  3704  3815 D PowerManagerService: mDisplayReady: true
07-17 13:38:53.840  3704  4039 D lights  : lcd : 118 +
07-17 13:38:53.849  3704  4039 D lights  : lcd : 118 -
07-17 13:38:53.849  3704  4039 D DisplayPowerState: Tracking!!: 118
07-17 13:38:53.858  3704  4257 D SLocation: cellLocation is null
07-17 13:38:53.859  3704  4022 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: GW is reachable. - 211 msec.
07-17 13:38:53.878 10156 10156 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:53.889  4070  4224 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [755x150]-format:1
,07-17 13:38:53.898  3300  3772 D EnterpriseController: netId is 0
07-17 13:38:53.898  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10001
07-17 13:38:53.899  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:38:53.904  4070  4357 D ViewRootImpl@b1c1de4[Toast]: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-17 13:38:53.907  4989  5802 W MdnsClient_Cast: #acquireLock. Multicast lock not held. Acquiring. Subtypes:"805741C9"
,07-17 13:38:53.908  3704  3931 D WifiHAL : Setting APF program, halHandle = 0x7d03737960
07-17 13:38:53.908  3704  3931 I WifiHAL : 
07-17 13:38:53.908  3704  3931 I WifiHAL : createRequest: APF set program request
,07-17 13:38:53.911  3704  3931 I WifiHAL : Done!
,07-17 13:38:53.926 10156 10156 I FOTA    : [lllIIIIIIlllIlIIIIII(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
,07-17 13:38:53.931 10156 10156 I FOTA    : [lllIIIIIIlllIlIIIIII(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
07-17 13:38:53.937  9199  9239 I DevicePlayback: Allowing woodstock playback due to restored connection
07-17 13:38:53.938  3704  6348 D WindowManager: finishDrawingWindow: Window{57a691dd0 u0 Toast} mDrawState=DRAW_PENDING
07-17 13:38:53.943  3704  4257 D SLocation: geofence id (1) detected : 0
,07-17 13:38:53.954  3704  3760 D WifiScanController: isNLPPackage:com.google.android.gms, true
,07-17 13:38:53.956  3704  3931 I WifiScanController: location is disabled
,07-17 13:38:53.967 10156 10156 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,07-17 13:38:53.971  4070  4204 D vol.MediaSessions: onQueueChanged com.google.android.music []
,07-17 13:38:53.981 10156 10168 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-17 13:38:53.984 10156 10168 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-17 13:38:53.987 10156 10168 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-17 13:38:53.990 10156 10156 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(186/llIIIIlllllIIllIIllI)] try read dbString
,07-17 13:38:53.993 10156 10167 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-17 13:38:53.995 10156 10167 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
,07-17 13:38:53.997 10156 10167 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,07-17 13:38:54.005  3704  4184 D MountService: getExternalStorageMountMode : 1
07-17 13:38:54.005  3704  4184 D MountService: getExternalStorageMountMode : 3
07-17 13:38:54.005  3704  4184 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.soagent
,07-17 13:38:54.021 10156 10156 I DBG_POLICYDM: [com.policydm.db.XDB(231/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,07-17 13:38:54.033 10179 10179 E Zygote  : v2
07-17 13:38:54.033 10179 10179 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:54.033 10179 10179 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:54.034 10179 10179 E Zygote  : accessInfo : 0
,07-17 13:38:54.038  3704  4184 I ActivityManager: Start proc 10179:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
,07-17 13:38:54.039 10179 10179 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:54.040 10179 10179 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.soagent 
,07-17 13:38:54.061 10179 10179 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-17 13:38:54.062 10179 10179 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:54.063  3704  3920 I ActivityManager: DSS on for com.sec.android.soagent and scale is 1.0
,07-17 13:38:54.073  3704  4022 D WifiWatchdogStateMachine:  [|205]
,07-17 13:38:54.084 10179 10179 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,07-17 13:38:54.097 10179 10179 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:54.116 10156 10156 I DBG_POLICYDM: [com.policydm.XDMService(164/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
07-17 13:38:54.119  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:38:54.120  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:54.127 10156 10156 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(455/IIIIIIlIIIllllllIlII)] xdbGetFUMOStatus : 0
,07-17 13:38:54.129 10156 10156 I DBG_POLICYDM: [com.policydm.XDMService(588/llIlIllllllllllllllI)] get NotibarState : 0
,07-17 13:38:54.131  3704  3760 D MountService: getExternalStorageMountMode : 1
07-17 13:38:54.132  3704  3760 D MountService: getExternalStorageMountMode : 3
07-17 13:38:54.132  3704  3760 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10134, packageName : com.sec.android.app.sbrowser
,07-17 13:38:54.150 10197 10197 E Zygote  : v2
,07-17 13:38:54.150 10197 10197 I libpersona: KNOX_SDCARD checking this for 10134
07-17 13:38:54.150 10197 10197 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:54.151 10197 10197 E Zygote  : isSdpEnabledProcess - SDP enabled
07-17 13:38:54.151 10197 10197 E Zygote  : accessInfo : 64
07-17 13:38:54.151 10197 10197 E Zygote  : isSdpEnabledProcess - SDP enabled
,07-17 13:38:54.151 10197 10197 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10134 / [uid]: 10134
07-17 13:38:54.152  3704  3760 I ActivityManager: Start proc 10197:com.sec.android.app.sbrowser:CustomLogger/u0a134 for content provider com.sec.android.app.sbrowser/.logging.CustomLoggingProvider
,07-17 13:38:54.157 10197 10197 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:54.158 10197 10197 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser:CustomLogger 
,07-17 13:38:54.162  3704  9910 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{77757b6: PendingIntentRecord{74dfcb7 com.google.android.gms broadcastIntent}}
,07-17 13:38:54.178 10197 10197 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:54.179 10197 10197 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:54.181  3704  4184 I ActivityManager: DSS on for com.sec.android.app.sbrowser and scale is 1.0
,07-17 13:38:54.215  4626  4626 I BeaconBle: 'L' hardware scan: scan stopped, no clients
,07-17 13:38:54.220 10197 10197 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_5.0/lib/arm
,07-17 13:38:54.238 10197 10197 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:54.250 10197 10197 I cr_ApplicationStatus: initialize application : com.sec.android.app.sbrowser.SBrowserApplication@60d8294
,07-17 13:38:54.258 10197 10209 D ReflectField: Cannot load field: SDL_INT
07-17 13:38:54.258 10197 10209 E ReflectField: Incorrect type : Fallback exception
07-17 13:38:54.258 10197 10209 D ReflectField: Cannot load field: KEYCODE_EMAIL
07-17 13:38:54.258 10197 10209 E ReflectField: Incorrect type : Fallback exception
,07-17 13:38:54.268  3704  5299 D MountService: getExternalStorageMountMode : 1
07-17 13:38:54.268  3704  5299 D MountService: getExternalStorageMountMode : 3
07-17 13:38:54.268  3704  5299 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.wssyncmldm
,07-17 13:38:54.293 10211 10211 E Zygote  : v2
07-17 13:38:54.294 10211 10211 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:38:54.294 10211 10211 I libpersona: KNOX_SDCARD not a persona
07-17 13:38:54.294 10211 10211 E Zygote  : accessInfo : 0
,07-17 13:38:54.297  3704  5299 I ActivityManager: Start proc 10211:com.wssyncmldm/1000 for content provider com.wssyncmldm/com.samsung.android.app.fotaclient.log.MasterLogProvider
,07-17 13:38:54.300 10211 10211 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:38:54.302 10211 10211 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.wssyncmldm 
,07-17 13:38:54.321 10211 10211 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:38:54.322 10211 10211 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:54.324  3704  9910 I ActivityManager: DSS on for com.wssyncmldm and scale is 1.0
,07-17 13:38:54.344 10211 10211 W System  : ClassLoader referenced unknown path: /system/priv-app/FotaAgent/lib/arm64
,07-17 13:38:54.359 10211 10211 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:54.365 10211 10211 I FOTA    : [com.samsung.android.app.syncmldm.db.sql.XDMDbContentProvider(96/onCreate)] 
07-17 13:38:54.365  3704  4021 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
07-17 13:38:54.366  3704  4021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
,07-17 13:38:54.369  3704  4017 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
,07-17 13:38:54.369  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-17 13:38:54.369  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: MaybeNotifyState{ when=-1ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-17 13:38:54.369  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-17 13:38:54.370  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: CMD_ACCEPT_UNVALIDATED_WIFI
07-17 13:38:54.370  3704  3963 D ConnectivityService: NetworkMonitor.CMD_ACCEPT_UNVALIDATED_WIFI network
07-17 13:38:54.370  3704  3963 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,07-17 13:38:54.370  3704  3963 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:54.370  3704  3963 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-17 13:38:54.370  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:54.370  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.370  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.370  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:54.370  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.370  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.371  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.371  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.371  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.371  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.371  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.371  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.371  3704  3963 D ConnectivityService: sending new Min Network Score(100): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.372  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=-1ms what=151655 target=com.android.internal.util.StateMachine$SmHandler }
07-17 13:38:54.372  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: RESULT_VALID
07-17 13:38:54.372  3704 10136 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
07-17 13:38:54.374  3704  4026 D Ethernet: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.374  3704  4026 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
07-17 13:38:54.374  3704  4026 D Ethernet: evalRequest
07-17 13:38:54.374  3704  4026 D Ethernet:   done
07-17 13:38:54.375  3704  3927 D WIFI_P2P: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.375  3704  3927 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-17 13:38:54.375  3704  3927 D WIFI_P2P: evalRequest
07-17 13:38:54.375  3704  3927 D ,WIFI_P2P:   done
07-17 13:38:54.375  3704  3704 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
07-17 13:38:54.376  4044  4044 D PhoneSwitcherNetworkRequstListener: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.376  4044  4044 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
07-17 13:38:54.376  4044  4044 D PhoneSwitcherNetworkRequstListener: evalRequest
07-17 13:38:54.376  4044  4044 D PhoneSwitcherNetworkRequstListener:   done
07-17 13:38:54.377  3704  3963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-17 13:38:54.377  3704  3963 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-17 13:38:54.378  3704  3963 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation passed
07-17 13:38:54.378  3704  3963 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:54.379  3704  3963 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-17 13:38:54.379  3704  3963 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]
07-17 13:38:54.379  3704  3963 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-17 13:38:54.379  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:54.379  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.380  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.380  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:54.380  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.380  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.380  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.381  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.381  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.381  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.381  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ ,Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.381  3704  3963 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.381  3704  3963 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-17 13:38:54.382  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.382  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:54.382  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
07-17 13:38:54.382  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.382  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=5, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.383  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.383  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.383  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:54.383  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [] ]
07-17 13:38:54.384  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.384  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.385  3704  3931 D WIFI_UT : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.385  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.385  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.385  3704  3931 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-17 13:38:54.385  3704  3931 D WIFI_UT : evalRequest
07-17 13:38:54.385  3704  3931 D WIFI_UT :   done
07-17 13:38:54.386  3704  3931 D WIFI    : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.386  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.386  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.386  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.387  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.386  3704  3931 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-17 13:38:54.387  3704  3931 D WIFI    : evalRequest
07-17 13:38:54.387  3704  3931 D WIFI    :   releaseNetworkFor
07-17 13:38:54.387  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.388  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-17 13:38:54.388  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.388  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.389  3704  3963 D ConnectivityService:  sending notification for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.389  3704  3963 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=15, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
07-17 13:38:54.391  3704  3963 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-17 13:38:54.393  3704  3931 D WifiConfigManager: update usableInternet : true
07-17 13:38:54.394  3704 10224 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-17 13:38:54.394  3704 10224 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-17 13:38:54.394  3704 10224 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-17 13:38:54.394  3704 10224 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-17 13:38:54.394  3704 10224 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-17 13:38:54.394  3704 10224 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-17 13:38:54.394  3704 10224 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-17 13:38:54.394  3704 10224 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-17 13:38:54.395  3704 10224 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-17 13:38:54.395  3704 10224 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-17 13:38:54.395  3704 10224 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-17 13:38:54.395  3704 10224 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-17 13:38:54.399  4070  4357 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
07-17 13:38:54.400  4070  4357 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
07-17 13:38:54.410  3704  3931 D WifiConfigStore: saveNetwork skipInternetCheck
,07-17 13:38:54.424 10211 10211 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.file.XDB(422/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
07-17 13:38:54.425  3704  3931 D WifiConfigStore: readNetwork skipInternetCheck
07-17 13:38:54.436  3704  4338 I ActivityManager: KPU : put [com.sec.android.widgetapp.samsungapps] : 25852 K
07-17 13:38:54.436  3704  4338 I ActivityManager: Killing 9245:com.sec.android.widgetapp.samsungapps/u0a105 (adj 906): DHA:empty #33
07-17 13:38:54.437  3704 10229 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
07-17 13:38:54.437  3704 10229 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
07-17 13:38:54.437  3704 10229 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
07-17 13:38:54.437  3704 10229 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
07-17 13:38:54.437  3704  4338 I ActivityManager: KPU : put [com.sec.android.app.sbrowser] : 21124 K
07-17 13:38:54.437  3704  4338 I ActivityManager: Killing 9219:com.sec.android.app.sbrowser/u0a134 (adj 906): DHA:empty #33
07-17 13:38:54.437  3704 10229 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
07-17 13:38:54.438  3704 10229 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
07-17 13:38:54.438  3704 10229 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: false
07-17 13:38:54.438  3704 10229 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
07-17 13:38:54.438  3704 10229 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
07-17 13:38:54.438  3704 10229 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
07-17 13:38:54.438  3704 10229 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
07-17 13:38:54.439  3704 10229 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
07-17 13:38:54.447  3704  3704 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
07-17 13:38:54.447  3704  3704 D WifiHs20Service: reason: 2
07-17 13:38:54.448  3704  3959 I WifiHs20Service: Message received 5014
07-17 13:38:54.448  3704  3959 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,07-17 13:38:54.486  3300  3772 D EnterpriseController: netId is 0
,07-17 13:38:54.486  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-17 13:38:54.486  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:38:54.491  4989  4989 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-17 13:38:54.491  3704  4182 D ActivityManager: cleanUpApplicationRecord -- 9219
07-17 13:38:54.492  4670  4686 D ForegroundUtils: could not check pending caller
07-17 13:38:54.494  4989  7986 I iu.UploadsManager: num queued entries: 0
,07-17 13:38:54.537 10000 10000 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
07-17 13:38:54.538 10000 10000 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? ]
07-17 13:38:54.538 10000 10000 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
07-17 13:38:54.538  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:38:54.539  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:54.550 10000 10000 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-17 13:38:54.550 10000 10000 I SA      : [OR] == isSIMCardReady false ==
07-17 13:38:54.552 10000 10000 I SA      : [SCU] == networkStateCheck == true
07-17 13:38:54.552 10000 10000 I SA      : [DM] getCountryCodeFromCSC : PL
07-17 13:38:54.552 10000 10000 I SA      : isChinaCountryCode : false
07-17 13:38:54.552 10000 10000 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-17 13:38:54.552 10000 10000 I SA      : [OR] == networkStateCheck true ==
,07-17 13:38:54.569  3704  9910 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170717T140854 - CU:10124/CP:4872
,07-17 13:38:54.579  4989  7986 I iu.UploadsManager: num updated entries: 0
07-17 13:38:54.579  4989  4999 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-17 13:38:54.582  4989  7986 I iu.SyncManager: NEXT; no task
,07-17 13:38:54.583 10000 10000 I SA      : [OR] GetMyCountryZoneTask
07-17 13:38:54.583 10000 10000 I SA      : [OR] onReceive END
,07-17 13:38:54.599  3704  3963 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-17 13:38:54.603 10023 10023 I SVCAgent: Ignore network change.
,07-17 13:38:54.611 10036 10036 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,07-17 13:38:54.615  3704  5299 D ActivityManager: cleanUpApplicationRecord -- 9245
,07-17 13:38:54.624  4670  4687 D ForegroundUtils: could not check pending caller
07-17 13:38:54.626 10211 10211 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(297/lllIlIlIIIllIIlIllIl)] Voice : true
07-17 13:38:54.628 10211 10211 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(298/lllIlIlIIIllIIlIllIl)] SMS : true
,07-17 13:38:54.633  7762  7762 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,07-17 13:38:54.633  7762  7762 E SPPClientService: [SystemStateMoniter] Current Time : 205377
07-17 13:38:54.634  7762  7762 E SPPClientService: [SystemStateMoniter] No Connect : false
,07-17 13:38:54.635 10211 10211 I FOTA_AGENT: [llIllIlIlIIlIlIlllII(299/lllIlIlIIIllIIlIllIl)] isDataOnly : false
,07-17 13:38:54.642  3704  3704 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
07-17 13:38:54.643 10036 10036 D AutoSelfUpgradeService: onCreate() 
07-17 13:38:54.643  3704  3704 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,07-17 13:38:54.645 10036 10036 D AutoSelfUpgradeService: onStartCommand() action.selfupgrade.via.net
07-17 13:38:54.645  3704  3704 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
07-17 13:38:54.646 10036 10235 D AutoSelfUpgradeService: startInitAutoSelfUpdate()
07-17 13:38:54.652  3704  3704 D SLocation: PendingIntent onSendFinished id:1
,07-17 13:38:54.658 10036 10235 I AutoSelfUpgradeService: Not a time to rum self upgrade yet.
07-17 13:38:54.660 10036 10036 D AutoSelfUpgradeService: onDestroy()
,07-17 13:38:54.680 10000 10234 I SA      : [SRS] prepareGetMyCountryZone
,07-17 13:38:54.691 10211 10211 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(645/IllIlIIIIlIIlIIIllIl)] bootTime: 1500291352654
,07-17 13:38:54.692 10000 10234 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-17 13:38:54.693 10000 10234 I SA      : [SSP] query invoked
,07-17 13:38:54.701 10000 10234 I SA      : [TPMU] GetMccFromDB : null
07-17 13:38:54.701 10000 10234 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-17 13:38:54.701 10000 10234 I SA      : [LBE] isSupportCheckDomainRegion : true
07-17 13:38:54.702 10211 10211 I FOTA_AGENT: [IIIlIlIIIllIIIIllIlI(638/lllIlIlIIIllIIlIllIl)] bootTime: 1500291352654, savedBootTime: 1500000484534
07-17 13:38:54.702 10000 10234 I SA      : [TPM] isNoProxy(default) : true
,07-17 13:38:54.705 10000 10234 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-17 13:38:54.712 10211 10211 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3131/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,07-17 13:38:54.724 10211 10211 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3184/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,07-17 13:38:54.736 10211 10211 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3237/IllIlIIIIlIIlIIIllIl)] xdmdbsqlGetNotiSaveState : 0
,07-17 13:38:54.746 10211 10211 I FOTA_AGENT: [com.samsung.android.app.syncmldm.db.sql.llllIIIllIlIIIIllllI(3386/llllllIllIlIlllIIlIl)] xdmdbsqlGetFumoInitType : 0
,07-17 13:38:54.748 10211 10211 I FOTA_AGENT: [com.samsung.android.app.fotaclient.FotaApplication(93/onCreate)] DMApplication NOT Start !
,07-17 13:38:54.815  3704  4265 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / op:PendingIntent{a472941: PendingIntentRecord{8248ee6 android broadcastIntent}}
,07-17 13:38:54.818  3704  4265 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20170718T133854 - CU:1000/CP:3704
,07-17 13:38:54.884  3704  4019 D WifiWatchdogStateMachine:  [] [|407]
,07-17 13:38:54.904  3704  3911 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170717T134804 - CU:10019/CP:4626
,07-17 13:38:54.905  3704  3911 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755642, nowELAPSED=205648
,07-17 13:38:54.912  3704  3788 D MountService: getExternalStorageMountMode : 1
07-17 13:38:54.912  3704  3788 D MountService: getExternalStorageMountMode : 3
07-17 13:38:54.912  3704  3788 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10112, packageName : com.google.android.talk
,07-17 13:38:54.933 10239 10239 E Zygote  : v2
07-17 13:38:54.933 10239 10239 I libpersona: KNOX_SDCARD checking this for 10112
07-17 13:38:54.933 10239 10239 I libpersona: KNOX_SDCARD not a persona
,07-17 13:38:54.934 10239 10239 E Zygote  : accessInfo : 0
,07-17 13:38:54.936  3704  3788 I ActivityManager: Start proc 10239:com.google.android.talk/u0a112 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.broadcastreceiver.GcmStateReceiver
,07-17 13:38:54.944 10239 10239 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
07-17 13:38:54.946 10239 10239 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.talk 
07-17 13:38:54.951  3704  4338 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{49cbaf: PendingIntentRecord{dcd4f14 com.google.android.gms broadcastIntent}}
07-17 13:38:54.952  3704  4338 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T135853, SetElapsed=1404182, nowELAPSED=205696
,07-17 13:38:54.962  3704  4184 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20170717T134804 - CU:10019/CP:4626
,07-17 13:38:54.963  3704  4184 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755696, nowELAPSED=205706
,07-17 13:38:54.973 10239 10239 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-17 13:38:54.973 10239 10239 D ActivityThread: Added TimaKeyStore provider
,07-17 13:38:54.975  3704  4740 I ActivityManager: DSS on for com.google.android.talk and scale is 1.0
,07-17 13:38:54.996  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:54.996  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:55.013 10239 10239 I art     : Starting a blocking GC AddRemoveAppImageSpace
,07-17 13:38:55.016 10239 10239 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm64
,07-17 13:38:55.037 10239 10239 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:38:55.227  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:38:55.264 10000 10234 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
,07-17 13:38:55.264 10000 10234 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-17 13:38:55.267 10000 10234 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-17 13:38:55.268 10000 10234 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:55.269 10000 10234 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:55.270  3300  3772 D EnterpriseController: netId is 0
07-17 13:38:55.270  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10041
07-17 13:38:55.270  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:38:55.302 10239 10239 D BabelGcmRegistration: GcmRegistration: Checking GCM registration
,07-17 13:38:55.312 10239 10239 I Babel_telephony: TeleModule.onApplicationCreate
,07-17 13:38:55.316 10239 10261 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
07-17 13:38:55.316 10239 10261 I Babel_SMS: MmsConfig.loadMmsSettings
,07-17 13:38:55.316 10239 10261 E TelephonyManager: getCustomerPath : /system/csc/customer.xml file exist
07-17 13:38:55.317 10239 10261 E TelephonyManager: getCustomerPath : /system/csc/customer.xml file exist
,07-17 13:38:55.318 10239 10261 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: userAgent=SAMSUNG-ANDROID-MMS/uaprof, uaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
07-17 13:38:55.318 10239 10261 I Babel_SMS: MmsConfig.loadFromDatabase
,07-17 13:38:55.321 10239 10239 I Babel_App: Startup - clean
,07-17 13:38:55.325  3704  4184 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.SmsReceiver newState = 2 callingPackage = 10112
,07-17 13:38:55.326  3704  4184 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.MmsWapPushReceiver newState = 2 callingPackage = 10112
,07-17 13:38:55.327 10239 10261 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
07-17 13:38:55.327 10239 10261 I Babel_SMS: MmsConfig.loadFromResources
07-17 13:38:55.328 10239 10261 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
07-17 13:38:55.328 10239 10261 I Babel_SMS: MmsConfig.loadMmsSettings: userAgent=SAMSUNG-ANDROID-MMS/uaprof, uaProfUrl=http://wap.samsungmobile.com/uaprof/uaprof.rdf
,07-17 13:38:55.329  3704  6348 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortSmsReceiver newState = 2 callingPackage = 10112
07-17 13:38:55.330  3704  6348 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.sms.AbortMmsWapPushReceiver newState = 2 callingPackage = 10112
,07-17 13:38:55.331  3704  6348 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.service.NoConfirmationSmsSendService newState = 1 callingPackage = 10112
,07-17 13:38:55.352  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:55.353  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:55.403  3704  4328 D CryptdConnector: SND -> {23 cryptfs getpwtype}
,07-17 13:38:55.405  3095  3174 D VoldCryptCmdListener: cryptfs getpwtype
07-17 13:38:55.406  3704  3893 D CryptdConnector: RCV <- {213 23 default}
,07-17 13:38:55.560  3704  9911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:38:55.560  3704  9911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:38:55.560  3704  9911 D BatteryService: online:4, current avg:108, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:175
07-17 13:38:55.561  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:38:55.564  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:38:55.564  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:38:55.565  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:38:55.567  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-17 13:38:55.568  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:38:55.572  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-17 13:38:55.578  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:38:55.579  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:38:55.583  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-17 13:38:55.584  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:38:55.590  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:38:55.733  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:38:55.733  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:55.801  4070  4357 D ViewRootImpl@b1c1de4[Toast]: dispatchDetachedFromWindow
,07-17 13:38:55.806  3704  3920 D InputTransport: Input channel destroyed: fd=459
,07-17 13:38:55.806  3704  3920 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3704) eventTime = 206550
07-17 13:38:55.807  3704  3920 D PowerManagerService: [s] UserActivityState : 4 -> 1
07-17 13:38:55.807  3704  3920 D PowerManagerService: [api] release WakeLock SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3704, ws=WorkSource{10062}) (uid=1000, pid=3704, ws=WorkSource{10062}, pkg=android, elapsedTime=1972) (0x0)
07-17 13:38:55.807  3704  3920 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3704, ws=WorkSource{10062}) (uid=1000, pid=3704, ws=WorkSource{10062}, pkg=android, elapsedTime=1972)
07-17 13:38:55.808  4070  4357 D InputTransport: Input channel destroyed: fd=117
,07-17 13:38:56.067  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:56.068  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
07-17 13:38:56.068  3704  3931 D WifiStateMachine: User moved, open or psk 24GHz, currentRssi = -45, mQnsUpperRssiThreshold = 200
,07-17 13:38:56.069  3704  3931 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@1235601
07-17 13:38:56.070  3704  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,07-17 13:38:56.073  3704  3931 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170717T133900 - CU:1000/CP:3704
07-17 13:38:56.073  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133900, SetElapsed=210847, nowELAPSED=206817
,07-17 13:38:56.164  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:56.165  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:56.241  4528  4528 D io_stats: !@   8,0 r 26160 2309460 w 5273 211976 d 702 74772 f 2149 2149 iot 11720 11010 th 463244 0 0 pt 0 inp 0 0 206.984
,07-17 13:38:56.347  3704  3813 I WindowManager: Destroying surface Surface(name=Toast) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementInner:499 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementLoop:274 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacement:222 com.android.server.wm.WindowManagerService$H.handleMessage:9166 android.os.Handler.dispatchMessage:102 
,07-17 13:38:56.348  3111  9361 I SurfaceFlinger: id=17 Removed Uoast (5/5)
07-17 13:38:56.349  3111  3117 I SurfaceFlinger: id=17 Removed Uoast (-2/5)
,07-17 13:38:56.630 10000 10234 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 1363
07-17 13:38:56.632  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:38:56.633  9787 10150 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:56.694 10000 10234 I SA      : [ODM] saveOpenData( GEO_IP, EU )
07-17 13:38:56.695 10000 10234 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-17 13:38:56.699 10000 10234 I SA      : [OCP]  Cursor is not null
,07-17 13:38:56.704 10000 10234 I SA      : [OCP] update openData : EU
,07-17 13:38:56.709 10000 10234 I SA      : [TPMU] getNetworkMcc : 
,07-17 13:38:56.713 10000 10234 I SA      : [SRS] prepareGetMyCountryZone
,07-17 13:38:56.720 10000 10234 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-17 13:38:56.721 10000 10234 I SA      : [SSP] query invoked
,07-17 13:38:56.725 10000 10234 I SA      : [TPMU] GetMccFromDB : null
07-17 13:38:56.725 10000 10234 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-17 13:38:56.725 10000 10234 I SA      : [LBE] isSupportCheckDomainRegion : true
07-17 13:38:56.726 10000 10234 I SA      : [TPM] isNoProxy(default) : true
,07-17 13:38:56.727 10000 10234 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
07-17 13:38:56.727 10000 10234 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,07-17 13:38:56.729 10000 10234 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,07-17 13:38:56.730 10000 10234 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:38:56.731 10000 10234 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:38:58.129 10000 10234 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 1399
,07-17 13:38:58.133 10000 10234 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,07-17 13:38:58.134 10000 10234 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,07-17 13:38:58.140 10000 10234 I SA      : [OCP]  Cursor is not null
,07-17 13:38:58.149 10000 10234 I SA      : [OCP] update openData : EU
,07-17 13:38:58.158 10000 10234 I SA      : [TPMU] getNetworkMcc : 
,07-17 13:38:58.162 10000 10234 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1434
07-17 13:38:58.162 10000 10234 I SA_HTTPURLCONNECTION: [RC New] Execute end
07-17 13:38:58.163 10000 10234 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 2898
07-17 13:38:58.163 10000 10234 I SA_HTTPURLCONNECTION: [RC New] Execute end
,07-17 13:38:58.165 10000 10000 I SA      : [OR] GetMyCountryZoneTask mcc = null
07-17 13:38:58.165 10000 10000 I SA      : [OR] GetMyCountryZoneTask Fail
,07-17 13:38:58.438  9623  9687 I io.jxcore.node.IncomingSocketThreadTest: testRun
,07-17 13:38:58.439  9623  9687 I !!      :  finally closed
,07-17 13:38:58.444  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
07-17 13:38:58.445  9623  9687 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-17 13:38:58.449  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
07-17 13:38:58.450  9623  9687 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-17 13:38:58.453  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,07-17 13:38:58.459  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
07-17 13:38:58.460  9623  9687 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@f5e902c Bundle[{}]
,07-17 13:38:58.463  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
07-17 13:38:58.464  9623  9687 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-17 13:38:58.464  9623  9687 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-17 13:38:58.468  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,07-17 13:38:58.469  9623  9687 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-17 13:38:58.471  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
07-17 13:38:58.471  9623  9687 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-17 13:38:58.473  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,07-17 13:38:58.474  9623  9687 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-17 13:38:58.476  9623  9687 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
07-17 13:38:58.476  9623  9687 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-17 13:38:58.479  9623  9687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,07-17 13:38:58.482  9623  9687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,07-17 13:38:58.484  9623  9687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,07-17 13:38:58.486  9623  9687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,07-17 13:38:58.488  9623  9687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,07-17 13:38:58.491  9623  9687 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,07-17 13:38:58.494  9623  9687 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,07-17 13:38:58.498  9623 10274 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
07-17 13:38:58.498  9623 10274 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-17 13:38:58.501  3300  3772 D EnterpriseController: netId is 0
07-17 13:38:58.502  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10033
07-17 13:38:58.502  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:38:58.505  9623 10276 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
07-17 13:38:58.505  9623 10276 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
07-17 13:38:58.505  9623 10274 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
07-17 13:38:58.505  9623 10276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:38:58.505  9623 10274 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,07-17 13:38:58.506  9623 10274 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:38:58.506  9623 10276 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:38:58.506  9623 10274 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:38:58.506  9623 10276 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
07-17 13:38:58.506  9623 10274 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,07-17 13:38:58.508  9623 10280 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 228, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.508  9623 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:58.508  9623 10280 D io.jxcore.node.StreamCopyingThread:  id: 77
07-17 13:38:58.508  9623 10281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 229, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.508  9623 10281 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:58.508  9623 10281 D io.jxcore.node.StreamCopyingThread:  id: 78
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 229, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread:  id: 78
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread:  id: 78
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-17 13:38:58.509  9623 10281 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 229, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:58.509  9623 10281 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
07-17 13:38:58.510  9623 10279 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 227, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.510  9623 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:58.510  9623 10279 D io.jxcore.node.StreamCopyingThread:  id: 78
07-17 13:38:58.510  9623 10279 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 227, thread name: OutgoingSocketThread/Sender): Socket closed
07-17 13:38:58.510  9623 10279 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 227, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.510  9623 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:58.510  9623 10279 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
07-17 13:38:58.510  9623 10279 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
07-17 13:38:58.510  9623 10279 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
07-17 13:38:58.511  9623 10279 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 227, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.511  9623 10279 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:38:58.511  9623 10279 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,07-17 13:38:58.511  9623 10280 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 228, thread name: IncomingSocketThread/Receiver): Broken pipe
07-17 13:38:58.511  9623 10278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 226, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.511  9623 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:58.511  9623 10278 D io.jxcore.node.StreamCopyingThread:  id: 77
07-17 13:38:58.511  9623 10280 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 228, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.511  9623 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:58.511  9623 10280 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
07-17 13:38:58.512  9623 10280 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: Broken pipe", this is likely due to peer having disconnected
07-17 13:38:58.512  9623 10280 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
07-17 13:38:58.512  9623 10280 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 228, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.512  9623 10280 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:58.512  9623 10280 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
07-17 13:38:58.512  9623 10278 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 226, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.512  9623 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:58.512  9623 10278 D io.jxcore.node.StreamCopyingThread:  id: 77
,07-17 13:38:58.512  9623 10278 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.512  9623 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:58.512  9623 10278 D io.jxcore.node.StreamCopyingThread:  id: 77
07-17 13:38:58.513  9623 10278 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-17 13:38:58.513  9623 10278 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-17 13:38:58.513  9623 10278 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-17 13:38:58.513  9623 10278 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-17 13:38:58.513  9623 10278 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-17 13:38:58.513  9623 10278 I io.jxcore.node.IncomingSocketThread: The sending thread is done
07-17 13:38:58.513  9623 10278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 226, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:38:58.513  9623 10278 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
07-17 13:38:58.513  9623 10278 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,07-17 13:38:58.567  9932 10146 I NetworkServiceClient: WiFi is connected
,07-17 13:38:58.586  3704  4338 I ActivityManager: KPU : put [com.wssnps] : 24208 K
07-17 13:38:58.586  3704  4338 I ActivityManager: Killing 9260:com.wssnps/1000 (adj 906): DHA:empty #33
,07-17 13:38:58.627  3704  9910 D ActivityManager: cleanUpApplicationRecord -- 9260
,07-17 13:38:58.628  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:38:59.097  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:38:59.097  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:38:59.811  3704  3815 D PowerManagerService: [s] UserActivityState : 1 -> 4
07-17 13:38:59.811  3704  3815 D PowerManagerService: mDisplayReady: false
07-17 13:38:59.811  3704  3815 I PowerManagerService: [PWL] On : 0 (210555 ms ago)
07-17 13:38:59.811  3704  3815 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
07-17 13:38:59.812  3704  3815 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-17 13:38:59.812  3704  3815 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-17 13:38:59.812  3704  3815 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-17 13:38:59.812  3704  3815 D DisplayPowerController: Animating brightness: target=57, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-17 13:38:59.813  3704  3815 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-17 13:38:59.814  3704  3815 D PowerManagerService: mDisplayReady: true
,07-17 13:38:59.832  3704  4039 D lights  : lcd : 85 +
,07-17 13:38:59.838  3704  4039 D lights  : lcd : 85 -
,07-17 13:38:59.848  3704  3815 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-17 13:38:59.848  3704  4039 D lights  : lcd : 57 +
07-17 13:38:59.848  3704  3815 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-17 13:38:59.848  3704  3815 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
07-17 13:38:59.848  3704  3815 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-17 13:38:59.850  3704  4039 D lights  : lcd : 57 -
,07-17 13:39:00.001  3704  3866 D SamsungAlarmManager: Expired : 8
,07-17 13:39:00.002  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{ef1103e type 3 when 210744 android}
,07-17 13:39:00.010  3704  3704 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170717T134000 - CU:1000/CP:3704
,07-17 13:39:00.013  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-17 13:39:00.013  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-17 13:39:00.013  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
07-17 13:39:00.023  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-17 13:39:00.037  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-17 13:39:00.040  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-17 13:39:00.049  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:39:00.050  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 13:39:00.052  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:39:00.055  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:39:00.071  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:39:00.073  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 13:39:00.074  4070  4070 V hong    : mid yDiff = 438
07-17 13:39:00.074  4070  4070 V hong    : mid yDiff = 438
,07-17 13:39:00.077  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
,07-17 13:39:00.077  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-17 13:39:00.081  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
07-17 13:39:00.083  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-17 13:39:00.101  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:39:00.103  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:39:00.103  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 13:39:00.103  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755696, nowELAPSED=210847
07-17 13:39:00.104  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170717T134000, SetElapsed=270744, nowELAPSED=210847
07-17 13:39:00.104  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@72473c0 alarm=Alarm{d8afe9f type 2 when 210847 android}
07-17 13:39:00.105  3704  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
07-17 13:39:00.107 10093 10093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-17 13:39:00.108 10093 10093 I wpa_supplicant: P2P: Current p2p state = IDLE
07-17 13:39:00.113  3704  3931 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20170717T133908 - CU:1000/CP:3704
07-17 13:39:00.113  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133908, SetElapsed=218849, nowELAPSED=210857
,07-17 13:39:00.118  3704  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T133915 - CU:1000/CP:3704
07-17 13:39:00.119  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:39:00.120  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:39:00.124  5265  5265 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-17 13:39:00.126 10093 10093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-17 13:39:00.126  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-17 13:39:00.129  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-17 13:39:00.137  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-17 13:39:00.137  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
07-17 13:39:00.138  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-17 13:39:00.138  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-17 13:39:00.139  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-17 13:39:00.142  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-17 13:39:00.143  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB548169489A7ED530437295274FE5269270C1D4724434FDC97B45793A383D2A7BBFD4F1D95E52E804E7E5263DDD4E2C8]}
07-17 13:39:00.143  5265  5265 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-17 13:39:00.947  3704  5557 D SSRM:f  : SIOP:: AP = 280, PST = 281 (W:10), CP = 226, CUR = 128, LCD = 57
,07-17 13:39:01.247  4528  4528 D io_stats: !@   8,0 r 26160 2309460 w 5321 212248 d 702 74772 f 2151 2151 iot 11730 11016 th 467292 0 0 pt 0 inp 0 0 211.989
,07-17 13:39:02.120  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:02.120  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:39:02.922  3704  3788 I ActivityManager: Waited long enough for: ServiceRecord{ad1411a u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,07-17 13:39:03.448  3704 10284 D WifiMHD::s: req(2):1, 6, 1
,07-17 13:39:03.451  3704 10284 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:03.453  3704 10284 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:03.458  3300  3772 D EnterpriseController: netId is 0
07-17 13:39:03.458  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 1000
07-17 13:39:03.458  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:39:04.003  9623  9687 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,07-17 13:39:04.007  9623  9687 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,07-17 13:39:04.012  9623  9687 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,07-17 13:39:04.104  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:39:04.107 10093 10093 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
,07-17 13:39:04.108  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:39:04.108  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
,07-17 13:39:04.113  3704  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@da82bb5
,07-17 13:39:05.021  9623  9687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,07-17 13:39:05.025  9623  9687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,07-17 13:39:05.029  9623  9687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,07-17 13:39:05.030  9623  9687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 237)
,07-17 13:39:05.034  9623  9687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,07-17 13:39:05.035  9623  9687 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-17 13:39:05.035  9623  9687 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 238)
,07-17 13:39:05.039  9623  9687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,07-17 13:39:05.042  9623  9687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,07-17 13:39:05.047  9623  9687 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,07-17 13:39:05.050  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-17 13:39:05.050  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc415df added. We now have 2 listener(s)
07-17 13:39:05.050  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc415df added. We now have 3 listener(s)
07-17 13:39:05.050  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-17 13:39:05.054  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
07-17 13:39:05.055  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-17 13:39:05.055  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,07-17 13:39:05.055  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-17 13:39:05.056  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa1722c added. We now have 4 listener(s)
07-17 13:39:05.056  9623  9687 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-17 13:39:05.057  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-17 13:39:05.066  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.073  9623  9687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,07-17 13:39:05.075  9623  9687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
07-17 13:39:05.075  9623  9687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,07-17 13:39:05.075  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
07-17 13:39:05.076  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-17 13:39:05.079  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-17 13:39:05.080  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-17 13:39:05.080  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.081  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-17 13:39:05.084  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
07-17 13:39:05.085  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,07-17 13:39:05.085  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.086  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
07-17 13:39:05.086  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-17 13:39:05.086  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-17 13:39:05.086  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-17 13:39:05.088  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-17 13:39:05.089  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-17 13:39:05.090  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,07-17 13:39:05.090  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-17 13:39:05.090  9623 10287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,07-17 13:39:05.090  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-17 13:39:05.090  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
07-17 13:39:05.090  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-17 13:39:05.090  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-17 13:39:05.090  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-17 13:39:05.093  9623 10287 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:39:05.093  9623 10287 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-17 13:39:05.098  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-17 13:39:05.098  9623  9687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-17 13:39:05.098  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-17 13:39:05.100  9623 10287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-17 13:39:05.100  9623 10287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@69a628a, port: 6, type: 1, local socket address: null, socket type: 0
,07-17 13:39:05.103  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.104  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.105  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.109  9623  9687 D BluetoothAdapter: isSecureModeEnabled
,07-17 13:39:05.110  9764  9776 D BtConfig.SecureMode: isSecureModeOn:false
07-17 13:39:05.110  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.111  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-17 13:39:05.112  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.114  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:05.114  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-17 13:39:05.114  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-17 13:39:05.114  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-17 13:39:05.118  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.125  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.126  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.126  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-17 13:39:05.126  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-17 13:39:05.126  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9823b41d-e4b3-4cc0-9bad-a60fa5a52179", Bluetooth MAC address: "44:78:3E:94:4A:3E"
07-17 13:39:05.127  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 4A 3E
,07-17 13:39:05.127  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:39:05.128  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:39:05.128  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.129  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.129  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,07-17 13:39:05.130  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:39:05.130  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.130  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.131  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.133  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:05.135  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:05.135  9623  9687 D BluetoothAdapter: isSecureModeEnabled
,07-17 13:39:05.136  9764  9785 D BtConfig.SecureMode: isSecureModeOn:false
07-17 13:39:05.137  9623  9687 D BluetoothLeAdvertiser: start advertising
07-17 13:39:05.139  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:05.142  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:05.142  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:39:05.144  9764  9775 D BtGatt.GattService: registerClient() - UUID=460d5fb5-d1b2-4328-b0b1-e48cd6a70874
,07-17 13:39:05.249  9764  9784 D BtGatt.GattService: onClientRegistered() - UUID=460d5fb5-d1b2-4328-b0b1-e48cd6a70874, clientIf=5, status=0
,07-17 13:39:05.251  9623  9634 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,07-17 13:39:05.255  9764  9785 E BtGatt.ContextMap: Context not found for ID 5
,07-17 13:39:05.256  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
07-17 13:39:05.257  9764  9801 D BtGatt.AdvertiseManager: message : 0
,07-17 13:39:05.260  9764  9801 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-17 13:39:05.260  9764  9801 D BtGatt.AdvertiseManager: size of list is =0
,07-17 13:39:05.269  9764  9801 D BtGatt.AdvertiseManager: starting advertising
,07-17 13:39:05.274  9764  9801 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-17 13:39:05.280  9764  9819 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-17 13:39:05.297  9764  9784 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,07-17 13:39:05.302  9764  9801 D BtGatt.AdvertiseManager: starting multi advertising
,07-17 13:39:05.313  9764  9784 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,07-17 13:39:05.314  9764  9801 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
07-17 13:39:05.314  9764  9801 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-17 13:39:05.314  9764  9801 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
07-17 13:39:05.315  9764  9801 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,07-17 13:39:05.316  9623  9739 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-17 13:39:05.318  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.319  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.319  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,07-17 13:39:05.320  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.321  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.322  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.323  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.324  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.324  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-17 13:39:05.328  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-17 13:39:05.329  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.334  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.335  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.337  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.338  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,07-17 13:39:05.340  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.341  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,07-17 13:39:05.341  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
07-17 13:39:05.342  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,07-17 13:39:05.343  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.344  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-17 13:39:05.345  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.345  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
07-17 13:39:05.346  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,07-17 13:39:05.346  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.347  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,07-17 13:39:05.348  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.350  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,07-17 13:39:05.351  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-17 13:39:05.359  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.360  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-17 13:39:05.360  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.361  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.362  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,07-17 13:39:05.627  3704  4184 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:39:05.628  3704  4184 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:39:05.628  3704  4184 D BatteryService: online:4, current avg:134, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:141
07-17 13:39:05.628  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:39:05.638  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:39:05.638  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:39:05.642  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:39:05.647  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 13:39:05.648  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:39:05.657  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
07-17 13:39:05.661  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:39:05.662  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:39:05.672  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-17 13:39:05.673  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:39:05.687  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:39:05.842  9623  9687 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-17 13:39:05.843  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,07-17 13:39:05.843  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
07-17 13:39:05.843  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-17 13:39:05.843  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,07-17 13:39:05.844  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-17 13:39:05.844  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-17 13:39:05.845  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-17 13:39:05.845  9623 10287 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-17 13:39:05.845  9623 10287 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-17 13:39:05.845  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-17 13:39:05.845  9623 10287 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-17 13:39:05.845  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-17 13:39:05.845  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-17 13:39:05.846  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-17 13:39:05.846  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-17 13:39:05.846  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-17 13:39:05.847  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.847  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-17 13:39:05.847  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-17 13:39:05.848  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.850  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.851  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.852  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.856  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.860  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:05.860  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-17 13:39:05.864  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.867  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:05.867  9623  9687 D BluetoothLeScanner: could not find callback wrapper
07-17 13:39:05.867  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-17 13:39:05.868  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.869  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.871  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.871  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-17 13:39:05.872  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.875  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:05.879  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:05.879  9623  9687 D BluetoothLeAdvertiser: stop advertising
,07-17 13:39:05.881  9764  9785 E BtGatt.ContextMap: Context not found for ID 5
07-17 13:39:05.882  9764  9801 D BtGatt.AdvertiseManager: message : 1
,07-17 13:39:05.883  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,07-17 13:39:05.884  9764  9801 D BtGatt.AdvertiseManager: stop advertise for client =  5
07-17 13:39:05.884  9764  9801 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
07-17 13:39:05.888  9764  9801 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-17 13:39:05.900  9764  9784 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
07-17 13:39:05.900  9764  9784 D BtGatt.GattService: Client app is not null!
,07-17 13:39:05.901  9623  9635 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-17 13:39:05.904  9764  9786 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-17 13:39:05.907  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-17 13:39:05.908  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.909  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-17 13:39:05.910  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.911  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.912  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.912  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-17 13:39:05.913  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-17 13:39:05.915  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-17 13:39:05.916  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.922  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.922  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:39:05.923  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:05.924  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:05.925  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-17 13:39:05.926  9623  9623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
07-17 13:39:05.927  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-17 13:39:05.927  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:39:05.928  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,07-17 13:39:05.929  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-17 13:39:05.930  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.930  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-17 13:39:05.931  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,07-17 13:39:05.931  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.932  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,07-17 13:39:05.933  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-17 13:39:05.934  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:39:06.252  4528  4528 D io_stats: !@   8,0 r 26160 2309460 w 5328 212452 d 704 74780 f 2156 2156 iot 11740 11025 th 467368 0 0 pt 0 inp 0 0 216.995
,07-17 13:39:06.436  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-17 13:39:08.105  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:39:08.106  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755696, nowELAPSED=218850
07-17 13:39:08.107  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@bbd0bec alarm=Alarm{edce916 type 2 when 218849 android}
,07-17 13:39:08.111  3704  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,07-17 13:39:08.114 10093 10093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-17 13:39:08.117 10093 10093 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-17 13:39:08.122  3704  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T133924 - CU:1000/CP:3704
07-17 13:39:08.123  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=218867
,07-17 13:39:08.131  3704  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T133923 - CU:1000/CP:3704
,07-17 13:39:08.133 10093 10093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-17 13:39:08.162  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:08.163  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:39:08.548  3704  3788 I ActivityManager: Waited long enough for: ServiceRecord{3edf5c u0 com.samsung.android.sm.policy/.PolicyHandlerService}
,07-17 13:39:08.932  9623  9687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
07-17 13:39:08.933  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-17 13:39:08.934  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-17 13:39:08.934  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-17 13:39:08.935  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-17 13:39:08.935  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-17 13:39:08.935  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-17 13:39:08.948  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-17 13:39:08.949  9623  9687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-17 13:39:08.949  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-17 13:39:08.956  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:08.959  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:08.962  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:08.970  9623  9687 D BluetoothAdapter: isSecureModeEnabled
,07-17 13:39:08.971  9764  9775 D BtConfig.SecureMode: isSecureModeOn:false
,07-17 13:39:08.973  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:08.973  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-17 13:39:08.977  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:08.980  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:08.980  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-17 13:39:08.981  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-17 13:39:08.981  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,07-17 13:39:08.989  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:08.992  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:09.001  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:09.004  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:09.009  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:09.009  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-17 13:39:09.009  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-17 13:39:09.009  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 36489
,07-17 13:39:09.011  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=36489, mManufacturerData=null, mManufacturerDataMask=null]
,07-17 13:39:09.012  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:09.013  9623  9687 D BluetoothLeScanner: Start Scan
,07-17 13:39:09.016  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:09.019  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:09.023  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:09.026  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:09.032  9764  9785 D BtGatt.GattService: registerClient() - UUID=531a9f4c-92f7-4bcd-ac99-ac726e1c6f46
,07-17 13:39:09.137  9764  9784 D BtGatt.GattService: onClientRegistered() - UUID=531a9f4c-92f7-4bcd-ac99-ac726e1c6f46, clientIf=5, status=0
,07-17 13:39:09.138  9623  9634 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
07-17 13:39:09.139  9764  9786 D BtGatt.GattService: start scan with filters
,07-17 13:39:09.145  9764  9786 D BtGatt.GattService: getScanSettings
,07-17 13:39:09.147  9764  9786 D BtGatt.GattService: Is it foreground application = true
07-17 13:39:09.148  9764  9786 D BtGatt.GattService: not a background application
,07-17 13:39:09.161  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
07-17 13:39:09.162  9764  9812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:39:09.162  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
07-17 13:39:09.162  9764  9802 D BtGatt.ScanManager: handling starting scan
07-17 13:39:09.163  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:09.163  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-17 13:39:09.164  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:09.165  9764  9802 D BluetoothAdapter: STATE_ON
07-17 13:39:09.165  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-17 13:39:09.167  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-17 13:39:09.167  9764  9802 D BluetoothAdapter: STATE_ON
07-17 13:39:09.168  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:39:09.168  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
07-17 13:39:09.168  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-17 13:39:09.169  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:39:09.170  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
07-17 13:39:09.171  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-17 13:39:09.172  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,07-17 13:39:09.180  3704  3788 I ActivityManager: KPU : put [com.sec.android.app.shealth] : 30196 K
,07-17 13:39:09.180  3704  3788 I ActivityManager: Killing 7426:com.sec.android.app.shealth/u0a36 (adj 906): DHA:empty #33
,07-17 13:39:09.182  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-17 13:39:09.182  3704  3788 I ActivityManager: KPU : put [com.google.android.gm] : 30140 K
07-17 13:39:09.182  3704  3788 I ActivityManager: Killing 8591:com.google.android.gm/u0a108 (adj 906): DHA:empty #33
,07-17 13:39:09.185  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:09.185  9764  9784 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-17 13:39:09.186  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:09.186  9764  9802 D BtGatt.ScanManager: set filter index= 6 for clientIf= 5
07-17 13:39:09.186  9764  9802 D BtGatt.ScanManager: High Rssi Filter value is = -128
07-17 13:39:09.186  9764  9802 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-17 13:39:09.186  9764  9802 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
07-17 13:39:09.193  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:09.193  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-17 13:39:09.194  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:09.195  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:09.195  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-17 13:39:09.202  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-17 13:39:09.203  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-17 13:39:09.203  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-17 13:39:09.204  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-17 13:39:09.205  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,07-17 13:39:09.205  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:09.206  9764  9802 D BtGatt.ScanManager: Starting BLE batch scan
,07-17 13:39:09.206  9764  9802 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-17 13:39:09.220  9764  9784 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-17 13:39:09.220  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:09.228  9764  9784 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-17 13:39:09.229  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:09.230  3704  3911 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{b1c4cf0: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:09.238  3704  5299 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133909 - CU:1002/CP:9764
07-17 13:39:09.239  3704  5299 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133910, SetElapsed=220975, nowELAPSED=219982
,07-17 13:39:09.257  3704  4752 D ActivityManager: cleanUpApplicationRecord -- 7426
,07-17 13:39:09.262  4670  4686 D ForegroundUtils: could not check pending caller
07-17 13:39:09.262  3704  6511 D ActivityManager: cleanUpApplicationRecord -- 8591
,07-17 13:39:09.265  4670  4687 D ForegroundUtils: could not check pending caller
,07-17 13:39:09.705  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
07-17 13:39:09.706  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-17 13:39:09.706  9623  9623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-17 13:39:10.231  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:39:10.232  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=220976
07-17 13:39:10.233  3704  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{c1e1269 type 2 when 220474 com.android.bluetooth}
,07-17 13:39:10.240  9764  9764 D BtGatt.ScanManager: awakened up at time 220984
,07-17 13:39:10.242  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:10.254  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:10.255  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:10.258  3704  4740 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{8a004ee: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:10.270  3704  9909 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133910 - CU:1002/CP:9764
07-17 13:39:10.271  3704  9909 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133911, SetElapsed=222004, nowELAPSED=221014
,07-17 13:39:10.426  3704  9910 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.talk cmp = com.google.android.apps.hangouts.phone.ShareIntentSmsOnlyActivity newState = 2 callingPackage = 10112
,07-17 13:39:10.450 10239 10239 I Babel_ConcService: Binding ConcurrentService
,07-17 13:39:10.507 10239 10294 I Babel_ConcService: Scheduling delay with GcmNetworkManager of 244834 s for task fstaccount_reg_renewal_26828_3 and tag network_connectivity_wakeup:persisted
,07-17 13:39:10.513 10239 10295 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
,07-17 13:39:10.517 10239 10295 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-17 13:39:10.536 10239 10294 I Babel_ConcService: Scheduling delay with GcmNetworkManager of 3599 s for task fvzDB_CLEANUP_221145_1 and tag timed_wakeup
,07-17 13:39:10.539 10239 10296 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
,07-17 13:39:10.541 10239 10296 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-17 13:39:10.544 10239 10297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:10.545 10239 10297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:10.547 10239 10298 I Babel_ConcService: Acquired partial wake lock to keep ConcurrentService alive
,07-17 13:39:10.547  3300  3772 D EnterpriseController: netId is 0
07-17 13:39:10.547  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10112
07-17 13:39:10.547  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:39:10.550 10239 10298 I Babel_ConcService: Released partial wake lock as ConcurrentService became idle
,07-17 13:39:10.571  3704  3759 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{314d220: PendingIntentRecord{b109a37 com.google.android.gms broadcastIntent}}
,07-17 13:39:10.572  3704  3759 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133910, SetElapsed=221503, nowELAPSED=221316
,07-17 13:39:10.652  3704  4753 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143606 - CU:10019/CP:4626
,07-17 13:39:10.663  3704  5299 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{60d859e: PendingIntentRecord{b109a37 com.google.android.gms broadcastIntent}}
,07-17 13:39:10.694  3704  5299 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143606 - CU:10019/CP:4626
,07-17 13:39:10.706  3704  9909 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143606 - CU:10019/CP:4626
,07-17 13:39:10.714  3704  3920 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{8ac387f: PendingIntentRecord{b109a37 com.google.android.gms broadcastIntent}}
,07-17 13:39:10.759  3704  3866 D SamsungAlarmManager: Expired : 4
07-17 13:39:10.759  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=221503
,07-17 13:39:10.760  3704  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{ad9a895 type 2 when 221503 com.android.bluetooth}
,07-17 13:39:10.764  9764  9764 D BtGatt.ScanManager: awakened up at time 221508
,07-17 13:39:10.765  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:10.772  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-17 13:39:10.772  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:10.773  3704  4740 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{8485daa: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:10.784  3704  3911 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133911 - CU:1002/CP:9764
07-17 13:39:10.784  3704  3911 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133911, SetElapsed=222517, nowELAPSED=221528
,07-17 13:39:10.842  3704  5299 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143910 - CU:10019/CP:4626
,07-17 13:39:10.877  3704  4752 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133911, SetElapsed=222017, nowELAPSED=221621
,07-17 13:39:10.883  3704  4752 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143910 - CU:10019/CP:4626
,07-17 13:39:10.898  3704  4753 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{9f4924e: PendingIntentRecord{b109a37 com.google.android.gms broadcastIntent}}
,07-17 13:39:10.915  3704  3760 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143606 - CU:10019/CP:4626
,07-17 13:39:10.917  3285  3353 I Drm     : android::Drm::Drm() is called from com.google.android.gms.unstable(pid:9487)
,07-17 13:39:10.929  9487  9500 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:39:10.929  9487  9500 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:39:10.931  3300  3772 D EnterpriseController: netId is 0
07-17 13:39:10.931  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-17 13:39:10.931  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:39:10.939  3285  3353 D WVCdm   : Instantiating CDM.
,07-17 13:39:10.940  3285  9509 I Drm     : virtual status_t android::Drm::openSession(Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:9487)
07-17 13:39:10.940  3285  9509 I WVCdm   : CdmEngine::OpenSession
,07-17 13:39:10.941  3285  9509 I WVCdm   : Level3 Library 4445 Mar 30 2016 13:23:54
,07-17 13:39:10.944  3285  9509 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-17 13:39:10.946  3285  9509 E wv_dash : No saved usage table. Creating new table.
,07-17 13:39:10.959  3285  9509 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
,07-17 13:39:10.967  3704  5557 D SSRM:f  : SIOP:: AP = 270, PST = 280 (W:10), CP = 224, CUR = 137, LCD = 57
,07-17 13:39:10.982  3285  9509 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,07-17 13:39:11.013  3285  9509 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-17 13:39:11.014  3285  3353 I WVCdm   : CdmEngine::GenerateKeyRequest
,07-17 13:39:11.017  3285  3353 D WVCdm   : PrepareKeyRequest: nonce=2961761431
,07-17 13:39:11.070 10239 10297 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,07-17 13:39:11.115 10239 10297 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 242 native methods...
,07-17 13:39:11.139 10239 10297 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,07-17 13:39:11.142 10239 10297 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-17 13:39:11.173  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:11.173  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:39:11.255  4528  4528 D io_stats: !@   8,0 r 26167 2309884 w 5409 213116 d 710 74804 f 2186 2186 iot 11780 11052 th 470832 0 0 pt 0 inp 0 0 221.998
,07-17 13:39:11.273  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:39:11.273  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=222017
,07-17 13:39:11.274  3704  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{80a3f6f type 2 when 222017 com.android.bluetooth}
,07-17 13:39:11.276  9764  9764 D BtGatt.ScanManager: awakened up at time 222020
07-17 13:39:11.277  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:11.283  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:11.283  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:11.284  3704  9909 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{a8b047c: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:11.290  3704  4753 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133911 - CU:1002/CP:9764
07-17 13:39:11.291  3704  4753 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133912, SetElapsed=223028, nowELAPSED=222035
,07-17 13:39:11.314  3285  3285 I Drm     : virtual status_t android::Drm::closeSession(const Vector<uint8_t> &) is called from com.google.android.gms.unstable(pid:9487)
07-17 13:39:11.314  3285  3285 I WVCdm   : CdmEngine::CloseSession
,07-17 13:39:11.321  3285  3285 I TeeDriverClient: driver client closed [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:113]
,07-17 13:39:12.200  9623  9687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,07-17 13:39:12.201  9623  9687 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
07-17 13:39:12.201  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,07-17 13:39:12.202  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,07-17 13:39:12.210  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-17 13:39:12.210  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-17 13:39:12.211  3300  3769 D Netd    : Iface wlan0 link up
07-17 13:39:12.211 10093 10093 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
07-17 13:39:12.215  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
,07-17 13:39:12.215  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:39:12.216  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.216  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
07-17 13:39:12.220  3704  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@c9aec84
,07-17 13:39:12.222  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133911, SetElapsed=222528, nowELAPSED=222966
07-17 13:39:12.223  3704  3866 D SamsungAlarmManager: Expired : 4
07-17 13:39:12.224  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-17 13:39:12.224  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
07-17 13:39:12.224 10239 10297 I Babel   : connection state changed from UNKNOWN to CONNECTED
07-17 13:39:12.225  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.226  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=222970
,07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 36489
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
07-17 13:39:12.227  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.227  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
07-17 13:39:12.228  3704  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{c76e105 type 2 when 222528 com.android.bluetooth}
07-17 13:39:12.228  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.229  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.230  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-17 13:39:12.230  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-17 13:39:12.231  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.232  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.233  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.235  9764  9764 D BtGatt.ScanManager: awakened up at time 222979
,07-17 13:39:12.237  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:12.240  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.242  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.243  9764  9786 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,07-17 13:39:12.244  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,07-17 13:39:12.246  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:12.248  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:12.248  9623  9687 D BluetoothLeScanner: Stop Scan
07-17 13:39:12.251  9764  9786 D BtGatt.GattService: stopScan() - queue size =1
07-17 13:39:12.252  9764  9786 D BtGatt.GattService: stopScan() - queue size =1
07-17 13:39:12.252  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-17 13:39:12.253  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:12.253  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:12.254  3704  4753 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{60b855a: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
07-17 13:39:12.259  9764  9775 D BtGatt.GattService: unregisterClient() - clientIf=5
07-17 13:39:12.261  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-17 13:39:12.261  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.262  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-17 13:39:12.262  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.262  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-17 13:39:12.263  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.264  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.264  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-17 13:39:12.264  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-17 13:39:12.264  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 36489
07-17 13:39:12.264  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=36489, mManufacturerData=null, mManufacturerDataMask=null]
07-17 13:39:12.264  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.265  9623  9687 D BluetoothLeScanner: Start Scan
07-17 13:39:12.267  3704  3920 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133912 - CU:1002/CP:9764
07-17 13:39:12.267  3704  3920 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133913, SetElapsed=224003, nowELAPSED=223011
,07-17 13:39:12.268  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.269  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-17 13:39:12.273  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.275  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:12.275  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:12.275  9764  9784 E BtGatt.ContextMap: Context not found for ID 5
07-17 13:39:12.276  3704  6348 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{325638b: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
07-17 13:39:12.278  3704  6348 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=223022
07-17 13:39:12.279  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.280  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.283  9764  9776 D BtGatt.GattService: registerClient() - UUID=f41b71d2-9c45-4ac2-9862-5ff57abfd02b
,07-17 13:39:12.288  3704  9910 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133912 - CU:1002/CP:9764
07-17 13:39:12.288  3704  9910 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133913, SetElapsed=224023, nowELAPSED=223032
,07-17 13:39:12.290  9764  9802 D BtGatt.ScanManager: filter size is 1
,07-17 13:39:12.290  9764  9802 D BtGatt.ScanManager: delete FilterIndex - 6
,07-17 13:39:12.296  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-17 13:39:12.296  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:12.296  9764  9802 D BtGatt.ScanManager: stopping BLe Batch
,07-17 13:39:12.302  9764  9784 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-17 13:39:12.303  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:12.303  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:12.308  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:12.308  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:12.309  3704  4182 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{3c1ec68: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
07-17 13:39:12.310  3704  4182 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=223053
07-17 13:39:12.311  3704  6347 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{98881: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:12.385  9764  9784 D BtGatt.GattService: onClientRegistered() - UUID=f41b71d2-9c45-4ac2-9862-5ff57abfd02b, clientIf=5, status=0
,07-17 13:39:12.386  9623  9634 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
07-17 13:39:12.386  9764  9785 D BtGatt.GattService: start scan with filters
,07-17 13:39:12.388  9764  9785 D BtGatt.GattService: getScanSettings
,07-17 13:39:12.390  9764  9785 D BtGatt.GattService: Is it foreground application = true
07-17 13:39:12.390  9764  9785 D BtGatt.GattService: not a background application
,07-17 13:39:12.395  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,07-17 13:39:12.395  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,07-17 13:39:12.395  9764  9812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f6b5171
07-17 13:39:12.396  9764  9802 D BtGatt.ScanManager: handling starting scan
07-17 13:39:12.396  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.396  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-17 13:39:12.396  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.397  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
07-17 13:39:12.397  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.398  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.398  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-17 13:39:12.398  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,07-17 13:39:12.398  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
07-17 13:39:12.398  9623  9687 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
07-17 13:39:12.398  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.398  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-17 13:39:12.399  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-17 13:39:12.399  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.399  9764  9802 D BluetoothAdapter: STATE_ON
07-17 13:39:12.401  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-17 13:39:12.402  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-17 13:39:12.402  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
07-17 13:39:12.402  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-17 13:39:12.402  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-17 13:39:12.402  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
07-17 13:39:12.402  9764  9802 D BluetoothAdapter: STATE_ON
07-17 13:39:12.402  9623 10312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
07-17 13:39:12.403  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,07-17 13:39:12.405  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
07-17 13:39:12.405  9623  9687 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-17 13:39:12.411  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.411  9764  9784 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-17 13:39:12.411  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:12.412  9764  9802 D BtGatt.ScanManager: set filter index= 7 for clientIf= 5
07-17 13:39:12.412  9764  9802 D BtGatt.ScanManager: High Rssi Filter value is = -128
,07-17 13:39:12.412  9764  9802 D BtGatt.ScanManager: Low Rssi Filter value is = -128
07-17 13:39:12.412  9764  9802 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
07-17 13:39:12.413  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.414  9623 10312 D BluetoothSocket: bindListen(): myUserId = 0
07-17 13:39:12.414  9623 10312 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-17 13:39:12.417  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
07-17 13:39:12.417  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:12.418  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:12.418  9764  9802 D BtGatt.ScanManager: Starting BLE batch scan
07-17 13:39:12.418  9764  9802 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-17 13:39:12.420  9623 10312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
07-17 13:39:12.420  9623 10312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@25ddac4, port: 6, type: 1, local socket address: null, socket type: 0
,07-17 13:39:12.422  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:12.428  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:12.428  9764  9784 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-17 13:39:12.428  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:12.433  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.433  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.434  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.434  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
07-17 13:39:12.434  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
07-17 13:39:12.434  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "9823b41d-e4b3-4cc0-9bad-a60fa5a52179", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,07-17 13:39:12.434  9764  9784 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-17 13:39:12.434  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:12.434  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 4A 3E
07-17 13:39:12.435  9623  9687 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:39:12.435  3704  4753 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{6c9d26: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
07-17 13:39:12.435  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:39:12.435  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.436  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.436  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
07-17 13:39:12.436  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
07-17 13:39:12.437  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.437  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.438  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[9823b41d-e4b3-4cc0-9bad-a60fa5a52179], mManufacturerSpecificData={}, mServiceData={9823b41d-e4b3-4cc0-9bad-a60fa5a52179=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.440  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:12.442  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:12.442  9623  9687 D BluetoothAdapter: isSecureModeEnabled
07-17 13:39:12.443  9764  9841 D BtConfig.SecureMode: isSecureModeOn:false
07-17 13:39:12.443  9623  9687 D BluetoothLeAdvertiser: start advertising
07-17 13:39:12.444  3704  9909 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133912 - CU:1002/CP:9764
07-17 13:39:12.444  3704  9909 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133913, SetElapsed=224180, nowELAPSED=223188
07-17 13:39:12.444  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:12.450  9764  9785 D BtGatt.GattService: registerClient() - UUID=5e57ee17-cbb9-4429-af12-ef211846ce49
,07-17 13:39:12.553  9764  9784 D BtGatt.GattService: onClientRegistered() - UUID=5e57ee17-cbb9-4429-af12-ef211846ce49, clientIf=6, status=0
,07-17 13:39:12.554  9623  9739 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,07-17 13:39:12.559  9764  9841 E BtGatt.ContextMap: Context not found for ID 6
,07-17 13:39:12.560  9764  9801 D BtGatt.AdvertiseManager: message : 0
07-17 13:39:12.560  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,07-17 13:39:12.562  9764  9801 D BtGatt.AdvertiseManager: number of adv instance running = 0
07-17 13:39:12.562  9764  9801 D BtGatt.AdvertiseManager: size of list is =0
,07-17 13:39:12.571  9764  9801 D BtGatt.AdvertiseManager: starting advertising
,07-17 13:39:12.578  9764  9801 D BtGatt.AdvertiseManager: isStandardAdv = false
,07-17 13:39:12.582  9764  9819 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,07-17 13:39:12.605  9764  9784 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,07-17 13:39:12.609  9764  9801 D BtGatt.AdvertiseManager: starting multi advertising
,07-17 13:39:12.622  9764  9784 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
07-17 13:39:12.622  9764  9801 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
,07-17 13:39:12.622  9764  9801 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
07-17 13:39:12.623  9764  9801 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
07-17 13:39:12.623  9764  9801 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
07-17 13:39:12.624  9623  9635 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,07-17 13:39:12.626  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.627  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.628  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
07-17 13:39:12.629  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.630  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.631  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.632  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.633  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.635  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.638  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.639  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:12.639  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
07-17 13:39:12.640  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
,07-17 13:39:12.640  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-17 13:39:12.644  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-17 13:39:12.646  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.655  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.655  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.660  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:12.661  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-17 13:39:12.662  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.663  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
07-17 13:39:12.663  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,07-17 13:39:12.664  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.664  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.665  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,07-17 13:39:12.666  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.666  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
07-17 13:39:12.666  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,07-17 13:39:12.667  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.667  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.668  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,07-17 13:39:12.669  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.669  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,07-17 13:39:12.675  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.675  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-17 13:39:12.675  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.676  9623  9623 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
07-17 13:39:12.677  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,07-17 13:39:13.178  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
07-17 13:39:13.179  9623  9623 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-17 13:39:13.179  9623  9623 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,07-17 13:39:13.289  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:39:13.290  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 13:39:13.292  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:39:13.292  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:39:13.341  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:13.436  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:39:13.437  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=224181
07-17 13:39:13.438  3704  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{784ad67 type 2 when 223679 com.android.bluetooth}
,07-17 13:39:13.444  9764  9764 D BtGatt.ScanManager: awakened up at time 224188
,07-17 13:39:13.447  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:13.459  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-17 13:39:13.459  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:13.460  3704  4338 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{4fd6714: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:13.471  3704  3920 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133913 - CU:1002/CP:9764
07-17 13:39:13.471  3704  3920 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133914, SetElapsed=225206, nowELAPSED=224215
,07-17 13:39:14.034  3704  4236 E Watchdog: !@Sync 7 [17_lip_13_39_14.033]
,07-17 13:39:14.206  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:14.206  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:14.462  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:39:14.463  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=225207
07-17 13:39:14.464  3704  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{2c52bbd type 2 when 224705 com.android.bluetooth}
,07-17 13:39:14.470  9764  9764 D BtGatt.ScanManager: awakened up at time 225214
,07-17 13:39:14.473  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:14.483  3704  9910 I ActivityManager: KPU : put [com.samsung.android.app.watchmanager:contentprovider] : 24440 K
,07-17 13:39:14.484  3704  9910 I ActivityManager: Killing 9277:com.samsung.android.app.watchmanager:contentprovider/u0a18 (adj 906): DHA:empty #33
07-17 13:39:14.487  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:14.487  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:14.488  3704  4183 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{27565b2: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:14.517  3704  3760 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133914 - CU:1002/CP:9764
07-17 13:39:14.517  3704  3760 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133915, SetElapsed=226240, nowELAPSED=225261
,07-17 13:39:14.535  3704  3911 D ActivityManager: cleanUpApplicationRecord -- 9277
,07-17 13:39:14.538  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:39:15.496  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:39:15.497  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=226241
07-17 13:39:15.498  3704  3866 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{aa4b903 type 2 when 225738 com.android.bluetooth}
,07-17 13:39:15.504  9764  9764 D BtGatt.ScanManager: awakened up at time 226248
,07-17 13:39:15.506  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:15.519  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:15.519  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-17 13:39:15.521  3704  5299 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{3d3e080: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:15.536  3704  4182 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133916 - CU:1002/CP:9764
07-17 13:39:15.537  3704  4182 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133916, SetElapsed=227267, nowELAPSED=226280
,07-17 13:39:15.667  9623  9687 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,07-17 13:39:15.669  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-17 13:39:15.669  9623  9687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-17 13:39:15.669  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-17 13:39:15.669  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-17 13:39:15.670  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-17 13:39:15.670  9623 10312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-17 13:39:15.670  9623 10312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-17 13:39:15.670  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
07-17 13:39:15.671  9623 10312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-17 13:39:15.671  9623  9687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-17 13:39:15.671  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-17 13:39:15.671  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-17 13:39:15.671  9623  9687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc415df removed from the list
07-17 13:39:15.671  9623  9623 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
07-17 13:39:15.671  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc415df removed from the list
07-17 13:39:15.671  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-17 13:39:15.672  9623  9687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-17 13:39:15.672  9623  9623 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-17 13:39:15.673  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.673  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
07-17 13:39:15.673  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-17 13:39:15.674  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.675  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:15.677  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.677  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-17 13:39:15.678  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:15.682  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:15.684  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:15.686  9764  9775 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,07-17 13:39:15.687  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
07-17 13:39:15.688  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:15.691  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:15.695  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:15.696  9623  9687 D BluetoothLeScanner: Stop Scan
,07-17 13:39:15.699  3704  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-17 13:39:15.701  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:15.701  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:15.702  3704  9909 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{29dc6b9: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
07-17 13:39:15.703  9764  9776 D BtGatt.GattService: stopScan() - queue size =1
07-17 13:39:15.703  9764  9776 D BtGatt.GattService: stopScan() - queue size =1
,07-17 13:39:15.704  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
07-17 13:39:15.704  3704  9909 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=226448
,07-17 13:39:15.707  9764  9786 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-17 13:39:15.708  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-17 13:39:15.709  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.709  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-17 13:39:15.710  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:15.710  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.711  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.711  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
07-17 13:39:15.712  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:15.714  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:15.715  3704  3924 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20170717T133916 - CU:1002/CP:9764
07-17 13:39:15.715  3704  3924 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133916, SetElapsed=227449, nowELAPSED=226459
,07-17 13:39:15.716  9623  9687 D BluetoothAdapter: STATE_ON
07-17 13:39:15.716  9623  9687 D BluetoothLeAdvertiser: stop advertising
07-17 13:39:15.718  9764  9802 D BtGatt.ScanManager: filter size is 1
07-17 13:39:15.718  9764  9802 D BtGatt.ScanManager: delete FilterIndex - 7
,07-17 13:39:15.718  9764  9841 E BtGatt.ContextMap: Context not found for ID 6
07-17 13:39:15.719  9764  9812 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
07-17 13:39:15.719  9764  9801 D BtGatt.AdvertiseManager: message : 1
07-17 13:39:15.720  9764  9801 D BtGatt.AdvertiseManager: stop advertise for client =  6
07-17 13:39:15.720  9764  9801 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
07-17 13:39:15.722  9764  9801 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,07-17 13:39:15.724  9764  9784 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
07-17 13:39:15.724  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:15.724  9764  9802 D BtGatt.ScanManager: stopping BLe Batch
,07-17 13:39:15.729  9764  9784 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,07-17 13:39:15.729  9764  9784 D BtGatt.GattService: Client app is not null!
07-17 13:39:15.730  9623  9739 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,07-17 13:39:15.732  9764  9776 D BtGatt.GattService: unregisterClient() - clientIf=6
,07-17 13:39:15.734  9764  9784 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-17 13:39:15.734  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:15.734  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-17 13:39:15.734  9764  9802 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-17 13:39:15.735  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.735  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
07-17 13:39:15.735  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:15.737  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:15.740  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.740  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-17 13:39:15.740  9764  9784 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-17 13:39:15.740  9764  9784 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-17 13:39:15.741  9623  9687 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-17 13:39:15.741  3704  6348 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{bd02afe: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
07-17 13:39:15.742  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-17 13:39:15.742  3704  6348 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133924, SetElapsed=234857, nowELAPSED=226486
07-17 13:39:15.742  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.743  3704  3924 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9764 / op:PendingIntent{32fe25f: PendingIntentRecord{ab24e53 com.android.bluetooth broadcastIntent}}
,07-17 13:39:15.745  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.745  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-17 13:39:15.746  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 119
,07-17 13:39:15.747  9623  9687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 119
07-17 13:39:15.747  9623  9687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa1722c removed from the list
07-17 13:39:15.747  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:39:15.747  9623  9687 D io.jxcore.node.ConnectivityMonitor: stop
07-17 13:39:15.747  9623  9687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-17 13:39:15.747  9623  9687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-17 13:39:15.747  9623  9623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-17 13:39:15.748  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-17 13:39:15.748  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:39:15.748  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-17 13:39:15.748  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
07-17 13:39:15.749  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:39:15.749  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
07-17 13:39:15.750  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
07-17 13:39:15.750  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-17 13:39:15.750  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-17 13:39:15.750  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-17 13:39:15.750  9623  9623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
07-17 13:39:15.750  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-17 13:39:15.750  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
07-17 13:39:15.751  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
07-17 13:39:15.751  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
07-17 13:39:15.751  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-17 13:39:15.751  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNN,ING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-17 13:39:15.751  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
07-17 13:39:15.751  9623  9687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-17 13:39:15.751  9623  9623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
07-17 13:39:15.751  9623  9623 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-17 13:39:15.752  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,07-17 13:39:15.755  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,07-17 13:39:15.759  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,07-17 13:39:15.760  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,07-17 13:39:15.762  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
,07-17 13:39:15.764  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,07-17 13:39:15.765  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,07-17 13:39:15.767  9623  9687 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,07-17 13:39:16.253  9623  9623 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-17 13:39:16.259  4528  4528 D io_stats: !@   8,0 r 26167 2309884 w 5433 213436 d 714 74820 f 2193 2193 iot 11790 11064 th 472648 0 0 pt 0 inp 0 0 227.001
,07-17 13:39:17.233  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:17.236  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:17.246  4626  6458 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:39:17.247  4626  6458 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:17.250  3300  3772 D EnterpriseController: netId is 0
,07-17 13:39:17.250  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-17 13:39:17.250  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:39:17.429  4626  6458 W Conscrypt: Could not set socket write timeout: null
,07-17 13:39:17.566  4626  6458 W Conscrypt: Could not set socket write timeout: null
,07-17 13:39:17.670  3704  6348 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{a7d3f98: PendingIntentRecord{b109a37 com.google.android.gms broadcastIntent}}
,07-17 13:39:17.685  3704  6511 I ActivityManager: KPU : put [com.google.android.apps.photos:CameraShortcut] : 32904 K
,07-17 13:39:17.685  3704  6511 I ActivityManager: Killing 9328:com.google.android.apps.photos:CameraShortcut/u0a129 (adj 906): DHA:empty #33
,07-17 13:39:17.746  3704  4183 D ActivityManager: cleanUpApplicationRecord -- 9328
,07-17 13:39:17.750  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:39:17.770  9623  9687 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,07-17 13:39:17.780  3704  3911 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143910 - CU:10019/CP:4626
,07-17 13:39:17.822  3704  9911 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143910 - CU:10019/CP:4626
,07-17 13:39:17.863  3704  9911 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{7ac9bd6: PendingIntentRecord{b109a37 com.google.android.gms broadcastIntent}}
,07-17 13:39:17.870  9623 10322 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 251, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:17.870  9623 10322 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:17.870  9623 10322 D io.jxcore.node.StreamCopyingThread:  id: 83
,07-17 13:39:17.877  3704  9911 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143910 - CU:10019/CP:4626
,07-17 13:39:17.885  3704  4184 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{97dbe57: PendingIntentRecord{b109a37 com.google.android.gms broadcastIntent}}
,07-17 13:39:17.914  3704  4328 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143910 - CU:10019/CP:4626
,07-17 13:39:18.002  9623  9628 I art     : Do partial code cache collection, code=18KB, data=31KB
,07-17 13:39:18.003  9623  9628 I art     : After code cache collection, code=17KB, data=30KB
07-17 13:39:18.003  9623  9628 I art     : Increasing code cache capacity to 128KB
,07-17 13:39:18.028  4626 10321 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-17 13:39:18.037  4626 10321 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-17 13:39:18.045  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
07-17 13:39:18.049  3704  3920 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.094  4626 10321 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:39:18.095  4626 10321 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:18.096  3300  3772 D EnterpriseController: netId is 0
,07-17 13:39:18.096  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10019
07-17 13:39:18.096  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:39:18.538  3704  3759 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.550  3704  4752 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.559  3704  4183 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.569  3704  6348 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.577  3704  5299 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.585  3704  4740 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.595  3704  3760 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.601  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:18.612  3704  5299 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.617  9623 10322 W !!      : call onHalfStreamCopied
,07-17 13:39:18.617  9623 10322 I testCopyDataAndClose: closing input stream
,07-17 13:39:18.624  3704  4740 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.635  3704  3760 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.644  3704  6347 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.654  3704  9910 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.664  3704  4753 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.672  3704  3759 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.684  4626 10321 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-17 13:39:18.684  4626 10321 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:18.810  4626 10321 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-17 13:39:18.818  3704  4752 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-17 13:39:18.833  4626 10321 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:18.833  4626 10321 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:39:19.152  4626 10321 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-17 13:39:19.204  3704  6511 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143910 - CU:10019/CP:4626
,07-17 13:39:19.211  3704  3760 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4626 / op:PendingIntent{135e8f3: PendingIntentRecord{b109a37 com.google.android.gms broadcastIntent}}
,07-17 13:39:19.223  3704  9910 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20170717T143910 - CU:10019/CP:4626
,07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 251, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread:  id: 83
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread:  id: 83
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 251, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:19.281  9623 10322 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-17 13:39:20.259  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:20.259  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:20.708  9623  9687 I StreamCopyingThreadTest: Starting test: testCopyBigData
,07-17 13:39:20.743  9623 10327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 254, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:20.743  9623 10327 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:20.743  9623 10327 D io.jxcore.node.StreamCopyingThread:  id: 85
,07-17 13:39:20.981  3704  5557 D SSRM:f  : SIOP:: AP = 300, PST = 282 (W:6), CP = 223, CUR = 30, LCD = 57
,07-17 13:39:21.263  4528  4528 D io_stats: !@   8,0 r 26181 2310152 w 5581 215608 d 745 74956 f 2249 2249 iot 11920 11147 th 473828 0 0 pt 0 inp 0 0 232.006
,07-17 13:39:21.732  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:21.744  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:21.753  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:21.764  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:21.769  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:22.109  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 254, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread:  id: 85
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread:  id: 85
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 254, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:22.134  9623 10327 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,07-17 13:39:22.437  3704  3931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,07-17 13:39:23.276  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:23.276  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:23.513  9623  9687 I StreamCopyingThreadTest: Starting test: testRunNotify
,07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 256, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread:  id: 86
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 256, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread:  id: 86
,07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread:  id: 86
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 256, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:23.513  9623 10328 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
07-17 13:39:23.514  9623  9687 I StreamCopyingThreadTest: Starting test: testSetBufferSize
07-17 13:39:23.514  9623  9687 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
07-17 13:39:23.514  9623  9687 I StreamCopyingThreadTest: Starting test: testRunWithException
07-17 13:39:23.514  9623 10329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 260, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:23.514  9623 10329 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:23.514  9623 10329 D io.jxcore.node.StreamCopyingThread:  id: 89
07-17 13:39:23.515  9623 10329 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 260, thread name: My test thread name): Test exception.
07-17 13:39:23.515  9623 10329 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 260, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:23.515  9623 10329 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:23.515  9623 10329 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-17 13:39:23.515  9623 10329 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
07-17 13:39:23.515  9623 10329 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 260, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
07-17 13:39:23.515  9623 10329 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
07-17 13:39:23.515  9623 10329 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
07-17 13:39:23.516  9623  9687 I jxcore-log: 2017-07-17 11:39:23 - DEBUG UnitTest_app: 'Running unit tests'
07-17 13:39:23.516  9623  9687 I jxcore-log: 
07-17 13:39:23.516  9623  9687 I jxcore-log: *Native tests were executed*
07-17 13:39:23.516  9623  9687 I jxcore-log: 
07-17 13:39:23.516  9623  9687 I jxcore-log: Total number of executed tests:  78
07-17 13:39:23.516  9623  9687 I jxcore-log: 
07-17 13:39:23.516  9623  9687 I jxcore-log: Number of passed tests:  76
07-17 13:39:23.516  9623  9687 I jxcore-log: 
07-17 13:39:23.516  9623  9687 I jxcore-log: Number of failed tests:  0
07-17 13:39:23.516  9623  9687 I jxcore-log: 
07-17 13:39:23.516  9623  9687 I jxcore-log: Number of ignored tests:  2
07-17 13:39:23.516  9623  9687 I jxcore-log: 
07-17 13:39:23.516  9623  9687 I jxcore-log: Total duration:  48205
07-17 13:39:23.516  9623  9687 I jxcore-log: 
07-17 13:39:23.516  9623  9687 I jxcore-log: 2017-07-17 11:39:23 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
07-17 13:39:23.516  9623  9687 I jxcore-log: 
07-17 13:39:23.517  9623  9687 I jxcore-log: 2017-07-17 11:39:23 - WARN testUtils: 'myNameCallback not set!'
07-17 13:39:23.517  9623  9687 I jxcore-log: 
,07-17 13:39:24.113  3704  3866 D SamsungAlarmManager: Expired : 4
07-17 13:39:24.113  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755696, nowELAPSED=234857
07-17 13:39:24.113  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@182297 alarm=Alarm{a90b8ba type 2 when 234857 android}
07-17 13:39:24.114  3704  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 32000: mInRange : true
,07-17 13:39:24.116 10093 10093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-17 13:39:24.116 10093 10093 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-17 13:39:24.124  3704  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T133956 - CU:1000/CP:3704
,07-17 13:39:24.124  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133956, SetElapsed=266859, nowELAPSED=234868
07-17 13:39:24.126  3704  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T133939 - CU:1000/CP:3704
07-17 13:39:24.126  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133939, SetElapsed=249865, nowELAPSED=234870
,07-17 13:39:24.130 10093 10093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-17 13:39:24.145  4783  4840 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 3ms lastUpdatedAfter : 31963 ms mFlush_time_threasold : 2000 mCurrentSize : 229
,07-17 13:39:24.173  4989 10331 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-17 13:39:24.207  4989  5802 I Icing   : App usage reports: 1
,07-17 13:39:24.207  4989  5802 I Icing   : Usage reports 1 indexed 0 rejected 0 imm upload false
,07-17 13:39:24.251  4989  5802 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-17 13:39:24.279  4989  5802 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-17 13:39:24.302  4989  5802 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-17 13:39:24.331  4989  5802 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-17 13:39:24.363  4989  5738 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-17 13:39:24.390  4989  5738 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,07-17 13:39:24.947  9623  9687 I jxcore-log: 2017-07-17 11:39:24 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
07-17 13:39:24.947  9623  9687 I jxcore-log: 
,07-17 13:39:24.951  9623  9687 I jxcore-log: 2017-07-17 11:39:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
07-17 13:39:24.951  9623  9687 I jxcore-log: 
,07-17 13:39:24.961  9623  9687 I jxcore-log: 2017-07-17 11:39:24 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
07-17 13:39:24.961  9623  9687 I jxcore-log: 
,07-17 13:39:25.118  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
07-17 13:39:25.118  9623  9687 I jxcore-log: 
,07-17 13:39:25.146  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
07-17 13:39:25.146  9623  9687 I jxcore-log: 
,07-17 13:39:25.155  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
07-17 13:39:25.155  9623  9687 I jxcore-log: 
,07-17 13:39:25.188  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
07-17 13:39:25.188  9623  9687 I jxcore-log: 
,07-17 13:39:25.206  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
07-17 13:39:25.206  9623  9687 I jxcore-log: 
,07-17 13:39:25.210  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
07-17 13:39:25.210  9623  9687 I jxcore-log: 
,07-17 13:39:25.254  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
07-17 13:39:25.254  9623  9687 I jxcore-log: 
,07-17 13:39:25.258  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
07-17 13:39:25.258  9623  9687 I jxcore-log: 
,07-17 13:39:25.261  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
07-17 13:39:25.261  9623  9687 I jxcore-log: 
,07-17 13:39:25.264  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
07-17 13:39:25.264  9623  9687 I jxcore-log: 
,07-17 13:39:25.309  3704  3920 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSCM@ADE
07-17 13:39:25.309  3704  3920 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSCM@ADE
,07-17 13:39:25.318  3704  3920 I Telecom : com.android.server.telecom.PhoneAccountRegistrar: SimCallManager queried, returning: null: TSI.gSCM@ADE
,07-17 13:39:25.330 10239 10239 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-17 13:39:25.355 10239 10239 W Babel   : BAM#gBA: invalid account id: -1
,07-17 13:39:25.355 10239 10239 W Babel   : BAM#gBA: invalid account id: -1
07-17 13:39:25.356 10239 10239 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-17 13:39:25.369  3704  9911 I Telecom : TelecomFeature: getContactsPackageName: com.samsung.android.contacts: TSI.gSCM@ADM
,07-17 13:39:25.369  3704  9911 I Telecom : com.android.server.telecom.TelecomServiceImpl$1: getSystemDialerPackage: com.samsung.android.contacts: TSI.gSCM@ADM
,07-17 13:39:25.374  3704  9911 I Telecom : com.android.server.telecom.PhoneAccountRegistrar: SimCallManager queried, returning: null: TSI.gSCM@ADM
,07-17 13:39:25.578  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
07-17 13:39:25.578  9623  9687 I jxcore-log: 
,07-17 13:39:25.584  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
07-17 13:39:25.584  9623  9687 I jxcore-log: 
,07-17 13:39:25.647  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
07-17 13:39:25.647  9623  9687 I jxcore-log: 
,07-17 13:39:25.650  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
07-17 13:39:25.650  9623  9687 I jxcore-log: 
,07-17 13:39:25.668  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
07-17 13:39:25.668  9623  9687 I jxcore-log: 
,07-17 13:39:25.672  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
07-17 13:39:25.672  9623  9687 I jxcore-log: 
,07-17 13:39:25.703  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
07-17 13:39:25.703  9623  9687 I jxcore-log: 
,07-17 13:39:25.743  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
07-17 13:39:25.743  9623  9687 I jxcore-log: 
,07-17 13:39:25.748  3704  4328 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:39:25.749  3704  4328 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4250, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:39:25.749  3704  4328 D BatteryService: online:4, current avg:-95, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:-407
07-17 13:39:25.750  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:39:25.755  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:39:25.756  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:39:25.758  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:39:25.762  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 13:39:25.763  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:39:25.770  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-17 13:39:25.773  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:39:25.774  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:39:25.776  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
07-17 13:39:25.776  9623  9687 I jxcore-log: 
,07-17 13:39:25.789  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-17 13:39:25.790  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:39:25.798  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:39:25.804  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
07-17 13:39:25.804  9623  9687 I jxcore-log: 
,07-17 13:39:25.812  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
07-17 13:39:25.812  9623  9687 I jxcore-log: 
,07-17 13:39:25.858  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
07-17 13:39:25.858  9623  9687 I jxcore-log: 
,07-17 13:39:25.887  9623  9687 I jxcore-log: 2017-07-17 11:39:25 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
07-17 13:39:25.887  9623  9687 I jxcore-log: 
,07-17 13:39:26.267  4528  4528 D io_stats: !@   8,0 r 26181 2310152 w 5635 216576 d 754 74992 f 2270 2270 iot 11950 11174 th 463180 0 0 pt 0 inp 0 0 237.010
,07-17 13:39:26.290  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:26.290  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -44
,07-17 13:39:26.506  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
07-17 13:39:26.506  9623  9687 I jxcore-log: 
,07-17 13:39:26.532  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
07-17 13:39:26.532  9623  9687 I jxcore-log: 
,07-17 13:39:26.537  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
07-17 13:39:26.537  9623  9687 I jxcore-log: 
,07-17 13:39:26.541  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
07-17 13:39:26.541  9623  9687 I jxcore-log: 
,07-17 13:39:26.560  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
07-17 13:39:26.560  9623  9687 I jxcore-log: 
,07-17 13:39:26.578  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
07-17 13:39:26.578  9623  9687 I jxcore-log: 
,07-17 13:39:26.592  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
07-17 13:39:26.592  9623  9687 I jxcore-log: 
,07-17 13:39:26.600  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
07-17 13:39:26.600  9623  9687 I jxcore-log: 
,07-17 13:39:26.608  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
07-17 13:39:26.608  9623  9687 I jxcore-log: 
,07-17 13:39:26.616  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
07-17 13:39:26.616  9623  9687 I jxcore-log: 
,07-17 13:39:26.633  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
07-17 13:39:26.633  9623  9687 I jxcore-log: 
,07-17 13:39:26.646  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
07-17 13:39:26.646  9623  9687 I jxcore-log: 
,07-17 13:39:26.652  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
07-17 13:39:26.652  9623  9687 I jxcore-log: 
,07-17 13:39:26.816  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
07-17 13:39:26.816  9623  9687 I jxcore-log: 
,07-17 13:39:26.891  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
07-17 13:39:26.891  9623  9687 I jxcore-log: 
,07-17 13:39:26.904  9623  9687 D BluetoothAdapter: STATE_ON
,07-17 13:39:26.909  9623  9687 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-17 13:39:26.910  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO testUtils: 'BLE multiple advertisement supported'
07-17 13:39:26.910  9623  9687 I jxcore-log: 
,07-17 13:39:26.911  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - DEBUG UnitTest_app: 'Unit Test app is loaded'
07-17 13:39:26.911  9623  9687 I jxcore-log: 
,07-17 13:39:26.918  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-17 13:39:26.918  9623  9687 I jxcore-log: 
07-17 13:39:26.919  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-17 13:39:26.919  9623  9687 I jxcore-log: 
,07-17 13:39:26.919  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-17 13:39:26.919  9623  9687 I jxcore-log: 
07-17 13:39:26.920  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-17 13:39:26.920  9623  9687 I jxcore-log: 
07-17 13:39:26.920  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-17 13:39:26.920  9623  9687 I jxcore-log: 
07-17 13:39:26.920  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-17 13:39:26.920  9623  9687 I jxcore-log: 
,07-17 13:39:26.920  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-17 13:39:26.920  9623  9687 I jxcore-log: 
07-17 13:39:26.920  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-17 13:39:26.920  9623  9687 I jxcore-log: 
07-17 13:39:26.921  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-17 13:39:26.921  9623  9687 I jxcore-log: 
07-17 13:39:26.921  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-17 13:39:26.921  9623  9687 I jxcore-log: 
07-17 13:39:26.921  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
07-17 13:39:26.921  9623  9687 I jxcore-log: 
07-17 13:39:26.921  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-17 13:39:26.921  9623  9687 I jxcore-log: 
,07-17 13:39:26.921  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
07-17 13:39:26.921  9623  9687 I jxcore-log: 
07-17 13:39:26.922  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
07-17 13:39:26.922  9623  9687 I jxcore-log: 
,07-17 13:39:26.930  9623  9623 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,07-17 13:39:26.930  9623  9623 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,07-17 13:39:26.952  9623  9687 I jxcore-log: 2017-07-17 11:39:26 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
07-17 13:39:26.952  9623  9687 I jxcore-log: 
,07-17 13:39:27.242  9623  9687 I jxcore-log: 2017-07-17 11:39:27 - DEBUG CoordinatedClient: 'connected to the test server'
07-17 13:39:27.242  9623  9687 I jxcore-log: 
,07-17 13:39:28.127  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:39:28.129 10093 10093 I wpa_supplicant: nl80211: Received scan results (18 BSSes)
07-17 13:39:28.130  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:39:28.131  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
,07-17 13:39:28.134  3704  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@20bbec8
,07-17 13:39:28.138  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T133956, SetElapsed=266859, nowELAPSED=238881
,07-17 13:39:28.164  4783  4840 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 5ms lastUpdatedAfter : 4017 ms mFlush_time_threasold : 2000 mCurrentSize : 232
,07-17 13:39:29.316  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:29.317  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:31.006  3704  5557 D SSRM:f  : SIOP:: AP = 320, PST = 290 (W:6), CP = 234, CUR = -87, LCD = 57
,07-17 13:39:31.272  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5674 216940 d 758 75008 f 2272 2272 iot 11960 11184 th 463996 0 0 pt 0 inp 0 0 242.015
,07-17 13:39:32.351  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:32.351  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:35.383  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:35.384  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:36.278  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5677 217032 d 759 75012 f 2274 2274 iot 11960 11187 th 464032 0 0 pt 0 inp 0 0 247.020
,07-17 13:39:38.417  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:38.418  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:40.333  3704  3924 I ActivityManager: KPU : put [com.google.android.apps.photos] : 28360 K
07-17 13:39:40.334  3704  3924 I ActivityManager: Killing 9309:com.google.android.apps.photos/u0a129 (adj 906): DHA:empty #33
,07-17 13:39:40.380  3704  9909 D ActivityManager: cleanUpApplicationRecord -- 9309
07-17 13:39:40.385  4670  4686 D ForegroundUtils: could not check pending caller
,07-17 13:39:41.032  3704  5557 D SSRM:f  : SIOP:: AP = 280, PST = 290 (W:14), CP = 231, CUR = -35, LCD = 57
,07-17 13:39:41.283  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5703 217332 d 762 75024 f 2278 2278 iot 11970 11210 th 468484 0 0 pt 0 inp 0 0 252.025
,07-17 13:39:41.451  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:41.452  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:43.294  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:39:43.295  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 13:39:43.297  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:39:43.297  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:39:44.036  3704  4236 E Watchdog: !@Sync 8 [17_lip_13_39_44.035]
,07-17 13:39:44.495  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:44.495  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:46.288  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5714 217432 d 763 75028 f 2279 2279 iot 11970 11212 th 468520 0 0 pt 0 inp 0 0 257.031
,07-17 13:39:47.528  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:47.528  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:47.557  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-17 13:39:47.557  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-17 13:39:47.557  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({system=1, android.process.acore=1, com.google.android.gms=2})  ]
,07-17 13:39:47.564  4783  4840 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 19400 ms mFlush_time_threasold : 2000 mCurrentSize : 293
,07-17 13:39:49.835  3704  3815 I PowerManagerService: [PWL] On : 0 (260579 ms ago)
07-17 13:39:49.835  3704  3815 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-17 13:39:50.563  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:50.563  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:51.017  3300  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 13:39:51.059  3704  5557 D SSRM:f  : SIOP:: AP = 270, PST = 282 (W:14), CP = 226, CUR = -14, LCD = 57
,07-17 13:39:51.294  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5724 217544 d 764 75032 f 2281 2281 iot 11970 11217 th 468464 0 0 pt 0 inp 0 0 262.036
,07-17 13:39:52.241  3300  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 13:39:52.916  3704  4019 D WifiWatchdogStateMachine:  [|217] []
,07-17 13:39:53.586  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:53.587  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:55.801  3704  3924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:39:55.802  3704  3924 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:39:55.803  3704  3924 D BatteryService: online:4, current avg:-9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
,07-17 13:39:55.803  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:39:55.814  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:39:55.815  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:39:55.821  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:39:55.825  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 13:39:55.826  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:39:55.838  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-17 13:39:55.845  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:39:55.846  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:39:55.861  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-17 13:39:55.861  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:39:55.864  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:39:56.115  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:39:56.115  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755696, nowELAPSED=266859
07-17 13:39:56.116  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@1c3836b alarm=Alarm{f0dfc3f type 2 when 266859 android}
,07-17 13:39:56.117  3704  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 64000: mInRange : true
,07-17 13:39:56.119 10093 10093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-17 13:39:56.119 10093 10093 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-17 13:39:56.120  3704  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T134100 - CU:1000/CP:3704
07-17 13:39:56.120  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134100, SetElapsed=330862, nowELAPSED=266864
07-17 13:39:56.122 10093 10093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-17 13:39:56.123  3704  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T134011 - CU:1000/CP:3704
07-17 13:39:56.123  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134011, SetElapsed=281864, nowELAPSED=266867
,07-17 13:39:56.299  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5726 217588 d 765 75036 f 2283 2283 iot 11970 11219 th 470244 0 0 pt 0 inp 0 0 267.042
,07-17 13:39:56.613  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:56.613  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:39:59.634  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:39:59.634  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:00.000  3704  3866 D SamsungAlarmManager: Expired : 8
,07-17 13:40:00.001  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{be8c46a type 3 when 270744 android}
,07-17 13:40:00.011  3704  3704 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170717T134100 - CU:1000/CP:3704
,07-17 13:40:00.016  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-17 13:40:00.017  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-17 13:40:00.017  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-17 13:40:00.038  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-17 13:40:00.039  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-17 13:40:00.043  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-17 13:40:00.057  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:40:00.059  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:40:00.063  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:40:00.065  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:40:00.091  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:40:00.093  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:40:00.095  4070  4070 V hong    : mid yDiff = 438
07-17 13:40:00.095  4070  4070 V hong    : mid yDiff = 438
,07-17 13:40:00.097  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-17 13:40:00.097  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-17 13:40:00.103  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-17 13:40:00.108  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-17 13:40:00.121  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:40:00.124  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:40:00.125  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:40:00.126 10093 10093 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
07-17 13:40:00.130  3704  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@8347255
07-17 13:40:00.130  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
,07-17 13:40:00.130  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:40:00.131  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134100, SetElapsed=330862, nowELAPSED=270875
07-17 13:40:00.131  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170717T134100, SetElapsed=330744, nowELAPSED=270875
,07-17 13:40:00.140  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 13:40:00.141  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:40:00.146  5265  5265 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
07-17 13:40:00.148  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
07-17 13:40:00.152  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
07-17 13:40:00.157  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
07-17 13:40:00.158  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-17 13:40:00.159  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-17 13:40:00.160  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-17 13:40:00.161  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
07-17 13:40:00.165  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-17 13:40:00.168  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB548169489A7ED530437295274FE5269A22009025F95C89ED195E9C4F8C4C541DAD222303C71F4897E6BDF3BDBA9AC55]}
07-17 13:40:00.169  5265  5265 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-17 13:40:01.083  3704  5557 D SSRM:f  : SIOP:: AP = 260, PST = 281 (W:14), CP = 223, CUR = -5, LCD = 57
,07-17 13:40:01.305  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5732 217620 d 765 75036 f 2283 2283 iot 11970 11220 th 469964 0 0 pt 0 inp 0 0 272.047
,07-17 13:40:02.665  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:02.665  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:05.700  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:05.700  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:06.310  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5733 217632 d 765 75036 f 2284 2284 iot 11970 11221 th 470092 0 0 pt 0 inp 0 0 277.052
,07-17 13:40:08.732  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:08.732  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:11.110  3704  5557 D SSRM:f  : SIOP:: AP = 260, PST = 280 (W:14), CP = 220, CUR = -2, LCD = 57
,07-17 13:40:11.764  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:11.764  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:13.299  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:40:13.300  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-17 13:40:13.302  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:40:13.302  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:40:14.037  3704  4236 E Watchdog: !@Sync 9 [17_lip_13_40_14.037]
,07-17 13:40:14.786  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:14.787  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:17.819  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:17.819  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:20.852  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:20.853  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:21.141  3704  5557 D SSRM:f  : SIOP:: AP = 260, PST = 277 (W:14), CP = 219, LCD = 57
,07-17 13:40:23.875  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:23.875  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:25.863  3704  4740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:40:25.864  3704  4740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:40:25.864  3704  4740 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-17 13:40:25.864  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:40:25.875  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:40:25.875  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:40:25.880  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:40:25.884  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 13:40:25.885  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:40:25.896  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
07-17 13:40:25.905  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:40:25.907  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-17 13:40:25.908  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:40:25.909  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:40:25.912  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:40:26.330  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5735 217640 d 765 75036 f 2285 2285 iot 11970 11222 th 469964 0 0 pt 0 inp 0 0 297.072
,07-17 13:40:26.908  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:26.908  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:29.934  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:29.935  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:31.169  3704  5557 D SSRM:f  : SIOP:: AP = 260, PST = 273 (W:14), CP = 218, LCD = 57
,07-17 13:40:31.308  3704  3714 I art     : Background sticky concurrent mark sweep GC freed 218268(11MB) AllocSpace objects, 86(1720KB) LOS objects, 26% free, 41MB/56MB, paused 3.785ms total 145.036ms
,07-17 13:40:32.297  3300  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 13:40:32.969  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:32.969  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:35.998  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:35.998  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:36.059  3300  3768 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,07-17 13:40:36.340  4528  4528 D io_stats: !@   8,0 r 26185 2310424 w 5737 217656 d 765 75036 f 2286 2286 iot 11970 11223 th 471100 0 0 pt 0 inp 0 0 307.082
,07-17 13:40:39.031  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:39.031  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:41.197  3704  5557 D SSRM:f  : SIOP:: AP = 260, PST = 272 (W:14), CP = 217, LCD = 57
,07-17 13:40:42.064  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:42.064  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:43.303  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:40:43.305  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 13:40:43.306  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:40:43.307  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:40:43.978  3704  3880 I TLC_TIMA_PKM_initialize: initializing...
,07-17 13:40:43.978  3704  3880 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
07-17 13:40:43.978  3704  3880 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
07-17 13:40:43.978  3704  3880 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
07-17 13:40:43.978  3704  3880 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
07-17 13:40:43.978  3704  3880 I TZ: mc_tlc_communication: root = 0, root_len = 1
07-17 13:40:43.979  3704  3880 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
07-17 13:40:43.979  3704  3880 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
07-17 13:40:43.979  3704  3880 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
07-17 13:40:43.979  3704  3880 I TZ: mc_tlc_communication: device_id = 0x0
07-17 13:40:43.979  3704  3880 I TZ: mc_tlc_communication: tlc_open() was called
07-17 13:40:43.979  3704  3880 I TZ: mc_tlc_communication: Opening MobiCore device
07-17 13:40:43.979  3704  3880 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,07-17 13:40:43.981  3704  3880 I TZ: mc_tlc_communication: Opening the session
,07-17 13:40:44.034  3704  3880 I TZ: mc_tlc_communication: tlc_open() succeeded
07-17 13:40:44.034  3704  3880 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,07-17 13:40:44.039  3704  4236 E Watchdog: !@Sync 10 [17_lip_13_40_44.038]
,07-17 13:40:44.070  3704  3880 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,07-17 13:40:44.076  3704  3880 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,07-17 13:40:44.081  3704  3880 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,07-17 13:40:44.085  3704  3880 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-17 13:40:44.836  3704  3815 I PowerManagerService: [PWL] On : 0 (315579 ms ago)
07-17 13:40:44.836  3704  3815 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-17 13:40:45.096  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:45.096  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:46.350  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5737 217656 d 765 75036 f 2286 2286 iot 11990 11228 th 470888 0 0 pt 0 inp 0 0 317.092
,07-17 13:40:47.062  3704  3920 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170717T183338 - CU:10007/CP:4677
,07-17 13:40:47.606  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-17 13:40:47.606  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-17 13:40:47.606  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-17 13:40:47.624  4783  4840 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 10ms lastUpdatedAfter : 60059 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-17 13:40:48.117  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:48.117  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:48.164  3704  3880 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-17 13:40:48.164  3704  3880 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-17 13:40:51.140  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:51.140  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:51.225  3704  5557 D SSRM:f  : SIOP:: AP = 260, PST = 270 (W:14), CP = 216, LCD = 57
,07-17 13:40:51.355  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5741 217748 d 766 75040 f 2288 2288 iot 12000 11231 th 470852 0 0 pt 0 inp 0 0 322.097
,07-17 13:40:54.174  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:54.174  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:40:55.913  3704  9910 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:40:56.361  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5746 217804 d 767 75044 f 2290 2290 iot 12000 11233 th 470860 0 0 pt 0 inp 0 0 327.103
,07-17 13:40:57.167  3704  4019 D WifiWatchdogStateMachine:  [|213] []
,07-17 13:40:57.194  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:40:57.194  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:00.000  3704  3866 D SamsungAlarmManager: Expired : 8
,07-17 13:41:00.001  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{b5e2da4 type 3 when 330744 android}
,07-17 13:41:00.010  3704  3704 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170717T134200 - CU:1000/CP:3704
,07-17 13:41:00.014  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-17 13:41:00.015  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-17 13:41:00.015  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-17 13:41:00.046  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
07-17 13:41:00.047  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,07-17 13:41:00.050  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-17 13:41:00.064  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:41:00.067  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:41:00.070  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 13:41:00.073  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:41:00.096  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:41:00.098  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 13:41:00.100  4070  4070 V hong    : mid yDiff = 438
,07-17 13:41:00.100  4070  4070 V hong    : mid yDiff = 438
07-17 13:41:00.102  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-17 13:41:00.103  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-17 13:41:00.109  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-17 13:41:00.112  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-17 13:41:00.118  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:41:00.118  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755696, nowELAPSED=330862
07-17 13:41:00.119  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170717T134200, SetElapsed=390744, nowELAPSED=330862
07-17 13:41:00.119  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@389c90c alarm=Alarm{9d9970d type 2 when 330862 android}
,07-17 13:41:00.121  3704  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-17 13:41:00.123 10093 10093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-17 13:41:00.123 10093 10093 I wpa_supplicant: P2P: Current p2p state = IDLE
07-17 13:41:00.128  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 13:41:00.130  3704  3931 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T134308 - CU:1000/CP:3704
07-17 13:41:00.131  3704  3931 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134308, SetElapsed=458865, nowELAPSED=330875
07-17 13:41:00.131  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
07-17 13:41:00.136 10093 10093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-17 13:41:00.137  3704  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T134115 - CU:1000/CP:3704
07-17 13:41:00.138  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134115, SetElapsed=345873, nowELAPSED=330882
,07-17 13:41:00.150  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 13:41:00.151  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:41:00.158  5265  5265 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-17 13:41:00.162  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-17 13:41:00.168  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-17 13:41:00.173  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-17 13:41:00.174  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-17 13:41:00.175  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-17 13:41:00.176  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-17 13:41:00.177  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-17 13:41:00.181  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-17 13:41:00.183  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB548169489A7ED530437295274FE52694F88825E005E58794B8B3707992624B259A179650BDEA5347A0CFA7D395CE35B]}
,07-17 13:41:00.183  5265  5265 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-17 13:41:00.205  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:00.205  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:01.254  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 268 (W:14), CP = 215, LCD = 57
,07-17 13:41:01.366  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5753 217848 d 767 75044 f 2291 2291 iot 12000 11235 th 470916 0 0 pt 0 inp 0 0 332.108
,07-17 13:41:03.236  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:03.236  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 13:41:04.124  3300  3769 D Netd    : Iface wlan0 link up
,07-17 13:41:04.125 10093 10093 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
,07-17 13:41:04.129  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
,07-17 13:41:04.129  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
07-17 13:41:04.131  3704  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@332dcd3
,07-17 13:41:04.134  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134308, SetElapsed=458865, nowELAPSED=334878
,07-17 13:41:06.269  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:06.270  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 13:41:09.303  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:09.303  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 13:41:10.895  8631  8661 I PlayCommon: [744] com.google.android.play.a.g.e(932): Preparing logs for uploading
,07-17 13:41:10.902  8631  8661 W PlayCommon: [744] com.google.android.play.a.g.a(1239): No account for auth token provided
,07-17 13:41:10.903  8631  8661 I PlayCommon: [744] com.google.android.play.a.g.a(1035): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,07-17 13:41:10.909  8631  8661 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:41:10.910  8631  8661 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-17 13:41:10.914  3300  3772 D EnterpriseController: netId is 0
,07-17 13:41:10.915  3300  3772 D Netd    : getNetworkForDns: using netid 503 for uid 10032
07-17 13:41:10.915  3300  3772 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,07-17 13:41:11.283  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 266 (W:14), CP = 215, LCD = 57
,07-17 13:41:11.356  8631  8661 I PlayCommon: [744] com.google.android.play.a.g.a(1113): Successfully uploaded logs.
,07-17 13:41:12.329  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:12.330  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:13.308  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:41:13.309  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 13:41:13.311  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:41:13.311  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:41:14.040  3704  4236 E Watchdog: !@Sync 11 [17_lip_13_41_14.040]
,07-17 13:41:15.364  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:15.365  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:18.390  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:18.390  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:21.313  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 264 (W:14), CP = 214, LCD = 57
,07-17 13:41:21.386  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5756 217908 d 769 75052 f 2292 2292 iot 12000 11237 th 470876 0 0 pt 0 inp 0 0 352.128
,07-17 13:41:21.422  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:21.422  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:24.457  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:24.457  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:25.965  3704  3760 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-17 13:41:25.967  3704  3760 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:41:25.967  3704  3760 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
,07-17 13:41:25.967  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:41:25.979  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:41:25.979  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:41:25.983  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:41:25.988  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 13:41:25.988  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:41:25.998  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
07-17 13:41:26.003  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:41:26.004  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:41:26.012  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-17 13:41:26.013  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:41:26.026  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:41:26.391  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5765 217964 d 769 75052 f 2294 2294 iot 12000 11239 th 470872 0 0 pt 0 inp 0 0 357.134
,07-17 13:41:27.485  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:27.485  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:30.519  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:30.519  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:31.340  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 262 (W:14), CP = 214, LCD = 57
,07-17 13:41:31.397  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5769 217988 d 769 75052 f 2295 2295 iot 12000 11240 th 470872 0 0 pt 0 inp 0 0 362.139
,07-17 13:41:33.548  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:33.549  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:35.515  9623  9687 I jxcore-log: 2017-07-17 11:41:35 - DEBUG CoordinatedClient: 'device disconnected from the test server'
07-17 13:41:35.515  9623  9687 I jxcore-log: 
,07-17 13:41:36.402  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5770 217992 d 769 75052 f 2295 2295 iot 12000 11241 th 470860 0 0 pt 0 inp 0 0 367.144
,07-17 13:41:36.583  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:36.583  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:36.679  9623  9687 I jxcore-log: 2017-07-17 11:41:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:41:36.679  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:41:36.679  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:41:36.679  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:41:36.679  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:41:36.679  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:41:36.679  9623  9687 I jxcore-log: 
,07-17 13:41:36.683  9623  9687 I jxcore-log: 2017-07-17 11:41:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:41:36.683  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:41:36.683  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:41:36.683  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:41:36.683  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:41:36.683  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:41:36.683  9623  9687 I jxcore-log: 
,07-17 13:41:37.333  3704  4022 D WifiWatchdogStateMachine:  [|216]
,07-17 13:41:37.537  3704  4021 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
,07-17 13:41:37.538  3704  4021 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
,07-17 13:41:39.615  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:39.615  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:41.064  9623  9687 I jxcore-log: 2017-07-17 11:41:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:41:41.064  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:41:41.064  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:41:41.064  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:41:41.064  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:41:41.064  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:41:41.064  9623  9687 I jxcore-log: 
,07-17 13:41:41.068  9623  9687 I jxcore-log: 2017-07-17 11:41:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:41:41.068  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:41:41.068  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:41:41.068  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:41:41.068  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:41:41.068  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:41:41.068  9623  9687 I jxcore-log: 
,07-17 13:41:41.370  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 260 (W:14), CP = 213, LCD = 57
,07-17 13:41:42.640  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:42.641  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:43.312  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:41:43.313  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-17 13:41:43.315  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
,07-17 13:41:43.315  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:41:43.475 10093 10093 I wpa_supplicant: WPA: Group rekeying completed with F4.E6.C2 [GTK=CCMP]
,07-17 13:41:43.480  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 13:41:43.489 10093 10093 I wpa_supplicant: WPA: Group rekeying completed with F4.E6.C2 [GTK=CCMP]
,07-17 13:41:43.499  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 13:41:43.500  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:41:43.504  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 13:41:43.509  3704  3931 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,07-17 13:41:43.513  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:41:43.520  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:41:43.525  9623  9623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-17 13:41:43.575 10093 10093 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-17 13:41:43.590 10093 10093 I wpa_supplicant: Interworking: Fetch ANQP after connect
,07-17 13:41:44.042  3704  4236 E Watchdog: !@Sync 12 [17_lip_13_41_44.041]
,07-17 13:41:44.855  3704  3815 I PowerManagerService: [PWL] On : 0 (375599 ms ago)
07-17 13:41:44.855  3704  3815 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-17 13:41:45.673  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:45.674  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:47.724  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-17 13:41:47.724  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-17 13:41:47.724  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-17 13:41:47.735  4783  4840 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 7ms lastUpdatedAfter : 60111 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-17 13:41:48.702  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:48.702  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:48.784  9623  9687 I jxcore-log: 2017-07-17 11:41:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:41:48.784  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:41:48.784  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:41:48.784  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:41:48.784  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:41:48.784  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:41:48.784  9623  9687 I jxcore-log: 
,07-17 13:41:48.788  9623  9687 I jxcore-log: 2017-07-17 11:41:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:41:48.788  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:41:48.788  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:41:48.788  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:41:48.788  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:41:48.788  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:41:48.788  9623  9687 I jxcore-log: 
,07-17 13:41:51.399  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 257 (W:14), CP = 213, LCD = 57
,07-17 13:41:51.416  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5774 218084 d 770 75056 f 2297 2297 iot 12000 11243 th 470828 0 0 pt 0 inp 0 0 382.158
,07-17 13:41:51.735  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-17 13:41:51.735  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:54.768  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:54.768  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:56.015  3704  9910 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:41:56.016  3704  9910 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 243, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:41:56.016  3704  9910 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-17 13:41:56.017  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:41:56.028  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:41:56.028  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:41:56.032  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:41:56.037  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-17 13:41:56.038  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:41:56.050  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
07-17 13:41:56.053  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:41:56.054  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:41:56.072  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:41:56.078  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-17 13:41:56.079  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:41:56.421  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5779 218140 d 771 75060 f 2299 2299 iot 12000 11246 th 470904 0 0 pt 0 inp 0 0 387.163
,07-17 13:41:57.405  3704  4019 D WifiWatchdogStateMachine:  [|215] []
,07-17 13:41:57.795  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:41:57.795  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:41:58.813  9623  9687 I jxcore-log: 2017-07-17 11:41:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:41:58.813  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:41:58.813  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:41:58.813  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:41:58.813  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:41:58.813  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:41:58.813  9623  9687 I jxcore-log: 
,07-17 13:41:58.816  9623  9687 I jxcore-log: 2017-07-17 11:41:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:41:58.816  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:41:58.816  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:41:58.816  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:41:58.816  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:41:58.816  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:41:58.816  9623  9687 I jxcore-log: 
,07-17 13:42:00.000  3704  3866 D SamsungAlarmManager: Expired : 8
,07-17 13:42:00.001  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{f44732f type 3 when 390744 android}
,07-17 13:42:00.012  3704  3704 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170717T134300 - CU:1000/CP:3704
07-17 13:42:00.012  3704  3704 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170717T134300, SetElapsed=450744, nowELAPSED=390756
,07-17 13:42:00.017  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-17 13:42:00.018  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-17 13:42:00.018  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-17 13:42:00.037  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-17 13:42:00.045  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
07-17 13:42:00.048  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-17 13:42:00.057  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:42:00.059  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:42:00.064  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:42:00.069  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:42:00.081  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:42:00.083  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:42:00.087  4070  4070 V hong    : mid yDiff = 438
,07-17 13:42:00.087  4070  4070 V hong    : mid yDiff = 438
07-17 13:42:00.088  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-17 13:42:00.088  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-17 13:42:00.093  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-17 13:42:00.096  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-17 13:42:00.110  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:42:00.112  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:42:00.127  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:42:00.129  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:42:00.134  5265  5265 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-17 13:42:00.136  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-17 13:42:00.139  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-17 13:42:00.145  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,07-17 13:42:00.146  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-17 13:42:00.148  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,07-17 13:42:00.149  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,07-17 13:42:00.150  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-17 13:42:00.155  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,07-17 13:42:00.157  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB548169489A7ED530437295274FE526956F41253B3D93311A44BA3B70309D2249FA810AB00AC8D11EEC5EF36A9ABD4F9]}
07-17 13:42:00.158  5265  5265 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-17 13:42:00.829  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:00.830  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:01.426  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5786 218184 d 771 75060 f 2300 2300 iot 12000 11248 th 470848 0 0 pt 0 inp 0 0 392.168
07-17 13:42:01.428  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 255 (W:14), CP = 212, LCD = 57
,07-17 13:42:03.859  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:03.859  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:06.893  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:06.893  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:08.848  9623  9687 I jxcore-log: 2017-07-17 11:42:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:08.848  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:08.848  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:08.848  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:08.848  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:08.848  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:08.848  9623  9687 I jxcore-log: 
,07-17 13:42:08.852  9623  9687 I jxcore-log: 2017-07-17 11:42:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:08.852  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:08.852  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:08.852  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:08.852  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:08.852  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:08.852  9623  9687 I jxcore-log: 
,07-17 13:42:09.925  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:09.925  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:11.457  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 254 (W:14), CP = 212, LCD = 57
,07-17 13:42:12.451  9487  9515 V NativeCrypto: SSL shutdown failed: ssl=0x7d2d82fb80: I/O error during system call, Software caused connection abort
,07-17 13:42:12.951  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:12.951  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:13.316  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:42:13.317  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 13:42:13.319  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:42:13.319  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:42:14.044  3704  4236 E Watchdog: !@Sync 13 [17_lip_13_42_14.043]
,07-17 13:42:15.982  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:15.982  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:18.898  9623  9687 I jxcore-log: 2017-07-17 11:42:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:18.898  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:18.898  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:18.898  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:18.898  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:18.898  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:18.898  9623  9687 I jxcore-log: 
,07-17 13:42:18.901  9623  9687 I jxcore-log: 2017-07-17 11:42:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:18.901  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:18.901  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:18.901  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:18.901  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:18.901  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:18.901  9623  9687 I jxcore-log: 
,07-17 13:42:19.005  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:19.005  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:21.491  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 253 (W:14), CP = 211, LCD = 57
,07-17 13:42:22.039  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:22.039  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:25.071  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:25.071  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:26.063  3704  4753 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:42:28.099  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:28.099  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:28.929  9623  9687 I jxcore-log: 2017-07-17 11:42:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:28.929  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:28.929  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:28.929  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:28.929  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:28.929  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:28.929  9623  9687 I jxcore-log: 
,07-17 13:42:28.935  9623  9687 I jxcore-log: 2017-07-17 11:42:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:28.935  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:28.935  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:28.935  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:28.935  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:28.935  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:28.935  9623  9687 I jxcore-log: 
,07-17 13:42:31.134  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:31.134  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:31.456  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5789 218204 d 771 75060 f 2302 2302 iot 12000 11249 th 470800 0 0 pt 0 inp 0 0 422.198
,07-17 13:42:31.521  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 252 (W:14), CP = 211, LCD = 57
,07-17 13:42:34.158  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:34.159  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:36.462  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5790 218208 d 771 75060 f 2302 2302 iot 12000 11250 th 470804 0 0 pt 0 inp 0 0 427.204
,07-17 13:42:37.192  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:37.192  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:38.962  9623  9687 I jxcore-log: 2017-07-17 11:42:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:38.962  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:38.962  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:38.962  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:38.962  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:38.962  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:38.962  9623  9687 I jxcore-log: 
,07-17 13:42:38.965  9623  9687 I jxcore-log: 2017-07-17 11:42:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:38.965  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:38.965  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:38.965  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:38.965  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:38.965  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:38.965  9623  9687 I jxcore-log: 
,07-17 13:42:40.224  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:40.224  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:41.551  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 252 (W:14), CP = 210, LCD = 57
,07-17 13:42:43.258  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:43.258  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:43.320  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:42:43.321  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
07-17 13:42:43.323  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:42:43.323  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:42:44.045  3704  4236 E Watchdog: !@Sync 14 [17_lip_13_42_44.045]
,07-17 13:42:46.290  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:46.290  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:42:47.746  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
07-17 13:42:47.746  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
07-17 13:42:47.746  4783  4840 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,07-17 13:42:47.753  4783  4840 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60018 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,07-17 13:42:49.004  9623  9687 I jxcore-log: 2017-07-17 11:42:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:49.004  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:49.004  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:49.004  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:49.004  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:49.004  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:49.004  9623  9687 I jxcore-log: 
,07-17 13:42:49.008  9623  9687 I jxcore-log: 2017-07-17 11:42:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:49.008  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:49.008  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:49.008  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:49.008  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:49.008  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:49.008  9623  9687 I jxcore-log: 
,07-17 13:42:49.313  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:49.313  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 13:42:49.905  3704  3815 I PowerManagerService: [PWL] On : 0 (440649 ms ago)
07-17 13:42:49.905  3704  3815 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,07-17 13:42:51.477  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5794 218296 d 772 75064 f 2304 2304 iot 12010 11254 th 470740 0 0 pt 0 inp 0 0 442.219
,07-17 13:42:51.580  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 251 (W:14), CP = 210, LCD = 57
,07-17 13:42:52.345  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:52.345  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 13:42:55.379  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:55.380  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 13:42:56.123  3704  9911 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-17 13:42:56.124  3704  9911 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 242, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
07-17 13:42:56.124  3704  9911 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
07-17 13:42:56.124  3704  3704 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-17 13:42:56.134  3704  3704 V UiModeManager: updateLocked: null action, mDockState=0, category=null
07-17 13:42:56.134  3704  3704 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,07-17 13:42:56.138  3704  3704 D GameManagerService: new battery level: 100
,07-17 13:42:56.143  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-17 13:42:56.144  4070  4070 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-17 13:42:56.154  4070  4070 D PowerUI : priorPlugType = 2 mPlugType =  2
,07-17 13:42:56.165  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
07-17 13:42:56.167  4070  4070 D BatteryMeterDrawable: isSomethingChanged - false
,07-17 13:42:56.174  9764  9764 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-17 13:42:56.175  9764  9822 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-17 13:42:56.192  4070  4070 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,07-17 13:42:56.482  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5798 218348 d 773 75068 f 2306 2306 iot 12010 11256 th 470744 0 0 pt 0 inp 0 0 447.224
,07-17 13:42:58.411  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:42:58.411  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 13:42:59.080  9623  9687 I jxcore-log: 2017-07-17 11:42:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:59.080  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:59.080  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:59.080  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:59.080  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:59.080  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:59.080  9623  9687 I jxcore-log: 
,07-17 13:42:59.087  9623  9687 I jxcore-log: 2017-07-17 11:42:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:42:59.087  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:42:59.087  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:42:59.087  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:42:59.087  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:42:59.087  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:42:59.087  9623  9687 I jxcore-log: 
,07-17 13:42:59.642  3704  4019 D WifiWatchdogStateMachine:  [|211] []
,07-17 13:43:00.000  3704  3866 D SamsungAlarmManager: Expired : 8
,07-17 13:43:00.002  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{42f134b type 3 when 450744 android}
,07-17 13:43:00.011  3704  3704 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20170717T134400 - CU:1000/CP:3704
,07-17 13:43:00.016  4070  4070 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-17 13:43:00.017  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#start
07-17 13:43:00.017  4070  4070 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,07-17 13:43:00.037  4070  4070 D KeyguardUpdateMonitor: handleTimeUpdate#end
,07-17 13:43:00.037  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
07-17 13:43:00.039  4070  4070 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,07-17 13:43:00.051  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:43:00.053  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:43:00.056  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 13:43:00.059  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:43:00.072  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
07-17 13:43:00.073  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:43:00.074  4070  4070 V hong    : mid yDiff = 438
07-17 13:43:00.076  4070  4070 V hong    : mid yDiff = 438
07-17 13:43:00.076  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
07-17 13:43:00.077  4070  4070 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,07-17 13:43:00.081  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,07-17 13:43:00.085  4070  4070 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,07-17 13:43:00.097  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:43:00.099  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:43:00.114  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : start
,07-17 13:43:00.116  4070  4070 D TextClock: TextClock received ACTION_TIME_TICK : end
,07-17 13:43:00.120  5265  5265 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,07-17 13:43:00.122  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,07-17 13:43:00.125  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,07-17 13:43:00.129  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
07-17 13:43:00.130  5265  5265 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,07-17 13:43:00.130  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
07-17 13:43:00.131  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
07-17 13:43:00.131  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,07-17 13:43:00.134  5265  5265 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
07-17 13:43:00.135  5265  5265 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB548169489A7ED530437295274FE5269E997E6028E91BD34D306708A771A1CAA2A0DE1C530542A00B5E338108B5B1932]}
,07-17 13:43:00.135  5265  5265 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,07-17 13:43:01.445  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,07-17 13:43:01.445  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:43:01.488  4528  4528 D io_stats: !@   8,0 r 26195 2311384 w 5805 218392 d 773 75068 f 2307 2307 iot 12010 11258 th 470620 0 0 pt 0 inp 0 0 452.230
,07-17 13:43:01.608  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 210, LCD = 57
,07-17 13:43:04.471  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:43:04.471  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:43:07.505  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:43:07.505  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:43:08.121  3704  3866 D SamsungAlarmManager: Expired : 4
,07-17 13:43:08.125  3704  3866 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170717T141152 - CU:1000/CP:3704
,07-17 13:43:08.126  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755696, nowELAPSED=458870
07-17 13:43:08.127  3704  3866 I SamsungAlarmManager: setLocked to kernel - T:3 / 20170717T134400, SetElapsed=510744, nowELAPSED=458871
,07-17 13:43:08.132  3704  3866 V SamsungAlarmManager: Sending to uid : 10019 action=null alarm=Alarm{6ee4128 type 0 when 1500291712440 com.google.android.gms}
,07-17 13:43:08.136  3704  3866 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@eb976c2 alarm=Alarm{83c1e41 type 2 when 458865 android}
,07-17 13:43:08.140  3704  3931 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,07-17 13:43:08.143 10093 10093 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-17 13:43:08.144 10093 10093 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-17 13:43:08.156  3704  3961 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20170717T134323 - CU:1000/CP:3704
,07-17 13:43:08.157  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134323, SetElapsed=473889, nowELAPSED=458900
,07-17 13:43:08.159 10093 10093 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-17 13:43:08.228  4989 10366 I EventLogChimeraService: Aggregate from 1500289912019 (log), 1500289912019 (data)
,07-17 13:43:08.386  3704  3911 D MountService: getExternalStorageMountMode : 1
07-17 13:43:08.386  3704  3911 D MountService: getExternalStorageMountMode : 3
,07-17 13:43:08.386  3704  3911 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.lool
,07-17 13:43:08.408 10369 10369 E Zygote  : v2
07-17 13:43:08.409 10369 10369 I libpersona: KNOX_SDCARD checking this for 1000
07-17 13:43:08.409 10369 10369 I libpersona: KNOX_SDCARD not a persona
,07-17 13:43:08.410 10369 10369 E Zygote  : accessInfo : 0
07-17 13:43:08.410  3704  3911 I ActivityManager: Start proc 10369:com.samsung.android.lool/1000 for broadcast com.samsung.android.lool/com.samsung.android.sm.common.SmartManagerReceiver
,07-17 13:43:08.421 10369 10369 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,07-17 13:43:08.423 10369 10369 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.lool 
,07-17 13:43:08.454 10369 10369 D TimaKeyStoreProvider: TimaSignature is unavailable
07-17 13:43:08.454 10369 10369 D ActivityThread: Added TimaKeyStore provider
,07-17 13:43:08.455  3704  4752 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20170717T141308 - CU:10019/CP:4989
,07-17 13:43:08.456  3704  3920 I ActivityManager: DSS on for com.samsung.android.lool and scale is 1.0
,07-17 13:43:08.497 10369 10369 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,07-17 13:43:08.579 10369 10369 D SamsungAnalytics:1.8.22: cf feature is supported
,07-17 13:43:08.587 10369 10369 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
,07-17 13:43:09.185  9623  9687 I jxcore-log: 2017-07-17 11:43:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:43:09.185  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:43:09.185  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:43:09.185  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:43:09.185  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:43:09.185  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:43:09.185  9623  9687 I jxcore-log: 
,07-17 13:43:09.192  9623  9687 I jxcore-log: 2017-07-17 11:43:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:43:09.192  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:43:09.192  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:43:09.192  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:43:09.192  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:43:09.192  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:43:09.192  9623  9687 I jxcore-log: 
,07-17 13:43:10.536  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:43:10.537  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:43:11.498  4528  4528 D io_stats: !@   8,0 r 26200 2311672 w 5812 218564 d 774 75072 f 2311 2311 iot 12010 11264 th 468668 0 0 pt 0 inp 0 0 462.240
,07-17 13:43:11.640  3704  5557 D SSRM:f  : SIOP:: AP = 250, PST = 250 (W:14), CP = 210, LCD = 57
,07-17 13:43:12.197  3300  3769 D Netd    : Iface wlan0 link up
07-17 13:43:12.200 10093 10093 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
07-17 13:43:12.201  3704  3811 D Tethering: interfaceLinkStateChanged wlan0, true
07-17 13:43:12.201  3704  3811 D Tethering: interfaceStatusChanged wlan0, true
,07-17 13:43:12.206  3704  3961 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3704 / listener:android.app.AlarmManager$ListenerWrapper@a16dfe6
,07-17 13:43:12.210  3704  3961 I SamsungAlarmManager: setLocked to kernel - T:2 / 20170717T134804, SetElapsed=755696, nowELAPSED=462953
,07-17 13:43:13.324  3704  3704 D UsbMonitorService: readUsbState++
,07-17 13:43:13.325  3704  3704 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,07-17 13:43:13.327  3704  3704 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
07-17 13:43:13.328  3704  3704 D UsbMonitorService: Posting Message again
,07-17 13:43:13.491  4989 10368 W PlatformStatsUtil: Could not retrieve Usage & Diagnostics setting. Giving up.
,07-17 13:43:13.562  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:43:13.562  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -45
,07-17 13:43:14.047  3704  4236 E Watchdog: !@Sync 15 [17_lip_13_43_14.046]
,07-17 13:43:16.504  4528  4528 D io_stats: !@   8,0 r 26200 2311672 w 5823 218696 d 776 75112 f 2312 2312 iot 12010 11268 th 468592 0 0 pt 0 inp 0 0 467.246
,07-17 13:43:16.595  3704  3931 D WifiStateMachine: Current network is: "NG700" , ID is: 4
07-17 13:43:16.595  3704  3931 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -46
,07-17 13:43:18.569  4989 10368 W PlatformStatsUtil: Could not retrieve Usage & Diagnostics setting. Giving up.
,07-17 13:43:19.248  9623  9687 I jxcore-log: 2017-07-17 11:43:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:43:19.248  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:43:19.248  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:43:19.248  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:43:19.248  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:43:19.248  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:43:19.248  9623  9687 I jxcore-log: 
,07-17 13:43:19.253  9623  9687 I jxcore-log: 2017-07-17 11:43:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
07-17 13:43:19.253  9623  9687 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
07-17 13:43:19.253  9623  9687 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
07-17 13:43:19.253  9623  9687 I jxcore-log: emit@events.js:82:1
07-17 13:43:19.253  9623  9687 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
07-17 13:43:19.253  9623  9687 I jxcore-log: emit@events.js:82:1''
07-17 13:43:19.253  9623  9687 I jxcore-log: 

```
