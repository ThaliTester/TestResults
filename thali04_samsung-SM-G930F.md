#### Test 1459176191a53731_thali04_samsung-SM-G930F Logs


```
--------- beginning of system
,10-12 16:08:45.897  3703  4845 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
--------- beginning of main
10-12 16:08:45.946  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:08:45.947  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
10-12 16:08:46.411  9829  9829 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 9829 | app_process
10-12 16:08:46.411  9829  9829 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
10-12 16:08:46.417  9829  9829 E appproc : Enhanced Zygote ASLR: ro.knox.enhance.zygote.aslr != 1. Enhanced Zygote ASLR is DISABLED!
10-12 16:08:46.417  9829  9829 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-12 16:08:46.419  9829  9829 D AndroidRuntime: CheckJNI is OFF
10-12 16:08:46.419  9829  9829 D AndroidRuntime: addProductProperty: start
10-12 16:08:46.457  9829  9829 I [saiv 1.1]: saiv_OnLoadJNI.cpp(38): _init: Version 1.1 Build # 3532
10-12 16:08:46.457  9829  9829 I [saiv 1.1]: saiv_OnLoadJNI.cpp(43): _init: _init() was called
10-12 16:08:46.473  9829  9829 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
10-12 16:08:46.473  9829  9829 I MLDAP   :            libMLDAP/MLDAP.c:  53:  MLDAP_LIB v1.1.15
10-12 16:08:46.473  9829  9829 I MLDAP   :            libMLDAP/MLDAP.c:  53: ================================================
10-12 16:08:46.550  9829  9829 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl
10-12 16:08:46.595  9829  9829 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-12 16:08:46.633  9829  9829 I Enhanced Zygote ASLR: DISABLED!
10-12 16:08:46.634  9829  9829 I Radio-JNI: register_android_hardware_Radio DONE
10-12 16:08:46.642  9829  9829 D ReflectionHelper: loadKlass() : caller=android.app.Activity.<clinit>:7525 <bottom of call stack> 
10-12 16:08:46.642  9829  9829 D ReflectionHelper: Reflecting method.....  class <onScreenChanged>
10-12 16:08:46.644  9829  9829 E SemAffinityControl: SemAffinityControl: registerfunction enter
10-12 16:08:46.661  9829  9829 D AndroidRuntime: Calling main entry com.android.commands.am.Am
10-12 16:08:46.685  3703  3920 I ActivityManager: START u0 {act=null typ=null flg=0x10000000 cmp=ComponentInfo{com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}} from uid 2000 on display 0
10-12 16:08:46.727  3703  3920 D ActivityManager: ActivityRecord() Constructor : multiScreenAttrs=MultiScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
10-12 16:08:46.730  3703  3920 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3703  pkgName : AMS_RESUME@CPU_MIN@7
10-12 16:08:46.733  3703  3920 D ActivityManager: mActivityResumeBooster.acquire()
10-12 16:08:46.734  3703  3920 I MultiWindowManagerService: setTaskDimensions: Task=TaskRecord{9d1230bd0 #6 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} minWidth=-1 minHeight=-1 maxWidth=-1 maxHeight=-1
10-12 16:08:46.735  3703  3920 D ActivityManager: moveToFront() : reason=startedActivity setFocusedActivity isAttached=true TaskRecord{9d1230bd0 #6 A=com.thaliproject.thalitest U=0 StackId=1 sz=1}
10-12 16:08:46.735  3703  3920 D InputDispatcher: Focused application set to: xxxx
10-12 16:08:46.736  3703  3920 D ActivityManager: resumeTopActivityInnerLocked() : #1 prevTask=TaskRecord{9d1230bd0 #6 A=com.thaliproject.thalitest U=0 StackId=1 sz=1} next=ActivityRecord{5106efd0 u0 com.thaliproject.thalitest/.MainActivity t6} mFocusedStack=ActivityStack{3b1cc81d0 stackId=1, 3 tasks}
10-12 16:08:46.737  3703  3920 D MountService: getExternalStorageMountMode : 1
10-12 16:08:46.737  3703  3920 D MountService: getExternalStorageMountMode : 3
10-12 16:08:46.737  3703  3920 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10033, packageName : com.thaliproject.thalitest
10-12 16:08:46.740  3703  3798 D WindowManager: addWindow: android.view.ViewRootImpl$W@418e883 displayId=0
10-12 16:08:46.741  3703  3798 D InputTransport: Input channel constructed: fd=455
10-12 16:08:46.741  3703  3798 D InputTransport: Input channel constructed: fd=456
10-12 16:08:46.741  3703  3798 D ViewRootImpl@866a332[thalitest]: setView = DecorView@6d84239[thalitest] touchMode=true
10-12 16:08:46.751  9839  9839 E Zygote  : v2
10-12 16:08:46.751  9839  9839 I libpersona: KNOX_SDCARD checking this for 10033
10-12 16:08:46.751  9839  9839 I libpersona: KNOX_SDCARD not a persona
10-12 16:08:46.751  3703  3920 I ActivityManager: Start proc 9839:com.thaliproject.thalitest/u0a33 for activity com.thaliproject.thalitest/.MainActivity
10-12 16:08:46.752  9839  9839 E Zygote  : accessInfo : 0
10-12 16:08:46.753  9829  9829 D AndroidRuntime: Shutting down VM
10-12 16:08:46.759  9839  9839 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:08:46.760  9839  9839 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.thaliproject.thalitest 
10-12 16:08:46.762  3703  3798 V WindowManager: Relayout Window{dc51a00d0 u0 Starting com.thaliproject.thalitest}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#20 ty=3 fl=#81830118 pfl=0x20011 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
10-12 16:08:46.763  3111  3111 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, uhalitest
10-12 16:08:46.783  9829  9829 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter
10-12 16:08:46.783  9829  9829 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Enter2
10-12 16:08:46.783  9829  9829 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - mSource2
10-12 16:08:46.783  9829  9829 I TMSDISP : AcsAndroidVirtualDisplayIntfImpl::~AcsAndroidVirtualDisplayIntfImpl - Exit
10-12 16:08:46.784  9839  9839 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:08:46.784  9839  9839 D ActivityThread: Added TimaKeyStore provider
10-12 16:08:46.787  3703  5217 I ActivityManager: DSS on for com.thaliproject.thalitest and scale is 1.0
10-12 16:08:46.789  3703  5217 I WindowManager: Failed to capture screenshot of Token{9b5903 ActivityRecord{1a285b2d0 u0 com.samsung.android.MtpApplication/.USBConnection t5}} appWin=Window{9e3bf62d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection} drawState=4
10-12 16:08:46.789  3703  5217 I WindowManager: Failed to capture screenshot of Token{8709167 ActivityRecord{bc99126d0 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity t4}} appWin=Window{dc2cf47d0 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity} drawState=4
10-12 16:08:46.798  3703  3922 V WindowManager: Relayout Window{9e3bf62d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=4 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
10-12 16:08:46.800  3703  5217 D GameManagerService: sem_perfomance_mode: 0
10-12 16:08:46.801  3703  3703 D GameManagerService: NotifyRunnable. pkg: com.thaliproject.thalitest, type: 4, isMinimized: false, isTunableApp: false
10-12 16:08:46.801  3703  3703 D GameManagerService: unexpected mPrevNotiType: -1
10-12 16:08:46.805  3703  4542 V WindowManager: Relayout Window{dc2cf47d0 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: viewVisibility=4 req=0x0 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800802 fmt=-2 wanim=0x103038b vsysui=0x2000 surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
10-12 16:08:46.807  3703  4873 V WindowManager: Relayout Window{652ab3d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=4 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
10-12 16:08:46.810  4919  4919 D Launcher: onTrimMemory. Level: 20
10-12 16:08:46.810  3703  3798 D WindowManager: finishDrawingWindow: Window{dc51a00d0 u0 Starting com.thaliproject.thalitest} mDrawState=DRAW_PENDING
10-12 16:08:46.810  3703  5217 D ActivityTrigger: ActivityTrigger activityPauseTrigger 
10-12 16:08:46.810  3703  5217 D GameManagerService: sem_perfomance_mode: 0
,10-12 16:08:46.811  3703  3798 D ViewRootImpl@866a332[thalitest]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
10-12 16:08:46.814  4646  4646 D io_stats: !@   8,0 r 25187 2215912 w 4534 197680 d 572 73468 f 1859 1859 iot 11100 10427 th 497912 0 0 pt 0 inp 0 1 177.017
10-12 16:08:46.817  4769  4782 D ForegroundUtils: could not check pending caller
10-12 16:08:46.817  4769  4782 D ForegroundUtils: could not check pending caller
10-12 16:08:46.817  3703  5698 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
10-12 16:08:46.817  4769  4782 D ForegroundUtils: could not check pending caller
10-12 16:08:46.817  3703  5698 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
10-12 16:08:46.817  4769  4782 D ForegroundUtils: could not check pending caller
,10-12 16:08:46.823  3703  3798 I WindowManager: Destroying surface Surface(name=com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.AppWindowToken.destroySurfaces:412 com.android.server.wm.AppWindowToken.destroySurfaces:376 com.android.server.wm.WindowStateAnimator.finishExit:654 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:564 com.android.server.wm.WindowAnimator.updateWindowsLocked:439 
10-12 16:08:46.823  3111  3120 I SurfaceFlinger: id=12 Removed MauncherAct (1/6)
,10-12 16:08:46.824  3111  3122 I SurfaceFlinger: id=12 Removed MauncherAct (-2/6)
,10-12 16:08:46.824  3703  3798 D WindowManager: finishDrawingWindow: Window{dc51a00d0 u0 Starting com.thaliproject.thalitest} mDrawState=HAS_DRAWN
,10-12 16:08:46.827  3703  3795 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
,10-12 16:08:46.831  3703  3941 V WindowManager: Relayout Window{dc2cf47d0 u0 com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}: viewVisibility=8 req=0x0 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800802 fmt=-2 wanim=0x103038b vsysui=0x2000 surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,10-12 16:08:46.835  3703  4543 V WindowManager: Relayout Window{652ab3d0 u0 com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}: viewVisibility=8 req=1080x1920 WM.LayoutParams{(0,0)(fillxfill) sim=#130 ty=1 fl=#81910d00 pfl=0x20000 fmt=-2 wanim=0x103038a vsysui=0x600 needsMenuKey=2 dimDuration=0 naviIconColor=0}
,10-12 16:08:46.836  3703  5698 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
10-12 16:08:46.837  3703  5698 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,10-12 16:08:46.838  3703  3920 V WindowManager: Relayout Window{bb25e57d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1015x1572 WM.LayoutParams{(0,0)(wrapxwrap) gr=#11 sim=#120 ty=2 fl=#1820002 fmt=-3 wanim=0x103038b surfaceInsets=Rect(6, 6 - 6, 6) needsMenuKey=2 naviIconColor=0}
,10-12 16:08:46.841  3703  3725 V WindowManager: Relayout Window{9e3bf62d0 u0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: viewVisibility=8 req=1026x96 WM.LayoutParams{(0,0)(wrapxwrap) sim=#120 ty=1 fl=#1800002 fmt=-3 wanim=0x1030466 surfaceInsets=Rect(96, 96 - 96, 96) needsMenuKey=2 naviIconColor=0}
,10-12 16:08:46.853  9839  9839 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:08:46.877  9839  9839 I CordovaLog: Changing log level to DEBUG(3)
10-12 16:08:46.877  9839  9839 I CordovaActivity: Apache Cordova native platform version 6.1.2 is starting
10-12 16:08:46.877  9839  9839 D CordovaActivity: CordovaActivity.onCreate()
,10-12 16:08:46.887  9839  9839 W System  : ClassLoader referenced unknown path: /system/app/Chrome/lib/arm
,10-12 16:08:46.892  9839  9839 I WebViewFactory: Loading com.android.chrome version 56.0.2924.87 (code 292408752)
,10-12 16:08:46.939  9839  9839 I cr_LibraryLoader: Time to load native libraries: 14 ms (timestamps 7127-7141)
10-12 16:08:46.939  9839  9839 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,10-12 16:08:46.947  3703  3989 D MdnieScenarioControlService:  packageName : com.thaliproject.thalitest    className : com.thaliproject.thalitest.MainActivity
,10-12 16:08:46.955  9839  9839 I cr_LibraryLoader: Expected native library version number "56.0.2924.87", actual native library version number "56.0.2924.87"
,10-12 16:08:46.961  9839  9839 I chromium: [INFO:library_loader_hooks.cc(163)] Chromium logging enabled: level = 0, default verbosity = 0
,10-12 16:08:46.979  9839  9839 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,10-12 16:08:47.112  3703  4871 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10033
10-12 16:08:47.113  3703  4871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:921 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:26544 com.android.server.am.ActivityManagerService.registerReceiver:21403 android.app.ActivityManagerNative.onTransact:466 com.android.server.am.ActivityManagerService.onTransact:3573 
,10-12 16:08:47.114  3703  3703 D KnoxVpnEngineService: Vpn Receiver : com.samsung.android.knox.intent.action.VPN_PROXY_BROADCAST_INTERNAL
10-12 16:08:47.114  3703  3915 I KnoxVpnEngineService: vpn handle : Message received
,10-12 16:08:47.148  9839  9839 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9839
,10-12 16:08:47.150  3703  4542 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9839 for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-12 16:08:47.151  3703  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
10-12 16:08:47.151  3703  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-12 16:08:47.151  3703  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.151  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-12 16:08:47.190  9839  9839 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,10-12 16:08:47.198  9839  9839 D PluginManager: init()
,10-12 16:08:47.201  9839  9839 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,10-12 16:08:47.218  9839  9839 I cr_Ime  : ImeThread is enabled.
,10-12 16:08:47.230  9839  9839 D CordovaActivity: Started the activity.
,10-12 16:08:47.232  9839  9839 D CordovaActivity: Resumed the activity.
,10-12 16:08:47.246  3703  4873 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@2bae5d5 displayId=0
,10-12 16:08:47.246  3703  4873 D InputTransport: Input channel constructed: fd=457
10-12 16:08:47.246  3703  4873 D InputTransport: Input channel constructed: fd=458
,10-12 16:08:47.248  3703  4873 D InputTransport: Input channel destroyed: fd=458
,10-12 16:08:47.248  9839  9839 D InputTransport: Input channel constructed: fd=98
10-12 16:08:47.248  9839  9839 D ViewRootImpl@51436d9[MainActivity]: setView = DecorView@727a89e[MainActivity] touchMode=true
,10-12 16:08:47.249  3703  4871 D ActivityManager: post active user change for 0 fullscreen true isHomeActivity() false
10-12 16:08:47.249  3703  4871 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
10-12 16:08:47.249  3703  3703 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 0
10-12 16:08:47.249  9839  9839 D CordovaActivity: Paused the activity.
,10-12 16:08:47.250  3703  3703 I KnoxTimeoutHandler: Shared devices show user statefalse
,10-12 16:08:47.253  3703  3765 D ActivityTrigger: ActivityTrigger activityStopTrigger 
,10-12 16:08:47.260  9839  9839 D ConnectivityManager: requestNetwork; CallingUid : 10033, CallingPid : 9839
,10-12 16:08:47.261  3703  3725 D ConnectivityService: listenForNetwork for Listen from uid/pid:10033/9839 for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-12 16:08:47.262  3703  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
10-12 16:08:47.262  3703  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]
10-12 16:08:47.262  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.262  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.262  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:08:47.262  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.263  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:08:47.263  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.263  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:08:47.263  3703  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
10-12 16:08:47.263  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:08:47.263  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-12 16:08:47.263  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.263  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:08:47.263  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:08:47.263  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-12 16:08:47.273  3703  3920 V WindowManager: Relayout Window{b907cdbd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}: viewVisibility=0 req=1080x1848 WM.LayoutParams{(0,0)(fillxfill) sim=#110 ty=1 fl=#81810900 pfl=0x20000 wanim=0x103038a vsysui=0x600 needsMenuKey=2 naviIconColor=0}
,10-12 16:08:47.274  3111  3111 I SurfaceFlinger: id=18 createSurf (1x1),1 flag=404, NainActivit
,10-12 16:08:47.283  9839  9888 I OpenGLRenderer: Initialized EGL, version 1.4
10-12 16:08:47.284  9839  9888 D OpenGLRenderer: Swap behavior 1
,10-12 16:08:47.288  9839  9888 D libGLESv1: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,10-12 16:08:47.290  9839  9888 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1080x1920]-format:1
10-12 16:08:47.290  9839  9839 D CordovaActivity: Stopped the activity.
,10-12 16:08:47.298  3703  3798 V WindowManager: Now policy hidden: Window{b907cdbd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity}
,10-12 16:08:47.325  9839  9894 E libEGL  : validate_display:99 error 3008 (EGL_BAD_DISPLAY)
,10-12 16:08:47.343  9839  9894 W AudioCapabilities: Unsupported mime audio/mpeg-L1
10-12 16:08:47.343  9839  9894 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,10-12 16:08:47.344  3703  4873 D WindowManager: finishDrawingWindow: Window{b907cdbd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=DRAW_PENDING
,10-12 16:08:47.344  9839  9839 D ViewRootImpl@51436d9[MainActivity]: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,10-12 16:08:47.346  9839  9894 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,10-12 16:08:47.347  9839  9894 W AudioCapabilities: Unsupported mime audio/x-ima
10-12 16:08:47.349  3703  4845 D WindowManager: finishDrawingWindow: Window{b907cdbd0 u0 com.thaliproject.thalitest/com.thaliproject.thalitest.MainActivity} mDrawState=HAS_DRAWN
10-12 16:08:47.349  9839  9894 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
10-12 16:08:47.349  9839  9894 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
10-12 16:08:47.349  9839  9894 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
10-12 16:08:47.350  9839  9839 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
10-12 16:08:47.351  3703  3798 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
10-12 16:08:47.351  3703  3703 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false isMutiwindowRecord is false multiwindowstyle is 1
10-12 16:08:47.352  3703  3703 I KnoxTimeoutHandler: SD activityfalse
10-12 16:08:47.352  3703  3798 I ActivityManager: Displayed com.thaliproject.thalitest/.MainActivity: +541ms (total +616ms)
10-12 16:08:47.352  3703  3703 I KnoxTimeoutHandler: Fullscreen and mCurrent is not KNOX user. Hence hide keyguard
10-12 16:08:47.353  3703  3798 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3703  tag : AMS_RESUME@CPU_MIN@7
10-12 16:08:47.353  3703  3798 D ActivityManager: mActivityResumeBooster.release()
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.353  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.354  3703  3765 D ActivityManager: mActivityResumeBoosterTail.acquire()
10-12 16:08:47.356  3703  3765 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3703  pkgName : AMS_RESUME_TAIL@CPU_MIN@13
10-12 16:08:47.356  3703  3798 D ViewRootImpl@866a332[thalitest]: dispatchDetachedFromWindow
10-12 16:08:47.358  3703  3798 I WindowManager: Destroying surface Surface(name=Starting com.thaliproject.thalitest) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.removeLocked:1776 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:2876 com.android.server.wm.WindowManagerService.removeWindowLocked:2826 com.android.server.wm.WindowManagerService.removeWindowLocked:2641 com.android.server.wm.WindowManagerService.removeWindow:2636 com.android.server.wm.Session.remove:208 
10-12 16:08:47.358  3111  4437 I SurfaceFlinger: id=17 Removed uhalitest (4/6)
10-12 16:08:47.358  3111  3120 I SurfaceFlinger: id=17 Removed uhalitest (-2/6)
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.359  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.360  3703  3798 D InputTransport: Input channel destroyed: fd=455
10-12 16:08:47.360  3703  3798 D InputTransport: Input channel destroyed: fd=456
10-12 16:08:47.367  9839  9894 W VideoCapabilities: Unsupported mime video/wvc1
10-12 16:08:47.368  9839  9894 W VideoCapabilities: Unsupported mime video/x-ms-wmv
10-12 16:08:47.372  9839  9894 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
10-12 16:08:47.372  9839  9894 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
10-12 16:08:47.372  9839  9894 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
10-12 16:08:47.374  9839  9894 W VideoCapabilities: Unsupported mime video/wvc1
10-12 16:08:47.375  9839  9894 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,10-12 16:08:47.376  9839  9894 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,10-12 16:08:47.377  9839  9894 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,10-12 16:08:47.378  9839  9894 W VideoCapabilities: Unsupported mime video/mp43
,10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
10-12 16:08:47.381  9839  9894 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,10-12 16:08:47.384  9839  9894 W VideoCapabilities: Unrecognized profile/level 1/32 for video/mp4v-es
10-12 16:08:47.384  9839  9894 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
10-12 16:08:47.384  9839  9894 W VideoCapabilities: Unrecognized profile/level 32768/64 for video/mp4v-es
,10-12 16:08:47.399  9839  9894 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,10-12 16:08:47.411  9839  9894 W VideoCapabilities: Unsupported mime video/sorenson
,10-12 16:08:47.427  9839  9894 D libGLESv2: STS_GLApi : DTS is not allowed for Package : com.thaliproject.thalitest
,10-12 16:08:47.436  3298  3783 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-12 16:08:47.454  9839  9839 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9839
,10-12 16:08:47.587  9839  9839 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,10-12 16:08:47.599  9839  9839 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,10-12 16:08:47.638  9839  9902 D jxcore_app_log: JniHelper::setJavaVM(0xe4fb4000), pthread_self() = -1108346592
,10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@986e50 added. We now have 1 listener(s)
,10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@986e50 added. We now have 1 listener(s)
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: null
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 256
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-12 16:08:47.642  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-12 16:08:47.647  9839  9902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:78:3E:94:4A:3E
,10-12 16:08:47.647  9839  9902 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
10-12 16:08:47.647  9839  9902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 16:08:47.648  9839  9902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
,10-12 16:08:47.649  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 16:08:47.649  9839  9902 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dce66f added. We now have 2 listener(s)
10-12 16:08:47.649  9839  9902 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 16:08:47.654  9839  9902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 16:08:47.654  9839  9902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 56320
,10-12 16:08:47.655  9839  9902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 120
10-12 16:08:47.655  9839  9902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-12 16:08:47.655  9839  9902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-12 16:08:47.655  9839  9902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-12 16:08:47.655  9839  9902 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,7,main], id: 120
,10-12 16:08:47.657  3703  3703 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1560000  uid : 1000  pid : 3703  tag : AMS_RESUME_TAIL@CPU_MIN@13
,10-12 16:08:47.658  9839  9902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 16:08:47.658  9839  9902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:78:3E:94:4A:3E
,10-12 16:08:47.667  9839  9902 D BluetoothAdapter: STATE_ON
,10-12 16:08:47.671  9839  9902 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:08:47.671  9839  9902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 16:08:47.671  9839  9902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-12 16:08:47.671  9839  9902 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 16:08:47.671  9839  9902 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-12 16:08:47.675  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:08:47.680  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:08:47.688  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:08:47.691  9839  9839 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
10-12 16:08:47.691  9839  9839 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,10-12 16:08:48.317  9839  9905 W jxcore-log: Initializing JXcore engine
10-12 16:08:48.317  9839  9905 W jxcore-log: JXcore engine is ready
,10-12 16:08:48.336  3239  3239 E audit   : type=1400 audit(1507817328.325:518): avc:  denied  { ioctl } for  pid=9905 comm="Thread-9" path="socket:[64831]" dev="sockfs" ino=64831 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0 SEPF_SECMOBILE_7.0_0006
10-12 16:08:48.336  3703  3793 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / /system/bin/sh /system/bin/install-recovery.sh
10-12 16:08:48.336  3239  3239 E audit   : type=1300 audit(1507817328.325:518): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=3 a1=5451 a2=9a5601ca a3=22 items=0 ppid=3272 pid=9905 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-12 16:08:48.336  3703  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,10-12 16:08:48.338  3239  3239 E audit   : type=1327 audit(1507817328.325:518): proctitle="com.thaliproject.thalitest"
10-12 16:08:48.338  3239  3239 E audit   : type=1320 audit(1507817328.325:518): 
10-12 16:08:48.338  3239  3239 E audit   : type=1400 audit(1507817328.325:519): avc:  denied  { ioctl } for  pid=9905 comm="Thread-9" path="/dev/pmsg0" dev="tmpfs" ino=9110 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0 SEPF_SECMOBILE_7.0_0006
,10-12 16:08:48.338  3239  3239 E audit   : type=1300 audit(1507817328.325:519): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=4 a1=5451 a2=9a5601ca a3=22 items=0 ppid=3272 pid=9905 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
,10-12 16:08:48.339  3703  3793 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,10-12 16:08:48.340  3239  3239 E audit   : type=1327 audit(1507817328.325:519): proctitle="com.thaliproject.thalitest"
10-12 16:08:48.340  3239  3239 E audit   : type=1320 audit(1507817328.325:519): 
10-12 16:08:48.340  3239  3239 E audit   : type=1400 audit(1507817328.325:520): avc:  denied  { ioctl } for  pid=9905 comm="Thread-9" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2251 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs_trace_marker:s0 tclass=file permissive=0 SEPF_SECMOBILE_7.0_0006
10-12 16:08:48.340  3703  3793 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent for audit.log / "com.thaliproject.thalitest"
10-12 16:08:48.340  3239  3239 E audit   : type=1300 audit(1507817328.325:520): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=5 a1=5451 a2=9a5601ca a3=22 items=0 ppid=3272 pid=9905 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-12 16:08:48.341  3703  3793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.SEDenialService$AuditFileObserver.onEvent:84 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
10-12 16:08:48.341  3239  3239 E audit   : type=1327 audit(1507817328.325:520): proctitle="com.thaliproject.thalitest"
10-12 16:08:48.341  3703  3765 D MountService: getExternalStorageMountMode : 1
10-12 16:08:48.341  3239  3239 E audit   : type=1320 audit(1507817328.325:520): 
10-12 16:08:48.341  3703  3765 D MountService: getExternalStorageMountMode : 3
10-12 16:08:48.342  3703  3765 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.securitylogagent
10-12 16:08:48.341  9839  9905 W jxcore-log: Starting JXcore engine
10-12 16:08:48.342  3239  3239 E audit   : type=1400 audit(1507817328.325:521): avc:  denied  { ioctl } for  pid=9905 comm="Thread-9" path="socket:[64924]" dev="sockfs" ino=64924 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0 SEPF_SECMOBILE_7.0_0006
10-12 16:08:48.342  3239  3239 E audit   : type=1300 audit(1507817328.325:521): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=54 a1=5451 a2=9a5601ca a3=22 items=0 ppid=3272 pid=9905 auid=4294967295 uid=10033 gid=10033 euid=10033 suid=10033 fsuid=10033 egid=10033 sgid=10033 fsgid=10033 tty=(none) ses=4294967295 comm="Thread-9" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
10-12 16:08:48.344  3239  3239 E audit   : type=1327 audit(1507817328.325:521): proctitle="com.thaliproject.thalitest"
10-12 16:08:48.344  3239  3239 E audit   : type=1320 audit(1507817328.325:521): 
,10-12 16:08:48.358  9907  9907 E Zygote  : v2
,10-12 16:08:48.358  9907  9907 I libpersona: KNOX_SDCARD checking this for 1000
10-12 16:08:48.358  9907  9907 I libpersona: KNOX_SDCARD not a persona
10-12 16:08:48.359  9907  9907 E Zygote  : accessInfo : 0
,10-12 16:08:48.362  9907  9907 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:08:48.363  9907  9907 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.securitylogagent 
,10-12 16:08:48.368  3703  3765 I ActivityManager: Start proc 9907:com.samsung.android.securitylogagent/1000 for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver
,10-12 16:08:48.370  3703  3793 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,10-12 16:08:48.376  9907  9907 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:08:48.376  9907  9907 D ActivityThread: Added TimaKeyStore provider
,10-12 16:08:48.378  3703  4872 I ActivityManager: DSS on for com.samsung.android.securitylogagent and scale is 1.0
,10-12 16:08:48.378  9839  9905 W jxcore-log: Platform android
10-12 16:08:48.378  9839  9905 W jxcore-log: 
10-12 16:08:48.378  9839  9905 W jxcore-log: Process ARCH arm
10-12 16:08:48.378  9839  9905 W jxcore-log: 
,10-12 16:08:48.392  9907  9907 W System  : ClassLoader referenced unknown path: /system/app/SecurityLogAgent/lib/arm64
,10-12 16:08:48.402  9907  9907 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:08:48.405  9907  9907 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,10-12 16:08:48.411  9907  9907 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,10-12 16:08:48.513  9839  9905 I jxcore-log: JXcore Cordova bridge is ready
10-12 16:08:48.513  9839  9905 I jxcore-log: 
10-12 16:08:48.513  9839  9905 W jxcore-log: JXcore engine is started
,10-12 16:08:48.517  9839  9902 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-12 16:08:48.521  9839  9839 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
10-12 16:08:48.522  9839  9839 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-12 16:08:48.957  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:08:48.957  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:08:51.818  4646  4646 D io_stats: !@   8,0 r 25614 2264832 w 4564 198432 d 579 73496 f 1876 1876 iot 11280 10615 th 466600 0 0 pt 0 inp 0 7 182.020
,10-12 16:08:51.975  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:08:51.975  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:08:52.030  3703  5698 D SSRM:f  : SIOP:: AP = 330, PST = 288 (W:6), CP = 243, CUR = -11, LCD = 57
,10-12 16:08:52.428  3298  3783 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-12 16:08:52.445  3703  4850 I ActivityManager: KPU : put [com.google.android.apps.walletnfcrel] : 31688 K
10-12 16:08:52.445  3703  4850 I ActivityManager: Killing 8980:com.google.android.apps.walletnfcrel/u0a15 (adj 906): DHA:empty #33
,10-12 16:08:52.482  3703  3922 D ActivityManager: cleanUpApplicationRecord -- 8980
,10-12 16:08:52.484  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:08:52.818  3703  5698 D GameManagerService: identifyGamePackage. com.thaliproject.thalitest
,10-12 16:08:54.991  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:08:54.991  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:08:55.920  9839  9905 I jxcore-log: 2017-10-12 14:08:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-12 16:08:55.920  9839  9905 I jxcore-log: 
,10-12 16:08:55.922  9839  9905 I jxcore-log: 2017-10-12 14:08:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-12 16:08:55.922  9839  9905 I jxcore-log: 
10-12 16:08:55.922  9839  9905 I jxcore-log: 2017-10-12 14:08:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
10-12 16:08:55.922  9839  9905 I jxcore-log: 
,10-12 16:08:55.932  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:08:55.936  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 16:08:55.940  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:08:55.944  9839  9905 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
10-12 16:08:55.945  9839  9905 I jxcore-log: 2017-10-12 14:08:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-12 16:08:55.945  9839  9905 I jxcore-log: 
10-12 16:08:55.946  9839  9905 I jxcore-log: 2017-10-12 14:08:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
10-12 16:08:55.946  9839  9905 I jxcore-log: 
10-12 16:08:55.946  9839  9905 I jxcore-log: 2017-10-12 14:08:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-12 16:08:55.946  9839  9905 I jxcore-log: 
,10-12 16:08:55.958  3703  4851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:08:55.959  3703  4851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4265, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:08:55.960  3703  4851 D BatteryService: online:4, current avg:-97, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:-261
10-12 16:08:55.960  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:08:55.966  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-12 16:08:55.966  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:08:55.969  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:08:55.972  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-12 16:08:55.973  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:08:55.978  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:08:55.980  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:08:55.981  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:08:55.984  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:08:55.986  4055  4055 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-12 16:08:55.987  4055  4700 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:08:56.222  9839  9905 D ExecuteNativeTests: Running unit tests
10-12 16:08:56.222  9839  9905 D BluetoothAdapter: enable()
,10-12 16:08:56.228  4055  5721 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,10-12 16:08:56.229  4055  5721 D AdapterProvider: query
,10-12 16:08:56.244  4055  5721 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@1a3240c
,10-12 16:08:56.247  4055  5721 D BluetoothAdapterService: updateEvent - already set, update
10-12 16:08:56.247  4055  5721 W BluetoothAdapterService: updateEvent - alreadySet is true
,10-12 16:08:56.248  4055  5721 D AdapterProvider: update
,10-12 16:08:56.258  4055  5721 E BluetoothAdapterService: updateEvent - update success 1
,10-12 16:08:56.262  9839  9905 D BluetoothAdapter: enable(): BT is already enabled..!
,10-12 16:08:56.274  3703  4871 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:08:56.275  3703  4871 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-12 16:08:56.276  3703  4871 D WifiControlHistoryProvider: query
,10-12 16:08:56.304  3703  4871 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-12 16:08:56.306  3703  4871 D SecContentProvider: called from android.uid.system:1000
10-12 16:08:56.308  3703  4871 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-12 16:08:56.313  3703  4871 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-12 16:08:56.314  3703  4871 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-12 16:08:56.791  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-12 16:08:56.818  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-12 16:08:56.819  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-12 16:08:56.822  4646  4646 D io_stats: !@   8,0 r 25623 2265184 w 4612 198884 d 579 73496 f 1881 1881 iot 11300 10629 th 472536 0 0 pt 0 inp 0 0 187.024
,10-12 16:08:58.011  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:08:58.012  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:09:00.000  3703  3864 D SamsungAlarmManager: Expired : 8
,10-12 16:09:00.001  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{c6652cb type 3 when 190203 android}
,10-12 16:09:00.011  3703  3703 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171012T161000 - CU:1000/CP:3703
10-12 16:09:00.012  3703  3703 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171012T161000, SetElapsed=250204, nowELAPSED=190215
,10-12 16:09:00.016  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
10-12 16:09:00.017  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#start
,10-12 16:09:00.017  4069  4069 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-12 16:09:00.045  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#end
10-12 16:09:00.046  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-12 16:09:00.051  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-12 16:09:00.061  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:09:00.063  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:09:00.066  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:09:00.069  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:09:00.083  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:09:00.086  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:09:00.089  4069  4069 V hong    : mid yDiff = 438
10-12 16:09:00.089  4069  4069 V hong    : mid yDiff = 438
,10-12 16:09:00.091  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-12 16:09:00.092  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-12 16:09:00.096  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:09:00.098  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:09:00.113  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:09:00.114  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:09:00.130  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-12 16:09:00.133  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-12 16:09:00.138  5082  5082 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-12 16:09:00.140  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-12 16:09:00.144  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-12 16:09:00.149  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-12 16:09:00.150  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,10-12 16:09:00.151  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-12 16:09:00.152  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-12 16:09:00.153  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-12 16:09:00.157  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-12 16:09:00.158  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB5FCA37F9ACC437DAB58E78E59D669ACF117144EC89E612A5F14A2E2171ED13284ACBC718C921A0B096D177883DEA625]}
,10-12 16:09:00.160  5082  5082 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-12 16:09:01.032  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:01.032  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:09:02.052  3703  5698 D SSRM:f  : SIOP:: AP = 320, PST = 295 (W:6), CP = 254, CUR = 24, LCD = 57
,10-12 16:09:03.283  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:09:03.284  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-12 16:09:03.286  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:09:03.286  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:09:04.064  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:04.065  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:09:05.316  3703  4450 E Watchdog: !@Sync 6 [12_paź_16_09_05.316]
,10-12 16:09:05.629  3703  3804 I PowerManagerService: [PWL] On : 0 (195832 ms ago)
10-12 16:09:05.629  3703  3804 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-12 16:09:06.027  3703  4543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:09:06.028  3703  4543 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:09:06.028  3703  4543 D BatteryService: online:4, current avg:75, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:190
10-12 16:09:06.029  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:09:06.041  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-12 16:09:06.041  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:09:06.044  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:09:06.050  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-12 16:09:06.050  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:09:06.058  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:09:06.064  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
10-12 16:09:06.064  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:09:06.082  4055  4055 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-12 16:09:06.085  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:09:06.087  4055  4700 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:09:06.320  9839  9905 I com.test.thalitest.ThaliTestRunner: Running UT
,10-12 16:09:06.449  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 16:09:06.449  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5011656 added. We now have 2 listener(s)
10-12 16:09:06.449  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5011656 added. We now have 3 listener(s)
10-12 16:09:06.449  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 16:09:06.450  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: ", Bluetooth MAC address: "44:78:3E:94:4A:3E"Peer extra info: "256
10-12 16:09:06.450  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 16:09:06.450  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: null
10-12 16:09:06.450  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 16:09:06.450  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c8e6d7 added. We now have 4 listener(s)
10-12 16:09:06.450  9839  9905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 16:09:06.451  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 16:09:06.458  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.464  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
10-12 16:09:06.464  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-12 16:09:06.464  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 16:09:06.464  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 16:09:06.465  9839  9905 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [00:11:22:33:44:55] timed out
10-12 16:09:06.465  9839  9905 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 16:09:06.465  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 16:09:06.465  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 16:09:06.465  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-12 16:09:06.466  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
10-12 16:09:06.466  9839  9905 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-12 16:09:06.468  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,10-12 16:09:06.470  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
10-12 16:09:06.470  9839  9905 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-12 16:09:06.473  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 16:09:06.482  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:06.485  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 16:09:06.485  9839  9905 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 16:09:06.485  9839  9905 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 0
,10-12 16:09:06.485  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 256 -> 0
10-12 16:09:06.486  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
10-12 16:09:06.488  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:06.488  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:06.488  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:06.488  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:06.490  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":0,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:06.490  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":0,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:06.491  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.491  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 16:09:06.491  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 16:09:06.491  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 16:09:06.491  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 16:09:06.492  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:06.493  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 16:09:06.494  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 16:09:06.494  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 16:09:06.494  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 16:09:06.495  9839  9925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 16:09:06.495  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 16:09:06.495  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-12 16:09:06.495  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 16:09:06.495  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 16:09:06.498  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:06.501  9839  9925 D BluetoothSocket: bindListen(): myUserId = 0
,10-12 16:09:06.501  9839  9925 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 16:09:06.505  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:06.506  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-12 16:09:06.508  9839  9925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-12 16:09:06.508  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-12 16:09:06.508  9839  9905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 16:09:06.509  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 16:09:06.510  9839  9925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@f9041e2, port: 6, type: 1, local socket address: null, socket type: 0
,10-12 16:09:06.512  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.513  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.515  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.518  9839  9905 D BluetoothAdapter: isSecureModeEnabled
,10-12 16:09:06.518  4055  4568 D BtConfig.SecureMode: isSecureModeOn:false
,10-12 16:09:06.520  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:06.520  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 16:09:06.522  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.523  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:06.523  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 16:09:06.524  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 16:09:06.524  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 0
,10-12 16:09:06.526  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.530  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.531  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:06.531  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 16:09:06.531  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
10-12 16:09:06.531  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d795b619-8f1d-4c80-8da3-dbe435a7fe11", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,10-12 16:09:06.532  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 00 44 78 3E 94 4A 3E
,10-12 16:09:06.534  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 16:09:06.534  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:06.535  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.535  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:06.535  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-12 16:09:06.536  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 16:09:06.536  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:06.537  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.538  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[0, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.539  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.541  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:06.541  9839  9905 D BluetoothAdapter: isSecureModeEnabled
10-12 16:09:06.541  4055  5721 D BtConfig.SecureMode: isSecureModeOn:false
,10-12 16:09:06.542  9839  9905 D BluetoothLeAdvertiser: start advertising
,10-12 16:09:06.543  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:06.553  4055  5721 D BtGatt.GattService: registerClient() - UUID=cc7211aa-e6af-46a4-b5b7-8686f76ae88e
,10-12 16:09:06.657  4055  4176 D BtGatt.GattService: onClientRegistered() - UUID=cc7211aa-e6af-46a4-b5b7-8686f76ae88e, clientIf=5, status=0
,10-12 16:09:06.659  9839  9850 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-12 16:09:06.664  4055  4067 E BtGatt.ContextMap: Context not found for ID 5
,10-12 16:09:06.665  4055  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
,10-12 16:09:06.666  4055  4570 D BtGatt.AdvertiseManager: message : 0
,10-12 16:09:06.669  4055  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-12 16:09:06.669  4055  4570 D BtGatt.AdvertiseManager: size of list is =0
,10-12 16:09:06.677  4055  4570 D BtGatt.AdvertiseManager: starting advertising
,10-12 16:09:06.682  4055  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-12 16:09:06.686  4055  4636 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-12 16:09:06.704  4055  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 16:09:06.707  4055  4570 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 16:09:06.716  4055  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-12 16:09:06.717  4055  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-12 16:09:06.717  4055  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,10-12 16:09:06.717  4055  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
10-12 16:09:06.718  4055  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,10-12 16:09:06.719  9839  9851 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-12 16:09:06.721  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.722  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:06.722  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-12 16:09:06.723  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.725  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.726  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.727  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.728  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:06.728  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 16:09:06.732  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 16:09:06.733  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.737  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.738  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:06.739  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:06.740  9839  9905 I io.jxcore.node.ConnectionHelper: start: OK
10-12 16:09:06.740  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-12 16:09:06.742  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.743  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:06.743  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-12 16:09:06.744  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.745  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.746  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,10-12 16:09:06.747  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:06.748  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 16:09:06.748  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 16:09:06.749  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.749  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.751  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.752  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.753  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.758  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-12 16:09:06.758  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 16:09:06.759  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:06.760  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,10-12 16:09:06.760  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 16:09:06.831  4646  4646 D io_stats: !@   8,0 r 25649 2266000 w 4635 199264 d 584 73584 f 1889 1889 iot 11320 10645 th 472956 0 0 pt 0 inp 0 0 197.033
,10-12 16:09:07.087  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:07.087  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:09:07.243  9839  9927 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,10-12 16:09:07.246  9839  9905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 16:09:07.247  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
10-12 16:09:07.247  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
10-12 16:09:07.247  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
10-12 16:09:07.247  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
10-12 16:09:07.248  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
10-12 16:09:07.248  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
,10-12 16:09:07.248  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
10-12 16:09:07.248  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
10-12 16:09:07.249  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
10-12 16:09:07.249  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
10-12 16:09:07.249  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
10-12 16:09:07.250  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,10-12 16:09:07.250  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
10-12 16:09:07.250  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
10-12 16:09:07.250  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
10-12 16:09:07.250  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
10-12 16:09:07.251  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
10-12 16:09:07.251  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
10-12 16:09:07.251  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
10-12 16:09:07.252  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
,10-12 16:09:07.252  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
10-12 16:09:07.252  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
10-12 16:09:07.252  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
10-12 16:09:07.253  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
10-12 16:09:07.253  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
10-12 16:09:07.253  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
10-12 16:09:07.253  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
10-12 16:09:07.254  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
10-12 16:09:07.254  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
,10-12 16:09:07.254  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
10-12 16:09:07.254  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
10-12 16:09:07.255  9839  9905 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-12 16:09:07.255  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-12 16:09:07.256  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 16:09:07.256  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 16:09:07.256  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-12 16:09:07.256  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-12 16:09:07.257  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 16:09:07.257  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 16:09:07.258  9839  9925 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 16:09:07.258  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 16:09:07.258  9839  9925 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 16:09:07.258  9839  9925 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 16:09:07.258  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 16:09:07.258  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 16:09:07.258  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 16:09:07.259  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.260  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-12 16:09:07.260  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-12 16:09:07.262  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.263  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.264  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.265  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.269  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.272  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.273  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-12 16:09:07.276  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.279  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:07.280  9839  9905 D BluetoothLeScanner: could not find callback wrapper
10-12 16:09:07.280  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-12 16:09:07.281  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.282  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.283  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.283  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-12 16:09:07.284  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.288  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.291  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.291  9839  9905 D BluetoothLeAdvertiser: stop advertising
,10-12 16:09:07.294  4055  4068 E BtGatt.ContextMap: Context not found for ID 5
,10-12 16:09:07.295  4055  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
10-12 16:09:07.295  4055  4570 D BtGatt.AdvertiseManager: message : 1
10-12 16:09:07.298  4055  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
10-12 16:09:07.298  4055  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-12 16:09:07.302  4055  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-12 16:09:07.313  4055  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-12 16:09:07.313  4055  4176 D BtGatt.GattService: Client app is not null!
,10-12 16:09:07.314  9839  9850 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-12 16:09:07.316  4055  4568 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 16:09:07.319  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 16:09:07.320  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.320  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-12 16:09:07.321  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.323  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.324  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.324  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 16:09:07.324  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-12 16:09:07.327  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 16:09:07.328  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.333  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.333  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 16:09:07.334  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.335  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.336  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 16:09:07.337  9839  9839 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 16:09:07.338  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-12 16:09:07.338  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 16:09:07.338  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-12 16:09:07.339  9839  9928 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
10-12 16:09:07.339  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 16:09:07.339  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 16:09:07.340  9839  9905 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-12 16:09:07.340  9839  9905 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-12 16:09:07.340  9839  9905 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
10-12 16:09:07.340  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:07.340  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
10-12 16:09:07.341  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
10-12 16:09:07.341  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.341  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 16:09:07.342  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-12 16:09:07.342  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.343  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.344  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.345  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 16:09:07.349  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:07.349  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:07.350  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.351  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:07.357  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":1,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:07.358  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":1,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:07.358  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.359  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 16:09:07.359  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 16:09:07.359  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 16:09:07.359  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 16:09:07.361  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 16:09:07.362  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 16:09:07.363  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-12 16:09:07.363  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 16:09:07.363  9839  9929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 16:09:07.363  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 16:09:07.363  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-12 16:09:07.363  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 16:09:07.363  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 16:09:07.363  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 16:09:07.367  9839  9929 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:07.367  9839  9929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 16:09:07.371  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-12 16:09:07.372  9839  9905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 16:09:07.372  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 16:09:07.373  9839  9929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-12 16:09:07.373  9839  9929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@ab3d9cf, port: 6, type: 1, local socket address: null, socket type: 0
,10-12 16:09:07.376  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.378  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.380  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.383  9839  9905 D BluetoothAdapter: isSecureModeEnabled
,10-12 16:09:07.384  4055  4067 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:07.384  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.385  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 16:09:07.387  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.389  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.389  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 16:09:07.389  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 16:09:07.389  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 1
,10-12 16:09:07.392  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.397  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.397  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.397  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 16:09:07.397  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,10-12 16:09:07.398  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d795b619-8f1d-4c80-8da3-dbe435a7fe11", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-12 16:09:07.398  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 44 78 3E 94 4A 3E
10-12 16:09:07.399  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:07.399  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 16:09:07.400  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.401  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.401  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-12 16:09:07.401  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 16:09:07.402  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.402  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.403  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[1, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.405  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.406  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:07.406  9839  9905 D BluetoothAdapter: isSecureModeEnabled
,10-12 16:09:07.407  4055  4568 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:07.407  9839  9905 D BluetoothLeAdvertiser: start advertising
,10-12 16:09:07.409  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:07.416  4055  4568 D BtGatt.GattService: registerClient() - UUID=c2b64bb2-3c1c-4f13-b166-a0fa382a7f5d
,10-12 16:09:07.477  3298  3783 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-12 16:09:07.495  3703  3941 I ActivityManager: KPU : put [com.google.android.gm] : 32496 K
10-12 16:09:07.495  3703  3941 I ActivityManager: Killing 8716:com.google.android.gm/u0a108 (adj 906): DHA:empty #33
,10-12 16:09:07.519  4055  4176 D BtGatt.GattService: onClientRegistered() - UUID=c2b64bb2-3c1c-4f13-b166-a0fa382a7f5d, clientIf=5, status=0
,10-12 16:09:07.520  9839  9851 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-12 16:09:07.522  4055  4068 E BtGatt.ContextMap: Context not found for ID 5
10-12 16:09:07.523  4055  4570 D BtGatt.AdvertiseManager: message : 0
10-12 16:09:07.523  4055  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-12 16:09:07.524  4055  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-12 16:09:07.524  4055  4570 D BtGatt.AdvertiseManager: size of list is =0
,10-12 16:09:07.529  4055  4570 D BtGatt.AdvertiseManager: starting advertising
,10-12 16:09:07.533  4055  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-12 16:09:07.536  4055  4636 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-12 16:09:07.547  4055  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 16:09:07.549  4055  4570 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 16:09:07.553  3703  5217 D ActivityManager: cleanUpApplicationRecord -- 8716
,10-12 16:09:07.555  4055  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-12 16:09:07.555  4055  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-12 16:09:07.555  4055  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-12 16:09:07.555  4055  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
10-12 16:09:07.555  4055  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,10-12 16:09:07.556  9839  9850 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
10-12 16:09:07.558  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.558  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.558  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-12 16:09:07.559  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.559  4769  4788 D ForegroundUtils: could not check pending caller
10-12 16:09:07.559  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.560  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.560  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.560  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.560  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 16:09:07.563  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 16:09:07.563  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.563  9839  9905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,10-12 16:09:07.567  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.568  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:07.568  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:07.569  9839  9905 I io.jxcore.node.ConnectionHelper: start: OK
10-12 16:09:07.569  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 16:09:07.570  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.570  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:07.570  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-12 16:09:07.571  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.571  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.572  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:07.572  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.572  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 16:09:07.572  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 16:09:07.573  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.573  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.573  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.574  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.574  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:07.578  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.578  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 16:09:07.579  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.579  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:07.579  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 16:09:08.078  9839  9932 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,10-12 16:09:08.081  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-12 16:09:08.082  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 16:09:08.082  9839  9839 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 16:09:08.082  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
10-12 16:09:08.083  9839  9905 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-12 16:09:08.084  9839  9905 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-12 16:09:08.084  9839  9905 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
10-12 16:09:08.084  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-12 16:09:08.085  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:08.093  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:08.094  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:08.095  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.095  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:08.102  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:08.103  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:08.104  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 56320
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 2
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-12 16:09:08.105  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.105  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 2
10-12 16:09:08.107  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.108  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.109  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.111  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.113  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.113  9839  9905 D BluetoothLeAdvertiser: stop advertising
10-12 16:09:08.115  4055  5721 E BtGatt.ContextMap: Context not found for ID 5
10-12 16:09:08.115  4055  4570 D BtGatt.AdvertiseManager: message : 1
10-12 16:09:08.115  4055  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
10-12 16:09:08.117  4055  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
10-12 16:09:08.117  4055  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
10-12 16:09:08.119  4055  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
10-12 16:09:08.125  4055  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-12 16:09:08.126  4055  4176 D BtGatt.GattService: Client app is not null!
10-12 16:09:08.126  9839  9851 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
10-12 16:09:08.128  4055  4067 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 16:09:08.130  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 16:09:08.130  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.131  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 16:09:08.131  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.132  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.133  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.133  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 16:09:08.133  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.134  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.135  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.135  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 16:09:08.135  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
10-12 16:09:08.135  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d795b619-8f1d-4c80-8da3-dbe435a7fe11", Bluetooth MAC address: "44:78:3E:94:4A:3E"
,10-12 16:09:08.136  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 44 78 3E 94 4A 3E
,10-12 16:09:08.136  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:08.137  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 16:09:08.137  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.138  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.138  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,10-12 16:09:08.139  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 16:09:08.139  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.140  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.141  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[2, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.142  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.144  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.144  9839  9905 D BluetoothAdapter: isSecureModeEnabled
10-12 16:09:08.144  4055  5721 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:08.145  9839  9905 D BluetoothLeAdvertiser: start advertising
10-12 16:09:08.146  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.152  4055  5721 D BtGatt.GattService: registerClient() - UUID=d2fe135e-211e-4351-804a-f711f5c02597
,10-12 16:09:08.255  4055  4176 D BtGatt.GattService: onClientRegistered() - UUID=d2fe135e-211e-4351-804a-f711f5c02597, clientIf=5, status=0
,10-12 16:09:08.257  9839  9850 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-12 16:09:08.261  4055  4067 E BtGatt.ContextMap: Context not found for ID 5
,10-12 16:09:08.262  4055  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-12 16:09:08.262  4055  4570 D BtGatt.AdvertiseManager: message : 0
10-12 16:09:08.264  4055  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-12 16:09:08.264  4055  4570 D BtGatt.AdvertiseManager: size of list is =0
,10-12 16:09:08.274  4055  4570 D BtGatt.AdvertiseManager: starting advertising
,10-12 16:09:08.278  4055  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-12 16:09:08.282  4055  4636 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-12 16:09:08.303  4055  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 16:09:08.306  4055  4570 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 16:09:08.319  4055  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-12 16:09:08.320  4055  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-12 16:09:08.320  4055  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
,10-12 16:09:08.320  4055  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
10-12 16:09:08.321  4055  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
10-12 16:09:08.322  9839  9851 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-12 16:09:08.323  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.323  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.324  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.325  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-12 16:09:08.326  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.327  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.328  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.329  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.331  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.331  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,10-12 16:09:08.331  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-12 16:09:08.332  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.332  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.332  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 16:09:08.333  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.333  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.333  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 16:09:08.334  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 16:09:08.334  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 16:09:08.334  9839  9905 I io.jxcore.node.ConnectionHelper: start: OK
10-12 16:09:08.334  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:08.335  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.336  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 16:09:08.337  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-12 16:09:08.338  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.338  9839  9934 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,10-12 16:09:08.339  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.339  9839  9905 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 16:09:08.340  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-12 16:09:08.340  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 16:09:08.341  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 16:09:08.341  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 16:09:08.341  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-12 16:09:08.342  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 16:09:08.342  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-12 16:09:08.342  9839  9929 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 16:09:08.342  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 16:09:08.342  9839  9929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 16:09:08.342  9839  9929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 16:09:08.342  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 16:09:08.343  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 16:09:08.343  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.344  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 16:09:08.344  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-12 16:09:08.344  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 16:09:08.345  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.346  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.347  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.348  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.351  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.352  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.353  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-12 16:09:08.354  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.355  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.355  9839  9905 D BluetoothLeScanner: could not find callback wrapper
10-12 16:09:08.355  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-12 16:09:08.356  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.357  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.358  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.358  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-12 16:09:08.358  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.360  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.362  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.362  9839  9905 D BluetoothLeAdvertiser: stop advertising
,10-12 16:09:08.363  4055  5721 E BtGatt.ContextMap: Context not found for ID 5
10-12 16:09:08.364  4055  4570 D BtGatt.AdvertiseManager: message : 1
10-12 16:09:08.364  4055  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
10-12 16:09:08.365  4055  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
10-12 16:09:08.365  4055  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-12 16:09:08.367  4055  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-12 16:09:08.373  4055  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-12 16:09:08.373  4055  4176 D BtGatt.GattService: Client app is not null!
,10-12 16:09:08.373  9839  9850 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-12 16:09:08.375  4055  4067 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 16:09:08.377  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-12 16:09:08.377  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.378  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 16:09:08.378  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.379  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.380  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.380  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 16:09:08.380  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 16:09:08.381  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 16:09:08.382  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.383  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-12 16:09:08.383  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-12 16:09:08.383  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-12 16:09:08.385  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.385  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 16:09:08.386  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.387  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.387  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 16:09:08.388  9839  9839 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 16:09:08.388  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 16:09:08.388  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 16:09:08.388  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 16:09:08.388  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 16:09:08.389  9839  9935 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
10-12 16:09:08.389  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:08.389  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.390  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 16:09:08.390  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-12 16:09:08.390  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.390  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.391  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.391  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testListenToConnectivityChanges
10-12 16:09:08.391  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 16:09:08.392  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 16:09:08.392  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6b548 added. We now have 3 listener(s)
10-12 16:09:08.392  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6b548 added. We now have 5 listener(s)
10-12 16:09:08.392  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 16:09:08.395  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":2,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:08.396  9839  9905 D org.tha,liproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 16:09:08.396  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":2,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:08.397  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 16:09:08.397  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f74fe1 added. We now have 6 listener(s)
10-12 16:09:08.397  9839  9905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 16:09:08.398  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 16:09:08.401  4949  5001 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 4ms lastUpdatedAfter : 60113 ms mFlush_time_threasold : 2000 mCurrentSize : 257
10-12 16:09:08.405  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 16:09:08.414  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:08.419  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 16:09:08.419  9839  9905 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 16:09:08.424  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:08.429  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:08.434  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:08.442  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:08.445  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 16:09:08.445  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 16:09:08.445  9839  9905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 16:09:08.445  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 16:09:08.445  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 16:09:08.445  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 16:09:08.445  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6b548 removed from the list
10-12 16:09:08.445  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6b548 removed from the list
10-12 16:09:08.445  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 16:09:08.445  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f74fe1 removed from the list
,10-12 16:09:08.450  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:08.450  9839  9905 D io.jxcore.node.ConnectivityMonitor: stop
10-12 16:09:08.451  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 16:09:08.453  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
10-12 16:09:08.453  9839  9905 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-12 16:09:08.455  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,10-12 16:09:08.457  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,10-12 16:09:08.458  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
10-12 16:09:08.459  9839  9905 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-12 16:09:08.460  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
10-12 16:09:08.461  9839  9905 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,10-12 16:09:08.462  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
,10-12 16:09:08.463  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 16:09:08.463  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 16:09:08.463  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 16:09:08.463  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 16:09:08.464  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 16:09:08.464  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 16:09:08.464  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 16:09:08.464  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 16:09:08.465  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 16:09:08.466  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
,10-12 16:09:08.467  9839  9905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 16:09:08.467  9839  9905 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-12 16:09:08.467  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [00:11:22:33:44:55]
,10-12 16:09:08.470  9839  9905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-12 16:09:08.471  9839  9905 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-12 16:09:08.471  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [10:010:010:010:010:010]
10-12 16:09:08.471  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [11:110:110:110:110:110]
,10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [12:210:210:210:210:210]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [13:310:310:310:310:310]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [14:410:410:410:410:410]
,10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [15:510:510:510:510:510]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [16:610:610:610:610:610]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [17:710:710:710:710:710]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [18:810:810:810:810:810]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [19:910:910:910:910:910]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [20:1010:1010:1010:1010:1010]
,10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [21:1110:1110:1110:1110:1110]
,10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [22:1210:1210:1210:1210:1210]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [23:1310:1310:1310:1310:1310]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [24:1410:1410:1410:1410:1410]
10-12 16:09:08.472  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [25:1510:1510:1510:1510:1510]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [26:1610:1610:1610:1610:1610]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [27:1710:1710:1710:1710:1710]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [28:1810:1810:1810:1810:1810]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [29:1910:1910:1910:1910:1910]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [30:2010:2010:2010:2010:2010]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [31:2110:2110:2110:2110:2110]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [32:2210:2210:2210:2210:2210]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [33:2310:2310:2310:2310:2310]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [34:2410:2410:2410:2410:2410]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [35:2510:2510:2510:2510:2510]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [36:2610:2610:2610:2610:2610]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [37:2710:2710:2710:2710:2710]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [38:2810:2810:2810:2810:2810]
10-12 16:09:08.473  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [39:2910:2910:2910:2910:2910]
10-12 16:09:08.473  9839  9905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-12 16:09:08.474  9839  9905 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 16:09:08.474  9839  9905 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-12 16:09:08.474  9839  9905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 16:09:08.474  9839  9905 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 16:09:08.474  9839  9905 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-12 16:09:08.475  9839  9905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 16:09:08.475  9839  9905 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 16:09:08.475  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [00:11:22:33:44:55]
,10-12 16:09:08.481  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-12 16:09:08.482  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
10-12 16:09:08.482  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-12 16:09:08.483  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-12 16:09:08.483  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-12 16:09:08.483  9839  9905 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-12 16:09:08.483  9839  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 195)
10-12 16:09:08.483  9839  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect: mIsShuttingDown = false
10-12 16:09:08.483  9839  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket 1
10-12 16:09:08.483  9839  9905 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 16:09:08.483  9839  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: createBluetoothSocket: given port
,10-12 16:09:08.483  9839  9905 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-12 16:09:08.485  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
10-12 16:09:08.485  9839  9905 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,10-12 16:09:08.488  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
10-12 16:09:08.488  9839  9905 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-12 16:09:08.490  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
10-12 16:09:08.490  9839  9905 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-12 16:09:08.491  9839  9905 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-12 16:09:08.491  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 16:09:08.491  9839  9905 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-12 16:09:08.491  9839  9905 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 16:09:08.491  9839  9905 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-12 16:09:08.491  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 16:09:08.491  9839  9905 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-12 16:09:08.491  9839  9905 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 16:09:08.491  9839  9905 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-12 16:09:08.492  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 16:09:08.492  9839  9905 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,10-12 16:09:08.492  9839  9936 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
10-12 16:09:08.492  9839  9936 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: connecting
,10-12 16:09:08.493  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-12 16:09:08.494  9839  9905 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-12 16:09:08.494  9839  9905 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-12 16:09:08.494  9839  9905 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-12 16:09:08.494  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,10-12 16:09:08.494  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:08.497  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:08.497  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:08.498  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.498  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:08.501  9839  9936 D BluetoothSocket: connect(): myUserId = 0
,10-12 16:09:08.501  9839  9936 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 16:09:08.501  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:08.501  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:08.502  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.502  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 16:09:08.502  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 16:09:08.502  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 16:09:08.502  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 16:09:08.504  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-12 16:09:08.504  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 16:09:08.505  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 16:09:08.505  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 16:09:08.505  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 16:09:08.505  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,10-12 16:09:08.505  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 16:09:08.505  9839  9937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 16:09:08.505  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 16:09:08.505  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 16:09:08.508  9839  9937 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:08.508  9839  9937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 16:09:08.511  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-12 16:09:08.511  9839  9905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 16:09:08.511  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 16:09:08.512  9839  9937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-12 16:09:08.512  9839  9937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@965ddf4, port: 6, type: 1, local socket address: null, socket type: 0
,10-12 16:09:08.514  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.515  3703  3725 D SecContentProvider: insert(), uri = 2
10-12 16:09:08.515  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.516  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.516  3703  3725 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:08.517  4055  4636 W bt_btif : bta_dm_bl_change_cback : reason=0
,10-12 16:09:08.520  4055  4176 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
,10-12 16:09:08.522  9839  9905 D BluetoothAdapter: isSecureModeEnabled
,10-12 16:09:08.522  4055  4067 D BtConfig.SecureMode: isSecureModeOn:false
,10-12 16:09:08.523  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.523  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 16:09:08.525  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.525  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.526  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 16:09:08.526  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 16:09:08.526  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 3
,10-12 16:09:08.529  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.532  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.533  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.533  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 16:09:08.533  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
,10-12 16:09:08.533  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d795b619-8f1d-4c80-8da3-dbe435a7fe11", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-12 16:09:08.533  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 44 78 3E 94 4A 3E
10-12 16:09:08.533  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 16:09:08.534  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:08.534  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.534  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.534  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-12 16:09:08.534  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-12 16:09:08.534  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.535  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.535  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[3, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.536  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.538  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:08.538  9839  9905 D BluetoothAdapter: isSecureModeEnabled
,10-12 16:09:08.538  4055  4068 D BtConfig.SecureMode: isSecureModeOn:false
,10-12 16:09:08.539  9839  9905 D BluetoothLeAdvertiser: start advertising
,10-12 16:09:08.541  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:08.544  4055  4068 D BtGatt.GattService: registerClient() - UUID=9102fe62-c281-407b-aff7-d97db3d9fe33
,10-12 16:09:08.647  4055  4176 D BtGatt.GattService: onClientRegistered() - UUID=9102fe62-c281-407b-aff7-d97db3d9fe33, clientIf=5, status=0
,10-12 16:09:08.647  9839  9850 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-12 16:09:08.649  4055  5721 E BtGatt.ContextMap: Context not found for ID 5
,10-12 16:09:08.650  4055  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-12 16:09:08.650  4055  4570 D BtGatt.AdvertiseManager: message : 0
,10-12 16:09:08.652  4055  4570 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-12 16:09:08.652  4055  4570 D BtGatt.AdvertiseManager: size of list is =0
,10-12 16:09:08.657  4055  4570 D BtGatt.AdvertiseManager: starting advertising
,10-12 16:09:08.659  4055  4570 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-12 16:09:08.661  4055  4636 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-12 16:09:08.670  4055  4176 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 16:09:08.671  4055  4570 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 16:09:08.676  4055  4176 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-12 16:09:08.676  4055  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-12 16:09:08.676  4055  4570 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-12 16:09:08.676  4055  4570 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
,10-12 16:09:08.676  4055  4570 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
,10-12 16:09:08.677  9839  9851 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
10-12 16:09:08.678  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.678  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.678  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-12 16:09:08.679  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.679  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.680  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.680  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.681  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.681  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 16:09:08.683  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 16:09:08.683  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.683  9839  9905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,10-12 16:09:08.686  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.686  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:08.687  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:08.687  9839  9905 I io.jxcore.node.ConnectionHelper: start: OK
10-12 16:09:08.688  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-12 16:09:08.689  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.689  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:08.689  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-12 16:09:08.690  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.690  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.691  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:08.691  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.692  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 16:09:08.692  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 16:09:08.692  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.693  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.693  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.694  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.694  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.699  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.699  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-12 16:09:08.700  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:08.700  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,10-12 16:09:08.701  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 16:09:09.196  9839  9927 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
10-12 16:09:09.197  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 16:09:09.197  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-12 16:09:09.197  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 16:09:09.197  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 16:09:09.198  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 16:09:09.198  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 16:09:09.198  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 16:09:09.198  9839  9937 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 16:09:09.198  9839  9937 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 16:09:09.198  9839  9937 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 16:09:09.199  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 16:09:09.199  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 16:09:09.199  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-12 16:09:09.199  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 16:09:09.200  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 16:09:09.202  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-12 16:09:09.202  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5011656 removed from the list
10-12 16:09:09.202  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5011656 removed from the list
10-12 16:09:09.202  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 16:09:09.203  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 16:09:09.203  9839  9939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 195
10-12 16:09:09.203  9839  9939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
10-12 16:09:09.203  9839  9939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: Trying to close the bluetooth socket... (thread ID: 195)
10-12 16:09:09.204  4055  4752 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 8, channel: 1
10-12 16:09:09.205  9839  9939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: closeBluetoothSocket: bluetooth socket closed (thread ID: 195)
10-12 16:09:09.206  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.206  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-12 16:09:09.207  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-12 16:09:09.207  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:09.208  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.209  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.209  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:09.211  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:09.211  9839  9936 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  connect: read failed, socket might closed or timeout, read ret: -1
,10-12 16:09:09.212  9839  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socket is not connected
10-12 16:09:09.212  9839  9936 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 195)
10-12 16:09:09.213  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:09.213  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-12 16:09:09.215  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:09.216  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:09.216  9839  9905 D BluetoothLeScanner: could not find callback wrapper
10-12 16:09:09.216  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-12 16:09:09.217  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.217  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:09.218  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.218  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-12 16:09:09.218  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:09.220  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:09.221  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:09.222  9839  9905 D BluetoothLeAdvertiser: stop advertising
,10-12 16:09:09.223  4055  4568 E BtGatt.ContextMap: Context not found for ID 5
10-12 16:09:09.223  4055  4570 D BtGatt.AdvertiseManager: message : 1
10-12 16:09:09.223  4055  4584 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
10-12 16:09:09.224  4055  4570 D BtGatt.AdvertiseManager: stop advertise for client =  5
10-12 16:09:09.224  4055  4570 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-12 16:09:09.225  4055  4570 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-12 16:09:09.231  4055  4176 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-12 16:09:09.231  4055  4176 D BtGatt.GattService: Client app is not null!
,10-12 16:09:09.232  9839  9850 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-12 16:09:09.233  4055  4067 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 16:09:09.234  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-12 16:09:09.235  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.235  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 16:09:09.236  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:09.236  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:09.237  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.237  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 16:09:09.237  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-12 16:09:09.238  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 16:09:09.239  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:09.242  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.242  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 16:09:09.242  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:09.243  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:09.243  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c8e6d7 removed from the list
10-12 16:09:09.243  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 16:09:09.243  9839  9905 D io.jxcore.node.ConnectivityMonitor: stop
10-12 16:09:09.243  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-12 16:09:09.244  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 16:09:09.244  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:09.245  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:09.245  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 16:09:09.245  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-12 16:09:09.245  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:09.246  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-12 16:09:09.246  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:09.246  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 16:09:09.748  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 16:09:10.108  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:10.108  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -54
,10-12 16:09:11.836  4646  4646 D io_stats: !@   8,0 r 25649 2266000 w 4672 199984 d 597 73636 f 1901 1901 iot 11350 10670 th 475480 0 0 pt 0 inp 0 0 202.038
,10-12 16:09:12.080  3703  5698 D SSRM:f  : SIOP:: AP = 300, PST = 298 (W:14), CP = 251, CUR = 119, LCD = 57
,10-12 16:09:12.455  3298  3783 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-12 16:09:12.992  3703  4016 D WifiWatchdogStateMachine:  [|211] []
,10-12 16:09:13.129  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-12 16:09:14.246  9839  9928 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,10-12 16:09:14.251  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-12 16:09:14.253  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-12 16:09:14.254  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 16:09:14.258  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 16:09:14.260  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-12 16:09:14.260  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 16:09:14.260  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 16:09:14.260  9839  9941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 16:09:14.261  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 16:09:14.262  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 16:09:14.262  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-12 16:09:14.265  9839  9941 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:14.265  9839  9941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 16:09:14.267  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,10-12 16:09:14.270  9839  9905 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [00:11:22:33:44:55], error message: ErrorMessage
,10-12 16:09:14.271  9839  9905 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-12 16:09:14.272  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 16:09:14.272  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-12 16:09:14.275  9839  9941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-12 16:09:14.275  9839  9941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@290e792, port: 6, type: 1, local socket address: null, socket type: 0
10-12 16:09:14.277  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,10-12 16:09:14.296  9839  9905 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-12 16:09:14.299  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 16:09:14.299  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 16:09:14.299  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 16:09:14.299  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 16:09:14.300  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-12 16:09:14.300  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 16:09:14.300  9839  9941 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 16:09:14.300  9839  9941 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-12 16:09:14.300  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 16:09:14.301  9839  9941 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 16:09:14.301  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-12 16:09:14.302  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 16:09:14.303  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 16:09:14.303  9839  9905 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5011656 not in the list
10-12 16:09:14.303  9839  9905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5011656 not in the list
10-12 16:09:14.303  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 16:09:14.303  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 16:09:14.304  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:14.304  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-12 16:09:14.304  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 16:09:14.305  9839  9905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 16:09:14.305  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-12 16:09:14.305  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:14.309  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:14.309  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 16:09:14.309  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:14.310  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:14.310  9839  9905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c8e6d7 not in the list
,10-12 16:09:14.310  9839  9905 D io.jxcore.node.ConnectivityMonitor: stop
10-12 16:09:14.310  9839  9905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 16:09:14.310  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 16:09:14.310  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-12 16:09:14.310  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 16:09:14.311  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 16:09:14.313  9839  9905 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,10-12 16:09:14.314  9839  9905 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-12 16:09:14.314  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 16:09:14.314  9839  9905 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-12 16:09:14.315  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-12 16:09:14.315  9839  9905 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-12 16:09:14.315  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-12 16:09:14.317  9839  9905 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,10-12 16:09:14.319  9839  9905 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,10-12 16:09:14.321  9839  9905 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,10-12 16:09:14.322  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [incoming]
,10-12 16:09:14.322  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [outgoing]
,10-12 16:09:14.324  9839  9905 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,10-12 16:09:14.325  9839  9905 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-12 16:09:14.325  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-12 16:09:14.326  9839  9905 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-12 16:09:14.326  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 16:09:14.326  9839  9905 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-12 16:09:14.326  9839  9905 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,10-12 16:09:14.328  9839  9905 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,10-12 16:09:14.329  9839  9905 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-12 16:09:14.329  9839  9905 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-12 16:09:14.331  9839  9905 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,10-12 16:09:14.332  9839  9905 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-12 16:09:14.332  9839  9905 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-12 16:09:14.332  9839  9905 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-12 16:09:14.332  9839  9905 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-12 16:09:14.334  9839  9905 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,10-12 16:09:14.336  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 16:09:14.336  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2d4563 added. We now have 2 listener(s)
10-12 16:09:14.336  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2d4563 added. We now have 3 listener(s)
10-12 16:09:14.337  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 16:09:14.340  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:14.340  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-12 16:09:14.340  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:14.341  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 16:09:14.341  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afce560 added. We now have 4 listener(s)
10-12 16:09:14.341  9839  9905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 16:09:14.342  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 16:09:14.348  9839  9905 D BluetoothAdapter: enable()
,10-12 16:09:14.353  4055  5721 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-12 16:09:14.353  4055  5721 D AdapterProvider: query
,10-12 16:09:14.362  4055  5721 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@7b1745b
,10-12 16:09:14.364  4055  5721 D BluetoothAdapterService: updateEvent - already set, update
10-12 16:09:14.364  4055  5721 W BluetoothAdapterService: updateEvent - alreadySet is true
10-12 16:09:14.364  4055  5721 D AdapterProvider: update
10-12 16:09:14.368  4055  5721 E BluetoothAdapterService: updateEvent - update success 1
10-12 16:09:14.370  9839  9905 D BluetoothAdapter: enable(): BT is already enabled..!
,10-12 16:09:14.375  3703  3725 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:09:14.376  3703  3725 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-12 16:09:14.376  3703  3725 D WifiControlHistoryProvider: query
,10-12 16:09:14.382  3703  3725 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-12 16:09:14.383  3703  3725 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:14.384  3703  3725 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-12 16:09:14.387  3703  3725 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-12 16:09:14.388  3703  3725 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-12 16:09:14.390  9839  9905 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,10-12 16:09:14.393  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:14.398  9839  9905 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,10-12 16:09:14.400  9839  9905 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,10-12 16:09:14.402  9839  9905 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,10-12 16:09:14.405  9839  9942 D BluetoothAdapter: disable()
,10-12 16:09:14.410  4055  5721 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : false
,10-12 16:09:14.410  4055  5721 D AdapterProvider: query
,10-12 16:09:14.416  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:14.421  9839  9905 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 16:09:14.422  4055  5721 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@95d4036
,10-12 16:09:14.424  4055  5721 D BluetoothAdapterService: updateEvent - already set, update
10-12 16:09:14.424  4055  5721 W BluetoothAdapterService: updateEvent - alreadySet is true
10-12 16:09:14.424  4055  5721 D AdapterProvider: update
,10-12 16:09:14.433  4055  5721 E BluetoothAdapterService: updateEvent - update success 1
,10-12 16:09:14.439  3703  3797 D SecContentProvider: insert(), uri = 2
,10-12 16:09:14.440  3703  3797 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:14.441  4055  4163 D BluetoothAdapterState: Current state: ON, message: BLE_TURN_OFF
,10-12 16:09:14.443  4055  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-12 16:09:14.443  4055  4163 D BluetoothAdapterService: Bluetooth PBAP supported is true
,10-12 16:09:14.446  4055  4055 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
10-12 16:09:14.447  4055  4163 D BluetoothAdapterService: Autoconnection is available 
10-12 16:09:14.447  4055  4163 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
10-12 16:09:14.447  3703  3797 D BluetoothManagerService: Turning On/Off, G state: 3, S state: 3, mBLE count: 0, s BLE count: 0
10-12 16:09:14.447  4055  4163 D BluetoothAdapterService: terminating service from this receiver
,10-12 16:09:14.454  4069  4069 D BluetoothPbap: Proxy object disconnected
10-12 16:09:14.454  4069  4069 D PbapServerProfile: Bluetooth service disconnected
,10-12 16:09:14.455  4055  4055 D DOWNLOADABLE_DB: onReceive of BR
10-12 16:09:14.455  4055  4055 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
10-12 16:09:14.455  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.455  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:14.464  4055  4163 W bt_btif : btif_dm_cancel_discovery
,10-12 16:09:14.466  3703  4541 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
10-12 16:09:14.467  3703  4541 D SecContentProvider: called from android.uid.bluetooth:1002
10-12 16:09:14.468  3703  4851 D SecContentProvider: insert(), uri = 2
10-12 16:09:14.469  3703  4851 D SecContentProvider: called from android.uid.bluetooth:1002
10-12 16:09:14.471  4069  4296 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:14.471  4069  4296 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
10-12 16:09:14.475  3703  3703 D BluetoothPhoneService: Bluetooth Adapter state : 13
10-12 16:09:14.475  4055  4163 I BluetoothAdapterState: Entering PendingCommandState
,10-12 16:09:14.482  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
10-12 16:09:14.482  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:14.482  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,10-12 16:09:14.493  9839  9839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:14.493  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 16:09:14.495  3703  5217 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{d3cadd8: PendingIntentRecord{cde0531 com.google.android.gms broadcastIntent}}
10-12 16:09:14.496  3703  4873 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4055 / op:PendingIntent{5035416: PendingIntentRecord{50db197 com.android.bluetooth broadcastIntent}}
10-12 16:09:14.497  9839  9839 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 16:09:14.497  9839  9839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
,10-12 16:09:14.497  4055  4176 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
10-12 16:09:14.497  4055  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BEGIN_DISABLE
,10-12 16:09:14.501  4055  4163 E BluetoothServiceJni: disableBrEdrNative:
10-12 16:09:14.501  4055  4163 E bt_btif : disable_bredr
10-12 16:09:14.502  4055  4176 W bt_btif : btif_dm_generic_evt: event=33035
10-12 16:09:14.502  4055  4753 W bt_osi_thread: run_thread: thread id 4753, thread name btif_sock exited
10-12 16:09:14.505  4055  4993 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-12 16:09:14.505  4055  4168 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-12 16:09:14.505  4055  4993 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-12 16:09:14.505  4055  4994 V ObexServerSockets: Accept exception: (expected at shutdown)java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-12 16:09:14.505  4055  4994 D ObexServerSockets: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-12 16:09:14.505  4055  4168 E bt_btif : BTA_DisableBluetoothOnly
10-12 16:09:14.506  4055  4636 W bt_btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
10-12 16:09:14.508  4055  4176 W bt_btif : btif_dm_generic_evt: event=33035
10-12 16:09:14.508  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:14.508  4055  4055 D DOWNLOADABLE_DB: onReceive of BR
10-12 16:09:14.508  4055  4055 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
10-12 16:09:14.508  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.508  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.509  4055  4055 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:14.517  3703  4871 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{4bacf84: PendingIntentRecord{2dcc36d com.google.android.gms broadcastIntent}}
10-12 16:09:14.517  4055  4055 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
10-12 16:09:14.518  4055  4055 D BluetoothSdpJni: SDP Remove record success - handle: 0
10-12 16:09:14.518  4055  4731 D BluetoothSdpJni: sdpRemoveSdpRecordNative:
10-12 16:09:14.518  4055  4731 D BluetoothSdpJni: SDP Remove record success - handle: 1
,10-12 16:09:14.518  4055  4731 D BluetoothMapMasInstance: RemoveSDPrecord returns true
10-12 16:09:14.518  4055  4731 D ObexServerSockets: shutdown(block = true)
10-12 16:09:14.518  4055  4731 D ObexServerSockets: shutdown called from another thread - interrupt().
10-12 16:09:14.518  4055  4731 D ObexServerSockets: shutdown called from another thread - interrupt().
10-12 16:09:14.518  4055  4055 I BtOppRfcommListener: stopping Accept Thread
10-12 16:09:14.518  9115  9115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 16:09:14.519  4055  5521 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-12 16:09:14.520  4055  5521 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-12 16:09:14.518  4055  4176 W bt_btif : btif_dm_generic_evt: event=33035
,10-12 16:09:14.537  4055  4055 V BluetoothOppManager: cleanUp...
10-12 16:09:14.538  4055  4176 W bt_btif : btif_dm_generic_evt: event=33035
10-12 16:09:14.539  4055  4636 W bt_btm  : btm_sec_connected
10-12 16:09:14.540  4055  4636 W bt_btif : bta_dm_bl_change_cback : reason=2
10-12 16:09:14.540  4055  4636 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
10-12 16:09:14.540  4055  4636 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 8
10-12 16:09:14.540  4055  4636 W bt_btif : bta_dm_bl_change_cback : reason=2
10-12 16:09:14.541  4055  4176 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_BUSY_LEVEL_EVT
10-12 16:09:14.541  4055  4176 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
10-12 16:09:14.548  9115  9115 D LocalBluetoothManager: LocalBluetoothManager :: sInstance == null
,10-12 16:09:14.553  4055  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:14.555  4055  4176 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 1
,10-12 16:09:14.557  9115  9115 D LocalBluetoothManager: LocalBluetoothManager :: constructor
10-12 16:09:14.558  9115  9115 D BluetoothEventManager: BluetoothEventManager Constructor :: 
,10-12 16:09:14.564  4069  4296 V BluetoothEventManager: onReceive :: android.bluetooth.device.action.CLASS_CHANGED
,10-12 16:09:14.565  4055  4176 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
10-12 16:09:14.565  4055  4176 E BluetoothRemoteDevices: devicePropertyChangedCallback: bdDevice: 00:11:22:33:44:XX, value is empty for type: 241
,10-12 16:09:14.568  9115  9115 D LocalBluetoothProfileManager: LocalBluetoothProfileManager :: uuid is null
10-12 16:09:14.568  9115  9115 D LocalBluetoothProfileManager: PANU : true
,10-12 16:09:14.580  9115  9115 D BluetoothSap: Create BluetoothSap proxy object
,10-12 16:09:14.586  9115  9115 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-12 16:09:14.586  9115  9115 D LocalBluetoothManager: LocalBluetoothManager :: onInitCallback != null
,10-12 16:09:14.593  9115  9115 D DockEventReceiver: finishStartingService: stopping service
,10-12 16:09:14.600  9115  9115 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,10-12 16:09:14.601  9115  9115 D BluetoothStatusReceiver: AdapterStateChanged :: state = 13
10-12 16:09:14.601  9115  9115 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 16:09:14.602  9115  9115 D PanProfile: Bluetooth service connected
10-12 16:09:14.603  9115  9115 D BluetoothSap: Proxy object connected
10-12 16:09:14.604  9115  9115 D SapProfile: Bluetooth service connected
,10-12 16:09:14.638  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-12 16:09:14.653  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-12 16:09:14.653  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-12 16:09:14.734  4055  4176 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_BT_EVT
10-12 16:09:14.734  4055  4176 E BluetoothAdapterState: stateChangeCallback : 16
10-12 16:09:14.734  4055  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STOPED
,10-12 16:09:14.811  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 16:09:14.819  4055  4163 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:14.820  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,10-12 16:09:14.835  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,10-12 16:09:14.836  4055  4055 D HeadsetService: Received stop request...Stopping profile...
,10-12 16:09:14.840  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.840  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Message sending
10-12 16:09:14.840  4055  4055 D HeadsetService: notifyProfileServiceStateChanged
10-12 16:09:14.841  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,10-12 16:09:14.845  4069  4069 D HeadsetProfile: Bluetooth service disconnected
10-12 16:09:14.845  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
10-12 16:09:14.847  3703  3703 W BluetoothHeadset: Proxy not attached to service
10-12 16:09:14.847  3703  3703 I Telecom : SecBluetoothManager : not single connected gear
10-12 16:09:14.847  3703  3703 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
10-12 16:09:14.847  3703  3703 D BluetoothHeadset: unRegisterMessageListener : 11
10-12 16:09:14.847  3703  3703 W BluetoothHeadset: Proxy not attached to service
10-12 16:09:14.848  3703  3703 I Telecom : SecBluetoothManager : unregister MessageListener
10-12 16:09:14.848  3703  4565 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACY_0
10-12 16:09:14.848  3703  4565 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACY_0
10-12 16:09:14.849  3703  4565 I Telecom : SecBluetoothManager : mBluetoothHeadset is null
10-12 16:09:14.849  3703  4565 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSD->CARSM.pM_DISCONNECT_BLUETOOTH@ACY_0
,10-12 16:09:14.852  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,10-12 16:09:14.852  4055  4055 D A2dpService: Received stop request...Stopping profile...
,10-12 16:09:14.854  4055  4716 D A2dpStateMachine: Exit Disconnected: -1
,10-12 16:09:14.855  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,10-12 16:09:14.855  4055  4055 D Avrcp   : unregisterContentObserver
10-12 16:09:14.857  4055  4055 D Avrcp   : removeOnActiveSessionsChangedListener
10-12 16:09:14.858  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
10-12 16:09:14.858  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.858  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Message sending
10-12 16:09:14.859  4055  4055 D A2dpService: notifyProfileServiceStateChanged
10-12 16:09:14.860  4069  4069 D A2dpProfile: Bluetooth service disconnected
10-12 16:09:14.862  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:14.863  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
10-12 16:09:14.863  4055  4163 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
10-12 16:09:14.863  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Before synchronized
10-12 16:09:14.863  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
10-12 16:09:14.863  4055  4055 V BluetoothAdapterState: isTurningOff()=true
10-12 16:09:14.863  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:14.863  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:14.863  4055  4055 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:14.863  4055  4163 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
10-12 16:09:14.863  4055  4163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
10-12 16:09:14.864  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:14.871  4055  4055 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-12 16:09:14.871  4055  4055 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-12 16:09:14.876  4055  4055 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
,10-12 16:09:14.877  4055  4055 D HidService: Received stop request...Stopping profile...
,10-12 16:09:14.878  4055  4055 D HidService: Stopping Bluetooth HidService
10-12 16:09:14.878  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.878  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Message sending
10-12 16:09:14.878  4055  4055 D HidService: notifyProfileServiceStateChanged
10-12 16:09:14.879  4069  4069 D BluetoothInputDevice: Proxy object disconnected
10-12 16:09:14.879  4069  4069 D HidProfile: Bluetooth service disconnected
,10-12 16:09:14.881  4055  4055 D HealthService: Received stop request...Stopping profile...
,10-12 16:09:14.882  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.882  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Message sending
10-12 16:09:14.882  4055  4055 D HealthService: notifyProfileServiceStateChanged
,10-12 16:09:14.884  4055  4055 D PanService: Received stop request...Stopping profile...
,10-12 16:09:14.890  4055  4055 D EnhancedTetheringManager: stop
,10-12 16:09:14.892  4055  4055 D EnhancedTetheringManager: tetherEnabled : false
10-12 16:09:14.892  4055  4055 D ETMLeHelper: stopAdvertise
10-12 16:09:14.893  4055  4055 D BluetoothAdapter: STATE_TURNING_OFF
10-12 16:09:14.894  4055  4055 D BluetoothAdapter: STATE_TURNING_OFF
10-12 16:09:14.894  4055  4055 D BluetoothLeAdvertiser: stop advertising
10-12 16:09:14.894  4055  4055 D BluetoothLeAdvertiser: wrapper is null
10-12 16:09:14.895  4055  4055 D EnhancedTetheringManager: removeNapWakeAlarm
,10-12 16:09:14.897  3703  4842 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4055 / op:PendingIntent{d083ed9: PendingIntentRecord{47f109e com.android.bluetooth broadcastIntent}}
10-12 16:09:14.898  4055  4055 D EnhancedTetheringManager: cancelFindTetherServer
10-12 16:09:14.898  4055  4055 D ETMLeHelper: stopScan
10-12 16:09:14.899  4055  4055 D BluetoothAdapter: STATE_TURNING_OFF
10-12 16:09:14.899  4055  4055 D BluetoothAdapter: STATE_TURNING_OFF
,10-12 16:09:14.900  4055  4055 D BluetoothLeScanner: could not find callback wrapper
10-12 16:09:14.900  4055  4055 D EnhancedTetheringManager: removePanuWakeAlarm
10-12 16:09:14.902  3703  5217 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4055 / op:PendingIntent{95e677f: PendingIntentRecord{bf4f34c com.android.bluetooth broadcastIntent}}
10-12 16:09:14.903  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.903  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Message sending
10-12 16:09:14.903  4055  4055 D PanService: notifyProfileServiceStateChanged
10-12 16:09:14.904  4069  4069 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 16:09:14.904  4069  4069 D PanProfile: Bluetooth service disconnected
10-12 16:09:14.906  4055  4055 D BluetoothMapService: Received stop request...Stopping profile...
10-12 16:09:14.911  9115  9115 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 16:09:14.911  9115  9115 D PanProfile: Bluetooth service disconnected
,10-12 16:09:14.913  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:14.913  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Message sending
,10-12 16:09:14.913  4055  4055 D BluetoothMapService: notifyProfileServiceStateChanged
10-12 16:09:14.914  4069  4069 D BluetoothMap: Proxy object disconnected
,10-12 16:09:14.914  4069  4069 D MapProfile: Bluetooth service disconnected
,10-12 16:09:14.915  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:14.915  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Before synchronized
10-12 16:09:14.915  4055  4055 V BluetoothAdapterState: isTurningOff()=true
10-12 16:09:14.915  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:14.915  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:14.915  4055  4055 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:14.915  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:14.918  4055  4055 D SapService: Received stop request...Stopping profile...
10-12 16:09:14.918  4055  4055 V SapService: stop()
10-12 16:09:14.919  4055  4717 W bt_osi_thread: run_thread: thread id 4717, thread name media_worker exited
,10-12 16:09:14.921  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.921  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Message sending
10-12 16:09:14.921  4055  4055 D SapService: notifyProfileServiceStateChanged
10-12 16:09:14.924  4069  4069 D BluetoothSap: Proxy object disconnected
10-12 16:09:14.924  9115  9115 D BluetoothSap: Proxy object disconnected
10-12 16:09:14.924  9115  9115 D SapProfile: Bluetooth service disconnected
10-12 16:09:14.924  4069  4069 D SapProfile: Bluetooth service disconnected
10-12 16:09:14.925  4055  4055 D HidDevService: Received stop request...Stopping profile...
10-12 16:09:14.925  4055  4055 D HidDevService: stop()
10-12 16:09:14.925  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.925  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Message sending
10-12 16:09:14.925  4055  4055 D HidDevService: notifyProfileServiceStateChanged
10-12 16:09:14.932  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:14.932  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, Before synchronized
10-12 16:09:14.933  4055  4055 V BluetoothAdapterState: isTurningOff()=true
10-12 16:09:14.933  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:14.933  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:14.933  4055  4055 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:14.933  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.933  4055  4055 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 16:09:14.933  4055  4055 W bt_btif : cleanup: HH disabling or disabled already, status = 0
10-12 16:09:14.933  4055  4055 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-12 16:09:14.934  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:14.934  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, Before synchronized
10-12 16:09:14.934  4055  4055 V BluetoothAdapterState: isTurningOff()=true
10-12 16:09:14.934  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:14.934  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:14.934  4055  4055 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:14.934  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.934  4055  4055 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-12 16:09:14.935  4055  4055 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-12 16:09:14.935  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:14.935  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, Before synchronized
10-12 16:09:14.935  4055  4055 V BluetoothAdapterState: isTurningOff()=true
10-12 16:09:14.935  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:14.935  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:14.935  4055  4055 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:14.936  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.936  4055  4055 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 16:09:14.936  4055  4055 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-12 16:09:14.940  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:14.940  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Before synchronized
10-12 16:09:14.940  4055  4055 V BluetoothAdapterState: isTurningOff()=true
10-12 16:09:14.940  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:14.940  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:14.940  4055  4055 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:14.941  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.941  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:14.941  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=10, Before synchronized
10-12 16:09:14.941  4055  4055 V BluetoothAdapterState: isTurningOff()=true
10-12 16:09:14.941  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:14.941  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:14.941  4055  4055 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:14.942  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.942  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:14.943  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=10, Before synchronized
10-12 16:09:14.943  4055  4055 V BluetoothAdapterState: isTurningOff()=true
10-12 16:09:14.944  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:14.944  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:14.944  4055  4055 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:14.945  4055  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STOPPED
10-12 16:09:14.948  4055  4163 D BtGatt.GattService: getGattService(): returning com.android.bluetooth.gatt.GattService@69b67ee
10-12 16:09:14.948  4055  4163 D BtGatt.GattService: serverDisconnectIncomingConnClients()
10-12 16:09:14.949  4055  4636 W bt_btif : BTA got unregistered event id 32
10-12 16:09:14.949  4055  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 16:09:14.949  4055  4163 D BluetoothAdapterService: Bluetooth PBAP supported is true
10-12 16:09:14.950  3703  4845 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{234ef95: PendingIntentRecord{3c798aa com.google.android.gms broadcastIntent}}
10-12 16:09:14.951  9839  9942 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:14.952  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 16:09:14.954  9839  9942 D BluetoothAdapter: enable()
10-12 16:09:14,.955  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.955  4055  4055 D HidDevService: cleanup()
10-12 16:09:14.955  4055  4055 V BluetoothHidDevServiceJni: cleanupNative enter
10-12 16:09:14.955  4055  4055 I BluetoothHidDevServiceJni: Cleaning up interface
10-12 16:09:14.955  4055  4055 I BluetoothHidDevServiceJni: Cleaning up callback object
10-12 16:09:14.955  4055  4055 V BluetoothHidDevServiceJni: cleanupNative done
10-12 16:09:14.958  4055  4163 D BluetoothAdapterService: Autoconnection is available 
10-12 16:09:14.958  4055  4163 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 15
10-12 16:09:14.958  4055  4163 I BluetoothAdapterState: Entering BleOnState
10-12 16:09:14.960  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:14.962  4055  5721 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-12 16:09:14.962  4055  5721 D AdapterProvider: query
10-12 16:09:14.968  4055  4055 D DOWNLOADABLE_DB: onReceive of BR
10-12 16:09:14.968  4055  4055 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
10-12 16:09:14.968  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.968  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.978  4055  4068 D BluetoothAdapter: onBluetoothStateChange: up=false
10-12 16:09:14.979  9839  9851 D BluetoothAdapter: onBluetoothStateChange: up=false
10-12 16:09:14.979  9839  9851 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-12 16:09:14.979  9839  9851 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
10-12 16:09:14.979  9839  9851 D BluetoothLeAdvertiser: Exit stop advertising
10-12 16:09:14.979  4733  6828 I BeaconBle: Client requested to stop, listener=hjz@b76e99e
10-12 16:09:14.981  9839  9851 D BluetoothAdapter: There are no active google scan apps, stop scan
10-12 16:09:14.981  9839  9851 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
10-12 16:09:14.981  9839  9851 D BluetoothLeScanner: Exiting stopAllScan
10-12 16:09:14.982  4055  5721 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@5b0200e
10-12 16:09:14.982  4069  5977 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 16:09:14.983  4055  5721 D BluetoothAdapterService: updateEvent - already set, update
10-12 16:09:14.983  4055  5721 W BluetoothAdapterService: updateEvent - alreadySet is true
10-12 16:09:14.983  4055  5721 D AdapterProvider: update
10-12 16:09:14.986  4055  5721 E BluetoothAdapterService: updateEvent - update success 1
10-12 16:09:14.993  4055  4064 E System  : Uncaught exception thrown by finalizer
10-12 16:09:14.994  4055  4055 D DOWNLOADABLE_DB: onReceive of BR
10-12 16:09:14.995  4055  4055 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
10-12 16:09:14.995  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:14.995  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:14.998  4055  4064 E System  : java.io.IOException: socket not created
10-12 16:09:14.998  4055  4064 E System  : 	at android.net.LocalSocketImpl.shutdownInput(LocalSocketImpl.java:404)
10-12 16:09:14.998  4055  4064 E System  : 	at android.net.LocalSocket.shutdownInput(LocalSocket.java:207)
10-12 16:09:14.998  4055  4064 E System  : 	at android.bluetooth.BluetoothSocket.close(BluetoothSocket.java:800)
10-12 16:09:14.998  4055  4064 E System  : 	at android.bluetooth.BluetoothSocket.finalize(BluetoothSocket.java:309)
10-12 16:09:14.998  4055  4064 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:222)
10-12 16:09:14.998  4055  4064 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:209)
10-12 16:09:14.998  4055  4064 E System  : 	at java.lang.Thread.run(Thread.java:762)
,10-12 16:09:14.999  4055  4064 E System  : Uncaught exception thrown by finalizer
10-12 16:09:14.999  4055  4064 E System  : java.io.IOException: socket not created
10-12 16:09:14.999  4055  4064 E System  : 	at android.net.LocalSocketImpl.shutdownInput(LocalSocketImpl.java:404)
10-12 16:09:14.999  4055  4064 E System  : 	at android.net.LocalSocket.shutdownInput(LocalSocket.java:207)
10-12 16:09:14.999  4055  4064 E System  : 	at android.bluetooth.BluetoothSocket.close(BluetoothSocket.java:800)
10-12 16:09:14.999  4055  4064 E System  : 	at android.bluetooth.BluetoothSocket.finalize(BluetoothSocket.java:309)
10-12 16:09:14.999  4055  4064 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:222)
10-12 16:09:14.999  4055  4064 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:209)
10-12 16:09:14.999  4055  4064 E System  : 	at java.lang.Thread.run(Thread.java:762)
10-12 16:09:15.000  9115  9127 D BluetoothSap: onBluetoothStateChange: up=false
10-12 16:09:15.001  4733  6828 I BeaconBle: Scan canceled successfully.
10-12 16:09:15.004  9115  9126 D BluetoothPan: onBluetoothStateChange on: false
,10-12 16:09:15.006  3703  4850 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{b5e9576: PendingIntentRecord{813c777 com.google.android.gms broadcastIntent}}
,10-12 16:09:15.006  3703  3941 W ActivityManager: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-12 16:09:15.009  4069  4086 D BluetoothPbap: onBluetoothStateChange: up=false
,10-12 16:09:15.010  3703  3941 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-12 16:09:15.010  3703  3941 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-12 16:09:15.010  3703  3941 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-12 16:09:15.010  3703  3941 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-12 16:09:15.010  3703  3941 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-12 16:09:15.010  3703  3941 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-12 16:09:15.010  3703  3941 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-12 16:09:15.010  3703  3941 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-12 16:09:15.010  3703  3941 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-12 16:09:15.010  3703  3941 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-12 16:09:15.011  4069  4245 D BluetoothPan: onBluetoothStateChange on: false
10-12 16:09:15.013  4769  4788 D BluetoothAdapter: onBluetoothStateChange: up=false
,10-12 16:09:15.013  4769  4788 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-12 16:09:15.014  3703  3941 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,10-12 16:09:15.015  4769  4788 D BluetoothAdapter: There are no active google scan apps, stop scan
10-12 16:09:15.015  3703  3941 D SecContentProvider: called from com.thaliproject.thalitest
10-12 16:09:15.015  4733  6810 W NearbyMessages: NetworkPollManager:  No operations for client(com.google.android.gms#0p:discoverer). It should not be in the tracker.
10-12 16:09:15.015  4733  6810 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
10-12 16:09:15.018  3703  4850 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{1447c4d: PendingIntentRecord{8969302 com.google.android.gms broadcastIntent}}
,10-12 16:09:15.019  4733  6711 D BluetoothAdapter: onBluetoothStateChange: up=false
10-12 16:09:15.019  4733  6711 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-12 16:09:15.020  4733  6711 D BluetoothAdapter: There are no active google scan apps, stop scan
10-12 16:09:15.020  4733  6711 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
10-12 16:09:15.020  4733  6711 D BluetoothLeScanner: Exiting stopAllScan
10-12 16:09:15.021  4069  8161 D BluetoothSap: onBluetoothStateChange: up=false
10-12 16:09:15.022  9115  9127 D BluetoothAdapter: onBluetoothStateChange: up=false
10-12 16:09:15.022  9115  9127 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-12 16:09:15.023  9115  9127 D BluetoothAdapter: There are no active google scan apps, stop scan
10-12 16:09:15.024  4069  4086 D BluetoothMap: onBluetoothStateChange: up=false
10-12 16:09:15.031  4042  4246 D BluetoothAdapter: onBluetoothStateChange: up=false
10-12 16:09:15.031  4042  4246 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-12 16:09:15.032  4042  4246 D BluetoothAdapter: There are no active google scan apps, stop scan
10-12 16:09:15.032  4069  8161 D BluetoothAdapter: onBluetoothStateChange: up=false
10-12 16:09:15.032  4069  8161 D BluetoothAdapter: Bluetooth is turned off, stop adv
,10-12 16:09:15.034  4069  8161 D BluetoothAdapter: There are no active google scan apps, stop scan
,10-12 16:09:15.035  3703  3797 D BluetoothAdapter: onBluetoothStateChange: up=false
10-12 16:09:15.035  3703  3797 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-12 16:09:15.035  3703  3797 D BluetoothAdapter: There are no active google scan apps, stop scan
,10-12 16:09:15.035  9435  9449 D BluetoothAdapter: onBluetoothStateChange: up=false
,10-12 16:09:15.035  9435  9449 D BluetoothAdapter: Bluetooth is turned off, stop adv
10-12 16:09:15.036  9435  9449 D BluetoothAdapter: There are no active google scan apps, stop scan
,10-12 16:09:15.038  4055  4163 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_OFF
,10-12 16:09:15.041  3703  3797 W BluetoothManagerService: BT is in BLE_ON State
,10-12 16:09:15.043  4055  4568 E BluetoothBondStateMachine: initStateMachine
,10-12 16:09:15.044  4069  4296 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:15.044  4069  4296 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,10-12 16:09:15.046  3703  3703 D Telecom : SecBluetoothManager : unregister BluetoothHeadset after STATE_OFF : null
10-12 16:09:15.046  3703  3703 D Telecom : SecBluetoothManager : unRegisterBluetoothHeadsetMessageListener fail
10-12 16:09:15.047  3703  3703 D BluetoothPhoneService: Bluetooth Adapter state : 10
,10-12 16:09:15.051  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
10-12 16:09:15.051  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:15.051  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,10-12 16:09:15.058  9115  9115 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:15.059  9115  9115 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,10-12 16:09:15.061  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:15.063  4055  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 16:09:15.063  4055  4163 D BluetoothAdapterService: Bluetooth PBAP supported is true
10-12 16:09:15.064  4055  4163 D BluetoothAdapterService: Autoconnection is available 
10-12 16:09:15.064  4055  4163 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 16
10-12 16:09:15.064  3703  3797 D BluetoothManagerService: Ble Turning On/Off, G state: 3, S state: 3
10-12 16:09:15.066  3703  4542 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
10-12 16:09:15.068  4055  4055 D DOWNLOADABLE_DB: onReceive of BR
10-12 16:09:15.068  4055  4055 D DOWNLOADABLE_DB: android.bluetooth.adapter.action.BLE_STATE_CHANGED
10-12 16:09:15.068  3703  4873 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{e736413: PendingIntentRecord{9519650 com.google.android.gms broadcastIntent}}
10-12 16:09:15.068  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:15.068  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:15.068  3703  4542 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.070  3703  4180 D SecContentProvider: insert(), uri = 2
10-12 16:09:15.071  3703  4180 D SecContentProvider: called from android.uid.bluetooth:1002
10-12 16:09:15.072  4055  4163 I BluetoothAdapterState: Entering PendingCommandState
10-12 16:09:15.072  4055  4168 E bt_btif : btif_vhci_sock_cleanup
,10-12 16:09:15.073  4055  4636 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 16:09:15.074  4055  4168 I bt_core_module: module_shut_down Shutting down module "btif_config_module"
10-12 16:09:15.075  4055  4176 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
10-12 16:09:15.076  4055  4176 W bt_btif : btif_dm_generic_evt: event=33035
10-12 16:09:15.080  3703  4873 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{5699049: PendingIntentRecord{95edd4e com.google.android.gms broadcastIntent}}
,10-12 16:09:15.081  4055  4055 D DOWNLOADABLE_DB: onReceive of BR
10-12 16:09:15.081  4055  4055 D DOWNLOADABLE_DB: com.samsung.bluetooth.adapter.action.BLE_STATE_CHANGED
10-12 16:09:15.081  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:15.081  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:15.083  4055  4168 I bt_core_module: module_shut_down Shutdown of module "btif_config_module" completed
10-12 16:09:15.083  4055  4176 W bt_btif : btif_dm_generic_evt: event=33035
10-12 16:09:15.083  9115  9115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 16:09:15.084  4055  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: USER_TURN_ON
,10-12 16:09:15.092  4055  4163 I BluetoothAdapterState: Deferring USER_TURN_ON request...
10-12 16:09:15.092  4055  4163 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:15.093  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:15.101  9115  9115 D DockEventReceiver: finishStartingService: stopping service
,10-12 16:09:15.107  9115  9115 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:15.108  9115  9115 D BluetoothStatusReceiver: AdapterStateChanged :: state = 10
,10-12 16:09:15.217  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-12 16:09:15.232  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-12 16:09:15.232  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-12 16:09:15.273  4055  4176 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
,10-12 16:09:15.273  4055  4176 I bt_core_module: module_shut_down Shutting down module "hci_module"
10-12 16:09:15.273  4055  4176 I bt_hci  : shut_down
,10-12 16:09:15.333  4055  4586 D bt_hwcfg: hw_epilog_process
,10-12 16:09:15.338  4055  4586 I bt_vendor: low_power_mode_cb
,10-12 16:09:15.340  5172  6765 I Authzen : [PermitStore] Getting all permits...
,10-12 16:09:15.343  4055  4586 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-12 16:09:15.343  4055  4586 I bt_vendor: epilog_cb
10-12 16:09:15.343  4055  4586 I bt_hci  : epilog_finished_callback
,10-12 16:09:15.346  4055  4586 W bt_osi_thread: run_thread: thread id 4586, thread name hci_thread exited
10-12 16:09:15.347  4055  4176 I bt_hci_h4: hal_close
,10-12 16:09:15.347  4055  4599 W bt_osi_thread: run_thread: thread id 4599, thread name hci_single_chann exited
,10-12 16:09:15.348  4055  4176 I bt_userial_vendor: device fd = 96 close
10-12 16:09:15.349  4055  4176 I bt_upio : upio_set_bluetooth_power(on: 0)
10-12 16:09:15.352  4055  4176 I bt_core_module: module_shut_down Shutdown of module "hci_module" completed
10-12 16:09:15.353  4055  4176 I bt_core_module: module_shut_down Shutting down module "btsnoop_module"
10-12 16:09:15.353  4055  4176 I bt_core_module: module_shut_down Shutdown of module "btsnoop_module" completed
10-12 16:09:15.353  4055  4176 I bt_core_module: module_clean_up Cleaning up module "bte_logmsg_module"
10-12 16:09:15.353  4055  4176 I bt_core_module: module_clean_up Cleanup of module "bte_logmsg_module" completed
10-12 16:09:15.354  4055  4636 W bt_osi_thread: run_thread: thread id 4636, thread name bt_workqueue exited
10-12 16:09:15.355  4055  4168 I bt_core_module: module_shut_down Shutting down module "controller_module"
10-12 16:09:15.355  4055  4168 I bt_core_module: module_shut_down Shutdown of module "controller_module" completed
10-12 16:09:15.355  4055  4176 E BluetoothAdapterState: stateChangeCallback : 0
10-12 16:09:15.355  4055  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: DISABLED
,10-12 16:09:15.368  4055  4055 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 16:09:15.369  4055  4163 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-12 16:09:15.369  4055  4055 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 16:09:15.369  4055  4055 D BtGatt.GattService: stop()
,10-12 16:09:15.370  4055  4055 D BtGatt.GattService: cleanup binder
,10-12 16:09:15.370  4055  4055 D BtGatt.AdvertiseManager: advertise clients cleared
10-12 16:09:15.370  4055  4055 D BtGatt.ScanManager: cleanup
10-12 16:09:15.371  3703  3922 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :4055 / op:PendingIntent{a6dff81: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:15.373  4055  4055 D BtGatt.ScanManager: cleanup handler
,10-12 16:09:15.375  4055  4055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:15.375  4055  4055 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Message sending
10-12 16:09:15.375  4055  4055 D BtGatt.GattService: notifyProfileServiceStateChanged
10-12 16:09:15.377  4055  4055 E BluetoothAdapterService: handleMessage() - Message: 1
,10-12 16:09:15.378  4055  4055 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, Before synchronized
,10-12 16:09:15.378  4055  4055 V BluetoothAdapterState: isTurningOff()=false
10-12 16:09:15.378  4055  4055 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:15.378  4055  4055 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:15.378  4055  4055 V BluetoothAdapterState: isBleTurningOff()=true
10-12 16:09:15.378  4055  4163 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STOPPED
,10-12 16:09:15.380  4055  4163 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-12 16:09:15.380  4055  4163 D BluetoothAdapterService: Bluetooth PBAP supported is true
10-12 16:09:15.381  4055  4163 D BluetoothAdapterService: Autoconnection is available 
10-12 16:09:15.381  4055  4163 D BluetoothAdapterService: updateAdapterState prevState = 16newState = 10
10-12 16:09:15.381  3703  3797 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-12 16:09:15.381  4055  4163 I BluetoothAdapterState: Entering OffState
,10-12 16:09:15.386  4055  4163 D BluetoothAdapterState: Current state: OFF, message: USER_TURN_ON
,10-12 16:09:15.394  4055  4055 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-12 16:09:15.394  4055  4055 W BluetoothSdpJni: Cleaning up Bluetooth SDP object
10-12 16:09:15.394  3703  5217 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{84f7c67: PendingIntentRecord{698a14 com.google.android.gms broadcastIntent}}
10-12 16:09:15.394  4055  4168 E BluetoothServiceJni: Callback env check fail: env: 0x0, callback: 0xd81d6910
10-12 16:09:15.394  4055  4168 E BluetoothServiceJni: Callback: 'callback_thread_event' is not called on the correct thread
10-12 16:09:15.394  4055  4176 W bt_btif : btif_dm_generic_evt: event=33035
10-12 16:09:15.395  4055  4176 E bt_btif_dm: ### ASSERT : system/bt/btif/src/btif_dm.c line 2983 Callback is NULL (0) ###
10-12 16:09:15.395  4055  4176 W bt_osi_thread: run_thread: thread id 4176, thread name bt_jni_workqueue exited
10-12 16:09:15.396  4055  4168 I bt_core_module: module_clean_up Cleaning up module "stack_config_module"
10-12 16:09:15.396  4055  4168 I bt_core_module: module_clean_up Cleanup of module "stack_config_module" completed
10-12 16:09:15.396  4055  4168 I bt_core_module: module_clean_up Cleaning up module "interop_module"
,10-12 16:09:15.396  4055  4168 I bt_core_module: module_clean_up Cleanup of module "interop_module" completed
10-12 16:09:15.396  4055  4168 I bt_core_module: module_clean_up Cleaning up module "btif_config_module"
,10-12 16:09:15.406  4055  4168 I bt_core_module: module_clean_up Cleanup of module "btif_config_module" completed
,10-12 16:09:15.406  4055  4168 I bt_core_module: module_clean_up Cleaning up module "bt_utils_module"
10-12 16:09:15.406  4055  4168 I bt_core_module: module_clean_up Cleanup of module "bt_utils_module" completed
10-12 16:09:15.406  4055  4168 I bt_core_module: module_clean_up Cleaning up module "osi_module"
10-12 16:09:15.407  4055  4175 D bt_osi_alarm: callback_dispatch Callback thread exited
10-12 16:09:15.407  4055  4175 W bt_osi_thread: run_thread: thread id 4175, thread name alarm_dispatcher exited
10-12 16:09:15.408  4055  4174 W bt_osi_thread: run_thread: thread id 4174, thread name alarm_default_ca exited
10-12 16:09:15.408  4055  4168 I bt_core_module: module_clean_up Cleanup of module "osi_module" completed
10-12 16:09:15.408  4055  4055 I BluetoothServiceJni: cleanupNative: return from cleanup
10-12 16:09:15.408  4055  4055 D DOWNLOADABLE_DB: cleanup
10-12 16:09:15.413  4733  6810 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
10-12 16:09:15.417  4055  4055 I art     : System.exit called, status: 0
10-12 16:09:15.417  4055  4055 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-12 16:09:15.442  3703  4845 I ActivityManager: Process com.android.bluetooth (pid 4055) has died(71,1803)
10-12 16:09:15.442  3703  4845 D ActivityManager: cleanUpApplicationRecord -- 4055
,10-12 16:09:15.444  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:15.522  9839  9942 D BluetoothAdapter: enable()
,10-12 16:09:15.539  3703  4871 W ActivityManager: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-12 16:09:15.541  3703  4871 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-12 16:09:15.541  3703  4871 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-12 16:09:15.541  3703  4871 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-12 16:09:15.541  3703  4871 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-12 16:09:15.541  3703  4871 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-12 16:09:15.541  3703  4871 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-12 16:09:15.541  3703  4871 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-12 16:09:15.541  3703  4871 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-12 16:09:15.541  3703  4871 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-12 16:09:15.541  3703  4871 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-12 16:09:15.544  3703  4871 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,10-12 16:09:15.546  3703  4871 D SecContentProvider: called from com.thaliproject.thalitest
,10-12 16:09:15.556  3703  3797 D MountService: getExternalStorageMountMode : 3
10-12 16:09:15.556  3703  3797 D MountService: getExternalStorageMountMode : 3
10-12 16:09:15.556  3703  3797 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 1002, packageName : com.android.bluetooth
,10-12 16:09:15.601  9969  9969 E Zygote  : v2
,10-12 16:09:15.601  9969  9969 I libpersona: KNOX_SDCARD checking this for 1002
10-12 16:09:15.601  9969  9969 I libpersona: KNOX_SDCARD not a persona
,10-12 16:09:15.602  9969  9969 E Zygote  : accessInfo : 0
10-12 16:09:15.603  3703  3797 I ActivityManager: Start proc 9969:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-12 16:09:15.614  9969  9969 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:15.615  9969  9969 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.android.bluetooth 
,10-12 16:09:15.641  9969  9969 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:15.641  9969  9969 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:15.644  3703  3941 I ActivityManager: DSS on for com.android.bluetooth and scale is 1.0
,10-12 16:09:15.715  9969  9969 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,10-12 16:09:15.721  9969  9969 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:15.731  9969  9969 I HeadsetProvider: onCreate
,10-12 16:09:15.747  9969  9969 D BtSettings.ProfileConfig: Adding GattService
10-12 16:09:15.747  9969  9969 D BtSettings.ProfileConfig: Adding HeadsetService
10-12 16:09:15.747  9969  9969 D BtSettings.ProfileConfig: Adding A2dpService
10-12 16:09:15.748  9969  9969 D BtSettings.ProfileConfig: Adding HidService
10-12 16:09:15.748  9969  9969 D BtSettings.ProfileConfig: Adding HealthService
10-12 16:09:15.748  9969  9969 D BtSettings.ProfileConfig: Adding PanService
10-12 16:09:15.748  9969  9969 D BtSettings.ProfileConfig: Adding BluetoothMapService
10-12 16:09:15.748  9969  9969 D BtSettings.ProfileConfig: Adding SapService
10-12 16:09:15.748  9969  9969 D BtSettings.ProfileConfig: Adding HeadsetClientService
10-12 16:09:15.748  9969  9969 D BtSettings.ProfileConfig: Adding A2dpSinkService
10-12 16:09:15.748  9969  9969 D BtSettings.ProfileConfig: Adding HidDevService
10-12 16:09:15.748  9969  9969 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,10-12 16:09:15.757  3703  4541 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.759  3703  4541 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.764  3703  4872 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.766  3703  4872 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.770  3703  4850 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.771  3703  4850 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.774  3703  4842 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.775  3703  4842 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.777  3703  3920 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.778  3703  3920 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.780  3703  4873 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.781  3703  4873 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.783  3703  3725 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.784  3703  3725 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.786  3703  4543 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
10-12 16:09:15.787  3703  4543 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.789  3703  4851 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.790  3703  4851 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.792  3703  3724 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.793  3703  3724 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.795  3703  4845 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:15.796  3703  4845 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:15.884  9969  9969 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 16:09:15.887  9969  9983 I BluetoothAdapterState: Entering OffState
,10-12 16:09:15.891  9969  9985 W bt_osi_thread: run_thread: thread id 9985, thread name stack_manager started
,10-12 16:09:15.892  9969  9985 I bt_core_module: module_init Initializing module "osi_module"
10-12 16:09:15.892  9969  9985 I bt_core_module: module_init Initialized module "osi_module"
10-12 16:09:15.892  9969  9985 I bt_core_module: module_init Initializing module "bt_utils_module"
10-12 16:09:15.892  9969  9985 I bt_core_module: module_init Initialized module "bt_utils_module"
10-12 16:09:15.892  9969  9985 I bt_core_module: module_init Initializing module "btif_config_module"
,10-12 16:09:15.893  9969  9988 W bt_osi_thread: run_thread: thread id 9988, thread name alarm_default_ca started
10-12 16:09:15.894  9969  9989 W bt_osi_thread: run_thread: thread id 9989, thread name alarm_dispatcher started
10-12 16:09:15.894  9969  9985 I bt_core_module: module_init Initialized module "btif_config_module"
10-12 16:09:15.894  9969  9985 I bt_core_module: module_init Initializing module "interop_module"
10-12 16:09:15.894  9969  9985 I bt_core_module: module_init Initialized module "interop_module"
10-12 16:09:15.894  9969  9985 I bt_core_module: module_init Initializing module "stack_config_module"
,10-12 16:09:15.896  9969  9985 I bt_core_module: module_init Initialized module "stack_config_module"
,10-12 16:09:15.897  9969  9990 W bt_osi_thread: run_thread: thread id 9990, thread name bt_jni_workqueue started
10-12 16:09:15.897  9969  9969 I bt_osi_wakelock: wakelock_set_os_callouts set to non-native
,10-12 16:09:15.898  9969  9969 W bt_btif : btif_get_adapter_property 2
10-12 16:09:15.898  9969  9969 W bt_btif : btif_get_adapter_property 1
,10-12 16:09:15.900  9969  9990 E BluetoothServiceJni: populateRssiValuesNative
10-12 16:09:15.900  9969  9990 I bt_btif : getModelRssiValues
10-12 16:09:15.900  9969  9990 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
,10-12 16:09:15.901  9969  9969 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,10-12 16:09:15.903  9969  9969 D BluetoothAdapterService: makeHashMapAvPerformance: Loading from conf
,10-12 16:09:15.920  3703  3797 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,10-12 16:09:15.924  9969  9981 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-12 16:09:15.924  9969  9983 D BluetoothAdapterState: Current state: OFF, message: BLE_TURN_ON
10-12 16:09:15.925  9969  9981 D AdapterProvider: query
,10-12 16:09:15.929  9969  9983 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-12 16:09:15.929  9969  9983 D BluetoothAdapterService: Bluetooth PBAP supported is true
10-12 16:09:15.930  9969  9983 D BluetoothAdapterService: Autoconnection is available 
10-12 16:09:15.930  9969  9983 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 14
10-12 16:09:15.931  9969  9983 D BluetoothAdapterState: Set Downloadbale DB
10-12 16:09:15.931  9969  9983 D DOWNLOADABLE_DB: initBluetoothDatabase
10-12 16:09:15.931  3703  3797 D BluetoothManagerService: Ble Turning On/Off, G state: 0, S state: 0
10-12 16:09:15.932  9969  9983 D DOWNLOADABLE_DB: initBroadcastReceiver
,10-12 16:09:15.935  9969  9983 D DOWNLOADABLE_DB: cleanupLooper
10-12 16:09:15.935  9969  9983 D DOWNLOADABLE_DB: quit init handler
,10-12 16:09:15.941  9969  9981 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@2310833
,10-12 16:09:15.942  9969  9981 D BluetoothAdapterService: updateEvent - already set, update
,10-12 16:09:15.943  9969  9981 W BluetoothAdapterService: updateEvent - alreadySet is true
10-12 16:09:15.943  9969  9981 D AdapterProvider: update
,10-12 16:09:15.948  9969  9981 E BluetoothAdapterService: updateEvent - update success 1
,10-12 16:09:15.954  9969  9983 D DOWNLOADABLE_DB: verifyPolicyVersion
,10-12 16:09:15.958  3703  4842 D MountService: getExternalStorageMountMode : 1
10-12 16:09:15.958  3703  4842 D MountService: getExternalStorageMountMode : 3
10-12 16:09:15.958  3703  4842 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10135, packageName : com.samsung.android.sm.policy
,10-12 16:09:15.983  9993  9993 E Zygote  : v2
10-12 16:09:15.983  9993  9993 I libpersona: KNOX_SDCARD checking this for 10135
10-12 16:09:15.983  9993  9993 I libpersona: KNOX_SDCARD not a persona
,10-12 16:09:15.985  9993  9993 E Zygote  : accessInfo : 0
,10-12 16:09:15.991  3703  4842 I ActivityManager: Start proc 9993:com.samsung.android.sm.policy/u0a135 for content provider com.samsung.android.sm.policy/.db.PolicyClientProvider
,10-12 16:09:15.995  9993  9993 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:15.997  9993  9993 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.policy 
,10-12 16:09:16.035  9993  9993 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:16.037  9993  9993 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:16.040  3703  4873 I ActivityManager: DSS on for com.samsung.android.sm.policy and scale is 1.0
,10-12 16:09:16.052  9839  9942 D BluetoothAdapter: enable()
,10-12 16:09:16.060  9969  9980 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,10-12 16:09:16.061  9969  9980 D AdapterProvider: query
,10-12 16:09:16.070  9969  9980 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@6bae31c
,10-12 16:09:16.072  9969  9980 D BluetoothAdapterService: updateEvent - already set, update
,10-12 16:09:16.073  9969  9980 W BluetoothAdapterService: updateEvent - alreadySet is true
,10-12 16:09:16.074  9969  9980 D AdapterProvider: update
10-12 16:09:16.078  9969  9980 E BluetoothAdapterService: updateEvent - update success 1
,10-12 16:09:16.080  3703  4850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
10-12 16:09:16.081  3703  4850 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:09:16.081  3703  4850 D BatteryService: online:4, current avg:133, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:182
10-12 16:09:16.081  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:09:16.084  9993  9993 W System  : ClassLoader referenced unknown path: /system/app/SCPMClient_N/lib/arm64
,10-12 16:09:16.087  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-12 16:09:16.087  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:09:16.090  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:09:16.092  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,10-12 16:09:16.092  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
10-12 16:09:16.097  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
10-12 16:09:16.099  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
10-12 16:09:16.099  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:09:16.104  9993  9993 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:16.114  3703  4542 W ActivityManager: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-12 16:09:16.115  3703  4542 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-12 16:09:16.115  3703  4542 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-12 16:09:16.115  3703  4542 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-12 16:09:16.115  3703  4542 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-12 16:09:16.115  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-12 16:09:16.115  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-12 16:09:16.115  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-12 16:09:16.115  3703  4542 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-12 16:09:16.115  3703  4542 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-12 16:09:16.115  3703  4542 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
10-12 16:09:16.117  3703  4542 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
10-12 16:09:16.118  3703  4542 D SecContentProvider: called from com.thaliproject.thalitest
10-12 16:09:16.118  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:09:16.147  9969  9983 D DOWNLOADABLE_DB: Local DB version is = 20160428 SCPM Client DB version is= 20160428
,10-12 16:09:16.147  9969  9983 D DOWNLOADABLE_DB: latest polices have already been updated for BT_HFP
,10-12 16:09:16.150  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-12 16:09:16.159  9969  9983 D DOWNLOADABLE_DB: verifyPolicyVersion
,10-12 16:09:16.174  9969  9983 D DOWNLOADABLE_DB: Local DB version is = 20160617 SCPM Client DB version is= 20160617
,10-12 16:09:16.174  9969  9983 D DOWNLOADABLE_DB: latest polices have already been updated for BT_BLE
,10-12 16:09:16.187  9969  9983 D DOWNLOADABLE_DB: verifyPolicyVersion
,10-12 16:09:16.205  9969  9983 D DOWNLOADABLE_DB: Local DB version is = 201612050001 SCPM Client DB version is= 201612050001
10-12 16:09:16.205  9969  9983 D DOWNLOADABLE_DB: latest polices have already been updated for BT_A2DP
,10-12 16:09:16.215  9969  9983 D BluetoothSecureManager: getInstant: null
10-12 16:09:16.216  9969  9983 D BluetoothSecureManager: calling getMethod for getService
10-12 16:09:16.216  9969  9983 D BluetoothSecureManager: calling getService
,10-12 16:09:16.218  9969  9983 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2da14fa
,10-12 16:09:16.219  3703  4543 D BluetoothSecureManagerService: isSecureModeEnabled
10-12 16:09:16.220  3703  4543 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,10-12 16:09:16.220  9969  9983 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:16.220  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,10-12 16:09:16.222  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
10-12 16:09:16.222  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,10-12 16:09:16.223  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
10-12 16:09:16.223  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,10-12 16:09:16.224  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,10-12 16:09:16.225  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,10-12 16:09:16.226  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
10-12 16:09:16.226  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
10-12 16:09:16.227  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
10-12 16:09:16.228  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,10-12 16:09:16.229  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
10-12 16:09:16.229  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,10-12 16:09:16.231  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
10-12 16:09:16.231  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
,10-12 16:09:16.232  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.sap.SapService
10-12 16:09:16.232  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
10-12 16:09:16.234  9969  9983 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,10-12 16:09:16.234  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,10-12 16:09:16.235  9969  9983 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
10-12 16:09:16.235  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,10-12 16:09:16.237  9969  9983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidDevService
,10-12 16:09:16.238  9969  9983 D BluetoothBondStateMachine: make
,10-12 16:09:16.240  9969 10007 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 16:09:16.249  9969  9983 I BluetoothAdapterState: Entering PendingCommandState
,10-12 16:09:16.251  9969  9969 I BtGatt.JNI: classInitNative(L979): classInitNative: Success!
,10-12 16:09:16.258  9969  9969 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 16:09:16.260  9969  9969 D BtGatt.GattService: Received start request. Starting profile...
10-12 16:09:16.260  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:16.260  9969  9969 D BtGatt.GattService: start()
,10-12 16:09:16.262  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:16.262  9969  9969 D BtGatt.AdvertiseManager: advertise manager created
10-12 16:09:16.262  9969  9969 D BtGatt.AdvertiseManager: start
,10-12 16:09:16.268  9969  9969 D BtGatt.ScanManager: start
,10-12 16:09:16.294  9969  9969 D BtGatt.GattService: setGattService(): set to: com.android.bluetooth.gatt.GattService@77ed9dd
10-12 16:09:16.294  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:16.294  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:16.294  9969  9969 D BtGatt.GattService: refreshAbusiveScanPackages
,10-12 16:09:16.295  9969  9969 D DOWNLOADABLE_DB: getAbuseScanPackages
,10-12 16:09:16.303  9969  9969 D BtGatt.GattService: refreshAbusiveScanValue()
,10-12 16:09:16.304  9969  9969 D DOWNLOADABLE_DB: getAbuseMaxScanCount
,10-12 16:09:16.311  9969  9969 D DOWNLOADABLE_DB: getAbuseAccumulatedScanTime
,10-12 16:09:16.319  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:16.319  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Message sending
10-12 16:09:16.319  9969  9969 D BtGatt.GattService: notifyProfileServiceStateChanged
,10-12 16:09:16.321  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:16.321  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, Before synchronized
10-12 16:09:16.321  9969  9969 V BluetoothAdapterState: isTurningOff()=false
,10-12 16:09:16.321  9969  9969 V BluetoothAdapterState: isTurningOn()=false
10-12 16:09:16.322  9969  9969 V BluetoothAdapterState: isBleTurningOn()=true
10-12 16:09:16.322  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 16:09:16.322  9969  9983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BLE_STARTED
,10-12 16:09:16.328  9969  9985 I bt_core_module: module_start_up Starting module "btif_config_module"
10-12 16:09:16.328  9969  9985 I bt_core_module: module_start_up Started module "btif_config_module"
10-12 16:09:16.328  9969  9985 I bt_core_module: module_start_up Starting module "btsnoop_module"
10-12 16:09:16.328  9969  9985 I bt_core_module: module_start_up Started module "btsnoop_module"
10-12 16:09:16.328  9969  9985 I bt_core_module: module_start_up Starting module "hci_module"
10-12 16:09:16.328  9969  9985 I bt_hci  : start_up
10-12 16:09:16.328  9969  9990 W bt_btif : btif_dm_generic_evt: event=33035
,10-12 16:09:16.329  9969 10021 W bt_osi_thread: run_thread: thread id 10021, thread name hci_thread started
,10-12 16:09:16.336  9969  9985 I bt_vendor: alloc value 0xc5379d35
10-12 16:09:16.336  9969  9985 I bt_vendor: init
10-12 16:09:16.336  9969  9985 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 16:09:16.336  9969  9985 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
10-12 16:09:16.336  9969  9985 I bt_upio : upio_set_bluetooth_power(on: 0)
,10-12 16:09:16.338  9969  9985 I bt_upio : upio_set_bluetooth_power(on: 1)
,10-12 16:09:16.447  9969  9985 D bt_hci  : start_up starting async portion
10-12 16:09:16.448  9969 10021 I bt_hci  : event_finish_startup
10-12 16:09:16.448  9969 10021 I bt_hci_h4: hal_open
10-12 16:09:16.448  9969 10021 I bt_userial_vendor: userial vendor open: opening /dev/ttySAC1
,10-12 16:09:16.451  9969 10021 I bt_userial_vendor: userial_vendor_open():UART is setup
,10-12 16:09:16.451  9969 10021 I bt_userial_vendor: device fd = 95 open
,10-12 16:09:16.452  9969 10024 W bt_osi_thread: run_thread: thread id 10024, thread name hci_single_chann started
10-12 16:09:16.453  9969 10021 E bt_hwcfg: Start CFG HW, HCI reset
,10-12 16:09:16.463  9969 10021 E bt_hwcfg: Read Local Name after HCI reset
,10-12 16:09:16.488  9969 10021 D bt_hwcfg: Chipset BCM4359C0
10-12 16:09:16.489  9969 10021 D bt_hwcfg: Target name = [BCM4359C0]
10-12 16:09:16.489  9969 10021 I bt_hwcfg: module_type[semco_b90s_c0].
,10-12 16:09:16.490  9969 10021 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
10-12 16:09:16.490  9969 10021 E bt_hwcfg: ORG patchram base 0092
,10-12 16:09:16.490  9969 10021 E bt_hwcfg: ORG patchram minor 0143
10-12 16:09:16.490  9969 10021 E bt_hwcfg: fw ver (org)92.143
10-12 16:09:16.490  9969 10021 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4359C0_V0092.0143_semco.hcd
,10-12 16:09:16.499  9969 10021 I bt_hwcfg: Axi patch failure or not include AXI patching
,10-12 16:09:16.501  9969 10021 I bt_hwcfg: bt vendor lib baud_1: set UART baud 3000000
,10-12 16:09:16.624  9839  9942 D BluetoothAdapter: enable()
,10-12 16:09:16.636  9969  9981 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,10-12 16:09:16.637  9969  9981 D AdapterProvider: query
,10-12 16:09:16.653  9969  9981 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@727a89e
,10-12 16:09:16.661  9969  9981 D BluetoothAdapterService: updateEvent - already set, update
,10-12 16:09:16.661  9969  9981 W BluetoothAdapterService: updateEvent - alreadySet is true
,10-12 16:09:16.661  9969  9981 D AdapterProvider: update
,10-12 16:09:16.665  9969  9981 E BluetoothAdapterService: updateEvent - update success 1
,10-12 16:09:16.675  3703  4542 W ActivityManager: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-12 16:09:16.676  3703  4542 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-12 16:09:16.676  3703  4542 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-12 16:09:16.676  3703  4542 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-12 16:09:16.676  3703  4542 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-12 16:09:16.676  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-12 16:09:16.676  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-12 16:09:16.676  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-12 16:09:16.676  3703  4542 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-12 16:09:16.676  3703  4542 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
,10-12 16:09:16.676  3703  4542 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-12 16:09:16.678  3703  4542 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
10-12 16:09:16.680  3703  4542 D SecContentProvider: called from com.thaliproject.thalitest
,10-12 16:09:16.840  4646  4646 D io_stats: !@   8,0 r 25744 2272220 w 4752 201388 d 617 73736 f 1934 1934 iot 11550 10759 th 473916 0 0 pt 0 inp 0 0 207.043
,10-12 16:09:17.052  9969 10021 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-12 16:09:17.053  9969 10021 I bt_hwcfg: FW Download delta = 589385
10-12 16:09:17.053  9969 10021 D bt_hwcfg: Settlement delay -- 100 ms
10-12 16:09:17.053  9969 10021 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 16:09:17.181  9969 10021 I bt_hwcfg: bt vendor lib baud_2: set UART baud 3000000
,10-12 16:09:17.185  9839  9942 D BluetoothAdapter: enable()
,10-12 16:09:17.196  9969  9981 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
,10-12 16:09:17.197  9969  9981 D AdapterProvider: query
,10-12 16:09:17.213  9969  9981 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@b086795
10-12 16:09:17.216  9969  9981 D BluetoothAdapterService: updateEvent - already set, update
10-12 16:09:17.217  9969  9981 W BluetoothAdapterService: updateEvent - alreadySet is true
10-12 16:09:17.218  9969  9981 D AdapterProvider: update
,10-12 16:09:17.224  9969  9981 E BluetoothAdapterService: updateEvent - update success 1
,10-12 16:09:17.232  3703  4542 W ActivityManager: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-12 16:09:17.233  3703  4542 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-12 16:09:17.233  3703  4542 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-12 16:09:17.233  3703  4542 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-12 16:09:17.233  3703  4542 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-12 16:09:17.233  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-12 16:09:17.233  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-12 16:09:17.233  3703  4542 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-12 16:09:17.233  3703  4542 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-12 16:09:17.233  3703  4542 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-12 16:09:17.233  3703  4542 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-12 16:09:17.236  3703  4542 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,10-12 16:09:17.239  3703  4542 D SecContentProvider: called from com.thaliproject.thalitest
,10-12 16:09:17.283  9969 10021 I bt_hwcfg: vendor lib fwcfg completed
10-12 16:09:17.283  9969 10021 I bt_vendor: firmware callback
10-12 16:09:17.283  9969 10021 I bt_hci  : firmware_config_callback
10-12 16:09:17.284  9969  9985 I bt_core_module: module_start_up Started module "hci_module"
,10-12 16:09:17.284  9969 10025 W bt_osi_thread: run_thread: thread id 10025, thread name bt_workqueue started
,10-12 16:09:17.286  9969 10025 I bt_core_module: module_init Initializing module "bte_logmsg_module"
,10-12 16:09:17.286  9969 10025 I bt_core_module: module_init Initialized module "bte_logmsg_module"
,10-12 16:09:17.286  9969  9990 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,10-12 16:09:17.289  3112  3112 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9969
10-12 16:09:17.289  3112  3112 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
10-12 16:09:17.289  9969  9990 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
10-12 16:09:17.289  9969  9990 W bt_btif : get_secure_storage_key - ss_is_supported = 1
10-12 16:09:17.289  9969  9990 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
10-12 16:09:17.289  9969  9990 W bt_btif : btif_dm_generic_evt: event=33035
10-12 16:09:17.290  3112  3112 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,10-12 16:09:17.292  9969  9990 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,10-12 16:09:17.292  3112  3112 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1002, gid 1002, pid 9969
10-12 16:09:17.293  3112  3112 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,10-12 16:09:17.492  3112  3112 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,10-12 16:09:17.494  9969  9990 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,10-12 16:09:17.495  9969 10026 W bt_osi_thread: run_thread: thread id 10026, thread name module_wrapper started
10-12 16:09:17.496  9969 10026 I bt_core_module: module_start_up Starting module "controller_module"
,10-12 16:09:17.596  9969 10026 I bt_core_module: module_start_up Started module "controller_module"
,10-12 16:09:17.597  9969 10026 W bt_osi_thread: run_thread: thread id 10026, thread name module_wrapper exited
,10-12 16:09:17.658  9969  9990 W bt_btif : btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,10-12 16:09:17.666  9969  9990 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
10-12 16:09:17.667  9969  9990 W bt_btif : btif_dm_generic_evt: event=33035
,10-12 16:09:17.669  9969  9990 D bt_hci  : do_postload posting postload work item
,10-12 16:09:17.670  9969 10021 I bt_hci  : event_postload
10-12 16:09:17.670  9969  9990 E bt_btif_sock: btif_sock_init: !vhci_init
10-12 16:09:17.670  9969 10021 D bt_hwcfg: hw_sco_config
10-12 16:09:17.670  9969  9990 E bt_btif : ## init_cmd_fd assert ts[h].cmd_fdr == -1 && ts[h].cmd_fdw == -1 failed at line:227 ##
10-12 16:09:17.670  9969 10021 I bt_hwcfg: I2SPCM config {0x1, 0x0, 0x0, 0x1}
10-12 16:09:17.670  9969 10021 I bt_vendor: sco_config_cb
10-12 16:09:17.670  9969 10021 I bt_hci  : sco_config_callback postload finished.
,10-12 16:09:17.672  9969  9990 I         : iop_db_open: iop_db_open status 0
,10-12 16:09:17.673  9969  9990 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  14 , val : 15
,10-12 16:09:17.673  9969  9990 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  15 , val : 8
10-12 16:09:17.673  9969  9990 D BluetoothDataManager: updateLocalInfo for int is called!!!type :  16 , val : 24838
,10-12 16:09:17.673  9969  9990 D BluetoothDataManager: UpdateLocalInfo for String is called!!! type : 17, val : BCM4359C0 Grace SWB-B90S eLNA-0092
10-12 16:09:17.673  9969  9990 D BluetoothDataManager: firmwareVersion from Property : bcm4359C0_V0092.0143_semco.hcd
,10-12 16:09:17.673  9969  9990 W bt_btif : btif_dm_upstreams_cback  ev: UNKNOWN DM EVENT
10-12 16:09:17.674  9969  9990 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 9 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 20 mIsExtendedScanSupported = true mIsDebugLogSupported = true
10-12 16:09:17.674  9969  9990 E BluetoothAdapterState: stateChangeCallback : 1
10-12 16:09:17.675  9969  9983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: ENABLED_READY
10-12 16:09:17.679  9969  9983 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.679  9969  9983 D DOWNLOADABLE_DB: refreshDbFile
10-12 16:09:17.679  9969  9983 D BluetoothServiceJni: refreshDownloadableDbFileNative:
10-12 16:09:17.679  9969  9983 I bt_btif : refreshDownloadableDbFile
,10-12 16:09:17.683  9969 10021 I bt_hwcfg: SCO PCM configure {0x0, 0x1, 0x0, 0x0, 0x0}
,10-12 16:09:17.683  9969  9983 I         : iop_db_open: iop_db_open status 0
,10-12 16:09:17.684  9969  9983 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-12 16:09:17.684  9969  9983 D BluetoothAdapterService: Bluetooth PBAP supported is true
10-12 16:09:17.684  9969 10021 I bt_vendor: low_power_mode_cb
,10-12 16:09:17.692  9969  9983 D BluetoothAdapterService: Autoconnection is available 
10-12 16:09:17.692  9969  9983 D BluetoothAdapterService: updateAdapterState prevState = 14newState = 15
10-12 16:09:17.692  9969  9983 I BluetoothAdapterState: Entering BleOnState
,10-12 16:09:17.699  3703  3797 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
,10-12 16:09:17.700  3703  3797 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
,10-12 16:09:17.701  3703  3797 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:17.703  9969  9980 E BluetoothBondStateMachine: initStateMachine
10-12 16:09:17.703  9969  9983 D BluetoothAdapterState: Current state: BLE ON, message: USER_TURN_ON
,10-12 16:09:17.706  9969  9983 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-12 16:09:17.706  9969  9983 D BluetoothAdapterService: Bluetooth PBAP supported is true
10-12 16:09:17.707  9969  9983 D BluetoothAdapterService: Autoconnection is available 
10-12 16:09:17.707  3703  3797 D BluetoothManagerService: Turning On/Off, G state: 0, S state: 0, mBLE count: 0, s BLE count: 0
10-12 16:09:17.707  9969  9983 D BluetoothAdapterService: updateAdapterState prevState = 15newState = 11
10-12 16:09:17.707  9969  9983 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,10-12 16:09:17.708  9969  9983 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dpsink.A2dpSinkService
,10-12 16:09:17.708  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,10-12 16:09:17.719  3703  3703 D BluetoothPhoneService: Bluetooth Adapter state : 11
10-12 16:09:17.722  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
10-12 16:09:17.722  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:17.722  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
10-12 16:09:17.723  9969  9969 D HeadsetService: Received start request. Starting profile...
10-12 16:09:17.724  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.724  4069  4296 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:17.724  4069  4296 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
10-12 16:09:17.725  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
10-12 16:09:17.737  9115  9115 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:17.738  9115  9115 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
10-12 16:09:17.738  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:17.743  9839  9942 D BluetoothAdapter: enable()
10-12 16:09:17.753  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
10-12 16:09:17.755  3703  5217 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{3bba274: PendingIntentRecord{c1bb39d com.google.android.gms broadcastIntent}}
10-12 16:09:17.755  9969  9969 I HeadsetService: clearAllHeadsetSettings(0) - complete : 0
10-12 16:09:17.758  9969  9969 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-12 16:09:17.759  9969  9969 D HeadsetStateMachine: make
10-12 16:09:17.761  9969  9969 E HeadsetStateMachine: # of Max HF connection is 3
,10-12 16:09:17.772  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,10-12 16:09:17.780  9969  9992 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-12 16:09:17.781  9969  9992 D AdapterProvider: query
,10-12 16:09:17.787  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,10-12 16:09:17.790  9969  9992 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@986e50
10-12 16:09:17.792  9969  9992 D BluetoothAdapterService: updateEvent - already set, update
10-12 16:09:17.792  9969  9992 W BluetoothAdapterService: updateEvent - alreadySet is true
10-12 16:09:17.792  9969  9992 D AdapterProvider: update
10-12 16:09:17.793  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,10-12 16:09:17.796  9969  9992 E BluetoothAdapterService: updateEvent - update success 1
,10-12 16:09:17.806  3703  4541 W ActivityManager: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
,10-12 16:09:17.808  3703  4541 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
10-12 16:09:17.808  3703  4541 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9839, uid=10033 requires android.permission.INTERACT_ACROSS_USERS
10-12 16:09:17.808  3703  4541 W BluetoothManagerService: 	at com.android.server.am.UserController.getCurrentUser(UserController.java:1642)
10-12 16:09:17.808  3703  4541 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:25897)
10-12 16:09:17.808  3703  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.checkItPolicy(BluetoothManagerService.java:2985)
10-12 16:09:17.808  3703  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.isRestrictedBtPolicy(BluetoothManagerService.java:2975)
10-12 16:09:17.808  3703  4541 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:1243)
10-12 16:09:17.808  3703  4541 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
10-12 16:09:17.808  3703  4541 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:573)
10-12 16:09:17.808  3703  4541 E DevicePolicyManagerService: semGetAllowBluetoothMode - value retunrs : 2
10-12 16:09:17.809  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sap.SapService
10-12 16:09:17.813  9969  9969 I DualScoManager: Instantiating Dual Sco Manager
10-12 16:09:17.813  9969  9969 I DualScoManager: Set HeadsetServiceHelper
,10-12 16:09:17.813  9969  9969 I DualScoManager: setNotificationManager
10-12 16:09:17.813  9969  9969 I DualScoManager: setAudioManager
10-12 16:09:17.814  9969  9969 D BluetoothAtMessage: createCMTIContentObservers
10-12 16:09:17.815  3703  4541 D SecContentProvider: query(), uri = 3 selection = isBluetoothEnabled
10-12 16:09:17.816  3703  4541 D SecContentProvider: called from com.thaliproject.thalitest
,10-12 16:09:17.824  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,10-12 16:09:17.824  9969  9983 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,10-12 16:09:17.824  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dpsink.A2dpSinkService
,10-12 16:09:17.824  9969  9983 W BluetoothAdapterService: setProfileServiceState() Profile supported, But not enabled com.android.bluetooth.a2dpsink.A2dpSinkService
10-12 16:09:17.824  9969  9983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
10-12 16:09:17.831  9969  9983 I BluetoothAdapterState: Entering PendingCommandState
,10-12 16:09:17.838  9969  9969 D HeadsetProvider: Created cursor android.database.sqlite.SQLiteCursor@3ebb768
,10-12 16:09:17.839  9969  9969 I HeadsetService: getHeadsetDB(true) - 44:78:3E:94:4A:XX, 300, 1
10-12 16:09:17.840  9969  9969 I DualScoManager: setSystemAudioInbandSupported : true
,10-12 16:09:17.841  9969  9969 I HeadsetStateMachine: isAutoAppInstalled : false
,10-12 16:09:17.841  9969  9969 I HeadsetStateMachine: IBR : true (SysA : 1 / DB : 1)
,10-12 16:09:17.843  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:17.844  9969  9969 D DOWNLOADABLE_DB: getNotAllowedVoiceRecognitionDeviceList
,10-12 16:09:17.851  9969 10028 D HeadsetStateMachine: Enter Disconnected: -2, size: 0/0
,10-12 16:09:17.855  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.855  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Message sending
10-12 16:09:17.855  9969  9969 D HeadsetService: notifyProfileServiceStateChanged
,10-12 16:09:17.856  9969 10028 D HeadsetStateMachine: Clear mHeadsetBrsf
10-12 16:09:17.857  9969 10028 D HeadsetStateMachine: map size, before remove : 0
10-12 16:09:17.857  9969 10028 D HeadsetStateMachine: map size, after remove: 0
10-12 16:09:17.857  9969 10028 D HeadsetStateMachine: connectNextConnectingDevice(false) : null
,10-12 16:09:17.860  9969  9969 D A2dpService: Received start request. Starting profile...
10-12 16:09:17.860  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:17.861  9969  9969 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-12 16:09:17.867  9969 10021 I bt_hwcfg: SCO PCM data format {0x0, 0x0, 0x3, 0x0, 0x0}
,10-12 16:09:17.870  9969 10021 I bt_hwcfg: sco I2S/PCM config result 0 [0-Success, 1-Fail]
10-12 16:09:17.870  9969 10021 I bt_vendor: sco_audiostate_cb(status: 0)
,10-12 16:09:17.872  9969  9969 I Avrcp   : No of Audio players :: 1
10-12 16:09:17.872  9969  9969 I Avrcp   : App Package name is GM
,10-12 16:09:17.888  9969  9969 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,10-12 16:09:17.891  9969  9969 I Avrcp   : No of Video players :: 2
10-12 16:09:17.891  9969  9969 I Avrcp   : Video App Package name is VP
,10-12 16:09:17.896  9969  9969 V Avrcp   : MediaPlayerInfo: mPlayerId=2
10-12 16:09:17.896  9969  9969 I Avrcp   : Video App Package name is others
,10-12 16:09:17.904  9969  9969 V Avrcp   : MediaPlayerInfo: mPlayerId=3
10-12 16:09:17.904  9969  9969 I Avrcp   : Add tempPlayer
10-12 16:09:17.904  9969  9969 V Avrcp   : MediaPlayerInfo: mPlayerId=4
10-12 16:09:17.904  9969  9969 V Avrcp   : no_of_players : 4
10-12 16:09:17.904  9969  9969 I Avrcp   : Total no of players: 4
10-12 16:09:17.904  9969  9969 V Avrcp   : Samsung player is the 1st player
,10-12 16:09:17.905  9969  9969 D Avrcp   : Compose Browsing Service Candidate
,10-12 16:09:17.906  9969  9969 D Avrcp   : ResolveInfo info ResolveInfo{318d8b2 com.android.bluetooth/.a2dpsink.mbs.A2dpMediaBrowserService m=0x108000}
10-12 16:09:17.906  9969  9969 D Avrcp   : ResolveInfo info ResolveInfo{f46b003 com.google.android.music/.browse.MediaBrowserService m=0x108000}
10-12 16:09:17.906  9969  9969 D Avrcp   : Initialize Media Controller
,10-12 16:09:17.908  9969  9969 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,10-12 16:09:17.913  9969  9969 E Avrcp   : getActiveSessions
10-12 16:09:17.913  9969  9969 D Avrcp   : pick active media Controller
10-12 16:09:17.913  9969  9969 D Avrcp   : Get the active Media Controller 
,10-12 16:09:17.917  9969  9969 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 16:09:17.917  9969  9969 D A2dpStateMachine: make
,10-12 16:09:17.919  9969 10031 W bt_osi_thread: run_thread: thread id 10031, thread name media_worker started
,10-12 16:09:17.919  9969  9969 E bt_btif : warning : media task started media_task_refcnt 1 
10-12 16:09:17.919  9969  9969 W bt_btif : btif_ar_init
10-12 16:09:17.920  9969  9990 W bt_btif : av start inhibit off
10-12 16:09:17.922  9969  9969 E A2dpStateMachine: isDualPlayEnabled : Dual Play not supported
,10-12 16:09:17.922  9969 10030 D A2dpStateMachine: Enter Disconnected: -2
10-12 16:09:17.926  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.926  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Message sending
10-12 16:09:17.926  9969  9969 D A2dpService: notifyProfileServiceStateChanged
10-12 16:09:17.927  9969  9969 I BluetoothHidServiceJni: classInitNative: succeeds
,10-12 16:09:17.931  9969  9969 D HidService: Received start request. Starting profile...
,10-12 16:09:17.931  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.931  9969  9969 D HidService: setHidService(): set to: null
10-12 16:09:17.931  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.931  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Message sending
10-12 16:09:17.931  9969  9969 D HidService: notifyProfileServiceStateChanged
,10-12 16:09:17.941  9969  9969 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-12 16:09:17.944  9115  9115 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
,10-12 16:09:17.944  9115  9115 D BluetoothStatusReceiver: AdapterStateChanged :: state = 11
,10-12 16:09:17.945  9969  9969 D HealthService: Received start request. Starting profile...
10-12 16:09:17.945  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:17.951  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.951  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Message sending
10-12 16:09:17.951  9969  9969 D HealthService: notifyProfileServiceStateChanged
,10-12 16:09:17.954  9969  9969 I BluetoothPanServiceJni: classInitNative(L139): succeeds
,10-12 16:09:17.958  9969  9969 D PanService: Received start request. Starting profile...
10-12 16:09:17.959  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.959  9969  9969 D BluetoothPanServiceJni: initializeNative(L144): pan
,10-12 16:09:17.970  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.970  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Message sending
10-12 16:09:17.970  9969  9969 D PanService: notifyProfileServiceStateChanged
,10-12 16:09:17.976  9969  9969 D BluetoothMapService: Received start request. Starting profile...
10-12 16:09:17.976  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:17.987  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:17.987  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Message sending
10-12 16:09:17.987  9969  9969 D BluetoothMapService: notifyProfileServiceStateChanged
10-12 16:09:17.988  9969  9969 D HeadsetStateMachine: Proxy object connected
,10-12 16:09:17.992  9969  9969 V SapService: SapBinder()
,10-12 16:09:17.993  9969  9969 D SapService: Received start request. Starting profile...
10-12 16:09:17.993  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:17.993  9969  9969 V SapService: start()
10-12 16:09:17.994  9969  9969 D SapService: Disable sap : false
,10-12 16:09:18.001  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:18.001  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Message sending
10-12 16:09:18.001  9969  9969 D SapService: notifyProfileServiceStateChanged
10-12 16:09:18.002  9969  9969 V BluetoothHidDevServiceJni: classInitNative: done
,10-12 16:09:18.007  9969  9969 D HidDevService: Received start request. Starting profile...
,10-12 16:09:18.007  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:18.007  9969  9969 D HidDevService: start()
10-12 16:09:18.007  9969  9969 V BluetoothHidDevServiceJni: initNative enter
10-12 16:09:18.007  9969  9969 V BluetoothHidDevServiceJni: initNative done
10-12 16:09:18.007  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:18.007  9969  9969 E BluetoothAdapterService: onProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Message sending
10-12 16:09:18.007  9969  9969 D HidDevService: notifyProfileServiceStateChanged
10-12 16:09:18.008  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:18.008  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Before synchronized
10-12 16:09:18.008  9969  9969 V BluetoothAdapterState: isTurningOff()=false
10-12 16:09:18.008  9969  9969 V BluetoothAdapterState: isTurningOn()=true
10-12 16:09:18.008  9969  9969 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:18.008  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:18.009  9969  9969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-12 16:09:18.009  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:18.009  9969 10028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
10-12 16:09:18.009  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Before synchronized
10-12 16:09:18.009  9969  9969 V BluetoothAdapterState: isTurningOff()=false
10-12 16:09:18.009  9969  9969 V BluetoothAdapterState: isTurningOn()=true
10-12 16:09:18.009  9969  9969 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:18.009  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:18.010  9969 10028 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-12 16:09:18.010  9969  9969 D A2dpService: A2dpService - WIFI_STATE_ENABLED
10-12 16:09:18.010  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:18.010  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, Before synchronized
10-12 16:09:18.010  9969 10028 D HeadsetStateMachine: Disconnected process message: 11, size: 0
10-12 16:09:18.010  9969  9969 V BluetoothAdapterState: isTurningOff()=false
10-12 16:09:18.010  9969  9969 V BluetoothAdapterState: isTurningOn()=true
10-12 16:09:18.010  9969 10028 E HeadsetStateMachine: Unknown message: 11
10-12 16:09:18.010  9969  9969 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:18.010  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:18.010  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:18.010  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, Before synchronized
10-12 16:09:18.010  9969  9969 V BluetoothAdapterState: isTurningOff()=false
10-12 16:09:18.010  9969  9969 V BluetoothAdapterState: isTurningOn()=true
10-12 16:09:18.010  9969  9969 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:18.010  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:18.013  9969  9969 D BluetoothUtils: readSalesCode :: sales code is XEO
,10-12 16:09:18.014  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:18.014  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, Before synchronized
10-12 16:09:18.014  9969  9969 V BluetoothAdapterState: isTurningOff()=false
10-12 16:09:18.014  9969  9969 V BluetoothAdapterState: isTurningOn()=true
10-12 16:09:18.014  9969  9969 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:18.014  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:18.014  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:18.014  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Before synchronized
,10-12 16:09:18.014  9969  9969 V BluetoothAdapterState: isTurningOff()=false
10-12 16:09:18.014  9969  9969 V BluetoothAdapterState: isTurningOn()=true
10-12 16:09:18.014  9969  9969 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:18.014  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 16:09:18.167  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:18.167  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.sap.SapService, state=12, Before synchronized
,10-12 16:09:18.168  9969  9969 V BluetoothAdapterState: isTurningOff()=false
,10-12 16:09:18.168  9969  9969 V BluetoothAdapterState: isTurningOn()=true
10-12 16:09:18.168  9969  9969 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:18.168  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:18.168  9969  9969 E BluetoothAdapterService: handleMessage() - Message: 1
10-12 16:09:18.168  9969  9969 E BluetoothAdapterService: processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidDevService, state=12, Before synchronized
10-12 16:09:18.168  9969  9969 V BluetoothAdapterState: isTurningOff()=false
10-12 16:09:18.168  9969  9969 V BluetoothAdapterState: isTurningOn()=true
10-12 16:09:18.169  9969  9969 V BluetoothAdapterState: isBleTurningOn()=false
10-12 16:09:18.169  9969  9969 V BluetoothAdapterState: isBleTurningOff()=false
10-12 16:09:18.170  9969  9983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_STARTED
10-12 16:09:18.173  9969  9969 I BluetoothA2dpServiceJni: Attempting to set busy level
,10-12 16:09:18.187  9969  9983 E BluetoothServiceJni: enableBrEdrNative:
10-12 16:09:18.187  9969  9983 I bt_btif : enable_bredr
,10-12 16:09:18.189  9969  9990 W bt_btif : btif_dm_generic_evt: event=33035
,10-12 16:09:18.202  9969  9990 W bt_btif : btif_dm_generic_evt: event=33035
,10-12 16:09:18.205  9969 10025 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
10-12 16:09:18.215  9969  9990 W bt_btif : IsSoftphone: 
10-12 16:09:18.215  9969  9990 E bt_btif : btif_transfer_context() Caller thread is BTIF thread. Don't try context switch.
10-12 16:09:18.216  9969  9990 W bt_btif : btif_dm_generic_evt: event=33035
10-12 16:09:18.216  9969 10025 D CODEC_IF_MOD: codec_open: codec_open
10-12 16:09:18.216  9969 10025 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
10-12 16:09:18.216  9969 10025 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
10-12 16:09:18.216  9969 10025 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
10-12 16:09:18.216  9969 10025 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-12 16:09:18.216  9969 10025 D CODEC_IF: codec_if_close: codec_if_close hdl -999702524
10-12 16:09:18.216  9969 10025 D CODEC_IF_MOD: codec_close: codec_close
10-12 16:09:18.216  9969 10025 D CODEC_IF_MOD: codec_close: freed apt-x encoder
10-12 16:09:18.216  9969 10025 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
10-12 16:09:18.216  9969 10025 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,10-12 16:09:18.225  9969  9990 E BluetoothServiceJni: populateRssiValuesNative
10-12 16:09:18.225  9969  9990 I bt_btif : getModelRssiValues
10-12 16:09:18.225  9969  9990 E BluetoothServiceJni: model_rssi_values_callback: low = -75, mid = -65, high = 127
10-12 16:09:18.226  9969 10025 D CODEC_IF_SSHD: codec_open: codec_open
10-12 16:09:18.226  9969 10025 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
10-12 16:09:18.226  9969 10025 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
10-12 16:09:18.226  9969 10025 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-12 16:09:18.226  9969 10025 D CODEC_IF: codec_if_close: codec_if_close hdl -1030886016
10-12 16:09:18.226  9969 10025 D CODEC_IF_SSHD: codec_close: codec_close
10-12 16:09:18.226  9969 10025 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
10-12 16:09:18.226  9969 10025 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
10-12 16:09:18.226  9969 10025 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
10-12 16:09:18.235  9969 10025 D CODEC_IF_SSHD2: codec_open: codec_open
10-12 16:09:18.235  9969 10025 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
10-12 16:09:18.236  9969 10025 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
10-12 16:09:18.236  9969 10025 D CODEC_IF: codec_if_open: codec module opened (v0.1
,10-12 16:09:18.236  9969 10025 D CODEC_IF: codec_if_close: codec_if_close hdl -1000493056
10-12 16:09:18.236  9969 10025 D CODEC_IF_SSHD2: codec_close: codec_close
10-12 16:09:18.236  9969 10025 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
10-12 16:09:18.238  9969 10025 D CODEC_IF: codec_if_open: opening libbt-codec_aptx.so...
10-12 16:09:18.240  9969 10025 D CODEC_IF_MOD: codec_open: codec_open
10-12 16:09:18.240  9969 10025 D CODEC_IF_MOD: codec_open: apt-x encoder initialized successfully
10-12 16:09:18.240  9969 10025 D CODEC_IF_MOD: codec_open:    version : 1.0.1.0
10-12 16:09:18.240  9969 10025 D CODEC_IF_MOD: codec_open:    build : Android_JB_4.2.2
10-12 16:09:18.240  9969 10025 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-12 16:09:18.240  9969 10025 D CODEC_IF: codec_if_close: codec_if_close hdl -999702524
,10-12 16:09:18.240  9969 10025 D CODEC_IF_MOD: codec_close: codec_close
10-12 16:09:18.240  9969 10025 D CODEC_IF_MOD: codec_close: freed apt-x encoder
10-12 16:09:18.240  9969 10025 D         : Codec ==> check 96kHz mode : check_sshd_encoder_available:396
10-12 16:09:18.240  9969 10025 D CODEC_IF: codec_if_open: opening libbt-codec_sshd.so...
,10-12 16:09:18.244  9969 10025 D CODEC_IF_SSHD: codec_open: codec_open
10-12 16:09:18.244  9969 10025 D CODEC_IF_SSHD: Codec ==> pcm_info.sampling_freq : 96000
10-12 16:09:18.244  9969 10025 D CODEC_IF_SSHD: codec_open: SSHD encoder initialized successfully
10-12 16:09:18.245  9969 10025 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-12 16:09:18.245  9969 10025 D CODEC_IF: codec_if_close: codec_if_close hdl -1030886016
10-12 16:09:18.245  9969 10025 D CODEC_IF_SSHD: codec_close: codec_close
10-12 16:09:18.245  9969 10025 D         : Codec ==> copy capability info [bta_av_co_audio_init:747]
,10-12 16:09:18.245  9969 10025 D         : Codec ==> check 96kHz mode : check_sshd2_encoder_available:440
10-12 16:09:18.245  9969 10025 D CODEC_IF: codec_if_open: opening libbt-codec_sshd2.so...
,10-12 16:09:18.247  9969 10025 D CODEC_IF_SSHD2: codec_open: codec_open
10-12 16:09:18.247  9969 10025 D CODEC_IF_SSHD2: codec_open: Codec ==> pcm_info.sampling_freq : 96000
10-12 16:09:18.247  9969 10025 D CODEC_IF_SSHD2: codec_open: SSHD2 encoder initialized successfully
10-12 16:09:18.247  9969 10025 D CODEC_IF: codec_if_open: codec module opened (v0.1
10-12 16:09:18.247  9969 10025 D CODEC_IF: codec_if_close: codec_if_close hdl -1000493056
,10-12 16:09:18.248  9969 10025 D CODEC_IF_SSHD2: codec_close: codec_close
10-12 16:09:18.248  9969 10025 D         : Codec ==> copy capability info [bta_av_co_audio_init:781]
,10-12 16:09:18.250  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:18.260  9969  9990 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,10-12 16:09:18.260  9969  9990 E bt_btif : btif_handle_bluetooth_enable_evt
,10-12 16:09:18.260  9969  9990 E bt_btif : ANT+ socket does not initialize.
,10-12 16:09:18.264  9969 10044 W bt_osi_thread: run_thread: thread id 10044, thread name btif_sock started
,10-12 16:09:18.264  9969  9990 E BluetoothAdapterState: stateChangeCallback : 17
,10-12 16:09:18.265  9969  9990 E bt_btif : no av cb found, event:0, BTA_AV_ENABLE_EVT ignored!
10-12 16:09:18.265  9969  9990 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
,10-12 16:09:18.265  9969  9990 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:3
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:3
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:2
10-12 16:09:18.265  9969  9990 E bt_btif : warning : no command pending, ignore ack
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:3
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:2
10-12 16:09:18.265  9969  9990 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
10-12 16:09:18.265  9969  9990 E bt_btif : bta_av_co_get_peer peer index out of bounds:255
10-12 16:09:18.265  9969  9990 E bt_btif : bta_av_co_audio_peer_init No active peer with this handle 0x0
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:3
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:3
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:2
10-12 16:09:18.265  9969  9990 E bt_btif : warning : no command pending, ignore ack
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:3
10-12 16:09:18.265  9969  9990 E bt_btif : no av control block available at state:2
10-12 16:09:18.265  9969  9990 W bt_btif : btif_av_state_idle_handler : unhandled event:BTA_AV_REGISTER_EVT
10-12 16:09:18.265  9969 10031 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
,10-12 16:09:18.265  9969 10031 E bt_btif : warning : no command pending, ignore ack
10-12 16:09:18.265  9969 10031 W bt_btif : btif_media_task_aa_stop_tx : tx already stopped, ignore request
10-12 16:09:18.266  9969 10031 E bt_btif : warning : no command pending, ignore ack
10-12 16:09:18.266  9969  9983 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: BREDR_NATIVE_STARTED
10-12 16:09:18.269  9969  9990 D BluetoothPanServiceJni: control_state_callback(L64): state:0, local_role:3, ifname:bt-pan
10-12 16:09:18.269  9969  9983 D BluetoothAdapterProperties: ScanMode =  20
10-12 16:09:18.270  9969  9983 D BluetoothAdapterProperties: State =  11
,10-12 16:09:18.274  3703  4845 D SecContentProvider: query(), uri = 3 selection = isDiscoverableEnabled
10-12 16:09:18.275  3703  4845 D SecContentProvider: called from android.uid.bluetooth:1002
10-12 16:09:18.277  3703  3725 D SecContentProvider: insert(), uri = 2
10-12 16:09:18.277  3703  3725 D SecContentProvider: called from android.uid.bluetooth:1002
,10-12 16:09:18.281  9969  9983 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-12 16:09:18.281  9969  9990 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,10-12 16:09:18.282  9969  9983 D BluetoothAdapterService: [VendorCapa] prevState: 11, newState: 12
,10-12 16:09:18.282  9969  9983 I bt_btif : vsc_getvendorcapabilities
,10-12 16:09:18.283  9969  9983 D BluetoothAdapterService: Bluetooth PBAP supported is true
,10-12 16:09:18.285  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-12 16:09:18.291  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:18.297  9969  9983 D BluetoothAdapterService: Autoconnection is available 
10-12 16:09:18.297  9969  9983 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
10-12 16:09:18.297  9969  9983 D BluetoothAdapterService: starting service from this receiver
10-12 16:09:18.297  9839  9965 D BluetoothAdapter: onBluetoothStateChange: up=true
,10-12 16:09:18.297  9839  9965 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-12 16:09:18.298  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:18.299  4069  4087 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 16:09:18.307  9839  9839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-12 16:09:18.309  9969  9983 I BluetoothAdapterState: Entering OnState
10-12 16:09:18.314  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:18.317  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:18.319  9839  9839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-12 16:09:18.323  9969  9969 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
10-12 16:09:18.326  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:18.326  9115  9126 D BluetoothSap: onBluetoothStateChange: up=true
10-12 16:09:18.326  9115  9126 D BluetoothSap: Binding service...
10-12 16:09:18.331  4733  6810 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:18.332  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 16:09:18.332  9115  9127 D BluetoothPan: onBluetoothStateChange on: true
10-12 16:09:18.337  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:18.340  4069  8161 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 16:09:18.343  9839  9839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
10-12 16:09:18.347  9839  9942 D BluetoothAdapter: STATE_ON
,10-12 16:09:18.352  4069  5977 D BluetoothPan: onBluetoothStateChange on: true
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:18.353  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 16:09:18.355  9839  9905 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,10-12 16:09:18.359  4069  4069 D BluetoothInputDevice: Proxy object connected
10-12 16:09:18.359  4069  4069 D HidProfile: Bluetooth service connected
10-12 16:09:18.360  9969  9969 I BluetoothPbapService: Handler(): got msg=1
10-12 16:09:18.362  3703  3922 D WifiService: setWifiEnabled: false pid=9839, uid=10033
10-12 16:09:18.363  9969 10046 V BluetoothPbapService: PBAP Service initSocket try: 0
10-12 16:09:18.363  3703  3922 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-12 16:09:18.363  3703  3922 D WifiControlHistoryProvider: query
10-12 16:09:18.364  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:18.366  4769  4782 D BluetoothAdapter: onBluetoothStateChange: up=true
,10-12 16:09:18.366  4769  4782 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-12 16:09:18.366  9969  9990 W bt_btif : btif_dm_generic_evt: event=34050
10-12 16:09:18.367  9969  9990 D BluetoothAdapterProperties: [VendorCapa] : mDbfwSupported: 1 , mA2dpLinkFeedbackSupported: 1
10-12 16:09:18.370  4733  6713 D BluetoothAdapter: onBluetoothStateChange: up=true
,10-12 16:09:18.370  4733  6713 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-12 16:09:18.371  9969 10046 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:18.371  9969 10046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 16:09:18.371  4069  8161 D BluetoothSap: onBluetoothStateChange: up=true
10-12 16:09:18.371  4069  8161 D BluetoothSap: Binding service...
10-12 16:09:18.374  3703  3922 D WifiNative-wlan0: callSECApiVoid - ID [312]
10-12 16:09:18.374  3703  4013 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
10-12 16:09:18.376  9969 10046 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
10-12 16:09:18.377  3703  3703 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
10-12 16:09:18.378  4069  4069 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 16:09:18.378  3703  3922 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-12 16:09:18.378  4069  4069 D PanProfile: Bluetooth service connected
10-12 16:09:18.378  9115  9126 D BluetoothAdapter: onBluetoothStateChange: up=true
10-12 16:09:18.378  9115  9126 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-12 16:09:18.380  3703  3922 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.380  9969  9981 D BluetoothAdapter: onBluetoothStateChange: up=true
10-12 16:09:18.380  9969  9981 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-12 16:09:18.381  9115  9115 D BluetoothSap: Proxy object connected
10-12 16:09:18.381  9115  9115 D SapProfile: Bluetooth service connected
10-12 16:09:18.381  3703  3922 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
10-12 16:09:18.381  9115  9115 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 16:09:18.381  9115  9115 D PanProfile: Bluetooth service connected
10-12 16:09:18.382  4069  4087 D BluetoothMap: onBluetoothStateChange: up=true
,10-12 16:09:18.385  3703  3922 D WifiService: unRegisterForSContext() : skip - it does not registered.
10-12 16:09:18.386  3703  3927 D SecContentProvider: insert(), uri = 2
,10-12 16:09:18.389  3703  3927 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.390  4069  4069 D BluetoothPbap: Proxy object connected
,10-12 16:09:18.390  4069  4069 D PbapServerProfile: Bluetooth service connected
10-12 16:09:18.390  4069  4069 D BluetoothSap: Proxy object connected
10-12 16:09:18.390  3703  3927 D SecContentProvider: insert(), uri = 2
10-12 16:09:18.390  4069  4069 D SapProfile: Bluetooth service connected
10-12 16:09:18.390  4069  4069 D BluetoothMap: Proxy object connected
10-12 16:09:18.391  4069  4069 D MapProfile: Bluetooth service connected
10-12 16:09:18.391  4069  4069 D BluetoothMap: getConnectedDevices()
10-12 16:09:18.391  3703  3927 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.393  4069  4087 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,10-12 16:09:18.395  3703  3928 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-12 16:09:18.397  3703  3928 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@dda2359
10-12 16:09:18.398  3703  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161818, SetElapsed=748299, nowELAPSED=208601
10-12 16:09:18.398  4069  4069 D A2dpProfile: Bluetooth service connected
10-12 16:09:18.398  3703  3928 D WifiStateMachine: isFindLocationId() - Location Id : 1
10-12 16:09:18.398  3703  3928 D WifiStateMachine: ConnectedState - exit() - stopLearning id : 1
10-12 16:09:18.398  3703  3928 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
10-12 16:09:18.399  3703  3928 D SLocation: system
10-12 16:09:18.399  3703  3928 D SLocation: stopLearning ID = 1
,10-12 16:09:18.399  3703  3928 D SLocation: setLearningStatus ID = 1 / status = false
10-12 16:09:18.400  3703  3928 D SecContentProvider: insert(), uri = 2
10-12 16:09:18.401  4069  4086 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
10-12 16:09:18.401  3703  3928 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.401  3703  3928 D WifiStateMachine: Wifi got Disconnected in connectedstate, Send provisioning intent mAutoRoamingfalse
,10-12 16:09:18.402  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiStateMachine$ConnectedState.exit:11809 com.android.internal.util.StateMachine$SmHandler.invokeExitMethods:1009 com.android.internal.util.StateMachine$SmHandler.performTransitions:865 com.android.internal.util.StateMachine$SmHandler.handleMessage:809 
,10-12 16:09:18.404  9969  9980 D A2dpStateMachine: getConnectedDevices : size=0
10-12 16:09:18.404  3703  3928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 16:09:18.405  3703  3933 D DhcpClient: doQuit
10-12 16:09:18.405  3703  3933 D ApfFilter: (wlan0): shutting down
10-12 16:09:18.405  3703  5121 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@7ffef36
10-12 16:09:18.406  3703  5121 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@553c8c2
,10-12 16:09:18.409  4042  4053 D BluetoothAdapter: onBluetoothStateChange: up=true
10-12 16:09:18.409  4042  4053 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-12 16:09:18.410  4069  5977 D BluetoothAdapter: onBluetoothStateChange: up=true
10-12 16:09:18.410  4069  5977 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-12 16:09:18.411  3703  3797 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,10-12 16:09:18.413  3703  5121 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@9699109
,10-12 16:09:18.414  3703  3797 D BluetoothAdapter: onBluetoothStateChange: up=true
10-12 16:09:18.414  3703  3797 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
10-12 16:09:18.414  9435  9450 D BluetoothAdapter: onBluetoothStateChange: up=true
10-12 16:09:18.414  9435  9450 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,10-12 16:09:18.418  9115  9115 I WifiApBroadcastReceiver: onReceive: action com.samsung.intent.action.START_PROVISIONING userID :0
,10-12 16:09:18.420  4069  4296 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
,10-12 16:09:18.420  4069  4296 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,10-12 16:09:18.427  3703  4842 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-12 16:09:18.438  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 16:09:18.438  9115  9115 V BluetoothEventManager: onReceive :: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:18.438  9115  9115 D BluetoothEventManager: AdapterStateChangedHandler :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
10-12 16:09:18.440  9969  9969 D PanService: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:18.440  9969  9969 D PanService: BT STATE ON
10-12 16:09:18.441  9969  9969 D EnhancedTetheringManager: EnhancedTetheringManager()
10-12 16:09:18.441  9969  9969 D EnhancedTetheringManager: start
10-12 16:09:18.442  3703  3924 D WifiP2pService: InactiveState{ what=143375 }
10-12 16:09:18.442  3703  3924 D WifiP2pService: P2pEnabledState{ what=143375 }
10-12 16:09:18.442  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-12 16:09:18.443  3703  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-12 16:09:18.443  3703  3959 D ConnectivityService: ignoring duplicate network state non-change
10-12 16:09:18.443  3703  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 12
10-12 16:09:18.443  3703  4013 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
10-12 16:09:18.446  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:18.446  9969  9991 D A2dpStateMachine: getConnectedDevices : size=0
10-12 16:09:18.447  3703  5121 D DhcpClient: onQuitting
10-12 16:09:18.447  3703  5217 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{e84315: PendingIntentRecord{e93262a com.google.android.gms broadcastIntent}}
10-12 16:09:18.450  3703  3959 V NetworkStats: updateIfacesLocked()
10-12 16:09:18.450  3703  3959 V NetworkStats: performPollLocked(flags=0x1)
10-12 16:09:18.450  3703  3959 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:18.450  9115  9115 E BluetoothEventManager: unregisterProfileIntentReceiver :: mProfileConnectionReceiver was not registered.
10-12 16:09:18.450  9115  9115 D LocalBluetoothProfileManager: Adding local A2DP profile
10-12 16:09:18.451  3703  3928 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
10-12 16:09:18.451  3703  3928 I WifiConnectivityManager: Set WiFi disabled
10-12 16:09:18.451  3703  3928 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@62ead44
10-12 16:09:18.452  3703  3928 I WifiStateMachine: deinitGeofence
10-12 16:09:18.452  3703  3928 D SLocation: stopGeofence ID = 1
10-12 16:09:18.454  3703  3703 D Telecom : SecBluetoothManager : register BluetoothHeadset after STATE_ON : null
10-12 16:09:18.454  3703  3703 D Telecom : SecBluetoothManager : registerBluetoothHeadsetMessageListener fail
10-12 16:09:18.454  3703  3703 D BluetoothPhoneService: Bluetooth Adapter state : 12
10-12 16:09:18.455  3703  3703 I BluetoothPhoneService: queryPhoneState
10-12 16:09:18.455  3703  3703 I BluetoothPhoneService: updateHeadsetWithCallState : true
10-12 16:09:18.460  3298  3792 D CommandListener: Clearing all IP addresses on wlan0
10-12 16:09:18.466  9115  9115 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
10-12 16:09:18.468  4042  4042 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
10-12 16:09:18.469  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive
10-12 16:09:18.469  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive action: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:18.469  3703  3703 D KnoxKeyguardUpdateMonitor: BroadcastReceiver onReceive BT state is changed
,10-12 16:09:18.470  3703  3959 V NetworkStats: performPollLocked() took 20ms
,10-12 16:09:18.470  3703  3959 D NtpTrustedTime: currentTimeMillis() cache hit
,10-12 16:09:18.479  9115  9115 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-12 16:09:18.481  3703  3703 I WifiTrafficPoller: evaluateTrafficStatsPolling
,10-12 16:09:18.481  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-12 16:09:18.481  3703  3703 D HS20StateMachine: checkifOSUAP  null disconnectedFromSsid"NG700"
10-12 16:09:18.482  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-12 16:09:18.482  3703  3959 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,10-12 16:09:18.482  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.482  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:18.483  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:18.483  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:18.483  3703  4013 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
10-12 16:09:18.483  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:18.483  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-12 16:09:18.483  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.483  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.484  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.484  9115  9115 E BluetoothHeadset: BTStateChangeCB is registed
10-12 16:09:18.485  3703  3955 I WifiHs20Service: Message received 5007
,10-12 16:09:18.487  3703  4011 D DnsEventListenerService: Logging 24 results for netId 502
,10-12 16:09:18.487  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
,10-12 16:09:18.487  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.487  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.487  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:18.489  9115  9115 D BluetoothMap: Create BluetoothMap proxy object
10-12 16:09:18.489  4527  4606 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [false]
10-12 16:09:18.490  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.490  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.491  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-12 16:09:18.491  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.492  3703  3703 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
10-12 16:09:18.493  4527  4616 D PdnController: handleMessage: what 106
10-12 16:09:18.493  4527  4616 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [false]
10-12 16:09:18.493  4527  4616 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [false]
10-12 16:09:18.494  9969  9969 D ETMLeHelper: ETMLeHelper()
10-12 16:09:18.494  9969  9969 D ETMLeHelper: initTetherAdv
10-12 16:09:18.494  4527  4616 D ResipRegiMgr: handleMessage(): 3
10-12 16:09:18.495  4527  4616 D RegiMgrBase: handleMessage: what 3
,10-12 16:09:18.496  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:18.496  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:18.497  4527  4606 D GeolocationController: WIFI : onLost
,10-12 16:09:18.497  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.497  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.497  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:18.497  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:18.497  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:18.497  3703  3959 D ConnectivityService: sending notification LOST for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:18.497  3703  3959 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.498  3703  5110 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 16:09:18.498  3703  5110 D NetworkMonitor/NetworkAgentInfo [WIFI () - 502]: unregister CaptivePortalReceiver
10-12 16:09:18.498  3703  4023 D Ethernet: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.498  3703  4023 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
10-12 16:09:18.498  3703  4023 D Ethernet: evalRequest
10-12 16:09:18.498  3703  4023 D Ethernet:   done
10-12 16:09:18.499  3703  3924 D WIFI_P2P: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.499  3703  3924 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:18.499  3703  3924 D WIFI_P2P: evalRequest
10-12 16:09:18.499  3703  3924 D WIFI_P2P:   done
10-12 16:09:18.499  4042  4042 D PhoneSwitcherNetworkRequstListener: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.499  4042  4042 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
10-12 16:09:18.499  4042  4042 D PhoneSwitcherNetworkRequstListener: evalRequest
10-12 16:09:18.499  4042  4042 D PhoneSwitcherNetworkRequstListener:   done
10-12 16:09:18.500  3703  3797 D EntConnectivity: Not allowed due to - mEnabled false
,10-12 16:09:18.505  9969  9969 D BluetoothAdapter: STATE_ON
,10-12 16:09:18.506  9969  9969 D BluetoothAdapter: STATE_ON
10-12 16:09:18.507  9969  9969 D BluetoothAdapter: STATE_ON
10-12 16:09:18.508  9115  9115 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,10-12 16:09:18.509  9969  9969 D BluetoothAdapter: isSecureModeEnabled
10-12 16:09:18.510  9969  9969 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:18.510  4069  4296 W LocalBluetoothProfileManager: updateLocalProfiles :: MAP profile was previously added but the UUID is now missing.
10-12 16:09:18.510  4069  4296 W LocalBluetoothProfileManager: updateLocalProfiles :: PBAP profile was previously added but the UUID is now missing.
10-12 16:09:18.510  4069  4296 W LocalBluetoothProfileManager: updateLocalProfiles :: SAP profile was previously added but the UUID is now missing.
,10-12 16:09:18.510  4069  4296 W LocalBluetoothProfileManager: updateLocalProfiles :: HID profile was previously added but the UUID is now missing.
10-12 16:09:18.510  4069  4296 W LocalBluetoothProfileManager: updateLocalProfiles :: Spp profile was created already 
10-12 16:09:18.511  9969  9969 D ETMLeHelper: initTetherScan
10-12 16:09:18.512  3239  3239 E audit   : type=1320 audit(1507817358.505:522): 
10-12 16:09:18.513  9969  9969 D BluetoothAdapter: STATE_ON
10-12 16:09:18.513  3703  3928 E SLocation: pendingIntent set to null
10-12 16:09:18.513  3703  3928 D SLocation: setStatus ID = 1 / status = 0
10-12 16:09:18.513  3703  3928 D SLocation: updateSession : trigger = false
10-12 16:09:18.513  3703  3928 D SLocation: updateSession : mSessionStatus = 0
10-12 16:09:18.513  3703  3928 D WifiStateMachine:  stopGeofence() - id : 1
10-12 16:09:18.514  9969  9969 D BluetoothAdapter: STATE_ON
10-12 16:09:18.514  3703  4484 D SLocation: Session stopped
10-12 16:09:18.514  3703  3928 D SLocation: stopGeofence ID = 2
10-12 16:09:18.514  3703  4484 D SLocation: triggerAlarm
10-12 16:09:18.514  3703  4484 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / op:PendingIntent{7ac363d: PendingIntentRecord{d07de32 android broadcastIntent}}
10-12 16:09:18.515  3703  4484 D SLocation: All alarm stopped
10-12 16:09:18.517  9969  9969 D BluetoothMapUtils: [RCS] imsConfigCscFeatures : , enableCpmFeature : false
10-12 16:09:18.517  9969  9969 D BluetoothMapUtils: mRcsSupported : false
,10-12 16:09:18.522  3703  3920 D MountService: getExternalStorageMountMode : 1
10-12 16:09:18.522  3703  3920 D MountService: getExternalStorageMountMode : 3
10-12 16:09:18.522  3703  3920 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,10-12 16:09:18.524  3239  3239 E audit   : type=1320 audit(1507817358.515:523): 
,10-12 16:09:18.525  3298  3792 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 16:09:18.525  9115  9115 D LocalBluetoothProfileManager: Adding local Spp profile
,10-12 16:09:18.529  3298  3784 I Netd    : Destroyed 17 sockets on 192.168.1.102 in 1.2 ms
10-12 16:09:18.529  4733  6842 V NativeCrypto: Read error: ssl=0x717ca48500: I/O error during system call, Software caused connection abort
,10-12 16:09:18.537  3239  3239 E audit   : type=1320 audit(1507817358.535:524): 
10-12 16:09:18.537  4733  6842 V NativeCrypto: SSL shutdown failed: ssl=0x717ca48500: I/O error during system call, Broken pipe
,10-12 16:09:18.547 10055 10055 E Zygote  : v2
,10-12 16:09:18.547 10055 10055 I libpersona: KNOX_SDCARD checking this for 10049
10-12 16:09:18.547 10055 10055 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:18.547  3703  3920 I ActivityManager: Start proc 10055:com.samsung.android.email.provider/u0a49 for content provider com.samsung.android.email.provider/.provider.database.EmailProvider
,10-12 16:09:18.547 10055 10055 E Zygote  : isSdpEnabledProcess - SDP enabled
10-12 16:09:18.547  3703  3928 E SLocation: pendingIntent set to null
10-12 16:09:18.547  3703  3928 D SLocation: setStatus ID = 2 / status = 0
10-12 16:09:18.547  3703  3928 D SLocation: updateSession : trigger = false
10-12 16:09:18.547  3703  3928 D SLocation: updateSession : mSessionStatus = 0
10-12 16:09:18.547  3703  3928 D WifiStateMachine:  stopGeofence() - id : 2
10-12 16:09:18.548  3703  3928 D wifi    : android_net_wifi_reset_alert_handler = 0x71766f3360
10-12 16:09:18.548  3703  3928 E WifiHAL : failed to request reset; result = -95
10-12 16:09:18.548  3703  3928 D wifi    : android_net_wifi_reset_log_handler = 0x71766f3360
10-12 16:09:18.548  3703  3928 I WifiHAL : Failed to remove command 1: 0x0
10-12 16:09:18.548  3703  3928 D WifiHAL : Success to clear alerthandler
10-12 16:09:18.548  3703  4484 D SLocation: Session stopped
10-12 16:09:18.548  3703  4484 D SLocation: triggerAlarm
10-12 16:09:18.549  3703  4484 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / op:PendingIntent{7ac363d: PendingIntentRecord{d07de32 android broadcastIntent}}
10-12 16:09:18.549  3239  3239 E audit   : type=1320 audit(1507817358.545:525): 
10-12 16:09:18.549  3703  4484 D SLocation: All alarm stopped
10-12 16:09:18.549  3703  3928 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-12 16:09:18.550  3703  3928 D WIFI_UT : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.550  3298  3792 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 16:09:18.550  3703  3928 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:18.550 10055 10055 E Zygote  : accessInfo : 64
10-12 16:09:18.550 10055 10055 E Zygote  : isSdpEnabledProcess - SDP enabled
10-12 16:09:18.550  3703  3928 D WIFI_UT : evalRequest
10-12 16:09:18.550 10055 10055 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
10-12 16:09:18.550  3703  3928 D WIFI_UT :   done
10-12 16:09:18.550  3703  4180 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{27a98df: PendingIntentRecord{d17099d com.google.android.gms broadcastIntent}}
10-12 16:09:18.550  3703  3928 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:18.550  3703  3924 D WifiP2pService: InactiveState{ what=131204 }
10-12 16:09:18.550  3703  3928 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:18.550  3703  3928 D WIFI    : evalRequest
10-12 16:09:18.550  3703  3928 D WIFI    :   needNetworkFor
10-12 16:09:18.550  3703  3924 D WifiP2pService: P2pEnabledState{ what=131204 }
10-12 16:09:18.551  3703  4180 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T163627, SetElapsed=1837417, nowELAPSED=208754
10-12 16:09:18.551  4733  6842 E GCM     : Wifi connection closed with errorCode 20
10-12 16:09:18.553  3703  3959 D ConnectivityService: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
10-12 16:09:18.553  3703  3959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 16:09:18.553  3703  3956 I WifiScanningService: wifi driver unloaded
10-12 16:09:18.554  3703  3956 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.scanner.SupplicantWifiScannerImpl$2@441392c
10-12 16:09:18.555  3703  3703 D RttService: SCAN_AVAILABLE : 1
10-12 16:09:18.556  3703  3957 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.,StateMachine$SmHandler }
10-12 16:09:18.556 10055 10055 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:09:18.558 10055 10055 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider 
10-12 16:09:18.559  4291  4291 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
10-12 16:09:18.559  4291  4291 I wpa_supplicant: P2P: Clear a pre-passphrase (State NONE)
10-12 16:09:18.561  3703  3924 D WifiP2pService: sending p2p connection changed broadcast: FAILED
10-12 16:09:18.566  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:18.566  3703 10067 I ApplicationPolicy: updateDataUsageMap
10-12 16:09:18.568  3703  3797 D EntConnectivity: Not allowed due to - mEnabled false
10-12 16:09:18.568  3703  3703 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
10-12 16:09:18.568  3703  3703 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = true
10-12 16:09:18.568  3703  3914 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
10-12 16:09:18.568  3703  3914 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
10-12 16:09:18.570  9115  9115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1386 android.content.ContextWrapper.startService:656 android.content.ContextWrapper.startService:656 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 16:09:18.570  3703  3703 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
10-12 16:09:18.571  3703  3703 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
10-12 16:09:18.571  3703  3915 I KnoxVpnEngineService: vpn handle : Message received
10-12 16:09:18.571  3703  3915 I KnoxVpnEngineService: vpn handle : Message received
10-12 16:09:18.571  3703  3915 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = true
10-12 16:09:18.575  3703  3703 D Tethering: Tethering got CONNECTIVITY_ACTION
10-12 16:09:18.576  3703  3960 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
10-12 16:09:18.576  3703  3960 D Tethering: MasterInitialState.processMessage what=327683
10-12 16:09:18.580  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:18.581  3239  3239 E audit   : type=1320 audit(1507817358.575:526): 
10-12 16:09:18.587  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-12 16:09:18.590 10055 10055 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:18.590 10055 10055 D ActivityThread: Added TimaKeyStore provider
10-12 16:09:18.592  3703  3919 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
10-12 16:09:18.592  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:18.593  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:18.593  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:18.593  3703  3919 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
10-12 16:09:18.593  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:18.593  3239  3239 E audit   : type=1320 audit(1507817358.585:527): 
10-12 16:09:18.594  5082  5082 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF50EC62EA054297E5426D68FE61E03F7CB63D06B4FC0A78A26416AA7E048F840EFBC21D921AABB61599A4C4654ABE1206043CF566A086A1148D0FC76C5AA3DFC0]}
10-12 16:09:18.594  3703  3919 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
10-12 16:09:18.594  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-12 16:09:18.595  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
10-12 16:09:18.595  5082  5082 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF006507037EF1FC27CFA959C112FA7F2D870458BE3926C900C8D0246DBBD82F5FF9735DB64481160EAC5657CBD115B580]}
,10-12 16:09:18.607  5172  5172 I CastMediaRouteProvider: Network connectivity changed
10-12 16:09:18.617  8049  8049 I FOTA_AGENT: [com.samsung.android.app.syncmldm.llllIIIllIlIIIIllllI(243/onReceive)] m_DataReceiver: g_nResumeStatus: 0 m_nWaitWifiConnectMode: 0
10-12 16:09:18.621  8049  8049 W FOTA_AGENT: [lIIlllIlIIlllIIIIlII(74/llIIIIlllllIIllIIllI)] NetworkInfo is null
10-12 16:09:18.622  9330  9330 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
10-12 16:09:18.622  9330  9330 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
10-12 16:09:18.623  3298  3792 E Netd    : netlink response contains error (No such file or directory)
10-12 16:09:18.624  8049  8049 I FOTA_AGENT: [com.samsung.android.app.syncmldm.XDMService(1152/IIIllIIllIllIlIIlIIl)] WiFi network Connected : false
10-12 16:09:18.632  3703  3959 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED
10-12 16:09:18.633  9399  9399 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@845b7e4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:18.633  8049  8049 W FOTA_AGENT: [lIIlllIlIIlllIIIIlII(74/llIIIIlllllIIllIIllI)] NetworkInfo is null
,10-12 16:09:18.648  4069  4296 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
10-12 16:09:18.653  9330  9330 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
10-12 16:09:18.653  9330  9330 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
10-12 16:09:18.653  9330  9330 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
10-12 16:09:18.654  9399  9399 I NetworkConnectivity: Network state changed: null
10-12 16:09:18.654  4826  4826 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-12 16:09:18.660  3703  3798 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
10-12 16:09:18.663  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:18.669  3703  3941 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
10-12 16:09:18.670  9115  9115 D A2dpProfile: Bluetooth service connected
,10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 16:09:18.673  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 16:09:18.676  9399  9399 I NetworkPolicyMonitor: Download-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
10-12 16:09:18.678  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:18.679  3703  3703 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
10-12 16:09:18.680  3703  3703 V MARsPolicyManager: DataConnection: false
10-12 16:09:18.680  3703  4484 D SLocation: checkWifiInfo
10-12 16:09:18.680  3703  4484 W SLocation: No Active Data Connection
10-12 16:09:18.680  3703  4484 W SLocation: No Active Data Connection
10-12 16:09:18.682  3703  4039 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,10-12 16:09:18.683  9839  9839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-12 16:09:18.684  3703  3924 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
10-12 16:09:18.684  3703  3959 D ConnectivityService: ignoring duplicate network state non-change
10-12 16:09:18.688  3703  3798 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
10-12 16:09:18.688  3703  3798 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
10-12 16:09:18.688  3703  3798 D WifiDisplayController: disconnect
10-12 16:09:18.688  3703  3798 D WifiDisplayAdapter: onFeatureStateChanged empty
10-12 16:09:18.688  3703  3798 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
10-12 16:09:18.689  9399  9399 I NetworkPolicyMonitor: Stream-ability status changed to (false) unmetered wifi/eth: false mobileOrMetered: false
10-12 16:09:18.694  3703  4039 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
10-12 16:09:18.695  3703  3924 D SecContentProvider: insert(), uri = 2
10-12 16:09:18.696  9969 10049 D A2dpStateMachine: getConnectedDevices : size=0
10-12 16:09:18.696  3703  3924 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.697  9115  9115 D BluetoothMap: Proxy object connected
10-12 16:09:18.697  3703  3924 D WifiP2pService: P2pDisablingState
10-12 16:09:18.697  3703  3924 D WifiP2pService: P2pDisablingState{ what=147458 }
10-12 16:09:18.697  9115  9115 D MapProfile: Bluetooth service connected
10-12 16:09:18.697  3703  3924 D WifiP2pService: p2p socket connection lost
10-12 16:09:18.697  9115  9115 D BluetoothMap: getConnectedDevices()
10-12 16:09:18.699  3703  3924 D SecContentProvider: insert(), uri = 2
,10-12 16:09:18.700  3703  3924 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.701  3703  3928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 16:09:18.701  3703  3924 D WifiP2pService: P2pDisabledState
,10-12 16:09:18.706  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-12 16:09:18.706  3703  4013 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
10-12 16:09:18.708  3703  3924 D WifiP2pService: P2pDisabledState{ what=143375 }
10-12 16:09:18.709  3703  3924 D WifiP2pService: DefaultState{ what=143375 }
10-12 16:09:18.714  3703  3798 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: false, roaming: false, metered: false]
10-12 16:09:18.719  3703  3928 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 16:09:18.720  4291  4291 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
10-12 16:09:18.721  3703  3928 D SecContentProvider: insert(), uri = 2
,10-12 16:09:18.725  3703  3703 I WifiTrafficPoller: evaluateTrafficStatsPolling
10-12 16:09:18.726  3703  3928 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.727  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-12 16:09:18.727  5172  6764 W MdnsClient_Cast: Multicast lock held. Releasing. Subtypes:"805741C9"
,10-12 16:09:18.728  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
,10-12 16:09:18.728  3703  3955 I WifiHs20Service: Message received 5007
10-12 16:09:18.730  9399  9399 I DevicePlayback: Got network change: mobile=falsewifi=false
,10-12 16:09:18.731  9399  9399 I DevicePlayback: Disabling Woodstock in 200000ms
10-12 16:09:18.732 10055 10055 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
10-12 16:09:18.735  5172  6764 W MdnsClient: unicast receiver thread is already dead.
10-12 16:09:18.735  4042  4042 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,10-12 16:09:18.737  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-12 16:09:18.740  9115  9115 D BluetoothPbap: Proxy object connected
,10-12 16:09:18.741  9115  9115 D PbapServerProfile: Bluetooth service connected
10-12 16:09:18.741  9115  9115 D BluetoothInputDevice: Proxy object connected
10-12 16:09:18.742  3703  4013 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
10-12 16:09:18.742  9115  9115 D HidProfile: Bluetooth service connected
,10-12 16:09:18.744  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:18.750 10055 10055 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:18.751  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
10-12 16:09:18.751  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
10-12 16:09:18.751  3703  3955 I WifiHs20Service: Message received 5011
10-12 16:09:18.752  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135173 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-12 16:09:18.755  3703  4039 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,10-12 16:09:18.757  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:18.757  3703  3703 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
10-12 16:09:18.757  3703  4484 D SLocation: checkWifiInfo
10-12 16:09:18.757  3703  4484 D SLocation: wifi available : false
10-12 16:09:18.757  3703  4484 D SLocation: Session stopped
10-12 16:09:18.757  3703  4484 D SLocation: triggerAlarm
10-12 16:09:18.757  3703  4484 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / op:PendingIntent{7ac363d: PendingIntentRecord{d07de32 android broadcastIntent}}
,10-12 16:09:18.758  3703  4484 D SLocation: All alarm stopped
,10-12 16:09:18.759  3703  4039 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
10-12 16:09:18.762  3703  3725 D RCPManagerService: exchangeData() failure , invalid userId
10-12 16:09:18.763  3703  3703 D WifiNotificationController: SHOW_NOTI_MESSAGE : 17, visible : false, ssid : null, targetSSID : null, netId : -1, titleType : -1
10-12 16:09:18.767  3298  3784 D Netd    : Iface p2p0 link up
10-12 16:09:18.769  9839  9839 D BluetoothAdapter: STATE_ON
,10-12 16:09:18.770  3703  3796 D Tethering: interfaceLinkStateChanged p2p0, true
10-12 16:09:18.770  3703  3796 D Tethering: interfaceStatusChanged p2p0, true
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 16:09:18.774  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 16:09:18.777  9115  9115 D DockEventReceiver: finishStartingService: stopping service
10-12 16:09:18.777  9839  9839 D BluetoothAdapter: STATE_ON
,10-12 16:09:18.780 10055 10055 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : Email, QJ5JBlRnP9, com.samsung.android.email.provider.service.sCloudBNRService
10-12 16:09:18.780  9839  9839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
10-12 16:09:18.780 10055 10055 I QBNRClientHelper: init SyncClientHelper : Email
10-12 16:09:18.780 10055 10055 I BNRClientProivder, VERSION : 1.7.5: register - xml6 quick_backup : EMAILFOLDER, 55LAYJm0O2, com.samsung.android.email.provider.service.sCloudBNRService2
10-12 16:09:18.781 10055 10055 I QBNRClientHelper: init SyncClientHelper : EMAILFOLDER
,10-12 16:09:18.784  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:18.799  3298  3787 D EnterpriseController: netId is 0
,10-12 16:09:18.799  3298  3787 D Netd    : getNetworkForDns: using netid 0 for uid 10001
10-12 16:09:18.799  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-12 16:09:18.803  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135179 arg1=193 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:18.806  3703  4871 D RCPManagerService: exchangeData() failure , invalid userId
,10-12 16:09:18.809 10055 10079 D skia    : ---- fAsset->read(8192) returned 0
10-12 16:09:18.809 10055 10079 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-12 16:09:18.812  3703  4180 D MountService: getExternalStorageMountMode : 1
10-12 16:09:18.812  3703  4180 D MountService: getExternalStorageMountMode : 3
10-12 16:09:18.812  3703  4180 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10049, packageName : com.samsung.android.email.provider
,10-12 16:09:18.814 10055 10079 D skia    : ---- fAsset->read(8192) returned 0
10-12 16:09:18.814 10055 10079 D skia    : --- SkAndroidCodec::NewFromStream returned null
10-12 16:09:18.814  5218 10075 E         : Error communicating to API: https://prod.yana.asideas.de/api/v2/advertising/frequencies/pl
10-12 16:09:18.814  5218 10075 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
10-12 16:09:18.814  5218 10075 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
10-12 16:09:18.814  5218 10075 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
10-12 16:09:18.814  5218 10075 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
10-12 16:09:18.814  5218 10075 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
10-12 16:09:18.814  5218 10075 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
10-12 16:09:18.814  5218 10075 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
10-12 16:09:18.814  5218 10075 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
10-12 16:09:18.814  5218 10075 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
10-12 16:09:18.814  5218 10075 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
10-12 16:09:18.814  5218 10075 E         : 	at java.lang.Thread.run(Thread.java:762)
10-12 16:09:18.814  5218 10075 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
10-12 16:09:18.814  5218 10075 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
10-12 16:09:18.814  5218 10075 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
10-12 16:09:18.814  5218 10075 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
10-12 16:09:18.814  5218 10075 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
10-12 16:09:18.814  5218 10075 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
10-12 16:09:18.814  5218 10075 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
10-12 16:09:18.814  5218 10075 E         : 	... 9 more
10-12 16:09:18.814  5218 10075 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
10-12 16:09:18.814  52,18 10075 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
10-12 16:09:18.814  5218 10075 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
10-12 16:09:18.814  5218 10075 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
10-12 16:09:18.814  5218 10075 E         : 	... 26 more
10-12 16:09:18.814  5218 10075 E         : 
10-12 16:09:18.815 10055 10079 D skia    : ---- fAsset->read(8192) returned 0
10-12 16:09:18.815 10055 10079 D skia    : --- SkAndroidCodec::NewFromStream returned null
10-12 16:09:18.818 10055 10055 D SamsungAnalytics:1.8.25: cf feature is supported
10-12 16:09:18.819  5218 10075 E         : Unable to fetch advertisement frequency.
10-12 16:09:18.819  5218 10075 E         : retrofit.RetrofitError: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
10-12 16:09:18.819  5218 10075 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:395)
10-12 16:09:18.819  5218 10075 E         : 	at retrofit.RestAdapter$RestHandler.access$100(RestAdapter.java:220)
10-12 16:09:18.819  5218 10075 E         : 	at retrofit.RestAdapter$RestHandler$1.invoke(RestAdapter.java:265)
10-12 16:09:18.819  5218 10075 E         : 	at retrofit.RxSupport$2.run(RxSupport.java:55)
10-12 16:09:18.819  5218 10075 E         : 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:428)
10-12 16:09:18.819  5218 10075 E         : 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
10-12 16:09:18.819  5218 10075 E         : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1133)
10-12 16:09:18.819  5218 10075 E         : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:607)
10-12 16:09:18.819  5218 10075 E         : 	at retrofit.Platform$Android$2$1.run(Platform.java:142)
10-12 16:09:18.819  5218 10075 E         : 	at java.lang.Thread.run(Thread.java:762)
10-12 16:09:18.819  5218 10075 E         : Caused by: java.net.UnknownHostException: Unable to resolve host "prod.yana.asideas.de": No address associated with hostname
10-12 16:09:18.819  5218 10075 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:125)
10-12 16:09:18.819  5218 10075 E         : 	at java.net.Inet6AddressImpl.lookupAllHostAddr(Inet6AddressImpl.java:74)
10-12 16:09:18.819  5218 10075 E         : 	at java.net.InetAddress.getAllByName(InetAddress.java:752)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.Dns$1.lookup(Dns.java:39)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.resetNextInetSocketAddress(RouteSelector.java:175)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.nextProxy(RouteSelector.java:141)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.internal.http.RouteSelector.next(RouteSelector.java:83)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findConnection(StreamAllocation.java:174)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.findHealthyConnection(StreamAllocation.java:126)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.internal.http.StreamAllocation.newStream(StreamAllocation.java:95)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:281)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:224)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.Call.getResponse(Call.java:286)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.Call$ApplicationInterceptorChain.proceed(Call.java:243)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.Call.getResponseWithInterceptorChain(Call.java:205)
10-12 16:09:18.819  5218 10075 E         : 	at com.squareup.okhttp.Call.execute(Call.java:80)
10-12 16:09:,18.819  5218 10075 E         : 	at retrofit.client.OkClient.execute(OkClient.java:53)
10-12 16:09:18.819  5218 10075 E         : 	at retrofit.RestAdapter$RestHandler.invokeRequest(RestAdapter.java:326)
10-12 16:09:18.819  5218 10075 E         : 	... 9 more
10-12 16:09:18.819  5218 10075 E         : Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
10-12 16:09:18.819  5218 10075 E         : 	at libcore.io.Posix.android_getaddrinfo(Native Method)
10-12 16:09:18.819  5218 10075 E         : 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
10-12 16:09:18.819  5218 10075 E         : 	at java.net.Inet6AddressImpl.lookupHostByName(Inet6AddressImpl.java:106)
10-12 16:09:18.819  5218 10075 E         : 	... 26 more
10-12 16:09:18.819  5218 10075 E         : 
10-12 16:09:18.820 10055 10055 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
10-12 16:09:18.827  4291  4291 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
10-12 16:09:18.833  3703  4180 I ActivityManager: Start proc 10083:com.samsung.android.email.provider:service/u0a49 for service com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService
10-12 16:09:18.833  4291  4291 E wpa_supplicant: can't get BSS information
10-12 16:09:18.833 10083 10083 E Zygote  : v2
10-12 16:09:18.833 10083 10083 I libpersona: KNOX_SDCARD checking this for 10049
10-12 16:09:18.833 10083 10083 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:18.834  4291  4291 I wpa_supplicant: CTRL_IFACE: Detach monitor that cannot receive messages: /data/misc/wifi/sockets/wpa_ctrl_3703-2\x00
10-12 16:09:18.834  4291  4291 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.E6.C2 reason=3 locally_generated=1
10-12 16:09:18.834 10083 10083 E Zygote  : isSdpEnabledProcess - SDP enabled
10-12 16:09:18.836 10083 10083 E Zygote  : accessInfo : 64
10-12 16:09:18.836 10083 10083 E Zygote  : isSdpEnabledProcess - SDP enabled
10-12 16:09:18.836 10083 10083 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10049 / [uid]: 10049
10-12 16:09:18.842  3298  3784 D Netd    : Iface wlan0 link up
10-12 16:09:18.844  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:18.844  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
10-12 16:09:18.844 10083 10083 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:09:18.846 10083 10083 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.email.provider:service 
10-12 16:09:18.856  4069  4211 D vol.MediaSessions: onQueueChanged com.google.android.music []
10-12 16:09:18.869 10083 10083 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:18.870 10083 10083 D ActivityThread: Added TimaKeyStore provider
10-12 16:09:18.872  3703  4180 I ActivityManager: DSS on for com.samsung.android.email.provider and scale is 1.0
,10-12 16:09:18.892  9839  9942 D BluetoothAdapter: STATE_ON
,10-12 16:09:18.894  9969  9969 D BluetoothUtils: readSalesCode :: sales code is XEO
,10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 16:09:18.895  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 16:09:18.897  4069  4069 D HeadsetProfile: Bluetooth service connected
,10-12 16:09:18.899  9115  9115 D HeadsetProfile: Bluetooth service connected
,10-12 16:09:18.900  3703  3922 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:09:18.901  3703  3922 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-12 16:09:18.901  9839  9905 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:18.901  3703  3922 D WifiControlHistoryProvider: query
10-12 16:09:18.903 10083 10083 W System  : ClassLoader referenced unknown path: /system/priv-app/SecEmail_N/lib/arm64
10-12 16:09:18.902  9969  9969 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:18.904  3703  3703 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.bluetooth.SecBluetoothMessageListener@1fc28ad
,10-12 16:09:18.904  3703  3703 D BluetoothHeadset: registerMessageListener
,10-12 16:09:18.903  9969  9969 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:18.907  9969  9980 D HeadsetService: registerMessageListener
10-12 16:09:18.908  9969  9980 D HeadsetService: registerMessageListener
10-12 16:09:18.908  3703  3703 I Telecom : SecBluetoothManager : register MessageListener
,10-12 16:09:18.911  9969 10028 D HeadsetStateMachine: Disconnected process message: 70, size: 0
10-12 16:09:18.911  9969 10028 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@b0d176a
,10-12 16:09:18.911  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-12 16:09:18.914  9969 10035 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2) for masId0
10-12 16:09:18.915  3703  3922 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-12 16:09:18.916  3703  3922 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.916  9969  9969 D BluetoothUtils: readSalesCode :: sales code is XEO
10-12 16:09:18.917  3703  3922 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
10-12 16:09:18.917 10083 10083 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
10-12 16:09:18.919  9969 10035 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:18.919  9969 10035 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 16:09:18.922  3703  3922 I WifiService: Wi-Fi Sharing settings has not been accessed
10-12 16:09:18.923  3703  3922 D WifiService: unRegisterForSContext() : skip - it does not registered.
10-12 16:09:18.923  3703  3927 D SecContentProvider: insert(), uri = 2
10-12 16:09:18.924  3703  3927 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.925  3703  3927 D SecContentProvider: insert(), uri = 2
10-12 16:09:18.925  3703  3927 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:18.927  9115  9115 D BluetoothStatusReceiver: Received :: android.bluetooth.adapter.action.STATE_CHANGED
10-12 16:09:18.927  9115  9115 D BluetoothStatusReceiver: AdapterStateChanged :: state = 12
,10-12 16:09:18.933  3703  3703 I Telecom : SecBluetoothManager : not single connected gear
,10-12 16:09:18.943  3703  3703 I Telecom : CallAudioRoutePeripheralAdapter : onBluetoothStateChange 1 => 1
,10-12 16:09:18.943  3703  3703 I BluetoothPhoneService: updateHeadsetWithCallState : true
,10-12 16:09:18.944  3703  4565 I Telecom : com.android.server.telecom.CallAudioRouteStateMachine: Message received: DISCONNECT_BLUETOOTH=4, arg1=0: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
10-12 16:09:18.944  3703  4565 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, Bluetooth disconnected: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
10-12 16:09:18.946  9969 10035 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:18.947  9969 10035 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 16:09:18.949  4733  6828 I BeaconBle: Client requested scan, settings=BleSettings [scanMode=LOW_LATENCY, callbackType=ALL_MATCHES, reportDelayMillis=0, 3 filters, 0 clients, callingClientName=Nearby], listener=hjz@706eeb7
10-12 16:09:18.950  9969 10100 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:18.950  9969 10100 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 16:09:18.957  4291  4291 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-12 16:09:18.959  9969  9969 V BtOppService: isOwner == true
,10-12 16:09:18.961  9969 10035 D ObexServerSockets: Succeed to create listening sockets 
,10-12 16:09:18.961  9969 10035 D ObexServerSockets: startAccept()
,10-12 16:09:18.964  9969 10101 D ObexServerSockets: Accepting socket connection for masId0
,10-12 16:09:18.965  9969 10102 D ObexServerSockets: Accepting socket connection for masId0
10-12 16:09:18.966  9969 10100 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-12 16:09:18.967  9969 10100 D BluetoothSdpJni: SDP Create record success - handle: 0
10-12 16:09:18.967  3703  4565 I Telecom : SecBluetoothManager : not single connected gear
10-12 16:09:18.968  3703  4565 I Telecom : Telecom: Non-call EVENT: AUDIO_ROUTE, mAvailableRoutes: 9: BMSL.oSC->CARSM.pM_DISCONNECT_BLUETOOTH@ACs_0
10-12 16:09:18.968  9969 10035 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,10-12 16:09:18.968  9969 10035 D BluetoothSdpJni: SDP Create record success - handle: 1
10-12 16:09:18.970  9969 10028 D HeadsetStateMachine: Disconnected process message: 9, size: 0
10-12 16:09:18.970  9969 10028 D A2dpSinkService: getA2dpSinkService(): service is NULL
10-12 16:09:18.970  9969 10028 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,10-12 16:09:18.981  3276  3276 D audio_hw_primary: adev_set_parameters: enter: kvpairs: A2dpSuspended=false
10-12 16:09:18.982  9969 10028 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,10-12 16:09:18.988  4733  6828 I BeaconBle: 'L' hardware scan: 3 filters, scanMode=2, reportdelay=0, callback type=1, #clients=1
10-12 16:09:18.992  4733  6828 I BeaconBle: Starting scan on delegate scanner - BT state: 12
10-12 16:09:18.992  4733  6828 D BluetoothLeScanner: Start Scan
,10-12 16:09:18.997  4733  6828 D BluetoothAdapter: STATE_ON
,10-12 16:09:19.002  4733  6828 D BluetoothAdapter: STATE_ON
,10-12 16:09:19.010  4733  6828 D BluetoothAdapter: STATE_ON
,10-12 16:09:19.016  4733  6828 D BluetoothAdapter: STATE_ON
10-12 16:09:19.017  3298  3784 D Netd    : Iface wlan0 link up
10-12 16:09:19.017  3298  3784 D Netd    : Iface wlan0 link up
10-12 16:09:19.018  4291  4291 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-12 16:09:19.019  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:19.019  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
10-12 16:09:19.020  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:19.020  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
10-12 16:09:19.029  3703  3725 D SecContentProvider: query(), uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,10-12 16:09:19.033 10083 10106 D skia    : ---- fAsset->read(8192) returned 0
,10-12 16:09:19.033 10083 10106 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-12 16:09:19.042 10083 10106 D skia    : ---- fAsset->read(8192) returned 0
10-12 16:09:19.042 10083 10106 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-12 16:09:19.044 10083 10106 D skia    : ---- fAsset->read(8192) returned 0
,10-12 16:09:19.044 10083 10106 D skia    : --- SkAndroidCodec::NewFromStream returned null
,10-12 16:09:19.125  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-12 16:09:19.133  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=settings_global.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
10-12 16:09:19.133  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=settings_global.xml.bak sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-12 16:09:19.176  9969  9981 D BtGatt.GattService: registerClient() - UUID=52dc7720-e2ea-45fa-bc02-8b409edc49f2
10-12 16:09:19.176  3703  4850 D RCPManagerService: exchangeData() failure , invalid userId
,10-12 16:09:19.180  3703  3725 D SecContentProvider: called from android.uid.bluetooth:1002
10-12 16:09:19.187  3703  4845 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BleCentralService newState = 1 callingPackage = 10019
10-12 16:09:19.190  3703  3928 D wifi    : In wifi stop Hal
10-12 16:09:19.190  3703  3928 D wifi    : halHandle = 0x71766e8d20, mVM = 0x71a2490300, mCls = 0x1010ce
10-12 16:09:19.190  3703  4289 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-12 16:09:19.190  3703  4289 D WifiHAL : Got a signal to exit!!!
10-12 16:09:19.190  3703  4289 I WifiHAL : Exit wifi_event_loop
10-12 16:09:19.192  3703  3928 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-12 16:09:19.192  3703  3928 E WifiHAL : Event processing terminated
10-12 16:09:19.193  5172  6765 I Authzen : [PermitStore] Getting all permits...
10-12 16:09:19.196  3703  4850 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.auth.proximity.BlePeripheralService newState = 1 callingPackage = 10019
,10-12 16:09:19.207  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,10-12 16:09:19.207  3703  3954 D HS20StateMachine: WIFI_STATE_DISABLED
10-12 16:09:19.207  3703  3954 D HS20StateMachine: CMD_HOTSPOT20_DISABLE
10-12 16:09:19.208  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
10-12 16:09:19.208  3703  3955 I WifiHs20Service: Message received 5011
,10-12 16:09:19.212  3298  3784 D Netd    : Iface p2p0 link down
10-12 16:09:19.216  3703  3796 D Tethering: interfaceLinkStateChanged p2p0, false
,10-12 16:09:19.216  3703  3796 D Tethering: interfaceStatusChanged p2p0, false
10-12 16:09:19.217 10083 10083 D SamsungAnalytics:1.8.25: cf feature is supported
10-12 16:09:19.220  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:19.227  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-12 16:09:19.227  3703  4039 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,10-12 16:09:19.230 10083 10083 D SamsungAnalytics:1.8.25: [Tracker] Tracker start:1.8.25
,10-12 16:09:19.232  3703  4039 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,10-12 16:09:19.232  3703  3703 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
10-12 16:09:19.233  3703  4484 D SLocation: checkWifiInfo
10-12 16:09:19.236  9969  9969 D A2dpService: A2dpService - WIFI_STATE_DISABLED
,10-12 16:09:19.237  9969  9969 I BluetoothA2dpServiceJni: Attempting to set busy level
10-12 16:09:19.245  9969 10118 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:19.245  9969 10118 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 16:09:19.245  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:19.246  4733  5210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 16:09:19.247  3703  3928 D wifi    : In wifi cleaned up handler
10-12 16:09:19.247  3703  3928 I WifiHAL : Internal cleanup completed
10-12 16:09:19.253  9969 10118 I BtOppRfcommListener: Accept thread started.
,10-12 16:09:19.280  9969  9990 D BtGatt.GattService: onClientRegistered() - UUID=52dc7720-e2ea-45fa-bc02-8b409edc49f2, clientIf=5, status=0
,10-12 16:09:19.281  4733  6713 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,10-12 16:09:19.282  9969  9980 D BtGatt.GattService: start scan with filters
,10-12 16:09:19.285  9969  9980 D BtGatt.GattService: getScanSettings
,10-12 16:09:19.292  9969  9980 D BtGatt.GattService: Is it foreground application = false
10-12 16:09:19.292  9969  9980 D BtGatt.GattService: Its third party background application, change scanmode to low power
,10-12 16:09:19.293  3703  3941 D MountService: getExternalStorageMountMode : 3
10-12 16:09:19.293  3703  3941 D MountService: getExternalStorageMountMode : 3
10-12 16:09:19.293  3703  3941 D MountService: getExternalStorageMountMode : final mountMode=3, uid : 5017, packageName : com.samsung.android.radiobasedlocation
,10-12 16:09:19.316 10123 10123 E Zygote  : v2
10-12 16:09:19.316 10123 10123 I libpersona: KNOX_SDCARD checking this for 5017
10-12 16:09:19.316 10123 10123 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:19.317  3703  3941 I ActivityManager: Start proc 10123:com.samsung.android.radiobasedlocation/5017 for broadcast com.samsung.android.radiobasedlocation/.RblServiceReceiver
,10-12 16:09:19.317 10123 10123 E Zygote  : accessInfo : 0
,10-12 16:09:19.327  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_START_SCAN
10-12 16:09:19.327 10123 10123 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:09:19.329 10123 10123 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.radiobasedlocation 
10-12 16:09:19.330  9969 10009 D BtGatt.ScanManager: handling starting scan
10-12 16:09:19.330  9969 10009 D BtGatt.ScanManager: isFilteringSupported
10-12 16:09:19.330  9969 10009 D BluetoothAdapter: enableStandAloneBleMode=
10-12 16:09:19.331  4733  6810 W NearbyMessages: NetworkPollManager:  RPC was requested, but deemed unnecessary.
10-12 16:09:19.333  9969 10009 D BluetoothAdapter: STATE_ON
10-12 16:09:19.335  9969 10009 D BluetoothAdapter: STATE_ON
,10-12 16:09:19.339  9969 10009 D BluetoothAdapter: STATE_ON
10-12 16:09:19.340  9969 10009 D BluetoothAdapter: STATE_ON
10-12 16:09:19.341  9969 10009 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:19.343  9969 10009 D BluetoothAdapter: STATE_ON
,10-12 16:09:19.344  9969 10009 D BluetoothAdapter: STATE_ON
,10-12 16:09:19.357  9969  9990 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 16:09:19.358  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 16:09:19.360  9969 10009 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
,10-12 16:09:19.360  9969 10009 D BtGatt.ScanManager: addFilterToController: 5
10-12 16:09:19.363 10123 10123 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:19.364 10123 10123 D ActivityThread: Added TimaKeyStore provider
10-12 16:09:19.366  3703  3941 I ActivityManager: DSS on for com.samsung.android.radiobasedlocation and scale is 1.0
10-12 16:09:19.368  9969  9990 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=47
10-12 16:09:19.369  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:19.369  9969 10009 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-12 16:09:19.369  9969 10009 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-12 16:09:19.370  9969 10009 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
10-12 16:09:19.380  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 16:09:19.380  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 16:09:19.380  9969 10009 D BtGatt.ScanManager: set filter index= 4 for clientIf= 5
10-12 16:09:19.380  9969 10009 D BtGatt.ScanManager: addFilterToController: 5
,10-12 16:09:19.384  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.384  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.384  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.384  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:19.384  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.384  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.385  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.385  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.385  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.385  3703  4842 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:19.385  9969  9990 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=5, availableSpace=46
10-12 16:09:19.385  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:19.385  9969 10009 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-12 16:09:19.385  9969 10009 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-12 16:09:19.386  9969 10009 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,10-12 16:09:19.390  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=30
10-12 16:09:19.391  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 16:09:19.391  9969 10009 D BtGatt.ScanManager: set filter index= 5 for clientIf= 5
10-12 16:09:19.391  9969 10009 D BtGatt.ScanManager: addFilterToController: 2
,10-12 16:09:19.395  9969  9990 D BtGatt.GattService: onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=45
10-12 16:09:19.396  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 16:09:19.396  9969 10009 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-12 16:09:19.396  9969 10009 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-12 16:09:19.396  9969 10009 D BtGatt.ScanManager: configureFilterParamter 500 10000 1 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =1
,10-12 16:09:19.398 10123 10123 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-12 16:09:19.400 10123 10123 W System  : ClassLoader referenced unknown path: /system/priv-app/RadioBasedLocation/lib/arm64
,10-12 16:09:19.401  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=29
,10-12 16:09:19.401  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:19.401  9969 10009 D BtGatt.ScanManager: configureRegularScanParams() - queue=1
10-12 16:09:19.401  9969 10009 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=0 mLastConfiguredScanSetting=-2147483648
10-12 16:09:19.402  9969 10009 D BtGatt.ScanManager: configureRegularScanParams - scanInterval = 8000configureRegularScanParams - scanWindow = 800
,10-12 16:09:19.405  9969  9990 D BtGatt.GattService: onScanParamSetupCompleted() status=0, clientIf=5
10-12 16:09:19.406  9969  9990 D BtGatt.GattService: onScanParamSetupCompleted : 0
,10-12 16:09:19.414 10123 10123 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:19.420 10123 10123 I [RBL] PathProvider: @onCreate
,10-12 16:09:19.424 10123 10123 I [RBL] ServiceReceiver: @onReceive - rawData : null
,10-12 16:09:19.427  3703  4845 D WifiService: setWifiEnabled: true pid=9839, uid=10033
,10-12 16:09:19.431  3703  3922 I ActivityManager: KPU : put [com.android.defcontainer] : 28104 K
10-12 16:09:19.431  3703  3922 I ActivityManager: Killing 9039:com.android.defcontainer/u0a8 (adj 906): DHA:empty #33
,10-12 16:09:19.433  3703  4845 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-12 16:09:19.434  3703  4845 D WifiControlHistoryProvider: query
10-12 16:09:19.439  3703  3922 D MountService: getExternalStorageMountMode : 1
10-12 16:09:19.439  3703  3922 D MountService: getExternalStorageMountMode : 3
10-12 16:09:19.439  3703  3922 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.diagmonagent
,10-12 16:09:19.460 10139 10139 E Zygote  : v2
10-12 16:09:19.460 10139 10139 I libpersona: KNOX_SDCARD checking this for 1000
10-12 16:09:19.460 10139 10139 I libpersona: KNOX_SDCARD not a persona
,10-12 16:09:19.460 10139 10139 E Zygote  : accessInfo : 0
,10-12 16:09:19.467 10139 10139 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:19.468 10139 10139 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.diagmonagent 
,10-12 16:09:19.469  3703  3922 I ActivityManager: Start proc 10139:com.sec.android.diagmonagent/1000 for broadcast com.sec.android.diagmonagent/.DiagMonConnectivityChangeReciever
,10-12 16:09:19.471  3703  4543 D ActivityManager: cleanUpApplicationRecord -- 9039
10-12 16:09:19.471  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:19.472  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:19.480  3703  4845 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-12 16:09:19.481  3703  4845 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:19.481  3703  4845 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-12 16:09:19.485  3703  4845 I WifiService: Wi-Fi Sharing settings has not been accessed
10-12 16:09:19.485  3703  4845 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-12 16:09:19.485  3703  3927 E WifiController: illegal state found both WifiController and WifiStateMachine
,10-12 16:09:19.499 10139 10139 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:19.500 10139 10139 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:19.502  3703  4180 I ActivityManager: DSS on for com.sec.android.diagmonagent and scale is 1.0
,10-12 16:09:19.528 10139 10139 W System  : ClassLoader referenced unknown path: /system/priv-app/DiagMonAgent/lib/arm64
,10-12 16:09:19.554 10139 10139 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:19.592 10139 10139 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,10-12 16:09:19.644 10139 10139 E SQLiteLog: (1) no such column: currentid
,10-12 16:09:19.645 10139 10139 E DIAGMON_AGENT: [llllIIIIlllIIIlIllIl(906/lllIlIlIIIllIIlIllIl)] android.database.sqlite.SQLiteException: no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1
10-12 16:09:19.645 10139 10139 E DIAGMON_AGENT: #################################################################
10-12 16:09:19.645 10139 10139 E DIAGMON_AGENT: Error Code : 1 (SQLITE_ERROR)
10-12 16:09:19.645 10139 10139 E DIAGMON_AGENT: Caused By : SQL(query) error or missing database.
10-12 16:09:19.645 10139 10139 E DIAGMON_AGENT: 	(no such column: currentid (code 1): , while compiling: SELECT DISTINCT rowid, profileindex, profilename1, profilename2, profilename3, sessionid, notievent, opmode, pushjobid, serviceid, sessionsavestate, notiuievent, notiretrycount, status, appid, uictype, result, number, text, len, size, oplevel, currentid, holdingid FROM profilelist WHERE rowid=1)
10-12 16:09:19.645 10139 10139 E DIAGMON_AGENT: #################################################################
,10-12 16:09:19.684 10139 10139 E SQLiteLog: (1) table profilelist has no column named currentid
10-12 16:09:19.684  3703  4485 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / op:PendingIntent{cd97729: PendingIntentRecord{d9c6aae android broadcastIntent}}
,10-12 16:09:19.685 10139 10139 E SQLiteDatabase: Error inserting number=0 len=0 profilename3=Mformation notiretrycount=0 currentid=-1 size=0 oplevel=0 serviceid= appid=0 profilename2=dm-Server notievent=0 sessionid=null profilename1=api-server status=0 uictype=0 text= holdingid=-1 sessionsavestate=0 profileindex=0 opmode= result=0 pushjobid= notiuievent=0
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: android.database.sqlite.SQLiteException: table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: #################################################################
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: Error Code : 1 (SQLITE_ERROR)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: Caused By : SQL(query) error or missing database.
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	(table profilelist has no column named currentid (code 1): , while compiling: INSERT INTO profilelist(number,len,profilename3,notiretrycount,currentid,size,oplevel,serviceid,appid,profilename2,notievent,sessionid,profilename1,status,uictype,text,holdingid,sessionsavestate,profileindex,opmode,result,pushjobid,notiuievent) VALUES (?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?,?))
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: #################################################################
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1005)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.prepare(SQLiteConnection.java:570)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:588)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:59)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.<init>(SQLiteStatement.java:31)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1771)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1643)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at llllIIIIlllIIIlIllIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:667)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at com.diagmondm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:399)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at IIlIIIIIIllllIIlIIlI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:116)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at com.sec.android.diagmonagent.DiagMonAgentApplication.onCreate(llIIIIlllllIIllIIllI:60)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1032)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5885)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap3(ActivityThread.java)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1703)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:154)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6692)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke,(Native Method)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1468)
10-12 16:09:19.685 10139 10139 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1358)
10-12 16:09:19.687  3703  4485 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T163627, SetElapsed=1837416, nowELAPSED=209891
10-12 16:09:19.693  3703  4485 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20171013T160919 - CU:1000/CP:3703
,10-12 16:09:19.726 10139 10139 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(64/onCreate)] nStatus : 0
,10-12 16:09:19.732 10139 10139 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(77/onCreate)] DiagMon DM Application Start !
10-12 16:09:19.733 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,10-12 16:09:19.734 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-12 16:09:19.734 10139 10139 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
10-12 16:09:19.734 10139 10139 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,10-12 16:09:19.739  3703 10073 D MountService: getExternalStorageMountMode : 1
10-12 16:09:19.739  3703 10073 D MountService: getExternalStorageMountMode : 3
10-12 16:09:19.739  3703 10073 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.app.RilErrorNotifier
,10-12 16:09:19.780 10152 10152 E Zygote  : v2
10-12 16:09:19.780 10152 10152 I libpersona: KNOX_SDCARD checking this for 1000
,10-12 16:09:19.780 10152 10152 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:19.781 10152 10152 E Zygote  : accessInfo : 0
,10-12 16:09:19.783  3703 10073 I ActivityManager: Start proc 10152:com.sec.app.RilErrorNotifier/1000 for broadcast com.sec.app.RilErrorNotifier/.PhoneErrorReceiver
,10-12 16:09:19.789  3703 10073 I ActivityManager: KPU : put [com.samsung.android.bbc.bbcagent] : 27100 K
10-12 16:09:19.789  3703 10073 I ActivityManager: Killing 9100:com.samsung.android.bbc.bbcagent/1000 (adj 906): DHA:empty #33
,10-12 16:09:19.791 10152 10152 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:19.793 10152 10152 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.app.RilErrorNotifier 
,10-12 16:09:19.817  3703  4543 D ActivityManager: cleanUpApplicationRecord -- 9100
,10-12 16:09:19.819  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:19.831 10152 10152 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:19.831 10152 10152 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:19.834  3703  4180 I ActivityManager: DSS on for com.sec.app.RilErrorNotifier and scale is 1.0
,10-12 16:09:19.855 10152 10152 W System  : ClassLoader referenced unknown path: /system/priv-app/PhoneErrService/lib/arm64
,10-12 16:09:19.871 10152 10152 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:19.876 10152 10152 I PhoneErrorReceiver: onReceive
,10-12 16:09:19.882  3703  3725 D MountService: getExternalStorageMountMode : 1
10-12 16:09:19.882  3703  3725 D MountService: getExternalStorageMountMode : 3
10-12 16:09:19.882  3703  3725 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.knox.switcher
,10-12 16:09:19.897  3298  3784 D Netd    : Iface wlan0 link down
,10-12 16:09:19.900  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, false
10-12 16:09:19.900  3703  3796 D Tethering: interfaceStatusChanged wlan0, false
,10-12 16:09:19.906  3703  4289 D wifi    : set interface wlan0 flags (DOWN)
,10-12 16:09:19.911  3703  3928 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 16:09:19.929 10165 10165 E Zygote  : v2
10-12 16:09:19.929 10165 10165 I libpersona: KNOX_SDCARD checking this for 1000
,10-12 16:09:19.929 10165 10165 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:19.931 10165 10165 E Zygote  : accessInfo : 0
,10-12 16:09:19.933  3703  3725 W ActivityManager: Slow operation: 53ms so far, now at startProcess: returned from zygote!
10-12 16:09:19.934  3703  3725 W ActivityManager: Slow operation: 54ms so far, now at startProcess: done updating battery stats
,10-12 16:09:19.934  3703  3725 W ActivityManager: Slow operation: 55ms so far, now at startProcess: building log message
10-12 16:09:19.934  3703  3725 I ActivityManager: Start proc 10165:com.sec.knox.switcher/1000 for broadcast com.sec.knox.switcher/.knoxusage.KnoxUsageReceiver
10-12 16:09:19.935  3703  3725 W ActivityManager: Slow operation: 55ms so far, now at startProcess: starting to update pids map
10-12 16:09:19.935  3703  3725 W ActivityManager: Slow operation: 55ms so far, now at startProcess: done updating pids map
10-12 16:09:19.935  3703  3725 W ActivityManager: Slow operation: 56ms so far, now at startProcess: done starting proc!
,10-12 16:09:19.941 10165 10165 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:09:19.943 10165 10165 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.knox.switcher 
,10-12 16:09:19.951  3703  3725 I ActivityManager: KPU : put [com.facebook.system] : 27228 K
10-12 16:09:19.951  3703  3725 I ActivityManager: Killing 9181:com.facebook.system/u0a12 (adj 906): DHA:empty #33
,10-12 16:09:19.967 10165 10165 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:19.968 10165 10165 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:19.972  3703  3725 I ActivityManager: DSS on for com.sec.knox.switcher and scale is 1.0
,10-12 16:09:19.980  4733  6828 I BeaconBle: Client requested to stop, listener=hjz@706eeb7
,10-12 16:09:19.992  3703  5217 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:09:19.993  3703  5217 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-12 16:09:19.993  3703  5217 D WifiControlHistoryProvider: query
10-12 16:09:19.995  3703  4850 D ActivityManager: cleanUpApplicationRecord -- 9181
10-12 16:09:19.998  4769  4788 D ForegroundUtils: could not check pending caller
10-12 16:09:19.999 10165 10165 W System  : ClassLoader referenced unknown path: /system/app/KnoxSwitcher/lib/arm64
10-12 16:09:19.999  4733  6828 I BeaconBle: Stopping scan on delegate scanner - BT state: 12
,10-12 16:09:20.001  4733  6828 D BluetoothAdapter: STATE_ON
,10-12 16:09:20.002  4733  6828 D BluetoothAdapter: STATE_ON
10-12 16:09:20.002  4733  6828 D BluetoothLeScanner: Stop Scan
,10-12 16:09:20.003  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:20.004  3703  5217 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-12 16:09:20.004  9969  9992 D BtGatt.GattService: stopScan() - queue size =1
,10-12 16:09:20.004  3703  5217 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:20.004  9969  9992 D BtGatt.GattService: stopScan() - queue size =1
10-12 16:09:20.005  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.google.uid.shared, msg: MESSAGE_STOP_SCAN
10-12 16:09:20.005  3703  5217 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
10-12 16:09:20.008  9969  9981 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 16:09:20.008  3703  5217 I WifiService: Wi-Fi Sharing settings has not been accessed
10-12 16:09:20.008  9969 10009 D BtGatt.ScanManager: stop scan
10-12 16:09:20.009  9969 10009 D BtGatt.ScanManager: delete FilterIndex - 3
,10-12 16:09:20.010  3703  5217 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-12 16:09:20.010  3703  3927 E WifiController: illegal state found both WifiController and WifiStateMachine
10-12 16:09:20.013  4733  6828 D BluetoothAdapter: STATE_ON
10-12 16:09:20.014 10165 10165 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
10-12 16:09:20.015  4733  6828 D BluetoothAdapter: STATE_ON
10-12 16:09:20.015  4733  6828 I BeaconBle: Resetting - new scanner available: true
10-12 16:09:20.016  4733  6828 I BeaconBle: 'L' hardware scan: scan stopped, no clients
10-12 16:09:20.016  4733  6828 I BeaconBle: Scan canceled successfully.
,10-12 16:09:20.019 10165 10165 D KnoxUsageDB: getInstance - KnoxUsageDBHelper
10-12 16:09:20.019 10165 10165 D KnoxUsageDB: null == mDbHelperInstance - KnoxUsageDBHelper
10-12 16:09:20.020 10165 10165 D ShareFileProvider: ShareFileProvider | onCreate [0]
,10-12 16:09:20.020 10165 10165 D ShareFileDBHelper: getInstance - ShareFileDBHelper
10-12 16:09:20.020 10165 10165 D ShareFileDBHelper: null == mDbHelperInstance - ShareFileDBHelper
10-12 16:09:20.020 10165 10165 D ShareFileDBHelper: ShareFileDBHelper - Constructor
,10-12 16:09:20.021  3703  4845 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{c7d706: PendingIntentRecord{d3e91c7 com.google.android.gms broadcastIntent}}
10-12 16:09:20.022  4733  6828 W NearbyMessages: Runnable[ScanComplete] not posted since EventLoop is destroyed
10-12 16:09:20.023  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=30
10-12 16:09:20.023  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:20.023  9969 10009 D BtGatt.ScanManager: delete FilterIndex - 4
,10-12 16:09:20.024 10165 10165 I usagelog: received in receiver
10-12 16:09:20.025 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,10-12 16:09:20.029  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=31
10-12 16:09:20.029  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:20.029  9969 10009 D BtGatt.ScanManager: delete FilterIndex - 5
10-12 16:09:20.029 10165 10165 I KnoxUsageLogPro: premStatus:2
,10-12 16:09:20.035  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 16:09:20.035  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:20.035 10165 10165 I KnoxUsageLogPro: isEulaShown : false
10-12 16:09:20.035 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,10-12 16:09:20.035  9969 10009 D BtGatt.ScanManager: configureRegularScanParams() - queue=0
10-12 16:09:20.036  9969 10009 D BtGatt.ScanManager: configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=0
10-12 16:09:20.036  9969 10009 D BtGatt.ScanManager: configureRegularScanParams() - queue emtpy, scan stopped
,10-12 16:09:20.042  3703  3765 I ActivityManager: KPU : put [com.google.android.apps.docs] : 41636 K
10-12 16:09:20.043  3703  3765 I ActivityManager: Killing 9204:com.google.android.apps.docs/u0a93 (adj 906): DHA:empty #33
,10-12 16:09:20.070  5172  5172 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-12 16:09:20.073  5172  8263 I iu.UploadsManager: num queued entries: 0
,10-12 16:09:20.074  5172  8263 I iu.UploadsManager: num updated entries: 0
10-12 16:09:20.077  5172  8263 I iu.SyncManager: NEXT; no task
,10-12 16:09:20.078  3703  3920 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:20.098  3703  4873 D ActivityManager: cleanUpApplicationRecord -- 9204
,10-12 16:09:20.102  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:20.104  3703  3941 D MountService: getExternalStorageMountMode : 1
10-12 16:09:20.105  3703  3941 D MountService: getExternalStorageMountMode : 3
10-12 16:09:20.105  3703  3941 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10041, packageName : com.osp.app.signin
,10-12 16:09:20.113  3703  3928 E WifiHW  : ##################### set firmware type 0 #####################
,10-12 16:09:20.114  3298  3792 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,10-12 16:09:20.115  3298  3792 I WifiHW  : module is semco
10-12 16:09:20.115  3298  3792 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
10-12 16:09:20.115  3298  3792 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
10-12 16:09:20.115  3298  3792 E WifiHW  : TEMP_FAILURE_RETRY complete
,10-12 16:09:20.115  3298  3792 D SoftapController: Softap fwReload - Ok
,10-12 16:09:20.117  3703  3928 E NetworkManagement: wifiFirmwareReload Error reloading wlan0 fw in STA mode: event = 200 210 Softap operation succeeded
,10-12 16:09:20.121  3298  3792 D CommandListener: Setting iface cfg
10-12 16:09:20.121  3298  3792 D CommandListener: Trying to bring down wlan0
10-12 16:09:20.122  3298  3792 D CommandListener: Clearing all IP addresses on wlan0
,10-12 16:09:20.125 10179 10179 E Zygote  : v2
,10-12 16:09:20.125 10179 10179 I libpersona: KNOX_SDCARD checking this for 10041
10-12 16:09:20.125 10179 10179 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:20.127 10179 10179 E Zygote  : accessInfo : 0
,10-12 16:09:20.128  3703  3928 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 16:09:20.130  3703  3941 I ActivityManager: Start proc 10179:com.osp.app.signin/u0a41 for broadcast com.osp.app.signin/.OspReceiver
,10-12 16:09:20.136 10179 10179 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:20.138 10179 10179 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.osp.app.signin 
,10-12 16:09:20.154  3703  4871 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T163616, SetElapsed=1826301, nowELAPSED=210358
,10-12 16:09:20.161  3703  4871 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20171012T163920 - CU:10124/CP:5105
,10-12 16:09:20.163 10179 10179 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:20.164 10179 10179 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:20.166  3703 10074 I ActivityManager: DSS on for com.osp.app.signin and scale is 1.0
,10-12 16:09:20.219 10179 10179 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-12 16:09:20.223 10179 10179 W System  : ClassLoader referenced unknown path: /system/priv-app/SamsungAccount_Dream/lib/arm64
,10-12 16:09:20.247 10179 10179 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:20.262 10179 10179 I SA      : [SSP] onCreated
,10-12 16:09:20.296 10179 10179 D SamsungAnalytics:1.8.22: cf feature is supported
,10-12 16:09:20.304 10179 10179 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
,10-12 16:09:20.310 10179 10179 I SA      : LBE isSupportBixbyModel() FALSE
,10-12 16:09:20.320 10179 10179 I SA      : [TPM] There is no property file
,10-12 16:09:20.331 10179 10179 I SA      : [SCU] isHaveSA() - false
,10-12 16:09:20.340 10179 10179 I SA      : [SS] no samsung account is signed in
,10-12 16:09:20.344 10179 10179 I SA      : [TPM] getModelProperty : null
10-12 16:09:20.344 10179 10179 I SA      : [TPM] getCSCProperty : null
,10-12 16:09:20.348 10179 10179 I SA      : [SCU] isHaveSA() - false
,10-12 16:09:20.350 10179 10179 I SA      : [SCU] == networkStateCheck == false
10-12 16:09:20.350 10179 10179 I SA      : [SS] network off, couldn't connect to DIR
,10-12 16:09:20.356 10179 10179 D BixbyApi_0.1.6: Version Name:2.2.03-46
,10-12 16:09:20.361 10179 10179 I SA      : [DM] init START
,10-12 16:09:20.372 10179 10179 I SA      : [DM] This device is not a Vodafone
,10-12 16:09:20.377 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.378 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.378 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.379 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.379 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.380 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.380 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.380 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.381 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.381 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.382 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.382 10179 10179 W ResourceType: Failure getting entry for 0x7f0b0002 (t=10 e=2) (error -75)
10-12 16:09:20.382 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.383 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.383 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.384 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.384 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.385 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.385 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.385 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.386 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.386 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.387 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.387 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.387 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.388 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.388 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.389 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.389 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.389 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.390 10179 10179 W ResourceType: Failure getting entry for 0x7f0b0005 (t=10 e=5) (error -75)
,10-12 16:09:20.390 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.391 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.391 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.392 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.392 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.392 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.393 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.393 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.394 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.394 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.394 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.395 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.395 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.396 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.396 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.397 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
10-12 16:09:20.397 10179 10179 W ResourceType: No package identifier when getting value for resource number 0x00000000
,10-12 16:09:20.399 10179 10179 I SA      : support phone number id : true
10-12 16:09:20.399 10179 10179 I SA      : [DM] Supports Ref Jpn : true
10-12 16:09:20.399 10179 10179 I SA      : [DM] init END
10-12 16:09:20.400 10179 10179 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,10-12 16:09:20.407 10179 10179 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
10-12 16:09:20.407 10179 10179 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,10-12 16:09:20.418 10179 10179 I SA      : [SLFUCHKMGR] constructor called
,10-12 16:09:20.435 10179 10179 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
10-12 16:09:20.435 10179 10179 I SA      : [OR] == isSIMCardReady false ==
,10-12 16:09:20.435 10179 10179 I SA      : [SCU] == networkStateCheck == false
10-12 16:09:20.435 10179 10179 I SA      : [OR] onReceive END
,10-12 16:09:20.443  3703  3922 I ActivityManager: KPU : put [com.facebook.appmanager] : 23352 K
10-12 16:09:20.443  3703  3922 I ActivityManager: Killing 9158:com.facebook.appmanager/u0a98 (adj 906): DHA:empty #33
,10-12 16:09:20.447  3703  3765 D MountService: getExternalStorageMountMode : 1
10-12 16:09:20.447  3703  3765 D MountService: getExternalStorageMountMode : 3
10-12 16:09:20.447  3703  3765 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.svcagent
,10-12 16:09:20.469 10202 10202 E Zygote  : v2
,10-12 16:09:20.469 10202 10202 I libpersona: KNOX_SDCARD checking this for 1000
10-12 16:09:20.469 10202 10202 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:20.470 10202 10202 E Zygote  : accessInfo : 0
10-12 16:09:20.470  3703  3765 I ActivityManager: Start proc 10202:com.samsung.android.svcagent/1000 for broadcast com.samsung.android.svcagent/com.samsung.android.service.svcagent.BootReceiver
10-12 16:09:20.472  3703  4850 D ActivityManager: cleanUpApplicationRecord -- 9158
10-12 16:09:20.476  4769  4788 D ForegroundUtils: could not check pending caller
10-12 16:09:20.476 10202 10202 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:20.477 10202 10202 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.svcagent 
,10-12 16:09:20.500 10202 10202 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:20.500 10202 10202 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:20.502  3703  3724 I ActivityManager: DSS on for com.samsung.android.svcagent and scale is 1.0
,10-12 16:09:20.519  3703  3920 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:09:20.519  3703  3920 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-12 16:09:20.520  3703  3920 D WifiControlHistoryProvider: query
,10-12 16:09:20.522 10202 10202 W System  : ClassLoader referenced unknown path: /system/priv-app/SVCAgent/lib/arm64
,10-12 16:09:20.527  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:20.527  3703  3920 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-12 16:09:20.528  3703  3920 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:20.529  3703  3920 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-12 16:09:20.533  3703  3920 I WifiService: Wi-Fi Sharing settings has not been accessed
10-12 16:09:20.533  3703  3920 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-12 16:09:20.534  3703  3927 E WifiController: illegal state found both WifiController and WifiStateMachine
,10-12 16:09:20.535 10202 10202 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:20.543 10202 10202 I SVCAgent: Ignore network change.
,10-12 16:09:20.545  3703  4850 D MountService: getExternalStorageMountMode : 1
10-12 16:09:20.546  3703  4850 D MountService: getExternalStorageMountMode : 3
10-12 16:09:20.546  3703  4850 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10064, packageName : com.samsung.android.themestore
,10-12 16:09:20.565 10215 10215 E Zygote  : v2
10-12 16:09:20.566 10215 10215 I libpersona: KNOX_SDCARD checking this for 10064
,10-12 16:09:20.566 10215 10215 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:20.566 10215 10215 E Zygote  : accessInfo : 0
,10-12 16:09:20.570  3703  4850 I ActivityManager: Start proc 10215:com.samsung.android.themestore/u0a64 for broadcast com.samsung.android.themestore/.manager.autoSelfUpgradeService.AutoSelfUpgradeReceiver
,10-12 16:09:20.572 10215 10215 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:20.573 10215 10215 I SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.themestore 
,10-12 16:09:20.574  3703  4850 I ActivityManager: KPU : put [com.google.android.partnersetup] : 26920 K
,10-12 16:09:20.574  3703  4850 I ActivityManager: Killing 9262:com.google.android.partnersetup/u0a23 (adj 906): DHA:empty #33
,10-12 16:09:20.589  3239  3239 E audit   : type=1320 audit(1507817360.585:528): 
,10-12 16:09:20.597 10215 10215 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:20.598 10215 10215 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:20.600  3703  3724 I ActivityManager: DSS on for com.samsung.android.themestore and scale is 1.0
,10-12 16:09:20.605  3239  3239 E audit   : type=1320 audit(1507817360.595:529): 
,10-12 16:09:20.607  3703  4851 D ActivityManager: cleanUpApplicationRecord -- 9262
,10-12 16:09:20.611  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:20.622  3239  3239 E audit   : type=1320 audit(1507817360.615:530): 
,10-12 16:09:20.627 10215 10215 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-12 16:09:20.628 10215 10215 W System  : ClassLoader referenced unknown path: /system/priv-app/GalaxyThemes/lib/arm64
,10-12 16:09:20.636  3239  3239 E audit   : type=1320 audit(1507817360.625:531): 
,10-12 16:09:20.643 10215 10215 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:20.662 10215 10215 D a       : Exist Config : false
,10-12 16:09:20.664 10215 10215 D a       : getMcc
,10-12 16:09:20.669 10215 10215 D as      : isQaMode
,10-12 16:09:20.675 10215 10215 D a       : getMnc
10-12 16:09:20.675 10215 10215 D a       : getCsc
10-12 16:09:20.676 10215 10215 D a       : getSystemCountryCode
,10-12 16:09:20.676 10215 10215 D a       : getImei
,10-12 16:09:20.681 10215 10215 D as      : getMd5HashString
10-12 16:09:20.682 10215 10215 D as      : getSha256HashString
,10-12 16:09:20.682 10215 10215 D a       : getModelName
10-12 16:09:20.682 10215 10215 D a       : getVirtualModelName
,10-12 16:09:20.683 10215 10215 D a       : getAndroidSDKVersion
10-12 16:09:20.683 10215 10215 D a       : getLanguageCode
10-12 16:09:20.683 10215 10215 D a       : getCountryCode
,10-12 16:09:20.685 10215 10215 D a       : getNetworkType
,10-12 16:09:20.691 10215 10215 D w       : isSupportedAodSystemFeature
10-12 16:09:20.695 10215 10215 D a       : getThemeFrameworkVersion
,10-12 16:09:20.702 10215 10215 D a       : isLogPrintMode
,10-12 16:09:20.706 10215 10215 D as      : isQaMode
,10-12 16:09:20.718 10215 10215 D a       : getVerName
,10-12 16:09:20.720 10215 10215 D a       : getVerCode
,10-12 16:09:20.726 10215 10215 D a       : getPackageName
,10-12 16:09:20.727 10215 10215 D a       : getAutoUpgradeInterval
,10-12 16:09:20.731 10215 10215 D a       : loadCountrySearchEx
,10-12 16:09:20.738 10215 10215 D a       : com.samsung.android.themestore.g.c.b.u; class invalid for deserialization
,10-12 16:09:20.739 10215 10215 I a       : # initConfig Time : 80
10-12 16:09:20.739 10215 10215 I a       : ● MCC/NNC: /0
10-12 16:09:20.739 10215 10215 I a       : ● Model: SM-G930F_TM
10-12 16:09:20.739 10215 10215 I a       : ● MyApp Version: 2.1.56-70306
,10-12 16:09:20.739 10215 10215 I a       : ● OS Version: 24
10-12 16:09:20.740 10215 10215 I a       : ● IsSupportedSView: true
,10-12 16:09:20.757 10215 10215 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,10-12 16:09:20.784 10215 10215 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,10-12 16:09:20.795  3703  4871 I ActivityManager: KPU : put [com.samsung.android.SettingsReceiver] : 26956 K
10-12 16:09:20.796  3703  4871 I ActivityManager: Killing 8363:com.samsung.android.SettingsReceiver/1000 (adj 906): DHA:empty #33
,10-12 16:09:20.809  8005  8005 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
10-12 16:09:20.809  8005  8005 E SPPClientService: [SystemStateMoniter] Current Time : 211013
,10-12 16:09:20.811  8005  8005 E SPPClientService: [SystemStateMoniter] No Connect : true
,10-12 16:09:20.819  3703  3765 D MountService: getExternalStorageMountMode : 1
10-12 16:09:20.819  3703  3765 D MountService: getExternalStorageMountMode : 3
10-12 16:09:20.820  3703  3765 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 5005, packageName : com.samsung.android.allshare.service.fileshare
,10-12 16:09:20.847 10245 10245 E Zygote  : v2
10-12 16:09:20.847 10245 10245 I libpersona: KNOX_SDCARD checking this for 5005
10-12 16:09:20.847 10245 10245 I libpersona: KNOX_SDCARD not a persona
,10-12 16:09:20.850 10245 10245 E Zygote  : accessInfo : 0
,10-12 16:09:20.851  3703  3765 I ActivityManager: Start proc 10245:com.samsung.android.allshare.service.fileshare/5005 for broadcast com.samsung.android.allshare.service.fileshare/.FileShareBroadcastReceiver
,10-12 16:09:20.861  3703  3928 D wifi    : set interface wlan0 flags (UP)
10-12 16:09:20.861  3298  3784 D Netd    : Iface wlan0 link up
10-12 16:09:20.863  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:20.863  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
10-12 16:09:20.863 10245 10245 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:09:20.865 10245 10245 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.allshare.service.fileshare 
10-12 16:09:20.867  3703  3928 I WifiHAL : Initializing wifi
10-12 16:09:20.867  3703  3928 I WifiHAL : Creating socket
,10-12 16:09:20.871  3703  3928 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-12 16:09:20.871  3703  3928 D wifi    : Did set static halHandle = 0x71766e8d20
10-12 16:09:20.871  3703  3928 D wifi    : halHandle = 0x71766e8d20, mVM = 0x71a2490300, mCls = 0x102bbe
10-12 16:09:20.871  3703  3928 D wifi    : array field set
10-12 16:09:20.873  3703  3928 I WifiHW  : CCMode is disabled, skip verifying wpa_supplicant
10-12 16:09:20.873  3703 10251 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=487318261024
10-12 16:09:20.873  3703 10251 D wifi    : waitForHalEvents called, vm = 0x71a2490300, obj = 0x102bbe, env = 0x7170dd4ac0
10-12 16:09:20.873  3703  3928 E WifiHW  : supplicant_name : p2p_supplicant
10-12 16:09:20.876  3703 10073 D ActivityManager: cleanUpApplicationRecord -- 8363
10-12 16:09:20.878  8005 10252 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
10-12 16:09:20.879  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:20.895 10245 10245 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:20.896 10245 10245 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:20.898  3703  4842 I ActivityManager: DSS on for com.samsung.android.allshare.service.fileshare and scale is 1.0
,10-12 16:09:20.936 10245 10245 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:20.943 10245 10245 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,10-12 16:09:20.945 10245 10245 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
,10-12 16:09:20.947 10259 10259 I FIPS_bssl: FIPS (v1.1) approved mode (1) | 10259 | /system/bin/wpa_supplicant
10-12 16:09:20.947 10259 10259 D SecurityManagerNative: SecurityManagerNative v2.7.2.2 On 64bit PLATFORM With BORINGSSL
,10-12 16:09:20.949 10259 10259 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
10-12 16:09:20.950 10259 10259 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 16:09:20.953 10259 10259 I wpa_supplicant: set_csc_config : ifname(wlan0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x400008), vendorssid_list()
10-12 16:09:20.953 10259 10259 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,10-12 16:09:20.954  3112  3112 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10259
10-12 16:09:20.955  3112  3112 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
10-12 16:09:20.955 10259 10259 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
10-12 16:09:20.955 10259 10259 I wpa_supplicant: ssSupport state is = 1
10-12 16:09:20.955 10259 10259 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
10-12 16:09:20.955 10259 10259 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
10-12 16:09:20.955  3112  3112 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
10-12 16:09:20.956  3112  3112 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 10259
10-12 16:09:20.956  3112  3112 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,10-12 16:09:20.964 10245 10245 D FileShare: Outbound.stopDelayTimer - 
,10-12 16:09:20.977  3703  3928 D SecContentProvider: insert(), uri = 2
,10-12 16:09:20.979  3703  3920 I ActivityManager: KPU : put [com.samsung.android.app.mirrorlink] : 21044 K
,10-12 16:09:20.980  3703  3920 I ActivityManager: Killing 9280:com.samsung.android.app.mirrorlink/1000 (adj 906): DHA:empty #33
,10-12 16:09:20.980  3703  3928 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:20.984  3703  3928 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 16:09:20.987  3703  3928 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
10-12 16:09:20.991  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
10-12 16:09:20.992  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
10-12 16:09:20.993  3703  3955 I WifiHs20Service: Message received 5011
10-12 16:09:20.995  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=2 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-12 16:09:21.002  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-12 16:09:21.002  3703  4039 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
,10-12 16:09:21.006  3703  3703 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
10-12 16:09:21.006  3703  4484 D SLocation: checkWifiInfo
10-12 16:09:21.007  3703  4039 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
,10-12 16:09:21.015  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:21.038  3703  4842 D ActivityManager: cleanUpApplicationRecord -- 9280
10-12 16:09:21.038 10123 10123 I [RBL] ServiceReceiver: @onReceive - rawData : null
10-12 16:09:21.040  3703  3724 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:09:21.044  3703  3724 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-12 16:09:21.044  3703  3724 D WifiControlHistoryProvider: query
,10-12 16:09:21.048  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:21.063  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:21.072 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,10-12 16:09:21.072 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-12 16:09:21.073 10139 10139 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
10-12 16:09:21.073  3703  3724 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
,10-12 16:09:21.074  3703  3724 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:21.075  3703  3724 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-12 16:09:21.082  3703  3724 I WifiService: Wi-Fi Sharing settings has not been accessed
10-12 16:09:21.082  3703  3724 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-12 16:09:21.085 10152 10152 I PhoneErrorReceiver: onReceive
,10-12 16:09:21.094 10165 10165 I usagelog: received in receiver
10-12 16:09:21.094 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
,10-12 16:09:21.095 10165 10165 I KnoxUsageLogPro: premStatus:2
10-12 16:09:21.096 10165 10165 I KnoxUsageLogPro: isEulaShown : false
10-12 16:09:21.096 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,10-12 16:09:21.106  9907  9907 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
10-12 16:09:21.107  9907  9907 D SecurityLogAgent: NetworkReceiver : Wifi_state is 0
,10-12 16:09:21.111  3703  3725 D MountService: getExternalStorageMountMode : 1
10-12 16:09:21.111  3703  3725 D MountService: getExternalStorageMountMode : 3
10-12 16:09:21.111  3703  3725 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10172, packageName : com.example.ThaliTestApp
,10-12 16:09:21.118  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,10-12 16:09:21.130 10262 10262 E Zygote  : v2
,10-12 16:09:21.130  3703  3725 I ActivityManager: Start proc 10262:com.example.ThaliTestApp/u0a172 for broadcast com.example.ThaliTestApp/io.jxcore.node.ConnectivityChangeListener
10-12 16:09:21.130 10262 10262 I libpersona: KNOX_SDCARD checking this for 10172
10-12 16:09:21.130 10262 10262 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:21.131 10262 10262 E Zygote  : accessInfo : 0
,10-12 16:09:21.140 10262 10262 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:21.141 10262 10262 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.example.ThaliTestApp 
,10-12 16:09:21.145 10262 10262 I art     : Late-enabling -Xcheck:jni
,10-12 16:09:21.150  3239  3239 E audit   : type=1320 audit(1507817361.145:532): 
,10-12 16:09:21.154 10259 10259 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,10-12 16:09:21.165  3239  3239 E audit   : type=1320 audit(1507817361.155:533): 
,10-12 16:09:21.182 10262 10262 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:21.183  3239  3239 E audit   : type=1320 audit(1507817361.175:534): 
10-12 16:09:21.183 10262 10262 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:21.187 10259 10259 W wpa_supplicant: Loading system cred
,10-12 16:09:21.187 10259 10259 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
10-12 16:09:21.187  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10259
10-12 16:09:21.188  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
10-12 16:09:21.188 10259 10259 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
10-12 16:09:21.188 10259 10259 I wpa_supplicant: ssSupport state is = 1
10-12 16:09:21.188  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
10-12 16:09:21.189 10259 10259 E wpa_supplicant: getSavedIMSI cannot open /data/misc/radio/kmem: No such file or directory
10-12 16:09:21.189 10259 10259 I wpa_supplicant: [getIMSI]: sim_num 0
,10-12 16:09:21.191  3703  3941 I ActivityManager: DSS on for com.example.ThaliTestApp and scale is 1.0
,10-12 16:09:21.200  3239  3239 E audit   : type=1320 audit(1507817361.195:535): 
,10-12 16:09:21.240 10259 10259 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-12 16:09:21.240  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:09:21.241  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:09:21.242  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:21.243  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
10-12 16:09:21.244  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:21.244  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:09:21.251 10262 10262 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-12 16:09:21.287 10262 10262 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:21.301  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.302  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.302  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.302  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.302  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.302  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.302  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.302  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.302  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.303  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.331 10259 10259 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
10-12 16:09:21.331 10259 10259 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,10-12 16:09:21.332  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10259
,10-12 16:09:21.333  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
10-12 16:09:21.333 10259 10259 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
10-12 16:09:21.333  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
10-12 16:09:21.333 10259 10259 I wpa_supplicant: ssSupport state is = 1
,10-12 16:09:21.338 10259 10259 E wpa_supplicant: nl80211: Could not configure driver mode
10-12 16:09:21.338 10259 10259 I wpa_supplicant: nl80211: deinit ifname=p2p0 disabled_11b_rates=0
10-12 16:09:21.339 10259 10259 E wpa_supplicant: p2p0: Failed to initialize driver interface
,10-12 16:09:21.342 10259 10259 I wpa_supplicant: set_csc_config : ifname(p2p0), certi_flags(0x0), autoconnect_flags(0x0), opbranding_flags(0x0), boolean_flags(0x0), vendorssid_list()
10-12 16:09:21.342 10259 10259 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,10-12 16:09:21.343  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 10259
10-12 16:09:21.343  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
10-12 16:09:21.343 10259 10259 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
10-12 16:09:21.344 10259 10259 I wpa_supplicant: ssSupport state is = 1
10-12 16:09:21.344  3112  3112 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,10-12 16:09:21.356 10262 10262 D jxcore_app_log: JniHelper::setJavaVM(0xe4fb4000), pthread_self() = -397257420
10-12 16:09:21.356 10262 10262 E JX-Cordova: JXcore wasn't initialized yet
,10-12 16:09:21.362  3703  3922 D MountService: getExternalStorageMountMode : 1
10-12 16:09:21.362  3703  3922 D MountService: getExternalStorageMountMode : 3
10-12 16:09:21.362  3703  3922 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10173, packageName : com.rockwellautomation.AppPlatformP2P
,10-12 16:09:21.397 10281 10281 E Zygote  : v2
10-12 16:09:21.397 10281 10281 I libpersona: KNOX_SDCARD checking this for 10173
10-12 16:09:21.397 10281 10281 I libpersona: KNOX_SDCARD not a persona
,10-12 16:09:21.399 10281 10281 E Zygote  : accessInfo : 0
10-12 16:09:21.400  3703  3922 I ActivityManager: Start proc 10281:com.rockwellautomation.AppPlatformP2P/u0a173 for broadcast com.rockwellautomation.AppPlatformP2P/io.jxcore.node.ConnectivityChangeListener
,10-12 16:09:21.409  3703  3922 I ActivityManager: KPU : put [com.samsung.android.scloud] : 28680 K
10-12 16:09:21.409  3703  3922 I ActivityManager: Killing 9295:com.samsung.android.scloud/5009 (adj 906): DHA:empty #33
,10-12 16:09:21.410 10281 10281 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:21.412 10281 10281 I SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.rockwellautomation.AppPlatformP2P 
,10-12 16:09:21.415 10281 10281 I art     : Late-enabling -Xcheck:jni
,10-12 16:09:21.438  3703  4850 D ActivityManager: cleanUpApplicationRecord -- 9295
,10-12 16:09:21.440  4769  4782 D ForegroundUtils: could not check pending caller
,10-12 16:09:21.443 10281 10281 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:21.444 10281 10281 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:21.446  3703  4872 I ActivityManager: DSS on for com.rockwellautomation.AppPlatformP2P and scale is 1.0
,10-12 16:09:21.479 10259 10259 I wpa_supplicant: rfkill: Cannot get wiphy information
,10-12 16:09:21.484 10281 10281 I art     : Starting a blocking GC AddRemoveAppImageSpace
,10-12 16:09:21.495 10259 10259 I wpa_supplicant: P2P: Set prekey state (NONE -> NONE)
,10-12 16:09:21.509 10281 10281 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:21.531  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.531  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.531  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.532  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.532  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.534  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.535  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.535  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.536  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.536  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.592  3703  4872 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:09:21.592  3703  4872 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-12 16:09:21.593  3703  4872 D WifiControlHistoryProvider: query
,10-12 16:09:21.599  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-12 16:09:21.599 10281 10281 D jxcore_app_log: JniHelper::setJavaVM(0xe4fb4000), pthread_self() = -397257420
10-12 16:09:21.599  3703  4872 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-12 16:09:21.599 10281 10281 E JX-Cordova: JXcore wasn't initialized yet
,10-12 16:09:21.600  3703  4872 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:21.601  3703  4872 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-12 16:09:21.604  3703  4872 I WifiService: Wi-Fi Sharing settings has not been accessed
10-12 16:09:21.605  3703  4872 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-12 16:09:21.610  3703  4871 I ActivityManager: KPU : put [com.samsung.android.sm.devicesecurity] : 27664 K
10-12 16:09:21.610  3703  4871 I ActivityManager: Killing 7148:com.samsung.android.sm.devicesecurity/5012 (adj 906): DHA:empty #33
,10-12 16:09:21.614  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.614  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.614  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.614  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.614  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.615  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.615  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.615  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.615  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.615  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.620  3703  4180 D MountService: getExternalStorageMountMode : 1
10-12 16:09:21.620  3703  4180 D MountService: getExternalStorageMountMode : 3
,10-12 16:09:21.621  3703  4180 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10003, packageName : com.sec.android.provider.badge
,10-12 16:09:21.645 10296 10296 E Zygote  : v2
10-12 16:09:21.645 10296 10296 I libpersona: KNOX_SDCARD checking this for 10003
10-12 16:09:21.645 10296 10296 I libpersona: KNOX_SDCARD not a persona
,10-12 16:09:21.646  3703  4180 I ActivityManager: Start proc 10296:com.sec.android.provider.badge/u0a3 for broadcast com.sec.android.provider.badge/.BadgeCountReceiver
10-12 16:09:21.646 10296 10296 E Zygote  : accessInfo : 0
10-12 16:09:21.647  3703  4543 D ActivityManager: cleanUpApplicationRecord -- 7148
,10-12 16:09:21.654  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:21.656 10296 10296 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:21.658 10296 10296 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.provider.badge 
,10-12 16:09:21.688 10296 10296 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:21.689 10296 10296 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:21.691  3703  5217 I ActivityManager: DSS on for com.sec.android.provider.badge and scale is 1.0
,10-12 16:09:21.714 10296 10296 W System  : ClassLoader referenced unknown path: /system/priv-app/BadgeProvider_N/lib/arm64
,10-12 16:09:21.728 10296 10296 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:21.738 10296 10296 D BadgeProvider: onCreate
10-12 16:09:21.738 10296 10296 D BadgeProvider: DatabaseHelper
,10-12 16:09:21.742 10296 10296 D BadgeCountReceiver: badge intent : Intent { act=com.sec.intent.action.BADGE_COUNT_UPDATE flg=0x10 cmp=com.sec.android.provider.badge/.BadgeCountReceiver launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:21.743 10296 10296 D BadgeCountReceiver: packageName: com.samsung.android.email.provider, className: com.samsung.android.email.ui.activity.MessageListXL, count: 0
,10-12 16:09:21.750 10296 10296 D BadgeProvider: onOpen
,10-12 16:09:21.753 10296 10296 D BaseReflect: null getOwnClass TEST
10-12 16:09:21.753 10296 10296 D MethodReflector: android.content.ContentResolver getClass TEST
10-12 16:09:21.754 10296 10296 D BaseReflect: class android.content.ContentResolver isSupportClass TEST
,10-12 16:09:21.754 10296 10296 D BaseReflect: class android.content.ContentResolver getOwnClass TEST
,10-12 16:09:21.758 10296 10296 D MethodReflector: notifyChange is called
10-12 16:09:21.758  4919  4919 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
,10-12 16:09:21.761 10296 10296 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
10-12 16:09:21.761 10296 10296 D BadgeProvider: sendNotify, [notify] : null
10-12 16:09:21.761  4919  4919 D LauncherApplication: onChange: mBadgeRefreshHandler removeCallbacks
10-12 16:09:21.761 10296 10296 D BadgeProvider: update, getCallingPackage() : com.sec.android.provider.badge
10-12 16:09:21.761 10296 10296 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
10-12 16:09:21.762 10296 10296 D BadgeProvider: update, [uri.query] : null
10-12 16:09:21.762 10296 10296 D BadgeProvider: update, [BadgeCount] : badgecount=0
10-12 16:09:21.762 10296 10296 D BadgeProvider: update, [UpdateCount] : 1
,10-12 16:09:21.780  9907  9907 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
10-12 16:09:21.781  9907  9907 D SecurityLogAgent: NetworkReceiver : Wifi_state is 1
,10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.792  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.793  3703  3724 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.803  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.803  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.803  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.803  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.803  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.804  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.804  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.804  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.804  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.804  3703  5217 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.811  3703  3922 I ActivityManager: KPU : put [com.samsung.android.themecenter] : 26760 K
,10-12 16:09:21.812  3703  3922 I ActivityManager: Killing 9317:com.samsung.android.themecenter/1000 (adj 906): DHA:empty #33
10-12 16:09:21.815  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.815  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.815  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.815  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.815  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.816  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.816  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.816  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.816  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.816  3703  4851 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.825  9907  9907 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
10-12 16:09:21.825  9907  9907 D SecurityLogAgent: NetworkReceiver : Wifi_state is 2
,10-12 16:09:21.836  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.837  3703 10074 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.839  3703 10074 D ActivityManager: cleanUpApplicationRecord -- 9317
,10-12 16:09:21.842  4646  4646 D io_stats: !@   8,0 r 25862 2287880 w 4900 203756 d 647 73896 f 1984 1984 iot 11730 10901 th 473616 0 0 pt 0 inp 0 0 212.045
,10-12 16:09:21.851  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.851  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.851  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.851  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.851  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.852  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.852  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.852  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.852  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.852  3703 10073 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.852  4769  4782 D ForegroundUtils: could not check pending caller
,10-12 16:09:21.861  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.861  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.861  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.861  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.861  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.862  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.862  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.862  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.862  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:21.862  3703  4180 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:21.962  4919  4919 D LauncherApplication: run: mBadgeRefreshHandler reloadBadges
10-12 16:09:21.962  4919  4919 D Launcher.Model: reloadBadges entered.
,10-12 16:09:21.993 10296 10308 D BadgeProvider: query, [selection] : null
,10-12 16:09:22.007  4919  5014 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.email.provider = 0
,10-12 16:09:22.007  4919  5014 D BadgeCache: 1. updateBadgeCounts: com.android.mms = 0
,10-12 16:09:22.007  4919  5014 D BadgeCache: 1. updateBadgeCounts: com.sec.android.app.samsungapps = 0
,10-12 16:09:22.008  4919  5014 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 1
10-12 16:09:22.008  4919  5014 D BadgeCache: 2. updateBadgeCounts: com.android.settings/.Settings = 1
,10-12 16:09:22.008  4919  5014 D BadgeCache: 1. updateBadgeCounts: com.android.settings = 0
10-12 16:09:22.008  4919  5014 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.sm = 0
,10-12 16:09:22.008  4919  5014 D BadgeCache: 1. updateBadgeCounts: com.samsung.android.lool = 0
,10-12 16:09:22.008  4919  5014 D BadgeCache: 1. updateBadgeCounts: com.wssyncmldm = 1
10-12 16:09:22.008  4919  5014 D BadgeCache: 2. updateBadgeCounts: com.wssyncmldm/com.samsung.android.app.fotaclient.FotaApplication = 1
10-12 16:09:22.017  4919  5014 D BadgeCache: updated Badged:2
10-12 16:09:22.017  4919  5014 D BadgeCache: updateBadgeCounts:2
10-12 16:09:22.017  4919  5014 D Launcher.Model: reloadBadges, badges count : 2
10-12 16:09:22.018  4919  5014 D Launcher.Model: appItems:0 homeItems:0
,10-12 16:09:22.032  3703  3776 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=212208 mStackState=3 mControllerTxTimeMs=0 mControllerTxTimePerLevelMs=[] mControllerRxTimeMs=0 mControllerIdleTimeMs=0 mControllerEnergyUsed=0 }
,10-12 16:09:22.058 10259 10259 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,10-12 16:09:22.062  3703  3928 I WifiConnectivityManager: User band preference: 0
,10-12 16:09:22.065  3703  3928 D WifiConfigManager: Loading config and enabling all networks 
,10-12 16:09:22.083  3703  3928 D WifiConfigStore: readNetwork skipInternetCheck
,10-12 16:09:22.102  3703  5698 D SSRM:f  : SIOP:: AP = 310, PST = 301 (W:10), CP = 249, CUR = 128, LCD = 57
,10-12 16:09:22.114  3703  3928 D WifiConfigStore: readNetwork skipInternetCheck
,10-12 16:09:22.114  3703  3920 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:09:22.115  3703  3920 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
10-12 16:09:22.115  3703  3920 D WifiControlHistoryProvider: query
,10-12 16:09:22.127  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:22.127  3703  3920 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-12 16:09:22.128  3703  3920 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:22.129  3703  3920 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
,10-12 16:09:22.133  3703  3920 I WifiService: Wi-Fi Sharing settings has not been accessed
,10-12 16:09:22.134  3703  3920 D WifiService: unRegisterForSContext() : skip - it does not registered.
,10-12 16:09:22.140  3703  3928 D WifiConfigStore: readNetwork skipInternetCheck
,10-12 16:09:22.151  3703  3928 D WifiConfigStore: readNetwork skipInternetCheck
,10-12 16:09:22.162  3703  3928 D WifiConfigStore: readNetwork skipInternetCheck
,10-12 16:09:22.174  3703  3928 D WifiConfigStore: readNetwork skipInternetCheck
,10-12 16:09:22.183  3703  3928 W WifiNetworkHistory: Upgrading network 4 to android.uid.system:1000
,10-12 16:09:22.184  3703  3928 W WifiNetworkHistory: Upgrading network 0 to android.uid.system:1000
10-12 16:09:22.184  3703  3928 W WifiNetworkHistory: Upgrading network 1 to android.uid.system:1000
,10-12 16:09:22.185  3703  3928 W WifiNetworkHistory: Upgrading network 5 to android.uid.system:1000
10-12 16:09:22.185  3703  3928 W WifiNetworkHistory: Upgrading network 2 to android.uid.system:1000
,10-12 16:09:22.186  3703  3928 W WifiNetworkHistory: Upgrading network 3 to android.uid.system:1000
,10-12 16:09:22.187  3703  3928 D WifiConfigManager: loaded 0 passpoint configs
,10-12 16:09:22.192  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
10-12 16:09:22.192  3703  3928 D WifiNative-wlan0: callSECApiBoolean - ID [301]
10-12 16:09:22.192  3703  3703 D WifiHs20Service: reason: 2
10-12 16:09:22.192  3703  3955 I WifiHs20Service: Message received 5014
10-12 16:09:22.192  3703  3955 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
10-12 16:09:22.192  3703  3955 E WifiHs20Service: The changed config is NULL
10-12 16:09:22.192 10259 10259 I wpa_supplicant: HOTSPOT20_ENABLE called ON
,10-12 16:09:22.206  3703  3928 D WifiNative-wlan0: callSECApiInt - ID [65]
,10-12 16:09:22.211  3703  3703 D WifiController: [FCC]setFccChannel() is called !!!
10-12 16:09:22.211  3703  3703 D WifiController: [FCC]Airplane on, setFccChannel(0)!!!
10-12 16:09:22.211  3703  3703 D WifiStateMachine: setFccChannel: channel = 0
,10-12 16:09:22.212  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.WIFI_STATE_CHANGED
,10-12 16:09:22.212  3703  3954 D HS20StateMachine: WIFI_STATE_ENABLED
10-12 16:09:22.212  3703  3954 D HS20StateMachine: reloadCredentialsToSupplicant
10-12 16:09:22.212  3703  3954 D WifiHs20DBHandler: getCredentialIds
10-12 16:09:22.213  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.WIFI_STATE_CHANGED
10-12 16:09:22.213  3703  3955 I WifiHs20Service: Message received 5011
10-12 16:09:22.215  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=135173 arg1=3 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:22.218  3703  3928 D WifiNative-wlan0: callSECApiBoolean - ID [13]
10-12 16:09:22.219 10259 10259 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
10-12 16:09:22.221  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-12 16:09:22.222  3703  4039 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
10-12 16:09:22.225  9969  9969 D A2dpService: A2dpService - WIFI_STATE_ENABLED
10-12 16:09:22.225  9969  9969 I BluetoothA2dpServiceJni: Attempting to set busy level
10-12 16:09:22.228  3703  4039 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
10-12 16:09:22.228  3703  3703 D SLocation: BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
10-12 16:09:22.228  3703  4484 D SLocation: checkWifiInfo
10-12 16:09:22.229  3703  4484 W SLocation: No Active Data Connection
10-12 16:09:22.232  9839  9839 D BluetoothAdapter: STATE_ON
,10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 16:09:22.235  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 16:09:22.235  9907  9907 D SecurityLogAgent: NetworkReceiver : Network Change Receiver Is Called
10-12 16:09:22.236  9907  9907 D SecurityLogAgent: NetworkReceiver : Wifi_state is 3
,10-12 16:09:22.238  3703  3954 D MountService: getExternalStorageMountMode : 1
10-12 16:09:22.239  3703  3954 D MountService: getExternalStorageMountMode : 3
10-12 16:09:22.239  3703  3954 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10114, packageName : com.samsung.hs20provider
10-12 16:09:22.240  9839  9839 D BluetoothAdapter: STATE_ON
,10-12 16:09:22.243  9839  9839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,10-12 16:09:22.261 10312 10312 E Zygote  : v2
10-12 16:09:22.261 10312 10312 I libpersona: KNOX_SDCARD checking this for 10114
10-12 16:09:22.261 10312 10312 I libpersona: KNOX_SDCARD not a persona
,10-12 16:09:22.263 10312 10312 E Zygote  : accessInfo : 0
,10-12 16:09:22.271  3703  3954 I ActivityManager: Start proc 10312:com.samsung.hs20provider/u0a114 for content provider com.samsung.hs20provider/.Hs20Provider
,10-12 16:09:22.273 10312 10312 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:09:22.274  3703  3928 D WifiNative-HAL: Setting external_sim to 1
,10-12 16:09:22.275  3703  3928 D wifi    : setting dfs flag to true, 0x71809c7ba0
10-12 16:09:22.275 10312 10312 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.samsung.hs20provider 
10-12 16:09:22.276  9907  9907 D SecurityLogAgent: NetworkReceiver : SendSecurityReport is off
10-12 16:09:22.276  3703  3928 D WifiStateMachine: Setting OUI to DA-A1-19
10-12 16:09:22.276  3703  3928 D wifi    : setting scan oui 0x71809c7ba0
10-12 16:09:22.276  3703  3928 D WifiHAL : Sending mac address OUI
10-12 16:09:22.278  3703  3928 D WifiCountryCode: [setCountryCodeNative] persist, Airplane mode return !!!
10-12 16:09:22.278  3703  3928 E WifiStateMachine: SupplicantStarted - enter() isAirplaneModeEnabled !!  
10-12 16:09:22.278  3703  3928 D WifiCountryCode: [setCountryCodeNative] Default CSC Country Code : PL
,10-12 16:09:22.287  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.288  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.288  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.288  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.288  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.288  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.288  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.288  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.288  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.289  3703  4845 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:22.303  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.303  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.303  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.303  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:22.303  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.303  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:22.304  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.304  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.304  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.304  3703  3725 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:22.313 10312 10312 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:22.314 10312 10312 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:22.316  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:22.317  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.317  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.317  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.317  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:22.317  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.317  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.317  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.318  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
10-12 16:09:22.318  3703  4542 W NetworkIdentity: Active mobile network without subscriber!
,10-12 16:09:22.320  3703  4871 I ActivityManager: DSS on for com.samsung.hs20provider and scale is 1.0
,10-12 16:09:22.327 10259 10259 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,10-12 16:09:22.329  3703  3928 D WifiCountryCode: Succeeded to set country code to: PL
10-12 16:09:22.330  3703  3928 D wifi    : android_net_wifi_get_firmware_version = 0x71809c7ba0
10-12 16:09:22.330  3703  3928 E WifiHAL : Failed to register debug response; result = -95
10-12 16:09:22.330  3703  3928 E wifi    : Fail to get Firmware version
10-12 16:09:22.330  3703  3928 D wifi    : android_net_wifi_get_driver_version = 0x71809c7ba0
10-12 16:09:22.330  3703  3928 E WifiHAL : Failed to register debug response; result = -95
10-12 16:09:22.330  3703  3928 E wifi    : Fail to get driver version
10-12 16:09:22.330  3703  3928 D wifi    : android_net_wifi_set_log_handler = 0x71809c7ba0
10-12 16:09:22.330  3703  3928 D wifi    : android_net_wifi_get_ring_buffer_status = 0x71809c7ba0
10-12 16:09:22.330  3703  3928 E WifiHAL : Failed to register debug response; result = -95
10-12 16:09:22.330  3703  3928 E WifiLogger: no ring buffers found
10-12 16:09:22.330  3703  3928 D WifiHAL : Start get packet fate command
10-12 16:09:22.330  3703  3928 D WifiHAL : createRequest Monitor packet fate request
10-12 16:09:22.331  3703  3928 E WifiHAL : Failed to register get pkt fate response; result = -95
10-12 16:09:22.331  3703  3928 E WifiLogger: Failed to start packet fate monitoring
,10-12 16:09:22.332  3703  4013 D WifiWatchdogStateMachine: Disconnected - Move to DefaultState
,10-12 16:09:22.341 10312 10312 W System  : ClassLoader referenced unknown path: /system/app/Hs20Provider/lib/arm64
,10-12 16:09:22.353 10312 10312 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:22.358  3703  3924 D WifiP2pService: P2pDisabledState{ what=131203 }
,10-12 16:09:22.358  3703  3928 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-12 16:09:22.359  3703  3928 I WifiConnectivityManager: Set WiFi enabled
10-12 16:09:22.359  3703  3928 E WifiStateMachine: ConnectModeState - enter !! - mIsSupportGeofence !!
10-12 16:09:22.359  3703  3956 I WifiScanningService: wifi driver loaded with scan capabilities: max buckets=16
,10-12 16:09:22.361  3703  3703 D RttService: SCAN_AVAILABLE : 3
10-12 16:09:22.361  3703  3957 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-12 16:09:22.362  3298  3792 D CommandListener: Setting iface cfg
10-12 16:09:22.362  3298  3792 D CommandListener: Trying to bring up p2p0
10-12 16:09:22.362  3703  3928 D WifiStateMachine: Remembered scan first is enabled
10-12 16:09:22.362  3703  3703 I WifiStateMachine: initGeofence
10-12 16:09:22.363  3298  3784 D Netd    : Iface p2p0 link up
10-12 16:09:22.364  3703  3928 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@62ead44
10-12 16:09:22.365  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
10-12 16:09:22.365  3703  3928 E wifi    : failed to get channel list : -95
10-12 16:09:22.365  3703  3928 D WifiConfigManager: getChannelsForBand(WifiScanner.WIFI_BAND_24_GHZ) is null. So set default 2.4GHz 14 channels.
10-12 16:09:22.367 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-12 16:09:22.367 10259 10259 I wpa_supplicant: P2P: Current p2p state = IDLE
10-12 16:09:22.370  3703  3924 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
10-12 16:09:22.371  3703  3924 D SecContentProvider: insert(), uri = 2
10-12 16:09:22.373  3703  3796 D Tethering: interfaceLinkStateChanged p2p0, true
10-12 16:09:22.373 10259 10259 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
10-12 16:09:22.373  3703  3796 D Tethering: interfaceStatusChanged p2p0, true
10-12 16:09:22.374  3703  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T160937 - CU:1000/CP:3703
10-12 16:09:22.375  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160937, SetElapsed=227572, nowELAPSED=212578
10-12 16:09:22.376  3703  3924 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:22.377  3703  3924 D WifiP2pService: P2pEnablingState
10-12 16:09:22.377  3703  3924 D WifiP2pService: P2pEnablingState{ what=147457 }
10-12 16:09:22.378  3703  3924 D WifiP2pService: P2p socket connection successful
10-12 16:09:22.378  3703  3924 D WifiP2pService: P2pEnabledState
10-12 16:09:22.378  3703  3928 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20171012T160930 - CU:1000/CP:3703
10-12 16:09:22.378  3703  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160930, SetElapsed=220578, nowELAPSED=212582
10-12 16:09:22.378  3703  3924 D SecContentProvider: insert(), uri = 2
10-12 16:09:22.386  3703  3924 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:22.388  3703  3924 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
10-12 16:09:22.388  3703  3959 D ConnectivityService: ignoring duplicate network state non-change
10-12 16:09:22.388 10312 10323 D HotspotProvider: inside  query methodcontent://com.samsung.passpoint/hotspot_credentials
10-12 16:09:22.389  3703  3798 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
10-12 16:09:22.389  3703  3798 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false, mScanRequestedInConnected = false
10-12 16:09:22.389  3703  3798 D WifiDisplayController: disconnect
10-12 16:09:22.389  3703  3798 D WifiDisplayAdapter: onFeatureStateChanged empty
10-12 16:09:22.389  3703  3798 V WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
10-12 16:09:22.389  3703  3928 D WifiStateMachine: setFccChannelNative: channel = 0
10-12 16:09:22.390 10312 10323 D HotspotProvider: CREDENTIAL
10-12 16:09:22.390  3703  3928 D WifiNative-wlan0: callSECApiInt - ID [230]
10-12 16:09:22.390 10312 10323 D HotspotProvider: No prepend tags
10-12 16:,09:22.400  3703  3798 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), failover: false, available: true, roaming: false, metered: false]
10-12 16:09:22.400 10259 10259 I wpa_supplicant: P2P: Set Samsung Discovery Icon = 256
10-12 16:09:22.404 10259 10259 I wpa_supplicant: P2P: Set Samsung Discovery name = 
10-12 16:09:22.410  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
10-12 16:09:22.413 10245 10245 D FileShare: FileShareBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
10-12 16:09:22.414 10245 10245 D FileShare: FileShareBroadcastReceiver.onReceive - disconnected
10-12 16:09:22.414 10245 10245 D FileShare: Outbound.stopDelayTimer - 
10-12 16:09:22.414  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
10-12 16:09:22.415  4042  4054 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
10-12 16:09:22.418  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:22.425  3703  3703 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
10-12 16:09:22.428  3703  3703 D SLocation: system
10-12 16:09:22.428  3703  3703 D SLocation: startGeofence ID = 1
10-12 16:09:22.430  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 16:09:22.431  3703  3928 D WifiNative-wlan0: callSECApiVoid - ID [311]
10-12 16:09:22.433  3703  3954 D HS20StateMachine: updateNumOfHS20Cred, numOfHS20Cred = 1
10-12 16:09:22.433  3703  3954 D HS20StateMachine: CMD_HOTSPOT20_ENABLE : 
10-12 16:09:22.433  3703  3954 D HS20StateMachine: enter : DiscoveringState
10-12 16:09:22.440  3703  3924 E WifiP2pService: Failed to set my phone number info into probe response
10-12 16:09:22.442  4949  5001 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 7ms lastUpdatedAfter : 14041 ms mFlush_time_threasold : 2000 mCurrentSize : 184
10-12 16:09:22.444  3703  3924 D WifiNative-HAL: p2pGetDeviceAddress
10-12 16:09:22.445  3703  3924 D WifiNative-HAL: p2pGetDeviceAddress returning 4e:66:41:a9:15:41
,10-12 16:09:22.446  3703  3924 D WifiP2pService: DeviceAddress: 4e:15:41
10-12 16:09:22.447  3703  3798 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: [Phone] Samsung Galaxy S7
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  deviceAddress: 4e:66:41:a9:15:41
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  primary type: 10-0050F204-5
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  secondary type: null
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  wps: 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  grpcapab: 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  devcapab: 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  status: 3
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  wfdInfo: WFD enabled: falseWFD DeviceInfo: 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  WFD CtrlPort: 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  WFD MaxThroughput: 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  groupownerAddress: null
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  GOdeviceName: null
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  interfaceAddress: 
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  SConnectInfo : null
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  contactInfoHash : null
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  ssDevInfo : 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  iconIdx : 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  semSamsungDeviceType : 0
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  serviceData : null
10-12 16:09:22.447  3703  3798 D WifiDisplayController:  fw_invite : 0
,10-12 16:09:22.456  3703  3703 D SLocation: addReceiver type4
10-12 16:09:22.456  3703  3703 D SLocation: already exsit record!
,10-12 16:09:22.465  3703  3924 D WifiP2pService: sending p2p persistent groups changed broadcast
,10-12 16:09:22.466  3703  3924 D WifiP2pService: InactiveState
,10-12 16:09:22.467  3703  3924 D WifiP2pService: InactiveState{ what=143376 }
10-12 16:09:22.467  3703  3924 D WifiP2pService: P2pEnabledState{ what=143376 }
10-12 16:09:22.467  3703  3924 E WifiP2pService: Airplane mode : skipped SET_COUNTRY_CODE
,10-12 16:09:22.483  3703  3703 D SLocation: setPendingIntent
10-12 16:09:22.483  3703  3703 D SLocation: setStatus ID = 1 / status = 3
,10-12 16:09:22.537  3703  3703 D SLocation: geofence id (1) detected : 0
10-12 16:09:22.537  3703  3703 D WifiStateMachine: startGeofence() - id : 1
,10-12 16:09:22.544  4042  4053 D TelephonyProvider: query: match = 7
,10-12 16:09:22.560  3703  3703 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
10-12 16:09:22.560  3703  3703 D SLocation: system
10-12 16:09:22.560  3703  3703 D SLocation: startGeofence ID = 2
,10-12 16:09:22.580  3703  3703 D SLocation: addReceiver type4
10-12 16:09:22.580  3703  3703 D SLocation: already exsit record!
,10-12 16:09:22.597  3703  3703 D SLocation: setPendingIntent
10-12 16:09:22.597  3703  3703 D SLocation: setStatus ID = 2 / status = 3
,10-12 16:09:22.637  3703  3703 D SLocation: geofence id (1) detected : 0
,10-12 16:09:22.644  9839  9942 D BluetoothAdapter: STATE_ON
,10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 16:09:22.648  9839  9942 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 16:09:22.649  9839  9905 D BluetoothAdapter: enable()
,10-12 16:09:22.656  9969  9980 D BluetoothAdapterService: updateEvent call by com.thaliproject.thalitest, isEnable : true
10-12 16:09:22.657  9969  9980 D AdapterProvider: query
,10-12 16:09:22.666  9969  9980 D AdapterProvider: Created cursor android.database.sqlite.SQLiteCursor@5b0200e
,10-12 16:09:22.668  9969  9980 D BluetoothAdapterService: updateEvent - already set, update
,10-12 16:09:22.668  9969  9980 W BluetoothAdapterService: updateEvent - alreadySet is true
10-12 16:09:22.668  9969  9980 D AdapterProvider: update
,10-12 16:09:22.673  9969  9980 E BluetoothAdapterService: updateEvent - update success 1
10-12 16:09:22.673  3703  3703 D SLocation: geofence id (2) detected : 0
10-12 16:09:22.673  3703  3703 D WifiStateMachine: startGeofence() - id : 2
,10-12 16:09:22.675  9839  9905 D BluetoothAdapter: enable(): BT is already enabled..!
,10-12 16:09:22.676  3703  3703 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
10-12 16:09:22.676  3703  3703 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,10-12 16:09:22.678  3703  3703 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,10-12 16:09:22.682  3703 10074 D WifiService: setWifiEnabled: true pid=9839, uid=10033
10-12 16:09:22.682  3703 10074 D WifiService: setControlHistory, packageName:  com.thaliproject.thalitest
,10-12 16:09:22.683  3703 10074 D WifiControlHistoryProvider: query
10-12 16:09:22.684  3703  3703 D SLocation: PendingIntent onSendFinished id:1
10-12 16:09:22.684  3703  3703 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
10-12 16:09:22.684  3703  3703 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
10-12 16:09:22.686  3703  3703 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
,10-12 16:09:22.691  3703  3703 D SLocation: PendingIntent onSendFinished id:1
,10-12 16:09:22.693  3703  3703 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [2], direction [0]
10-12 16:09:22.693  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=-1ms what=135243 arg1=1 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:22.693  3703  3703 D WifiStateMachine: BroadcastReceiver() - configKey : "ktwtestwifi"WPA_EAP IN. Reduce scan max interval
,10-12 16:09:22.694  3703 10074 D SecContentProvider: query(), uri = 18 selection = isWifiEnabled
10-12 16:09:22.695  3703  3703 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
10-12 16:09:22.696  3703 10074 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:22.696  3703 10074 D SecContentProvider2: query(), uri = 20 selection = isWifiStateChangeAllowed
10-12 16:09:22.698  3703  3703 D SLocation: PendingIntent onSendFinished id:2
10-12 16:09:22.700  3703 10074 I WifiService: Wi-Fi Sharing settings has not been accessed
10-12 16:09:22.701  3703 10074 D WifiService: unRegisterForSContext() : skip - it does not registered.
10-12 16:09:22.701  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 16:09:22.701  9839  9905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 16:09:22.702  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-12 16:09:22.702  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 16:09:22.702  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 16:09:22.702  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2d4563 removed from the list
10-12 16:09:22.702  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2d4563 removed from the list
10-12 16:09:22.702  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 16:09:22.702  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afce560 removed from the list
,10-12 16:09:22.703  9839  9905 D io.jxcore.node.ConnectivityMonitor: stop
10-12 16:09:22.703  9839  9905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 16:09:22.703  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,10-12 16:09:22.705  9839  9905 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,10-12 16:09:22.710  9839 10325 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,10-12 16:09:22.710  9839 10325 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-12 16:09:22.714  3298  3787 D EnterpriseController: netId is 0
10-12 16:09:22.714  3298  3787 D Netd    : getNetworkForDns: using netid 0 for uid 10033
10-12 16:09:22.715  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-12 16:09:22.720  9839 10327 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
10-12 16:09:22.721  9839 10325 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,10-12 16:09:22.723  9839 10327 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-12 16:09:22.723  9839 10325 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-12 16:09:22.724  9839 10327 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-12 16:09:22.724  9839 10325 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-12 16:09:22.724  9839 10327 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-12 16:09:22.724  9839 10325 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-12 16:09:22.725  9839 10327 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-12 16:09:22.725  9839 10325 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-12 16:09:22.727  9839 10330 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.727  9839 10330 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:22.727  9839 10330 D io.jxcore.node.StreamCopyingThread:  id: 75
,10-12 16:09:22.728  9839 10329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 224, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.728  9839 10329 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:22.728  9839 10329 D io.jxcore.node.StreamCopyingThread:  id: 74
10-12 16:09:22.728  9839 10331 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 225, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.728  9839 10331 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:22.728  9839 10331 D io.jxcore.node.StreamCopyingThread:  id: 74
10-12 16:09:22.728  9839 10331 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 225, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.728  9839 10331 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:22.728  9839 10331 D io.jxcore.node.StreamCopyingThread:  id: 74
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread:  id: 74
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 16:09:22.729  9839 10331 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 225, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:22.729  9839 10331 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 223, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread:  id: 75
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread:  id: 75
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 16:09:22.733  9839 10329 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 224, thread name: IncomingSocketThread/Sender): Socket closed
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 16:09:22.733  9839 10330 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
10-12 16:09:22.733  9839 10329 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 224, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.733  9839 10329 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:22.733  9839 10329 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 223, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:22.733  9839 10330 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
10-12 16:09:22.733  9839 10332 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 226, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.733  9839 10332 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:22.733  9839 10332 D io.jxcore.node.StreamCopyingThread:  id: 75
10-12 16:09:22.734  9839 10332 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 226, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.734  9839 10332 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:22.734  9839 10332 D io.jxcore.node.StreamCopyingThread:  id: 75
10-12 16:09:22.734  9839 10332 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.734  9839 10332 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:22.734  9839 10332 D io.jxcore.node.StreamCopyingThread:  id: 75
10-12 16:09:22.734  9839 10332 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 16:09:22.734  9839 10332 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-12 16:09:22.736  9839 10332 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 16:09:22.736  9839 10332 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 16:09:22.736  9839 10332 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 16:09:22.736  9839 10332 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,10-12 16:09:22.739  9839 10329 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-12 16:09:22.739  9839 10329 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-12 16:09:22.740  9839 10332 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
10-12 16:09:22.740  9839 10329 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 224, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.740  9839 10329 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:22.740  9839 10329 D io.jxcore.node.StreamCopyingThread:  id: 74 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-12 16:09:22.740  9839 10332 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 226, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:22.740  9839 10332 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:22.740  9839 10332 D io.jxcore.node.StreamCopyingThread:  id: 75 .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,10-12 16:09:22.947  3298  3784 D Netd    : Iface wlan0 link up
10-12 16:09:22.949 10259 10259 I wpa_supplicant: nl80211: Received scan results (20 BSSes)
,10-12 16:09:22.950  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:22.951  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:09:22.954  3703  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@55cc0de
,10-12 16:09:22.991  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:23.004  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:24.947  3703 10073 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{2d87fa7: PendingIntentRecord{f3d6c54 com.google.android.gms broadcastIntent}}
,10-12 16:09:25.027  4733  4733 I BeaconBle: 'L' hardware scan: scan stopped, no clients
,10-12 16:09:26.150  3703  4845 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:09:26.312  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:26.847  4646  4646 D io_stats: !@   8,0 r 25867 2288276 w 4976 204632 d 654 73924 f 2001 2001 iot 11760 10935 th 474544 0 0 pt 0 inp 0 0 217.049
,10-12 16:09:28.215  9839  9905 I io.jxcore.node.IncomingSocketThreadTest: testRun
,10-12 16:09:28.216  9839  9905 I !!      :  finally closed
,10-12 16:09:28.222  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,10-12 16:09:28.224  9839  9905 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-12 16:09:28.228  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,10-12 16:09:28.229  9839  9905 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-12 16:09:28.233  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,10-12 16:09:28.240  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
10-12 16:09:28.241  9839  9905 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.thaliproject.thalitest.MainActivity@2fdb33e Bundle[{}]
,10-12 16:09:28.244  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
10-12 16:09:28.245  9839  9905 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-12 16:09:28.245  9839  9905 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-12 16:09:28.249  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
10-12 16:09:28.250  9839  9905 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-12 16:09:28.253  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
10-12 16:09:28.254  9839  9905 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-12 16:09:28.260  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
10-12 16:09:28.261  9839  9905 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-12 16:09:28.262  9839  9905 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
10-12 16:09:28.263  9839  9905 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-12 16:09:28.266  9839  9905 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,10-12 16:09:28.269  9839  9905 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,10-12 16:09:28.272  9839  9905 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,10-12 16:09:28.274  9839  9905 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,10-12 16:09:28.278  9839  9905 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,10-12 16:09:28.280  9839  9905 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,10-12 16:09:28.283  9839  9905 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,10-12 16:09:28.286  9839 10334 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
10-12 16:09:28.287  9839 10334 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,10-12 16:09:28.289  3298  3787 D EnterpriseController: netId is 0
10-12 16:09:28.289  3298  3787 D Netd    : getNetworkForDns: using netid 0 for uid 10033
10-12 16:09:28.289  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-12 16:09:28.293  9839 10336 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
10-12 16:09:28.293  9839 10336 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
10-12 16:09:28.293  9839 10336 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-12 16:09:28.293  9839 10334 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
10-12 16:09:28.293  9839 10334 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
10-12 16:09:28.294  9839 10334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-12 16:09:28.294  9839 10336 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-12 16:09:28.294  9839 10334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-12 16:09:28.294  9839 10336 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
10-12 16:09:28.294  9839 10334 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,10-12 16:09:28.295  9839 10338 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 230, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.295  9839 10338 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:28.295  9839 10338 D io.jxcore.node.StreamCopyingThread:  id: 77
,10-12 16:09:28.295  9839 10339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.295  9839 10339 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:28.295  9839 10339 D io.jxcore.node.StreamCopyingThread:  id: 78
,10-12 16:09:28.296  9839 10340 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 232, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.296  9839 10340 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:28.296  9839 10340 D io.jxcore.node.StreamCopyingThread:  id: 77
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 233, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread:  id: 78
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 233, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread:  id: 78
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread:  id: 78
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 16:09:28.296  9839 10341 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 16:09:28.297  9839 10341 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 16:09:28.297  9839 10341 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 16:09:28.297  9839 10341 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
10-12 16:09:28.297  9839 10341 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 233, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.297  9839 10341 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:28.297  9839 10341 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-12 16:09:28.297  9839 10339 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 231, thread name: OutgoingSocketThread/Sender): Socket closed
10-12 16:09:28.298  9839 10339 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.298  9839 10339 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:28.298  9839 10339 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-12 16:09:28.298  9839 10339 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
10-12 16:09:28.298  9839 10339 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 230, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread:  id: 77
10-12 16:09:28.298  9839 10339 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 231, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.298  9839 10339 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:28.298  9839 10339 D io.jxcore.node.StreamCopyingThread:  id: 78 .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread:  id: 77
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 16:09:28.298  9839 10338 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 16:09:28.299  9839 10338 I io.jxcore.node.IncomingSocketThread: The sending thread is done
10-12 16:09:28.299  9839 10338 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 230, name: IncomingSocketThread/Sender). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.299  9839 10338 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:28.299  9839 10338 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,10-12 16:09:28.299  9839 10340 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 232, thread name: IncomingSocketThread/Receiver): Broken pipe
10-12 16:09:28.300  9839 10340 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 232, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.300  9839 10340 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:28.300  9839 10340 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
10-12 16:09:28.300  9839 10340 E io.jxcore.node.IncomingSocketThread: The receiving thread failed with error "Failed to write to the output stream: Broken pipe", this is likely due to peer having disconnected
10-12 16:09:28.300  9839 10340 D io.jxcore.node.StreamCopyingThread: number of bytes read = 4096
10-12 16:09:28.300  9839 10340 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 232, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:28.300  9839 10340 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true.
10-12 16:09:28.300  9839 10340 D io.jxcore.node.StreamCopyingThread:  id: 77 .During the lifetime of the thread the total number of bytes read was 8192 and the total number of bytes written 4096
,10-12 16:09:30.375  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:09:30.376  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T163616, SetElapsed=1826301, nowELAPSED=220579
,10-12 16:09:30.377  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@4f5f2bf alarm=Alarm{120e7fd type 2 when 220578 android}
10-12 16:09:30.380  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,10-12 16:09:30.384 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-12 16:09:30.384 10259 10259 I wpa_supplicant: P2P: Current p2p state = IDLE
10-12 16:09:30.386  3703  3928 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T160946 - CU:1000/CP:3703
,10-12 16:09:30.387  3703  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236584, nowELAPSED=220590
,10-12 16:09:30.392  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:30.395  3703  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T160945 - CU:1000/CP:3703
,10-12 16:09:30.406  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:30.437 10259 10259 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-12 16:09:30.955  3703  3928 E WifiStateMachine: DisconnectedState  CMD_THREE_TIMES_SCAN_IN_IDLE && mScreenOn
,10-12 16:09:30.958  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=-2ms what=131308 target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:31.852  4646  4646 D io_stats: !@   8,0 r 25867 2288276 w 4987 204720 d 655 73928 f 2002 2002 iot 11760 10938 th 475036 0 0 pt 0 inp 0 0 222.054
,10-12 16:09:32.133  3703  5698 D SSRM:f  : SIOP:: AP = 290, PST = 300 (W:14), CP = 248, CUR = 146, LCD = 57
,10-12 16:09:32.385  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:09:32.389  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:32.389 10259 10259 I wpa_supplicant: nl80211: Received scan results (55 BSSes)
10-12 16:09:32.389  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:09:32.398  3703  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@e036f43
,10-12 16:09:32.488 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-12 16:09:32.488 10259 10259 I wpa_supplicant: P2P: Current p2p state = IDLE
10-12 16:09:32.498  3703  3703 D WifiDefaultApController: checkDefaultAptoCopy: mNeedtoAddVendorAp( REQEUST_FROM_REBOOT ) general info file exists? ( false )
,10-12 16:09:32.507  3703  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T160947 - CU:1000/CP:3703
10-12 16:09:32.507  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160947, SetElapsed=237699, nowELAPSED=222711
,10-12 16:09:32.520 10259 10259 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-12 16:09:32.537  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:32.541  3703  3928 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=4 roam=false
,10-12 16:09:32.543  3703  3928 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=4
,10-12 16:09:32.547  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:32.564  3703  3928 D WifiConfigStore: saveNetwork skipInternetCheck
,10-12 16:09:32.584  3703  3928 D WifiConfigStore: readNetwork skipInternetCheck
,10-12 16:09:32.617  3703 10342 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
10-12 16:09:32.617  3703 10342 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
10-12 16:09:32.618  3703 10342 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
,10-12 16:09:32.618  3703 10342 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
10-12 16:09:32.618  3703 10342 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
10-12 16:09:32.618  3703 10342 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
10-12 16:09:32.618  3703 10342 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: true
10-12 16:09:32.619  3703 10342 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
10-12 16:09:32.619  3703 10342 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
10-12 16:09:32.619  3703 10342 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
,10-12 16:09:32.619  3703 10342 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
10-12 16:09:32.619  3703 10342 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
,10-12 16:09:32.623  3703  3928 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=4
,10-12 16:09:32.624  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
10-12 16:09:32.624  3703  3703 D WifiHs20Service: reason: 2
10-12 16:09:32.624  3703  3955 I WifiHs20Service: Message received 5014
10-12 16:09:32.624  3703  3955 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
,10-12 16:09:32.628  3703 10343 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:4 hasEverConnected: true
10-12 16:09:32.628  3703 10343 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
10-12 16:09:32.629  3703 10343 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
10-12 16:09:32.629  3703 10343 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
,10-12 16:09:32.629  3703 10343 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
10-12 16:09:32.629  3703 10343 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
10-12 16:09:32.630  3703 10343 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: true
10-12 16:09:32.630  3703 10343 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
10-12 16:09:32.630 10259 10259 I wpa_supplicant: Trying to associate with F4.E6.C2 (SSID='NG700' freq=2472 MHz)
10-12 16:09:32.630  3703 10343 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
10-12 16:09:32.630  3703 10343 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
,10-12 16:09:32.631  3703 10343 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
10-12 16:09:32.631  3703 10343 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
10-12 16:09:32.631  3703  3928 D SecContentProvider: insert(), uri = 2
,10-12 16:09:32.632  3703  3928 D SecContentProvider: called from android.uid.system:1000
,10-12 16:09:32.654 10259 10259 I wpa_supplicant: Scan aborted because the firmware maybe busy.
10-12 16:09:32.654 10259 10259 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
10-12 16:09:32.654 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,10-12 16:09:32.655  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:32.663  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:32.668  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:32.675  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:33.287  3703  3703 D UsbMonitorService: readUsbState++
10-12 16:09:33.288  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-12 16:09:33.290  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:09:33.290  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:09:33.437  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:09:33.437  3298  3784 D Netd    : Iface wlan0 link up
10-12 16:09:33.438  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:09:33.441  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:33.441  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:09:33.444  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:33.444  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:09:33.451 10259 10259 I wpa_supplicant: Associated with F4.E6.C2
10-12 16:09:33.451  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
,10-12 16:09:33.451  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:09:33.457 10259 10259 I wpa_supplicant: wlan0: CTRL-EVENT-SUBNET-STATUS-UPDATE status=0
,10-12 16:09:33.463  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:33.470  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:33.479  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:33.485  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:33.549 10259 10259 I wpa_supplicant: WPA: Key negotiation completed with F4.E6.C2 [PTK=CCMP GTK=CCMP]
10-12 16:09:33.550 10259 10259 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.E6.C2 completed [id=4 id_str=%7B%22creatorUid%22%3A%221000%22%2C%22configKey%22%3A%22%5C%22NG700%5C%22WPA_PSK%22%7D]
,10-12 16:09:33.551  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:09:33.555  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:33.555  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
10-12 16:09:33.556  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:33.562  3703  3928 D WifiNative-wlan0: callSECApiVoid - ID [50]
,10-12 16:09:33.569  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:33.570  3703  3928 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@c600cf2
,10-12 16:09:33.573  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-12 16:09:33.574  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-12 16:09:33.574  3703  3955 I WifiHs20Service: Message received 5007
10-12 16:09:33.574  3703  3928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: mIsSupportAdvancedCaptivePortal is true
,10-12 16:09:33.575  3703  3928 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-12 16:09:33.576  3703  3959 D ConnectivityService: Got NetworkAgent Messenger
10-12 16:09:33.576  3703  4013 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
10-12 16:09:33.577  3703  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
10-12 16:09:33.577  3703  3959 D ConnectivityService: NetworkAgent connected
,10-12 16:09:33.577  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-2ms what=69632 obj=com.android.internal.util.AsyncChannel@eb29f16 target=com.android.internal.util.StateMachine$SmHandler }
10-12 16:09:33.577  3703 10344 D NetworkMonitor: Async - Half connection with WWSM established
10-12 16:09:33.577  3703  4013 D WifiWatchdogStateMachine: Async - Half connection with NetworkMonitor established
10-12 16:09:33.578  3703  4013 D WifiWatchdogStateMachine: Async - Full connection with NetworkMonitor established
,10-12 16:09:33.582  4042  4042 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,10-12 16:09:33.583  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-12 16:09:33.586  3703  3924 D WifiP2pService: InactiveState{ what=143375 }
10-12 16:09:33.587  3703  3924 D WifiP2pService: P2pEnabledState{ what=143375 }
10-12 16:09:33.587  9969  9969 D BluetoothUtils: readSalesCode :: sales code is XEO
10-12 16:09:33.587  3703  3928 D WifiHAL : Getting APF capabilities, halHandle = 0x71809c7ba0
10-12 16:09:33.587  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-12 16:09:33.588  3703  3928 I WifiHAL : 
10-12 16:09:33.588  3703  3928 I WifiHAL : createRequest: APF get capabilities request
,10-12 16:09:33.590  3703  3928 D WifiHAL : In SetAPFCommand::handleResponse
10-12 16:09:33.590  3703  3928 D WifiHAL : Id = 0, subcmd = 0, len = 16
10-12 16:09:33.590  3703  3928 D WifiHAL : Response recieved for get packet filter capabilities command
10-12 16:09:33.590  3703  3928 I WifiHAL : APF version is 2
10-12 16:09:33.590  3703  3928 I WifiHAL : APF max len is 2048
10-12 16:09:33.590  3703  3928 I WifiHAL : Done!
10-12 16:09:33.590  3703  3928 D WifiHAL : Getting APF capability, version = 2, max_len = 2048
10-12 16:09:33.590  3703  3928 D wifi    : APF version supported: 2
10-12 16:09:33.590  3703  3928 D wifi    : Maximum APF program size: 2048
,10-12 16:09:33.594  3703  3928 D WifiStateMachine: Start Dhcp Watchdog 2
,10-12 16:09:33.608  3703 10345 D ApfFilter: (wlan0): begin monitoring
,10-12 16:09:33.619 10123 10123 I [RBL] ServiceReceiver: @onReceive - rawData : null
,10-12 16:09:33.629  3703  3959 D ConnectivityService: ignoring duplicate network state non-change
10-12 16:09:33.629  3703  3928 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true)
10-12 16:09:33.629  3703  3928 D WifiNative-wlan0: configureNeighborDiscoveryOffload(true) returned: -95
10-12 16:09:33.629  3703  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]
10-12 16:09:33.629  3703  3959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
10-12 16:09:33.629  3703  3959 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
10-12 16:09:33.630  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:09:33.632  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
,10-12 16:09:33.640  3703  3928 D WifiHAL : Setting APF program, halHandle = 0x71809c7ba0
10-12 16:09:33.640  3703  3928 I WifiHAL : 
10-12 16:09:33.640  3703  3928 I WifiHAL : createRequest: APF set program request
,10-12 16:09:33.642  3703  3928 I WifiHAL : Done!
,10-12 16:09:33.645  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:09:33.651 10259 10259 I wpa_supplicant: Interworking: Fetch ANQP after connect
10-12 16:09:33.651 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
10-12 16:09:33.652 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-12 16:09:33.652 10139 10139 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
10-12 16:09:33.652 10139 10139 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,10-12 16:09:33.660 10152 10152 I PhoneErrorReceiver: onReceive
,10-12 16:09:33.662  3703  3933 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T161009 - CU:1000/CP:3703
,10-12 16:09:33.664  3703  3959 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
10-12 16:09:33.664  3703  4013 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,10-12 16:09:33.664  3703  4013 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-12 16:09:33.664  3703  4013 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
10-12 16:09:33.665  3703  4013 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-12 16:09:33.665  3703  4013 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,10-12 16:09:33.670 10165 10165 I usagelog: received in receiver
10-12 16:09:33.670 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
10-12 16:09:33.671 10165 10165 I KnoxUsageLogPro: premStatus:2
,10-12 16:09:33.671 10165 10165 I KnoxUsageLogPro: isEulaShown : false
10-12 16:09:33.671 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,10-12 16:09:33.682  3703  3933 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T161009 - CU:1000/CP:3703
,10-12 16:09:33.792  9839  9905 I io.jxcore.node.OutgoingSocketThreadTest: OutgoingSocketThreadTest
,10-12 16:09:33.795  9839  9905 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,10-12 16:09:33.800  9839  9905 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,10-12 16:09:33.807  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=start target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
10-12 16:09:33.807  3703  3924 D WifiP2pService: InactiveState{ what=143375 }
,10-12 16:09:33.808  3703  3924 D WifiP2pService: P2pEnabledState{ what=143375 }
,10-12 16:09:33.822  3703 10346 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T160935 - CU:1000/CP:3703
10-12 16:09:33.823  3703 10346 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160935, SetElapsed=226202, nowELAPSED=224026
,10-12 16:09:33.833  3703  3765 I ActivityManager: Waited long enough for: ServiceRecord{398c4d7 u0 com.samsung.android.email.provider/com.samsung.android.email.sync.service.EmailService}
,10-12 16:09:34.810  9839  9905 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,10-12 16:09:34.814  9839  9905 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,10-12 16:09:34.818  9839  9905 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
10-12 16:09:34.819  9839  9905 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 241)
10-12 16:09:34.821  9839  9905 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,10-12 16:09:34.822  9839  9905 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-12 16:09:34.822  9839  9905 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 242)
,10-12 16:09:34.824  9839  9905 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,10-12 16:09:34.826  9839  9905 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,10-12 16:09:34.828  9839  9905 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,10-12 16:09:34.830  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 16:09:34.830  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73af78c added. We now have 2 listener(s)
10-12 16:09:34.830  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73af78c added. We now have 3 listener(s)
10-12 16:09:34.831  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 16:09:34.834  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":3,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:34.835  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 16:09:34.835  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":3,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:34.835  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 16:09:34.835  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd03ed5 added. We now have 4 listener(s)
10-12 16:09:34.836  9839  9905 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 16:09:34.837  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 16:09:34.844  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.851  9839  9905 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,10-12 16:09:34.853  9839  9905 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,10-12 16:09:34.853  9839  9905 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
10-12 16:09:34.853  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
10-12 16:09:34.854  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:34.858  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:34.858  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:34.859  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:34.859  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:34.863  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":4,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:34.863  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":4,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:34.863  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:34.864  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-12 16:09:34.864  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 16:09:34.864  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 16:09:34.864  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 16:09:34.866  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 16:09:34.867  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 16:09:34.867  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 16:09:34.867  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 16:09:34.867  9839 10349 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 16:09:34.867  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 16:09:34.867  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-12 16:09:34.867  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 16:09:34.867  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 16:09:34.867  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-12 16:09:34.870  9839 10349 D BluetoothSocket: bindListen(): myUserId = 0
,10-12 16:09:34.871  9839 10349 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 16:09:34.874  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-12 16:09:34.874  9839  9905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 16:09:34.875  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 16:09:34.876  9839 10349 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
,10-12 16:09:34.877  9839 10349 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@dbfddb, port: 6, type: 1, local socket address: null, socket type: 0
,10-12 16:09:34.879  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.880  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.882  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.885  9839  9905 D BluetoothAdapter: isSecureModeEnabled
,10-12 16:09:34.885  9969  9980 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:34.886  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:34.886  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 16:09:34.888  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.890  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.890  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 16:09:34.890  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 16:09:34.890  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,10-12 16:09:34.892  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.896  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:34.896  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:34.896  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 16:09:34.896  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
10-12 16:09:34.897  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d795b619-8f1d-4c80-8da3-dbe435a7fe11", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-12 16:09:34.897  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 44 78 3E 94 4A 3E
,10-12 16:09:34.897  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:34.898  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:34.898  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:34.899  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:34.899  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,10-12 16:09:34.899  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:34.900  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:34.900  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:34.901  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[4, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:34.902  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:34.903  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.903  9839  9905 D BluetoothAdapter: isSecureModeEnabled
10-12 16:09:34.904  9969 10049 D BtConfig.SecureMode: isSecureModeOn:false
10-12 16:09:34.904  9839  9905 D BluetoothLeAdvertiser: start advertising
,10-12 16:09:34.906  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:34.912  9969  9992 D BtGatt.GattService: registerClient() - UUID=79109310-766c-42ac-ab2a-def2a5736202
,10-12 16:09:35.015  9969  9990 D BtGatt.GattService: onClientRegistered() - UUID=79109310-766c-42ac-ab2a-def2a5736202, clientIf=5, status=0
,10-12 16:09:35.017  9839  9965 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-12 16:09:35.021  9969 10049 E BtGatt.ContextMap: Context not found for ID 5
10-12 16:09:35.022  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-12 16:09:35.023  9969 10008 D BtGatt.AdvertiseManager: message : 0
,10-12 16:09:35.028  9969 10008 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-12 16:09:35.028  9969 10008 D BtGatt.AdvertiseManager: size of list is =0
,10-12 16:09:35.037  9969 10008 D BtGatt.AdvertiseManager: starting advertising
,10-12 16:09:35.043  9969 10008 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-12 16:09:35.046  9969 10025 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-12 16:09:35.064  9969  9990 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-12 16:09:35.069  9969 10008 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 16:09:35.081  9969  9990 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-12 16:09:35.082  9969 10008 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-12 16:09:35.082  9969 10008 D BtGatt.AdvertiseManager: clientIf: 5, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-12 16:09:35.083  9969 10008 D BtGatt.AdvertiseManager: postCallback clientIf = 5 status = 0
,10-12 16:09:35.083  9969 10008 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=5, status=0, isStart=true
10-12 16:09:35.084  9839  9851 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
10-12 16:09:35.086  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.087  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.087  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-12 16:09:35.088  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.089  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.090  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.091  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.092  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.093  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 16:09:35.097  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 16:09:35.099  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.104  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.105  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.108  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.109  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-12 16:09:35.111  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,10-12 16:09:35.112  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:35.112  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-12 16:09:35.113  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,10-12 16:09:35.115  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,10-12 16:09:35.116  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:35.117  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.117  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-12 16:09:35.117  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-12 16:09:35.118  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.119  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,10-12 16:09:35.120  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.121  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
,10-12 16:09:35.122  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:35.130  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.130  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-12 16:09:35.131  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,10-12 16:09:35.132  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.133  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-12 16:09:35.318  3703  4450 E Watchdog: !@Sync 7 [12_paź_16_09_35.318]
,10-12 16:09:35.614  9839  9905 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-12 16:09:35.615  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-12 16:09:35.615  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 16:09:35.615  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 16:09:35.615  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 16:09:35.615  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 16:09:35.616  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 16:09:35.616  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 16:09:35.617  9839 10349 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 16:09:35.617  9839 10349 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-12 16:09:35.617  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 16:09:35.617  9839 10349 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 16:09:35.617  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 16:09:35.617  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 16:09:35.617  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 16:09:35.618  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 16:09:35.618  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 16:09:35.618  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.618  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-12 16:09:35.618  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 16:09:35.620  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.621  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.623  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.624  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.628  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:35.631  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:35.632  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-12 16:09:35.635  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:35.639  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:35.639  9839  9905 D BluetoothLeScanner: could not find callback wrapper
10-12 16:09:35.639  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-12 16:09:35.640  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.641  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.642  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.643  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-12 16:09:35.644  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.647  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:35.651  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:35.651  9839  9905 D BluetoothLeAdvertiser: stop advertising
,10-12 16:09:35.654  9969  9992 E BtGatt.ContextMap: Context not found for ID 5
,10-12 16:09:35.655  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
,10-12 16:09:35.655  9969 10008 D BtGatt.AdvertiseManager: message : 1
10-12 16:09:35.657  9969 10008 D BtGatt.AdvertiseManager: stop advertise for client =  5
10-12 16:09:35.657  9969 10008 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 5
,10-12 16:09:35.661  9969 10008 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
,10-12 16:09:35.673  9969  9990 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-12 16:09:35.673  9969  9990 D BtGatt.GattService: Client app is not null!
10-12 16:09:35.674  9839  9850 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-12 16:09:35.677  9969 10049 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 16:09:35.679  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-12 16:09:35.681  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.681  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-12 16:09:35.682  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.684  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.685  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.685  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 16:09:35.685  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-12 16:09:35.688  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,10-12 16:09:35.689  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.694  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:35.694  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 16:09:35.695  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.700  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:35.701  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 16:09:35.701  9839  9839 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 16:09:35.701  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 16:09:35.702  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 16:09:35.702  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-12 16:09:35.703  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,10-12 16:09:35.704  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.704  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 16:09:35.704  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-12 16:09:35.705  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.705  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.706  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:35.707  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 16:09:35.999  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:09:36.000  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160947, SetElapsed=237699, nowELAPSED=226203
10-12 16:09:36.000  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@7a1cb23 alarm=Alarm{8bbf67f type 2 when 226202 android}
,10-12 16:09:36.011  3703 10346 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T160939 - CU:1000/CP:3703
10-12 16:09:36.012  3703 10346 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160939, SetElapsed=230170, nowELAPSED=226215
,10-12 16:09:36.024  3703 10346 D DhcpClient: Got pending lease: IP address 192.168.1.102/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
10-12 16:09:36.024  3703 10346 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@25cd64c
,10-12 16:09:36.027  3703 10346 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160947, SetElapsed=237699, nowELAPSED=226230
,10-12 16:09:36.033  3703 10346 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T160954 - CU:1000/CP:3703
,10-12 16:09:36.044  3703 10346 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T160938 - CU:1000/CP:3703
10-12 16:09:36.044  3703 10346 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160938, SetElapsed=228418, nowELAPSED=226248
,10-12 16:09:36.066  3703 10346 D DhcpClient: Confirmed lease: IP address 192.168.1.102/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains lan DHCP server /192.168.1.1 Vendor info null lease 43200 seconds
10-12 16:09:36.067  3703  3933 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@65628dd
10-12 16:09:36.067  3703 10346 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@3237b9b
,10-12 16:09:36.070  3703 10346 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160947, SetElapsed=237699, nowELAPSED=226273
,10-12 16:09:36.071  3703 10346 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@8f1b3aa
,10-12 16:09:36.079  3703  3924 D WifiP2pService: InactiveState{ what=143375 }
,10-12 16:09:36.081  3703  3924 D WifiP2pService: P2pEnabledState{ what=143375 }
,10-12 16:09:36.087  3703  4013 E WifiWatchdogStateMachine: Unhandled message { when=0 what=131307 obj=complete target=com.android.internal.util.StateMachine$SmHandler } in state NotConnectedState
,10-12 16:09:36.087  3298  3792 D CommandListener: Setting iface cfg
,10-12 16:09:36.088  3703  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]
10-12 16:09:36.091  3703  4013 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,10-12 16:09:36.093  3703  3959 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
10-12 16:09:36.092  3703  4013 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-12 16:09:36.094  3703  4013 E WifiWatchdogStateMachine.DnsResolver: getDns::LinkProps has null dns - returning default
10-12 16:09:36.095  3703  4013 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-12 16:09:36.097  3703  4013 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-12 16:09:36.102  3703  3928 D WifiHAL : Setting APF program, halHandle = 0x71809c7ba0
10-12 16:09:36.102  3703  3928 I WifiHAL : 
10-12 16:09:36.102  3703  3928 I WifiHAL : createRequest: APF set program request
,10-12 16:09:36.103  3703  3933 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@1ada4b4
,10-12 16:09:36.105  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
10-12 16:09:36.106  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-12 16:09:36.106  3703  3928 I WifiHAL : Done!
10-12 16:09:36.106  3703  3955 I WifiHs20Service: Message received 5007
10-12 16:09:36.107  3703  3959 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false; everConnected=false
10-12 16:09:36.107  3703  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]
10-12 16:09:36.108  3703  4013 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,10-12 16:09:36.109  3703  4013 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,10-12 16:09:36.110  3703  4013 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,10-12 16:09:36.111  3703  4013 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
10-12 16:09:36.113  4042  4042 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
10-12 16:09:36.113  3703  4013 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
10-12 16:09:36.115  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:36.114  3703  3928 E WifiNative-HAL: setBssidBlacklist cmd 2 size 0
10-12 16:09:36.115  3703  3928 D wifi    : configure BSSID black list request [4] = 0x71809c7ba0
10-12 16:09:36.115  3703  3928 D wifi    : Added 0 bssids
10-12 16:09:36.116  3703  3928 E WifiHAL : Failed to execute bssid blacklist request, result = -95
10-12 16:09:36.116  3703  3928 D WifiStateMachine: sendConnectedState - setManualConnection: false!
,10-12 16:09:36.120  3703  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-12 16:09:36.121  9969  9969 D BluetoothUtils: readSalesCode :: sales code is XEO
,10-12 16:09:36.123  3703  3959 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
10-12 16:09:36.123  3703  3959 D ConnectivityService: Adding iface wlan0 to network 503
,10-12 16:09:36.129  3703 10346 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171012T215512 - CU:1000/CP:3703
,10-12 16:09:36.142 10123 10123 I [RBL] ServiceReceiver: @onReceive - rawData : null
,10-12 16:09:36.143  3703 10346 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171013T023936 - CU:1000/CP:3703
10-12 16:09:36.144  3239  3239 E audit   : type=1320 audit(1507817376.135:536): 
10-12 16:09:36.147  3703 10346 D SamsungAlarmManager: setExact Listener (T:2/F:9/AC:false) 20171013T040936 - CU:1000/CP:3703
10-12 16:09:36.147  3703 10346 D DhcpClient: Scheduling renewal in 20735s
10-12 16:09:36.147  3703 10346 D DhcpClient: Scheduling rebind in 37799s
10-12 16:09:36.147  3703 10346 D DhcpClient: Scheduling expiry in 43199s
10-12 16:09:36.148  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.RSSI_CHANGED flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:36.148  3703  3928 D SecContentProvider: insert(), uri = 2
10-12 16:09:36.149  3703  3928 D SecContentProvider: called from android.uid.system:1000
10-12 16:09:36.150  3703  3703 I WifiTrafficPoller: evaluateTrafficStatsPolling
10-12 16:09:36.150  3703  3928 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
10-12 16:09:36.152  3703  3928 I WifiConnectivityManager: scheduleWatchdogTimer
,10-12 16:09:36.153  3703  3703 D HS20StateMachine: Broadcast Received: android.net.wifi.STATE_CHANGE
,10-12 16:09:36.154  3703  3703 D HS20StateMachine: SSID : "NG700"
10-12 16:09:36.154  3703  3703 D HS20StateMachine: NetId : 4
10-12 16:09:36.154  3703  3703 D HS20StateMachine: checkifOSUAP  null
10-12 16:09:36.154  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.STATE_CHANGE
10-12 16:09:36.154  3703  3955 I WifiHs20Service: Message received 5007
10-12 16:09:36.156  3703  4013 D WifiWatchdogStateMachine: EVENT_NETWORK_STATE_CHANGE
,10-12 16:09:36.160  4042  4042 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.net.wifi.STATE_CHANGE
,10-12 16:09:36.162  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.wifi.STATE_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:36.163  3239  3239 E audit   : type=1320 audit(1507817376.155:537): 
,10-12 16:09:36.166  9969  9969 D BluetoothUtils: readSalesCode :: sales code is XEO
,10-12 16:09:36.173  3703  3959 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
10-12 16:09:36.175  3703  3928 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T162936 - CU:1000/CP:3703
10-12 16:09:36.176  3703  3959 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,10-12 16:09:36.178  3703  3959 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,10-12 16:09:36.181  3703  3959 D ConnectivityService: Setting DNS servers for network 503 to [/192.168.1.1]
10-12 16:09:36.182  3298  4206 D ResolverController: DNSDBG::server[0] 192.168.1.1
10-12 16:09:36.182  3298  4206 D ResolverController: DNSDBG::netId 503 search_domain lan
10-12 16:09:36.182  3298  4206 D ResolverController: DNSDBG::netId 503 searchDomains lan
10-12 16:09:36.182  3298  4206 D ResolverController: DNSDBG::server[0] 192.168.1.1
,10-12 16:09:36.192  3703  3928 D WifiStateMachine: isFindLocationId() - Location Id : 1
,10-12 16:09:36.196  3703  3928 D WifiGeofenceDBHelper: update() - 1*1507817376192
,10-12 16:09:36.201  3703  5217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:09:36.204 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
,10-12 16:09:36.205 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-12 16:09:36.205 10139 10139 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
,10-12 16:09:36.206 10139 10139 W DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(31/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
10-12 16:09:36.207  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
10-12 16:09:36.214  3703  3959 V NetworkStats: updateIfacesLocked()
10-12 16:09:36.215  3703  3959 V NetworkStats: performPollLocked(flags=0x1)
10-12 16:09:36.215  3703  3959 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.220  3703  3959 V NetworkStats: performPollLocked() took 5ms
10-12 16:09:36.220  3703  3959 D NtpTrustedTime: currentTimeMillis() cache hit
,10-12 16:09:36.230  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.230  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.231  3703  3959 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
10-12 16:09:36.231  3703  3959 D ConnectivityService: Not required to send intent.
10-12 16:09:36.232  3703  3959 V NetworkStats: updateIfacesLocked()
10-12 16:09:36.232  3703  3959 V NetworkStats: performPollLocked(flags=0x1)
10-12 16:09:36.232  3703  3959 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.238  3703  3959 V NetworkStats: performPollLocked() took 6ms
10-12 16:09:36.238  3703  3959 D NtpTrustedTime: currentTimeMillis() cache hit
,10-12 16:09:36.246 10152 10152 I PhoneErrorReceiver: onReceive
,10-12 16:09:36.250  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.250  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 16:09:36.250  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Connected
10-12 16:09:36.250  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: register CaptivePortalReceiver
10-12 16:09:36.250  3703  3959 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 503]
10-12 16:09:36.250  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.250  3703  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
10-12 16:09:36.250  3703  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]
,10-12 16:09:36.250  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.250  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-12 16:09:36.250  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:36.250  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.251  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.251  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.251  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.251  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.251  3703  3959 D ConnectivityService: currentScore = 0, newScore = 20
10-12 16:09:36.251  3703  3959 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 503]
10-12 16:09:36.251  3703  3959 D ConnectivityService:    accepting network in place of null
10-12 16:09:36.251  3703  3959 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.252  3703  4023 D Ethernet: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.252  3703  4023 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
10-12 16:09:36.252  3703  4023 D Ethernet: evalRequest
10-12 16:09:36.252  3703  4023 D Ethernet:   done
10-12 16:09:36.252  4042  4042 D PhoneSwitcherNetworkRequstListener: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.252  3703  3924 D WIFI_P2P: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.253  4042  4042 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
10-12 16:09:36.253  4042  4042 D PhoneSwitcherNetworkRequstListener: evalRequest
10-12 16:09:36.253  4042  4042 D PhoneSwitcherNetworkRequstListener:   done
10-12 16:09:36.253  3703  3924 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:36.253  3703  3924 D WIFI_P2P: evalRequest
10-12 16:09:36.253  3703  3924 D WIFI_P2P:   done
10-12 16:09:36.253  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:36.253  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.254  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.254  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.254  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.254  3703  3959 D ConnectivityService: Switching to new defa,ult network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]}  network{503}  nethandle{2160384985822}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.102/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: lan MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-12 16:09:36.256 10165 10165 I usagelog: received in receiver
10-12 16:09:36.256 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
10-12 16:09:36.257 10165 10165 I KnoxUsageLogPro: premStatus:2
10-12 16:09:36.258 10165 10165 I KnoxUsageLogPro: isEulaShown : false
10-12 16:09:36.258 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
10-12 16:09:36.260  3703  4013 D WifiWatchdogStateMachine: Connected - Move to CaptivePortalState
10-12 16:09:36.264  3703  3928 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
10-12 16:09:36.264  3703  4013 E WifiWatchdogStateMachine: current state: com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalState@f66e960
10-12 16:09:36.268  3239  3239 E audit   : type=1320 audit(1507817376.265:538): 
10-12 16:09:36.272  3703  4013 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
10-12 16:09:36.278  3703  3928 D SLocation: system
10-12 16:09:36.278  3703  3928 D SLocation: startGeofence ID = 1
10-12 16:09:36.278  3703  4013 D WifiStateMachine: isPackageRunning - top:com.thaliproject.thalitest.MainActivity
10-12 16:09:36.279  3703  4013 D WifiWatchdogStateMachine: start to check Captive portal
10-12 16:09:36.279  3239  3239 E audit   : type=1320 audit(1507817376.275:539): 
10-12 16:09:36.280  3298  3792 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 16:09:36.287 10123 10123 I [RBL] ServiceReceiver: @onReceive - rawData : null
10-12 16:09:36.287 10123 10123 W [RBL] ServiceReceiver: @onReceive - NETWORK_STATE_CHANGED_ACTION
10-12 16:09:36.292  3239  3239 E audit   : type=1320 audit(1507817376.285:540): 
,10-12 16:09:36.306  3239  3239 E audit   : type=1320 audit(1507817376.295:541): 
,10-12 16:09:36.307  3298  3792 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 16:09:36.310  3703  3928 E SLocation: id 1 is already started
,10-12 16:09:36.310  3703  3928 D WifiStateMachine: startGeofence() - id : 1, ERROR !!, mResult : -5
10-12 16:09:36.311  3703  3928 V SLocation: checkResolutionLevelIsSufficientForSLocationUse : 2
,10-12 16:09:36.312  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.312  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.313  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:36.313  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.313  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
,10-12 16:09:36.316  4527  4606 D GeolocationController: WIFI : onAvailable
10-12 16:09:36.316  4527  4606 D CapabilityProvider: mWifiStateListener.onAvailable(): mIsWifiConnected [true]
10-12 16:09:36.317  4527  4616 D PdnController: handleMessage: what 105
10-12 16:09:36.317  4527  4616 D RegiMgrBase: onDataConnectionStateChanged(): networkType [UNKNOWN], isWifiConnected [true]
10-12 16:09:36.317  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.317  4527  4616 D VolteServiceModule: onDataConnectionStateChanged(): networkType [UNKNOWN]isWifiConnected [true]
10-12 16:09:36.317  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.318  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:36.319  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.319  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.320  3703  3959 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.320  3703  3959 D ConnectivityService: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
10-12 16:09:36.320  3703  3959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 16:09:36.323  4527  4616 D ResipRegiMgr: handleMessage(): 3
10-12 16:09:36.323  4527  4616 D RegiMgrBase: handleMessage: what 3
10-12 16:09:36.325  3703  3928 D SLocation: system
10-12 16:09:36.325  3703  3928 D SLocation: startLearning ID = 1
10-12 16:09:36.325  3703  3928 D SLocation: setLearningStatus ID = 1 / status = true
10-12 16:09:36.325  3703  3928 D WifiStateMachine: ConnectedState - enter() - startLearning id : 1
10-12 16:09:36.325  3703  3928 D WifiStateMachine: ConnectedState()- id : 1,  startLearning Success !!
10-12 16:09:36.325 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.wifi.STATE_CHANGE
10-12 16:09:36.326  3703  3928 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-12 16:09:36.326 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
10-12 16:09:36.326 10139 10139 I DIAGMON_AGENT: ./bssid: f4:f2:6d:85:e6:c2
10-12 16:09:36.327  3703  3928 D WIFI_UT : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.327  3703  3797 D EntConnectivity: Not allowed due to - mEnabled false
10-12 16:09:36.327  3703  3928 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:36.327  3703  3928 D WIFI_UT : evalRequest
10-12 16:09:36.327  3703  3928 D WIFI_UT :   done
10-12 16:09:36.327  3703  3928 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.327  3703  3928 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:36.327  3703  3928 D WIFI    : evalRequest
10-12 16:09:36.327  3703  3928 D WIFI    :   done
10-12 16:09:36.327  3703  3928 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 16:09:36.328 10139 10139 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 android.content.ContextWrapper.sendBroadcast:452 android.content.ContextWrapper.sendBroadcast:452 com.sec.android.diagmonagent.DiagMonConnectivityChangeReciever.onReceive:19 android.app.ActivityThread.handleReceiver:3306 
10-12 16:09:36.331 10123 10123 D [RBL] StoredRequest: @Oncreate
10-12 16:09:36.331 10123 10123 I [RBL] GuardedSuspension: @getInstance
10-12 16:09:36.331 10123 10123 I [RBL] GuardedSuspension: GuardedSuspension
10-12 16:09:36.332  3703  3959 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
10-12 16:09:36.332  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.332  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:36.333  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:36.333  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:36.333  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:36.333  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.333  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.333  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.333  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.333  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.334  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.334  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.334  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.335  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.335  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.335  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.336 10123 10123 I [RBL] GuardedSuspension: @getInstance
10-12 16:09:36.336 10123 10123 D [RBL] RblSAccountUtil: @open
10-12 16:09:36.336 10123 10123 D [RBL] RblSAccountUtil:     - client : 1
10-12 16:09:36.337  4527  4616 D RegiMgrBase: onNetworkEventChanged: new=NetworkEvent [network=0, voiceOverPs=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=true, isEpdgConnected=false]
10-12 16:09:36.337  4527  4616 D RegiMgrBase: onNetworkEventChanged: old=NetworkEvent [network=0, voiceOverP,s=UNKNOWN, outOfService=true, isDataRoaming=false, isVoiceRoaming=false, csOutOfService=true, isWifiConnected=false, isEpdgConnected=false]
10-12 16:09:36.337  4527  4616 D RegiMgrBase: out of service.
10-12 16:09:36.337  4527  4616 D RegiMgrBase: onNetworkEventChanged: nTask= 0 nRegisteredTask= 0 bExistRetryTimer= false bHaveRegisteringTask= false
10-12 16:09:36.338  3703  3797 D EntConnectivity: Not allowed due to - mEnabled false
10-12 16:09:36.339  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.339  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.340  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.340  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.340  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.340  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.340  3703  3959 D ConnectivityService: sending notification PRECHECK for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.341  3703  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]
10-12 16:09:36.341  3703  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
10-12 16:09:36.341  3703  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]
10-12 16:09:36.341  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.341  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.341  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:36.341  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.341  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.341  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.341  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
10-12 16:09:36.342  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
10-12 16:09:36.342  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:36.342  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.343  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.343  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.343  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.343  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.343  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.345  3703  3703 D EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
10-12 16:09:36.345  3703  3703 I EnterprisePremiumVpnPolicyServiceV2: Vpn Receiver : Connection change = false
10-12 16:09:36.345  3703  3914 I EnterprisePremiumVpnPolicyServiceV2: vpn handle : Message received
10-12 16:09:36.345  3703  3914 D EnterprisePremiumVpnPolicyServiceV2: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION
10-12 16:09:36.345  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.345  3703  3914 D EnterprisePremiumVpnPolicyServiceV2: run all vpn : runAllVpnService beginning
10-12 16:09:36.345  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.346  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.346  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.347  3703  3703 D KnoxVpnEngineService: Vpn Receiver : android.net.conn.CONNECTIVITY_CHANGE
10-12 16:09:36.347  3703  3703 D KnoxVpnEngineService: change in connectivity has occured  for the network type1
10-12 16:09:36.347  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.347  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.347  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.347  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:36.347  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.347  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.347  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.347  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:36.350  4527  4616 D RegiMgrBase: onNetworkEventChanged: tryRegister
10-12 16:09:36.350  4527  4616 D RegiMgrBase: tryRegister:
10-12 16:09:36.353  3703  3915 I KnoxVpnEngineService: vpn handle : Message received
10-12 16:09:36.353  3703  3915 I KnoxVpnEngineService: vpn handle : Message received
10-12 16:09:36.353  3703  3915 D KnoxVpnEngineService: vpn handle : connectivity action : Handle MSG CONNECTIVITY_ACTION. networkDown = false
10-12 16:09:36.353  3703  3915 D KnoxVpnEngineService: run all vpn : runAllVpnService beginning
10-12 16:09:36.353  3703  3703 D Tethering: Tethering got CONNECTIVITY_ACTION
10-12 16:09:36.354  3703  3960 D Tethering: InitialState got CMD_UPSTREAM_CHANGED
10-12 16:09:36.354  3703  3960 D Tethering: MasterInitialState.processMessage what=327683
10-12 16:09:36.359  4527  4616 D RegiMgrBase: RegisterTask(s) -
10-12 16:09:36.360  4527  4616 D ResipRegiMgr: handleMessage(): 32
10-12 16:09:36.360  4527  4616 D RegiMgrBase: handleMessage: what 32
10-12 16:09:36.360  4527  4616 D RegiMgrBase: onPendingUpdateRegistration: 
10-12 16:09:36.360  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:36.361  4069  4296 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
10-12 16:09:36.366 10123 10123 D [RBL] RblSAccountUtil:     - DB is opened
10-12 16:09:36.366 10123 10123 D [RBL] CellDbHelper: @open
10-12 16:09:36.366 10123 10123 D [RBL] CellDbHelper:     - client : 1
10-12 16:09:36.367  5082  5082 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF50EC62EA054297E5426D68FE61E03F7CB63D06B4FC0A78A26416AA7E048F840EFBC21D921AABB61599A4C4654ABE1206043CF566A086A1148D0FC76C5AA3DFC0]}
,10-12 16:09:36.369  5082  5082 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF006507037EF1FC27CFA959C112FA7F2D1F670CE973374D2DC76D44F7D5EE5AC4ACC17241AE6937FB763E957545037025]}
10-12 16:09:36.370  3703  3919 D NetworkPolicy: NetworkPolicy.put: NetworkPolicy[NetworkTemplate: matchRule=WIFI, matchSubscriberIds=[null], networkId="AndroidHotspot2346"]: cycleDay=-1, cycleTimezone=UTC, warningBytes=-1, limitBytes=-1, lastWarningSnooze=-1, lastLimitSnooze=-1, metered=true, inferred=true
,10-12 16:09:36.370  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.370  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.371  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.371  3703  3919 V NetworkStats: advisePersistThreshold() given 9223372036854775807, clamped to 52428800
10-12 16:09:36.371  3703  3919 D NtpTrustedTime: currentTimeMillis() cache hit
10-12 16:09:36.374  3703  3703 D SLocation: BroadcastReceiver : CONNECTIVITY_ACTION
10-12 16:09:36.375  3703  3919 V NetworkStats: registerGlobalAlert(), Alert bytes: 52428800
10-12 16:09:36.377  3703  4484 D SLocation: checkWifiInfo
10-12 16:09:36.379  3703  4039 D ConnectivityManager: getMobileDataEnabled()+ subId=2147483643
10-12 16:09:36.379  3703  3703 V MARsPolicyManager: DataConnection: true
10-12 16:09:36.382  3703  4039 D ConnectivityManager: getMobileDataEnabled()- subId=2147483643 retVal=true
10-12 16:09:36.391  8049  8049 I FOTA_AGENT: [com.samsung.android.app.syncmldm.llllIIIllIlIIIIllllI(243/onReceive)] m_DataReceiver: g_nResumeStatus: 0 m_nWaitWifiConnectMode: 0
10-12 16:09:36.394  5172  5172 I CastMediaRouteProvider: Network connectivity changed
10-12 16:09:36.396  4826  4826 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-12 16:09:36.396 10123 10123 D [RBL] CellDbHelper:     - DB is opened
10-12 16:09:36.396 10123 10123 D [RBL] PolicyDbHelper: @open
10-12 16:09:36.397 10123 10123 D [RBL] PolicyDbHelper:     - client : 1
10-12 16:09:36.398  9330  9330 I SessionRuntime:main:  : VSP::updateNetworkStates networkState CONNECTIVITY_CHANGE
10-12 16:09:36.398  9330  9330 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState start
10-12 16:09:36.401  9399  9399 D MusicLifecycle: com.google.android.music.net.NetworkConnectivityMonitor$NetworkChangedReceiver generated event: Broadcast received with context com.google.android.music.MusicApplication@845b7e4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:36.403  9330  9330 I SessionRuntime:main:  : VSP::updateNetworkStates networkState = 2
10-12 16:09:36.403  9330  9330 I SessionRuntime:main:  : VSP::Current Network State is same as previous, so ignoring
10-12 16:09:36.403  9330  9330 I SessionRuntime:main:  : VSP::checkandUpdateNetworkState end
10-12 16:09:36.406  8750  8750 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
10-12 16:09:36.410  9399  9399 I NetworkConnectivity: Network state changed: [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false]
10-12 16:09:36.418  8049  8049 I FOTA_AGENT: [lIIlllIlIIlllIIIIlII(93/llllIIIllIlIIIIllllI)] WiFi Network is connected
10-12 16:09:36.423 10123 10123 D [RBL] PolicyDbHelper:     - DB is opened
10-12 16:09:36.423  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:36.424 10123 10362 D [RBL] StoredRequest: @onHandleIntent
10-12 16:09:36.425  5082  5082 D [WeatherWidget(1434)]  ConnectivityReceiver: {[8E9CEEBB4FA5730BE17E1F2CB9E366CF0553125B1A7ADEFBA03E3A7F9CEA3D9489139B6F35BA5D5C6F631797333959D1]}
10-12 16:09:36.427 10152 10152 I PhoneErrorReceiver: onReceive
10-12 16:09:36.428 10123 10123 D [RBL] CellDbHelper: @close
10-12 16:09:36.428 10123 10123 D [RBL] CellDbHelper:     - client : 0
10-12 16:09:36.428 10123 10123 D [RBL] CellDbHelper:     - DB is closed
10-12 16:09:36.428 10123 10123 D [RBL] PolicyDbHelper: @close
10-12 16:09:36.428 10123 10123 D [RBL] PolicyDbHelper:     - client : 0
10-12 16:09:36.428 10123 10123 D [RBL] PolicyDbHelper:     - DB is closed
10-12 16:09:36.428 10123 10123 D [RBL] RblSAccountUtil: @close
10-12 16:09:36.428 10123 10123 D [RBL] RblSAccountUtil:     - client : 0
10-12 16:09:36.428 10123 10123 D [RBL] RblSAccountUtil:     - DB is closed
10-12 16:09:36.428 10123 10123 D [RBL] StoredRequest: @onDestroy
10-12 16:09:36.429  9839  9839 V io.jxco,re.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 16:09:36.429  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 16:09:36.429  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 16:09:36.429  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 16:09:36.429  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 16:09:36.429  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:85:e6:c2
10-12 16:09:36.429  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
10-12 16:09:36.429  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 16:09:36.429  9839  9839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 16:09:36.431  8750  8750 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
10-12 16:09:36.432  9839  9839 D BluetoothAdapter: STATE_ON
10-12 16:09:36.433  5082  5082 D [WeatherWidget(1434)]  AutoRefresh: {[7D74CB60CAF3D3413AB6BB573C0D2852DB29E43AA0DFF8610F50F000609916CC778EE20F4C0BF92710C3F9097DA62F0495DABD0101A657F929F38259D0F4F774]}
10-12 16:09:36.436  9839  9839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:85:e6:c2, SSID name: "NG700"
10-12 16:09:36.443  9399  9399 I NetworkPolicyMonitor: Download-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
10-12 16:09:36.444  8750  8750 W Finsky  : [1] com.google.android.finsky.application.FinskyAppImpl.Z(1714): No account configured on this device.
10-12 16:09:36.445  3703  4484 D SLocation: cellLocation is null
10-12 16:09:36.457  9399  9399 I NetworkPolicyMonitor: Stream-ability status changed to (true) unmetered wifi/eth: true mobileOrMetered: false
10-12 16:09:36.459  3703  3922 D WindowManager: addWindow: android.view.IWindow$Stub$Proxy@feed326 displayId=0
10-12 16:09:36.460  3703  3922 D InputTransport: Input channel constructed: fd=460
10-12 16:09:36.460  3703  3922 D InputTransport: Input channel constructed: fd=461
,10-12 16:09:36.466  3703  3922 V MARsPolicyManager: handelAlertToastWindowStarted pkgName = com.android.systemui
,10-12 16:09:36.475  3703  3922 D InputTransport: Input channel destroyed: fd=461
10-12 16:09:36.475  5082  5082 D [WeatherWidget(1434)]  WidgetCount: {[65C2FDBB08E09D2E8E78BEFE0D618279BC32024A311F60279E75A9FD2AD8BED1]}
10-12 16:09:36.475  4069  4296 D InputTransport: Input channel constructed: fd=150
10-12 16:09:36.475  4069  4296 D ViewRootImpl@7d431ff[Toast]: setView = android.widget.LinearLayout{6cf2bcc V.E...... ......I. 0,0-0,0 #10204d0 android:id/toast_layout_root} touchMode=true
,10-12 16:09:36.478  5082  5082 D [WeatherWidget(1434)]  WidgetCount: {[51D05FFECDA2C35BD99FAAEAA7B9A301F0BE9CFAFD994C3F7B3209384CC66988]}
,10-12 16:09:36.482  9399  9399 I DevicePlayback: Got network change: mobile=falsewifi=true
10-12 16:09:36.482  9399  9399 I DevicePlayback: Connectivity restored - clearing all queued disable runnables
,10-12 16:09:36.485 10165 10165 I usagelog: received in receiver
,10-12 16:09:36.486 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.wifi.STATE_CHANGE myUserId=0
10-12 16:09:36.486 10165 10165 I KnoxUsageLogPro: premStatus:2
10-12 16:09:36.487 10165 10165 I KnoxUsageLogPro: isEulaShown : false
10-12 16:09:36.487 10165 10165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
10-12 16:09:36.489  5082  5082 E [WeatherWidget(1434)]  WidgetCount: {[575702F8165D33B66FFE59737B1A62BA08307BCFA3F3A497389D8A1664DA7207C61FE3795BDDA6ED7149C0C90BBA0789F02F175F5575CC50CF5DAAE8904C8914F88792B902BC3E22CDAD80A066BB3E6979730FC110332D83BB2D465425F6B25F89D3F8672D6293DD63CA48A914D2FE41578525C7DFC817959D978B0D1E4AEA3E8237DDDE31DA9CCBB38800CB9D7B42E57A86DA9FF9D55CAD67CE294EA9DE56535F45722BD7BAE690537BE548FCDE8E57ED456836297CA885487DA18C55446062]}
10-12 16:09:36.490  5082  5082 W [WeatherWidget(1434)]  AutoRefresh: {[FD51A315D37AAFC2E139641098576D046D458C57EE37DB6B9263681FFCD40CF01A6772634AEDA0D4B0B223A0763A58EE4BED955A823F243BEAE3A45567F08DD2321854D08A27F4D40285D5771BC7B0FC95FCD4E704A2C776AC2C52FEDFAEF037]}
10-12 16:09:36.491  5082  5082 D [WeatherWidget(1434)]  AutoRefresh: {[D66993CEC2139B42825F15423C8FC37CB81F28161A53B5553937AF4F1AAAEBA916B5697044B6E04751F07B003D46E660A784CB9E3B462E87AEB1AD3F809D90C23EB9D3B97867E467A798739D729C38BF02F8E7F88FD79BFB6259D7DAEFCF9DEF]}
10-12 16:09:36.492  5082  5082 D [WeatherWidget(1434)]  AutoRefresh: {[3B620F0E62100CD008166B45665AC4E0990189A1A2BD5FD130A6F5AC98AF999B]}
,10-12 16:09:36.494  3703  4541 D SamsungAlarmManager: Cancel Alarm calling from uid:10159 pid :5082 / op:PendingIntent{1db9703: PendingIntentRecord{1d46680 com.sec.android.daemonapp broadcastIntent}}
,10-12 16:09:36.495  5082  5082 D [WeatherWidget(1434)]  AutoRefresh: {[13EBFE39826C141B196DBEF817B05C2B8704215167EB2523B0284BC069F64B74]}
,10-12 16:09:36.527  9399  9458 I DevicePlayback: Allowing woodstock playback due to restored connection
,10-12 16:09:36.536  3298  3787 D EnterpriseController: netId is 0
,10-12 16:09:36.536  3298  3787 D Netd    : getNetworkForDns: using netid 503 for uid 10019
10-12 16:09:36.536  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-12 16:09:36.544  3703  4873 V WindowManager: Relayout Window{1e18d14d0 u0 Toast}: viewVisibility=0 req=755x150 WM.LayoutParams{(0,192)(wrapxwrap) gr=#51 sim=#20 ty=2005 fl=#1040088 fmt=-3 wanim=0x1030004 naviIconColor=0}
,10-12 16:09:36.545  3111  3111 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=4, Uoast
,10-12 16:09:36.558  3703  4873 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=3703 ws=WorkSource{10062} pkg=android
10-12 16:09:36.558  3703  4873 D PowerManagerService: mDisplayReady: false
,10-12 16:09:36.559  3703  3804 D DisplayPowerController: animateScreenStateChange[0]: target=2
10-12 16:09:36.559  3703  3804 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,10-12 16:09:36.560  3703  3804 D DisplayPowerController: Tracking Direct to etc : 104
10-12 16:09:36.560  3703  3804 D DisplayPowerController: getFinalBrightness : Summary is 104 -> 104
,10-12 16:09:36.560  3703  3804 D DisplayPowerController: Animating brightness: target=104, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-12 16:09:36.560  3703  3804 D DisplayPowerController: animateScreenStateChange[0]: target=2
10-12 16:09:36.560  3703  3804 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
10-12 16:09:36.560  3703  4037 D lights  : lcd : 104 +
10-12 16:09:36.560  3703  3804 D DisplayPowerController: getFinalBrightness : Summary is 104 -> 104
10-12 16:09:36.560  3703  3804 D DisplayPowerController: Animating brightness: target=104, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
10-12 16:09:36.561  3703  3804 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-12 16:09:36.561  3703  3804 D PowerManagerService: mDisplayReady: true
10-12 16:09:36.564  5172  5172 E MDM     : [1] SitrepChimeraService.a: No Google accounts; deferring server state update.
,10-12 16:09:36.566  3703  4872 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.gms cmp = com.google.android.gms.mdm.receivers.ConnectivityReceiver newState = 2 callingPackage = 10019
10-12 16:09:36.567  3703  4484 D SLocation: geofence id (1) detected : 0
10-12 16:09:36.568  4069  4296 D ViewRootImpl@7d431ff[Toast]: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
10-12 16:09:36.570  4069  4233 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [755x150]-format:1
10-12 16:09:36.572  3703  4037 D lights  : lcd : 104 -
10-12 16:09:36.572  3703  4037 D DisplayPowerState: Tracking!!: 104
10-12 16:09:36.591  3703  3725 D WindowManager: finishDrawingWindow: Window{1e18d14d0 u0 Toast} mDrawState=DRAW_PENDING
,10-12 16:09:36.599  5172  5676 W MdnsClient_Cast: #acquireLock. Multicast lock not held. Acquiring. Subtypes:"805741C9"
10-12 16:09:36.600  5172  5172 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
10-12 16:09:36.601  3703  3928 D WifiHAL : Setting APF program, halHandle = 0x71809c7ba0
10-12 16:09:36.601  3703  3928 I WifiHAL : 
10-12 16:09:36.601  3703  3928 I WifiHAL : createRequest: APF set program request
10-12 16:09:36.601  4069  4211 D vol.MediaSessions: onQueueChanged com.google.android.music []
10-12 16:09:36.605  3703  3928 I WifiHAL : Done!
,10-12 16:09:36.615  5172  8263 I iu.UploadsManager: num queued entries: 0
,10-12 16:09:36.617  5172  8263 I iu.UploadsManager: num updated entries: 0
,10-12 16:09:36.621  5172  8263 I iu.SyncManager: NEXT; no task
,10-12 16:09:36.623  3703  4019 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: GW is reachable. - 243 msec.
10-12 16:09:36.625  3703  4180 D WifiScanController: isNLPPackage:com.google.android.gms, true
,10-12 16:09:36.630  3298  3787 D EnterpriseController: netId is 0
,10-12 16:09:36.630  3298  3787 D Netd    : getNetworkForDns: using netid 503 for uid 10001
10-12 16:09:36.630  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
10-12 16:09:36.631  3703  3928 I WifiScanController: location is disabled
10-12 16:09:36.633  3703  4484 D SLocation: geofence id (2) detected : 0
,10-12 16:09:36.654  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:36.655  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -53
10-12 16:09:36.655  3703  3928 D WifiStateMachine: User moved, open or psk 24GHz, currentRssi = -53, mQnsUpperRssiThreshold = 200
10-12 16:09:36.656  3703  3928 W AlarmManager: Unrecognized alarm listener com.android.server.wifi.WifiConnectivityManager$3@62ead44
10-12 16:09:36.656  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
10-12 16:09:36.661  3703  3928 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20171012T160938 - CU:1000/CP:3703
10-12 16:09:36.661  3703  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160938, SetElapsed=228585, nowELAPSED=226865
,10-12 16:09:36.668 10179 10179 I SA      : [OR] onReceive log=[SA = 2.2.03-46 V = 24 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = pl_PL CSC = XEO MCC = 0 MNC 0 T = user DEVICE = herolte P = heroltexx I = NRD90M M = SM-G930F OKLEFT false DIS NRD90M.G930FXXU1DQEF PSS = 5.059173621445858  ]
,10-12 16:09:36.669 10179 10179 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", failover: false, available: true, roaming: false, metered: false] networkType:1 inetCondition:0 extraInfo:? ]
10-12 16:09:36.669 10179 10179 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,10-12 16:09:36.681 10179 10179 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
10-12 16:09:36.681 10179 10179 I SA      : [OR] == isSIMCardReady false ==
,10-12 16:09:36.684 10179 10179 I SA      : [SCU] == networkStateCheck == true
10-12 16:09:36.685 10179 10179 I SA      : [DM] getCountryCodeFromCSC : PL
,10-12 16:09:36.685 10179 10179 I SA      : isChinaCountryCode : false
10-12 16:09:36.685 10179 10179 I SA      : [SCU] is ChinestModel Data Restricted   : false
10-12 16:09:36.685 10179 10179 I SA      : [OR] == networkStateCheck true ==
,10-12 16:09:36.704  3703  4542 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20171012T163936 - CU:10124/CP:5105
,10-12 16:09:36.723 10179 10179 I SA      : [OR] GetMyCountryZoneTask
10-12 16:09:36.724 10179 10179 I SA      : [OR] onReceive END
,10-12 16:09:36.729  3703  3716 I art     : Background sticky concurrent mark sweep GC freed 178959(10MB) AllocSpace objects, 24(528KB) LOS objects, 22% free, 42MB/55MB, paused 2.330ms total 107.266ms
,10-12 16:09:36.746 10202 10202 I SVCAgent: Ignore network change.
,10-12 16:09:36.749  3703  4542 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{34b3e5: PendingIntentRecord{66b405b com.google.android.gms broadcastIntent}}
10-12 16:09:36.754 10215 10215 D AutoSelfUpgradeReceiver: onReceive() android.net.conn.CONNECTIVITY_CHANGE
,10-12 16:09:36.769  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=128 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-12 16:09:36.784  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=8 path=package-restrictions.xml sys=false lock=false imagePending=false whichPending=0x0 written=true index=0
,10-12 16:09:36.784  3703  3793 V WallpaperManagerService: Wallpaper file change: evt=512 path=package-restrictions-backup.xml sys=false lock=false imagePending=false whichPending=0x0 written=false index=0
,10-12 16:09:36.789  8005  8005 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,10-12 16:09:36.789  8005  8005 E SPPClientService: [SystemStateMoniter] Current Time : 226992
10-12 16:09:36.789  8005  8005 E SPPClientService: [SystemStateMoniter] No Connect : false
,10-12 16:09:36.792 10179 10374 I SA      : [SRS] prepareGetMyCountryZone
,10-12 16:09:36.805 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(51/llIIIIlllllIIllIIllI)] Receive broadcast: com.sec.android.diagmonagent.intent.NETWORK_CHANGED
10-12 16:09:36.805 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(52/llIIIIlllllIIllIIllI)] Receive broadcast:
,10-12 16:09:36.806 10139 10139 I DIAGMON_AGENT: [IIllIIIlIllIIIllIIlI(67/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,10-12 16:09:36.812 10179 10374 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,10-12 16:09:36.814 10179 10374 I SA      : [SSP] query invoked
,10-12 16:09:36.832 10179 10374 I SA      : [TPMU] GetMccFromDB : null
,10-12 16:09:36.833 10179 10374 I SA      : [SCU] getMccFromPreferece mcc = 260
10-12 16:09:36.833 10179 10374 I SA      : [LBE] isSupportCheckDomainRegion : true
,10-12 16:09:36.834 10179 10374 I SA      : [TPM] isNoProxy(default) : true
,10-12 16:09:36.849  3703  3941 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171012T170647 - CU:10019/CP:4733
10-12 16:09:36.851  3703  4019 D WifiWatchdogStateMachine:  [|208]
,10-12 16:09:36.855  4646  4646 D io_stats: !@   8,0 r 25871 2288292 w 5035 205468 d 665 73972 f 2021 2021 iot 11780 10964 th 472112 0 0 pt 0 inp 0 0 227.058
,10-12 16:09:36.857 10179 10374 D NetworkSecurityConfig: No Network Security Config specified, using platform default
,10-12 16:09:36.889  3703  4845 D MountService: getExternalStorageMountMode : 1
10-12 16:09:36.889  3703  4845 D MountService: getExternalStorageMountMode : 3
,10-12 16:09:36.889  3703  4845 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.policydm
,10-12 16:09:36.915  3703  4845 I ActivityManager: Start proc 10378:com.policydm/1000 for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider
10-12 16:09:36.915 10378 10378 E Zygote  : v2
10-12 16:09:36.915 10378 10378 I libpersona: KNOX_SDCARD checking this for 1000
10-12 16:09:36.915 10378 10378 I libpersona: KNOX_SDCARD not a persona
,10-12 16:09:36.916 10378 10378 E Zygote  : accessInfo : 0
,10-12 16:09:36.926 10378 10378 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:36.928 10378 10378 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.policydm 
,10-12 16:09:36.934  3703  3941 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20171012T162136 - CU:10019/CP:4733
,10-12 16:09:36.939  3703  4871 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
,10-12 16:09:36.939  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
10-12 16:09:36.940  3703 10344 D NetworkMonitor: handled
,10-12 16:09:36.950  3703  4850 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
10-12 16:09:36.950  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 16:09:36.950  3703 10344 D NetworkMonitor: handled
,10-12 16:09:36.955  3703  4542 D ConnectivityService: reportNetworkConnectivity(503, true) by 10019
10-12 16:09:36.956  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532488 arg1=10019 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 16:09:36.956  3703 10344 D NetworkMonitor: handled
,10-12 16:09:36.963  3703  3922 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{c81a961: PendingIntentRecord{d17099d com.google.android.gms broadcastIntent}}
,10-12 16:09:36.966 10378 10378 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:36.967 10378 10378 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:36.970  3703  4543 I ActivityManager: DSS on for com.policydm and scale is 1.0
,10-12 16:09:36.979  3703  3920 D SamsungAlarmManager: setExact Intent (T:2/F:5/AC:false) 20171012T162136 - CU:10019/CP:4733
,10-12 16:09:36.997 10378 10378 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm64
,10-12 16:09:37.018 10378 10378 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:37.038 10378 10378 I FOTA    : [lllIIIIIIlllIlIIIIII(108/llIIIIlllllIIllIIllI)] oms: /customer.xml
10-12 16:09:37.038 10378 10378 I FOTA    : [lllIIIIIIlllIlIIIIII(199/lllIlIlIIIllIIlIllIl)] read default : /system/csc/customer.xml
,10-12 16:09:37.070 10378 10378 I FOTA    : [com.sec.android.policyagent.PolicyApplication(36/onCreate)] PolicyApplication onCreated!
,10-12 16:09:37.081 10378 10390 I FOTA    : [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
10-12 16:09:37.082 10378 10390 I FOTA    : [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
10-12 16:09:37.087 10378 10390 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,10-12 16:09:37.093 10378 10389 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
10-12 16:09:37.095 10378 10389 I DBG_POLICYDM: [com.sec.android.policyagent.db.llllIIIllIlIIIIllllI(68/llIIIIlllllIIllIIllI)] get SalesCode from FotaFeature
10-12 16:09:37.097 10378 10389 I DBG_POLICYDM: [com.sec.android.policyagent.db.IIIIllIlIIlIIIIlllIl(45/llIIIIlllllIIllIIllI)] already Eula Agree
,10-12 16:09:37.103  3703 10073 D MountService: getExternalStorageMountMode : 1
10-12 16:09:37.103  3703 10073 D MountService: getExternalStorageMountMode : 3
10-12 16:09:37.103  3703 10073 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.sec.android.soagent
,10-12 16:09:37.113 10378 10378 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(186/llIIIIlllllIIllIIllI)] try read dbString
,10-12 16:09:37.130 10394 10394 E Zygote  : v2
10-12 16:09:37.130 10394 10394 I libpersona: KNOX_SDCARD checking this for 1000
10-12 16:09:37.130 10394 10394 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:37.131 10394 10394 E Zygote  : accessInfo : 0
10-12 16:09:37.133  3703 10073 I ActivityManager: Start proc 10394:com.sec.android.soagent/1000 for content provider com.sec.android.soagent/.log.MasterLogProvider
10-12 16:09:37.139 10394 10394 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:09:37.141 10394 10394 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.sec.android.soagent 
10-12 16:09:37.153 10378 10378 I DBG_POLICYDM: [com.policydm.db.XDB(231/IllIlIIIIlIIlIIIllIl)] xdbDMffs_Init
,10-12 16:09:37.163 10394 10394 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:37.164 10394 10394 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:37.177  3703  4180 I ActivityManager: DSS on for com.sec.android.soagent and scale is 1.0
,10-12 16:09:37.207 10394 10394 W System  : ClassLoader referenced unknown path: /system/priv-app/SOAgent/lib/arm64
,10-12 16:09:37.221  3703  4018 D WifiWatchdogStateMachine.QualitySocketHandler: response code: 204
10-12 16:09:37.222  3703  4018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.android.server.wifi.WifiWatchdogStateMachine$QualitySocketHandler.handleMessage:4711 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:154 android.os.HandlerThread.run:61 
10-12 16:09:37.224  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
10-12 16:09:37.224  3703  4013 D WifiWatchdogStateMachine: sendBroadcastFromWWSMForCurrentUser()
10-12 16:09:37.224  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: MaybeNotifyState{ when=0 what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
10-12 16:09:37.224  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: DefaultState{ when=-1ms what=532498 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
10-12 16:09:37.224  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: CMD_ACCEPT_UNVALIDATED_WIFI
10-12 16:09:37.224  3703  3959 D ConnectivityService: NetworkMonitor.CMD_ACCEPT_UNVALIDATED_WIFI network
10-12 16:09:37.224  3703  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
10-12 16:09:37.225  3703  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]
10-12 16:09:37.225  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: EvaluatingState{ when=0 what=151655 target=com.android.internal.util.StateMachine$SmHandler }
10-12 16:09:37.225  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: RESULT_VALID
10-12 16:09:37.225  3703 10344 D NetworkMonitor/NetworkAgentInfo [WIFI () - 503]: Validated
,10-12 16:09:37.227  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.227  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.227  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:37.228  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.228  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.228  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.228  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.228  3703  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
10-12 16:09:37.228  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
,10-12 16:09:37.229  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,10-12 16:09:37.229  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.229  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.229  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.229 10378 10378 I DBG_POLICYDM: [com.policydm.XDMService(164/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,10-12 16:09:37.229  3703  3959 D ConnectivityService: sending new Min Network Score(100): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.233  4042  4042 D PhoneSwitcherNetworkRequstListener: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.233  3703  4023 D Ethernet: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.234  3703  4023 D Ethernet:   my score=-1, my filter=[ Transports: ETHERNET Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=100000Kbps LinkDnBandwidth>=100000Kbps]
10-12 16:09:37.234  3703  4023 D Ethernet: evalRequest
10-12 16:09:37.234  3703  4023 D Ethernet:   done
,10-12 16:09:37.234  4042  4042 D PhoneSwitcherNetworkRequstListener:   my score=101, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&ENT1 Specifier: <*>]
,10-12 16:09:37.234  4042  4042 D PhoneSwitcherNetworkRequstListener: evalRequest
10-12 16:09:37.234  4042  4042 D PhoneSwitcherNetworkRequstListener:   done
10-12 16:09:37.235  3703  3924 D WIFI_P2P: new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.235  3703  3924 D WIFI_P2P:   my score=60, my filter=[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:37.235  3703  3924 D WIFI_P2P: evalRequest
10-12 16:09:37.235  3703  3924 D WIFI_P2P:   done
10-12 16:09:37.235 10394 10394 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
10-12 16:09:37.235  3703  3703 D WifiNotificationController: SHOW_NOTI_MESSAGE : 302, visible : false, ssid : "NG700", targetSSID : null, netId : -1, titleType : -1
10-12 16:09:37.236  3703  3959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 16:09:37.236  3703  3959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 16:09:37.236  3703  3959 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] validation passed
10-12 16:09:37.237  3703  3959 D ConnectivityService: updateCapabilities: oldCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53], newCap = [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]
10-12 16:09:37.237  3703  3959 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
10-12 16:09:37.237  3703  3959 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]
10-12 16:09:37.237  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.237  3703  3928 D WIFI_UT : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.237  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.237  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:37.237  3703  3928 D WIFI_UT :   my score=2147483647, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:37.237  3703  3928 D WIFI_UT : evalRequest
10-12 16:09:37.237  3703  3928 D WIFI_UT :   done
10-12 16:09:37.237  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.237  3703  3928 D WIFI    : new score 100 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.237  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.237  3703  3928 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: NOT_METERED&INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
10-12 16:09:37.237  3703  3959 D ConnectivityService:   checking if request is satisf,ied: NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.237  3703  3928 D WIFI    : evalRequest
10-12 16:09:37.238  3703  3928 D WIFI    :   releaseNetworkFor
10-12 16:09:37.238  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.238  3703  3959 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
10-12 16:09:37.238  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:37.238  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.238  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.238  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.238  3703  3959 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=5, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.238  3703  3959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 503]
10-12 16:09:37.238  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.238  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:37.238  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [] ]
10-12 16:09:37.239  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:37.239  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [] ]
10-12 16:09:37.239  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.239  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=6, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.240  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.240  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=7, legacyType=-1, [ Transports: CELLULAR|WIFI Capabilities: NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.240  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.240  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=8, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.242  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.242 10378 10378 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(455/IIIIIIlIIIllllllIlII)] xdbGetFUMOStatus : 0
10-12 16:09:37.242  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=9, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.242  3703  3959 D ConnectivityService:  sending notification for NetworkRequ,est [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.243  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=10, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.243  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.243  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.244  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.244  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
10-12 16:09:37.244  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.244  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.244 10378 10378 I DBG_POLICYDM: [com.policydm.XDMService(588/llIlIllllllllllllllI)] get NotibarState : 0
10-12 16:09:37.245  3703  3959 D ConnectivityService:  sending notification for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.245  3703  3959 D ConnectivityService: sending notification CAP_CHANGED for NetworkRequest [ id=14, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED] ]
10-12 16:09:37.247  3703  3959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-12 16:09:37.251  4733  4745 I art     : Background partial concurrent mark sweep GC freed 84225(5MB) AllocSpace objects, 30(600KB) LOS objects, 40% free, 11MB/19MB, paused 6.577ms total 83.576ms
10-12 16:09:37.258  3703  3928 D WifiConfigManager: update usableInternet : true
10-12 16:09:37.259  3703 10412 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
10-12 16:09:37.259  3703 10412 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
10-12 16:09:37.260  3703 10412 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
10-12 16:09:37.260  3703 10412 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
10-12 16:09:37.260  3703 10412 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
10-12 16:09:37.260  3703 10412 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
10-12 16:09:37.260  3703 10412 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: true
10-12 16:09:37.260  3703 10412 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
10-12 16:09:37.261  3703 10412 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
10-12 16:09:37.261  3703 10412 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
10-12 16:09:37.261  3703 10412 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
10-12 16:09:37.261  3703 10412 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
10-12 16:09:37.263  4069  4296 D NetworkController: onReceive: intent=Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:37.264  4069  4296 D NetworkController.MobileSignalController(0/-2): updateConnectivity: mCurrentState.bluetoothTethered + false
10-12 16:09:37.273  3703  4851 D MountService: getExternalStorageMountMode : 1
10-12 16:09:37.274  3703  4851 D MountService: getExternalStorageMountMode : 3
10-12 16:09:37.274  3703  4851 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10134, packageName : com.sec.android.app.sbrowser
10-12 16:09:37.283  3703  3928 D WifiConfigStore: saveNetwork skipInternetCheck
10-12 16:09:37.293 10413 10413 E Zygote  : v2
10-12 16:09:37.294 10413 10413 I libpersona: KNOX_SDCARD checking this for 10134
10-12 16:09:37.294 10413 10413 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:37.294 10413 10413 E Zygote  : isSdpEnabledProcess - SDP enabled
10-12 16:09:37.295 10413 10413 E Zygote  : accessInfo : 64
10-12 16:09:37.295 10413 10413 E Zygote  : isSdpEnabledProcess - SDP enabled
10-12 16:09:37.295 10413 10413 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10134 / [uid]: 10134
10-12 16:09:37.297  3703  4851 I ActivityManager: Start proc 10413:com.sec.android.app.sbrowser:CustomLogger/u0a134 for content provider com.sec.android.app.sbrowser/.logging.CustomLoggingProvider
10-12 16:09:37.301 10413 10413 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
10-12 16:09:37.302 10413 10413 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser:CustomLogger 
10-12 16:09:37.306  3703  3928 D WifiConfigStore: readNetwork skipInternetCheck
10-12 16:09:37.313  3703  3959 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,10-12 16:09:37.323 10413 10413 D TimaKeyStoreProvider: TimaSignature is unavailable
10-12 16:09:37.324 10413 10413 D ActivityThread: Added TimaKeyStore provider
10-12 16:09:37.327  3703 10426 D WifiNetworkHistory: saving network history: "NG700"WPA_PSK gw: f4:f2:6d:85:e6:c2 Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:0 nid:4 hasEverConnected: true
10-12 16:09:37.327  3703 10426 V WifiNetworkHistory: writeKnownNetworkHistory write config "NG700"WPA_PSK
10-12 16:09:37.327  3703 10426 D WifiNetworkHistory: saving network history: "Thali_internal"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:0 hasEverConnected: false
10-12 16:09:37.327  3703 10426 V WifiNetworkHistory: writeKnownNetworkHistory write config "Thali_internal"NONE
10-12 16:09:37.327  3703 10426 D WifiNetworkHistory: saving network history: "AndroidHotspot2346"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:1 hasEverConnected: false
10-12 16:09:37.327  3703 10426 V WifiNetworkHistory: writeKnownNetworkHistory write config "AndroidHotspot2346"WPA_PSK
10-12 16:09:37.328  3703 10426 D WifiNetworkHistory: saving network history: "ktwtestwifi"WPA_EAP gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:5 hasEverConnected: true
10-12 16:09:37.328  3703 10426 V WifiNetworkHistory: writeKnownNetworkHistory write config "ktwtestwifi"WPA_EAP
10-12 16:09:37.328  3703 10426 D WifiNetworkHistory: saving network history: "MC"NONE gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:2 hasEverConnected: false
10-12 16:09:37.328  3703 10426 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"NONE
10-12 16:09:37.328  3703 10426 D WifiNetworkHistory: saving network history: "MC"WPA_PSK gw: null Network Selection-status: NETWORK_SELECTION_ENABLED ephemeral=false choice:null link:0 status:1 nid:3 hasEverConnected: false
10-12 16:09:37.328  3703 10426 V WifiNetworkHistory: writeKnownNetworkHistory write config "MC"WPA_PSK
10-12 16:09:37.331  3703  3724 I ActivityManager: DSS on for com.sec.android.app.sbrowser and scale is 1.0
10-12 16:09:37.339  3703  3703 I WifiHs20Service: Broadcast received:android.net.wifi.CONFIGURED_NETWORKS_CHANGE
10-12 16:09:37.339  3703  3703 D WifiHs20Service: reason: 2
10-12 16:09:37.339  3703  3955 I WifiHs20Service: Message received 5014
10-12 16:09:37.339  3703  3955 E WifiHs20Service: received HS20_UTILITY_ACTION_TYPE_HS20_CONFIGURATION_CHANGED
10-12 16:09:37.350  4733 10377 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-12 16:09:37.356 10413 10413 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_5.0/lib/arm
,10-12 16:09:37.371  4733 10377 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-12 16:09:37.374 10413 10413 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:37.376  3703  4485 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / op:PendingIntent{cd97729: PendingIntentRecord{d9c6aae android broadcastIntent}}
10-12 16:09:37.379  3703  4485 D SamsungAlarmManager: setInexact Intent (T:3/F:8/AC:false) 20171013T160937 - CU:1000/CP:3703
,10-12 16:09:37.385 10413 10413 I cr_ApplicationStatus: initialize application : com.sec.android.app.sbrowser.SBrowserApplication@e2a5d66
,10-12 16:09:37.388  3703  3922 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.391 10413 10413 D ReflectField: Cannot load field: SDL_INT
10-12 16:09:37.391 10413 10413 E ReflectField: Incorrect type : Fallback exception
10-12 16:09:37.392 10413 10413 D ReflectField: Cannot load field: KEYCODE_EMAIL
10-12 16:09:37.392 10413 10413 E ReflectField: Incorrect type : Fallback exception
,10-12 16:09:37.399  3703  3922 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.409  3703  5217 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.416  3703  4180 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.425  3703  3941 I ActivityManager: KPU : put [com.samsung.svoice.sync] : 21112 K
10-12 16:09:37.426  3703  3941 I ActivityManager: Killing 9349:com.samsung.svoice.sync/u0a40 (adj 906): DHA:empty #33
,10-12 16:09:37.428  3703  3703 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [1], direction [0]
10-12 16:09:37.429  3703  3703 D WifiStateMachine: BroadcastReceiver() - configKey : "NG700"WPA_PSK IN. Reduce scan max interval
,10-12 16:09:37.433  3703  3703 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
10-12 16:09:37.437  3703  5217 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
10-12 16:09:37.444  3703  3703 D SLocation: PendingIntent onSendFinished id:1
10-12 16:09:37.445  3703  3703 D WifiStateMachine: BroadcastReceiver - WIFI_INTENT_ACTION_GEOFENCE_TRIGGERED : id [2], direction [0]
10-12 16:09:37.445  3703  3703 D WifiStateMachine: BroadcastReceiver() - configKey : "ktwtestwifi"WPA_EAP IN. Reduce scan max interval
10-12 16:09:37.447  3703  3703 D WifiStateMachine: sendBroadcastForInOutRange() - state : 0 getNetworkType() : 0
10-12 16:09:37.449  3703  4850 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.464  3703  4542 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
10-12 16:09:37.472  3703  3703 D SLocation: PendingIntent onSendFinished id:2
,10-12 16:09:37.484  3703  3941 D ActivityManager: cleanUpApplicationRecord -- 9349
10-12 16:09:37.487  4769  4782 D ForegroundUtils: could not check pending caller
10-12 16:09:37.490  3703  4873 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.501  3703  3725 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.514  3703  4543 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.525  3703  3941 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.533  3703  4016 D WifiWatchdogStateMachine:  [] [|204]
,10-12 16:09:37.536  3703  4541 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.540  3703  3724 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{44e7a9d: PendingIntentRecord{66b405b com.google.android.gms broadcastIntent}}
,10-12 16:09:37.544  3703  3725 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.553  3703  4845 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:37.565  3703  4851 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171012T170647 - CU:10019/CP:4733
,10-12 16:09:37.623  4733 10377 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:09:37.627  4733 10377 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:09:37.629  3298  3787 D EnterpriseController: netId is 0
,10-12 16:09:37.630  3298  3787 D Netd    : getNetworkForDns: using netid 503 for uid 10019
10-12 16:09:37.630  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-12 16:09:37.638 10179 10374 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
10-12 16:09:37.638 10179 10374 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,10-12 16:09:37.641 10179 10374 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,10-12 16:09:37.642 10179 10374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:09:37.643 10179 10374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:09:37.645  3298  3787 D EnterpriseController: netId is 0
10-12 16:09:37.645  3298  3787 D Netd    : getNetworkForDns: using netid 503 for uid 10041
10-12 16:09:37.645  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-12 16:09:38.089  3703  3920 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:38.106  4733 10377 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
10-12 16:09:38.106  4733 10377 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:09:38.223  4733 10377 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-12 16:09:38.239  3703  4543 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,10-12 16:09:38.261  4733 10377 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
10-12 16:09:38.261  4733 10377 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:09:38.382  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:09:38.383  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160947, SetElapsed=237699, nowELAPSED=228586
10-12 16:09:38.383  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@ae046f3 alarm=Alarm{296f65e type 2 when 228585 android}
,10-12 16:09:38.388  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 8000: mInRange : true
,10-12 16:09:38.394  3703  3928 D SamsungAlarmManager: setExact Listener (T:2/F:8/AC:false) 20171012T160946 - CU:1000/CP:3703
10-12 16:09:38.394  3703  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=228598
,10-12 16:09:38.404 10179 10374 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 763
,10-12 16:09:38.455  4069  4296 D ViewRootImpl@7d431ff[Toast]: dispatchDetachedFromWindow
,10-12 16:09:38.462  3703 10073 D InputTransport: Input channel destroyed: fd=460
,10-12 16:09:38.463  3703 10073 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 3703) eventTime = 228666
10-12 16:09:38.463  3703 10073 D PowerManagerService: [s] UserActivityState : 4 -> 1
,10-12 16:09:38.464  3703 10073 D PowerManagerService: [api] release WakeLock SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3703, ws=WorkSource{10062}) (uid=1000, pid=3703, ws=WorkSource{10062}, pkg=android, elapsedTime=1906) (0x0)
10-12 16:09:38.464  3703 10073 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=3703, ws=WorkSource{10062}) (uid=1000, pid=3703, ws=WorkSource{10062}, pkg=android, elapsedTime=1907)
10-12 16:09:38.466 10179 10374 I SA      : [ODM] saveOpenData( GEO_IP, EU )
10-12 16:09:38.467 10179 10374 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
10-12 16:09:38.468  4069  4296 D InputTransport: Input channel destroyed: fd=150
,10-12 16:09:38.470 10179 10374 I SA      : [OCP]  Cursor is not null
,10-12 16:09:38.475 10179 10374 I SA      : [OCP] update openData : EU
,10-12 16:09:38.480 10179 10374 I SA      : [TPMU] getNetworkMcc : 
,10-12 16:09:38.484 10179 10374 I SA      : [SRS] prepareGetMyCountryZone
,10-12 16:09:38.492 10179 10374 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,10-12 16:09:38.492 10179 10374 I SA      : [SSP] query invoked
,10-12 16:09:38.497 10179 10374 I SA      : [TPMU] GetMccFromDB : null
10-12 16:09:38.497 10179 10374 I SA      : [SCU] getMccFromPreferece mcc = 260
10-12 16:09:38.497 10179 10374 I SA      : [LBE] isSupportCheckDomainRegion : true
,10-12 16:09:38.497 10179 10374 I SA      : [TPM] isNoProxy(default) : true
10-12 16:09:38.499 10179 10374 I SA_HTTPURLCONNECTION: [RC New] invalidHeader - value is null : x-osp-trxId
10-12 16:09:38.499 10179 10374 I SA_HTTPURLCONNECTION: [RC New] Execute method=[GET] start
,10-12 16:09:38.501 10179 10374 I SA_HTTPURLCONNECTION: [RC New] Security=[true]
,10-12 16:09:38.501 10179 10374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
10-12 16:09:38.502 10179 10374 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:09:38.531  4733 10377 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-12 16:09:38.592  3703  4851 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171012T170647 - CU:10019/CP:4733
,10-12 16:09:38.602  3703  3725 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{d81a6a: PendingIntentRecord{66b405b com.google.android.gms broadcastIntent}}
,10-12 16:09:38.622  3703  4873 D SamsungAlarmManager: setInexact Intent (T:2/F:0/AC:false) 20171012T170647 - CU:10019/CP:4733
,10-12 16:09:38.709  9839  9905 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,10-12 16:09:38.711  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 16:09:38.712  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 16:09:38.712  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 16:09:38.712  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 16:09:38.713  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 16:09:38.713  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 16:09:38.728  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-12 16:09:38.729  9839  9905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 16:09:38.729  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 16:09:38.737  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.740  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.744  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.751  9839  9905 D BluetoothAdapter: isSecureModeEnabled
,10-12 16:09:38.752  9969 10049 D BtConfig.SecureMode: isSecureModeOn:false
,10-12 16:09:38.754  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:38.754  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 16:09:38.758  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:38.761  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:38.761  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 16:09:38.762  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 16:09:38.762  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 4
,10-12 16:09:38.769  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.771  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.780  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.783  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.786  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:38.787  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 16:09:38.787  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 16:09:38.787  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 56320
,10-12 16:09:38.789  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=56320, mManufacturerData=null, mManufacturerDataMask=null]
,10-12 16:09:38.790  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:38.790  9839  9905 D BluetoothLeScanner: Start Scan
,10-12 16:09:38.794  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.798  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.803  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.807  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:38.814  9969  9981 D BtGatt.GattService: registerClient() - UUID=469f700a-59cc-4d3f-895b-dddf531059c3
,10-12 16:09:38.918  9969  9990 D BtGatt.GattService: onClientRegistered() - UUID=469f700a-59cc-4d3f-895b-dddf531059c3, clientIf=5, status=0
,10-12 16:09:38.919  9839  9965 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
10-12 16:09:38.920  9969  9991 D BtGatt.GattService: start scan with filters
,10-12 16:09:38.921  9969  9991 D BtGatt.GattService: getScanSettings
,10-12 16:09:38.923  9969  9991 D BtGatt.GattService: Is it foreground application = true
10-12 16:09:38.923  9969  9991 D BtGatt.GattService: not a background application
,10-12 16:09:38.928  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,10-12 16:09:38.928  9969 10019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
10-12 16:09:38.928  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-12 16:09:38.929  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:38.929  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 16:09:38.930  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:38.930  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 16:09:38.930  9969 10009 D BtGatt.ScanManager: handling starting scan
10-12 16:09:38.932  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 16:09:38.933  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:38.933  9839  9905 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: seems that updateState call different BlePeerDiscoverer
,10-12 16:09:38.934  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:38.934  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:38.934  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 16:09:38.934  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 16:09:38.935  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:38.935  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
10-12 16:09:38.935  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:38.936  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
10-12 16:09:38.936  9969 10009 D BluetoothAdapter: STATE_ON
10-12 16:09:38.937  9969 10009 D BluetoothAdapter: STATE_ON
10-12 16:09:38.938  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:38.938  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:38.939  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:38.939  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:38.945  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-12 16:09:38.945  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 16:09:38.946  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:38.946  9969  9990 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 16:09:38.946  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:38.946  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:38.946  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 16:09:38.949  9969 10009 D BtGatt.ScanManager: set filter index= 6 for clientIf= 5
10-12 16:09:38.949  9969 10009 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-12 16:09:38.949  9969 10009 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-12 16:09:38.949  9969 10009 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
10-12 16:09:38.953  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 16:09:38.953  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:38.954  9969 10009 D BtGatt.ScanManager: Starting BLE batch scan
10-12 16:09:38.954  9969 10009 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 16:09:38.965  9969  9990 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 16:09:38.965  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:38.969  9969  9990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 16:09:38.969  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:38.970  3703  4871 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{340b237: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
10-12 16:09:38.981  3703  4180 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160939 - CU:1002/CP:9969
10-12 16:09:38.981  3703  4180 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160939, SetElapsed=230175, nowELAPSED=229185
,10-12 16:09:39.012  3703  3798 I WindowManager: Destroying surface Surface(name=Toast) called by com.android.server.wm.WindowStateAnimator.destroySurface:2838 com.android.server.wm.WindowStateAnimator.destroySurfaceLocked:1069 com.android.server.wm.WindowState.destroyOrSaveSurface:2534 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementInner:499 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacementLoop:274 com.android.server.wm.WindowSurfacePlacer.performSurfacePlacement:222 com.android.server.wm.WindowManagerService$H.handleMessage:9166 android.os.Handler.dispatchMessage:102 
,10-12 16:09:39.012  3111  3122 I SurfaceFlinger: id=19 Removed Uoast (6/6)
10-12 16:09:39.013  3111  4437 I SurfaceFlinger: id=19 Removed Uoast (-2/6)
,10-12 16:09:39.448  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-12 16:09:39.449  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 16:09:39.449  9839  9839 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 16:09:39.623 10179 10374 I SA_HTTPURLCONNECTION: [RC New] [v2liruge] api execute + 1121
,10-12 16:09:39.627 10179 10374 I SA      : [ODM] saveOpenData( GEO_IP, EU )
,10-12 16:09:39.628 10179 10374 I SA      : [OCP]  URI : content://com.msc.openprovider.openContentProvider/openData
,10-12 16:09:39.634 10179 10374 I SA      : [OCP]  Cursor is not null
,10-12 16:09:39.644 10179 10374 I SA      : [OCP] update openData : EU
,10-12 16:09:39.653 10179 10374 I SA      : [TPMU] getNetworkMcc : 
,10-12 16:09:39.659 10179 10374 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 1158
10-12 16:09:39.659 10179 10374 I SA_HTTPURLCONNECTION: [RC New] Execute end
10-12 16:09:39.660 10179 10374 I SA_HTTPURLCONNECTION: [RC New] executeRequest [v2liruge] end. 2021
10-12 16:09:39.660 10179 10374 I SA_HTTPURLCONNECTION: [RC New] Execute end
,10-12 16:09:39.663 10179 10179 I SA      : [OR] GetMyCountryZoneTask mcc = null
,10-12 16:09:39.665 10179 10179 I SA      : [OR] GetMyCountryZoneTask Fail
,10-12 16:09:39.678  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:39.678  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -53
,10-12 16:09:39.809  3703  4542 I ActivityManager: KPU : put [com.sec.android.app.sbrowser] : 21600 K
10-12 16:09:39.809  3703  4542 I ActivityManager: Killing 9416:com.sec.android.app.sbrowser/u0a134 (adj 906): DHA:empty #33
,10-12 16:09:39.849  3703 10074 D ActivityManager: cleanUpApplicationRecord -- 9416
,10-12 16:09:39.851  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:39.972  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:09:39.973  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=230176
10-12 16:09:39.974  3703  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{968450d type 2 when 229674 com.android.bluetooth}
,10-12 16:09:39.980  9969  9969 D BtGatt.ScanManager: awakened up at time 230184
,10-12 16:09:39.983  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 16:09:39.997  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-12 16:09:39.997  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 16:09:39.999  3703  4873 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{b7d8cc2: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:40.017  3703  3920 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160940 - CU:1002/CP:9969
10-12 16:09:40.018  3703  3920 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160941, SetElapsed=231204, nowELAPSED=230221
,10-12 16:09:41.001  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:09:41.002  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=231205
10-12 16:09:41.003  3703  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{5643ad3 type 2 when 230703 com.android.bluetooth}
,10-12 16:09:41.009  9969  9969 D BtGatt.ScanManager: awakened up at time 231212
,10-12 16:09:41.011  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 16:09:41.025  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-12 16:09:41.025  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 16:09:41.028  3703  3725 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{7cb8610: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:41.044  3703  4845 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160941 - CU:1002/CP:9969
,10-12 16:09:41.045  3703  4845 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160942, SetElapsed=232233, nowELAPSED=231248
,10-12 16:09:41.859  4646  4646 D io_stats: !@   8,0 r 25875 2288452 w 5212 208284 d 704 74204 f 2080 2080 iot 11930 11063 th 472480 0 0 pt 0 inp 0 0 232.061
,10-12 16:09:41.944  9839  9905 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
10-12 16:09:41.944  9839  9905 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
10-12 16:09:41.945  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
10-12 16:09:41.945  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:41.953  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:41.954  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
,10-12 16:09:41.955  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:41.955  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: clearIdentityString
,10-12 16:09:41.962  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"generation":5,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:41.962  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"generation":5,"address":"44:78:3E:94:4A:3E"}
10-12 16:09:41.963  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 56320
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-12 16:09:41.964  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:41.965  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Beacon extra: 5
10-12 16:09:41.966  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:41.967  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:41.967  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 16:09:41.967  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 16:09:41.968  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:41.969  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:41.970  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:41.974  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:41.977  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:41.978  9969  9980 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
10-12 16:09:41.978  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
10-12 16:09:41.980  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 16:09:41.981  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:41.984  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:41.985  9839  9905 D BluetoothLeScanner: Stop Scan
,10-12 16:09:41.990  9969  9991 D BtGatt.GattService: stopScan() - queue size =1
10-12 16:09:41.991  9969  9991 D BtGatt.GattService: stopScan() - queue size =1
10-12 16:09:41.991  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 16:09:41.991  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
10-12 16:09:41.991  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:41.993  3703  3725 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{4e12509: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:41.995  9969  9992 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 16:09:41.996  3703  3725 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=232199
10-12 16:09:41.997  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 16:09:41.997  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:41.998  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 16:09:41.998  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:41.999  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 16:09:41.999  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.000  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.000  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 16:09:42.000  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 16:09:42.000  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 56320
10-12 16:09:42.000  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=56320, mManufacturerData=null, mManufacturerDataMask=null]
10-12 16:09:42.001  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.001  9839  9905 D BluetoothLeScanner: Start Scan
,10-12 16:09:42.003  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:42.005  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:42.006  3703  4541 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160942 - CU:1002/CP:9969
10-12 16:09:42.007  3703  4541 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160942, SetElapsed=233201, nowELAPSED=232210
10-12 16:09:42.009  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:42.009  9969 10009 D BtGatt.ScanManager: filter size is 1
10-12 16:09:42.009  9969 10009 D BtGatt.ScanManager: delete FilterIndex - 6
,10-12 16:09:42.011  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:42.015  9969  9981 D BtGatt.GattService: registerClient() - UUID=bf4c3db0-4b1d-4719-a8e6-5d6a815df79c
10-12 16:09:42.017  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 16:09:42.017  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:42.017  9969 10009 D BtGatt.ScanManager: stopping BLe Batch
,10-12 16:09:42.024  9969  9990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 16:09:42.024  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:42.024  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 16:09:42.031  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 16:09:42.031  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:42.032  3703  4842 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{b1bb30e: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:42.033  3703  4842 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=232237
,10-12 16:09:42.034  3703  4543 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{62db12f: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:42.118  9969  9990 D BtGatt.GattService: onClientRegistered() - UUID=bf4c3db0-4b1d-4719-a8e6-5d6a815df79c, clientIf=5, status=0
,10-12 16:09:42.119  9839  9850 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5 mClientIf=0
,10-12 16:09:42.120  9969  9980 D BtGatt.GattService: start scan with filters
,10-12 16:09:42.124  9969  9980 D BtGatt.GattService: getScanSettings
,10-12 16:09:42.127  9969  9980 D BtGatt.GattService: Is it foreground application = true
,10-12 16:09:42.127  9969  9980 D BtGatt.GattService: not a background application
,10-12 16:09:42.139  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_SCAN
,10-12 16:09:42.139  9969 10019 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@285bcbb
,10-12 16:09:42.139  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-12 16:09:42.140  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.140  9969 10009 D BtGatt.ScanManager: handling starting scan
10-12 16:09:42.141  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 16:09:42.142  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.142  9969 10009 D BluetoothAdapter: STATE_ON
10-12 16:09:42.146  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:42.147  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-12 16:09:42.147  9839  9905 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-12 16:09:42.147  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 16:09:42.148  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 16:09:42.148  9969 10009 D BluetoothAdapter: STATE_ON
10-12 16:09:42.149  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:42.150  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.150  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 16:09:42.150  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 16:09:42.151  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.152  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.152  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-12 16:09:42.155  9839 10440 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 16:09:42.154  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 16:09:42.157  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 16:09:42.157  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 16:09:42.158  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 16:09:42.158  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-12 16:09:42.158  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 16:09:42.162  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-12 16:09:42.162  9839  9905 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 16:09:42.164  9969  9990 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 16:09:42.164  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:42.165  9969 10009 D BtGatt.ScanManager: set filter index= 7 for clientIf= 5
10-12 16:09:42.165  9969 10009 D BtGatt.ScanManager: High Rssi Filter value is = -128
10-12 16:09:42.165  9969 10009 D BtGatt.ScanManager: Low Rssi Filter value is = -128
10-12 16:09:42.165  9969 10009 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0scanFilterRssiThreshold = -128trackableScanFilterRssiThreshold = -128matchmode is =2
10-12 16:09:42.166  3703  5698 D SSRM:f  : SIOP:: AP = 290, PST = 296 (W:14), CP = 246, CUR = 140, LCD = 104
10-12 16:09:42.172  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:42.172  3703  3765 I ActivityManager: KPU : put [com.sec.android.widgetapp.samsungapps] : 26128 K
10-12 16:09:42.173  3703  3765 I ActivityManager: Killing 9478:com.sec.android.widge,tapp.samsungapps/u0a105 (adj 906): DHA:empty #33
10-12 16:09:42.174  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:42.175  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 16:09:42.176  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:42.176  9969 10009 D BtGatt.ScanManager: Starting BLE batch scan
10-12 16:09:42.176  9969 10009 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 16:09:42.183  9839 10440 D BluetoothSocket: bindListen(): myUserId = 0
10-12 16:09:42.183  9839 10440 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 16:09:42.189  9839 10440 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: portAndTypeToString
10-12 16:09:42.190  9839 10440 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections... Server socket = Socket android.bluetooth.BluetoothSocket@492738d, port: 6, type: 1, local socket address: null, socket type: 0
10-12 16:09:42.197  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:42.197  9969  9990 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 16:09:42.198  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:42.199  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:42.203  9969  9990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 16:09:42.204  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:42.206  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:42.206  3703  5217 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{6caf33c: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
10-12 16:09:42.212  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.213  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.213  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.213  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-12 16:09:42.214  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
10-12 16:09:42.214  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "d795b619-8f1d-4c80-8da3-dbe435a7fe11", Bluetooth MAC address: "44:78:3E:94:4A:3E"
10-12 16:09:42.214  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 44 78 3E 94 4A 3E
10-12 16:09:42.214  9839  9905 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:42.215  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:42.215  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.216  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.216  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
10-12 16:09:42.217  3703  3725 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160942 - CU:1002/CP:9969
10-12 16:09:42.216  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-12 16:09:42.217  3703  3725 I SamsungAlarmMan,ager: setLocked to kernel - T:2 / 20171012T160943, SetElapsed=233412, nowELAPSED=232420
10-12 16:09:42.217  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:42.220  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.221  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... advertisement data = AdvertiseData [mServiceUuids=[d795b619-8f1d-4c80-8da3-dbe435a7fe11], mManufacturerSpecificData={}, mServiceData={d795b619-8f1d-4c80-8da3-dbe435a7fe11=[5, 68, 120, 62, -108, 74, 62]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false], Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:42.223  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:42.224  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:42.225  9839  9905 D BluetoothAdapter: isSecureModeEnabled
10-12 16:09:42.225  9969 10049 D BtConfig.SecureMode: isSecureModeOn:false
,10-12 16:09:42.226  9839  9905 D BluetoothLeAdvertiser: start advertising
,10-12 16:09:42.228  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:42.237  9969  9992 D BtGatt.GattService: registerClient() - UUID=6b9a31a2-1e05-455a-9589-8faae6dae20b
,10-12 16:09:42.249  3703  4845 D ActivityManager: cleanUpApplicationRecord -- 9478
,10-12 16:09:42.253  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:42.341  9969  9990 D BtGatt.GattService: onClientRegistered() - UUID=6b9a31a2-1e05-455a-9589-8faae6dae20b, clientIf=6, status=0
,10-12 16:09:42.343  9839  9850 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,10-12 16:09:42.347  9969 10049 E BtGatt.ContextMap: Context not found for ID 6
10-12 16:09:42.348  9969 10008 D BtGatt.AdvertiseManager: message : 0
,10-12 16:09:42.349  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_START_ADV
10-12 16:09:42.350  9969 10008 D BtGatt.AdvertiseManager: number of adv instance running = 0
10-12 16:09:42.350  9969 10008 D BtGatt.AdvertiseManager: size of list is =0
,10-12 16:09:42.358  9969 10008 D BtGatt.AdvertiseManager: starting advertising
,10-12 16:09:42.364  9969 10008 D BtGatt.AdvertiseManager: isStandardAdv = false
,10-12 16:09:42.368  9969 10025 E bt_btm  : btm_ble_multi_adv_set_params dummy[0] : 0x0 dummy[5] : 0x1
,10-12 16:09:42.381  9969  9990 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,10-12 16:09:42.383  9969 10008 D BtGatt.AdvertiseManager: starting multi advertising
,10-12 16:09:42.390  9969  9990 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,10-12 16:09:42.390  9969 10008 D BtGatt.AdvertiseManager: logClientsSet() - status: 0
10-12 16:09:42.390  9969 10008 D BtGatt.AdvertiseManager: clientIf: 6, Mode: 2, TxPowerLevel: 3, isConnectable: false, Timeout: 0
10-12 16:09:42.390  9969 10008 D BtGatt.AdvertiseManager: postCallback clientIf = 6 status = 0
10-12 16:09:42.390  9969 10008 D BtGatt.GattService: onMultipleAdvertiseCallback() clientIf=6, status=0, isStart=true
10-12 16:09:42.391  9839  9851 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = true
,10-12 16:09:42.392  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.393  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.393  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-12 16:09:42.393  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.394  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:42.394  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.395  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:42.395  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.396  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:42.396  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.397  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.397  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-12 16:09:42.397  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
10-12 16:09:42.397  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 16:09:42.399  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 16:09:42.400  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:42.404  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.405  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:42.405  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:42.406  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-12 16:09:42.407  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.407  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:42.408  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-12 16:09:42.408  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.409  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,10-12 16:09:42.410  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,10-12 16:09:42.410  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.410  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
,10-12 16:09:42.410  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 16:09:42.411  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.411  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.412  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.413  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.413  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-12 16:09:42.417  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.417  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-12 16:09:42.418  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.418  9839  9839 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-12 16:09:42.418  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-12 16:09:42.464  3703  3804 D PowerManagerService: [s] UserActivityState : 1 -> 4
10-12 16:09:42.464  3703  3804 D PowerManagerService: mDisplayReady: false
10-12 16:09:42.464  3703  3804 I PowerManagerService: [PWL] On : 0 (232668 ms ago)
10-12 16:09:42.465  3703  3804 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
10-12 16:09:42.465  3703  3804 D DisplayPowerController: animateScreenStateChange[0]: target=2
10-12 16:09:42.465  3703  3804 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
10-12 16:09:42.465  3703  3804 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
10-12 16:09:42.465  3703  3804 D DisplayPowerController: Animating brightness: target=57, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,10-12 16:09:42.465  3703  3804 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
10-12 16:09:42.465  3703  3804 D PowerManagerService: mDisplayReady: true
,10-12 16:09:42.477  3703  4037 D lights  : lcd : 86 +
,10-12 16:09:42.480  3703  4037 D lights  : lcd : 86 -
,10-12 16:09:42.501  3703  3804 D DisplayPowerController: animateScreenStateChange[0]: target=2
10-12 16:09:42.501  3703  4037 D lights  : lcd : 57 +
10-12 16:09:42.502  3703  3804 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
10-12 16:09:42.502  3703  3804 D DisplayPowerController: getFinalBrightness : Summary is 57 -> 57
10-12 16:09:42.502  3703  3804 D DisplayPowerController: Animating brightness: target=57, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,10-12 16:09:42.504  3703  4037 D lights  : lcd : 57 -
,10-12 16:09:42.700  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:42.700  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -55
,10-12 16:09:42.920  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
10-12 16:09:42.921  9839  9839 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-12 16:09:42.921  9839  9839 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 16:09:43.209  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:09:43.210  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=233413
10-12 16:09:43.210  3703  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{6ee08c5 type 2 when 232912 com.android.bluetooth}
,10-12 16:09:43.216  9969  9969 D BtGatt.ScanManager: awakened up at time 233419
,10-12 16:09:43.218  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 16:09:43.228  3703 10073 I ActivityManager: KPU : put [com.wssnps] : 26312 K
,10-12 16:09:43.229  3703 10073 I ActivityManager: Killing 9499:com.wssnps/1000 (adj 906): DHA:empty #33
,10-12 16:09:43.230  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 16:09:43.231  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:43.233  3703  4872 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{763f21a: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:43.251  3703 10074 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160943 - CU:1002/CP:9969
10-12 16:09:43.251  3703 10074 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160944, SetElapsed=234439, nowELAPSED=233455
,10-12 16:09:43.273  3703  4845 D ActivityManager: cleanUpApplicationRecord -- 9499
,10-12 16:09:43.275  4769  4782 D ForegroundUtils: could not check pending caller
,10-12 16:09:44.235  3703  3864 D SamsungAlarmManager: Expired : 4
10-12 16:09:44.237  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=234440
,10-12 16:09:44.238  3703  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{36e314b type 2 when 233938 com.android.bluetooth}
,10-12 16:09:44.244  9969  9969 D BtGatt.ScanManager: awakened up at time 234448
,10-12 16:09:44.247  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 16:09:44.262  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 16:09:44.262  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 16:09:44.263  3703  4871 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{3f20728: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:44.273  3703  4842 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160944 - CU:1002/CP:9969
10-12 16:09:44.273  3703  4842 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160945, SetElapsed=235468, nowELAPSED=234476
,10-12 16:09:44.389  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:45.265  3703  3864 D SamsungAlarmManager: Expired : 4
10-12 16:09:45.266  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=235469
,10-12 16:09:45.267  3703  3864 V SamsungAlarmManager: Sending to uid : 1002 action=com.android.bluetooth.gatt.REFRESH_BATCHED_SCAN alarm=Alarm{d2b6c41 type 2 when 234967 com.android.bluetooth}
,10-12 16:09:45.272  9969  9969 D BtGatt.ScanManager: awakened up at time 235475
,10-12 16:09:45.274  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 16:09:45.287  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 16:09:45.287  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:45.288  3703  4845 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{1bf15e6: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
,10-12 16:09:45.304  3703  4543 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160945 - CU:1002/CP:9969
10-12 16:09:45.305  3703  4543 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236494, nowELAPSED=235508
,10-12 16:09:45.411  9839  9905 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,10-12 16:09:45.413  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 16:09:45.413  9839  9905 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 16:09:45.413  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 16:09:45.413  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 16:09:45.415  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 16:09:45.415  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-12 16:09:45.415  9839  9905 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 16:09:45.415  9839 10440 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 16:09:45.415  9839 10440 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 16:09:45.415  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 16:09:45.416  9839 10440 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 16:09:45.416  9839  9839 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-12 16:09:45.416  9839  9905 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73af78c removed from the list
10-12 16:09:45.416  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73af78c removed from the list
10-12 16:09:45.416  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 16:09:45.416  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 16:09:45.416  9839  9839 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 16:09:45.416  9839  9905 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 16:09:45.417  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.417  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
10-12 16:09:45.417  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 16:09:45.418  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.419  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:45.419  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.419  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 16:09:45.420  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:45.422  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:45.423  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:45.424  9969  9981 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
10-12 16:09:45.424  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,10-12 16:09:45.425  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 16:09:45.426  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:45.428  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:45.428  9839  9905 D BluetoothLeScanner: Stop Scan
,10-12 16:09:45.431  9969  9980 D BtGatt.GattService: stopScan() - queue size =1
10-12 16:09:45.431  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 16:09:45.431  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:45.431  9969  9980 D BtGatt.GattService: stopScan() - queue size =1
10-12 16:09:45.431  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_SCAN
10-12 16:09:45.432  3703  5217 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{cec9727: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
10-12 16:09:45.433  9969  9991 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 16:09:45.433  3703  5217 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160946, SetElapsed=236592, nowELAPSED=235636
,10-12 16:09:45.434  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 16:09:45.435  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.435  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 16:09:45.435  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:45.436  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.437  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.437  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-12 16:09:45.437  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-9,7,main], id: 123
,10-12 16:09:45.439  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:45.440  9839  9905 D BluetoothAdapter: STATE_ON
10-12 16:09:45.441  9839  9905 D BluetoothLeAdvertiser: stop advertising
,10-12 16:09:45.442  9969 10049 E BtGatt.ContextMap: Context not found for ID 6
10-12 16:09:45.442  9969 10008 D BtGatt.AdvertiseManager: message : 1
10-12 16:09:45.442  9969 10019 E BtGatt.GattService: [GSIM LOG]: gsimLogHandler: com.thaliproject.thalitest, msg: MESSAGE_STOP_ADV
10-12 16:09:45.443  9969 10008 D BtGatt.AdvertiseManager: stop advertise for client =  6
10-12 16:09:45.443  9969 10008 D BtGatt.AdvertiseManager: stop advertising, standardAdvClientIf = 0 client.clientIf = 6
10-12 16:09:45.443  3703  3920 D SamsungAlarmManager: setInexact Intent (T:2/F:8/AC:false) 20171012T160945 - CU:1002/CP:9969
,10-12 16:09:45.445  9969 10009 D BtGatt.ScanManager: filter size is 1
,10-12 16:09:45.445  9969 10008 D BtGatt.AdvertiseManager: logClientsSet() - status: -1
10-12 16:09:45.445  9969 10009 D BtGatt.ScanManager: delete FilterIndex - 7
,10-12 16:09:45.450  9969  9990 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
10-12 16:09:45.450  9969  9990 D BtGatt.GattService: Client app is not null!
,10-12 16:09:45.450  9839  9850 D BluetoothLeAdvertiser: onMultiAdvertiseCallback status = 0 isStart = false
,10-12 16:09:45.453  9969  9980 D BtGatt.GattService: unregisterClient() - clientIf=6
10-12 16:09:45.454  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 16:09:45.454  9969  9990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 16:09:45.455  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:45.455  9969 10009 D BtGatt.ScanManager: stopping BLe Batch
10-12 16:09:45.455  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.455  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-12 16:09:45.455  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.456  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.457  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.457  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 16:09:45.457  9839  9905 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-12 16:09:45.458  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-12 16:09:45.459  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.460  9969  9990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 16:09:45.460  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:45.461  9969 10009 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 16:09:45.462  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.462  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 16:09:45.462  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.463  9839  9905 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-9,7,main], id: 123
10-12 16:09:45.463  9839  9905 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd03ed5 removed from the list
10-12 16:09:45.463  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 16:09:45.463  9839  9905 D io.jxcore.node.ConnectivityMonitor: stop
10-12 16:09:45.463  9839  9905 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 16:09:45.463  9839  9839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 16:09:45.463  9839  9905 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
10-12 16:09:45.464  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:45.464  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:45.464  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 16:09:45.464  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
10-12 16:09:45.465  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:45.465  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
10-12 16:09:45.465  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
10-12 16:09:45.466  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-12 16:09:45.466  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 16:09:45.466  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:45.466  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-12 16:09:45.466  9969  9990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 16:09:45.466  9969  9990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 16:09:45.466  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 16:09:45.467  9839  9839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
10-12 16:09:45.467  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-12 16:09:45.467  9839  9905 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 16:09:45.467  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-12 16:09:45.467  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 16:09:45.467  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 16:09:45.467  9839  9839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-12 16:09:45.468  9839  9839 D org.thaliproject.p2p.btconnectorlib.inte,rnal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-12 16:09:45.468  9839  9839 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 16:09:45.469  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
10-12 16:09:45.469  3703 10073 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{5f46dd4: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
10-12 16:09:45.471  3703  3922 D SamsungAlarmManager: Cancel Alarm calling from uid:1002 pid :9969 / op:PendingIntent{8818b7d: PendingIntentRecord{3754826 com.android.bluetooth broadcastIntent}}
10-12 16:09:45.471  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
10-12 16:09:45.472  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
10-12 16:09:45.474  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
10-12 16:09:45.475  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
10-12 16:09:45.478  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
,10-12 16:09:45.479  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,10-12 16:09:45.481  9839  9905 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-12 16:09:45.730  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:45.730  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -55
,10-12 16:09:45.970  9839  9839 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 16:09:46.163  3703 10445 D WifiMHD::s: req(2):1, 7, 1
,10-12 16:09:46.167  3703 10445 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:09:46.168  3703 10445 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
10-12 16:09:46.170  3298  3787 D EnterpriseController: netId is 0
,10-12 16:09:46.170  3298  3787 D Netd    : getNetworkForDns: using netid 503 for uid 1000
10-12 16:09:46.171  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-12 16:09:46.283  3703  3724 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:09:46.389  3703  3864 D SamsungAlarmManager: Expired : 4
10-12 16:09:46.390  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T160947, SetElapsed=237699, nowELAPSED=236593
,10-12 16:09:46.390  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@40bba3f alarm=Alarm{e017ec3 type 2 when 236592 android}
,10-12 16:09:46.394  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 16000: mInRange : true
,10-12 16:09:46.402  3703  3928 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161002 - CU:1000/CP:3703
,10-12 16:09:46.670  4069  4069 D ShortcutManager: onReceive : android.intent.action.PACKAGE_CHANGED
,10-12 16:09:46.701  3703  3884 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-12 16:09:46.711  4769  4769 D RegisteredServicesCache: invalidateCache
10-12 16:09:46.726  4769  4769 D ApduServiceInfo: seId: 0
,10-12 16:09:46.731  4769  4769 D ApduServiceInfo: seId: 0
10-12 16:09:46.731  4769  4769 D RegisteredOthersCache: start invalidate
10-12 16:09:46.731  4769  4769 D RegisteredOthersCache: update valid otherService: ComponentInfo{com.google.android.apps.walletnfcrel/com.google.commerce.tapandpay.android.hce.service.ValuableApduService} AIDs: [4F53452E5641532E3031, A000000476D0000101, A000000476D0000111]
10-12 16:09:46.731  4769  4769 D RegisteredOthersCache: Existed other serivcee
10-12 16:09:46.731  4769  4769 D RegisteredPoliciesCache: invalidate
10-12 16:09:46.731  4769  4769 D RegisteredAidCache: onServicePolicyUpdated
10-12 16:09:46.731  4769  4769 D RegisteredAidCache: generateAidPolicyMapLocked
10-12 16:09:46.731  4769  4769 D AidPolicyManager: print policy
10-12 16:09:46.731  4769  4769 D AidPolicyManager: table size : 0
10-12 16:09:46.733  3703  4543 W ActivityManager: Permission Denial: Accessing service ComponentInfo{com.google.android.music/com.google.android.music.dial.DialMediaRouteProviderService} from pid=5105, uid=10124 that is not exported from uid 10122
,10-12 16:09:46.739  3703  3820 D PackageManager: com.google.android.gms.permission.CAR_FUEL is a new runtime permission
,10-12 16:09:46.739  3703  3820 D PackageManager: com.google.android.gms.permission.CAR_MILEAGE is a new runtime permission
10-12 16:09:46.739  3703  3820 D PackageManager: com.google.android.gms.permission.CAR_SPEED is a new runtime permission
10-12 16:09:46.739  3703  3820 D PackageManager: com.google.android.gms.permission.CAR_VENDOR_EXTENSION is a new runtime permission
10-12 16:09:46.739  3703  3820 D PackageManager: Permission Group is null for permission com.sec.smartcard.permission.SMARTCARD_ADAPTER
10-12 16:09:46.739  3703  3820 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_READ
10-12 16:09:46.740  3703  3820 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_WRITE
10-12 16:09:46.740  3703  3820 D ApplicationPolicy: groups[android.permission-group.SMS, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.LOCATION, android.permission-group.MESSAGES, android.permission-group.SMS, android.permission-group.SENSORS, android.permission-group.LOCATION, android.permission-group.SMS, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.MESSAGES, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.SMS, android.permission-group.PHONE, android.permission-group.CONTACTS, android.permission-group.CAMERA, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.SMS, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, android.permission-group.CONTACTS, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.STORAGE, com.samsung.android.memo.EXTRA_READ, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.MICROPHONE, android.permission-group.CONTACTS, com.samsung.android.memo.EXTRA_WRITE, android.permission-group.PHONE]
10-12 16:09:46.740  3703  3820 D ApplicationPolicy: Permission GRoups [android.permission-group.CONTACTS, android.permission-group.CALENDAR, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.MICROPHONE, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, com.samsung.android.memo.EXTRA_READ, com.samsung.android.memo.EXTRA_WRITE]
,10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.747  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidPolicyManager: There are not service policy for this aid
10-12 16:09:46.748  4769  4769 D AidRoutingManager: Override power table is not changed
,10-12 16:09:46.750  4042  4042 D CarrierSvcBindHelper: No carrier app for: 0
,10-12 16:09:46.753  4769  4769 D RegisteredNfcFServicesCache: Service unchanged, not updating
,10-12 16:09:46.759  4769  4769 D RegisteredComponentCache: Collect Tech packages for Knox
,10-12 16:09:46.818  3703  3820 D PackageManager: com.google.android.gms.permission.CAR_FUEL is a new runtime permission
10-12 16:09:46.818  3703  3820 D PackageManager: com.google.android.gms.permission.CAR_MILEAGE is a new runtime permission
10-12 16:09:46.818  3703  3820 D PackageManager: com.google.android.gms.permission.CAR_SPEED is a new runtime permission
10-12 16:09:46.818  3703  3820 D PackageManager: com.google.android.gms.permission.CAR_VENDOR_EXTENSION is a new runtime permission
10-12 16:09:46.818  3703  3820 D PackageManager: Permission Group is null for permission com.sec.smartcard.permission.SMARTCARD_ADAPTER
10-12 16:09:46.818  3703  3820 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_READ
,10-12 16:09:46.818  3703  3820 D PackageManager: Permission Group is null for permission com.samsung.android.memo.EXTRA_WRITE
10-12 16:09:46.818  3703  3820 D ApplicationPolicy: groups[android.permission-group.SMS, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.LOCATION, android.permission-group.MESSAGES, android.permission-group.SMS, android.permission-group.SENSORS, android.permission-group.LOCATION, android.permission-group.SMS, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.MESSAGES, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.SMS, android.permission-group.PHONE, android.permission-group.CONTACTS, android.permission-group.CAMERA, android.permission-group.CALENDAR, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.PHONE, android.permission-group.SMS, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, android.permission-group.CONTACTS, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.STORAGE, com.samsung.android.memo.EXTRA_READ, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, android.permission-group.MICROPHONE, android.permission-group.CONTACTS, com.samsung.android.memo.EXTRA_WRITE, android.permission-group.PHONE]
10-12 16:09:46.818  3703  3820 D ApplicationPolicy: Permission GRoups [android.permission-group.CONTACTS, android.permission-group.CALENDAR, android.permission-group.SMS, android.permission-group.STORAGE, android.permission-group.LOCATION, android.permission-group.PHONE, android.permission-group.MICROPHONE, android.permission-group.CAMERA, android.permission-group.SENSORS, android.permission-group.MESSAGES, com.google.android.gms.permission.CAR_INFORMATION, com.sec.smartcard.permission.SMARTCARD_ADAPTER, com.samsung.android.memo.EXTRA_READ, com.samsung.android.memo.EXTRA_WRITE]
,10-12 16:09:46.854  3703  3703 D UcmService: onReceive android.intent.action.PACKAGE_CHANGED
10-12 16:09:46.854  3703  3703 D UcmService: Package update in userId-0 and uid-10019
,10-12 16:09:46.854  3703  3703 D UcmService: isUCMPlugin pkgName-com.google.android.gms
10-12 16:09:46.855  3703  3703 D UcmService: enforcePermission : com.google.android.gms
10-12 16:09:46.855  3703  3703 D UcmService: isUCMPlugin pkgName-com.google.android.backuptransport
10-12 16:09:46.855  3703  3703 D UcmService: enforcePermission : com.google.android.backuptransport
10-12 16:09:46.855  3703  3703 D UcmService: isUCMPlugin pkgName-com.google.android.gsf
10-12 16:09:46.855  3703  3703 D UcmService: enforcePermission : com.google.android.gsf
10-12 16:09:46.855  3703  3703 D UcmService: isUCMPlugin pkgName-com.google.android.gsf.login
10-12 16:09:46.855  3703  3703 D UcmService: enforcePermission : com.google.android.gsf.login
10-12 16:09:46.855  3703  3703 D UcmService: isPCSCService pkgName-com.google.android.gms
10-12 16:09:46.855  3703  3703 D UcmService: isPCSCService pkgName-com.google.android.backuptransport
10-12 16:09:46.855  3703  3703 D UcmService: isPCSCService pkgName-com.google.android.gsf
10-12 16:09:46.855  3703  3703 D UcmService: isPCSCService pkgName-com.google.android.gsf.login
10-12 16:09:46.855  3703  3703 D UcmService: Updated app is not valid UCM plugin so ignoring refresh agent list....
,10-12 16:09:46.857  3703  3703 W PackageManager: STAHP USING HIDDEN APIS KTHX
,10-12 16:09:46.861  3703  3703 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x44000010 launchParam=MultiScreenLaunchParams { mDisplayId=0 mFlags=0 } bqHint=1 (has extras) }
10-12 16:09:46.861  3703  3703 I BackupManagerService: Package com.google.android.gms changed; rechecking
10-12 16:09:46.861  3703  3703 I BackupManagerService:    * com.google.android.gms.mdm.receivers.ConnectivityReceiver
10-12 16:09:46.861  3703  3703 I BackupManagerService: Checking need to rebind com.google.android.gms.backup.BackupTransportService
,10-12 16:09:46.863  4646  4646 D io_stats: !@   8,0 r 25879 2288808 w 5238 208648 d 709 74224 f 2086 2086 iot 11960 11076 th 474312 0 0 pt 0 inp 0 0 237.066
,10-12 16:09:46.943  3703  3764 W SearchableInfo: Invalid searchable metadata for com.samsung.android.themestore/.activity.WTSearchActivity: Search label must be a resource reference.
,10-12 16:09:46.965  3703  3764 I PrintManagerService: onPackageModified com.google.android.gms
10-12 16:09:46.965  3703  3764 I PrintManagerService:  - hadPrintService false
,10-12 16:09:46.966  3703  3764 I PrintManagerService:  - hasPrintService false
10-12 16:09:46.966  3703  3764 I RemotePrintSpooler: pruneApprovedPrintServices
10-12 16:09:46.966  3703  3764 I RemotePrintSpooler: [user: 0] bindLocked() 
,10-12 16:09:46.966  3703  3764 I RemotePrintSpooler: bindLocked binding service java.lang.Object@d6de884
10-12 16:09:46.967  3703  3764 D MountService: getExternalStorageMountMode : 1
10-12 16:09:46.967  3703  3764 D MountService: getExternalStorageMountMode : 3
10-12 16:09:46.967  3703  3764 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 10138, packageName : com.android.printspooler
,10-12 16:09:47.007 10448 10448 E Zygote  : v2
10-12 16:09:47.007 10448 10448 I libpersona: KNOX_SDCARD checking this for 10138
,10-12 16:09:47.007 10448 10448 I libpersona: KNOX_SDCARD not a persona
10-12 16:09:47.007  3703  3764 I ActivityManager: Start proc 10448:com.android.printspooler/u0a138 for service com.android.printspooler/.model.PrintSpoolerService
10-12 16:09:47.007  3703  3764 I RemotePrintSpooler: bindLocked waiting. remainingMillis: 8000
10-12 16:09:47.008 10448 10448 E Zygote  : accessInfo : 0
,10-12 16:09:47.015 10448 10448 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:09:47.017 10448 10448 I SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.printspooler 
,10-12 16:09:47.053 10448 10448 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:09:47.055 10448 10448 D ActivityThread: Added TimaKeyStore provider
,10-12 16:09:47.060  3703  4871 I ActivityManager: DSS on for com.android.printspooler and scale is 1.0
,10-12 16:09:47.115 10448 10448 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:09:47.128 10448 10448 D PrintSpoolerService: No existing print spooler state.
,10-12 16:09:47.132  3703  3703 I RemotePrintSpooler: onServiceConnected
10-12 16:09:47.133  3703  3764 I RemotePrintSpooler: [user: 0] pruneApprovedPrintServices()
,10-12 16:09:47.148  4733  4733 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,10-12 16:09:47.164  3703 10073 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
,10-12 16:09:47.165  3703 10073 D SecContentProvider: called from com.google.uid.shared:10019
,10-12 16:09:47.180  3703  5217 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{a3025ee: PendingIntentRecord{df242f4 com.google.android.gms broadcastIntent}}
,10-12 16:09:47.182  3703  4543 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{622da8f: PendingIntentRecord{ee85492 com.google.android.gms broadcastIntent}}
,10-12 16:09:47.183  3703  3764 D LocationProviderProxy: applying state to connected service
10-12 16:09:47.184  4919  4919 D Launcher.Model: onPackageChanged:com.google.android.gms user:UserHandle{0}
,10-12 16:09:47.194  3703  3920 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{508d11c: PendingIntentRecord{c6a9a60 com.google.android.gms broadcastIntent}}
10-12 16:09:47.194  4919  4919 D Launcher.Model: isValidStateInKnoxMode:false user:UserHandle{0}
10-12 16:09:47.195  4919  4919 E Launcher.Model: onPackageChanged :com.google.android.gms
10-12 16:09:47.195  4919  5014 D LauncherApps: getActivityList callingUid: 0 user: 0
10-12 16:09:47.196  3703  4542 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{c1fc125: PendingIntentRecord{d3327de com.google.android.gms broadcastIntent}}
,10-12 16:09:47.199  3703  4845 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{dfcb2fa: PendingIntentRecord{a4efc8c com.google.android.gms broadcastIntent}}
10-12 16:09:47.200  3703  4541 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{a7c90ab: PendingIntentRecord{ac5e3ea com.google.android.gms broadcastIntent}}
,10-12 16:09:47.201  4919  5014 D MenuAppLoader: There is no package to remove in mApps:com.google.android.gms
10-12 16:09:47.202  3703  4850 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{a5fe308: PendingIntentRecord{8355578 com.google.android.gms broadcastIntent}}
10-12 16:09:47.204  4919  5014 D LauncherApps: getActivityList callingUid: 0 user: 0
10-12 16:09:47.205  3703  3764 D LocationProviderProxy: applying state to connected service
,10-12 16:09:47.209  3703 10074 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{2304aa1: PendingIntentRecord{d1654b6 com.google.android.gms broadcastIntent}}
10-12 16:09:47.210  3703  4871 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{ed304c6: PendingIntentRecord{8265124 com.google.android.gms broadcastIntent}}
10-12 16:09:47.210  4919  5014 D Launcher.MenuWidgetsLoader: packageChanged : com.google.android.gms
10-12 16:09:47.210  4919  4919 D Launcher.MenuWidgetsLoader: MenuWidgetLoade-loadMenuWidgets : false
10-12 16:09:47.212  3703  3941 D SamsungAlarmManager: Cancel Alarm calling from uid:10019 pid :4733 / op:PendingIntent{2718c87: PendingIntentRecord{92b0642 com.google.android.gms broadcastIntent}}
10-12 16:09:47.212  4919  4919 D MenuView: packageChanged:
10-12 16:09:47.212  4919  4919 D MenuView: packagesChanged:2
10-12 16:09:47.212  4919  4919 D MenuView: frag:null
10-12 16:09:47.212  4919  4919 D MenuView: frag:MenuAppsGridFragment{aaae338 #0 id=0x1020011 APPS}
,10-12 16:09:47.215  4919 10462 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-start : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@1f9bf52 , false
,10-12 16:09:47.285  4733  5080 W GCoreFlp: No location to return for getLastLocation()
,10-12 16:09:47.287  4733  5080 W GCoreFlp: No location to return for getLastLocation()
,10-12 16:09:47.302  4919  4919 D Launcher.MenuWidgetsLoader: MenuWidgetLoader-done : com.android.launcher2.MenuWidgetsLoader$LoadMenuWidgetsTask@1f9bf52 , update : false , size : 48
,10-12 16:09:47.487  9839  9905 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-12 16:09:47.496  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:09:47.497  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161002, SetElapsed=252600, nowELAPSED=237700
,10-12 16:09:47.498  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@42ef9c0 alarm=Alarm{b30b94c type 2 when 237699 android}
,10-12 16:09:47.498  3703  3956 E SupplicantWifiScannerImpl: Timed out waiting for scan result from supplicant
,10-12 16:09:47.506 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,10-12 16:09:47.507 10259 10259 I wpa_supplicant: P2P: Current p2p state = IDLE
,10-12 16:09:47.521  3703  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161002 - CU:1000/CP:3703
10-12 16:09:47.522  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161002, SetElapsed=252717, nowELAPSED=237725
,10-12 16:09:47.529 10259 10259 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-12 16:09:47.633  9839 10463 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 255, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:47.633  9839 10463 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:47.633  9839 10463 D io.jxcore.node.StreamCopyingThread:  id: 83
,10-12 16:09:47.641  9839  9844 I art     : Do partial code cache collection, code=19KB, data=29KB
10-12 16:09:47.642  9839  9844 I art     : After code cache collection, code=17KB, data=28KB
10-12 16:09:47.642  9839  9844 I art     : Increasing code cache capacity to 128KB
,10-12 16:09:48.378  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:48.394  9839 10463 W !!      : call onHalfStreamCopied
10-12 16:09:48.394  9839 10463 I testCopyDataAndClose: closing input stream
,10-12 16:09:48.752  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:48.752  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -53
,10-12 16:09:49.070  9839 10463 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 255, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:49.070  9839 10463 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:49.070  9839 10463 D io.jxcore.node.StreamCopyingThread:  id: 83
10-12 16:09:49.070  9839 10463 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:49.070  9839 10463 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:49.070  9839 10463 D io.jxcore.node.StreamCopyingThread:  id: 83
10-12 16:09:49.071  9839 10463 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 16:09:49.071  9839 10463 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 16:09:49.071  9839 10463 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 16:09:49.071  9839 10463 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 16:09:49.071  9839 10463 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 16:09:49.071  9839 10463 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 255, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:49.071  9839 10463 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:49.071  9839 10463 D io.jxcore.node.StreamCopyingThread:  id: 83 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 16:09:50.118  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:50.571  9839  9905 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-12 16:09:50.603  9839 10464 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 258, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:50.603  9839 10464 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:50.603  9839 10464 D io.jxcore.node.StreamCopyingThread:  id: 85
,10-12 16:09:51.381  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:09:51.383 10259 10259 I wpa_supplicant: nl80211: Received scan results (40 BSSes)
,10-12 16:09:51.383  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:09:51.383  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:09:51.390  3703  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@8fc3d95
,10-12 16:09:51.392  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161002, SetElapsed=252600, nowELAPSED=241596
,10-12 16:09:51.771  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:51.771  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:09:51.867  4646  4646 D io_stats: !@   8,0 r 25880 2288812 w 5242 208732 d 711 74232 f 2089 2089 iot 11980 11079 th 472724 0 0 pt 0 inp 0 0 242.069
,10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 258, thread name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread:  id: 85
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread:  id: 85
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 258, name: testCopyBigData thread). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:51.899  9839 10464 D io.jxcore.node.StreamCopyingThread:  id: 85 .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 16:09:52.010  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:52.022  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:52.032  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:52.039  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:52.049  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:52.139  3703  4845 I RemotePrintSpooler: [user: 0] unbindLocked()
,10-12 16:09:52.150  3703  4541 I ActivityManager: KPU : put [com.sec.android.app.shealth] : 21108 K
,10-12 16:09:52.150  3703  4541 I ActivityManager: Killing 9465:com.sec.android.app.shealth/u0a36 (adj 906): DHA:empty #33
,10-12 16:09:52.192  3703  4851 D ActivityManager: cleanUpApplicationRecord -- 9465
10-12 16:09:52.194  4769  4788 D ForegroundUtils: could not check pending caller
,10-12 16:09:52.196  3703  5698 D SSRM:f  : SIOP:: AP = 340, PST = 299 (W:6), CP = 247, CUR = -27, LCD = 57
,10-12 16:09:52.384  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:52.696  3703  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:906 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.sendBroadcastToContextFramework:364 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.parseAndSendData:409 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager.-wrap2:-1 com.samsung.android.server.wifi.bigdata.WifiBigDataLogManager$MainHandler.handleMessage:469 
,10-12 16:09:53.241  9839  9905 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 260, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread:  id: 86
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 260, thread name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread:  id: 86
,10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread:  id: 86
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 260, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:53.242  9839 10466 D io.jxcore.node.StreamCopyingThread:  id: 86 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-12 16:09:53.243  9839  9905 I StreamCopyingThreadTest: Starting test: testSetBufferSize
10-12 16:09:53.243  9839  9905 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-12 16:09:53.243  9839  9905 I StreamCopyingThreadTest: Starting test: testRunWithException
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 264, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread:  id: 89
,10-12 16:09:53.244  9839 10467 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 264, thread name: My test thread name): Test exception.
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 264, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 264, name: My test thread name). Connection data: Peer properties: [0:0:0:0:0:0].
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false.
10-12 16:09:53.244  9839 10467 D io.jxcore.node.StreamCopyingThread:  id: 89 .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-12 16:09:53.245  9839  9905 I jxcore-log: 2017-10-12 14:09:53 - DEBUG UnitTest_app: 'Running unit tests'
10-12 16:09:53.245  9839  9905 I jxcore-log: 
10-12 16:09:53.245  9839  9905 I jxcore-log: *Native tests were executed*
10-12 16:09:53.245  9839  9905 I jxcore-log: 
10-12 16:09:53.245  9839  9905 I jxcore-log: Total number of executed tests:  78
10-12 16:09:53.245  9839  9905 I jxcore-log: 
10-12 16:09:53.245  9839  9905 I jxcore-log: Number of passed tests:  76
10-12 16:09:53.245  9839  9905 I jxcore-log: 
10-12 16:09:53.245  9839  9905 I jxcore-log: Number of failed tests:  0
10-12 16:09:53.245  9839  9905 I jxcore-log: 
10-12 16:09:53.245  9839  9905 I jxcore-log: Number of ignored tests:  2
10-12 16:09:53.245  9839  9905 I jxcore-log: 
10-12 16:09:53.245  9839  9905 I jxcore-log: Total duration:  46799
10-12 16:09:53.245  9839  9905 I jxcore-log: 
10-12 16:09:53.246  9839  9905 I jxcore-log: 2017-10-12 14:09:53 - DEBUG UnitTest_app: 'My device name is: 'samsung-SM-G930F''
10-12 16:09:53.246  9839  9905 I jxcore-log: 
10-12 16:09:53.246  9839  9905 I jxcore-log: 2017-10-12 14:09:53 - WARN testUtils: 'myNameCallback not set!'
10-12 16:09:53.246  9839  9905 I jxcore-log: 
,10-12 16:09:54.731  9839  9905 I jxcore-log: 2017-10-12 14:09:54 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
10-12 16:09:54.731  9839  9905 I jxcore-log: 
,10-12 16:09:54.735  9839  9905 I jxcore-log: 2017-10-12 14:09:54 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-12 16:09:54.735  9839  9905 I jxcore-log: 
,10-12 16:09:54.744  9839  9905 I jxcore-log: 2017-10-12 14:09:54 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-12 16:09:54.744  9839  9905 I jxcore-log: 
,10-12 16:09:54.797  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:54.797  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:09:54.909  9839  9905 I jxcore-log: 2017-10-12 14:09:54 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-12 16:09:54.909  9839  9905 I jxcore-log: 
,10-12 16:09:54.938  9839  9905 I jxcore-log: 2017-10-12 14:09:54 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-12 16:09:54.938  9839  9905 I jxcore-log: 
,10-12 16:09:55.029  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-12 16:09:55.029  9839  9905 I jxcore-log: 
,10-12 16:09:55.062  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-12 16:09:55.062  9839  9905 I jxcore-log: 
,10-12 16:09:55.080  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-12 16:09:55.080  9839  9905 I jxcore-log: 
,10-12 16:09:55.084  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-12 16:09:55.084  9839  9905 I jxcore-log: 
,10-12 16:09:55.128  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
10-12 16:09:55.128  9839  9905 I jxcore-log: 
,10-12 16:09:55.131  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
10-12 16:09:55.131  9839  9905 I jxcore-log: 
,10-12 16:09:55.134  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-12 16:09:55.134  9839  9905 I jxcore-log: 
,10-12 16:09:55.138  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-12 16:09:55.138  9839  9905 I jxcore-log: 
,10-12 16:09:55.365  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-12 16:09:55.365  9839  9905 I jxcore-log: 
,10-12 16:09:55.370  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-12 16:09:55.370  9839  9905 I jxcore-log: 
,10-12 16:09:55.434  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testHttp.js'
10-12 16:09:55.434  9839  9905 I jxcore-log: 
,10-12 16:09:55.437  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-12 16:09:55.437  9839  9905 I jxcore-log: 
,10-12 16:09:55.455  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-12 16:09:55.455  9839  9905 I jxcore-log: 
,10-12 16:09:55.459  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-12 16:09:55.459  9839  9905 I jxcore-log: 
,10-12 16:09:55.491  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-12 16:09:55.491  9839  9905 I jxcore-log: 
,10-12 16:09:55.532  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-12 16:09:55.532  9839  9905 I jxcore-log: 
,10-12 16:09:55.566  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-12 16:09:55.566  9839  9905 I jxcore-log: 
,10-12 16:09:55.595  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-12 16:09:55.595  9839  9905 I jxcore-log: 
,10-12 16:09:55.604  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-12 16:09:55.604  9839  9905 I jxcore-log: 
,10-12 16:09:55.650  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-12 16:09:55.650  9839  9905 I jxcore-log: 
,10-12 16:09:55.680  9839  9905 I jxcore-log: 2017-10-12 14:09:55 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-12 16:09:55.680  9839  9905 I jxcore-log: 
,10-12 16:09:56.331  3703 10073 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:09:56.332  3703 10073 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4268, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:09:56.332  3703 10073 D BatteryService: online:4, current avg:-113, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:-239
10-12 16:09:56.332  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:09:56.338  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-12 16:09:56.338  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:09:56.341  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:09:56.344  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,10-12 16:09:56.345  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:09:56.352  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:09:56.356  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
10-12 16:09:56.356  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:09:56.359  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:09:56.369  9969  9969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-12 16:09:56.369  9969 10028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:09:56.381  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-12 16:09:56.381  9839  9905 I jxcore-log: 
,10-12 16:09:56.404  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-12 16:09:56.404  9839  9905 I jxcore-log: 
,10-12 16:09:56.409  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-12 16:09:56.409  9839  9905 I jxcore-log: 
,10-12 16:09:56.413  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-12 16:09:56.413  9839  9905 I jxcore-log: 
,10-12 16:09:56.429  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-12 16:09:56.429  9839  9905 I jxcore-log: 
,10-12 16:09:56.446  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-12 16:09:56.446  9839  9905 I jxcore-log: 
,10-12 16:09:56.459  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-12 16:09:56.459  9839  9905 I jxcore-log: 
,10-12 16:09:56.468  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-12 16:09:56.468  9839  9905 I jxcore-log: 
,10-12 16:09:56.475  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-12 16:09:56.475  9839  9905 I jxcore-log: 
,10-12 16:09:56.483  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-12 16:09:56.483  9839  9905 I jxcore-log: 
,10-12 16:09:56.498  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-12 16:09:56.498  9839  9905 I jxcore-log: 
,10-12 16:09:56.510  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-12 16:09:56.510  9839  9905 I jxcore-log: 
,10-12 16:09:56.516  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-12 16:09:56.516  9839  9905 I jxcore-log: 
,10-12 16:09:56.592  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-12 16:09:56.592  9839  9905 I jxcore-log: 
,10-12 16:09:56.668  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testLoader: 'loading file: /data/data/com.thaliproject.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
10-12 16:09:56.668  9839  9905 I jxcore-log: 
,10-12 16:09:56.681  9839  9905 D BluetoothAdapter: STATE_ON
,10-12 16:09:56.686  9839  9905 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-12 16:09:56.687  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO testUtils: 'BLE multiple advertisement supported'
10-12 16:09:56.687  9839  9905 I jxcore-log: 
,10-12 16:09:56.688  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-12 16:09:56.688  9839  9905 I jxcore-log: 
,10-12 16:09:56.696  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
10-12 16:09:56.696  9839  9905 I jxcore-log: 
10-12 16:09:56.696  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-12 16:09:56.696  9839  9905 I jxcore-log: 
,10-12 16:09:56.697  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
10-12 16:09:56.697  9839  9905 I jxcore-log: 
10-12 16:09:56.697  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-12 16:09:56.697  9839  9905 I jxcore-log: 
10-12 16:09:56.697  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
10-12 16:09:56.697  9839  9905 I jxcore-log: 
10-12 16:09:56.698  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-12 16:09:56.698  9839  9905 I jxcore-log: 
10-12 16:09:56.698  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
10-12 16:09:56.698  9839  9905 I jxcore-log: 
10-12 16:09:56.698  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-12 16:09:56.698  9839  9905 I jxcore-log: 
10-12 16:09:56.698  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare","bssidName":null,"ssidName":null}'
10-12 16:09:56.698  9839  9905 I jxcore-log: 
10-12 16:09:56.698  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-12 16:09:56.698  9839  9905 I jxcore-log: 
,10-12 16:09:56.699  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":null,"ssidName":null}'
10-12 16:09:56.699  9839  9905 I jxcore-log: 
10-12 16:09:56.699  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-12 16:09:56.699  9839  9905 I jxcore-log: 
10-12 16:09:56.699  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:85:e6:c2","ssidName":"NG700"}'
10-12 16:09:56.699  9839  9905 I jxcore-log: 
10-12 16:09:56.699  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-12 16:09:56.699  9839  9905 I jxcore-log: 
,10-12 16:09:56.708  9839  9839 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
10-12 16:09:56.708  9839  9839 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-12 16:09:56.731  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
10-12 16:09:56.731  9839  9905 I jxcore-log: 
,10-12 16:09:56.791  9839  9905 I jxcore-log: 2017-10-12 14:09:56 - DEBUG CoordinatedClient: 'connected to the test server'
10-12 16:09:56.791  9839  9905 I jxcore-log: 
,10-12 16:09:56.870  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5258 208860 d 711 74232 f 2091 2091 iot 11980 11085 th 466168 0 0 pt 0 inp 0 0 247.073
,10-12 16:09:57.828  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:09:57.828  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:09:58.665  3703  4180 I ActivityManager: KPU : put [com.sec.android.service.health] : 12616 K
10-12 16:09:58.665  3703  4180 I ActivityManager: Killing 9541:com.sec.android.service.health/u0a24 (adj 906): DHA:empty #33
,10-12 16:09:58.706  3703  4851 D ActivityManager: cleanUpApplicationRecord -- 9541
,10-12 16:09:58.708  4769  4782 D ForegroundUtils: could not check pending caller
,10-12 16:10:00.001  3703  3864 D SamsungAlarmManager: Expired : 8
10-12 16:10:00.002  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{2a6fa9b type 3 when 250204 android}
,10-12 16:10:00.011  3703  3703 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171012T161100 - CU:1000/CP:3703
,10-12 16:10:00.015  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
10-12 16:10:00.015  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-12 16:10:00.016  4069  4069 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-12 16:10:00.044  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#end
10-12 16:10:00.044  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-12 16:10:00.048  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-12 16:10:00.064  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:10:00.067  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:10:00.070  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
10-12 16:10:00.073  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:10:00.088  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:10:00.090  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:10:00.091  4069  4069 V hong    : mid yDiff = 438
10-12 16:10:00.092  4069  4069 V hong    : mid yDiff = 438
10-12 16:10:00.093  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-12 16:10:00.093  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-12 16:10:00.100  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:10:00.102  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:10:00.117  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:10:00.119  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:10:00.134  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-12 16:10:00.137  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-12 16:10:00.143  5082  5082 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-12 16:10:00.146  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-12 16:10:00.150  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-12 16:10:00.156  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-12 16:10:00.157  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,10-12 16:10:00.158  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
10-12 16:10:00.160  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-12 16:10:00.161  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-12 16:10:00.166  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-12 16:10:00.168  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB5FCA37F9ACC437DAB58E78E59D669ACFCF59FBEB17D47FC8E06EBA08060337CBED7F5B3A972788F211FFB2080C68857]}
,10-12 16:10:00.169  5082  5082 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-12 16:10:00.860  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:00.861  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:10:01.874  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5266 209004 d 712 74236 f 2093 2093 iot 11980 11088 th 468420 0 0 pt 0 inp 0 0 252.076
,10-12 16:10:02.217  3703  5698 D SSRM:f  : SIOP:: AP = 330, PST = 305 (W:6), CP = 258, CUR = 4, LCD = 57
,10-12 16:10:02.397  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:10:02.398  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T162136, SetElapsed=947168, nowELAPSED=252601
10-12 16:10:02.398  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171012T161100, SetElapsed=310204, nowELAPSED=252602
10-12 16:10:02.399  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@9149340 alarm=Alarm{561e38 type 2 when 252600 android}
,10-12 16:10:02.403  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 32000: mInRange : true
,10-12 16:10:02.407 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-12 16:10:02.407 10259 10259 I wpa_supplicant: P2P: Current p2p state = IDLE
10-12 16:10:02.414  3703  3928 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161034 - CU:1000/CP:3703
10-12 16:10:02.414  3703  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161034, SetElapsed=284610, nowELAPSED=252618
,10-12 16:10:02.420  3703  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161017 - CU:1000/CP:3703
10-12 16:10:02.421  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161017, SetElapsed=267618, nowELAPSED=252625
,10-12 16:10:02.424 10259 10259 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-12 16:10:03.291  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:10:03.293  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-12 16:10:03.294  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:10:03.295  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:10:03.884  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:03.885  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:05.320  3703  4450 E Watchdog: !@Sync 8 [12_paź_16_10_05.320]
,10-12 16:10:06.245  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:10:06.247 10259 10259 I wpa_supplicant: nl80211: Received scan results (39 BSSes)
,10-12 16:10:06.248  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:10:06.248  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:10:06.255  3703  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@4cc2b76
,10-12 16:10:06.258  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161034, SetElapsed=284610, nowELAPSED=256462
,10-12 16:10:06.375  3703  4851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:10:06.375  3703  4851 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:10:06.376  3703  4851 D BatteryService: online:4, current avg:64, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:192
10-12 16:10:06.376  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:10:06.380  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-12 16:10:06.380  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:10:06.382  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:10:06.384  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-12 16:10:06.384  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:10:06.387  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:10:06.389  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
10-12 16:10:06.390  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:10:06.405  9969  9969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-12 16:10:06.405  9969 10028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:10:06.415  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:10:06.624  3703  3716 I art     : Background partial concurrent mark sweep GC freed 224216(12MB) AllocSpace objects, 37(788KB) LOS objects, 27% free, 41MB/57MB, paused 2.205ms total 227.510ms
,10-12 16:10:06.773  4949  5001 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 3ms lastUpdatedAfter : 44331 ms mFlush_time_threasold : 2000 mCurrentSize : 229
,10-12 16:10:06.809  5172 10479 W IcingInternalCorpora: getNumBytesRead when not calculated.
,10-12 16:10:06.845  5172  5676 I Icing   : App usage reports: 1
10-12 16:10:06.848  5172  5676 I Icing   : Usage reports 1 indexed 0 rejected 0 imm upload false
,10-12 16:10:06.877  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5295 209308 d 714 74244 f 2101 2101 iot 11980 11095 th 468296 0 0 pt 0 inp 0 0 257.079
,10-12 16:10:06.904  5172  5676 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-12 16:10:06.905  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:06.905  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:06.949  5172  5676 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-12 16:10:06.981  5172  5676 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-12 16:10:07.022  5172  5676 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-12 16:10:07.057  5172  5676 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-12 16:10:07.086  5172  5676 I Icing   : Usage reports 0 indexed 0 rejected 0 imm upload false
,10-12 16:10:08.416  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-12 16:10:08.416  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-12 16:10:08.416  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({system=1, android.process.acore=1, com.google.android.gms=2})  ]
,10-12 16:10:09.933  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:09.934  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:10.789  4949  5001 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 1Kb duration : 5ms lastUpdatedAfter : 4015 ms mFlush_time_threasold : 2000 mCurrentSize : 525
,10-12 16:10:11.881  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5354 210020 d 723 74280 f 2116 2116 iot 12040 11121 th 469500 0 0 pt 0 inp 0 0 262.083
,10-12 16:10:12.244  3703  5698 D SSRM:f  : SIOP:: AP = 300, PST = 306 (W:14), CP = 254, CUR = 111, LCD = 57
,10-12 16:10:12.961  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:12.961  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -53
,10-12 16:10:13.681  3703  4016 D WifiWatchdogStateMachine:  [|211] []
,10-12 16:10:15.995  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:15.995  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:16.445  3703  4542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:10:16.887  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5356 210064 d 724 74284 f 2118 2118 iot 12040 11124 th 469680 0 0 pt 0 inp 0 0 267.089
,10-12 16:10:18.696  3703  4842 I ActivityManager: KPU : put [com.samsung.android.app.watchmanager:contentprovider] : 16204 K
10-12 16:10:18.697  3703  4842 I ActivityManager: Killing 9556:com.samsung.android.app.watchmanager:contentprovider/u0a18 (adj 906): DHA:empty #33
,10-12 16:10:18.741  3703  4541 D ActivityManager: cleanUpApplicationRecord -- 9556
,10-12 16:10:18.744  4769  4782 D ForegroundUtils: could not check pending caller
,10-12 16:10:19.029  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:19.029  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:21.892  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5364 210108 d 724 74284 f 2119 2119 iot 12040 11125 th 470852 0 0 pt 0 inp 0 0 272.094
,10-12 16:10:22.063  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:22.063  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:22.276  3703  5698 D SSRM:f  : SIOP:: AP = 290, PST = 302 (W:14), CP = 250, CUR = 143, LCD = 57
,10-12 16:10:25.090  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:25.091  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:26.514  3703  4543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:10:28.125  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:28.125  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:31.159  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:31.160  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:31.902  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5366 210124 d 724 74284 f 2121 2121 iot 12040 11126 th 473252 0 0 pt 0 inp 0 0 282.104
,10-12 16:10:32.334  3703  5698 D SSRM:f  : SIOP:: AP = 290, PST = 302 (W:14), CP = 246, CUR = 152, LCD = 57
,10-12 16:10:32.490  3703  3804 I PowerManagerService: [PWL] On : 0 (282693 ms ago)
10-12 16:10:32.490  3703  3804 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-12 16:10:33.296  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:10:33.298  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-12 16:10:33.299  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:10:33.300  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:10:34.187  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:34.187  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:34.407  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:10:34.408  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T162136, SetElapsed=947168, nowELAPSED=284611
10-12 16:10:34.408  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@9301e11 alarm=Alarm{ff7c08b type 2 when 284610 android}
,10-12 16:10:34.412  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 64000: mInRange : true
,10-12 16:10:34.416 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-12 16:10:34.416 10259 10259 I wpa_supplicant: P2P: Current p2p state = IDLE
10-12 16:10:34.422  3703  3928 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161138 - CU:1000/CP:3703
10-12 16:10:34.423  3703  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161138, SetElapsed=348616, nowELAPSED=284626
,10-12 16:10:34.430  3703  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161049 - CU:1000/CP:3703
10-12 16:10:34.430  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161049, SetElapsed=299622, nowELAPSED=284634
,10-12 16:10:34.434 10259 10259 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-12 16:10:35.322  3703  4450 E Watchdog: !@Sync 9 [12_paź_16_10_35.321]
,10-12 16:10:36.576  3703  5217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:10:36.908  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5367 210128 d 724 74284 f 2122 2122 iot 12040 11127 th 473224 0 0 pt 0 inp 0 0 287.110
,10-12 16:10:37.209  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:37.209  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:38.261  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:10:38.264 10259 10259 I wpa_supplicant: nl80211: Received scan results (37 BSSes)
10-12 16:10:38.265  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:10:38.265  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:10:38.271  3703  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@843ad81
,10-12 16:10:38.274  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161138, SetElapsed=348616, nowELAPSED=288478
,10-12 16:10:40.236  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:40.236  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:41.913  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5368 210140 d 724 74284 f 2123 2123 iot 12040 11128 th 474840 0 0 pt 0 inp 0 0 292.115
,10-12 16:10:42.359  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 302 (W:14), CP = 244, CUR = 150, LCD = 57
,10-12 16:10:43.270  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:43.271  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:46.305  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:46.305  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:10:46.645  3703 10074 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:10:46.919  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5369 210144 d 724 74284 f 2124 2124 iot 12040 11129 th 474908 0 0 pt 0 inp 0 0 297.121
,10-12 16:10:49.339  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:49.339  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:10:51.924  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5370 210156 d 724 74284 f 2125 2125 iot 12040 11130 th 474908 0 0 pt 0 inp 0 0 302.126
,10-12 16:10:52.396  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:52.396  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:10:52.401  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 297 (W:14), CP = 243, CUR = 147, LCD = 57
,10-12 16:10:55.427  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:55.427  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:10:56.706  3703  4851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:10:58.453  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:10:58.453  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:00.001  3703  3864 D SamsungAlarmManager: Expired : 8
,10-12 16:11:00.002  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{a459014 type 3 when 310204 android}
,10-12 16:11:00.011  3703  3703 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171012T161200 - CU:1000/CP:3703
,10-12 16:11:00.016  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
10-12 16:11:00.018  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-12 16:11:00.018  4069  4069 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-12 16:11:00.038  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#end
10-12 16:11:00.039  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-12 16:11:00.041  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-12 16:11:00.058  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:11:00.061  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:11:00.064  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:11:00.070  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:11:00.080  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:11:00.081  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
10-12 16:11:00.083  4069  4069 V hong    : mid yDiff = 438
10-12 16:11:00.083  4069  4069 V hong    : mid yDiff = 438
10-12 16:11:00.084  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-12 16:11:00.084  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
10-12 16:11:00.090  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:11:00.094  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:11:00.105  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:11:00.106  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:11:00.122  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-12 16:11:00.125  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-12 16:11:00.130  5082  5082 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-12 16:11:00.132  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-12 16:11:00.134  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-12 16:11:00.137  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-12 16:11:00.137  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
10-12 16:11:00.138  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
10-12 16:11:00.138  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,10-12 16:11:00.139  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-12 16:11:00.141  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-12 16:11:00.142  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB5FCA37F9ACC437DAB58E78E59D669AC98BD0BD89E1BD15ECEDC8B1411A73A6C9406C0F72943D42D5E9ED04FBFBF1386AF34982BBA29DE77D4E051E0E2D1A3C6]}
10-12 16:11:00.142  5082  5082 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-12 16:11:01.486  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:01.486  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:01.934  4646  4646 D io_stats: !@   8,0 r 25884 2289084 w 5372 210172 d 724 74284 f 2127 2127 iot 12040 11131 th 474920 0 0 pt 0 inp 0 0 312.136
,10-12 16:11:02.428  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 294 (W:14), CP = 241, CUR = 143, LCD = 57
,10-12 16:11:02.548  3703  3878 I TLC_TIMA_PKM_initialize: initializing...
,10-12 16:11:02.549  3703  3878 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
10-12 16:11:02.549  3703  3878 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: root = 0, root_len = 1
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: device_id = 0x0
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: tlc_open() was called
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: Opening MobiCore device
10-12 16:11:02.549  3703  3878 I TZ: mc_tlc_communication: Allocating message buffer for TCI
,10-12 16:11:02.552  3703  3878 I TZ: mc_tlc_communication: Opening the session
,10-12 16:11:02.602  3703  3878 I TZ: mc_tlc_communication: tlc_open() succeeded
10-12 16:11:02.602  3703  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,10-12 16:11:02.614  3703  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,10-12 16:11:02.623  3703  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,10-12 16:11:02.631  3703  3878 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,10-12 16:11:02.662  3703  3878 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,10-12 16:11:03.300  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:11:03.302  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-12 16:11:03.303  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:11:03.304  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:11:04.514  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:04.514  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:05.324  3703  4450 E Watchdog: !@Sync 10 [12_paź_16_11_05.323]
,10-12 16:11:06.747  3703  4542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:11:06.767  3703  3878 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
10-12 16:11:06.767  3703  3878 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,10-12 16:11:06.940  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5373 210176 d 724 74284 f 2128 2128 iot 12060 11137 th 474832 0 0 pt 0 inp 0 0 317.142
,10-12 16:11:07.547  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:07.547  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:07.695  3703  4180 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20171012T183338 - CU:10007/CP:4783
,10-12 16:11:08.527  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-12 16:11:08.527  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-12 16:11:08.527  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-12 16:11:08.535  4949  5001 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 57746 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-12 16:11:10.580  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:10.580  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:11.945  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5378 210280 d 725 74288 f 2131 2131 iot 12060 11141 th 474808 0 0 pt 0 inp 0 0 322.147
,10-12 16:11:12.461  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 292 (W:14), CP = 241, CUR = 140, LCD = 57
,10-12 16:11:13.608  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:13.608  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:16.641  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:16.641  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:16.824  3703  3920 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
10-12 16:11:16.825  3703  3920 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:11:16.825  3703  3920 D BatteryService: online:4, current avg:138, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:138
,10-12 16:11:16.825  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:11:16.834  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-12 16:11:16.834  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:11:16.841  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:11:16.845  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-12 16:11:16.845  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:11:16.852  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:11:16.855  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:11:16.856  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:11:16.873  9969  9969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-12 16:11:16.874  9969 10028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:11:16.882  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:11:16.951  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5384 210340 d 726 74292 f 2134 2134 iot 12060 11144 th 474844 0 0 pt 0 inp 0 0 327.153
,10-12 16:11:19.667  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:19.667  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:19.935  3703  4016 D WifiWatchdogStateMachine:  [|213] []
,10-12 16:11:21.956  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5392 210388 d 726 74292 f 2135 2135 iot 12060 11145 th 474980 0 0 pt 0 inp 0 0 332.158
,10-12 16:11:22.490  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 291 (W:14), CP = 240, CUR = 83, LCD = 57
,10-12 16:11:22.690  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:22.690  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:25.712  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:25.712  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:27.501  3703  3804 I PowerManagerService: [PWL] On : 0 (337705 ms ago)
10-12 16:11:27.502  3703  3804 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-12 16:11:28.745  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:28.745  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:30.456  8750  8780 I PlayCommon: [748] com.google.android.play.a.g.e(932): Preparing logs for uploading
,10-12 16:11:30.462  8750  8780 W PlayCommon: [748] com.google.android.play.a.g.a(1239): No account for auth token provided
,10-12 16:11:30.463  8750  8780 I PlayCommon: [748] com.google.android.play.a.g.a(1035): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,10-12 16:11:30.470  8750  8780 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:11:30.471  8750  8780 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,10-12 16:11:30.477  3298  3787 D EnterpriseController: netId is 0
,10-12 16:11:30.477  3298  3787 D Netd    : getNetworkForDns: using netid 503 for uid 10032
10-12 16:11:30.477  3298  3787 D DnsProxyListener: DNSDBG::dns addrinfo af 0
,10-12 16:11:30.767  8750  8780 I PlayCommon: [748] com.google.android.play.a.g.a(1113): Successfully uploaded logs.
,10-12 16:11:31.778  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:31.779  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:31.966  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5394 210396 d 726 74292 f 2135 2135 iot 12060 11146 th 474980 0 0 pt 0 inp 0 0 342.168
,10-12 16:11:32.519  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 290 (W:14), CP = 239, CUR = 33, LCD = 57
,10-12 16:11:33.308  3703  3703 D UsbMonitorService: readUsbState++
10-12 16:11:33.309  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-12 16:11:33.311  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:11:33.311  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:11:34.805  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:34.806  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:35.325  3703  4450 E Watchdog: !@Sync 11 [12_paź_16_11_35.325]
,10-12 16:11:36.971  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5395 210448 d 728 74300 f 2136 2136 iot 12060 11147 th 474984 0 0 pt 0 inp 0 0 347.173
,10-12 16:11:37.839  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:37.839  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:38.413  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:11:38.413  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T162136, SetElapsed=947168, nowELAPSED=348617
10-12 16:11:38.418  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171012T161200, SetElapsed=370203, nowELAPSED=348617
10-12 16:11:38.419  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@fa98568 alarm=Alarm{ff59980 type 2 when 348616 android}
,10-12 16:11:38.429  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
,10-12 16:11:38.433 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,10-12 16:11:38.433 10259 10259 I wpa_supplicant: P2P: Current p2p state = IDLE
,10-12 16:11:38.442  3703  3928 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161346 - CU:1000/CP:3703
10-12 16:11:38.443  3703  3928 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161346, SetElapsed=476633, nowELAPSED=348646
,10-12 16:11:38.447  3703  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161153 - CU:1000/CP:3703
10-12 16:11:38.447  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161153, SetElapsed=363639, nowELAPSED=348651
,10-12 16:11:38.449 10259 10259 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-12 16:11:40.862  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:40.862  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:11:42.281  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:11:42.283 10259 10259 I wpa_supplicant: nl80211: Received scan results (35 BSSes)
,10-12 16:11:42.285  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:11:42.285  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:11:42.290  3703  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@ef0bfe
10-12 16:11:42.293  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161442, SetElapsed=533167, nowELAPSED=352496
,10-12 16:11:42.550  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 288 (W:14), CP = 239, CUR = 13, LCD = 57
,10-12 16:11:43.897  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:43.897  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:46.878  3703 10073 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:11:46.879  3703 10073 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:11:46.880  3703 10073 D BatteryService: online:4, current avg:9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
10-12 16:11:46.880  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:11:46.892  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,10-12 16:11:46.892  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:11:46.896  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:11:46.907  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,10-12 16:11:46.907  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:11:46.920  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:11:46.935  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:11:46.936  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:11:46.940  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:46.940  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:46.954  9969  9969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-12 16:11:46.954  9969 10028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:11:46.957  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:11:46.979  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5405 210508 d 728 74300 f 2138 2138 iot 12060 11153 th 475040 0 0 pt 0 inp 0 0 357.182
,10-12 16:11:49.966  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:49.967  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:52.576  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 287 (W:14), CP = 238, CUR = 5, LCD = 57
,10-12 16:11:53.000  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:53.000  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:56.029  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:56.029  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:11:56.988  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5409 210532 d 728 74300 f 2139 2139 iot 12060 11154 th 475048 0 0 pt 0 inp 0 0 367.190
,10-12 16:11:59.061  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:11:59.062  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:00.000  3703  3864 D SamsungAlarmManager: Expired : 8
,10-12 16:12:00.001  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{7dc2a75 type 3 when 370203 android}
,10-12 16:12:00.011  3703  3703 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171012T161300 - CU:1000/CP:3703
10-12 16:12:00.012  3703  3703 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171012T161300, SetElapsed=430204, nowELAPSED=370215
,10-12 16:12:00.016  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
10-12 16:12:00.017  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-12 16:12:00.017  4069  4069 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-12 16:12:00.044  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#end
10-12 16:12:00.045  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-12 16:12:00.049  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-12 16:12:00.062  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:12:00.064  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:12:00.067  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
10-12 16:12:00.069  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:12:00.084  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:12:00.086  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:12:00.087  4069  4069 V hong    : mid yDiff = 438
10-12 16:12:00.087  4069  4069 V hong    : mid yDiff = 438
10-12 16:12:00.088  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-12 16:12:00.089  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-12 16:12:00.095  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:12:00.098  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:12:00.112  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:12:00.114  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:12:00.129  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-12 16:12:00.133  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-12 16:12:00.137  5082  5082 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
10-12 16:12:00.139  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-12 16:12:00.143  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-12 16:12:00.149  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-12 16:12:00.150  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,10-12 16:12:00.152  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-12 16:12:00.153  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-12 16:12:00.154  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-12 16:12:00.160  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-12 16:12:00.161  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB5FCA37F9ACC437DAB58E78E59D669AC2A5C34C35A7F46000D41ED5B78DAF8C7F8D05E1195B71C9D57EFF0C41D3CA7F49E44044E7CE288E0F7857938F2C684C8]}
,10-12 16:12:00.162  5082  5082 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-12 16:12:01.993  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5410 210536 d 728 74300 f 2139 2139 iot 12060 11155 th 474988 0 0 pt 0 inp 0 0 372.195
,10-12 16:12:02.083  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:02.083  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:02.607  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 285 (W:14), CP = 238, CUR = 2, LCD = 57
,10-12 16:12:03.312  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:12:03.314  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-12 16:12:03.315  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:12:03.315  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:12:05.114  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:05.114  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:05.327  3703  4450 E Watchdog: !@Sync 12 [12_paź_16_12_05.327]
,10-12 16:12:08.147  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:08.148  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:08.639  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-12 16:12:08.639  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-12 16:12:08.639  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-12 16:12:08.647  4949  5001 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60112 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-12 16:12:11.172  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:11.172  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:12:12.004  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5414 210628 d 729 74304 f 2141 2141 iot 12060 11158 th 475052 0 0 pt 0 inp 0 0 382.205
,10-12 16:12:12.635  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 284 (W:14), CP = 237, LCD = 57
,10-12 16:12:14.207  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:14.207  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:12:16.917  3298  3783 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-12 16:12:16.939  3703 10074 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:12:17.009  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5419 210684 d 730 74308 f 2143 2143 iot 12070 11161 th 475060 0 0 pt 0 inp 0 0 387.211
,10-12 16:12:17.241  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:17.242  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:12:18.829  3298  3783 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-12 16:12:20.269  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:20.270  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:12:22.014  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5426 210716 d 730 74308 f 2143 2143 iot 12070 11162 th 475000 0 0 pt 0 inp 0 0 392.216
,10-12 16:12:22.663  3703  5698 D SSRM:f  : SIOP:: AP = 280, PST = 282 (W:14), CP = 237, LCD = 57
,10-12 16:12:23.304  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:23.305  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:12:26.333  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:26.333  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:12:27.020  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5427 210728 d 730 74308 f 2144 2144 iot 12070 11163 th 475004 0 0 pt 0 inp 0 0 397.221
,10-12 16:12:27.527  3703  3804 I PowerManagerService: [PWL] On : 0 (397730 ms ago)
10-12 16:12:27.527  3703  3804 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-12 16:12:28.209  3703  4016 D WifiWatchdogStateMachine:  [|215] []
,10-12 16:12:29.368  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:29.368  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:12:32.402  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:32.402  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:32.691  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 280 (W:14), CP = 236, LCD = 57
,10-12 16:12:33.316  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:12:33.318  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-12 16:12:33.319  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:12:33.320  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:12:35.329  3703  4450 E Watchdog: !@Sync 13 [12_paź_16_12_35.328]
,10-12 16:12:35.430  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:35.430  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:38.464  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:38.464  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:41.493  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:41.493  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:42.720  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 279 (W:14), CP = 236, LCD = 57
,10-12 16:12:44.527  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:44.528  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:45.601  9722  9749 V NativeCrypto: SSL shutdown failed: ssl=0x7194cd3a80: I/O error during system call, Software caused connection abort
,10-12 16:12:46.998  3703  3922 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:12:46.999  3703  3922 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:12:46.999  3703  3922 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
10-12 16:12:47.000  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:12:47.009  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-12 16:12:47.010  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:12:47.013  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:12:47.019  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-12 16:12:47.020  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:12:47.028  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:12:47.033  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:12:47.034  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:12:47.039  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5429 210736 d 730 74308 f 2145 2145 iot 12070 11164 th 474948 0 0 pt 0 inp 0 0 417.241
,10-12 16:12:47.055  9969  9969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,10-12 16:12:47.056  9969 10028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:12:47.067  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:12:47.567  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-12 16:12:47.567  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:50.076  4733  9786 V NativeCrypto: SSL shutdown failed: ssl=0x717c97ec80: I/O error during system call, Software caused connection abort
,10-12 16:12:50.592  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:50.592  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:52.752  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 277 (W:14), CP = 236, LCD = 57
,10-12 16:12:53.625  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:53.625  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:56.653  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:56.653  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:12:57.049  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5430 210748 d 730 74308 f 2146 2146 iot 12070 11165 th 474888 0 0 pt 0 inp 0 0 427.251
,10-12 16:12:59.685  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:12:59.686  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:00.001  3703  3864 D SamsungAlarmManager: Expired : 8
10-12 16:13:00.002  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{9d1f8f1 type 3 when 430204 android}
,10-12 16:13:00.010  3703  3703 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171012T161400 - CU:1000/CP:3703
10-12 16:13:00.011  3703  3703 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171012T161400, SetElapsed=490204, nowELAPSED=430214
,10-12 16:13:00.015  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
10-12 16:13:00.016  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#start
,10-12 16:13:00.017  4069  4069 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-12 16:13:00.043  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#end
,10-12 16:13:00.044  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-12 16:13:00.047  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-12 16:13:00.064  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:13:00.068  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:13:00.073  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
10-12 16:13:00.078  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:13:00.100  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:13:00.102  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:13:00.103  4069  4069 V hong    : mid yDiff = 438
10-12 16:13:00.104  4069  4069 V hong    : mid yDiff = 438
,10-12 16:13:00.105  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
,10-12 16:13:00.105  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-12 16:13:00.111  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:13:00.115  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:13:00.127  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:13:00.128  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:13:00.140  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
,10-12 16:13:00.143  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-12 16:13:00.148  5082  5082 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
10-12 16:13:00.150  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-12 16:13:00.153  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-12 16:13:00.158  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-12 16:13:00.159  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
,10-12 16:13:00.160  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-12 16:13:00.162  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
,10-12 16:13:00.162  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
10-12 16:13:00.167  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-12 16:13:00.169  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB5FCA37F9ACC437DAB58E78E59D669ACABEA63F11E0816ABD258BC028CE21E777AAF68B0C1E1C31569E2C6C1641483D81D6DDD88EC0C663EAFB65A30714D8300]}
,10-12 16:13:00.169  5082  5082 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-12 16:13:02.719  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:02.719  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:02.784  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 277 (W:14), CP = 235, LCD = 57
,10-12 16:13:03.320  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:13:03.322  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-12 16:13:03.323  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:13:03.323  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:13:05.330  3703  4450 E Watchdog: !@Sync 14 [12_paź_16_13_05.330]
,10-12 16:13:05.744  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:05.744  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:08.726  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-12 16:13:08.726  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-12 16:13:08.726  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-12 16:13:08.735  4949  5001 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 7ms lastUpdatedAfter : 60087 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-12 16:13:08.771  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:08.771  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:11.795  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-12 16:13:11.795  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:12.064  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5435 210840 d 731 74312 f 2148 2148 iot 12090 11173 th 474640 0 0 pt 0 inp 0 0 442.266
,10-12 16:13:12.810  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 276 (W:14), CP = 235, LCD = 57
,10-12 16:13:13.917  3298  3783 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-12 16:13:14.830  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:14.830  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:16.971  3298  3783 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
,10-12 16:13:17.045  3703 10074 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:13:17.068  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5440 210896 d 732 74316 f 2150 2150 iot 12090 11175 th 474608 0 0 pt 0 inp 0 0 447.271
,10-12 16:13:17.867  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:17.867  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:20.893  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:20.894  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:22.073  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5447 210928 d 732 74316 f 2150 2150 iot 12090 11176 th 474596 0 0 pt 0 inp 0 0 452.275
,10-12 16:13:22.839  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 275 (W:14), CP = 235, LCD = 57
,10-12 16:13:23.927  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:23.927  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:24.760  9839  9905 I jxcore-log: 2017-10-12 14:13:24 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-12 16:13:24.760  9839  9905 I jxcore-log: 
,10-12 16:13:25.969  9839  9905 I jxcore-log: 2017-10-12 14:13:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:25.969  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:25.969  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:25.969  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:25.969  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:25.969  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:25.969  9839  9905 I jxcore-log: 
,10-12 16:13:25.973  9839  9905 I jxcore-log: 2017-10-12 14:13:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:25.973  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:25.973  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:25.973  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:25.973  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:25.973  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:25.973  9839  9905 I jxcore-log: 
,10-12 16:13:26.950  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:26.950  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:29.972  9839  9905 I jxcore-log: 2017-10-12 14:13:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:29.972  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:29.972  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:29.972  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:29.972  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:29.972  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:29.972  9839  9905 I jxcore-log: 
,10-12 16:13:29.976  9839  9905 I jxcore-log: 2017-10-12 14:13:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:29.976  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:29.976  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:29.976  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:29.976  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:29.976  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:29.976  9839  9905 I jxcore-log: 
,10-12 16:13:29.978  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:29.978  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:13:30.450  3703  4016 D WifiWatchdogStateMachine:  [|214] []
,10-12 16:13:32.084  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5449 210944 d 732 74316 f 2151 2151 iot 12090 11177 th 474568 0 0 pt 0 inp 0 0 462.286
,10-12 16:13:32.560  3703  3804 I PowerManagerService: [PWL] On : 0 (462763 ms ago)
10-12 16:13:32.560  3703  3804 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-12 16:13:32.867  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 275 (W:14), CP = 235, LCD = 57
,10-12 16:13:33.010  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:33.011  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:33.324  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:13:33.326  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
,10-12 16:13:33.327  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:13:33.327  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:13:35.332  3703  4450 E Watchdog: !@Sync 15 [12_paź_16_13_35.331]
,10-12 16:13:36.043  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:36.043  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:39.065  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-12 16:13:39.065  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:39.540  9839  9905 I jxcore-log: 2017-10-12 14:13:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:39.540  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:39.540  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:39.540  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:39.540  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:39.540  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:39.540  9839  9905 I jxcore-log: 
,10-12 16:13:39.547  9839  9905 I jxcore-log: 2017-10-12 14:13:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:39.547  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:39.547  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:39.547  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:39.547  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:39.547  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:39.547  9839  9905 I jxcore-log: 
,10-12 16:13:42.092  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:42.092  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:42.892  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 274 (W:14), CP = 234, LCD = 57
,10-12 16:13:45.125  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:45.125  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:47.101  3703  4845 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:13:47.102  3703  4845 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:13:47.102  3703  4845 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
10-12 16:13:47.103  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:13:47.114  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
,10-12 16:13:47.114  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:13:47.118  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:13:47.123  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-12 16:13:47.124  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:13:47.133  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:13:47.137  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
10-12 16:13:47.138  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
10-12 16:13:47.143  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:13:47.153  9969  9969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-12 16:13:47.153  9969 10028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:13:48.154  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:48.154  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:49.571  9839  9905 I jxcore-log: 2017-10-12 14:13:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:49.571  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:49.571  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:49.571  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:49.571  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:49.571  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:49.571  9839  9905 I jxcore-log: 
,10-12 16:13:49.575  9839  9905 I jxcore-log: 2017-10-12 14:13:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:49.575  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:49.575  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:49.575  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:49.575  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:49.575  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:49.575  9839  9905 I jxcore-log: 
,10-12 16:13:51.187  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:51.187  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:13:52.918  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 273 (W:14), CP = 234, LCD = 57
,10-12 16:13:54.219  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:54.220  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:13:55.035  3300  3300 I bootchecker: bootchecker wake up!!
,10-12 16:13:57.109  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5451 210960 d 732 74316 f 2153 2153 iot 12090 11178 th 474412 0 0 pt 0 inp 0 0 487.311
,10-12 16:13:57.249  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:13:57.249  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:13:59.611  9839  9905 I jxcore-log: 2017-10-12 14:13:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:59.611  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:59.611  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:59.611  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:59.611  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:59.611  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:59.611  9839  9905 I jxcore-log: 
,10-12 16:13:59.617  9839  9905 I jxcore-log: 2017-10-12 14:13:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:13:59.617  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:13:59.617  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:13:59.617  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:13:59.617  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:13:59.617  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:13:59.617  9839  9905 I jxcore-log: 
,10-12 16:14:00.001  3703  3864 D SamsungAlarmManager: Expired : 8
,10-12 16:14:00.002  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 action=android.intent.action.TIME_TICK alarm=Alarm{b7c332d type 3 when 490204 android}
,10-12 16:14:00.010  3703  3703 D SamsungAlarmManager: setExact Intent (T:3/F:1/AC:false) 20171012T161500 - CU:1000/CP:3703
,10-12 16:14:00.015  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
10-12 16:14:00.016  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#start
10-12 16:14:00.017  4069  4069 I KeyguardClockPage: refreshTime(): DefaultSingle2016 hometime:null locale:pl_PL hasBG?false, Roaming:false
,10-12 16:14:00.038  4069  4069 D KeyguardUpdateMonitor: handleTimeUpdate#end
,10-12 16:14:00.054  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : start
,10-12 16:14:00.059  4069  4069 D SystemUI_Clock: Clock received ACTION_TIME_TICK : end
,10-12 16:14:00.076  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:14:00.079  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:14:00.082  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
10-12 16:14:00.084  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:14:00.099  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:14:00.100  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:14:00.102  4069  4069 V hong    : mid yDiff = 438
10-12 16:14:00.102  4069  4069 V hong    : mid yDiff = 438
,10-12 16:14:00.103  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : start
10-12 16:14:00.103  4069  4069 D SystemUI_DateView: DateView received ACTION_TIME_TICK : end
,10-12 16:14:00.109  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:14:00.111  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:14:00.132  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : start
,10-12 16:14:00.134  4069  4069 D TextClock: TextClock received ACTION_TIME_TICK : end
,10-12 16:14:00.148  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : start
10-12 16:14:00.151  4069  4069 D DateTimeView: DateTimeView received ACTION_TIME_TICK : end
,10-12 16:14:00.156  5082  5082 D [WeatherWidget(1434)]  WeatherService: {[B73D43639EB27FAA34EF41A6129C1FA7EB7C69B2413A882B51D740D673E9232A546D20833562A945E90153AD6347B3D5D64657F32B2AA3FC1BFAEE665D8B0581]}
,10-12 16:14:00.158  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E0CFD4B9B94C7886DA9F9793DD8C1B4F2]}
,10-12 16:14:00.161  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B623A9033B6C82EC1F6350A42D68D2E0CC94B6985FBB6EC3E92BF375BC4CBB0183A926513A5FAFAD6FA35C0BB54CE136B6]}
,10-12 16:14:00.169  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B610546A4399DC4572377ED7BF91816E3A41F7006E553CA693BDB231FDB44F0D69842AE18F57A3F1D739D4E8FB5C5F1C090D73020DC058D6B28B47FB9E8D11FDD8]}
,10-12 16:14:00.171  5082  5082 D [WeatherWidget(1434)]  : {[236FFFA4FE6D378EDABD8749C406D4B6A035A088D794472CF8E9764473296DF8F467AE4C0961127855BAA2F94756B31597615C26E76CB1BB1BD34EA5A6184824F7EC8BCB8FB92471C227A05EB6A1FBD16E5062FEE4A21FC677B1C9EF7734CC38]}
10-12 16:14:00.172  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FE8CDC30408F1DA82A689965D33BAFA134B63421D06DA018DAF47A9A1E961B5E0C7F474060C79B5A274E9E5F38D4EE626E]}
,10-12 16:14:00.173  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E91EF92CC71A1D7C1EBAC80FCECAEDCC10D1060E503462115BAFB8C8862486FAC4DD36592CDD3163680318BA960D2344B46C348CAA02F2E7F8E672FCB39FB0DF1]}
10-12 16:14:00.174  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03EBE13DDB18748E8A058BC28CDE271348666B0E85047E17C2C9A5C50E10E415CD7]}
,10-12 16:14:00.180  5082  5082 D [WeatherWidget(1434)]  : {[3AE6950019B083611567B0F9442DB03E7A10C97B3D7B9E7ED3A9DA0DC4F27D29897E7E7610B2B67551703917D97DE2671B04590549B0C65DE72B2F22958C1A1E]}
,10-12 16:14:00.181  5082  5082 D [WeatherWidget(1434)]  : {[A1AF0F6A1A65A89C43D705938923D0FEAE7CBA118D77CBAEE371C39D5B3A5D2896DCAEA9F69E652337891F3DD0F99968B8A92A41339C651B4714AB1F37E2900CB5FCA37F9ACC437DAB58E78E59D669AC229D05FF94E28F84D50C8D7FCE0BDD0B4B1712AC306D5DAA4C8017B73F14BB89203E2EDFE07F1D05F5FD5053C674B66C]}
,10-12 16:14:00.182  5082  5082 D [WeatherWidget(1434)]  : {[CBE90F3EF23DAF7447FA950223C7E0849EC1C379F8C5CEFDE6152E98A1BB9160]}
,10-12 16:14:00.282  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:00.282  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:02.945  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 272 (W:14), CP = 234, LCD = 57
,10-12 16:14:03.310  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:03.310  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:03.329  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:14:03.330  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-12 16:14:03.332  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:14:03.332  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:14:05.333  3703  4450 E Watchdog: !@Sync 16 [12_paź_16_14_05.333]
,10-12 16:14:06.343  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:06.344  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:08.806  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([]) countryIso(PL) userId(0)  ]
10-12 16:14:08.806  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
10-12 16:14:08.806  4949  5001 D ContactsProvider_EventLog: contents_sample_state: [ actCnt({android.process.acore=1})  ]
,10-12 16:14:08.814  4949  5001 E ContactsProvider_EventLog: Flush buffer to file cnt : 1 size : 0Kb duration : 6ms lastUpdatedAfter : 60078 ms mFlush_time_threasold : 2000 mCurrentSize : 257
,10-12 16:14:09.379  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:09.379  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:09.643  9839  9905 I jxcore-log: 2017-10-12 14:14:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:14:09.643  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:14:09.643  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:14:09.643  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:14:09.643  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:14:09.643  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:14:09.643  9839  9905 I jxcore-log: 
,10-12 16:14:09.648  9839  9905 I jxcore-log: 2017-10-12 14:14:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:14:09.648  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:14:09.648  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:14:09.648  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:14:09.648  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:14:09.648  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:14:09.648  9839  9905 I jxcore-log: 
,10-12 16:14:12.124  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5456 211056 d 733 74320 f 2155 2155 iot 12090 11183 th 474168 0 0 pt 0 inp 0 0 502.326
,10-12 16:14:12.405  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
,10-12 16:14:12.405  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:12.973  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 272 (W:14), CP = 234, LCD = 57
,10-12 16:14:15.439  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:15.439  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:17.131  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5460 211108 d 734 74324 f 2156 2156 iot 12090 11184 th 474180 0 0 pt 0 inp 0 0 507.332
,10-12 16:14:17.155  3703  4543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:14:18.466  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:18.466  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:19.709  9839  9905 I jxcore-log: 2017-10-12 14:14:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:14:19.709  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:14:19.709  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:14:19.709  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:14:19.709  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:14:19.709  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:14:19.709  9839  9905 I jxcore-log: 
,10-12 16:14:19.713  9839  9905 I jxcore-log: 2017-10-12 14:14:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:14:19.713  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:14:19.713  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:14:19.713  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:14:19.713  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:14:19.713  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:14:19.713  9839  9905 I jxcore-log: 
,10-12 16:14:21.490  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:21.490  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:14:22.136  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5468 211144 d 734 74324 f 2157 2157 iot 12090 11185 th 474156 0 0 pt 0 inp 0 0 512.337
,10-12 16:14:23.000  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 271 (W:14), CP = 234, LCD = 57
,10-12 16:14:24.523  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:24.524  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:24.675  3703  3716 I art     : Background sticky concurrent mark sweep GC freed 226238(11MB) AllocSpace objects, 162(3MB) LOS objects, 26% free, 41MB/57MB, paused 4.275ms total 146.854ms
,10-12 16:14:27.142  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5469 211156 d 734 74324 f 2158 2158 iot 12090 11186 th 474468 0 0 pt 0 inp 0 0 517.344
,10-12 16:14:27.557  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:27.557  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:14:29.745  9839  9905 I jxcore-log: 2017-10-12 14:14:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:14:29.745  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:14:29.745  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:14:29.745  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:14:29.745  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:14:29.745  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:14:29.745  9839  9905 I jxcore-log: 
,10-12 16:14:29.748  9839  9905 I jxcore-log: 2017-10-12 14:14:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:14:29.748  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:14:29.748  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:14:29.748  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:14:29.748  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:14:29.748  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:14:29.748  9839  9905 I jxcore-log: 
,10-12 16:14:30.504 10259 10259 I wpa_supplicant: WPA: Group rekeying completed with F4.E6.C2 [GTK=CCMP]
,10-12 16:14:30.508  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:14:30.520  3703  3928 D SecContentProvider2: query(), uri = 20 selection = getPromptCredentialsEnabled
,10-12 16:14:30.534  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:14:30.547  9839  9839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 16:14:30.576  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:30.577  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:14:30.605 10259 10259 I wpa_supplicant: Interworking: Fetch ANQP after connect
,10-12 16:14:30.689  3703  4016 D WifiWatchdogStateMachine:  [|215] []
,10-12 16:14:32.147  4646  4646 D io_stats: !@   8,0 r 25894 2290044 w 5470 211160 d 734 74324 f 2158 2158 iot 12090 11187 th 475184 0 0 pt 0 inp 0 0 522.349
,10-12 16:14:33.026  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 270 (W:14), CP = 233, LCD = 57
,10-12 16:14:33.332  3703  3703 D UsbMonitorService: readUsbState++
,10-12 16:14:33.333  3703  3703 D UsbMonitorService: !@readUsbState 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
10-12 16:14:33.335  3703  3703 D UsbMonitorService: failed to write /efs/usb_hw_param/usb_hw_param.log , java.io.FileNotFoundException: /efs/usb_hw_param/usb_hw_param.log (No such file or directory)
10-12 16:14:33.335  3703  3703 D UsbMonitorService: Posting Message again
,10-12 16:14:33.604  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:33.604  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -51
,10-12 16:14:35.335  3703  4450 E Watchdog: !@Sync 17 [12_paź_16_14_35.335]
,10-12 16:14:36.639  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:36.639  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:39.661  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:39.661  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:39.780  9839  9905 I jxcore-log: 2017-10-12 14:14:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:14:39.780  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:14:39.780  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:14:39.780  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:14:39.780  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:14:39.780  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:14:39.780  9839  9905 I jxcore-log: 
,10-12 16:14:39.784  9839  9905 I jxcore-log: 2017-10-12 14:14:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-12 16:14:39.784  9839  9905 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-12 16:14:39.784  9839  9905 I jxcore-log: onError@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-12 16:14:39.784  9839  9905 I jxcore-log: emit@events.js:82:1
10-12 16:14:39.784  9839  9905 I jxcore-log: onerror@/data/data/com.thaliproject.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-12 16:14:39.784  9839  9905 I jxcore-log: emit@events.js:82:1''
10-12 16:14:39.784  9839  9905 I jxcore-log: 
,10-12 16:14:42.602  3703  3804 I PowerManagerService: [PWL] On : 0 (532805 ms ago)
10-12 16:14:42.602  3703  3804 I PowerManagerService: [PWL]  mStayOn: true  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 0  mUserActivitySummary: 0x4
,10-12 16:14:42.694  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:42.695  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:42.964  3703  3864 D SamsungAlarmManager: Expired : 4
,10-12 16:14:42.968  3703  3864 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20171012T164442 - CU:1000/CP:3703
,10-12 16:14:42.969  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T162136, SetElapsed=947168, nowELAPSED=533172
10-12 16:14:42.969  3703  3864 I SamsungAlarmManager: setLocked to kernel - T:3 / 20171012T161500, SetElapsed=550204, nowELAPSED=533173
10-12 16:14:42.970  3703  3864 V SamsungAlarmManager: Sending to uid : 1000 listener=android.app.AlarmManager$ListenerWrapper@9578bb9 alarm=Alarm{86262b0 type 2 when 476633 android}
,10-12 16:14:42.976  3703  3928 D WifiConnectivityManager: startPeriodicSingleScan  mPeriodicSingleScanInterval : 128000: mInRange : true
10-12 16:14:42.978  3703  3864 V SamsungAlarmManager: Sending to uid : 10019 action=null alarm=Alarm{15d529 type 0 when 1507817682963 com.google.android.gms}
,10-12 16:14:42.979 10259 10259 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
10-12 16:14:42.980 10259 10259 I wpa_supplicant: P2P: Current p2p state = IDLE
,10-12 16:14:42.995 10259 10259 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,10-12 16:14:43.002  3703  3956 D SamsungAlarmManager: setInexact Listener (T:2/F:8/AC:false) 20171012T161457 - CU:1000/CP:3703
,10-12 16:14:43.003  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T161457, SetElapsed=548188, nowELAPSED=533206
,10-12 16:14:43.048  3703  5698 D SSRM:f  : SIOP:: AP = 270, PST = 270 (W:14), CP = 233, LCD = 57
,10-12 16:14:43.094  5172 10506 I EventLogChimeraService: Aggregate from 1507815882698 (log), 1507815882698 (data)
,10-12 16:14:43.258  3703  4873 D MountService: getExternalStorageMountMode : 1
10-12 16:14:43.258  3703  4873 D MountService: getExternalStorageMountMode : 3
10-12 16:14:43.258  3703  4873 D MountService: getExternalStorageMountMode : final mountMode=1, uid : 1000, packageName : com.samsung.android.lool
,10-12 16:14:43.281 10510 10510 E Zygote  : v2
10-12 16:14:43.281 10510 10510 I libpersona: KNOX_SDCARD checking this for 1000
10-12 16:14:43.281 10510 10510 I libpersona: KNOX_SDCARD not a persona
,10-12 16:14:43.283 10510 10510 E Zygote  : accessInfo : 0
10-12 16:14:43.283  3703  4873 I ActivityManager: Start proc 10510:com.samsung.android.lool/1000 for broadcast com.samsung.android.lool/com.samsung.android.sm.common.SmartManagerReceiver
,10-12 16:14:43.294 10510 10510 W SELinux : SELinux selinux_android_compute_policy_index : Policy Index[1],  Con:u:r:zygote:s0 SPD:SEPF_SECMOBILE_7.0_0006 RAM:SEPF_SECMOBILE_7.0_0005, [-1 -1 0 1 0 1]
,10-12 16:14:43.296 10510 10510 I SELinux : SELinux: seapp_context_lookup: seinfo=platform, pkgname=com.samsung.android.lool 
,10-12 16:14:43.324  3703  4872 D SamsungAlarmManager: setInexact Intent (T:0/F:0/AC:false) 20171012T164443 - CU:10019/CP:5172
,10-12 16:14:43.325 10510 10510 D TimaKeyStoreProvider: TimaSignature is unavailable
,10-12 16:14:43.326 10510 10510 D ActivityThread: Added TimaKeyStore provider
,10-12 16:14:43.328  3703  4845 I ActivityManager: DSS on for com.samsung.android.lool and scale is 1.0
,10-12 16:14:43.368 10510 10510 D ContextRelationMgrBrdg: loadKlass() : caller=com.samsung.android.bridge.multiscreen.common.ContextRelationManagerBridge.<clinit>:28 android.app.LoadedApk.makeApplication:840 
,10-12 16:14:43.435 10510 10510 D SamsungAnalytics:1.8.22: cf feature is supported
,10-12 16:14:43.442 10510 10510 D SamsungAnalytics:1.8.22: [Tracker] Tracker start:1.8.22
,10-12 16:14:45.732  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:45.733  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52
,10-12 16:14:46.856  3298  3784 D Netd    : Iface wlan0 link up
,10-12 16:14:46.860 10259 10259 I wpa_supplicant: nl80211: Received scan results (38 BSSes)
10-12 16:14:46.860  3703  3796 D Tethering: interfaceLinkStateChanged wlan0, true
10-12 16:14:46.860  3703  3796 D Tethering: interfaceStatusChanged wlan0, true
,10-12 16:14:46.866  3703  3956 D SamsungAlarmManager: Cancel Alarm calling from uid:1000 pid :3703 / listener:android.app.AlarmManager$ListenerWrapper@6f470ae
,10-12 16:14:46.869  3703  3956 I SamsungAlarmManager: setLocked to kernel - T:2 / 20171012T162136, SetElapsed=947168, nowELAPSED=537072
,10-12 16:14:47.162  4646  4646 D io_stats: !@   8,0 r 25898 2290328 w 5476 211328 d 735 74328 f 2162 2162 iot 12120 11194 th 473340 0 0 pt 0 inp 0 0 537.364
,10-12 16:14:47.208  3703  4542 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,10-12 16:14:47.210  3703  4542 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303682, invalid charger:0, maxChargingCurrent:0, maxChargingVoltage:0, chargeCounter:0
10-12 16:14:47.210  3703  4542 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, misc_event:0, current_now:0
10-12 16:14:47.211  3703  3703 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,10-12 16:14:47.221  3703  3703 V UiModeManager: updateLocked: null action, mDockState=0, category=null
10-12 16:14:47.221  3703  3703 D UiModeManager: updateConfigurationLocked: mDockState=0; mCarMode=false; mNightMode=1; uiMode=17
,10-12 16:14:47.226  3703  3703 D GameManagerService: new battery level: 100
,10-12 16:14:47.232  4069  4069 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
10-12 16:14:47.233  4069  4069 D KeyguardUpdateMonitor: handleBatteryUpdate
,10-12 16:14:47.242  4069  4069 D PowerUI : priorPlugType = 2 mPlugType =  2
,10-12 16:14:47.246  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
10-12 16:14:47.248  4069  4069 D BatteryMeterDrawable: isSomethingChanged - false
,10-12 16:14:47.252  4069  4069 D Tile.FlashlightTile: ACTION_BATTERY_CHANGED - Level :: 100, emEnabled :: false
,10-12 16:14:47.274  9969  9969 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
10-12 16:14:47.275  9969 10028 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,10-12 16:14:48.351  5172 10509 W PlatformStatsUtil: Could not retrieve Usage & Diagnostics setting. Giving up.
,10-12 16:14:48.759  3703  3928 D WifiStateMachine: Current network is: "NG700" , ID is: 4
10-12 16:14:48.759  3703  3928 D WifiStateMachine: 24GHz mQnsLowerRssiThreshold is recovered, currentRssi = -52

```
